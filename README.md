# python_docker_demo

edit requirements.txt with the pip packages you need. All python files must be in this directory


build with `docker build -t my-python-app .` (The dot "full stop" means the Dockerfile in this directory)

run with interactive shell (--rm remove once done) `docker run -it --rm --name mypython my-python-app`

run in background `docker run -d --name mypythonBG my-python-app`

you can stop and delete with Portainer or `docker stop mypythonBG` and remove `docker rm mypyhtonBG`



