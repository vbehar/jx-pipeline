## jx-pipeline get

Display one or more pipelines

***Aliases**: list,ls*

### Usage

```
jx-pipeline get
```

### Synopsis

Display one or more pipelines.

### Examples

  # list all pipelines
  jx pipeline get

### Options

```
  -b, --batch-mode         Runs in batch mode without prompting for user input
      --configmap string   The name of the Lighthouse ConfigMap to find the trigger configurations (default "config")
  -f, --format string      The output format such as 'yaml' or 'json'
  -h, --help               help for get
      --log-level string   Sets the logging level. If not specified defaults to $JX_LOG_LEVEL
  -n, --namespace string   The kubernetes namespace to use. If not specified the default namespace is used
      --postsubmit         Views the available lighthouse postsubmit triggers rather than just the current PipelineRuns
      --presubmit          Views the available lighthouse presubmit triggers rather than just the current PipelineRuns
      --verbose            Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warn, info, debug, trace
```

### SEE ALSO

* [jx-pipeline](jx-pipeline.md)	 - commands for working with Jenkins X Pipelines

###### Auto generated by spf13/cobra on 24-May-2021
