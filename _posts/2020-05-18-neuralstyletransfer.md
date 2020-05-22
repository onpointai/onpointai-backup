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
The trained model is implemented using a webapp. The user is asked to select an image and the analysis is displayed.
---
Here are the examples:
![]({{site.baseurl}}/images/rp-style-transfer.png "Racing Point")
![]({{site.baseurl}}/images/renault-style-transfer.png "Renault")

[Look here for Setup, code and Results](https://github.com/DexterDSilva/f1car-styletransfer)

```
Loss = distance((style(reference_image) - style(generated_image)) +  
        (distance(content(original_image) - content(generated_image))
        
original_image = a picture of an F1 car 
reference_image = a style image such as Picasso

```
---
![]({{site.baseurl}}/images/onpointai_logo.gif)
