https://www.elastic.co/blog/ten-process-injection-techniques-technical-survey-common-and-trending-process

# 1. Classic DLL Injection - CreateRemoteThread and LoadLibrary
This technique is one of the most common techniques used to inject malware into another process. The malware writes the path to its malicious dynamic-link library (DLL) in the virtual address space of another process, and ensures the remote process loads it by creating a remote thread in the target process.
