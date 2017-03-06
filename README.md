# DXConvertExample
Repository containing an example of the issue I'm seeing converting existing source.

There is a single lightning application named AMS_PackageManager.

Executing :

    sfdx force:mdapi:convert --rootdir FromOrg'

converts this to a customApplication:

    State  Full Name              Type               Workspace Path
    ─────  ─────────────────────  ─────────────────  ──────────────────────────────────────────────────────────────────────
    Add    AMS_PackageManagement  CustomApplication  force-app/main/default/applications/AMS_PackageManagement.app-meta.xml
