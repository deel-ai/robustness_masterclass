# 🚀 Welcome to the **Robustness DEEL Master Class** !

#When a Machine Learning (ML) model is deployed, we may perform inference on a wide variety of data, in particular data the model has not been trained to predict on, thus producing erroneous or even nonsense predictions. *Out-of-Distribution (OOD) Detection* seeks precisely to detect this data, so that we avoid performing inference on it, or we warn the user about the untrustworhiness of the model predictions. *Post-hoc OOD detection* is a series of OOD detection techniques that use a trained ML model in order to detect OOD data, without changing the predictive model's weights or training auxiliar model.

This repository gathers materials from the DEEL master class to acquire theoretical and practical knowledge about Robust by-design models and training . Through these resources, you will discover how to train a 1-Lipschitz neural network, explore the robustness-accuracy tradeoff. You will learn to transform a classical Torch neural network into a TorchLip one, and develop the skills to leran and enhance robustness for real-world applications.

## 👨‍🎓 Tutorial Notebooks

This repository contains the tutorial notebooks for the following topics:

-

-

-

You can either work locally by cloning the project or open the notebooks following the colab links.

## 🐾 Installation

To get started with this tutorial, you have two options:


#### Option 1: Using Google Colab (Recommended)

If you have access to Google Colab, you can run this project directly in your web browser without needing to install anything locally. 

1. **Sign in to Google Colab**: Ensure you have a Google account to sign in.
2. **Open the Colab Notebook**: Open the Colab notebook links (see below).
3. **Install Dependencies in Colab**: The notebook will install all required packages in Colab’s environment.

This option is ideal if Colab is accessible to you.


#### Option 2: Local Installation (If Colab Access is Unavailable)

If access to Google Colab is restricted or unavailable, follow these steps to install the project locally:

1. **Clone the repository:**
```bash
git clone https://github.com/deel-ai/uq-masterclass.git
cd uq-masterclass
```
2. **Create a virtual environment:**
```bash
python -m virtualenv venv-masterclass
```
3. **Activate the virtual environment:**
    * On windows:
    ```bash
    venv-masterclass\Scripts\activate
    ```
    * On macOS/Linux:
    ```bash
    source venv-masterclass/bin/activate
    ```

4. **Install the required packages:**

```bash
pip install -r requirements.txt
```
5. **Add the virtual environment to Jupyter as a new kernel:**

```bash
python -m ipykernel install --user --name=venv-masterclass"
```

6. **Launch Jupyter Notebook:**

```bash
jupyter notebook
```

In Jupyter, you can select the newly created kernel Python (`venv-masterclass`) from the kernel options.


## 📖 Completed Notebooks

If you want to check your work, you can find all solutions in the **"completed_notebooks"** folder. Each file in this folder corresponds to the respective tutorial notebook. Feel free to review these solutions as you progress through the exercises.


## 🔗 Links
- [<img src="https://github.githubassets.com/images/icons/emoji/octocat.png" width=20> TORCHLIP Github](https://github.com/deel-ai/torchlip)
- [📘 TORCHLIP Documentation](https://deel-ai.github.io/deel-torchlip/)

## 🙏 Acknowledgments

<img align="right" src="https://www.deel.ai/wp-content/uploads/2021/05/logo-DEEL.png" width="25%">
This project received funding from the French ”Investing for the Future – PIA3” program within the Artificial and Natural Intelligence Toulouse Institute (ANITI). The authors gratefully acknowledge the support of the <a href="https://www.deel.ai/"> DEEL </a> project.
