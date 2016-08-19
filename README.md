Jupyter
=======

!["Prompt"](https://raw.githubusercontent.com/gbraad/assets/gh-pages/icons/prompt-icon-64.png)


Docker container containing Jupyter


## Registries

### GitLab

Available as an automated builds at the GitLab [container registry](https://gitlab.com/gbraad/jupyter/container_registry).

  * Fedora 24:  
    `docker pull registry.gitlab.com/gbraad/jupyter:f24`


### Docker hub

Available as an automated build from the [Docker registry](https://hub.docker.com/r/gbraad/jupyter/).

  * Fedora 24:  
    `docker pull gbraad/jupyter:f24`


Usage
-----

```
$ alias jupyter='docker run -it --rm -v $PWD:/workspace registry.gitlab.com/gbraad/jupyter:f24'
$ jupyter notebook
```

and open your browser to `http://localhost:8888` [http://localhost:8888](http://localhost:8888)



Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |
