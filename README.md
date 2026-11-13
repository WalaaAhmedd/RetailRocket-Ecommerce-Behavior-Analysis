# RetailRocket E-commerce Behavior Analysis

## Project Overview
An end-to-end e-commerce behavior analysis project using Python and the RetailRocket dataset. The project explores user interactions, session activity, purchasing behavior, conversion funnels, and user retention patterns.

## Dataset Overview
- **Total Events:** 2,756,101
- **Unique Visitors:** 1,407,580
- **Identified Sessions:** 1,761,675
- **Date Range:** May 3 – September 18, 2015

## Analysis Performed
- Data exploration and preprocessing.
- Event distribution analysis.
- Session identification using a 30-minute inactivity threshold.
- Session-based conversion funnel analysis.
- User activity and retention analysis.
- Cohort analysis based on first observed activity.

## Key Findings

### Event Distribution
| Event Type | Count |
|---|---:|
| View | 2,664,312 |
| Add to Cart | 69,332 |
| Transaction | 22,457 |

### Session-Based Funnel
| Funnel Stage | Sessions |
|---|---:|
| Sessions with Product Views | 1,755,781 |
| Sessions with Add-to-Cart after View | 36,675 |
| Sessions with Transaction after Add-to-Cart | 10,721 |

**Conversion Rates:**
- View to Cart: 2.09%
- Cart to Purchase: 29.23%
- View to Purchase: 0.61%

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Structure
```text
RetailRocket-Ecommerce-Behavior-Analysis/
├── data/
│   ├── category_tree.csv
│   ├── events.csv
│   ├── item_properties_part1.csv
│   └── item_properties_part2.csv
├── notebooks/
│   └── retailrocket_ecommerce_behavior_analysis.ipynb
└── README.md
```

## Notes & Limitations
- The dataset covers historical activity from 2015.
- Sessions are identified using a 30-minute inactivity rule.
- Cohorts are based on the first observed activity, not actual registration dates.
- Retention metrics represent observed repeat activity and should not be interpreted as signup-based D1/D7 retention.

