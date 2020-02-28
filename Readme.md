# Trix Talks 
## Descomplicando Machine Learning

In this repository I will post all samples of the series of presentations about Machine Learning.

To run this samples follow this steps:

```bash
git clone https://github.com/eduardoslopes/trix-talks-machine-learning.git

docker pull jupyter/datascience-notebook

cd trix-talks-machine-learning/

docker run -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/datascience-notebook
```

After that, you will see a link in your terminal, like that: `http://127.0.0.1:8888/?token=<token>`. Copy and paste this in your browser. 