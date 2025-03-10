# CH calling pipeline 

This is the CH calling pipeline used in the "Risk of clonal hematopoiesis in families exposed to radiation following the Chornobyl accident" manuscript. 
The pipeline was developed by the [Bolton Lab](https://www.kellyboltonlab.org/). Please refer to the [ArCH manuscript](https://academic.oup.com/bioinformatics/article/40/4/btae121/7629130) and the [ArCH GitHub repository](https://github.com/kbolton-lab/ArCH) for more information. 

# Annotation and model files
- The annotation files can be found under WDL/AnnotatePD\ Files/ in the [ArCH pipeline v1.0.0](https://github.com/kbolton-lab/ArCH/releases/tag/v1.0.0)
- The xgb_model files can be found under xgb_model/ in the [ArCH pipeline v1.0.0](https://github.com/kbolton-lab/ArCH/releases/tag/v1.0.0)

# Workflow files and scripts  
- WDL/terra_pipline.wdl was run on all samples for alignment, variant calling 
- WDL/archer_annotate.wdl was then run on all samples for annotation
- PostPipelineFilters.R was used for generating filtered list of variants

