# HomeServerScripts

Collection of scripts written to help manage my home server.

### DeISO:

**Description:**  
 Detects .iso files within a directory and queues them to be encoded to .mkv via HandBrakeCLI. Preserves audio and subtitle tracks.

**Requires:**

- HandBrakeCLI >= 1.0.4

**Useage:**  
`bash /path/to/deiso /path/to/mediaDirectory`

### R230FanSpeed

**Description:**
Automatic fan speed setting specifically for the Dell PowerEdge R230 but with a few edits will probably work for whichever PowerEdge you need.

**Requires**

- IPMITool

**Useage**
Set a crontab entry for every minute to invoke the script.
