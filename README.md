# EcommerceTryAndBuy

Customer expectations are constantly getting higher. So its necessary for all the businesses to keep innovating and meet ever increasing customer expectations by providing better experiences and convenience.
We are focusing here on e-commerce industry and specifically digital footwear store. We trying to add virtual reality into the buying process. 
Traditionally we can see only the 2D image of the product(in some cases 3d image of the product) but here we are trying to give better product representation by showing 3D model of the user(by taking specific inputs from customer) along with the footwear attached to the feet. 
This will let the customer know how well the footwear suits him, is it matching with the dress, is the product is of correct size. 
Overall we are trying to increase the sales of the product by providing better purchasing experience.

## Flow Chart
![alt text](https://github.com/Inishpy/EcommerceTryAndBuy/blob/main/staticfiles/images/flow.png?raw=true)

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/Inishpy/EcommerceTryAndBuy.git
$ cd EcommerceTryAndBuy
```
Dowload [Blender](https://www.blender.org/download/) and paste the whole blender folder in this directory

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd project
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/



## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[Meshroom](https://meshroom-manual.readthedocs.io/en/latest/about/licenses/licenses.html)  


 ![alt text](https://github.com/Inishpy/EcommerceTryAndBuy/blob/main/staticfiles/images/AliceVision.png?raw=true)

[Blender](https://www.blender.org/about/license/)

![alt text](https://github.com/Inishpy/EcommerceTryAndBuy/blob/main/staticfiles/images/pngegg.png?raw)
