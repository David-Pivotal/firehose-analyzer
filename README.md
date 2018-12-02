## Firehose Aanalyzer

Collects a summary of firehose activity by reading ValueMetric and CountEvent metrics from the firehose.

### Instance stats

Averages the cpu and memory stats accorss instance groups.

### Drain Information

Reports how many syslog drains are configured and how many are actually bound.

### Doppler 

Reports subscription, ingress, and dropped metrics for each doppler instance.

### Metron Health
If a metron agent reports any dropped envelopes this section will display the job and index information.

### Usage

```
Usage of firehose-analyzer:
  -api string
    	CF API endpoint https://api.system.domain.com
  -o string
    	Specifiy an output file that records data in csv format
  -token string
    	Provide an access token used to authenticate with doppler endpoint. Defaults to ~/.cf/config.json
  -url string
    	Web socket address example: wss://doppler.system.domain:443
```

### Demo

[![asciicast](https://asciinema.org/a/VwJhb3avWZg05bheHwQSNBmUf.svg)](https://asciinema.org/a/VwJhb3avWZg05bheHwQSNBmUf)