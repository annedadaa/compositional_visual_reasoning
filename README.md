
# Compositional Visual Reasoning

Repository for the project on compositional visual reasoning in large (visual) language models.

![Alt text](GQA_output_example.jpg?raw=true "Title")


### To get started

Clone this repository

```
git clone https://github.com/annedadaa/compositional_visual_reasoning.git
```

Go to viper directory
```
cd viper
```

Follow the installation instruction from [Viper](https://github.com/cvlab-columbia/viper/tree/09fe3465224766860d8dd4ec48db942f22b05092)

### Reproducibility

Since our project is primarily focused on reproducing ViperGPT's approach (Surís et al., 2023), the main code is located in the _viper_ directory. However, we made some modifications to run the code, so you should place all the files from this repository into the _viper_ folder (the original names have been preserved).

Note: We used Vertex AI by Google and OpenAI to access large (Visual) Language Models. To use our implementation, you will need to sign up and set up access to these services from your virtual environment.

### Data

We present a few samples from different datasets in the _data_ folder. These samples are primarily for demonstration purposes, but their structure mirrors that used in our experiments.

### References

Dídac Surís, Sachit Menon, and Carl Vondrick. 2023. Vipergpt: Visual inference via python execution for reasoning. In Proceedings of the IEEE/CVF Interna- tional Conference on Computer Vision, pages 11888– 11898.

