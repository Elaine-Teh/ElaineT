# CNSHA Rate Tier Analysis

上海 (CNSHA) 运价层级分析报告

## 📊 报告文件

- **CNSHA_Rate_Tier_Report_v2.html** - 交互式管理报告（HTML）
- **CNSHA_Booking_Breakdown.xlsx** - Booking 明细分析（Excel）

## 📈 分析内容

### Vessel
- **TGLK2610W**

### 运价层级分类 (Rate Tier)

| Tier | 说明 | 状态 |
|------|------|------|
| FAK | 最佳运价 | 🟢 Best |
| T2 | 可接受范围 | 🟡 Acceptable |
| T1 | 目标运价 | 🔵 Target |
| Spot | 低于目标 | 🔴 Below Target |

### 数据摘要

- **Total TEUs**: 393
- **20' Container**: 53 TEUs
- **40' Container**: 170 FEUs (340 TEUs)

### Tier 分布

| Tier | TEUs | 占比 |
|------|------|------|
| FAK | 11 | 2.8% |
| T1 | 4 | 1.0% |
| T2 | 66 | 16.8% |
| Spot | 312 | 79.4% |

## 📐 Rate Tier 阈值定义

### 20' Container (USD/TEU)

| POD | FAK | T2 | T1 | Spot |
|-----|-----|-----|-----|------|
| SAJED/EGSOK | >$3,000 | $2,601-$2,999 | $2,600 | <$2,600 |
| DJIJB | >$3,100 | $2,701-$3,099 | $2,700 | <$2,700 |
| JOAQJ | >$3,200 | $2,801-$3,199 | $2,800 | <$2,800 |
| YEADE/SDPZU | >$4,000 | $3,601-$3,999 | $3,600 | <$3,600 |

### 40' Container (USD/FEU)

| POD | FAK | T2 | T1 | Spot |
|-----|-----|-----|-----|------|
| SAJED/EGSOK | >$4,000 | $3,601-$3,999 | $3,600 | <$3,600 |
| DJIJB | >$4,200 | $3,801-$4,199 | $3,800 | <$3,800 |
| JOAQJ | >$4,400 | $4,001-$4,399 | $4,000 | <$4,000 |
| YEADE/SDPZU | >$5,200 | $4,801-$4,999 | $4,800 | <$4,800 |

---
*Generated: 14 April 2026*
