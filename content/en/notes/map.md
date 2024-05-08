---
title: "Cholera Death Map"
date: 2024-05-08T02:32:23-05:00
author: "Weifan Zhou"
slug:
draft: false
toc: false
---
<em>Note: this is the final assignment of Intro GIS class (ENST 200) at Illinois Wesleyan University, Spring 2024. The map was made in ArcMap (though it is going to retire after summer).</em>

---


---

#### Death Around Each Water Pump

| Water Pumps’ Location | Death within 300-feet<br><br>Radius Buffer |
| --- | --- |
| Ramillies PL | 0   |
| Great Marlborough Street | 26  |
| Warwick Street | 2   |
| Broadwick Street | 175 |
| Brewer Street | 23  |
| Sch & PW | 9   |
| Old Compton St / Shaftesbury Ave | 0   |
| Piccadilly A4 Coventry Street | 0   |

**Table 1:** _The table recorded death caused by cholera around each water pump (within 300-feet radius buffer). There are some buffers overlap. There are 8 water pumps: water pumps on Ramillies PL, Old Compton St (Shaftesbury Ave), and Piccadilly A4 (Coventry Street) are further away from Broadwick Street (at the map center), and they have zero deaths and lower prediction death. Broadwick Street has the highest number of death._

---

The Broad Street water pump WAS likely to be the cause of cholera outbreak. In the map, darker purple exists near Broad Street water pump, and as the distance gets further and further away from this pump, the light color (death prediction) it is. There are more red and orange dots, indicating more severe death, in the buffer around Broadwick Street. In the table, among all 300-feet radius buffers, Broadwick Street water pump has the highest number of death (175). Great Marlborough Street (26) and Brewer Street (23) has lower death, and they are closer to Broadwick Street water pump. Ramillies PL, Old Compton St / Shaftesbury Ave, and Piccadilly A4 Coventry Street has no death, and they are far away from Broadwick Street. To sum up, it seems that the closer those observation points to Broadwick Street, the higher number of cholera death there was. And thus, it seems that Broadwick Street water pump is the cause of cholera outbreak.