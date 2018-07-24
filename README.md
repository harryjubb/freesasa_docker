# FreeSASA Docker
Dockerfile for building FreeSASA (Simon Mitternacht (2016) FreeSASA: An open source C library for solvent accessible surface area calculation. F1000Research 5:189 (doi: 10.12688/f1000research.7931.1)

## Building and running locally

    docker build -t 'freesasa' .
    docker run --rm -it freesasa freesasa -h
    
## Running (from DockerHub)

    docker run --rm -it harryjubb/freesasa freesasa -h
