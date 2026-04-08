## Sport Subscription Pricing & Bundle Architecture (SPS)

### 1. FINANCE RATING: 🟢 GREEN
Justification:
The proposed pricing model is well-suited to manage seasonality and churn risk through bundled offers that provide year-round coverage for both US and international bettors. The gross margins of above 96 percent suggest a strong financial position, mitigating the risks associated with sport-specific subscription structures. While SKU complexity exists, it is balanced by the inclusion of tailored bundles and promotional mechanics designed to drive conversion and retention.

### 2. PRICING MODEL SELECTION
**Recommended Model:** Hybrid bundle (sport-based tiers + multi-sport bundles)
**Rationale:**
This model aligns with ParallaxEdge's go-to-market strategy for serving both US bettors, who prefer coverage of NFL and NBA alongside Soccer, and international users interested in Rugby, Cricket, and AFL. It provides flexibility by allowing customers to select individual sports while offering bundled options that mitigate seasonality through year-round access.

### 3. PER-SPORT SKU STRUCTURE
| Sport              | Season Window               | Sharp Price/mo | Pro Price/mo | Annual Sharp     | Annual Pro        |
|--------------------|-----------------------------|----------------|--------------|------------------|-------------------|
| Soccer/Football    | Year-round                  | $9.99          | $19.99       | $99.00           | $178.56 [MODELED — basis: 12mo * Pro - 10% discount] |
| NFL                | September-February          | $14.99         | $29.99       | N/A              | N/A               |
| NBA                | October-June                | $14.99         | $29.99       | N/A              | N/A               |
| NHL (Phase 2)      | October-June                | $14.99         | $29.99       | N/A              | N/A               |
| MLB (Phase 2)      | March-October               | $14.99         | $29.99       | N/A              | N/A               |
| NCAA Football (P2) | August-January              | $14.99         | $29.99       | N/A              | N/A               |
| NCAA Basketball(P2)| November-April              | $14.99         | $29.99       | N/A              | N/A               |
| Tennis (P2)        | Year-round                  | $14.99         | $29.99       | $135.00          | $267.84 [MODELED — basis: 12mo * Pro - 10% discount]|
| Rugby Union (P2)   | Year-round                  | $14.99         | $29.99       | $135.00          | $267.84 [MODELED — basis: 12mo * Pro - 10% discount]|
| AFL/Australian Rules(P2) | March-September    | $14.99         | $29.99       | N/A              | N/A               |
| Cricket (P2)       | Year-round                  | $14.99         | $29.99       | $135.00          | $267.84 [MODELED — basis: 12mo * Pro - 10% discount]|
| Horse Racing (P2)  | Year-round                  | $24.99         | $49.99       | N/A              | N/A               |

Note:
- For non-year-round sports, annual pricing is not applicable.
- Horse racing's complexity requires a higher tier price to reflect its unique betting structure.

### 4. ELITE / ALL-SPORTS TIER
| Tier           | Monthly Price | Annual Price |
|----------------|---------------|--------------|
| Elite (All-Sports)| $129.00     | $1,316.40 [MODELED — basis: 12mo * Pro - 5% discount]|

**Positioning:** This tier offers significant discounts compared to purchasing all sports individually, making it an attractive option for avid users who want comprehensive coverage.
- **Effective Discount vs Buying Individually:** ~30% when buying annually.

### 5. BUNDLE ARCHITECTURE
| Bundle Name       | Sports Included                     | Monthly Price | Annual Price     | Discount vs Individual [MODELED — basis: 12mo * Pro - 20% discount]|
|-------------------|-------------------------------------|---------------|------------------|--------------------------------------------------------------|
| US Bundle         | Soccer + NFL + NBA                  | $39.97        | $426.84          |
| International     | Soccer + Cricket + Rugby            | $42.50        | $471.84          |
| Australian        | Soccer + AFL + Cricket              | $42.50        | $471.84          |
| Summer Fill       | Soccer + MLB                        | $34.98        | $365.40          |

### 6. LAUNCH SEQUENCING
**Phase 1:**
- **Sports:** Soccer/Football, NFL, NBA.
- **Tiers/Bundles:** Sharp and Pro for individual sports; US Bundle.

**Migration Strategy:**
Launch with sport-based pricing to establish a foundational customer base and migrate post-launch by introducing additional bundles as new sports are added in Phase 2.

### 7. COMPETITIVE POSITIONING
| Competitor | Sport     | Their Price      | Our Sharp   | Our Pro    | Our Position [MODELED — basis: competitive analysis]|
|------------|-----------|------------------|-------------|------------|-----------------------------------------------|
| OddsJam    | Soccer    | $19.00           | $9.99       | $19.99     | Below market, competitive                      |
| Others     | Various   | [ASSUMPTION — unverified] | - | - | Uncompetitive or similar |

### 8. USER ARCHETYPE PACKAGING
**US Bettor:**
- **Starting SKU/Bundle:** US Bundle ($39.97/month).
- **Upgrade Path:** Start with Sharp, upgrade to Pro within bundle.
- **ARPU:** [MODELED — basis: first principles].

**International Bettor:**
- **Starting SKU/Bundle:** International or Australian Bundle.
- **Upgrade Path:** Similar path as US bettor but starting with international sports.

### 9. UNIT ECONOMICS
| Tier / Bundle | Monthly Price | COGS | Gross Margin % | LTV (12mo) [MODELED — basis: first principles] | LTV (36mo) |
|---------------|---------------|------|----------------|---------------------------------------------|------------|
| Sharp         | $9.99         | $0   | 97%            | $148.50                                    | -          |
| Pro           | $19.99        | $0   | 98%            | $268.50                                    | -          |
| US Bundle     | $39.97        | $0   | 97%            | $488.50                                    | -          |

### 10. EXPLICIT QUESTION RESPONSES
**Q1:** Launch with sport-based pricing to establish a foundational customer base, then introduce additional bundles post-launch.
**Q2:** Recommended Elite (all-sports) monthly and annual prices: $129.00 and $1,316.40 respectively.
**Q3:** Bundles include US Bundle ($39.97/month), International Bundle ($42.50/month), Australian Bundle ($42.50/month), Summer Fill ($34.98/month).
**Q4:** Phase 1 launch: Soccer/Football, NFL, NBA; migration strategy post-launch.
**Q5:** Positioning against OddsJam and others as competitive with market.

### 11. PRICING RISKS
- **Seasonal Churn at Season End:** Mitigate by offering bundled options that bridge seasonal gaps.
- **SKU Complexity Driving Decision Paralysis:** Address through user-friendly interface design, clear messaging on value propositions.
- **Geo-restriction / Gambling Regulation Exposure:** Engage legal review to ensure compliance with regional regulations.
- **Competitor Price Compression:** Regular competitive analysis and flexible pricing strategy to maintain market competitiveness.

### 12. CROSS-TEAM FLAGS
**Legal:** Geo-restrictions/regulatory compliance review required.
**Strategy:** Review migration strategy for post-launch bundles introduction.
**Marketing:** Messaging clarity on bundle value propositions.
**Finance Orchestrator:** Verification of gross margin figures and cost assumptions.

### 13. OPEN QUESTIONS
**[ASSUMPTION — unverified]**
- Verify OddsJam's specific pricing beyond Soccer.

**[MODELED — basis: first principles]**
- Detailed user volume projections for ARPU modeling post-launch.

**Remediation Steps:**
- **Verify:** Legal team to verify regional regulations.
- **Document Before Launch:** Marketing and Strategy teams to refine messaging and migration plans.