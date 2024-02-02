## You can also do
* npm package:
```bash
npm install -g @stoplight/spectral @stoplight/spectral-owasp-ruleset
```
* Can include other rules
  ```
  extends:
  - ./spectral/example1.spectral.yaml
  - ./spectral/example2.spectral.yaml
  - ./spectral/oas.spectral.yaml
  - ./spectral/owasp.spectral.yaml
  ```
