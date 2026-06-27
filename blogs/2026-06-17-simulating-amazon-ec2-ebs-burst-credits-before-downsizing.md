---
title: "Simulating Amazon EC2 EBS burst credits before downsizing an instance"
url: "https://aws.amazon.com/blogs/compute/simulating-amazon-ec2-ebs-burst-credits-before-downsizing-an-instance/"
date: "2026-06-17"
author: "Vineedh George"
feed_url: "https://aws.amazon.com/blogs/compute/feed/"
---
Explains how to evaluate whether smaller EC2 instances can handle existing workloads by simulating EBS burst credit depletion. The methodology extracts CloudWatch metrics over multiple weeks, compares actual I/O patterns against target instance limits, and models credit balance changes, with worked examples of instances that fit comfortably, those with tight margins, and those exceeding throughput ceilings, plus post-migration monitoring guidance.
