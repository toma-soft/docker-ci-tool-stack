# CI/CD tool stack

# Why use this fork?

I tried to make the original source code as simple as possible. It does not contain any additional configuration or featuers. It must just work!

### How to use it?

Just clone this fork whereever you want to. Then make a symbolic link to /compose so the structure looks like this:
- /compose/jenkins
- /compose/nexus/
- /compose/docker-compose.yml

Create a data structure on the file system. You can create also a symbolic link, to match such pattern:

- /data
- /data/jenkins_data
- /data/nexus_data
- /data/sonar_data
- /data/sonardb_data

### Read the article

Go the article of mine http://tomasoftware.com/resources/pdfs/Docker_Compose_EN_v1.0.pdf which I created to describe the Docker Compose technology.
The main idea of the article and this fork, is to bring the simplest working example out-of-the-box. I found many examples on the Net, which did not work as expected wihtout additional/hidden tunning. So, I hope that you can use my example and say, that it does work immeidielty after preconfiguration of the filesystem.



