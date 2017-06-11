+++
categories = ["Others"]
date = "2017-06-11T15:32:45+01:00"
title = "codetest"

+++

this is some code just here

`aws ec2 describe-snapshots --snapshot-id snap-1234567890abcdef0`

and this is the output

```
{
    "Snapshots": [
        {
            "Description": "This is my snapshot.",
            "VolumeId": "vol-049df61146c4d7901",
            "State": "completed",
            "VolumeSize": 8,
            "Progress": "100%",
            "StartTime": "2014-02-28T21:28:32.000Z",
            "SnapshotId": "snap-1234567890abcdef0",
            "OwnerId": "012345678910"
        }
    ]
}
```

so there we go
