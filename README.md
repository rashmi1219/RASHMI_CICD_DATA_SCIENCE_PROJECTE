# RASHMI_CICD_DATA_SCIENCE_PROJECTE
MY_FULL_CICD_DATA_SCIENCE_PROJECT


creating conda environment
```
conda create -p venv python==3.7 -y

```
activate venv
```
conda activate venv/

```
install requirements.txt file
```
pip install -r requirements.txt

```
git commands
```
git add <file name>        # to add one file
git restore <file name>    # to cancle the file sent to git hub
git add .                  #to add all the file to the git hub
git status                 #to check which modified or new file is not yet added to git hub
git commit -m"updated"     # to create the version of file
git log                    #to see all the version available
git push origin main       #to send the changed version to git hub, origin is the name given to url link
git remote -v              #to check the url

```
to setup CI/CD pipeline on heroku we need three information
```
heroku email id:shinning.prakash@gmail.com
heroku api key: 78d95231-ef6d-4f22-870a-334fca41d151
app name: 

```
to build docker image
```
docker build -t <image_name>:<tagname> . #image name should always be in small case
 
```
to list docker image
```
docker images

```
to run docker image
````
docker run -p 5000:5000 -e PORT=5000 <IMAGE-ID>

```
To check running container in docker
```
docker ps

```
To stop running container
```
docker stop <container-id>

```



                                                                                                            