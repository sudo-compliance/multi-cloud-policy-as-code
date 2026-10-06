# Threat model

## Risk scenario

A developer tries to create cloud storage that allows public internet access.

## Expected result

The pull request check fails before deployment. If unsafe settings reach the cloud, the cloud policy denies or reports them.

## Main threats

1. Public access to storage data.
2. A change that removes security logging.
3. Resources created outside approved regions.
4. Resources with no named owner.
