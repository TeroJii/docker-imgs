# How to run

## First build the image

```bash	
docker build -t raps_ubuntu_r .
```

This will create a docker image with the name `raps_ubuntu_r`.

## Run the image

We want to run the image in detached mode, with an interactive terminal, and name the container `ubuntu_r_1`.

```bash
docker run -d -it --name ubuntu_r_1 raps_ubuntu_r
```

We can now access the container with the following command:

```bash
docker exec -it ubuntu_r_1 R
```

This will open an interactive R session in the container.