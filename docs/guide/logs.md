# Logs

One of the primary purposes of farmOS is record keeping. Record keeping is
essentially just the recording and organizing of events.

In farmOS, **logs** are records of events that *have* taken place, or *will*
take place in the future.

farmOS is very flexible in the granularity of the data that it can store. You
can decide what is worth remembering and what isn't. The more you save, the
more you can recall and learn from in the future.

## Log types

There are different types of logs in farmOS - each with it's own
purpose and set of fields. Some of the general log types are described below.

### Actions

**Action logs** are for recording general actions on the farm. This can be
thought of as a catch-all log type for any kind of activity that doesn't fit
into a more specific log type (like harvests or inputs).

This should be used for "active" events, whereas observation logs should be
used for "passive" events.

### Observations

**Observation logs** are used to record passive observations on the farm. For
example, seeing that a planting has germinated is an observation. This is a
very flexible log type that can be used for a lot of different things.

### Harvests

**Harvest logs** are used to record harvests.

### Inputs

**Input logs** are used to record inputs.
