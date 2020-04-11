# WWT D.I.Y. Planetarium Dome Guide: Source Code

This repository contains the source code for the [WWT Do-It-Yourself Planetarium Dome Guide].
The `master` branch of this repo gets published here:

### https://docs.worldwidetelescope.org/diy-planetarium-dome/1/

[WWT Do-It-Yourself Planetarium Dome Guide]: https://docs.worldwidetelescope.org/diy-planetarium-dome/1/

If you’re just interested in the documentation itself, you should go to that
website. If you’re interested in *contributing* to this documentation, you’ve
come to the right place!


## Quick Start for the Initiated

The guide is a static site written in [CommonMark Markdown] and processed
with [Zola]. Zola is distributed as a single executable so it is ridiculously
[easy to install][install-zola].

This repository is themed by referencing [zola-wwtguide] as a submodule, so
upon first checkout you’ll have to run:

```
git submodule update --init
```

Once everything is set up, all you have to do is run

```
zola serve
```

to build the site and serve it locally for testing. The command `zola check`
will check the build and verify that outgoing links are valid. Zola has
[lots of documentation][zola-docs].

[CommonMark Markdown]: https://commonmark.org/
[Zola]: https://getzola.org/
[install-zola]: https://www.getzola.org/documentation/getting-started/installation/
[zola-wwtguide]: https://github.com/WorldWideTelescope/zola-wwtguide
[zola-docs]: https://www.getzola.org/documentation/getting-started/overview/

Merges to `master` will be published automatically using WWT’s continuous
deployment infrastructure.


## Contributing

Contributions are welcome! If you’re new to the project, please see the
[WWT Contributors’ Guide] and the [WWT Code of Conduct]. We operate with a
standard [fork-and-pull] model.

[WWT Contributors’ Guide]: https://worldwidetelescope.github.io/contributing/
[WWT Code of Conduct]: https://worldwidetelescope.github.io/code-of-conduct/
[fork-and-pull]: https://help.github.com/en/articles/about-collaborative-development-models


## Acknowledgments

The AAS WorldWide Telescope system is a [.NET Foundation] project managed by
the non-profit [American Astronomical Society] (AAS). Work on WWT has been
supported by the AAS, the US [National Science Foundation] (grants [1550701]
and [1642446]), the [Gordon and Betty Moore Foundation], and [Microsoft].

[.NET Foundation]: https://dotnetfoundation.org/
[American Astronomical Society]: https://aas.org/
[National Science Foundation]: https://www.nsf.gov/
[1550701]: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1550701
[1642446]: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1642446
[Gordon and Betty Moore Foundation]: https://www.moore.org/
[Microsoft]: https://www.microsoft.com/
