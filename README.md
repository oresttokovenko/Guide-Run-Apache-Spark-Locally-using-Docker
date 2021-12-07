# Guide-Run-Apache-Spark-Locally-using-Docker
Guide on running a local Apache Spark cluster and interacting with it using Jupyter Notebook or JetBrains DataSpell (2021.3 / build 213.5744.251)


## Instructions

1. run `docker pull jupyter/pyspark-notebook`
2. run `docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook`
3. option 1: copy and paste the url you see into chrome, I had `http://127.0.0.1:8888/?token=f7fd6c10e8609ea376ddfd2aead17356abfac033c31e94af`. It will open a Jupyter Notebook and you're done.
4. option 2: in DataSpell select the `environment` tab in the menu bar and click `Add Jupyter Connection`<sup>(fig. 1)</sup>
5. select `Connect to Jupyter server using URL` and enter the url that contains `127.0.0.1:8888`
7. once that is done, you can click on the Python interpret in the bottom right and select the one that is called `jupyter-remote`<sup>(fig. 2)</sup>
8. check to ensure that Spark is running<sup>(fig. 3)</sup>

fig. 1

![Screen Shot 2021-12-07 at 2 37 36 PM](https://user-images.githubusercontent.com/51058259/145110705-79f64c7f-661f-4d30-bd66-4e170a7a0df2.png)

fig. 2

![Screen Shot 2021-12-07 at 2 37 27 PM](https://user-images.githubusercontent.com/51058259/145110796-c35596d6-5d50-4f28-b66c-2913725d435d.png)

fig. 3

![Screen Shot 2021-12-07 at 2 37 13 PM](https://user-images.githubusercontent.com/51058259/145110826-4c7aeb76-cd22-463e-af2e-44294b370620.png)
