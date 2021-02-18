---
layout: post
title: markdown notation
sub_heading: mermaid.js - charting, gantt,  flow & process diagrams
date: 
tags: []
banner_image: "/uploads/2021/02/18/mermaid-diagram-20210218103414.svg"
related_posts: []

---

Mermaid JS - is a project we love, which it in use on this website. it can be as simple as 

[https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbIHZvbHVudGVlciBdIC0tPnxTaW1wbGUgYXBwbGljYXRpb258IEIoYWdyZWUgdG8gdGVybXMgKVxuQiAtLT4gQ3tDaG9vc2UgYSByb2xlfVxuQyAtLT58cHJvamVjdCBjb250YWN0fCBEW0NvbW11bmljYXRlIHdpdGggY29tbXVuaXR5XVxuQyAtLT58cHJvamVjdCBsaWFzb258IEVbUHJvamVjdCBsaWFzb25dXG5DIC0tPnxwcm9qZWN0IGxlYWR8IEZ7Y29tbXVuaXR5IGlucHV0fVxuQyAtLT58cmVzZWFyY2ggcGFydG5lcnwgR1tCYWNrZ3JvdW5kIFJlc2VhcmNoXVxuQyAtLT58bWVldGluZyBjb29yZGluYXRvcnwgSFtleHBlcnRzLGxvY2FsIGxlYWRlcnMsIHJlc2VhcmNoIHBhcnRuZXJzIF1cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbIHZvbHVudGVlciBdIC0tPnxTaW1wbGUgYXBwbGljYXRpb258IEIoYWdyZWUgdG8gdGVybXMgKVxuQiAtLT4gQ3tDaG9vc2UgYSByb2xlfVxuQyAtLT58cHJvamVjdCBjb250YWN0fCBEW0NvbW11bmljYXRlIHdpdGggY29tbXVuaXR5XVxuQyAtLT58cHJvamVjdCBsaWFzb258IEVbUHJvamVjdCBsaWFzb25dXG5DIC0tPnxwcm9qZWN0IGxlYWR8IEZ7Y29tbXVuaXR5IGlucHV0fVxuQyAtLT58cmVzZWFyY2ggcGFydG5lcnwgR1tCYWNrZ3JvdW5kIFJlc2VhcmNoXVxuQyAtLT58bWVldGluZyBjb29yZGluYXRvcnwgSFtleHBlcnRzLGxvY2FsIGxlYWRlcnMsIHJlc2VhcmNoIHBhcnRuZXJzIF1cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9 "https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbIHZvbHVudGVlciBdIC0tPnxTaW1wbGUgYXBwbGljYXRpb258IEIoYWdyZWUgdG8gdGVybXMgKVxuQiAtLT4gQ3tDaG9vc2UgYSByb2xlfVxuQyAtLT58cHJvamVjdCBjb250YWN0fCBEW0NvbW11bmljYXRlIHdpdGggY29tbXVuaXR5XVxuQyAtLT58cHJvamVjdCBsaWFzb258IEVbUHJvamVjdCBsaWFzb25dXG5DIC0tPnxwcm9qZWN0IGxlYWR8IEZ7Y29tbXVuaXR5IGlucHV0fVxuQyAtLT58cmVzZWFyY2ggcGFydG5lcnwgR1tCYWNrZ3JvdW5kIFJlc2VhcmNoXVxuQyAtLT58bWVldGluZyBjb29yZGluYXRvcnwgSFtleHBlcnRzLGxvY2FsIGxlYWRlcnMsIHJlc2VhcmNoIHBhcnRuZXJzIF1cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9")

**graph** TD

A\[ volunteer \] **-->**|Simple application| B(agree to terms )

B **-->** C**{**Choose a role**}**

C **-->**|project contact| D\[Communicate with community\]

C **-->**|project liason| E\[Project liason\]

C **-->**|project lead| F**{**community input**}**

C **-->**|research partner| G\[Background Research\]

C **-->**|meeting coordinator| H\[experts,local leaders, research partners \]