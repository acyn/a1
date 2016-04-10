<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">

<html>
<head>
    <title>TC Direct Setup Guide - TopCoder Wiki</title>
                
    <META HTTP-EQUIV="Pragma" CONTENT="no-cache">
    <META HTTP-EQUIV="Expires" CONTENT="-1">
    <script language="javascript">
        var contextPath = '/wiki';
        var i18n = [];
    </script>

                            <link rel="stylesheet" href="/wiki/s/1109/1/2/_/styles/main-action.css?spaceKey=docs" type="text/css" />
            
    

        
            <script type="text/javascript" src="/wiki/s/1109/1/_/decorators/effects.js"></script>
    

            <script type="text/javascript">
var gaJsHost = (("https:" == document.location.protocol) ? "https://ssl." : "http://www.");
document.write(unescape("%3Cscript src='" + gaJsHost + "google-analytics.com/ga.js' type='text/javascript'%3E%3C/script%3E"));
</script>
<script type="text/javascript">
var pageTracker = _gat._getTracker("UA-6340959-1");
pageTracker._trackPageview();
</script>
    <link type="image/x-icon" rel="shortcut icon" href="/i/favicon.ico"/>
    <link type="text/css" rel="stylesheet" href="/css/tcStyles.css" />
    <link type="text/css" rel="stylesheet" href="/css/coders.css" />
    <link type="text/css" rel="stylesheet" href="/css/wiki.css" />
</head>

                    <body onload="">
    








<script type="text/javascript" src="/js/popup.js"></script>

<div id="shortcutBar">
    <div class="icon"><a href="http://community.topcoder.com/tc"><img src="/i/interface/scHome.png" alt="" onmouseover="postPopUpText('globalPopupText','Home'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="javascript:arena();"><img src="/i/interface/scAlgo.png" alt="" onmouseover="postPopUpText('globalPopupText','Algorithm Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&amp;pt=23"><img src="/i/interface/scConceptualization.png" alt="" onmouseover="postPopUpText('globalPopupText','Software Conceptualization Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&amp;pt=6"><img src="/i/interface/scSpecification.png" alt="" onmouseover="postPopUpText('globalPopupText','Software Specification Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&amp;pt=7"><img src="/i/interface/scArchitecture.png" alt="" onmouseover="postPopUpText('globalPopupText','Software Architecture Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ViewActiveContests&amp;ph=112"><img src="/i/interface/scDesign.png" alt="" onmouseover="postPopUpText('globalPopupText','Component Design Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ViewActiveContests&amp;ph=113"><img src="/i/interface/scDevelopment.png" alt="" onmouseover="postPopUpText('globalPopupText','Component Development Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>

    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&pt=14"><img src="/i/interface/scAssembly.png" alt="" onmouseover="postPopUpText('globalPopupText','Software Assembly Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&pt=13"><img src="/i/interface/scTesting.png" alt="" onmouseover="postPopUpText('globalPopupText','Testing Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://www.topcoder.com/tc?module=ActiveContests&pt=9"><img src="/i/interface/scBugHunt.png" alt="" onmouseover="postPopUpText('globalPopupText','Bug Hunt Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&pt=35"><img src="/i/interface/scContentCreation.gif" alt="" onmouseover="postPopUpText('globalPopupText','Content Creation Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/tc?module=ActiveContests&pt=36"><img src="/i/interface/scReporting.gif" alt="" onmouseover="postPopUpText('globalPopupText','Reporting Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="javascript:arena();"><img src="/i/interface/scTCHS.png" alt="" onmouseover="postPopUpText('globalPopupText','High School Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://community.topcoder.com/longcontest/?module=ViewActiveContests"><img src="/i/interface/scMarathon.png" alt="" onmouseover="postPopUpText('globalPopupText','Marathon Matches'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
    <div class="icon"><a href="http://studio.topcoder.com/?module=ViewActiveContests"><img src="/i/interface/scStudio.png" alt="" onmouseover="postPopUpText('globalPopupText','TopCoder Studio Competitions'); popUp(this,'globalPopup');" onmouseout="popHide()" /></a></div>
</div>

<div id="globalPopup" class="popUp"><div id="globalPopupText"></div></div>


<div style="position: absolute; right:0px; top:31px;"><a href="http://community.topcoder.com/tc?module=MyHome"><img src="/i/interface/myTopCoder.png" alt="My TopCoder" style="display:block;"/></a></div>


<div align="center" style="margin: 0px 290px 0px 280px;">
   <div id="outerLogo">
      <div id="innerLogo">
      <a href="http://www.topcoder.com/"><img src="/i/interface/topcoder.gif" alt="TopCoder" style="display: block;" /></a>
      </div>
   </div>
</div>

<div class="memberCountBox">
Member Count: 984,997 - 


April 10, 2016

&nbsp;<a class="gMetal" href="Javascript:tcTime()">[Get Time]</a>
</div>

<div class="topBar">
    <div style="float: right; margin: 5px 0px 0px 0px;">
        
            Hello,&nbsp;<a href="http://www.topcoder.com/tc?module=MemberProfile&amp;cr=22723787" class="coderTextGray">Acyn</a>
            
                | <a class="gMetal" href="http://community.topcoder.com/tc?module=Logout">Logout</a>
            
        
    </div>
</div>


<table width="100%" border="0" cellpadding="0" cellspacing="0">
<tbody>
    <tr valign="top">
        <td width="180">
            










<script language="JavaScript" type="text/javascript" src="/js/arena.js"></script>


<script language="JavaScript" type="text/javascript">
<!--
function toggleMenu(menuTitle,menuID){
   var menu = document.getElementById(menuID);
   if(menu.style.display == 'block') menu.className = 'CLOSED';
   else if(menu.className == 'OPEN' && menu.style.display != 'none') menu.className = 'CLOSED';
   else {
      menu.className = 'OPEN';
   }
   if(menuTitle.blur)menuTitle.blur();
   if(menuTitle.className == 'exp') menuTitle.className = 'exp_ed';
   else menuTitle.className = 'exp';
   return;
}
function flipMenu(myMenuName){
   var menuName = document.getElementById(myMenuName);
   menuName.className = 'exp_ed';
}

// -->
</script>

<div style="padding: 0px;"><img src="/i/interface/leftnav_top.gif" alt="" /></div>
<div id="navbar">
    
<ul>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_competitions')">Challenges</a>
<ul id="m_competitions">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_competitions_overview')">Overview</a>
<ul id="m_competitions_overview">
<li><a href="http://apps.topcoder.com/wiki/x/MQD9Ag">Reliability</a></li>
<li><a href="http://apps.topcoder.com/wiki/x/lYE_/">Ratings</a></li>
<li><a href="http://apps.topcoder.com/wiki/x/EoK1B/">Badges</a></li>
<li><a href="http://apps.topcoder.com/wiki/x/aoE_/">How to Get Paid</a></li>
<li><a href="http://apps.topcoder.com/wiki/x/2gRmAw">Administrative Overview </a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_copilot_opportunities')">Copilot Opportunities</a>
<ul id="m_copilot_opportunities">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Copilot+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_copilot_support')">Track Information</a>
<ul id="m_copilot_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Copilot+Opportunities">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Copilot+Opportunities">Documentation</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Copilot+Opportunities">Tutorial</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=29">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=140">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewCopilotPool&size=20&view=0&sort=12">Copilot Pool</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'competition_design')">Design</a>
<ul id="competition_design">
<li><a href="http://studio.topcoder.com">Studio</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_conceptualization_competitions')">Conceptualization</a>
<ul id="m_conceptualization_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/TopCoder+Conceptualization+Contests">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_conceptualization_support')">Track Information</a>
<ul id="m_conceptualization_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Conceptualization+Competition+Tutorial">Tutorial</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Conceptualization+Documentation">Documentation</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&pt=23">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=23">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=134">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=23">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=23">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_specification_competitions')">Specification</a>
<ul id="m_specification_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/TopCoder+Specification+Contests">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_specification_support')">Track Information</a>
<ul id="m_specification_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Specification+Competitions">How to Compete</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=6">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=6">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=117">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=6">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=6">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_architecture_competitions')">Architecture</a>
<ul id="m_architecture_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Architecture+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_architecture_support')">Track Information</a>
<ul id="m_architecture_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Module+Architecture+Tutorial">Module Architecture Tutorial</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=7">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=7">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=118">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=7">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=7">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_des_competitions')">Component Design</a>
<ul id="m_des_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Component+Design+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_des_support')">Track Information</a>
<ul id="m_des_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Component+Design+Competitions">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Component+Design+Documentation">Documentation</a></li>
<li><a href="http://www.topcoder.com/tc?module=ColorChange&amp;ph=112">Recent Color Changes</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Component+Design+Data+Feeds">Data Feeds</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ViewActiveContests&amp;ph=112">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=1">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=112">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=1">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=1">Meet the Review Board</a></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'competition_dev')">Development</a>
<ul id="competition_dev">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_dev_competitions')">Component Development</a>
<ul id="m_dev_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Component+Development+Competitions">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_dev_support')">Track Information</a>
<ul id="m_dev_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Component+Development+Competitions">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Component+Development+Documentation">Documentation</a></li>
<li><a href="http://www.topcoder.com/tc?module=ColorChange&amp;ph=113">Recent Color Changes</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Component+Development+Data+Feeds">Data Feeds</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ViewActiveContests&amp;ph=113">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=2">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=113">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=2">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=2">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_assembly_competitions')">Assembly</a>
<ul id="m_assembly_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Assembly">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_assembly_support')">Track Information</a>
<ul id="m_assembly_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Assembly+Competition+Tutorials">Tutorials</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Assembly+Competition+Documentation">Documentation</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=14">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=14">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;ph=125">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=14">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=14">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_first2finish_competitions')">First2Finish</a>
<ul id="m_first2finish_competitions">
<li><a href="http://www.cloudspokes.com/how-it-works-members">Overview</a></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=38">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=38">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=38">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=38">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=38">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_code_competitions')">Code</a>
<ul id="m_code_competitions">
<li><a href="http://www.cloudspokes.com/how-it-works-members">Overview</a></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=39">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=39">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=39">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=39">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=39">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_test_suites_competitions')">Test Suites</a>
<ul id="m_test_suites_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Test+Scenarios+and+Scripts">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_test_suites_support')">Track Information</a>
<ul id="m_test_suites_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Testing+Competitions">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Testing+Competition+Tutorial">Tutorial</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Testing+Competition+Documentation">Documentation</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=13">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=13">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=13">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=13">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=13">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_reporting_competitions')">Reporting</a>
<ul id="m_reporting_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Reporting">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_reporting_support')">Track Information</a>
<ul id="m_reporting_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Reporting+Competitions">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Reporting+Competition+Tutorial">Tutorial</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Reporting+Competition+Documentation">Documentation</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=36">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=36">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=36">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=36">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=36">Meet the Review Board</a></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'competition_ui_dev')">UI Development</a>
<ul id="competition_ui_dev">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_ui_prototype_competitions')">UI Prototype</a>
<ul id="m_ui_prototype_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/UI+Prototype+Competitions">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_ui_prototype_support')">Track Information</a>
<ul id="m_ui_prototype_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/UI+Prototype+Competitions">UI Prototype Tutorial</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=19">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=19">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=19">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=19">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=19">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_ria_build_competitions')">RIA Build</a>
<ul id="m_ria_build_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/RIA+Build+Competitions">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_ria_build_support')">Track Information</a>
<ul id="m_ria_build_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/RIA+Build+Competitions">RIA Build Tutorial</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=24">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=24">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=24">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=24">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=24">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_content_creation_competitions')">Content Creation</a>
<ul id="m_content_creation_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Content+Contests+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_content_creation_support')">Track Information</a>
<ul id="m_content_creation_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Content+Creation+Competitions">How to Compete</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&pt=35">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=35">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=35">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=35">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=35">Meet the Review Board</a></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'competition_qa')">QA and Maintenance</a>
<ul id="competition_qa">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_test_scenarios_competitions')">Test Scenarios</a>
<ul id="m_test_scenarios_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Test+Scenarios+and+Scripts">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_test_scenarios_support')">Track Information</a>
<ul id="m_test_scenarios_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Testing+Competitions">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Testing+Competition+Tutorial">Tutorial</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Testing+Competition+Documentation">Documentation</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=26">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=26">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=26">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=26">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=26">Meet the Review Board</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_bugraces_competitions')">Race</a>
<ul id="m_bugraces_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Race+Competition+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_bugraces_support')">Track Information</a>
<ul id="m_bugraces_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Bug+Race+Competitions">How to Compete</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ViewActiveBugRaces">Active Challenges</a></li>
<li><a href="http://apps.topcoder.com/wiki/x/FQG2AQ">Review Opportunities</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_bughunt_competitions')">Bug Hunt</a>
<ul id="m_bughunt_competitions">
<li><a href="http://apps.topcoder.com/wiki/x/W5ogAg">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_bughunt_support')">Track Information</a>
<ul id="m_bughunt_support">
<li><a href="http://apps.topcoder.com/wiki/x/cpogAg">How to Compete</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=ActiveContests&amp;pt=9">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ContestStatus&amp;pt=9">Challenge Status</a></li>
<li><a href="http://www.topcoder.com/tc?module=CompList&amp;pt=9">Past Challenges</a></li>
<li><a href="http://www.topcoder.com/tc?module=ViewReviewAuctions&amp;pt=9">Review Opportunities</a></li>
<li><a href="http://www.topcoder.com/tc?module=ReviewBoard&amp;pt=9">Meet the Review Board</a></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'competition_algo')">Algorithm</a>
<ul id="competition_algo">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_algo_competitions')">Single Round Matches (SRM)</a>
<ul id="m_algo_competitions">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Algorithm+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_algo_support')">Track Information</a>
<ul id="m_algo_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+SRM+Algorithm+Competitions">How to Compete</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/SRM+Algorithm+Competition+FAQs">FAQs</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Algorithm+Competition+Rating+System">Rating System</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Write+Problems+for+TopCoder">Write Problems</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_algo_stats')">Statistics</a>
<ul id="m_algo_stats">
<li><a href="http://www.topcoder.com/tc?module=MatchList">Match Archive</a></li>
<li><a href="http://www.topcoder.com/stat?c=round_overview">Match Overviews</a></li>
<li><a href="http://www.topcoder.com/tc?module=SrmDivisionWins">Match Winners</a></li>
<li><a href="http://www.topcoder.com/stat?c=last_match">Match Results</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Algorithm+Problem+Set+Analysis">Match Editorials</a></li>
<li><a href="http://www.topcoder.com/tc?module=ProblemArchive">Problem Archive</a></li>
<li><a href="http://www.topcoder.com/tc?module=ColorChange&amp;ratid=1">Recent Color Changes</a></li>
<li><a href="http://apps.topcoder.com/wiki/display/tc/Algorithm+Data+Feeds">Data Feeds</a></li>
</ul></li>
<li><a href="javascript:arena();">Launch Arena</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_long_contests')">Marathon Match</a>
<ul id="m_long_contests">
<li><a href="http://apps.topcoder.com/wiki/display/tc/Marathon+Match+Overview">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_long_support')">Track Information</a>
<ul id="m_long_support">
<li><a href="http://apps.topcoder.com/wiki/display/tc/How+to+Compete+in+Marathon+Match+Events">How to Compete</a></li>
<li><a href="http://www.topcoder.com/longcontest/?module=Static&amp;d1=support&amp;d2=ratings">Rating System</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_long_stats')">Statistics</a>
<ul id="m_long_stats">
<li><a href="http://www.topcoder.com/longcontest/stats/?module=MatchList">Match Archive</a></li>
<li><a href="http://www.topcoder.com/longcontest/stats/?module=ViewOverview">Match Overview</a></li>
<li><a href="http://www.topcoder.com/longcontest/stats/?module=MatchWinners">Match Winners</a></li>
<li><a href="http://www.topcoder.com/longcontest/?module=Static&amp;d1=match_editorials&amp;d2=archive">Match Editorials</a></li>
<li><a href="http://www.topcoder.com/longcontest/?module=Static&amp;d1=support&amp;d2=dataFeed">Data Feeds</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/longcontest/?module=ViewActiveContests">Active Challenges</a></li>
<li><a href="http://www.topcoder.com/longcontest/?module=ViewPractice">Practice</a></li>
<li><a href="http://www.topcoder.com/longcontest/?module=ViewQueue">Queue Status</a></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_hs_competitions')">High School</a>
<ul id="m_hs_competitions">
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=hs&amp;d2=home">Overview</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_hs_stats')">Statistics</a>
<ul id="m_hs_stats">
<li><a href="http://www.topcoder.com/tc?module=HSRoundOverview">Match Overview</a></li>
<li><a href="http://www.topcoder.com/tc?module=HSRoundStatsTeam">Match Results (Team)</a></li>
<li><a href="http://www.topcoder.com/tc?module=HSRoundStatsInd">Match Results (Indiv.)</a></li>
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=hs&amp;d2=match_editorials&amp;d3=archive">Match Editorials</a></li>
<li><a href="http://www.topcoder.com/tc?module=ColorChange&amp;ratid=2">Recent Color Changes</a></li>
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=hs&amp;d2=support&amp;d3=dataFeed">Data Feeds</a></li>
</ul></li>
<li><a href="http://www.topcoder.com/tc?module=Static&d1=hs&d2=spotlightSessions">Spotlight Sessions</a></li>
<li><a href="javascript:arena();">Launch Arena</a></li>
</ul></li>
<li><a href="http://software.topcoder.com/review">Submit &amp; Review</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_topcoder_networks')">TopCoder Networks</a>
<ul id="m_topcoder_networks">
<li><a href="http://community.topcoder.com/alcatel/">Alcatel Lucent</a></li>
<li><a href="http://community.topcoder.com/amdapp/">AMD OpenCL</a></li>
<li><a href="http://community.topcoder.com/darpacs/">DARPA CS-STEM</a></li>
<li><a href="http://community.topcoder.com/lifetech-network/">Life Technologies</a></li>
<li><a href="http://community.topcoder.com/ntl/">NASA Tournament Lab</a></li>
<li><a href="http://community.topcoder.com/x/">PayPalX</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_events')">Events</a>
<ul id="m_events">
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=calendar&amp;d2=thisMonth">Event Calendar</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_tournaments')">Tournaments</a>
<ul id="m_tournaments">
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=tournaments&amp;d2=home">TopCoder</a></li>
<li><a href="http://www.topcoder.com/pl/">Powered by TopCoder</a></li>
<li><a href="http://www.topcoder.com/tc?module=CRPFStatic&amp;d1=crpf&amp;d2=crpf_overview">Charity</a></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_stats')">Statistics</a>
<ul id="m_stats">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_competitor_stats')">The Tops</a>
<ul id="m_competitor_stats">
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_top_rated_competitors')">Top Ranked</a>
<ul id="m_top_rated_competitors">
<li><a href="http://www.topcoder.com/tc?module=AlgoRank">Algorithm</a></li>
<li><a href="http://www.topcoder.com/tc?module=HSRank">High School</a></li>
<li><a href="http://www.topcoder.com/longcontest/stats/?module=CoderRank">Marathon Match</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_conceptors">Conceptualization</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_specificators">Specification</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_architects">Architecture</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_designers">Design</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_developers">Development</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_assemblers">Assembly</a></li>
<li><a href="http://www.topcoder.com/stat?c=top_testers">Test Suites</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_recordbook')">Record Book</a>
<ul id="m_recordbook">
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=statistics&amp;d2=recordbook_home">Algorithm</a></li>
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=compstats&amp;d2=comp_recordbook_home">Component</a></li>
<li><a href="http://www.topcoder.com/longcontest/?module=Static&amp;d1=stats&amp;d2=recordbook_home">Marathon Match</a></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_com')">Coder of the Month</a>
<ul id="m_com">
<li><a href="http://www.topcoder.com/tc?module=COMHistory&amp;achtid=5">Algorithm</a></li>
<li><a href="http://www.topcoder.com/tc?module=COMHistory&amp;achtid=6">Design</a></li>
<li><a href="http://www.topcoder.com/tc?module=COMHistory&amp;achtid=7">Development</a></li>
</ul></li>
</ul></li>
</ul></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_edu_content')">Tutorials</a>
<ul id="m_edu_content">
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=education&amp;d2=overview">Overview</a></li>
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=tutorials&amp;d2=alg_index">Algorithm Tutorials</a></li>
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=tutorials&amp;d2=software_index">Software Tutorials</a></li>
<li><a href="http://www.topcoder.com/tc?module=Static&amp;d1=tutorials&amp;d2=mm_index">Marathon Tutorials</a></li>
<li><a href="http://apps.topcoder.com/wiki/dashboard.action">Wiki</a></li>
</ul></li>
<li><a href="http://forums.topcoder.com/">Forums</a></li>
<li><a href="http://www.topcoder.com/tc?&amp;module=SurveyList">Surveys</a></li>
<li><a href="http://www.topcoder.com/tc?module=MyHome">My TopCoder</a></li>
<li><a href="http://www.topcoder.com/help">Help Center</a></li>
<li class="exp"><a href="javascript:void(0)" onclick="Javascript:toggleMenu(this.parentNode,'m_about_tc')">About TopCoder</a>
<ul id="m_about_tc">
<li><a href="http://www.topcoder.com/aboutus/">Overview</a></li>
<li><a href="http://www.topcoder.com/aboutus/">Why Join TopCoder?</a></li>
<li><a href="http://www.topcoder.com/aboutus/careers/">Working at TopCoder</a></li>
<li><a href="http://www.topcoder.com/aboutus/management/">Leadership</a></li>
<li><a href="http://www.topcoder.com/aboutus/news/">Press Room</a></li>
</ul></li></ul>

    <div style="float: left; padding: 10px 0px 0px 17px;">
        
        <a href="http://www.topcoder.com/tc?module=LinkTracking&amp;link=http://apps.topcoder.com/wiki/x/L4TD&amp;refer=leftnav"><img src="/i/leftnav/umlTool.png" alt="UML Tool" /></a>

        
        
        
        
    </div>
    

<div id="navbarSearch">
<b>Member Search:</b>
<form action="http://www.topcoder.com/tc" method="get" name="simpleSearchForm" class="noSpace" id="simpleSearchForm">
   <input class="noSpace" type="hidden" name="module" value="SimpleSearch" />
   <input class="noSpace" type="text" name="ha" value="Handle:" size="12" maxlength="15" onfocus="javascript: if (document.simpleSearchForm.ha.value=='Handle:') document.simpleSearchForm.ha.value = '';" onblur="javascript:if (document.simpleSearchForm.ha.value == '')document.simpleSearchForm.ha.value = 'Handle:';" />
   <a class="gMetal" href="javascript:void document.simpleSearchForm.submit();">Go</a><br />
   <a class="gMetal" href="http://www.topcoder.com/tc?module=ViewAdvanced">Advanced Search</a>
</form>
</div>
</div>
<div style="float: left; clear:left; padding: 0px 0px 23px 0px;"><img src="/i/interface/leftnav_bottom.gif" alt="" /></div>


    <div align="center" style="float: left; clear:left; width: 170px; margin: 0px;">
        <img src="/i/interface/brackets.png" alt="" style="margin-bottom: 23px;" />
    </div>


        </td>
        <td width="100%" align="left" class="bodyColumn">


    <script type="text/javascript">
        function hideMessage(messageId)
        {
            var message = document.getElementById(messageId)
            message.style.display = "none";
            setCookie(messageId, true);
        }
    </script>

        

    <table border="0" cellpadding="0" cellspacing="0" width="100%">

                <tr class="topBar">
            <td align="left">
                <span class="topBarDiv">             
    <script language="JavaScript">
        function showBreadcrumbsEllipsis()
        {
            document.getElementById('breadcrumbsEllipsis').style.display = 'none';
            document.getElementById('breadcrumbsExpansion').style.display = 'inline';
        }
    </script>
                                                    <a href="/wiki/dashboard.action">Dashboard</a>
                                     &gt;                         <a href="/wiki/display/docs">Software Documentation</a>
                                                    <span id="breadcrumbs">
                    &gt;
                    <span id="breadcrumbsEllipsis">
                        <a href="#" onclick="showBreadcrumbsEllipsis();return false;" title="
                    Home             &gt;         Holding Area             &gt;         Applications    ">...</a>
                    </span>
                    <span id="breadcrumbsExpansion" style="display:none;">
                                <a href="/wiki/display/docs/Home">Home</a>
                 &gt;                     <a href="/wiki/display/docs/Holding+Area">Holding Area</a>
                 &gt;                     <a href="/wiki/display/docs/Applications">Applications</a>
        </span>
                </span>
                                                                                                                             &gt;                         <a href="/wiki/display/docs/TopCoder+Site+Resource+Page">TopCoder Site Resource Page</a>
                                     &gt;                         <a href="/wiki/display/docs/TC+Direct+Setup+Guide">TC Direct Setup Guide</a>
                
     </span>
            </td>

            <td align="right" valign="middle" style="white-space:nowrap">
                    <form id="quickSearch" method="POST" action="/wiki/dosearchsite.action" name="searchForm">
        <input type="hidden" name="quickSearch" value="true" />
        
        <input type="hidden" name="searchQuery.spaceKey" value="conf_global" />
        <input type="text" accessKey="s" name="searchQuery.queryString" size="25"/>
        <input type="submit" value="Search"/>
    </form>
            </td>
        </tr>
        
                <tr>
            <td style="padding: 5px 0px;" colspan="2">
            <table style="padding: 0px; margin: 0px; width: 100%;" cellspacing="0" cellpadding="0" border="0">
                <tr>
                                                                                                                                                <td valign="bottom" align="left" width="1%" nowrap>
                        <span class="logoSpaceLink">            <a href="/wiki/display/docs">Software Documentation</a>    </span>
                    </td>
                    <td align="right" valign="top" width="98%">
                                                    
    <span class="smalltext" id="userNavBar">
        
            

            </span>
                            
                                <a href="/wiki/display/docs/TC+Direct+Setup+Guide?decorator=printable" rel="nofollow"><img src="/wiki/images/icons/print_16.gif" width="16" height="16" hspace="1" vspace="1" align="absmiddle" border="0" alt="View a printable version of the current page." title="View a printable version of the current page."/></a>

                                                        
            <a href="/wiki/pages/doexportpage.action?pageId=57018232&type=TYPE_PDF" rel="nofollow">
        <img src="/wiki/images/icons/attachments/pdf.gif" height="16" width="16" border="0" align="absmiddle" title="Export Page as PDF"></a>
                                                                                &nbsp;
                    </td>
                </tr>
                <tr>
                    <td height="22" align="left" colspan="2">
                        <span class="pagetitle" style="line-height: 1; margin: 0px; text-decoration: none">
                                        TC Direct Setup Guide
                            </span>
                    </td>
                </tr>
            </table>
            </td>
        </tr>
            </table>

        <!--
    Root decorator: all decisions about how a page is to be decorated via the
                    inline decoration begins here.
-->



<!--
    Switch based upon the context. However, for now, just delegate to a decorator
    identified directly by the context.
-->


    
    


    
    
        
    
    
<table border="0" cellpadding="0" cellspacing="0" width="100%">

    <tr>
        <td>
            <div class="greynavbar">
                <span style="float:right; padding: 6px 10px 4px 0px">
						
        
        
        
                    <a  href="/wiki/spaces/browsespace.action?key=docs"><img src="/wiki/images/icons/browse_space.gif" height="16" width="16" border="0" align="absmiddle" title="Browse Space">&nbsp;<span>Browse Space</span></a>
		    				</span>

				<ul id="foldertab" style="margin-bottom: 0px; padding-top: 10px;">
											<li><a  id="viewPageLink"  href="/wiki/display/docs/TC+Direct+Setup+Guide"  class="current"    accessKey="v"><u>V</u>iew</a></li>
											<li><a  id="viewAttachmentsLink"  href="/wiki/pages/viewpageattachments.action?pageId=57018232"    accessKey="a"><u>A</u>ttachments (0)</a></li>
											<li><a  id="viewPageInfoLink"  href="/wiki/pages/viewinfo.action?pageId=57018232"    accessKey="i"><u>I</u>nfo</a></li>
									</ul>
            </div>
        </td>
    </tr>
    <tr>
        <td valign="top" class="pagebody">

                        <table width="100%" cellpadding="0" cellspacing="0" border="0" style="clear: both">
                <tr>
                    <td width='100%' class="pagecontent" valign="top">

                    
                    
                    
                                                    
                            <table width="100%" style="margin-bottom: 5px" cellspacing="0">
                                <tr>
                                    <td align="left" valign="top">
                                        <span class="smalltext">
                                                        Added by             lmmortal
, last edited by             kennyalive
 on Jan 17, 2013
                      &nbsp;(<a href="/wiki/pages/diffpages.action?pageId=57018232&originalId=96176343">view change</a>)
              
                                            
 
<style type="text/css">
div.auto_complete {
    width: 350px;
    background: #fff;
}

div.auto_complete ul {
    border: 1px solid #888;
    margin: 0;
    padding: 0;
    width: 100%;
    list-style-type: none;
}

div.auto_complete ul li {
    margin: 0;
    padding: 3px;
}

div.auto_complete ul li.selected {
    background-color: #ffb;
}

div.auto_complete ul strong.highlight {
    color: #800;
    margin: 0;
    padding: 0;
}
</style>


<!-- Delay the loading of the external javascript file needed for labels (as it takes too long to load and visibly holds loading of the page body) -->
<!-- To do this without javascript errors over undefined functions, we need to declare stubs here (that are overrided later by the proper implementations) -->
<script language="JavaScript" type="text/javascript">
    function doAddLabel(hideTextfieldAfterAddParam)
    {
        // stub
    }

    function onAddLabel()
    {
        // stub
    }

    function showLabelsInput()
    {
        // stub
    }
</script>

<!-- This is a hack to work around an apparent SiteMesh bug - http://jira.opensymphony.com/browse/SIM-198 -->


<span class="error"><span class="errorMessage" id="errorSpan"></span></span>
<form name="addLabelForm" method="" action="" onSubmit="doAddLabel(false); return false;" style="margin: 0px; padding: 0px">
    <div style="float: left">Labels:&nbsp;</div>
    <div id="labelsInfo" style="float: left; width: 90%">
        <span id="labelsList">
                    (None)
                </span>
                    <span id="editLabelsLink" class="inline-control-link fontSizeTiny" style="display: none;">
            <a href="" onclick="onAddLabel(); showLabelsInput(); return false;">EDIT</a>
        </span>
            </div>
    <br clear="all"/><!-- Do not remove this line-break. You will make Safari cry. -->
    <div id="labelInputSpan" style="display: none; clear: both;">
        <div style="border: 1px solid #cccccc; padding: 8px; align: center; background-color: #f0f0f0">

        <div id="labelOperationErrorContainer" style="display: none"><span class="error"><span class="errorMessage" id="labelOperationErrorMessage"></span></span></div>

        <table width="100%">
            <tr>
                <td>
                    <div class="formtitle" style="padding-bottom: 3px; font-size: 13px;">Add Labels</div>
                </td>
                <td align="right"><div id="waitImageAndStatus" style="display: none; height: 16px;"><img alt="Wait Image" border=0 align="absmiddle" src="/wiki/images/icons/wait.gif">&nbsp;<span id="labelOperationStatus" class="smalltext" style="vertical-align: middle"></span></div></td>
            </tr>
            <tr><td width="50%">
                    Enter labels to add to this page:<br/>
        <input autocomplete="off" type="text" id="labelName" name="labelsString" value="" class="monospaceInput" size="40">
        <input type="submit" onclick="doAddLabel(false); return false;" value="Add"><input type="button" onclick="doAddLabel(true); return false;" value="Done">
        <div class="auto_complete" id="labelsAutocompleteList"></div>
        <div class="smalltext">
            <em>Tip:</em> Looking for a label? Just start typing.
        </div>
        </td>
            <td width="50%" valign="top">
                <div id="suggestedLabelsSpan"></div>
            </td>
        </tr></table>
        </div>
    </div>
</form>
    <script type="text/javascript">
        // if there is javascript support, enable the [Edit] link that enables AJAX label adding/removing functionality
        if (document.getElementById('editLabelsLink'))
        {
            document.getElementById('editLabelsLink').style.display = 'inline';
        }
    </script>
                                        </span>
                                    </td>
                                    <td align="right" valign="top">
                                                                                    <div style="padding: 5px; border: 1px solid #cccccc; margin: 0px; float:right;">
                                                <center>
                                                                                                    <a  id="pageFavourite"  href="/wiki/labels/addfavourite.action?entityId=57018232"><img src="/wiki/images/icons/star_grey.gif" height="16" width="16" border="0" align="absmiddle" title="Add this page to your favourites list" alt="Add this page to your favourites list"></a>
					                                                                                <a  id="pageWatch"  href="/wiki/pages/addpagenotification.action?pageId=57018232"><img src="/wiki/images/icons/watch_16.gif" height="16" width="16" border="0" align="absmiddle" title="Watch this page" alt="Watch this page"></a>
					                                                                            </center>
                                            </div>
                                                                            </td>
                                </tr>
                            </table>

                                                        
                            <div class="wiki-content">
                               <!-- wiki content -->
            <div>
<ul>
    <li><a href='#TCDirectSetupGuide-1.0SoftwarePrerequisites'>1.0 Software Prerequisites</a></li>
    <li><a href='#TCDirectSetupGuide-2.0DatabaseSetup'>2.0 Database Setup</a></li>
    <li><a href='#TCDirectSetupGuide-3.0InstallandconfigureJBossinstance'>3.0 Install and configure JBoss instance</a></li>
<ul>
    <li><a href='#TCDirectSetupGuide-3.1JBossSSLsupport'>3.1 JBoss SSL support</a></li>
</ul>
    <li><a href='#TCDirectSetupGuide-4.0SVN'>4.0 SVN</a></li>
    <li><a href='#TCDirectSetupGuide-5.0TCDirectSetup'>5.0 TC Direct Setup</a></li>
<ul>
    <li><a href='#TCDirectSetupGuide-5.1ModifyBuildScriptsConfiguration'>5.1 Modify Build Scripts Configuration</a></li>
    <li><a href='#TCDirectSetupGuide-5.2Tokensconfiguration'>5.2 Tokens configuration</a></li>
    <li><a href='#TCDirectSetupGuide-5.3BuildandDeploy'>5.3 Build and Deploy</a></li>
    <li><a href='#TCDirectSetupGuide-5.4Targets'>5.4 Targets</a></li>
    <li><a href='#TCDirectSetupGuide-5.5StartJbossServer'>5.5 Start Jboss Server</a></li>
    <li><a href='#TCDirectSetupGuide-5.6OpeningtheApplication'>5.6 Opening the Application</a></li>
</ul>
    <li><a href='#TCDirectSetupGuide-6.0ResourceContactList'>6.0 Resource Contact List</a></li>
</ul></div>
<h2><a name="TCDirectSetupGuide-1.0SoftwarePrerequisites"></a>1.0 Software Prerequisites</h2>
<ul>
	<li>Java JDK - On windows, be sure JAVA_HOME is set after installation.</li>
	<li>SVN or TortoiseSVN (<span class="nobr"><a href="http://tortoisesvn.net" rel="nofollow">http://tortoisesvn.net<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>) - to check out the source code from SVN</li>
	<li>Ant (<span class="nobr"><a href="http://ant.apache.org" rel="nofollow">http://ant.apache.org<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>) - On windows, be sure to set ANT_HOME after installation and that the install dir is added to your PATH
	<ul>
		<li>AntContrib (<span class="nobr"><a href="http://sourceforge.net/projects/ant-contrib/files/ant-contrib/1.0b3/ant-contrib-1.0b3-bin.zip/download" rel="nofollow">http://sourceforge.net/projects/ant-contrib/files/ant-contrib/1.0b3/ant-contrib-1.0b3-bin.zip/download<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>) - put all jars from the zip into the lib directory of your Ant installation.</li>
		<li>bsj 2.4.0 (<span class="nobr"><a href="http://apache.mivzakim.net//commons/bsf/binaries/bsf-bin-2.4.0.zip" rel="nofollow">http://apache.mivzakim.net//commons/bsf/binaries/bsf-bin-2.4.0.zip<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>) - put jar into the lib directory of your Ant installation.</li>
		<li>commons-logging 1.1.1 (<span class="nobr"><a href="http://commons.apache.org/logging/download_logging.cgi" rel="nofollow">http://commons.apache.org/logging/download_logging.cgi<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>) - put jar into the lib directory of your Ant installation.</li>
	</ul>
	</li>
	<li>JBoss 4.2.3-GA (<span class="nobr"><a href="http://www.jboss.org/jbossas/downloads/" rel="nofollow">http://www.jboss.org/jbossas/downloads/<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>)</li>
</ul>


<h2><a name="TCDirectSetupGuide-2.0DatabaseSetup"></a>2.0 Database Setup</h2>
<p>Before you start deploying TC Direct, you have to deploy TopCoder databases. See instructions on the wiki <a href="/wiki/display/docs/TopCoder+Databases+Setup+Guide" title="TopCoder Databases Setup Guide">TopCoder Databases Setup Guide</a>.
<br clear="all" /></p>
<h2><a name="TCDirectSetupGuide-3.0InstallandconfigureJBossinstance"></a>3.0 Install and configure JBoss instance</h2>
<p>Download and unzip the JBoss 4.2.3 distribution <span class="nobr"><a href="http://www.jboss.org/jbossas/downloads" rel="nofollow">http://www.jboss.org/jbossas/downloads<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>.</p>

<p>In order to run the TC Direct application properly, we should alert the Perm related settings to resolve the famous OutOfMemeory. You must add the following settings <b>-XX:PermSize=128m -XX:MaxPermSize=512m</b> to <b>JAVA_OPTS</b>.<br/>
For Windows, the setting is in &lt;&lt;jboss.home&gt;&gt;/bin/run.bat. For Linux, the setting is in &lt;&lt;jboss.home&gt;&gt;/bin/run.conf.</p>

<p>Now edit &lt;&lt;jboss.home&gt;&gt;/server/default/conf/jboss-service.xml. Lines below must be uncommented. This is needed to setup Jboss to use non-default set of preconfigured ports. If you skip this step you <b>will not be able</b> to run Online Review and TC Direct simultaneously on your machine. Besides default values in token.properties.example <b>will not work</b> for you so thats better to follow this guide <img class="emoticon" src="/wiki/images/icons/emoticons/smile.gif" height="20" width="20" align="absmiddle" alt="" border="0"/></p>
<div class="code panel" style="border-width: 1px;"><div class="codeContent panelContent">
<pre class="code-java">&lt;mbean code=<span class="code-quote">"org.jboss.services.binding.ServiceBindingManager"</span>
     name=<span class="code-quote">"jboss.system:service=ServiceBindingManager"</span>&gt;
     &lt;attribute name=<span class="code-quote">"ServerName"</span>&gt;ports-01&lt;/attribute&gt;
     &lt;attribute name=<span class="code-quote">"StoreURL"</span>&gt;${jboss.home.url}/docs/examples/binding-manager/sample-bindings.xml&lt;/attribute&gt;
     &lt;attribute name=<span class="code-quote">"StoreFactoryClassName"</span>&gt;
       org.jboss.services.binding.XMLServicesStoreFactory
     &lt;/attribute&gt;
   &lt;/mbean&gt;</pre>
</div></div>
<p><br clear="all" /></p>
<h3><a name="TCDirectSetupGuide-3.1JBossSSLsupport"></a>3.1 JBoss SSL support</h3>
<p>It is also recommended to enable SSL support for JBoss (since Oct 2012 cockpit uses https). For this add the following xml element (new connector) to &lt;&lt;jboss.home&gt;&gt;/server/default/deploy/jboss-web.deployer/server.xml:</p>

<div class="code panel" style="border-width: 1px;"><div class="codeContent panelContent">
<pre class="code-java">&lt;Connector port=<span class="code-quote">"443"</span> address=<span class="code-quote">"${jboss.bind.address}"</span> protocol=<span class="code-quote">"HTTP/1.1"</span>
           SSLEnabled=<span class="code-quote">"<span class="code-keyword">true</span>"</span> maxThreads=<span class="code-quote">"150"</span> scheme=<span class="code-quote">"https"</span> secure=<span class="code-quote">"<span class="code-keyword">true</span>"</span>
           clientAuth=<span class="code-quote">"<span class="code-keyword">false</span>"</span> sslProtocol=<span class="code-quote">"TLS"</span> 
          keystoreFile=<span class="code-quote">"${jboss.server.home.dir}/conf/myserver.keystore"</span> 
          keystorePass=<span class="code-quote">"&lt;&lt;your_password&gt;&gt;"</span> /&gt;</pre>
</div></div>

<p>Generate the keystore using the following command (keytool is from java jdk):</p>
<div class="code panel" style="border-width: 1px;"><div class="codeContent panelContent">
<pre class="code-java">keytool -genkey -alias myserver -keyalg RSA -keystore &lt;&lt;some_temp_dir_path&gt;&gt;/myserver.keystore</pre>
</div></div>
<p>You will need to enter kestore password, personal information and key password during this step.</p>

<p>Make sure the the keystore is generated successfully by using the following command.</p>
<div class="code panel" style="border-width: 1px;"><div class="codeContent panelContent">
<pre class="code-java">keytool -list -v -keystore &lt;&lt;some_temp_dir_path&gt;&gt;/myserver.keystore</pre>
</div></div>

<p>Put the generated key to &lt;&lt;jboss.home&gt;&gt;/server/default/conf
<br clear="all" /></p>
<h2><a name="TCDirectSetupGuide-4.0SVN"></a>4.0 SVN</h2>
<p>To start working with TC Direct, you must download the source code from TopCoder SVN <span class="nobr"><a href="https://coder.topcoder.com/tcs/clients/cronos/applications/direct/trunk" rel="nofollow">https://coder.topcoder.com/tcs/clients/cronos/applications/direct/trunk<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>
<br clear="all" /></p>
<h2><a name="TCDirectSetupGuide-5.0TCDirectSetup"></a>5.0 TC Direct Setup</h2>

<h3><a name="TCDirectSetupGuide-5.1ModifyBuildScriptsConfiguration"></a>5.1 Modify Build Scripts Configuration</h3>
<p>Build scripts related configuration are defined in topcoder_global.properties. We have provided a sample file - topcoder_global.properties.example.</p>

<p>Copy topcoder_global.properties.example and rename it as topcoder_global.properties.</p>

<p>Modify the environment related configuration. </p>
<table class='confluenceTable'><tbody>
<tr>
<th class='confluenceTh'>Property</th>
<th class='confluenceTh'>Description</th>
</tr>
<tr>
<td class='confluenceTd'>base</td>
<td class='confluenceTd'>The path of the code base (absolute path must be used)</td>
</tr>
<tr>
<td class='confluenceTd'>jboss.home</td>
<td class='confluenceTd'>The location of jboss server</td>
</tr>
<tr>
<td class='confluenceTd'>svn.username</td>
<td class='confluenceTd'>SVN credentials, needed for switch-and-checkout ant target.</td>
</tr>
<tr>
<td class='confluenceTd'>svn.password</td>
<td class='confluenceTd'>SVN credentials, needed for switch-and-checkout ant target.</td>
</tr>
</tbody></table>

<h3><a name="TCDirectSetupGuide-5.2Tokensconfiguration"></a>5.2 Tokens configuration</h3>
<p>After you modified topcoder_global.properties, you have to create file token.properties with the same content as token.properties.example.<br/>
File token.properties contains tokens that must reflect your environment. Build scripts will replace tokens with their values in TC Direct configuration files.<br/>
token.properties.example files contains typical token values for windows and unix environments.</p>

<div class='panelMacro'><table class='tipMacro'><colgroup><col width='24'><col></colgroup><tr><td valign='top'><img src="/wiki/images/icons/emoticons/check.gif" width="16" height="16" align="absmiddle" alt="" border="0"></td><td>
<p>Be sure to replace all occurrences of "&lt;&lt;some_path&gt;&gt;" with actual paths to existing folders!</p></td></tr></table></div>

<p><br clear="all" /></p>
<h3><a name="TCDirectSetupGuide-5.3BuildandDeploy"></a>5.3 Build and Deploy</h3>

<p><b>To build and deploy the TC Direct</b>:
<br clear="all" />
<b>ant switch-and-checkout</b><br/>
<b>ant dist-backend</b></p>

<p>For the first time, the jboss does not contain the needed dependencies and configuration for TC Direct application, so we should first run</p>

<p><b>ant first_deploy</b></p>

<p>For later deployment you can simply run '<b>ant deploy</b>' to build and deploy the latest EAR tarball.</p>

<h3><a name="TCDirectSetupGuide-5.4Targets"></a>5.4 Targets</h3>
<p>The build.xml defines the following main targets.</p>

<ol>
	<li><b>first_deploy</b> It is used if the jboss is not setup yet for deploying TC Direct. It will copy all dependencies to your local JBoss folder, build and deploy the EAR file by using the already built libs. <b>deploy</b> It will build and deploy EAR file using the already built libs.</li>
	<li><b>deploy-internal</b>  this target deploys the configurations files to jboss.</li>
	<li><b>deploy-static-files</b> this target deploys the static files to jboss.</li>
	<li><b>deploy-jboss-files</b> this target deploys the dependent ears to jboss.</li>
	<li><b>switch-and-checkout</b> this target checkout or switch to the defined source code branches for all components defined in subprojects.xml.</li>
	<li><b>dist-backend</b> this target will rebuilt all the components from the source code.</li>
	<li><b>ear</b> this target will build the EAR tarball file.
<br clear="all" /></li>
</ol>


<h3><a name="TCDirectSetupGuide-5.5StartJbossServer"></a>5.5 Start Jboss Server</h3>
<p>To start jboss, please run &lt;&lt;jboss_home&gt;&gt;/bin/run.bat (Windows) or &lt;&lt;jboss_home&gt;&gt;/bin/run.sh (Unix OSes).
<br clear="all" />
You can check the <b>server.log</b> file to see that the application is run properly.
<br clear="all" /></p>
<h3><a name="TCDirectSetupGuide-5.6OpeningtheApplication"></a>5.6 Opening the Application</h3>
<p>Once the application is deployed, you can open the browser and locate <span class="nobr"><a href="http://localhost:8180/direct" rel="nofollow">http://localhost:8180/direct<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>.<br/>
The list of username and password of the mock authenticator is available in file <b>MockXMLAuthenticator.xml</b>. Most common user is <b>heffan/password</b> (password is indeed 'password').
<br clear="all" /></p>

<h2><a name="TCDirectSetupGuide-6.0ResourceContactList"></a>6.0 Resource Contact List </h2>

<p>If you run into any issues or have any suggestions for this guide do not hesitate to contact </p>
<table class='confluenceTable'><tbody>
<tr>
<th class='confluenceTh'> Name </th>
<th class='confluenceTh'> Resource Email </th>
</tr>
<tr>
<td class='confluenceTd'> lmmortal </td>
<td class='confluenceTd'> roman.apostol@gmail.com </td>
</tr>
<tr>
<td class='confluenceTd'> delemach </td>
<td class='confluenceTd'> dhessing@topcoder.com </td>
</tr>
</tbody></table>
<p><br clear="all" /></p>
                            </div>

                            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide"
    dc:title="TC Direct Setup Guide"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/57018232"/>
</rdf:RDF>
-->

                                
                                <!--
    Root decorator: all decisions about how a page is to be decorated via the
                    inline decoration begins here.
-->



<!--
    Switch based upon the context. However, for now, just delegate to a decorator
    identified directly by the context.
-->


    
    

<div class="wiki-content" style="margin-right:10px;">
    <p style="clear: both"/><!-- comments should always display underneath the content. we should have a 'clear:both' here just in case there are floats or aligned images in the content -->

    
            <div class="tabletitle" style="border: 0px">
            <a name="comments">Comments</a>
                        <span class="smalltext">&nbsp;(<a href="/wiki/display/docs/TC+Direct+Setup+Guide?showComments=false">Hide Comments</a>)</span>
                    </div>
    
    
            
            
                                                    <div style="padding: 0 0 0  0 ">
        <a name="comment-69175993"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>i can't checkout the components, following is the output:<br/>
switch-and-checkout:<br/>
[echo] DEBUG: &#45;------------------&#45; Starting sync for subprojects</p>

<p>sync-all:<br/>
[echo] DEBUG: &#45;------------------&#45; Checking for: configuration_manager<br/>
[echo] &#45;------------------&#45; Checking out: configuration_manager<br/>
[svn] &lt;Checkout&gt; started ...<br/>
[svn] svn: connection refused by the server<br/>
[svn] svn: OPTIONS request failed on '/tcs/catalog/java/configuration_mana<br/>
ger/branches/cockpit_trunk'<br/>
[svn] svn: connection refused by the server<br/>
[svn] svn: OPTIONS request failed on '/tcs/catalog/java/configuration_mana<br/>
ger/branches/cockpit_trunk'<br/>
[svn] Connection timed out: connect<br/>
[svn] &lt;Checkout&gt; failed &#33;</p>

<p>BUILD FAILED<br/>
F:\coding\tc\testsuites\tc_cockpit\direct\build-master-targets.xml:402: The following error occurred while executing this line:<br/>
F:\coding\tc\testsuites\tc_cockpit\direct\build-master-targets.xml:457: The following error occurred while executing this line:<br/>
F:\coding\tc\testsuites\tc_cockpit\direct\build-master-utils.xml:116: Can't checkout</p>


<p>then it stops, do u have any idea?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             gjw99
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=69175993#comment-69175993'>Nov 20, 2011 17:10</a>
                
                                                                                          | <a id="reply-69175993" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=69175993#comment-69175993">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=69175993#comment-69175993"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=69175993#comment-69175993"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/69175993"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-69664809"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>Did you put your SVN credentials into topcoder_global.properties file? I found that was necessary; the switch-and-checkout didn't seem to use the cached credentials for the subprojects.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             delemach
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=69664809#comment-69664809'>Nov 22, 2011 05:01</a>
                
                                                                                          | <a id="reply-69664809" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=69664809#comment-69664809">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=69664809#comment-69664809"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=69664809#comment-69664809"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/69664809"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                <div style="padding: 0 0 0  20px ">
        <a name="comment-100368873"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>The fix seems to be to provide only your SVN username by un-commenting "svn.username" while leaving "svn.password" commented out in topcoder_global.properties.</p>

<p>This ensures that the script is forced request for your password at the command prompt (see line 113 in build-master-utils.xml). Tested on Windows 8, JDK 1.6.0_41, Ant 1.8.4, SVN 1.6.17.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             sah2ed
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=100368873#comment-100368873'>Mar 13, 2013 11:29</a>
                
                                                                                          | <a id="reply-100368873" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=100368873#comment-100368873">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=100368873#comment-100368873"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=100368873#comment-100368873"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/100368873"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-73138650"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>When start jboss, I got this error, please help, thanks.<br/>
2012-04-10 14:02:32,476 ERROR <span class="error">&#91;org.jboss.deployment.MainDeployer&#93;</span> Could not start deployment: <span class="nobr"><a href="file:/D:/Java/jboss-4.2.3.GA/server/default/deploy/direct.ear/liquid_portal_service.jar" rel="nofollow">file:/D:/Java/jboss-4.2.3.GA/server/default/deploy/direct.ear/liquid_portal_service.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
java.lang.IllegalStateException: Cannot build JAXB context<br/>
............................<br/>
...............................<br/>
Caused by: org.jboss.ws.WSException: Failed to create JAXBContext<br/>
at org.jboss.ws.core.jaxws.CustomizableJAXBContextFactory.createContext(CustomizableJAXBContextFactory.java:116)<br/>
at org.jboss.ws.metadata.builder.jaxws.JAXWSMetaDataBuilder.createJAXBContext(JAXWSMetaDataBuilder.java:951)<br/>
... 82 more<br/>
Caused by: com.sun.xml.bind.v2.runtime.IllegalAnnotationsException: 1 counts of IllegalAnnotationExceptions<br/>
java.lang.StackTraceElement does not have a no-arg default constructor.<br/>
this problem is related to the following location:<br/>
at java.lang.StackTraceElement<br/>
at public java.lang.StackTraceElement[] java.lang.Throwable.getStackTrace()<br/>
at java.lang.Throwable<br/>
at private java.lang.Throwable[] com.liquid.portal.service.jaxws.LiquidPortalServiceExceptionBean.suppressed<br/>
at com.liquid.portal.service.jaxws.LiquidPortalServiceExceptionBean</p>

<p>at com.sun.xml.bind.v2.runtime.IllegalAnnotationsException$Builder.check(IllegalAnnotationsException.java:102)<br/>
at com.sun.xml.bind.v2.runtime.JAXBContextImpl.getTypeInfoSet(JAXBContextImpl.java:438)<br/>
at com.sun.xml.bind.v2.runtime.JAXBContextImpl.&lt;init&gt;(JAXBContextImpl.java:286)<br/>
at com.sun.xml.bind.v2.ContextFactory.createContext(ContextFactory.java:139)<br/>
at com.sun.xml.bind.api.JAXBRIContext.newInstance(JAXBRIContext.java:105)<br/>
at org.jboss.ws.core.jaxws.CustomizableJAXBContextFactory.createContext(CustomizableJAXBContextFactory.java:110)<br/>
... 83 more</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                                            Posted by             westine
 at Mar 05, 2012 22:14Updated by <b>            westine
</b>
                                    
                                                                                          | <a id="reply-73138650" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=73138650#comment-73138650">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=73138650#comment-73138650"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=73138650#comment-73138650"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/73138650"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-105809459"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>I got the same error.</p>

<p>Anyone can help?</p>

<p>thanks</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             dljg718
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809459#comment-105809459'>Jun 03, 2013 03:36</a>
                
                                                                                          | <a id="reply-105809459" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809459#comment-105809459">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809459#comment-105809459"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809459#comment-105809459"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809459"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-105809517"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>I found that because I was running in jre 1.7. switch jre 1.6, the problem solved.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             dljg718
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809517#comment-105809517'>Jun 03, 2013 10:26</a>
                
                                                                                          | <a id="reply-105809517" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809517#comment-105809517">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809517#comment-105809517"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809517#comment-105809517"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809517"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                                            </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-86869311"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>is this setup guide still works?</p>

<p>After deployed successfully, I tried to login, but I met the LDAP connection error.</p>

<p>Detailed error log:2012-08-21 09:23:46,203 ERROR <span class="error">&#91;org.jboss.ejb.plugins.LogInterceptor&#93;</span> Unexpected Error in method: public abstract com.topcoder.security.TCSubject com.topcoder.security.login.LoginRemote.login(java.lang.String,java.lang.String) throws java.rmi.RemoteException,com.topcoder.security.GeneralSecurityException<br/>
java.lang.NoClassDefFoundError: com/topcoder/util/net/ldap/sdkinterface/LDAPSDKException<br/>
	at com.topcoder.security.login.LoginBean.loginToLDAPDirectory(LoginBean.java:250)<br/>
	at com.topcoder.security.login.LoginBean.login(LoginBean.java:114)<br/>
	at com.topcoder.security.login.LoginBean.login(LoginBean.java:75)<br/>
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)<br/>
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:39)<br/>
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)<br/>
...<br/>
From section 5.6, it says the user is mock in MockXMLAuthenticator.xml<br/>
 <br/>
Please help, thank you.
<br clear="all" /></p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             gjw99
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=86869311#comment-86869311'>Aug 25, 2012 23:26</a>
                
                                                                                          | <a id="reply-86869311" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=86869311#comment-86869311">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=86869311#comment-86869311"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=86869311#comment-86869311"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/86869311"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-86869562"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>java.lang.NoClassDefFoundError: com/topcoder/util/net/ldap/sdkinterface/LDAPSDKException<br clear="all" /></p>

<p>&#45;-&gt; after deploy, do you see this jar under direct.ear (lib)?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             mashannon168
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=86869562#comment-86869562'>Aug 27, 2012 12:37</a>
                
                                                                                          | <a id="reply-86869562" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=86869562#comment-86869562">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=86869562#comment-86869562"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=86869562#comment-86869562"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/86869562"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-90048387"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>I have the same error&#33; And I haven't&nbsp; com/topcoder/util/net/ldap/sdkinterface/LDAPSDKException under direct.ear. Moreover VM hasn't this class under direct.ear&#33; Please help&#33;&#33;&#33;</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             zpetrovich
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048387#comment-90048387'>Oct 12, 2012 04:26</a>
                
                                                                                          | <a id="reply-90048387" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=90048387#comment-90048387">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048387#comment-90048387"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048387#comment-90048387"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/90048387"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-90048405"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>This class is in: /home/direct/direct/lib/tcs/ldap_sdk_interface/1.0.2/ldap_sdk_interface.jar<br/>
You can copy it from there into direct.ear. </p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             sah2ed
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048405#comment-90048405'>Oct 12, 2012 06:28</a>
                
                                                                                          | <a id="reply-90048405" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=90048405#comment-90048405">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048405#comment-90048405"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048405#comment-90048405"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/90048405"/>
</rdf:RDF>
-->

                    </div>
        
                                                            <div style="padding-left: 60px; color: #666666" class="smallfont">
                            <a href="/wiki/display/docs/TC+Direct+Setup+Guide?rootCommentId=90048405#comments">View the rest of this thread</a>. Most recent comment:  Oct 12, 2012 <br/>
                            3 more comments by:                                     sah2ed
,
                                            zpetrovich
            <br/>
                        </div>
                                        </div>
                                                <div style="padding: 0 0 0  20px ">
        <a name="comment-90048412"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>1. Stop JBoss. Empty the work, temp and deploy folders.</p>

<p>2. Note that you cannot login using LDAP in your local machine; it only works on the VM. Instead you should setup your environment to use MockXMLAuthenticator.xml for logins.</p>

<p>a. Create your own token.properties based on the <span class="nobr"><a href="https://coder.topcoder.com/tcs/clients/cronos/applications/direct/trunk/token.properties.example" rel="nofollow">token.properties<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>example in svn.</p>

<p>b. Update <div class="code panel" style="border-width: 1px;"><div class="codeContent panelContent">
<pre class="code-java">@loginProcessor@=com.topcoder.direct.services.view.processor.security.EJBLoginProcessor</pre>
</div></div> <br/>
with:</p>
<div class="code panel" style="border-width: 1px;"><div class="codeContent panelContent">
<pre class="code-java">@loginProcessor@=com.topcoder.direct.services.view.processor.security.MockLoginProcessor</pre>
</div></div>
<p>3. Redeploy direct.ear and start JBoss.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             sah2ed
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048412#comment-90048412'>Oct 12, 2012 07:28</a>
                
                                                                                          | <a id="reply-90048412" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=90048412#comment-90048412">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048412#comment-90048412"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048412#comment-90048412"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/90048412"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-90048415"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>Thanks man&#33; Your are a genius&#33; It works&#33;</p>


<p>&nbsp;It would good to mention this not trivial step at Setup Guide.</p>

<p>Many thanks again&#33;&#33;&#33; </p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             zpetrovich
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048415#comment-90048415'>Oct 12, 2012 07:44</a>
                
                                                                                          | <a id="reply-90048415" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=90048415#comment-90048415">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048415#comment-90048415"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=90048415#comment-90048415"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/90048415"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                                            </div>
                                                            </div>
                                                            </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-100370014"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>I encountered some issues during the setup on a windows 7 computer, adding them here in case someone else ran in them too:</p>

<p>1. svnant (<span class="nobr"><a href="http://subclipse.tigris.org/svnant.html" rel="nofollow">http://subclipse.tigris.org/svnant.html<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>) is a must have dependency, add the jars to ant/lib folder. I used 1.3.1<br/>
2. Must use ant 1.7, and 1.8 or newer versions don't work with grails<br/>
3. Must have grails 1.3.7 and make sure you have GRAILS_HOME in your environment variables, also make sure you have %GRAILS_HOME%\bin in path<br/>
4. Must use JDK 1.6, newer versions don't work<br/>
5. token.properties.example in trunk folder is not up to date (at least it's missing the scorecardUrl property), so I had to copy the one from trunk\conf and make modifications to it<br/>
6. All port 1599 in token.properties should be changed to 1199 if you need to run this on windows 7<br/>
7. commons-codec-1.7.jar is needed, add to ant/lib folder<br/>
8. Read the comments above and use MockLoginProcessor instead of EJBLoginProcessor</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                                            Posted by             wendell
 at Mar 18, 2013 12:59Updated by <b>            wendell
</b>
                                    
                                                                                          | <a id="reply-100370014" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=100370014#comment-100370014">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=100370014#comment-100370014"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=100370014#comment-100370014"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/100370014"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-102859579"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>when I run  "switch-and-checkout" it will stop at "<span class="error">&#91;svn&#93;</span> &lt;checkout&gt; started ..."<br/>
How to solve it?  thanks~</p>
</div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             lcxjtu
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=102859579#comment-102859579'>Apr 14, 2013 21:50</a>
                
                                                                                          | <a id="reply-102859579" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=102859579#comment-102859579">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=102859579#comment-102859579"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=102859579#comment-102859579"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/102859579"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                <div style="padding: 0 0 0  20px ">
        <a name="comment-105809403"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>Did you found the root cause, why new versions are not supported. I meet the same problem recently.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             fireice
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809403#comment-105809403'>Jun 02, 2013 20:44</a>
                
                                                                                          | <a id="reply-105809403" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809403#comment-105809403">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809403#comment-105809403"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809403#comment-105809403"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809403"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-105809415"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>what is the porblem?can you describe it, or attach the error message.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             lcxjtu
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809415#comment-105809415'>Jun 02, 2013 22:25</a>
                
                                                                                          | <a id="reply-105809415" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809415#comment-105809415">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809415#comment-105809415"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809415#comment-105809415"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809415"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                                <div style="padding: 0 0 0  20px ">
        <a name="comment-105810109"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>I am using MockLoginProcessor instead of EJBLoginProcessor, but an error occurred when starting JBoss:</p>

<p>org.springframework.beans.factory.CannotLoadBeanClassException: Cannot <br/>
find class <span class="error">&#91;com.topcoder.ppt.security.MockLoginProcessor&#93;</span> for bean with <br/>
name 'loginProcessor' defined in ServletContext resource [/WEB     <br/>
-INF/applicationContext.xml]; nested exception is <br/>
java.lang.ClassNotFoundException: <br/>
com.topcoder.ppt.security.MockLoginProcessor</p>

<p>And I can find file MockLoginProcessor.class at place build\classes\com\topcoder\ppt\security.<br/>
I have used EJBLoginProcessor directly, another occurred when starting JBoss, which is likely that listening 1129 port error.</p>

<p>Do you know what's wrong with me? I have tried a lot of time about deploying the project on my XP/Ubuntu PC.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                                            Posted by             copperybean
 at Jun 06, 2013 07:06Updated by <b>            copperybean
</b>
                                    
                                                                                          | <a id="reply-105810109" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105810109#comment-105810109">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105810109#comment-105810109"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105810109#comment-105810109"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105810109"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                <div style="padding: 0 0 0  20px ">
        <a name="comment-105810159"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>I try start JBoss on my xp operation system, get following error:</p>



<p>22:21:45,937 INFO  <span class="error">&#91;STDOUT&#93;</span> Cannot create JDBC driver of class 'com.informix.jdbc.IfxDriver' for connect URL '<input type="text" name="variableValues.scorecardUrl" size="12" onkeyup="updateOthers(this)" />&nbsp;<span class="templateparameter">(scorecardUrl)</span>'</p>

<p>java.sql.SQLException: No suitable driver</p>

<p>	at java.sql.DriverManager.getDriver(DriverManager.java:243)</p>

<p>	at org.apache.commons.dbcp.BasicDataSource.createConnectionFactory(BasicDataSource.java:1437)</p>

<p>	at org.apache.commons.dbcp.BasicDataSource.createDataSource(BasicDataSource.java:1371)</p>

<p>	at org.apache.commons.dbcp.BasicDataSource.getConnection(BasicDataSource.java:1044)</p>


<p>It seems that not driver for informix, but how to install, install to where?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             copperybean
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105810159#comment-105810159'>Jun 06, 2013 11:11</a>
                
                                                                                          | <a id="reply-105810159" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105810159#comment-105810159">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105810159#comment-105810159"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105810159#comment-105810159"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105810159"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-104268800"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>I start jboss,i got these errors,please help&#33;</p>

<p>ERROR [org.springframework.web.context.ContextLoader] Context initialization failed<br/>
org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'paymentStatusDetailsAction' defined in ServletContext resource [/WEB-INF/applicationContext.xml]: Error setting property values; nested exception is org.springframework.beans.PropertyBatchUpdateException; nested PropertyAccessExceptions (1) are:<br/>
PropertyAccessException 1: org.springframework.beans.MethodInvocationException: Property 'paymentsByStatusByDays' threw exception; nested exception is com.topcoder.direct.services.payments.ConfigurationException<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.applyPropertyValues(AbstractAutowireCapableBeanFactory.java:1279)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.populateBean(AbstractAutowireCapableBeanFactory.java:1010)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:472)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory$1.run(AbstractAutowireCapableBeanFactory.java:409)<br/>
&nbsp;&nbsp;&nbsp; at java.security.AccessController.doPrivileged(Native Method)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:380)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractBeanFactory$1.getObject(AbstractBeanFactory.java:264)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:261)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:185)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:164)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.DefaultListableBeanFactory.preInstantiateSingletons(DefaultListableBeanFactory.java:429)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:728)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:380)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.web.context.ContextLoader.createWebApplicationContext(ContextLoader.java:255)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.web.context.ContextLoader.initWebApplicationContext(ContextLoader.java:199)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.web.context.ContextLoaderListener.contextInitialized(ContextLoaderListener.java:45)<br/>
&nbsp;&nbsp;&nbsp; at org.apache.catalina.core.StandardContext.listenerStart(StandardContext.java:3856)<br/>
&nbsp;&nbsp;&nbsp; at org.apache.catalina.core.StandardContext.start(StandardContext.java:4361)<br/>
&nbsp;&nbsp;&nbsp; at org.apache.catalina.core.ContainerBase.addChildInternal(ContainerBase.java:790)<br/>
&nbsp;&nbsp;&nbsp; at org.apache.catalina.core.ContainerBase.addChild(ContainerBase.java:770)</p>

<p>............ </p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             cffjx
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=104268800#comment-104268800'>May 19, 2013 11:17</a>
                
                                                                                          | <a id="reply-104268800" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=104268800#comment-104268800">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=104268800#comment-104268800"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=104268800#comment-104268800"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/104268800"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-105809698"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>After deployed successfully<br/>
i start jboss<br/>
the jboss log shows no errors<br/>
but the login jsp in the homepage of the direct does not existed<br/>
is there anyone could help?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             cffjx
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809698#comment-105809698'>Jun 04, 2013 02:09</a>
                
                                                                                          | <a id="reply-105809698" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809698#comment-105809698">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809698#comment-105809698"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809698#comment-105809698"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809698"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-105809760"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>Does jboss log show direct.ear deployed?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             systic
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809760#comment-105809760'>Jun 04, 2013 09:39</a>
                
                                                                                          | <a id="reply-105809760" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809760#comment-105809760">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809760#comment-105809760"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809760#comment-105809760"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809760"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-108003725"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>yes ,jboss_home server.log show no errors</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             cffjx
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=108003725#comment-108003725'>Jun 17, 2013 09:29</a>
                
                                                                                          | <a id="reply-108003725" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=108003725#comment-108003725">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=108003725#comment-108003725"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=108003725#comment-108003725"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/108003725"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                                            </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-105809855"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>When I setup the local direct at the setp: "ant dist-backend"<br/>
I have got some wrong message as follow, is other saw the same or similar trouble.<br/>
init-scorecard:<br/>
<span class="error">&#91;copy&#93;</span> Copying 1 file to E:\TopCoder\Assembly\direct\scorecard_tool\grails-app\conf</p>

<p>scorecard_war:</p>

<p>download-ivy:</p>

<p>-download-ivy:</p>

<p>init-ivy:</p>

<p>-resolve:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: Apache Ivy 1.3.1 - 20060330160721 :: <span class="nobr"><a href="http://ant.apache.org/ivy/" rel="nofollow">http://ant.apache.org/ivy/<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span> ::<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: loading settings :: file = E:\TopCoder\Assembly\direct\scorecard_tool\ivysettings.xml<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: resolving dependencies :: org.example#scorecard;working@carlos-PC<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> confs: <span class="error">&#91;build&#93;</span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> found org.grails#grails-bootstrap;1.3.7 in codehaus<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> found org.codehaus.gpars#gpars;0.9 in codehaus<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> found org.coconut.forkjoin#jsr166y;070108 in codehaus<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> found org.codehaus.gant#gant_groovy1.7;1.9.2 in codehaus<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> found org.codehaus.groovy#groovy-all;1.7.8 in codehaus<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> You probably access the destination server through a proxy server that is not well configured.<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: resolution report :: resolve 45703ms :: artifacts dl 9ms<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: evicted modules:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> org.apache.ant#ant;1.8.0 by <span class="error">&#91;org.apache.ant#ant;1.7.1&#93;</span> in <span class="error">&#91;build&#93;</span><br/>
---------------------------------------------------------------------</p>
<table class='confluenceTable'><tbody>
<tr>
<td class='confluenceTd'>&nbsp;</td>
<td class='confluenceTd'> modules </td>
<th class='confluenceTh'> artifacts </th>
</tr>
<tr>
<td class='confluenceTd'> conf </td>
<td class='confluenceTd'> number</td>
<td class='confluenceTd'> search</td>
<td class='confluenceTd'>dwnlded</td>
<td class='confluenceTd'>evicted</td>
<th class='confluenceTh'> number</th>
<td class='confluenceTd'>dwnlded</td>
</tr>
</tbody></table>
<p>---------------------------------------------------------------------</p>
<table class='confluenceTable'><tbody>
<tr>
<td class='confluenceTd'> build </td>
<td class='confluenceTd'> 12 </td>
<td class='confluenceTd'> 0 </td>
<td class='confluenceTd'> 0 </td>
<td class='confluenceTd'> 1 </td>
<th class='confluenceTh'> 5 </th>
<td class='confluenceTd'> 0 </td>
</tr>
</tbody></table>
<p>---------------------------------------------------------------------<br/>
<span class="error">&#91;ivy:retrieve&#93;</span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: problems summary ::<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :::: WARNINGS<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span></p>

<p><span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span></p>

<p><span class="error">&#91;ivy:retrieve&#93;</span> module not found: org.apache.ivy#ivy;2.2.0<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus-snapshots: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom" rel="nofollow">http://snapshots.repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ivy#ivy;2.2.0!ivy.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar" rel="nofollow">http://snapshots.repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom" rel="nofollow">http://repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ivy#ivy;2.2.0!ivy.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar" rel="nofollow">http://repository.codehaus.org/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== javanet: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom" rel="nofollow">http://download.java.net/maven/2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ivy#ivy;2.2.0!ivy.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar" rel="nofollow">http://download.java.net/maven/2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== spring-milestone: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ivy#ivy;2.2.0!ivy.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== public: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ivy#ivy;2.2.0!ivy.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ivy/ivy/2.2.0/ivy-2.2.0.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.pom" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span></p>

<p><span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.jar" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span></p>

<p><span class="error">&#91;ivy:retrieve&#93;</span> module not found: org.apache.ant#ant;1.7.1<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus-snapshots: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.pom" rel="nofollow">http://snapshots.repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant;1.7.1!ant.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.jar" rel="nofollow">http://snapshots.repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.pom" rel="nofollow">http://repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant;1.7.1!ant.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.jar" rel="nofollow">http://repository.codehaus.org/org/apache/ant/ant/1.7.1/ant-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== javanet: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/apache/ant/ant/1.7.1/ant-1.7.1.pom" rel="nofollow">http://download.java.net/maven/2/org/apache/ant/ant/1.7.1/ant-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant;1.7.1!ant.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/apache/ant/ant/1.7.1/ant-1.7.1.jar" rel="nofollow">http://download.java.net/maven/2/org/apache/ant/ant/1.7.1/ant-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== spring-milestone: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant/1.7.1/ant-1.7.1.pom" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant/1.7.1/ant-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant;1.7.1!ant.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant/1.7.1/ant-1.7.1.jar" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant/1.7.1/ant-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== public: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.pom" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant;1.7.1!ant.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.jar" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant/1.7.1/ant-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
launcher-1.7.1.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
launcher-1.7.1.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> module not found: org.apache.ant#ant-launcher;1.7.1<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus-snapshots: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom" rel="nofollow">http://snapshots.repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant-launcher;1.7.1!ant-launcher.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar" rel="nofollow">http://snapshots.repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom" rel="nofollow">http://repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant-launcher;1.7.1!ant-launcher.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar" rel="nofollow">http://repository.codehaus.org/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== javanet: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom" rel="nofollow">http://download.java.net/maven/2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant-launcher;1.7.1!ant-launcher.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar" rel="nofollow">http://download.java.net/maven/2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== spring-milestone: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant-launcher/1.7.1/ant-laun" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant-launcher/1.7.1/ant-laun<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
cher-1.7.1.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant-launcher;1.7.1!ant-launcher.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant-launcher/1.7.1/ant-laun" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/apache/ant/ant-launcher/1.7.1/ant-laun<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
cher-1.7.1.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== public: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.apache.ant#ant-launcher;1.7.1!ant-launcher.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar" rel="nofollow">http://repo1.maven.org/maven2/org/apache/ant/ant-launcher/1.7.1/ant-launcher-1.7.1.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-ove" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-ove<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
r-slf4j-1.5.8.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-ove" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-ove<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
r-slf4j-1.5.8.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> module not found: org.slf4j#jcl-over-slf4j;1.5.8<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus-snapshots: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom" rel="nofollow">http://snapshots.repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jcl-over-slf4j;1.5.8!jcl-over-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar" rel="nofollow">http://snapshots.repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom" rel="nofollow">http://repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jcl-over-slf4j;1.5.8!jcl-over-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar" rel="nofollow">http://repository.codehaus.org/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== javanet: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom" rel="nofollow">http://download.java.net/maven/2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jcl-over-slf4j;1.5.8!jcl-over-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar" rel="nofollow">http://download.java.net/maven/2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== spring-milestone: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-sl" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-sl<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
f4j-1.5.8.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jcl-over-slf4j;1.5.8!jcl-over-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-sl" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-sl<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
f4j-1.5.8.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== public: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jcl-over-slf4j;1.5.8!jcl-over-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jcl-over-slf4j/1.5.8/jcl-over-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-sl" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-sl<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
f4j-1.5.8.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-sl" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-sl<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
f4j-1.5.8.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> module not found: org.slf4j#jul-to-slf4j;1.5.8<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus-snapshots: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom" rel="nofollow">http://snapshots.repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jul-to-slf4j;1.5.8!jul-to-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar" rel="nofollow">http://snapshots.repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom" rel="nofollow">http://repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jul-to-slf4j;1.5.8!jul-to-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar" rel="nofollow">http://repository.codehaus.org/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== javanet: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom" rel="nofollow">http://download.java.net/maven/2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jul-to-slf4j;1.5.8!jul-to-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar" rel="nofollow">http://download.java.net/maven/2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== spring-milestone: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
1.5.8.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jul-to-slf4j;1.5.8!jul-to-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
1.5.8.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== public: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#jul-to-slf4j;1.5.8!jul-to-slf4j.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/jul-to-slf4j/1.5.8/jul-to-slf4j-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>.<br/>
5.8.pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> Host repo1.maven.org not found. url=<span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>.<br/>
5.8.jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> module not found: org.slf4j#slf4j-api;1.5.8<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus-snapshots: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom" rel="nofollow">http://snapshots.repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#slf4j-api;1.5.8!slf4j-api.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://snapshots.repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar" rel="nofollow">http://snapshots.repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== codehaus: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom" rel="nofollow">http://repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#slf4j-api;1.5.8!slf4j-api.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar" rel="nofollow">http://repository.codehaus.org/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== javanet: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom" rel="nofollow">http://download.java.net/maven/2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#slf4j-api;1.5.8!slf4j-api.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://download.java.net/maven/2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar" rel="nofollow">http://download.java.net/maven/2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== spring-milestone: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>.<br/>
pom<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#slf4j-api;1.5.8!slf4j-api.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8" rel="nofollow">http://s3.amazonaws.com/maven.springframework.org/milestone/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span>.<br/>
jar<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ==== public: tried<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.pom<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> &#8211; artifact org.slf4j#slf4j-api;1.5.8!slf4j-api.jar:<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> <span class="nobr"><a href="http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar" rel="nofollow">http://repo1.maven.org/maven2/org/slf4j/slf4j-api/1.5.8/slf4j-api-1.5.8.jar<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ::::::::::::::::::::::::::::::::::::::::::::::<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: UNRESOLVED DEPENDENCIES ::<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ::::::::::::::::::::::::::::::::::::::::::::::<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: org.apache.ivy#ivy;2.2.0: not found<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: org.apache.ant#ant;1.7.1: not found<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: org.apache.ant#ant-launcher;1.7.1: not found<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: org.slf4j#jcl-over-slf4j;1.5.8: not found<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: org.slf4j#jul-to-slf4j;1.5.8: not found<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: org.slf4j#slf4j-api;1.5.8: not found<br/>
<span class="error">&#91;ivy:retrieve&#93;</span> ::::::::::::::::::::::::::::::::::::::::::::::<br/>
<span class="error">&#91;ivy:retrieve&#93;</span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span><br/>
<span class="error">&#91;ivy:retrieve&#93;</span> :: USE VERBOSE OR DEBUG MESSAGE LEVEL FOR MORE DETAILS</p>

<p>BUILD FAILED<br/>
E:\TopCoder\Assembly\direct\build-master-targets.xml:43: The following error occurred while executing this line:<br/>
E:\TopCoder\Assembly\direct\build.xml:786: The following error occurred while executing this line:<br/>
E:\TopCoder\Assembly\direct\scorecard_tool\build.xml:59: impossible to resolve dependencies:<br/>
resolve failed - see output for details</p>

<p>pleasure to receive your reply or discussion.</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             lcxjtu
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809855#comment-105809855'>Jun 04, 2013 20:04</a>
                
                                                                                          | <a id="reply-105809855" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=105809855#comment-105809855">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809855#comment-105809855"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=105809855#comment-105809855"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/105809855"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-137658849"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>When starting JBoss after deployment, I got the following error in server.log :</p>

<p>............</p>

<p>.......</p>

<p>&nbsp;&nbsp;&nbsp; at java.lang.Thread.run(Thread.java:701)<br/>
Caused by: java.lang.RuntimeException: java.lang.IllegalStateException: Failed to initialize AmazonSNS.<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.interceptor.LifecycleInterceptorHandler.postConstruct(LifecycleInterceptorHandler.java:113)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.EJBContainer.invokePostConstruct(EJBContainer.java:623)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.AbstractPool.create(AbstractPool.java:131)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.InfinitePool.get(InfinitePool.java:49)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.ThreadlocalPool.create(ThreadlocalPool.java:50)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.ThreadlocalPool.get(ThreadlocalPool.java:90)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.stateless.StatelessInstanceInterceptor.invoke(StatelessInstanceInterceptor.java:54)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.aop.joinpoint.MethodInvocation.invokeNext(MethodInvocation.java:101)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.aspects.security.AuthenticationInterceptor.invoke(AuthenticationInterceptor.java:77)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.security.Ejb3AuthenticationInterceptor.invoke(Ejb3AuthenticationInterceptor.java:110)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.aop.joinpoint.MethodInvocation.invokeNext(MethodInvocation.java:101)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.ENCPropagationInterceptor.invoke(ENCPropagationInterceptor.java:46)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.aop.joinpoint.MethodInvocation.invokeNext(MethodInvocation.java:101)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.asynchronous.AsynchronousInterceptor.invoke(AsynchronousInterceptor.java:106)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.aop.joinpoint.MethodInvocation.invokeNext(MethodInvocation.java:101)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.stateless.StatelessContainer.dynamicInvoke(StatelessContainer.java:304)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.remoting.IsLocalInterceptor.invokeLocal(IsLocalInterceptor.java:81)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.remoting.IsLocalInterceptor.invoke(IsLocalInterceptor.java:72)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.aop.joinpoint.MethodInvocation.invokeNext(MethodInvocation.java:101)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.stateless.StatelessRemoteProxy.invoke(StatelessRemoteProxy.java:107)<br/>
&nbsp;&nbsp;&nbsp; at com.sun.proxy.$Proxy366.getActiveTechnologies(Unknown Source)<br/>
&nbsp;&nbsp;&nbsp; at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)<br/>
&nbsp;&nbsp;&nbsp; at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:57)<br/>
&nbsp;&nbsp;&nbsp; at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)<br/>
&nbsp;&nbsp;&nbsp; at java.lang.reflect.Method.invoke(Method.java:622)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.aop.support.AopUtils.invokeJoinpointUsingReflection(AopUtils.java:307)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.aop.framework.JdkDynamicAopProxy.invoke(JdkDynamicAopProxy.java:198)<br/>
&nbsp;&nbsp;&nbsp; at com.sun.proxy.$Proxy355.getActiveTechnologies(Unknown Source)<br/>
&nbsp;&nbsp;&nbsp; at com.topcoder.direct.services.configs.ReferenceDataBean.afterPropertiesSet(ReferenceDataBean.java:329)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.invokeInitMethods(AbstractAutowireCapableBeanFactory.java:1369)<br/>
&nbsp;&nbsp;&nbsp; at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1335)<br/>
&nbsp;&nbsp;&nbsp; ... 148 more<br/>
Caused by: java.lang.IllegalStateException: Failed to initialize AmazonSNS.<br/>
&nbsp;&nbsp;&nbsp; at com.topcoder.service.facade.contest.ejb.ContestServiceFacadeBean.init(ContestServiceFacadeBean.java:1740)<br/>
&nbsp;&nbsp;&nbsp; at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)<br/>
&nbsp;&nbsp;&nbsp; at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:57)<br/>
&nbsp;&nbsp;&nbsp; at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)<br/>
&nbsp;&nbsp;&nbsp; at java.lang.reflect.Method.invoke(Method.java:622)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.interceptor.LifecycleInvocationContextImpl.proceed(LifecycleInvocationContextImpl.java:159)<br/>
&nbsp;&nbsp;&nbsp; at org.jboss.ejb3.interceptor.LifecycleInterceptorHandler.postConstruct(LifecycleInterceptorHandler.java:109)<br/>
&nbsp;&nbsp;&nbsp; ... 178 more<br/>
Caused by: java.lang.NullPointerException <br clear="all" /></p>

<p>It seems that ContestServiceFacadeBean needs to use Amazon SNS. Can you please describe how to get the Amazon SNS access key and secret key, Is it free ?. I tried to create an account in Amazon but requires a Credit Card number.</p>

<p>Please advise.</p>

<p>Thanks </p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             schpotsky
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=137658849#comment-137658849'>Jan 28, 2014 12:34</a>
                
                                                                                          | <a id="reply-137658849" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=137658849#comment-137658849">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=137658849#comment-137658849"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=137658849#comment-137658849"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/137658849"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-137658948"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>Try to use these values</p>


<p><input type="text" name="variableValues.amazonSNSAccessKey" size="12" onkeyup="updateOthers(this)" />&nbsp;<span class="templateparameter">(amazonSNSAccessKey)</span>=AKIAIGN4KRVNTBGLQDJA<br/>
<input type="text" name="variableValues.amazonSNSSecretKey" size="12" onkeyup="updateOthers(this)" />&nbsp;<span class="templateparameter">(amazonSNSSecretKey)</span>=D/ijNVZNiayKcj4s3mI2KpxnE2kvhpcHUyh7g7qY<br/>
<input type="text" name="variableValues.contestCreationArn" size="12" onkeyup="updateOthers(this)" />&nbsp;<span class="templateparameter">(contestCreationArn)</span>=arn:aws:sns:us-west-2:170569073448:tc-test<br/>
<input type="text" name="variableValues.contestCreationSubject" size="12" onkeyup="updateOthers(this)" />&nbsp;<span class="templateparameter">(contestCreationSubject)</span>=cmc challenge contest creation<br/>
<input type="text" name="variableValues.contestCreationMessageTemplatePath" size="12" onkeyup="updateOthers(this)" />&nbsp;<span class="templateparameter">(contestCreationMessageTemplatePath)</span>=contest_creation_sns_message.txt</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             mashannon168
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=137658948#comment-137658948'>Jan 29, 2014 10:29</a>
                
                                                                                          | <a id="reply-137658948" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=137658948#comment-137658948">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=137658948#comment-137658948"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=137658948#comment-137658948"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/137658948"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-140739057"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>after deploy, can't login.<br/>
always redirect to login page.</p>

<p>any idea?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             tangzx
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=140739057#comment-140739057'>Mar 19, 2014 12:56</a>
                
                                                                                          | <a id="reply-140739057" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=140739057#comment-140739057">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=140739057#comment-140739057"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=140739057#comment-140739057"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/140739057"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-141099106"></a>
                <div  class="commentBox" style="background-color:  f0f0f0">
            <div class="commentblock"><p>Social login button or the old login button?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             mashannon168
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=141099106#comment-141099106'>Mar 24, 2014 14:09</a>
                
                                                                                          | <a id="reply-141099106" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=141099106#comment-141099106">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=141099106#comment-141099106"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=141099106#comment-141099106"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/141099106"/>
</rdf:RDF>
-->

                    </div>
        
                                                                                    <div style="padding: 0 0 0  20px ">
        <a name="comment-141099112"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>the old login button.</p>

<p>do we need to do something to make it work which is not mentioned in this page?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             tangzx
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=141099112#comment-141099112'>Mar 24, 2014 14:26</a>
                
                                                                                          | <a id="reply-141099112" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=141099112#comment-141099112">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=141099112#comment-141099112"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=141099112#comment-141099112"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/141099112"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                                            </div>
                                                            </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-148766942"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>which ANT version should be used to deploy using github code? </p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             shazzz
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=148766942#comment-148766942'>Nov 15, 2014 10:11</a>
                
                                                                                          | <a id="reply-148766942" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=148766942#comment-148766942">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=148766942#comment-148766942"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=148766942#comment-148766942"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/148766942"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                                        <div style="padding: 0 0 0  0 ">
        <a name="comment-151552214"></a>
                <div  class="commentBox" style="background-color: ">
            <div class="commentblock"><p>I followed instruction <span class="nobr"><a href="https://github.com/cloudspokes/direct-app/" rel="nofollow">https://github.com/cloudspokes/direct-app/<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span> to deploy the VM.<br/>
I have also done these steps:</p>

<p>1) Update the following to /home/direct/direct token.properties</p>

<p>@ApplicationServer.SERVER_NAME@=cockpit.cloud.topcoder.com<br/>
 Rebuild and restart the topcoder Direct</p>

<p>2) Add the following to /home/tc/jboss-4.0.4.GA/server/all/conf/ApplicationServer.properties<br/>
JWT_COOKIE_KEY = tcjwt<br/>
Restart the jboss under /home/tc</p>


<p>Still I cannot login to the Direct dashboard.<br/>
Login from cockpit.cloud.topcoder.com/direct/, it then redirects to tc.cloud.topcoder.com/reg2/ for auth and it only bring me to the TopCoder error page.</p>

<p>I checked the log, it says that the TC cannot find PrincipalMgrRemoteHome. It seems that security ejb is not bound in TC jboss.</p>

<p>I then manually deploy the security ejb to the /home/tc/jboss-4.0.4.GA/server/all/deploy. PrincipalMgr ejb is now bounded.<br/>
Tried the login once more, now the TC vm yield a different error</p>

<p> <span class="error">&#91;com.topcoder.web.common.SecurityHelper&#93;</span> UNABLE TO INSERT INTO CACHE: getArguments failed<br/>
2014-12-15 03:35:41,907 DEBUG <span class="error">&#91;com.topcoder.web.common.SessionInfo&#93;</span> servername: tc.cloud.topcoder.com servletpath:/reg2/callback.action query: ?code=buFqrFLrAXdTm2En&amp;state=https%3A%2F%2Fcockpit.cloud.topcoder.com%2Fdirect%2F request: <span class="nobr"><a href="http://tc.cloud.topcoder.com/reg2/callback.action?code=buFqrFLrAXdTm2En&amp;state=https%3A%2F%2Fcockpit.cloud.topcoder.com%2Fdirect%2F" rel="nofollow">http://tc.cloud.topcoder.com/reg2/callback.action?code=buFqrFLrAXdTm2En&amp;state=https%3A%2F%2Fcockpit.cloud.topcoder.com%2Fdirect%2F<sup><img class="rendericon" src="/wiki/images/icons/linkext7.gif" height="7" width="7" align="absmiddle" alt="" border="0"/></sup></a></span><br/>
2014-12-15 03:35:41,913 ERROR <span class="error">&#91;com.topcoder.shared.dataAccess.DataRetriever&#93;</span> Exception caught: java.lang.Exception: Query information for command member_count missing from DB<br/>
2014-12-15 03:35:41,913 ERROR <span class="error">&#91;com.topcoder.shared.dataAccess.DataRetriever&#93;</span> The last query run was: <br/>
2014-12-15 03:35:41,913 ERROR <span class="error">&#91;com.topcoder.shared.dataAccess.DataRetriever&#93;</span> SELECT cqx.query_id,  q.text,  q.name,  q.ranking,  q.column_index,  cqx.sort_order,  c.command_id FROM command c, query q, command_query_xref cqx WHERE c.command_desc = ? AND cqx.command_id = c.command_id AND q.query_id = cqx.query_id ORDER BY cqx.sort_order ASC <br/>
2014-12-15 03:35:41,913 ERROR <span class="error">&#91;com.topcoder.shared.dataAccess.DataRetriever&#93;</span> Function inputs were: <br/>
2014-12-15 03:35:41,913 ERROR <span class="error">&#91;com.topcoder.shared.dataAccess.DataRetriever&#93;</span> Input code: c &#8212; Input value: member_count<br/>
2014-12-15 03:35:41,913 ERROR <span class="error">&#91;com.topcoder.shared.dataAccess.DataRetriever&#93;</span> Exception details:<br/>
2014-12-15 03:35:41,914 ERROR <span class="error">&#91;STDERR&#93;</span> java.lang.Exception: Query information for command member_count missing from DB<br/>
2014-12-15 03:35:41,914 ERROR <span class="error">&#91;STDERR&#93;</span> 	at com.topcoder.shared.dataAccess.DataRetriever.executeCommand(DataRetriever.java:386)</p>


<p>Any help on this?</p></div>
            <div align="left" class="smallfont" style="color: #666666; width: 98%">
                         <img src="/wiki/images/icons/comment_16.gif" height="16" width="16" border="0" align="absmiddle"/>
    
                                
                
                                    Posted by             suno1234
 at <a href='/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=151552214#comment-151552214'>Feb 03, 2015 10:48</a>
                
                                                                                          | <a id="reply-151552214" href="/wiki/display/docs/TC+Direct+Setup+Guide?replyToComment=151552214#comment-151552214">Reply To This</a>
                                              </div>

            <!--
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
         xmlns:dc="http://purl.org/dc/elements/1.1/"
         xmlns:trackback="http://madskills.com/public/xml/rss/module/trackback/">
<rdf:Description
    rdf:about="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=151552214#comment-151552214"
    dc:identifier="http://apps.topcoder.com/wiki/display/docs/TC+Direct+Setup+Guide?focusedCommentId=151552214#comment-151552214"
    dc:title="$comment.title"
    trackback:ping="http://apps.topcoder.com/wiki/rpc/trackback/151552214"/>
</rdf:RDF>
-->

                    </div>
        
                                </div>
                            
            
                                        <div ">
                <a href="/wiki/display/docs/TC+Direct+Setup+Guide?showComments=true&showCommentArea=true#addcomment"><img src="/wiki/images/icons/add_comment_16.gif" height="16" width="16" border="0" align="absmiddle"></a>
                <a href="/wiki/display/docs/TC+Direct+Setup+Guide?showComments=true&showCommentArea=true#addcomment">Add Comment</a>
                </div>
                        </div>



                                                            </td>


                                                    </tr>
        </table>

        
        </td>
    </tr>
</table>

    

        </td>
    </tr>
</tbody>
</table>


<!-- delay the loading of large javascript files to the end so that they don't interfere with the loading of page content -->
<span style="display: none">
    <script type="text/javascript" language="JavaScript">var domainName = 'http://apps.topcoder.com/wiki'; var entityId = '57018232'; var spaceKey = 'docs'</script>
    <script type="text/javascript" language="JavaScript" src="/wiki/s/1109/1/_/labels-javascript"></script>
    <script>new Ajax.Autocompleter('labelName', 'labelsAutocompleteList', '57018232', { tokens: new Array(',', ' '), dwrFunction: GenerateAutocompleteLabelsListForEntity.autocompleteLabels});</script>
</span>

<table width="100%" border="0" cellpadding="0" cellspacing="0">
<tbody>
    <tr>
        <td width="100%" class="footer">
            <a href="http://www.topcoder.com/" class="footerLinks">Home</a>  |  
            <a href="http://www.topcoder.com/tc?module=Static&d1=about&d2=index" class="footerLinks">About TopCoder</a>  |  
            <a href="http://www.topcoder.com/tc?module=Static&d1=pressroom&d2=index" class="footerLinks">Press Room</a>  |  
            <a href="http://www.topcoder.com/tc?module=Static&d1=about&d2=contactus" class="footerLinks">Contact Us</a>  |  
            <a href="http://www.topcoder.com/tc?module=Static&d1=about&d2=privacy" class="footerLinks">Privacy</a>  |  
            <a href="http://www.topcoder.com/tc?module=Static&d1=about&d2=terms" class="footerLinks">Terms</a>
            <br />
            <a href="http://www.topcoder.com/tc" class="footerLinks">Developer Center</a>  |  
            <a href="http://www.topcoder.com/corp/?module=Static&d1=corp&d2=index" class="footerLinks">Corporate Services</a>
        </td>
    </tr>
    <tr><td width="100%" class="copyright">Copyright TopCoder, Inc. 2001-<script type="text/javascript">d=new Date();document.write(d.getFullYear());</script></td></tr>
</tbody>
</table>

</body>
</html>
