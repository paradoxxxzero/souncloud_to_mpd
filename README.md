# soundcloud_to_mpd
Load soundcloud sounds into a mpd instance:

```bash
    $ soundcloud_to_mpd --soundcloud-id a-sound-cloud-api-id --tracks edm -n 10
```

```bash
    $ soundcloud_to_mpd --help

    Usage: soundcloud_to_mpd [OPTIONS]

    Options:
      --group=STR            (default: )
      --likes=STR            (default: )
      --playlists=STR        (default: )
      --soundcloud-id=STR    (default: )
      --tags=STR             (default: )
      --top=STR              (default: )
      --tracks=STR           (default: )
      --trending=STR         (default: )
      --mpd=STR              (default: localhost)
      -n INT                 (default: 50)

    Other actions:
      -h, --help            Show the help
```
