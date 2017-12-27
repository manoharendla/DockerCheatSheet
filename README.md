# Welcome to Docker cheat Sheet


| S.No. | Dockercommand | Description | 
| --- | --- | --- |
| 1. | docker images | Displays the images in the docker host |
| 2. | docker build -t="sampleTagName to Identify your image created using docker file" | When docker build is executed in the directory where the docker file is available, an image will be created with the definitions created in the docker file |
| 3. | docker jenkins pull | Pulls a Jenkins image from the docker cloud repository or docker hub  |
| 4. | docker stop containerId(or)ContainerName | Stops the running container using SIGTERM and then SIGKILL, helps in gracefull shutdown of the container |
| 5. | docker kill jenkins | Stops a container without a gracefull shutdown, chances of unstable state of the container |
| 6. | docker run imageName | Creates a container from the image |
| 7. | docker run -it imageName /bin/bash | Creates a container in interactive mode and executes the command /bin/bash as an entry point |
| 8. | docker run --name="CreateANameforContainer" imageName  | Creates a container with specified Name |
| 9. | docker run -d imageName  | Creates a container in detached mode |
| 10. | docker attach containerName  | Allows you to attach to the container in interactive mode |
| 11. | docker ps  | Lists the running containers |
| 12. | docker ps -a  | Lists all the containers in running or exited state |
| 13. | docker inspect container  | Lists all the containers in running or exited state |
| 14. | docker run --help  | Lists all the available commands with run |
| 15. | docker start containerName  | Start a container that is in existed ot stopped state |
| 16. | docker exec -it containerName bash | Connect interactively through terminal or ssh into running container |








|    | `Details of commands used in Dockerfile` |  |
| 1. |  ENV var1=Mano var2=Master |  Using ENV keyword we declare variables |
| 2. | WORKDIR dirname | Set the Working directory when the container is launched |
| 3. | CMD pwd |  Execute a command when container is launcher |
| 4. | FROM ubuntu | Base image |
| 5. | MAINTAINER  manoharendla277@gmail.com | Helps in dentifying the  owner of the image file |




































## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/manoharendla/DockerCheatSheet/edit/gh-pages/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3



- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/manoharendla/DockerCheatSheet/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
