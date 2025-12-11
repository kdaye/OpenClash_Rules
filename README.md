# OpenClash_Rules
```
  custom:
    type: http
    behavior: domain
    url: "https://raw.githubusercontent.com/kdaye/OpenClash_Rules/refs/heads/main/custom.yaml"
    path: ./ruleset/custom.yaml
    interval: 86400
    
  Netflix:
    type: http
    behavior: classical
    url: "https://raw.githubusercontent.com/kdaye/OpenClash_Rules/refs/heads/main/Netflix.yaml"
    path: ./ruleset/Netflix.yaml
    interval: 86400
    
  DisneyPlus:
    type: http
    behavior: classical
    url: "https://raw.githubusercontent.com/kdaye/OpenClash_Rules/refs/heads/main/DisneyPlus.yaml"
    path: ./ruleset/DisneyPlus.yaml
    interval: 86400
```