# Dataset on Cloud Network Variability

This is the dataset obtained while benchmarking public and private clouds for the following article:

### Alexandru Uta, Alexandru Custura, Dmitry Duplyakin, Ivo Jimenez, Jan Rellermeyer, Carlos Maltzahn, Robert Ricci, Alexandru Iosup. Is Big Data Performance Reproducible in Modern Cloud Networks?. In proceedings of 17th USENIX Symposium on Networked Systems Design and Implementation (NSDI), 2020, February 25-27, Santa Clara, USA.

The dataset contains bandwidth variability data for:
- Amazon EC2
- Google Compute Engine
- Microsoft Azure (limited data)
- Scaleway (limited data)
- SURFsara HPCCloud

The dataset contains TCP latency (RTT) data for:
- Amazon EC2
- Google Compute Engine

The dataset contains data regarding token bucket sizes (explained in depth in the aforementioned article) for Amazon EC2.

Please note that the full archive is over 3.5 GB of data, made up of hundreds of thousands of small files. This is why we decided to archive the data, which we then split into smaller files, to accommodate for the Github max file size of 100 MB.
