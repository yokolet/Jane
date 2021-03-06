# Becoming Jane by Deep Learning

This repositry holds files for the Machine Learning Capstone Project.
The project experiments RNN using Tensorflow and generates a sequence of
words after training. The training is done by Jane Austen's novels.
For training and validation, Pride and Prejudice, Sense and
Sensibility, and Emma are used. For test, the first part of Persuation
will be used. All data are from <http://www.fullbooks.com/>.

The project report is [Report.pdf](Report.pdf).

### TensorFlow

TensorFlow must be installed prior to run the Python notebook. For this
porject, Tensorflow was installed using Anaconda's pip. As of October
2016, Anaconda installs Tensorflow version 0.9. The code in notebook
works on this version.

To use TensorFlow, its environment should be enabled before hitting
jupyter command.

```bash
source activate tensorflow
```

Some libraries must be installed after TensorFlow enviroment starts.
Even though Anaconda has those already, there may be a case the
libraries need to be installed again.


### Files

This repository has the files below:

```
.
├── Jane-RNN.html
├── Jane-RNN.ipynb
├── Jane-Sampling.html
├── Jane-Sampling.ipynb
├── README.md
├── Report.pdf
├── data
│   ├── test.txt
│   ├── train.txt
│   └── valid.txt
└── saved                <--- not pushed to the repo
    ├── checkpoint
    ├── model.ckpt
    ├── model.ckpt.meta
```

- README.me : this file
- Report.pdf : project report
- Jane-RNN.html : HTML export of Jane-RNN notebook
- Jane-RNN.ipynb : Python notebook for training
- Jane-Sampling.html : HTML export of Jane-Sampling notebook
- Jane-Sampling.ipynb : Python notebook for sampling
- data : input data directory
- saved : not pushed to the repository, automatically created once the training runs
