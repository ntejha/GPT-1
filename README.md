# Notes

I am using ananconda, so please download your respective versions of the anancoda to proceed. 

Also in your terminal enter,
- sudo ubuntu-drivers autoinstall
- nvidia-smi (find the cuda version, mine is 12.2)
- pip install torch

in terminal, type python and enter,
- import torch
- print(torch.cuda.is_available()) If, it prints true everything is done properly

We are going to create a virtual environment in conda named tax.
- conda create -n tax python=3.11 anaconda
- conda activate tax

then the needed libraries are:
- matplotlib
- numpy
- pylzma
- torch

Make a ipynb notebook and choose the kernel tax the virtual environment so we can use the downloaded libraries

As we going to use a tax book as knowledge base, we convert the pdf to txt file.