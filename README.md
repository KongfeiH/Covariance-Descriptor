# Covariance-Descriptor
the python tool of Covariance descriptor,
the introuduce will coming soon,
a simple demo:
from CovarianceDescriptor import CovD

img=...
img1=...

fx={"I":True,"dx":True,"dy":True,"ddx":True,"ddy":True }，
# fx={"x":True,"y":True,"R":True,"G":True,"B":True,"I":True,"dx":True,"dy":True,"ddx":True,"ddy":True}，

covd=CovD(rectangle=(32,32),**fx)，
T=covd.get_CovD(img)，
T1=covd.get_CovD(img1)，

print(CovD.Get_Distance(T,T1))，
