# Installation

## Generals steps for Basis expert:

1. [Obtain and import the transport files for release `2020FPS01`](../inst/step-1.md)
2. [Activate Frontend ICF nodes](../inst/step-2.md) for node `ZGVR`
3. [Enable backend odata service](../inst/step-3.md) for service `ZNYPEGVR_SRV`
4. [Assign pfcg roles](../inst/step-4.md) for role `ZNYPE_GVR`
5. [Enter the activation key](../inst/step-5.md)
## "As-is" API installation steps for Basis expert

1. [Install As-is Main API on Central system](../../asis/SPS02/inst-cen.md)
2. [Install As-is Connector on each Managed system](../../asis/SPS02/inst-man.md)

## Products compatibility
    
| Main product | Main prod. release | Uses product | Compatible release  |
| -------------| ------- | ------------- | ------------------- |
| Gover        | FPS01   | ["As-is" Main API]({{ prod.gv.R2020FPS01.compatibleAsIsMainLink }})        | {{ prod.gv.R2020FPS01.compatibleAsIsMainRel }}               |
