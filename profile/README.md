<div align="center">
  <h1><code>sc2</code></h1>

  <p>
    <strong>Serverless Confidential Containers</strong>
  </p>
  <hr>
</div>

SC2 is a research project with the goal of making confidential VMs usable for
serverless computing. It is developed at the [LSDS](https://lsds.doc.ic.ac.uk/)
group of the Imperial College London.

## Organization Structure

* [sc2-sys/deploy](https://github.com/sc2-sys/deploy) - main entrypoint to deploy SC2 and build patched components.
* [sc2-sys/experiments](https://github.com/sc2-sys/experiments) - experiments and plots for SC2.
* [sc2-sys/applications](https://github.com/sc2-sys/applications) - applications used as workloads for SC2's experiments.

## Citing Our Work

If you use SC2, please consider checking our [vision paper](
https://dl.acm.org/doi/abs/10.1145/3642977.3652097?casa_token=ikkXY0sv32oAAAAA:CSVuwADv22-tlnAX8Q_bZxF4T0IuvMnmc_dzdZfsdS1UUdWzSHDdOyW9goRDtUSA2aDMFK3IaGA)
and citing our work:

```bibtex
@inproceedings{sesame2024sc2_challenges_opps,
  author = {Segarra, Carlos and Feldman-Fitzthum, Tobin and Buono, Daniele and Pietzuch, Peter},
  title = {Serverless Confidential Containers: Challenges and Opportunities},
  booktitle = {Proceedings of the 2nd Workshop on SErverless Systems, Applications and MEthodologies},
  year = {2024},
  series = {SESAME '24}
}
```
