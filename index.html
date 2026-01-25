<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Condică Onco România 2025 - Lista Completă</title>
    <style>
        /* Stiluri Generale (Desktop First) */
        body { 
            background-color: #0d0d0d; 
            color: #ffffff; 
            font-family: 'Segoe UI', Roboto, Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            line-height: 1.4;
        }

        .header { 
            position: sticky; 
            top: 0; 
            background-color: #1a1a1a; 
            padding: 20px; 
            border-bottom: 3px solid #333; 
            z-index: 1000; 
            box-shadow: 0 5px 15px rgba(0,0,0,0.6); 
        }

        #searchInput { 
            width: 100%; 
            padding: 18px; 
            font-size: 24px; 
            border-radius: 12px; 
            border: 2px solid #444; 
            background: #252525; 
            color: #fff; 
            box-sizing: border-box; 
            outline: none; 
        }

        .container { padding: 15px; }

        table { 
            width: 100%; 
            border-collapse: collapse; 
            margin-bottom: 50px;
        }

        th { 
            text-align: left; 
            font-size: 14px; 
            color: #888; 
            text-transform: uppercase; 
            padding: 15px; 
            border-bottom: 2px solid #333; 
        }

        td { 
            padding: 20px 12px; 
            border-bottom: 1px solid #222; 
            vertical-align: middle; 
        }

        .loc { 
            color: #aaaaaa; 
            font-size: 17px; 
            display: block; 
            margin-bottom: 4px; 
            font-weight: 400; 
            text-transform: uppercase; 
        }

        .subst { 
            color: #ffffff; 
            font-size: 24px; 
            font-weight: 700; 
            display: block; 
        }

        .mech { 
            color: #3498db; 
            font-size: 19px; 
            font-weight: 500; 
        }

        .badge { 
            padding: 12px 18px; 
            border-radius: 8px; 
            font-size: 15px; 
            font-weight: 900; 
            white-space: nowrap; 
            text-align: center; 
            display: inline-block; 
            min-width: 140px; 
        }

        .cv { background-color: #7a0000; color: #ffcccc; border: 1px solid #cc0000; }
        .pns { background-color: #004d1a; color: #ccffdd; border: 1px solid #00cc44; }

        tr:hover { background-color: #161616; }

        /* OPTIMIZĂRI PENTRU MOBIL */
        @media screen and (max-width: 768px) {
            .header { padding: 12px; }
            #searchInput { font-size: 18px; padding: 12px; }
            
            /* Ascundem coloana cu Mecanism pe mobil pentru a evita aglomerația */
            th:nth-child(2), td:nth-child(2) { display: none; }

            .subst { font-size: 18px; }
            .loc { font-size: 13px; }
            
            .badge { 
                min-width: 60px; 
                padding: 6px 10px; 
                font-size: 12px; 
            }
            
            /* Schimbăm textul lung cu abrevieri pe ecrane foarte mici via JS sau CSS */
            .badge-text-full { display: none; }
            .badge-text-short { display: inline; }
        }

        @media screen and (min-width: 769px) {
            .badge-text-short { display: none; }
            .badge-text-full { display: inline; }
        }
    </style>
</head>
<body>

<div class="header">
    <input type="text" id="searchInput" placeholder="CAUTĂ MEDICAMENT SAU BOALĂ..." onkeyup="filterTable()">
</div>

<div class="container">
    <table id="drugTable">
        <thead>
            <tr>
                <th>Indicație & Substanță</th>
                <th>Mecanism / Tip</th>
                <th style="text-align: right;">Condică</th>
            </tr>
        </thead>
        <tbody id="tableBody"></tbody>
    </table>
</div>

<script>
const data = [
    {l: "Bazocelular", s: "Cemiplimab", m: "Anti-PD1", t: "CV"},
    {l: "Cutanat Scuamos", s: "Cemiplimab", m: "Anti-PD1", t: "CV"},
    {l: "Celule Merkel", s: "Avelumab", m: "Anti-PD-L1", t: "CV"},
    {l: "Neuroendocrine", s: "Analogi de Somatostatina", m: "Analog Hormonal", t: "PNS"},
    {l: "Neuroendocrine", s: "Everolimus", m: "Inhibitor mTOR", t: "CV"},
    {l: "Neuroendocrine", s: "Sunitinib", m: "TKI", t: "PNS"},
    {l: "Sarcoame", s: "Eribulin", m: "Inhibitor Microtubuli", t: "CV"},
    {l: "Sarcoame", s: "Imatinib", m: "TKI", t: "PNS"},
    {l: "Sarcoame", s: "Pazopanib", m: "TKI", t: "PNS"},
    {l: "Sarcoame", s: "Trabectedinum", m: "Agent Alchilant", t: "CV"},
    {l: "Mamar", s: "Abemaciclib", m: "Inhibitor CDK 4/6", t: "CV"},
    {l: "Mamar", s: "Atezolizumab", m: "Anti-PD-L1", t: "CV"},
    {l: "Mamar", s: "Bevacizumab", m: "Anti-VEGF", t: "PNS"},
    {l: "Mamar", s: "Eribulin", m: "Inhibitor Microtubuli", t: "CV"},
    {l: "Mamar", s: "Lapatinib", m: "TKI HER2", t: "PNS"},
    {l: "Mamar", s: "Olaparib", m: "Inhibitor PARP", t: "CV"},
    {l: "Mamar", s: "Palbociclib", m: "Inhibitor CDK 4/6", t: "CV"},
    {l: "Mamar", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Mamar", s: "Pertuzumab", m: "Anti-HER2", t: "PNS"},
    {l: "Mamar", s: "Ribociclib", m: "Inhibitor CDK 4/6", t: "CV"},
    {l: "Mamar", s: "Sacituzumab Govitecan", m: "ADC Trop-2", t: "PNS"},
    {l: "Mamar", s: "Trastuzumab", m: "Anti-HER2", t: "PNS"},
    {l: "Mamar", s: "Trastuzumab Deruxtecan", m: "ADC Anti-HER2", t: "CV"},
    {l: "Mamar", s: "Trastuzumab Emtansine", m: "ADC Anti-HER2", t: "PNS"},
    {l: "Mamar", s: "Trastuzumab + Pertuzumab", m: "Dublă blocadă HER2", t: "PNS"},
    {l: "Mamar", s: "Tucatinib", m: "TKI HER2", t: "CV"},
    {l: "Gastric", s: "Nivolumab", m: "Anti-PD1", t: "CV"},
    {l: "Gastric", s: "Ramucirumab", m: "Anti-VEGFR2", t: "CV"},
    {l: "Gastric", s: "Trastuzumab", m: "Anti-HER2", t: "PNS"},
    {l: "Gastric", s: "Trastuzumab Deruxtecan", m: "ADC Anti-HER2", t: "CV"},
    {l: "Gastric", s: "Trifluridin Tipiracil", m: "Citostatic oral", t: "PNS"},
    {l: "Esofag", s: "Nivolumab + Ipilimumab", m: "Dublă Imunoterapie", t: "CV"},
    {l: "Esofag", s: "Nivolumab", m: "Anti-PD1", t: "CV"},
    {l: "Esofag", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Prostata", s: "Abiraterona", m: "Inhibitor Androgeni", t: "PNS"},
    {l: "Prostata", s: "Apalutamida", m: "Inhibitor AR", t: "CV"},
    {l: "Prostata", s: "Cabazitaxel", m: "Taxan Gen. 2", t: "PNS"},
    {l: "Prostata", s: "Enzalutamida", m: "Inhibitor AR", t: "CV"},
    {l: "Prostata", s: "Olaparib", m: "Inhibitor PARP", t: "CV"},
    {l: "Pancreas", s: "Erlotinib", m: "TKI EGFR", t: "PNS"},
    {l: "Pancreas", s: "Onivyde", m: "Irinotecan Lipozomal", t: "CV"},
    {l: "Colorectal", s: "Aflibercept", m: "VEGF Trap", t: "CV"},
    {l: "Colorectal", s: "Bevacizumab", m: "Anti-VEGF", t: "PNS"},
    {l: "Colorectal", s: "Cetuximab", m: "Anti-EGFR", t: "PNS"},
    {l: "Colorectal", s: "Nivolumab + Ipilimumab", m: "Dublă Imunoterapie", t: "CV"},
    {l: "Colorectal", s: "Panitumumab", m: "Anti-EGFR", t: "PNS"},
    {l: "Colorectal", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Colorectal", s: "Trifluridin Tipiracil", m: "Citostatic oral", t: "CV"},
    {l: "Mezoteliom Pleural", s: "Nivolumab + Ipilimumab", m: "Dublă Imunoterapie", t: "CV"},
    {l: "Mezoteliom Pleural", s: "Pemetrexed", m: "Antifolat", t: "PNS"},
    {l: "GIST", s: "Regorafenib", m: "Inhibitor Multikinază", t: "CV"},
    {l: "GIST", s: "Sunitinib", m: "TKI", t: "PNS"},
    {l: "Melanom", s: "Dabrafenib", m: "Inhibitor BRAF", t: "CV"},
    {l: "Melanom", s: "Dabrafenib + Trametinib", m: "Inhibitori BRAF/MEK", t: "CV"},
    {l: "Melanom", s: "Ipilimumab", m: "Anti-CTLA-4", t: "CV"},
    {l: "Melanom", s: "Nivolumab", m: "Anti-PD1", t: "CV"},
    {l: "Melanom", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Melanom", s: "Vemurafenib", m: "Inhibitor BRAF", t: "CV"},
    {l: "Urotelial", s: "Atezolizumab", m: "Anti-PD-L1", t: "PNS"},
    {l: "Urotelial", s: "Avelumab", m: "Anti-PD-L1", t: "CV"},
    {l: "Urotelial", s: "Nivolumab", m: "Anti-PD1", t: "PNS"},
    {l: "Urotelial", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Urotelial", s: "Vaccin BCG", m: "Imunoterapie BCG", t: "PNS"},
    {l: "Tiroidian", s: "Sorafenib", m: "TKI", t: "PNS"},
    {l: "Tiroidian", s: "Vandetanib", m: "TKI", t: "CV"},
    {l: "Renal", s: "Avelumab", m: "Anti-PD-L1", t: "CV"},
    {l: "Renal", s: "Axitinib", m: "TKI", t: "CV"},
    {l: "Renal", s: "Bevacizumab", m: "Anti-VEGF", t: "PNS"},
    {l: "Renal", s: "Cabozantinib", m: "TKI", t: "CV"},
    {l: "Renal", s: "Everolimus", m: "Inhibitor mTOR", t: "CV"},
    {l: "Renal", s: "Nivolumab", m: "Anti-PD1", t: "CV"},
    {l: "Renal", s: "Nivolumab + Cabozantinib", m: "I-O + TKI", t: "CV"},
    {l: "Renal", s: "Nivolumab + Ipilimumab", m: "Dublă I-O", t: "CV"},
    {l: "Renal", s: "Pazopanib", m: "TKI", t: "PNS"},
    {l: "Renal", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Renal", s: "Sorafenib", m: "TKI", t: "PNS"},
    {l: "Renal", s: "Sunitinib", m: "TKI", t: "PNS"},
    {l: "Renal", s: "Tivozanib", m: "TKI", t: "CV"},
    {l: "Ovarian", s: "Bevacizumab", m: "Anti-VEGF", t: "PNS"},
    {l: "Ovarian", s: "Olaparib", m: "Inhibitor PARP", t: "CV"},
    {l: "Ovarian", s: "Trabectedinum", m: "Agent Alchilant", t: "CV"},
    {l: "Hepatocelular", s: "Atezolizumab", m: "Anti-PD-L1", t: "CV"},
    {l: "Hepatocelular", s: "Cabozantinib", m: "TKI", t: "CV"},
    {l: "Hepatocelular", s: "Ramucirumab", m: "Anti-VEGFR2", t: "CV"},
    {l: "Hepatocelular", s: "Regorafenib", m: "Inhibitor Multikinază", t: "CV"},
    {l: "Hepatocelular", s: "Sorafenib", m: "TKI", t: "PNS"},
    {l: "Scuamos Cap și Gat", s: "Cetuximab", m: "Anti-EGFR", t: "PNS"},
    {l: "Scuamos Cap și Gat", s: "Nivolumab", m: "Anti-PD1", t: "CV"},
    {l: "Scuamos Cap și Gat", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "Col Uterin", s: "Bevacizumab", m: "Anti-VEGF", t: "PNS"},
    {l: "Col Uterin", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "NSCLC", s: "Afatinib", m: "TKI EGFR", t: "PNS"},
    {l: "NSCLC", s: "Alectinib", m: "Inhibitor ALK", t: "CV"},
    {l: "NSCLC", s: "Atezolizumab", m: "Anti-PD-L1", t: "CV"},
    {l: "NSCLC", s: "Bevacizumab", m: "Anti-VEGF", t: "PNS"},
    {l: "NSCLC", s: "Brigatinib", m: "Inhibitor ALK", t: "CV"},
    {l: "NSCLC", s: "Cemiplimab", m: "Anti-PD1", t: "CV"},
    {l: "NSCLC", s: "Ceritinib", m: "Inhibitor ALK", t: "CV"},
    {l: "NSCLC", s: "Crizotinib", m: "Inhibitor ALK/ROS1", t: "PNS"},
    {l: "NSCLC", s: "Durvalumab", m: "Anti-PD-L1", t: "CV"},
    {l: "NSCLC", s: "Erlotinib", m: "TKI EGFR", t: "PNS"},
    {l: "NSCLC", s: "Gefitinib", m: "TKI EGFR", t: "PNS"},
    {l: "NSCLC", s: "Lorlatinib", m: "Inhibitor ALK G3", t: "CV"},
    {l: "NSCLC", s: "Nivolumab + Ipilimumab", m: "Dublă I-O", t: "CV"},
    {l: "NSCLC", s: "Nivolumab", m: "Anti-PD1", t: "CV"},
    {l: "NSCLC", s: "Pembrolizumab", m: "Anti-PD1", t: "CV"},
    {l: "NSCLC", s: "Osimertinib", m: "TKI EGFR G3", t: "CV"},
    {l: "NSCLC", s: "Ramucirumab", m: "Anti-VEGFR2", t: "PNS"},
    {l: "SCLC", s: "Atezolizumab", m: "Anti-PD-L1", t: "CV"},
    {l: "SCLC", s: "Durvalumab", m: "Anti-PD-L1", t: "CV"}
];

function populateTable() {
    const tbody = document.getElementById('tableBody');
    // Sortăm alfabetic după localizare
    const sortedData = data.sort((a, b) => a.l.localeCompare(b.l));
    
    tbody.innerHTML = sortedData.map(item => {
        const isCV = item.t.toUpperCase() === 'CV';
        return `
            <tr>
                <td>
                    <span class="loc">${item.l}</span>
                    <span class="subst">${item.s}</span>
                </td>
                <td><span class="mech">${item.m}</span></td>
                <td align="right">
                    <span class="badge ${isCV ? 'cv' : 'pns'}">
                        <span class="badge-text-full">${isCV ? 'COST-VOLUM' : 'PROGRAM'}</span>
                        <span class="badge-text-short">${item.t}</span>
                    </span>
                </td>
            </tr>
        `;
    }).join('');
}

function filterTable() {
    let input = document.getElementById("searchInput");
    let filter = input.value.toUpperCase();
    let tr = document.getElementById("drugTable").getElementsByTagName("tr");
    for (let i = 1; i < tr.length; i++) {
        let text = tr[i].textContent || tr[i].innerText;
        tr[i].style.display = text.toUpperCase().indexOf(filter) > -1 ? "" : "none";
    }
}

window.onload = populateTable;
</script>
</body>
</html>
