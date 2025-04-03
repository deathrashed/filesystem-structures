# Time-Based File Structure

<div align="center">
  
  [![Methodology](https://img.shields.io/badge/Methodology-Chronological-yellow?style=for-the-badge)](https://github.com/username/filesystem-structures)
  [![Target User](https://img.shields.io/badge/For-Archivists_&_Project_Managers-blue?style=for-the-badge)](https://github.com/username/filesystem-structures)
  [![Complexity](https://img.shields.io/badge/Complexity-Low_Medium-green?style=for-the-badge)](https://github.com/username/filesystem-structures)
  [![Focus](https://img.shields.io/badge/Focus-Temporal_Organization-orange?style=for-the-badge)](https://github.com/username/filesystem-structures)

  **A filesystem organization structured around time periods, perfect for archival purposes, chronological work, and tracking progress over time. Particularly useful when documents are frequently referenced by when they were created.**
</div>

## 🌟 Key Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧰 Structure Highlights</h3>
      <ul>
        <li><b>Chronological Organization</b> - Files arranged by year, quarter, month</li>
        <li><b>Natural Timeline</b> - Creates an intuitive historical record of work</li>
        <li><b>Self-Archiving</b> - Older time periods automatically become archives</li>
        <li><b>Regular Structure</b> - Consistent patterns for all time periods</li>
        <li><b>Context Preservation</b> - Retains the temporal context of files</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 Perfect For</h3>
      <ul>
        <li>Financial record keeping</li>
        <li>Project management with clear timelines</li>
        <li>Academic or business quarterly planning</li>
        <li>Legal and compliance documentation</li>
        <li>Historical record maintenance</li>
        <li>Regular reporting (monthly, quarterly, annual)</li>
        <li>Personal journals and history tracking</li>
      </ul>
    </td>
  </tr>
</table>

## 📆 Core Organization Principle

This structure uses time as the primary organizing factor, with content type as a secondary factor. Every top-level directory (except for a few time-independent ones) follows this pattern:

```
Category/
├── 2025/
│   ├── Q1/
│   │   ├── January/
│   │   ├── February/
│   │   └── March/
│   ├── Q2/
│   └── ...
├── 2024/
│   ├── Q1/
│   ├── Q2/
│   └── ...
├── 2023/
└── Archive Pre 2023/
    ├── 2022/
    ├── 2021/
    └── ...
```

## 📂 Directory Overview

<details>
<summary><b>Documents</b> - General documents organized by time</summary>
<ul>
  <li><b>2025</b> - Current year broken down by quarter and month
    <ul>
      <li><b>Q1, Q2, Q3, Q4</b> - Quarterly folders</li>
      <li><b>January, February, etc.</b> - Monthly folders within quarters</li>
    </ul>
  </li>
  <li><b>2024</b> - Previous year with content-based subfolders
    <ul>
      <li><b>Q1</b> - First quarter
        <ul>
          <li><b>Project Alpha</b> - Project-specific documents</li>
          <li><b>Tax Documents</b> - Q1 tax materials</li>
          <li><b>Meeting Notes</b> - Q1 meeting documentation</li>
        </ul>
      </li>
      <li><b>Q2, Q3, Q4</b> - Remaining quarters with similar organization</li>
    </ul>
  </li>
  <li><b>2023</b> - Two-year-old documents with annual organization
    <ul>
      <li><b>Annual Report</b> - Yearly summary documents</li>
      <li><b>Client Projects</b> - Client work from 2023</li>
      <li><b>Financial Statements</b> - Financial records from 2023</li>
      <li><b>HR Documents</b> - Human resources documentation from 2023</li>
    </ul>
  </li>
  <li><b>Archive Pre 2023</b> - Older documents organized by year
    <ul>
      <li><b>2022, 2021, 2020</b> - Annual archives</li>
    </ul>
  </li>
</ul>
</details>

<details>
<summary><b>Projects</b> - Project work organized chronologically</summary>
<ul>
  <li><b>2025</b> - Current year projects by quarter
    <ul>
      <li><b>Q1</b> - First quarter projects
        <ul>
          <li><b>Website Redesign</b> - Specific Q1 project</li>
          <li><b>Marketing Campaign</b> - Another Q1 project</li>
        </ul>
      </li>
      <li><b>Q2, Q3, Q4</b> - Remaining quarters with their respective projects</li>
    </ul>
  </li>
  <li><b>2024</b> - Previous year's projects by quarter</li>
  <li><b>Archive Pre 2024</b> - Older project archives by year</li>
</ul>
</details>

<details>
<summary><b>Finances</b> - Financial records with fine-grained time organization</summary>
<ul>
  <li><b>2025</b> - Current year finances by quarter
    <ul>
      <li><b>Q1, Q2, Q3, Q4</b> - Quarterly financial records
        <ul>
          <li><b>Expenses</b> - Expense tracking</li>
          <li><b>Invoices</b> - Sent and received invoices</li>
          <li><b>Statements</b> - Account statements</li>
        </ul>
      </li>
    </ul>
  </li>
  <li><b>2024</b> - Previous year finances summarized annually
    <ul>
      <li><b>Tax Documents</b> - Tax filings and supporting materials</li>
      <li><b>Annual Reports</b> - Yearly financial summaries</li>
    </ul>
  </li>
  <li><b>2023</b> - Two-year-old financial records</li>
  <li><b>Tax Archives</b> - Older tax records by year range
    <ul>
      <li><b>2020-2022</b> - Multi-year tax archives</li>
    </ul>
  </li>
</ul>
</details>

<details>
<summary><b>Meeting Notes</b> - Chronological record of all meetings</summary>
<ul>
  <li><b>2025</b> - Current year meetings by quarter
    <ul>
      <li><b>Q1, Q2</b> - Quarterly meeting notes
        <ul>
          <li><b>Team Meetings</b> - Internal team meetings</li>
          <li><b>Client Meetings</b> - Client meeting notes</li>
          <li><b>One on Ones</b> - Individual meetings</li>
        </ul>
      </li>
    </ul>
  </li>
  <li><b>2024, 2023</b> - Previous years' meeting notes</li>
  <li><b>Archive Pre 2023</b> - Older meeting archives</li>
</ul>
</details>

<details>
<summary><b>Pictures</b> - Photos organized by capture date</summary>
<ul>
  <li><b>2025, 2024, 2023</b> - Photos from each year</li>
  <li><b>Archive Pre 2023</b> - Older photo archives</li>
</ul>
</details>

<details>
<summary><b>Non-Temporal Directories</b></summary>
<ul>
  <li><b>Reference</b> - Time-independent reference information</li>
  <li><b>Templates</b> - Document and project templates that are used across time periods</li>
  <li><b>Downloads</b> - Default browser download location (can be periodically sorted into appropriate time folders)</li>
</ul>
</details>

## 🔄 Time Progression & Organization Flow

<table>
  <tr>
    <td colspan="3" align="center">
      <h3>📅 How Content Moves Through Time</h3>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top" align="center">
      <h4>Current Period</h4>
      <p>Most detailed organization<br>(Year/Quarter/Month)</p>
      <p>Example: 2025/Q1/January</p>
    </td>
    <td width="33%" valign="top" align="center">
      <h4>Recent Past</h4>
      <p>Medium-detail organization<br>(Year/Quarter)</p>
      <p>Example: 2024/Q3</p>
    </td>
    <td width="33%" valign="top" align="center">
      <h4>Historical Archive</h4>
      <p>Broader organization<br>(Year)</p>
      <p>Example: Archive Pre 2023/2021</p>
    </td>
  </tr>
  <tr>
    <td colspan="3" align="center">
      <p>As time passes, detailed folders consolidate into increasingly broader archives</p>
      <p>⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶⟶</p>
    </td>
  </tr>
</table>

## 💡 Implementation Tips

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🗓️ Date Format Consistency</h3>
      <p>Use consistent date formats in all filenames and folders:</p>
      <ul>
        <li><b>Folders</b>: Use consistent formats like YYYY for years, QN for quarters</li>
        <li><b>Files</b>: Prefix with dates in ISO format (YYYY-MM-DD) for natural sorting</li>
        <li><b>Example</b>: <code>2025-04-15_Quarterly_Report.docx</code></li>
        <li><b>Avoid</b>: Month names in filenames (except in folder names) as they don't sort chronologically</li>
        <li><b>Script</b>: Consider using scripts to batch rename files with correct date prefixes</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⏱️ Time-Based Automation</h3>
      <p>Use automation to maintain the structure:</p>
      <ul>
        <li><b>Quarterly Scripts</b>: Run scripts at quarter end to organize and archive</li>
        <li><b>Year-End Process</b>: Create a checklist for year-end file migrations</li>
        <li><b>Auto-Creation</b>: Automatically create the next month/quarter folders</li>
        <li><b>Download Sorting</b>: Use tools like Hazel to automatically move downloads to appropriate date folders</li>
        <li><b>Backup Schedule</b>: Align backup schedule with your time-based structure</li>
      </ul>
    </td>
  </tr>
</table>

## ✨ Key Advantages

1. **Historical Context** - Files exist in the context of when they were created or used
2. **Natural Archiving** - As time progresses, older content naturally moves to archives
3. **Compliance Friendly** - Excellent for industries with retention requirements
4. **Progress Tracking** - Easily visualize work and output over time
5. **Familiar Structure** - Based on universally understood calendar periods
6. **Search Efficiency** - Quickly narrow searches to specific time periods
7. **Regular Cleanup** - Encourages consistent review and organization

## 🚀 Who Should Use This Structure

This structure is particularly valuable for:

- **Accountants & Financial Professionals** - For tax records, statements, and financial planning
- **Project Managers** - For tracking projects across quarters and fiscal years
- **Lawyers & Compliance Officers** - For managing documents with regulatory retention requirements
- **Journalists & Researchers** - For organizing research materials chronologically
- **Academics** - For organizing work by semester/term
- **Archivists** - For preserving historical records with temporal context

## 🔄 Migration Strategy

If you're transitioning to this structure:

1. **Start with current year** - Set up the structure for the current year first
2. **Work backward** - Organize previous years one at a time, starting with most recent
3. **Use file creation dates** - Use file metadata to automatically sort into time periods
4. **Create consolidated archives** - Group older years into broader time periods
5. **Update any references** - Adjust any links or references to reflect new file locations

## 📝 Customization Ideas

- **Academic Calendar** - Modify to use semesters or terms instead of quarters
- **Fiscal Year Alignment** - Adjust to match your organization's fiscal year
- **Daily Organization** - Add daily folders for high-volume time periods
- **Project-Time Hybrid** - Create project folders within time periods for complex projects
- **Client-Time Structure** - Add client-specific folders within each time period

---

<div align="center">
  <p><i>"Time brings all things to pass."</i></p>
  <p><a href="../Structure%207%20-%20Action%20Oriented%20(GTD)">← Action-Oriented (GTD) Structure</a> | <a href="../Structure%209%20-%20Developer%20Focused">Developer-Focused Structure →</a></p>
</div>
