# MachineLearningProject
This is a Machine Learning Project

creating conda environment:
conda create -p <env_name> python==3.7 -y(-y means yes)

TO ACTIVE ENVIRONMENT:
conda activate <env_name>/ or conda activate <env_name>

TO INSTALL requirements.txt FILE:
pip install -r requirements.txt

TO ADD FILES TO GIT:
git add . or git add <filename>

Note:To ignore file or folder from git we can write name of file/folder in .gitignore file

TO CHECK GIT STATUS:
git status

TO CHECK ALL VERSION MAINTAINED BY GIT:
git log

TO CREATE VERSION/COMMIT ALL CHANGES BY GIT:
git commit -m "message"

TO CHECK REMOTE URL:
git remote -v

TO SEND VERSION/CHANGES TO GITHUB:
git push origin main

To setup CI/CD pipeline in heroku we need 3 information
1.HEROKU_EMAIL:abcd@gmail.com
2.HEROKU_API_KEY:
3.HEROKU_APP_NAME:ml-applic
Note:to delete any application in keroku first click on the application,go to settings,scroll down and click delete app and enter the app name and delete

BUILD DOCKER IMAGE:
docker build -t <image_name>:<tagname> .
note:image name for docker must be lowercase

TO LIST DOCKER IMAGE:
docker images

TO RUN DOCKER IMAGE:
docker run -p 5000:5000 -e PORT=5000 <image_id>(docker run -p 5000:5000 -e PORT=5000 3ef47uggb7g)

TO CHECK RUNNING CONTAINERS IN DOCKER:
docker ps

TO STOP DOCKER CONTAINER:
docker stop <container_id>


python setup.py install