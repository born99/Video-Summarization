The implementation of the paper "Video Summarization using Deep Semantic Features" in ACCV'16 [[arXiv](arxiv.org/abs/1609.08758)]


### Install dependency

	
Requirements:
- numpy=1.11
- scipy
- scikit learn
- chainer=2.0

Optional:
- scikit video ( for exporting video )


### Download dataset and model parameters

To test the model in the paper, download a `data.zip` [**HERE**](https://www.dropbox.com/s/zxp8dq18t0tqlk2/data.zip?dl=0) and extract it in the folder `vsum_dsf`.

The demo performs video summarization on the SumMe dataset ([project page](https://people.ee.ethz.ch/~gyglim/vsum/index.php)).

You can download the dataset as: 

	cd data/summe
	wget https://data.vision.ee.ethz.ch/cvl/SumMe/SumMe.zip
	unzip SumMe.zip

## Example


	python script/summarize.py
	python script/evaluate.py results/summe/smt_feat