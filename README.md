# rhbd-sram-cell-and-6t-basic-sram-cell-design
Abstract

This work mainly focuses on studying the behaviour of different sram cells that have
been proposed and their advantages and disadvantages in comparison to one another.
A novel 14T sram cell design in a 45-nm cmos technology to protect the circuit from
the uncertain seu events is also proposed which is to be further studied and optimized
for low power dissipation.

Introduction

The 6T sram cell is the most basic structure which is generally used in the cache
memory. It is kind of a volatile memory because it is not able to retain its original
state when the power is switched off. But when we want this memory to work in
tough environment, lets say in aviation field or under the sea for the equipments of
submarines then 6T somehow comes out to be a big failure. The reason behind this is
when some particle trying to strike the drain of the pmos or nmos that is involved in
the circuit then it forcefully charges it which is leading to change the originally stored
state. So if the circuit is not protected then the false value will propagate during read
and write operations and hence leading to the failure of the circuit and so the
equipment. So in order to skip this unfortunate event various cell designs have been
proposed like 7T, 10T, 12T, 13T, 14T etc. This circuits have their own advantages
and disadvantages in terms of various parameters like power, area, noise margins and
most importantly the ability to protect the design from single event upsets.
