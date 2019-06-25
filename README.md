<!DOCTYPE html>



<html>
<head id="headLogin">
    <style type="text/css">
        .text {
            font-size: 12px;
            color: #506473;
            font-family: Sans-Serif;
        }

        .title {
            font-size: 30px;
            font-family: Sans-Serif;
            color: Black;
        }

        .td {
            font-style: normal;
            font-size: medium;
        }

        .modalBackground {
            background-color: black;
            filter: alpha(opacity=60);
            opacity: 0.6;
        }

        .detail {
            border-color: Gray;
            border-style: solid;
            width: 330px;
            height: 320px;
            border-width: thick;
            font-size: small;
            background-color: White;
        }

        .login-btn {
            width: 240px;
            height: 35px;
            display: block;
            font-family: Arial, "Helvetica", sans-serif;
            font-size: 16px;
            font-weight: bold;
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            text-align: center;
            text-shadow: 1px 1px 0px #37a69b;
            padding-top: 6px;
            margin: 15px 0 0 0;
            position: relative;
            cursor: pointer;
            border: none;
            background-color: #37a69b;
            background-image: linear-gradient(top,#3db0a6,#3111);
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
            border-bottom-right-radius: 5px;
            border-bottom-left-radius: 5px;
            box-shadow: inset 0px 1px 0px #2ab7ec, 0px 5px 0px 0px #497a78, 0px 10px 5px #999;
        }
    </style>
    <title>
        Invisible - Anonymous Feedback
    </title>
</head>
<body marginwidth="0" marginheight="0" topmargin="0" leftmargin="0">
    <form name="formLogin" method="post" action="./loginpage.aspx" id="formLogin">
        <input id="__PortalCSRFToken" type="hidden" name="__PortalCSRFToken" value="99dd0a3c-cada-4f15-9031-dac893c2648e" />
        <div>
            <input type="hidden" name="__EVENTTARGET" id="__EVENTTARGET" value="" />
            <input type="hidden" name="__EVENTARGUMENT" id="__EVENTARGUMENT" value="" />
            <input type="hidden" name="__VIEWSTATE" id="__VIEWSTATE" value="/wEPDwUKLTMyMzk0Njg4MWQYAQUeX19Db250cm9sc1JlcXVpcmVQb3N0QmFja0tleV9fFgIFEGNoa1VzZXJBZ3JlZW1lbnQFD2Noa1dpbmRvd3NMb2dpbg5X0B71B+MNUnUT6v9vseU1aGjwHYPyTMpw7a8saluF" />
        </div>

        <script type="text/javascript">
//<![CDATA[
var theForm = document.forms['formLogin'];
if (!theForm) {
    theForm = document.formLogin;
}
function __doPostBack(eventTarget, eventArgument) {
    if (!theForm.onsubmit || (theForm.onsubmit() != false)) {
        theForm.__EVENTTARGET.value = eventTarget;
        theForm.__EVENTARGUMENT.value = eventArgument;
        theForm.submit();
    }
}
//]]>
        </script>
        <script type="text/javascript">
//<![CDATA[
if (typeof(Sys) === 'undefined') throw new Error('ASP.NET Ajax client-side framework failed to load.');
//]]>
        </script>

        <div>

            <input type="hidden" name="__VIEWSTATEGENERATOR" id="__VIEWSTATEGENERATOR" value="7F7DBA9C" />
            <input type="hidden" name="__EVENTVALIDATION" id="__EVENTVALIDATION" value="/wEdAAj6Z4Hn3i5DqTByZVX9Jq+K2QPusZQWj2p67zIF+ycbC2N6ZYJNGAQHn0c9zMgZU3B2NvjHOkq5wKoqN6Aim8WG16yW+2q+6wN8x2103BsKBKKeKEbp39eHc9mbdvkCgxABAed/FI+VO/+rajOXWzBIcOJNvwqY098LMLmBG5qMHQqYqAKCe0KQxW22SCQiMC/tw6tdRH3hX9S9VENI2Rsh" />
        </div>
        <script type="text/javascript">
//<![CDATA[
Sys.WebForms.PageRequestManager._initialize('smLogin', 'formLogin', ['tupnlTicketInformation',''], [], ['btnOk',''], 90, '');
//]]>
        </script>

        <div style="width: 100%;">
            <div style="width: 100%;">
                <img id="imgBanner" src="Images\banner.jpg" style="height:0%;width:100%;border-width:0px;" />
            </div>

            <div style="width: 100%">
                <table style="width: 100%;">
                    <tr>
                        <td style="width: 72%;" valign="top">
                            
                            <br />
                            <div style="background-color:#F5F5F5;border-radius:10px;color:white;padding:10px;font-style:normal;">
                                <table style="margin-left:1%;" width="100%" border="0">
                                    <tr>
                                        <td>
                                            <span style="color:Black;font-family:Sans-Serif;"><input id="chkUserAgreement" type="checkbox" name="chkUserAgreement" checked="checked" /><label for="chkUserAgreement">I agree that I will maintain the.......................</label></span>

                                        </td>
                                    </tr>
                                </table>
                            </div>
                        </td>
                        <td style="width: 50%;" valign="top">
                            <center>
                                <div style="background: #eceeee;
    					            border: 1px solid #42464b;
    					            border-radius: 6px;
    					            height: 238px;
    					            margin: 20px auto 0;
    					            width: 298px;">
                                    <input name="txtUserName" type="text" id="txtUserName" placeholder="Domain\LoginId" style=" border: 1px solid #a1a3a3;border-radius: 4px;box-shadow: 0 1px #fff;box-sizing: border-box;color: #696969;height: 39px;margin: 15px 0 0 0;
    				                    padding-left: 14px; transition: box-shadow 0.3s;width: 240px;display:block;" />
                                    <input name="txtPassword" type="password" id="txtPassword" placeholder="Password" style=" border: 1px solid #a1a3a3;border-radius: 4px; box-shadow: 0 1px #fff;box-sizing: border-box;color: #696969;height: 39px;
    			                        margin: 15px 0 0 0;padding-left: 14px;transition: box-shadow 0.3s;width: 240px;" />
                                    <span style="display:inline-block;color:Black;background-color:WhiteSmoke;font-family:Sans-Serif;font-size:8pt;width:245px;margin: 15px 0 0 0;display:block;"><input id="chkWindowsLogin" type="checkbox" name="chkWindowsLogin" /><label for="chkWindowsLogin">Use Windows Credentials</label></span>

                                    <input type="submit" name="btnLogin" value="Login" onclick="return checkFields();" id="btnLogin" style="background-color: #37a69b;height: 35px;display: block; font-size: 16px;font-weight: bold;color: #fff;   padding-top: 6px;margin: 15px 0 0 0;   background-image: linear-gradient(top,#3db0a6,#3111);
    			                        border-top-left-radius: 5px;border-top-right-radius: 5px;border-bottom-right-radius: 5px;border-bottom-left-radius: 5px;box-shadow: inset 0px 1px 0px #2ab7ec, 0px 5px 0px 0px #497a78, 0px 10px 5px #999;
			                            background-image: linear-gradient(top,#3db0a6,#3111);text-decoration: none;text-transform: uppercase;text-align: center; text-shadow: 1px 1px 0px #37a69b;width: 240px;position: relative;cursor: pointer;border: none;" />
                                    <br />
                                    <span id="lblError" style="color:Red;font-weight:bold;margin-bottom: 0px"></span>

                                </div>
                                <div class="shadow"></div>

                                <br />
                            </center>
                            <br />
                        </td>
                    </tr>
                </table>

            </div>
        </div>

        <div style="vertical-align: bottom; margin: 0 auto;">
            <center>
                <span id="lblCopyRightsInfo" style="color:#506473;">Copyright Ⓒ 2019 Siemens Technology and Services Private Limited .</span>
            </center>
        </div>



        <div id="pnlTicketInformation" class="detail" style="display: none">

            <div id="upnlTicketInformation">


                <input type="submit" name="btnTicketInformation" value="" id="btnTicketInformation" style="display: none" />
                <table>
                    <tr>
                        <td colspan="2">
                            <center>
                                <br />
                                <span id="lblToolName" style="font-size:16px;font-weight:bold;"></span>
                            </center>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <img src="Data/Images/ApplicationImages/new-version.png" style="height: 125px; width: 125px; float: right;" />
                        </td>
                        <td>
                            <span id="lblTicketInformation" style="font-size:12px;"></span>
                            <br />
                            <br />
                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            <input type="submit" name="btnOk" value="OK" id="btnOk" />
                        </td>
                    </tr>
                </table>

            </div>

        </div>
        <script type="text/javascript">

            /// <summary>
            /// Method to validate the Text boxes on login
            /// </summary>
            function checkFields() {
                if (document.getElementById('chkUserAgreement').checked == false) {
                        alert('Kindly accept user agreement');
                        return false;
                 }
                if (document.getElementById('chkWindowsLogin').checked) {
                    return true;
                }
                else {
                    if (trim(document.getElementById('txtUserName').value) == '') {
                        alert('Enter Login Id');
                        return false;
                    }
                    if (trim(document.getElementById('txtPassword').value) == '') {
                        alert('Enter Password ');
                        return false;
                    }

                }
                return true;
            }

            /// <summary>
            /// Method to trim unwanted space at the begning & end of the string.
            /// </summary>
            function trim(stringToTrim) {
                return stringToTrim.replace(/^\s+|\s+$/g, "");
            }
        </script>


        <script type="text/javascript">
//<![CDATA[
Sys.Application.add_init(function() {
    $create(AjaxControlToolkit.ModalPopupBehavior, {"BackgroundCssClass":"modalBackground","PopupControlID":"pnlTicketInformation","dynamicServicePath":"/iport/loginpage.aspx","id":"mdlTicketInformation"}, null, null, $get("btnTicketInformation"));
});
//]]>
        </script>
    </form>
</body>
</html>
