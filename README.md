# sidata.ai platform project

You can see here to know about the `sidata.ai` platform.

https://liuyuwei.github.io/sidata.ai/

## service-data-evaluation-analysis
You can use this service to get the evaluation easily.

- You can get the evaluation:
  - [x] Confusion matrix
  - [x] Accuracy
  - [x] Precision/Recall

### How to use it?

- Please use docker to start the service.
```bash
$ cd docker
$ ./docker_build_service.sh
$ ./docker_start_service.sh
```

- If you want to remove the service.
```bash
$ ./docker_remove_service.sh
```

- Swagger api website:

http://{ip-address}:8000/docs

![image](demo/swagger_ui.png)

- sqlite website visualization:

http://{ip-address}:8080/

![image](demo/sqlite_db_ui.png)

### Version, author and other information:
- See the relation information in [setup file](setup.py).

### License
- See License file [here](LICENSE).
