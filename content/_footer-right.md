#### Community

<ul>
{{ if isset .Site.Params.urls "facebookurl" }}
  <li><a href="{{ .Site.Params.urls.FacebookUrl }}"><i class="fab fa-facebook-f"></i> Facebook</a></li>
{{ end }}
{{ if isset .Site.Params.urls "twitterurl" }}
  <li><a href="{{ .Site.Params.urls.TwitterUrl }}"><i class="fab fa-twitter"></i> Twitter</a></li>
{{ end }}
{{ if isset .Site.Params.urls "meetupurl" }}
  <li><a href="{{ .Site.Params.urls.MeetupUrl }}"><i class="fab fa-meetup"></i> Meetup</a></li>
{{ end }}
</ul>
