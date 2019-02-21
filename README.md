# Githubproject
<apex:page standardcontroller="Lead" setup="true" showHeader="true"  >
   <apex:sectionHeader title=" Subleads" rendered="true"/>
    <apex:form >
     <apex:pageBlock title="LeadInfo" >
       <apex:pageBlocksection columns="1">
         <apex:inputField value="{!lead.name}"/>
         <apex:inputField value = "{!lead.status}"/>
            <apex:inputField value="{!lead.Title}"/> 
              <apex:inputField value="{!lead.Email}"/>
                <apex:inputField value="{!lead.fax}"/>
                <apex:inputField value = "{!lead.BudgetAmount}"/>
                  <apex:inputField value="{!lead.phone}"/>
                     <apex:commandButton value="submit" action="{!save}"/>
                     <apex:commandButton values = "cancel" action = "{!Do not save}"/>
                     <apex:commadButton values = "Do not submit " action = "{!Do not insert}"/>
             </apex:pageBlocksection>
         </apex:pageblock>
  </apex:form>
 </apex:page>
