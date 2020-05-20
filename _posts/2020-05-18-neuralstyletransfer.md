---
toc: true
layout: post
description: Desc - Render F1 car images in the style of Picasso
categories: [markdown]
title: Style Transfer using Neural Networks
---
As a workflow exercise I attempted to render the image of an F1 car in the style of Picasso!
I used images of recent Racing Point and Renault F1 cars.

I trained it on Google Colab using both Tensorflow and Pytorch (separately ofcourse!)

The resulting images were very similar.

[Look here for Setup and Results](https://github.com/DexterDSilva/f1car-styletransfer)

```
Loss = distance((style(reference_image) - style(generated_image)) +  
        (distance(content(original_image) - content(generated_image))
        
original_image = a picture of an F1 car 
reference_image = a style image such as Picasso

```
> ##### Note to self: Put results on this page too.
---

![](/images/aero-robot-with-logo-small.png)![](/images/onpointai-logo-small.png)
