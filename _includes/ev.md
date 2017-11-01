
__When__ : {{include.page.ev_when}} 

__Ends At__ : {{include.page.ev_end}} 

__Where__ : [{{include.page.ev_where}}](//uw.edu/maps/?{{include.page.ev_building}})

[Add to Google Calendar](https://www.google.com/calendar/render?action=TEMPLATE&text=Audiophile+{{include.page.title | url_encode }}&dates={{include.page.ev_when | date: "%Y%m%dT" }}{{include.page.ev_when | date: "%H" | plus: 8 }}{{include.page.ev_when | date: "%M00Z" }}/{{include.page.ev_end | date: "%Y%m%dT" }}{{include.page.ev_end | date: "%H" | plus: 8 }}{{include.page.ev_end | date: "%M00Z" }}&ctz=America/Vancouver&details=For+details,+link+here:+https://audio.udub.club{{include.page.url | url_encode }}&location={{include.page.ev_where | url_encode }}&sf=true&output=xml)