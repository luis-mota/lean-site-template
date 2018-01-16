#### Community

{{ if isset .Site.Params.urls "facebookurl" }}
* <a href="{{ .Site.Params.urls.FacebookUrl }}"><i class="fab fa-facebook-f"></i> Facebook</a>
{{ end }}
{{ if isset .Site.Params.urls "twitterurl" }}
* <a href="{{ .Site.Params.urls.TwitterUrl }}"><i class="fab fa-twitter"></i> Twitter</a>
{{ end }}
{{ if isset .Site.Params.urls "meetupurl" }}
* <a href="{{ .Site.Params.urls.MeetupUrl }}"><i class="fab fa-meetup"></i> Meetup</a>
{{ end }}
