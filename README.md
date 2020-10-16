# Repositorio de trabajo de memoria de titulación: Pronóstico de fallas para mantenimiento predictivo usando metodologías de aprendizaje profundo supervisado

### Francisco Araya López - Departamento de Electrónica - UTFSM
#### Turbofan Engine Degradation Simulation Dataset
#### Octubre 2020

![alt text](https://cdn.pixabay.com/photo/2019/08/22/02/07/a-10-jet-engine-4422314_960_720.jpg)

##### Archivos:

- **turbofan.ipynb:** Contiene código que permite generar features maps (muestras/samples) para training, validation y test set de datasets FD001, FD002, FD003, FD004 con time windows, optimizador, batch size y epochs deseados. Además permite entrenar modelos usando arquitectura de X. Li, Q. Ding, J. Sun, Remaining useful life estimation in prognostics using deep convolution neural network.

- **analisis_descriptivo_turbofan_faraya.ipynb:** Contiene análisis descriptivo previo de dataset turbofan tales como histogramas de cada dataset del training set (FD001,FD002, FD003 y FD004) y aplicación de PCA a cada uno de ellos.

- **turbofan_Li_modificado_faraya.ipynb:** Contiene código que permite generar features maps (muestras/samples) para training, validation y test set de datasets FD001, FD002, FD003, FD004 con time windows, optimizador, batch size y epochs deseados. Además permite entrenar modelos usando arquitectura propuesta en el trabajo de memoria de titulación basada en _X. Li, Q. Ding, J. Sun, Remaining useful life estimation in prognostics using deep convolution neural network_.

- **turbofan_Babu_modificado_faraya.ipynb:** Contiene código que permite generar features maps (muestras/samples) para training, validation y test set de datasets FD001, FD002, FD003, FD004 con time windows, optimizador, batch size y epochs deseados. Además permite entrenar modelos usando arquitectura propuesta en el trabajo de memoria de titulación basada en _G. Babu, P. Zhao, X.-L. Li, Deep Convolutional Neural Network Based Regression Approach for Estimation of Remaining Useful Life_.

- **Li_graphics_loss_predictions.ipynb:** Contiene gráficos dispersion RUL verdadero vs RUL estimado + Gráficos Log(Error) vs # Epochs de modelos entrenados con arquitectura propuesta basada en _X. Li, Q. Ding, J. Sun, Remaining useful life estimation in prognostics using deep convolution neural network_.

- **Ba_graphics_loss_predictions.ipynb:** Contiene gráficos dispersion RUL verdadero vs RUL estimado + Gráficos Log(Error) vs # Epochs de modelos entrenados con arquitectura propuesta basada en _G. Babu, P. Zhao, X.-L. Li, Deep Convolutional Neural Network Based Regression Approach for Estimation of Remaining Useful Life_.


_Proyecto licenciado bajo GNU General Public License v3.0 /  Project licensed under the GNU General Public License v3.0_
