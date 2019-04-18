# Logging like a STAR

---

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
![](assets/img/presentation.png)
@snapend

---

## Let's talk about types of Logging
@ul[spaced text-gray]
- Error Logging
- General Logging
- Performance & Metrics

---?color=#DC143C
@title[Error Logging]
@snap[north span-100 headline]
Error Logging
@snapend

![](assets/img/presentation.png)

---?color=#DC143C
@title[Error Tracking]
@snap[north span-100 headline]
Error Tracking
@snapend

![](assets/img/presentation.png)

---
@snap[north]
### Fenix Standard Logging
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

@snap[north span-100 headline]
Structured Logging
@snapend

Standard Logging
@fa[arrow-down]
+++?color=#272c34 @title[Standard Logging]
```
QUEUE_SMS ERROR: Default SMS Gateway missing for +260961314844
```

---


@snap[east span-55]
Standard logging

```{"msisdn": "+260961314844", "message": "Default SMS Gateway missing", "exc": "<class 'fenix.sms.models.DoesNotExist'>", "event": "queue_sms"}```
@snapend
