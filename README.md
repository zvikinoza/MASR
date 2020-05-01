# Mini Automatic Speech Recognition 
## Using Fourier transforms and CNN (VGG like) architecture

![ ](https://github.com/zvikiNozadze/MASR/blob/master/imgs/number_spectogram.png)

EDA and modeling on ≈150 samples of sounds speaking numbers form 1 to 5 recorded by 10 people.
<br>
<br>Accyracy on large (>10k) dataset: 94%. 
<br>Accyracy on given small  dataset: 93% 
<br>
Task was more or less chalenging because of small dataset.  
<br>
Augmentation techniques:
*   increase/decrease pitch
*   increase/decrease speed
*   stretching
*   frequency and time masking
*   white noice injection
*   time shifting
*   overlay 2 samples (quiet and louder)
*   pre/post noise padding  
<br>
Splitting data is done by speakers 5-5.
<br>
<br>
Training graph :
<br>

![ ]( https://github.com/zvikiNozadze/MASR/blob/master/imgs/acc_graph.png)
