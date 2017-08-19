A Jupyter kernel for /usr/bin/dc

This requires IPython 3.

To install::

    pip install dc_kernel
    python -m dc_kernel.install

To use it, run one of:

.. code:: shell

    jupyter notebook
    # In the notebook interface, select Bash from the 'New' menu
    jupyter qtconsole --kernel dc
    jupyter console --kernel dc

For details of how this works, see the Jupyter docs on `wrapper kernels
<http://jupyter-client.readthedocs.org/en/latest/wrapperkernels.html>`_, and
Pexpect's docs on the `replwrap module
<http://pexpect.readthedocs.org/en/latest/api/replwrap.html>`_
