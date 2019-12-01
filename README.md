# DeepLearning-Workshop

Azure Machine Learning service を使った Deep Learning のワークショップコンテンツです。


# Sample Code

下記の表には、本リポジトリに含まれるサンプルコードのリストです。Environment 列のリンクからアクセスできます。


| Algorithm | Environment | Data | Description | 
| --- | --- | --- | --- |
| CNN | [Optuna](Sample/Keras/Keras-mnist-optuna-local.ipynb)| MNIST 文字認識| Optuna によるハイパーパラメータチューニングを実行。Notebook VM / ローカル環境での学習とメトリック記録|
| CNN | [Optuna](Sample/Keras/Keras-mnist-optuna-dist-remote.ipynb)| MNIST 文字認識| TensoFlow Estimator + Optuna による並列ハイパーパラメータチューニング| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-mnist-local.ipynb)| MNIST 文字認識| Notebook VM / ローカル環境での学習とメトリック記録| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-catdog-dataset-remote.ipynb)| Cat & Dog 画像認識 | TensorFlow Esimator による学習。Datastore から階層構造になっている 1 つの Dataset を利用。| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-catdog-each-dataset-remote.ipynb)| Cat & Dog 画像認識| TensorFlow Esimator による学習。各ラベル毎に学習用・検証用それぞれに対して Dataset を利用。| 
| CNN | [Azure ML service Python SDK](Sample/Keras/Keras-catdog-dataset-Hyperdrive.ipynb)| Cat & Dog 画像認識| **Hyperdrive によるハイパーパラメータチューニング**を実行。Datastore から 1つの Dataset を利用。| 
| LSTM | [Azure ML service Python SDK](Sample/Keras/Keras-LSTM-PredictiveMaintenance-datastore-Hyperdrive.ipynb)| 設備保全(時系列予測)| **Hyperdrive によるハイパーパラメータチューニング**を実行。Datastore を直接マウント。| 

