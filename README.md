# semaphore-ci-starter
:tada: Semaphore CI 2.0 Starter

1. Install dependencies and cache
2. Running lint and test
3. If all test passed we deploy to hosting (Firebase hosting)
4. We use `sem secret` for environment variables (firebase token)

## Usage

```
# Create secret
sem create -f firebase-secret.yml

# Get secret
sem get secrets firebase-secret
```
