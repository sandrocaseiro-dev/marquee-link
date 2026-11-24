# marquee-link

One static page for Marquee, a personal Android TV app. MyAnimeList only sends a sign-in back to a fixed `https` address; `mal.html` is that address. It reads the TV's home-network address from the sign-in's `state` and forwards the phone to the TV, which finishes the sign-in. It forwards only to private network addresses and stores nothing.
