# Data Dictionary: NPWT vs CWT RCT Dataset

| Variable                  | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Serial                   | De-identified patient serial number                                         |
| Age                      | Age category (Adult, Elderly)                                               |
| Age years                | Numerical age                                                               |
| Age Groups               | Age binned by decades                                                       |
| Gender                   | Male / Female                                                               |
| DM                       | Diabetes mellitus status (Yes/No)                                           |
| Smoking                  | Current smoking status (Yes/No)                                             |
| BMI                      | BMI category (Underweight, Normal, Overweight, Obese)                       |
| Wound_Infection          | Baseline wound infection (Yes/No)                                           |
| Treatment Arm            | Assigned treatment: NPWT or Conventional Dressing                           |
| PreTreatArea             | Wound area at baseline (cm²)                                                |
| MidTreatArea             | Wound area at Day 5                                                         |
| PostTreatArea            | Wound area at Day 10                                                        |
| Day 1 to Day 5 GAR       | Granulation area reduction over days 1–5                                    |
| Day 5 to Day 10 GAR      | Granulation area reduction over days 5–10                                   |
| GAR                      | Overall granulation area reduction                                          |
| Day 5 PAR (%)            | Percentage area reduction by Day 5                                          |
| Day 10 PAR (%)           | Percentage area reduction by Day 10                                         |
| PAR (%)                  | Total % area reduction over 10 days                                         |
| VAS                      | Visual Analog Scale score for pain (0–10)                                   |
| Other SSC                | Other surgical site complications (Yes/No)                                  |

### Notes:
- Wound area was measured using ImageJ digital planimetry
- Pain scores assessed using standard 10-point VAS
- Dataset includes variables used in WHIPS and TRI exploratory models
