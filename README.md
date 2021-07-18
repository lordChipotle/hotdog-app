# The Hotdog-Not-Hotdog App is running on Fast.ai via [Render](https://render.com)

The app can be accessed via https://fastai-v3.onrender.com. Test it out with hotdog-ish looking images!


A detailed notebook of how we created this can also be found here:
https://colab.research.google.com/drive/1h_mibPuKCOK0t4XImQQX6zhE5S7tfRkF?usp=sharing#scrollTo=QPJyrnBkrGlf


Test changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

