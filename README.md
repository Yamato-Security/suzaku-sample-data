# Suzaku Sample Data

This repository contains various cloud logs containing attack data.
This is to be used to test detection capabilities with [Suzaku](https://github.com/Yamato-Security/suzaku).

The data is gathered from the following sources:
 - [Invictus-ir dataset](https://www.invictus-ir.com/nieuws/automated-first-response-in-aws-using-sigma-and-athena): In August 2023, Invictus-ir did great research on simulating 32 attacks against AWS with the [Stratus Red Team](https://github.com/DataDog/stratus-red-team) to compare detections with Sigma, Athena and Splunk rules and shared the dataset after the attacks.
 - [Flaws.cloud dataset](http://flaws.cloud/): Scott Piper from Summit Route made his public data from attacks against his free [flaws.cloud](http://flaws.cloud/) training website in 2020. (Note that the IP addresses and accound IDs have been anonymized as explained [here](https://summitroute.com/blog/2020/10/09/) )public_dataset_of_cloudtrail_logs_from_flaws_cloud/) )
 - [Traildiscover.cloud dataset](https://traildiscover.cloud/): A great website that lists up all of the AWS attack techniques and provides sample JSON data of the attack.