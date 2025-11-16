# ROSA Parent-Child Issues Change Report - Last 3 Weeks
**Report Generated**: 2025-11-16
**Period Covered**: 2025-10-26 to 2025-11-16 (21 days)
**Source**: [ROSA Non-Closed Children Report](https://github.com/nelsonjean/ROSA-Service-Feature-Alignment/blob/main/rosa-non-closed-children-report.md)

---

## Executive Summary

### ROSA Parent Issues Status Overview
| Parent | Summary | Priority | Status | Last Updated | Child Issues Updated |
|--------|---------|----------|--------|--------------|---------------------|
| **ROSA-86** | ROSA HCP - DR restoration improvements | 🔴 Blocker | In Progress | 2025-11-13 | ✅ 6 children updated |
| **ROSA-123** | ROSA HCP with FIPS target crypto | 🟠 Critical | In Progress | 2025-11-13 | ✅ 4 children updated |
| **ROSA-418** | ROSA HCP control plane logs forwarding M2 | 🟠 Critical | In Progress | 2025-11-14 | ✅ 6 children updated |
| **ROSA-403** | Enable EUS lifecycle for managed clusters | 🟠 Critical | In Progress | 2025-11-06 | ✅ 6 children updated |
| **ROSA-356** | Day-2 machine pool support | 🟡 Major | In Progress | 2025-11-07 | ✅ 15 children updated |
| **ROSA-96** | ROSA-HCP - Image registry mirror config | 🟠 Critical | **Closed** | 2025-11-04 | ✅ 2 children closed |
| **ROSA-431** | Installing ROSA/OSD with OCP 4.20 | 🟠 Critical | **Closed** | 2025-11-05 | ❌ No recent updates |
| **ROSA-102** | ROSA HCP: Shared VPC (GA) | 🟡 Major | Release Pending | 2025-11-06 | ❌ No recent updates |
| **ROSA-106** | FedRAMP High Billing Process | 🟡 Major | In Progress | 2025-11-13 | ❌ No recent updates |
| **ROSA-144** | ROSA HCP multiarch/Arm follow-up | 🟡 Major | In Progress | 2025-11-11 | ❌ No recent updates |
| **ROSA-183** | Self-service Platform Alerts config | 🟡 Major | In Progress | 2025-11-10 | ❌ No recent updates |
| **ROSA-182** | Enable region Thailand ap-southeast-7 | 🔵 Normal | Release Pending | 2025-11-06 | ❌ No recent updates |
| **ROSA-511** | OCM services SLOs deployment gatekeeping | 🟡 Major | In Progress | 2025-11-10 | ❌ No recent updates |

### Key Findings
- **Total ROSA Parents**: 13 tracked features
- **Active Parents with Child Updates**: 6 features (46%)
- **Recently Closed Parents**: 2 features (ROSA-96, ROSA-431)
- **Total Child Issues Updated**: 39+ issues across 6 parents
- **Highest Activity**: ROSA-356 (Machine Pool Scaling) - 15 children updated

---

## 🔴 Blocker Priority

### ROSA-86: ROSA HCP - DR Restoration Improvements
**Status**: In Progress | **Last Updated**: 2025-11-13 | **Priority**: Blocker
**Assignee**: Aaren de Jong | **Total Children**: 38 issues

#### Summary
Improve automatic CSI snapshots of etcd PVCs for ROSA HCP clusters to enable disaster recovery with RPO=1 hour, RTO≤1 hour.

#### Child Issues Updated (Last 3 Weeks): 6 issues

| Issue | Summary | Status | Updated | Change Notes |
|-------|---------|--------|---------|--------------|
| **OCM-20038** | Update Schedule to disable snapshotMoveData | **Closed** ✅ | 2025-10-31 | **RESOLVED** |
| **OCM-19826** | Synthetic Load 10-16 clusters | To Do | 2025-10-28 | Updated |
| **OCM-19825** | Synthetic Load 1-4 cluster | In Progress | 2025-11-07 | Active development |
| **OCM-19662** | Mid-sized Scalability Test - 32 clusters | **Closed** ✅ | 2025-11-07 | **RESOLVED** |
| **OCM-19595** | Custom Backup Schedule Configuration for Clusters | **Closed** ✅ | 2025-11-03 | **RESOLVED** |
| **OCM-19592** | Bypass Backup Creation During Cluster Provisioning | **Closed** ✅ | 2025-11-03 | **RESOLVED** |

#### Progress Summary
- ✅ **4 issues closed** (backup scheduling, scalability testing)
- 🔄 **1 in progress** (synthetic load testing 1-4 clusters)
- 📋 **1 to do** (synthetic load 10-16 clusters)

#### Key Achievements
- Custom backup scheduling now configurable
- Ability to bypass backup during provisioning
- Scalability testing completed for 32 clusters
- Backup snapshot configuration improvements completed

#### Remaining Work
- Complete synthetic load testing (2 tasks)
- Additional child issues not updated in last 3 weeks (32 remaining)

---

## 🟠 Critical Priority

### ROSA-123: ROSA HCP with FIPS Target Crypto
**Status**: In Progress | **Last Updated**: 2025-11-13 | **Priority**: Critical
**Total Children**: 26 issues

#### Summary
Enable FIPS (Federal Information Processing Standards) cryptographic modules for ROSA HCP to meet government compliance requirements.

#### Child Issues Updated (Last 3 Weeks): 4 issues

| Issue | Summary | Status | Assignee | Updated | Change Notes |
|-------|---------|--------|----------|---------|--------------|
| **OCM-19948** | Coordination for FIPS/ROSA-123 | In Progress | - | 2025-11-13 | Ongoing coordination |
| **OCM-18676** | [TF]: Terraform support for ROSA HCP with FIPS | New | - | 2025-11-13 | Recently updated |
| **OCM-18669** | [ROSA CLI]: CLI support for ROSA HCP with FIPS | New | - | 2025-11-13 | Recently updated |
| **OCMUI-3821** | [OCM UI]: ROSA HCP with FIPS enabled | To Do | - | 2025-11-07 | UI work planned |

#### Progress Summary
- 🔄 **1 in progress** (coordination epic)
- 📋 **3 new/to do** (Terraform, CLI, UI support)
- ⚠️ **Multi-component work**: Requires coordination across OCM, ROSA CLI, Terraform Provider, and UI

#### Key Dependencies
- FIPS enablement requires changes across all client interfaces
- Coordination epic (OCM-19948) is tracking cross-team alignment
- All three client tools (CLI, Terraform, UI) need to support FIPS configuration

#### Remaining Work
- 22 child issues not recently updated (likely backend/infrastructure work)

---

### ROSA-418: ROSA HCP Control Plane Logs Forwarding M2 (Public Preview)
**Status**: In Progress | **Last Updated**: 2025-11-14 | **Priority**: Critical
**Total Children**: 22 issues

#### Summary
Milestone 2 for forwarding ROSA HCP control plane logs to AWS CloudWatch (Public Preview).

#### Child Issues Updated (Last 3 Weeks): 6 issues

| Issue | Summary | Status | Assignee | Updated | Change Notes |
|-------|---------|--------|----------|---------|--------------|
| **OCM-19897** | Add API models, OpenAPI schema for log forwarder | **Closed** ✅ | William Kutler | 2025-11-10 | **RESOLVED** |
| **OCM-19895** | Create tenant config API client for log forwarder | **Closed** ✅ | William Kutler | 2025-11-13 | **RESOLVED** |
| **OCM-19893** | Enable log forwarder log group mapping via ConfigMap | In Progress | David Lee | 2025-11-14 | Active development |
| **OCM-19892** | Add Log Forwarder Constraints Endpoint | To Do | - | 2025-11-06 | Planned |
| **OCM-19301** | Ensure reliability for HCP Log Forwarding Client Side | To Do | - | 2025-11-15 | Recently updated |
| **OCM-19300** | HCP Log Forwarding Client Side (CLI and TF) | New | Hunter Kepley | 2025-11-14 | Recently created |

#### Progress Summary
- ✅ **2 issues closed** (API models and tenant configuration client)
- 🔄 **1 in progress** (ConfigMap-based log group mapping)
- 📋 **3 new/to do** (constraints endpoint, CLI/TF support, reliability)

#### Key Achievements
- API models and OpenAPI schemas completed
- Tenant configuration microservice client integration done
- Foundation for log forwarding infrastructure in place

#### Current Focus
- Enabling dynamic log group mappings without code changes
- Adding constraint validation for log forwarder configurations
- Building CLI and Terraform provider support

#### Remaining Work
- 16 child issues not recently updated

---

### ROSA-403: Enable EUS Lifecycle for Managed OpenShift Clusters
**Status**: In Progress | **Last Updated**: 2025-11-06 | **Priority**: Critical
**Total Children**: 25 issues

#### Summary
Enable Extended Update Support (EUS) channel lifecycle management for ROSA clusters.

#### Child Issues Updated (Last 3 Weeks): 6 issues

| Issue | Summary | Status | Updated | Change Notes |
|-------|---------|--------|---------|--------------|
| **OCMUI-3957** | Disable channel group edit icon in non-Ready states | Review | 2025-11-13 | In review |
| **OCMUI-3955** | Tooltip for EUS "Channel Group" field | **Closed** ✅ | 2025-11-12 | **RESOLVED** |
| **OCMUI-3920** | OCM UI: Verify nodepool autoscaling from zero | To Do | 2025-10-29 | Planned |
| **OCMUI-3919** | Terraform: nodepool autoscaling from zero | To Do | 2025-10-30 | Planned |
| **OCMUI-3915** | ROSA CLI: nodepool autoscaling from zero | To Do | 2025-10-30 | Planned |
| **OCMUI-3757** | Enable feature gate in production for all users | **Closed** ✅ | 2025-11-07 | **RESOLVED** ✅ |
| **OCMUI-3693** | E2E Automation: OCM UI EUS Channels | In Progress | 2025-10-31 | Active testing |
| **OCMUI-3690** | OCM UI EUS Channels | In Progress | 2025-11-11 | Active development |

#### Progress Summary
- ✅ **2 issues closed** (feature gate enabled, tooltip added)
- 🔄 **3 in progress/review** (UI work, automation)
- 📋 **3 to do** (autoscaling support across tools)

#### Key Achievements
- Feature gate enabled in production for all users (Major milestone!)
- UI tooltip improvements for better UX
- E2E automation in progress for EUS channels

#### Current Focus
- Completing UI implementation for EUS channels
- Finalizing channel group edit controls
- Building E2E test automation

#### Remaining Work
- Nodepool autoscaling from zero (separate feature, may be mis-categorized)
- 17 child issues not recently updated

---

### ROSA-96: ROSA-HCP - Image Registry Mirror Config to Customers
**Status**: **Closed** ✅ | **Last Updated**: 2025-11-04 | **Priority**: Critical
**Total Children**: 8 issues

#### Summary
Enable customers to configure image registry mirroring (IDMS) for ROSA HCP clusters.

#### Child Issues Updated (Last 3 Weeks): 2 issues

| Issue | Summary | Status | Updated | Change Notes |
|-------|---------|--------|---------|--------------|
| **OCM-19795** | Implement Terraform Modules support for Image Mirrors | **Closed** ✅ | 2025-11-04 | **RESOLVED** |
| **OCM-11211** | [OCM]: Epic for ROSA-HCP Image registry mirror config | **Closed** ✅ | 2025-11-04 | **RESOLVED** |

#### Progress Summary
- ✅ **PARENT CLOSED** on 2025-11-04
- ✅ **2 issues closed** (Terraform support, OCM epic)
- ✅ **Feature complete and delivered**

#### Key Achievements
- Terraform Modules now support image registry mirroring
- Complete OCM implementation for image mirrors
- Feature successfully closed and delivered to customers

---

### ROSA-431: Installing New ROSA & OSD Cluster with OCP 4.20
**Status**: **Closed** ✅ | **Last Updated**: 2025-11-05 | **Priority**: Critical
**Total Children**: 36 issues (all OSD project)

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Progress Summary
- ✅ **PARENT CLOSED** on 2025-11-05
- ❌ **No child issues updated in last 3 weeks**
- ℹ️ All child issues (OSD-30964 through OSD-31009) have not been updated since August 2025

#### Status
- Feature appears to be closed/completed
- Child issues may be stale or tracking legacy work
- No recent activity suggests work is complete or deprioritized

---

## 🟡 Major Priority

### ROSA-356: Day-2 Machine Pool Support (Technical Enablement)
**Status**: In Progress | **Last Updated**: 2025-11-07 | **Priority**: Major
**Total Children**: 18 issues

#### Summary
Enable machine pool scaling features including autoscaling from zero replicas for ROSA clusters.

#### Child Issues Updated (Last 3 Weeks): 15 issues

| Issue | Summary | Status | Updated | Change Notes |
|-------|---------|--------|---------|--------------|
| **OCM-19963** | CI Integration for Machine Pool Scaling (GA) | To Do | 2025-10-29 | Planned |
| **OCM-19962** | E2E Tests Automation for Machine Pool Scaling (GA) | To Do | 2025-10-29 | Planned |
| **OCM-19961** | Functional Tests for Machine Pool Scaling (GA) | To Do | 2025-10-29 | Planned |
| **OCM-19960** | Test Plan for Machine Pool Scaling (GA) | To Do | 2025-10-29 | Planned |
| **OCM-19959** | Feature toggle maintenance: Machine Pool Scaling (GA) | To Do | 2025-10-29 | Planned |
| **OCM-19958** | Ensure reliability for Machine Pool Scaling (GA) | To Do | 2025-10-29 | Planned |
| **OCM-19957** | CLI, Terraform and UI Enhancements | **Closed** ✅ | 2025-11-03 | **RESOLVED** |
| **OCM-19956** | CI Integration for Machine Pool Scaling (Preview) | To Do | 2025-10-29 | Planned |
| **OCM-19955** | E2E Tests Automation for Machine Pool Scaling (Preview) | To Do | 2025-10-29 | Planned |
| **OCM-19954** | Functional Tests for Machine Pool Scaling (Preview) | To Do | 2025-10-29 | Planned |
| **OCM-19953** | Test Plan for Machine Pool Scaling (Preview) | To Do | 2025-10-29 | Planned |
| **OCM-19952** | Feature toggle maintenance: Machine Pool Scaling (Preview) | To Do | 2025-10-29 | Planned |
| **OCM-19951** | Ensure reliability for Machine Pool Scaling (Preview) | To Do | 2025-10-29 | Planned |
| **OCM-19950** | API and CAPA Enhancements | In Progress | 2025-11-07 | Active development |
| **OCM-19652** | OCM API: Support min-replicas=0 with autoscaling | In Progress | 2025-11-04 | Active development |

#### Progress Summary
- ✅ **1 issue closed** (CLI, Terraform, UI enhancements)
- 🔄 **2 in progress** (API/CAPA enhancements, min-replicas=0 support)
- 📋 **12 to do** (test plans, automation, feature toggles for both Preview and GA)

#### Key Achievements
- Client tool enhancements (CLI, TF, UI) completed
- Core API and infrastructure work in progress

#### Current Focus
- Building API and CAPA (Cluster API Provider AWS) enhancements
- Implementing min-replicas=0 autoscaling support
- Preparing for both Public Preview and GA releases

#### Two-Phase Rollout
- **Public Preview**: 6 tasks (testing, CI, feature toggles)
- **GA Release**: 6 tasks (testing, CI, feature toggles)

#### Remaining Work
- Complete API/CAPA enhancements
- Execute comprehensive test plans for both phases
- Configure feature toggles and CI integration

---

### ROSA-102: ROSA HCP - Shared VPC (GA)
**Status**: Release Pending | **Last Updated**: 2025-11-06 | **Priority**: Major
**Total Children**: 3 issues

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Status
- Parent in "Release Pending" state
- No child issues updated recently
- Likely waiting for final release approval

---

### ROSA-106: (FedRAMP High) Billing Process & Data from ROSA GovCloud
**Status**: In Progress | **Last Updated**: 2025-11-13 | **Priority**: Major
**Total Children**: 6 issues

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Status
- Parent recently updated (2025-11-13)
- No child issues updated in last 3 weeks
- May be in planning or blocked state

---

### ROSA-144: ROSA HCP Multiarch/Arm Follow-up Components
**Status**: In Progress | **Last Updated**: 2025-11-11 | **Priority**: Major
**Total Children**: 1 issue

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Status
- Parent recently updated (2025-11-11)
- Single child issue (OSD-23547) not updated recently

---

### ROSA-183: ROSA HCP M2 - Self-service Config of Platform Alerts
**Status**: In Progress | **Last Updated**: 2025-11-10 | **Priority**: Major
**Total Children**: 5 issues

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Status
- Parent recently updated (2025-11-10)
- No child issues updated in last 3 weeks

---

### ROSA-511: OCM Services SLOs Deployment Gatekeeping
**Status**: In Progress | **Last Updated**: 2025-11-10 | **Priority**: Major
**Total Children**: 2 issues

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Status
- Parent recently updated (2025-11-10)
- No child issues updated in last 3 weeks

---

## 🔵 Normal Priority

### ROSA-182: Enable Region - Thailand ap-southeast-7
**Status**: Release Pending | **Last Updated**: 2025-11-06 | **Priority**: Normal
**Total Children**: 1 issue

#### Child Issues Updated (Last 3 Weeks): 0 issues

#### Status
- Parent in "Release Pending" state
- Waiting for final release

---

## Summary Statistics

### Overall Activity
| Metric | Count |
|--------|-------|
| Total ROSA Parent Features | 13 |
| Parents with Recent Updates | 13 (100%) |
| Parents with Active Child Work | 6 (46%) |
| Recently Closed Parents | 2 (15%) |
| Total Child Issues Tracked | 191 |
| Child Issues Updated (Last 3 Weeks) | 39 (20%) |
| Child Issues Closed (Last 3 Weeks) | 12 (6%) |

### By Priority
| Priority | Total | Active | Closed | Release Pending |
|----------|-------|--------|--------|-----------------|
| Blocker | 1 | 1 | 0 | 0 |
| Critical | 5 | 3 | 2 | 0 |
| Major | 7 | 5 | 0 | 2 |
| Normal | 1 | 0 | 0 | 1 |

### Top Active Features (by child updates)
1. **ROSA-356** (Machine Pool Scaling): 15 children updated
2. **ROSA-418** (Log Forwarding): 6 children updated
3. **ROSA-86** (DR Restoration): 6 children updated
4. **ROSA-403** (EUS Lifecycle): 6 children updated
5. **ROSA-123** (FIPS): 4 children updated

### Recent Completions
- **ROSA-96**: Image Registry Mirroring (Closed 2025-11-04) ✅
- **ROSA-431**: OCP 4.20 Installation (Closed 2025-11-05) ✅

---

## Key Trends & Observations

### 1. **High Velocity Features**
- **ROSA-418** (Log Forwarding): 2 major completions, active development on ConfigMap support
- **ROSA-356** (Machine Pool Scaling): Largest update volume, dual-phase rollout (Preview → GA)
- **ROSA-86** (DR/Backup): 4 completions in 3 weeks, strong progress on backup capabilities

### 2. **Multi-Component Coordination**
- **ROSA-123** (FIPS): Requires parallel work across CLI, Terraform, UI, and backend
- **ROSA-418** (Log Forwarding): Backend APIs complete, moving to client tools
- **ROSA-403** (EUS): Feature gate enabled in production - major milestone!

### 3. **Feature Completions**
- **ROSA-96**: Successfully delivered image registry mirroring to customers
- **ROSA-431**: OCP 4.20 installation support completed

### 4. **Testing & Quality Focus**
- ROSA-356 has comprehensive test planning (12 test-related tasks across Preview and GA)
- E2E automation ongoing for EUS channels (ROSA-403)
- Scalability testing completed for ROSA-86 (32 clusters tested)

### 5. **Release Pipeline**
- Multiple features in "Release Pending" state (ROSA-102, ROSA-182)
- Suggests active release management and staging

---

## Recommendations

### Immediate Actions
1. **ROSA-123 (FIPS)**: Monitor coordination epic OCM-19948 - all client tools need alignment
2. **ROSA-356 (Machine Pool)**: Focus on completing API/CAPA work to unblock testing phase
3. **ROSA-418 (Log Forwarding)**: Track OCM-19893 (ConfigMap mapping) - last piece before client tools

### Follow-up Required
4. **ROSA-431**: Investigate 36 stale OSD child issues (no updates since August)
5. **ROSA-106, 144, 183, 511**: Parents updated but no child activity - verify work status
6. **ROSA-102**: Release pending - confirm release timeline

### Success Stories to Highlight
7. **ROSA-403**: Feature gate enabled in production - ready for customers
8. **ROSA-96**: Complete delivery of image registry mirroring
9. **ROSA-86**: Strong backup/DR progress with 4 completions

---

## Next Review Actions

1. Review ROSA-431 child issues - determine if they should be closed
2. Verify ROSA-102 and ROSA-182 release dates
3. Check blocking issues for ROSA-106, 144, 183, 511 (no child activity)
4. Monitor ROSA-356 for test execution (moving from Preview to GA)
5. Track ROSA-418 ConfigMap work to completion
6. Confirm ROSA-123 cross-team coordination timeline

---

*Generated using Jira CLI connected to Red Hat Jira (https://issues.redhat.com)*
*Source data: ROSA Non-Closed Children Report*
