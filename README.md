# LargeSHS: A Large-Scale Dataset of Music Adaptation
![alt text](https://github.com/tanchihpin0517/LargeSHS/blob/main/adaption.png?raw=true)

**LargeSHS** is a large-scale dataset designed to support research on **music adaptation**, **cover song generation**, and **reference-based music generation**.  
It is built upon the [SecondHandSongs (SHS)](https://secondhandsongs.com) database and provides structured adaptation relationships between musical works, performances, and artists.

---

## 🌐 Key Features

- **Structured adaptation relationships** between works — enabling the construction of *adaptation trees* and *cover song families*.
- **Metadata** derived from SHS, including artist names, adaptation types, and performance details.
- **~900K public audio links** (via YouTube IDs) for large-scale audio-based tasks.
- Enables **adaptation-aware MIR tasks** such as:
  - Cover song identification  
  - Reference-based music generation  
  - Music copyright and similarity analysis  

---

## 🧩 Comparison with Existing Datasets

| Dataset | Size | Source | Type |
|----------|-------|---------|------|
| Da-TACOS | 25K | SHS | Features only |
| Million Song Dataset | 18K | SHS | Features only |
| Cover10000 | 10K | SHS | Features only |
| Covers80 | 160 | Authors | Audio pairs |
| SHS100K | 100K | SHS | Metadata + Links |
| **LargeSHS (ours)** | **1.7M / 900K** | **SHS** | **Metadata + Audio links + Adaptation trees** |

LargeSHS is the **largest publicly available dataset** containing structured adaptation information, bridging the gap between symbolic metadata and audio-level data for music adaptation research.

---

## 🧠 Research Use Cases

- **Cover song generation**  
- **Reference-guided music generation**  
- **Music adaptation structure analysis**  
- **Cross-version retrieval and alignment**  
- **Copyright or influence tracing in music networks**

---

## 📄 Citation

If you use **LargeSHS** in your research, please cite:

> Chih-Pin Tan, Hsuan-Kai Kao, Li Su, and Yi-Hsuan Yang.  
> “**LargeSHS: A Large-Scale Dataset of Music Adaption**.”  
> *Extended Abstracts for the Late-Breaking Demo Session, ISMIR 2025, Daejeon, South Korea.*  

