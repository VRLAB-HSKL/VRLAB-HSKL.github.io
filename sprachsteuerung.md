---
title: Sprachsteuerung
has_children: true
nav_order: 2
---


# Sprachsteuerung
{: .no_toc }

Hier finden Sie allgemeine Informationen zum VR Labor.
{: .fs-6 .fw-300 }

## Inhaltsverzeichnis
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Wichtig
Die in folgenden Punkten beschriebene Sprachsteuerung funktioniert lediglich auf Windows 10. 
Grund hierfür ist der Einsatz der Klasse "KeywordRecognizer" von UnityEngine.Windows.Speech
## Integration in ein Projekt
## Umsetzung
### SpeechRecognitionController
### ActivationRecognizer
### CommandRecognizer
### JsonSpeechDataReader
### KeywordHolder
### JSON Struktur
Die Json Datei besteht aus mehreren Arrays die, die jeweiligen Sprachbefehle definieren. 
Der Inhalt des Array **"activationWords"** definiert die Aktivierungsbefehle.
Die Inhalte der anderen Arrays definieren die Kommandobefehle der einzelnen Events. **"event1Keywords"** für das Event1 UnityEvent
