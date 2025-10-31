# ROSA Features - Non-Closed Immediate Children Report (with Sprint Info)

**Generated:** 2025-10-31 00:05:46

## Summary

This report shows all **non-closed** immediate children (childOf relationship) for ROSA features with status: In Progress, Review, or Release Pending.

**Active Sprint information is included for issues with "In Progress" status.**

**Filters Applied:**
- Only immediate children (no descendants)
- Excludes issues with status = Closed
- Queried across specified Jira projects

**Results:**
- **Total ROSA Features:** 12
- **Total Non-Closed Child Issues:** 170
- **Projects Represented:** 6

### Children Count by Feature:
- **ROSA-86** (Blocker): 38 non-closed children
- **ROSA-123** (Critical): 26 non-closed children
- **ROSA-198** (Critical): 30 non-closed children
- **ROSA-403** (Critical): 25 non-closed children
- **ROSA-418** (Critical): 22 non-closed children
- **ROSA-96** (Critical): 8 non-closed children
- **ROSA-102** (Major): 3 non-closed children
- **ROSA-106** (Major): 6 non-closed children
- **ROSA-144** (Major): 1 non-closed children
- **ROSA-179** (Major): 5 non-closed children
- **ROSA-183** (Major): 5 non-closed children
- **ROSA-182** (Normal): 1 non-closed children

### Children Count by Project:
- **ACM**: 3 issues
- **OCM**: 129 issues
- **OCMUI**: 16 issues
- **OSD**: 2 issues
- **OSDOCS**: 11 issues
- **SLSRE**: 9 issues

---

## Features by Priority


### 🔴 Blocker Priority

#### [ROSA-86](https://issues.redhat.com/browse/ROSA-86): ROSA HCP - DR restoration improvements

**38 Non-Closed Child Issues**

<details>
<summary>ACM Project (2 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [ACM-24861](https://issues.redhat.com/browse/ACM-24861) | Feature | Resolved | - | Mehmet Pekpergel | Alerts for DR account reconciliation | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-01 | 2025-10-03 |  |
| [ACM-20793](https://issues.redhat.com/browse/ACM-20793) | Story | Resolved | - | Mehmet Pekpergel | as an operator of FM, existing management clusters will also have DR A | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-14 | 2025-10-24 |  |

</details>

<details>
<summary>OCM Project (26 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-20038](https://issues.redhat.com/browse/OCM-20038) | Task | In Progress | - | Eric Cambel | Update Schedule to disable snapshotMoveData | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-30 | 2025-10-30 |  |
| [OCM-19826](https://issues.redhat.com/browse/OCM-19826) | Task | To Do | - | Synthetic Load 10-16 clusters | 2025-10-27 14:45:38 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-28 |  |  |
| [OCM-19825](https://issues.redhat.com/browse/OCM-19825) | Task | To Do | - | Synthetic Load 1-4 cluster | 2025-10-27 14:45:12 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-28 |  |  |
| [OCM-19662](https://issues.redhat.com/browse/OCM-19662) | Task | In Progress | ROSA-Operators-1 | Eric Cambel | Mid-sized Scalability Test - 32 clusters | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-23 | 2025-10-27 |  |
| [OCM-19649](https://issues.redhat.com/browse/OCM-19649) | Story | To Do | - | Lucas Ponce | Capture backup dependencies versions in hcm-deployment snapshot | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-23 | 2025-10-23 |  |
| [OCM-19595](https://issues.redhat.com/browse/OCM-19595) | Task | Review | - | Guilherme Branco | Custom Backup Schedule Configuration for Clusters | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-22 | 2025-10-30 |  |
| [OCM-19592](https://issues.redhat.com/browse/OCM-19592) | Task | Review | - | Guilherme Branco | Bypass Backup Creation During Cluster Provisioning | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-22 | 2025-10-30 |  |
| [OCM-18502](https://issues.redhat.com/browse/OCM-18502) | Task | In Progress | ROSA-Operators-1 | Lawton Mizell | Evaluate the impact of cluster upgrades in the backups (and vice versa | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 | 2025-10-27 |  |
| [OCM-18398](https://issues.redhat.com/browse/OCM-18398) | Story | To Do | - | Velero Backup Timing Analysis | 2025-09-11 16:08:25 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18397](https://issues.redhat.com/browse/OCM-18397) | Story | To Do | - | Velero Resource Utilization Monitoring | 2025-09-11 16:07:38 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18396](https://issues.redhat.com/browse/OCM-18396) | Story | To Do | - | Core Velero Backup Metrics Collection | 2025-09-11 16:06:37 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18365](https://issues.redhat.com/browse/OCM-18365) | Task | To Do | - | Benchmark ROSA HCP Backup speeds using multiple workers | 2025-09-08 17:10:53 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-17510](https://issues.redhat.com/browse/OCM-17510) | Task | In Progress | Service Development - Sprint 6 | Eric Cambel | Create a scalability testing plan | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-07-31 | 2025-10-27 |  |
| [OCM-17454](https://issues.redhat.com/browse/OCM-17454) | Epic | In Progress | - | Eric Cambel | OADP + Velero Scalability Tests for ROSA HCP | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-07-29 | 2025-10-30 |  |
| [OCM-16136](https://issues.redhat.com/browse/OCM-16136) | Risk | To Do | - | No Prometheus metrics for Kopia uploads | 2025-06-02 10:09:12 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-16135](https://issues.redhat.com/browse/OCM-16135) | Risk | To Do | - | Unable to use enable S3 Bucket Keys with OADP/Velero | 2025-06-02 09:58:50 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-16134](https://issues.redhat.com/browse/OCM-16134) | Risk | To Do | - | Backup objects created by Kopia are not tagged in S3 | 2025-06-02 09:52:32 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-15906](https://issues.redhat.com/browse/OCM-15906) | Task | To Do | - | Define process to rotate KMS Keys used to encrypt backups | 2025-05-21 08:49:55 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-29 |  |  |
| [OCM-15776](https://issues.redhat.com/browse/OCM-15776) | Story | In Progress | ROSA-Operators-1 | Elveera Mathias | E2E Tests Automation for Clusters Service requirements for ROSA HCP Ba | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-10-27 |  |
| [OCM-15775](https://issues.redhat.com/browse/OCM-15775) | Story | In Progress | ROSA-Operators-1 | Elveera Mathias | Functional Tests for Clusters Service requirements for ROSA HCP Backup | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-10-27 |  |
| [OCM-15774](https://issues.redhat.com/browse/OCM-15774) | Story | In Progress | Service Development - Sprint 7 | Elveera Mathias | Test Plan for Clusters Service requirements for ROSA HCP Backup and Re | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-10-27 |  |
| [OCM-15773](https://issues.redhat.com/browse/OCM-15773) | Story | To Do | - | Feature toggle maintenance: Clusters Service requirements for ROSA HCP Backup and Restore | 2025-05-13 10:41:13 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-15771](https://issues.redhat.com/browse/OCM-15771) | Epic | In Progress | - | Lucas Ponce | Clusters Service requirements for ROSA HCP Backup and Restore | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-10-23 |  |
| [OCM-15599](https://issues.redhat.com/browse/OCM-15599) | Story | To Do | - | Spike Restoration Flow for etcd specific failures and test node re-adoption | 2025-05-01 14:42:26 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-14679](https://issues.redhat.com/browse/OCM-14679) | Task | To Do | - | Spike restoration flow | 2025-03-17 15:44:20 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-29 |  |  |
| [OCM-13195](https://issues.redhat.com/browse/OCM-13195) | Epic | In Progress | - | Lucas Ponce | ROSA HCP - DR restoration improvements - Research/Refinement | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2024-12-19 | 2025-10-03 |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12727](https://issues.redhat.com/browse/OSDOCS-12727) | Epic | New | - | Ryan Deussing | docs for cluster backup & restore | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2024-11-20 | 2025-09-10 |  |

</details>

<details>
<summary>SLSRE Project (9 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [SLSRE-382](https://issues.redhat.com/browse/SLSRE-382) | Story | New | - | Review metrics to capture during Perf/Scale testing | 2025-09-16 11:03:47 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-381](https://issues.redhat.com/browse/SLSRE-381) | Story | New | - | Review Test Plan | 2025-09-16 11:00:40 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-380](https://issues.redhat.com/browse/SLSRE-380) | Story | New | - | Define alerts for AWS Quota and Resource utilization in the Backup Account | 2025-09-16 10:58:29 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-374](https://issues.redhat.com/browse/SLSRE-374) | Epic | In Progress | - | Sergio Lopez | ROSA HCP - Backup Reliability | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 | 2025-09-16 |  |
| [SLSRE-377](https://issues.redhat.com/browse/SLSRE-377) | Story | To Do | - | Monitor DataUpload and BackUp CRs for backup data upload verification | 2025-06-02 15:50:17 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-378](https://issues.redhat.com/browse/SLSRE-378) | Story | To Do | - | Implement Alerting Rules | 2025-06-02 13:10:14 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-379](https://issues.redhat.com/browse/SLSRE-379) | Story | To Do | - | Build Dashboards for Backup Visibility | 2025-06-02 13:09:20 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-376](https://issues.redhat.com/browse/SLSRE-376) | Story | In Progress | OCM-Reliability-276 | Integrate Backup Metrics into Monitoring Platform | 2025-06-02 13:07:11 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-30 |  |  |
| [SLSRE-375](https://issues.redhat.com/browse/SLSRE-375) | Story | In Progress | OCM-Reliability-276 | Sergio Lopez | Define Backup Monitoring Metrics | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-06-02 | 2025-10-28 |  |

</details>

---


### 🟠 Critical Priority

#### [ROSA-123](https://issues.redhat.com/browse/ROSA-123): ROSA HCP with FIPS target crypto

**26 Non-Closed Child Issues**

<details>
<summary>ACM Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [ACM-24746](https://issues.redhat.com/browse/ACM-24746) | Epic | New | - | Mohamed ElSerngawy | [CAPA]: Epic for ROSA-123 - CAPA support for ROSA HCP with FIPS enable | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 | 2025-10-10 |  |

</details>

<details>
<summary>OCM Project (23 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-19948](https://issues.redhat.com/browse/OCM-19948) | Story | To Do | - | Idit Gavra | Coordination fot FIPS/ROSA-123 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-29 | 2025-10-29 |  |
| [OCM-18682](https://issues.redhat.com/browse/OCM-18682) | Story | To Do | - | CI Integration for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:56 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18681](https://issues.redhat.com/browse/OCM-18681) | Story | To Do | - | E2E Tests Automation for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:53 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18680](https://issues.redhat.com/browse/OCM-18680) | Story | To Do | - | Functional Tests for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:51 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18679](https://issues.redhat.com/browse/OCM-18679) | Story | To Do | - | Test Plan for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:49 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18678](https://issues.redhat.com/browse/OCM-18678) | Story | To Do | - | Feature toggle maintenance: [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:45 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18677](https://issues.redhat.com/browse/OCM-18677) | Story | To Do | - | Ensure reliability for epic [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:42 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |
| [OCM-18676](https://issues.redhat.com/browse/OCM-18676) | Epic | New | - | Hunter Kepley | [TF]: Epic for ROSA-123 - Terraform support for ROSA HCP with FIPS ena | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 | 2025-10-22 |  |
| [OCM-18675](https://issues.redhat.com/browse/OCM-18675) | Story | To Do | - | CI Integration for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:23 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18674](https://issues.redhat.com/browse/OCM-18674) | Story | To Do | - | E2E Tests Automation for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers  | 2025-09-28 07:28:21 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18673](https://issues.redhat.com/browse/OCM-18673) | Story | To Do | - | Functional Tests for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:18 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18672](https://issues.redhat.com/browse/OCM-18672) | Story | To Do | - | Test Plan for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:16 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18671](https://issues.redhat.com/browse/OCM-18671) | Story | To Do | - | Feature toggle maintenance: [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:13 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18670](https://issues.redhat.com/browse/OCM-18670) | Story | To Do | - | Ensure reliability for epic: [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:09 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |
| [OCM-18669](https://issues.redhat.com/browse/OCM-18669) | Epic | New | - | Hunter Kepley | [ROSA CLI]: Epic for ROSA-123 - ROSA CLI support for ROSA HCP with FIP | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 | 2025-10-22 |  |
| [OCM-18059](https://issues.redhat.com/browse/OCM-18059) | Story | Review | - | Idit Gavra | Verify that FIPS is enabled and all components are ok | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-08-28 | 2025-10-29 |  |
| [OCM-17197](https://issues.redhat.com/browse/OCM-17197) | Story | To Do | - | CI Integration for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | 2025-07-16 11:40:31 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 |  |  |
| [OCM-17196](https://issues.redhat.com/browse/OCM-17196) | Story | To Do | - | Jeff Frazier | E2E Tests Automation for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with  | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-09-16 |  |
| [OCM-17195](https://issues.redhat.com/browse/OCM-17195) | Story | To Do | - | Jeff Frazier | Functional Tests for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-09-16 |  |
| [OCM-17194](https://issues.redhat.com/browse/OCM-17194) | Story | To Do | - | Jeff Frazier | Test Plan for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-09-16 |  |
| [OCM-17193](https://issues.redhat.com/browse/OCM-17193) | Story | To Do | - | Feature toggle maintenance: [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | 2025-07-16 11:40:20 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-30 |  |  |
| [OCM-17192](https://issues.redhat.com/browse/OCM-17192) | Story | To Do | - | Ensure reliability for epic [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | 2025-07-16 11:40:17 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |
| [OCM-17191](https://issues.redhat.com/browse/OCM-17191) | Epic | In Progress | - | Idit Gavra | [OCM]: Epic for ROSA-123 - ROSA HCP with FIPS target crypto | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-10-29 |  |

</details>

<details>
<summary>OCMUI Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-3821](https://issues.redhat.com/browse/OCMUI-3821) | Story | To Do | - | [ROSA-HCP] OCM UI- ROSA HCP with FIPS enabled | 2025-09-28 10:59:29 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-27 |  |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-16476](https://issues.redhat.com/browse/OSDOCS-16476) | Epic | New | - | [DOCS]: Epic for ROSA-123 - Document support for ROSA HCP with FIPS | 2025-10-10 04:58:38 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |

</details>

---

#### [ROSA-198](https://issues.redhat.com/browse/ROSA-198): ROSA-HCP support Windows LI for CNV - GA

**30 Non-Closed Child Issues**

<details>
<summary>OCM Project (22 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-19949](https://issues.redhat.com/browse/OCM-19949) | Story | In Progress | ROSA Focaccia Sprint 3 | Brae Troutman | Update Cloud Resource ConfigMaps in AppInterface with WinLI Feature Su | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-29 | 2025-10-29 |  |
| [OCM-18768](https://issues.redhat.com/browse/OCM-18768) | Story | To Do | - | Brae Troutman | Update Instance Type Cloud Resources Spreadsheet and OCM CSV Parser wi | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-01 | 2025-10-30 |  |
| [OCM-18705](https://issues.redhat.com/browse/OCM-18705) | Story | To Do | - | Brae Troutman | Map updated OCM API ImageType fields to hypershift resources in CS | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-09-30 | 2025-10-29 |  |
| [OCM-18568](https://issues.redhat.com/browse/OCM-18568) | Story | Code Review | - | Brae Troutman | Expose new image type for Node Pools in Hypershift | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-09-22 | 2025-10-29 |  |
| [OCM-14669](https://issues.redhat.com/browse/OCM-14669) | Story | Code Review | - | Brae Troutman | Implement Instance Type OCM GA API changes for Windows LI | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-03-17 | 2025-10-30 |  |
| [OCM-14668](https://issues.redhat.com/browse/OCM-14668) | Story | In Progress | ROSA Focaccia Sprint 3 | Brae Troutman | Expose Instance Type API changes for GA in the model and SDK | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-03-17 | 2025-10-30 |  |
| [OCM-13507](https://issues.redhat.com/browse/OCM-13507) | Story | To Do | - | Brae Troutman | Validate user input when updating machine type | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-01-21 | 2025-10-30 |  |
| [OCM-12655](https://issues.redhat.com/browse/OCM-12655) | Story | To Do | - | E2E Automation: [OCM]: Epic for XCMSTRAT-1066 - Terraform support for Windows LI | 2024-11-19 08:50:21 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-06-14 |  |  |
| [OCM-12654](https://issues.redhat.com/browse/OCM-12654) | Story | To Do | - | CI Automation: [OCM]: Epic for XCMSTRAT-1066 - Terraform support for Windows LI | 2024-11-19 08:50:19 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-06-14 |  |  |
| [OCM-12653](https://issues.redhat.com/browse/OCM-12653) | Story | To Do | - | Post-merge testing: [OCM]: Epic for XCMSTRAT-1066 - Terraform support for Windows LI | 2024-11-19 08:50:18 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-06-14 |  |  |
| [OCM-12652](https://issues.redhat.com/browse/OCM-12652) | Epic | New | - | [OCM]: Epic for XCMSTRAT-1066 - Terraform support for Windows LI | 2024-11-19 08:50:15 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-06-14 |  |  |
| [OCM-12651](https://issues.redhat.com/browse/OCM-12651) | Story | To Do | - | E2E Automation: [OCM]: Epic for XCMSTRAT-1066 - ROSA CLI support for Windows LI | 2024-11-19 08:48:18 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-30 |  |  |
| [OCM-12650](https://issues.redhat.com/browse/OCM-12650) | Story | To Do | - | CI Automation: [OCM]: Epic for XCMSTRAT-1066 - ROSA CLI support for Windows LI | 2024-11-19 08:48:17 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-30 |  |  |
| [OCM-12649](https://issues.redhat.com/browse/OCM-12649) | Story | To Do | - | Post-merge testing: [OCM]: Epic for XCMSTRAT-1066 - ROSA CLI support for Windows LI | 2024-11-19 08:48:15 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-30 |  |  |
| [OCM-12648](https://issues.redhat.com/browse/OCM-12648) | Epic | New | - | Hunter Kepley | [OCM]: Epic for XCMSTRAT-1066 - ROSA CLI support for Windows LI | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-19 | 2025-10-30 |  |
| [OCM-12645](https://issues.redhat.com/browse/OCM-12645) | Story | In Progress | ROSA Focaccia Sprint 3 | Implement Node Pool OCM GA API changes for Windows LI | 2024-11-19 08:40:51 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-29 |  |  |
| [OCM-12644](https://issues.redhat.com/browse/OCM-12644) | Story | In Progress | ROSA Focaccia Sprint 3 | Brae Troutman | Expose Node Pool API changes for GA in the model and SDK | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-19 | 2025-10-30 |  |
| [OCM-12417](https://issues.redhat.com/browse/OCM-12417) | Story | To Do | - | Brae Troutman | Improve metrics for node pool readiness | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-08 | 2025-09-24 |  |
| [OCM-12416](https://issues.redhat.com/browse/OCM-12416) | Story | To Do | - | Aadarsh Raj | E2E Automation: [OCM]: Epic for XCMSTRAT-1066 - ROSA-HCP support Windo | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-08 | 2025-10-29 |  |
| [OCM-12415](https://issues.redhat.com/browse/OCM-12415) | Story | To Do | - | CI Automation: [OCM]: Epic for XCMSTRAT-1066 - ROSA-HCP support Windows LI - GA | 2024-11-08 04:40:33 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-10-21 |  |  |
| [OCM-12414](https://issues.redhat.com/browse/OCM-12414) | Story | To Do | - | Post-merge testing: [OCM]: Epic for XCMSTRAT-1066 - ROSA-HCP support Windows LI - GA | 2024-11-08 04:40:32 | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-05-30 |  |  |
| [OCM-12413](https://issues.redhat.com/browse/OCM-12413) | Epic | In Progress | - | Brae Troutman | [OCM]: Epic for XCMSTRAT-1066 - ROSA-HCP support Windows LI - GA | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-08 | 2025-10-29 |  |

</details>

<details>
<summary>OCMUI Project (6 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-2907](https://issues.redhat.com/browse/OCMUI-2907) | Story | To Do | - | Lior Keren | [ROSA-HCP] Windows LI Phase 3: Remove Feature Flag | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-01-13 | 2025-10-01 |  |
| [OCMUI-2906](https://issues.redhat.com/browse/OCMUI-2906) | Story | To Do | - | Lior Keren | [ROSA-HCP] Windows LI Phase 2: Use Official Red Hat Documentation | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-01-13 | 2025-10-01 |  |
| [OCMUI-2905](https://issues.redhat.com/browse/OCMUI-2905) | Story | To Do | - | Lior Keren | [ROSA-HCP] Windows LI Phase 2: Use Backend API Quieries | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2025-01-13 | 2025-10-28 |  |
| [OCMUI-2705](https://issues.redhat.com/browse/OCMUI-2705) | Story | To Do | - | Denis Ragan | E2E Automation: ROSA-HCP support Windows LI for CNV - GA | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-20 | 2025-09-09 |  |
| [OCMUI-2703](https://issues.redhat.com/browse/OCMUI-2703) | Story | To Do | - | Denis Ragan | Post-merge testing: ROSA-HCP support Windows LI for CNV - GA | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-20 | 2025-09-09 |  |
| [OCMUI-2702](https://issues.redhat.com/browse/OCMUI-2702) | Epic | In Progress | - | Lior Keren | [ROSA-HCP] OCM UI support Windows LI for CNV - GA | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-20 | 2025-10-28 |  |

</details>

<details>
<summary>OSDOCS Project (2 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12593](https://issues.redhat.com/browse/OSDOCS-12593) | Story | In Progress | SD OSDOCS Sprint 263 | Aedin Collins | ROSA-HCP support Windows LI for CNV - GA | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-11-07 | 2025-10-27 |  |
| [OSDOCS-12268](https://issues.redhat.com/browse/OSDOCS-12268) | Epic | In Progress | - | Aedin Collins | [MOS Docs]: Epic for XCMSTRAT-1066 - ROSA-HCP support Windows LI | [ROSA-198](https://issues.redhat.com/browse/ROSA-198) | 2024-10-04 | 2025-07-11 |  |

</details>

---

#### [ROSA-403](https://issues.redhat.com/browse/ROSA-403): Enable EUS lifecycle for managed OpenShift clusters

**25 Non-Closed Child Issues**

<details>
<summary>OCM Project (18 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-18499](https://issues.redhat.com/browse/OCM-18499) | Story | In Progress | ROSA Focaccia Sprint 2 | Patrick Jennings | Enable EUS channel group in FedRAMP | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 | 2025-10-30 |  |
| [OCM-18497](https://issues.redhat.com/browse/OCM-18497) | Story | To Do | - | CI Integration for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:33 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18496](https://issues.redhat.com/browse/OCM-18496) | Story | To Do | - | E2E Tests Automation for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:30 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18495](https://issues.redhat.com/browse/OCM-18495) | Story | To Do | - | Functional Tests for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:27 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18494](https://issues.redhat.com/browse/OCM-18494) | Story | To Do | - | Test Plan for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:24 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18493](https://issues.redhat.com/browse/OCM-18493) | Story | To Do | - | Feature toggle maintenance: [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:18 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18492](https://issues.redhat.com/browse/OCM-18492) | Story | To Do | - | Ensure reliability for epic [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:12 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18491](https://issues.redhat.com/browse/OCM-18491) | Epic | In Progress | - | Patrick Jennings | [OCM CS] Enable EUS channel group in FedRAMP | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 | 2025-10-28 |  |
| [OCM-17743](https://issues.redhat.com/browse/OCM-17743) | Story | To Do | - | CI Integration for [TF]: Terraform EUS channel support | 2025-08-18 06:09:48 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17742](https://issues.redhat.com/browse/OCM-17742) | Story | To Do | - | E2E Tests Automation for [TF]: Terraform EUS channel support | 2025-08-18 06:09:46 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17741](https://issues.redhat.com/browse/OCM-17741) | Story | To Do | - | Functional Tests for [TF]: Terraform EUS channel support | 2025-08-18 06:09:43 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17740](https://issues.redhat.com/browse/OCM-17740) | Story | To Do | - | Test Plan for [TF]: Terraform EUS channel support | 2025-08-18 06:09:40 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17739](https://issues.redhat.com/browse/OCM-17739) | Story | To Do | - | Feature toggle maintenance: [TF]: Terraform EUS channel support | 2025-08-18 06:09:36 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17738](https://issues.redhat.com/browse/OCM-17738) | Story | To Do | - | Ensure reliability for epic [TF]: Terraform EUS channel support | 2025-08-18 06:09:32 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-15074](https://issues.redhat.com/browse/OCM-15074) | Story | To Do | - | CI Integration for [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:16 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-15072](https://issues.redhat.com/browse/OCM-15072) | Story | To Do | - | Functional Tests for [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:11 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-15071](https://issues.redhat.com/browse/OCM-15071) | Story | To Do | - | Test Plan for [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:09 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-15070](https://issues.redhat.com/browse/OCM-15070) | Story | To Do | - | Ensure reliability for epic [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:04 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |

</details>

<details>
<summary>OCMUI Project (5 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-3957](https://issues.redhat.com/browse/OCMUI-3957) | Task | To Do | - | Disable the channel group edit icon when the cluster is in other states other than Ready status | 2025-10-27 22:49:06 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-10-30 |  |  |
| [OCMUI-3955](https://issues.redhat.com/browse/OCMUI-3955) | Story | In Progress | OCMUI Team Sprint 279 | Dylan Cooper | Tooltip for EUS Channel Group field | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-10-27 | 2025-10-29 |  |
| [OCMUI-3757](https://issues.redhat.com/browse/OCMUI-3757) | Task | To Do | - | Enable feature gate in production for all users | 2025-09-10 11:42:55 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-15 |  |  |
| [OCMUI-3693](https://issues.redhat.com/browse/OCMUI-3693) | Story | To Do | - | LAKSHMI SHIVANTHI AMARACHINTHA | E2E Automation: OCM UI EUS Channels | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 | 2025-10-29 |  |
| [OCMUI-3690](https://issues.redhat.com/browse/OCMUI-3690) | Epic | In Progress | - | Dylan Cooper | OCM UI EUS Channels | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 | 2025-10-29 |  |

</details>

<details>
<summary>OSDOCS Project (2 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-16538](https://issues.redhat.com/browse/OSDOCS-16538) | Story | In Progress | SD OSDOCS Sprint 279 | Aedin Collins | Life Cycle (Extension) (UI for OSD and ROSA) | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-10-15 | 2025-10-30 |  |
| [OSDOCS-11705](https://issues.redhat.com/browse/OSDOCS-11705) | Epic | In Progress | - | Ryan Deussing | Revised ROSA Life Cycle (Extension) | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2024-08-14 | 2025-10-28 |  |

</details>

---

#### [ROSA-418](https://issues.redhat.com/browse/ROSA-418): ROSA HCP control plane logs forwarding to cloudwatch M2 (public preview)

**22 Non-Closed Child Issues**

<details>
<summary>OCM Project (22 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-19897](https://issues.redhat.com/browse/OCM-19897) | Story | To Do | - | Add API models, OpenAPI schema definitions, and SDK generation support for log forwarder endpoints | 2025-10-28 13:01:05 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-29 |  |  |
| [OCM-19895](https://issues.redhat.com/browse/OCM-19895) | Story | To Do | - | Create a tenant configuration API client to communicate with the tenant configuration microservice for managing log forwarder resources | 2025-10-28 12:55:52 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-29 |  |  |
| [OCM-19893](https://issues.redhat.com/browse/OCM-19893) | Story | To Do | - | Enable configuration of log forwarder log group to application mappings through a ConfigMap, allowing mapping updates without code changes | 2025-10-28 12:45:55 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-29 |  |  |
| [OCM-19892](https://issues.redhat.com/browse/OCM-19892) | Story | To Do | - | Add Log Forwarder Constraints Endpoint | 2025-10-28 12:40:21 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-29 |  |  |
| [OCM-19306](https://issues.redhat.com/browse/OCM-19306) | Story | To Do | - | CI Integration for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:28 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19305](https://issues.redhat.com/browse/OCM-19305) | Story | To Do | - | E2E Tests Automation for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:26 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19304](https://issues.redhat.com/browse/OCM-19304) | Story | To Do | - | Functional Tests for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:24 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19303](https://issues.redhat.com/browse/OCM-19303) | Story | To Do | - | Test Plan for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:21 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19302](https://issues.redhat.com/browse/OCM-19302) | Story | To Do | - | Feature toggle maintenance: HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:17 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19301](https://issues.redhat.com/browse/OCM-19301) | Story | To Do | - | Ensure reliability for epic HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:13 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19300](https://issues.redhat.com/browse/OCM-19300) | Epic | New | - | Carl Brumm | HCP Log Forwarding Client Side(CLI and TF) | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 | 2025-10-21 |  |
| [OCM-18907](https://issues.redhat.com/browse/OCM-18907) | Story | To Do | - | Document process for changing allowed log forwarding pods | 2025-10-13 12:19:21 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-29 |  |  |
| [OCM-18879](https://issues.redhat.com/browse/OCM-18879) | Story | To Do | - | Jeff Frazier | CI Integration for Log Forwarding | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-29 |  |
| [OCM-18878](https://issues.redhat.com/browse/OCM-18878) | Story | To Do | - | Jeff Frazier | Functional Tests for Log Forwarding | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-29 |  |
| [OCM-18877](https://issues.redhat.com/browse/OCM-18877) | Story | In Progress | ROSA Coffee Sprint 8 | Jeff Frazier | Test Plan for Log Forwarding | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-30 |  |
| [OCM-18876](https://issues.redhat.com/browse/OCM-18876) | Story | To Do | - | Jeff Frazier | E2E Tests Automation for Log Forwarding | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-29 |  |
| [OCM-18875](https://issues.redhat.com/browse/OCM-18875) | Epic | New | - | Jeff Frazier | HCP Log Forwarding E2E testing | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-30 |  |
| [OCM-18862](https://issues.redhat.com/browse/OCM-18862) | Epic | In Progress | - | Christopher Doan | [OSDFM] HCP Log Forwarding Process for regional provisioning | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-23 |  |
| [OCM-18874](https://issues.redhat.com/browse/OCM-18874) | Story | To Do | - | Christopher Doan | Investigate how to best deploy the Log Forwarding Components to Manage | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-09-18 | 2025-10-23 |  |
| [OCM-18503](https://issues.redhat.com/browse/OCM-18503) | Task | Code Review | - | William Kutler | Update OCM DDR to use shared logging hub architecture | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-09-16 | 2025-10-29 |  |
| [OCM-13315](https://issues.redhat.com/browse/OCM-13315) | Task | In Progress | - | William Kutler | Spike: set up proof of concept for control plane log forwarding in CS | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-01-07 | 2025-10-16 |  |
| [OCM-12601](https://issues.redhat.com/browse/OCM-12601) | Epic | Refinement | - | William Kutler | [OCM]: Epic for XCMSTRAT-1358 - ROSA HCP control plane logs to cloudwa | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2024-11-15 | 2025-10-28 |  |

</details>

---

#### [ROSA-96](https://issues.redhat.com/browse/ROSA-96): ROSA-HCP - IDMS Image registry mirror config to customers

**8 Non-Closed Child Issues**

<details>
<summary>OCM Project (8 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-19795](https://issues.redhat.com/browse/OCM-19795) | Story | Code Review | - | Philip Wu | Implement Terraform Modules support for Image Mirrors | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-10-27 | 2025-10-29 |  |
| [OCM-17630](https://issues.redhat.com/browse/OCM-17630) | Story | To Do | - | CI Integration for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:12 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17629](https://issues.redhat.com/browse/OCM-17629) | Story | To Do | - | E2E Tests Automation for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:10 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17628](https://issues.redhat.com/browse/OCM-17628) | Story | To Do | - | Functional Tests for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:08 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17627](https://issues.redhat.com/browse/OCM-17627) | Story | To Do | - | Test Plan for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:05 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17626](https://issues.redhat.com/browse/OCM-17626) | Story | To Do | - | Feature toggle maintenance: [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:01 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17625](https://issues.redhat.com/browse/OCM-17625) | Story | To Do | - | Ensure reliability for epic [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:00:57 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-06 |  |  |
| [OCM-11211](https://issues.redhat.com/browse/OCM-11211) | Epic | Review | - | David Lee | [OCM]: Epic for XCMSTRAT-994 - ROSA-HCP - Image registry mirror config | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2024-09-17 | 2025-10-27 |  |

</details>

---


### 🟡 Major Priority

#### [ROSA-102](https://issues.redhat.com/browse/ROSA-102): ROSA HCP: Shared VPC (GA)

**3 Non-Closed Child Issues**

<details>
<summary>OCM Project (2 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-13434](https://issues.redhat.com/browse/OCM-13434) | Story | To Do | - | Jericho Keyne | E2E Automation: ROSA HCP : Terraform for Shared VPC | [ROSA-102](https://issues.redhat.com/browse/ROSA-102) | 2025-01-14 | 2025-09-18 |  |
| [OCM-13433](https://issues.redhat.com/browse/OCM-13433) | Story | To Do | - | Jericho Keyne | CI Automation: ROSA HCP : Terraform for Shared VPC | [ROSA-102](https://issues.redhat.com/browse/ROSA-102) | 2025-01-14 | 2025-09-18 |  |

</details>

<details>
<summary>OSD Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSD-31045](https://issues.redhat.com/browse/OSD-31045) | Story | In Progress | - | Rafael Azevedo | Send customer notifications for ROSA HCP Shared VPC IAM policy migrati | [ROSA-102](https://issues.redhat.com/browse/ROSA-102) | 2025-08-25 | 2025-10-08 |  |

</details>

---

#### [ROSA-106](https://issues.redhat.com/browse/ROSA-106): (FedRAMP High) Billing Process & Data from ROSA GovCloud

**6 Non-Closed Child Issues**

<details>
<summary>OCM Project (4 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-17642](https://issues.redhat.com/browse/OCM-17642) | Story | Code Review | - | Eric Himmelreich | setup AMS prometheus in FedRAMP | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-08-07 | 2025-10-29 |  |
| [OCM-17213](https://issues.redhat.com/browse/OCM-17213) | Story | To Do | - | Add documentation for the service | 2025-07-16 22:20:45 | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-08-15 |  |  |
| [OCM-17209](https://issues.redhat.com/browse/OCM-17209) | Story | To Do | - | [FedRAMP]: Fetch ROSA HCP metrics from AMS Prometheus instance | 2025-07-16 22:10:11 | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-08-15 |  |  |
| [OCM-13099](https://issues.redhat.com/browse/OCM-13099) | Epic | In Progress | - | Leonardo Dorneles | [OCM]: Epic for XCMSTRAT-1104 - Egress of Billing Data from ROSA GovCl | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2024-12-13 | 2025-09-24 |  |

</details>

<details>
<summary>OCMUI Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-2793](https://issues.redhat.com/browse/OCMUI-2793) | Epic | New | - | [OCM UI]: Epic for XCMSTRAT-1104 - Egress of Billing Data from ROSA GovCloud | 2024-12-13 12:15:36 | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-06-14 |  |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12936](https://issues.redhat.com/browse/OSDOCS-12936) | Epic | New | - | Ryan Deussing | [MOS Docs]: Epic for XCMSTRAT-1104 - Egress of Billing Data from ROSA  | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2024-12-13 | 2025-08-25 |  |

</details>

---

#### [ROSA-144](https://issues.redhat.com/browse/ROSA-144): ROSA HCP multiarch/Arm follow-up components

**1 Non-Closed Child Issue**

<details>
<summary>OSD Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSD-23547](https://issues.redhat.com/browse/OSD-23547) | Story | To Do | - | Rafael Azevedo | Migrate SRE HCP operators that run on worker nodes to Konflux and enab | [ROSA-144](https://issues.redhat.com/browse/ROSA-144) | 2024-05-22 | 2025-09-12 |  |

</details>

---

#### [ROSA-179](https://issues.redhat.com/browse/ROSA-179): [ROSA HCP] M2 /GA: Support for EC2 Capacity Reservations

**5 Non-Closed Child Issues**

<details>
<summary>OCMUI Project (3 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-3833](https://issues.redhat.com/browse/OCMUI-3833) | Story | To Do | - | David Taylor | Support upgrades, autoscaling, and reservation preferences | [ROSA-179](https://issues.redhat.com/browse/ROSA-179) | 2025-10-02 | 2025-10-16 |  |
| [OCMUI-3832](https://issues.redhat.com/browse/OCMUI-3832) | Story | Review | - | Dylan Cooper | Display Capacity Reservation ID with a Tool tip | [ROSA-179](https://issues.redhat.com/browse/ROSA-179) | 2025-10-01 | 2025-10-30 |  |
| [OCMUI-3484](https://issues.redhat.com/browse/OCMUI-3484) | Epic | Refinement | - | David Taylor | [ROSA HCP] Support for EC2 Capacity Reservations | [ROSA-179](https://issues.redhat.com/browse/ROSA-179) | 2025-06-09 | 2025-10-16 |  |

</details>

<details>
<summary>OSDOCS Project (2 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-16544](https://issues.redhat.com/browse/OSDOCS-16544) | Story | New | - | Olga Tikhomirova | Update Capacity Reservations docs post CLI release | [ROSA-179](https://issues.redhat.com/browse/ROSA-179) | 2025-10-15 | 2025-10-22 |  |
| [OSDOCS-16543](https://issues.redhat.com/browse/OSDOCS-16543) | Epic | In Progress | - | Olga Tikhomirova | [Docs] Capacity Reservations in ROSA HCP | [ROSA-179](https://issues.redhat.com/browse/ROSA-179) | 2025-10-15 | 2025-10-15 |  |

</details>

---

#### [ROSA-183](https://issues.redhat.com/browse/ROSA-183): ROSA HCP: M2: Self-service configuration of Platform Alerts using CMO

**5 Non-Closed Child Issues**

<details>
<summary>OCM Project (3 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-18528](https://issues.redhat.com/browse/OCM-18528) | Story | In Progress | ROSA CLI & TF Sprint 2025-8 | Lucas Freitas | [ROSA CLI] Discontinue UWM for ROSA HCP clusters | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-09-18 | 2025-10-29 |  |
| [OCM-15221](https://issues.redhat.com/browse/OCM-15221) | Epic | In Progress | ROSA CLI & TF Sprint 2025-6 | Hunter Kepley | [OCM-ROSA-Experience]: ROSA CLI to discontinue support for UWM-Toggle | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-04-14 | 2025-09-18 |  |
| [OCM-11038](https://issues.redhat.com/browse/OCM-11038) | Epic | New | - | [OCM]: OCM-CS to disable UWM Toggle during cluster creation and after cluster creation | 2024-09-10 11:23:18 | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-10-29 |  |  |

</details>

<details>
<summary>OSDOCS Project (2 issues)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12898](https://issues.redhat.com/browse/OSDOCS-12898) | Story | In Progress | - | Ben Hardesty | ROSA HCP: Self-service configuration of Platform Alerts using CMO | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2024-12-11 | 2025-10-22 |  |
| [OSDOCS-11965](https://issues.redhat.com/browse/OSDOCS-11965) | Epic | In Progress | - | Ben Hardesty | [MOS Docs]: Replace ROSA HCP Monitoring Docs with OCP Monitoring Docs | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2024-09-10 | 2025-10-21 |  |

</details>

---


### 🔵 Normal Priority

#### [ROSA-182](https://issues.redhat.com/browse/ROSA-182): enable region: Thailand ap-southeast-7

**1 Non-Closed Child Issue**

<details>
<summary>OCM Project (1 issue)</summary>

| Key | Type | Status | Sprint | Assignee | Summary | Parent | Created | Updated | Target Date |
|-----|------|--------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-17518](https://issues.redhat.com/browse/OCM-17518) | Epic | New | - | Carl Brumm | [OCM/CS]: Epic for XCMSTRAT-1110 - enable region: Thailand ap-southeas | [ROSA-182](https://issues.redhat.com/browse/ROSA-182) | 2025-07-31 | 2025-10-08 |  |

</details>

---

## Notes

1. This report shows **immediate children only** (not descendants) using the `childIssuesOf()` JQL function
2. **Closed issues are excluded** - only showing active work
3. **Sprint information** is shown for issues with "In Progress" status
4. Children are issues that have a "Child Of" relationship to the parent ROSA feature
5. Queried across projects: OCM, ACM, OCMUI, OSDOCS, OSD, SLSRE
6. Data retrieved via Jira CLI using JQL queries
7. Sprint data retrieved from customfield_12310940

## Query Details

For each ROSA feature, the following JQL query was used across multiple projects:
```
issue in childIssuesOf('<ROSA-KEY>') AND status NOT IN (Closed)
```

This ensures we only see:
- Direct children (not grandchildren or deeper descendants)
- Issues that are still active (not Closed)

