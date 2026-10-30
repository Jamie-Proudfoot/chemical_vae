Important note:
You must add the `ZINC_Michael_ordered.csv.gz` file from https://github.com//the-grayson-group/ZINC-Michael_generative to this directory (this is a private repository that stores training data)

To run chemvae training:  
(1st activate chemvae environment)  
Then cd to `chemical_vae/models/<mymodel>`: 

`nohup python -m chemvae.train_vae > train_vae.out &`

(make sure that the GPU is not being used by someone else first with nvidia-smi)