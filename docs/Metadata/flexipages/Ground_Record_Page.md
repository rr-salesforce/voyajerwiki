---
layout: default
title: Ground_Record_Page
parent: flexipages
grand_parent: Metadata
---
# Metadata Type
flexipages


# Filename 
Ground_Record_Page


# Raw XML
```
<?xml version="1.0" encoding="UTF-8"?>
<FlexiPage xmlns="http://soap.sforce.com/2006/04/metadata">
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>collapsed</name>
                    <value>false</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>hideChatterActions</name>
                    <value>false</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>numVisibleActions</name>
                    <value>3</value>
                </componentInstanceProperties>
                <componentName>force:highlightsPanel</componentName>
                <identifier>force_highlightsPanel</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>header</name>
        <type>Region</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>parentFieldApiName</name>
                    <value>Ground__c.Id</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>relatedListApiName</name>
                    <value>Ground__r</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>relatedListComponentOverride</name>
                    <value>NONE</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>rowsToDisplay</name>
                    <value>10</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>showActionBar</name>
                    <value>true</value>
                </componentInstanceProperties>
                <componentName>force:relatedListSingleContainer</componentName>
                <identifier>force_relatedListSingleContainer</identifier>
            </componentInstance>
        </itemInstances>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>parentFieldApiName</name>
                    <value>Ground__c.Id</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>relatedListApiName</name>
                    <value>Concessions__r</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>relatedListComponentOverride</name>
                    <value>NONE</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>rowsToDisplay</name>
                    <value>10</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>showActionBar</name>
                    <value>true</value>
                </componentInstanceProperties>
                <componentName>force:relatedListSingleContainer</componentName>
                <identifier>force_relatedListSingleContainer2</identifier>
            </componentInstance>
        </itemInstances>
        <itemInstances>
            <componentInstance>
                <componentName>force:detailPanel</componentName>
                <identifier>force_detailPanel</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>detailTabContent</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>active</name>
                    <value>true</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>body</name>
                    <value>detailTabContent</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>title</name>
                    <value>Standard.Tab.detail</value>
                </componentInstanceProperties>
                <componentName>flexipage:tab</componentName>
                <identifier>detailTab</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>maintabs</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>tabs</name>
                    <value>maintabs</value>
                </componentInstanceProperties>
                <componentName>flexipage:tabset</componentName>
                <identifier>flexipage_tabset</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>main</name>
        <type>Region</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentName>runtime_sales_activities:activityPanel</componentName>
                <identifier>runtime_sales_activities_activityPanel</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>activityTabContent</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>active</name>
                    <value>true</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>body</name>
                    <value>activityTabContent</value>
                </componentInstanceProperties>
                <componentInstanceProperties>
                    <name>title</name>
                    <value>Standard.Tab.activity</value>
                </componentInstanceProperties>
                <componentName>flexipage:tab</componentName>
                <identifier>activityTab</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>sidebartabs</name>
        <type>Facet</type>
    </flexiPageRegions>
    <flexiPageRegions>
        <itemInstances>
            <componentInstance>
                <componentInstanceProperties>
                    <name>tabs</name>
                    <value>sidebartabs</value>
                </componentInstanceProperties>
                <componentName>flexipage:tabset</componentName>
                <identifier>flexipage_tabset2</identifier>
            </componentInstance>
        </itemInstances>
        <mode>Replace</mode>
        <name>sidebar</name>
        <type>Region</type>
    </flexiPageRegions>
    <masterLabel>Ground Record Page</masterLabel>
    <parentFlexiPage>flexipage__default_rec_L</parentFlexiPage>
    <sobjectType>Ground__c</sobjectType>
    <template>
        <name>flexipage:recordHomeTemplateDesktop</name>
    </template>
    <type>RecordPage</type>
</FlexiPage>
```


# Last Modified


# Usage