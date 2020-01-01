# TinyRayTracer
https://github.com/ssloy/tinyraytracer/wiki/Part-1:-understandable-raytracing

Step1: �̹��� �����ϱ�
-----------
* Geometry / �̹��� ���� �ڵ�
* Geometry.h���� 2����/3����/4���� ���� �� �� ������ �����ε� ���ǵǾ� ����
* main.cpp������ ��� �̹����� std::vector<Vec3f>�� �����, �̸� ppm���Ϸ� ���

Step2: �� �������ϱ�
----------
* Ray Intersect
* Cast Ray
* Calculate dir for each pixel
</br><img src="/TinyRayTracer/Img/Step2.png" width="540" height="960"></img>

Step3: �� ������ �������ϱ�
----------
* ���� ��� �߰�
* �տ� �ִ� ������ ĥ�������� ���� �߰�

Step4: Lighting
----------
* normal�� light vector�� dot product�� intensity ���

Step5: Specular Lighting
----------
* Material �߰�
* specular lighting ���