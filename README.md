# jack-latency-updater

Update PipeWire jack.conf node.latency from a simple GUI

![Jack Latency Updater](https://raw.githubusercontent.com/rolodoom/jack-latency-updater/master/screenshot.png)

## Status

[![GitHub license](https://img.shields.io/badge/license-GPL--3.0-blue)](https://raw.githubusercontent.com/rolodoom/jack-latency-updater/master/LICENSE)

## Dependencies

```bash
sudo apt install python3-gi gir1.2-gtk-4.0
```

## Build .deb

```bash
dpkg-deb --build --root-owner-group . jack-latency-updater_0.1-1_amd64.deb
```

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/rolodoom/jack-latency-updater/issues) here on GitHub.

## License

This code is released under the [GPL-3.0](https://github.com/rolodoom/jack-latency-updater/blob/master/LICENSE) license, which means you have the four freedoms to run, study, share, and modify the software. Any derivative work must be distributed under the same or equivalent license terms.
