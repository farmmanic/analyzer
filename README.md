# QBAnalyzer
QBAnalyzer is an open source threat intelligence framework that automates extracting artifacts and IOCs from file/dump into readable format.

### Running
![](https://raw.githubusercontent.com/bd249ce4/QBAnalyzer/master/readme/intro.gif)

### E.g. HTML Outputs
- [Linux-Xorddos](https://bd249ce4.github.io/pages/Xorddos.html)
- [Android-BrazilianRAT](https://bd249ce4.github.io/pages/BrRAT.apk.html)
- [Android-Ransom](https://bd249ce4.github.io/pages/sexSimulator.apk.html)
- [macOS-DMG-BundloreAdware](https://bd249ce4.github.io/pages/BundloreAdware.dmg.html)
- [Windows-GoziBankerISFB](https://bd249ce4.github.io/pages/GoziBankerISFB.exe.html)
- [PDF-TrojanDownloader](https://bd249ce4.github.io/pages/Downloader.pdf.html)
- [PCAP-dump](https://bd249ce4.github.io/pages/dump.pcap.html)
- [Office-JSDropper](https://bd249ce4.github.io/pages/officejsdropper.docx.html)
- [RTF-Downloader](https://bd249ce4.github.io/pages/f9boo3.doc.html)
- [EMAIL-Shademalspam](https://bd249ce4.github.io/pages/Shaderansomwaremalspam.eml.html)

### E.g. Output json
![](https://raw.githubusercontent.com/bd249ce4/QBAnalyzer/master/readme/json.gif)

---

### Backstory
Back in 2018, I used to analyze many files and dumps using my old automated tools I developed in the past. The main tool called (QManager) that interacted with the rest of them through Pipes, APIs, Events sand RAW Files. The interaction happened in phases using a queue due to the variation and availability of some tools. Then, results were handled by a parser that piped structured and unstructured information into centralized databases. Finally, it informed me with the end of the process by sending a notification message. This worked just fine until recently when I wanted to implement some machine learning and few other features to the process. After a lot of researching I came to the conclusion that the best way is rewriting most of those old tools, and implement different opensource packages into modules. Then, have them compiled into one framework for easy management by researchers.

### Features
- Runs locally and easy to maintain
- Generates HTML and JSON as output
- Write your ideas under each output
- General file information MD5, charset, mime, ssdeep
- Different string/patterns analysis methods
- NL English words detection
- OCR words detections (!)
- IPS countries description
- IPS reserved hints
- World IPS countries image
- Ports description
- DNS servers description (Top servers)
- Websites similarity detection (Top 10000)
- Artifacts force directed image
- Xrefs force directed image
- Xrefs count table
- MITRE att&ck tools detection (could be FP)
- MITRE att&ck patterns detection (could be FP)
- Similarity image
- Yara module and yara rules included
- JSON editable records 
- URL/EMAIL/TEL/Tags common patterns extraction
- Credit cards patterns extraction
- Encryption patterns (base64, md5, sha1..) detection
- Linux
    - ELF information
    - API functions descriptions
    - System commands descriptions
    - Secitons descriptions
    - Lib descriptions
    - Encrypted section detection
    - Symbs extraction
    - MITRE artifacts detection
    - Xref detection
- macOS
    - DMG extraction
    - Shell code detection
    - PLIST information
    - MITRE artifacts detection
    - macOS information
- Windows
    - PE information
    - Encrypted section detection
    - Secitons descriptions
    - DLL descriptions
    - Symbs extraction
    - Signature extraction
    - API functions descriptions
    - PE ASLR, DEP, SEH and CFG detection
    - MITRE artifacts detection
    - API Behavior detections (DLL injection, Process Hollowing, Process Doppelganging etc..)
    - Xref detection
- Android
    - APK information
    - DEX information
    - Manifest descriptions
    - Intent descriptions
    - Resources extraction
    - Symbs extraction
    - Classes extraction
    - Big functinon identification 
    - Xref detection
    - API Behavior detections
- Iphone
    - IPA information
- BlackBerry (COD)
    - COD information
    - Functions extraction
    - Strings extraction
- PCAP
    - Frame Filter
    - HT                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              