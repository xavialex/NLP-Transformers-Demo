# NLP Transformers Demo

Deep Learning architectures based in Transformers ([Vaswani et al., 2017, Attention is all you need](https://arxiv.org/abs/1706.03762)) have demonstrated state of the art results in Natural Language Processing (NLP) and are quickly jumping to other fields ([DEtection TRansformer](https://github.com/facebookresearch/detr)). This notebook aims to demonstrate the power and easiness of use of the [HuggingFace Pipelines](https://huggingface.co/transformers/main_classes/pipelines.html), which can be quickly deployed to achieve outstanding results in several NLP tasks, including Sentiment Classification, Text Generation, Summarization and more.

## Dependencies

Running the application can be done following the instructions above:

1. To create a Python Virtual Environment (virtualenv) to run the code, type:

    ```python3 -m venv my-env```
    
2. Activate the new environment:
    * Windows: ```my-env\Scripts\activate.bat```
    * macOS and Linux: ```source my-env/bin/activate``` 

3. Install all the dependencies from *requirements.txt*:

    ```pip install -r requirements.txt```
    
4. To make the environment visible as a kernel for Jupyter, type:

    ```python -m ipykernel install --name=my-env```
    
## Use

To run the notebook, with the environment activated (see [Dependencies](#Dependencies) section), create an IPyKernel running this instruction:

```python -m ipykernel install --user --name=myenv```

Check if your kernel was created by listing them:

```jupyter kernelspec list```

Finally, inside the notebook, and from a base environment where *Jupyter* is installed, select your kernel to make all packages needed for the project ready to import.