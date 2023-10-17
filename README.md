# Teknik Pendekatan Pembuatan Model #
Project Pribadi MNIST menggunakan 3 Pendekatan Pembuatan Model

- Model Sequential  
Model Sequential adalah pendekatan yang paling sederhana dalam membuat model neural network dengan TensorFlow atau Keras. 

- Model Functional API  
 Model Functional API adalah Pendekatan pembuatan model menggunakan Functional API yaitu mendefinisikan lapisan-lapisan dan menghubungkannya menggunakan sintaksis yang lebih fleksibel dan mendukung berbagai arsitektur jaringan yang kompleks.

- Model Subclassing  
Model Subclassing adalah pendekatan yang lebih fleksibel di mana Anda mendefinisikan model Anda dengan menurunkan kelas tf.keras.Model dan menentukan perilaku forward pass dengan metode call. Yang memungkinkan untuk membuat model yang lebih kompleks dan tidak terbatas pada urutan linear lapisan