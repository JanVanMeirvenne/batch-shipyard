# Batch Shipyard Installation

## Requirements
The Batch Shipyard tool is written in Python. The client script is compatible
with Python 2.7 or 3.3+. You will also need to install the
[Azure Batch](https://pypi.python.org/pypi/azure-batch) and
[Azure Storage](https://pypi.python.org/pypi/azure-storage) python packages.
Installation can be performed using the [requirements.txt](../requirements.txt)
file via the command `pip install --user -r requirements.txt` (or via `pip3`
for python3).

## Installation
Simply clone the repository:

```
git clone https://github.com/Azure/batch-shipyard.git
```

or [download the latest release](https://github.com/Azure/batch-shipyard/releases).

Please note that if cloning the repository on Windows to ensure that git does
not modify the Unix line-endings (LF) for in the files in the `scripts`
directory. If these files are modified with Windows line-endings (CRLF) then
compute nodes will fail to start properly.

## Batch Shipyard Configuration
Continue on to
[Batch Shipyard Configuration](02-batch-shipyard-configuration.md).