# Convolutional Recurrent Neural Net For Imputing Missing Network Measurement Data

This is the implementation for the paper "Convolutional Recurrent Neural Network for Imputing Misisng Network Measurement Data" - under review at [GLOBECOM-2020][globecom2020]

## Getting Started

The following instructions will get you a copy and run the proposed CRIND model.

### Example of the missing network traffic data
![Network traffic data example](/traffic_data.png)

### Prerequisites

1. Extract the code

 The password to extract the code in included in the paper.

2. Obtain the dataset

 You need to get a copy of the AbileneTM, AbileneLL and BeijingAQ dataset.  
 The url to download password to extract the dataset is provided in the paper.

3. Directory structure

 You need to place the code and data somewhat similar to this structure
```
data/...
crind_code/...
```

### Installing dependencies

Our implementation was tested on Python version 3.6.9 or higher.
To install 
```
pip3 install -r requirements.txt --user
```

We implement our model using PyTorch.
If you need to retrain model on GPU then follow their guide to install [Pytorch][pytorch].

## Running the tests

You can run a simple test following the script "crind\_code/main.py".
The full experiment is included in the script "crind\_code/run\_experiment.py".


## Authors

* **Le Van An** - *anle@nii.ac.jp*
* **Le Tien Thanh** - *20144075@student.hust.edu.vn*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



[globecom2020]: https://globecom2020.ieee-globecom.org/
[pytorch]: https://pytorch.org/

