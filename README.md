# Docker Playground

## Some examples

### Updating Dockerfile after changes, you need run:

```sh
[sudo] docker build -t user/project:tag .
```

Where `user/project:tag` is an alias to run your Docker container.

`user/project` can be your own Dockerhub user and project name, and `:tag` is an alias that can be the version of your project.

After that, you can run this with command:

```sh
[sudo] docker run user/project:tag
```

### Mounting directories

```
[sudo] docker run -v /home/user/host_dir:/docker/image/dir docker_image
```
Where `/home/user/host_dir` is the directory's path (must be full path) that gonna be mounted into the docker's image in `/docker/image/dir`.


## Links

- [GUI apps with docker :shipit:](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
- [Docker for DevOps: From development to production](https://www.kickstarter.com/projects/nickjj/docker-for-devops-from-development-to-production)
- [Bash style](https://github.com/progrium/bashstyle)
- [How to Manually Build Docker Containers for WordPress](https://www.sitepoint.com/how-to-manually-build-docker-containers-for-wordpress/)
- [How to Use the Official Docker WordPress Image](https://www.sitepoint.com/how-to-use-the-official-docker-wordpress-image/)
