# sign-language

Welcome to GitHub Pages
You can use the editor on GitHub to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run Jekyll to rebuild the pages in your site, from the content in your Markdown files.

Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

Syntax highlighted code block

# Sign Language Recognition
## Natural Language 

Natural language processing (NLP) refers to the branch of computer science—and more specifically, the branch of artificial intelligence or AI—concerned with giving computers the ability to understand text and spoken words in much the same way human beings can.

## Sentiment analysis

Sentiment analysis is the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information



### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your repository settings. The name of this theme is saved in the Jekyll _config.yml configuration file.




Ansible installation:
$ sudo apt update 
$ sudo apt install software-properties-common 
$ sudo add-apt-repository --yes --update ppa:ansible/ansible 
$ sudo apt install ansible
sudo apt-get install git				 //install
sudo apt-get remove --auto-remove git 	//uninstall



//git push

mkdir devops
Cd devops
Git init
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
Git remote add origin “https://github.com/abcd/devops_trial.git”
Git push -u origin main/master

// git_pull

mkdir devops
Cd devops
git init
Git remote add origin <link>
Git pull origin <branch>

// Git_config

mkdir devops
Cd devops
Git init
Git config user.email “<email>”
Git config user.name “<name>”
Ls -al
Cd .git
Ls -al
Cat config



// git log

mkdir devops
Cd devops
Git init
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
git log


Installing docker
Sudo apt-get install docker.io

Docker Pull 
Sudo bash
Docker images
Docker pull ubuntu
Docker images
(optional)
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash

Docker Push
Docker images
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash
(inside ubuntu)
Echo abcd>newfile
Cat newfile
Exit
(outside)
Docker ps
Docker commit <conatiner-id> new
docker tag SOURCE_IMAGE[:TAG] dockerusername/TARGET_IMAGE[:TAG]
Docker tag new:latest <username>/dickshant:pussy
Docker login
Docker images
Docker push <username>/dickshant:pussy


Deploy
mkdir devops
cd devops
Nano app.py
Print(“Welcome Docker file”)
nano dockerfile (//Below 3 lines under dockerfile)
FROM python
COPY . /src
CMD ["python", "/src/app.py"]
sudo bash
docker build . -t python_app
docker run python_app












