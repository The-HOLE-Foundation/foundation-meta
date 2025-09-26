# The HOLE Foundation - GitHub Repository Index

## Repository Overview

This document provides a comprehensive index of all repositories in The HOLE Foundation GitHub organization, their purposes, current status, and coordination information.

## 📁 Active Repositories

### 1. foundation-meta (THIS REPOSITORY)
- **URL**: https://github.com/The-HOLE-Foundation/foundation-meta.git
- **Purpose**: 🎯 Central Command & Cross-Project Coordination
- **Status**: Active - Primary coordination hub
- **Current Files**: 4 (README, PROJECT_STATUS_UPDATE, reorganization docs)
- **Role**: Organization-wide standards, strategic planning, integration mapping

### 2. us-transparency-laws-database
- **URL**: https://github.com/The-HOLE-Foundation/us-transparency-laws-database.git
- **Purpose**: 📊 Transparency Law Data Repository
- **Status**: Active - Contains 250+ files (NEEDS REORGANIZATION)
- **Issue**: Currently contains misplaced organizational and platform content
- **Target Role**: Pure data repository for transparency laws and validation

### 3. Theholefoundation.org
- **URL**: https://github.com/The-HOLE-Foundation/Theholefoundation.org.git
- **Purpose**: 🏢 HOLE Foundation Organization Website
- **Status**: Minimal - Needs development
- **Current Files**: 2 (LICENSE, basic README)
- **Target Role**: Foundation mission, governance, fundraising, organizational content

### 4. THEHOLETRUTH.ORG
- **URL**: https://github.com/The-HOLE-Foundation/THEHOLETRUTH.ORG.git
- **Purpose**: 🌐 THE HOLE TRUTH PROJECT Platform
- **Status**: Minimal - Needs architecture migration
- **Current Files**: 1 (basic README)
- **Target Role**: Transparency Wiki, Map, FOIA Generator, Liberated Library

## 📋 Required New Repository

### 5. liberated-documents (TO BE CREATED)
- **Purpose**: 📄 Foundation's Transparency Victories Archive
- **Status**: Planning phase - "Coming Soon" feature
- **Content**: Border violence, corruption, transparency violations documentation
- **Access**: Foundation-controlled, no public uploads initially

## 🔗 Project Structure & Separation

### HOLE Foundation (Organization)
```
Repository: Theholefoundation.org
Purpose: Organizational identity, mission, governance
Tagline: "Shining light in holes where democracy goes dark"
Leadership: Physician with personal political experience
```

### THE HOLE TRUTH PROJECT (Platform)
```
Repository: THEHOLETRUTH.ORG
Purpose: Public transparency tools and resources
Features: Wiki, Map, FOIA Generator, Liberated Library
Tagline: "The truth will set you free | Free the truth"
Philosophy: "Elections are auditions. Public records are receipts"
```

## ⚙️ Standardized Tech Stack

All public-facing repositories should use:
- **Framework**: Next.js 15 (App Router, React Server Components)
- **Styling**: Tailwind CSS + Shadcn/ui (Radix primitives)
- **Data**: Supabase (Postgres, Auth, Storage)
- **Fetching**: Server Components + React Query
- **Deployment**: SSR/SEO-first, Edge runtime optimization

## 📊 Current Status Summary

| Repository | Files | Status | Priority Action |
|------------|-------|--------|-----------------|
| foundation-meta | 4 | ✅ Active | Central coordination |
| us-transparency-laws-database | 250+ | ⚠️ Bloated | Reorganize & extract |
| Theholefoundation.org | 2 | 🔴 Minimal | Develop org website |
| THEHOLETRUTH.ORG | 1 | 🔴 Minimal | Migrate platform architecture |
| liberated-documents | 0 | 🟡 Planned | Create & populate |

## 🎯 Reorganization Priorities

### Immediate (Week 1-2)
1. **Extract misplaced content** from us-transparency-laws-database
2. **Create liberated-documents repository** with "Coming Soon" content
3. **Migrate platform architecture** to THEHOLETRUTH.ORG
4. **Move foundation standards** to foundation-meta

### Short-term (Week 3-4)
1. **Develop organizational website** in Theholefoundation.org
2. **Standardize tech stack** across all repositories
3. **Implement documentation localization**
4. **Update cross-references** and integration docs

## 🔍 Coordination Guidelines

### For Contributors
- **Organization work** → `theholefoundation.org` repository
- **Platform development** → `THEHOLETRUTH.ORG` repository
- **Data work** → `us-transparency-laws-database` repository
- **Cross-project issues** → `foundation-meta` repository

### For Project Management
- All strategic planning and cross-repo coordination happens here (`foundation-meta`)
- Repository-specific documentation lives in respective repositories
- Integration and dependency mapping maintained centrally

---

*Last Updated: 2025-09-25*
*Total Repositories: 4 active, 1 planned*
*Reorganization Status: Ready for implementation*