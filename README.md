# Globalized Reference Views - GRVs &amp; Globalized Design Transfers - GDTs

> Two of the commonly known [Model View Definitions](https://technical.buildingsmart.org/standards/mvd/) (MVDs) that are officially approved by buildingSMART are the References View (RV) and Design Transfer View (DTV) (bSI, 2015b, bSI, 2015a). The RV is defined as a subset of the IFC4 schema that comprises a set of MVDs for reference workflows such as iterative design review and coordination in BIM projects. The RV can represent geometry and properties as read-only: that is, RV users can extract data from RVs, but cannot edit them. On the contrary, as an extension of the IFC4 RV, the IFC4 DTV supports handover workflows and allows editing, such as inserting, deleting, and modifying DTVs. Some use-cases of RV include background reference, coordination planning, clash detection, and visualization. Those of DTV include takeover or import data from a previous design. The scope of DTV is larger than that of RV; in other words, the RV is considered a subset of DTV. In addition, other MVDs, such as coordination view, structural analysis view, and basic FM handover view (East et al., 2013), are still in development. More model views being developed by other organizations can be found on the IFC Solution Factory website (buildingSMART, 2005).
>
> Reference: Kahyun Jeon & Ghang Lee, Information Delivery Manual (IDM) Configurator: Previous Efforts and Future Work


_Imagine you have a rare pot, for example, an old Chinese pot, which just few of them exist in the world, so how you check if those are original or fake?``_

_You compare them with the original one you have, if are the same you say they are original, otherwise are fake_


The proposed idea is so close to RVs and DTVs (DTs) but different! We have some “Globalized RVs and DTVs” as international references that represent:

**1. Globalized Reference Views - GRVs**

* [MaterialPass](https://github.com/IfcXtreme/MaterialPass)
* [ProductPass](https://github.com/IfcXtreme/ProductPass)
* [FacilityPass](https://github.com/IfcXtreme/FacilityPass)
* Other Globalized Reference Views


**2. Globalized Design Transfers - GDTs**

Also, Globalized Design Transfers as references which generated once globally and can be used multiple times in local projects

For instance, a globalized schedule document, or a globalized legal document which accepted as a reference for all countries as a base and can be developed/improved based on local needs

![An alternative scenario for IFC & ISO 19650](https://media.licdn.com/dms/image/C4D12AQEC4nl8xmHEwg/article-inline_image-shrink_1000_1488/0?e=1574294400&v=beta&t=rr2KNzn6TkmOQRDdx7YG5CcVg2huR9X18xuJO35AsFg)

And all the Globalized resources flattened as well as decoupled as “Models” and “Data/Information Templates/Psets” for multiple-use resources to generate GRVs and GDTs as you see in the aforementioned picture

**This will reduce costs and repetitions, and will increase trustworthy and accuracy and less legal issues in the projects**

All rights reserved - Ehsan Azari
