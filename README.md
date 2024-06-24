# python-jupyter-notebook-studies

```bash
docker container run --rm --name jupyter-notebook -v $(pwd):/home/jovyan/work -p 3010:8888 -it jupyter/base-notebook:python-3.9

# Then, access the URL provided by logs of container!
```
