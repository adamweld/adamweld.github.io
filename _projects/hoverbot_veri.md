---
title: 'Hoverbot Verification Boards'
subtitle: 'Quick-turn schematic and component verification boards'
date: 2018-06-30 00:00:00
description: 'Hoverbot Verification Boards: Quick-turn schematic and component verification boards'
featured_image: '/images/electronics/main.jpg'
category: 'electronics'
---

## Hoverbot Design Verification Boards

![](/images/electronics/main.jpg)

I put together these PCBs to verify my schematic design and component selection for the above flight controller project. The first larger board helped me spot a few serious issues with the schematic and footprint library, such as the WS2812B LEDs having reversed pin polarity in the Altium content vault library. I also had bringup difficulties with the analog video OSD chip, and ended up redesigning for better voltage filtering to that IC.

Overall, though, the majority of the design worked well without too much fuss.

![](/images/electronics/test_paste.jpg)

![](/images/electronics/test_place.jpg)

Here is another verification pcb, to confirm fixes to the OSD design:

![](/images/electronics/osd_test.jpg)

![](/images/electronics/osd_test_2.jpg)