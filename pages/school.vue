<style>
.legal-agreemnt-block {
    background-color: #F9F9F9;
    padding: 20px;
    margin-bottom: 20px;
}
.legal-agreemnt-block iframe {
    background-color: white;
    border: 1px solid #979797;
}
</style>
<template>
<Yogaheader/>
<section id="yas-dnncontent" class="yas-Col12">
		<div class="yas-dnnrow">
			<div class="yas-marginlr" id="yas-main-content">

				  <div id="dnn_ContentPane" class="yas-ContentPane"><div class="DnnModule DnnModule-SchoolNewRegisteration DnnModule-4020"><a name="4020"></a><div id="dnn_ctr4020_ContentPane"><!-- Start_Module_4020 --><div id="dnn_ctr4020_ModuleContent" class="DNNModuleContent ModSchoolNewRegisterationC">
<input type="hidden" id="hdModuleId" value="4020">
<input type="hidden" id="hdTabId" value="1260">

<input type="hidden" name="dnn$ctr4020$View$HdCurrentStep" id="dnn_ctr4020_View_HdCurrentStep" value="Start">
<div id="SpecialWordDetectedDialog" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3 class="modal-title">Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p class="bodyDescription">Your Directory Name has one or more restricted words</p>
        <strong class="YA_RestriectedWords"></strong>
        <p class="additionalText"></p>
        <p class="allText" style="display: none"></p>
        <p class="footerOfBody">Please replace or remove the highlighted language.</p>
        <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMore" class="ya-action-external" target="_blank">Learn More</a>
    </div>
    <div class="modal-footer">
        <button type="button" id="SpecialWordDetectedDialogAnotherBtn" class="btn" data-dismiss="modal" style="display: none">OK</button>
        <button type="button" id="SpecialWordDetectedDialogOK" class="btn" data-dismiss="modal">OK</button>

    </div>
</div>
<div id="RemoveDisclaimerDialog" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3 class="modal-title">Remove Disclaimer</h3>
    </div>
    <div class="modal-body">
        <p>Are you sure you want to remove your school disclaimer?</p>

    </div>
    <div class="modal-footer">
        <button type="button" id="BtnRemove" class="btn" data-dismiss="modal">Yes, Remove</button>
        <button type="button" id="BtnCancel" class="btn" data-dismiss="modal">No, Cancel</button>
    </div>
</div>

<div id="schoolAddDisclaimerModal" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3>Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p>In accordance with our <a href="https://devteam.yogaalliance.org/YogaTherapyPolicy" id="dnn_ctr4020_View_ctl07_HrefYogaTherapyPolicy" target="_blank" class="ya-action-external">Yoga Therapy Policy</a> the following words may not be used unless they are part of your school's legal name:
        </p>

        <p class="YA_RestriectedWords"></p>

        <p>If you wish to continue with this school name:</p>

        <p class="allText ya-semi-strong"></p>

        <p>Please fill out the disclaimer. (This disclaimer will appear on your profile and directory listing)</p>

        <p>
            <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMore1" class="ya-action-external" target="_blank">Learn More</a>
        </p>
    </div>
    <div class="modal-footer">
        <a class="btn btn-default" id="ShowFillDisclaimer" data-dismiss="modal">Add Disclaimer</a>
        <a class="btn btn-default" data-dismiss="modal" onclick=" closeCustomModal(&#39;schoolAddDisclaimerModal&#39;) ">Change School Name</a>
    </div>
</div>

<div id="SpecialWordDetectedDialogForDirectoryName" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3 class="modal-title">Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p>Your Directory Name has one or more restricted words:</p>
        <strong class="YA_RestriectedWords">Yoga Therapy</strong>
        <p>Please replace or remove the highlighted language. </p>
        <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMoreDirectoryName" class="ya-action-external" target="_blank">Learn More</a>
    </div>
    <div class="modal-footer">
        <button type="button" id="SpecialWordDetectedDialogForDirectoryNameOK" class="btn" data-dismiss="modal" onclick=" closeCustomModal(&#39;SpecialWordDetectedDialogForDirectoryName&#39;) ">OK</button>
    </div>
</div>

<div id="SpecialWordDetectedDialogForDisplayName" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true" style="cursor: default">
    <div class="modal-header">
        <h3 class="modal-title">Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p>Your Display Name has one or more restricted words:</p>
        <strong class="YA_RestriectedWords">Yoga Therapy</strong>
        <p>Please replace or remove the highlighted language. </p>
        <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMoreDisplayName" class="ya-action-external" target="_blank" style="cursor:pointer">Learn More</a>
    </div>
    <div class="modal-footer">
        <button type="button" id="SpecialWordDetectedDialogForDisplayNameOK" class="btn" data-dismiss="modal" onclick=" closeCustomModal(&#39;SpecialWordDetectedDialogForDisplayName&#39;) ">OK</button>
    </div>
</div>
<div class="row-fluid">
    <div class="container-fluid ya-main-content ya-school-registration ya-standard-page">
        <div class="multi-step five-steps numbered color-ya hidden">
            <ol id="SchoolNewRegistrationSteps">
                <li class="current">
                    <div id="dnn_ctr4020_View_BtnStartState" class="wrap hidden-phone">
                    </div>
                </li>
                <li>
                    <div id="dnn_ctr4020_View_BtnPeopleState" class="wrap hidden-phone"></div>
                </li>
            </ol>
        </div>
        <!--CDF(Javascript|/DesktopModules/YA.Client/viewmodels/createschool/createschool-viewmodels.js?cdv=461)-->
<!--CDF(Javascript|/DesktopModules/YA.Client/viewmodels/Teacher/TeacherRegistration/TeacherRegistration-viewmodels.js?cdv=461)-->


<input type="hidden" name="dnn$ctr4020$View$UcCreateSchool$HSchoolId" id="dnn_ctr4020_View_UcCreateSchool_HSchoolId">
<div id="dnn_ctr4020_View_UcCreateSchool_createSchoolPanel" onkeypress="javascript:return WebForm_FireDefaultButton(event, &#39;dnn_ctr4020_View_UcCreateSchool_BtnContinue&#39;)">
<div class="content">
        <section class="ya-main ya-school-registration-1">
            <h1 class="ya-page-title" style="border-bottom: none; margin-bottom: 15px; padding-bottom: 0;">School Creation</h1>
            <h1 class="ya-page-title" style="border-bottom: none; margin-bottom: 15px; padding-bottom: 0; color: black; font-size: 25px;">Contact Information</h1>
            <div class="row-fluid">
                <div class="span8">
                    <div class="ya-warning-box" id="DivErrorEnglish" style="display: none">
                        <span class="ya-warning-icon" data-icon="R"></span>
                        To be found in the YA Registry, please only use English characters in your school name.
                    </div>
                    <div class="ya-school-name">
                        <label for="TxtSchoolName">
                            School Name <span class="ya-required" style="font-size: 14px;">*</span>
                        </label>
                        <div style="max-width: 500px"><input name="dnn$ctr4020$View$UcCreateSchool$TxtSchoolName"  style= "width: 100%;" type="text" maxlength="200" id="TxtSchoolName" tabindex="1" onkeydown="onKeyDownSchoolName(event)" data-validateyogatherapy="True" data-yogatherapycontainerid="dnn_ctr4020_View_UcCreateSchool_createSchoolPanel" data-yogatherapysubmitid="dnn_ctr4020_View_UcCreateSchool_BtnContinue" data-yogatherapymodalid="schoolAddDisclaimerModal" data-validatefield="True" data-callback="callBackAfterChecking"></div>
                        <span id="dnn_ctr4020_View_UcCreateSchool_rfvSchoolName" class="ya-validation-message" style="display:none;"><br>Please enter a School Name</span>
                        <span id="dnn_ctr4020_View_UcCreateSchool_ctl02" class="ya-validation-message" style="display:none;"></span>
                    </div>
                </div>
            </div>
            <div class="span8">
                <div class="row">
                    
                    <div id="DivAdditionalContactInformation" class="control-group input-xlarge">
                        <label class="ya-label">
                            Phone Number</label>
                        <div style="width: 100%">
                            <input name="dnn$ctr4020$View$UcCreateSchool$TxtPhoneInfo" type="text" id="dnn_ctr4020_View_UcCreateSchool_TxtPhoneInfo" tabindex="8" class="input-block-level" style= "width: 200%;">
                            <span id="dnn_ctr4020_View_UcCreateSchool_REV_Phone" class="ya-validation-message" style="display:none;"><br>Please enter a valid Phone</span>
                            <div class="help-block" style="margin-bottom: 20px;"><em>e.g. 123456789</em></div>
                        </div>

                        <label class="ya-label">Email</label>
                        <div style="width: 100%">
                            <input name="dnn$ctr4020$View$UcCreateSchool$TxtSkypeInfo" type="text" id="dnn_ctr4020_View_UcCreateSchool_TxtSkypeInfo" class="input-block-level" tabindex="9" style= "width: 200%;">
                        </div>
                    </div>
                </div>

            </div>
            
        </section>
        </div>
</div></div></div></div>
</div></div></div></div>
</div>
</section>
<section id="yas-dnncontent" class="yas-Col12">
<div class="yas-dnnrow">
<div class="yas-marginlr" id="yas-main-content">
<div id="dnn_ContentPane" class="yas-ContentPane"><div class="DnnModule DnnModule-SchoolNewRegisteration DnnModule-4020"><a name="4020"></a><div id="dnn_ctr4020_ContentPane"><!-- Start_Module_4020 --><div id="dnn_ctr4020_ModuleContent" class="DNNModuleContent ModSchoolNewRegisterationC">
<div class="row-fluid">
<div class="container-fluid ya-main-content ya-school-registration ya-standard-page">
<h1 class="ya-page-title" style="border-bottom: none; margin-bottom: 15px; padding-bottom: 0; color: black; font-size: 27px;">Your School Staff</h1>
<br/>
<div id="staff-grid" style="max-inline-size: 564px; display:none;">
<table id="schooltable">
<thead>
    <tr>
        <label style="display: inline; font-weight: bold; margin-left: 10px; margin-right: 115px;">Name</label>
        <label style="display: inline; font-weight: bold; margin-right: 110px;">Roles</label>
        <label style="display: inline; font-weight: bold; color: maroon; margin-right: 10px; margin-left: 44px;">Status</label>
    </tr>
</thead>
<tbody>
</tbody>
</table>
</div>
<br/>
<div id="AddStaffButton">
<button type="button" id="searchButton" class="btn btn-orange btn-medium" @click="searchButtonClicked">Add a Staff Member</button>
</div>
<div id="StaffSearchParameters" style="display:none; background: #F9F9F9;;border: 2px solid black;padding: 39px;margin: 20px;">
<h1 class="ya-page-title" style="border-bottom: none; margin-bottom: 15px; padding-bottom: 0;">Add School Staff</h1>
<hr>
    <label style="display: inline; margin-right: 120px;">Search by</label>
    <label style="display: inline;">Name</label>
    <div>
        <select v-model="searchParamterCriteria" name="SearchByParameter" id="SearchByParameter" style="width: 150px; height: 25px;  margin-right: 20px;">
            <option value="Name">Name</option>
            <option value="Email">Email</option>
            <option value="ID" selected>ID</option>
        </select>
        <input style="display: inline; width: 150px; height: 15px;" type="text" v-model="searchParameterValue" id="searchParameter">
    </div>
    <button class="btn btn-orange btn-medium"  id="searchButton1" @click="submit">Search </button>
<br>
    <br>
    <br><hr>
    <div id="SearchGrid" style="display:none">
    <table id="schooltable1">
        <thead>
            <tr>
                <label style="display: inline; font-weight: bold; margin-left: 10px; margin-right: 115px;">Name</label>
                <label style="display: inline; font-weight: bold; margin-right: 110px;">Designation</label>
                <label style="display: inline; font-weight: bold; color: maroon; margin-right: 10px;">Location</label>
            </tr>
        </thead>
        <tbody>
        </tbody>
    </table>
    </div>
    <br/>
    <button type="button" id="CancelButton2" class="btn" style=" background-color: white; border-color: orange; width: 77px; height: 31px; color: orange;" @click="searchStaff">Cancel</button>
</div>
</div></div></div></div>
</div></div>
</div></div>
</section>
<section id="yas-dnncontent" class="yas-Col12">
		<div class="yas-dnnrow">
			<div class="yas-marginlr" id="yas-main-content">

				  <div id="dnn_ContentPane" class="yas-ContentPane"><div class="DnnModule DnnModule-SchoolNewRegisteration DnnModule-4020"><a name="4020"></a><div id="dnn_ctr4020_ContentPane"><!-- Start_Module_4020 --><div id="dnn_ctr4020_ModuleContent" class="DNNModuleContent ModSchoolNewRegisterationC">

<input type="hidden" id="hdModuleId" value="4020">
<input type="hidden" id="hdTabId" value="1260">

<input type="hidden" name="dnn$ctr4020$View$HdCurrentStep" id="dnn_ctr4020_View_HdCurrentStep" value="LegalAgreement">
<!--CDF(Javascript|/DesktopModules/YA.Client/viewmodels/YogaTherapy/YogaTherapyValidation-viewmodels.js?cdv=461)-->
<!--CDF(Javascript|/DesktopModules/YA.Client/dataservices/YogaTherapy/YogaTherapy-dataservices.js?cdv=461)-->


<div id="SpecialWordDetectedDialog" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3 class="modal-title">Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p class="bodyDescription">Your Directory Name has one or more restricted words</p>
        <strong class="YA_RestriectedWords"></strong>
        <p class="additionalText"></p>
        <p class="allText" style="display: none"></p>
        <p class="footerOfBody">Please replace or remove the highlighted language.</p>
        <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMore" class="ya-action-external" target="_blank">Learn More</a>
    </div>
    <div class="modal-footer">
        <button type="button" id="SpecialWordDetectedDialogAnotherBtn" class="btn" data-dismiss="modal" style="display: none">OK</button>
        <button type="button" id="SpecialWordDetectedDialogOK" class="btn" data-dismiss="modal">OK</button>

    </div>
</div>

<div id="RemoveDisclaimerDialog" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3 class="modal-title">Remove Disclaimer</h3>
    </div>
    <div class="modal-body">
        <p>Are you sure you want to remove your school disclaimer?</p>

    </div>
    <div class="modal-footer">
        <button type="button" id="BtnRemove" class="btn" data-dismiss="modal">Yes, Remove</button>
        <button type="button" id="BtnCancel" class="btn" data-dismiss="modal">No, Cancel</button>
    </div>
</div>

<div id="schoolAddDisclaimerModal" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3>Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p>In accordance with our <a href="https://devteam.yogaalliance.org/YogaTherapyPolicy" id="dnn_ctr4020_View_ctl07_HrefYogaTherapyPolicy" target="_blank" class="ya-action-external">Yoga Therapy Policy</a> the following words may not be used unless they are part of your school's legal name:
        </p>

        <p class="YA_RestriectedWords"></p>

        <p>If you wish to continue with this school name:</p>

        <p class="allText ya-semi-strong"></p>

        <p>Please fill out the disclaimer. (This disclaimer will appear on your profile and directory listing)</p>

        <p>
            <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMore1" class="ya-action-external" target="_blank">Learn More</a>
        </p>
    </div>
    <div class="modal-footer">
        <a class="btn btn-default" id="ShowFillDisclaimer" data-dismiss="modal">Add Disclaimer</a>
        <a class="btn btn-default" data-dismiss="modal" onclick=" closeCustomModal(&#39;schoolAddDisclaimerModal&#39;) ">Change School Name</a>
    </div>
</div>

<div id="SpecialWordDetectedDialogForDirectoryName" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true">
    <div class="modal-header">
        <h3 class="modal-title">Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p>Your Directory Name has one or more restricted words:</p>
        <strong class="YA_RestriectedWords">Yoga Therapy</strong>
        <p>Please replace or remove the highlighted language. </p>
        <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMoreDirectoryName" class="ya-action-external" target="_blank">Learn More</a>
    </div>
    <div class="modal-footer">
        <button type="button" id="SpecialWordDetectedDialogForDirectoryNameOK" class="btn" data-dismiss="modal" onclick=" closeCustomModal(&#39;SpecialWordDetectedDialogForDirectoryName&#39;) ">OK</button>
    </div>
</div>

<div id="SpecialWordDetectedDialogForDisplayName" class="modal hide fade" tabindex="-1" role="dialog" aria-hidden="true" style="cursor: default">
    <div class="modal-header">
        <h3 class="modal-title">Further Action Needed</h3>
    </div>
    <div class="modal-body">
        <p>Your Display Name has one or more restricted words:</p>
        <strong class="YA_RestriectedWords">Yoga Therapy</strong>
        <p>Please replace or remove the highlighted language. </p>
        <a href="https://devteam.yogaalliance.org/YogaTherapyLearnMore" id="dnn_ctr4020_View_ctl07_HrefLearnMoreDisplayName" class="ya-action-external" target="_blank" style="cursor:pointer">Learn More</a>
    </div>
    <div class="modal-footer">
        <button type="button" id="SpecialWordDetectedDialogForDisplayNameOK" class="btn" data-dismiss="modal" onclick=" closeCustomModal(&#39;SpecialWordDetectedDialogForDisplayName&#39;) ">OK</button>
    </div>
</div>
<div class="row-fluid">
    <div class="container-fluid ya-main-content ya-school-registration ya-standard-page">
        <div class="multi-step five-steps numbered color-ya hidden">
            <ol id="SchoolNewRegistrationSteps">
                <li>
                    <div id="dnn_ctr4020_View_BtnStartState" class="wrap hidden-phone">
                    </div>
                </li>
                <li>
                    <div id="dnn_ctr4020_View_BtnPeopleState" class="wrap hidden-phone"></div>
                </li>
            </ol>
        </div>
        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$HSchoolId" id="dnn_ctr4020_View_ucLegalAgreement_HSchoolId" value="15707">
<div id="dnn_ctr4020_View_ucLegalAgreement_legalAgreementPanel">
		
    <div class="content">
        <section id="dnn_ctr4020_View_ucLegalAgreement_secAgreementView" class="ya-main ya-school-registration-1">

            <div class="row-fluid">
                <div class="span10">

                    <h1 style="margin-bottom: 20px; color: #B4341D;">Legal Agreements</h1>
                    <p style="margin-bottom: 30px;">
                        You must read and accept the Yoga Alliance legal agreements below. These are separate from the policies under which your school operates that you will be asked to upload in Part One of your application.
                    </p>


                    <div class="legal-agreemnt-block">
                        <div>
                            <h4 class="span8">RYS Ownership Agreement</h4>
                            <div class="span4">
                                <a id="dnn_ctr4020_View_ucLegalAgreement_btnDownloadOwnershipAgreement" class="pull-right" href="javascript:__doPostBack(&#39;dnn$ctr4020$View$ucLegalAgreement$btnDownloadOwnershipAgreement&#39;,&#39;&#39;)">Download Policy</a>
                            </div>
                        </div>
                        <p>
                            <iframe src="/rysOwnershipAgreement" id="dnn_ctr4020_View_ucLegalAgreement_frmLegalAgreement" width="100%" height="200" style="padding: 15px 0px 15px 15px; background-color: white; border: 1px solid #979797;"></iframe>
                        </p>
                        <label class="checkbox">
                            




<span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck">
    <span class="ya-check-icon" tabindex="1" onchange="validateSchoolLegalAgreement(&#39;CCB_CbLegalAgreementCheck_CustomCheckBox&#39;, &#39;LnkLegalAgreementAcceptedValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck_CustomCheckBox" type="checkbox" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbLegalAgreementCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbLegalAgreementCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbLegalAgreementCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck_HdClientDate">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbLegalAgreementCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">
    
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbLegalAgreementCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck_HdIsViewLnkseen">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbLegalAgreementCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbLegalAgreementCheck_HdIsRequiredToSeeLnk">
</span>


                            I have read and accept the RYS Ownership Agreement.
                        </label>
                        <div class="ya-validation-message hidden" id="LnkLegalAgreementAcceptedValidationMsg">Please accept the RYS Ownership Agreement.</div>
                    </div>

                    <div class="legal-agreemnt-block">
                        <div>
                            <h4 class="span8">Scope of Practice</h4>
                            <div class="span4">
                                <a id="dnn_ctr4020_View_ucLegalAgreement_btnDownloadScopeOfPolicy" class="pull-right" href="javascript:__doPostBack(&#39;dnn$ctr4020$View$ucLegalAgreement$btnDownloadScopeOfPolicy&#39;,&#39;&#39;)">Download Policy</a>
                            </div>
                        </div>
                        <p>
                            <iframe src="/scopeOfPractice" id="dnn_ctr4020_View_ucLegalAgreement_frmScopeOfPractice" width="100%" height="200" style="padding: 15px 0px 15px 15px; background-color: white; border: 1px solid #979797;"></iframe>
                        </p>
                        <label class="checkbox">
                            




<span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck">
    <span class="ya-check-icon" tabindex="1" onchange="validateSchoolLegalAgreement(&#39;CCB_CbScopeOfPracticeCheck_CustomCheckBox&#39;, &#39;LnkScopeOfPracticeValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_CustomCheckBox" type="checkbox" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDate">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">
    
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsViewLnkseen">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsRequiredToSeeLnk">
</span>


                            I have read and accept the Scope of Practice.
                        </label>
                        <div class="ya-validation-message hidden" id="LnkScopeOfPracticeValidationMsg">Please accept the Scope of Practice.</div>
                    </div>

                    <div class="legal-agreemnt-block">
                        <div>
                            <h4 class="span8">Code of Conduct</h4>
                            <div class="span4">
                                <a id="dnn_ctr4020_View_ucLegalAgreement_btnDownloadCodeOfConduct" class="pull-right" href="javascript:__doPostBack(&#39;dnn$ctr4020$View$ucLegalAgreement$btnDownloadCodeOfConduct&#39;,&#39;&#39;)">Download Policy</a>
                            </div>
                        </div>
                        <p>
                            <iframe src="/codeOfConduct" id="dnn_ctr4020_View_ucLegalAgreement_frmCodeOfConduct" width="100%" height="200" style="padding: 15px 0px 15px 15px; background-color: white; border: 1px solid #979797;"></iframe>
                        </p>
                        <label class="checkbox">
                            




<span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck">
    <span class="ya-check-icon" tabindex="2" onchange="validateSchoolLegalAgreement(&#39;CCB_CbCodeConductCheck_CustomCheckBox&#39;, &#39;LnkCodeOfConductAcceptedValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck_CustomCheckBox" type="checkbox" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbCodeConductCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbCodeConductCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbCodeConductCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck_HdClientDate">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbCodeConductCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">
    
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbCodeConductCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck_HdIsViewLnkseen">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbCodeConductCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbCodeConductCheck_HdIsRequiredToSeeLnk">
</span>


                            I have read and accept the Code of Conduct.
                        </label>
                        <div class="ya-validation-message hidden" id="LnkCodeOfConductAcceptedValidationMsg">Please accept the Code of Conduct.</div>
                    </div>



                    <div class="legal-agreemnt-block">
                        <div>
                            <h4 class="span8">Yoga Therapy Policy</h4>
                            <div class="span4">
                                <a id="dnn_ctr4020_View_ucLegalAgreement_btnDownloadYogaTherapy" class="pull-right" href="javascript:__doPostBack(&#39;dnn$ctr4020$View$ucLegalAgreement$btnDownloadYogaTherapy&#39;,&#39;&#39;)">Download Policy</a>
                            </div>
                        </div>
                        <p>
                            <iframe src="/yogaTherapyPolicy" id="dnn_ctr4020_View_ucLegalAgreement_frmYogaTherapyPolicy" width="100%" height="200" style="padding: 15px 0px 15px 15px; background-color: white; border: 1px solid #979797;"></iframe>
                        </p>
                        <label class="checkbox">
                            




<span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck">
    <span class="ya-check-icon" tabindex="3" onchange="validateSchoolLegalAgreement(&#39;CCB_CbTherapyAgreementCheck_CustomCheckBox&#39;, &#39;LnkTherapyAgreementAcceptedValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck_CustomCheckBox" type="checkbox" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbTherapyAgreementCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbTherapyAgreementCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbTherapyAgreementCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck_HdClientDate">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbTherapyAgreementCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">
    
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbTherapyAgreementCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck_HdIsViewLnkseen">
    <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbTherapyAgreementCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbTherapyAgreementCheck_HdIsRequiredToSeeLnk">
</span>


                            I have read and accept the Yoga Therapy Policy.
                        </label>
                        <div class="ya-validation-message hidden" id="LnkTherapyAgreementAcceptedValidationMsg">Please accept the Yoga Therapy Policy.</div>
                    </div>
                    <div style="margin-top: 50px;">
                        <p style="font-size: 12px;">
                            Clicking “Continue” will direct you to OpenWater’s platform to proceed with your application. Yoga Alliance does not own or operate OpenWater, 
                            and OpenWater has its own <a href="https://www.getopenwater.com/the-company/security/" target="_blank">Security Policy</a> to safeguard your information. Please note: Yoga Alliance requires that its third-party platforms have stringent protections in place, which are subject to annual audits. OpenWater’s Security Policy provides that OpenWater keeps your data private and safe, protects your account from cyberattack, provides a controlled physical environment for your data, and performs nightly offsite backup of your data.  
                        </p>
                    </div>

                </div>
            </div>

            <div class="fluid-row">
                <div class="ya-widget ya_begin-application span8">
                    <div class="ya-continue-btn">
                        <input type="submit" name="dnn$ctr4020$View$ucLegalAgreement$BtnDecline" value="Cancel" id="dnn_ctr4020_View_ucLegalAgreement_BtnDecline" tabindex="5" class="btn btn-default input-medium" style=" background-color: white; border-color: orange; width: 174px; height: 40px; color: orange;">
                        <input type="submit" name="dnn$ctr4020$View$ucLegalAgreement$BtnContinue" value="Save & Continue" @click="redirecttoNext" id="dnn_ctr4020_View_ucLegalAgreement_BtnContinue" tabindex="4" class="btn btn-orange btn-large" style=" width: 174px; height: 40px;">  
                    </div>
                </div>
            </div>
        </section>
            </div>

	</div>


        
    </div>
</div>
</div><!-- End_Module_4020 --></div>


</div></div>
			
			</div>
		</div>
	</section>

<Yogafooter/>
<Yogaheadlinks/>
</template>

<script setup>

const searchParamterCriteria = ref('');
const searchParameterValue = ref('');
const name = ref('');
const teacherList = [{id :875 ,name : "wilson" ,email: "wilson4545@gmail.com",designation: "Yoga Teacher", location: "Arlington, VA", roles: "developer", status: "APPROVED" },
{id :213 ,name : "Kris" ,email: "kris@gmail.com",designation: "E-RYT 500", location: "Arlington, VA", roles: "developer", status: "APPROVED" },
{id :896 ,name : "Manu" ,email: "manu.h@gmail.com",designation: "School Owner", location: "Arlington, VA", roles: "developer", status: "PENDING CONFIRMATION" },
{id :7965 ,name : "Mathew" ,email: "mathewjohns@gmail.com",designation: "RYT 500", location: "Arlington, VA", roles: "developer", status: "APPROVED" },
{id :86896 ,name : "Roger" ,email: "rogerphilip@gmail.com",designation: "RYT 500", location: "Arlington, VA", roles: "developer", status: "APPROVED" },
{id :786 ,name : "Jasmin" ,email: "jasmin231@gmail.com",designation: "RYT 500", location: "London", roles: "developer", status: "DECLINED" },
{id :2678 ,name : "George" ,email: "grorge.gen@gmail.com",designation: "E-RYT 500", location: "Arlington, VA", roles: "developer", status: "PENDING CONFIRMATION" }];
var list = [];
function redirecttoNext(){
    navigateTo("/ProgramInformation");
}
function searchButtonClicked(){
    console.log("clicked");
    var x =document.getElementById("StaffSearchParameters");
    if(x.style.display == "none"){
        x.style.display = "block";
    }
    else{
        x.style.display = "none";
    }
}

function addButtonClicked(element){
    let id = element.getAttribute("data-id");
    console.log(id);
    var newItem = findTeacher("id",id);
    updateTeacherList(newItem);
    debugger;
    element.parentElement.remove()
    
}

function findTeacher(criteria,value){
        return  teacherList.filter(function (el) {
        return el[criteria] == value;
      });  
}

function updateTeacherList(list){
    var table = document.getElementById('schooltable');        
    for (var i = 0; i < list.length; i++){
        var tr= document.createElement('div'); 
        tr.style="height: 70px; font-size: 20px; border-radius: 10px; padding: 10px; border: 2px solid lightgray; background-color: white;";

        var td1 = document.createElement('label');
        td1.style="display: inline; font-weight: bold; margin-right: 50px;";
        var td2 = document.createElement('label');
        td2.style="display: inline; font-weight: bold; margin-right: 130px;";
        var td3 = document.createElement('label');
        td3.style="display: inline; font-weight: bold; margin-right: 130px;";

        var text1 = document.createTextNode(list[i].name);
        var text2 = document.createTextNode(list[i].designation);
        var text3 = document.createTextNode(list[i].location);

        td1.appendChild(text1);
        td2.appendChild(text2);
        td3.appendChild(text3);
        tr.appendChild(td1);
        tr.appendChild(td2);
        tr.appendChild(td3);
        table.appendChild(tr);
    }
}

function updateList(list){
    var table = document.getElementById('schooltable1');
    table.querySelectorAll('tbody').forEach((tbody, i) => {
        if (i !== 0) {
            table.removeChild(tbody);
        }
    });
    var new_tbody = document.createElement('tbody');
        
    for (var i = 0; i < list.length; i++){
        var tr= document.createElement('div'); 
        tr.style="height: 70px; font-size: 20px; border-radius: 10px; padding: 10px; border: 2px solid lightgray; background-color: white;";

        var td1 = document.createElement('label');
        td1.style="display: inline; font-weight: bold; margin-right: 50px;";
        var td2 = document.createElement('label');
        td2.style="display: inline; font-weight: bold; margin-right: 130px;";
        var td3 = document.createElement('label');
        td3.style="display: inline; font-weight: bold; margin-right: 130px;";
        var bt1 = document.createElement('button');
        bt1.style="border-radius: 5px;";
        bt1.innerHTML="Add";
        bt1.setAttribute("data-id", list[i].id);
        bt1.onclick = function(e,event){
            e.preventDefault();
            addButtonClicked(e.target);
            var grid1 =document.getElementById("staff-grid");
            grid1.style.display = "block";
            };

        var text1 = document.createTextNode(list[i].name);
        var text2 = document.createTextNode(list[i].designation);
        var text3 = document.createTextNode(list[i].location);

        td1.appendChild(text1);
        td2.appendChild(text2);
        td3.appendChild(text3);
        tr.appendChild(td1);
        tr.appendChild(td2);
        tr.appendChild(td3);
        tr.appendChild(bt1);

        new_tbody.appendChild(tr);
    }
    table.appendChild(new_tbody);
}

async function submitApi(){
    let url = "https://devteam.yogaalliance.org/DesktopModules/YAServices/API/Trainers/List?";
    let criteria;
    if(searchParamterCriteria.value == "ID"){
      url = url+"RegistryId="+searchParameterValue.value;
      criteria = "id";
    }
    else if(searchParamterCriteria.value  == "Name"){
        url = url + "ExactName="+searchParameterValue.value;
        criteria = "name";
    }
    else{
        url = url + "Email="+searchParameterValue.value;
        criteria = "email";
    }
    var x =document.getElementById("SearchGrid");
    x.style.display = "none"
    x.style.display = "block"
    //await $fetch( url, {
    //    method: 'GET',
    //    header: {"OpwDnnSharedKey": "d%vC&5$Uf&8ZuDTm5xd-XFFxrAYNQuK#H$XmZ+gs"}
    //});

    list =findTeacher();   
}
function submit(){
    let url = "https://devteam.yogaalliance.org/DesktopModules/YAServices/API/Trainers/List?";
    let criteria;
    if(searchParamterCriteria.value == "ID"){
      url = url+"RegistryId="+searchParameterValue.value;
      criteria = "id";
    }
    else if(searchParamterCriteria.value  == "Name"){
        url = url + "ExactName="+searchParameterValue.value;
        criteria = "name";
    }
    else{
        url = url + "Email="+searchParameterValue.value;
        criteria = "email";
    }

    list =findTeacher(criteria,searchParameterValue.value);  
    updateList(list);
    console.log(list);
    var grid =document.getElementById("SearchGrid");
    grid.style.display = "block";
    console.log("clicked");
}
</script>