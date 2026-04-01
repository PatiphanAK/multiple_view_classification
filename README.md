# Classification for Material Part Inspection

## Problem Overview

In industrial manufacturing, metal parts often suffer from defects such as *flashing* material that remains attached after the process. These defects can compromise product quality and must be detected reliably during quality control.

This project focuses on building a **binary classification system (pass / fail)** for automated inspection. Each item is captured from **multiple viewpoints (14 views per sample)**.

The key challenge lies in effectively **leveraging multi-view information** to improve classification performance under conditions such as occlusion, lighting variation, and subtle defect patterns.

## Viewpoint Design Rationale
The 14-view configuration is structured to ensure comprehensive coverage:
- Top and Bottom Views
- Angled Views (Top-Side / Bottom-Side)
- Side-Oriented Views
