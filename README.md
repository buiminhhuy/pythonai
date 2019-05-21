# PythonAI
Just demo application base on example [Flowers Recognition](https://medium.com/@ferrygunawan/create-flower-image-classification-with-tensorflow-keras-and-flask-4fd6efd4c5ac)

Todo list:
- [x] Initialize AI project base on Flowers Recognition
- [x] Predict upload image to 5 categories: daisy, dandelion, rose, sunflower, tulip.
- [x] Users can upload image for predict and choose to correct category.
- [ ] Admin can review users's upload images for appending to train data, or can set auto review.
- [ ] Guest can see how much upload images were predicted for each categories.

Run:
```python
[setup virtualenv](https://docs.python-guide.org/dev/virtualenvs/)
pip install -r requirements.txt
python train-multiclass.py
python app.py
```

App screen:
![App Screen](./app_screen.png?raw=true "App Screen")

Refs:
- [Fork from](https://github.com/ferrygun/AIFlowers2)
- [Train data](https://www.kaggle.com/alxmamaev/flowers-recognition)

