# Logging like a STAR

---
@title[Why do we log]
@snap[north span-100 headline]
Why do we log?
@snapend

@snap[west span-55]
@ul[spaced text-gray]
- Troubleshoot
- Visibility
- Analysis & Insight
@snapend

@snap[east span-55]
![](assets/img/logs.jpg)
@snapend

---

## Let's talk about types of Logging
@ul[spaced text-gray]
- Error Logging
- General Logging
- Performance & Metrics

---
@title[Logging Tools]
## Standing upon the shoulders of Giants

@snapend[south span 30]
@img[fragment](assets/img/the-elastic-stack-thumb.png)
@img[fragment](assets/img/sentry-logo.png)
@snapend

---?color=#DC143C
@title[Error Logging]
@snap[north span-100 headline]
Error Logging
@snapend

![](assets/img/kibana.png)

---?color=#DC143C
@title[Error Tracking]
@snap[north span-100 headline]
Error Tracking
@snapend

![](assets/img/sentry.png)

---
@title[Fenix Standard Logging]
@snap[north span-200 headline]
Fenix Standard Logging
@snapend

@snap[west span-100]
@ul[spaced text-gray]
- DEBUG - Local Development only
- INFO - General logs
- WARNING - Handled errors
- Error - Quick, call the fire marshall
- Exception - Daaaaamn!!!
@snapend

---
@title[Logging Examples]
Standard Logging
@fa[arrow-down]
+++?color=#272c34 @title[Standard Logging]
@title[Standard Logging Example]
```
QUEUE_SMS ERROR: Default SMS Gateway missing for +260961314844
```

Structured Logging
@fa[arrow-down]
+++?color=#272c34 @title[Structured Logging]
@title[Structured Logging Example]
```json
{"msisdn": "+260961314844",
"message": "Default SMS Gateway missing",
"exc": "<class 'fenix.sms.models.DoesNotExist'>",
"event": "queue_sms"}
```

---
@title[Querying Logs]
# How to query logs

---
@title[Thank You]
![](assets/img/thanks.gif)
