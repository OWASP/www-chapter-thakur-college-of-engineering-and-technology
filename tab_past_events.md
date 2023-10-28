title: Past Events
layout: null
tab: true
order: 1
tags: OWASP TCET
---

# Past Events

{% for event in events %}
## {{ event.title }}

**Date:** {{ event.date }}
**Location:** {{ event.location }}

**Event Overview:**  
{{ event.description }}

**Event Photos:**

[![Image 1]({{ event.image1 }})]({{ event.image1_link }})
[![Image 2]({{ event.image2 }})]({{ event.image2_link }})
[![Image 3]({{ event.image3 }})]({{ event.image3_link }})

**Event Videos:**

- [Watch Video 1]({{ event.video1_link }})
- [Watch Video 2]({{ event.video2_link }})
- [Watch Video 3]({{ event.video3_link }})

**Event Highlights:**  
{{ event.highlights }}
{% endfor %}


events:
  - title: Event 1
    date: [Event 1 Date]
    location: [Event 1 Location]
    description: [Event 1 description and highlights]
    image1: [event1_image1.jpg]
    image1_link: [event1_image1_link]
    image2: [event1_image2.jpg]
    image2_link: [event1_image2_link]
    image3: [event1_image3.jpg]
    image3_link: [event1_image3_link]
    video1_link: [event1_social_media_link_1]
    video2_link: [event1_social_media_link_2]
    video3_link: [event1_social_media_link_3]
    highlights: [Highlight any special moments or key takeaways from Event 1]

  - title: Event 2
    date: [Event 2 Date]
    location: [Event 2 Location]
    description: [Event 2 description and highlights]
    image1: [event2_image1.jpg]
    image1_link: [event2_image1_link]
    image2: [event2_image2.jpg]
    image2_link: [event2_image2_link]
    image3: [event2_image3.jpg]
    image3_link: [event2_image3_link]
    video1_link: [event2_social_media_link_1]
    video2_link: [event2_social_media_link_2]
    video3_link: [event2_social_media_link_3]
    highlights: [Highlight any special moments or key takeaways from Event 2]

