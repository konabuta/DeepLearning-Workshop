# DeepLearning-Workshop

Azure Machine Learning service を使った Deep Learning のワークショップコンテンツです。


# Sample Code

下記の表には、本リポジトリに含まれるサンプルコードのリストです。Environment 列のリンクからアクセスできます。


| Algorithm | Environment | Data | Description | 
| --- | --- | --- | --- |
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-mnist-local.ipynb)| MNIST 画像認識| Notebook VM / ローカル環境での学習とメトリック記録| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-catdog-dataset-remote.ipynb)| Cat & Dog 画像認識 | TensorFlow Esimator による学習。Datastore から 1つの Dataset を作成しダウンロード。| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-catdog-each-dataset-remote.ipynb)| Cat & Dog 画像認識| TensorFlow Esimator による学習。各ラベル毎に学習用・検証用それぞれに対して Dataset を作成しダウンロード。| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-catdog-dataset-Hyperdrive.ipynb)| Cat & Dog 画像認識| **Hyperdrive によるハイパーパラメータチューニング**を実行。Datastore から 1つの Dataset を作成しダウンロード。| 

