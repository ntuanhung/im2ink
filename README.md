# im2ink
This project aims to reconstruct the offline character images back to online handwritten trajectories using an encoder-decoder with attention and GMM

## Recovered samples
1. Successful recovered sample

![Attention successful recovery](https://github.com/ntuanhung/im2ink/blob/master/demo_gif/unsucess_2.gif)

2. Unsuccessful recovered sample

![Attention successful recovery](https://github.com/ntuanhung/im2ink/blob/master/demo_gif/unsucess_1.gif)

3. Unnatural recorved samples
Although the following samples are successfully recovered, their online trajectories consist of more points than the original ones.

Original &nbsp; &nbsp; &nbsp; Recovered trajectories


![Original speed](https://github.com/ntuanhung/im2ink/blob/master/demo_gif/unnatural_2_org.gif)
&nbsp; &nbsp; &nbsp;![Recovery speed](https://github.com/ntuanhung/im2ink/blob/master/demo_gif/unnatural_2_rec.gif)


![Original speed](https://github.com/ntuanhung/im2ink/blob/master/demo_gif/unnatural_3_org.gif)
&nbsp; &nbsp; &nbsp;![Recovery speed](https://github.com/ntuanhung/im2ink/blob/master/demo_gif/unnatural_3_rec.gif)
