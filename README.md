``` php
<?php

define("ME", "Benjamin Reisz");

class MyLife {

  const MUSIC = TRUE;

  public function because() {
    echo "Sans la musique, la vie serait une erreur, une besogne éreintante, un exil.<sup>*</sup>";
  }
}

$thatslife = new MyLife();
if ($thatslife::MUSIC) {
  $thatslife->because(); // la question elle est vite répondue :-)
}


```

```
*Le Crépuscule des idoles, Friedrich Nietzsche.
```

:notes:  [mon profil SoundCloud](https://soundcloud.com/benjbmc)  :notes:
