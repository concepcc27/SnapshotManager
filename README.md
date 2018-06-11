# SnapshotManager
Demo project to manage AWS EC2 instance snapshots

## About

This project requires Python 3 and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running
```
pipenv shell
python shotty/shotty.py
```
