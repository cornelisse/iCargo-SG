# Semantic Gateways - an introduction

## Cargo message structure

![SG-1](../images/Semantic%20Gateway%201%20(2013-04-17)

## Software components

A Semantic Gateway service contains two software components: the operational online service for conversion and an offline application to configuration.

![SG-in-0](../images/SG-in-0.png)

## Inbound process

![SG-in-1](../images/SG-in-1.png)

#### Online conversion service

The Semantic Gateway as designed in the iCargo project consists of two types of software modules: a Virtual Service Point (VSP) and a Convertor.
  
![SG-in-2](../images/SG-in-2.png)

A Virtual Service Point is able to check incoming requests, to validated if the originator of the request is known and authorised. If so, the Virtual Service Point will direct the incoming message to a specific convertor. Once the incoming request is processed, the result is forwarded by a Virtual Service Point to an Access Point.

The design looks symmetric but the reverse operation to convert entities into messages is functional different. Incoming messages need to be decomposed into smaller information elements while the reverse process requires a composition of a message out of smaller information elements. 
 
#### SG inbound 3

![SG-in-3](../images/SG-in-3.png)

#### SG inbound 4

![SG-in-4](../images/SG-in-4.png)

## The Semantic Gateway in reverse

#### SG outbound 0

![SG-out-0](../images/SG-out-0.png)

## Outbound process

#### SG outbound 1

![SG-out-1](../images/SG-out-1.png)

#### SG outbound 2

![SG-out-2](../images/SG-out-2.png)

#### SG outbound 3

![SG-out-3](../images/SG-out-3.png)

#### SG outbound 4

![SG-out-4](../images/SG-out-4.png)

## Offline configuration application



