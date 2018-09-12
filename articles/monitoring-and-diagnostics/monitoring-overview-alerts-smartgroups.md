
# Smart groups
Smart groups reduce noise by allowing you to manage related alerts as a single unit rather than as individual alerts. You can view the details of smart groups and set the state similarly to how you can with alerts. Each alert is a member of one and only one smart group.

Smart groups are automatically created by using machine learning to combine related alerts that represent a single issue. When an alert is created, the algorithm adds it to a new smart group or an existing smart group based on information such as historical patterns, similar properties, and similar structure. 

Currently, the algorithm only considers alerts from the same monitor service within a subscription. Smart groups can reduce up to 99% of alert noise through this consolidation. You can view the reason that alerts were included in a group in the smart group detail page.

The name of a smart group is the name of its first alert. You can't create or rename a smart group.

### Smart Group Details Page

The Smart group detail page is displayed when you select a smart group. It provides details about the smart group, including the reasoning that was used to create the group, and enables you to change its state.
 
![Smart group detail](media/monitoring-overview-unified-alerts/smart-group-detail.png)


The smart group detail page includes the following sections.

| Section | Description |
|:---|:---|
| Alerts | Lists the individual alerts that are included in the smart group. Select an alert to open its alert detail page. |
| History | Lists each action taken by the smart group and any changes that are made to it. This is currently limited to state changes and alert membership changes. |
