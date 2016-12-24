# jhmq

Website to display Julia's Historic Marker Quest data.

<https://stevenclontz.github.io/jhmq/>

## About JHMQ

My sister-in-law Julia's hobby is finding and cataloging historical markers
across the state of Alabama. Her
[Facebook page](https://www.facebook.com/juliashistoric.markerquest)
has a few of them, but I wanted to give her a way to easily share these
finds with the greater internet.

If you're Julia you can edit the
[Google Sheet](https://docs.google.com/spreadsheets/d/17POJsIXACyxW5NrUV677niPT563_j-wTXLOTPBFVi_w/edit?usp=sharing)
that acts as the backend to the site. If you're not Julia, you can view it
to see how the site is generated.

## Google Maps API

As far as I can tell, there's no easy way to use the Google Maps API without
revealing the API key publicly. It's configured to only work with
`stevenclontz.github.io/*` and `127.0.0.1:4000/*`, but please be kind to
my quotas and generate your own key if you choose to fork and play with this
repo.
