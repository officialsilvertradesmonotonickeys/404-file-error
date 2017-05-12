[ViewStateException: Invalid viewstate. 
	Client IP: 192.168.15.17
	Port: 49574
	Referer: https://profiles.newsmax.com/sso/signup.aspx?ReturnUrl=http%3A%2F%2Fwww.newsmaxtv.com%2F
	Path: /CMSPages/PortalTemplate.aspx
	User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.96 Safari/537.36
	ViewState: /wEPDwUJODc3OTc4NjAwD2QWAgIBEGRkFgICBQ9kFgJmD2QWAmYPZBYCAgMPZBYCZg9kFgICAg9kFgJmD2QWAmYPZBYCZg9kFgJmDw8WAh4JUmV0dXJuVXJsBRlodHRwOi8vd3d3Lm5ld3NtYXh0di5jb20vZBYCAgEPZBYCAgEPZBYEAgUPDxYCHhRWYWxpZGF0aW9uRXhwcmVzc2lvbgWfAV5bQS1aYS16MC05ISMkJSYnKisvPT9eX2B7fH1+LV0rKD86XC5bQS1aYS16MC05ISMkJSYnKisvPT9eX2B7fH1+LV0rKSpAKD86W0EtWmEtejAtOV0oPzpbQS1aYS16MC05LV0qW0EtWmEtejAtOV0pP1wuKStbQS1aYS16MC05XSg/OltBLVphLXowLTktXSpbQS1aYS16MC05XSk/JGRkAjcPEA8WAh4LXyFEYXRhQm91bmRnZBAV9gELQWZnaGFuaXN0YW4HQWxiYW5pYQdBbGdlcmlhDkFtZXJpY2FuIFNhbW9hB0FuZG9ycmEGQW5nb2xhCEFuZ3VpbGxhCkFudGFyY3RpY2ETQW50aWd1YSBhbmQgQmFyYnVkYQlBcmdlbnRpbmEHQXJtZW5pYQVBcnViYQlBdXN0cmFsaWEHQXVzdHJpYQpBemVyYmFpamFuB0JhaGFtYXMHQmFocmFpbgpCYW5nbGF...]

[HttpException (0x80004005): Validation of viewstate MAC failed. If this application is hosted by a Web Farm or cluster, ensure that <machineKey> configuration specifies the same validationKey and validation algorithm. AutoGenerate cannot be used in a cluster.

See http://go.microsoft.com/fwlink/?LinkID=314055 for more information.]
   System.Web.UI.ViewStateException.ThrowError(Exception inner, String persistedState, String errorPageMessage, Boolean macValidationError) +147
   System.Web.UI.ObjectStateFormatter.Deserialize(String inputString, Purpose purpose) +625
   System.Web.UI.Util.DeserializeWithAssert(IStateFormatter2 formatter, String serializedState, Purpose purpose) +67
   System.Web.UI.HiddenFieldPageStatePersister.Load() +311
   System.Web.UI.Page.LoadPageStateFromPersistenceMedium() +420
   System.Web.UI.Page.LoadAllState() +51
   System.Web.UI.Page.ProcessRequestMain(Boolean includeStagesBeforeAsyncPoint, Boolean includeStagesAfterAsyncPoint) +5366
   System.Web.UI.Page.ProcessRequest(Boolean includeStagesBeforeAsyncPoint, Boolean includeStagesAfterAsyncPoint) +1273
   System.Web.UI.Page.ProcessRequest(Boolean includeStagesBeforeAsyncPoint, Boolean includeStagesAfterAsyncPoint) +1656
   System.Web.UI.Page.ProcessRequest() +105
   System.Web.UI.Page.ProcessRequest(HttpContext context) +129
   System.Web.CallHandlerExecutionStep.System.Web.HttpApplication.IExecutionStep.Execute() +1440
   System.Web.CallHandlerExecutionStep.System.Web.HttpApplication.IExecutionStep.Execute() +2450
   System.Web.HttpApplication.ExecuteStep(IExecutionStep step, Boolean& completedSynchronously) +946# 404-file-error
404 page errror 
