For matlab version 9.4 (R2018a) or higher

English part:
I didn’t need to draw such a strange thing, but even for something almost esoteric, but, it seems, it didn’t go any further, however, I still had the function to draw nice, but very strange things, like 22.jpg and 43.jpg.
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


Русская часть:
Отрисовка такой странной штуки была нужна не мне, а даже для чего-то чуть ли не эзотерического, но, вроде, дальше дело и не пошло, однако, у меня осталась функция для рисования симпатичных, но очень страных штук, как 22.jpg и 43.jpg.
Функция RorSpic.m отрисовывает ровно одну картинку с заданными параметрами.
Функция PicIt.m создает целое семейство изображений.
Обе они могут нарисовать круг, квадрат с равным расстоянием между точками или квадрат с равным угловым расстоянием между точками.
Вызывается функция так:
PicIt( N,n,m,h,variant, papka)
где: 
variant = 1 - в круге
variant = 2 - в квадрате
variant = 3 - в растянутом в квадрат круге
N - количество точек на круге (1); на стороне квадрата (2); на растянутом
в квадрат круге (3)
n - минимальный коэффициент умножения
m - максимальный коэффициент умножения
h - шаг изменения коэффициента умножения
papka - необязательный параметр, сразу кладет рисунок в уже существующую папку
Например: PicIt(100,2,100,1,2);  PicIt(10,2,25,1,2,'var2 N=10\');
При этом для variant = 2 общее количество точек это 4(N-1), а для остальных просто N
Поэтому 396 соответствует 100, а 100 - 26, это почти не страшно. Ну, почти.