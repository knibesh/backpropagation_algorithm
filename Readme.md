Assign small random variable to weight (-0.5 to +0.5)
Use feed forward method to calculate o/p(yk) by supply inputs
calculate delta for o/p layer (dk=(tk-yk)f(yink)
calculate delta for hidden layer dj = dinj f'(zinj)  |  dinj=sum(dk,wjk)
calculate dw, dwij=axi,di   |  dwjk = azj,dk
adjust neuron weight  wif(new)=wij(old)  + dwij  |  wjk(new)=wjk(old) + dwjk
Repeate from step2 until supplied cycyle threshold level 

