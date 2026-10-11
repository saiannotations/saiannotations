<!--
  Sai Pavan Vanka · GitHub profile README
  Setup: upload this README.md and the assets/ folder to the repo named exactly like your username.
  Then replace PORTFOLIO_LINK, LINKEDIN_LINK and YOUR-USERNAME.
-->

<p align="center">
  <img src="assets/header.svg" alt="Sai Pavan Vanka, Data Annotation Specialist, Dallas TX" width="100%">
</p>

<p align="center">
  <a href="PORTFOLIO_LINK"><img src="https://img.shields.io/badge/▶_Portfolio-watch_labels_in_motion-ff5c93?style=for-the-badge&labelColor=0f1218" alt="Portfolio"></a>
  <a href="https://github.com/YOUR-USERNAME/data-annotation-samples"><img src="https://img.shields.io/badge/Dataset-data--annotation--samples-e8ebf1?style=for-the-badge&logo=github&logoColor=white&labelColor=0f1218&color=272d3a" alt="Samples repository"></a>
  <a href="LINKEDIN_LINK"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0f1218" alt="LinkedIn"></a>
  <a href="mailto:saivanka1999@gmail.com"><img src="https://img.shields.io/badge/Email-saivanka1999%40gmail.com-3ddc84?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0f1218" alt="Email"></a>
</p>

<br>

```json
{
  "id": 1,
  "class": "data_annotation_specialist",
  "name": "Sai Pavan Vanka",
  "location": "Dallas, TX",
  "attributes": {
    "data": ["images", "video", "text", "llm_outputs"],
    "focus": "labels a model can actually learn from",
    "works_in": ["your guideline", "your tool", "your export format"],
    "timezone": "US Central",
    "open_to": ["annotation projects", "QA review", "LLM evaluation"]
  },
  "occluded": false,
  "truncated": false
}
```

Hi, I'm **Sai**. I label image, video and text data for machine learning teams: tight boxes, stable track IDs, clean masks, and text labels that match what people mean. Every judgment call I make goes into an edge-case log, so your guideline gets better with each batch.

<br>

## `label_set` · what I annotate

<p align="center">
  <img src="assets/label-set.svg" alt="Label set: bbox_detection, video_tracking, polygon_segmentation, keypoints_pose, named_entities, text_classification, llm_evaluation" width="100%">
</p>

<br>

## `qa_review` · problems I solve

<p align="center">
  <img src="assets/before-after.svg" alt="Before and after: IoU 0.56 to 0.97, ID switches 2 to 0, building mask 14,320 to 9,600 px²" width="100%">
</p>

<table>
  <tr>
    <th align="left">Problem</th>
    <th align="left">How I solve it</th>
    <th align="left">Result in my samples</th>
  </tr>
  <tr>
    <td>Loose boxes teach the model the wrong size</td>
    <td>Snap each side to the outermost visible pixel; check against a reference in QA</td>
    <td><b>IoU 0.56 → 0.97</b></td>
  </tr>
  <tr>
    <td>IDs swap when people cross paths</td>
    <td>Scrub every crossing; follow clothing and direction; one ID per object</td>
    <td><b>ID switches 2 → 0</b></td>
  </tr>
  <tr>
    <td>Building masks bleed into shadows</td>
    <td>Trace the roof edge using the sun direction, never the shadow line</td>
    <td><b>Mask 14,320 → 9,600 px²</b></td>
  </tr>
  <tr>
    <td>Sarcasm labeled as positive</td>
    <td>Label meaning, not keywords; write a reason for every ambiguous item</td>
    <td><b>Label matches intent</b></td>
  </tr>
</table>

<br>

## `pipeline` · how I work on every batch

<p align="center">
  <img src="assets/pipeline.svg" alt="Pipeline: read guideline, calibrate, label, self-QA, log edge cases" width="100%">
</p>

<br>

## `dataset` · featured work

<p align="center">
  <img src="assets/qa-report.svg" alt="QA report: four annotation exports pass validation" width="100%">
</p>

My **[data-annotation-samples](https://github.com/YOUR-USERNAME/data-annotation-samples)** repository holds the real export files behind my portfolio, plus the Python QA script that checks them before delivery.

```text
data-annotation-samples/
├── image/
│   ├── street_cam04_tracking/        300 frames · 7 tracks · MOT + YOLO
│   ├── aerial_tile_33_18_segmentation/   water · road · building · vegetation (COCO)
│   └── pose_jumping_jacks/           17 keypoints per frame (COCO)
├── text/
│   ├── ner/                          PERSON · ORG · LOC · DATE · MONEY spans
│   ├── classification/               intent + sentiment with annotator notes
│   └── llm_evaluation/               preference pair · 4-axis rubric · rationale
├── guidelines/                       labeling rules + edge-case log
└── scripts/validate_annotations.py   QA checks run before every delivery
```

<br>

## `tools` · what I work in

<p>
  <img src="https://img.shields.io/badge/Label_Studio-0f1218?style=for-the-badge&logoColor=white" alt="Label Studio">
  <img src="https://img.shields.io/badge/CVAT-0f1218?style=for-the-badge" alt="CVAT">
  <img src="https://img.shields.io/badge/Labelbox-0f1218?style=for-the-badge" alt="Labelbox">
  <img src="https://img.shields.io/badge/Roboflow-0f1218?style=for-the-badge&logo=roboflow&logoColor=white" alt="Roboflow">
  <img src="https://img.shields.io/badge/Python-0f1218?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Google_Sheets-0f1218?style=for-the-badge&logo=googlesheets&logoColor=white" alt="Google Sheets">
</p>
<p>
  <img src="https://img.shields.io/badge/COCO-272d3a?style=flat-square" alt="COCO">
  <img src="https://img.shields.io/badge/YOLO-272d3a?style=flat-square" alt="YOLO">
  <img src="https://img.shields.io/badge/MOT-272d3a?style=flat-square" alt="MOT">
  <img src="https://img.shields.io/badge/Pascal_VOC-272d3a?style=flat-square" alt="Pascal VOC">
  <img src="https://img.shields.io/badge/JSONL-272d3a?style=flat-square" alt="JSONL">
  <img src="https://img.shields.io/badge/spaCy-272d3a?style=flat-square" alt="spaCy">
  <img src="https://img.shields.io/badge/CSV-272d3a?style=flat-square" alt="CSV">
</p>

<br>

## `contact` · let's label something

Send me a small sample of your data and your guideline. I'll label a **pilot batch** and return it with an edge-case log, so you can judge the quality before you commit.

<p align="center">
  <img src="assets/footer.svg" alt="Contact: saivanka1999@gmail.com, Dallas TX" width="100%">
</p>
