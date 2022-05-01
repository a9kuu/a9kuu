
   $$$$$$\                 $$\ $$\      $$\ $$\
  \_$$  _|                $$ |$$$\    $$$ |\__|
     $$ |  $$$$$$$\   $$$$$$$ |$$$$\  $$$$ |$$\ $$$$$$$\   $$$$$$\   $$$$$$\
     $$ |  $$  $$\ $$  __$$ |$$\$$\$$ $$ |$$ |$$  __$$\ $$  __$$\ $$  __$$\
     $$ |  $$ |  $$ |$$ /  $$ |$$ \$$$  $$ |$$ |$$ |  $$ |$$$$$$$$ |$$ |  \|
     $$ |  $$ |  $$ |$$ |  $$ |$$ |\$  /$$ |$$ |$$ |  $$ |$$   ____|$$ |
   $$$$$$\ $$ |  $$ |\$$$$$$$ |$$ | \_/ $$ |$$ |$$ |  $$ |\$$$$$$$\ $$ |
  \______|\__|  \__| \_______|\__|     \__|\__|\__|  \__| \_______|\__|

                          v1.2.5.1 | indminer.tk



Unhandled Exception: System.Net.WebException: An exception occurred during a WebClient request. ---> System.Configuration.ConfigurationErrorsException: Error creating the Web Proxy specified in the 'system.net/defaultProxy' configuration section. ---> System.Net.Sockets.SocketException: An attempt was made to access a socket in a way forbidden by its access permissions
   at System.Net.SafeCloseSocketAndEvent.CreateWSASocketWithEvent(AddressFamily addressFamily, SocketType socketType, ProtocolType protocolType, Boolean autoReset, Boolean signaled)
   at System.Net.NetworkAddressChangePolled..ctor()
   at System.Net.AutoWebProxyScriptEngine.AutoDetector.Initialize()
   at System.Net.AutoWebProxyScriptEngine.AutoDetector.get_CurrentAutoDetector()
   at System.Net.AutoWebProxyScriptEngine..ctor(WebProxy proxy, Boolean useRegistry)
   at System.Net.WebProxy.UnsafeUpdateFromRegistry()
   at System.Net.WebProxy..ctor(Boolean enableAutoproxy)
   at System.Net.Configuration.DefaultProxySectionInternal..ctor(DefaultProxySection section)
   at System.Net.Configuration.DefaultProxySectionInternal.GetSection()
   --- End of inner exception stack trace ---
   at System.Net.Configuration.DefaultProxySectionInternal.GetSection()
   at System.Net.WebRequest.get_InternalDefaultWebProxy()
   at System.Net.HttpWebRequest..ctor(Uri uri, ServicePoint servicePoint)
   at System.Net.HttpRequestCreator.Create(Uri Uri)
   at System.Net.WebRequest.Create(Uri requestUri, Boolean useUriBase)
   at System.Net.WebRequest.Create(Uri requestUri)
   at System.Net.WebClient.GetWebRequest(Uri address)
   at System.Net.WebClient.DownloadFile(Uri address, String fileName)
   --- End of inner exception stack trace ---
   at System.Net.WebClient.DownloadFile(Uri address, String fileName)
   at System.Net.WebClient.DownloadFile(String address, String fileName)
   at ♥️ .☻(String[] ☻)
