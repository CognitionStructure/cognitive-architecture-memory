# Memory Flow

This section describes how experience enters the system and becomes structured memory.

---

## 1. Continuous Stream

The system receives a continuous flow of data from:
- sensors  
- internal state  

This flow is not stored directly.

---

## 2. Buffer

A temporary sliding window across all channels.

Properties:
- short-lived  
- multi-channel  
- pre-memory stage  

The buffer is:
- not memory  
- not structured  
- source for capture  

---

## 3. Trigger

The system does not record everything.

Capture occurs only when a trigger fires.

Triggers include:
- anomaly  
- novelty  
- significance  
- conflict  
- important regular events  

---

## 4. Capture

When triggered, a fragment of the buffer is captured.

Includes:
- data before the event  
- the event itself  
- data after  

This creates a **primary slice**.

---

## 5. Primary Slice

A primary slice is:
- a raw fragment of experience  
- multi-channel  
- temporally structured  

It is not:
- interpreted  
- labeled  
- stored long-term  

---

## Summary

Flow → Buffer → Trigger → Slice

Memory begins not from storage, but from selective capture of experience.
