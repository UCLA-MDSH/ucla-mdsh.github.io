---
#layout: frontpage
layout: page-fullwidth
show_meta: false
# title: "Upcoming Events"
# subheadline: "Layouts of Feeling Responsive"
header: no

callforaction:
 url: /apply/
 text: Apply Now ›
 style: alert

permalink: "/events_calendar/"
---

<!-- Require some minimum pixel widths, otherwise detect screen width and use 100% width, maintain aspect ratio -->
<!-- Calendar logo gets weird less than 415px -->
<!-- Get code to embed calendar by going to any calendar -> options -> settings and sharing -> Integrate calendar -> Customize -->
<!-- Then, remove the parts about height and width.  The below html code will set the height and width. -> Customize -->

<html>
<head>
    <style>
        .iframe-container {
            width: 100%;
            max-width: 100%;
            min-width: 415px; 
            position: relative;
            padding-bottom: 75%; 
            height: 0;

        }
        .iframe-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            min-height: 300px;
            border: 0;
        }
    </style>
</head>
<body>
    <div class="iframe-container">

<iframe src="https://calendar.google.com/calendar/embed?wkst=1&ctz=America%2FLos_Angeles&bgcolor=%23ffffff&showTitle=0&showPrint=0&src=Y185OTUyNmRlYjQyZGQxZWRkZTQzNzdiN2YzNDU5Zjc4MGRlMWUwZmY2OTEyMjBjYWY5ZTAzZWQ5NWM1NDA4NGMzQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=Y183NmY2N2RkNjMzYjA4OTkyZDNiMjBlY2ExMjUwZjJiODNmZDllNTJiZThjMGE4YWJjM2VhNmI3YjQwMDRkYzg4QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&src=Y19mODYwYTUxZDc5YmQwNjU4MzYyNWI5ZDQzZTJlZThiNmUxZjNiNTZkYmYzM2YzYWMzZDFiYmZjMTc4YmI5YmY4QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%234285F4&color=%23A79B8E&color=%23AD1457" style="border:solid 1px #777" frameborder="0" scrolling="no"></iframe>

    </div>
</body>
</html>

