# Kerangka Berpikir Penelitian

Berikut adalah visualisasi skema kerangka berpikir untuk penelitian ini. Diagram ini menjelaskan hubungan antara variabel input, proses, dan output.

```mermaid
graph TD;
    subgraph Variabel Input;
        X1["<b>X1: Penerapan PBL</b><br>(Problem-Based Learning)"]
        X2["<b>X2: Kompetensi TPACK Guru</b><br>(Technological Pedagogical Content Knowledge)"]
    end

    subgraph Proses Pembelajaran;
        P["<b>Proses Pembelajaran PBL Berbasis TPACK</b><br>(Kolaborasi & Sinergi di Kelas PPKn)"]
    end

    subgraph Variabel Output;
        Y["<b>Y: Hasil Belajar Siswa</b>"]
    end
    
    subgraph Indikator Hasil Belajar;
        Y1["Y1: Kognitif"]
        Y2["Y2: Afektif"]
        Y3["Y3: Psikomotorik"]
    end

    X1 -- Pengaruh Bersama --> P;
    X2 -- Pengaruh Bersama --> P;
    P -- Berpengaruh Terhadap --> Y;
    Y ---> Y1;
    Y ---> Y2;
    Y ---> Y3;

    style X1 fill:#cce5ff,stroke:#333,stroke-width:2px
    style X2 fill:#cce5ff,stroke:#333,stroke-width:2px
    style P fill:#d4edda,stroke:#333,stroke-width:2px
    style Y fill:#fff3cd,stroke:#333,stroke-width:2px
    style Y1 fill:#f8d7da,stroke:#333,stroke-width:1px
    style Y2 fill:#f8d7da,stroke:#333,stroke-width:1px
    style Y3 fill:#f8d7da,stroke:#333,stroke-width:1px
