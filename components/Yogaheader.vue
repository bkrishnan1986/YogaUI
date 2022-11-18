<template>
      <header id="yas-header" style="padding-bottom:5%">
            <div class="yas-dnnrow">
                <div class="ya-small-sticky-pane">
                    <div class="ya-pane-1" style="display: none;">
                    </div>
                    
    
    <div class="ya-pane-2 is-not-logged" id="id-top-header-container">
        <div id="LoginContainer" class="row-fluid">
        <div class="btns-wrapper">
            <div class="ya_group-search">
                <div class="ya_container">
                    <div class="ya_search-options">
                        <span>Find:</span>
                        <a href="https://www.yogaalliance.org/Directory?Type=Teacher" class="ya-hyperlink">Teachers</a> <a href="https://www.yogaalliance.org/Directory?Type=School" class="ya-hyperlink">Schools</a> <a href="https://www.yogaalliance.org/Directory?Type=YACEP" class="ya-hyperlink">Continuing Ed</a>
                    </div>
                </div>
            </div>
            <div class="ya_group-session">
            <div class="ya_container">
            <a id="dnn_userLogin_registerLink" href="https://www.yogaalliance.org/AccountSetup">Join</a>
              <span class="separator">|</span>
              <a id="loginLink" onclick="Ya.Auth.openPingAuthorizePageForModal(true);" class="ya-login-sign-in">Log In</a>
            
              <span class="separator">|</span>
              <a class="faq" href="https://www.yogaalliance.org/Contact_Us/Help_Center">Help</a>
              <a href="https://www.yogaalliance.org/#" id="btnnavFadein"></a>
            </div>
            
            
          </div>
        
        <div id="LoginBox" class="ya-loginbox hide ya-popuploginbox">
           
            <div class="login-inner-box">
    
                <div class="row-fluid">
                    <h2 id="HeaderTagLine" style="display: none;">Welcome,<br>
                        Please Sign In</h2>
                </div>
                <div id="dnn_userLogin_UpdatePanelLoginBox">
        
                        <div onkeypress="javascript:return WebForm_FireDefaultButton(event, &#39;dnn_userLogin_btnLogin&#39;)">
            
                            <div class="row-fluid">
                            
                        </div>
                        <div class="ya-login-form row-fluid">
                            <div id="LoginForm">
                                <label class="ya-label">Email</label>
                                <input name="dnn$userLogin$txtLoginEmail" type="text" id="dnn_userLogin_txtLoginEmail" class="LoginEmail">
                                <label class="ya-label">Password</label>
                                <input name="dnn$userLogin$txtLoginPassword" type="password" autocomplete="off" id="dnn_userLogin_txtLoginPassword">
                                <div class="ya-validation-message" id="dvModalLoginErrorMsg" style="display: none;">
                                    <span id="dnn_userLogin_lblError" class="LoginError"></span>
                                </div>
    
                                <div class="ya-button-row text-center">
                                  <a onclick="return Ya.Auth.clickOnLoginTempButton();" id="dnn_userLogin_btnLogin" class="btn btn-warning" href="javascript:__doPostBack(&#39;dnn$userLogin$btnLogin&#39;,&#39;&#39;)">Log In</a>
                                </div>
                                <label class="checkbox" style="display: none;">
                                    <input id="dnn_userLogin_chkRememberMe" type="checkbox" name="dnn$userLogin$chkRememberMe">
                                    Stay Signed In
                                </label>
                            </div>
                        </div>
                        
        </div>		
                        
                    
    </div>
                <div class="row-fluid text-center">
                    Forgot your <a id="dnn_userLogin_lnkForgotPassword" class="ya-action" href="https://www.yogaalliance.org/ResetPassword">password</a> or <a id="dnn_userLogin_lnkForgotEmail" class="ya-action" href="https://www.yogaalliance.org/EmailAccountRecovery">email</a>?
                </div>
            </div>
                    
    </div>
        
    </div>
    </div>
        
    </div>
    
    
                    <div class="ya-login-row">
                        <div class="yas-logo">
                            <a id="dnn_dnnLOGO_hypLogo" title="Yoga Alliance" href="https://www.yogaalliance.org/"><img id="dnn_dnnLOGO_imgLogo" src="../static/image/Logo.png" alt="Yoga Alliance"></a>
                        </div>
    
                    </div>
                    <span id="dnn_SearchBar_ClassicSearch">
    
        <span class="searchInputContainer" data-moreresults="See More Results" data-noresult="No Results Found">
            <input name="dnn$SearchBar$txtSearch" type="text" maxlength="255" size="20" id="dnn_SearchBar_txtSearch" class="NormalTextBox" aria-label="Search" autocomplete="off" placeholder="Search...">
            <a class="dnnSearchBoxClearText" title="Clear search text"></a>
        </span>
        <a id="dnn_SearchBar_cmdSearch" class="SkinObject" href="javascript:__doPostBack(&#39;dnn$SearchBar$cmdSearch&#39;,&#39;&#39;)">Search</a>
    </span>
    
    
    
    
                </div>
            </div>
        </header>
        <nav id="yas-nav">
            <div class="yas-dnnrow">
                <div id="yas-dnnmenu" class="">
                    <div class="yas-pophead">
                        <a href="https://www.yogaalliance.org/#" id="btnnavFadeout">
                            <span id="dnn_dnnTEXTBack_lblText" class="nostyle"></span>
    
                        </a>
                        <h4>
                            <span id="dnn_dnnTEXTSiteMenu_lblText" class="nostyle"></span>
    
                        </h4>
                    </div>
                    <!--SEO NOINDEX--><div id="SuperFish">
      <ul class="yas-menustyle sf-js-enabled sf-arrows" style="touch-action: pan-y;">
        <li class="root first haschild child-1"><a href="https://www.yogaalliance.org/Our_Standards" class="sf-with-ul">Our Standards</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://www.yogaalliance.org/Our_Standards/Elevated_RYS_200_Standards">Elevated RYS 200 Standards</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/Our_Standards/The_Ethical_Commitment">The Ethical Commitment</a></li>
            <li class="category child-3"><a href="https://www.yogaalliance.org/Our_Standards/Community_Conversations">Community Conversations</a></li>
            <li class="category child-4"><a href="https://www.yogaalliance.org/Our_Standards/Accountability">Accountability</a></li>
            <li class="category last child-5"><a href="https://www.yogaalliance.org/Our_Standards/RYS_Online_Teacher_Training_Requirements">RYS Online Teacher Training Requirements</a></li>
          </ul>
        </li>
        <li class="root haschild child-2"><a href="https://www.yogaalliance.org/Designations/How_to_Join" class="sf-with-ul">Become a Member</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://www.yogaalliance.org/Credentialing">Member Overview</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/Credentialing/CredentialsforSchools">Schools</a></li>
            <li class="category child-3"><a href="https://www.yogaalliance.org/Credentialing/Credentials_for_Teachers">Teachers</a></li>
            <li class="category child-4"><a href="https://www.yogaalliance.org/Member_Overview/For_Continuing_Education_Providers">Continuing Education Providers</a></li>
            <li class="category last child-5"><a href="https://www.yogaalliance.org/Become_a_Member/Frequently_Asked_Questions">Frequently Asked Questions</a></li>
          </ul>
        </li>
        <li class="root haschild child-3"><a href="https://www.yogaalliance.org/Benefits" class="sf-with-ul">Membership Benefits</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://www.yogaalliance.org/Membership_Benefits/Member_Assistance_Program">Member Assistance Program</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/CommUnity">YA CommUnity</a></li>
            <li class="category child-3"><a href="https://www.yourya.org/">YourYa.org</a></li>
            <li class="category child-4"><a href="https://www.yogaalliance.org/Directory">Member Directory</a></li>
            <li class="category child-5"><a href="https://www.yogaalliance.org/Search_member_perks">Discounts</a></li>
            <li class="category child-6"><a href="https://www.yogaalliance.org/Membership_Benefits/Unity_in_Yoga">Unity in Yoga</a></li>
            <li class="category child-7"><a href="https://www.yogaalliance.org/Benefits/Advocacy">Advocacy</a></li>
            <li class="category child-8"><a href="https://www.yogaalliance.org/Credentialing">Standards and Credentials</a></li>
            <li class="category last child-9"><a href="https://www.yogaalliance.org/foundation">The Yoga Alliance Foundation</a></li>
          </ul>
        </li>
        <li class="root haschild child-4"><a href="https://www.yogaalliance.org/Events/Upcoming_Events" class="sf-with-ul">Events</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://www.yogaalliance.org/Events/Upcoming_Events">Upcoming Events</a></li>
            <li class="category last child-2"><a href="https://www.yogaalliance.org/Events/Watch_Past_Events">Watch Past Events</a></li>
          </ul>
        </li>
        <li class="root haschild child-5"><a href="https://www.yogaalliance.org/Learn" class="sf-with-ul">About Yoga</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://www.yogaalliance.org/2016YogaInAmericaStudy">2016 Yoga in America Study</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/Learn/Article_Archive">Article Archive</a></li>
            <li class="category last child-3"><a href="https://www.yogaalliance.org/About_Yoga/Scientific_Research_on_Yoga">Scientific Research on Yoga</a></li>
          </ul>
        </li>
        <li class="root haschild child-6"><a href="https://www.yogaalliance.org/GetInvolved" class="sf-with-ul">Get Involved</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://yourya.org/">COVID-19 Resources</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/Become_a_Member/Member_Overview/Social_Credentialing">Social Credentialing</a></li>
            <li class="category child-3"><a href="https://www.yogaalliance.org/Home/Media_Inquiries">Media Inquiries</a></li>
            <li class="category child-4"><a href="https://www.yogaalliance.org/Contact_YogaAlliance">Contact Us</a></li>
            <li class="category last child-5"><a href="https://www.yogaalliance.org/Get_Involved/Sexual_Misconduct_Resources">Sexual Misconduct Resources</a></li>
          </ul>
        </li>
        <li class="root haschild child-7"><a href="https://www.yogaalliance.org/About_Yoga_Alliance" class="sf-with-ul">About Us</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://issuu.com/yogaalliance/docs/annual_report_2020-2021_final">Annual Report</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/About_Us/Our_People/Our_Board">Board of Directors</a></li>
            <li class="category child-3"><a href="https://www.yogaalliance.org/About_Us/Our_People/Our_Leadership">Leadership</a></li>
            <li class="category child-4"><a href="https://www.yogaalliance.org/About_YA/Our_People/OurCommittees">Committees</a></li>
            <li class="category child-5"><a href="https://www.yogaalliance.org/About_Us/Our_History">History</a></li>
            <li class="category child-6"><a href="https://www.yogaalliance.org/About_Us/Our_Policies">Policies</a></li>
            <li class="category child-7"><a href="https://www.yogaalliance.org/About_Us/Financials">Financials</a></li>
            <li class="category child-8"><a href="https://www.yogaalliance.org/About_Us/Work_for_Us">Join Our Team</a></li>
            <li class="category last child-9"><a href="https://www.yogaalliance.org/foundation">Foundation</a></li>
          </ul>
        </li>
        <li class="root child-8"><a href="https://www.yogaalliance.org/CommUnity">CommUnity</a></li>
        <li class="root last haschild child-9"><a href="https://www.yogaalliance.org/foundation" class="sf-with-ul">Foundation</a><span class="yas-sub-indicator">&nbsp;</span><ul style="display: none;">
            <li class="category first child-1"><a href="https://www.yogaalliance.org/Donation">Donate</a></li>
            <li class="category child-2"><a href="https://www.yogaalliance.org/Foundation/Teaching_for_Equity_Program">Teaching for Equity Program</a></li>
            <li class="category child-3"><a href="https://www.yogaalliance.org/Foundation/Emergency_Relief_Fund">Emergency Relief Fund</a></li>
            <li class="category child-4"><a href="https://www.yogaalliance.org/Foundation/Eka_Recovery_Fund">Eka Recovery Fund</a></li>
            <li class="category last child-5"><a href="https://www.yogaalliance.org/Foundation/Eka_Well-Being_Services">Eka Well-Being Services</a></li>
          </ul>
        </li>
      </ul>
    </div><!--END SEO-->
                </div>
            </div>
        </nav>
</template>