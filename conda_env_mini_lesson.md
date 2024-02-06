# Conda environment mini-lesson and setup

Hello, here is a short summary on how to create the conda environment for our project :)

1. If you are on Windows, open the `anaconda console`. If you are on MacOS or Linux, open the `terminal`

2. Create a new conda environment named `python-project` with Python 3.10 kernel:

    ```bash
    conda create -n python-project python=3.10
    ```

3. Activate our new environment:

    ```bash
    conda activate python-project
    ```

4. Install the following packages: `numpy`, `matplotlib`, `scipy`, `pandas`, `h5py`, and `jupyterlab`. Note that to install `jupyterlab`, we must specify the channel by using `-c conda-forge`.

    ```bash
    conda install numpy matplotlib scipy pandas h5py
    conda install -c conda-forge jupyterlab
    ```

5. Open Jupyter:

    ```bash
    jupyter lab
    ```

6. Create a jupyter notebook and run `import h5py` to test the environment.

7. To kill the kernel, go to the console/terminal and press `Ctrl-c`.

8. To deactivate conda environment, type

    ```bash
    conda deactivate
    ```

9. Next time you work on the project, simply open the anaconda console (Windows) or terminal (MacOS), activate environment and open jupyter lab:

    ```bash
    conda activate python-project
    jupyter lab
    ```