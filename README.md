# C3O Experiments

Here are the experiment data for the paper

**Towards Collaborative Optimization of Cluster Configurations for Distributed Dataflow Jobs** [[PDF](https://arxiv.org/pdf/2011.07965)]

Presented at the [BPOD workshop](https://userpages.umbc.edu/~jianwu/BPOD/) of the [IEEE Big Data 2020 conference](http://bigdataieee.org/BigData2020/) [[Presentation Video](https://www.youtube.com/watch?v=-3cI-8i02Ps)].

The individual files contain the experiment data for each job in tsv format.

---

**Paper Abstract:**

Analyzing large datasets with distributed dataflow systems requires the use of clusters. Public cloud providers offer a large variety and quantity of resources that can be used for such clusters. However, picking the appropriate resources in both type and number can often be challenging, as the selected configuration needs to match a distributed dataflow job's resource demands and access patterns. A good cluster configuration avoids hardware bottlenecks and maximizes resource utilization, avoiding costly overprovisioning.

We propose a collaborative approach for finding optimal cluster configurations based on sharing and learning from historical runtime data of distributed dataflow jobs. Collaboratively shared data can be utilized to predict runtimes of future job executions through the use of specialized regression models. However, training prediction models on historical runtime data that were produced by different users and in diverse contexts requires the models to take these contexts into account. 

---

**Cite Us:**

```
@inproceedings{will2020towards,
    title={{Towards Collaborative Optimization of Cluster Configurations for Distributed Dataflow Jobs}},
    author={Will, Jonathan and Bader, Jonathan and Thamsen, Lauritz},
    booktitle={2020 IEEE International Conference on Big Data},
    year={2020},
    pages={To appear},
    organization={IEEE},
}
```


