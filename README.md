# DDIS ʵ��  
���о���Ҫ�������ҩ���ת¼�����ݹ������Ӿ�ȷ��ҩ��-ҩ���໥����(drug�Cdrug interactions,DDIs)Ԥ��ģ���е�������Ҫ����:
1��ҩ��ת¼�������еĻ�������.
2������̽���˽�ҩ�￴��������Ϣ�Ƿ��������DDIs��Ԥ�⡣

## �ļ�Ŀ¼�ṹ  

<div>
    <div style="float:left">/codes/</div>
    <div style="float:right">ʵ����룬��������Ԥ����ģ��ѵ����ģ�ͶԱȵ�</div>
</div>


<div>
    <div style="float:left">/data/original_data/</div>
    <div style="float:right">LINCS L1000���ݿ����ѻ����˶���ҩ���յ���ת¼������</div>
</div>

<div>
    <div style="float:left">/data/feature_processed_data/</div>
    <div style="float:right">����GCN��ܽ�������Ԥ����������</div>
</div>

<div>
    <div style="float:left">/result/</div>
    <div style="float:right">����м��������ս����</div>
</div>

## ��Ŀִ�����蹤�߰�֧�ּ���֤ͨ���İ汾��  

| ���߰�    | numpy  |pandas  |tensorflow |skmultilearn  |sklearn  |
| ----------| -------| -------| ----------| -------------| --------| 
| �汾��    | ������ |��������| ����������| ������������ | ��������|

## ����˵��
����ִ��˳��:
`��ִ�� "P1_preprocessing_GCN_data.py" ` ,��ԭʼ���ݽ���Ԥ����
`��ִ�� "P2_LSTM_GCN_train_RNN_2layer.py"` ,��Ԥ����������ѵ��ģ�ͣ�
`���ִ�� "P3_compare_model.py"` ���Ա�ģ�����ܡ�

1. ����Ԥ����

   `inits.py��Layer.py��Model.py`��;��GCN��ܵĳ�ʼ��
   
   `P1_preprocessing_GCN_data.py`��;��GCN��ܽ�������Ԥ����
   
    
2. ģ��ѵ��
   
   `P2_LSTM_GCN_train_RNN_2layer.py` ��;����LSTM_GCN���ѵ��RNNģ��

3. �Ա�ģ��

   `P3_compare_model.py` ��;�Ա� "MLARAM", "MLkNN", "BRkNNa", "BRkNNb", "RF", "MLTSVM"����ģ������
   
    
## ����ļ�  
* �������½���ļ� 
    * /result/������/������������xxx
    * /result/������/���������� xxx 
    
    