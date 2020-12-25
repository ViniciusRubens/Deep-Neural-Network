<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/DEEP%20NEURAL%20NETWORK%20Logotipo.png alt="DEEP NEURAL NETWORK" width="200">
<br>
<br>
DEEP NEURAL NETWORK
</h1>

<p align="justify">
My project is based on the development of a machine learning using the concepts of Deep Neural Network. 

Pode-se dizer que a Regressão Logística é um caso de uma Shallow Neural Network, enquanto que uma Deep Neural Network são redes que possuem um número muito maior de camadas ocultas. Cada Camada Oculta é dotada de um número de neurônios determinado pelo projetista. A Camada de Entrada permanece com o número de neurônios correspondendo ao vetor característica que foi obtido no processamento das iamgens, e como esse projeto se trata de uma classificação binário de 0 para gatos e 1 para cachorros, a Camada de Saída permanece com um único neurônio.
</p>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/Deep%20neural%20network%20model.png alt="DEEP NEURAL NETWORK" width="350" height = "550">
<br>
</h1>

<p align="justify">
Os valores que são transmitidos entre as diferentes camadas são chamados de valores de ativação e são armazenados na matriz denominada de AL neste projeto. Como se trata de um modelo com L camadas, tanto a Forward como Backward propagation passam por cada camada através de incrementos e decrementos em laços de repetição for. 

Each layer is associated with parameters W and b, which will be updated according to Forward and Backward propagation, decreasing the value of the Cost Function, improving the accuracy and precision of the project.
</P>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/sequence.png alt="DEEP NEURAL NETWORK" width="210">
                    
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/calculus.png alt="DEEP NEURAL NETWORK" width="300">
<br>
</h1>

<p align="justify">
Moreover, it is important to note that this project is a Shalow Neural Network model for study and knowledge of how machine learning works for simple situations, without using mechanisms and frameworks, which would have a more significant efficiency, but which is not the goal in this work. This can be seen, by the uses of various functions of calculations such as Sigmoide, Cost Function, Forward Propagation and Backward Propagation.

Thanks, and enjoy.

</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## Features
[//]: # (Add the features of your project here:)
The programming language used was Python 3 in Jupyter environment, using the libraries highlighted below whose documentation is in the links just by clicking on them. In the next topic you will have a description of how you can install the libraries and test the code.

- 📁 [Numpy](https://numpy.org/) — Python library used for the calculations of multidimensional matrices.
- 📁 [Matplotlib](https://matplotlib.org/3.3.3/contents.html) — Library used to check the tests.
- 📁 [Os](https://docs.python.org/3/library/os.html) — Library used to browse directories from our PC.
- 📁 [OpenCV](https://opencv.org/) — Library used to modify and load our images.

## Getting started

To use this project, we need to do some library installations. Let's see below how to do this step:

👉 To install the Numpy library, if we use the Windows Command Prompt we can run the command:

`pip install numpy`

If you want to install directly by Jupyter through Conda, we can execute the command:

`conda install numpy`

If you are having problems during installation, a good alternative is to check your version of pip and Python, when we run the command below in the Command Prompt both information are provided: 

`pip --version`

👉 To install the Matplotlib library, the process is similar. By Command Prompt we will do: 

`pip install matplotlib`

👉 By default the Os library is a package already installed together with the Python installation.

👉 Finally, the OpenCV library can be installed through the following command in the Command Prompt:

`pip install opencv-python`

⚠️ This project works with a database of images available free of charge on the [Kaggle](https://www.kaggle.com/) platform . In this project the volume of images was reduced due to the hardware limitations of the computer that performed the training.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.