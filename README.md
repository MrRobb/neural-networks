# Neural Networks
### Introducción
An statistical approach to neural networks

### Instalar requerimientos (macOS)
Ejecuta en la terminal:
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install python
brew postinstall python
brew install python3
brew postinstall python3
sudo pip install tensorflow
sudo pip3 install tensorflow
```

### Instalar requerimientos (Ubuntu)
Ejecuta en la terminal:
```sh
sudo apt-get update
sudo apt-get install python2.7
sudo apt-get install python3.6
sudo apt-get install python-pip
sudo apt-get install python3-pip
```

### Instalar requerimientos (Windows)
Baja al final de la [página](https://www.python.org/downloads/release/python-362/) e instala python3 (Windows Executable Installer)

Ejecuta en la terminal:
```sh
pip3 install --upgrade tensorflow
pip3 install --upgrade tensorflow-gpu
```

Para ver si funciona ejecuta:
```sh
python
```

Y en la consola interactiva escribe:
```python3
>>> import tensorflow as tf
>>> hello = tf.constant('Hello, TensorFlow!')
>>> sess = tf.Session()
>>> print(sess.run(hello))
```

Asegurate de que sale (significaría que todo funciona correctamente):
```sh
Hello, TensorFlow!
```

### Cómo ejecutar
Ahora podéis ejecutar los códigos del archivo `neural-networks.py` sin problema, así:
```sh
python3 neural-networks.py
```
