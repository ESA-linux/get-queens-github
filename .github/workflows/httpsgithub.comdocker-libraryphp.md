# https://github.com/docker-library/php
http://webdav@192.168.1.107:8080/
From 071d062c02d4e0146074e166c920c1e8c9130601 Mon Sep 17 00:00:00 2001
From: ESA <psinab@icloud.com>
Date: Mon, 23 Dec 2019 11:46:19 +0100
Subject: [PATCH] active-http

- - - -
 Alexa LED Animation Files for AVS/LED Animation Files for Alexa Attention States.pdf | Bin 0 -> 257873 bytes
 Alexa LED Animation Files for AVS/license.txt                                        |   9 +++++++++
 Alexa LED Animation Files for AVS_linear_11_active-ending.animation                  |  85 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_active-talking.animation                 |  56 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_active-thinking.animation                |  41 +++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_active-waking.animation                  |  31 +++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_alert-short.animation                    |  89 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_alert.animation                          |  89 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_btconnect.animation                      |  23 +++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_btdisconnect.animation                   |  23 +++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_do_not_disturb.animation                 | 110 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_error.animation                          |  86 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_mics-off_end.animation                   |  12 ++++++++++++
 Alexa LED Animation Files for AVS_linear_11_mics-off_on.animation                    |   8 ++++++++
 Alexa LED Animation Files for AVS_linear_11_mics-off_start.animation                 |  17 +++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_ntf_incoming.animation                   | 172 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_11_ntf_queued.animation                     | 150 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_active-ending.animation                   |  32 ++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_active-talking.animation                  |  56 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_active-thinking.animation                 |  40 ++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_active-waking.animation                   |  20 ++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_alert-short.animation                     | 266 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_alert.animation                           |  88 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_btconnect.animation                       |  48 ++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_btdisconnect.animation                    |  48 ++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_do_not_disturb.animation                  |  59 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_error.animation                           |  86 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_mics-off_end.animation                    |  12 ++++++++++++
 Alexa LED Animation Files for AVS_linear_5_mics-off_on.animation                     |   8 ++++++++
 Alexa LED Animation Files for AVS_linear_5_mics-off_start.animation                  |  17 +++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_ntf_incoming.animation                    |  37 +++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_5_ntf_queued.animation                      |  29 +++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_active-ending.animation                   |  32 ++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_active-talking.animation                  |  56 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_active-thinking.animation                 |  40 ++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_active-waking.animation                   |  19 +++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_alert-short.animation                     | 266 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_alert.animation                           |  88 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_btconnect.animation                       |  23 +++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_btdisconnect.animation                    |  23 +++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_do_not_disturb.animation                  | 110 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_error.animation                           |  86 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_mics-off_end.animation                    |  12 ++++++++++++
 Alexa LED Animation Files for AVS_linear_7_mics-off_on.animation                     |   8 ++++++++
 Alexa LED Animation Files for AVS_linear_7_mics-off_start.animation                  | 167 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_ntf_incoming.animation                    | 172 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_linear_7_ntf_queued.animation                      | 150 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_active-ending.animation                  |  16 ++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_active-talking.animation                 |  57 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_active-thinking.animation                |  10 ++++++++++
 Alexa LED Animation Files for AVS_radial_12_active-waking.animation                  |  16 ++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_alert-short.animation                    |  36 ++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_alert.animation                          |  46 ++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_btconnect.animation                      |  48 ++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_btdisconnect.animation                   |  48 ++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_do_not_disturb.animation                 |  59 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_error.animation                          |  86 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_mics-off_end.animation                   |  19 +++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_mics-off_on.animation                    |  10 ++++++++++
 Alexa LED Animation Files for AVS_radial_12_mics-off_start.animation                 |  23 +++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_ntf_incoming.animation                   |  37 +++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_radial_12_ntf_queued.animation                     |  29 +++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_active-ending.animation                     |  22 ++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_active-talking.animation                    | 120 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_active-thinking.animation                   |  16 ++++++++++++++++
 Alexa LED Animation Files for AVS_single_active-waking.animation                     |  22 ++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_alert-short.animation                       | 207 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_alert.animation                             | 100 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_btconnect.animation                         |  48 ++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_btdisconnect.animation                      |  48 ++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_do_not_disturb.animation                    | 110 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_error.animation                             |  86 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_mics-off_end.animation                      |  19 +++++++++++++++++++
 Alexa LED Animation Files for AVS_single_mics-off_on.animation                       |   8 ++++++++
 Alexa LED Animation Files for AVS_single_mics-off_start.animation                    |  23 +++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_ntf_incoming.animation                      | 172 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 Alexa LED Animation Files for AVS_single_ntf_queued.animation                        | 150 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 http.stats.txt                                                                       | 942 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 78 files changed, 5732 insertions(+)
 create mode 100644 Alexa LED Animation Files for AVS/LED Animation Files for Alexa Attention States.pdf
 create mode 100644 Alexa LED Animation Files for AVS/license.txt
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_active-ending.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_active-talking.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_active-thinking.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_active-waking.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_alert-short.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_alert.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_11_btconnect.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_11_btdisconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_do_not_disturb.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_error.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_11_mics-off_end.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_mics-off_on.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_mics-off_start.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_ntf_incoming.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_11_ntf_queued.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_5_active-ending.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_active-talking.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_5_active-thinking.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_active-waking.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_5_alert-short.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_5_alert.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_btconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_btdisconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_do_not_disturb.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_error.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_5_mics-off_end.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_mics-off_on.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_mics-off_start.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_ntf_incoming.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_5_ntf_queued.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_active-ending.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_7_active-talking.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_active-thinking.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_active-waking.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_alert-short.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_alert.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_btconnect.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_btdisconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_7_do_not_disturb.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_7_error.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_mics-off_end.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_7_mics-off_on.animation
 create mode 100755 Alexa LED Animation Files for AVS_linear_7_mics-off_start.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_7_ntf_incoming.animation
 create mode 100644 Alexa LED Animation Files for AVS_linear_7_ntf_queued.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_active-ending.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_active-talking.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_active-thinking.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_active-waking.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_alert-short.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_alert.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_btconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_btdisconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_do_not_disturb.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_error.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_mics-off_end.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_mics-off_on.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_mics-off_start.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_ntf_incoming.animation
 create mode 100644 Alexa LED Animation Files for AVS_radial_12_ntf_queued.animation
 create mode 100755 Alexa LED Animation Files for AVS_single_active-ending.animation
 create mode 100755 Alexa LED Animation Files for AVS_single_active-talking.animation
 create mode 100755 Alexa LED Animation Files for AVS_single_active-thinking.animation
 create mode 100755 Alexa LED Animation Files for AVS_single_active-waking.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_alert-short.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_alert.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_btconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_btdisconnect.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_do_not_disturb.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_error.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_mics-off_end.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_mics-off_on.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_mics-off_start.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_ntf_incoming.animation
 create mode 100644 Alexa LED Animation Files for AVS_single_ntf_queued.animation
 create mode 100644 http.stats.txt

diff --git a_Alexa LED Animation Files for AVS_LED Animation Files for Alexa Attention States.pdf b_Alexa LED Animation Files for AVS_LED Animation Files for Alexa Attention States.pdf
new file mode 100644
index 0000000000000000000000000000000000000000..417877cf6f80beee05d3bf892eccb514858c3a00
GIT binary patch
literal 257873
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

literal 0
Hc$@<O00001

diff --git a_Alexa LED Animation Files for AVS_license.txt b_Alexa LED Animation Files for AVS_license.txt
new file mode 100644
index 0000000..18b14a9
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_license.txt
@@ -0,0 +1,9 @@
+Copyright 2017-18 Amazon.com, Inc. or its affiliates. All Rights Reserved. 
+
+These materials are licensed as “Program Materials” under the Program Materials License Agreement (the “Agreement”) in connection with the Alexa Voice Service Program. The Agreement is available at https://developer.amazon.com/support/legal/pml. See the Agreement for the specific terms and conditions of the Agreement. Capitalized terms not defined in this file have the meanings given to them in the Agreement.
+
+In addition to the terms and conditions of the Agreement, the following terms and conditions (“Additional Terms” and collectively with the Agreement, the “Terms”) apply to these materials. In the event of a conflict between the terms and conditions of the Agreement and these Additional Terms, these Additional Terms will apply.
+
+1. These materials may only be used to implement the Alexa attention states and transitions for the Alexa Voice Service using LEDs as described in the Attention System guidance (https://developer.amazon.com/docs/alexa-voice-service/ux-design-attention.html). If you are a subcontractor who is using these materials on behalf of a third party, you may only use these materials in connection with the products of that third party.
+
+2. These materials are Restricted Program Materials. However, the prohibition in the Agreement’s Restricted Program Materials Schedule on providing Restricted Program Materials to any contractor or other third party without our prior written consent will not apply to these materials.
diff --git a_Alexa LED Animation Files for AVS_linear_11/active-ending.animation b_Alexa LED Animation Files for AVS_linear_11/active-ending.animation
new file mode 100644
index 0000000..bbe1049
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/active-ending.animation
@@ -0,0 +1,85 @@
+16:0000ff,0000ff,0000ff,0000ff,0010ff,00eeff,000eff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0020ff,00eeff,001fff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0036ff,00eeff,0035ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0052ff,00eeff,0051ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0076ff,00eeff,0074ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00a2ff,00eeff,00a1ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00d8ff,00eeff,00d6ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0019ff,00eeff,00eeff,00eeff,0018ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0057ff,00eeff,00eeff,00eeff,0056ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0094ff,00eeff,00eeff,00eeff,0093ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,00ccff,00eeff,00eeff,00eeff,00cbff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,000bff,00ecff,00eeff,00eeff,00eeff,00ecff,000bff,0000ff,0000ff,000000
+16:0000ff,0000ff,0035ff,00eeff,00eeff,00eeff,00eeff,00eeff,0033ff,0000ff,0000ff,000000
+16:0000ff,0000ff,005fff,00eeff,00eeff,00eeff,00eeff,00eeff,005eff,0000ff,0000ff,000000
+16:0000ff,0000ff,0085ff,00eeff,00eeff,00eeff,00eeff,00eeff,0084ff,0000ff,0000ff,000000
+16:0000ff,0000ff,00a9ff,00eeff,00eeff,00eeff,00eeff,00eeff,00a7ff,0000ff,0000ff,000000
+16:0000ff,0001ff,00c6ff,00eeff,00eeff,00eeff,00eeff,00eeff,00c5ff,0001ff,0000ff,000000
+16:0000ff,0008ff,00daff,00eeff,00eeff,00eeff,00eeff,00eeff,00d9ff,0008ff,0000ff,000000
+16:0000ff,0016ff,00e5ff,00eeff,00eeff,00eeff,00eeff,00eeff,00e4ff,0015ff,0000ff,000000
+16:0000ff,0028ff,00eaff,00eeff,00eeff,00eeff,00eeff,00eeff,00eaff,0027ff,0000ff,000000
+16:0000ff,003cff,00ecff,00eeff,00eeff,00eeff,00eeff,00eeff,00ecff,003bff,0000ff,000000
+16:0000ff,0051ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,004fff,0000ff,000000
+16:0000ff,0065ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0064ff,0000ff,000000
+16:0000ff,0078ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0077ff,0000ff,000000
+16:0001ff,0089ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0088ff,0001ff,000000
+16:0002ff,0096ff,00eaff,00eaff,00eaff,00eaff,00eaff,00eaff,00eaff,0095ff,0002ff,000000
+16:0005ff,00a0ff,00e7ff,00e7ff,00e7ff,00e7ff,00e7ff,00e7ff,00e7ff,009fff,0005ff,000000
+16:0008ff,00a7ff,00e2ff,00e2ff,00e2ff,00e2ff,00e2ff,00e2ff,00e2ff,00a6ff,0008ff,000000
+16:000cff,00adff,00deff,00deff,00deff,00deff,00deff,00deff,00deff,00acff,000cff,000000
+16:0011ff,00b1ff,00daff,00daff,00daff,00daff,00daff,00daff,00daff,00b0ff,0011ff,000000
+16:0017ff,00b3ff,00d7ff,00d7ff,00d7ff,00d7ff,00d7ff,00d7ff,00d7ff,00b3ff,0017ff,000000
+16:001dff,00b3ff,00d2ff,00d2ff,00d2ff,00d2ff,00d2ff,00d2ff,00d2ff,00b3ff,001cff,000000
+16:0023ff,00b4ff,00ceff,00ceff,00ceff,00ceff,00ceff,00ceff,00ceff,00b3ff,0022ff,000000
+16:0028ff,00b4ff,00cbff,00cbff,00cbff,00cbff,00cbff,00cbff,00cbff,00b3ff,0028ff,000000
+16:002eff,00b3ff,00c7ff,00c7ff,00c7ff,00c7ff,00c7ff,00c7ff,00c7ff,00b2ff,002dff,000000
+16:0033ff,00b0ff,00c2ff,00c2ff,00c2ff,00c2ff,00c2ff,00c2ff,00c2ff,00b0ff,0032ff,000000
+16:0038ff,00aeff,00beff,00beff,00beff,00beff,00beff,00beff,00beff,00aeff,0037ff,000000
+16:003cff,00acff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00acff,003bff,000000
+16:0040ff,00a9ff,00b7ff,00b7ff,00b7ff,00b7ff,00b7ff,00b7ff,00b7ff,00a9ff,003fff,000000
+16:0043ff,00a6ff,00b2ff,00b2ff,00b2ff,00b2ff,00b2ff,00b2ff,00b2ff,00a5ff,0042ff,000000
+16:0046ff,00a3ff,00afff,00afff,00afff,00afff,00afff,00afff,00afff,00a3ff,0045ff,000000
+16:0048ff,00a0ff,00abff,00abff,00abff,00abff,00abff,00abff,00abff,00a0ff,0048ff,000000
+16:004aff,009dff,00a7ff,00a7ff,00a7ff,00a7ff,00a7ff,00a7ff,00a7ff,009cff,004aff,000000
+16:004bff,0099ff,00a2ff,00a2ff,00a2ff,00a2ff,00a2ff,00a2ff,00a2ff,0098ff,004bff,000000
+16:004cff,0095ff,009fff,009fff,009fff,009fff,009fff,009fff,009fff,0095ff,004cff,000000
+16:004dff,0092ff,009bff,009bff,009bff,009bff,009bff,009bff,009bff,0092ff,004cff,000000
+16:004dff,008eff,0097ff,0097ff,0097ff,0097ff,0097ff,0097ff,0097ff,008eff,004dff,000000
+16:004dff,008aff,0093ff,0093ff,0093ff,0093ff,0093ff,0093ff,0093ff,008aff,004dff,000000
+16:004dff,0087ff,008fff,008fff,008fff,008fff,008fff,008fff,008fff,0086ff,004cff,000000
+16:004cff,0083ff,008bff,008bff,008bff,008bff,008bff,008bff,008bff,0083ff,004cff,000000
+16:004cff,0080ff,0087ff,0087ff,0087ff,0087ff,0087ff,0087ff,0087ff,007fff,004bff,000000
+16:004afa,007bfc,0083fc,0083fc,0083fc,0083fc,0083fc,0083fc,0083fc,007bfc,004afa,000000
+16:0049f5,0078f8,007ff8,007ff8,007ff8,007ff8,007ff8,007ff8,007ff8,0077f8,0049f5,000000
+16:0048f0,0074f4,007bf4,007bf4,007bf4,007bf4,007bf4,007bf4,007bf4,0074f4,0048f0,000000
+16:0047ea,0070ef,0077f0,0077f0,0077f0,0077f0,0077f0,0077f0,0077f0,0070ef,0046ea,000000
+16:0045e5,006ceb,0073ec,0073ec,0073ec,0073ec,0073ec,0073ec,0073ec,006ceb,0045e5,000000
+16:0043df,0068e6,006fe7,006fe7,006fe7,006fe7,006fe7,006fe7,006fe7,0068e6,0043df,000000
+16:0041d9,0065e1,006be2,006be2,006be2,006be2,006be2,006be2,006be2,0065e1,0041d9,000000
+16:0040d3,0061db,0068dd,0068dd,0068dd,0068dd,0068dd,0068dd,0068dd,0061db,003fd3,000000
+16:003dcd,005dd6,0063d8,0063d8,0063d8,0063d8,0063d8,0063d8,0063d8,005cd6,003dcd,000000
+16:003bc7,0059d0,005fd2,005fd2,005fd2,005fd2,005fd2,005fd2,005fd2,0059d0,003bc7,000000
+16:0039c1,0055ca,005bcd,005bcd,005bcd,005bcd,005bcd,005bcd,005bcd,0055ca,0039c1,000000
+16:0037ba,0052c4,0058c6,0058c6,0058c6,0058c6,0058c6,0058c6,0058c6,0052c4,0037ba,000000
+16:0034b3,004dbd,0053c0,0053c0,0053c0,0053c0,0053c0,0053c0,0053c0,004dbd,0034b3,000000
+16:0032ac,004ab6,004fb9,004fb9,004fb9,004fb9,004fb9,004fb9,004fb9,004ab6,0032ac,000000
+16:0030a6,0046b0,004cb3,004cb3,004cb3,004cb3,004cb3,004cb3,004cb3,0046b0,0030a6,000000
+16:002e9e,0042a8,0048ab,0048ab,0048ab,0048ab,0048ab,0048ab,0048ab,0042a8,002e9e,000000
+16:002b97,003ea1,0043a4,0043a4,0043a4,0043a4,0043a4,0043a4,0043a4,003ea1,002b97,000000
+16:00288f,003b99,003f9c,003f9c,003f9c,003f9c,003f9c,003f9c,003f9c,003a99,00288f,000000
+16:002688,003792,003c95,003c95,003c95,003c95,003c95,003c95,003c95,003792,002688,000000
+16:002480,003389,00388c,00388c,00388c,00388c,00388c,00388c,00388c,003389,00247f,000000
+16:002178,002f81,003384,003384,003384,003384,003384,003384,003384,002f81,002178,000000
+16:001e6f,002c78,00307b,00307b,00307b,00307b,00307b,00307b,00307b,002b78,001e6f,000000
+16:001c67,002870,002c73,002c73,002c73,002c73,002c73,002c73,002c73,002870,001c67,000000
+16:001a5f,002467,002869,002869,002869,002869,002869,002869,002869,002467,001a5e,000000
+16:001756,00215d,002360,002360,002360,002360,002360,002360,002360,00215d,001756,000000
+16:00144d,001d54,002056,002056,002056,002056,002056,002056,002056,001d54,00144d,000000
+16:001244,00194b,001c4d,001c4d,001c4d,001c4d,001c4d,001c4d,001c4d,00194b,001244,000000
+16:00103b,001641,001842,001842,001842,001842,001842,001842,001842,001641,00103b,000000
+16:000d32,001236,001438,001438,001438,001438,001438,001438,001438,001236,000d32,000000
+16:000a28,000e2b,00102d,00102d,00102d,00102d,00102d,00102d,00102d,000e2b,000a28,000000
+16:00081e,000b22,000c23,000c23,000c23,000c23,000c23,000c23,000c23,000b22,00081e,000000
+16:000615,000717,000817,000817,000817,000817,000817,000817,000817,000717,000615,000000
+16:00030b,00040c,00040c,00040c,00040c,00040c,00040c,00040c,00040c,00040c,00030b,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/active-talking.animation b_Alexa LED Animation Files for AVS_linear_11/active-talking.animation
new file mode 100644
index 0000000..d79a708
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/active-talking.animation
@@ -0,0 +1,56 @@
+100:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+80:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+70:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+60:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+50:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+40:0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+40:0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+100:0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff
+40:0066FF,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+50:0088FF,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+60:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+70:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+80:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+90:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+100:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+80:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+70:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+60:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+50:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+40:0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+40:0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+100:0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff
+40:0066FF,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+50:0088FF,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+60:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+70:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+80:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+90:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
diff --git a_Alexa LED Animation Files for AVS_linear_11/active-thinking.animation b_Alexa LED Animation Files for AVS_linear_11/active-thinking.animation
new file mode 100644
index 0000000..321894b
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/active-thinking.animation
@@ -0,0 +1,41 @@
+16:0000ff,0000ff,0000ff,0000ff,0010ff,00eeff,000eff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0038ff,00eeff,0037ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,007eff,00eeff,007dff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00e7ff,00eeff,00e6ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0070ff,00eeff,00eeff,00eeff,006fff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0003ff,00e0ff,00eeff,00eeff,00eeff,00dfff,0003ff,0000ff,0000ff,000000
+16:0000ff,0000ff,004eff,00eeff,00eeff,00eeff,00eeff,00eeff,004dff,0000ff,0000ff,000000
+16:0000ff,0000ff,009eff,00eeff,00eeff,00eeff,00eeff,00eeff,009dff,0000ff,0000ff,000000
+16:0000ff,000bff,00d1ff,00eeff,00eeff,00eeff,00eeff,00eeff,00d0ff,000bff,0000ff,000000
+16:0000ff,002cff,00e4ff,00eeff,00eeff,00eeff,00eeff,00eeff,00e4ff,002cff,0000ff,000000
+16:0000ff,0055ff,00eaff,00eeff,00eeff,00eeff,00eeff,00eeff,00eaff,0053ff,0000ff,000000
+16:0002ff,0079ff,00ecff,00eeff,00eeff,00eeff,00eeff,00eeff,00ecff,0078ff,0002ff,000000
+16:0009ff,0095ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,0094ff,0008ff,000000
+16:0014ff,00a9ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00a8ff,0014ff,000000
+16:0022ff,00b7ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00b6ff,0022ff,000000
+16:0032ff,00c0ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00bfff,0031ff,000000
+16:0041ff,00c6ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00c5ff,0040ff,000000
+16:004fff,00caff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00c9ff,004eff,000000
+16:005aff,00cdff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00ccff,005aff,000000
+16:0065ff,00cfff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00ceff,0064ff,000000
+16:006dff,00d0ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00cfff,006cff,000000
+16:0074ff,00d0ff,00edff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,00d0ff,0073ff,000000
+16:007aff,00d0ff,00ecff,00eeff,00eeff,00eeff,00eeff,00eeff,00ecff,00d0ff,0079ff,000000
+16:007eff,00d0ff,00ecff,00eeff,00eeff,00eeff,00eeff,00eeff,00ecff,00d0ff,007eff,000000
+16:0082ff,00d0ff,00ebff,00eeff,00eeff,00eeff,00eeff,00eeff,00ebff,00d0ff,0082ff,000000
+16:007dff,00c4ff,00ddff,00dfff,00dfff,00dfff,00dfff,00dfff,00ddff,00c4ff,007dff,000000
+16:0078ff,00b8ff,00ceff,00d0ff,00d0ff,00d0ff,00d0ff,00d0ff,00ceff,00b8ff,0077ff,000000
+16:0072ff,00acff,00bfff,00c1ff,00c1ff,00c1ff,00c1ff,00c1ff,00bfff,00acff,0071ff,000000
+16:006bff,00a0ff,00b1ff,00b2ff,00b2ff,00b2ff,00b2ff,00b2ff,00b1ff,00a0ff,006aff,000000
+16:0063ff,0093ff,00a2ff,00a3ff,00a3ff,00a3ff,00a3ff,00a3ff,00a2ff,0093ff,0063ff,000000
+16:005bff,0086ff,0093ff,0094ff,0094ff,0094ff,0094ff,0094ff,0093ff,0086ff,005bff,000000
+16:0053ff,0079ff,0085ff,0085ff,0085ff,0085ff,0085ff,0085ff,0085ff,0079ff,0053ff,000000
+16:004bff,006cff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,006cff,004bff,000000
+16:0042ff,005fff,0068ff,0069ff,0069ff,0069ff,0069ff,0069ff,0068ff,005fff,0042ff,000000
+16:0039ff,0052ff,0059ff,005aff,005aff,005aff,005aff,005aff,0059ff,0052ff,0039ff,000000
+16:0030ff,0044ff,004bff,004bff,004bff,004bff,004bff,004bff,004bff,0044ff,0030ff,000000
+16:0027ff,0036ff,003cff,003cff,003cff,003cff,003cff,003cff,003cff,0036ff,0026ff,000000
+16:001dff,0029ff,002dff,002dff,002dff,002dff,002dff,002dff,002dff,0029ff,001dff,000000
+16:0013ff,001bff,001eff,001eff,001eff,001eff,001eff,001eff,001eff,001bff,0013ff,000000
+16:0009ff,000eff,000fff,000fff,000fff,000fff,000fff,000fff,000fff,000eff,0009ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/active-waking.animation b_Alexa LED Animation Files for AVS_linear_11/active-waking.animation
new file mode 100644
index 0000000..efea422
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/active-waking.animation
@@ -0,0 +1,31 @@
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0049ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,004dff,000000
+16:00e8ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,00ebff,000000
+16:00eeff,00d1ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,00d4ff,00eeff,000000
+16:004dff,00eeff,00a5ff,0000ff,0000ff,0000ff,0000ff,0000ff,00a8ff,00eeff,004aff,000000
+16:0000ff,00a5ff,00eeff,0048ff,0000ff,0000ff,0000ff,004aff,00eeff,00a2ff,0000ff,000000
+16:0000ff,0025ff,00eeff,00c1ff,0000ff,0000ff,0000ff,00c3ff,00eeff,0023ff,0000ff,000000
+16:0000ff,0000ff,00b8ff,00eeff,0026ff,0000ff,0028ff,00eeff,00b6ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0062ff,00eeff,0074ff,0000ff,0076ff,00eeff,0060ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0019ff,00eeff,00b4ff,0000ff,00b6ff,00eeff,0017ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,00d4ff,00eaff,0000ff,00ecff,00d2ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,009cff,00eeff,003dff,00eeff,009aff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,006aff,00eeff,008aff,00eeff,0069ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,003eff,00eeff,00cdff,00eeff,003cff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0017ff,00eeff,00eeff,00eeff,0015ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00eeff,00eeff,00ecff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00ceff,00eeff,00ccff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00b1ff,00eeff,00b0ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0098ff,00eeff,0096ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0081ff,00eeff,007fff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,006cff,00eeff,006bff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,005aff,00eeff,0058ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,004aff,00eeff,0048ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,003cff,00eeff,003bff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0030ff,00eeff,002fff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0026ff,00eeff,0025ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,001eff,00eeff,001dff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0018ff,00eeff,0016ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0013ff,00eeff,0012ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0011ff,00eeff,000fff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0010ff,00eeff,000fff,0000ff,0000ff,0000ff,0000ff,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/alert-short.animation b_Alexa LED Animation Files for AVS_linear_11/alert-short.animation
new file mode 100644
index 0000000..a0377ea
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/alert-short.animation
@@ -0,0 +1,89 @@
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00e2ff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,009bff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,0035ff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00e8ff,0000ff,00e9ff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00a0ff,0000ff,00a2ff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,0051ff,0000ff,0053ff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,0000ff,0000ff,0000ff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00afff,0000ff,0000ff,0000ff,00b1ff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,0052ff,0000ff,0000ff,0000ff,0053ff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00fdff,0000ff,0000ff,0000ff,0000ff,0000ff,00feff,00ffff,00ffff,000000
+16:00ffff,00ffff,009bff,0000ff,0000ff,0000ff,0000ff,0000ff,009cff,00ffff,00ffff,000000
+16:00ffff,00ffff,0036ff,0000ff,0000ff,0000ff,0000ff,0000ff,0038ff,00ffff,00ffff,000000
+16:00ffff,00deff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,00e0ff,00ffff,000000
+16:00ffff,007dff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,007eff,00ffff,000000
+16:00ffff,0024ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0026ff,00ffff,000000
+16:00ffff,0073ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0074ff,00ffff,000000
+16:00ffff,00ddff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,00deff,00ffff,000000
+16:00ffff,00ffff,0046ff,0000ff,0000ff,0000ff,0000ff,0000ff,0047ff,00ffff,00ffff,000000
+16:00ffff,00ffff,00baff,0000ff,0000ff,0000ff,0000ff,0000ff,00bbff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,001bff,0000ff,0000ff,0000ff,001cff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,007eff,0000ff,0000ff,0000ff,0080ff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00d7ff,0000ff,0000ff,0000ff,00d8ff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,0019ff,0000ff,001bff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,005eff,0000ff,005fff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,009aff,0000ff,009bff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ceff,0000ff,00cfff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00faff,0000ff,00fbff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,0026ff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,0064ff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,0096ff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00bdff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00daff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00efff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00faff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
+16:00f5ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00f7ff,000000
+16:00ceff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00cfff,000000
+16:0096ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0097ff,000000
+16:0051ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0052ff,000000
+16:0002ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0003ff,000000
+16:0000ff,00b7ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00b9ff,0000ff,000000
+16:0000ff,005aff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,005bff,0000ff,000000
+16:0000ff,0000ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0000ff,0000ff,000000
+16:0000ff,0000ff,009cff,00ffff,00ffff,00ffff,00ffff,00ffff,009eff,0000ff,0000ff,000000
+16:0000ff,0000ff,0032ff,00ffff,00ffff,00ffff,00ffff,00ffff,0033ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,00d1ff,00ffff,00ffff,00ffff,00d2ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0062ff,00ffff,00ffff,00ffff,0064ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00feff,00ffff,00ffff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0094ff,00ffff,0096ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0033ff,00ffff,0034ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0089ff,00ffff,008bff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00feff,00ffff,00feff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0073ff,00ffff,00ffff,00ffff,0075ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,00f4ff,00ffff,00ffff,00ffff,00f5ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0060ff,00ffff,00ffff,00ffff,00ffff,00ffff,0061ff,0000ff,0000ff,000000
+16:0000ff,0000ff,00cdff,00ffff,00ffff,00ffff,00ffff,00ffff,00cfff,0000ff,0000ff,000000
+16:0000ff,0023ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0024ff,0000ff,000000
+16:0000ff,0079ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,007bff,0000ff,000000
+16:0000ff,00c5ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00c7ff,0000ff,000000
+16:0000ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0000ff,000000
+16:0034ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0035ff,000000
+16:0064ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,0066ff,000000
+16:008eff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,008fff,000000
+16:00afff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00b1ff,000000
+16:00cbff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00cdff,000000
+16:00e1ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00e2ff,000000
+16:00f1ff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00f2ff,000000
+16:00fcff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00fdff,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/alert.animation b_Alexa LED Animation Files for AVS_linear_11/alert.animation
new file mode 100644
index 0000000..8286596
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/alert.animation
@@ -0,0 +1,89 @@
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00d4ff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,0091ff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,0032ff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00d9ff,0000ff,00daff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,0096ff,0000ff,0097ff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,004cff,0000ff,004eff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,0000ff,0000ff,0000ff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00a5ff,0000ff,0000ff,0000ff,00a6ff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,004dff,0000ff,0000ff,0000ff,004fff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00edff,0000ff,0000ff,0000ff,0000ff,0000ff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,0092ff,0000ff,0000ff,0000ff,0000ff,0000ff,0093ff,00eeff,00eeff,000000
+16:00eeff,00eeff,0034ff,0000ff,0000ff,0000ff,0000ff,0000ff,0036ff,00eeff,00eeff,000000
+16:00eeff,00d1ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,00d3ff,00eeff,000000
+16:00eeff,0076ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0077ff,00eeff,000000
+16:00eeff,0024ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0025ff,00eeff,000000
+16:00eeff,006dff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,006eff,00eeff,000000
+16:00eeff,00d0ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,00d1ff,00eeff,000000
+16:00eeff,00eeff,0043ff,0000ff,0000ff,0000ff,0000ff,0000ff,0044ff,00eeff,00eeff,000000
+16:00eeff,00eeff,00afff,0000ff,0000ff,0000ff,0000ff,0000ff,00b0ff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,001aff,0000ff,0000ff,0000ff,001bff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,0077ff,0000ff,0000ff,0000ff,0078ff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00caff,0000ff,0000ff,0000ff,00cbff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,0018ff,0000ff,001aff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,0058ff,0000ff,005aff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,0090ff,0000ff,0091ff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00c0ff,0000ff,00c2ff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00e9ff,0000ff,00ebff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,0024ff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,005eff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,008cff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00b1ff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00cdff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00e0ff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eaff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
+16:00e5ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00e6ff,000000
+16:00c0ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00c2ff,000000
+16:008cff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,008dff,000000
+16:004cff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,004dff,000000
+16:0002ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0003ff,000000
+16:0000ff,00acff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00adff,0000ff,000000
+16:0000ff,0055ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0056ff,0000ff,000000
+16:0000ff,0000ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0000ff,0000ff,000000
+16:0000ff,0000ff,0093ff,00eeff,00eeff,00eeff,00eeff,00eeff,0094ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0030ff,00eeff,00eeff,00eeff,00eeff,00eeff,0031ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,00c5ff,00eeff,00eeff,00eeff,00c6ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,005dff,00eeff,00eeff,00eeff,005fff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00eeff,00eeff,00eeff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,008cff,00eeff,008eff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0031ff,00eeff,0033ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,0082ff,00eeff,0083ff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,0000ff,00edff,00eeff,00eeff,0000ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,006dff,00eeff,00eeff,00eeff,006fff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,0000ff,00e5ff,00eeff,00eeff,00eeff,00e6ff,0000ff,0000ff,0000ff,000000
+16:0000ff,0000ff,005aff,00eeff,00eeff,00eeff,00eeff,00eeff,005cff,0000ff,0000ff,000000
+16:0000ff,0000ff,00c1ff,00eeff,00eeff,00eeff,00eeff,00eeff,00c2ff,0000ff,0000ff,000000
+16:0000ff,0021ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0023ff,0000ff,000000
+16:0000ff,0072ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0073ff,0000ff,000000
+16:0000ff,00b9ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00baff,0000ff,000000
+16:0000ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0000ff,000000
+16:0031ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0032ff,000000
+16:005eff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,005fff,000000
+16:0084ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,0086ff,000000
+16:00a4ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00a5ff,000000
+16:00beff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00bfff,000000
+16:00d2ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00d3ff,000000
+16:00e1ff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00e2ff,000000
+16:00ecff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00edff,000000
+16:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/btconnect.animation b_Alexa LED Animation Files for AVS_linear_11/btconnect.animation
new file mode 100755
index 0000000..f4fa18c
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/btconnect.animation
@@ -0,0 +1,23 @@
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000BB,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000EE,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000FF,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/btdisconnect.animation b_Alexa LED Animation Files for AVS_linear_11/btdisconnect.animation
new file mode 100755
index 0000000..f4fa18c
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/btdisconnect.animation
@@ -0,0 +1,23 @@
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000BB,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000EE,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000FF,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/do_not_disturb.animation b_Alexa LED Animation Files for AVS_linear_11/do_not_disturb.animation
new file mode 100644
index 0000000..32b8150
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/do_not_disturb.animation
@@ -0,0 +1,110 @@
+16:0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,000000
+16:0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,000000
+16:10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,000000
+16:120025,120025,120025,120025,120025,120025,120025,120025,120025,120025,120025,000000
+16:15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,000000
+16:180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,000000
+16:1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,000000
+16:1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,000000
+16:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,000000
+16:220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,000000
+16:24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,000000
+16:27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,000000
+16:290053,290053,290053,290053,290053,290053,290053,290053,290053,290053,290053,000000
+16:2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,000000
+16:2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,000000
+16:2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,000000
+16:320065,320065,320065,320065,320065,320065,320065,320065,320065,320065,320065,000000
+16:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,000000
+16:36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,000000
+16:380072,380072,380072,380072,380072,380072,380072,380072,380072,380072,380072,000000
+16:3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,000000
+16:3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,000000
+16:3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,000000
+16:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,000000
+16:420086,420086,420086,420086,420086,420086,420086,420086,420086,420086,420086,000000
+16:430088,430088,430088,430088,430088,430088,430088,430088,430088,430088,430088,000000
+16:45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,000000
+16:46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,000000
+16:47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,000000
+16:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,000000
+16:490093,490093,490093,490093,490093,490093,490093,490093,490093,490093,490093,000000
+16:4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,000000
+16:4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,000000
+16:4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,000000
+16:4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,000000
+16:4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,000000
+16:5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,000000
+16:5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,000000
+16:5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,000000
+16:5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,000000
+16:5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,000000
+16:5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,000000
+16:4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,000000
+16:4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,000000
+16:4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,000000
+16:4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,000000
+16:4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,000000
+16:4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,000000
+16:490092,490092,490092,490092,490092,490092,490092,490092,490092,490092,490092,000000
+16:480090,480090,480090,480090,480090,480090,480090,480090,480090,480090,480090,000000
+16:47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,000000
+16:46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,000000
+16:45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,000000
+16:440087,440087,440087,440087,440087,440087,440087,440087,440087,440087,440087,000000
+16:420085,420085,420085,420085,420085,420085,420085,420085,420085,420085,420085,000000
+16:410082,410082,410082,410082,410082,410082,410082,410082,410082,410082,410082,000000
+16:400080,400080,400080,400080,400080,400080,400080,400080,400080,400080,400080,000000
+16:3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,000000
+16:3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,000000
+16:3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,000000
+16:3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,000000
+16:390073,390073,390073,390073,390073,390073,390073,390073,390073,390073,390073,000000
+16:380070,380070,380070,380070,380070,380070,380070,380070,380070,380070,380070,000000
+16:37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,000000
+16:36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,000000
+16:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,000000
+16:330066,330066,330066,330066,330066,330066,330066,330066,330066,330066,330066,000000
+16:320064,320064,320064,320064,320064,320064,320064,320064,320064,320064,320064,000000
+16:310061,310061,310061,310061,310061,310061,310061,310061,310061,310061,310061,000000
+16:2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,000000
+16:2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,000000
+16:2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,000000
+16:2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,000000
+16:2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,000000
+16:290052,290052,290052,290052,290052,290052,290052,290052,290052,290052,290052,000000
+16:28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,000000
+16:26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,000000
+16:25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,000000
+16:240047,240047,240047,240047,240047,240047,240047,240047,240047,240047,240047,000000
+16:220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,000000
+16:210042,210042,210042,210042,210042,210042,210042,210042,210042,210042,210042,000000
+16:200040,200040,200040,200040,200040,200040,200040,200040,200040,200040,200040,000000
+16:1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,000000
+16:1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,000000
+16:1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,000000
+16:1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,000000
+16:190033,190033,190033,190033,190033,190033,190033,190033,190033,190033,190033,000000
+16:180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,000000
+16:17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,000000
+16:16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,000000
+16:140029,140029,140029,140029,140029,140029,140029,140029,140029,140029,140029,000000
+16:130026,130026,130026,130026,130026,130026,130026,130026,130026,130026,130026,000000
+16:120024,120024,120024,120024,120024,120024,120024,120024,120024,120024,120024,000000
+16:110021,110021,110021,110021,110021,110021,110021,110021,110021,110021,110021,000000
+16:0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,000000
+16:0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,000000
+16:0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,000000
+16:0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,000000
+16:0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,000000
+16:090012,090012,090012,090012,090012,090012,090012,090012,090012,090012,090012,000000
+16:08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,000000
+16:06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,000000
+16:05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,000000
+16:040008,040008,040008,040008,040008,040008,040008,040008,040008,040008,040008,000000
+16:030006,030006,030006,030006,030006,030006,030006,030006,030006,030006,030006,000000
+16:020004,020004,020004,020004,020004,020004,020004,020004,020004,020004,020004,000000
+16:010002,010002,010002,010002,010002,010002,010002,010002,010002,010002,010002,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/error.animation b_Alexa LED Animation Files for AVS_linear_11/error.animation
new file mode 100644
index 0000000..1f777e0
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/error.animation
@@ -0,0 +1,86 @@
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:A00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:E00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
diff --git a_Alexa LED Animation Files for AVS_linear_11/mics-off_end.animation b_Alexa LED Animation Files for AVS_linear_11/mics-off_end.animation
new file mode 100755
index 0000000..0c6c787
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/mics-off_end.animation
@@ -0,0 +1,12 @@
+16:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+16:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+16:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+16:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+16:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
+16:880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000
+16:660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000
+16:550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000
+16:330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000
+16:110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/mics-off_on.animation b_Alexa LED Animation Files for AVS_linear_11/mics-off_on.animation
new file mode 100644
index 0000000..12da7fd
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/mics-off_on.animation
@@ -0,0 +1,8 @@
+66:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+66:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+66:DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000
+66:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+66:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+66:AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000
+loop
+1000:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
diff --git a_Alexa LED Animation Files for AVS_linear_11/mics-off_start.animation b_Alexa LED Animation Files for AVS_linear_11/mics-off_start.animation
new file mode 100644
index 0000000..38b6a25
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/mics-off_start.animation
@@ -0,0 +1,17 @@
+33:110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000
+33:220000,220000,220000,220000,220000,220000,220000,220000,220000,220000,220000,220000
+33:330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000
+33:440000,440000,440000,440000,440000,440000,440000,440000,440000,440000,440000,440000
+33:550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000
+33:660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000
+33:770000,770000,770000,770000,770000,770000,770000,770000,770000,770000,770000,770000
+33:880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000
+33:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
+33:AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000
+33:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+33:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+33:DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000
+33:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+loop
+1000:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+
diff --git a_Alexa LED Animation Files for AVS_linear_11/ntf_incoming.animation b_Alexa LED Animation Files for AVS_linear_11/ntf_incoming.animation
new file mode 100644
index 0000000..cb60029
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/ntf_incoming.animation
@@ -0,0 +1,172 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,000000
+16:0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,000000
+16:120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,000000
+16:181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,000000
+16:1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,000000
+16:2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,000000
+16:352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,000000
+16:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,000000
+16:413600,413600,413600,413600,413600,413600,413600,413600,413600,413600,413600,000000
+16:473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,000000
+16:4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,000000
+16:534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,000000
+16:594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,000000
+16:5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,000000
+16:655400,655400,655400,655400,655400,655400,655400,655400,655400,655400,655400,000000
+16:6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,000000
+16:715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,000000
+16:776300,776300,776300,776300,776300,776300,776300,776300,776300,776300,776300,000000
+16:7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,000000
+16:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,000000
+16:887100,887100,887100,887100,887100,887100,887100,887100,887100,887100,887100,000000
+16:8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,000000
+16:947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,000000
+16:9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,000000
+16:a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,000000
+16:a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,000000
+16:ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,000000
+16:b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,000000
+16:b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,000000
+16:be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,000000
+16:c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,000000
+16:caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,000000
+16:d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,000000
+16:e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,000000
+16:edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,000000
+16:f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,000000
+16:f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,000000
+16:f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,000000
+16:edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,000000
+16:e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,000000
+16:e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,000000
+16:c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,000000
+16:c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,000000
+16:bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,000000
+16:b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,000000
+16:b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,000000
+16:aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,000000
+16:a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,000000
+16:9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,000000
+16:987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,000000
+16:927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,000000
+16:8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,000000
+16:866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,000000
+16:806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,000000
+16:796500,796500,796500,796500,796500,796500,796500,796500,796500,796500,796500,000000
+16:736000,736000,736000,736000,736000,736000,736000,736000,736000,736000,736000,000000
+16:6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,000000
+16:675600,675600,675600,675600,675600,675600,675600,675600,675600,675600,675600,000000
+16:615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,000000
+16:5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,000000
+16:554700,554700,554700,554700,554700,554700,554700,554700,554700,554700,554700,000000
+16:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,000000
+16:493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,000000
+16:433800,433800,433800,433800,433800,433800,433800,433800,433800,433800,433800,000000
+16:3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,000000
+16:372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,000000
+16:312800,312800,312800,312800,312800,312800,312800,312800,312800,312800,312800,000000
+16:2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,000000
+16:181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,000000
+16:120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,000000
+16:0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,000000
+16:060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_11/ntf_queued.animation b_Alexa LED Animation Files for AVS_linear_11/ntf_queued.animation
new file mode 100644
index 0000000..0a6a7e7
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_11/ntf_queued.animation
@@ -0,0 +1,150 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,000000
+16:0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,000000
+16:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,000000
+16:141100,141100,141100,141100,141100,141100,141100,141100,141100,141100,141100,000000
+16:1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,000000
+16:1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,000000
+16:2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,000000
+16:332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,000000
+16:382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,000000
+16:3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,000000
+16:423700,423700,423700,423700,423700,423700,423700,423700,423700,423700,423700,000000
+16:473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,000000
+16:4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,000000
+16:524400,524400,524400,524400,524400,524400,524400,524400,524400,524400,524400,000000
+16:574800,574800,574800,574800,574800,574800,574800,574800,574800,574800,574800,000000
+16:5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,000000
+16:615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,000000
+16:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,000000
+16:6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,000000
+16:705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,000000
+16:756200,756200,756200,756200,756200,756200,756200,756200,756200,756200,756200,000000
+16:7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,000000
+16:806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,000000
+16:856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,000000
+16:8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,000000
+16:8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,000000
+16:947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,000000
+16:997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,000000
+16:9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,000000
+16:a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,000000
+16:a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,000000
+16:ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,000000
+16:b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,000000
+16:b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,000000
+16:bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,000000
+16:c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,000000
+16:c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,000000
+16:ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,000000
+16:d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,000000
+16:d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,000000
+16:e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,000000
+16:ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,000000
+16:f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,000000
+16:f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,000000
+16:fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,000000
+16:f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,000000
+16:efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,000000
+16:eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,000000
+16:e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,000000
+16:e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,000000
+16:cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,000000
+16:c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,000000
+16:c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,000000
+16:bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,000000
+16:b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,000000
+16:b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,000000
+16:ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,000000
+16:a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,000000
+16:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,000000
+16:9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,000000
+16:977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,000000
+16:927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,000000
+16:8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,000000
+16:877000,877000,877000,877000,877000,877000,877000,877000,877000,877000,877000,000000
+16:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,000000
+16:7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,000000
+16:786400,786400,786400,786400,786400,786400,786400,786400,786400,786400,786400,000000
+16:725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,000000
+16:6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,000000
+16:685700,685700,685700,685700,685700,685700,685700,685700,685700,685700,685700,000000
+16:635200,635200,635200,635200,635200,635200,635200,635200,635200,635200,635200,000000
+16:5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,000000
+16:584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,000000
+16:534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,000000
+16:4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,000000
+16:493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,000000
+16:443800,443800,443800,443800,443800,443800,443800,443800,443800,443800,443800,000000
+16:3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,000000
+16:393000,393000,393000,393000,393000,393000,393000,393000,393000,393000,393000,000000
+16:342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,000000
+16:2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,000000
+16:2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,000000
+16:1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,000000
+16:151100,151100,151100,151100,151100,151100,151100,151100,151100,151100,151100,000000
+16:100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,000000
+16:0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,000000
+16:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+1500:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/active-ending.animation b_Alexa LED Animation Files for AVS_linear_5/active-ending.animation
new file mode 100755
index 0000000..69f9216
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/active-ending.animation
@@ -0,0 +1,32 @@
+16:00ffff,0000ff,0000ff,0000ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0000ff,0000ff,0000ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0000ff,0000ff,0000ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00fafb,0004ff,0000ff,0005ff,00f9f9,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000cff,0000ff,000dff,00f1f1,000000,000000,000000,000000,000000,000000,000000
+16:00e8e9,0016ff,0000ff,0017ff,00e7e7,000000,000000,000000,000000,000000,000000,000000
+16:00dddd,0021ff,0000ff,0023ff,00dbdc,000000,000000,000000,000000,000000,000000,000000
+16:00d0d0,002eff,0000ff,0030ff,00cecf,000000,000000,000000,000000,000000,000000,000000
+16:00c2c2,003dff,0000ff,003eff,00c1c1,000000,000000,000000,000000,000000,000000,000000
+16:00b2b3,004cff,0000ff,004dff,00b1b1,000000,000000,000000,000000,000000,000000,000000
+16:00a2a2,005cff,0000ff,005dff,00a1a1,000000,000000,000000,000000,000000,000000,000000
+16:009091,006dff,0000ff,006fff,008f90,000000,000000,000000,000000,000000,000000,000000
+16:007f7f,0080ff,0000ff,0081ff,007d7e,000000,000000,000000,000000,000000,000000,000000
+16:006b6c,0093ff,0000ff,0094ff,006a6a,000000,000000,000000,000000,000000,000000,000000
+16:005858,00a7ff,0000ff,00a8ff,005757,000000,000000,000000,000000,000000,000000,000000
+16:004344,00bbff,0000ff,00bdff,004242,000000,000000,000000,000000,000000,000000,000000
+16:002e2e,00d0ff,0000ff,00d2ff,002d2d,000000,000000,000000,000000,000000,000000,000000
+16:001919,00e6ff,0000ff,00e8ff,001717,000000,000000,000000,000000,000000,000000,000000
+16:000202,00fcff,0000ff,00fdff,000101,000000,000000,000000,000000,000000,000000,000000
+16:000000,00f8f8,000eff,00f6f7,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,00e1e1,003cff,00e0e0,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,00caca,006bff,00c8c9,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,00b2b2,009aff,00b1b1,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,009a9a,00caff,009899,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,008282,00faff,008081,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,006a6a,00ffff,006869,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,005252,00ffff,005051,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,003a3a,00ffff,003939,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,002424,00ffff,002222,000000,000000,000000,000000,000000,000000,000000,000000
+16:000000,000d0e,00ffff,000c0c,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/active-talking.animation b_Alexa LED Animation Files for AVS_linear_5/active-talking.animation
new file mode 100644
index 0000000..d79a708
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/active-talking.animation
@@ -0,0 +1,56 @@
+100:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+80:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+70:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+60:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+50:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+40:0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+40:0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+100:0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff
+40:0066FF,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+50:0088FF,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+60:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+70:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+80:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+90:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+100:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+80:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+70:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+60:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+50:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+40:0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+40:0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+100:0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff
+40:0066FF,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+50:0088FF,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+60:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+70:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+80:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+90:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
diff --git a_Alexa LED Animation Files for AVS_linear_5/active-thinking.animation b_Alexa LED Animation Files for AVS_linear_5/active-thinking.animation
new file mode 100755
index 0000000..768113e
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/active-thinking.animation
@@ -0,0 +1,40 @@
+16:0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0002ff,0000ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0000ff,000cff,0000ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0007ff,0023ff,0007ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0024ff,004eff,0024ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0067ff,0099ff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00d9ff,00ffff,00d7ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00feff,00ffff,00fcff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0011ff,00ffff,00ffff,00ffff,000fff,000000,000000,000000,000000,000000,000000,000000
+16:002cff,00ffff,00ffff,00ffff,002aff,000000,000000,000000,000000,000000,000000,000000
+16:0043ff,00ffff,00ffff,00ffff,0042ff,000000,000000,000000,000000,000000,000000,000000
+16:0058ff,00ffff,00ffff,00ffff,0057ff,000000,000000,000000,000000,000000,000000,000000
+16:006aff,00ffff,00ffff,00ffff,0069ff,000000,000000,000000,000000,000000,000000,000000
+16:007bff,00ffff,00ffff,00ffff,0079ff,000000,000000,000000,000000,000000,000000,000000
+16:008aff,00ffff,00ffff,00ffff,0088ff,000000,000000,000000,000000,000000,000000,000000
+16:0097ff,00ffff,00ffff,00ffff,0096ff,000000,000000,000000,000000,000000,000000,000000
+16:00a3ff,00ffff,00ffff,00ffff,00a2ff,000000,000000,000000,000000,000000,000000,000000
+16:00aeff,00ffff,00ffff,00ffff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:00b8ff,00ffff,00ffff,00ffff,00b7ff,000000,000000,000000,000000,000000,000000,000000
+16:00c1ff,00ffff,00ffff,00ffff,00bfff,000000,000000,000000,000000,000000,000000,000000
+16:00c9ff,00ffff,00ffff,00ffff,00c8ff,000000,000000,000000,000000,000000,000000,000000
+16:00d1ff,00ffff,00ffff,00ffff,00cfff,000000,000000,000000,000000,000000,000000,000000
+16:00d7ff,00ffff,00ffff,00ffff,00d6ff,000000,000000,000000,000000,000000,000000,000000
+16:00deff,00ffff,00ffff,00ffff,00ddff,000000,000000,000000,000000,000000,000000,000000
+16:00baff,00d0ff,00d0ff,00d0ff,00b8ff,000000,000000,000000,000000,000000,000000,000000
+16:0095ff,00a4ff,00a4ff,00a4ff,0095ff,000000,000000,000000,000000,000000,000000,000000
+16:0074ff,007dff,007dff,007dff,0073ff,000000,000000,000000,000000,000000,000000,000000
+16:0058ff,005dff,005dff,005dff,0057ff,000000,000000,000000,000000,000000,000000,000000
+16:0040ff,0043ff,0043ff,0043ff,0040ff,000000,000000,000000,000000,000000,000000,000000
+16:002eff,002fff,002fff,002fff,002dff,000000,000000,000000,000000,000000,000000,000000
+16:001fff,0020ff,0020ff,0020ff,001fff,000000,000000,000000,000000,000000,000000,000000
+16:0016ff,0016ff,0016ff,0016ff,0016ff,000000,000000,000000,000000,000000,000000,000000
+16:000eff,000eff,000eff,000eff,000eff,000000,000000,000000,000000,000000,000000,000000
+16:0009ff,0009ff,0009ff,0009ff,0009ff,000000,000000,000000,000000,000000,000000,000000
+16:0006ff,0006ff,0006ff,0006ff,0006ff,000000,000000,000000,000000,000000,000000,000000
+16:0004ff,0004ff,0004ff,0004ff,0004ff,000000,000000,000000,000000,000000,000000,000000
+16:0003ff,0003ff,0003ff,0003ff,0003ff,000000,000000,000000,000000,000000,000000,000000
+16:0002ff,0002ff,0002ff,0002ff,0002ff,000000,000000,000000,000000,000000,000000,000000
+16:0001ff,0001ff,0001ff,0001ff,0001ff,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/active-waking.animation b_Alexa LED Animation Files for AVS_linear_5/active-waking.animation
new file mode 100644
index 0000000..9227f1e
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/active-waking.animation
@@ -0,0 +1,20 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d52,000007,000007,000007,005156,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00000e,00000e,00000e,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:007781,008891,000013,008a93,00747e,000000,000000,000000,000000,000000,000000,000000
+16:00182c,00e7e9,000017,00e9eb,00152a,000000,000000,000000,000000,000000,000000,000000
+16:00001a,00e0e3,003e52,00dee2,00001a,000000,000000,000000,000000,000000,000000,000000
+16:00001d,00adb6,00a4af,00abb5,00001d,000000,000000,000000,000000,000000,000000,000000
+16:000020,008695,00f4f6,008393,000020,000000,000000,000000,000000,000000,000000,000000
+16:000023,00657b,00ffff,006479,000023,000000,000000,000000,000000,000000,000000,000000
+16:000028,004c68,00ffff,004a67,000028,000000,000000,000000,000000,000000,000000,000000
+16:00002d,00375a,00ffff,003559,00002d,000000,000000,000000,000000,000000,000000,000000
+16:000035,002653,00ffff,002552,000035,000000,000000,000000,000000,000000,000000,000000
+16:00003f,001952,00ffff,001851,00003f,000000,000000,000000,000000,000000,000000,000000
+16:00004c,000e56,00ffff,000d55,00004c,000000,000000,000000,000000,000000,000000,000000
+16:00005e,000662,00ffff,000561,00005e,000000,000000,000000,000000,000000,000000,000000
+16:00007a,00017a,00ffff,00007a,00007a,000000,000000,000000,000000,000000,000000,000000
+16:00009c,00009c,00ffff,00009c,00009c,000000,000000,000000,000000,000000,000000,000000
+16:0000ca,0000ca,00ffff,0000ca,0000ca,000000,000000,000000,000000,000000,000000,000000
+loop
+1000:0000ca,0000ca,00ffff,0000ca,0000ca,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/alert-short.animation b_Alexa LED Animation Files for AVS_linear_5/alert-short.animation
new file mode 100755
index 0000000..54ba22d
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/alert-short.animation
@@ -0,0 +1,266 @@
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f0ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ccff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,005bff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0013ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00edff,0000ff,00efff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00c3ff,0000ff,00c4ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0096ff,0000ff,0097ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0067ff,0000ff,0068ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0036ff,0000ff,0037ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0004ff,0000ff,0006ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,00e0ff,000000,000000,000000,000000,000000,000000,000000
+16:00acff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:007bff,0000ff,0000ff,0000ff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:004eff,0000ff,0000ff,0000ff,0050ff,000000,000000,000000,000000,000000,000000,000000
+16:0076ff,0000ff,0000ff,0000ff,0077ff,000000,000000,000000,000000,000000,000000,000000
+16:00abff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,0000ff,0000ff,0000ff,00e7ff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0014ff,0000ff,0015ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,004bff,0000ff,004cff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,007dff,0000ff,007eff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00aaff,0000ff,00abff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00d1ff,0000ff,00d2ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00f4ff,0000ff,00f5ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,000cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0040ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,006cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0091ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00b1ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ddff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ecff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f7ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00fcff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00efff,000000,000000,000000,000000,000000,000000,000000
+16:00daff,00ffff,00ffff,00ffff,00d9ff,000000,000000,000000,000000,000000,000000,000000
+16:00bfff,00ffff,00ffff,00ffff,00beff,000000,000000,000000,000000,000000,000000,000000
+16:00a0ff,00ffff,00ffff,00ffff,009fff,000000,000000,000000,000000,000000,000000,000000
+16:007eff,00ffff,00ffff,00ffff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:0059ff,00ffff,00ffff,00ffff,0057ff,000000,000000,000000,000000,000000,000000,000000
+16:0032ff,00ffff,00ffff,00ffff,0030ff,000000,000000,000000,000000,000000,000000,000000
+16:0009ff,00ffff,00ffff,00ffff,0008ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ebff,00ffff,00eaff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00c0ff,00ffff,00bfff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0094ff,00ffff,0093ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0069ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003eff,00ffff,003dff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0017ff,00ffff,0016ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003aff,00ffff,0038ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0068ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,009bff,00ffff,009aff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ceff,00ffff,00ccff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00fdff,00ffff,00fcff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:001cff,00ffff,00ffff,00ffff,001bff,000000,000000,000000,000000,000000,000000,000000
+16:0043ff,00ffff,00ffff,00ffff,0041ff,000000,000000,000000,000000,000000,000000,000000
+16:0065ff,00ffff,00ffff,00ffff,0064ff,000000,000000,000000,000000,000000,000000,000000
+16:0083ff,00ffff,00ffff,00ffff,0082ff,000000,000000,000000,000000,000000,000000,000000
+16:009dff,00ffff,00ffff,00ffff,009cff,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000,000000,000000
+16:00c7ff,00ffff,00ffff,00ffff,00c6ff,000000,000000,000000,000000,000000,000000,000000
+16:00d7ff,00ffff,00ffff,00ffff,00d6ff,000000,000000,000000,000000,000000,000000,000000
+16:00e5ff,00ffff,00ffff,00ffff,00e3ff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00eeff,000000,000000,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000,000000,000000
+16:00feff,00ffff,00ffff,00ffff,00fdff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f0ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ccff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,005bff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0013ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00edff,0000ff,00efff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00c3ff,0000ff,00c4ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0096ff,0000ff,0097ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0067ff,0000ff,0068ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0036ff,0000ff,0037ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0004ff,0000ff,0006ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,00e0ff,000000,000000,000000,000000,000000,000000,000000
+16:00acff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:007bff,0000ff,0000ff,0000ff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:004eff,0000ff,0000ff,0000ff,0050ff,000000,000000,000000,000000,000000,000000,000000
+16:0076ff,0000ff,0000ff,0000ff,0077ff,000000,000000,000000,000000,000000,000000,000000
+16:00abff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,0000ff,0000ff,0000ff,00e7ff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0014ff,0000ff,0015ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,004bff,0000ff,004cff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,007dff,0000ff,007eff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00aaff,0000ff,00abff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00d1ff,0000ff,00d2ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00f4ff,0000ff,00f5ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,000cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0040ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,006cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0091ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00b1ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ddff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ecff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f7ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00fcff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00efff,000000,000000,000000,000000,000000,000000,000000
+16:00daff,00ffff,00ffff,00ffff,00d9ff,000000,000000,000000,000000,000000,000000,000000
+16:00bfff,00ffff,00ffff,00ffff,00beff,000000,000000,000000,000000,000000,000000,000000
+16:00a0ff,00ffff,00ffff,00ffff,009fff,000000,000000,000000,000000,000000,000000,000000
+16:007eff,00ffff,00ffff,00ffff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:0059ff,00ffff,00ffff,00ffff,0057ff,000000,000000,000000,000000,000000,000000,000000
+16:0032ff,00ffff,00ffff,00ffff,0030ff,000000,000000,000000,000000,000000,000000,000000
+16:0009ff,00ffff,00ffff,00ffff,0008ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ebff,00ffff,00eaff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00c0ff,00ffff,00bfff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0094ff,00ffff,0093ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0069ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003eff,00ffff,003dff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0017ff,00ffff,0016ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003aff,00ffff,0038ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0068ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,009bff,00ffff,009aff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ceff,00ffff,00ccff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00fdff,00ffff,00fcff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:001cff,00ffff,00ffff,00ffff,001bff,000000,000000,000000,000000,000000,000000,000000
+16:0043ff,00ffff,00ffff,00ffff,0041ff,000000,000000,000000,000000,000000,000000,000000
+16:0065ff,00ffff,00ffff,00ffff,0064ff,000000,000000,000000,000000,000000,000000,000000
+16:0083ff,00ffff,00ffff,00ffff,0082ff,000000,000000,000000,000000,000000,000000,000000
+16:009dff,00ffff,00ffff,00ffff,009cff,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000,000000,000000
+16:00c7ff,00ffff,00ffff,00ffff,00c6ff,000000,000000,000000,000000,000000,000000,000000
+16:00d7ff,00ffff,00ffff,00ffff,00d6ff,000000,000000,000000,000000,000000,000000,000000
+16:00e5ff,00ffff,00ffff,00ffff,00e3ff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00eeff,000000,000000,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000,000000,000000
+16:00feff,00ffff,00ffff,00ffff,00fdff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f0ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ccff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,005bff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0013ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00edff,0000ff,00efff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00c3ff,0000ff,00c4ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0096ff,0000ff,0097ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0067ff,0000ff,0068ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0036ff,0000ff,0037ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0004ff,0000ff,0006ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,00e0ff,000000,000000,000000,000000,000000,000000,000000
+16:00acff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:007bff,0000ff,0000ff,0000ff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:004eff,0000ff,0000ff,0000ff,0050ff,000000,000000,000000,000000,000000,000000,000000
+16:0076ff,0000ff,0000ff,0000ff,0077ff,000000,000000,000000,000000,000000,000000,000000
+16:00abff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,0000ff,0000ff,0000ff,00e7ff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0014ff,0000ff,0015ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,004bff,0000ff,004cff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,007dff,0000ff,007eff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00aaff,0000ff,00abff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00d1ff,0000ff,00d2ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00f4ff,0000ff,00f5ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,000cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0040ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,006cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0091ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00b1ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ddff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ecff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f7ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00fcff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00efff,000000,000000,000000,000000,000000,000000,000000
+16:00daff,00ffff,00ffff,00ffff,00d9ff,000000,000000,000000,000000,000000,000000,000000
+16:00bfff,00ffff,00ffff,00ffff,00beff,000000,000000,000000,000000,000000,000000,000000
+16:00a0ff,00ffff,00ffff,00ffff,009fff,000000,000000,000000,000000,000000,000000,000000
+16:007eff,00ffff,00ffff,00ffff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:0059ff,00ffff,00ffff,00ffff,0057ff,000000,000000,000000,000000,000000,000000,000000
+16:0032ff,00ffff,00ffff,00ffff,0030ff,000000,000000,000000,000000,000000,000000,000000
+16:0009ff,00ffff,00ffff,00ffff,0008ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ebff,00ffff,00eaff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00c0ff,00ffff,00bfff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0094ff,00ffff,0093ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0069ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003eff,00ffff,003dff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0017ff,00ffff,0016ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003aff,00ffff,0038ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0068ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,009bff,00ffff,009aff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ceff,00ffff,00ccff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00fdff,00ffff,00fcff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:001cff,00ffff,00ffff,00ffff,001bff,000000,000000,000000,000000,000000,000000,000000
+16:0043ff,00ffff,00ffff,00ffff,0041ff,000000,000000,000000,000000,000000,000000,000000
+16:0065ff,00ffff,00ffff,00ffff,0064ff,000000,000000,000000,000000,000000,000000,000000
+16:0083ff,00ffff,00ffff,00ffff,0082ff,000000,000000,000000,000000,000000,000000,000000
+16:009dff,00ffff,00ffff,00ffff,009cff,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000,000000,000000
+16:00c7ff,00ffff,00ffff,00ffff,00c6ff,000000,000000,000000,000000,000000,000000,000000
+16:00d7ff,00ffff,00ffff,00ffff,00d6ff,000000,000000,000000,000000,000000,000000,000000
+16:00e5ff,00ffff,00ffff,00ffff,00e3ff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00eeff,000000,000000,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000,000000,000000
+16:00feff,00ffff,00ffff,00ffff,00fdff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+loop
+100:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/alert.animation b_Alexa LED Animation Files for AVS_linear_5/alert.animation
new file mode 100755
index 0000000..a8ce0ea
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/alert.animation
@@ -0,0 +1,88 @@
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f0ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ccff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,005bff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0013ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00edff,0000ff,00efff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00c3ff,0000ff,00c4ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0096ff,0000ff,0097ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0067ff,0000ff,0068ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0036ff,0000ff,0037ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0004ff,0000ff,0006ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,00e0ff,000000,000000,000000,000000,000000,000000,000000
+16:00acff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:007bff,0000ff,0000ff,0000ff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:004eff,0000ff,0000ff,0000ff,0050ff,000000,000000,000000,000000,000000,000000,000000
+16:0076ff,0000ff,0000ff,0000ff,0077ff,000000,000000,000000,000000,000000,000000,000000
+16:00abff,0000ff,0000ff,0000ff,00adff,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,0000ff,0000ff,0000ff,00e7ff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,0014ff,0000ff,0015ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,004bff,0000ff,004cff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,007dff,0000ff,007eff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00aaff,0000ff,00abff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00d1ff,0000ff,00d2ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00f4ff,0000ff,00f5ff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,000cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0040ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,006cff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0091ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00b1ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ddff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ecff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f7ff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00fcff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00efff,000000,000000,000000,000000,000000,000000,000000
+16:00daff,00ffff,00ffff,00ffff,00d9ff,000000,000000,000000,000000,000000,000000,000000
+16:00bfff,00ffff,00ffff,00ffff,00beff,000000,000000,000000,000000,000000,000000,000000
+16:00a0ff,00ffff,00ffff,00ffff,009fff,000000,000000,000000,000000,000000,000000,000000
+16:007eff,00ffff,00ffff,00ffff,007cff,000000,000000,000000,000000,000000,000000,000000
+16:0059ff,00ffff,00ffff,00ffff,0057ff,000000,000000,000000,000000,000000,000000,000000
+16:0032ff,00ffff,00ffff,00ffff,0030ff,000000,000000,000000,000000,000000,000000,000000
+16:0009ff,00ffff,00ffff,00ffff,0008ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ebff,00ffff,00eaff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00c0ff,00ffff,00bfff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0094ff,00ffff,0093ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0069ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003eff,00ffff,003dff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0017ff,00ffff,0016ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,003aff,00ffff,0038ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,0068ff,00ffff,0067ff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,009bff,00ffff,009aff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00ceff,00ffff,00ccff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,00fdff,00ffff,00fcff,0000ff,000000,000000,000000,000000,000000,000000,000000
+16:001cff,00ffff,00ffff,00ffff,001bff,000000,000000,000000,000000,000000,000000,000000
+16:0043ff,00ffff,00ffff,00ffff,0041ff,000000,000000,000000,000000,000000,000000,000000
+16:0065ff,00ffff,00ffff,00ffff,0064ff,000000,000000,000000,000000,000000,000000,000000
+16:0083ff,00ffff,00ffff,00ffff,0082ff,000000,000000,000000,000000,000000,000000,000000
+16:009dff,00ffff,00ffff,00ffff,009cff,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000,000000,000000
+16:00c7ff,00ffff,00ffff,00ffff,00c6ff,000000,000000,000000,000000,000000,000000,000000
+16:00d7ff,00ffff,00ffff,00ffff,00d6ff,000000,000000,000000,000000,000000,000000,000000
+16:00e5ff,00ffff,00ffff,00ffff,00e3ff,000000,000000,000000,000000,000000,000000,000000
+16:00f0ff,00ffff,00ffff,00ffff,00eeff,000000,000000,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000,000000,000000
+16:00feff,00ffff,00ffff,00ffff,00fdff,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/btconnect.animation b_Alexa LED Animation Files for AVS_linear_5/btconnect.animation
new file mode 100644
index 0000000..d1429ce
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/btconnect.animation
@@ -0,0 +1,48 @@
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+5:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+5:000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033
+5:000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044
+5:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+5:000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066
+5:000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077
+5:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+5:000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099
+5:0000AA,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa
+5:0000BB,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+5:0000CC,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc
+5:0000DD,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd
+5:0000EE,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000FF,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+5:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+5:000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033
+5:000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044
+5:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+5:000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066
+5:000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077
+5:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+5:000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099
+5:0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa
+5:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+5:0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc
+5:0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd
+5:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+5:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+5:000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033
+5:000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044
+5:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+5:000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066
+5:000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077
+5:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+5:000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099
+5:0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa
+5:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+5:0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc
+5:0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd
+5:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
diff --git a_Alexa LED Animation Files for AVS_linear_5/btdisconnect.animation b_Alexa LED Animation Files for AVS_linear_5/btdisconnect.animation
new file mode 100644
index 0000000..d1429ce
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/btdisconnect.animation
@@ -0,0 +1,48 @@
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+5:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+5:000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033
+5:000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044
+5:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+5:000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066
+5:000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077
+5:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+5:000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099
+5:0000AA,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa
+5:0000BB,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+5:0000CC,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc
+5:0000DD,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd
+5:0000EE,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000FF,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+5:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+5:000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033
+5:000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044
+5:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+5:000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066
+5:000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077
+5:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+5:000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099
+5:0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa
+5:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+5:0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc
+5:0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd
+5:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+5:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+5:000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033,000033
+5:000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044,000044
+5:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+5:000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066,000066
+5:000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077,000077
+5:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+5:000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099,000099
+5:0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa,0000aa
+5:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+5:0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc,0000cc
+5:0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd,0000dd
+5:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
diff --git a_Alexa LED Animation Files for AVS_linear_5/do_not_disturb.animation b_Alexa LED Animation Files for AVS_linear_5/do_not_disturb.animation
new file mode 100644
index 0000000..123774f
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/do_not_disturb.animation
@@ -0,0 +1,59 @@
+10:0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014
+10:020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005
+10:05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A
+10:07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F
+10:0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014
+10:0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019
+10:0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E
+10:110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023
+10:140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028
+10:16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D
+10:190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034
+10:1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A
+22:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041
+22:230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048
+22:27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E
+22:2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055
+22:2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C
+22:310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062
+22:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069
+22:370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070
+22:3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076
+22:3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D
+22:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084
+50:45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A
+50:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091
+50:4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098
+50:4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E
+60:5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5
+50:4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E
+50:4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098
+50:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091
+50:45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A
+40:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084
+40:3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D
+40:3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076
+40:370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070
+40:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069
+40:310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062
+40:2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C
+40:2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055
+40:27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E
+40:230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048
+40:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041
+40:1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A
+40:190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034
+40:16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D
+40:140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028
+40:110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023
+40:0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E
+40:0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019
+40:0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014
+40:07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F
+40:05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A
+30:020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/error.animation b_Alexa LED Animation Files for AVS_linear_5/error.animation
new file mode 100644
index 0000000..1263a33
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/error.animation
@@ -0,0 +1,86 @@
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:A00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:E00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_linear_5/mics-off_end.animation b_Alexa LED Animation Files for AVS_linear_5/mics-off_end.animation
new file mode 100755
index 0000000..0c6c787
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/mics-off_end.animation
@@ -0,0 +1,12 @@
+16:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+16:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+16:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+16:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+16:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
+16:880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000
+16:660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000
+16:550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000
+16:330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000
+16:110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_5/mics-off_on.animation b_Alexa LED Animation Files for AVS_linear_5/mics-off_on.animation
new file mode 100644
index 0000000..12da7fd
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/mics-off_on.animation
@@ -0,0 +1,8 @@
+66:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+66:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+66:DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000
+66:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+66:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+66:AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000
+loop
+1000:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
diff --git a_Alexa LED Animation Files for AVS_linear_5/mics-off_start.animation b_Alexa LED Animation Files for AVS_linear_5/mics-off_start.animation
new file mode 100644
index 0000000..38b6a25
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/mics-off_start.animation
@@ -0,0 +1,17 @@
+33:110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000
+33:220000,220000,220000,220000,220000,220000,220000,220000,220000,220000,220000,220000
+33:330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000
+33:440000,440000,440000,440000,440000,440000,440000,440000,440000,440000,440000,440000
+33:550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000
+33:660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000
+33:770000,770000,770000,770000,770000,770000,770000,770000,770000,770000,770000,770000
+33:880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000
+33:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
+33:AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000
+33:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+33:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+33:DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000
+33:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+loop
+1000:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+
diff --git a_Alexa LED Animation Files for AVS_linear_5/ntf_incoming.animation b_Alexa LED Animation Files for AVS_linear_5/ntf_incoming.animation
new file mode 100644
index 0000000..946d861
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/ntf_incoming.animation
@@ -0,0 +1,37 @@
+40:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+50:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+50:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400
+50:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+50:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+50:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+50:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+50:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+50:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+50:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+50:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+50:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+50:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+50:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+
+
+1200:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400
+40:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+40:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+40:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+40:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+40:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+40:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+40:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+40:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+40:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+40:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+40:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+40:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+40:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+
+
diff --git a_Alexa LED Animation Files for AVS_linear_5/ntf_queued.animation b_Alexa LED Animation Files for AVS_linear_5/ntf_queued.animation
new file mode 100644
index 0000000..159adbb
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_5/ntf_queued.animation
@@ -0,0 +1,29 @@
+60:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+60:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+60:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400
+60:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+60:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+60:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+60:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+60:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+60:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+60:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+60:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+60:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+60:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+60:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+800:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400
+60:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+60:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+60:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+60:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+60:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+60:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+60:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+60:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+60:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+60:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+60:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+60:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+60:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+1500:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/active-ending.animation b_Alexa LED Animation Files for AVS_linear_7/active-ending.animation
new file mode 100755
index 0000000..ea6fbd2
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/active-ending.animation
@@ -0,0 +1,32 @@
+16:00ffff,0000ff,0000ff,0000ff,0000ff,0000ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0000ff,0000ff,0000ff,0000ff,0000ff,00ffff,000000,000000,000000,000000,000000
+16:00feff,0001ff,0000ff,0000ff,0000ff,0002ff,00fdfe,000000,000000,000000,000000,000000
+16:00f5f7,000aff,0000ff,0000ff,0000ff,000bff,00f4f5,000000,000000,000000,000000,000000
+16:00e9eb,0016ff,0000ff,0000ff,0000ff,0018ff,00e7e9,000000,000000,000000,000000,000000
+16:00dadc,0025ff,0000ff,0000ff,0000ff,0027ff,00d8da,000000,000000,000000,000000,000000
+16:00c9ca,0036ff,0000ff,0000ff,0000ff,0038ff,00c7c9,000000,000000,000000,000000,000000
+16:00b5b7,004aff,0000ff,0000ff,0000ff,004bff,00b4b6,000000,000000,000000,000000,000000
+16:00a0a2,005fff,0000ff,0000ff,0000ff,0060ff,009fa0,000000,000000,000000,000000,000000
+16:00898b,0076ff,0000ff,0000ff,0000ff,0077ff,008889,000000,000000,000000,000000,000000
+16:007072,008fff,0000ff,0000ff,0000ff,0090ff,006f71,000000,000000,000000,000000,000000
+16:005658,00a9ff,0000ff,0000ff,0000ff,00aaff,005557,000000,000000,000000,000000,000000
+16:003b3d,00c4ff,0000ff,0000ff,0000ff,00c5ff,003a3b,000000,000000,000000,000000,000000
+16:001f20,00e0ff,0000ff,0000ff,0000ff,00e2ff,001d1f,000000,000000,000000,000000,000000
+16:000102,00feff,0000ff,0000ff,0000ff,00ffff,000001,000000,000000,000000,000000,000000
+16:000000,00eff0,0010ff,0000ff,0012ff,00edef,000000,000000,000000,000000,000000,000000
+16:000000,00cfd0,0030ff,0000ff,0031ff,00cecf,000000,000000,000000,000000,000000,000000
+16:000000,00aeb0,0051ff,0000ff,0052ff,00adae,000000,000000,000000,000000,000000,000000
+16:000000,008d8e,0072ff,0000ff,0073ff,008c8d,000000,000000,000000,000000,000000,000000
+16:000000,006b6c,0094ff,0000ff,0095ff,006a6b,000000,000000,000000,000000,000000,000000
+16:000000,00494a,00b6ff,0000ff,00b8ff,004748,000000,000000,000000,000000,000000,000000
+16:000000,002526,00daff,0000ff,00dbff,002425,000000,000000,000000,000000,000000,000000
+16:000000,000203,00fdff,0000ff,00feff,000101,000000,000000,000000,000000,000000,000000
+16:000000,000000,00eaeb,002aff,00e9ea,000000,000000,000000,000000,000000,000000,000000
+16:000000,000000,00c6c7,0073ff,00c5c6,000000,000000,000000,000000,000000,000000,000000
+16:000000,000000,00a2a3,00bbff,00a1a2,000000,000000,000000,000000,000000,000000,000000
+16:000000,000000,007e7f,00ffff,007d7e,000000,000000,000000,000000,000000,000000,000000
+16:000000,000000,005b5b,00ffff,005a5a,000000,000000,000000,000000,000000,000000,000000
+16:000000,000000,003839,00ffff,003737,000000,000000,000000,000000,000000,000000,000000
+16:000000,000000,001818,00ffff,001616,000000,000000,000000,000000,000000,000000,000000
+loop
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/active-talking.animation b_Alexa LED Animation Files for AVS_linear_7/active-talking.animation
new file mode 100644
index 0000000..d79a708
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/active-talking.animation
@@ -0,0 +1,56 @@
+100:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+80:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+70:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+60:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+50:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+40:0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+40:0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+100:0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff
+40:0066FF,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+50:0088FF,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+60:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+70:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+80:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+90:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+100:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+80:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+70:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+60:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+50:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+40:0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+40:0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF,0055FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+100:0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF,0000FF
+40:0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF,0022FF
+40:0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF,0033FF
+40:0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF,0044FF
+40:0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff,0055ff
+40:0066FF,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff,0066ff
+40:0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff,0077ff
+50:0088FF,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff,0088ff
+60:0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff,0099ff
+70:00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff,00aaff
+80:00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff,00bbff
+90:00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff,00ccff
+90:00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff,00ddff
+90:00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff,00eeff
diff --git a_Alexa LED Animation Files for AVS_linear_7/active-thinking.animation b_Alexa LED Animation Files for AVS_linear_7/active-thinking.animation
new file mode 100755
index 0000000..d90cfef
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/active-thinking.animation
@@ -0,0 +1,40 @@
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0002ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,000cff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,002fff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0099ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0041ff,00ffff,0040ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,009fff,00ffff,009eff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00faff,00ffff,00f9ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,003cff,00ffff,00ffff,00ffff,003aff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,007cff,00ffff,00ffff,00ffff,007bff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00b1ff,00ffff,00ffff,00ffff,00afff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00ddff,00ffff,00ffff,00ffff,00dcff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00ffff,00ffff,00ffff,00ffff,00ffff,0000ff,000000,000000,000000,000000,000000
+16:0017ff,00ffff,00ffff,00ffff,00ffff,00ffff,0016ff,000000,000000,000000,000000,000000
+16:0034ff,00ffff,00ffff,00ffff,00ffff,00ffff,0032ff,000000,000000,000000,000000,000000
+16:004dff,00ffff,00ffff,00ffff,00ffff,00ffff,004cff,000000,000000,000000,000000,000000
+16:0063ff,00ffff,00ffff,00ffff,00ffff,00ffff,0062ff,000000,000000,000000,000000,000000
+16:0077ff,00ffff,00ffff,00ffff,00ffff,00ffff,0076ff,000000,000000,000000,000000,000000
+16:0088ff,00ffff,00ffff,00ffff,00ffff,00ffff,0087ff,000000,000000,000000,000000,000000
+16:0098ff,00ffff,00ffff,00ffff,00ffff,00ffff,0097ff,000000,000000,000000,000000,000000
+16:00a7ff,00ffff,00ffff,00ffff,00ffff,00ffff,00a5ff,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000
+16:00bfff,00ffff,00ffff,00ffff,00ffff,00ffff,00bdff,000000,000000,000000,000000,000000
+16:00a4ff,00d0ff,00d0ff,00d0ff,00d0ff,00d0ff,00a3ff,000000,000000,000000,000000,000000
+16:0087ff,00a4ff,00a4ff,00a4ff,00a4ff,00a4ff,0086ff,000000,000000,000000,000000,000000
+16:006bff,007dff,007dff,007dff,007dff,007dff,006aff,000000,000000,000000,000000,000000
+16:0052ff,005dff,005dff,005dff,005dff,005dff,0052ff,000000,000000,000000,000000,000000
+16:003dff,0043ff,0043ff,0043ff,0043ff,0043ff,003dff,000000,000000,000000,000000,000000
+16:002cff,002fff,002fff,002fff,002fff,002fff,002cff,000000,000000,000000,000000,000000
+16:001eff,0020ff,0020ff,0020ff,0020ff,0020ff,001eff,000000,000000,000000,000000,000000
+16:0015ff,0016ff,0016ff,0016ff,0016ff,0016ff,0015ff,000000,000000,000000,000000,000000
+16:000eff,000eff,000eff,000eff,000eff,000eff,000eff,000000,000000,000000,000000,000000
+16:0009ff,0009ff,0009ff,0009ff,0009ff,0009ff,0009ff,000000,000000,000000,000000,000000
+16:0006ff,0006ff,0006ff,0006ff,0006ff,0006ff,0006ff,000000,000000,000000,000000,000000
+16:0004ff,0004ff,0004ff,0004ff,0004ff,0004ff,0004ff,000000,000000,000000,000000,000000
+16:0003ff,0003ff,0003ff,0003ff,0003ff,0003ff,0003ff,000000,000000,000000,000000,000000
+16:0002ff,0002ff,0002ff,0002ff,0002ff,0002ff,0002ff,000000,000000,000000,000000,000000
+16:0001ff,0001ff,0001ff,0001ff,0001ff,0001ff,0001ff,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/active-waking.animation b_Alexa LED Animation Files for AVS_linear_7/active-waking.animation
new file mode 100755
index 0000000..e5bab37
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/active-waking.animation
@@ -0,0 +1,19 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006c6d,000001,000001,000001,000001,000001,006e6e,000000,000000,000000,000000,000000
+16:00acad,005252,000001,000001,000001,005354,00abac,000000,000000,000000,000000,000000
+16:000002,00f8f8,000608,000002,000709,00f6f7,000002,000000,000000,000000,000000,000000
+16:000003,007a7b,008486,000003,008687,00787a,000003,000000,000000,000000,000000,000000
+16:000005,002024,00dedf,000005,00e0e0,001e23,000005,000000,000000,000000,000000,000000
+16:000007,000007,00e8e9,002e34,00e7e8,000007,000007,000000,000000,000000,000000,000000
+16:00000a,00000a,00b3b6,00979c,00b2b5,00000a,00000a,000000,000000,000000,000000,000000
+16:00000f,00000f,008990,00ecee,00878f,00000f,00000f,000000,000000,000000,000000,000000
+16:000016,000016,006774,00ffff,006573,000016,000016,000000,000000,000000,000000,000000
+16:000020,000020,004b62,00ffff,004a61,000020,000020,000000,000000,000000,000000,000000
+16:00002c,00002c,003558,00ffff,003457,00002c,00002c,000000,000000,000000,000000,000000
+16:00003c,00003c,002457,00ffff,002256,00003c,00003c,000000,000000,000000,000000,000000
+16:000051,000051,001560,00ffff,00145f,000051,000051,000000,000000,000000,000000,000000
+16:00006a,00006a,000a70,00ffff,000970,00006a,00006a,000000,000000,000000,000000,000000
+16:00008a,00008a,00038b,00ffff,00018b,00008a,00008a,000000,000000,000000,000000,000000
+16:0000ae,0000ae,0000ae,00ffff,0000ae,0000ae,0000ae,000000,000000,000000,000000,000000
+loop
+16:0000d6,0000d6,0000d6,00ffff,0000d6,0000d6,0000d6,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/alert-short.animation b_Alexa LED Animation Files for AVS_linear_7/alert-short.animation
new file mode 100755
index 0000000..ea3ec95
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/alert-short.animation
@@ -0,0 +1,266 @@
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e7ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00aeff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,005bff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0000ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00cdff,0000ff,00ceff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,008dff,0000ff,008fff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0049ff,0000ff,004aff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0000ff,0000ff,0002ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00c1ff,0000ff,0000ff,0000ff,00c2ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0073ff,0000ff,0000ff,0000ff,0074ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0023ff,0000ff,0000ff,0000ff,0024ff,00ffff,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,0000ff,0000ff,00dfff,000000,000000,000000,000000,000000
+16:008dff,0000ff,0000ff,0000ff,0000ff,0000ff,008eff,000000,000000,000000,000000,000000
+16:003eff,0000ff,0000ff,0000ff,0000ff,0000ff,003fff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0036ff,0000ff,0000ff,0000ff,0000ff,0000ff,0037ff,000000,000000,000000,000000,000000
+16:008cff,0000ff,0000ff,0000ff,0000ff,0000ff,008dff,000000,000000,000000,000000,000000
+16:00eaff,0000ff,0000ff,0000ff,0000ff,0000ff,00ecff,000000,000000,000000,000000,000000
+16:00ffff,003cff,0000ff,0000ff,0000ff,003dff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0094ff,0000ff,0000ff,0000ff,0096ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00e5ff,0000ff,0000ff,0000ff,00e6ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0020ff,0000ff,0022ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0060ff,0000ff,0061ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0098ff,0000ff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c8ff,0000ff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f2ff,0000ff,00f3ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0013ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0050ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0081ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00a9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00c9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00f2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00fbff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00faff,00ffff,00ffff,00ffff,00ffff,00ffff,00f9ff,000000,000000,000000,000000,000000
+16:00ddff,00ffff,00ffff,00ffff,00ffff,00ffff,00dcff,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000
+16:007fff,00ffff,00ffff,00ffff,00ffff,00ffff,007eff,000000,000000,000000,000000,000000
+16:0044ff,00ffff,00ffff,00ffff,00ffff,00ffff,0043ff,000000,000000,000000,000000,000000
+16:0003ff,00ffff,00ffff,00ffff,00ffff,00ffff,0002ff,000000,000000,000000,000000,000000
+16:0000ff,00caff,00ffff,00ffff,00ffff,00c9ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0080ff,00ffff,00ffff,00ffff,007eff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0033ff,00ffff,00ffff,00ffff,0031ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00efff,00ffff,00eeff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,009eff,00ffff,009cff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,004bff,00ffff,004aff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0067ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0057ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0058ff,00ffff,0056ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00b8ff,00ffff,00b6ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0005ff,00ffff,00ffff,00ffff,0004ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0057ff,00ffff,00ffff,00ffff,0056ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00a1ff,00ffff,00ffff,00ffff,009fff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00e1ff,00ffff,00ffff,00ffff,00e0ff,0000ff,000000,000000,000000,000000,000000
+16:000eff,00ffff,00ffff,00ffff,00ffff,00ffff,000dff,000000,000000,000000,000000,000000
+16:003fff,00ffff,00ffff,00ffff,00ffff,00ffff,003eff,000000,000000,000000,000000,000000
+16:006aff,00ffff,00ffff,00ffff,00ffff,00ffff,0068ff,000000,000000,000000,000000,000000
+16:008eff,00ffff,00ffff,00ffff,00ffff,00ffff,008dff,000000,000000,000000,000000,000000
+16:00adff,00ffff,00ffff,00ffff,00ffff,00ffff,00abff,000000,000000,000000,000000,000000
+16:00c6ff,00ffff,00ffff,00ffff,00ffff,00ffff,00c5ff,000000,000000,000000,000000,000000
+16:00dbff,00ffff,00ffff,00ffff,00ffff,00ffff,00daff,000000,000000,000000,000000,000000
+16:00ebff,00ffff,00ffff,00ffff,00ffff,00ffff,00eaff,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e7ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00aeff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,005bff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0000ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00cdff,0000ff,00ceff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,008dff,0000ff,008fff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0049ff,0000ff,004aff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0000ff,0000ff,0002ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00c1ff,0000ff,0000ff,0000ff,00c2ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0073ff,0000ff,0000ff,0000ff,0074ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0023ff,0000ff,0000ff,0000ff,0024ff,00ffff,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,0000ff,0000ff,00dfff,000000,000000,000000,000000,000000
+16:008dff,0000ff,0000ff,0000ff,0000ff,0000ff,008eff,000000,000000,000000,000000,000000
+16:003eff,0000ff,0000ff,0000ff,0000ff,0000ff,003fff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0036ff,0000ff,0000ff,0000ff,0000ff,0000ff,0037ff,000000,000000,000000,000000,000000
+16:008cff,0000ff,0000ff,0000ff,0000ff,0000ff,008dff,000000,000000,000000,000000,000000
+16:00eaff,0000ff,0000ff,0000ff,0000ff,0000ff,00ecff,000000,000000,000000,000000,000000
+16:00ffff,003cff,0000ff,0000ff,0000ff,003dff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0094ff,0000ff,0000ff,0000ff,0096ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00e5ff,0000ff,0000ff,0000ff,00e6ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0020ff,0000ff,0022ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0060ff,0000ff,0061ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0098ff,0000ff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c8ff,0000ff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f2ff,0000ff,00f3ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0013ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0050ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0081ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00a9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00c9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00f2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00fbff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00faff,00ffff,00ffff,00ffff,00ffff,00ffff,00f9ff,000000,000000,000000,000000,000000
+16:00ddff,00ffff,00ffff,00ffff,00ffff,00ffff,00dcff,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000
+16:007fff,00ffff,00ffff,00ffff,00ffff,00ffff,007eff,000000,000000,000000,000000,000000
+16:0044ff,00ffff,00ffff,00ffff,00ffff,00ffff,0043ff,000000,000000,000000,000000,000000
+16:0003ff,00ffff,00ffff,00ffff,00ffff,00ffff,0002ff,000000,000000,000000,000000,000000
+16:0000ff,00caff,00ffff,00ffff,00ffff,00c9ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0080ff,00ffff,00ffff,00ffff,007eff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0033ff,00ffff,00ffff,00ffff,0031ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00efff,00ffff,00eeff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,009eff,00ffff,009cff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,004bff,00ffff,004aff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0067ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0057ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0058ff,00ffff,0056ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00b8ff,00ffff,00b6ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0005ff,00ffff,00ffff,00ffff,0004ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0057ff,00ffff,00ffff,00ffff,0056ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00a1ff,00ffff,00ffff,00ffff,009fff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00e1ff,00ffff,00ffff,00ffff,00e0ff,0000ff,000000,000000,000000,000000,000000
+16:000eff,00ffff,00ffff,00ffff,00ffff,00ffff,000dff,000000,000000,000000,000000,000000
+16:003fff,00ffff,00ffff,00ffff,00ffff,00ffff,003eff,000000,000000,000000,000000,000000
+16:006aff,00ffff,00ffff,00ffff,00ffff,00ffff,0068ff,000000,000000,000000,000000,000000
+16:008eff,00ffff,00ffff,00ffff,00ffff,00ffff,008dff,000000,000000,000000,000000,000000
+16:00adff,00ffff,00ffff,00ffff,00ffff,00ffff,00abff,000000,000000,000000,000000,000000
+16:00c6ff,00ffff,00ffff,00ffff,00ffff,00ffff,00c5ff,000000,000000,000000,000000,000000
+16:00dbff,00ffff,00ffff,00ffff,00ffff,00ffff,00daff,000000,000000,000000,000000,000000
+16:00ebff,00ffff,00ffff,00ffff,00ffff,00ffff,00eaff,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e7ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00aeff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,005bff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0000ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00cdff,0000ff,00ceff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,008dff,0000ff,008fff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0049ff,0000ff,004aff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0000ff,0000ff,0002ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00c1ff,0000ff,0000ff,0000ff,00c2ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0073ff,0000ff,0000ff,0000ff,0074ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0023ff,0000ff,0000ff,0000ff,0024ff,00ffff,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,0000ff,0000ff,00dfff,000000,000000,000000,000000,000000
+16:008dff,0000ff,0000ff,0000ff,0000ff,0000ff,008eff,000000,000000,000000,000000,000000
+16:003eff,0000ff,0000ff,0000ff,0000ff,0000ff,003fff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0036ff,0000ff,0000ff,0000ff,0000ff,0000ff,0037ff,000000,000000,000000,000000,000000
+16:008cff,0000ff,0000ff,0000ff,0000ff,0000ff,008dff,000000,000000,000000,000000,000000
+16:00eaff,0000ff,0000ff,0000ff,0000ff,0000ff,00ecff,000000,000000,000000,000000,000000
+16:00ffff,003cff,0000ff,0000ff,0000ff,003dff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0094ff,0000ff,0000ff,0000ff,0096ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00e5ff,0000ff,0000ff,0000ff,00e6ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0020ff,0000ff,0022ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0060ff,0000ff,0061ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0098ff,0000ff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c8ff,0000ff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f2ff,0000ff,00f3ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0013ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0050ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0081ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00a9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00c9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00f2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00fbff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00faff,00ffff,00ffff,00ffff,00ffff,00ffff,00f9ff,000000,000000,000000,000000,000000
+16:00ddff,00ffff,00ffff,00ffff,00ffff,00ffff,00dcff,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000
+16:007fff,00ffff,00ffff,00ffff,00ffff,00ffff,007eff,000000,000000,000000,000000,000000
+16:0044ff,00ffff,00ffff,00ffff,00ffff,00ffff,0043ff,000000,000000,000000,000000,000000
+16:0003ff,00ffff,00ffff,00ffff,00ffff,00ffff,0002ff,000000,000000,000000,000000,000000
+16:0000ff,00caff,00ffff,00ffff,00ffff,00c9ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0080ff,00ffff,00ffff,00ffff,007eff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0033ff,00ffff,00ffff,00ffff,0031ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00efff,00ffff,00eeff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,009eff,00ffff,009cff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,004bff,00ffff,004aff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0067ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0057ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0058ff,00ffff,0056ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00b8ff,00ffff,00b6ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0005ff,00ffff,00ffff,00ffff,0004ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0057ff,00ffff,00ffff,00ffff,0056ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00a1ff,00ffff,00ffff,00ffff,009fff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00e1ff,00ffff,00ffff,00ffff,00e0ff,0000ff,000000,000000,000000,000000,000000
+16:000eff,00ffff,00ffff,00ffff,00ffff,00ffff,000dff,000000,000000,000000,000000,000000
+16:003fff,00ffff,00ffff,00ffff,00ffff,00ffff,003eff,000000,000000,000000,000000,000000
+16:006aff,00ffff,00ffff,00ffff,00ffff,00ffff,0068ff,000000,000000,000000,000000,000000
+16:008eff,00ffff,00ffff,00ffff,00ffff,00ffff,008dff,000000,000000,000000,000000,000000
+16:00adff,00ffff,00ffff,00ffff,00ffff,00ffff,00abff,000000,000000,000000,000000,000000
+16:00c6ff,00ffff,00ffff,00ffff,00ffff,00ffff,00c5ff,000000,000000,000000,000000,000000
+16:00dbff,00ffff,00ffff,00ffff,00ffff,00ffff,00daff,000000,000000,000000,000000,000000
+16:00ebff,00ffff,00ffff,00ffff,00ffff,00ffff,00eaff,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000
+loop
+100:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/alert.animation b_Alexa LED Animation Files for AVS_linear_7/alert.animation
new file mode 100755
index 0000000..3611b41
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/alert.animation
@@ -0,0 +1,88 @@
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e7ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00aeff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,005bff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0000ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00cdff,0000ff,00ceff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,008dff,0000ff,008fff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0049ff,0000ff,004aff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0000ff,0000ff,0002ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00c1ff,0000ff,0000ff,0000ff,00c2ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0073ff,0000ff,0000ff,0000ff,0074ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0023ff,0000ff,0000ff,0000ff,0024ff,00ffff,000000,000000,000000,000000,000000
+16:00deff,0000ff,0000ff,0000ff,0000ff,0000ff,00dfff,000000,000000,000000,000000,000000
+16:008dff,0000ff,0000ff,0000ff,0000ff,0000ff,008eff,000000,000000,000000,000000,000000
+16:003eff,0000ff,0000ff,0000ff,0000ff,0000ff,003fff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0036ff,0000ff,0000ff,0000ff,0000ff,0000ff,0037ff,000000,000000,000000,000000,000000
+16:008cff,0000ff,0000ff,0000ff,0000ff,0000ff,008dff,000000,000000,000000,000000,000000
+16:00eaff,0000ff,0000ff,0000ff,0000ff,0000ff,00ecff,000000,000000,000000,000000,000000
+16:00ffff,003cff,0000ff,0000ff,0000ff,003dff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,0094ff,0000ff,0000ff,0000ff,0096ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00e5ff,0000ff,0000ff,0000ff,00e6ff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0020ff,0000ff,0022ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0060ff,0000ff,0061ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,0098ff,0000ff,0099ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00c8ff,0000ff,00c9ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00f2ff,0000ff,00f3ff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0013ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0050ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,0081ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00a9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00c9ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00e2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00f2ff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00fbff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,000000,000000,000000,000000,000000
+16:00faff,00ffff,00ffff,00ffff,00ffff,00ffff,00f9ff,000000,000000,000000,000000,000000
+16:00ddff,00ffff,00ffff,00ffff,00ffff,00ffff,00dcff,000000,000000,000000,000000,000000
+16:00b3ff,00ffff,00ffff,00ffff,00ffff,00ffff,00b2ff,000000,000000,000000,000000,000000
+16:007fff,00ffff,00ffff,00ffff,00ffff,00ffff,007eff,000000,000000,000000,000000,000000
+16:0044ff,00ffff,00ffff,00ffff,00ffff,00ffff,0043ff,000000,000000,000000,000000,000000
+16:0003ff,00ffff,00ffff,00ffff,00ffff,00ffff,0002ff,000000,000000,000000,000000,000000
+16:0000ff,00caff,00ffff,00ffff,00ffff,00c9ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0080ff,00ffff,00ffff,00ffff,007eff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0033ff,00ffff,00ffff,00ffff,0031ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00efff,00ffff,00eeff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,009eff,00ffff,009cff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,004bff,00ffff,004aff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0067ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,0057ff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0000ff,00ffff,0000ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,0058ff,00ffff,0056ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0000ff,00b8ff,00ffff,00b6ff,0000ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0005ff,00ffff,00ffff,00ffff,0004ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,0057ff,00ffff,00ffff,00ffff,0056ff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00a1ff,00ffff,00ffff,00ffff,009fff,0000ff,000000,000000,000000,000000,000000
+16:0000ff,00e1ff,00ffff,00ffff,00ffff,00e0ff,0000ff,000000,000000,000000,000000,000000
+16:000eff,00ffff,00ffff,00ffff,00ffff,00ffff,000dff,000000,000000,000000,000000,000000
+16:003fff,00ffff,00ffff,00ffff,00ffff,00ffff,003eff,000000,000000,000000,000000,000000
+16:006aff,00ffff,00ffff,00ffff,00ffff,00ffff,0068ff,000000,000000,000000,000000,000000
+16:008eff,00ffff,00ffff,00ffff,00ffff,00ffff,008dff,000000,000000,000000,000000,000000
+16:00adff,00ffff,00ffff,00ffff,00ffff,00ffff,00abff,000000,000000,000000,000000,000000
+16:00c6ff,00ffff,00ffff,00ffff,00ffff,00ffff,00c5ff,000000,000000,000000,000000,000000
+16:00dbff,00ffff,00ffff,00ffff,00ffff,00ffff,00daff,000000,000000,000000,000000,000000
+16:00ebff,00ffff,00ffff,00ffff,00ffff,00ffff,00eaff,000000,000000,000000,000000,000000
+16:00f8ff,00ffff,00ffff,00ffff,00ffff,00ffff,00f6ff,000000,000000,000000,000000,000000
+16:00ffff,00ffff,00ffff,00ffff,00ffff,00ffff,00feff,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/btconnect.animation b_Alexa LED Animation Files for AVS_linear_7/btconnect.animation
new file mode 100755
index 0000000..f4fa18c
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/btconnect.animation
@@ -0,0 +1,23 @@
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000BB,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000EE,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000FF,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/btdisconnect.animation b_Alexa LED Animation Files for AVS_linear_7/btdisconnect.animation
new file mode 100755
index 0000000..f4fa18c
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/btdisconnect.animation
@@ -0,0 +1,23 @@
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000BB,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000EE,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000FF,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+75:000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011,000011
+16:000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022,000022
+16:000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055,000055
+16:000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088,000088
+16:0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb,0000bb
+16:0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee,0000ee
+150:0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff,0000ff
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/do_not_disturb.animation b_Alexa LED Animation Files for AVS_linear_7/do_not_disturb.animation
new file mode 100644
index 0000000..32b8150
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/do_not_disturb.animation
@@ -0,0 +1,110 @@
+16:0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,000000
+16:0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,000000
+16:10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,000000
+16:120025,120025,120025,120025,120025,120025,120025,120025,120025,120025,120025,000000
+16:15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,000000
+16:180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,000000
+16:1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,000000
+16:1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,000000
+16:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,000000
+16:220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,000000
+16:24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,000000
+16:27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,000000
+16:290053,290053,290053,290053,290053,290053,290053,290053,290053,290053,290053,000000
+16:2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,000000
+16:2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,000000
+16:2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,000000
+16:320065,320065,320065,320065,320065,320065,320065,320065,320065,320065,320065,000000
+16:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,000000
+16:36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,000000
+16:380072,380072,380072,380072,380072,380072,380072,380072,380072,380072,380072,000000
+16:3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,000000
+16:3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,000000
+16:3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,000000
+16:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,000000
+16:420086,420086,420086,420086,420086,420086,420086,420086,420086,420086,420086,000000
+16:430088,430088,430088,430088,430088,430088,430088,430088,430088,430088,430088,000000
+16:45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,000000
+16:46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,000000
+16:47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,000000
+16:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,000000
+16:490093,490093,490093,490093,490093,490093,490093,490093,490093,490093,490093,000000
+16:4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,000000
+16:4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,000000
+16:4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,000000
+16:4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,000000
+16:4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,000000
+16:5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,000000
+16:5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,000000
+16:5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,000000
+16:5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,000000
+16:5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,000000
+16:5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,000000
+16:4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,000000
+16:4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,000000
+16:4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,000000
+16:4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,000000
+16:4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,000000
+16:4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,000000
+16:490092,490092,490092,490092,490092,490092,490092,490092,490092,490092,490092,000000
+16:480090,480090,480090,480090,480090,480090,480090,480090,480090,480090,480090,000000
+16:47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,000000
+16:46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,000000
+16:45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,000000
+16:440087,440087,440087,440087,440087,440087,440087,440087,440087,440087,440087,000000
+16:420085,420085,420085,420085,420085,420085,420085,420085,420085,420085,420085,000000
+16:410082,410082,410082,410082,410082,410082,410082,410082,410082,410082,410082,000000
+16:400080,400080,400080,400080,400080,400080,400080,400080,400080,400080,400080,000000
+16:3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,000000
+16:3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,000000
+16:3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,000000
+16:3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,000000
+16:390073,390073,390073,390073,390073,390073,390073,390073,390073,390073,390073,000000
+16:380070,380070,380070,380070,380070,380070,380070,380070,380070,380070,380070,000000
+16:37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,000000
+16:36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,000000
+16:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,000000
+16:330066,330066,330066,330066,330066,330066,330066,330066,330066,330066,330066,000000
+16:320064,320064,320064,320064,320064,320064,320064,320064,320064,320064,320064,000000
+16:310061,310061,310061,310061,310061,310061,310061,310061,310061,310061,310061,000000
+16:2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,000000
+16:2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,000000
+16:2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,000000
+16:2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,000000
+16:2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,000000
+16:290052,290052,290052,290052,290052,290052,290052,290052,290052,290052,290052,000000
+16:28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,000000
+16:26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,000000
+16:25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,000000
+16:240047,240047,240047,240047,240047,240047,240047,240047,240047,240047,240047,000000
+16:220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,000000
+16:210042,210042,210042,210042,210042,210042,210042,210042,210042,210042,210042,000000
+16:200040,200040,200040,200040,200040,200040,200040,200040,200040,200040,200040,000000
+16:1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,000000
+16:1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,000000
+16:1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,000000
+16:1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,000000
+16:190033,190033,190033,190033,190033,190033,190033,190033,190033,190033,190033,000000
+16:180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,000000
+16:17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,000000
+16:16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,000000
+16:140029,140029,140029,140029,140029,140029,140029,140029,140029,140029,140029,000000
+16:130026,130026,130026,130026,130026,130026,130026,130026,130026,130026,130026,000000
+16:120024,120024,120024,120024,120024,120024,120024,120024,120024,120024,120024,000000
+16:110021,110021,110021,110021,110021,110021,110021,110021,110021,110021,110021,000000
+16:0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,000000
+16:0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,000000
+16:0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,000000
+16:0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,000000
+16:0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,000000
+16:090012,090012,090012,090012,090012,090012,090012,090012,090012,090012,090012,000000
+16:08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,000000
+16:06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,000000
+16:05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,000000
+16:040008,040008,040008,040008,040008,040008,040008,040008,040008,040008,040008,000000
+16:030006,030006,030006,030006,030006,030006,030006,030006,030006,030006,030006,000000
+16:020004,020004,020004,020004,020004,020004,020004,020004,020004,020004,020004,000000
+16:010002,010002,010002,010002,010002,010002,010002,010002,010002,010002,010002,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/error.animation b_Alexa LED Animation Files for AVS_linear_7/error.animation
new file mode 100644
index 0000000..1f777e0
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/error.animation
@@ -0,0 +1,86 @@
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:A00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:E00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
diff --git a_Alexa LED Animation Files for AVS_linear_7/mics-off_end.animation b_Alexa LED Animation Files for AVS_linear_7/mics-off_end.animation
new file mode 100755
index 0000000..0c6c787
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/mics-off_end.animation
@@ -0,0 +1,12 @@
+16:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+16:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+16:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+16:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+16:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
+16:880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000,880000
+16:660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000,660000
+16:550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000,550000
+16:330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000,330000
+16:110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000,110000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/mics-off_on.animation b_Alexa LED Animation Files for AVS_linear_7/mics-off_on.animation
new file mode 100644
index 0000000..12da7fd
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/mics-off_on.animation
@@ -0,0 +1,8 @@
+66:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+66:EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000,EE0000
+66:DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000,DD0000
+66:CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000,CC0000
+66:BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000,BB0000
+66:AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000,AA0000
+loop
+1000:990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000,990000
diff --git a_Alexa LED Animation Files for AVS_linear_7/mics-off_start.animation b_Alexa LED Animation Files for AVS_linear_7/mics-off_start.animation
new file mode 100755
index 0000000..ae73623
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/mics-off_start.animation
@@ -0,0 +1,167 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:030000,030000,030000,030000,030000,030000,030000,000000,000000,000000,000000,000000
+16:090000,090000,090000,090000,090000,090000,090000,000000,000000,000000,000000,000000
+16:110000,110000,110000,110000,110000,110000,110000,000000,000000,000000,000000,000000
+16:170000,170000,170000,170000,170000,170000,170000,000000,000000,000000,000000,000000
+16:1d0000,1d0000,1d0000,1d0000,1d0000,1d0000,1d0000,000000,000000,000000,000000,000000
+16:270000,270000,270000,270000,270000,270000,270000,000000,000000,000000,000000,000000
+16:3a0000,3a0000,3a0000,3a0000,3a0000,3a0000,3a0000,000000,000000,000000,000000,000000
+16:5f0000,5f0000,5f0000,5f0000,5f0000,5f0000,5f0000,000000,000000,000000,000000,000000
+16:a50000,a50000,a50000,a50000,a50000,a50000,a50000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,ff0000,000000,000000,000000,000000,000000
+16:f60000,f60000,f60000,f60000,f60000,f60000,f60000,000000,000000,000000,000000,000000
+16:ea0000,ea0000,ea0000,ea0000,ea0000,ea0000,ea0000,000000,000000,000000,000000,000000
+16:de0000,de0000,de0000,de0000,de0000,de0000,de0000,000000,000000,000000,000000,000000
+16:d50000,d50000,d50000,d50000,d50000,d50000,d50000,000000,000000,000000,000000,000000
+16:c90000,c90000,c90000,c90000,c90000,c90000,c90000,000000,000000,000000,000000,000000
+16:be0000,be0000,be0000,be0000,be0000,be0000,be0000,000000,000000,000000,000000,000000
+16:b00000,b00000,b00000,b00000,b00000,b00000,b00000,000000,000000,000000,000000,000000
+16:a50000,a50000,a50000,a50000,a50000,a50000,a50000,000000,000000,000000,000000,000000
+16:9b0000,9b0000,9b0000,9b0000,9b0000,9b0000,9b0000,000000,000000,000000,000000,000000
+16:910000,910000,910000,910000,910000,910000,910000,000000,000000,000000,000000,000000
+16:880000,880000,880000,880000,880000,880000,880000,000000,000000,000000,000000,000000
+16:7d0000,7d0000,7d0000,7d0000,7d0000,7d0000,7d0000,000000,000000,000000,000000,000000
+16:750000,750000,750000,750000,750000,750000,750000,000000,000000,000000,000000,000000
+16:6e0000,6e0000,6e0000,6e0000,6e0000,6e0000,6e0000,000000,000000,000000,000000,000000
+16:670000,670000,670000,670000,670000,670000,670000,000000,000000,000000,000000,000000
+16:5f0000,5f0000,5f0000,5f0000,5f0000,5f0000,5f0000,000000,000000,000000,000000,000000
+16:5a0000,5a0000,5a0000,5a0000,5a0000,5a0000,5a0000,000000,000000,000000,000000,000000
+16:540000,540000,540000,540000,540000,540000,540000,000000,000000,000000,000000,000000
+16:4e0000,4e0000,4e0000,4e0000,4e0000,4e0000,4e0000,000000,000000,000000,000000,000000
+16:4a0000,4a0000,4a0000,4a0000,4a0000,4a0000,4a0000,000000,000000,000000,000000,000000
+16:460000,460000,460000,460000,460000,460000,460000,000000,000000,000000,000000,000000
+16:420000,420000,420000,420000,420000,420000,420000,000000,000000,000000,000000,000000
+16:3e0000,3e0000,3e0000,3e0000,3e0000,3e0000,3e0000,000000,000000,000000,000000,000000
+16:3a0000,3a0000,3a0000,3a0000,3a0000,3a0000,3a0000,000000,000000,000000,000000,000000
+16:370000,370000,370000,370000,370000,370000,370000,000000,000000,000000,000000,000000
+16:350000,350000,350000,350000,350000,350000,350000,000000,000000,000000,000000,000000
+16:320000,320000,320000,320000,320000,320000,320000,000000,000000,000000,000000,000000
+16:2f0000,2f0000,2f0000,2f0000,2f0000,2f0000,2f0000,000000,000000,000000,000000,000000
+16:2d0000,2d0000,2d0000,2d0000,2d0000,2d0000,2d0000,000000,000000,000000,000000,000000
+16:2b0000,2b0000,2b0000,2b0000,2b0000,2b0000,2b0000,000000,000000,000000,000000,000000
+16:290000,290000,290000,290000,290000,290000,290000,000000,000000,000000,000000,000000
+16:270000,270000,270000,270000,270000,270000,270000,000000,000000,000000,000000,000000
+16:250000,250000,250000,250000,250000,250000,250000,000000,000000,000000,000000,000000
+16:240000,240000,240000,240000,240000,240000,240000,000000,000000,000000,000000,000000
+16:230000,230000,230000,230000,230000,230000,230000,000000,000000,000000,000000,000000
+16:210000,210000,210000,210000,210000,210000,210000,000000,000000,000000,000000,000000
+16:200000,200000,200000,200000,200000,200000,200000,000000,000000,000000,000000,000000
+16:1f0000,1f0000,1f0000,1f0000,1f0000,1f0000,1f0000,000000,000000,000000,000000,000000
+16:1e0000,1e0000,1e0000,1e0000,1e0000,1e0000,1e0000,000000,000000,000000,000000,000000
+16:1d0000,1d0000,1d0000,1d0000,1d0000,1d0000,1d0000,000000,000000,000000,000000,000000
+16:1c0000,1c0000,1c0000,1c0000,1c0000,1c0000,1c0000,000000,000000,000000,000000,000000
+16:1b0000,1b0000,1b0000,1b0000,1b0000,1b0000,1b0000,000000,000000,000000,000000,000000
+16:1b0000,1b0000,1b0000,1b0000,1b0000,1b0000,1b0000,000000,000000,000000,000000,000000
+16:1a0000,1a0000,1a0000,1a0000,1a0000,1a0000,1a0000,000000,000000,000000,000000,000000
+16:190000,190000,190000,190000,190000,190000,190000,000000,000000,000000,000000,000000
+16:180000,180000,180000,180000,180000,180000,180000,000000,000000,000000,000000,000000
+16:180000,180000,180000,180000,180000,180000,180000,000000,000000,000000,000000,000000
+16:170000,170000,170000,170000,170000,170000,170000,000000,000000,000000,000000,000000
+16:160000,160000,160000,160000,160000,160000,160000,000000,000000,000000,000000,000000
+16:160000,160000,160000,160000,160000,160000,160000,000000,000000,000000,000000,000000
+16:150000,150000,150000,150000,150000,150000,150000,000000,000000,000000,000000,000000
+16:140000,140000,140000,140000,140000,140000,140000,000000,000000,000000,000000,000000
+16:130000,130000,130000,130000,130000,130000,130000,000000,000000,000000,000000,000000
+16:120000,120000,120000,120000,120000,120000,120000,000000,000000,000000,000000,000000
+16:120000,120000,120000,120000,120000,120000,120000,000000,000000,000000,000000,000000
+16:110000,110000,110000,110000,110000,110000,110000,000000,000000,000000,000000,000000
+16:100000,100000,100000,100000,100000,100000,100000,000000,000000,000000,000000,000000
+16:0f0000,0f0000,0f0000,0f0000,0f0000,0f0000,0f0000,000000,000000,000000,000000,000000
+16:0e0000,0e0000,0e0000,0e0000,0e0000,0e0000,0e0000,000000,000000,000000,000000,000000
+16:0d0000,0d0000,0d0000,0d0000,0d0000,0d0000,0d0000,000000,000000,000000,000000,000000
+16:0c0000,0c0000,0c0000,0c0000,0c0000,0c0000,0c0000,000000,000000,000000,000000,000000
+16:0b0000,0b0000,0b0000,0b0000,0b0000,0b0000,0b0000,000000,000000,000000,000000,000000
+16:0a0000,0a0000,0a0000,0a0000,0a0000,0a0000,0a0000,000000,000000,000000,000000,000000
+16:090000,090000,090000,090000,090000,090000,090000,000000,000000,000000,000000,000000
+16:080000,080000,080000,080000,080000,080000,080000,000000,000000,000000,000000,000000
+16:070000,070000,070000,070000,070000,070000,070000,000000,000000,000000,000000,000000
+16:060000,060000,060000,060000,060000,060000,060000,000000,000000,000000,000000,000000
+16:060000,060000,060000,060000,060000,060000,060000,000000,000000,000000,000000,000000
+16:050000,050000,050000,050000,050000,050000,050000,000000,000000,000000,000000,000000
+16:040000,040000,040000,040000,040000,040000,040000,000000,000000,000000,000000,000000
+16:030000,030000,030000,030000,030000,030000,030000,000000,000000,000000,000000,000000
+16:030000,030000,030000,030000,030000,030000,030000,000000,000000,000000,000000,000000
+16:020000,020000,020000,020000,020000,020000,020000,000000,000000,000000,000000,000000
+16:010000,010000,010000,010000,010000,010000,010000,000000,000000,000000,000000,000000
+16:010000,010000,010000,010000,010000,010000,010000,000000,000000,000000,000000,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/ntf_incoming.animation b_Alexa LED Animation Files for AVS_linear_7/ntf_incoming.animation
new file mode 100644
index 0000000..cb60029
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/ntf_incoming.animation
@@ -0,0 +1,172 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,000000
+16:0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,000000
+16:120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,000000
+16:181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,000000
+16:1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,000000
+16:2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,000000
+16:352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,000000
+16:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,000000
+16:413600,413600,413600,413600,413600,413600,413600,413600,413600,413600,413600,000000
+16:473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,000000
+16:4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,000000
+16:534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,000000
+16:594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,000000
+16:5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,000000
+16:655400,655400,655400,655400,655400,655400,655400,655400,655400,655400,655400,000000
+16:6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,000000
+16:715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,000000
+16:776300,776300,776300,776300,776300,776300,776300,776300,776300,776300,776300,000000
+16:7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,000000
+16:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,000000
+16:887100,887100,887100,887100,887100,887100,887100,887100,887100,887100,887100,000000
+16:8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,000000
+16:947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,000000
+16:9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,000000
+16:a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,000000
+16:a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,000000
+16:ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,000000
+16:b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,000000
+16:b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,000000
+16:be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,000000
+16:c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,000000
+16:caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,000000
+16:d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,000000
+16:e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,000000
+16:edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,000000
+16:f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,000000
+16:f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,000000
+16:f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,000000
+16:edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,000000
+16:e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,000000
+16:e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,000000
+16:c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,000000
+16:c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,000000
+16:bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,000000
+16:b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,000000
+16:b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,000000
+16:aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,000000
+16:a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,000000
+16:9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,000000
+16:987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,000000
+16:927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,000000
+16:8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,000000
+16:866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,000000
+16:806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,000000
+16:796500,796500,796500,796500,796500,796500,796500,796500,796500,796500,796500,000000
+16:736000,736000,736000,736000,736000,736000,736000,736000,736000,736000,736000,000000
+16:6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,000000
+16:675600,675600,675600,675600,675600,675600,675600,675600,675600,675600,675600,000000
+16:615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,000000
+16:5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,000000
+16:554700,554700,554700,554700,554700,554700,554700,554700,554700,554700,554700,000000
+16:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,000000
+16:493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,000000
+16:433800,433800,433800,433800,433800,433800,433800,433800,433800,433800,433800,000000
+16:3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,000000
+16:372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,000000
+16:312800,312800,312800,312800,312800,312800,312800,312800,312800,312800,312800,000000
+16:2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,000000
+16:181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,000000
+16:120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,000000
+16:0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,000000
+16:060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_linear_7/ntf_queued.animation b_Alexa LED Animation Files for AVS_linear_7/ntf_queued.animation
new file mode 100644
index 0000000..0a6a7e7
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_linear_7/ntf_queued.animation
@@ -0,0 +1,150 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,000000
+16:0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,000000
+16:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,000000
+16:141100,141100,141100,141100,141100,141100,141100,141100,141100,141100,141100,000000
+16:1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,000000
+16:1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,000000
+16:2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,000000
+16:332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,000000
+16:382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,000000
+16:3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,000000
+16:423700,423700,423700,423700,423700,423700,423700,423700,423700,423700,423700,000000
+16:473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,000000
+16:4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,000000
+16:524400,524400,524400,524400,524400,524400,524400,524400,524400,524400,524400,000000
+16:574800,574800,574800,574800,574800,574800,574800,574800,574800,574800,574800,000000
+16:5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,000000
+16:615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,000000
+16:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,000000
+16:6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,000000
+16:705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,000000
+16:756200,756200,756200,756200,756200,756200,756200,756200,756200,756200,756200,000000
+16:7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,000000
+16:806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,000000
+16:856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,000000
+16:8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,000000
+16:8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,000000
+16:947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,000000
+16:997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,000000
+16:9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,000000
+16:a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,000000
+16:a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,000000
+16:ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,000000
+16:b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,000000
+16:b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,000000
+16:bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,000000
+16:c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,000000
+16:c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,000000
+16:ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,000000
+16:d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,000000
+16:d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,000000
+16:e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,000000
+16:ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,000000
+16:f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,000000
+16:f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,000000
+16:fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,000000
+16:f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,000000
+16:efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,000000
+16:eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,000000
+16:e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,000000
+16:e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,000000
+16:cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,000000
+16:c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,000000
+16:c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,000000
+16:bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,000000
+16:b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,000000
+16:b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,000000
+16:ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,000000
+16:a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,000000
+16:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,000000
+16:9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,000000
+16:977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,000000
+16:927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,000000
+16:8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,000000
+16:877000,877000,877000,877000,877000,877000,877000,877000,877000,877000,877000,000000
+16:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,000000
+16:7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,000000
+16:786400,786400,786400,786400,786400,786400,786400,786400,786400,786400,786400,000000
+16:725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,000000
+16:6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,000000
+16:685700,685700,685700,685700,685700,685700,685700,685700,685700,685700,685700,000000
+16:635200,635200,635200,635200,635200,635200,635200,635200,635200,635200,635200,000000
+16:5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,000000
+16:584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,000000
+16:534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,000000
+16:4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,000000
+16:493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,000000
+16:443800,443800,443800,443800,443800,443800,443800,443800,443800,443800,443800,000000
+16:3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,000000
+16:393000,393000,393000,393000,393000,393000,393000,393000,393000,393000,393000,000000
+16:342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,000000
+16:2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,000000
+16:2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,000000
+16:1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,000000
+16:151100,151100,151100,151100,151100,151100,151100,151100,151100,151100,151100,000000
+16:100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,000000
+16:0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,000000
+16:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+1500:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_radial_12/active-ending.animation b_Alexa LED Animation Files for AVS_radial_12/active-ending.animation
new file mode 100644
index 0000000..1542449
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/active-ending.animation
@@ -0,0 +1,16 @@
+22:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,0FF,0FF
+21:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,0FF,0FF
+20:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,000000,000000
+20:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,000000,000000
+20:0FF,00F,00F,00F,00F,00F,00F,00F,00F,0FF,000000,000000
+20:0FF,00F,00F,00F,00F,00F,00F,00F,00F,0FF,000000,000000
+20:000000,0FF,00F,00F,00F,00F,00F,00F,0FF,000000,000000,000000
+20:000000,0FF,00F,00F,00F,00F,00F,00F,0FF,000000,000000,000000
+20:000000,000000,0FF,00F,00F,00F,00F,0FF,000000,000000,000000,000000
+20:000000,000000,0FF,00F,00F,00F,00F,0FF,000000,000000,000000,000000
+15:000000,000000,000000,0FF,00F,00F,0FF,000000,000000,000000,000000,000000
+15:000000,000000,000000,0FF,00F,00F,0FF,000000,000000,000000,000000,000000
+15:000000,000000,000000,000000,0FF,0FF,000000,000000,000000,000000,000000,000000
+15:000000,000000,000000,000000,0FF,0FF,000000,000000,000000,000000,000000,000000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_radial_12/active-talking.animation b_Alexa LED Animation Files for AVS_radial_12/active-talking.animation
new file mode 100644
index 0000000..bd2d899
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/active-talking.animation
@@ -0,0 +1,57 @@
+100:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+90:0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef
+90:0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df
+80:0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf
+70:0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf
+60:0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af
+50:09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f
+40:08f,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f
+40:07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f
+40:06f,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f
+40:05F,05F,05F,05F,05F,05F,05F,05F,05F,05F,05F,05F
+40:04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F
+40:03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F
+40:02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F
+100:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,00F
+40:02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F
+40:03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F
+40:04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F
+40:05f,05f,05f,05f,05f,05f,05f,05f,05f,05f,05f,05f
+40:06F,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f
+40:07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f
+50:08F,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f
+60:09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f
+70:0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af
+80:0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf
+90:0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf
+90:0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df
+90:0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef
+100:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+90:0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef
+90:0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df
+80:0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf
+70:0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf
+60:0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af
+50:09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f
+40:08f,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f
+40:07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f
+40:06f,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f
+40:05F,05F,05F,05F,05F,05F,05F,05F,05F,05F,05F,05F
+40:04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F
+40:03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F
+40:02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F
+100:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,00F
+40:02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F,02F
+40:03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F,03F
+40:04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F,04F
+40:05f,05f,05f,05f,05f,05f,05f,05f,05f,05f,05f,05f
+40:06F,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f,06f
+40:07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f,07f
+50:08F,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f,08f
+60:09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f,09f
+70:0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af,0af
+80:0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf,0bf
+90:0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf,0cf
+90:0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df,0df
+90:0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef,0ef
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/active-thinking.animation b_Alexa LED Animation Files for AVS_radial_12/active-thinking.animation
new file mode 100644
index 0000000..1898991
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/active-thinking.animation
@@ -0,0 +1,10 @@
+loop
+100:09F,00f,0FF,05F,0CE,00F,0FF,05f,00F,05f,0ff,00F
+100:00F,05F,09F,0CE,00F,09F,05f,0FF,00f,0ce,00f,0ce
+100:0ff,0ce,00F,09F,05F,00F,0FF,00f,0ce,0ff,0ce,00f
+100:00F,09F,05f,0FF,09F,05F,0CE,0CE,05f,05F,00F,09F
+100:0FF,00f,0ce,05f,00f,0CE,00F,05F,0ce,00f,0CE,00f
+100:05f,09F,00f,0CE,0CE,00F,09F,0FF,00f,09F,00F,0ff
+100:00F,0ce,0FF,05f,00F,0FF,0ce,05f,0ff,05F,0ce,00F
+100:0FF,05f,09F,00F,0CE,05f,00f,0CE,05F,0FF,00F,09F
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/active-waking.animation b_Alexa LED Animation Files for AVS_radial_12/active-waking.animation
new file mode 100644
index 0000000..73248ae
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/active-waking.animation
@@ -0,0 +1,16 @@
+11:000000,000000,000000,000000,0FF,0FF,000000,000000,000000,000000,000000,000000
+12:000000,000000,000000,000000,0DF,0DF,000000,000000,000000,000000,000000,000000
+13:000000,000000,000000,0FF,0AF,0AF,0FF,000000,000000,000000,000000,000000
+14:000000,000000,000000,0DF,00F,00F,0DF,000000,000000,000000,000000,000000
+15:000000,000000,0FF,0AF,00F,00F,0AF,0FF,000000,000000,000000,000000
+16:000000,000000,0DF,00F,00F,00F,00F,0DF,000000,000000,000000,000000
+17:000000,0FF,0AF,00F,00F,00F,00F,0AF,0FF,000000,000000,000000
+18:000000,0DF,00F,00F,00F,00F,00F,00F,0DF,000000,000000,000000
+19:0FF,0AF,00F,00F,00F,00F,00F,00F,0AF,0FF,000000,000000
+20:0DF,00F,00F,00F,00F,00F,00F,00F,00F,0DF,000000,000000
+21:0AF,00F,00F,00F,00F,00F,00F,00F,00F,0AF,0FF,0FF
+22:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,0DF,0DF
+22:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,0AF,0AF
+loop
+1000:00F,00F,00F,00F,00F,00F,00F,00F,00F,00F,0FF,0FF
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/alert-short.animation b_Alexa LED Animation Files for AVS_radial_12/alert-short.animation
new file mode 100644
index 0000000..066cdbd
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/alert-short.animation
@@ -0,0 +1,36 @@
+50:000,0bf,0bf,000,000,000,000,0bf,0bf,000,000,000
+50:00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+250:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000
+50:000,0bf,0bf,000,000,000,000,0bf,0bf,000,000,000
+50:000,000,0bf,0bf,000,000,000,000,0bf,0bf,000,000
+50:000,00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000
+50:000,0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000
+50:00F,0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F
+50:0bf,0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf
+250:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0bf,0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf
+50:00F,0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F
+50:000,0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000
+50:000,00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000
+50:000,000,0bf,0bf,000,000,000,00F,0bf,0bf,000,000
+50:000,0bf,0bf,00F,000,000,000,0bf,0bf,00F,000,000
+50:00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+250:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:000,0ff,0ff,000,000,000,00F,0ff,0ff,00F,000,000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/alert.animation b_Alexa LED Animation Files for AVS_radial_12/alert.animation
new file mode 100644
index 0000000..5367e83
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/alert.animation
@@ -0,0 +1,46 @@
+loop
+50:000,0bf,0bf,000,000,000,000,0bf,0bf,000,000,000
+50:00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+250:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000
+50:000,0bf,0bf,000,000,000,000,0bf,0bf,000,000,000
+50:000,000,0bf,0bf,000,000,000,000,0bf,0bf,000,000
+50:000,00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000
+50:000,0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000
+50:00F,0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F
+50:0bf,0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf
+250:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0bf,0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf
+50:00F,0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F
+50:000,0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000
+50:000,00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000
+50:000,000,0bf,0bf,000,000,000,00F,0bf,0bf,000,000
+50:000,0bf,0bf,00F,000,000,000,0bf,0bf,00F,000,000
+50:00F,0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+250:0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0ff,0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf
+50:0ff,0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F
+50:0bf,0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000
+50:000,0ff,0ff,000,000,000,00F,0ff,0ff,00F,000,000
+50:00F,0bf,0bf,000,000,000,00F,0bf,0bf,000,000,000
+50:0bf,0bf,00F,000,000,000,0bf,0bf,00F,000,000,000
+50:0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000,00F
+50:0ff,0ff,0bf,000,000,0bf,0FF,0ff,0bf,000,000,0bf
+50:0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F,0ff
+50:0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf,0ff
+250:0ff,0ff,0FF,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff,0ff
+50:0ff,0ff,0ff,0bf,0bf,0ff,0ff,0ff,0ff,0bf,0bf,0ff
+50:0ff,0ff,0ff,00F,00F,0ff,0ff,0ff,0ff,00F,00F,0ff
+50:0ff,0ff,0bf,000,000,0bf,0ff,0ff,0bf,000,000,0bf
+50:0ff,0ff,00F,000,000,00F,0ff,0ff,00F,000,000,00F
+50:0bf,0bf,00F,000,000,000,0bf,0bf,00F,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/btconnect.animation b_Alexa LED Animation Files for AVS_radial_12/btconnect.animation
new file mode 100644
index 0000000..767544b
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/btconnect.animation
@@ -0,0 +1,48 @@
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00A,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00B,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00C,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00D,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00E,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00F,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/btdisconnect.animation b_Alexa LED Animation Files for AVS_radial_12/btdisconnect.animation
new file mode 100644
index 0000000..767544b
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/btdisconnect.animation
@@ -0,0 +1,48 @@
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00A,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00B,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00C,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00D,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00E,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00F,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/do_not_disturb.animation b_Alexa LED Animation Files for AVS_radial_12/do_not_disturb.animation
new file mode 100644
index 0000000..123774f
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/do_not_disturb.animation
@@ -0,0 +1,59 @@
+10:0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014
+10:020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005
+10:05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A
+10:07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F
+10:0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014
+10:0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019
+10:0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E
+10:110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023
+10:140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028
+10:16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D
+10:190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034
+10:1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A
+22:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041
+22:230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048
+22:27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E
+22:2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055
+22:2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C
+22:310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062
+22:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069
+22:370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070
+22:3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076
+22:3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D
+22:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084
+50:45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A
+50:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091
+50:4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098
+50:4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E
+60:5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5,5200A5
+50:4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E,4F009E
+50:4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098,4B0098
+50:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091
+50:45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A,45008A
+40:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084
+40:3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D,3E007D
+40:3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076,3B0076
+40:370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070,370070
+40:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069
+40:310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062,310062
+40:2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C,2D005C
+40:2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055,2A0055
+40:27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E,27004E
+40:230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048,230048
+40:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041
+40:1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A,1D003A
+40:190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034,190034
+40:16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D,16002D
+40:140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028,140028
+40:110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023,110023
+40:0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E,0F001E
+40:0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019,0C0019
+40:0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014,0A0014
+40:07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F,07000F
+40:05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A,05000A
+30:020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005,020005
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_radial_12/error.animation b_Alexa LED Animation Files for AVS_radial_12/error.animation
new file mode 100644
index 0000000..1263a33
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/error.animation
@@ -0,0 +1,86 @@
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:A00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:E00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/mics-off_end.animation b_Alexa LED Animation Files for AVS_radial_12/mics-off_end.animation
new file mode 100644
index 0000000..5e880d1
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/mics-off_end.animation
@@ -0,0 +1,19 @@
+# MICS OFF - END
+
+11:F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00
+11:E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00
+11:D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00
+11:C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00
+11:B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00
+11:A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00
+11:900,900,900,900,900,900,900,900,900,900,900,900
+11:800,800,800,800,800,800,800,800,800,800,800,800
+11:700,700,700,700,700,700,700,700,700,700,700,700
+11:600,600,600,600,600,600,600,600,600,600,600,600
+11:500,500,500,500,500,500,500,500,500,500,500,500
+11:400,400,400,400,400,400,400,400,400,400,400,400
+11:300,300,300,300,300,300,300,300,300,300,300,300
+11:200,200,200,200,200,200,200,200,200,200,200,200
+11:100,100,100,100,100,100,100,100,100,100,100,100
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
\ No newline at end of file
diff --git a_Alexa LED Animation Files for AVS_radial_12/mics-off_on.animation b_Alexa LED Animation Files for AVS_radial_12/mics-off_on.animation
new file mode 100644
index 0000000..f747d57
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/mics-off_on.animation
@@ -0,0 +1,10 @@
+# MICS OFF - ON
+
+66:F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00
+66:E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00
+66:D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00
+66:C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00
+66:B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00
+66:A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00
+loop
+1000:900,900,900,900,900,900,900,900,900,900,900,900
\ No newline at end of file
diff --git a_Alexa LED Animation Files for AVS_radial_12/mics-off_start.animation b_Alexa LED Animation Files for AVS_radial_12/mics-off_start.animation
new file mode 100644
index 0000000..6876eac
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/mics-off_start.animation
@@ -0,0 +1,23 @@
+# MICS OFF - START
+
+33:100,100,100,100,100,100,100,100,100,100,100,100
+33:200,200,200,200,200,200,200,200,200,200,200,200
+33:300,300,300,300,300,300,300,300,300,300,300,300
+33:400,400,400,400,400,400,400,400,400,400,400,400
+33:500,500,500,500,500,500,500,500,500,500,500,500
+33:600,600,600,600,600,600,600,600,600,600,600,600
+33:700,700,700,700,700,700,700,700,700,700,700,700
+33:800,800,800,800,800,800,800,800,800,800,800,800
+33:900,900,900,900,900,900,900,900,900,900,900,900
+33:A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00
+33:B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00
+33:C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00
+33:D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00
+33:E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00
+loop
+1000:F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00
+
+
+
+
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/ntf_incoming.animation b_Alexa LED Animation Files for AVS_radial_12/ntf_incoming.animation
new file mode 100644
index 0000000..946d861
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/ntf_incoming.animation
@@ -0,0 +1,37 @@
+40:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+50:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+50:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400
+50:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+50:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+50:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+50:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+50:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+50:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+50:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+50:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+50:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+50:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+50:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+
+
+1200:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400
+40:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+40:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+40:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+40:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+40:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+40:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+40:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+40:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+40:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+40:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+40:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+40:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+40:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+
+
+
diff --git a_Alexa LED Animation Files for AVS_radial_12/ntf_queued.animation b_Alexa LED Animation Files for AVS_radial_12/ntf_queued.animation
new file mode 100644
index 0000000..159adbb
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_radial_12/ntf_queued.animation
@@ -0,0 +1,29 @@
+60:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+60:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+60:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400
+60:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+60:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+60:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+60:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+60:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+60:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+60:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+60:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+60:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+60:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+60:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+800:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400
+60:e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00,e5bf00
+60:c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400,c4a400
+60:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600
+60:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00
+60:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500
+60:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200
+60:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100
+60:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200
+60:1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700,1c1700
+60:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00
+60:080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600,080600
+60:030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200,030200
+60:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+1500:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_active-ending.animation b_Alexa LED Animation Files for AVS_single_active-ending.animation
new file mode 100755
index 0000000..348dce2
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/active-ending.animation
@@ -0,0 +1,22 @@
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ccff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0080ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0066ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0033ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:001aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000033,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00001a,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+1000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_active-talking.animation b_Alexa LED Animation Files for AVS_single_active-talking.animation
new file mode 100755
index 0000000..fcab371
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/active-talking.animation
@@ -0,0 +1,120 @@
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0001ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0002ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0003ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0004ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0006ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0008ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0010ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0012ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0015ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0018ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:001cff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:001fff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0023ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0026ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:002aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:002eff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0032ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0036ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:003aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:003eff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0043ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0047ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004cff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0050ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0055ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005fff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0064ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0069ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006eff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0073ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0078ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0082ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0088ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0092ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0098ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a3ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a8ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00aeff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b9ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00c4ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00caff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d0ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d6ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00dbff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e1ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e7ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ecff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f7ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00fcff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00feff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00fdff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00fcff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00fbff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f9ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f7ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f4ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00efff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ecff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e9ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e3ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00dfff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00dcff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d8ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d4ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d0ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ccff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00c8ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00c4ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bbff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b6ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b2ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00adff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a8ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a3ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009eff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0094ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008fff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0085ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007fff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0075ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006fff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0064ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005fff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0059ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0053ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004eff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0048ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0042ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:003dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0037ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0031ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:002cff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0026ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0021ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:001bff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0016ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0010ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000bff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0007ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0002ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_active-thinking.animation b_Alexa LED Animation Files for AVS_single_active-thinking.animation
new file mode 100755
index 0000000..cd624bf
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/active-thinking.animation
@@ -0,0 +1,16 @@
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ccff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0066ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0033ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0033ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0066ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ccff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_active-waking.animation b_Alexa LED Animation Files for AVS_single_active-waking.animation
new file mode 100755
index 0000000..408e40c
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/active-waking.animation
@@ -0,0 +1,22 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00001a,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000033,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:001aff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0033ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004dff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0066ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0080ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ccff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+100:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_alert-short.animation b_Alexa LED Animation Files for AVS_single_alert-short.animation
new file mode 100644
index 0000000..a87bd85
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/alert-short.animation
@@ -0,0 +1,207 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000033,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000bf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00008c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000073,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000059,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00005c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00007d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000bf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00008c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000073,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000059,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00335c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00667d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d9d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfbf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a6a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009999,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008c8c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007373,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006666,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005959,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d4d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005c5c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007d7d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a3a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cfcf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d9d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfbf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a6a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009999,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008c8c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007373,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006666,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005959,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d4d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:002a5c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00187d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000ba3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0004cf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000bf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00008c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000073,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000059,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00005c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00007d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000bf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00008c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000073,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000059,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00335c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00667d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d9d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfbf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a6a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009999,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008c8c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007373,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006666,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005959,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d4d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005c5c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007d7d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a3a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cfcf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d9d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfbf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a6a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009999,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008c8c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007373,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006666,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005959,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d4d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:003333,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:002626,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:001a1a,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000d0d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+2000:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_alert.animation b_Alexa LED Animation Files for AVS_single_alert.animation
new file mode 100644
index 0000000..e8d5df6
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/alert.animation
@@ -0,0 +1,100 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000033,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000bf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00008c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000073,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000059,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00005c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00007d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000ff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000cc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000bf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0000a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000099,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00008c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000073,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000066,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000059,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00004d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:000040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00335c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00667d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:0099a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d9d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfbf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a6a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009999,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008c8c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007373,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006666,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005959,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d4d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004040,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005c5c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007d7d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a3a3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cfcf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00ffff,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00f2f2,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00e6e6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00d9d9,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00cccc,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00bfbf,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00b3b3,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:00a6a6,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:009999,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008c8c,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:008080,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:007373,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:006666,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:005959,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:004d4d,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_btconnect.animation b_Alexa LED Animation Files for AVS_single_btconnect.animation
new file mode 100644
index 0000000..767544b
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/btconnect.animation
@@ -0,0 +1,48 @@
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00A,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00B,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00C,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00D,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00E,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00F,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_single_btdisconnect.animation b_Alexa LED Animation Files for AVS_single_btdisconnect.animation
new file mode 100644
index 0000000..767544b
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/btdisconnect.animation
@@ -0,0 +1,48 @@
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00A,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00B,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00C,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00D,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00E,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00F,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+75:001,001,001,001,001,001,001,001,001,001,001,001
+5:002,002,002,002,002,002,002,002,002,002,002,002
+5:003,003,003,003,003,003,003,003,003,003,003,003
+5:004,004,004,004,004,004,004,004,004,004,004,004
+5:005,005,005,005,005,005,005,005,005,005,005,005
+5:006,006,006,006,006,006,006,006,006,006,006,006
+5:007,007,007,007,007,007,007,007,007,007,007,007
+5:008,008,008,008,008,008,008,008,008,008,008,008
+5:009,009,009,009,009,009,009,009,009,009,009,009
+5:00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a,00a
+5:00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b,00b
+5:00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c,00c
+5:00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d,00d
+5:00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e,00e
+150:00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f,00f
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_single_do_not_disturb.animation b_Alexa LED Animation Files for AVS_single_do_not_disturb.animation
new file mode 100644
index 0000000..32b8150
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/do_not_disturb.animation
@@ -0,0 +1,110 @@
+16:0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,000000
+16:0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,0d001a,000000
+16:10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,10001f,000000
+16:120025,120025,120025,120025,120025,120025,120025,120025,120025,120025,120025,000000
+16:15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,15002b,000000
+16:180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,000000
+16:1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,000000
+16:1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,000000
+16:200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,200041,000000
+16:220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,000000
+16:24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,24004a,000000
+16:27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,27004e,000000
+16:290053,290053,290053,290053,290053,290053,290053,290053,290053,290053,290053,000000
+16:2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,000000
+16:2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,2d005c,000000
+16:2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,2f0060,000000
+16:320065,320065,320065,320065,320065,320065,320065,320065,320065,320065,320065,000000
+16:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,000000
+16:36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,36006e,000000
+16:380072,380072,380072,380072,380072,380072,380072,380072,380072,380072,380072,000000
+16:3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,3a0077,000000
+16:3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,000000
+16:3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,3f0080,000000
+16:410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,410084,000000
+16:420086,420086,420086,420086,420086,420086,420086,420086,420086,420086,420086,000000
+16:430088,430088,430088,430088,430088,430088,430088,430088,430088,430088,430088,000000
+16:45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,45008b,000000
+16:46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,46008d,000000
+16:47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,47008f,000000
+16:480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,480091,000000
+16:490093,490093,490093,490093,490093,490093,490093,490093,490093,490093,490093,000000
+16:4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,4a0095,000000
+16:4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,4c0098,000000
+16:4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,4d009a,000000
+16:4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,4e009c,000000
+16:4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,4f009e,000000
+16:5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,5000a0,000000
+16:5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,5100a2,000000
+16:5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,000000
+16:5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,5200a5,000000
+16:5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,5100a3,000000
+16:5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,5000a1,000000
+16:4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,4f009f,000000
+16:4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,4e009d,000000
+16:4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,4d009b,000000
+16:4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,4c0099,000000
+16:4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,4b0096,000000
+16:4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,4a0094,000000
+16:490092,490092,490092,490092,490092,490092,490092,490092,490092,490092,490092,000000
+16:480090,480090,480090,480090,480090,480090,480090,480090,480090,480090,480090,000000
+16:47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,47008e,000000
+16:46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,46008c,000000
+16:45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,45008a,000000
+16:440087,440087,440087,440087,440087,440087,440087,440087,440087,440087,440087,000000
+16:420085,420085,420085,420085,420085,420085,420085,420085,420085,420085,420085,000000
+16:410082,410082,410082,410082,410082,410082,410082,410082,410082,410082,410082,000000
+16:400080,400080,400080,400080,400080,400080,400080,400080,400080,400080,400080,000000
+16:3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,3f007d,000000
+16:3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,3d007b,000000
+16:3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,3c0078,000000
+16:3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,3b0076,000000
+16:390073,390073,390073,390073,390073,390073,390073,390073,390073,390073,390073,000000
+16:380070,380070,380070,380070,380070,380070,380070,380070,380070,380070,380070,000000
+16:37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,37006e,000000
+16:36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,36006b,000000
+16:340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,340069,000000
+16:330066,330066,330066,330066,330066,330066,330066,330066,330066,330066,330066,000000
+16:320064,320064,320064,320064,320064,320064,320064,320064,320064,320064,320064,000000
+16:310061,310061,310061,310061,310061,310061,310061,310061,310061,310061,310061,000000
+16:2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,2f005e,000000
+16:2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,2e005c,000000
+16:2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,2d0059,000000
+16:2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,2b0057,000000
+16:2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,2a0054,000000
+16:290052,290052,290052,290052,290052,290052,290052,290052,290052,290052,290052,000000
+16:28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,28004f,000000
+16:26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,26004d,000000
+16:25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,25004a,000000
+16:240047,240047,240047,240047,240047,240047,240047,240047,240047,240047,240047,000000
+16:220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,220045,000000
+16:210042,210042,210042,210042,210042,210042,210042,210042,210042,210042,210042,000000
+16:200040,200040,200040,200040,200040,200040,200040,200040,200040,200040,200040,000000
+16:1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,1f003d,000000
+16:1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,1d003b,000000
+16:1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,1c0038,000000
+16:1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,1b0036,000000
+16:190033,190033,190033,190033,190033,190033,190033,190033,190033,190033,190033,000000
+16:180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,180030,000000
+16:17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,17002e,000000
+16:16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,16002b,000000
+16:140029,140029,140029,140029,140029,140029,140029,140029,140029,140029,140029,000000
+16:130026,130026,130026,130026,130026,130026,130026,130026,130026,130026,130026,000000
+16:120024,120024,120024,120024,120024,120024,120024,120024,120024,120024,120024,000000
+16:110021,110021,110021,110021,110021,110021,110021,110021,110021,110021,110021,000000
+16:0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,0f001e,000000
+16:0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,0e001c,000000
+16:0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,0d0019,000000
+16:0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,0b0017,000000
+16:0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,0a0014,000000
+16:090012,090012,090012,090012,090012,090012,090012,090012,090012,090012,090012,000000
+16:08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,08000f,000000
+16:06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,06000d,000000
+16:05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,05000a,000000
+16:040008,040008,040008,040008,040008,040008,040008,040008,040008,040008,040008,000000
+16:030006,030006,030006,030006,030006,030006,030006,030006,030006,030006,030006,000000
+16:020004,020004,020004,020004,020004,020004,020004,020004,020004,020004,020004,000000
+16:010002,010002,010002,010002,010002,010002,010002,010002,010002,010002,010002,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_error.animation b_Alexa LED Animation Files for AVS_single_error.animation
new file mode 100644
index 0000000..1263a33
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/error.animation
@@ -0,0 +1,86 @@
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:A00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:E00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+25:380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000,380000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+100:FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000,FF0000
+25:F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000,F80000
+25:F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000,F00000
+25:e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000,e00000
+25:D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000,D00000
+25:C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000,C00000
+25:a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000,a00000
+25:900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000,900000
+25:780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000,780000
+25:680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000,680000
+25:580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000,580000
+25:500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000,500000
+25:480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000,480000
+25:280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000,280000
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
+
diff --git a_Alexa LED Animation Files for AVS_single_mics-off_end.animation b_Alexa LED Animation Files for AVS_single_mics-off_end.animation
new file mode 100644
index 0000000..5e880d1
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/mics-off_end.animation
@@ -0,0 +1,19 @@
+# MICS OFF - END
+
+11:F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00
+11:E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00
+11:D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00
+11:C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00
+11:B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00
+11:A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00
+11:900,900,900,900,900,900,900,900,900,900,900,900
+11:800,800,800,800,800,800,800,800,800,800,800,800
+11:700,700,700,700,700,700,700,700,700,700,700,700
+11:600,600,600,600,600,600,600,600,600,600,600,600
+11:500,500,500,500,500,500,500,500,500,500,500,500
+11:400,400,400,400,400,400,400,400,400,400,400,400
+11:300,300,300,300,300,300,300,300,300,300,300,300
+11:200,200,200,200,200,200,200,200,200,200,200,200
+11:100,100,100,100,100,100,100,100,100,100,100,100
+loop
+1000:000,000,000,000,000,000,000,000,000,000,000,000
\ No newline at end of file
diff --git a_Alexa LED Animation Files for AVS_single_mics-off_on.animation b_Alexa LED Animation Files for AVS_single_mics-off_on.animation
new file mode 100644
index 0000000..fdc181f
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/mics-off_on.animation
@@ -0,0 +1,8 @@
+66:F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00
+66:E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00
+66:D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00
+66:C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00
+66:B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00
+66:A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00
+loop
+1000:900,900,900,900,900,900,900,900,900,900,900,900
\ No newline at end of file
diff --git a_Alexa LED Animation Files for AVS_single_mics-off_start.animation b_Alexa LED Animation Files for AVS_single_mics-off_start.animation
new file mode 100644
index 0000000..6876eac
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/mics-off_start.animation
@@ -0,0 +1,23 @@
+# MICS OFF - START
+
+33:100,100,100,100,100,100,100,100,100,100,100,100
+33:200,200,200,200,200,200,200,200,200,200,200,200
+33:300,300,300,300,300,300,300,300,300,300,300,300
+33:400,400,400,400,400,400,400,400,400,400,400,400
+33:500,500,500,500,500,500,500,500,500,500,500,500
+33:600,600,600,600,600,600,600,600,600,600,600,600
+33:700,700,700,700,700,700,700,700,700,700,700,700
+33:800,800,800,800,800,800,800,800,800,800,800,800
+33:900,900,900,900,900,900,900,900,900,900,900,900
+33:A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00,A00
+33:B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00,B00
+33:C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00,C00
+33:D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00,D00
+33:E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00,E00
+loop
+1000:F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00,F00
+
+
+
+
+
diff --git a_Alexa LED Animation Files for AVS_single_ntf_incoming.animation b_Alexa LED Animation Files for AVS_single_ntf_incoming.animation
new file mode 100644
index 0000000..cb60029
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/ntf_incoming.animation
@@ -0,0 +1,172 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,000000
+16:0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,000000
+16:120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,000000
+16:181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,000000
+16:1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,000000
+16:2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,000000
+16:352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,352c00,000000
+16:3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,3b3100,000000
+16:413600,413600,413600,413600,413600,413600,413600,413600,413600,413600,413600,000000
+16:473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,000000
+16:4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,000000
+16:534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,000000
+16:594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,594a00,000000
+16:5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,5f4f00,000000
+16:655400,655400,655400,655400,655400,655400,655400,655400,655400,655400,655400,000000
+16:6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,000000
+16:715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,715e00,000000
+16:776300,776300,776300,776300,776300,776300,776300,776300,776300,776300,776300,000000
+16:7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,000000
+16:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,000000
+16:887100,887100,887100,887100,887100,887100,887100,887100,887100,887100,887100,000000
+16:8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,8e7600,000000
+16:947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,000000
+16:9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,9a8000,000000
+16:a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,a08500,000000
+16:a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,a68a00,000000
+16:ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,000000
+16:b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,b29400,000000
+16:b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,000000
+16:be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,be9e00,000000
+16:c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,c4a300,000000
+16:caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,caa800,000000
+16:d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,000000
+16:e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,000000
+16:edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,000000
+16:f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,000000
+16:f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,f9cf00,000000
+16:f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,f3ca00,000000
+16:edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,edc500,000000
+16:e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,e7c000,000000
+16:e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,e1bb00,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,ceac00,000000
+16:c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,c8a700,000000
+16:c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,c2a200,000000
+16:bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,bc9c00,000000
+16:b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,000000
+16:b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,b09200,000000
+16:aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,aa8d00,000000
+16:a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,a48800,000000
+16:9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,000000
+16:987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,987e00,000000
+16:927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,000000
+16:8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,8c7400,000000
+16:866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,866f00,000000
+16:806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,000000
+16:796500,796500,796500,796500,796500,796500,796500,796500,796500,796500,796500,000000
+16:736000,736000,736000,736000,736000,736000,736000,736000,736000,736000,736000,000000
+16:6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,000000
+16:675600,675600,675600,675600,675600,675600,675600,675600,675600,675600,675600,000000
+16:615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,000000
+16:5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,5b4c00,000000
+16:554700,554700,554700,554700,554700,554700,554700,554700,554700,554700,554700,000000
+16:4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,4f4200,000000
+16:493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,000000
+16:433800,433800,433800,433800,433800,433800,433800,433800,433800,433800,433800,000000
+16:3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,3d3200,000000
+16:372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,372d00,000000
+16:312800,312800,312800,312800,312800,312800,312800,312800,312800,312800,312800,000000
+16:2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,2b2300,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,1e1900,000000
+16:181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,181400,000000
+16:120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,120f00,000000
+16:0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,0c0a00,000000
+16:060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,060500,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+loop
+33:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_Alexa LED Animation Files for AVS_single_ntf_queued.animation b_Alexa LED Animation Files for AVS_single_ntf_queued.animation
new file mode 100644
index 0000000..0a6a7e7
--- _dev_null
+++ b_Alexa LED Animation Files for AVS_single/ntf_queued.animation
@@ -0,0 +1,150 @@
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+16:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,000000
+16:0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,0a0800,000000
+16:0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,0f0d00,000000
+16:141100,141100,141100,141100,141100,141100,141100,141100,141100,141100,141100,000000
+16:1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,1a1500,000000
+16:1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,1f1900,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,292200,000000
+16:2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,2e2600,000000
+16:332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,332a00,000000
+16:382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,382f00,000000
+16:3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,3d3300,000000
+16:423700,423700,423700,423700,423700,423700,423700,423700,423700,423700,423700,000000
+16:473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,473b00,000000
+16:4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,4d4000,000000
+16:524400,524400,524400,524400,524400,524400,524400,524400,524400,524400,524400,000000
+16:574800,574800,574800,574800,574800,574800,574800,574800,574800,574800,574800,000000
+16:5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,5c4c00,000000
+16:615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,615100,000000
+16:665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,665500,000000
+16:6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,6b5900,000000
+16:705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,705d00,000000
+16:756200,756200,756200,756200,756200,756200,756200,756200,756200,756200,756200,000000
+16:7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,7a6600,000000
+16:806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,806a00,000000
+16:856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,856e00,000000
+16:8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,8a7200,000000
+16:8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,8f7700,000000
+16:947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,947b00,000000
+16:997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,997f00,000000
+16:9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,9e8300,000000
+16:a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,a38800,000000
+16:a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,a88c00,000000
+16:ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,ad9000,000000
+16:b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,b39400,000000
+16:b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,b89900,000000
+16:bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,bd9d00,000000
+16:c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,c2a100,000000
+16:c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,c7a500,000000
+16:ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,ccaa00,000000
+16:d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,d1ae00,000000
+16:d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,d6b200,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,e0bb00,000000
+16:e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,e6bf00,000000
+16:ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,ebc300,000000
+16:f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,f0c700,000000
+16:f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,f5cc00,000000
+16:fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,ffd400,000000
+16:fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,fad000,000000
+16:f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,f5cb00,000000
+16:efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,efc700,000000
+16:eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,eac300,000000
+16:e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,e5be00,000000
+16:e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,e0ba00,000000
+16:dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,dbb600,000000
+16:d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,d5b100,000000
+16:d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,d0ad00,000000
+16:cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,cba900,000000
+16:c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,c6a400,000000
+16:c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,c1a000,000000
+16:bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,bb9c00,000000
+16:b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,b69700,000000
+16:b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,b19300,000000
+16:ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,ac8f00,000000
+16:a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,a78a00,000000
+16:a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,a18600,000000
+16:9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,9c8200,000000
+16:977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,977d00,000000
+16:927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,927900,000000
+16:8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,8d7500,000000
+16:877000,877000,877000,877000,877000,877000,877000,877000,877000,877000,877000,000000
+16:826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,826c00,000000
+16:7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,7d6800,000000
+16:786400,786400,786400,786400,786400,786400,786400,786400,786400,786400,786400,000000
+16:725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,725f00,000000
+16:6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,6d5b00,000000
+16:685700,685700,685700,685700,685700,685700,685700,685700,685700,685700,685700,000000
+16:635200,635200,635200,635200,635200,635200,635200,635200,635200,635200,635200,000000
+16:5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,5e4e00,000000
+16:584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,584a00,000000
+16:534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,534500,000000
+16:4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,4e4100,000000
+16:493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,493d00,000000
+16:443800,443800,443800,443800,443800,443800,443800,443800,443800,443800,443800,000000
+16:3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,3e3400,000000
+16:393000,393000,393000,393000,393000,393000,393000,393000,393000,393000,393000,000000
+16:342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,342b00,000000
+16:2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,2f2700,000000
+16:2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,2a2300,000000
+16:241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,241e00,000000
+16:1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,1f1a00,000000
+16:1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,1a1600,000000
+16:151100,151100,151100,151100,151100,151100,151100,151100,151100,151100,151100,000000
+16:100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,100d00,000000
+16:0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,0a0900,000000
+16:050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,050400,000000
+16:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
+1500:000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000,000000
diff --git a_http.stats.txt b_http.stats.txt
new file mode 100644
index 0000000..8c755f9
--- _dev_null
+++ b/http.stats.txt
@@ -0,0 +1,942 @@
+
+
+
+
+
+
+<!DOCTYPE html>
+<html lang="en">
- [x]  <head>
- [x]    <meta charset="utf-8">
- [x]  <link rel="dns-prefetch" href="https://github.githubassets.com">
- [x]  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
- [x]  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
- [x]  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
- [x]  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
- [x]  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
- [x]  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">
+
+
+
- [x]  <link crossorigin="anonymous" media="all" integrity="sha512-hddDYPWR0gBbqLRmIZP242WMEiYsVkYI2UCYCVUHB4h5DhD2cbtFJYG+HPh21dZGb+sbgDHxQBNJCBq7YbmlBQ==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-02a3eaa24db2bd1ed9b64450595fc2cf.css" />
- [x]  <link crossorigin="anonymous" media="all" integrity="sha512-8BxpFTogSyEi7yQb7rCnH1J/gTxVdHNk1Rrg92rh2zMf++XM8Us8Pcp+5GzjxqRxkax0Ckz52LufuEGch2uE7w==" rel="stylesheet" href="https://github.githubassets.com/assets/site-1faffb77dc8b20778aa60ecb5998972e.css" />
- [x]    <link crossorigin="anonymous" media="all" integrity="sha512-YdIM_FwAk7kxvPGCpeT2JXxPrThv4m9rH7fLzjn+dg3zKb+PWOaxX1ioiOcmOb64+LeDKgBXsGL4b_BJQY/cdA==" rel="stylesheet" href="https://github.githubassets.com/assets/github-102d2679bcc893600ce928d5c6d34297.css" />
- [x]    
- [x]    
- [x]    
- [x]    
+
+
- [x]  <meta name="viewport" content="width=device-width">
- [x]  
- [x]  <title>googlevoice_.travis.yml at master · jaraco_googlevoice · GitHub</title>
- [x]    <meta name="description" content="Python Google Voice library based on pygooglevoice - jaraco/googlevoice">
- [x]    <link rel="search" type="application_opensearchdescription+xml" href="_opensearch.xml" title="GitHub">
- [x]  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
- [x]  <meta property="fb:app_id" content="1401488693436528">
+
- [x]    <meta name="twitter:image:src" content="https://avatars2.githubusercontent.com/u/308610?s=400&amp;v=4" _><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="jaraco_googlevoice" _><meta name="twitter:description" content="Python Google Voice library based on pygooglevoice - jaraco_googlevoice" />
- [x]    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/308610?s=400&amp;v=4" _><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="jaraco_googlevoice" _><meta property="og:url" content="https://github.com/jaraco/googlevoice" /><meta property="og:description" content="Python Google Voice library based on pygooglevoice - jaraco_googlevoice" />
+
- [x]  <link rel="assets" href="https://github.githubassets.com/">
- [x]  
- [x]  
+
- [x]    <meta name="request-id" content="1CFA:40D29:1656D7D:21C3DC1:5E009A64" data-pjax-transient>
+
+
+
- [x]  
+
- [x]  <meta name="selected-link" value="repo_source" data-pjax-transient>
+
- [x]      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
- [x]    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
- [x]    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
+
- [x]    <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="1CFA:40D29:1656D7D:21C3DC1:5E009A64" /><meta name="octolytics-dimension-region_edge" content="ams" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="4742934680062433892" />
+
+<meta name="analytics-location" content="_&lt;user-name&gt;_&lt;repo-name&gt;_blob_show" data-pjax-transient="true" />
+
+
+
- [x]    <meta name="google-analytics" content="UA-3769691-2">
+
+
+<meta class="js-ga-set" name="dimension1" content="Logged Out">
+
- [x]  <meta class="js-ga-set" name="dimension3" content="mobile">
+
+
- [x]  
+
- [x]      <meta name="hostname" content="github.com">
- [x]    <meta name="user-login" content="">
+
- [x]      <meta name="expected-hostname" content="github.com">
+
- [x]      <meta name="js-proxy-site-detection-payload" content="ZDcwMDQzZGY2MTFhNjAxNjBiMmVmNmFhZjc5YjgzMGRlNWIzNWQ4NGRhODA5ODM2N2U1YzYyMGRjMTg4ZTc0Nnx7InJlbW90ZV9hZGRyZXNzIjoiMTk1LjI0Mi4yMTMuMTE1IiwicmVxdWVzdF9pZCI6IjFDRkE6NDBEMjk6MTY1NkQ3RDoyMUMzREMxOjVFMDA5QTY0IiwidGltZXN0YW1wIjoxNTc3MDk3ODI4LCJob3N0IjoiZ2l0aHViLmNvbSJ9">
+
- [x]    <meta name="enabled-features" content="MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS">
+
- [x]    <meta name="html-safe-nonce" content="88bdc7840377f01bfce57b83b9b1f9f32762379d">
+
- [x]  <meta http-equiv="x-pjax-version" content="61f8c219e8739359a3bf9c46bc342ad6">
- [x]  
+
- [x]      <link href="https://github.com/jaraco/googlevoice/commits/master.atom" rel="alternate" title="Recent Commits to googlevoice:master" type="application/atom+xml">
+
- [x]  <meta name="go-import" content="github.com/jaraco/googlevoice git https://github.com/jaraco/googlevoice.git">
+
- [x]  <meta name="octolytics-dimension-user_id" content="308610" _><meta name="octolytics-dimension-user_login" content="jaraco" /><meta name="octolytics-dimension-repository_id" content="127651068" /><meta name="octolytics-dimension-repository_nwo" content="jaraco_googlevoice" _><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="true" /><meta name="octolytics-dimension-repository_parent_id" content="3269817" /><meta name="octolytics-dimension-repository_parent_nwo" content="pettazz_pygooglevoice" _><meta name="octolytics-dimension-repository_network_root_id" content="3269817" /><meta name="octolytics-dimension-repository_network_root_nwo" content="pettazz_pygooglevoice" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />
+
+
- [x]    <link rel="canonical" href="https://github.com/jaraco/googlevoice/blob/master/.travis.yml" data-pjax-transient>
+
+
- [x]  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
+
- [x]  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
+
- [x]  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
- [x]  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">
+
+<meta name="theme-color" content="#1e2327">
+
- [x]  <link rel="apple-touch-icon" href="https://github.githubassets.com/apple-touch-icon.png">
- [x]  <link rel="apple-touch-icon" sizes="180x180" href="https://github.githubassets.com/apple-touch-icon-180x180.png">
- [x]  <meta name="apple-mobile-web-app-title" content="GitHub">
+
+
+
+
- [x]  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">
+
- [x]  </head>
+
- [x]  <body class="logged-out env-production page-responsive page-blob">
- [x]    
+
- [x]  <div class="position-relative js-header-wrapper ">
- [x]    <a href="#start-of-content" tabindex="1" class="px-2 py-4 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
- [x]    <span class="Progress progress-pjax-loader position-fixed width-full js-pjax-loader-bar">
- [x]      <span class="progress-pjax-loader-bar top-0 left-0" style="width: 0%;"></span>
- [x]    </span>
+
- [x]    
- [x]    
- [x]    
+
+
- [x]        <header class="Header-old header-logged-out js-details-container Details position-relative f4 py-2" role="banner">
- [x]  <div class="container-lg d-lg-flex flex-items-center p-responsive">
- [x]    <div class="d-flex flex-justify-between flex-items-center">
- [x]        <a class="mr-4" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
- [x]          <svg height="32" class="octicon octicon-mark-github text-white" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"_><_svg>
- [x]        </a>
+
- [x]          <div class="d-lg-none css-truncate css-truncate-target width-fit p-2">
- [x]            
- [x]              <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"_><_svg>
- [x]    <a class="Header-link" href="_jaraco">jaraco<_a>
- [x]    /
- [x]    <a class="Header-link" href="_jaraco_googlevoice">googlevoice</a>
+
+
- [x]          </div>
+
- [x]        <div class="d-flex flex-items-center">
- [x]            <a href="/join?source=header-repo"
- [x]              class="d-inline-block d-lg-none f5 text-white no-underline border border-gray-dark rounded-2 px-2 py-1 mr-3 mr-sm-5"
- [x]              data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="c6520095b227aa69bb0816f7409cfe12f33921d7b836774191bedba2437f0a06"
- [x]              data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">
- [x]              Sign&nbsp;up
- [x]            </a>
+
- [x]          <button class="btn-link d-lg-none mt-1 js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
- [x]            <svg height="24" class="octicon octicon-three-bars text-white" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"_><_svg>
- [x]          </button>
- [x]        </div>
- [x]    </div>
+
- [x]    <div class="HeaderMenu HeaderMenu--logged-out position-fixed top-0 right-0 bottom-0 height-fit position-lg-relative d-lg-flex flex-justify-between flex-items-center flex-auto">
- [x]      <div class="d-flex d-lg-none flex-justify-end border-bottom bg-gray-light p-3">
- [x]        <button class="btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
- [x]          <svg height="24" class="octicon octicon-x text-gray" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"_><_svg>
- [x]        </button>
- [x]      </div>
+
- [x]        <nav class="mt-0 px-3 px-lg-0 mb-5 mb-lg-0" aria-label="Global">
- [x]          <ul class="d-lg-flex list-style-none">
- [x]              <li class="d-block d-lg-flex flex-lg-nowrap flex-lg-items-center border-bottom border-lg-bottom-0 mr-0 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
- [x]                <details class="HeaderMenu-details details-overlay details-reset width-full">
- [x]                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap d-block d-lg-inline-block">
- [x]                    Why GitHub?
- [x]                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-absolute position-lg-relative">
- [x]                      <path d="M1,1l6.2,6L13,1"></path>
- [x]                    </svg>
- [x]                  </summary>
- [x]                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 mt-0 pb-4 p-lg-4 position-relative position-lg-absolute left-0 left-lg-n4">
- [x]                    <a href="_features" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Features">Features <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span></a>
- [x]                    <ul class="list-style-none f5 pb-3">
- [x]                      <li class="edge-item-fix"><a href="_features_code-review_" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code review">Code review<_a></li>
- [x]                      <li class="edge-item-fix"><a href="_features_project-management_" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Project management">Project management<_a></li>
- [x]                      <li class="edge-item-fix"><a href="_features_integrations" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Integrations">Integrations<_a><_li>
- [x]                      <li class="edge-item-fix"><a href="_features_actions" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Actions">Actions<_a><_li>
- [x]                          <li class="edge-item-fix"><a href="_features_packages" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to GitHub Packages">Packages<_a><_li>
- [x]                      <li class="edge-item-fix"><a href="_features_security" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Security">Security<_a><_li>
- [x]                      <li class="edge-item-fix"><a href="_features#team-management" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Team management">Team management<_a></li>
- [x]                      <li class="edge-item-fix"><a href="_features#hosting" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code hosting">Hosting<_a></li>
- [x]                    </ul>
+
- [x]                    <ul class="list-style-none mb-0 border-lg-top pt-lg-3">
- [x]                      <li class="edge-item-fix"><a href="_customer-stories" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Customer stories">Customer stories <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span><_a><_li>
- [x]                      <li class="edge-item-fix"><a href="_security" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Security">Security <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span><_a><_li>
- [x]                    </ul>
- [x]                  </div>
- [x]                </details>
- [x]              </li>
- [x]              <li class="border-bottom border-lg-bottom-0 mr-0 mr-lg-3">
- [x]                <a href="_enterprise" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Enterprise">Enterprise<_a>
- [x]              </li>
+
- [x]              <li class="d-block d-lg-flex flex-lg-nowrap flex-lg-items-center border-bottom border-lg-bottom-0 mr-0 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
- [x]                <details class="HeaderMenu-details details-overlay details-reset width-full">
- [x]                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap d-block d-lg-inline-block">
- [x]                    Explore
- [x]                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-absolute position-lg-relative">
- [x]                      <path d="M1,1l6.2,6L13,1"></path>
- [x]                    </svg>
- [x]                  </summary>
+
- [x]                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-0 mt-0 pb-4 p-lg-4 position-relative position-lg-absolute left-0 left-lg-n4">
- [x]                    <ul class="list-style-none mb-3">
- [x]                      <li class="edge-item-fix"><a href="_explore" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Explore">Explore GitHub <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span><_a><_li>
- [x]                    </ul>
+
- [x]                    <h4 class="text-gray-light text-normal text-mono f5 mb-2 border-lg-top pt-lg-3">Learn &amp; contribute</h4>
- [x]                    <ul class="list-style-none mb-3">
- [x]                      <li class="edge-item-fix"><a href="_topics" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Topics">Topics<_a></li>
- [x]                        <li class="edge-item-fix"><a href="_collections" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Collections">Collections<_a></li>
- [x]                      <li class="edge-item-fix"><a href="_trending" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Trending">Trending<_a></li>
- [x]                      <li class="edge-item-fix"><a href="https://lab.github.com/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Learning lab">Learning Lab<_a><_li>
- [x]                      <li class="edge-item-fix"><a href="https://opensource.guide" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Open source guides">Open source guides<_a><_li>
- [x]                    </ul>
+
- [x]                    <h4 class="text-gray-light text-normal text-mono f5 mb-2 border-lg-top pt-lg-3">Connect with others</h4>
- [x]                    <ul class="list-style-none mb-0">
- [x]                      <li class="edge-item-fix"><a href="https://github.com/events" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Events">Events<_a><_li>
- [x]                      <li class="edge-item-fix"><a href="https://github.community" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Community forum">Community forum<_a><_li>
- [x]                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to GitHub Education">GitHub Education<_a><_li>
- [x]                    </ul>
- [x]                  </div>
- [x]                </details>
- [x]              </li>
+
- [x]              <li class="border-bottom border-lg-bottom-0 mr-0 mr-lg-3">
- [x]                <a href="_marketplace" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Marketplace">Marketplace<_a>
- [x]              </li>
+
- [x]              <li class="d-block d-lg-flex flex-lg-nowrap flex-lg-items-center border-bottom border-lg-bottom-0 mr-0 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
- [x]                <details class="HeaderMenu-details details-overlay details-reset width-full">
- [x]                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap d-block d-lg-inline-block">
- [x]                    Pricing
- [x]                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-absolute position-lg-relative">
- [x]                       <path d="M1,1l6.2,6L13,1"></path>
- [x]                    </svg>
- [x]                  </summary>
+
- [x]                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-4 mt-0 p-lg-4 position-relative position-lg-absolute left-0 left-lg-n4">
- [x]                    <a href="_pricing" class="pb-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Pricing">Plans <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span></a>
+
- [x]                    <ul class="list-style-none mb-3">
- [x]                      <li class="edge-item-fix"><a href="_pricing#feature-comparison" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Compare plans">Compare plans<_a></li>
- [x]                      <li class="edge-item-fix"><a href="https://enterprise.github.com/contact" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Contact Sales">Contact Sales<_a><_li>
- [x]                    </ul>
+
- [x]                    <ul class="list-style-none mb-0 border-lg-top pt-lg-3">
- [x]                      <li class="edge-item-fix"><a href="_nonprofit" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Nonprofits">Nonprofit <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span><_a><_li>
- [x]                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover"  data-ga-click="(Logged out) Header, go to Education">Education <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;<_span><_a></li>
- [x]                    </ul>
- [x]                  </div>
- [x]                </details>
- [x]              </li>
- [x]          </ul>
- [x]        </nav>
+
- [x]      <div class="d-lg-flex flex-items-center px-3 px-lg-0 text-center text-lg-left">
- [x]          <div class="d-lg-flex mb-3 mb-lg-0">
- [x]            <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative "
- [x]  role="search"
+>
- [x]  <div class="position-relative">
- [x]    <!-- '"` --><!-- <_textarea><_xmp> --><_option><_form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="127651068" data-scoped-search-url="_jaraco_googlevoice_search" data-unscoped-search-url="_search" action="_jaraco_googlevoice/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
- [x]      <label class="form-control input-sm header-search-wrapper p-0  js-chromeless-input-container">
- [x]            <a class="header-search-scope no-underline" href="_jaraco_googlevoice_blob_master_.travis.yml">This repository<_a>
- [x]        <input type="text"
- [x]          class="form-control input-sm header-search-input  js-site-search-focus js-site-search-field is-clearable"
- [x]          data-hotkey="s,/"
- [x]          name="q"
- [x]          value=""
- [x]          placeholder="Search"
- [x]          data-unscoped-placeholder="Search GitHub"
- [x]          data-scoped-placeholder="Search"
- [x]          autocapitalize="off"
- [x]          aria-label="Search this repository"
- [x]          >
- [x]          <input type="hidden" class="js-site-search-type-field" name="type" >
- [x]      </label>
+<_form>  <_div>
+</div>
+
- [x]          </div>
+
- [x]        <a href="/login?return_to=%2Fjaraco%2Fgooglevoice%2Fblob%2Fmaster%2F.travis.yml"
- [x]          class="HeaderMenu-link no-underline mr-3"
- [x]          data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="22b43522fc3ad2b5cfbc37ea87b8e635eaa1e3a4433a10e5754f55cdf1aef85d"
- [x]          data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">
- [x]          Sign&nbsp;in
- [x]        </a>
- [x]          <a href="/join?source=header-repo&amp;source_repo=jaraco%2Fgooglevoice"
- [x]            class="HeaderMenu-link d-inline-block no-underline border border-gray-dark rounded-1 px-2 py-1"
- [x]            data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="22b43522fc3ad2b5cfbc37ea87b8e635eaa1e3a4433a10e5754f55cdf1aef85d"
- [x]            data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">
- [x]            Sign&nbsp;up
- [x]          </a>
- [x]      </div>
- [x]    </div>
- [x]  </div>
+</header>
+
- [x]  </div>
+
- [x]  <div id="start-of-content" class="show-on-focus"></div>
+
+
- [x]    <div id="js-flash-container">
+
+</div>
+
+
+
- [x]  <div class="application-main " data-commit-hovercards-enabled>
- [x]        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
- [x]    <main  >
- [x]      
+
+
- [x]  
+
+
+
+
+
+
+
+
+
+
- [x]  <div class=" pagehead repohead readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
- [x]    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">
+
- [x]      <ul class="pagehead-actions">
+
+
+
+
- [x]  <li>
- [x]    
- [x]  <a class="tooltipped tooltipped-s btn btn-sm btn-with-count" aria-label="You must be signed in to watch a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;notification subscription menu watch&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="42ccfda9944dd00b5bf0051d53457bbcc6a93a1781d84f8a88aa57dad0297961" href="/login?return_to=%2Fjaraco%2Fgooglevoice">
- [x]    <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"_><_svg>
- [x]    Watch
+<_a>    <a class="social-count" href="_jaraco_googlevoice_watchers"
- [x]       aria-label="11 users are watching this repository">
- [x]      11
- [x]    </a>
+
- [x]  </li>
+
- [x]  <li>
- [x]        <a class="btn btn-sm btn-with-count tooltipped tooltipped-s" aria-label="You must be signed in to star a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;star button&quot;,&quot;repository_id&quot;:127651068,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="7c5a7e8b2e87b616485e491f89fb0311769734367e4dcd09addf01fea28bf0eb" href="/login?return_to=%2Fjaraco%2Fgooglevoice">
- [x]      <svg aria-label="star" height="16" class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" role="img"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"_><_svg>
+
- [x]      Star
+</a>
- [x]    <a class="social-count js-social-count" href="_jaraco_googlevoice/stargazers"
- [x]      aria-label="45 users starred this repository">
- [x]      45
- [x]    </a>
+
- [x]  </li>
+
- [x]  <li>
- [x]      <a class="btn btn-sm btn-with-count tooltipped tooltipped-s" aria-label="You must be signed in to fork a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;repo details fork button&quot;,&quot;repository_id&quot;:127651068,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="998da0fba8173e5afc58a40109d4e4d7535604781cbbb1f3de95a6df138e884a" href="/login?return_to=%2Fjaraco%2Fgooglevoice">
- [x]        <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"_><_svg>
- [x]        Fork
+</a>
- [x]    <a href="_jaraco_googlevoice_network_members" class="social-count"
- [x]       aria-label="95 users forked this repository">
- [x]      95
- [x]    </a>
- [x]  </li>
+</ul>
+
- [x]      <h1 class="public ">
- [x]    <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"_><_svg>
- [x]  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="_users_jaraco_hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="_jaraco">jaraco<_a><_span><!--
+--><span class="path-divider">_<_span><!--
+--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="_jaraco_googlevoice">googlevoice<_a><_strong>
- [x]  
+
- [x]    <span class="fork-flag" data-repository-hovercards-enabled>
- [x]      <span class="text">forked from <a data-hovercard-type="repository" data-hovercard-url="_pettazz_pygooglevoice_hovercard" href="_pettazz_pygooglevoice">pettazz_pygooglevoice<_a><_span>
- [x]    </span>
+</h1>
+
- [x]    </div>
- [x]    
+<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
- [x]     itemscope
- [x]     itemtype="http://schema.org/BreadcrumbList"
- [x]    aria-label="Repository"
- [x]     data-pjax="#js-repo-pjax-container">
+
- [x]  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages _jaraco_googlevoice" href="_jaraco_googlevoice">
- [x]      <div class="d-inline"><svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"_><_svg></div>
- [x]      <span itemprop="name">Code</span>
- [x]      <meta itemprop="position" content="1">
+<_a>  <_span>
+
- [x]    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones _jaraco_googlevoice_issues" href="_jaraco_googlevoice_issues">
- [x]        <div class="d-inline"><svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 011.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"_><_svg></div>
- [x]        <span itemprop="name">Issues</span>
- [x]        <span class="Counter">4</span>
- [x]        <meta itemprop="position" content="2">
+<_a>    <_span>
+
+
- [x]  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]    <a data-hotkey="g p" data-skip-pjax="true" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks _jaraco_googlevoice_pulls" href="_jaraco_googlevoice_pulls">
- [x]      <div class="d-inline"><svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0010 15a1.993 1.993 0 001-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v6.56A1.993 1.993 0 002 15a1.993 1.993 0 001-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"_><_svg></div>
- [x]      <span itemprop="name">Pull requests</span>
- [x]      <span class="Counter">0</span>
- [x]      <meta itemprop="position" content="4">
+<_a>  <_span>
+
+
- [x]    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project _jaraco_googlevoice_projects" href="_jaraco_googlevoice_projects">
- [x]      <div class="d-inline"><svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"_><_svg></div>
- [x]      Projects
- [x]      <span class="Counter" >0</span>
+</a>
+
+
- [x]    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning _jaraco_googlevoice_security_advisories" href="_jaraco_googlevoice_security_advisories">
- [x]      <div class="d-inline"><svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"_><_svg></div>
- [x]      Security
+</a>
- [x]    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people _jaraco_googlevoice_pulse" href="_jaraco_googlevoice_pulse">
- [x]      <div class="d-inline"><svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"_><_svg></div>
- [x]      Insights
+</a>
+
+</nav>
+
- [x]  <div class="reponav-wrapper reponav-small d-lg-none">
- [x]  <nav class="reponav js-reponav text-center no-wrap"
- [x]       itemscope
- [x]       itemtype="http://schema.org/BreadcrumbList">
+
- [x]    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages _jaraco_googlevoice" href="_jaraco_googlevoice">
- [x]        <span itemprop="name">Code</span>
- [x]        <meta itemprop="position" content="1">
+<_a>    <_span>
+
- [x]      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones _jaraco_googlevoice_issues" href="_jaraco_googlevoice_issues">
- [x]          <span itemprop="name">Issues</span>
- [x]          <span class="Counter">4</span>
- [x]          <meta itemprop="position" content="2">
+<_a>      <_span>
+
- [x]    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks _jaraco_googlevoice_pulls" href="_jaraco_googlevoice_pulls">
- [x]        <span itemprop="name">Pull requests</span>
- [x]        <span class="Counter">0</span>
- [x]        <meta itemprop="position" content="3">
+<_a>    <_span>
+
- [x]      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
- [x]        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project _jaraco_googlevoice_projects" href="_jaraco_googlevoice_projects">
- [x]          <span itemprop="name">Projects</span>
- [x]          <span class="Counter">0</span>
- [x]          <meta itemprop="position" content="4">
+<_a>      <_span>
+
+
- [x]      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning _jaraco_googlevoice_security_advisories" href="_jaraco_googlevoice_security_advisories">
- [x]        <span itemprop="name">Security</span>
- [x]        <meta itemprop="position" content="6">
+</a>
- [x]      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse _jaraco_googlevoice_pulse" href="_jaraco_googlevoice_pulse">
- [x]        Pulse
+</a>
+
- [x]  </nav>
+</div>
+
+
- [x]  </div>
+<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
- [x]  <div class="repository-content ">
+
- [x]    
- [x]    
+
+
- [x]  
+
+
- [x]    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="_jaraco_googlevoice_blob/49c20e5463c9ba7e9d1b5e47a7737b0bc8c203dc_.travis.yml">Permalink</a>
+
- [x]    <!-- blob contrib key: blob_contributors:v21:d58155a189fe591d0eb2cab1d405c52c -->
- [x]          <div class="signup-prompt-bg rounded-1">
- [x]      <div class="signup-prompt p-4 text-center mb-4 rounded-1">
- [x]        <div class="position-relative">
- [x]          <!-- '"` --><!-- <_textarea><_xmp> --><_option><_form><form action="_prompt_dismissals_signup" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" _><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="A8OWnUv39I8Hx+QB5waLkwNaiwC_iyshgUv6Lv3nCg7oFKH+PiJJ/j1Qcng0uECWopR8ugE0VFBvn2HwFnvsZw==" />
- [x]            <button type="submit" class="position-absolute top-0 right-0 btn-link link-gray" data-ga-click="(Logged out) Sign up prompt, clicked Dismiss, text:dismiss">
- [x]              Dismiss
- [x]            </button>
+<_form>          <h3 class="pt-2">Join GitHub today<_h3>
- [x]          <p class="col-6 mx-auto">GitHub is home to over 40 million developers working together to host and review code, manage projects, and build software together.</p>
- [x]          <a class="btn btn-primary" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;files signup prompt&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:null,&quot;originating_request_id&quot;:&quot;1CFA:40D29:1656D7D:21C3DC1:5E009A64&quot;,&quot;originating_url&quot;:&quot;https://github.com/jaraco/googlevoice/blob/master/.travis.yml&quot;,&quot;referrer&quot;:null,&quot;user_id&quot;:null}}" data-hydro-click-hmac="22bb4d0cd4098ba794b9c7d6ab41373f8d28ad483ae71d05ce70e850204732a4" data-ga-click="(Logged out) Sign up prompt, clicked Sign up, text:sign-up" href="_join?source=prompt-blob-show&amp;source_repo=jaraco%2Fgooglevoice">Sign up<_a>
- [x]        </div>
- [x]      </div>
- [x]    </div>
+
+
- [x]    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
- [x]      <span class="d-flex flex-justify-between width-full width-md-auto">
- [x]        
+<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
- [x]  <summary class="btn btn-sm select-menu-button css-truncate"
- [x]           data-hotkey="w"
- [x]           title="Switch branches or tags">
- [x]    <i>Branch:</i>
- [x]    <span class="css-truncate-target" data-menu-button>master</span>
- [x]  </summary>
+
- [x]  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="_jaraco_googlevoice_refs_master/.travis.yml?source_action=show&amp;source_controller=blob" preload>
- [x]    <include-fragment class="select-menu-loading-overlay anim-pulse">
- [x]      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"_><_svg>
- [x]    </include-fragment>
- [x]  </details-menu>
+</details>
+
- [x]        <div class="BtnGroup flex-shrink-0 d-md-none">
- [x]          <a href="_jaraco_googlevoice_find_master"
- [x]                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
- [x]                data-pjax
- [x]                data-hotkey="t">
- [x]            Find file
- [x]          </a>
- [x]          <clipboard-copy value=".travis.yml" class="btn btn-sm BtnGroup-item">
- [x]            Copy path
- [x]          </clipboard-copy>
- [x]        </div>
- [x]      </span>
- [x]      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
- [x]        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="_jaraco_googlevoice"><span>googlevoice<_span><_a><_span><_span><span class="separator">_<_span><strong class="final-path">.travis.yml</strong>
- [x]      </h2>
+
- [x]      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
- [x]        <a href="_jaraco_googlevoice_find_master"
- [x]              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
- [x]              data-pjax
- [x]              data-hotkey="t">
- [x]          Find file
- [x]        </a>
- [x]        <clipboard-copy value=".travis.yml" class="btn btn-sm BtnGroup-item">
- [x]          Copy path
- [x]        </clipboard-copy>
- [x]      </div>
- [x]    </div>
+
- [x]    
+
+
+
- [x]    
- [x]  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
- [x]      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
- [x]        <span class="pr-md-4 f6">
- [x]          <a rel="author" data-skip-pjax="true" href="_jaraco"><img class="avatar" skip_hovercard="13" src="https://avatars3.githubusercontent.com/u/308610?s=40&amp;v=4" width="20" height="20" alt="@jaraco" /><_a>
- [x]          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="author" href="_jaraco">jaraco<_a>
- [x]            <span class="lh-default v-align-middle">
- [x]              <a data-pjax="true" title="Install deployment password" class="link-gray" href="_jaraco_googlevoice_commit/61d4a2cc6735cff69711ddd308947197886fbff0">Install deployment password<_a>
- [x]            </span>
- [x]        </span>
- [x]        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
- [x]          <a class="pr-2 text-mono link-gray" href="_jaraco_googlevoice_commit/61d4a2cc6735cff69711ddd308947197886fbff0" data-pjax>61d4a2c<_a>
- [x]          <relative-time datetime="2018-08-17T14:13:08Z" class="no-wrap">Aug 17, 2018</relative-time>
- [x]        </span>
- [x]      </div>
+
- [x]    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
- [x]      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
- [x]        <summary class="btn-link">
- [x]          <span><strong>1<_strong> contributor<_span>
- [x]        </summary>
- [x]        <details-dialog
- [x]          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
- [x]          aria-label="Users who have contributed to this file"
- [x]          src="_jaraco_googlevoice_contributors-list_master/.travis.yml" preload>
- [x]          <div class="Box-header">
- [x]            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
- [x]              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"_><_svg>
- [x]            </button>
- [x]            <h3 class="Box-title">
- [x]              Users who have contributed to this file
- [x]            </h3>
- [x]          </div>
- [x]          <include-fragment class="octocat-spinner my-3" aria-label="Loading..."></include-fragment>
- [x]        </details-dialog>
- [x]      </details>
- [x]    </div>
- [x]  </div>
+
+
+
+
+
- [x]    <div class="Box mt-3 position-relative">
- [x]      
+<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
- [x]  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
+
- [x]      39 lines (34 sloc)
- [x]      <span class="file-info-divider"></span>
- [x]    1.31 KB
- [x]  </div>
+
- [x]  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">
+
- [x]    <div class="BtnGroup">
- [x]      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="_jaraco_googlevoice_raw_master_.travis.yml">Raw<_a>
- [x]        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="_jaraco_googlevoice_blame_master_.travis.yml">Blame<_a>
- [x]      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="_jaraco_googlevoice_commits_master_.travis.yml">History<_a>
- [x]    </div>
+
+
- [x]    <div>
+
- [x]          <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
- [x]            aria-label="You must be signed in to make or propose changes">
- [x]            <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 011.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"_><_svg>
- [x]          </button>
- [x]          <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
- [x]            aria-label="You must be signed in to make or propose changes">
- [x]            <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"_><_svg>
- [x]          </button>
- [x]    </div>
- [x]  </div>
+</div>
+
+
+
+
- [x]      
+
- [x]  <div itemprop="text" class="Box-body p-0 blob-wrapper data type-yaml ">
- [x]      
+<table class="highlight tab-size js-file-line-container" data-tab-size="8">
- [x]      <tr>
- [x]        <td id="L1" class="blob-num js-line-number" data-line-number="1"></td>
- [x]        <td id="LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">dist<_span>: <span class="pl-s">xenial<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L2" class="blob-num js-line-number" data-line-number="2"></td>
- [x]        <td id="LC2" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">sudo<_span>: <span class="pl-c1">false<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L3" class="blob-num js-line-number" data-line-number="3"></td>
- [x]        <td id="LC3" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">language<_span>: <span class="pl-s">python<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L4" class="blob-num js-line-number" data-line-number="4"></td>
- [x]        <td id="LC4" class="blob-code blob-code-inner js-file-line">
+</td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L5" class="blob-num js-line-number" data-line-number="5"></td>
- [x]        <td id="LC5" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">python<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L6" class="blob-num js-line-number" data-line-number="6"></td>
- [x]        <td id="LC6" class="blob-code blob-code-inner js-file-line">- <span class="pl-c1">2.7<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L7" class="blob-num js-line-number" data-line-number="7"></td>
- [x]        <td id="LC7" class="blob-code blob-code-inner js-file-line">- <span class="pl-c1">3.6<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L8" class="blob-num js-line-number" data-line-number="8"></td>
- [x]        <td id="LC8" class="blob-code blob-code-inner js-file-line"><span class="pl-s">- &amp;latest_py3 3.7<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L9" class="blob-num js-line-number" data-line-number="9"></td>
- [x]        <td id="LC9" class="blob-code blob-code-inner js-file-line">
+</td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L10" class="blob-num js-line-number" data-line-number="10"></td>
- [x]        <td id="LC10" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">jobs<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L11" class="blob-num js-line-number" data-line-number="11"></td>
- [x]        <td id="LC11" class="blob-code blob-code-inner js-file-line">  <span class="pl-ent">fast_finish<_span>: <span class="pl-c1">true<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L12" class="blob-num js-line-number" data-line-number="12"></td>
- [x]        <td id="LC12" class="blob-code blob-code-inner js-file-line">  <span class="pl-ent">include<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L13" class="blob-num js-line-number" data-line-number="13"></td>
- [x]        <td id="LC13" class="blob-code blob-code-inner js-file-line">  - <span class="pl-ent">stage<_span>: <span class="pl-s">deploy<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L14" class="blob-num js-line-number" data-line-number="14"></td>
- [x]        <td id="LC14" class="blob-code blob-code-inner js-file-line">    <span class="pl-ent">if<_span>: <span class="pl-s">tag IS present<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L15" class="blob-num js-line-number" data-line-number="15"></td>
- [x]        <td id="LC15" class="blob-code blob-code-inner js-file-line">    <span class="pl-ent">python<_span>: <span class="pl-s">*latest_py3<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L16" class="blob-num js-line-number" data-line-number="16"></td>
- [x]        <td id="LC16" class="blob-code blob-code-inner js-file-line">    <span class="pl-ent">install<_span>: <span class="pl-s">skip<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L17" class="blob-num js-line-number" data-line-number="17"></td>
- [x]        <td id="LC17" class="blob-code blob-code-inner js-file-line">    <span class="pl-ent">script<_span>: <span class="pl-s">skip<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L18" class="blob-num js-line-number" data-line-number="18"></td>
- [x]        <td id="LC18" class="blob-code blob-code-inner js-file-line">    <span class="pl-ent">deploy<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L19" class="blob-num js-line-number" data-line-number="19"></td>
- [x]        <td id="LC19" class="blob-code blob-code-inner js-file-line">      <span class="pl-ent">provider<_span>: <span class="pl-s">pypi<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L20" class="blob-num js-line-number" data-line-number="20"></td>
- [x]        <td id="LC20" class="blob-code blob-code-inner js-file-line">      <span class="pl-ent">on<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L21" class="blob-num js-line-number" data-line-number="21"></td>
- [x]        <td id="LC21" class="blob-code blob-code-inner js-file-line">        <span class="pl-ent">tags<_span>: <span class="pl-c1">true<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L22" class="blob-num js-line-number" data-line-number="22"></td>
- [x]        <td id="LC22" class="blob-code blob-code-inner js-file-line">        <span class="pl-ent">all_branches<_span>: <span class="pl-c1">true<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L23" class="blob-num js-line-number" data-line-number="23"></td>
- [x]        <td id="LC23" class="blob-code blob-code-inner js-file-line">      <span class="pl-ent">user<_span>: <span class="pl-s">jaraco<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L24" class="blob-num js-line-number" data-line-number="24"></td>
- [x]        <td id="LC24" class="blob-code blob-code-inner js-file-line">      <span class="pl-ent">password<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L25" class="blob-num js-line-number" data-line-number="25"></td>
- [x]        <td id="LC25" class="blob-code blob-code-inner js-file-line">        <span class="pl-ent">secure<_span>: <span class="pl-s">EVOgggLHfPvfJaVyBISGePd7YJWT29tky5ZzLbHvvppBZXXcx0SDyv1HN0FoDAtJvWMUgUJN5lAGnjKMuCNIzByl6IHX6jpkByMIpInsoME1VWK845L5DhdjWF5Pi4gbgNxXh46sNT7w23r9tMgopDiN3PydsK621ba3OQ8RCjEnv2S6WOzEKYUeC4aUt5CKRvAi+Ax+paY8VjcknIXdkDyXW3H5f6jN0Ldg84W_MPhgANVp_b1MiAGe2R4D3Pt1nPE4jsTlYcwwdWT3eA0EFqj+scUnVGM189LJmBdzHz089AQyBGNvAcZwdKb+Vopyq43qUmk1Oq_KtELkTnW0cyZTkntAfIaJLR9mSUh+Icfo8HrYOLpa+TolfGIMt_3uGjbiLnjdgBucQx9ReTBgMUtknSzsBxE1DSsrW5GEm0UlMTPZmmK_vKEENn5dKJ74+y1wB5Qxm7qaseJAaiagcxaRhi+iKKkTLFvF5TpP+cIiASWaRS_E3Oh_v7CqKhlg4meAfNZekvrMnqzmIKjBM43slt+DaZ_8TMGIbXF2gR25JQfT02SQuWRSJCKo4eRNmewsGTJwp6SKE77UsGWYVXpP13dBi8g4xjNeOMyqsoTFvamuKWNZt8Xo89vSmdWj6ryyPlDLE2H+vVqPWxhzjwABOQ49tGDKEfcMaOT10rA=<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L26" class="blob-num js-line-number" data-line-number="26"></td>
- [x]        <td id="LC26" class="blob-code blob-code-inner js-file-line">      <span class="pl-ent">distributions<_span>: <span class="pl-s">dists<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L27" class="blob-num js-line-number" data-line-number="27"></td>
- [x]        <td id="LC27" class="blob-code blob-code-inner js-file-line">      <span class="pl-ent">skip_cleanup<_span>: <span class="pl-c1">true<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L28" class="blob-num js-line-number" data-line-number="28"></td>
- [x]        <td id="LC28" class="blob-code blob-code-inner js-file-line">
+</td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L29" class="blob-num js-line-number" data-line-number="29"></td>
- [x]        <td id="LC29" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">cache<_span>: <span class="pl-s">pip<_span></td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L30" class="blob-num js-line-number" data-line-number="30"></td>
- [x]        <td id="LC30" class="blob-code blob-code-inner js-file-line">
+</td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L31" class="blob-num js-line-number" data-line-number="31"></td>
- [x]        <td id="LC31" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">install<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L32" class="blob-num js-line-number" data-line-number="32"></td>
- [x]        <td id="LC32" class="blob-code blob-code-inner js-file-line">- <span class="pl-s">pip install tox tox-venv<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L33" class="blob-num js-line-number" data-line-number="33"></td>
- [x]        <td id="LC33" class="blob-code blob-code-inner js-file-line">
+</td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L34" class="blob-num js-line-number" data-line-number="34"></td>
- [x]        <td id="LC34" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">before_script<_span>:<_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L35" class="blob-num js-line-number" data-line-number="35"></td>
- [x]        <td id="LC35" class="blob-code blob-code-inner js-file-line">  <span class="pl-c"><span class="pl-c">#</span> Disable IPv6. Ref travis-ci/travis-ci#8361<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L36" class="blob-num js-line-number" data-line-number="36"></td>
- [x]        <td id="LC36" class="blob-code blob-code-inner js-file-line">  - <span class="pl-s">if [ &quot;${TRAVIS_OS_NAME}&quot; == &quot;linux&quot; ]; then<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L37" class="blob-num js-line-number" data-line-number="37"></td>
- [x]        <td id="LC37" class="blob-code blob-code-inner js-file-line">      <span class="pl-s">sudo sh -c &#39;echo 0 &gt; /proc/sys/net/ipv6/conf/all/disable_ipv6&#39;;<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L38" class="blob-num js-line-number" data-line-number="38"></td>
- [x]        <td id="LC38" class="blob-code blob-code-inner js-file-line">    <span class="pl-s">fi<_span><_td>
- [x]      </tr>
- [x]      <tr>
- [x]        <td id="L39" class="blob-num js-line-number" data-line-number="39"></td>
- [x]        <td id="LC39" class="blob-code blob-code-inner js-file-line"><span class="pl-ent">script<_span>: <span class="pl-s">tox<_span></td>
- [x]      </tr>
+</table>
+
- [x]  <details class="details-reset details-overlay BlobToolbar position-absolute js-file-line-actions dropdown d-none" aria-hidden="true">
- [x]    <summary class="btn-octicon ml-0 px-2 p-0 bg-white border border-gray-dark rounded-1" aria-label="Inline file action toolbar">
- [x]      <svg class="octicon octicon-kebab-horizontal" viewBox="0 0 13 16" version="1.1" width="13" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.5 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm5 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3zM13 7.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0z"_><_svg>
- [x]    </summary>
- [x]    <details-menu>
- [x]      <ul class="BlobToolbar-dropdown dropdown-menu dropdown-menu-se mt-2" style="width:185px">
- [x]        <li>
- [x]          <clipboard-copy role="menuitem" class="dropdown-item" id="js-copy-lines" style="cursor:pointer;">
- [x]            Copy lines
- [x]          </clipboard-copy>
- [x]        </li>
- [x]        <li>
- [x]          <clipboard-copy role="menuitem" class="dropdown-item" id="js-copy-permalink" style="cursor:pointer;">
- [x]            Copy permalink
- [x]          </clipboard-copy>
- [x]        </li>
- [x]        <li><a class="dropdown-item js-update-url-with-hash" id="js-view-git-blame" role="menuitem" href="_jaraco_googlevoice_blame/49c20e5463c9ba7e9d1b5e47a7737b0bc8c203dc_.travis.yml">View git blame<_a><_li>
- [x]          <li><a class="dropdown-item" id="js-new-issue" role="menuitem" href="_jaraco_googlevoice_issues_new">Reference in new issue<_a><_li>
- [x]      </ul>
- [x]    </details-menu>
- [x]  </details>
+
- [x]  </div>
+
- [x]    </div>
+
- [x]  
+
- [x]  <details class="details-reset details-overlay details-overlay-dark">
- [x]    <summary data-hotkey="l" aria-label="Jump to line"></summary>
- [x]    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
- [x]      <!-- '"` --><!-- <_textarea><_xmp> --><_option><_form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
- [x]        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
- [x]        <button type="submit" class="btn" data-close-dialog>Go</button>
+<_form>    <_details-dialog>
- [x]  </details>
+
+
+
- [x]  </div>
+</div>
+
- [x]    </main>
- [x]  </div>
- [x]  
+
- [x]  </div>
+
- [x]        
+<div class="footer container-lg width-full p-responsive" role="contentinfo">
- [x]  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
- [x]    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
- [x]      <li class="mr-3 mr-lg-0">&copy; 2019 GitHub, Inc.</li>
- [x]        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms<_a><_li>
- [x]        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy<_a><_li>
- [x]        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security<_a><_li>
- [x]        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status<_a><_li>
- [x]        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help<_a><_li>
- [x]    </ul>
+
- [x]    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
- [x]      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"_><_svg>
+</a>
- [x]   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
- [x]        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub<_a><_li>
- [x]        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing<_a><_li>
- [x]      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API<_a><_li>
- [x]      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training<_a><_li>
- [x]        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog<_a><_li>
- [x]        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About<_a><_li>
+
- [x]    </ul>
- [x]  </div>
- [x]  <div class="d-flex flex-justify-center pb-6">
- [x]    <span class="f6 text-gray-light"></span>
- [x]  </div>
+</div>
+
+
+
- [x]  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
- [x]    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"_><_svg>
- [x]    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
- [x]      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"_><_svg>
- [x]    </button>
- [x]    You can’t perform that action at this time.
- [x]  </div>
+
+
- [x]    
- [x]    <script crossorigin="anonymous" integrity="sha512-_VSJJF96vCzSgC6y09Z4FqzjjuXRWOKIq2twF0Nb5_v8xy4qzngnH6Au6TFwbmNN_lborYJsojEpgIbYjoGvHQ==" type="application_javascript" src="https://github.githubassets.com/assets/frameworks-fd548924.js"></script>
- [x]    
- [x]    <script crossorigin="anonymous" async="async" integrity="sha512-0mcBYsTTDNy016WuG7Zu_Pb5dsdoVzVb5FlxH4btAPKKyTBKn+5g6N6lXxmMo1WokYH8uOYuLpTgLjU29jSqcA==" type="application_javascript" src="https://github.githubassets.com/assets/github-bootstrap-d2670162.js"></script>
- [x]    
- [x]    
- [x]    
- [x]  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
- [x]    >
- [x]    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"_><_svg>
- [x]    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload<_a> to refresh your session.<_span>
- [x]    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload<_a> to refresh your session.<_span>
- [x]  </div>
- [x]  <template id="site-details-dialog">
- [x]  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
- [x]    <summary role="button" aria-label="Close dialog"></summary>
- [x]    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
- [x]      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
- [x]        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"_><_svg>
- [x]      </button>
- [x]      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
- [x]    </details-dialog>
- [x]  </details>
+</template>
+
- [x]  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
- [x]  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
- [x]  </div>
+</div>
+
- [x]  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>
+
- [x]  </body>
+</html>
+
--
Working Copy 3.9.9



## Maintained by: [the Docker Community](https://github.com/docker-library/php)
This is the Git repo of the [Docker "Official Image"](https://github.com/docker-library/official-images#what-are-official-images) for [`php`](https://hub.docker.com/_/php/) (not to be confused with any official `php` image provided by `php` upstream). See [the Docker Hub page](https://hub.docker.com/_/php/) for the full readme on how to use this Docker image and for information regarding contributing and issues.

The [full image description on Docker Hub](https://hub.docker.com/_/php/) is generated/maintained over in [the docker-library/docs repository](https://github.com/docker-library/docs), specifically in [the `php` directory](https://github.com/docker-library/docs/tree/master/php).

## See a change merged here that doesn't show up on Docker Hub yet?
For more information about the full official images change lifecycle, see [the "An image's source changed in Git, now what?" FAQ entry](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

For outstanding `php` image PRs, check [PRs with the "library/php" label on the official-images repository](https://github.com/docker-library/official-images/labels/library%2Fphp). For the current "source of truth" for [`php`](https://hub.docker.com/_/php/), see [the `library/php` file in the official-images repository](https://github.com/docker-library/official-images/blob/master/library/php).

- - - -
* [build status badge](https://travis-ci.org/docker-library/php/branches)
* [build status badge](https://doi-janky.infosiftr.net/job/update.sh/job/php)

| Build | Status | Badges | (per-arch) |
|:-:|:-:|:-:|:-:|
| [amd64 build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/php) | [arm32v5 build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/php) | [arm32v6 build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v6/job/php) | [arm32v7 build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/php) |
| [arm64v8 build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/php) | [i386 build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/i386/job/php) | [ppc64le build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/php) | [s390x build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/s390x/job/php) |
| [put-shared build status badge](https://doi-janky.infosiftr.net/job/put-shared/job/heavy) |
https://www.apache.org/dev/
https://api.darksky.net/forecast/eda7a7dd775843a3d3fbd0324ea9c597/37.8267,-122.4233
<a href='293475617.html'>293475617.html</a>
Bryggan
Frekvensband: 2 400–2 483,5 MHz

Bryggan
Diameter
88 mm
Frekvensband
2400-2483.5 MHz
Höjd
26 mm
Längd x bredd
90.9 x 90.6 mm
Max. antal tillbehör
10
Max. antal lampor
50
Monteringsalternativ
Stationär dator
Vägg
Nätadapter
100–240 V AC / 50–60Hz
Utspänning: 5 V DC 600mA
Vilolägeseffekt: max 0,1 W
Strömförbrukning
250mA max
Signify's second quarter results 2019
