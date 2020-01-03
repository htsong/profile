***************
课程教学(Teaching)
***************

.. plot:: _code/sinx.py
    :include-source:

    添加一些描述(可选的)

.. plot::

    import matplotlib.pyplot as plt
    import numpy as np

    x = np.linspace(-6, 6, 1000)
    y = np.sin(x)
    plt.plot(x, y)
    plt.title("sin(x)")

    # 最后必须要调用 show 方法, 才能显示
    plt.show()


教学相关内容
