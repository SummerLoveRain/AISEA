.. SciML_RP documentation master file, created by
   sphinx-quickstart on Sun Jun  4 16:33:14 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SciNEA's Team!
====================================

**SciNEA: Scientific Computing for Nuclear Engineering Applications**

Team Members
====================================

.. .. |QiaolinHe| image:: ./_static/prof/QiaolinHe.png
..                     :scale: 119
.. .. |ShiquanZhang| image:: ./_static/prof/ShiquanZhang.png
..                     :scale: 30
.. .. |HelinGong| image:: ./_static/prof/HelinGong.png
..                     :scale: 14

.. |QiaolinHe| image:: ./_static/prof/QiaolinHe.png
                    :width: 206
                    :height: 289
.. |ShiquanZhang| image:: ./_static/prof/ShiquanZhang.png
                    :width: 206
                    :height: 289
.. |HelinGong| image:: ./_static/prof/HelinGong.png
                    :width: 206
                    :height: 289

.. |YuYang| image:: ./_static/stu/YuYang.png
                    :width: 167
                    :height: 213
.. |QihongYang| image:: ./_static/stu/QihongYang.png
                    :width: 167
                    :height: 213
.. |ShupeiYu| image:: ./_static/stu/ShupeiYu.png
                    :width: 167
                    :height: 213
.. |XufanChen| image:: ./_static/stu/XufanChen.png
                    :width: 167
                    :height: 213


.. =================      ==================  ================
.. |QiaolinHe|            |ShiquanZhang|      |HelinGong|
.. =================      ==================  ================
.. Prof. Qiaolin He       A.P. Shiquan Zhang  A.P. Helin Gong
.. =================      ==================  ================

.. _Prof. Qiaolin He: https://math.scu.edu.cn/info/1013/3065.htm
.. _A.P. Shiquan Zhang: https://math.scu.edu.cn/info/1013/3056.htm
.. _A.P. Helin Gong: https://speit.sjtu.edu.cn/faculty/team-152.html


+--------------------+---------------------+--------------------+
|    |QiaolinHe|     |  |ShiquanZhang|     |     |HelinGong|    |
+--------------------+---------------------+--------------------+
| `Prof. Qiaolin He`_|`A.P. Shiquan Zhang`_| `A.P. Helin Gong`_ |
+--------------------+---------------------+--------------------+


.. _PhD. Yu Yang: https://github.com/YangYuSCU
.. _PhD. Qihong Yang: https://github.com/SummerLoveRain

+-------------------+---------------------+--------------------+--------------------+
|     |YuYang|      |     |QihongYang|    |    |ShupeiYu|      |     |XufanChen|    |
+-------------------+---------------------+--------------------+--------------------+
|`PhD. Yu Yang`_    | `PhD. Qihong Yang`_ |   M.S. Shupei Yu   |   M.S. Xufan Chen  |
+-------------------+---------------------+--------------------+--------------------+

Research Fields
====================================

**Research Fields:**

 | **Scientific Computing + Maching Learning**

 | **Numerical Methods of Fluid Mechanics**

 | **Construction and Analysis of High-Precision Finite Element Method**

 | **Fast Algorithms for Solving Linear Equations**

 | **Model Reduction method and Machine Learning Methods**

 | **Modeling and Reconstruction based on Experimental Data**

 | **...**

Members of the team were awarded **the second prize of natural science by the Ministry of Education in 2020**, undertook **three research projects of the National Natural Science Foundation of China**, presided over **two sub-projects of the National Key Research and Development Program** and **one pre-research project of the installation and development**, published more than 50 papers in well-known national journals such as JCP and SIAM Multiscale Model and Simulation, and granted one patent. 

Recently, them have successfully completed the development of a module for 3D ground stress modelling and display of shale gas; designed an efficient pre-processing method for rapid solution of large-scale linear equation systems for subsea oil field development, improving the simulation efficiency; established a reconstruction model and algorithm based on partial observation data of reactors and fuel rods, realizing data reconstruction and inversion of physical parameters.


.. |Boat| image:: ./_static/nuclear/boat.png
                  :width: 257
                  :height: 149
.. |Base| image:: ./_static/nuclear/base.png
                  :width: 257
                  :height: 149
.. |Core| image:: ./_static/nuclear/core.png
                  :width: 257
                  :height: 149

+------------+------------+---------------+
|  |Boat|    |  |Base|    |     |Core|    |
+------------+------------+---------------+

Some Problems and Results
====================================

DEPINN: A Data-Enabled Physics-Informed Neural Network
----

.. |DEPINN| image:: ./_static/results/DEPINN.png
.. |1D_circle| image:: ./_static/results/1D_circle.png
.. |2D_cylinder| image:: ./_static/results/2D_cylinder.png
.. |IAEA| image:: ./_static/results/IAEA.png

+-------------------------+---------------------------+
||1D_circle|              |  |2D_cylinder|            |
+-------------------------+---------------------------+
|finite spherical reactor |finite cylindrical reactor |
+-------------------------+---------------------------+


+----------------------------------------------------+
||IAEA|                                              |
+----------------------------------------------------+
|The 2D IAEA Benchmark Problem (IBP) (1977) modeled  |
|by two-dimension two-group diffusion equations,     |
|which was adapted from a practical nuclear reactor. |
+----------------------------------------------------+


+----------------------------------------------------+
||DEPINN|                                            |
+----------------------------------------------------+
|The process of solving the 2D IBP by DEPINN.        |
+----------------------------------------------------+

DEPINN: Uncertainty Analysis
----

.. |DEPINN_noise| image:: ./_static/results/DEPINN_noise.png

+----------------------------------------------------+
||DEPINN_noise|                                      |
+----------------------------------------------------+
|The process of solving parametric neutron diffusion |
|eigenvalue problems containing noisy data by DEPINN.|
+----------------------------------------------------+


.. |1D_circle_noise| image:: ./_static/results/noise_1.png
.. |2D_cylinder_noise| image:: ./_static/results/noise_2.png

+-----------------------------------------------------+
||1D_circle_noise|                                    |
+-----------------------------------------------------+
|finite spherical reactor: prediction 𝑢 from different|
|prior data noise scales. Interval loss is used in    |
|(a)(c) on the left, and SSE loss is used in (b)(d) on|
|the right. (a) 𝜎 = 0.05. (b) 𝜎 = 0.05. (c) 𝜎 = 0.1.  |
|(d) 𝜎 = 0.1.                                         |
+-----------------------------------------------------+
||2D_cylinder_noise|                                  |
+-----------------------------------------------------+
|finite cylindrical reactor: prediction 𝑢 from        |
|different prior data noise scales. Interval loss     |
|is used in (a)(c) on the left, and SSE loss is used  |
|in (b)(d) on the right. (a) 𝜎 = 0.05. (b) 𝜎 = 0.05.  |
|(c) 𝜎 = 0.1.  (d) 𝜎 = 0.1.                           |
+-----------------------------------------------------+

GIPMNN: Generalized Inverse Power Method Neural Network
----
At first, we present how to use the generalized inverse power method to solve the following Equation.

.. math::
      \boldsymbol{A} \boldsymbol{\phi} = \lambda \boldsymbol{B} \boldsymbol{\phi}

The key step we need to focus on is shown in the following Equation, where :math:`\mathbf{A}` and :math:`\mathbf{B}` are two matrices, :math:`\lambda_{k-1}` and :math:`\boldsymbol{\phi}_{k-1}` are the results of previous iteration. Therefore, :math:`\lambda_k` and :math:`\boldsymbol{\phi}_k`  are obtained by the following Equation.

.. math::
      &\boldsymbol{A} \boldsymbol{\phi}_k = \lambda_{k-1} \boldsymbol{B} \boldsymbol{\phi}_{k-1}, \\
      &\lambda_k = \frac{<\boldsymbol{A}\boldsymbol{\phi}_{k}, \boldsymbol{\phi}_{k}>}{<\boldsymbol{B}\boldsymbol{\phi}_{k}, \boldsymbol{\phi}_{k}>}

We use the neural network :math:`\mathcal{N}^{\theta}` to represent the approximated eigenvector :math:`\Phi`. The :math:`\mathcal{N}^{\theta}` is utilized to represent the neural network and the eigenfunction :math:`\phi` can be denoted as :math:`\Phi=\mathcal{N}^{\theta}`. In GIPMNN, the following Equation is an analogue to the key code of generalized inverse power method, where :math:`\mathcal{L}` and :math:`\mathcal{Q}` are linear differential operators which are implemented by AD rather than specially discretized matrices. The same as the generalized inverse power method, we will record the results :math:`\lambda_{k-1}` of previous iteration. One difference with the generalized inverse power method is that instead of recording :math:`\boldsymbol{\phi}_{k-1}`, we record :math:`\mathcal{Q}\Phi_{k-1}`. It is worth noting that :math:`\Phi_{k-1}` is the eigenfunction represented by the neural network in :math:`(k-1)`-th iteration and :math:`\mathcal{Q}\Phi_{k-1}` is realized by AD. In :math:`k`-th iteration, we directly compute :math:`\Phi_{k}` through the neural network, that is, :math:`\Phi_k = \mathcal{N}^{\theta}`, and calculate :math:`\mathcal{L}\Phi_{k}` by AD. 

.. math::
      &\mathcal{L} \Phi_{k} = \lambda_{k-1} \mathcal{Q} \Phi_{k-1}, \\
      &\lambda_k = \frac{<\mathcal{L}\Phi_{k}, \Phi_{k}>}{<\mathcal{Q}\Phi_{k}, \Phi_{k}>}

Since we attain :math:`\Phi_k` directly through the neural network instead of solving the equation :math:`\mathcal{L} \Phi_{k} = \lambda_{k-1} \mathcal{Q} \Phi_{k-1}`, we define the loss function :math:`Loss_{gipmnn}` in the following Equation to propel the neural network to learn :math:`\Phi_k`. When the neural network gets convergence, we obtain the smallest eigenvalue and the associated eigenfunction expressed by the neural network.

.. math::
      Loss_{gipmnn} = \sum_{i=1}^N \lvert \mathcal{L} \Phi_k(\boldsymbol{x}_i) - \lambda_{k-1} \mathcal{Q} \Phi_{k-1}(\boldsymbol{x}_i) \rvert ^2


PC-GIPMNN: Physics-Constrained GIPMNN
----

.. |PC_GIPMNN| image:: ./_static/results/PC_GIPMNN.png

+----------------------------------------------------+
||PC_GIPMNN|                                         |
+----------------------------------------------------+
|Illustration of PC-GIPMNN architecture diagram.     |
|There are multiple neurons in the output layer      |
|which denote the eigenfunctions in different        |
|sub-domains.                                        |
+----------------------------------------------------+


Publications
====================================

DEPINN
----

#. Yu Yang, Helin Gong, Shiquan Zhang, Qihong Yang, Zhang Chen, Qiaolin He, Qing Li, `A data-enabled physics-informed neural network with comprehensive numerical study on solving neutron diffusion eigenvalue problems <https://www.sciencedirect.com/science/article/abs/pii/S0306454922006867?via%3Dihub>`_, *Annals of Nuclear Energy*. 2023, 183:109656
#. Yu Yang, Helin Gong, Qiaolin He, Qihong Yang, Yangtao Deng and Shiquan Zhang, `On the uncertainty analysis of the data-enabled physics-informed neural network for solving neutron diffusion eigenvalue problem <https://arxiv.org/abs/2303.08455>`_, *arXiv preprint arXiv:2302.04107*, 2023.

PMNN and IPMNN
----
#. Qihong Yang, Yangtao Deng, Yu Yang, Qiaolin He, Shiquan Zhang, `Neural Networks Based on Power Method and Inverse Power Method for Solving Linear Eigenvalue Problems <https://arxiv.org/abs/2209.11134>`_, *arXiv preprint arXiv:2209.11134*, 2022.

GIPMNN and PC-GIPMNN
----
#. Qihong Yang, Yu Yang, Yangtao Deng, Qiaolin He, Helin Gong, Shiquan Zhang, `A Physics-Constrained Neural Network for Solving Discontinuous Interface K-eigenvalue Problem with Application to Reactor Physics <https://arxiv.org/abs/2209.11134>`_, preprint, 2023


.. .. |SCUMath| image:: ./_static/scu/scu_math.jpg
..                   :width: 454
..                   :height: 87
.. .. |SPEIT| image:: ./_static/speit/speit.png
..                   :width: 527
..                   :height: 87
.. |SCUMath| image:: ./_static/scu/scu_math_red.png
                  :width: 380
                  :height: 60
.. |SPEIT| image:: ./_static/speit/speit.png
                  :width: 520
                  :height: 50

+--------------+------------+
|   |SCUMath|  | |SPEIT|    |
+--------------+------------+

.. .. toctree::
..    :maxdepth: 2
..    :caption: contents:

..    modules/team_members.rst
..    modules/research_fields.rst
..    modules/papers.rst


.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
