# azure-license-rg-management
To demonstrate managing licenses, resource groups, tags, locks, and policies in Azure for proper governance and role-based access control.

# 💼 Azure License & Resource Group Management

This lab showcases how to manage licenses and organize users and resources effectively within Azure using **Resource Groups**, **Tags**, **Locks**, and **Policies**. Real-world scenarios often require tight governance to prevent resource sprawl, unauthorized access, or accidental deletion.

## 📸 Screenshots Included
1. Assigning licenses to users.
2. Managing resource groups tied to licenses.
3. Using tags to classify and track resources.
4. Locking critical resources to prevent deletion.

---

## 🔹 Key Concepts

### 1. License Management
- Assign specific Azure/M365 licenses to users based on roles and requirements.
- Licenses help unlock services like Entra ID P2, Microsoft Defender, etc.

### 2. Resource Groups
- Logical containers for related Azure resources.
- You can tie specific licenses, policies, or permissions to a resource group.

### 3. Tags
- Metadata added to Azure resources.
- Common usage: `Owner`, `Department`, `Environment`, `CostCenter`
- Helps in organizing, billing, and managing large environments.

### 4. Resource Locks
- Prevent accidental deletion or modification.
- Types:
  - **ReadOnly**: Allows read operations only.
  - **Delete**: Prevents deletion of the resource.

### 5. Policies (Governance)
- Define rules to enforce organizational standards (e.g., region restrictions, SKU limitations).
- Can be assigned at subscription, resource group, or resource level.
- Example policy: Only allow VM creation in `South Africa North`.

---

## 📁 Folder Structure (in repo)
```
azure-license-rg-management/
├── screenshots/
│   ├── 01_license_assignment.png
│   ├── 02_rg_user_assignment.png
│   ├── 03_tags_usage.png
│   └── 04_resource_lock.png
├── README.md
```

---

## ✅ Next Steps
- Apply role-based access control (RBAC) to these resource groups.
- Combine governance tools (locks, tags, policies) with automation.
- Track usage and compliance using Azure Monitor and Cost Management.

---

## 🔗 Learn More
- [Azure Tags](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources)
- [Azure Resource Locks](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources)
- [Azure Policy](https://learn.microsoft.com/en-us/azure/governance/policy/overview)

---

#️⃣ #AzureGovernance #RBAC #ResourceGroups #CloudManagement #LearningInPublic #HybridSkills #AzureLabs
