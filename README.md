# segmind/SSD-1B img2img Cog model

This is an implementation of the [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i image=@wolf.png -i prompt="a wolf with pink and blue fur"

## Example:

"a wolf with pink and blue fur"

![alt text](output.png)
