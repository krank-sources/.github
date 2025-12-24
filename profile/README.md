<h1 align="center">Krank sources collection</h1>

This organization houses a curated collection of dream-report datasets.

Each repository here contains Python code that downloads, inspects, preprocesses,
and repackages the dream reports into a single cleaned and validated csv file.

The output datasets are accessible through the GitHub release artifacts or
the Python package [Krank](https://github.com/remrama/krank).

> [!NOTE]
> **Credits:** The structure and underlying code of this GitHub organization and its repositories are modeled heavily after the [Fatiando a Terra FAIR data collection](https://github.com/fatiando-data). This overall project would not be possible without other products from the [Fatiando a Terra Project](https://www.fatiando.org), namely [Pooch](https://www.github.com/fatiando/pooch) for data access and [Ensaio](https://www.github.com/fatiando/ensaio) as inspiration for the broader [Krank](https://github.com/remrama/krank) project.
> 
> > Uieda, L., V. C. Oliveira Jr, and V. C. F. Barbosa (2013), Modeling the Earth with Fatiando a Terra, _Proceedings of the 12th Python in Science Conference_, pp. 91-98. doi:[10.25080/Majora-8b375195-010](https://doi.org/10.25080/Majora-8b375195-010)

---

<h2 align="center">Versioning</h2>

Datasets in this collection **use only a single number to denote their versions**.
This is because any change to data/metadata can lead to code that relies on them
breaking, so [semantic versioning](https://semver.org/) wouldn't make sense.
New releases are made when data/metadata are changed, added, or deleted.

That being said, an optional **pre-release versioning** might be specified
during development. When curating a dataset, one might want to test the dataset
out for a bit before releasing it more formally. In these cases,
[SemVer Specificiation 9](https://semver.org/#spec-item-9) is followed. Any
pre-release should be denoted with an `-alpha.X` tag, where `X` starts at 1 and
increases as needed. For example, release order might look like:

* `v1-alpha.1`
* `v1-alpha.2`
* `v1-alpha.3`
* `v1`
* `v2`
* `v3-alpha.1`
* `v3`
