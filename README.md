# faiss-docker

## Building Docker Image
`sudo docker build 'root directory of this repo` 

## Building index
two paths needs to be adjusted, the incoming directory and the output directory.

I run the image `sudo docker run -it -v vectors_directory(host):input_directory(container) -v out_dir:out_dir docker_image`

I suggest attaching the same directory as the build_index file so you can adjust the file as needed

finally run the script `python build_index.py`
