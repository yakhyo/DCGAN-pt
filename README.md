## Deep Convolutional Generative Adversarial Networks


Implementation of **Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks** using PyTorch | [Paper](https://arxiv.org/abs/1511.06434)
**Train:**
* Modify `config.py` file to specify `dataset, batch_size, img_size, ...`
* Run `python main.py`

<br>

**Results after 3 epochs:**

![](assets/img.png)


After every 100 training iterations, the files `real_samples.png` and `fake_samples.png` are written to disk with the samples from the generative model.

After every epoch, models are saved to: `netG_epoch_%d.pth` and `netD_epoch_%d.pth`

**Reference**
* https://github.com/pytorch/
