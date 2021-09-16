# Aimsity
Aimsity lets you visualize Aimsun Next traffic in Unity. Import simulated vehicle traffic from microsimulation vehicle trajectory tables (.csv) (table MIVEHDETAILEDTRAJECTORY). With Aimsity, you can create highly realistic animations, visualizations, and immersive experiences with your simulated traffic. Go to the [Aimsity page on the Unity Asset Store](https://assetstore.unity.com/packages/tools/integration/aimsity-195610) to learn more and get Aimsity.

# Technical Details
## Key Features:
- The Time Controller component allows you to speed up, slow down, pause, and reverse the simulation.
- The Traffic Manager component reads trajectory data from microsimulation vehicle trajectory tables (.csv) (table MIVEHDETAILEDTRAJECTORY), creates a traffic data file (.ba) in binary format, and facilitates the smooth animation of traffic in Play Mode.
- A Traffic Assets List is a data container that is assigned to a Traffic Manager component. It defines which prefabs the Traffic Manager should spawn for the Aimsun Next vehicle types in Play Mode.

## Setup:
LTS Unity versions are recommended for stability (2019.4.x or 2020.3.x). In a Unity project, import the Aimsity package. Navigate to **GameObject > Caelo Labs > Aimsity**. Alternatively, right-click in the Hierarchy and select **Caelo Labs > Aimsity**. A GameObject named Aimsity is created with a Quick Start Guide component attached. Two child GameObjects are additionally created, each with a correspondingly named component attached: (1) Time Controller and (2) Traffic Manager.

Aimsity takes advantage of custom inspectors wherever possible, which provide clear instructions every step of the way.

## Project Settings Requirements:
- API Compatibility Level .Net 4.x

## Support, Feedback, and Community:
We are eager to grow a community of users who will help drive Aimsity's development. If you need support, have feedback, or would like to engage with an active community of Aimsity users, join our Discord server. For details, see the last page of the documentation or the Quick Start Guide component.

## Disclaimer:
- Aimsity does not include source code.
- Aimsity does not include game ready assets (vehicles, traffic elements, etc.). The Prefabs folder contains traffic assets created with primitive GameObjects to demonstrate how vehicles and pedestrians should be set up to work with Aimsity. The Unity Asset Store has a large number of assets, some of which are free, that can be used in conjunction with Aimsity.
- Aimsity does not include a license for Aimsun Next.
- Aimsity does not offer a co-simulation feature with Aimsun Next.
- End user is responsible for ensuring that no license agreements are violated in their use of Aimsity.