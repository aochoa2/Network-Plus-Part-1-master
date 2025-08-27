# Lab – Identify IPv6 Addresses

## Objectives

- **Part 1:** Practice with Different Types of IPv6 Addresses  
- **Part 2:** Examine a Host IPv6 Network Interface and Address

---

## Background / Scenario

With IPv4 address space depletion and the transition to IPv6, networking professionals must understand IPv6 address types and configuration. This lab focuses on identifying IPv6 address types, compressing/decompressing IPv6 addresses, and examining IPv6 settings on a PC.

---

## Required Resources

- 1 PC (Windows with Internet access)

---

## Part 1: Practice with Different Types of IPv6 Addresses

### Step 1: Match the IPv6 Address to Its Type

**Answer choices:**

- a. Loopback address  
- b. Global unicast address  
- c. Link-local address  
- d. Unique-local address  
- e. Multicast address  

| IPv6 Address                          | Answer |
|--------------------------------------|--------|
| 2001:0db8:1:acad::fe55:6789:b210     |        |
| ::1                                  |        |
| fc00:22:a:2::cd4:23e4:76fa           |        |
| 2033:db8:1:1:22:a33d:259a:21fe       |        |
| fe80::3201:cc01:65b1                 |        |
| ff00::                               |        |
| ff00::db7:4322:a231:67c              |        |
| ff02::2                              |        |

---

### Step 2: Compress and Decompress IPv6 Addresses

Use IPv6 abbreviation rules to compress or decompress the following:

1. **2002:0ec0:0200:0001:0000:04eb:44ce:08a2**  
   _Compressed:_  
   _Decompressed:_  

2. **fe80:0000:0000:0001:0000:60bb:008e:7402**  
   _Compressed:_  
   _Decompressed:_  

3. **fe80::7042:b3d7:3dec:84b8**  
   _Compressed:_  
   _Decompressed:_  

4. **ff00::**  
   _Compressed:_  
   _Decompressed:_  

5. **2001:0030:0001:acad:0000:330e:10c2:32bf**  
   _Compressed:_  
   _Decompressed:_  

---

## Part 2: Examine a Host IPv6 Network Interface and Address

### Step 1: Check Your PC IPv6 Network Address Settings

1. Open **Control Panel**  
2. Go to **Network and Sharing Center**  
3. Click **Change adapter settings**  
4. Right-click active network interface → **Properties**  
5. Verify **Internet Protocol Version 6 (TCP/IPv6)** is installed and active  
6. Click **Properties** to view IPv6 settings  
7. Open Command Prompt and run:  
   ```bash
   ipconfig /all
   ```


**Example Output:**
```
Link-local IPv6 Address . . . . . : fe80::8d4f:4f4d:3237:95e2%14 (Preferred)
IPv4 Address. . . . . . . . . . . : 192.168.2.106 (Preferred)
Default Gateway . . . . . . . . . : 192.168.2.1
DNS Servers . . . . . . . . . . . : 192.168.1.1, 8.8.4.4
```

## Questions 

- What does it indicate about the network regarding IPv6 global unicast, unique-local, or gateway address?
Answer:
- What kind of IPv6 addresses did you find using ipconfig /all?
Answer:


## Reflection Questions

1. How do you think you must support IPv6 in the future?
Answer:

2. Do you think IPv4 networks will continue, or will everyone eventually switch to IPv6? How long do you think it will take?
Answer:
 