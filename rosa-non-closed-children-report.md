# ROSA Features - Non-Closed Immediate Children Report

**Generated:** 2025-10-24 12:03:31

## Summary

This report shows all **non-closed** immediate children (childOf relationship) for ROSA features with status: In Progress, Review, or Release Pending.

**Filters Applied:**
- Only immediate children (no descendants)
- Excludes issues with status = Closed
- Queried across multiple Jira projects

**Results:**
- **Total ROSA Features:** 12
- **Total Non-Closed Child Issues:** 183
- **Projects Represented:** 6

### Children Count by Feature:
- **ROSA-86** (Blocker): 40 non-closed children
- **ROSA-123** (Critical): 28 non-closed children
- **ROSA-403** (Critical): 30 non-closed children
- **ROSA-418** (Critical): 19 non-closed children
- **ROSA-431** (Critical): 38 non-closed children
- **ROSA-96** (Critical): 8 non-closed children
- **ROSA-102** (Major): 3 non-closed children
- **ROSA-106** (Major): 6 non-closed children
- **ROSA-144** (Major): 1 non-closed children
- **ROSA-183** (Major): 6 non-closed children
- **ROSA-511** (Major): 2 non-closed children
- **ROSA-182** (Normal): 2 non-closed children
- **ROSA-356** (Major): 0 children -- This wasn't found by Claude. Adding here manually. [ROSA-356](https://issues.redhat.com/browse/ROSA-356)

### Children Count by Project:
- **ACM**: 4 issues
- **OCM**: 111 issues
- **OCMUI**: 13 issues
- **OSD**: 38 issues
- **OSDOCS**: 8 issues
- **SLSRE**: 9 issues

---

## Features by Priority


### 🔴 Blocker Priority

#### [ROSA-86](https://issues.redhat.com/browse/ROSA-86)

**40 Non-Closed Child Issues**

<details>
<summary>ACM Project (3 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [ACM-24880](https://issues.redhat.com/browse/ACM-24880) | Task | In Progress | Anna Francis | Implement backend test to check the OADP resources per OCP version | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-01 | 2025-10-23 |  |
| [ACM-24861](https://issues.redhat.com/browse/ACM-24861) | Feature | Resolved | Mehmet Pekpergel | Alerts for DR account reconciliation | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-01 | 2025-10-03 |  |
| [ACM-20793](https://issues.redhat.com/browse/ACM-20793) | Story | Resolved | Mehmet Pekpergel | as an operator of FM, existing management clusters will also have DR AWS availab | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-14 | 2025-10-24 |  |

</details>

<details>
<summary>OCM Project (27 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-19662](https://issues.redhat.com/browse/OCM-19662) | Task | In Progress | Eric Cambel | Mid-sized Scalability Test - 32 clusters | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-23 | 2025-10-23 |  |
| [OCM-19649](https://issues.redhat.com/browse/OCM-19649) | Story | To Do | Lucas Ponce | Capture backup dependencies versions in hcm-deployment snapshot | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-23 | 2025-10-23 |  |
| [OCM-19595](https://issues.redhat.com/browse/OCM-19595) | Task | Review | Guilherme Branco | Custom Backup Schedule Configuration for Clusters | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-22 | 2025-10-24 |  |
| [OCM-19592](https://issues.redhat.com/browse/OCM-19592) | Task | Review | Guilherme Branco | Bypass Backup Creation During Cluster Provisioning | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-22 | 2025-10-24 |  |
| [OCM-18502](https://issues.redhat.com/browse/OCM-18502) | Task | In Progress | Lawton Mizell | Evaluate the impact of cluster upgrades in the backups (and vice versa) | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 | 2025-10-01 |  |
| [OCM-18451](https://issues.redhat.com/browse/OCM-18451) | Story | To Do | Find/Create AWS Account for Scalability Tests | 2025-09-15 11:01:11 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18398](https://issues.redhat.com/browse/OCM-18398) | Story | To Do | Velero Backup Timing Analysis | 2025-09-11 16:08:25 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18397](https://issues.redhat.com/browse/OCM-18397) | Story | To Do | Velero Resource Utilization Monitoring | 2025-09-11 16:07:38 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18396](https://issues.redhat.com/browse/OCM-18396) | Story | To Do | Core Velero Backup Metrics Collection | 2025-09-11 16:06:37 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-18365](https://issues.redhat.com/browse/OCM-18365) | Task | To Do | Benchmark ROSA HCP Backup speeds using multiple workers | 2025-09-08 17:10:53 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-17694](https://issues.redhat.com/browse/OCM-17694) | Task | Review | Guilherme Branco | Populate backup_state field during cluster provisioning | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-08-11 | 2025-10-09 |  |
| [OCM-17510](https://issues.redhat.com/browse/OCM-17510) | Task | In Progress | Eric Cambel | Create a scalability testing plan | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-07-31 | 2025-10-10 |  |
| [OCM-17454](https://issues.redhat.com/browse/OCM-17454) | Epic | In Progress | Eric Cambel | OADP + Velero Scalability Tests for ROSA HCP | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-07-29 | 2025-10-23 |  |
| [OCM-17403](https://issues.redhat.com/browse/OCM-17403) | Story | Code Review | Guilherme Branco | [Clusters-Service] Implement backup state patching via the control plane endpoin | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-07-25 | 2025-10-22 |  |
| [OCM-16136](https://issues.redhat.com/browse/OCM-16136) | Risk | To Do | No Prometheus metrics for Kopia uploads | 2025-06-02 10:09:12 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-16135](https://issues.redhat.com/browse/OCM-16135) | Risk | To Do | Unable to use enable S3 Bucket Keys with OADP/Velero | 2025-06-02 09:58:50 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-16134](https://issues.redhat.com/browse/OCM-16134) | Risk | To Do | Backup objects created by Kopia are not tagged in S3 | 2025-06-02 09:52:32 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-15906](https://issues.redhat.com/browse/OCM-15906) | Task | To Do | Define process to rotate KMS Keys used to encrypt backups | 2025-05-21 08:49:55 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-29 |  |  |
| [OCM-15776](https://issues.redhat.com/browse/OCM-15776) | Story | In Progress | Elveera Mathias | E2E Tests Automation for Clusters Service requirements for ROSA HCP Backup and R | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-10-20 |  |
| [OCM-15775](https://issues.redhat.com/browse/OCM-15775) | Story | To Do | Elveera Mathias | Functional Tests for Clusters Service requirements for ROSA HCP Backup and Resto | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-09-22 |  |
| [OCM-15774](https://issues.redhat.com/browse/OCM-15774) | Story | In Progress | Elveera Mathias | Test Plan for Clusters Service requirements for ROSA HCP Backup and Restore | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-09-22 |  |
| [OCM-15773](https://issues.redhat.com/browse/OCM-15773) | Story | To Do | Feature toggle maintenance: Clusters Service requirements for ROSA HCP Backup and Restore | 2025-05-13 10:41:13 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-15771](https://issues.redhat.com/browse/OCM-15771) | Epic | In Progress | Lucas Ponce | Clusters Service requirements for ROSA HCP Backup and Restore | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-05-13 | 2025-10-23 |  |
| [OCM-15599](https://issues.redhat.com/browse/OCM-15599) | Story | To Do | Spike Restoration Flow for etcd specific failures and test node re-adoption | 2025-05-01 14:42:26 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-22 |  |  |
| [OCM-15446](https://issues.redhat.com/browse/OCM-15446) | Epic | In Progress | Christopher Doan | OSDFM Requirements for ROSA HCP DR improvements | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-04-23 | 2025-10-10 |  |
| [OCM-14679](https://issues.redhat.com/browse/OCM-14679) | Task | To Do | Spike restoration flow | 2025-03-17 15:44:20 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-29 |  |  |
| [OCM-13195](https://issues.redhat.com/browse/OCM-13195) | Epic | In Progress | Lucas Ponce | ROSA HCP - DR restoration improvements - Research/Refinement | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2024-12-19 | 2025-10-03 |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12727](https://issues.redhat.com/browse/OSDOCS-12727) | Epic | New | Ryan Deussing | docs for cluster backup & restore | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2024-11-20 | 2025-09-10 |  |

</details>

<details>
<summary>SLSRE Project (9 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [SLSRE-382](https://issues.redhat.com/browse/SLSRE-382) | Story | New | Review metrics to capture during Perf/Scale testing | 2025-09-16 11:03:47 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-381](https://issues.redhat.com/browse/SLSRE-381) | Story | New | Review Test Plan | 2025-09-16 11:00:40 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-380](https://issues.redhat.com/browse/SLSRE-380) | Story | New | Define alerts for AWS Quota and Resource utilization in the Backup Account | 2025-09-16 10:58:29 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-374](https://issues.redhat.com/browse/SLSRE-374) | Epic | In Progress | Sergio Lopez | ROSA HCP - Backup Reliability | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 | 2025-09-16 |  |
| [SLSRE-377](https://issues.redhat.com/browse/SLSRE-377) | Story | To Do | Monitor DataUpload and BackUp CRs for backup data upload verification | 2025-06-02 15:50:17 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-378](https://issues.redhat.com/browse/SLSRE-378) | Story | To Do | Implement Alerting Rules | 2025-06-02 13:10:14 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-379](https://issues.redhat.com/browse/SLSRE-379) | Story | To Do | Build Dashboards for Backup Visibility | 2025-06-02 13:09:20 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-09-16 |  |  |
| [SLSRE-376](https://issues.redhat.com/browse/SLSRE-376) | Story | To Do | Integrate Backup Metrics into Monitoring Platform | 2025-06-02 13:07:11 | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-10-24 |  |  |
| [SLSRE-375](https://issues.redhat.com/browse/SLSRE-375) | Story | In Progress | Sergio Lopez | Define Backup Monitoring Metrics | [ROSA-86](https://issues.redhat.com/browse/ROSA-86) | 2025-06-02 | 2025-10-21 |  |

</details>

---


### 🟠 Critical Priority

#### [ROSA-123](https://issues.redhat.com/browse/ROSA-123)

**28 Non-Closed Child Issues**

<details>
<summary>ACM Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [ACM-24746](https://issues.redhat.com/browse/ACM-24746) | Epic | New | Mohamed ElSerngawy | [CAPA]: Epic for ROSA-123 - CAPA support for ROSA HCP with FIPS enabled on worke | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 | 2025-10-10 |  |

</details>

<details>
<summary>OCM Project (22 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-18682](https://issues.redhat.com/browse/OCM-18682) | Story | To Do | CI Integration for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:56 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18681](https://issues.redhat.com/browse/OCM-18681) | Story | To Do | E2E Tests Automation for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:53 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18680](https://issues.redhat.com/browse/OCM-18680) | Story | To Do | Functional Tests for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:51 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18679](https://issues.redhat.com/browse/OCM-18679) | Story | To Do | Test Plan for [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:49 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18678](https://issues.redhat.com/browse/OCM-18678) | Story | To Do | Feature toggle maintenance: [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:45 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18677](https://issues.redhat.com/browse/OCM-18677) | Story | To Do | Ensure reliability for epic [TF]: Epic for XCMSTRAT-144 - Terraform support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:40:42 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |
| [OCM-18676](https://issues.redhat.com/browse/OCM-18676) | Epic | New | Hunter Kepley | [TF]: Epic for ROSA-123 - Terraform support for ROSA HCP with FIPS enabled on wo | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 | 2025-10-22 |  |
| [OCM-18675](https://issues.redhat.com/browse/OCM-18675) | Story | To Do | CI Integration for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:23 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18674](https://issues.redhat.com/browse/OCM-18674) | Story | To Do | E2E Tests Automation for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers  | 2025-09-28 07:28:21 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18673](https://issues.redhat.com/browse/OCM-18673) | Story | To Do | Functional Tests for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:18 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18672](https://issues.redhat.com/browse/OCM-18672) | Story | To Do | Test Plan for [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:16 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18671](https://issues.redhat.com/browse/OCM-18671) | Story | To Do | Feature toggle maintenance: [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:13 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 |  |  |
| [OCM-18670](https://issues.redhat.com/browse/OCM-18670) | Story | To Do | Ensure reliability for epic: [ROSA CLI]: Epic for XCMSTRAT-144 - ROSA CLI support for ROSA HCP with FIPS enabled on workers | 2025-09-28 07:28:09 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |
| [OCM-18669](https://issues.redhat.com/browse/OCM-18669) | Epic | New | Hunter Kepley | [ROSA CLI]: Epic for ROSA-123 - ROSA CLI support for ROSA HCP with FIPS enabled  | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-28 | 2025-10-22 |  |
| [OCM-18059](https://issues.redhat.com/browse/OCM-18059) | Story | Review | Idit Gavra | Verify that FIPS is enabled and all components are ok | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-08-28 | 2025-10-06 |  |
| [OCM-17197](https://issues.redhat.com/browse/OCM-17197) | Story | To Do | CI Integration for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | 2025-07-16 11:40:31 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 |  |  |
| [OCM-17196](https://issues.redhat.com/browse/OCM-17196) | Story | To Do | Jeff Frazier | E2E Tests Automation for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS targe | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-09-16 |  |
| [OCM-17195](https://issues.redhat.com/browse/OCM-17195) | Story | To Do | Jeff Frazier | Functional Tests for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target cr | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-09-16 |  |
| [OCM-17194](https://issues.redhat.com/browse/OCM-17194) | Story | To Do | Jeff Frazier | Test Plan for [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-09-16 |  |
| [OCM-17193](https://issues.redhat.com/browse/OCM-17193) | Story | To Do | Feature toggle maintenance: [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | 2025-07-16 11:40:20 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-30 |  |  |
| [OCM-17192](https://issues.redhat.com/browse/OCM-17192) | Story | To Do | Ensure reliability for epic [OCM]: Epic for XCMSTRAT-144 - ROSA HCP with FIPS target crypto | 2025-07-16 11:40:17 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |
| [OCM-17191](https://issues.redhat.com/browse/OCM-17191) | Epic | In Progress | Idit Gavra | [OCM]: Epic for ROSA-123 - ROSA HCP with FIPS target crypto | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-07-16 | 2025-10-22 |  |

</details>

<details>
<summary>OCMUI Project (4 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-3824](https://issues.redhat.com/browse/OCMUI-3824) | Story | To Do | E2E Automation: [ROSA-HCP] OCM UI- ROSA HCP with FIPS enabled on worker nodes | 2025-09-28 10:59:37 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-30 |  |  |
| [OCMUI-3823](https://issues.redhat.com/browse/OCMUI-3823) | Story | To Do | CI Automation: [ROSA-HCP] OCM UI- ROSA HCP with FIPS enabled on worker nodes | 2025-09-28 10:59:35 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-30 |  |  |
| [OCMUI-3822](https://issues.redhat.com/browse/OCMUI-3822) | Story | To Do | Post-merge testing: [ROSA-HCP] OCM UI- ROSA HCP with FIPS enabled on worker nodes | 2025-09-28 10:59:33 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-09-30 |  |  |
| [OCMUI-3821](https://issues.redhat.com/browse/OCMUI-3821) | Epic | New | [ROSA-HCP] OCM UI- ROSA HCP with FIPS enabled | 2025-09-28 10:59:29 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-23 |  |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-16476](https://issues.redhat.com/browse/OSDOCS-16476) | Epic | New | [DOCS]: Epic for ROSA-123 - Document support for ROSA HCP with FIPS | 2025-10-10 04:58:38 | [ROSA-123](https://issues.redhat.com/browse/ROSA-123) | 2025-10-10 |  |  |

</details>

---

#### [ROSA-403](https://issues.redhat.com/browse/ROSA-403)

**30 Non-Closed Child Issues**

<details>
<summary>OCM Project (20 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-18696](https://issues.redhat.com/browse/OCM-18696) | Bug | Review | Maggie Chen | Review wording for version EOL notification | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-30 | 2025-10-22 |  |
| [OCM-18499](https://issues.redhat.com/browse/OCM-18499) | Story | To Do | Patrick Jennings | Enable EUS channel group in FedRAMP | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 | 2025-10-23 |  |
| [OCM-18497](https://issues.redhat.com/browse/OCM-18497) | Story | To Do | CI Integration for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:33 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18496](https://issues.redhat.com/browse/OCM-18496) | Story | To Do | E2E Tests Automation for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:30 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18495](https://issues.redhat.com/browse/OCM-18495) | Story | To Do | Functional Tests for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:27 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18494](https://issues.redhat.com/browse/OCM-18494) | Story | To Do | Test Plan for [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:24 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18493](https://issues.redhat.com/browse/OCM-18493) | Story | To Do | Feature toggle maintenance: [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:18 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18492](https://issues.redhat.com/browse/OCM-18492) | Story | To Do | Ensure reliability for epic [OCM CS] Enable EUS channel group in FedRAMP | 2025-09-16 10:01:12 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 |  |  |
| [OCM-18491](https://issues.redhat.com/browse/OCM-18491) | Epic | New | Brian Smith | [OCM CS] Enable EUS channel group in FedRAMP | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-16 | 2025-10-15 |  |
| [OCM-17743](https://issues.redhat.com/browse/OCM-17743) | Story | To Do | CI Integration for [TF]: Terraform EUS channel support | 2025-08-18 06:09:48 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17742](https://issues.redhat.com/browse/OCM-17742) | Story | To Do | E2E Tests Automation for [TF]: Terraform EUS channel support | 2025-08-18 06:09:46 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17741](https://issues.redhat.com/browse/OCM-17741) | Story | To Do | Functional Tests for [TF]: Terraform EUS channel support | 2025-08-18 06:09:43 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17740](https://issues.redhat.com/browse/OCM-17740) | Story | To Do | Test Plan for [TF]: Terraform EUS channel support | 2025-08-18 06:09:40 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17739](https://issues.redhat.com/browse/OCM-17739) | Story | To Do | Feature toggle maintenance: [TF]: Terraform EUS channel support | 2025-08-18 06:09:36 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-17738](https://issues.redhat.com/browse/OCM-17738) | Story | To Do | Ensure reliability for epic [TF]: Terraform EUS channel support | 2025-08-18 06:09:32 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 |  |  |
| [OCM-15074](https://issues.redhat.com/browse/OCM-15074) | Story | To Do | CI Integration for [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:16 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-15072](https://issues.redhat.com/browse/OCM-15072) | Story | To Do | Functional Tests for [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:11 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-15071](https://issues.redhat.com/browse/OCM-15071) | Story | To Do | Test Plan for [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:09 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-15070](https://issues.redhat.com/browse/OCM-15070) | Story | To Do | Ensure reliability for epic [ROSA CLI]: Epic for XCMSTRAT-1119 - ROSA CLI support for EUS Versions | 2025-04-07 08:26:04 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-06-12 |  |  |
| [OCM-14030](https://issues.redhat.com/browse/OCM-14030) | Epic | Review | Andrea Decorte | EUS Channel is available for ROSA/OSD | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-02-13 | 2025-10-23 |  |

</details>

<details>
<summary>OCMUI Project (8 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-3771](https://issues.redhat.com/browse/OCMUI-3771) | Story | Review | David Aznaurov | Clusters/day 2 - View/Edit channel group | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-11 | 2025-10-21 |  |
| [OCMUI-3770](https://issues.redhat.com/browse/OCMUI-3770) | Story | Review | Dylan Cooper | Wizard(s)/day 1 - Add version Channel group dropdown - OSD | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-11 | 2025-10-22 |  |
| [OCMUI-3763](https://issues.redhat.com/browse/OCMUI-3763) | Story | Review | Trevor Hendricks | Wizard(s)/day 1 - Add version Channel group dropdown - ROSA | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-10 | 2025-10-23 |  |
| [OCMUI-3757](https://issues.redhat.com/browse/OCMUI-3757) | Task | To Do | Enable feature gate in production for all users | 2025-09-10 11:42:55 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-15 |  |  |
| [OCMUI-3693](https://issues.redhat.com/browse/OCMUI-3693) | Story | To Do | E2E Automation: OCM UI EUS Channels | 2025-08-18 05:53:07 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-12 |  |  |
| [OCMUI-3692](https://issues.redhat.com/browse/OCMUI-3692) | Story | To Do | CI Automation: OCM UI EUS Channels | 2025-08-18 05:53:04 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-12 |  |  |
| [OCMUI-3691](https://issues.redhat.com/browse/OCMUI-3691) | Story | To Do | Post-merge testing: OCM UI EUS Channels | 2025-08-18 05:53:02 | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-09-12 |  |  |
| [OCMUI-3690](https://issues.redhat.com/browse/OCMUI-3690) | Epic | In Progress | Dylan Cooper | OCM UI EUS Channels | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-08-18 | 2025-10-21 |  |

</details>

<details>
<summary>OSDOCS Project (2 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-16538](https://issues.redhat.com/browse/OSDOCS-16538) | Story | New | Aedin Collins | Life Cycle (Extension) (UI for OSD and ROSA) | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2025-10-15 | 2025-10-23 |  |
| [OSDOCS-11705](https://issues.redhat.com/browse/OSDOCS-11705) | Epic | In Progress | Mark Letalien | Revised ROSA Life Cycle (Extension) | [ROSA-403](https://issues.redhat.com/browse/ROSA-403) | 2024-08-14 | 2025-10-20 |  |

</details>

---

#### [ROSA-418](https://issues.redhat.com/browse/ROSA-418)

**19 Non-Closed Child Issues**

<details>
<summary>OCM Project (19 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-19306](https://issues.redhat.com/browse/OCM-19306) | Story | To Do | CI Integration for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:28 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19305](https://issues.redhat.com/browse/OCM-19305) | Story | To Do | E2E Tests Automation for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:26 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19304](https://issues.redhat.com/browse/OCM-19304) | Story | To Do | Functional Tests for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:24 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19303](https://issues.redhat.com/browse/OCM-19303) | Story | To Do | Test Plan for HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:21 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19302](https://issues.redhat.com/browse/OCM-19302) | Story | To Do | Feature toggle maintenance: HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:17 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19301](https://issues.redhat.com/browse/OCM-19301) | Story | To Do | Ensure reliability for epic HCP Log Forwarding Client Side(CLI and TF) | 2025-10-16 10:15:13 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-19300](https://issues.redhat.com/browse/OCM-19300) | Epic | New | Carl Brumm | HCP Log Forwarding Client Side(CLI and TF) | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 | 2025-10-21 |  |
| [OCM-18907](https://issues.redhat.com/browse/OCM-18907) | Story | To Do | Document process for changing allowed log forwarding pods | 2025-10-13 12:19:21 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-13 |  |  |
| [OCM-18879](https://issues.redhat.com/browse/OCM-18879) | Story | To Do | CI Integration for Log Forwarding | 2025-10-09 13:58:45 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 |  |  |
| [OCM-18878](https://issues.redhat.com/browse/OCM-18878) | Story | To Do | Functional Tests for Log Forwarding | 2025-10-09 13:58:32 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 |  |  |
| [OCM-18877](https://issues.redhat.com/browse/OCM-18877) | Story | To Do | Test Plan for Log Forwarding | 2025-10-09 13:58:15 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-16 |  |  |
| [OCM-18876](https://issues.redhat.com/browse/OCM-18876) | Story | To Do | E2E Tests Automation for Log Forwarding | 2025-10-09 13:58:00 | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 |  |  |
| [OCM-18875](https://issues.redhat.com/browse/OCM-18875) | Epic | New | Jeff Frazier | HCP Log Forwarding E2E testing | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-13 |  |
| [OCM-18862](https://issues.redhat.com/browse/OCM-18862) | Epic | In Progress | Christopher Doan | [OSDFM] HCP Log Forwarding Process for regional provisioning | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-23 |  |
| [OCM-18855](https://issues.redhat.com/browse/OCM-18855) | Epic | New | William Kutler | HCP Log Forwarding Process for Log Grouping Updates | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-10-09 | 2025-10-20 |  |
| [OCM-18874](https://issues.redhat.com/browse/OCM-18874) | Story | To Do | Christopher Doan | Investigate how to best deploy the Log Forwarding Components to Management Clust | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-09-18 | 2025-10-23 |  |
| [OCM-18503](https://issues.redhat.com/browse/OCM-18503) | Task | In Progress | William Kutler | Update OCM DDR to use shared logging hub architecture | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-09-16 | 2025-10-09 |  |
| [OCM-13315](https://issues.redhat.com/browse/OCM-13315) | Task | In Progress | William Kutler | Spike: set up proof of concept for control plane log forwarding in CS | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2025-01-07 | 2025-10-16 |  |
| [OCM-12601](https://issues.redhat.com/browse/OCM-12601) | Epic | Refinement | William Kutler | [OCM]: Epic for XCMSTRAT-1358 - ROSA HCP control plane logs to cloudwatch | [ROSA-418](https://issues.redhat.com/browse/ROSA-418) | 2024-11-15 | 2025-10-23 |  |

</details>

---

#### [ROSA-431](https://issues.redhat.com/browse/ROSA-431)

**38 Non-Closed Child Issues**

<details>
<summary>OCM Project (2 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-16985](https://issues.redhat.com/browse/OCM-16985) | Story | In Progress | Jayakrishnan Mekkattillam | Post check test on UI after OCP 4.20 is enabled on UI | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-07-08 | 2025-10-24 |  |
| [OCM-16983](https://issues.redhat.com/browse/OCM-16983) | Epic | In Progress | Ying Zhang | Post Check after OCP 4.20 is enabled | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-07-08 | 2025-10-23 |  |

</details>

<details>
<summary>OSD Project (36 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSD-31009](https://issues.redhat.com/browse/OSD-31009) | Sub-task | To Do | Benjamin Toll | Investigate and create sub-tasks where applicable | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-31007](https://issues.redhat.com/browse/OSD-31007) | Sub-task | To Do | Kirk Bater | Enable the candidate Channel in Prod. | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-31006](https://issues.redhat.com/browse/OSD-31006) | Sub-task | To Do | Kirk Bater | Validating the new Versions in production. | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-31005](https://issues.redhat.com/browse/OSD-31005) | Sub-task | To Do | Additional Steps involved for releasing the GCP images in Marketplace. | 2025-08-05 22:32:12 | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 |  |  |
| [OSD-31004](https://issues.redhat.com/browse/OSD-31004) | Sub-task | To Do | Claudio Busse | Working with the respective lead to release new OSD version on the GCP Marketpla | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-31003](https://issues.redhat.com/browse/OSD-31003) | Sub-task | To Do | Kirk Bater | Working with the respective lead to release new ROSA version on the AWS Marketpl | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-31002](https://issues.redhat.com/browse/OSD-31002) | Sub-task | To Do | Suresh Peddinti | Identify the Lead or appropriate channels for both AWS and GCP. | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-31001](https://issues.redhat.com/browse/OSD-31001) | Sub-task | To Do | Suresh Peddinti | Investigate and create sub-tasks where applicable | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30995](https://issues.redhat.com/browse/OSD-30995) | Sub-task | To Do | Ramakrishna Kyatham | Building the test jobs and observing the test failures | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30994](https://issues.redhat.com/browse/OSD-30994) | Sub-task | To Do | Kelly Trainor | Analyze rosa-classic test results | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30993](https://issues.redhat.com/browse/OSD-30993) | Sub-task | To Do | Kelly Trainor | Analyze rosa-hcp test results | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30992](https://issues.redhat.com/browse/OSD-30992) | Sub-task | To Do | Kelly Trainor | Investigate fixing failing tests | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30991](https://issues.redhat.com/browse/OSD-30991) | Sub-task | To Do | Kelly Trainor | Run tests locally using osde2e (rosa-classic and rosa-hcp) | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30990](https://issues.redhat.com/browse/OSD-30990) | Sub-task | To Do | Amarthya Valija | Investigate fixing failing tests | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30989](https://issues.redhat.com/browse/OSD-30989) | Sub-task | To Do | Kelly Trainor | Run tests locally using osde2e (rosa-classic and rosa-hcp) | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30988](https://issues.redhat.com/browse/OSD-30988) | Sub-task | To Do | Amarthya Valija | Run tests locally using osde2e (osd-aws and osd-gcp) | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30987](https://issues.redhat.com/browse/OSD-30987) | Sub-task | To Do | Amarthya Valija | Analyze osd-gcp test results | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30986](https://issues.redhat.com/browse/OSD-30986) | Sub-task | To Do | Amarthya Valija | Analyze osd-aws test results | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30984](https://issues.redhat.com/browse/OSD-30984) | Sub-task | To Do | Benjamin Toll | Create pages to show new alerts and warnings | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30983](https://issues.redhat.com/browse/OSD-30983) | Sub-task | To Do | Benjamin Toll | Determine which alerts should make it into the new version | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30982](https://issues.redhat.com/browse/OSD-30982) | Sub-task | To Do | Benjamin Toll | Document the automation program | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30981](https://issues.redhat.com/browse/OSD-30981) | Sub-task | To Do | Benjamin Toll | Automate the steps to compare the alerts | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30978](https://issues.redhat.com/browse/OSD-30978) | Sub-task | To Do | Benjamin Toll | Create documentation | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30977](https://issues.redhat.com/browse/OSD-30977) | Sub-task | To Do | Benjamin Toll | Write go script for updating the yaml files | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30976](https://issues.redhat.com/browse/OSD-30976) | Sub-task | To Do | Benjamin Toll | Staging Deployment | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30975](https://issues.redhat.com/browse/OSD-30975) | Sub-task | To Do | Benjamin Toll | Validate the Go Script and yaml file deployment | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30974](https://issues.redhat.com/browse/OSD-30974) | Sub-task | To Do | Benjamin Toll | Merge request approval and merge | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30973](https://issues.redhat.com/browse/OSD-30973) | Sub-task | To Do | Ramakrishna Kyatham | Yaml Pipeline for automation. | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30972](https://issues.redhat.com/browse/OSD-30972) | Sub-task | To Do | Ramakrishna Kyatham | Test & Review Go Script. | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30971](https://issues.redhat.com/browse/OSD-30971) | Sub-task | To Do | Ramakrishna Kyatham | Create Go Script for enabling candidate channel using automation. | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30969](https://issues.redhat.com/browse/OSD-30969) | Sub-task | To Do | Benjamin Toll | Investigate Using Release Controller | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30968](https://issues.redhat.com/browse/OSD-30968) | Sub-task | To Do | Benjamin Toll | Go over identified issues with Red Hat | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30967](https://issues.redhat.com/browse/OSD-30967) | Sub-task | To Do | Benjamin Toll | Create Google Sheet demo | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30966](https://issues.redhat.com/browse/OSD-30966) | Sub-task | To Do | Benjamin Toll | Investigate Google Sheets API | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30965](https://issues.redhat.com/browse/OSD-30965) | Sub-task | To Do | Benjamin Toll | Investigate Go SDKs | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |
| [OSD-30964](https://issues.redhat.com/browse/OSD-30964) | Sub-task | To Do | Benjamin Toll | Investigate getting data via a REST API | [ROSA-431](https://issues.redhat.com/browse/ROSA-431) | 2025-08-05 | 2025-08-05 |  |

</details>

---

#### [ROSA-96](https://issues.redhat.com/browse/ROSA-96)

**8 Non-Closed Child Issues**

<details>
<summary>OCM Project (8 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-18302](https://issues.redhat.com/browse/OCM-18302) | Story | Code Review | Philip Wu | Implement Terraform support for Image Mirrors | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-09-04 | 2025-10-21 |  |
| [OCM-17630](https://issues.redhat.com/browse/OCM-17630) | Story | To Do | CI Integration for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:12 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17629](https://issues.redhat.com/browse/OCM-17629) | Story | To Do | E2E Tests Automation for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:10 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17628](https://issues.redhat.com/browse/OCM-17628) | Story | To Do | Functional Tests for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:08 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17627](https://issues.redhat.com/browse/OCM-17627) | Story | To Do | Test Plan for [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:05 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17626](https://issues.redhat.com/browse/OCM-17626) | Story | To Do | Feature toggle maintenance: [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:01:01 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-11 |  |  |
| [OCM-17625](https://issues.redhat.com/browse/OCM-17625) | Story | To Do | Ensure reliability for epic [OCM]: Epic for XCMSTRAT-994 - Client Side - ROSA-HCP - IDMS Image registry mirror config to customers | 2025-08-06 13:00:57 | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2025-08-06 |  |  |
| [OCM-11211](https://issues.redhat.com/browse/OCM-11211) | Epic | Review | David Lee | [OCM]: Epic for XCMSTRAT-994 - ROSA-HCP - Image registry mirror config to custom | [ROSA-96](https://issues.redhat.com/browse/ROSA-96) | 2024-09-17 | 2025-09-26 |  |

</details>

---


### 🟡 Major Priority

#### [ROSA-102](https://issues.redhat.com/browse/ROSA-102)

**3 Non-Closed Child Issues**

<details>
<summary>OCM Project (2 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-13434](https://issues.redhat.com/browse/OCM-13434) | Story | To Do | Jericho Keyne | E2E Automation: ROSA HCP : Terraform for Shared VPC | [ROSA-102](https://issues.redhat.com/browse/ROSA-102) | 2025-01-14 | 2025-09-18 |  |
| [OCM-13433](https://issues.redhat.com/browse/OCM-13433) | Story | To Do | Jericho Keyne | CI Automation: ROSA HCP : Terraform for Shared VPC | [ROSA-102](https://issues.redhat.com/browse/ROSA-102) | 2025-01-14 | 2025-09-18 |  |

</details>

<details>
<summary>OSD Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSD-31045](https://issues.redhat.com/browse/OSD-31045) | Story | In Progress | Rafael Azevedo | Send customer notifications for ROSA HCP Shared VPC IAM policy migration with 4- | [ROSA-102](https://issues.redhat.com/browse/ROSA-102) | 2025-08-25 | 2025-10-08 |  |

</details>

---

#### [ROSA-106](https://issues.redhat.com/browse/ROSA-106)

**6 Non-Closed Child Issues**

<details>
<summary>OCM Project (4 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-17642](https://issues.redhat.com/browse/OCM-17642) | Story | Code Review | Eric Himmelreich | setup AMS prometheus in FedRAMP | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-08-07 | 2025-09-20 |  |
| [OCM-17213](https://issues.redhat.com/browse/OCM-17213) | Story | To Do | Add documentation for the service | 2025-07-16 22:20:45 | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-08-15 |  |  |
| [OCM-17209](https://issues.redhat.com/browse/OCM-17209) | Story | To Do | [FedRAMP]: Fetch ROSA HCP metrics from AMS Prometheus instance | 2025-07-16 22:10:11 | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-08-15 |  |  |
| [OCM-13099](https://issues.redhat.com/browse/OCM-13099) | Epic | In Progress | Leonardo Dorneles | [OCM]: Epic for XCMSTRAT-1104 - Egress of Billing Data from ROSA GovCloud | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2024-12-13 | 2025-09-24 |  |

</details>

<details>
<summary>OCMUI Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCMUI-2793](https://issues.redhat.com/browse/OCMUI-2793) | Epic | New | [OCM UI]: Epic for XCMSTRAT-1104 - Egress of Billing Data from ROSA GovCloud | 2024-12-13 12:15:36 | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2025-06-14 |  |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12936](https://issues.redhat.com/browse/OSDOCS-12936) | Epic | New | Ryan Deussing | [MOS Docs]: Epic for XCMSTRAT-1104 - Egress of Billing Data from ROSA GovCloud | [ROSA-106](https://issues.redhat.com/browse/ROSA-106) | 2024-12-13 | 2025-08-25 |  |

</details>

---

#### [ROSA-144](https://issues.redhat.com/browse/ROSA-144)

**1 Non-Closed Child Issue**

<details>
<summary>OSD Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSD-23547](https://issues.redhat.com/browse/OSD-23547) | Story | To Do | Rafael Azevedo | Migrate SRE HCP operators that run on worker nodes to Konflux and enable ARM ima | [ROSA-144](https://issues.redhat.com/browse/ROSA-144) | 2024-05-22 | 2025-09-12 |  |

</details>

---

#### [ROSA-183](https://issues.redhat.com/browse/ROSA-183)

**6 Non-Closed Child Issues**

<details>
<summary>OCM Project (4 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-18528](https://issues.redhat.com/browse/OCM-18528) | Story | In Progress | Lucas Freitas | [ROSA CLI] Discontinue UWM for ROSA HCP clusters | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-09-18 | 2025-10-21 |  |
| [OCM-18289](https://issues.redhat.com/browse/OCM-18289) | Bug | Review | Andrea Decorte | disable_user_workload_monitoring fails to apply if passed with other fields | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-09-04 | 2025-10-21 |  |
| [OCM-15221](https://issues.redhat.com/browse/OCM-15221) | Epic | In Progress | Hunter Kepley | [OCM-ROSA-Experience]: ROSA CLI to discontinue support for UWM-Toggle | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-04-14 | 2025-09-18 |  |
| [OCM-11038](https://issues.redhat.com/browse/OCM-11038) | Epic | New | [OCM]: OCM-CS to disable UWM Toggle during cluster creation and after cluster creation | 2024-09-10 11:23:18 | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2025-09-08 |  |  |

</details>

<details>
<summary>OSDOCS Project (2 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-12898](https://issues.redhat.com/browse/OSDOCS-12898) | Story | In Progress | Ben Hardesty | ROSA HCP: Self-service configuration of Platform Alerts using CMO | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2024-12-11 | 2025-10-22 |  |
| [OSDOCS-11965](https://issues.redhat.com/browse/OSDOCS-11965) | Epic | In Progress | Ben Hardesty | [MOS Docs]: Replace ROSA HCP Monitoring Docs with OCP Monitoring Docs | [ROSA-183](https://issues.redhat.com/browse/ROSA-183) | 2024-09-10 | 2025-10-21 |  |

</details>

---

#### [ROSA-511](https://issues.redhat.com/browse/ROSA-511)

**2 Non-Closed Child Issues**

<details>
<summary>OCM Project (2 issues)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-17834](https://issues.redhat.com/browse/OCM-17834) | Story | To Do | Verify and Apply OSL Gatekeeping in Production | 2025-08-21 03:57:33 | [ROSA-511](https://issues.redhat.com/browse/ROSA-511) | 2025-09-30 |  |  |
| [OCM-17498](https://issues.redhat.com/browse/OCM-17498) | Epic | In Progress | Deployment Gatekeeping Practice for OSL SLOs | 2025-07-31 05:16:00 | [ROSA-511](https://issues.redhat.com/browse/ROSA-511) | 2025-09-30 |  |  |

</details>

---


### 🔵 Normal Priority

#### [ROSA-182](https://issues.redhat.com/browse/ROSA-182)

**2 Non-Closed Child Issues**

<details>
<summary>OCM Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OCM-17518](https://issues.redhat.com/browse/OCM-17518) | Epic | New | Carl Brumm | [OCM/CS]: Epic for XCMSTRAT-1110 - enable region: Thailand ap-southeast-7 | [ROSA-182](https://issues.redhat.com/browse/ROSA-182) | 2025-07-31 | 2025-10-08 |  |

</details>

<details>
<summary>OSDOCS Project (1 issue)</summary>

| Key | Type | Status | Assignee | Summary | Parent | Created | Updated | Due Date |
|-----|------|--------|----------|---------|--------|---------|---------|----------|
| [OSDOCS-13074](https://issues.redhat.com/browse/OSDOCS-13074) | Epic | Release Pending | Mark Letalien | [MOS Docs]: Epic for XCMSTRAT-1110 - enable region: Thailand ap-southeast-7 | [ROSA-182](https://issues.redhat.com/browse/ROSA-182) | 2025-01-09 | 2025-10-08 |  |

</details>

---

## Notes

1. This report shows **immediate children only** (not descendants) using the `childIssuesOf()` JQL function
2. **Closed issues are excluded** - only showing active work
3. Children are issues that have a "Child Of" relationship to the parent ROSA feature
4. Queried across multiple projects: OCM, SLSRE, OSDOCS, ROSA, OSD, OHSS, HOSTEDCP, ACM, HCMSTRAT, XCMSTRAT, OCMUI
5. Data retrieved via Jira CLI using JQL queries

## Query Details

For each ROSA feature, the following JQL query was used across multiple projects:
```
issue in childIssuesOf('<ROSA-KEY>') AND status NOT IN (Closed)
```

This ensures we only see:
- Direct children (not grandchildren or deeper descendants)
- Issues that are still active (not Closed)

