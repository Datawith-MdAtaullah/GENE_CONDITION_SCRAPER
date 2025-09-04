# 🧬 **GENE_CONDITION_SCRAPER**

A **Python-based scraper** for extracting **gene-condition relationships** from [MedlinePlus](https://medlineplus.gov).  
This project gathers structured data that links human genes to associated medical conditions, enabling use in **bioinformatics, medical research, and clinical tools**.

---

## 📂 **Repository Structure**

- **main-project-files/** → Contains the **main scraper code** (use this to run the program).  
- **Extras---Alternative-Methods---RoughWork/** → Contains **rough work and alternative approaches** (not needed for execution).  

---

## ✨ **Features**

- Extracts **human gene names** from MedlinePlus.  
- Maps each **gene** to one or more **medical conditions**.  
- Outputs results in a **JSON-like structured format**.  
- Optimized for step-by-step execution in **Jupyter Notebook**.  

---

## 🛠️ **Requirements**

Install the required Python libraries before running:

```bash
pip install requests beautifulsoup4
```

## 🚀 **How to Run**

1. Clone the repository
   ```bash
   git clone https://github.com/Datawith-MdAtaullah/GENE_CONDITION_SCRAPER.git
   cd GENE_CONDITION_SCRAPER 
   ```

2. Open Jupyter Notebook (recommended for better understanding)
   ```bash
   jupyter notebook
   ```
3. Navigate to the main-project-files/ folder and open the notebook or script.
  
4. Run the cells step by step to extract:

    -> Gene names

    -> Related conditions

    -> Structured JSON-like output

## 📊 **Example Output**

The scraper produces results like this:
```bash
 json
                      [
                        {
                          "gene": "AAAS",
                          "conditions": [
                            "Triple A syndrome"
                          ]
                        },
                        {
                          "gene": "AASS",
                          "conditions": [
                            "Hyperlysinemia"
                          ]
                        }
                      ]
```
## 📝 **Notes**

1. Use Jupyter Notebook for the clearest, step-by-step workflow.

2. The Extras---Alternative-Methods---RoughWork/ folder is optional and not required for execution.

3. Results can be saved/exported as JSON or CSV for downstream analysis.

 
