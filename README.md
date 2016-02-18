![Nodezoo][Logo]

# nodezoo-metrics

- __Lead:__ [Dean McDonnell][Lead]
- __Sponsor:__ [nearForm][]

This module handles metric collection for the [NodeZoo][] system. It uses Influx and Vidi: Metrics to do this.

## Install
1. clone this repo into a root _/nodezoo_ folder.
2. run `npm install`

## Starting
To start simply run,

```
npm run start
```

### Tagging and Logs
To tag your service and set up logs simply pass the relevant switches on start,

```
npm run start -- --seneca.options.tag=nodezoo-stats --seneca.log.all
```

## Inbound Messages
This micro-service emits no inbound messages.

## Outbound Messages
This micro-service emits no outbound messages.

## Contributing
The [NodeZoo org][] encourages __open__ and __safe__ participation.

- __[Code of Conduct][CoC]__

If you feel you can help in any way, be it with documentation, examples, extra testing, or new
features please get in touch.

## License
Copyright (c) 2016, Dean McDonnell and other contributors.
Licensed under [MIT][].


[MIT]: ./LICENSE
[CoC]: ./CoC.md
[Lead]: https://github.com/mcdonnelldean
[nearForm]: http://www.nearform.com/
[NodeZoo]: http://www.nodezoo.com/
[NodeZoo org]: https://github.com/nodezoo
[Logo]: https://raw.githubusercontent.com/nodezoo/org/master/assets/img/logo-nodezoo.png
