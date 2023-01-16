# Chaos

```
                           .oMc
                        .MMMMMP
                      .MM888MM
....                .MM88888MP
MMMMMMMMb.         d8MM8tt8MM
 MM88888MMMMc `:' dMME8ttt8MM
  MM88tt888EMMc:dMM8E88tt88MP
   MM8ttt888EEM8MMEEE8E888MC
   `MM888t8EEEM8MMEEE8t8888Mb
    "MM88888tEM8"MME88ttt88MM
     dM88ttt8EM8"MMM888ttt8MM
     MM8ttt88MM" " "MMNICKMM"
     3M88888MM"      "MMMP"
      "MNICKM"
```

A deterministic and bounded system is chaotic if tiny perturbations to the system get [exponentially amplified](https://www.nature.com/articles/s42003-019-0715-9). This is sometimes called the [butterfly effect](https://en.wikipedia.org/wiki/Butterfly_effect). The idea that small causes may have large effects in weather was recognized early on by French mathematician and engineer [Henri Poincaré](https://en.wikipedia.org/wiki/Henri_Poincar%C3%A9).

Veratasium has published an excellent [introdution video](https://youtu.be/fDek6cYijxI) to Chaos Theory. The video gives the history of the chaotic case discovered by meteorologist Edward Lorenz, where a small difference in rounding in an atmosperic model caused the model to evolve radically different from almost identical initial conditions.

This repo is my journey to understand Chaos Theory better, but from a very practical point of view. I want to learn the following.

- How to determine whether a fully simulated system (i.e. a set of equations) is [formally chaotic](https://www.maths.usyd.edu.au/u/gottwald/preprints/chaos1.pdf).
- Discover and write some [code](https://alpha.iodide.io/notebooks/34/?viewMode=report) that covers this topic.
- How to determine if [observational data](https://www.nature.com/articles/s42003-019-0715-9) comes from a chaotic real-world system.
    - Understand [permutation entropy](https://www.aptech.com/blog/permutation-entropy/), which helps understand how deterministic/stochastic a data-generating process is
    - Understand the [Schreiber algorithm](https://www.worldscientific.com/doi/abs/10.1142/S0218127491000403) and [denoising](https://arxiv.org/pdf/nlin/0002028.pdf)
## Code in this repo

Check out the [3D simulator](./3d-simulator.ipynb), e.g. of the lorenz attractor.
