# h2o
High performance, distributed machine learning algorithms on Spark, using R

```
sudo apt-get install r-base libapparmor1 gdebi-core
wget https://download2.rstudio.org/rstudio-server-1.0.136-amd64.deb
sudo gdebi rstudio-server-1.0.136-amd64.deb
sudo adduser jrcajide
echo jrcajide:xxx | chpasswd
sudo su -
sudo rstudio-server start

sudo apt-get update

sudo apt-get install git


sudo apt-get install openssl

sudo apt-get install libssl-dev

sudo apt-get -y install libcurl4-openssl-dev

sudo rstudio-server restart

# Update R
sudo apt-get update && sudo apt-get upgrade
sudo apt-get install r-base
R --version

sudo apt-get install libgsl0-dev

sudo apt-get -f install

./steam login localhost --username=admin --password=admin
```

## Models

### GLM

Generalized Linear Models (GLM): Provides flexible generalization of
ordinary linear regression for response variables with error distribution models
other than a Gaussian (normal) distribution. GLM unifies various other
statistical models, including Poisson, linear, logistic, and others when using `1
and `2 regularization.

[H2O GLM](glm.md)
