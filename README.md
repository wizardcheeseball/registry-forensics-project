# Windows Registry Forensics Analysis

## Overview
This project demonstrates forensic analysis of offline Windows Registry hive files to identify system activity, installed applications, and potential persistence mechanisms. The analysis was conducted in a Linux environment using registry parsing tools.

## Objectives
- Analyze Windows Registry hives outside of a live system
- Identify artifacts related to system and user activity
- Detect registry locations commonly associated with persistence
- Extract meaningful security insights from registry data

## Methodology
- Examined offline registry hive files in a Linux environment
- Parsed registry keys and values using HiveSXH
- Focused on areas related to:
  - System configuration
  - Installed applications
  - Potential persistence mechanisms
- Documented findings and assessed security relevance

## Tools Used
- Linux command line
- HiveSXH (Registry hive analysis)
- Windows Registry Explorer

## Key Findings
- Identified registry keys associated with system startup and persistence mechanisms  
- Located installed application artifacts, including Google Chrome version data (`pv` value) within Omaha registry keys  
- Observed registry entries reflecting system and user activity  
- Documented how registry artifacts can be used to support system profiling and investigation  

## Security Relevance
Registry artifacts provide critical insight during incident response. Attackers commonly use registry-based persistence to maintain access, while defenders use the same artifacts to identify system changes, installed software, and potential indicators of compromise. This analysis demonstrates how registry data supports threat detection and forensic investigation within a SOC environment.

## Skills Demonstrated
- Digital forensics and artifact analysis  
- Registry hive analysis in Linux environments  
- Threat detection mindset  
- Identification of persistence mechanisms  
- Technical documentation and reporting  

## Project File
See the attached PowerPoint/PDF for full analysis, methodology, and findings.
