# NER-Chinese
中文命名实体识别
## 这是一个基于BI-LSTM-CRF的中文命名实体识别算法
## 运行环境：
python3.5以上  tensorflow 1.4（我用的1.4,没试过其他版本）
## 运行方法
直接运行main.py即可 即python3 main.py.
至于运行方法有训练，测试和demo三种。均在该文件的参数解析有说明，根据需要修改即可
（默认GPU，么有GPU的伙伴们找到 with tf.Session(config=self.config) as sess: 这句,把config参数删掉就可以啦,这个在model.py文件中哦）

## 数据
项目中已有数据，直接可以运行的。
