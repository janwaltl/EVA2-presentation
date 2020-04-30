# EVA2-presentation
Presentation slides and generated data for Evolutionary Algorithms II about Estimation of Distribution Algorithms.

# Presentation slides
- The presentation slides should also be present [here](https://docs.google.com/presentation/d/1moMqPstjdawwnlx5uaEdFxFht8BS38UN3B1u9_0dS_A/edit?usp=sharing).
- Sorry fot not showing (the better) half of them.
# Notebook
The notebook contains all the necessary code to recreate the graphs contained in the presentation as well as the source code for a few algorithms. I recommend running it directly in Google Colab:
 - [Colab](https://colab.research.google.com/drive/1G-r_jzoEEWf9HnYpivPDv0cStkrF9KSL) (Graphs must be rerun, it does not save them :/ )
 - Do not forget to upload already generated `.npy` data in order to avoid generating them, it takes a while.
 - If you do not see any graphs after running the cells, try running them one by one. At least my Opera browser gets very laggy and refuses to show some if I run them all via "Run all" button.
 - The sliders are little laggy too as the tutorials from plotly did not work.
 - Feel free to point any mistakes.

## VAE
I did try to implement simple VAE-Q version, but it does not work very well, I did not use Tournament selection, maybe that's why? Or I made some mistakes somewhere.
## Sudoku
Also did not work very well, gets stuck in local maxima all the time. But the model and encoding is not very good. Definitely see this presentation https://www.slideshare.net/InformaticaUCM/dealing-with-constraints-in-estimation-of-distribution-algorithms for more information on constrained models.
