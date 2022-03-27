# barataria
> _El lugar donde se desvanecen los sueños_

Impresionante la librería/proyecto [`fastai`](https://www.fast.ai/). El [libro](https://course.fast.ai/) en [versión notebook](https://github.com/fastai/course20/tree/master/) es muy ameno e informativo. 

La GPU quedó probada a satistacción. `pytorch` se demuestra un entorno mas fiable que `tensorflow` (estarán más orientados a TPU, que viene a ser un invento suyo??).

Decepcionante no haber conseguido ejecutar ninguna de las versiones del `AWD-LSTM` preentrenado.

Puede ser muy interesante la librería [`IpExperiments`](https://github.com/stas00/ipyexperiments) para ajustar con garantías el *batch_size* y/o el tamaño del modelo.

Otro hallazgo puede ser [`numba`](https://numba.readthedocs.io/en/stable/user/jit.html), que permite gestionar la GPU desde python 
