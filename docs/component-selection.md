# Component Selection

**Team 101: Automatic Pet Food Dispenser**

**Subsystem:** Weight/Height Sensor  
**Student:** Connor

## 1. Load Cell Sensor

### Candidate 1: SparkFun TAL220B, 5kg

**Price:** $15.50

[Product information and datasheet](https://www.sparkfun.com/load-cell-5kg-straight-bar-tal220b.html)

**Pros**
- 5kg measurement capacity
- Four-wire Wheatstone bridge
- IP65 protection
- Suitable for measuring food weight

**Cons**
- Requires signal amplification
- Requires mechanical mounting and calibration
- Must verify that 5kg covers the maximum expected load

**Proposed selection:** SparkFun TAL220B, subject to confirming the dispenser's required weight range.

## 2. Operational Amplifier

**Proposed selection:** Microchip MCP6004-I/P

[Product information and datasheet](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

## 3. Linear Voltage Regulator

**Proposed selection:** onsemi MC7805CTG

[Product information and datasheet](https://www.digikey.com/en/products/detail/on-semiconductor/MC7805CTG/MC7805CTGOS-ND/919333)

## 4. External Power Source

**Proposed architecture:** 9V DC wall adapter with a 5V linear regulator.

Final adapter and barrel jack selections pending verification.
