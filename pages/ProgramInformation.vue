<template>
    <Yogaheader />
    <section id="yas-dnncontent" class="yas-Col12">
        <div class="yas-dnnrow">
            <div class="yas-marginlr" id="yas-main-content">

                <div id="dnn_ContentPane" class="yas-ContentPane">
                    <div class="DnnModule DnnModule-SchoolNewRegisteration DnnModule-4020">
                        <a name="4020"></a><div id="dnn_ctr4020_ContentPane">
                            <!-- Start_Module_4020 --><div id="dnn_ctr4020_ModuleContent" class="DNNModuleContent ModSchoolNewRegisterationC">
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
                                        <p>
                                            In accordance with our <a href="https://devteam.yogaalliance.org/YogaTherapyPolicy" id="dnn_ctr4020_View_ctl07_HrefYogaTherapyPolicy" target="_blank" class="ya-action-external">Yoga Therapy Policy</a> the following words may not be used unless they are part of your school's legal name:
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
                                                    <div>
                                                        <h1  class="ya-page-title" style="border-bottom: none; margin-bottom: 15px; padding-bottom: 0; display: inline;">RYS Application</h1>
                                                    <h6 style="display: inline;">  Sunstone Academy (YA ID 12345)</h6>
                                                    <svg style="margin-left: 400px; margin-right: 5px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-globe2" viewBox="0 0 16 16">
  <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855-.143.268-.276.56-.395.872.705.157 1.472.257 2.282.287V1.077zM4.249 3.539c.142-.384.304-.744.481-1.078a6.7 6.7 0 0 1 .597-.933A7.01 7.01 0 0 0 3.051 3.05c.362.184.763.349 1.198.49zM3.509 7.5c.036-1.07.188-2.087.436-3.008a9.124 9.124 0 0 1-1.565-.667A6.964 6.964 0 0 0 1.018 7.5h2.49zm1.4-2.741a12.344 12.344 0 0 0-.4 2.741H7.5V5.091c-.91-.03-1.783-.145-2.591-.332zM8.5 5.09V7.5h2.99a12.342 12.342 0 0 0-.399-2.741c-.808.187-1.681.301-2.591.332zM4.51 8.5c.035.987.176 1.914.399 2.741A13.612 13.612 0 0 1 7.5 10.91V8.5H4.51zm3.99 0v2.409c.91.03 1.783.145 2.591.332.223-.827.364-1.754.4-2.741H8.5zm-3.282 3.696c.12.312.252.604.395.872.552 1.035 1.218 1.65 1.887 1.855V11.91c-.81.03-1.577.13-2.282.287zm.11 2.276a6.696 6.696 0 0 1-.598-.933 8.853 8.853 0 0 1-.481-1.079 8.38 8.38 0 0 0-1.198.49 7.01 7.01 0 0 0 2.276 1.522zm-1.383-2.964A13.36 13.36 0 0 1 3.508 8.5h-2.49a6.963 6.963 0 0 0 1.362 3.675c.47-.258.995-.482 1.565-.667zm6.728 2.964a7.009 7.009 0 0 0 2.275-1.521 8.376 8.376 0 0 0-1.197-.49 8.853 8.853 0 0 1-.481 1.078 6.688 6.688 0 0 1-.597.933zM8.5 11.909v3.014c.67-.204 1.335-.82 1.887-1.855.143-.268.276-.56.395-.872A12.63 12.63 0 0 0 8.5 11.91zm3.555-.401c.57.185 1.095.409 1.565.667A6.963 6.963 0 0 0 14.982 8.5h-2.49a13.36 13.36 0 0 1-.437 3.008zM14.982 7.5a6.963 6.963 0 0 0-1.362-3.675c-.47.258-.995.482-1.565.667.248.92.4 1.938.437 3.008h2.49zM11.27 2.461c.177.334.339.694.482 1.078a8.368 8.368 0 0 0 1.196-.49 7.01 7.01 0 0 0-2.275-1.52c.218.283.418.597.597.932zm-.488 1.343a7.765 7.765 0 0 0-.395-.872C9.835 1.897 9.17 1.282 8.5 1.077V4.09c.81-.03 1.577-.13 2.282-.287z"/>
</svg>
<select style="width: 100px; display: inline;">
                                                                <option>English</option>
                                                                <option>やる気起こ</option>
                                                                <option>Francais</option>
                                                                <option>気を起こ</option>
                                                                <option>español</option>
                                                                <option>やる気を</option>
                                                            </select>
                                                    </div>
                                                    
                                                    <br>
                                                    <div style="background-color: lightsteelblue; width:100%; border-radius: 15px; height: 5px;">
        <div style="background-color: maroon; width:50%; color: white; height: 5px;
                border-radius: 15px;"></div>
    </div>

                                                    <div>
                                                    <h3 style="font-weight: bold;">Program Information</h3>
                                                    <br>
                                                </div>
                                                    <div class="row-fluid">
                                                        <div class="span8" style="height: 210px">
                                                            <div class="ya-warning-box" id="DivErrorEnglish" style="display: none">
                                                                <span class="ya-warning-icon" data-icon="R"></span><br>
                                                                To be found in the YA Registry, please only use English characters in your school name.
                                                            </div>
                                                            <div class="ya-school-name">
                                                                <label for="TxtSchoolName" style="font-weight: bold;">
                                                                    What is the name of your training program?
                                                                </label><br>
                                                                <div style="max-width: 500px"><input name="dnn$ctr4020$View$UcCreateSchool$TxtSchoolName" type="text" placeholder="Example School" maxlength="200" id="TxtSchoolName" tabindex="1" onkeydown="onKeyDownSchoolName(event)" data-validateyogatherapy="True" data-yogatherapycontainerid="dnn_ctr4020_View_UcCreateSchool_createSchoolPanel" data-yogatherapysubmitid="dnn_ctr4020_View_UcCreateSchool_BtnContinue" data-yogatherapymodalid="schoolAddDisclaimerModal" data-validatefield="True" data-callback="callBackAfterChecking">
                                                                </div>
                                                                <label for="TxtSchoolName" style="font-weight: bold;">
                                                                    <br>
                                                        What designation are you applying for?
                                                    </label><br>
                                                    <div style="background: ghostwhite; visibility: collapse; height: auto; padding: 5px; border: 2px solid green; float: right; width: 350px;">
                                                    <p>Yoga Alliance currently offers five different RYS credentials, each of which has similar but different standards underlying it.  Review RYS requirements associated with your desired credential from the list below<br>
                                                    </p>
                                                    <ul>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">RYS<sup>TM</sup> 200</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">RYS<sup>TM</sup> 300</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">RYS<sup>TM</sup> 500</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Registered Children's Yoga School (RCYS)<sup>TM</sup>) </a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Registered Prenatal Yoga School (RPYS)<sup>TM</sup>) </a></li>
                                                    </ul>
                                                </div>
                                                        

                                                    <div style="width: 500px">
                                                        <input id="dnn_SearchBar_SiteRadioButton" aria-checked="true" value="yes" type="radio" name="dnn$SearchBar$Search" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  RYS 200</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" checked="true" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  RYS 300</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  RYS 500</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  RCYS</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  RPYS</label><br><br>
                                                    </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </section>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="yas-dnncontent" class="yas-Col12">
        <div class="yas-dnnrow">
            <div class="yas-marginlr" id="yas-main-content">

                <div id="dnn_ContentPane" class="yas-ContentPane">
                    <div class="DnnModule DnnModule-SchoolNewRegisteration DnnModule-4020">
                        <a name="4020"></a><div id="dnn_ctr4020_ContentPane">
                            <!-- Start_Module_4020 --><div id="dnn_ctr4020_ModuleContent" class="DNNModuleContent ModSchoolNewRegisterationC">

                                
                                <div class="row-fluid">
                                    <div class="container-fluid ya-main-content ya-school-registration ya-standard-page">
                                        <div id="dnn_ctr4020_View_ucLegalAgreement_legalAgreementPanel">

                                            <div class="content">
                                                <section id="dnn_ctr4020_View_ucLegalAgreement_secAgreementView" class="ya-main ya-school-registration-1">

                                                    <div class="row-fluid">
                                                        <div class="span10">

                                                            <label for="TxtSchoolName">
                                                                    Please read and review the <a href="https://calendly.com/credentialingconsultation/60min" target="_blank">RYS Standards</a>
                                                                </label>
                                                                <label class="checkbox">
                                                                    <span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck">
                                                                        <span class="ya-check-icon" tabindex="1" onchange="validateSchoolLegalAgreement(&#39;CCB_CbScopeOfPracticeCheck_CustomCheckBox&#39;, &#39;LnkScopeOfPracticeValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_CustomCheckBox" type="checkbox" checked="true" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDate">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">

                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsViewLnkseen">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsRequiredToSeeLnk">
                                                                    </span>


                                                                    I have read and reviewed the RYS standards
                                                                    </label>
                                                                    <h3 style="font-weight: bold;">Ethical Commitment</h3>
                                                                    <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <label class="checkbox">
                                                                    <span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck">
                                                                        <span class="ya-check-icon" tabindex="1" onchange="validateSchoolLegalAgreement(&#39;CCB_CbScopeOfPracticeCheck_CustomCheckBox&#39;, &#39;LnkScopeOfPracticeValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_CustomCheckBox" type="checkbox" checked="true" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDate">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">

                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsViewLnkseen">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsRequiredToSeeLnk">
                                                                    </span>


                                                                    I have read and reviewed the RYS standards
                                                                    </label>
                                                                    <div style="background: ghostwhite; visibility: collapse; height: auto; padding: 5px; border: 2px solid green; float: right; width: 350px;">
                                                    <p>Yoga Alliance currently offers five different RYS credentials, each of which has similar but different standards underlying it.  Review RYS requirements associated with your desired credential from the list below<br>
                                                    </p>
                                                </div>
                                                                    <h3 style="font-weight: bold;">Your Trainers</h3>
                                                                    
                                                                    <h5 style="font-weight: bold;">Trainers</h5>
                                                                    <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <button type="button" style="background-color: white; height: auto; width: 200px; border: 3px solid orange; color: orange;" id="addTrainerButton" class="btn" @click="addTrainerButtonClicked">Add a Trainer</button>
                                                            <div id="AddTrainerForm" style="display:none; background: rgb(242, 242, 242); height: auto; padding: 15px; border: 2px solid green; width: 700px;">
                                                                <h4 style="font-weight: bold;">Add a Trainer</h4>
                                                                <hr>
                                                                <div>
                                                                <label style="display: inline; margin-right: 110px;">Search by</label>
                                                                <label style="display: inline;">Name</label>
                                                                </div>
                                                                <div>
                                                                    <select style="width: 150px; height: 25px;  margin-right: 20px;">
                                                                <option>Name</option>
                                                                <option>YA ID</option>
                                                                <option>Email</option>
                                                            </select>
                                                                    <input style="display: inline; width: 150px; height: 15px;" type="text">
                                                                </div>
                                                                <button class="btn btn-orange btn-large input-medium" style="width: 150px; font-weight: bold; height: 35px; font-size: small; text-align: top;" id="searchTrainerButton" @click="searchTrainerButtonClicked">Search </button>
<div id="displayTrinerData" style="display: none;">
    <label for="TxtSchoolName">
                                                        Is the trainer is a lead trainer?
                                                    </label>
                                                        <input id="dnn_SearchBar_SiteRadioButton" checked="true" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  Yes</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" checked="true" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  No</label><br>
                                                        <h5 style="font-weight: bold;">Send confirmation email to Charlotte Raich</h5>
                                                                    <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ed do eiusmod tempor incididunt ut labore et dolore magna aliqua.. <br><br>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <label>Enter a message for Charlotte Raich</label>
                                                        <div style="height: 100px; font-size: 20px; padding: 10px; border: 2px solid lightgray; margin: 10px;"></div>
                                                        
</div><br>
                                                                <button type="button" id="trainerCancelButton" style="display:inline; margin: 10px;" class="btn" @click="searchStaff">Cancel</button>
                                                        <button type="button" id="trainerBackButton" style="display: none; margin: 10px;" class="btn" @click="searchStaff">Back</button>
                                                        <button type="button" id="trainerSendButton" style="display: none; margin: 10px;" class="btn" @click="searchStaff">Send confirmation</button>
                                                            
                                                            </div>
                                                                    <h5 style="font-weight: bold;">Other faculty</h5>
                                                                    <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <button type="button" style="background-color: white; height: auto; padding: 5px; width: 200px; border: 2px solid orange; color: orange ;" id="addFacultyButton" class="btn" @click="addFacultyButtonClicked">Add a Faculty member</button>
                                                            <div id="FacultyForm" style="display:none; background: rgb(242, 242, 242); height: auto; padding: 15px; border: 2px solid green; width: 700px;">
                                                                <h4 style="font-weight: bold;">Add a Faculty member</h4>
                                                                <hr>
                                                                <div id="AddFacultyForm" style="display:none;">
                                                                <label style="display: inline; margin-right: 120px;">Search by</label>
                                                                <label style="display: inline;">Name</label>
                                                                <div>
                                                                    <select style="width: 150px; height: 25px;  margin-right: 20px;">
                                                                <option>Name</option>
                                                                <option>Email</option>
                                                            </select>
                                                                    <input style="display: inline; width: 150px; height: 15px;" type="text">
                                                                </div>
                                                                <button class="btn btn-orange btn-large input-medium" style="width: 150px; height: 35px; font-size: small; text-align: top;"  id="searchFacultyButton" @click="searchFacultyButtonClicked">Search </button>
<br>
                                                            </div>
                                                                
<div id="displayFacultyResultData" style="display: none;">
    <br>
    <label v-text="1" style="display: inline; font-size: 20px;"></label>
<label style="display: inline; font-size: 20px;">  Results Found  </label>
<label style="display: inline; font-weight: bold; color: maroon;">  x Clear Search</label>
<br><hr>
<label style="display: inline; font-weight: bold; margin-left: 10px; margin-right: 115px;">Name</label>
<label style="display: inline; font-weight: bold; margin-right: 110px;">Designation</label>
<label style="display: inline; font-weight: bold; color: maroon; margin-right: 10px;">Location</label>
<div style="height: 70px; font-size: 20px; border-radius: 10px; padding: 10px; border: 2px solid lightgray; background-color: white;">
<label style="display: inline; font-weight: bold; margin-right: 50px;"><a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">Charlote Raiser</a></label>
<label style="display: inline; font-weight: bold; margin-right: 130px;">RYT 200</label>
<label style="display: inline; font-weight: bold; margin-right: 130px;">Rockville, MD</label>
<button style="border-radius: 5px;" id="selectFacultyButton" @click="selectFacultyButtonClicked">Select</button>
</div>
</div>
<div id="displayFacultydetailData" style="display: none;">
<table>
                                                                    <thead>
                                                                        <tr>
                                                                            <th  style="text-align: left; width: auto; padding: 5px;">Name  </th>
                                                                            <th  style="text-align: left; width: auto; padding: 5px;">Email</th>
                                                                        </tr>
                                                                    </thead>
                                                                    <tbody>
                                                                        <tr>
                                                                            <td style="text-align: left; width: auto; padding: 5px;">Charlote Raiser      </td>
                                                                            <td style="text-align: left; width: auto; padding: 5px;">charlote@yogaalliance.org</td>
                                                                        </tr>
                                                                    </tbody>
                                                                </table>
                                                                <br>
                                                            <label style="font-weight: bold;">Education<span class="ya-required" style="font-size: 14px;">*</span></label>
                                                        <input style="height: 100px; border-radius: 7px; font-size: 20px; padding: 10px; border: 2px solid lightgray; margin: 10px; width: 600px;">
                                                        <label>Charecters left: 8000</label>
                                                        <br>
                                                        <label for="TxtSchoolName" style="font-weight: bold;">
                                                        Background and experience
                                                    </label>
                                                        <input id="dnn_SearchBar_SiteRadioButton" checked="true" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  Enter summery of backgroud and experience as text</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  Upload summery of backgroud and experience</label><br>
<br>
<label style="font-weight: bold;">Background<span class="ya-required" style="font-size: 14px;">*</span></label>
<input style="height: 100px; border-radius: 7px; font-size: 20px; padding: 10px; border: 2px solid lightgray; margin: 10px; width: 600px;">
                                                        <label>Charecters left: 8000</label>
                                                        <br>
<label style="font-weight: bold;">Experience<span class="ya-required" style="font-size: 14px;">*</span></label>
<input style="height: 100px; font-size: 20px; padding: 10px; border-radius: 7px; border: 2px solid lightgray; margin: 10px; width: 600px;">
                                                        <label>Charecters left: 8000</label>
                                                        <br>
<label style="font-weight: bold;">Instagram Username</label>
<input style="height: 15px; font-size: 20px; padding: 10px; border-radius: 5px; border: 2px solid lightgray; margin-bottom: 10px; width: 450px;">
                                                        <br>
<label style="font-weight: bold;">Twitter Username</label>
<input style="height: 15px; font-size: 20px; padding: 10px; border-radius: 5px; border: 2px solid lightgray; margin-bottom: 10px; width: 450px;">

                                                        <br>
<label style="font-weight: bold;">Facebook dnn_userLogin_registerLink</label>
<input style="height: 15px; font-size: 20px; padding: 10px; border-radius: 5px; border: 2px solid lightgray; margin-bottom: 10px; width: 450px;">
                                                        <label style="font-weight: bold;">Website URL</label>
                                                        <input style="height: 15px; font-size: 20px; padding: 10px; border-radius: 5px; border: 2px solid lightgray; margin-bottom: 10px; width: 450px;">
                                                        
                                                        <br><label for="TxtSchoolName" style="font-weight: bold;">
                                                                    Assertion<span class="ya-required" style="font-size: 14px;">*</span>
                                                                </label>
                                                                <label class="checkbox">
                                                                    <span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck">
                                                                        <span class="ya-check-icon" tabindex="1" onchange="validateSchoolLegalAgreement(&#39;CCB_CbScopeOfPracticeCheck_CustomCheckBox&#39;, &#39;LnkScopeOfPracticeValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_CustomCheckBox" type="checkbox" checked="true" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDate">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">

                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsViewLnkseen">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsRequiredToSeeLnk">
                                                                    </span>


                                                                    I assert that this faculty member has the required education and equivalent of two years of relevent experience in the selected Education categories, and/or 
                                                                    </label>
                                                                    <br>
                                                                <label class="checkbox">
                                                                    <span id="ya_divCheckBox_dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck">
                                                                        <span class="ya-check-icon" tabindex="1" onchange="validateSchoolLegalAgreement(&#39;CCB_CbScopeOfPracticeCheck_CustomCheckBox&#39;, &#39;LnkScopeOfPracticeValidationMsg&#39;)"><input id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_CustomCheckBox" type="checkbox" checked="true" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$CustomCheckBox" onclick="ya.yaCheckBoxViewModel.getClientDate(this);"></span>



                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdServerDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdServerDate" value="11/18/2022 1:45:35 PM">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDate" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDate">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdClientDateOnPageLoad" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdClientDateOnPageLoad" value="11/19/2022 0:15:54">

                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsViewLnkseen" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsViewLnkseen">
                                                                        <input type="hidden" name="dnn$ctr4020$View$ucLegalAgreement$CCB_CbScopeOfPracticeCheck$HdIsRequiredToSeeLnk" id="dnn_ctr4020_View_ucLegalAgreement_CCB_CbScopeOfPracticeCheck_HdIsRequiredToSeeLnk">
                                                                    </span>


                                                                    I assert that this faculty member has the required education and minumum of 500 hours of teaching experience in the selected Education categories, and/or 
                                                                    </label>
                                                                    <h4 style="font-weight: bold;">Send confirmation email</h4>
                                                                    <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ed do eiusmod tempor incididunt ut labore et dolore magna aliqua.. <br><br>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <label>Enter a message for Charlotte Raich</label>
                                                            <input style="height: 100px; border-radius: 7px; font-size: 20px; padding: 10px; border: 2px solid lightgray; margin: 10px; width: 600px;">
                                                        
                                                        
</div>
                                                        <button type="button" id="facultyCancelButton" style="display:inline; margin: 10px;" class="btn" @click="searchStaff">Cancel</button>
                                                        <button type="button" id="facultyBackButton" style="display: none; margin: 10px;" class="btn" @click="searchStaff">Back</button>
                                                        <button type="button" id="facultySendButton" style="display: none; margin: 10px;" class="btn" @click="searchStaff">Send confirmation</button>
                                                            
                                                            </div>
                                                            
                                                            <h3 style="font-weight: bold;">Selection process for Trainees</h3>
                                                            <br>
                                                            <label>How would you describe your requirements for entrollment in your training program? </label>
                                                            <select style="width: 400px;">
                                                                <option>Other</option>
                                                                <option>We let all trainees into our program</option>
                                                                <option>2+ years of practicing yoga</option>
                                                                <option>5+ years of practicing yoga</option>
                                                            </select>
                                                            <div>
                                                                <br>
                                                                <label for="TxtSchoolName">
                                                                Please explain
                                                            </label>
                                                            <div style="width: 400px"><input name="dnn$ctr4020$View$UcCreateSchool$TxtSchoolName" type="text" maxlength="200" id="TxtSchoolName" tabindex="1" onkeydown="onKeyDownSchoolName(event)" data-validateyogatherapy="True" data-yogatherapycontainerid="dnn_ctr4020_View_UcCreateSchool_createSchoolPanel" data-yogatherapysubmitid="dnn_ctr4020_View_UcCreateSchool_BtnContinue" data-yogatherapymodalid="schoolAddDisclaimerModal" data-validatefield="True" data-callback="callBackAfterChecking">
                                                                </div>
                                                            </div>
                                                            <br>
                                                                
                                                                <label for="TxtSchoolName">
                                                        Do you have any additional prequisites for trainees?
                                                    </label>
                                                        <input id="dnn_SearchBar_SiteRadioButton" checked="true" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  Yes</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  No</label><br><br>
                                                        <label>Please describe your prequesites:</label>
                                                        <div style="height: 100px; width: 700px; font-size: 20px; padding: 10px; border: 2px solid lightgray; border-radius: 8px;"></div>
                                                        <br>
                                                                <label>what is your teacher trainee ratio </label>
                                                            
                                                            <select @change="otherOptionSelected" id="otherOption" style="width: 400px;">
                                                                <option id="other" value="1">Other</option>
                                                                <option id="other1" value="2">1:1</option>
                                                                <option id="other2" value="3">1:5</option>
                                                                <option id="other3" value="4">1:10</option>
                                                                <option id="other4" value="5">1:20</option>
                                                            </select> <br>
                                                            <br>
                                                                    
                                                            <label for="TxtSchoolName">
                                                                Please explain
                                                            </label>
                                                            <div style="width: 500px"><input name="dnn$ctr4020$View$UcCreateSchool$TxtSchoolName" type="text" maxlength="200" id="TxtSchoolName" tabindex="1" onkeydown="onKeyDownSchoolName(event)" data-validateyogatherapy="True" data-yogatherapycontainerid="dnn_ctr4020_View_UcCreateSchool_createSchoolPanel" data-yogatherapysubmitid="dnn_ctr4020_View_UcCreateSchool_BtnContinue" data-yogatherapymodalid="schoolAddDisclaimerModal" data-validatefield="True" data-callback="callBackAfterChecking">
                                                                </div>
                                                                <h3 style="font-weight: bold;">Yoga alliance's review of course material</h3>
                                                                    <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <h5 style="font-weight: bold;">Letter of intent</h5>
                                                            <br>
                                                            <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <div style="border: dotted 3px black; width: 700px; height: 100px; text-align: center; font-weight: bold; font-size: 50px;" id="mydiv"><br>+
                                                            <br><label >Drag and drop to attach or <a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">Browse files</a></label></div> 
                                                            
                                                            <h5 style="font-weight: bold;">Sample Cerificate</h5>
                                                            <br>
                                                            <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Review the  <a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">RYS Certificate policy</a> to see what your certificate need to  include.  YOu may upload one complete policy document or one for each policy.
                                                            </p>
                                                            <div style="border: dotted 3px black; width: 700px; height: 100px; text-align: center; font-weight: bold; font-size: 50px;" id="mydiv"><br>+
                                                            <br><label >Drag and drop to attach or <a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">Browse files</a></label></div> 

                                                            <h5 style="font-weight: bold;">Training schedule</h5>
                                                            <br>
                                                            <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Please upload the vesion that you planned to distribute to trainees.  Visit our <a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">Daily scheduler </a> to help plan your hours to ensure you meet the necessary time requirements
                                                            </p>
                                                            <div style="border: dotted 3px black; width: 700px; height: 100px; text-align: center; font-weight: bold; font-size: 50px;" id="mydiv"><br>+
                                                            <br><label >Drag and drop to attach or <a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">Browse files</a></label></div> 
                                                            <div style="background: ghostwhite; visibility: collapse; height: auto; padding: 5px; margin-top: 10px; border: 2px solid green; float: right; width: 350px;">
                                                    <p>Downloadable templates:<br>
                                                    </p>
                                                    <ul>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Anti-Harassment Policy</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Anti-Retaliation Policy</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Attendance Policy</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Code of Conduct</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Grievance Policy</a></li>
                                                        <li><a href="https://calendly.com/credentialingconsultation/60min" target="_blank">Tuition and Refund Policy</a></li>
                                                    </ul>
                                                </div>
                                                        
                                                            <h5 style="font-weight: bold;">Required policies</h5>
                                                            <br>
                                                            <p style="margin-bottom: 30px; margin-right: 130px;">
                                                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                                            </p>
                                                            <div style="border: dotted 3px black; width: 700px; height: 100px; text-align: center; font-weight: bold; font-size: 50px;" id="mydiv"><br>+
                                                            <br><label >Drag and drop to attach or <a href="https://calendly.com/credentialingconsultation/60min" target="_blank" style="font-weight: bold;">Browse files</a></label></div> 
                                                            <h5 style="font-weight: bold;">RYS curriculam</h5>
                                                            <div style="background: ghostwhite; visibility: collapse; height: auto; padding: 5px; border: 2px solid green; float: right; width: 350px;">
                                                    <p>Fore more information on Yoga Alliance's RYS curriculam requirements. <a href="https://calendly.com/credentialingconsultation/60min" target="_blank">click here</a><br>
                                                    </p>
                                                </div>
                                                            <br>
                                                            <label for="TxtSchoolName">
                                                        Will you be using an existing school's curriculam?
                                                    </label>
                                                        <input id="dnn_SearchBar_SiteRadioButton" checked="true" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  Yes</label><br>
                                                        <input id="dnn_SearchBar_SiteRadioButton" type="radio" name="dnn$SearchBar$Search" value="SiteRadioButton" class="ya-highlight-checked" />
                                                        <label for="TxtSchoolName">  No</label><br><br><br><br>
                                                        <a class="btn btn-orange btn-large input-medium" target="_blank" style="display: inline; margin: 10px;" value="Back" href="https://www.yogaalliance.org/AccountSetup?applyRys=true">    Back    </a>
                                                        <a class="btn btn-orange btn-large input-medium" target="_blank" style="display: inline; margin: 10px;" value="Save Darft & Exit" href="https://www.yogaalliance.org/AccountSetup?applyRys=true">Save Draft & Exit</a>
                                                        <a class="btn btn-orange btn-large input-medium" target="_blank" style="display: inline; margin: 10px;" value="Save & Continue" href="https://www.yogaalliance.org/AccountSetup?applyRys=true">Save & Continue</a>

                                                        </div>
                                                    </div>
                                                </section>
                                            </div>

                                        </div>

                                    </div>
                                </div>
                            </div><!-- End_Module_4020 -->
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <Yogafooter />
    <Yogaheadlinks />
</template>

<script setup>
function addFacultyButtonClicked(){
    console.log("clicked");
    var x =document.getElementById("FacultyForm");
    var y =document.getElementById("AddFacultyForm");
    if(x.style.display == "none"){
        x.style.display = "block";
        y.style.display = "block";
    }
    else{
        x.style.display = "none";
        y.style.display = "none";
    }
}
function addTrainerButtonClicked(){
    console.log("clicked");
    var x =document.getElementById("AddTrainerForm");
    if(x.style.display == "none"){
        x.style.display = "block"
    }
    else{
        x.style.display = "none"
    }
}
function searchTrainerButtonClicked(){
    console.log("clicked");
    var x =document.getElementById("displayTrinerData");
    var back =document.getElementById("trainerBackButton");
    var send =document.getElementById("trainerSendButton");
    if(x.style.display == "none"){
        x.style.display = "block";
        back.style.display = "inline";
        send.style.display = "inline";
    }
    else{
        x.style.display = "none";
        back.style.display = "none";
        send.style.display = "none";
    }
}
function searchFacultyButtonClicked(){
    console.log("clicked");
    var x =document.getElementById("displayFacultyResultData");
    var back =document.getElementById("facultyBackButton");
    var send =document.getElementById("facultySendButton");
    if(x.style.display == "none"){
        x.style.display = "block";
    }
    else{
        x.style.display = "none";
    }
}
function selectFacultyButtonClicked(){
    console.log("clicked");
    var x =document.getElementById("displayFacultydetailData");
    var y =document.getElementById("AddFacultyForm");
    var back =document.getElementById("facultyBackButton");
    var send =document.getElementById("facultySendButton");
    var result =document.getElementById("displayFacultyResultData");
    result.style.display = "none";
        y.style.display = "none";
    if(x.style.display == "none"){
        x.style.display = "block";
        back.style.display = "inline";
        send.style.display = "inline";
        result.style.display = "none";
        y.style.display = "none";
    }
    else{
        x.style.display = "none";
        back.style.display = "none";
        send.style.display = "none";
        result.style.display = "none";
        y.style.display = "none";
    }
}

</script>
