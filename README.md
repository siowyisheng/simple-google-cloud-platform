# The Simple Guide to Google Cloud Platform

_Google Cloud Platform concepts explained simply._

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/siowyisheng/simple-google-cloud-platform/blob/master/LICENSE) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## Table of Contents <!-- omit in toc -->

- [What is Google Cloud Platform?](#what-is-google-cloud-platform)
- [What does Google Cloud Platform look like?](#what-does-google-cloud-platform-look-like)
- [TODO](#todo)
- [running a cloud sql instance is expensive](#running-a-cloud-sql-instance-is-expensive)

## What is Google Cloud Platform?

## What does Google Cloud Platform look like?

## TODO

projects
app engine
cloud sql instances
apis
setting up
cloud sql proxy
gcloud init
the different SDKs
standard environment vs flexible environment
connection
settings.py

## running a cloud sql instance is expensive

```bash
$ gcloud sql instances create YOUR_INSTANCE_NAME --region=asia-southeast1
```

create user
create database

```bash
$ gcloud sql instances describe YOUR_INSTANCE_NAME
```

look for connectionName

```bash
$ ./cloud_sql_proxy -instances="[YOUR_INSTANCE_CONNECTION_NAME]"=tcp:3306
```
