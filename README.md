# ghosts
![ghosts](https://unixtitan.net/images/cherries-clipart-pacman-6.png)
## What is ghosts?

`ghosts` is a distributed system for applied AI research and online StarCraft bot competition based on TorchCraft a bridge between *Torch and StarCraft that sends data out over a [ZMQ](http://zeromq.org) connection and certain [luerl](https://luerl.org) simulation engine that train information models provided for convenience spawning *nix daemons over time that grow into other units; nodes provide granular unit control with in `ghosts` clusters, spawn more nodes to allow control of additional units.

Feel free to [explore](https://github.com/spacebeam) and remember; as your system grow in number, you must spawn more nodes to control it.

## Goal 
The goal of `ghosts` application is to provide up-to-date information models for convenience consumption.

## Install

You can install `ghosts` from [hex.pm](https://hex.pm/packages/ghosts) by including the following in your `rebar.config`:

```
{deps,[
	{ghosts, "X.Y.Z"}
]}.
```
where _X.Y.Z_ is one of the [release versions](https://github.com/spacebeam/ghosts/releases).

For more info on rebar3 dependencies see the [rebar3 docs](http://www.rebar3.org/docs/dependencies).

## Help wanted

Would you like to help with the project? Pick any of the issues tagged [help wanted](https://github.com/spacebeam/ghosts/labels/help%20wanted) and contribute!

## Contributing

See  [Contributing](CONTRIBUTING.md).
