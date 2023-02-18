# kaggle_gokui
実践力がなさすぎるので極意本で修行
2, 3章をやってNFLに戻る。
# 日記
2023/2/17  
pytorch Model を nn.Sequential または class で定義する方法を理解  
2023/2/18  
pytorchのtensor型は行列の数値情報だけでなく、backward()によって得た勾配情報も保持できる。  
grad_fn=<AddBackward0>は関数の演算過程にrequires_grad=Trueの変数があり,backward()可能であることを示している.  
torch.ones(A, B, C) B=行, C=列, A=行列の数
ndarray ⇒ Tensor  torch.from_numpy()