# How to prepare the RFC destinations for Central system

On each Managed system you need to create an RFC destination pointing to your Central system.

Create RFC destination in your Managed system using transaction **sm59**. 

The user set in RFC destination should have type SYSTEM, and the following authorizations:

Authorization: S_RFC

ACTVT: 16

RFC_TYPE: FUGR

RFC_NAME: ZNYPEFACEN
