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

Step6: Shadow
----------
* point�������� light �������� intersection�� �� �� �� ����Ͽ� shadow ����
</br><img src="/TinyRayTracer/Img/Step6.png" width="540" height="960"></img>

Step7: Reflection
----------
* dir�� refelction �������� recursive�ϰ� ���� ��� �ݻ� ȿ�� ����

Step8: Refraction
----------
* Snell's law�� ����Ͽ� ���� ȿ�� ����
</br><img src="/TinyRayTracer/Img/Step8.jpg" width="540" height="960"></img>

Step9 : Add checkerboard
----------
* ����, ����� ���� ���� �̿��Ͽ� checkerboard ��鿡 ���� interection�� �߰� ���