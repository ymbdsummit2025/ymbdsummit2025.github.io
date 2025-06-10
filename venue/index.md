---
layout: page-with-toc
#title: Venue &amp; Transportation
title: Venue
headings: "intro,about_venue,getting-to,campus_navigation,accomodation,contact"
---

<h2 id="intro">Short Description</h2>

Venue: Patuakhali Science and Technology University (PSTU)<br>
Location: Dumki, Patuakhali, Bangladesh

<!-- <h2 class='space-bottom1' id='covid19'>Covid19 regulations</h2>

Currently, there are no Covid19 vaccination requirements in place for entering Italy. The use of masks remains mandatory on public transport and in healthcare facilities. Further information can be found on [salute.gov.it](https://www.salute.gov.it/portale/nuovocoronavirus/dettaglioNotizieNuovoCoronavirus.jsp?lingua=english&menu=notizie&p=dalministero&id=5893).

We highly recommend that everyone wear masks indoors during the conference. -->

<h2 id="about_venue">About the Venue</h2>

The YouthMappers Bangladesh Summit 2025 will be hosted at Patuakhali Science and Technology University (PSTU), a leading agricultural university in southern Bangladesh. Nestled in the coastal district of Patuakhali, PSTU’s serene 109.97 acres campus features modern facilities, lush greenery, and a commitment to sustainability.

<h3>Key Facilities:</h3>

- Auditorium: A 250+ capacity main hall for keynote sessions.
- Seminar Halls: 5 well-equipped halls (50+ capacity each) for workshops.
- Classrooms: 10+ air-conditioned rooms for breakout sessions.
- Accommodation: On-campus dormitories for 500+ participants (gender-segregated).
- Dining: Multiple canteens serving affordable local cuisine.
- Open Spaces: Gardens and courtyards ideal for networking and mapathons.
- Medical Support: 24/7 on-campus health center.


<h2 class='space-bottom1' id="getting-to">How to Get There</h2>

<h3>From Dhaka to PSTU (≈320 km):</h3>

By Road:

- Direct buses from Dhaka’s Sayedabad Terminal to Patuakhali (6–7 hours).
- From Patuakhali town, local transport (auto-rickshaws/buses) to PSTU (15 mins).

By Air + Road:

- Fly from Dhaka to Barisal Airport (50 mins).
- Take a local transport to Rupatoli Bus Terminal
- Take a bus to PSTU (2 hours).

By Waterway (Scenic Route):

- Launch/ferry from Dhaka to Patuakhali (overnight).


<h2 class='space-bottom1' id="campus_navigation">Campus Navigation:</h2>

- View the OSM Campus Map: PSTU on OpenStreetMap.
- Signage and volunteer guides will direct attendees.


<h2 id="accomodation">Accommodation</h2>
<h3>On-Campus (Priority for Attendees):</h3>

- Dormitories: Rooms (3–4 beds) with shared bathrooms.
  - Male: University Halls.
  - Female: Universeity Halls.
- Guest Rooms: Limited private rooms (early booking recommended).

<h3>Off-Campus (Patuakhali Town):</h3>

- Free shuttle buses will run between town and campus during the summit.


<h2 id="contact">Contact</h2>

For venue-related queries:

Local Coordinator: Md. Fardin Hasan

Email: es.fardinhasan@gmail.com

<!-- Phone: +8801712345678 (WhatsApp available) -->


<!-- Explore PSTU’s campus virtually:
[YouthMappers Bangladesh Summit 2025 Venue Wiki](https://wiki.openstreetmap.org/wiki/YouthMappers_Bangladesh_Summit_2025/Call_for_Venues/Patuakhali_Science_and_Technology_University_(PSTU)) -->

We look forward to welcoming you to Bangladesh’s vibrant coastal region! 🌏✨


<div id="map" style="height:420px; width:100%"></div>


<script>
  document.addEventListener('DOMContentLoaded', function() {
    var map = L.map('map').setView([22.46299, 90.36624], 14);
    L.control.scale().addTo(map);
    L.tileLayer('{{ site.map_tiles.url}}', {
      attribution: '{{ site.map_tiles.attribution }}',
      maxZoom: {{ site.map_tiles.maxZoom}}
    }).addTo(map);
    map.scrollWheelZoom.disable();
    L.marker([43.80054, 11.24501], {icon: L.icon({
      iconUrl: "{{ "/img/logo/ym_bd_summit_2025-logo.svg" | prepend: site.baseurl }}",
      iconSize: [40, 40],
      iconAnchor: [20, 40]
    })}).bindPopup("<h3>Patuakhali Science and Technology University</h3><p>Summit Venue. <a href='https://www.openstreetmap.org/?#map=14/22.46299/90.36624' target='_blank'>Open location on osm.org</a>.</p>").addTo(map);
  }, false);
</script>
