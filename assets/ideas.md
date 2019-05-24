RESPONSIVE TYPOGRAPHY

Responsive typography refers to scaling text and components by simply adjusting the root element’s 'font-size' within a series of media queries. Bootstrap doesn’t do this for you, but it’s fairly easy to add if you need it.


html {
  font-size: 1rem;
}

@include media-breakpoint-up(sm) {
  html {
    font-size: 1.2rem;
  }
}

@include media-breakpoint-up(md) {
  html {
    font-size: 1.4rem;
  }
}

@include media-breakpoint-up(lg) {
  html {
    font-size: 1.6rem;
  }
}