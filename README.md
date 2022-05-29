# Vision Transformer 

Research upon visual transformers on small datasets

### Models:

Road sign db:  

    * vit base 224 - dnoe
    * vit base 384 - done
    * vit base 224 with cosomethign loss  
    * DERT / YOLOS

Vehicle plate db:

    * vit base 224 - done
    * vit base 224 with cosomethign loss - in the working
        * doesn't work so I try: adding a var C, 
        * ignore the bbox loss if similarity == -1 (basically making it 0)
        * using predefined cosingembeddingloss
