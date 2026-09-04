# Persistent Project Instructions & Design Locks

## 🔒 Locked UI Proportions & Design Rules

### 1. Penta Words Layout & Proportion Lock (الكلمات الخماسية)
- **STRICT PROPORTION LOCK**: The dimensions, padding, font scaling, and aspect ratios of the 5-letter word cards (`.grid-penta-subgrid`, `.word-len-5`) are finalized and **PERMANENTLY LOCKED**.
- **DO NOT MODIFY** the penta words grid structure (4-column layout for penta words), cell min-heights (`98px` default, `115px` collapsed), or font scaling (`.word-len-5: clamp(4.45rem, 9.0cqi, 5.85rem)`, `line-height: 1.3`) unless the user explicitly requests to change them in their prompt.
- Preserve full cell coverage (`width: 100% !important; height: 100% !important;`) and textbook table grid styling.

### 2. Sentences Layout & Proportion Lock (جمل وتراكيب طلاقة القراءة)
- **STRICT PROPORTION LOCK**: The dimensions, padding, font scaling, and aspect ratios of the sentences section (`.grid-sentences-subgrid`, `.sentence-table-cell`, `.sentence-text-display`) are finalized and **PERMANENTLY LOCKED**.
- **DO NOT MODIFY** the sentences grid structure (2-column layout), cell min-heights (`92px` default, `110px` collapsed), padding (`0.35rem 1rem` default, `0.45rem 1.25rem` collapsed), or font scaling (`.sentence-text-display: clamp(3.95rem, 8.0cqi, 5.4rem)` default, `clamp(4.6rem, 9.4cqi, 6.2rem)` collapsed, `line-height: 1.3 !important;`) unless the user explicitly requests to change them in their prompt.
- Preserve full cell coverage (`width: 100% !important; height: 100% !important;`) and textbook table grid frame.

