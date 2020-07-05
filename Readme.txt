For matlab version 9.4 (R2018a) or higher

English part:
I didn�t need to draw such a strange thing, but even for something almost esoteric, but, it seems, it didn�t go any further, however, I still had the function to draw nice, but very strange things, like 22.jpg and 43.jpg.
The RorSpic.m function draws exactly one picture with the given parameters.
The PicIt.m function creates a whole family of images.
Both of them can draw a circle, a square with an equal distance between points, or a square with an equal angular distance between points.
The function is called like this:
PicIt (N, n, m, h, variant, papka)
Where:
variant = 1 - in a circle
variant = 2 - squared
variant = 3 - in a squared circle
N is the number of points on the circle (1); on the side of the square (2); on stretched
in a square circle (3)
n is the minimum multiplication factor
m - maximum multiplication factor
h is the step of changing the multiplication coefficient
papka - optional parameter, immediately puts the picture in an existing folder
For example: PicIt (100,2,100,1,2); PicIt (10,2,25,1,2, 'var2 N = 10 \');
Moreover, for variant = 2, the total number of points is 4 (N-1), and for the rest, just N
Therefore, 396 corresponds to 100, and 100 - 26, it is almost not scary. Almost.


������� �����:
��������� ����� �������� ����� ���� ����� �� ���, � ���� ��� ����-�� ���� �� �� ��������������, ��, �����, ������ ���� � �� �����, ������, � ���� �������� ������� ��� ��������� �����������, �� ����� ������� ����, ��� 22.jpg � 43.jpg.
������� RorSpic.m ������������ ����� ���� �������� � ��������� �����������.
������� PicIt.m ������� ����� ��������� �����������.
��� ��� ����� ���������� ����, ������� � ������ ����������� ����� ������� ��� ������� � ������ ������� ����������� ����� �������.
���������� ������� ���:
PicIt( N,n,m,h,variant, papka)
���: 
variant = 1 - � �����
variant = 2 - � ��������
variant = 3 - � ���������� � ������� �����
N - ���������� ����� �� ����� (1); �� ������� �������� (2); �� ����������
� ������� ����� (3)
n - ����������� ����������� ���������
m - ������������ ����������� ���������
h - ��� ��������� ������������ ���������
papka - �������������� ��������, ����� ������ ������� � ��� ������������ �����
��������: PicIt(100,2,100,1,2);  PicIt(10,2,25,1,2,'var2 N=10\');
��� ���� ��� variant = 2 ����� ���������� ����� ��� 4(N-1), � ��� ��������� ������ N
������� 396 ������������� 100, � 100 - 26, ��� ����� �� �������. ��, �����.