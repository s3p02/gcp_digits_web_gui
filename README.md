## Step i : Download Dataset

Once you have the digits docker container up and running, at your terminal, enter the following to download the dataset. For our dataset, we shall use google's creative-commons licensed flower photos.

```
!curl http://download.tensorflow.org/example_images/flower_photos.tgz \
    | tar xz -C ~/
```
 Your Dataset is located in your home directory. 
 
 We need a sample test images to test our dataset while the model is running, so download a smaple test image from wikipidia, as shown below.
 
 ```
!wget https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/Yonina_Tulip.jpg/220px-Yonina_Tulip.jpg -P ~/
```

Your Sample test image will also be in your home directory
 
Now open a web-browser

## Step ii : Access the web-app

In your web browser, enter http://__YOUR__EXTERNAL__IP__ADDRESS__:5000/	


<kbd>
  <img src="/update_1.png">
</kbd>

You will see the DIGITS webpage as shown above.

## Step iii : Create a Dataset

Click Images>>Classification under 'New Dataset' as shown below:

<kbd>
  <img src="/2.png">
</kbd>

In order to use DIGITS to create models and dataset's one needs to have a username to login. Enter your name. Given that Multiple users can access the same server, username isolates their usage i.e. creating models, and datasets from other accounts.



<kbd>
  <img src="/3.png">
</kbd>
