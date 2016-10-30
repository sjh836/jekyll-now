---
layout: post
title: You're up and running!
---

[root@ljh deploy]# bin/crawl urls -dir urls -depth 1 -topN 5 –solr http://ljh.main:8983/solr/
16/08/14 22:33:50 INFO crawl.Injector: Injector: starting at 2016-08-14 22:33:50
16/08/14 22:33:50 INFO crawl.Injector: Injector: crawlDb: -dir/crawldb
16/08/14 22:33:50 INFO crawl.Injector: Injector: urlDir: urls
16/08/14 22:33:50 INFO crawl.Injector: Injector: Converting injected urls to crawl db entries.
16/08/14 22:33:55 INFO client.RMProxy: Connecting to ResourceManager at ljh.main/192.168.111.100:8032
16/08/14 22:33:56 INFO client.RMProxy: Connecting to ResourceManager at ljh.main/192.168.111.100:8032
16/08/14 22:34:02 INFO mapred.FileInputFormat: Total input paths to process : 2
16/08/14 22:34:02 INFO mapreduce.JobSubmitter: number of splits:3
16/08/14 22:34:03 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1471179657432_0001
16/08/14 22:34:04 INFO impl.YarnClientImpl: Submitted application application_1471179657432_0001
16/08/14 22:34:05 INFO mapreduce.Job: The url to track the job: http://ljh.main:8088/proxy/application_1471179657432_0001/
16/08/14 22:34:05 INFO mapreduce.Job: Running job: job_1471179657432_0001
16/08/14 22:34:45 INFO mapreduce.Job: Job job_1471179657432_0001 running in uber mode : false
16/08/14 22:34:45 INFO mapreduce.Job:  map 0% reduce 0%
16/08/14 22:35:26 INFO mapreduce.Job:  map 33% reduce 0%
16/08/14 22:35:40 INFO mapreduce.Job:  map 67% reduce 0%
16/08/14 22:36:01 INFO mapreduce.Job:  map 100% reduce 0%
16/08/14 22:36:20 INFO mapreduce.Job:  map 100% reduce 100%
16/08/14 22:36:23 INFO mapreduce.Job: Job job_1471179657432_0001 completed successfully
