# AWS DataSync Python Examples

## Usage

With an includes filter:

```
$ python3 ./ds-execute-tasks --task_arn arn:aws:datasync:us-east-2:123456789012:task/task-0462c95856fa50c56 --includes_filter /test-data/folder2
```

No includes filter:

```
$ python3 ./ds-execute-tasks --task_arn arn:aws:datasync:us-east-2:123456789012:task/task-0462c95856fa50c56
```

With region and profile:

```
$ python3 ./ds-execute-tasks --task_arn arn:aws:datasync:us-east-2:123456789012:task/task-0462c95856fa50c56 --profile my-profile --region us-east-1
```