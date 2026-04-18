# LEAF++

LEAF++: Trait-Annotated Essay Feedback Dataset with Validation of Trait Scores via LLMs

## Dataset Description

The LEAF++ dataset is an extended version of the original LEAF dataset by Behzad et al. (2024) ([Paper](https://aclanthology.org/2024.naacl-short.36.pdf), [Dataset](https://github.com/shabnam-b/LEAF)), which previously included only free-form feedback collected from [EssayForum](https://essayforum.com). LEAF++ enriches the original dataset with detailed trait-level annotations, providing scores across multiple dimensions. The traits included in the dataset are:

- <code>alignment_with_topic</code>: Score regarding alignment with the topic (response to the topic).  
- <code>spelling_grammar_style</code>: Score on spelling, grammar, and writing style issues.  
- <code>clarity_of_view_point</code>: Score on the clarity of the author's point of view.  
- <code>arguments_supporting_details</code>: Score on arguments and supporting details in the essay.  

## Citation
If you find this work useful for your work, please cite our paper:

```bibtex
@ARTICLE{11303736,
  author={Misgna, Haile and On, Byung-Won and Lee, Ingyu and Sang Choi, Gyu},
  journal={IEEE Access}, 
  title={LEAF++: Trait-Annotated Essay Feedback Dataset With Validation of Trait Scores via LLMs}, 
  year={2026},
  volume={14},
  number={},
  pages={9062-9082},
  keywords={Annotations;Transformers;Grammar;Training;Standards;Reliability;Iterative methods;Distance measurement;Computational modeling;Coherence;Automated feedback generation;trait score validation using LLM;automated feedback revision;automated essay revision},
  doi={10.1109/ACCESS.2025.3646052}}


