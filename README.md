By: Michelle Kae Celine Jo-anne Bantugon<br>

Business Challenge built by [Professor Chase Kusterer](https://github.com/chase-kusterer)<br>
Hult International Business School<br>
Ernst & Young | NASA (2024 EY Open Science Data Challenge)<br>

<i>Note: This project was a collaboration with Ella Pesola, Italo Hidalgo, Jorge Solis, Karla Marie Banal , and Marcio Pineda in the context of a Business Challenge class with Professor Chase Kusterer at Hult International Business School.</i>

The 2024 challenge is focused on helping coastal communities become more resilient to the effects of climate change.

<b>How can data and AI be a lifeline for a vulnerable coastline?</b>

# Video Presentation
[Video Presentation](https://youtu.be/5YiImxXQS6o) <br>
# Introduction
Located in the northeastern Caribbean, Puerto Rico is part of the “hurricane belt.” The island’s location puts it directly in the path of tropical storms and hurricanes that form in the Atlantic Ocean. Hurricane Maria made landfall in Puerto Rico in September 2017, with sustained winds as high as 155 mph, which was barely below the Category 5 threshold. This natural event caused considerable damage to the island’s infrastructure. The entire island was affected by uprooted trees, power lines pulled down, and residential and commercial roofs being destroyed. (Scott, 2018).

In line with the above, we will analyze the Normalized Difference Vegetation Index (NDVI) to evaluate the health of vegetation pre and post storm. Moreover, the use deep learning model such as YOLO (You Only Look Once) for object detection and rapid analysis to assess infrastructure damage after hurricanes will be employed. This is crucial for efficient resource allocation and effective response in disasters’ immediate aftermath. The integration of these technologies ensures that responses are more targeted and that resources are optimally used, which is crucial for areas like Puerto Rico that are frequently in the path of hurricanes.

# Top Three Actionable Insights
<b>Housing Structure</b><br>
Housing structures in the Old San Juan, which is near the coastal line, are old century houses made of cobblestones or reinforced concrete with either flat roofs and or shingle roofings. The buildings were also erected near each other making them sturdier rather than stand-alone houses or buildings. While the most damaged areas by hurricane happened in rural areas where houses or buildings are more scattered, stand-alone and mostly made out of lightweight materials.

One way to lessen the effect of hurricanes on buildings, be it commercial or residential is by getting people to build more hurricane-proof buildings especially in the rural areas. Based on the outreach project initiated by the Federal Emergency Management Agency (FEMA) in conjunction with the Federal Alliance for Safe homes (FLASH), strong implementation of the use of materials based on ICC standards will surely make a lot of difference. The houses, especially the older homes must ensure roof coverings are high wind-rated and attached properly regardless of the type (tiles, shingles, or metal). It is also highly recommended to install permanently-mounted hurricane shutters, strengthen the roof deck connection, and strengthen roof-to-wall connections by installing hurricane clips or straps. Lastly install a secondary water barrier and improve the anchorage of attached structures.

<b>Integration of green and gray infrastructure (embankments/seawalls) with natural coastal habitats</b><br>

The pronounced change in NDVI in vegetation forests indicates heavy damage, highlighting the potential integration of natural coastal habitats such as mangrove forests, reefs, seagrass, or salt marshes into coastal defense strategies. These natural habitats can break tidal waves, reduce storm and erosion risks, and contribute to maintaining land as sea levels rise.

<b>Non-structural stabilization methods</b><br>

Given the increased vulnerability of coastal areas to infrastructure damage, implementing both structural and non-structural measures is crucial. Structural protection, such as coastal habitats, can mitigate damage. Additionally, non-structural methods like beach nourishment and dune restoration offer effective solutions. Beach nourishment involves adding sand or sediment that widens the beach, reducing storm damage, while dune restoration involves rebuilding dunes and planting native vegetation to stabilize them, trap sand, and enhance coastal habitat.

Another approach is living shorelines, which use vegetation such as oyster reefs, seagrasses, mangroves, and vegetated dunes. These features can calm waves, reduce wave energy, and stabilize the coastline.

# Conclusion
Our team labeled 60 images for both pre- and post-storm scenarios, achieving an mAP of around 0.50. Additionally, we leveraged Open Source Roboflow datasets, which use auto labeling, with the same images. We tried three different labeling approaches and concluded that manual labeling using polygons that outline the shape of the building without background elements yielded highest results compared to using fixed rectangles. Labeling commercial buildings is identifiable since we considered big parking spaces and flat roofings, while for residential buildings, it tends to appear smaller and with a ridge line in roofing.

Given more time, we could explore hybrid approaches of using polygons and fixed rectangles with overlapping, similar to how Roboflow labeled it. This is for further analysis, as our model performance improved after using open-source datasets from Roboflow.

Model results offer insights to NASA, Ernst and Young, and infrastructure sectors, enhancing disaster response using machine learning and deep learning with Sentinel-2 data, promoting resilient communities.
