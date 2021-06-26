# Hierarchical Category

## Problem

Implement a system to provide a group of users access priviledges. The criteria of providing access to any
individual depends on characteritics the individual and group share.

    Example: someone may be working on process technology 1274, 1275
    So they will get access to all groups marked 1274 and/or 1275.

The implementation should be such, that in the future the system should be capable of adding any new characteristics
such as Blue-badge/CW as an added classification. At some later date someone may require to classify further adding
department: Etch, Polish, Litho, Defmet as another level of classification. The requirement on the data structure is thatl
it be able to handle any future classification expansion, without the developer having to add any extra code or changing
the implemented structure.

## Introduction
