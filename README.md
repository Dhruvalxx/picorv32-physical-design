# PicoRV32 Physical Design Optimization

Physical design optimization project: **143 MHz → 167 MHz** (67% improvement)

![Technology](https://img.shields.io/badge/Technology-SkyWater%20130nm-blue)
![Frequency](https://img.shields.io/badge/Frequency-167%20MHz-green)
![Tool](https://img.shields.io/badge/Tool-OpenLane-orange)

---

## 📊 Results Summary

| Metric | Before | After | Change |
|--------|--------|-------|--------|
| **Frequency** | 143 MHz | 167 MHz | +67% ✅ |
| **Clock Period** | 7.0 ns | 6.0 ns | -1.0 ns |
| **Total Cells** | 11,147 | 10,293 | -854 cells |
| **Violations** | 86 fanout | 1 fanout | -99% ✅ |
| **DRC/LVS** | 0 errors | 0 errors | Clean ✅ |

---

## 🎯 What I Did

Optimized a RISC-V processor through **complete RTL-to-GDSII flow** using industry-standard tools.

**Key Achievement:** 67% frequency improvement while maintaining zero timing violations and manufacturing quality.

---

## 🛠️ Tools & Technology

- **Design:** PicoRV32 RISC-V Processor
- **Technology:** SkyWater 130nm PDK
- **Tools:** OpenLane, OpenROAD, Magic, Yosys
- **Environment:** Docker, WSL2

---

## 📖 Optimization Journey

Completed **6 complete design iterations**, learning from each failure:

### ❌ Iteration 1: Timing Failure
- Tried 200 MHz but gates were too slow
- **Learned:** Need faster gates for high frequency

### ❌ Iteration 2-4: Routing Failures  
- Larger gates caused routing congestion
- **Learned:** Must balance speed vs routability

### ✅ Iteration 5: SUCCESS!
- 167 MHz with perfect timing
- **Strategy:** Balanced approach with manual control

### ⚠️ Iteration 6: Over-optimization
- Automated fixes made things worse
- **Learned:** Sometimes "good enough" is best


---

## 📁 What's in This Repository
```
├── report/
│   └── PicoRV32_Report.pdf          # Complete technical report
├── config/
│   └── final_config.json            # Successful configuration
└── README.md                         # This file
```

---

## 🎓 What I Learned

**Technical Skills:**
- Complete RTL-to-GDSII physical design flow
- Timing optimization and analysis
- Routing congestion debugging
- Physical verification (DRC/LVS)

**Engineering Skills:**
- Systematic problem-solving
- Trade-off analysis
- When to use/avoid automation
- Professional documentation

---

## 📞 Connect With Me

- **Email:** dhruvalvachhani@gmail.com
- **GitHub:** github.com/Dhruvalxx
- **LinkedIn:** linkedin.com/in/dhruvalvachhani

---

## ⭐ Project Highlights

This project demonstrates **real engineering problem-solving** - not just running tools, but understanding failures, analyzing trade-offs, and making informed decisions.

Perfect for demonstrating skills to VLSI companies like Intel, Synopsys, Qualcomm, etc.

---

**Keywords:** VLSI, Physical Design, ASIC, RTL-to-GDSII, OpenLane, SkyWater, RISC-V, Semiconductor
```

### **Save the changes:**

1. Scroll to bottom
2. In the box, type: `Update README with professional content`
3. Click green button: **"Commit changes"**

---

## **STEP 2: ADD DESCRIPTION & TOPICS**

### **On the right side, you see "About" section**

1. Click the **⚙️ gear icon** next to "About"

### **A popup will appear:**

**In "Description" field, paste:**
```
Physical Design Optimization: 67% frequency improvement using OpenLane & SkyWater 130nm PDK
```

**In "Topics" field, add these ONE BY ONE (press Enter after each):**
```
vlsi
physical-design
rtl-to-gdsii
openlane
skywater-pdk
risc-v
asic-design
```

**Click "Save changes"**

---

## **STEP 3: CREATE REPORT FOLDER**

### **Click "Add file" button** (top-right, next to green "Code" button)

1. Select **"Create new file"**

### **In the name box that appears, type:**
```
report/placeholder.txt
```

**Important:** The `report/` part creates the folder!

### **In the big text box below, type:**
```
Temporary file - will be deleted after PDF upload
```

### **Scroll down and click "Commit new file"**

---

## **STEP 4: UPLOAD YOUR PDF**

### **Click on "report" folder** (you'll see it in the file list now)

### **Inside the report folder, click "Add file" → "Upload files"**

### **Upload your PDF:**

1. Click **"choose your files"**
2. Navigate to your PDF report
3. Select it
4. Wait for green checkmark

### **Scroll down:**
1. Type: `Add project report PDF`
2. Click **"Commit changes"**

---

## **STEP 5: DELETE PLACEHOLDER**

### **While still in report folder:**

1. Click on `placeholder.txt`
2. Click the **trash icon** 🗑️ (top-right)
3. Scroll down
4. Click **"Commit changes"**

---

## **STEP 6: CREATE CONFIG FOLDER AND FILE**

### **Go back to main page** (click `picorv32-physical-design` at top)

### **Click "Add file" → "Create new file"**

### **In name box, type:**
```
config/final_config.json

{
    "DESIGN_NAME": "picorv32",
    "VERILOG_FILES": "dir::src/picorv32.v",
    "CLOCK_PORT": "clk",
    "CLOCK_PERIOD": 6.0,
    "FP_SIZING": "absolute",
    "DIE_AREA": "0 0 900 900",
    "FP_CORE_UTIL": 50,
    "PL_TARGET_DENSITY": 0.50,
    "SYNTH_STRATEGY": "DELAY 1",
    "MAX_FANOUT_CONSTRAINT": 10,
    "GRT_REPAIR_ANTENNAS": 1
}
```

### **Scroll down:**
1. Type: `Add final successful configuration`
2. Click **"Commit new file"**

---

## **STEP 7: VERIFY EVERYTHING**

### **Go to main repository page**

You should now see:
```
picorv32-physical-design/
├── .gitignore
├── LICENSE
├── README.md                  ← Your professional README
├── config/
│   └── final_config.json     ← Your config file
└── report/
    └── PicoRV32_Report.pdf   ← Your PDF report
```

**Scroll down on the main page** - you should see your beautiful README with:
- ✅ Badges at the top
- ✅ Tables
- ✅ Project description
- ✅ All sections formatted nicely

**On the right side "About" section:**
- ✅ Description
- ✅ Topics/tags listed

---

## **STEP 8: TAKE SCREENSHOT & CELEBRATE!** 🎉

Take a screenshot of your complete repository and show me!

---

## **YOUR LINKS ARE NOW:**

**Profile:**
```
github.com/Dhruvalxx
```

**This Project:**
```
github.com/Dhruvalxx/picorv32-physical-design
