# A web-based catalogue of guidelines and examples for architecting Android apps 

This repository contains the files which produce the website. 
This website is produced to make the 42 guidelines from Verdecchia * et al* accessible.
These guidelines can be found [here](https://robertoverdecchia.github.io/papers/ICSA_2019.pdf).
This website was made using [Jekyll](https://jekyllrb.com/).
The theme [LessCss](http://lesscss.cn/) is modified to create this website.
On these website the guidelines are described using code examples and descriptions.
The Android architectures that are described on this website are MVVM and MVP. 
Also generic architectural practices are described to improve applications. 

## Making modifications of this website

For making modifications to this website, the website can be downloaded at this [page](https://github.com/Geertdepont/bachelor_thesis/tree/master/bachelor-thesis-site).

By running in the command line:
```
bundle exec jekyll serve
```

The website is created and hosted locally.
The files that produce the website can be found in the _site folder  


### Prerequisites

This website is build using ruby 2.6
To find the version of ruby, run in the command line:

```
ruby -v
```

## Applications described
The code examples that are used as code example can be found on the [GitHub page](https://github.com/Geertdepont/bachelor_thesis/tree/master/bachelor-thesis-site).


## Deployment

To deploy this website on a server, run this on the command line:

```
bundle exec jekyll serve
```

Then all the files in the _site folder can be dropped in on the server. 

## Built With

* [Jekyll](https://jekyllrb.com/) - The web framework used
*  [LessCss](http://lesscss.cn/) - The styling from the website.

## Versioning

1.0

## Authors of the website

* **Roberto Verdecchia** - **Ivano Malavolta** - **Patricia Lago** - **Geert de Pont** - *Initial work* 

