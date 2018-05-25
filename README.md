![Logo](logo.png)
# Bag of STARs
STAR mapping on slurm clusters in bags.

## Requirements
- `python3.4+`
- `STAR` in your `PATH`

## Installation
```bash
git clone https://github.com/iosonofabio/bag_of_stars.git
```

## Usage
Call bag of stars from the `bos` folder:
```bash
python bag_of_stars.py --genomeDir <your genome folder> --output <your output folder> <your fastq root folder>
```
- The fastq root folder must contain subfolders with each a read1 and read2 file.
- New subfolders with the same names will be made inside the output folder.
- The genome folder must contain STAR's hash files (e.g. `SA`, `SAindex`, `Genome`)
- `STAR` must be in your `PATH`, you can check your `.bashrc` for what folders are there.

## Help
```bash
python bag_of_stars.py --help
```
