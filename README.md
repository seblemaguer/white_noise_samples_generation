# Noise generation script

The goal of this script is simply to generate white noise samples given a TSV file which associates basenames to the expected duration

```sh
usage: generate.py [-h] [-l LOG_FILE] [-s SAMPLERATE] [-v] duration_file output_dir

Generate white noise wave files from given durations

positional arguments:
  duration_file         The TSV file associating the basename to the duration
  output_dir            The output directory which will contain the white noise wave files

optional arguments:
  -h, --help            show this help message and exit
  -l LOG_FILE, --log_file LOG_FILE
                        Logger file
  -s SAMPLERATE, --samplerate SAMPLERATE
                        The sample rate of the output samples
  -v, --verbosity       increase output verbosity
```
