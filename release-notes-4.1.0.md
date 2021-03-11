!not-ready-for-release!

#### Version Number
${version-number}

#### New Features
- SCMOD-12707: Added support for pausing and resuming jobs.
  - Three new endpoints have been added to pause, resume, and get the status of a job.

#### Breaking Changes
- SCMOD-12707: The type of the `job.status` field returned in responses has been changed from `String` to `JobStatus`.

#### Known Issues
- None
