<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>

<script type="text/javascript"
        src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

## **Unit 5: Characterization and Testing of Building Materials**

Different equipment, devices, and instruments to characterize the material response/ behavior; Current testing technology (displacement-controlled and load controlled) and its selection for capturing the response of the material; Documenting the experimental program, including the test procedures, collected data, method of interpretation and final results; Use of test data/ testing reports in the material selection for various civil engineering projects /construction

* [5.1 Introduction](#51-introduction)
* [5.2 Objectives of Material Testing](#52-objectives-of-material-testing)
* [5.3 Types of Tests and Classification](#53-types-of-tests-and-classification)
* [5.4 Equipment and Instrumentation](#54-equipment-and-instrumentation)
* [5.5 Load-Controlled vs Displacement-Controlled Testing Systems](#55-load-controlled-vs-displacement-controlled-testing-systems)
* [5.6 Selection of Testing Technique](#56-selection-of-testing-technique)
* [5.7 Testing Procedures (Illustrative Examples)](#57-testing-procedures-illustrative-examples)
* [5.8 Documentation of Experimental Program](#58-documentation-of-experimental-program)
* [5.9 Interpretation and Characterization of Test Results](#59-interpretation-and-characterization-of-test-results)
* [5.10 Application of Test Data in Material Selection](#510-application-of-test-data-in-material-selection)
* [5.11w Key IS and ASTM Standards](#512-key-is-and-astm-standards)

## **Unit 5: Characterization and Testing of Building Materials**

Characterization and testing involve evaluating the mechanical, physical, chemical, and durability behavior of construction materials under controlled conditions using modern laboratory instruments and testing setups. Characterization and testing of materials form a critical part of civil engineering quality assurance. It involves determining how materials respond to applied loads, environmental effects, and time-dependent factors. This unit discusses testing equipment, instrumentation, modern testing technologies, documentation, and data interpretation, with a focus on selecting suitable materials for various construction applications.

### **5.1 Introduction**

**Material characterization** is the process of determining physical, mechanical, and durability properties that define a material’s performance in structural and environmental conditions.

#### **Significance:**
- To ensure materials meet design and code-specified requirements  
- To study failure mechanisms (cracking, yielding, fatigue, etc.)  
- To compare materials for selection and performance optimization  
- To provide input for numerical modeling (FEM, simulation)

#### **Categories of Characterization:**
1. **Physical properties** – density, porosity, moisture content  
2. **Mechanical properties** – strength, stiffness, ductility  
3. **Durability aspects** – corrosion resistance, permeability, chemical attack  
4. **Microstructural aspects** – grain size, phase distribution, microcracks  

### **5.2 Objectives of Material Testing**

| **Objective**              | **Description**                                                  |
| -------------------------- | ---------------------------------------------------------------- |
| **Quality Assurance**      | Verify compliance with IS/ASTM standards                         |
| **Design Input**           | Determine parameters like $f_{ck}$, $E$, yield stress, etc.      |
| **Research & Development** | Study behavior under novel materials or mixes                    |
| **Failure Investigation**  | Analyze material response under overload or environmental damage |
| **Standardization**        | Establish benchmark data for reference                           |

### **5.3 Types of Tests and Classification** 

#### To learn more about Testing of material - Visit Unit 5 of this [website](https://gndec-yjs.github.io/CT/Contents/Content.html)

| **Category**                      | **Type of Test**                    | **Examples / Properties Measured**                     |
| --------------------------------- | ----------------------------------- | ------------------------------------------------------ |
| **Destructive Testing (DT)**      | Specimen is loaded till failure     | Compression, Tension, Flexure, Impact                  |
| **Non-Destructive Testing (NDT)** | No damage to specimen               | Rebound hammer, Ultrasonic Pulse Velocity, Cover meter |
| **Semi-Destructive Testing**      | Partial damage                      | Core cutting, Pull-out test                            |
| **Physical Tests**                | Density, Water absorption, Porosity | Cement fineness, Aggregate gradation                   |
| **Chemical Tests**                | Composition & contaminants          | Chloride, Sulphate, Alkali content                     |
| **Durability Tests**              | Long-term exposure                  | RCPT, carbonation depth, freeze–thaw resistance        |

### **5.4 Equipment and Instrumentation**

| **Equipment / Device**                     | **Purpose / Property Measured**                              | **Typical Range / Capacity** | **Relevant Standards / Codes**          |
| ------------------------------------------ | ------------------------------------------------------------ | ----------------------------- | --------------------------------------- |
| **Universal Testing Machine (UTM)**        | Performs tension, compression, and bending tests on steel, concrete, etc. | 100–2000 kN                  | IS 1608 (Part 1 : 2022), IS 516 (Part 1/Sec 1 : 2021) |
| **Compression Testing Machine (CTM)**      | Measures compressive strength of concrete cubes, cylinders, and bricks. | 1000–3000 kN                 | IS 516 (Part 1/Sec 1 : 2021)           |
| **Flexural Testing Frame / Machine**       | Determines flexural strength or modulus of rupture of beams, tiles, etc. | Up to 100 kN                 | IS 516 (Part 1/Sec 1 : 2021)           |
| **Rebound Hammer**                         | Evaluates surface hardness and indicative compressive strength of concrete. | 10–100 N/mm²                 | IS 516 (Part 5/Sec 4 : 2020)           |
| **Ultrasonic Pulse Velocity (UPV) Tester** | Determines internal integrity, cracks, and homogeneity of concrete. | 20–60 kHz                    | IS 516 (Part 5/Sec 1 : 2018)           |
| **Servo-Hydraulic Testing Machine**        | Performs load-controlled and displacement-controlled testing (static or cyclic). | Up to 2500 kN (varies)       | ASTM E4 (Ref.)                         |
| **Strain Gauge / LVDT**                    | Measures strain, deformation, or displacement with high precision. | Micron to mm range            | ASTM E83 (Ref.)                        |
| **Data Acquisition System (DAQ)**          | Records load, displacement, and strain data automatically in real-time. | Real-time sampling mode      | ASTM E4 (Ref.)                         |
| **Environmental Chamber**                  | Controls temperature and humidity for material conditioning or durability studies. | –10 °C to +60 °C             | ASTM D618 (Ref.)                       |
| **Corrosion Potential Meter (Half-Cell)**  | Measures half-cell potential to assess corrosion risk in reinforced concrete. | ±500 mV                      | ASTM C876 (Ref.)                       |
| **RCPT / Chloride Permeability Apparatus** | Evaluates chloride ion permeability and durability of concrete. | 0–4000 C                     | IS 516 (Part 2/Sec 3 : 2022)           |

### **5.5 Load-Controlled vs Displacement-Controlled Testing Systems**

| **Parameter**         | **Load-Controlled Testing**                     | **Displacement-Controlled Testing**                 |
| --------------------- | ----------------------------------------------- | --------------------------------------------------- |
| **Definition**        | Load is applied at a constant rate (e.g., kN/s) | Displacement or strain is controlled (e.g., mm/min) |
| **Suitable for**      | Brittle materials (concrete, masonry)           | Ductile materials (steel, fiber composites)         |
| **Control Variable**  | Force                                           | Displacement / Strain                               |
| **Response Observed** | Load vs deformation until failure               | Complete stress–strain curve including post-peak    |
| **Advantages**        | Simpler setup, suitable for QC tests            | Captures ductility, energy absorption               |
| **Disadvantages**     | Sudden failure in brittle materials             | Complex instrumentation                             |
| **Typical Standards** | IS 516, IS 1786                                 | ASTM E8, ASTM C469                                  |

### **5.6 Selection of Testing Technique**

The selection of an appropriate testing technique is a critical step in evaluating the performance, mechanical behavior, and durability of construction materials and structural components.  
The decision depends on the **type of material**, **property to be measured**, **accuracy required**, **testing environment**, and **control mode** (load- or displacement-controlled).  
A systematic approach ensures reliability, standardization, and reproducibility of experimental results.

#### **(a) Nature of Material**
- **Concrete:** Tested mainly for compressive, flexural, and durability characteristics. Common tests include compression (IS 516:2021), flexural strength, rebound hammer, and ultrasonic pulse velocity (UPV).  
- **Steel Reinforcement:** Tensile and ductility properties are measured as per IS 1608:2018, along with bend/re-bend tests (IS 1599:2012) and chemical analysis (IS 1786:2023).  
- **Masonry Units (Bricks / Blocks):** Compressive strength, water absorption, and efflorescence tests as per IS 3495 (Parts 1–4):1992.  

#### **(b) Type of Property to be Evaluated**
- **Mechanical Properties:** Include compressive strength, tensile strength, stiffness, and deformation behavior—typically under **load-controlled** conditions.  
- **Flexural or Ductility Behavior:** Evaluated using **displacement-controlled** tests to capture load–deflection and post-peak response accurately.  
- **Durability Properties:** Include permeability, corrosion potential, carbonation, and chloride penetration—performed under specialized environmental conditions.  
- **Elastic and Dynamic Properties:** Measured using non-destructive techniques like UPV or resonance frequency tests.  

#### **(c) Testing Environment**
- **Laboratory Testing:** Conducted under controlled conditions for precision and reproducibility (e.g., CTM, UTM, RCPT).  
- **Field Testing:** Performed on-site for rapid, non-destructive assessment of structural integrity (e.g., rebound hammer, UPV, corrosion mapping).  

#### **(d) Mode of Testing**
- **Destructive Testing (DT):**  
  Involves specimen failure to determine fundamental mechanical properties. Examples: compression, tension, and flexure tests.  
- **Non-Destructive Testing (NDT):**  
  Evaluates existing structures without damage, used for condition assessment and maintenance planning. Examples: rebound hammer, UPV, half-cell potential.  

#### **(e) Type of Control Mode**
- **Load-Controlled Testing:**  
  Load is applied at a constant rate until failure. Commonly used for **compressive and tensile strength** tests (CTM, UTM). Suitable for brittle materials where the load–strain response is linear until failure.  
- **Displacement-Controlled Testing:**  
  Cross-head displacement or strain is controlled. Used in **flexural tests, ductility studies, and post-peak response** of corroded or retrofitted RC members. Ensures stable data beyond peak load, especially with servo-hydraulic systems.  

#### **(f) Standardization and Accuracy**
Each test must comply with relevant **Indian (IS)** or **ASTM** standards.  
Equipment calibration, operator skill, and data-acquisition precision (as per ASTM E4 and IS 1828) significantly affect accuracy and repeatability.

#### **(g) Selection Criteria Summary**

| **Criteria** | **Description / Consideration** | **Example Test / Equipment** | **Control Type** | **Relevant Standards** |
|---------------|----------------------------------|-------------------------------|------------------|------------------------|
| **Nature of Material** | Concrete, Steel, Masonry | CTM, UTM | Load-controlled | IS 516:2021, IS 1608:2018 |
| **Mechanical Strength** | Compression, Tension, Flexure | UTM, Flexural Frame | Load / Displacement | IS 516:2021, ASTM E8 |
| **Ductility / Post-Cracking Response** | Load–deflection or stress–strain behavior | Servo-hydraulic UTM | Displacement-controlled | IS 516, ASTM C1609 |
| **Durability / Corrosion** | Permeability, Half-cell, Carbonation | RCPT, Corrosion Meter | N/A | ASTM C1202, ASTM C876 |
| **Elastic / Dynamic Properties** | Wave velocity, Modulus, Resonance | UPV Tester | N/A | IS 13311 (Part 1):1992 |
| **Field Assessment** | Surface hardness, strength estimation | Rebound Hammer | Load impact | IS 13311 (Part 2):1992 |

### **5.7 Testing Procedures (Illustrative Examples)**

#### To learn more about Testing of material - Visit Unit 5 of this [website](https://gndec-yjs.github.io/CT/Contents/Content.html)

#### **(a) Compressive Strength of Concrete**

$$ f_c = \frac{P}{A} $$

#### **(b) Tensile Test on Steel**

$$ L_0 = 5.65 \sqrt{A} $$

#### **(c) Flexural Strength of Concrete Beam**

$$ f_r = \frac{P L}{b d^2} $$

#### **(d) Split Tensile Strength of Concrete Cylinder**

$$ f_t = \frac{2P}{\pi D L} $$

#### **(f) Ultrasonic Pulse Velocity (UPV)**

$$ v = \frac{L}{t} $$

### **5.8 Documentation of Experimental Program**

Proper documentation of an experimental program is a vital component of material characterization and research.  
It ensures transparency, reproducibility, traceability, and reliability of the results obtained from laboratory or field testing.  
Documentation is required at all stages — from planning and execution to interpretation and reporting.

#### **(a) Objectives and Scope**
Before commencing any experimental work, clearly define:
- **Objective**: What property or behavior of the material is being evaluated.  
- **Scope**: Type of materials, number of samples, variables to be studied, and standards to be followed.  
- **Relevance**: Application of the findings in design, construction, or quality control.

#### **(b) Experimental Planning**
Key elements in planning include:
- **Selection of Testing Standards:** Use the latest revision of relevant IS or ASTM codes.  
- **Identification of Variables:** Material composition, curing conditions, corrosion exposure, loading rate, etc.  
- **Specimen Details:** Shape, size, quantity, and identification numbering.  
- **Instrumentation Setup:** Type of sensors (LVDTs, strain gauges), data acquisition frequency, calibration records.  
- **Test Matrix Preparation:** A structured table indicating test type, parameters, and replicates.

Example Test Matrix:

| **Test ID** | **Material / Mix** | **Specimen Type** | **Parameter Studied** | **No. of Specimens** | **Standard Reference** |
|--------------|-------------------|-------------------|------------------------|----------------------|------------------------|
| C1 | M25 Concrete | Cube (150 mm) | Compressive Strength | 3 | IS 516 |
| B1 | M25 Concrete | Beam (100×100×500 mm) | Flexural Strength | 3 | IS 516 |
| S1 | HYSD Steel | Rod (12 mm φ) | Tensile Strength | 3 | IS 1608 |

#### **(c) Data Recording and Observation**
During testing, all observations must be logged accurately in laboratory data sheets or electronic forms.

Include:
- **Identification Number** of specimen and date of testing.  
- **Environmental Conditions:** Temperature, humidity, and curing age.  
- **Instrument Readings:** Load, displacement, strain, voltage, current, etc.  
- **Failure Mode Description:** Crack pattern, yielding, crushing, etc.  
- **Operator’s Signature** for accountability.  

For automated systems, ensure proper calibration and time-stamped digital data storage (as per ASTM E4).

#### **(d) Data Processing and Analysis**
Post-testing, data should be processed systematically to obtain meaningful results:
- **Compute derived quantities** such as strength, modulus, or strain energy.  
- **Plot load–deflection or stress–strain curves** using standardized software tools.  
- **Statistical Analysis:** Mean, standard deviation, coefficient of variation (COV).  
- **Rejection of Outliers:** As per IS 8900 guidelines for statistical quality control.  
- **Graphical Representation:** Tables, charts, and comparison plots between theoretical and experimental data.

#### **(e) Interpretation and Discussion**
- Compare results with codal limits and literature values.  
- Identify deviations and possible reasons (mixing error, curing variation, instrument drift).  
- Highlight trends, e.g., “strength increases with curing period” or “corrosion reduces ductility.”  
- Link findings to real-world implications for design or material selection.

#### **(f) Preparation of Test Report**
Each experimental investigation must culminate in a structured report including the following sections:

| **Section** | **Description** |
|--------------|----------------|
| **Title Page** | Experiment title, course, laboratory name, date, and author details. |
| **Objective & Scope** | Brief statement of what is being tested and why. |
| **Reference Standards** | IS / ASTM codes followed. |
| **Materials & Equipment Used** | Details of cement, aggregates, admixtures, testing instruments, etc. |
| **Experimental Setup** | Schematics or photos of test arrangement. |
| **Procedure** | Step-by-step test method. |
| **Observations & Results** | Tables of readings and calculations. |
| **Discussion** | Analysis, interpretation, and comparison with standards. |
| **Conclusion** | Summary of key outcomes. |
| **References** | Books, IS codes, and papers referred. |

#### **(g) Data Archiving and Traceability**
To maintain long-term research integrity:
- Store all **raw data files**, **specimen photographs**, and **analysis spreadsheets** in an organized directory.  
- Maintain a **Digital Logbook** containing metadata — date, operator, equipment used, and calibration certificates.  
- Ensure **data backup** on institutional or cloud servers.  
- Follow institutional policies for research data management and sharing.

#### **(h) Importance of Documentation**
- Facilitates **verification** and **peer review**.  
- Enables **comparison** between multiple research programs.  
- Serves as a **reference** for design codes and quality audits.  
- Ensures **compliance** with BIS and accreditation bodies (e.g., NABL, ISO 17025).

**Summary:**  
A well-documented experimental program bridges the gap between raw testing and engineering application. It builds confidence in test results, supports decision-making in material selection, and contributes to the body of civil engineering knowledge.

### **5.9 Interpretation and Characterization of Test Results**

After conducting material tests, the collected data must be analyzed and interpreted to evaluate the **mechanical performance, deformation behavior, and durability characteristics** of the material.  
Interpretation converts raw experimental readings into meaningful engineering properties, which are then used in design, quality control, and material selection.

#### **Key Parameters and Their Interpretation**

| **Parameter**                     | **Definition / Formula**                                | **Interpretation / Significance**             |
| --------------------------------- | -------------------------------------------------------- | --------------------------------------------- |
| **Compressive Strength**          | $$ f_c = \frac{P}{A} $$                                 | Determines load-bearing capacity of concrete or masonry. |
| **Tensile Strength**              | $$ f_t = \frac{P}{A} $$                                 | Indicates cracking resistance and tensile capacity. |
| **Flexural Strength / Modulus of Rupture** | $$ f_r = \frac{P L}{b d^2} $$                           | Reflects bending strength and surface crack resistance. |
| **Modulus of Elasticity**         | $$ E = \frac{\sigma}{\varepsilon} $$ (within linear range) | Indicates stiffness or deformation behavior under elastic loading. |
| **Poisson’s Ratio**               | $$ \mu = \frac{\varepsilon_{lateral}}{\varepsilon_{longitudinal}} $$ | Represents lateral strain response to axial loading. |
| **Toughness / Energy Absorption** | Area under the stress–strain curve                       | Reflects ductility, energy dissipation, and post-yield behavior. |
| **Modulus of Resilience**         | $$ U_r = \frac{\sigma_y^2}{2E} $$                        | Energy absorbed per unit volume before yielding. |
| **Permeability / RCPT Value**     | Charge passed in Coulombs (C)                            | Indicates resistance to chloride or ion penetration; lower values imply better durability. |
| **Water Absorption / Porosity**   | $$ W = \frac{W_{sat} - W_{dry}}{W_{dry}} \times 100 $$  | Determines pore connectivity and durability against ingress. |
| **Density / Unit Weight**         | $$ \rho = \frac{m}{V} $$                                 | Indicates material compactness and quality control. |
| **Ductility Index**               | $$ D = \frac{\varepsilon_u}{\varepsilon_y} $$             | Ratio of ultimate strain to yield strain — measures deformability. |
| **Failure Mode**                  | Visual observation / post-test crack mapping             | Identifies brittle, ductile, or mixed behavior modes. |

#### **Graphical Representation**

Typical plots used for characterization:

- **Load–Deflection Curve:** Used for flexural behavior of beams or slabs.  
- **Stress–Strain Curve:** Used for tensile, compressive, or flexural tests; identifies yield point, ultimate strength, and ductility.  
- **RCPT Current–Time Curve:** Used to compute total charge passed (in Coulombs) for durability assessment.  
- **Creep and Shrinkage Curves:** Used for long-term deformation behavior.  
All graphs should be plotted on properly scaled axes with units and labeled legends.

#### **Interpretation Guidelines**

1. **Compare experimental results with codal limits** (e.g., IS 456 for concrete strength, IS 1608 for steel).  
2. **Check repeatability** by comparing values of replicate specimens; COV should generally be less than 10%.  
3. **Identify deviations** in behavior (e.g., premature cracking, excessive strain) and record observations.  
4. **Correlate mechanical and durability parameters** — e.g., higher permeability often corresponds to lower compressive strength.  
5. **Use normalized plots** (stress/strain ratios) for comparative studies across materials or curing conditions.

**Summary:**  
Interpretation transforms raw test data into performance indicators that describe **strength, stiffness, ductility, and durability**. These parameters enable engineers to **quantify material behavior** and form the foundation for design decisions and code validation.

### 5.10 Application of Test Data in Material Selection

Experimental test data play a crucial role in guiding engineers, researchers, and designers in the **selection, optimization, and qualification** of construction materials. The data obtained from laboratory and field tests provide **quantitative evidence** of material performance, enabling informed decisions for safe and sustainable design.

#### **(a) Concrete Mix Design Optimization**
- Test results such as **compressive strength**, **workability**, and **durability parameters** are analyzed to optimize mix proportions.
- Data from strength and permeability tests help balance **strength vs. durability trade-offs**.
- Example: A mix achieving 40 MPa compressive strength with low RCPT value (<1000 C) is preferred for marine structures.

#### **(b) Evaluation of Supplementary Cementitious Materials (SCMs)**
- Test data determine the suitability of materials like **fly ash, GGBS, silica fume, and metakaolin**.
- Indicators such as **strength gain with age**, **chloride resistance**, and **porosity reduction** are evaluated.
- Helps in replacing cement partially without compromising performance.

#### **(c) Steel Reinforcement Selection**
- **Tensile test** and **bend/rebend test** data (as per IS 1608 and IS 1786) guide the choice between **Fe 415, Fe 500, or Fe 550 grades**.
- Higher-grade steel may be preferred in **high-rise or earthquake-resistant structures**, provided ductility requirements are met.

#### **(d) Durability-Based Material Selection**
- Tests like **RCPT, water absorption, sorptivity, and carbonation depth** guide selection for **aggressive environments** (coastal, industrial).
- Materials with **low permeability** and **dense microstructure** are prioritized.
- Example: Use of micro-silica or nano-additives for high chloride resistance.

#### **(e) Fiber Reinforcement Evaluation**
- Flexural toughness and post-crack behavior help determine fiber type and dosage.
- **Steel fibers**, **polypropylene fibers**, or **basalt fibers** are selected based on test-derived improvements in **energy absorption** and **crack control**.

#### **(f) Sustainable Material Assessment**
- Life-cycle test data (strength retention, durability index, embodied energy) are used to evaluate **eco-friendly alternatives**.
- Example: Comparing test results of **CO₂-cured blocks** or **geopolymer concrete** against OPC-based systems.

#### **(g) Benchmarking and Quality Assurance**
- Experimental data serve as **benchmark values** during construction quality control.
- Any significant deviation in compressive or tensile test results triggers **re-evaluation or rejection** of material batches.

#### **(h) Data Integration with Design Codes**
- Test data are used to validate assumptions in **design equations** (e.g., modulus of elasticity, stress–strain curves).
- Helps in **refining partial safety factors** and **updating material models** in structural analysis software.

#### **Summary Table: Role of Test Data in Material Decisions**

| **Material Type**       | **Key Test Data Used**                         | **Design / Selection Decision**                              |
|--------------------------|------------------------------------------------|--------------------------------------------------------------|
| Concrete                 | Compressive strength, RCPT, carbonation depth  | Mix design approval, durability classification               |
| Reinforcing Steel        | Yield stress, elongation, bend test            | Selection of steel grade (Fe 415/500/550)                    |
| SCMs / Additives         | Strength gain, chloride resistance, porosity   | Dosage and replacement percentage determination              |
| Fiber Reinforcement      | Flexural toughness, energy absorption          | Fiber type and volume fraction selection                     |
| Alternative Binders      | Setting time, compressive strength, shrinkage  | Suitability for sustainable construction                     |
| Masonry Units / Blocks   | Compressive strength, density, water absorption | Acceptance or rejection for wall construction                |

**Conclusion:**  
Test data provide the **scientific basis** for comparing materials objectively, ensuring performance consistency, compliance with IS standards, and alignment with sustainability goals. Proper interpretation of experimental results transforms laboratory findings into **practical, code-compliant engineering solutions**.

### **5.11 Key IS and ASTM Standards**

| **Area**         | **IS Codes**              | **ASTM Codes** |
| ---------------- | ------------------------- | -------------- |
| Concrete Testing | IS 516, IS 1199, IS 13311 | ASTM C39, C469 |
| Steel Testing    | IS 1608, IS 1786          | ASTM E8        |
| NDT Methods      | IS 13311                  | ASTM C597      |
| Durability Tests | IS 456, IS 383            | ASTM C1202     |
| Data Acquisition | -                         | ASTM E4        |
| Timber Testing   | IS 1734, IS 1708          | ASTM D198      |
