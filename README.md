# Run

```
$ docker run -it --rm asannou/aws-ssm-console -h
Usage: aws-ssm-console [options]
        --instance-ids id,id,...
    -c command
        --tag Name:Value
```

```
$ docker run -it --rm -v ~/.aws:/root/.aws asannou/aws-ssm-console --instance-ids i-0b37d1d850bdd0a17
>> uname -a
Running uname -a
[i-0b37d1d850bdd0a17]    Success: uname -a
    Linux ip-172-31-19-88 4.4.35-33.55.amzn1.x86_64 #1 SMP Tue Dec 6 20:30:04 UTC 2016 x86_64 x86_64 x86_64 GNU/Linux
```
