# Project Charter - Quran Frontend

**Last Updated**: [Date]
**Version**: 1.0.0
**Status**: In Progress

---

## 1. Project Identification

| Field                  | Value                               |
| ---------------------- | ----------------------------------- |
| **Project Name**       | Quran Frontend                      |
| **Project Repo**       | quran-frontend                      |
| **Project Manager**    | [ekiuse](https://github.com/ekiuse) |
| **Development Team**   | Frontend                            |
| **Start Date**         | 2023-10-03                          |
| **Estimated End Date** |                                     |

---

## 2. Vision and Goals

### Vision

TBD

### High-Level Goals

TBD

## 3. Project Scope

### In-Scope

TBD

### Out-of-Scope

TBD

## 4. Architecture & Technologies

### Frontend

- **Framework**: React(PWA)
- **Standards**: frontend-standards
- **Template**: natiq-frontend

#### URLS

- /
- /search
- /settings
- /en/[view_mode]/[rom_slug][surah_number]:[ayah_number]
- /en/page/[number]

view_mode: [mushaf, surah, ayah]

### Infrastructure

- **CI/CD**: GitHub Actions
- **Hosting**:
  - Single standalone server (Linux) running Docker
  - AWS
- **Docker available containers**:
  - quran-frontend

---

## 5. Pending Decisions

TBD

---

## 6. Timeline

TBD

---

## 7. Risks & Challenges

TBD

---

## 8. Success Metrics

TBD

---

## 9. Budget & Resources

- **Human Resources**: 1 developer
- **Hardware/Software Resources**: 1 server

---

## 10. Approval Signatures

| Role            | Github Account                                    |
| --------------- | ------------------------------------------------- |
| Curator         | [Al-Abd](https://github.com/al-abd)               |
| DevOps          | [codebysilence](https://github.com/codebysilence) |
| Project Manager | [ekiuse](https://github.com/ekiuse)               |
