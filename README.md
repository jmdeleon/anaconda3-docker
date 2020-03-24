Minimal docker setup for Anaconda Python 3

Create the container:

docker-compose build

Start the container:

docker-compose up -d

Execute bash within the container and run jupyter notebook list to get the Jupyter Notebook URL, or:

docker exec -it anaconda3 jupyter notebook list
