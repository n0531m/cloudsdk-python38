


## build image
`docker build . `

## run basic checks

to make sure python3.8 is running

``` 
docker run 9687b17af00a  python3.8 --version
```

to make sure gcloud runs 
```
docker run 9687b17af00a  gcloud --version
```

## tag images
```
docker tag 9687b17af00a n0531m/cloudsdk-python38
```

## push image
```
docker push n0531m/cloudsdk-python38
```