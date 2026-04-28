# HoleFoodsAdaptiveAnalyticsSample
## Overview
Based on https://github.com/psteiwer/HoleFoodsAdaptiveAnalyticsSample - Converted into [SML](https://github.com/semanticdatalayer/SML).

HoleFoods Sample data (loaded into Intersystems IRIS) represented as SML for AtScale C2026.x.

### Configuration
Add https://github.com/coshiro/holefoods.git to your AtScale repos:

<img width="444" height="247" alt="image" src="https://github.com/user-attachments/assets/1426522b-801b-4515-b769-8183f7efb12d" />

As a public repo, the repo will show up in your Workspace:

<img width="382" height="483" alt="image" src="https://github.com/user-attachments/assets/77cf5304-b79f-4bf7-b27f-463bbeebd875" />

Ensure your Iris Datawarehouse is set up:
<img width="433" height="563" alt="image" src="https://github.com/user-attachments/assets/f7c8f8fa-6365-4824-a00f-6c8b261704ad" />

<img width="443" height="382" alt="image" src="https://github.com/user-attachments/assets/b474868c-7acf-49a7-95eb-d7241af67216" />

### SML 
If you follow the general connections as described in the [above repo](https://github.com/psteiwer/HoleFoodsAdaptiveAnalyticsSample), you should not have to change much.

Be sure, you have an AtScaleIRIS.yml in your connections folder. Ensure the AtScaleIRIS.yml has the right info matching your data warehouse setup:
<img width="273" height="206" alt="image" src="https://github.com/user-attachments/assets/f953ca45-3e6c-4d8e-a525-effb6cb0bd08" />
