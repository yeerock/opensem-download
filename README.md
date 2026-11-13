# OpenSEM - Free CB-SEM and PLS-SEM Software

OpenSEM is free desktop software for **PLS-SEM** (partial least squares structural equation modelling) and, from the next release, **CB-SEM** (covariance-based SEM). Free to download and use, including for business.

- **Automatic:** checks your data, picks the right method, explains every result in plain language
- **Backed by research:** every method and threshold cites its published source, and the report includes a methods paragraph and reference list
- **Fast:** uses every CPU core; 10,000 bootstrap resamples in well under a second
- **Private:** works fully offline; your data never leaves your computer

Website: https://vyrox.com/sem/

## Download

Get the latest version for Windows, macOS or Linux from **[Releases](https://github.com/yeerock/opensem-download/releases)**. Each file has a `.sha256` checksum.

## Quick Start

```bash
opensem demo
opensem analyze --data mydata.csv --model mymodel.txt
```

Model syntax:

```text
Trust   =~ T1 + T2 + T3      # reflective construct
Image   <~ I1 + I2           # formative construct
Loyalty =~ L1 + L2
Loyalty ~  Trust + Image     # structural paths
```

## Licence

Free for personal, academic and business use. You may share the unmodified download free of charge. No resale, modification or reverse engineering. See [LICENSE](LICENSE).

The source code is not public. This repository only hosts the downloads.
