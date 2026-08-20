# System Architecture

## Modules
1. **Vision Module** — captures PCB images and identifies candidate components.
2. **Decision Module** — determines which components are suitable for recovery.
3. **Motion & Extraction Module** — controls positioning and component removal.
4. **Electrical Testing Module** — validates recovered components.
5. **Grading Module** — converts results into functional status and reuse grade.
6. **Inventory Module** — stores component and test metadata.

The architecture is modular so individual modules can be improved independently.
