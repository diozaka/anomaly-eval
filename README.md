# anomaly-eval
This repository contains code for the paper:

> Erik Scharwächter and Emmanuel Müller: **"Statistical Evaluation of Anomaly Detectors for Sequences."**
> In: 6th ACM SIGKDD Workshop on Mining and Learning from Time Series (KDD MiLeTS 2020). [[arXiv preprint]](https://arxiv.org/abs/2008.05788)

**Abstract:** Although precision and recall are standard performance measures for anomaly detection, their statistical properties in sequential detection settings are poorly understood. In this work, we formalize a notion of precision and recall with temporal tolerance for point-based anomaly detection in sequential data. These measures are based on time-tolerant confusion matrices that may be used to compute time-tolerant variants of many other standard measures. However, care has to be taken to preserve interpretability. We perform a statistical simulation study to demonstrate that precision and recall may overestimate the performance of a detector, when computed with temporal tolerance. To alleviate this problem, we show how to obtain null distributions for the two measures to assess the statistical significance of reported results.

## Contact and Citation

* Corresponding author: [Erik Scharwächter](mailto:scharwaechter@bit-uni-bonn.de)
* Please cite our paper if you use or modify our code for your own work. Here's a `bibtex` snippet:

```
@inproceedings{Scharwachter2020,
   author = {Scharw{\"{a}}chter, Erik and M{\"{u}}ller, Emmanuel},
   booktitle = {6th ACM SIGKDD Workshop on Mining and Learning from Time Series (KDD MiLeTS 2020)},
   title = {{Statistical Evaluation of Anomaly Detectors for Sequences}},
   year = {2020} 
}
```

## License

The source codes are released under the [MIT license](./LICENSE). The data in [twitter-earthquakes.dat](./twitter-earthquakes.dat) was obtained via the ForSight platform from Crimson Hexagon ([Brandwatch](https://www.brandwatch.com/)).

