# Githubproject
<apex:page standardcontroller="Lead" setup="true" showHeader="true"  >
   <apex:sectionHeader title=" Subleads" rendered="true"/>
    <apex:form>
       <apex:pageBlock title="LeadInfo" >
       <apex:pageBlocksection columns="1">
          <apex:inputField value = "{!lead.budget}"/>
            <apex:inputField value= "{!lead.name}"/>
               <apex:inputField value = "{Lead.BudgetAmount}"/>
                  <apex:inputField value= "{!lead.Title}"/> 
                       <apex:inputField value= "{!lead.Email}"/>
                          <apex:inputField value= "{!lead.fax}"/>
                          <apex:input Field value= "/}
                             <apex:inputField value="{!lead.phone}"/>
                     <apex:commandButton value= "submit" action="{!save}"/>
              </apex:pageBlocksection>
         </apex:pageblock>
  </apex:form>
 </apex:page>
