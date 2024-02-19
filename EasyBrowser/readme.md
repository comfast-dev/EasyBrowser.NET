

# How to use
1. Configure using Configuration class
2. Use:
```csharp
    var driver = DriverSource.Driver
    driver.open("some url")
```


# Features: 
- [x] Multi-thread support - create one driver per thread
- [x] Support only Chromium/Brave browsers
- [x] Reconnect to already opened browser
- [x] Auto close/remain Browser depend on configuration

# Todo's
- [ ] Configuration based on all: 
  - json
  - env variable
- [ ] Manage all major browsers: Firefox, Chromium, Ie
- [ ] Reconnect working to all browses
- [ ] Make unit tests for all features