1. Create a dockerfile and name it Dockerfile
2. Build the image and give it a name using '-t' flag: docker image build -t nginx-with-html 
3. Run the built image: docker container run -p 80:80 -rm nginx-with-html

