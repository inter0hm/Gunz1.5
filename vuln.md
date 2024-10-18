CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZBirdDummyClient.h

87
	void SetPlayerName(const char* szPlayerName) { strcpy(m_szPlayerName, szPlayerName); }
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZBirdDummyClient.h

87
	void SetPlayerName(const char* szPlayerName) { strcpy(m_szPlayerName, szPlayerName); }
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZItemMenu.h

32
	void SetTargetName(const char* pszItemName) { strcpy(m_szItemName, pszItemName); }
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MDatabase/Include/
ODBCRecordset.h

57
		memcpy( m_Data, pData, nInDataSize );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MUpdate/
MFTCmd.h

67
		strcpy(m_szRemoteFileName, pszRemoteFileName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MUpdate/
MFTCmd.h

67
		strcpy(m_szRemoteFileName, pszRemoteFileName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MUpdate/
MFTCmd.h

68
		strcpy(m_szLocalFileName, pszLocalFileName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/ServerKeeper/
MServerKeeper.h

62
		strcpy(m_szServerPath, pszPath);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/ServerKeeper/
MServerKeeper.h

60
		strcpy(m_szServerType, pszType);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/ServerKeeper/
MServerKeeper.h

60
		strcpy(m_szServerType, pszType);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/ServerKeeper/
MServerKeeper.h

61
		strcpy(m_szServerName, pszName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/ServerKeeper/
MServerKeeper.h

61
		strcpy(m_szServerName, pszName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/ServerKeeper/
MServerKeeper.h

62
		strcpy(m_szServerPath, pszPath);
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/IncBuildNumber/
AssemblyInfo.vb

1
Imports System.Reflection
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/IncBuildNumber/
Connect.vb

37
	Public Sub OnDisconnection(ByVal RemoveMode As Extensibility.ext_DisconnectMode, ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnDisconnection
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/IncBuildNumber/
Connect.vb

31
	Public Sub OnAddInsUpdate(ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnAddInsUpdate
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/IncBuildNumber/
Connect.vb

28
	Public Sub OnBeginShutdown(ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnBeginShutdown
MEDIUM
Error prone


Move 'Connect' into a named namespace.

Stable/Utils/IncBuildNumber/
Connect.vb

20
Public Class Connect
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/IncBuildNumber/
Connect.vb

34
	Public Sub OnStartupComplete(ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnStartupComplete
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/IncBuildNumber/
Connect.vb

1
Imports Microsoft.Office.Core
MEDIUM
Error prone


Either remove or fill this block of code.

Stable/Utils/IncBuildNumber/
Connect.vb

60
			Catch e as System.Exception
MINOR
Unused code


Remove the unused local variable 'addInInstance'.

Stable/Utils/IncBuildNumber/
IncreaseBuildNumber.vb

 
MEDIUM
Unused code


Remove this unused procedure parameter 'Scope'.

Stable/Utils/IncBuildNumber/
IncreaseBuildNumber.vb

 
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/IncBuildNumber/
IncreaseBuildNumber.vb

1
Imports EnvDTE
CRITICAL
Error prone


Switch this use of the '+' operator to the '&'.

Stable/Utils/IncBuildNumber/
IncreaseBuildNumber.vb

 
CRITICAL
Error prone


Switch this use of the '+' operator to the '&'.

Stable/Utils/IncBuildNumber/
IncreaseBuildNumber.vb

53
    ByVal count As Integer, ByVal incrementby As Integer, _
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/MEncrypt/
FFileList.h

10
		memset(m_name,0,256);
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/OpenOpposite/
AssemblyInfo.vb

1
Imports System.Reflection
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/OpenOpposite/
Connect.vb

31
    Public Sub OnStartupComplete(ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnStartupComplete
MEDIUM
Error prone


Either remove or fill this block of code.

Stable/Utils/OpenOpposite/
Connect.vb

83
            Catch e As System.Exception
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/OpenOpposite/
Connect.vb

25
    Public Sub OnBeginShutdown(ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnBeginShutdown
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/OpenOpposite/
Connect.vb

34
    Public Sub OnDisconnection(ByVal RemoveMode As Extensibility.ext_DisconnectMode, ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnDisconnection
CRITICAL
Error prone


Add a nested comment explaining why this method is empty, throw a 'NotSupportedException' or complete the implementation.

Stable/Utils/OpenOpposite/
Connect.vb

28
    Public Sub OnAddInsUpdate(ByRef custom As System.Array) Implements Extensibility.IDTExtensibility2.OnAddInsUpdate
MEDIUM
Error prone


Move 'Connect' into a named namespace.

Stable/Utils/OpenOpposite/
Connect.vb

17
Public Class Connect
MINOR
Unused code


Remove the unused local variable 'colAddins'.

Stable/Utils/OpenOpposite/
Connect.vb

72
                Dim colAddins As AddIns
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/OpenOpposite/
Connect.vb

1
Imports Microsoft.Office.Core
MINOR
Unused code


Remove the unused local variable 'cmdobj'.

Stable/Utils/OpenOpposite/
Connect.vb

69
                Dim cmdobj As Command
CRITICAL
Error prone


Add the missing 'Else' clause.

Stable/Utils/OpenOpposite/
Connect.vb

102
            ElseIf cmdName = "OpenOpposite.Connect.ExpandSolution" Then
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/OpenOpposite/
ExpandSolution.vb

1
Imports EnvDTE
CRITICAL
Error prone


Switch this use of the '+' operator to the '&'.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

36
            strFind1 = strCurrent.Substring(0, strCurrent.Length - 4) + ".H"
CRITICAL
Error prone


Add the missing 'Else' clause.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

39
        ElseIf strCurrent.EndsWith(".H") Then
CRITICAL
Error prone


Switch this use of the '+' operator to the '&'.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

38
            strFind1 = strCurrent.Substring(0, strCurrent.Length - 2) + ".H"
CRITICAL
Error prone


Add the missing 'Else' clause.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

15
            ElseIf UCase(item.Name) = strFind2 Then
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

1
Imports EnvDTE
CRITICAL
Error prone


Switch this use of the '+' operator to the '&'.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

41
            strFind2 = strCurrent.Substring(0, strCurrent.Length - 2) + ".C"
CRITICAL
Error prone


Switch this use of the '+' operator to the '&'.

Stable/Utils/OpenOpposite/
OpenOpposite.vb

40
            strFind1 = strCurrent.Substring(0, strCurrent.Length - 2) + ".CPP"
CRITICAL
Error prone


Add or update the header of this file.

Stable/Utils/OpenOpposite/
ShowFullPath.vb

1
Imports EnvDTE
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
rpng2-win.c

766
        int x, y, len = strlen(msg);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
rpng2-win.c

711
        memset(wimage_data, 0, wimage_rowbytes*rpng2_info.height);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
rpng2-win.c

694
    memset(dib, 0, sizeof(BITMAPINFOHEADER));
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/pngminus/
pnm2png.c

114
      if ((fp_wr = fopen (argv[argi], "wb")) == NULL)
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/pngminus/
pnm2png.c

521
  sscanf ((const char *) token, "%lu", &ret_value);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
PngFile.c

300
    if (!(pfFile = fopen(pstrFileName, "wb")))
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

265
            strcat(filename_try,".zip");
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

122
    ftestexist = fopen(filename,"rb");
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

363
                    fin = fopen(filenameinzip,"rb");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

255
        strncpy(filename_try, argv[zipfilenamearg],MAXFILENAME-1);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

327
                  (strlen(argv[i]) == 2)))
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

79
    strncpy(name, f,MAXFILENAME-1);
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

255
        strncpy(filename_try, argv[zipfilenamearg],MAXFILENAME-1);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

79
    strncpy(name, f,MAXFILENAME-1);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

265
            strcat(filename_try,".zip");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
zip.c

747
    size_filename = (uInt)strlen(filename);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
zip.c

745
        size_comment = (uInt)strlen(comment);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

178
        BlockSizeUncompress=atol(argv[3]);
MEDIUM
Security


Avoid using user-controlled format strings passed into 'sprintf', 'printf' and 'vsprintf'. These functions put you at risk of buffer overflow vulnerabilities through the use of format string exploits.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

169
        printf("error reading %s\n",argv[1]);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

124
    stream=fopen(filename, "rb");
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

181
        cprLevel=(int)atol(argv[4]);
MEDIUM
Security


Avoid using user-controlled format strings passed into 'sprintf', 'printf' and 'vsprintf'. These functions put you at risk of buffer overflow vulnerabilities through the use of format string exploits.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

172
    else printf("file %s read, %u bytes\n",argv[1],lFileSize);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

137
  strcpy(buffer,arcname);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

482
                      outfile = fopen(fname,"wb");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

197
  sprintf(result,"%4d/%02d/%02d %02d:%02d:%02d",
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

142
       strcpy(buffer+origlen,TGZsuffix[i]);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

137
  strcpy(buffer,arcname);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

440
              strncpy(fname,buffer.header.name,SHORTNAMESIZE);
MEDIUM
Security

Insecure Storage


Usage of the `chmod` function call hints at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

277
      chmod(item->fname,item->mode);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

514
              if (fname[BLOCKSIZE-1] != 0 || (int)strlen(fname) > remaining)
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/examples/
zran.c

362
    in = fopen(argv[1], "rb");
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
trees.c

332
    FILE *header = fopen("trees.h", "w");
MEDIUM
Code style


Avoid using global variables

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/HTML/1033/
plugarray.js

18
	PlugArray = [	
MINOR
Error prone


`PlugArray` is assigned twice; the first assignment is useless

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/HTML/1033/
plugarray.js

17
	var PlugArray	 = new Array();
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

189
        if (strName == 'root.vcxproj.filters_template')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

180
		if (strName == 'root.def')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

186
        if (strName == 'root.vcxproj_template')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

22
		if (e.description.length != 0)
MINOR
Code style


Avoid using if...else statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

251
		else ret += s.substring(i,i+1);
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

171
		if (strName == 'dllentry.cpp')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

183
		if (strName == 'root.rc')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

174
		if (strName == wizard.FindSymbol('PLUGINTYPE_TEMPLATE') + '.cpp')
MEDIUM
Error prone


Use ===/!== to compare with true/false or Numbers

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

22
		if (e.description.length != 0)
MINOR
Code style


Avoid using if...else statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

250
			ret += '\\\\';
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

104
	if( wizard.FindSymbol('FILE_EXPORT_3DXI_TYPE'))
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

192
        if (strName == 'root.vcxproj.user_template')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

224
				if(strExt==".bmp" || strExt==".ico" || strExt==".gif" || strExt==".rtf" || strExt==".css")
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

177
		if (strName == 'root.h')
MINOR
Error prone


`strProjectNameWithExt` is assigned twice; the first assignment is useless

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

48
		var strProjectNameWithExt = '';
MEDIUM
Code style


Avoid using global variables

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

280
		pExt  = wizard.FindSymbol("PLUGEXT");
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

101
	if( wizard.FindSymbol('IMAGE_VIEWER_TYPE') )
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

168
		if (strName == 'sample.txt')
MINOR
Code style


Avoid using if statements without curly braces

Stable/sdk/maxsdk/howto/3dsmaxPluginWizard/Scripts/1033/
default.js

165
		if (strName == 'readme.txt')
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Include/
MAsyncDBJob_DuelTournament.h

133
		memset(m_szTimeStamp, 0, DUELTOURNAMENT_TIMESTAMP_MAX_LENGTH + 1);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MMatchServer.cpp

4112
		strcat(szTemp, szLog);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

100
	int nEnd = (int)strlen(szBuf)-1;
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchServer.cpp

2175
		memset(pNode, 0, sizeof(MTD_PeerListNode));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MMatchServer.cpp

485
				strcat(szText, ", ");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

2082
				memcpy(&nTotalSize, pData, sizeof(nTotalSize));
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

485
				strcat(szText, ", ");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

4112
		strcat(szTemp, szLog);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

4142
	strcpy(mail.message, "This is a test send");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MMatchServer.cpp

4142
	strcpy(mail.message, "This is a test send");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

484
				strcat(szText, MGetMapDescMgr()->GetMapName(i)); 
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchServer.cpp

147
	memset(pDest, 0, sizeof(MTD_CharInfo));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

2248
	if (strlen(pszSenderName) < 2) return;
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

133
	sprintf(szDesc, "Windows = %d.%d Build %d , %s (%dKB) : ", os.dwMajorVersion, os.dwMinorVersion,
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Gunz/
MSysInfo.cpp

34
			memcpy(CPUBrandString,
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

149
		if(os.dwMinorVersion==0)		sprintf(szDesc," Windows 2000..\n");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Gunz/
MSysInfo.cpp

40
			memcpy(CPUBrandString + 16,
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

151
		else if(os.dwMinorVersion==2)	sprintf(szDesc," Windows 2003..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

165
		sprintf(szDesc," ..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
Mint4Gunz.h

22
		sprintf(aliasname,"%s%s",fname,ext);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZBandiCapturer.cpp

202
	strcpy(pPath, foldername);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZBandiCapturer.cpp

244
		strcat(foldername, "\\Screenshots");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZCharacterSelectView.cpp

367
		strcpy( szName, pLabel->GetText());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

687
		sprintf( szName, "CharSel_Name%d", i);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

755
		sprintf( szWidgetName, "CharSel_Name%d", i);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Gunz/
ZCharacterSelectView.cpp

922
	memcpy(&ZCharacterSelectView::m_CharInfo[nCharNum].m_CharInfo, pCharInfo, sizeof(MTD_CharInfo));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCharacterSelectView.cpp

725
	if (strlen(m_CharInfo[nIndex].m_AccountCharInfo.szName) <= 0) return true;
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

775
		sprintf( szWidgetName, "CharSel_Selectbar%d", i);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZCharacterSelectView.cpp

69
	strcpy(m_szLastChar, szName); 
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Gunz/
ZCharacterSelectView.cpp

732
	memset(ZCharacterSelectView::m_CharInfo, 0, sizeof(ZSelectCharacterInfo) * MAX_CHAR_COUNT);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

360
	sprintf( szWidgetName, "CharSel_Name%d", m_nSelCharIndex);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCharacterSelectView.cpp

376
		mlog( ")  (len = %d)\n", (int)strlen( szName));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZCombatChat.cpp

86
				strcpy(szMsg, pWidget->GetText());
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZCombatChat.cpp

85
				strcpy(szMsg, szCommand);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

57
		sprintf(szBar[CH_CENTER],	"%s%02d%s",		FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

73
		sprintf(szBar[CH_BOTTOM],	"%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_BOTTOM,FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

58
		sprintf(szBar[CH_TOP],		"%s%02d%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_TOP,		FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

77
		sprintf(szPick[CH_CENTER],	"%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

65
		sprintf(szPick[CH_BOTTOM],	"%s%02d%s%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_BOTTOM,	FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZGameInterface_OnCommand.cpp

816
			if( 3 > strlen(szCountryCode) )
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZItemMenu.h

32
	void SetTargetName(const char* pszItemName) { strcpy(m_szItemName, pszItemName); }
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZScreenDebugger.cpp

703
	sprintf(buf, "     LAND(%s), BLAST(%s), BLASTDAGGER(%s), MOVING(%s), DEAD(%s), REQUESTED_DEAD(%s), MY_CONTROL(%s), DistFloor(%.2f)",
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

677
		strcpy(szTaskName, pCurrTask->GetTaskName());
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

698
	if (pActor->CheckFlag(AF_MOVING)) strcpy(szFlagMoving, "");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

698
	if (pActor->CheckFlag(AF_MOVING)) strcpy(szFlagMoving, "");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZShopEquipItem.cpp

343
			strcat(szBuf, sz);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

270
				sprintf( temp, "%d%s", dwRemaind, ZMsg( MSG_CHARINFO_MINUTE));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

84
				sprintf(temp,"%s -%d%%\n",  ZMsg( MSG_WORD_RUNSPEED), 100-pItemDesc->m_nLimitSpeed.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

266
				sprintf( temp, "%d%s ", dwRemaind / 60, ZMsg( MSG_CHARINFO_HOUR));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

450
		sprintf(szBuf, "%s%d", ZMsg(MSG_CHARINFO_LEVELMARKER), nResLevel);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZShopEquipItem.cpp

583
	strcpy(szBuf, m_pItemDesc->m_szQuestItemName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

132
				sprintf( temp, "%s x %d", temp, pItemDesc->m_nMaxBullet.Ref() / pItemDesc->m_nMagazine.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

348
		sprintf(sz, "\n(x%d)", m_pHandlerBringAccount->GetMyItemNode()->GetItemCount());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

63
			sprintf(DelayTemp,"%s : %.3f%s\n", ZMsg( MSG_WORD_RUNTIME), (float)pItemDesc->m_nDelay.Ref()/1000, ZMsg( MSG_CHARINFO_SECOND));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

261
					sprintf( temp, "%d%s ", dwRemaind / 1440, ZMsg( MSG_CHARINFO_DAY));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

342
			sprintf(sz, "\n(x%d)", pMyGambleItem->GetItemCount());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

28
			sprintf( temp,"%s : %d %s\n", ZMsg( MSG_WORD_LIMITEDLEVEL), nResLevel, ZMsg(MSG_CHARINFO_LEVELMARKER));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

59
			sprintf(DelayTemp,"%s : %.1f%s\n", ZMsg( MSG_WORD_RUNTIME), (float)pItemDesc->m_nDelay.Ref()/1000, ZMsg( MSG_CHARINFO_SECOND));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

144
			sprintf(temp,"%s : %d\n", ZMsg( MSG_WORD_DELAY), pItemDesc->m_nDelay.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

105
			sprintf( temp, "<%s>\n", ZMsg( MSG_WORD_ATTRIBUTE_POISON));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZShopEquipListbox.cpp

84
	strcpy(szDragString, m_szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZShopEquipListbox.cpp

85
	strcpy(szDragItemString, m_szName);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MDatabase/Include/
ODBCRecordset.h

43
		memcpy( pOutBuf, m_Data, m_UsedSize );
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MUpdate/
MFTCmd.h

68
		strcpy(m_szLocalFileName, pszLocalFileName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MUpdate/
MFTCmd.h

49
		strcpy(m_szDir, pszDir);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MUpdate/
MFTCmd.h

49
		strcpy(m_szDir, pszDir);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/RealSpace2/Source/
RBaseTexture.cpp

598
	strcpy(pnew->m_szTextureName,texturefilename);
CRITICAL
Security

Input Validation


The input buffer is the number of bytes in the string, but the size of the output buffer is the number of characters.

Stable/RealSpace2/Source/
RFont.cpp

239
	MultiByteToWideChar(CP_ACP, 0, szText, -1, wstrText, (int)nTextLen-1);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RFont.cpp

296
	ExtTextOut(m_hDC, 0, 0, ETO_OPAQUE, NULL, szText, _tcslen(szText), NULL);
CRITICAL
Security

Input Validation


The `LoadLibrary` function is used to load DLLs dynamically.

Stable/RealSpace2/Source/
RealSpace2.cpp

115
		HMODULE hD3D9 = LoadLibrary("DXVK\\d3d9.dll");
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/DownLoader/gzip/
trees.c

332
    FILE *header = fopen("trees.h", "w");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/MEncrypt/
FFileList.h

18
		strcpy(m_name,str);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/MEncrypt/
FFileList.h

18
		strcpy(m_name,str);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/MEncrypt/
FFileList.h

17
		if(strlen(str) > 255) return;
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
readppm.c

114
    sscanf(ppmline, "%d", &maxval);
MEDIUM
Error prone


Avoid 'sscanf()' for number conversions.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
readppm.c

114
    sscanf(ppmline, "%d", &maxval);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
readppm.c

109
    sscanf(ppmline, "%lu %lu", &width, &height);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/gregbook/
rpng2-win.c

727
    memset(&wndclass, 0, sizeof(wndclass));
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/pngminus/
pnm2png.c

82
          if ((fp_al = fopen (argv[argi], "rb")) == NULL)
MEDIUM
Error prone


Avoid 'sscanf()' for number conversions.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/pngminus/
pnm2png.c

521
  sscanf ((const char *) token, "%lu", &ret_value);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/pngminus/
pnm2png.c

105
      if ((fp_rd = fopen (argv[argi], "rb")) == NULL)
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
PngFile.c

117
    if (!(pfFile = fopen(pstrFileName, "rb")))
MEDIUM
Security

Visibility


The detected function is not sufficient at generating security-related random numbers, such as those used in key and nonce creation.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
crypt.h

113
        srand((unsigned)(time(NULL) ^ ZCR_SEED2));
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

152
   FILE * fin = fopen(filenameinzip,"rb");
MEDIUM
Security


Avoid using 'scanf()'. This function, when used improperly, does not consider buffer boundaries and can lead to buffer overflows.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

283
                    ret = scanf("%1s",answer);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

75
    int len = strlen(f);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

265
            strcat(filename_try,".zip");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
minizip.c

259
        len=(int)strlen(filename_try);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/minizip/
zip.c

1158
        size_global_comment = (uInt)strlen(global_comment);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

175
        BlockSizeCompress=atol(argv[2]);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

178
        BlockSizeUncompress=atol(argv[3]);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

175
        BlockSizeCompress=atol(argv[2]);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

181
        cprLevel=(int)atol(argv[4]);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/testzlib/
testzlib.c

197
        memset(&zcpr,0,sizeof(z_stream));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

138
  origlen = strlen(buffer);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

332
  int  len = strlen(buffer);
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

440
              strncpy(fname,buffer.header.name,SHORTNAMESIZE);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

142
       strcpy(buffer+origlen,TGZsuffix[i]);
MEDIUM
Security

Insecure Storage


Usage of the `access` function call hints at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/untgz/
untgz.c

143
       if (access(buffer,F_OK) == 0)
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
crc32.c

161
        out = fopen("crc32.h", "w");
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchObject.cpp

542
	memset(m_szName, 0, MATCHOBJECT_NAME_LENGTH);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchObject.cpp

543
	memset(m_nEquipedItemCIID, 0, sizeof(m_nEquipedItemCIID));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MMatchServer.cpp

2684
	sprintf( szStageDumpFileName, "Log/EquipDump_%d-%d-%d_%d-%d-%d.dmp"
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MMatchServer.cpp

2309
				sprintf( szLog, "[%s] '%s' , '(%d)%s'",
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

485
				strcat(szText, ", ");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

103
		strcat(szBuf, "\n");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MMatchServer.cpp

484
				strcat(szText, MGetMapDescMgr()->GetMapName(i)); 
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MMatchServer.cpp

4140
	strcpy(mail.sender, "Jetman82");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MMatchServer.cpp

103
		strcat(szBuf, "\n");
MEDIUM
Security

Visibility


The detected function is not sufficient at generating security-related random numbers, such as those used in key and nonce creation.

Stable/CSCommon/Source/
MMatchServer.cpp

851
	srand(timeGetTime());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MMatchServer.cpp

2319
		sprintf(szLog, "%s , Unknown Channel", pTargetObj->GetName());
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

4150
	strcpy(mail.message, "This is to test if read");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

4140
	strcpy(mail.sender, "Jetman82");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

103
		strcat(szBuf, "\n");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MMatchServer.cpp

4150
	strcpy(mail.message, "This is to test if read");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

2580
	int nNameLen = (int)strlen( szCharName);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

484
				strcat(szText, MGetMapDescMgr()->GetMapName(i)); 
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MMatchServer.cpp

2299
			sprintf( szLog, "[%s] '%s'",
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

53
	sprintf(szDesc, "CPU ID = %s ( family = %d , model = %d , stepping = %d )\n",
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

144
		else if (os.dwMinorVersion == 2) sprintf(szDesc, " Windows 8..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

143
		else if (os.dwMinorVersion == 1) sprintf(szDesc, " Windows 7..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

155
		if(os.dwMinorVersion==0)		sprintf(szDesc," Windows 95..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

145
		else if (os.dwMinorVersion == 3) sprintf(szDesc, " Windows 8.1..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

156
		else if(os.dwMinorVersion==10)	sprintf(szDesc," Windows 98..\n");
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Gunz/
ZActorWithFSM.cpp

1125
	memset(&pickinfo,0,sizeof(ZPICKINFO));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZBandiCapturer.cpp

200
		strcat(foldername, "");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

137
	sprintf(szTemp, "Video REC %.3f(sec)", (float)m_bandiCaptureLibrary.GetCaptureTime() / 1000);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZBandiCapturer.cpp

202
	strcpy(pPath, foldername);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZBandiCapturer.cpp

200
		strcat(foldername, "");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZBandiCapturer.cpp

200
		strcat(foldername, "");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZBandiCapturer.cpp

244
		strcat(foldername, "\\Screenshots");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

272
	sprintf(fileName, "%s_%4d%02d%02d_%02d%02d%02d",
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZBandiCapturer.cpp

198
		strcat(foldername, "\\Video");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZBandiCapturer.cpp

194
		strcat(foldername, "\\Gunz");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZBandiCapturer.cpp

193
		strcpy(foldername, pPath);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Gunz/
ZCharacterSelectView.cpp

43
	FILE* fp = fopen( FNAME_LASTCHAR, "rt");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

697
		sprintf( szName, "CharSel_Level%d", i);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

838
			sprintf( szWidgetName, "CharSel_Level%d", nIndex);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

869
			sprintf( szWidgetName, "CharSel_Selectbar%d", nIndex);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

880
			sprintf( szWidgetName, "CharSel_SelectBtn%d", nIndex);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCharacterSelectView.cpp

371
		for ( int i = 0;  i < (int)strlen( szName);  i++)
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

707
		sprintf( szName, "CharSel_ClanName%d", i);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

843
				sprintf( szString, "%d %s", pAccountCharInfo->nLevel, ZMsg(MSG_CHARINFO_LEVELMARKER));
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Gunz/
ZCharacterSelectView.cpp

47
		fscanf(fp, "%s", szName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

760
		sprintf( szWidgetName, "CharSel_Level%d", i);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCharacterSelectView.cpp

673
	   (strlen(m_CharInfo[nSelIndex].m_AccountCharInfo.szName) <= 0)) return;
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Gunz/
ZCharacterSelectView.cpp

198
	memset( &light, 0, sizeof(D3DLIGHT9)	);
MEDIUM
Security

Visibility


The detected function is not sufficient at generating security-related random numbers, such as those used in key and nonce creation.

Stable/Gunz/
ZCharacterSelectView.cpp

247
		srand(timeGetTime());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

826
			sprintf( szWidgetName, "CharSel_Name%d", nIndex);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZCombatChat.cpp

85
				strcpy(szMsg, szCommand);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZCombatChat.cpp

86
				strcpy(szMsg, pWidget->GetText());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

80
		sprintf(szPick[CH_LEFT],	"%s%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_LEFT,	FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

60
		sprintf(szBar[CH_LEFT],		"%s%02d%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_LEFT,		FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

71
		sprintf(szBar[CH_CENTER],	"%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

61
		sprintf(szBar[CH_RIGHT],	"%s%02d%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_RIGHT,	FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

59
		sprintf(szBar[CH_BOTTOM],	"%s%02d%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_BOTTOM,	FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

75
		sprintf(szBar[CH_RIGHT],	"%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_RIGHT, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

81
		sprintf(szPick[CH_RIGHT],	"%s%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_RIGHT,	FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

64
		sprintf(szPick[CH_TOP],		"%s%02d%s%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_TOP,		FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

79
		sprintf(szPick[CH_BOTTOM],	"%s%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_BOTTOM,	FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

74
		sprintf(szBar[CH_LEFT],		"%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_LEFT,	FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

66
		sprintf(szPick[CH_LEFT],	"%s%02d%s%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_LEFT,		FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZGameInterface_OnCommand.cpp

632
					sprintf(szNeedPointToNextRank, "%d", pCloseRankInfo->m_nTP - pMyRankInfo->m_nTP);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZGameInterface_OnCommand.cpp

596
				strcpy(tempItem.szCharName, pRankInfo->m_szCharName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZInterfaceBackground.cpp

349
				sprintf(szBuf, "%s/smoke.xml", DIR_LOGIN);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

699
	if (pActor->CheckFlag(AF_DEAD)) strcpy(szFlagDead, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

677
		strcpy(szTaskName, pCurrTask->GetTaskName());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZScreenDebugger.cpp

680
	sprintf(buf, "[%02d], %s, HP(%02d)AP(%2d) pos(%.2f %.2f %.2f), dir(%.2f %.2f %.2f), vel(%.2f %.2f %.2f), Task: %d, CurrTask: %s",
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

696
	if (pActor->CheckFlag(AF_BLAST)) strcpy(szFlagBlast, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

699
	if (pActor->CheckFlag(AF_DEAD)) strcpy(szFlagDead, "");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

700
	if (pActor->CheckFlag(AF_REQUESTED_DEAD)) strcpy(szFlagRequestedDead, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

701
	if (pActor->CheckFlag(AF_MY_CONTROL)) strcpy(szFlagMyControl, "");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

129
			sprintf( temp, "%s : %d", ZMsg( MSG_WORD_BULLET), pItemDesc->m_nMagazine.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

123
			sprintf(temp,"ItemID: %d",pItemDesc->m_nID);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

183
				sprintf(temp,"%s %d\n",  ZMsg( MSG_WORD_MAXWEIGHT), pItemDesc->m_nMaxWT.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

209
			sprintf(temp,"LR +%d\n",pItemDesc->m_nLR.Ref());
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZShopEquipItem.cpp

333
	strcpy(szBuf, m_pItemDesc->GetName().c_str());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

170
				sprintf(temp,"%s +%d\n", ZMsg(MSG_CHARINFO_AP), pItemDesc->m_nAP.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

199
			sprintf(temp,"CR +%d\n",pItemDesc->m_nCR.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

19
			sprintf( temp, "%s\n", ZMsg( MSG_WORD_FORWOMEN));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZShopEquipItem.cpp

343
			strcat(szBuf, sz);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

181
				sprintf(temp,"%s +%d\n", ZMsg( MSG_WORD_MAXWEIGHT), pItemDesc->m_nMaxWT.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

61
			sprintf(DelayTemp,"%s : %.2f%s\n", ZMsg( MSG_WORD_RUNTIME), (float)pItemDesc->m_nDelay.Ref()/1000, ZMsg( MSG_CHARINFO_SECOND));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

87
			sprintf(temp,"%s\n", ZMsg( MSG_WORD_DONOTDASH));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

26
			sprintf( temp,"%s : ^1%d ^0%s\n", ZMsg( MSG_WORD_LIMITEDLEVEL), nResLevel, ZMsg(MSG_CHARINFO_LEVELMARKER));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

89
			sprintf(temp,"%s\n", ZMsg( MSG_WORD_DONOTHANGWALL));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

172
				sprintf(temp,"%s %d\n",  ZMsg(MSG_CHARINFO_AP), pItemDesc->m_nAP.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

433
			sprintf(sz, "\n(x%d)", pMyItemNode->GetItemCount());
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZShopEquipItem.cpp

343
			strcat(szBuf, sz);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

204
			sprintf(temp,"PR +%d\n",pItemDesc->m_nPR.Ref());
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/RealSpace2/Source/
RBaseTexture.cpp

638
	strcpy(texturefilename,szName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RFont.cpp

238
	size_t nTextLen = strlen(szText)+1;
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RFont.cpp

313
	GetTextExtentPoint32(m_hDC, szChar, (int)_tcslen(szChar), &size);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/RealSpace2/Source/
RVisualMesh.cpp

2164
		memset(m_pAniNodeTable,0,sizeof(RAnimationNode*)*meshnode_cnt);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/RealSpace2/Source/
RVisualMesh.cpp

2167
		memset(m_pAniNodeTable,0,sizeof(RAnimationNode*)*m_nAniNodeTableCnt);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RealSpace2.cpp

864
			memcpy(dest,zero,4 - x*3 % 4);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/RealSpace2/Source/
RealSpace2.cpp

982
	sprintf(szFullFileName, "%s.bmp", szFilename);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/RealSpace2/Source/
RealSpace2.cpp

979
	sprintf(szFullFileName, "%s.jpg", szFilename);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/WorldEdit/
LightEditDlg.cpp

92
	sscanf(lightPosition.GetString(), "%s : %s : %s", tmp1, tmp2, tmp3);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/WorldEdit/
ObjectDialog.cpp

135
					sscanf(contents.c_str(), "%f,%f,%f", &worldObject.position.x, &worldObject.position.y, &worldObject.position.z);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

2025
	memcpy(szBuf, &a_PacketHeader, iHeaderSize);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MMatchServer.cpp

479
		sprintf(szText, "Enable Maps: ");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

4113
		strcat(szTemp, "\n");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

4113
		strcat(szTemp, "\n");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

4141
	strcpy(mail.receiver, "Jetman82");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer.cpp

2249
	if (strlen(pszTargetName) < 2) return;
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchServer.cpp

270
	memset(pDest, 0, sizeof(MTD_CharInfo_Detail));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MMatchServer.cpp

4112
		strcat(szTemp, szLog);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MMatchServer.cpp

4113
		strcat(szTemp, "\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MMatchServer.cpp

2241
	sprintf(szLog, "%s:\nReporter Name: %s\nReported Name: %s\nReason: %s\n", Time(), pObj->GetName(), pszTargetName, pszMessage);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MMatchServer.cpp

4141
	strcpy(mail.receiver, "Jetman82");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

152
		else							sprintf(szDesc," ..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

150
		else if(os.dwMinorVersion==1)	sprintf(szDesc," Windows xp..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

142
		if (os.dwMinorVersion == 0) sprintf(szDesc, " Windows Vista..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

161
		if(os.dwMinorVersion==51)		sprintf(szDesc," Windows NT 3.51..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

138
		if (os.dwMinorVersion == 0) sprintf(szDesc, " Windows 10..\n");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Gunz/
MSysInfo.cpp

46
			memcpy(CPUBrandString + 32, CPUInfo, sizeof(CPUInfo));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
MSysInfo.cpp

157
		else if(os.dwMinorVersion==90)	sprintf(szDesc," Windows Me..\n");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

142
	case BCAP_FILESIZE_100MB: {	if (m_lFileSize > 100000000)	Stop();	sprintf(szTemp, "[100MB]");	}break;
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZBandiCapturer.cpp

198
		strcat(foldername, "\\Video");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

143
	case BCAP_FILESIZE_300MB: {	if (m_lFileSize > 300000000)	Stop();	sprintf(szTemp, "[300MB]");	}break;
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

144
	case BCAP_FILESIZE_500MB: {	if (m_lFileSize > 500000000)	Stop();	sprintf(szTemp, "[500MB]");	}break;
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZBandiCapturer.cpp

198
		strcat(foldername, "\\Video");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

153
	sprintf(szTemp, "%s %.3fMB", szTemp, (float)m_lFileSize / 1000000);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBandiCapturer.cpp

145
	case BCAP_FILESIZE_UNLIMITED: {	sprintf(szTemp, "[Unlimited]");	}break;
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZBandiCapturer.cpp

193
		strcpy(foldername, pPath);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZBandiCapturer.cpp

194
		strcat(foldername, "\\Gunz");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZBandiCapturer.cpp

194
		strcat(foldername, "\\Gunz");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZBandiCapturer.cpp

244
		strcat(foldername, "\\Screenshots");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZCharacterSelectView.cpp

69
	strcpy(m_szLastChar, szName); 
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Gunz/
ZCharacterSelectView.cpp

555
	memset(nItemID, 0, sizeof(nItemID));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCharacterSelectView.cpp

453
		if (strlen(m_CharInfo[nSelectIndex].m_AccountCharInfo.szName) > 0)
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCharacterSelectView.cpp

425
	if (strlen(m_CharInfo[nSelectIndex].m_AccountCharInfo.szName) <= 0) return;
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

770
		sprintf( szWidgetName, "CharSel_SelectBtn%d", i);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

54
				sprintf( szWidget, "CharSel_Name%d", i);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

765
		sprintf( szWidgetName, "CharSel_ClanName%d", i);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Gunz/
ZCharacterSelectView.cpp

805
			memcpy(&ZCharacterSelectView::m_CharInfo[nIndex].m_AccountCharInfo, pAccountCharInfo, sizeof(MTD_AccountCharInfo));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZCharacterSelectView.cpp

367
		strcpy( szName, pLabel->GetText());
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Gunz/
ZCharacterSelectView.cpp

72
	FILE* fp = fopen(FNAME_LASTCHAR, "wt");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCharacterSelectView.cpp

850
			sprintf( szWidgetName, "CharSel_ClanName%d", nIndex);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZCombatChat.cpp

79
			if (strlen(pWidget->GetText()) >= 256) return false;
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

63
		sprintf(szPick[CH_CENTER],	"%s%02d%s%s",		FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

72
		sprintf(szBar[CH_TOP],		"%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_TOP,	FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

67
		sprintf(szPick[CH_RIGHT],	"%s%02d%s%s%s",	FN_CROSSHAIR_HEADER, (int)nPreset+1, FN_CROSSHAIR_RIGHT,	FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZCrossHair.cpp

78
		sprintf(szPick[CH_TOP],		"%s%s%s%s%s", PATH_CUSTOM_CROSSHAIR, FN_CROSSHAIR_HEADER, FN_CROSSHAIR_TOP,		FN_CROSSHAIR_PICK, FN_CROSSHAIR_TAILER);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZGameInterface_OnCommand.cpp

596
				strcpy(tempItem.szCharName, pRankInfo->m_szCharName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.h

24
	void SetDataCookie(const char* pszVal)	{ strcpy(m_DataCookie, pszVal);	}
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.h

26
	void SetSpareParam(const char* pszVal)	{ strcpy(m_SpareParam, pszVal);	}
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.h

26
	void SetSpareParam(const char* pszVal)	{ strcpy(m_SpareParam, pszVal);	}
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZRuleSpyMode.cpp

275
				sprintf(szText, "%02d,%02d,%02d", (((int)dwTime / 1000) / 60), (((int)dwTime / 1000) % 60), ((int)dwTime / 10) % 100);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

700
	if (pActor->CheckFlag(AF_REQUESTED_DEAD)) strcpy(szFlagRequestedDead, "");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

697
	if (pActor->CheckFlag(AF_BLAST_DAGGER)) strcpy(szFlagBlastDagger, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

695
	if (pActor->CheckFlag(AF_LAND)) strcpy(szFlagLand, "");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

695
	if (pActor->CheckFlag(AF_LAND)) strcpy(szFlagLand, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

697
	if (pActor->CheckFlag(AF_BLAST_DAGGER)) strcpy(szFlagBlastDagger, "");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZScreenDebugger.cpp

701
	if (pActor->CheckFlag(AF_MY_CONTROL)) strcpy(szFlagMyControl, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZScreenDebugger.cpp

696
	if (pActor->CheckFlag(AF_BLAST)) strcpy(szFlagBlast, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZShopEquipItem.cpp

583
	strcpy(szBuf, m_pItemDesc->m_szQuestItemName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

17
			sprintf( temp, "%s\n", ZMsg( MSG_WORD_FORMEN));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

68
			sprintf( temp, "<%s>\n", ZMsg( MSG_WORD_ATTRIBUTE_FIRE));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

414
	sprintf(szBuf, "%s", m_pItemDesc->m_pMItemName->Ref().m_szItemName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

99
				sprintf(temp,"%s : %d dmg.\n", ZMsg( MSG_WORD_ATTACK), pItemDesc->m_nDamage.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

357
	sprintf( szBuf, "%s-", ZMsg(MSG_CHARINFO_LEVELMARKER));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

73
				sprintf(temp,"%s : %d dmg/%s\n", ZMsg( MSG_WORD_DAMAGE), pItemDesc->m_nDamage.Ref(), ZMsg( MSG_CHARINFO_SECOND));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

189
			sprintf(temp,"SF +%d\n",pItemDesc->m_nSF.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

94
			sprintf( temp, "<%s>\n", ZMsg( MSG_WORD_ATTRIBUTE_LIGHTNING));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

221
			sprintf(temp,"%s\n", ZMsg( MSG_WORD_DONOTJUMP));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

79
			sprintf( temp, "<%s>\n", ZMsg( MSG_WORD_ATTRIBUTE_COLD));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

57
			sprintf(DelayTemp,"%s : %d%s\n", ZMsg( MSG_WORD_RUNTIME), pItemDesc->m_nDelay.Ref()/1000, ZMsg( MSG_CHARINFO_SECOND));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

194
			sprintf(temp,"FR +%d\n",pItemDesc->m_nFR.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

158
				sprintf(temp,"%s +%d\n", ZMsg(MSG_CHARINFO_HP), pItemDesc->m_nHP.Ref());
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZShopEquipItem.cpp

333
	strcpy(szBuf, m_pItemDesc->GetName().c_str());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

160
				sprintf(temp,"%s %d\n",  ZMsg(MSG_CHARINFO_HP), pItemDesc->m_nHP.Ref());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItem.cpp

34
		sprintf( temp,"%s : %d Wt.", ZMsg( MSG_WORD_WEIGHT), nWeight);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZShopEquipListbox.cpp

85
	strcpy(szDragItemString, m_szName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZShopEquipListbox.cpp

84
	strcpy(szDragString, m_szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/RealSpace2/Include/
RAniEventInfo.h

38
	void SetFileName(char * filename){ strcpy(m_cFileName, filename); }
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/RealSpace2/Include/
RAniEventInfo.h

38
	void SetFileName(char * filename){ strcpy(m_cFileName, filename); }
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/RealSpace2/Source/
RBaseTexture.cpp

579
	strcpy(texturefilename,filename);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RBaseTexture.cpp

575
	if(filename==NULL || strlen(filename)==0) return NULL;
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/RealSpace2/Source/
RBaseTexture.cpp

598
	strcpy(pnew->m_szTextureName,texturefilename);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/RealSpace2/Source/
RBaseTexture.cpp

579
	strcpy(texturefilename,filename);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/RealSpace2/Source/
RBaseTexture.cpp

638
	strcpy(texturefilename,szName);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RFont.cpp

624
				memcpy(g_FontIndexBuffer+g_nFontCount*6,indices,sizeof(indices));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RFont.cpp

623
				memcpy(g_FontVertexBuffer+g_nFontCount*4,vertices,sizeof(vertices));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RFont.cpp

231
	GetTextExtentPoint32(m_hDC, szText, (int)_tcslen(szText), &size);
CRITICAL
Security

Input Validation


The input buffer is the number of bytes in the string, but the size of the output buffer is the number of characters.

Stable/RealSpace2/Source/
RealSpace2.cpp

931
		MultiByteToWideChar(CP_ACP, 0, szFilename, -1, wstrName, (int)nNameLen - 1);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RealSpace2.cpp

930
		size_t nNameLen = strlen(szFilename) + 1;
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/RealSpace2/Source/
RealSpace2.cpp

962
	file=fopen(szFilename,"wb+");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/DownLoader/src/
memory.h

38
	strcpy(m->TypeName, TypeName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

534
    strcpy (szImgFileName, strrchr (pstrPathName, '\\') + 1);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

590
                strcpy (szTmp, *ppFileList + jj);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1010
    strcat(s->msg, m);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1010
    strcat(s->msg, m);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1010
    strcat(s->msg, m);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/WorldEdit/
LightEditDlg.cpp

102
	sscanf(lightColor.GetString(), "%s : %s : %s", tmp1, tmp2, tmp3);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/WorldEdit/
ObjectDialog.cpp

173
					sscanf(contents.c_str(), "%f,%f,%f", &worldObject.endposition.x, &worldObject.endposition.y, &worldObject.endposition.z);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/WorldEdit/
ObjectDialog.cpp

160
					sscanf(contents.c_str(), "%f,%f,%f", &worldObject.scale.x, &worldObject.scale.y, &worldObject.scale.z);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/WorldEdit/
ObjectDialog.cpp

142
					sscanf(contents.c_str(), "%f,%f,%f", &worldObject.direction.x, &worldObject.direction.y, &worldObject.direction.z);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/sdk/maxsdk/include/Graphics/
Matrix44.h

117
	memcpy(m, from.m, sizeof(m));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/
Blitz.h

296
		memset(&list, 0, sizeof(RouteList));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Include/
MCommandBuilder.h

78
		CopyMemory(pMsg->Buffer, SendBuf, nSize);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Include/
MMatchHShield.h

19
									memset(m_pbyReqMsg, 0, sizeof(m_pbyReqMsg));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Include/
MMatchHShield.h

20
									memset(m_pbyReqInfo, 0, sizeof(m_pbyReqInfo));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Include/
MMatchHShield.h

17
	void Clear()				{	memset(m_pbyGuidReqMsg, 0, sizeof(m_pbyGuidReqMsg));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Include/
MMatchHShield.h

18
									memset(m_pbyGuidReqInfo, 0, sizeof(m_pbyGuidReqInfo));	
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.h

24
	void SetDataCookie(const char* pszVal)	{ strcpy(m_DataCookie, pszVal);	}
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.h

22
	void SetAuthCookie(const char* pszVal)	{ strcpy(m_AuthCookie, pszVal);	}
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.h

22
	void SetAuthCookie(const char* pszVal)	{ strcpy(m_AuthCookie, pszVal);	}
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerListBox.h

83
		if (szLevel) strcpy(m_szLevel, szLevel);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerListBox.h

87
		if(szClanName) strcpy(m_szClanName, szClanName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerListBox.h

85
		if (szName) strcpy(m_szName, szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerListBox.h

223
			strcpy(m_szName, szName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerListBox.h

87
		if(szClanName) strcpy(m_szClanName, szClanName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerListBox.h

166
			strcpy(m_szLocation, szLocation);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerListBox.h

223
			strcpy(m_szName, szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerListBox.h

83
		if (szLevel) strcpy(m_szLevel, szLevel);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerListBox.h

313
		strcpy(m_szLevel, szLevel);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerListBox.h

313
		strcpy(m_szLevel, szLevel);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerListBox.h

85
		if (szName) strcpy(m_szName, szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerListBox.h

166
			strcpy(m_szLocation, szLocation);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZPlayerMenu.h

59
	void SetTargetName(const char* pszPlayerName) { strcpy(m_szPlayerName, pszPlayerName); }
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZPlayerMenu.h

59
	void SetTargetName(const char* pszPlayerName) { strcpy(m_szPlayerName, pszPlayerName); }
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/ItemThumbnailGenerator/tinyxml/
tinystr.h

125
		return append(suffix, static_cast<size_type>( strlen(suffix) ));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/ItemThumbnailGenerator/tinyxml/
tinystr.h

92
		init( static_cast<size_type>( strlen(copy) ));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/ItemThumbnailGenerator/tinyxml/
tinystr.h

93
		memcpy(start(), copy, length());
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/ItemThumbnailGenerator/tinyxml/
tinystr.h

86
		memcpy(start(), copy.data(), length());
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/ItemThumbnailGenerator/tinyxml/
tinystr.h

112
		return assign( copy, (size_type)strlen(copy));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/ItemThumbnailGenerator/tinyxml/
tinystr.h

100
		memcpy(start(), str, len);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/RealSpace2/Include/
RAniEventInfo.h

40
	void SetEventType(char* EventType){strcpy(m_cEventType, EventType);}
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/DownLoader/sha1/
sha1.c

155
	memset(&finalcount, 0, 8);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/DownLoader/sha1/
sha1.c

154
	memset(context->count, 0, 8);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/DownLoader/sha1/
sha1.c

119
	    memcpy(&context->buffer[j], data, (i = 64-j));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/DownLoader/sha1/
sha1.c

152
	memset(context->buffer, 0, SHA1_BLOCK_LENGTH);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/DownLoader/sha1/
sha1.c

127
	memcpy(&context->buffer[j], &data[i], len - i);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/DownLoader/sha1/
sha1.c

153
	memset(context->state, 0, SHA1_DIGEST_LENGTH);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/DownLoader/src/
memory.h

38
	strcpy(m->TypeName, TypeName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/DownLoader/src/
memory.h

39
	sprintf(m->FileName, "%s: Line %d", File, Line);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

104
            strncpy (szCmdFileName, szCmdLine + 1, strlen(szCmdLine) - 2);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

731
    memset (pDib, 0, sizeof(BITMAPINFOHEADER));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

592
                strcpy (*ppFileList + ii, szTmp);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

108
        strcpy (szCmdFileName, "");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

567
        strcpy (*ppFileList + ii, szImgPathName);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

538
    strcat (szImgFindName, "*.png");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

568
        strcpy (strrchr(*ppFileList + ii, '\\') + 1, finddata.cFileName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

639
            strcpy (pstrNextName, pFileList + (*pFileIndex * MAX_PATH));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

592
                strcpy (*ppFileList + ii, szTmp);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

681
        sprintf (szTmp, "VisualPng - %s", strrchr(pstrPathName, '\\') + 1);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

108
        strcpy (szCmdFileName, "");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

538
    strcat (szImgFindName, "*.png");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

536
    strcpy (szImgFindName, szImgPathName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

591
                strcpy (*ppFileList + jj, *ppFileList + ii);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

534
    strcpy (szImgFileName, strrchr (pstrPathName, '\\') + 1);
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

104
            strncpy (szCmdFileName, szCmdLine + 1, strlen(szCmdLine) - 2);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

627
            strcpy (pstrPrevName, pFileList + (*pFileIndex * MAX_PATH));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

538
    strcat (szImgFindName, "*.png");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

639
            strcpy (pstrNextName, pFileList + (*pFileIndex * MAX_PATH));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

568
        strcpy (strrchr(*ppFileList + ii, '\\') + 1, finddata.cFileName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

591
                strcpy (*ppFileList + jj, *ppFileList + ii);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

627
            strcpy (pstrPrevName, pFileList + (*pFileIndex * MAX_PATH));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

533
    strcpy (szImgPathName, pstrPathName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

590
                strcpy (szTmp, *ppFileList + jj);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

106
            strcpy (szCmdFileName, szCmdLine);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

536
    strcpy (szImgFindName, szImgPathName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

106
            strcpy (szCmdFileName, szCmdLine);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream2/
zstream.h

56
        izstream(const char* name) : m_fp(0) { open(name); }
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream2/
zstream.h

55
        izstream(FILE* fp) : m_fp(0) { open(fp); }
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream2/
zstream.h

278
    val.byte = 255;  val.word = ::strlen(x);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream2/
zstream.h

166
            open(name, level);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream2/
zstream.h

162
            open(fp, level);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/examples/
gzlog.c

147
    log->fd = open(path, O_RDWR | O_CREAT, 0600);
CRITICAL
Security

Input Validation


Format string vulnerabilities allow an attacker to read or in some cases, potentially write data to and from locations in the processes' memory.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

660
    snprintf(buf, sizeof(buf), format, a1, a2, a3, a4, a5, a6, a7, a8,
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

618
    len = vsprintf(buf, format, va);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

226
    sprintf(name, "<fd:%d>", fd); /* for debugging */
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

613
    (void)vsprintf(buf, format, va);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

625
    len = strlen(buf);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1009
    strcat(s->msg, ": ");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1009
    strcat(s->msg, ": ");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1008
    strcpy(s->msg, s->path);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

127
    s->path = (char*)ALLOC(strlen(path)+1);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

655
    len = sprintf(buf, format, a1, a2, a3, a4, a5, a6, a7, a8,
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1008
    strcpy(s->msg, s->path);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

131
    strcpy(s->path, path); /* do this early for debugging */
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

131
    strcpy(s->path, path); /* do this early for debugging */
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1009
    strcat(s->msg, ": ");
CRITICAL
Security

Input Validation


Format string vulnerabilities allow an attacker to read or in some cases, potentially write data to and from locations in the processes' memory.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

664
    len = snprintf(buf, sizeof(buf), format, a1, a2, a3, a4, a5, a6, a7, a8,
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

650
    sprintf(buf, format, a1, a2, a3, a4, a5, a6, a7, a8,
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

697
    return gzwrite(file, (char*)s, (unsigned)strlen(s));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/
gzio.c

1006
    s->msg = (char*)ALLOC(strlen(s->path) + strlen(m) + 3);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/SVNRevisionTracker/TinyXML/
tinystr.h

86
		memcpy(start(), copy.data(), length());
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/SVNRevisionTracker/TinyXML/
tinystr.h

92
		init( static_cast<size_type>( strlen(copy) ));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/SVNRevisionTracker/TinyXML/
tinystr.h

93
		memcpy(start(), copy, length());
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/SVNRevisionTracker/TinyXML/
tinystr.h

112
		return assign( copy, (size_type)strlen(copy));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/SVNRevisionTracker/TinyXML/
tinystr.h

100
		memcpy(start(), str, len);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/SVNRevisionTracker/TinyXML/
tinystr.h

125
		return append(suffix, static_cast<size_type>( strlen(suffix) ));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/cml/Include/
MWindowFinder.h

22
		if (strlen(szWinText) <= 0)
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/cml/Include/
MWindowFinder.h

54
		strcpy(m_szSearchText, pszName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/cml/Include/
MWindowFinder.h

54
		strcpy(m_szSearchText, pszName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/cml/Include/
MWindowFinder.h

38
		if (strlen(szClassName) <= 0)
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/sdk/maxsdk/include/containers/
Array.inline.h

81
			memcpy(pCopy, pSource, nCount * sizeof(T));
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MActorDef.cpp

66
			pActorDef->SetMaxAp(atoi(itor->first_attribute("max_ap")->value()));
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MActorDef.cpp

65
			pActorDef->SetMaxHp(atoi(itor->first_attribute("max_hp")->value()));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchRuleDuelTournament.cpp

58
				memset(pInfo, 0, sizeof(MDuelTournamentPlayerInfo));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer_Char.cpp

131
	for ( int i = 0;  i < (int)strlen( szCharName);  i++)
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MMatchServer_Quest.cpp

630
	memcpy( pMonBible, &(pCharInfo->m_QMonsterBible), MONSTER_BIBLE_SIZE );
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/CSCommon/Source/
MMatchWorldItemDesc.cpp

293
			int nCount = sscanf(szDirection, "%f %f %f", &dir.x,&dir.y,&dir.z);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestDropTable.cpp

137
	pDropSet->SetID(atoi(element->first_attribute(MTOK_DROPSET_ATTR_ID)->value()));
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestMap.cpp

281
					pSectorInfo->nSpawnPointCount[MNST_RANGE] = atoi(szAttrValue);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MQuestMap.cpp

285
					pSectorInfo->nSpawnPointCount[MNST_BOSS] = atoi(szAttrValue);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MQuestMap.cpp

166
					nSectorID = atoi(szAttrValue);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MQuestMap.cpp

209
					strcpy(pSector->Links[nLinkIndex].szName, szAttrValue);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MSacrificeQItemTable.cpp

68
	SacriQItemInfo.m_nDefaultQItemID = atoi(element->first_attribute(MSQITC_DIID)->value());
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MSacrificeQItemTable.cpp

67
	SacriQItemInfo.m_nQL = atoi(element->first_attribute(MSQITC_QL)->value());
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

84
				strcat(szAnnounce, "Դϴ.");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

428
				strcat(szWinnerMembers, pObj->GetCharInfo()->m_szName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
TestCRC32XORCache.cpp

55
		sprintf( pItemDesc->m_szDesc, "ItemDesc.nItemID = %d", i );
CRITICAL
Security

Input Validation


`Echo`ing user input risks cross-site scripting vulnerability.

Stable/GunZ Web Components/GunzAdmin/
ChangeCharName.php

19
	echo ("<CENTER><TABLE border=0>
CRITICAL
Security

Input Validation


`Echo`ing user input risks cross-site scripting vulnerability.

Stable/GunZ Web Components/GunzAdmin/
account_update_ugrade.php

87
	echo ("<meta http-equiv='Refresh' content='1; URL=./AccountInfo.html?mode=process&aid=" . $aid . "'>");
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
account_update_ugrade.php

23
	$query = "SELECT aid, userid, UGradeID FROM Account(nolock) where aid=" . $aid;
CRITICAL
Security

Input Validation


`Echo`ing user input risks cross-site scripting vulnerability.

Stable/GunZ Web Components/GunzAdmin/
account_update_ugrade.php

30
	echo("<FORM action='./account_update_ugrade.php' method=post>
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
login_action.php

20
	$query = "select * from user where userid='".$username."' AND passwd=PASSWORD('$password')";
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_create.php

74
	$query = "SELECT * FROM user WHERE userid='$r_userid'";
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_create.php

83
	$query = "INSERT INTO user (userid, passwd, name, level, regdate) " .
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_delete.php

36
	$query = "DELETE FROM user WHERE uid=$r_uid";
CRITICAL
Security

Input Validation


`Echo`ing user input risks cross-site scripting vulnerability.

Stable/GunZ Web Components/GunzAdmin/
user_delete.php

22
	echo ("<CENTER>
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

126
	$query = "SELECT * FROM user WHERE userid='$r_userid' AND uid != $r_uid";
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

34
	$query = "SELECT uid, userid, name, level FROM user WHERE uid=$r_uid";
CRITICAL
Security

Input Validation


`Echo`ing user input risks cross-site scripting vulnerability.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

85
	echo("
CRITICAL
Security

Input Validation


`Echo`ing user input risks cross-site scripting vulnerability.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

97
		echo ("<TABLE><TR><TD>
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

23
	$query = "SELECT uid FROM user WHERE userid='$r_userid'";
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

150
		$query = "UPDATE user SET userid='$r_userid', name='$r_name' " . $level_query .
CRITICAL
Security

Input Validation


User data flows into this manually-constructed SQL string.

Stable/GunZ Web Components/GunzAdmin/
user_edit.php

144
		$query = "UPDATE user SET userid='$r_userid', passwd=PASSWORD('$r_password'), name='$r_name' " . $level_query .
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZGameGuard.cpp

235
	if( (0 == szUserID) || (1 > strlen(szUserID)) ) 
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

339
				strcat( szHP, ZMsg(MSG_WORD_VERYWEAK));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZMonsterBookInterface.cpp

328
			strcpy( szHP, "HP : ");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNHN_USA.cpp

58
	strcpy( m_szGameStr, szGameStringNew);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNHN_USA.cpp

25
	strcpy( m_szAuthStr, "init" );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNHN_USA.cpp

58
	strcpy( m_szGameStr, szGameStringNew);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.cpp

91
		strncpy(token, porg, tlen);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.cpp

17
	strcpy( m_SpareParam, "12" );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.cpp

70
		strcpy(buf, str);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZShopEquipItemConfirm.cpp

220
	sprintf(szPrice, "%d %s", price, ZMsg(MSG_CHARINFO_BOUNTY));
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Locator/
MCountryCodeFilter.cpp

164
	strncpy( szPos2, &strIP[a + 1], b - a - 1 );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MUpdate/
MPatchBuilder.cpp

116
				sprintf(szFilePath, "%s/%s", szDir, FindData.cFileName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

103
		sprintf( szErrCode, "this ip address is invalid." );
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/MatchServer/
MBMatchServer.cpp

110
		fscanf(ReadFp, "%x", &readNum);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/MatchServer/
MBMatchServer.cpp

371
	strcat(log_buffer, temp);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/MatchServer/
MBMatchServer_Item.cpp

962
		memset( pSendGItem->szName, 0, MAX_GAMBLEITEMNAME_LEN );
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MatchServer/
MBMatchServer_Item.cpp

988
		memcpy( pSendGItem->szDesc
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

854
		sprintf(szTemp, "%s = %s\n", szBuffer, szValue);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

942
	memcpy(&node->bbTree, bb, sizeof(dboundingbox));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

337
		if (i == 0) strcpy(szTok, "solo");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Ani.cpp

217
		memcpy(&mesh_node->m_tm_key[i],&dm,sizeof(D3DXMATRIX));
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

189
			case ID_SS: wcscpy(buf, ID_MAP_SHINESTRENGTH);	break;
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

186
			case ID_DI: wcscpy(buf, ID_MAP_DIFFUSE);		break;
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/MaxPlugIns/MCPlug/
ani.cpp

161
	memset(mesh_node->m_tm_key,0,sizeof(t_tm_key_s) * mat_key_cnt);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

51
				strcat(pCommand->szBuffer2,".rsm");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

51
				strcat(pCommand->szBuffer2,".rsm");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

214
	strcpy(g_FileName,filename);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

269
				case CDESTINATION	:	strcpy(g_Destination,pCommand->szBuffer);break;
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

376
		strcpy(pCommand->szBuffer,g_Destination);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/RSBatchExporter/
OpenDlg.cpp

71
	int nLen = strlen(pNextNames);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/RSBatchExporter/
OpenDlg.cpp

92
	strcpy(szDir, pFileNames);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

78
	int nDirLen = strlen(pDir);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

180
	memcpy(szTemp+nNextPos, szDir+nEqualLen, strlen(szDir)-nEqualLen);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

219
	if(pBasePath[strlen(pBasePath)]!='\\') strcat(pBasePath,"\\");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

110
	memcpy(pDepthDir, pDir+nStartDir, nEndDir-nStartDir+1);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

191
		strcpy(pFullPath, pRelativePath);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Mcv/
McvView.cpp

2129
		strcpy( g_last_open_elu_file , filename );
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Mcv/
McvView.cpp

345
	memset(&dataRect, 0, sizeof(D3DLOCKED_RECT));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Mint2/Source/
MCursor.cpp

9
	_ASSERT(strlen(szName)<MCURSOR_NAME_LENGTH);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Mint2/Source/
MDrawContext.cpp

466
				strcat(pText, "^");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Mint2/Source/
MDrawContext.cpp

466
				strcat(pText, "^");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Mint2/Source/
MDrawContext.cpp

420
		if(nPos + 1 < strlen(pSrc)){
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Mint2/Source/
MDrawContext.cpp

453
	memset(pText, 0, nLen+1);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Mint2/Source/
MDrawContext.cpp

496
	int nLength = strlen(szText);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Mint2/Source/
MDrawContext.cpp

557
				strncpy(buffer,szCurrent,nCharCount);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/PatchInterface/PatchInterface/
Keeper.cpp

482
	if( (0 == pszAnnounce) || (strlen(pszAnnounce) != nLen) || (255 < strlen(pszAnnounce)) )
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/RealSpace2/Include/
RAniEventInfo.h

40
	void SetEventType(char* EventType){strcpy(m_cEventType, EventType);}
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject.cpp

1298
			memcpy(&pNode->bbTree,&pNode->m_pNegative->bbTree,sizeof(rboundingbox));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/RealSpace2/Source/
RBspObject.cpp

1342
	sprintf(bspname,"%s.bsp",filename);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject.cpp

1447
	memcpy(pIndices,m_pOcIndices,sizeof(WORD)*m_nIndices);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3352
					memcpy(pNode->pInfo+j,pNode->pInfo+k,sizeof(ttemp));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3452
		memcpy(g_pLPVertices+g_nCreatingPosition,pNode->pVertices,sizeof(BSPVERTEX)*pNode->nPolygon*3);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/MEncrypt/
FFileList.cpp

27
				strcat(_path,"/*");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/MEncrypt/
FFileList.cpp

51
					strcpy(temp_name,file_t.cFileName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/MEncrypt/
FFileList.cpp

34
			int filelen = (int)strlen(file_t.cFileName);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Utils/ReplayAnalysis/GunzReplayConverter/
ReplayConverter.cpp

40
	memset( &m_StageSetting, 0, sizeof(REPLAY_STAGE_SETTING_NODE) );
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/ReplayAnalysis/GunzReplayConverter/
ReplayConverter.cpp

394
			fp = fopen( fileName.c_str(), "w" );
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

533
    strcpy (szImgPathName, pstrPathName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

567
        strcpy (*ppFileList + ii, szImgPathName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/libPNG/contrib/visupng/
VisualPng.c

104
            strncpy (szCmdFileName, szCmdLine + 1, strlen(szCmdLine) - 2);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/cml/source/
MArchive.cpp

50
	pItem->szName[__min(strlen(szName), MAITEM_NAME_LENGTH-1)] = 0;
MEDIUM
Error prone


Detected use of `exit`. Use `sys.exit` over the python shell `exit` built-in. `exit` is a helper for the interactive shell and may not be available on all Python implementations.

Stable/sdk/maxsdk/tools/
RunMUIrct.py

204
    exit(main())
CRITICAL
Security

Input Validation


Detected subprocess function 'Popen' with user controlled data.

Stable/sdk/maxsdk/tools/
RunMUIrct.py

39
        return [1, subprocess.Popen(params), tmp, path]
CRITICAL
Security

Input Validation


Detected subprocess function 'Popen' without a static string.

Stable/sdk/maxsdk/tools/
RunMUIrct.py

39
        return [1, subprocess.Popen(params), tmp, path]
CRITICAL
Best practice


time.sleep() call; did you mean to leave this in?

Stable/sdk/maxsdk/tools/
RunMUIrct.py

162
                    time.sleep(0.1)
MEDIUM
Best practice


Missing 'encoding' parameter. 'open()' uses device locale encodings by default, corrupting files with special characters.

Stable/sdk/maxsdk/tools/
RunMUIrct.py

147
            with open(file_name, 'r') as f:
CRITICAL
Security

Input Validation


Python possesses many mechanisms to invoke an external executable.

Stable/sdk/maxsdk/tools/
RunMUIrct.py

39
        return [1, subprocess.Popen(params), tmp, path]
MEDIUM
Best practice


Missing 'encoding' parameter. 'open()' uses device locale encodings by default, corrupting files with special characters.

Stable/sdk/maxsdk/tools/
RunMUIrct.py

68
    fo = open(fullname, 'w+')
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/CSCommon/Source/
MMatchWorldItemDesc.cpp

283
		int nCnt = sscanf(szPosition, "%f %f %f", &x, &y, &z);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MQuestDropTable.cpp

148
				nQL = atoi(itor->first_attribute(MTOK_DROPSET_ATTR_QL)->value());
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestMap.cpp

285
					pSectorInfo->nSpawnPointCount[MNST_BOSS] = atoi(szAttrValue);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestMap.cpp

166
					nSectorID = atoi(szAttrValue);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MSacrificeQItemTable.cpp

67
	SacriQItemInfo.m_nQL = atoi(element->first_attribute(MSQITC_QL)->value());
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MSacrificeQItemTable.cpp

70
	SacriQItemInfo.m_nSpecialQItemID2 = atoi(element->first_attribute(MSQITC_SIID2)->value());
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MSurvivalMap.cpp

39
	strncpy( m_MapInfo[nMap].szName, szMapName, nMapNameLen );
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

433
				strcat(szLoserMembers, pObj->GetCharInfo()->m_szName);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

434
				strcat(szLoserMembers, " ");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBirdDummyAI.cpp

120
				sprintf(szStageName, "%s_stage%d", "", nRandNum);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZEffectStaticMesh.cpp

117
				strcpy( buffer, base_snd_name );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZEffectStaticMesh.cpp

117
				strcpy( buffer, base_snd_name );
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZGameClient_Ladder.cpp

170
		strcat(szMembers, ")");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZGameClient_Ladder.cpp

170
		strcat(szMembers, ")");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

286
		if (!m_AgreementBuilder.GetRejecter(szRejecter)) strcpy(szRejecter, szReplierName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

348
	strcpy(m_szStageName, "UnNamedStage");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

178
				strcat(szTemp, szMembers);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZGameGuard.cpp

262
	strncpy( m_szCallbackMsg, szCallbackMsg, strlen(szCallbackMsg) );
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZMonsterBookInterface.cpp

339
				strcat( szHP, ZMsg(MSG_WORD_VERYWEAK));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

284
					strcat( szGrade, ZMsg(MSG_WORD_REGULAR));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

331
				strcat( szHP, ZMsg(MSG_WORD_VERYHARD));
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZMonsterBookInterface.cpp

296
					strcat( szGrade, ZMsg(MSG_WORD_ELITE));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZMonsterBookInterface.cpp

288
					strcat( szGrade, ZMsg(MSG_WORD_LEGENDARY));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZMonsterBookInterface.cpp

337
				strcat( szHP, ZMsg(MSG_WORD_WEAK));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZMonsterBookInterface.cpp

333
				strcat( szHP, ZMsg(MSG_WORD_HARD));
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZMonsterBookInterface.cpp

292
					strcat( szGrade, ZMsg(MSG_WORD_BOSS));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

194
		sprintf( szErrCode, "memberID is invalid." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

186
		sprintf( szErrCode, "parameter of auth is invalid." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

202
		sprintf( szErrCode, "password mismatch( over 3 times )." );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetAgreementBuilder.cpp

112
		strcpy(ppReplierNames[nCount], pReplier->szCharName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.cpp

129
	strcpy(outStr, szTemp);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.cpp

17
	strcpy( m_SpareParam, "12" );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZNetmarble.cpp

144
	if(strlen(buf)==0)
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Gunz/
ZNetmarble.cpp

91
		strncpy(token, porg, tlen);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZNetmarble.cpp

163
	if(strlen(arg[0]) > 16)
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Gunz/
ZSkill.cpp

339
								sscanf(szAttrValue,"%f %f %f",	&repeat.vAngle.x,
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Locator/
MCountryCodeFilter.cpp

163
	strncpy( szPos1, &strIP[0], a );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MUpdate/
MPatchBuilder.cpp

138
		sprintf(szFind, "%s/*", strDir.c_str());
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MatchAgent/
MatchAgent.cpp

71
	strcpy(pszBuf, szFileName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MatchServer/
MBMatchAsyncDBJob_NetmarbleLogin.cpp

98
	strcpy(m_szUniqueID, szUniqueID);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchMonitor.cpp

188
		sprintf(strDBConnect, "DATABASE_CONNECT:%s", szExeFileName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

123
		sprintf( szErrCode, "system error." );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MatchServer/
MBMatchServer.cpp

36
	int nEnd = (int)(strlen(szBuf)-1);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchServer.cpp

33
	vsprintf(szBuf, pFormat, args);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

372
					strcpy(szItemName, pItemName);
MEDIUM
Security


Avoid using 'strtok()'. This function directly modifies the first argument buffer, permanently erasing the delimiter character.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

705
			token = strtok(szBuffer, ",");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

159
		fwrite(name,strlen(name)+1,1,file);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

367
					memset(szItemName, 0, sizeof(szItemName));
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

538
			strcat(strBuffer, ".elu");
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

706
			if (token != NULL) r = atoi(token);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

708
			if (token != NULL) g = atoi(token);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

537
			strcpy(strBuffer, psp->name.c_str());
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Ani.cpp

299
	memset(mesh_node->m_pos_key,0,sizeof(RPosKey)*pos_key_cnt);
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

181
		wcscpy(buf, ID_ENVMAP);
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

195
			case ID_RR: wcscpy(buf, ID_MAP_REFRACT);		break;
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

233
			wcstombs(mtrl_node->m_tex_name,str,wcslen(str));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

214
	strcpy(g_FileName,filename);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

330
		FILE *file=fopen(GetFileName(g_FileName,0),"w+");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

50
	strcpy(pRemoveExt, pFileName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

96
	for(int i=nCount; i<(int)strlen(pDir); i++){
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

45
			memcpy(pRemoveExt, pFileName, nLen-i-1);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

263
	FILE *file=fopen(filename,"r");
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

246
	memset(pHeader, 0, nHeaderSize);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

50
	strcpy(pRemoveExt, pFileName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

114
	BYTE n=strlen(x);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

152
				memcpy(&mesh->face[i],&mesh->face[mesh->nF-1],sizeof(rface));
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

306
	FILE *stream=fopen(name,"wb+");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

319
		sprintf(MaxFilePath,"%s%s",drive,dir);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

361
					sprintf(bmpname,"%s%s.bmp",MaxFilePath,fname);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Mcv/
McvView.cpp

2129
		strcpy( g_last_open_elu_file , filename );
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Mcv/
McvView.cpp

2179
		lstrcpy((LPSTR)t_filename,(LPSTR)t_str.operator const char*());
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Mint2/Source/
MDrawContext.cpp

582
	int nStrLen = strlen(szText);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Mint2/Source/
MDrawContext.cpp

466
				strcat(pText, "^");
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/PatchInterface/PatchInterface/
ReloadServerConfigDlg.cpp

49
		memset( szFile, 0, 64 );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Samples/
Preview.cpp

197
	if(!strlen(g_filename))
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RAnimationNode.cpp

201
		memcpy(pVecTable,v1,sizeof(D3DXVECTOR3)*vcnt);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/RealSpace2/Source/
RBspObject.cpp

1535
		if(strnicmp(plight->Name.c_str(),RTOK_MAX_OBJLIGHT,strlen(RTOK_MAX_OBJLIGHT))==0)
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/RealSpace2/Source/
RBspObject.cpp

1618
					strcat(fname,".ani");
MEDIUM
Security


Avoid using 'strtok()'. This function directly modifies the first argument buffer, permanently erasing the delimiter character.

Stable/RealSpace2/Source/
RBspObject.cpp

1866
					token = strtok(NULL, " ");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject.cpp

2489
						memcpy(pdi->pVertices+base,pNode->ppInfoSorted[k]->pVertices,sizeof(BSPVERTEX)*pNode->ppInfoSorted[k]->nVertices);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/RealSpace2/Source/
RBspObject.cpp

1599
			strcat(fname,szContents);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

2478
			memcpy(&pNode->bbTree,&pNode->Positive->bbTree,sizeof(rboundingbox));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3179
		memcpy(pbaseinfo,m_pOcInfo,sizeof(RPOLYGONINFO)*m_nPolygon);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3346
					memcpy(temp,pNode->pVertices+j*3,sizeof(BSPVERTEX)*3);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3180
		memcpy(pbasever,m_pOcVertices,sizeof(BSPVERTEX)*m_nPolygon*3);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

2508
		sprintf(bspname,"%s.bsp",filename);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RMesh_Render.cpp

795
					memcpy(vFindVec, vec, sizeof(rvector) * 3);
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/ServerKeeper/
MServerKeeper.cpp

658
		sscanf( szBuf, "%d %d", &nColumnID, &nConfigState );
CRITICAL
Security

Input Validation


Due to how `CreateProcess` parses spaces, an attacker may be able to exploit this function by creating a binary with the same name that is loaded first, depending on the search path order.

Stable/ServerKeeper/
MServerKeeper.cpp

339
		if(CreateProcess(NULL, _T(szBat), NULL, NULL, FALSE, 0, NULL, _T(szDir), &sui, &pi)){
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Utils/CodeShuffler/ShuffleLineOrder/
ShuffleLineOrder.cpp

97
			if (1 != sscanf(szTokFound, SWAPFORMAT, szTag))
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Utils/DDakzi/
Memo.cpp

64
		sprintf(filename2,"%s.%d",MEMO_FILE_NAME,i+1);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/MEncrypt/
FFileList.cpp

26
				strcat(_path,file_t.cFileName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/MEncrypt/
FFileList.cpp

46
					strncpy(temp_name,path,len-1);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Utils/MEncrypt/
FFileList.cpp

48
					strcat(temp_name,file_t.cFileName);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/ReplayAnalysis/GunzReplayConverter/
ReplayConverter.cpp

272
			memcpy(&serialNumber, pData+nDataCount, sizeof(serialNumber));
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream3/
zfstream.cc

163
    strcat(c_mode, "b");
CRITICAL
Security

Input Validation


The input buffer is the number of bytes in the string, but the size of the output buffer is the number of characters.

Stable/cml/source/
MLocale.cpp

118
	int nReqLen = (int)MultiByteToWideChar( nOldCodePage, 0, pszString, -1, 0, 0 ); 
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/sdk/maxsdk/howto/maxscript/testdlx/
tester.cpp

248
	DLGetTextExtent(ro->rollout_dc, text, static_cast<int>(_tcslen(text)), &size, true); 	
CRITICAL
Security

Input Validation


The `lstrcpyn` family of functions do not always check for invalid pointers or check if there is sufficient space prior to copying.

Stable/sdk/maxsdk/howto/postfilters/nodetrak/
nodetrak.cpp

362
			wcsncpy(data.nodename_w, nodeName.data(), _countof(data.nodename_w)-1);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/sdk/maxsdk/howto/postfilters/nodetrak/
nodetrak.cpp

360
			memcpy((void *)&data,ptr,sizeof(NODETRAKDATA_A));
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MActorDef.cpp

65
			pActorDef->SetMaxHp(atoi(itor->first_attribute("max_hp")->value()));
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MMatchNotify.cpp

42
				nID = atoi(itor->first_attribute(ZTOK_ID)->value());
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MMatchRuleDuelTournament.cpp

399
		memcpy(&m_CurrentMatchInfo, (MMatchDuelTournamentMatch*)iter1->second, sizeof(MMatchDuelTournamentMatch));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchWorldItemDesc.cpp

237
	memset(m_MapsSpawnInfo, 0, sizeof(MMatchMapsWorldItemSpawnInfoSet) * MMATCH_MAP_COUNT);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MNJ_DBAgentClient.cpp

9
	memset(m_cPacketBuf, 0, sizeof(m_cPacketBuf));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MNJ_DBAgentClient.cpp

31
	memcpy(pNewPacket->cDataBody, nCode, sizeof(int)*2);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestMap.cpp

269
					pSectorInfo->nID = atoi(szAttrValue);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestMap.cpp

277
					pSectorInfo->nSpawnPointCount[MNST_MELEE] = atoi(szAttrValue);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/CSCommon/Source/
MQuestMap.cpp

209
					strcpy(pSector->Links[nLinkIndex].szName, szAttrValue);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MSacrificeQItemTable.cpp

69
	SacriQItemInfo.m_nSpecialQItemID1 = atoi(element->first_attribute(MSQITC_SIID1)->value());
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/CSCommon/Source/
MSurvivalMap.cpp

39
	strncpy( m_MapInfo[nMap].szName, szMapName, nMapNameLen );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

78
				sprintf(szAnnounce, "^1  ");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

434
				strcat(szLoserMembers, " ");
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZBirdDummyAI.cpp

307
						strcpy(m_szLastStage, pNode->szStageName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZBirdDummyAI.cpp

155
					sprintf(szTemp, "Join Flood(%u)", stJoinCount++);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZClanListBox.cpp

78
	strcpy(pInfo->szClanName , szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZConsole.cpp

39
			strcpy(szMsg, &szInputStr[3]);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZEffectStaticMesh.cpp

118
				strcat( buffer, pCObj->m_pSoundMaterial );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZGameClient_Ladder.cpp

314
		int len = (int)strlen(ppReplierCharNames[i]);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZGameClient_Ladder.cpp

167
			strcat(szMembers, szMemberNames[i]);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

114
		strcpy(szDesc, 
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZGameClient_Ladder.cpp

111
		strcpy( szTitle, 
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZGameClient_Ladder.cpp

168
			if (i != nMemberCount-1) strcat(szMembers, ", ");
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZMonsterBookInterface.cpp

284
					strcat( szGrade, ZMsg(MSG_WORD_REGULAR));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZMonsterBookInterface.cpp

390
			sprintf( szPageNum, "- %d -", m_nCurrentPageNum);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZMonsterBookInterface.cpp

335
				strcat( szHP, ZMsg(MSG_WORD_NORAML));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

328
			strcpy( szHP, "HP : ");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

288
					strcat( szGrade, ZMsg(MSG_WORD_LEGENDARY));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

296
					strcat( szGrade, ZMsg(MSG_WORD_ELITE));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

335
				strcat( szHP, ZMsg(MSG_WORD_NORAML));
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZMonsterBookInterface.cpp

288
					strcat( szGrade, ZMsg(MSG_WORD_LEGENDARY));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

218
	sprintf( szLog, "Init Authentic fail. error code : (%s), comment : (%s)\n", szErrCode, strComment.c_str() );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNHN_USA.cpp

97
	strcpy( szGameStringOld, pszArgs );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

210
		sprintf( szErrCode, "system error." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

182
		sprintf( szErrCode, "general fault." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

206
		sprintf( szErrCode, "memberID is not HangameID." );
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.cpp

70
		strcpy(buf, str);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetmarble.cpp

111
			strcpy(szTemp, &szSrcStr[i]);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZNetmarble.cpp

68
		size_t slen = strlen(str);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZSurvival.cpp

1200
		sprintf(szText, "%d", pRank->m_dwPoint);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Locator/
MCountryCodeFilter.cpp

166
	strncpy( szPos4, &strIP[c + 1], strIP.length() - c - 1 );
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Locator/
MCountryCodeFilter.cpp

163
	strncpy( szPos1, &strIP[0], a );
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/Locator/
MCountryCodeFilter.cpp

173
	dwPos4 = static_cast< DWORD >( atoi(szPos4) );
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Locator/
MCountryCodeFilter.cpp

173
	dwPos4 = static_cast< DWORD >( atoi(szPos4) );
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Locator/
MCountryCodeFilter.cpp

171
	dwPos2 = static_cast< DWORD >( atoi(szPos2) );
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/Locator/
MCountryCodeFilter.cpp

428
		sscanf( szBuf, "%s", szLine );
CRITICAL
Security

Input Validation


Format string vulnerabilities allow an attacker to read or in some cases, potentially write data to and from locations in the processes' memory.

Stable/MDatabase/Source/
MDatabase.cpp

50
			_snprintf( szLog, 255, "MDatabase::Connect - %s\n", e->m_strError );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MUpdate/
MPatchBuilder.cpp

164
					strcpy( szFileExtName, FindData.cFileName + ( strlen( FindData.cFileName) - 3));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MUpdate/
MPatchBuilder.cpp

158
					sprintf(szFilePath, "%s/%s", strDir.c_str(), FindData.cFileName);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchAgent/
MatchAgent.cpp

62
		sprintf(szFileName, "Log/AgentLog_%02d-%02d-%02d-%d.txt", 
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

95
		sprintf( szErrCode, "general fault." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

115
		sprintf( szErrCode, "password mismatch( over 3 times )." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

99
		sprintf( szErrCode, "parameter of auth is invalid." );
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/MatchServer/
MBMatchServer.cpp

100
	FILE *ReadFp = fopen(filePath, "rb");
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

679
			_tcscpy(szBuffer, WSTRToTSTR(prospec->lpwstr));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

249
			sprintf(filename, "%s_%s.elu", MapName, pNode->GetName());
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

348
			sprintf(szDummyName, "spawn_item_%s", szTok);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

368
					memcpy(szItemName, pItemName, plast - pItemName);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

710
			if (token != NULL) b = atoi(token);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

338
		else strcpy(szTok, "team");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

971
			memcpy(&bbneg, bb, sizeof(dboundingbox));
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

192
			case ID_FI: wcscpy(buf, ID_MAP_FILTERCOLOR);	break;
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

191
			case ID_OP: wcscpy(buf, ID_MAP_OPACITY);		break;
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

190
			case ID_SI: wcscpy(buf, ID_MAP_SELFILLUM);		break;
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

269
				case CDESTINATION	:	strcpy(g_Destination,pCommand->szBuffer);break;
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

64
					strcpy(pAnim->szMaxFileName,szFile);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

142
		strcpy(pRelativePath, szPath);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

20
		memcpy(ft, &(fi.ftLastWriteTime), sizeof(FILETIME));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

64
	int nStr0Len = strlen(pStr0);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

65
	int nStr1Len = strlen(pStr1);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

401
					sprintf(bmpname,"%s%s%s.bmp",drive,dir,fname);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

556
	memcpy(&m_Vertices[nV],pVer,sizeof(rvertex));nV++;
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

535
				memcpy(&pFaces->face[j],temp[j+laststart],sizeof(rface));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

212
		memcpy(header,mesh->name,3);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

578
				memcpy(pFaces->verlist.Get(i*3+j),&v,sizeof(rvertex));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Mint2/Source/
MCursor.cpp

10
	strcpy(m_szName, szName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Mint2/Source/
MDrawContext.cpp

411
			strncpy(pText, pSrc, nPos);				// ŭ ī
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Mint2/Source/
MDrawContext.cpp

418
		nLen = strlen(pSrc);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/Mint2/Source/
MEvent.cpp

243
					memset(pMint->m_nCompositionAttributes, 0, sizeof(BYTE)*(MIMECOMPOSITIONSTRING_LENGTH));
MEDIUM
Security


Avoid using 'strtok()'. This function directly modifies the first argument buffer, permanently erasing the delimiter character.

Stable/RealSpace2/Source/
RBspObject.cpp

1864
					token = strtok(szBuffer, " ");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/RealSpace2/Source/
RBspObject.cpp

1599
			strcat(fname,szContents);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

1234
			memcpy(v,pVertices[i*3],3*sizeof(rvector));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3184
			memcpy(m_pOcInfo+i,pbaseinfo+pOrder[i],sizeof(RPOLYGONINFO));
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

2842
					int nSuccess = sscanf( szContents, "%f %f %f", &pos.x, &pos.y, &pos.z );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/RealSpace2/Source/
RToken.cpp

12
	sprintf(buffer,FORMAT_FLOAT,f);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/ServerKeeper/
MServerKeeper.cpp

336
	if(file = fopen(szBat, "r")){
CRITICAL
Security

Input Validation


Format string vulnerabilities allow an attacker to read or in some cases, potentially write data to and from locations in the processes' memory.

Stable/ServerKeeper/
MServerKeeper.cpp

1162
		_snprintf( szServerLastMod, 127, "%d.%d.%d %d:%d", 
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/ServerKeeper/
MServerKeeper.cpp

331
	strcat(szBat, "setup.bat");
CRITICAL
Security

Input Validation


It is generally not recommended to call out to the operating system to execute commands.

Stable/Utils/CodeShuffler/ShuffleLineOrder/
ShuffleLineOrder.cpp

160
	system("pause");
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/CodeShuffler/ShuffleLineOrder/
ShuffleLineOrder.cpp

67
	fp = fopen(szFile, "rt");
MEDIUM
Security

Visibility


The detected function is not sufficient at generating security-related random numbers, such as those used in key and nonce creation.

Stable/Utils/CodeShuffler/ShuffleLineOrder/
ShuffleLineOrder.cpp

113
	srand(timeGetTime());
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/MEncrypt/
FFileList.cpp

26
				strcat(_path,file_t.cFileName);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/MEncrypt/
FFileList.cpp

48
					strcat(temp_name,file_t.cFileName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/MEncrypt/
FFileList.cpp

24
				strcpy(_path,path);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/MEncrypt/
FFileList.cpp

33
			int len = (int)strlen(ext);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MBlobArray.cpp

9
	memcpy(pBlob, &nOneBlobSize, sizeof(nOneBlobSize));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MBlobArray.cpp

29
	memcpy(&nBlobCount, (unsigned char*)pBlob+sizeof(nOneBlobSize), sizeof(nBlobCount));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MCrypt.cpp

17
	memcpy(m_IV, IV, sizeof(m_IV));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/cml/source/
MLocale.cpp

122
	memset( pszDst, 0x00, (int)sizeof(wchar_t) * (nReqLen + 1));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/sdk/maxsdk/howto/utilities/MeshSplit/
SplitMeshes.cpp

165
		_stprintf (numstring, _T("_%d"), i);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MMatchServer_Char.cpp

630
	memcpy(pTransCharInfoDetail, &trans_charinfo_detail, sizeof(MTD_CharInfo_Detail));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MMatchWorldItemDesc.cpp

126
	memset(pNewWorldItemDesc, 0, sizeof(MMatchWorldItemDesc));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MNJ_DBAgentClient.cpp

83
			memcpy(m_cPacketBuf, m_cPacketBuf+sizeof(NJ_PACKET), m_nQueueTop-sizeof(NJ_PACKET));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/CSCommon/Source/
MNJ_DBAgentClient.cpp

73
	memcpy(m_cPacketBuf + m_nQueueTop, pPacket, dwSize);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestDropTable.cpp

148
				nQL = atoi(itor->first_attribute(MTOK_DROPSET_ATTR_QL)->value());
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MQuestDropTable.cpp

170
						nRentPeriodHour = atoi(it->first_attribute(MTOK_DROPSET_ATTR_RENT_PERIOD)->value());
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/CSCommon/Source/
MSacrificeQItemTable.cpp

70
	SacriQItemInfo.m_nSpecialQItemID2 = atoi(element->first_attribute(MSQITC_SIID2)->value());
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MSurvivalMap.cpp

33
	size_t nMapNameLen = strlen( szMapName );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

80
					if (strlen(szMembers[i]) <= 0) break;
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

433
				strcat(szLoserMembers, pObj->GetCharInfo()->m_szName);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

82
					strcat(szAnnounce, " ");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

429
				strcat(szWinnerMembers, " ");
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZClanListBox.cpp

62
				sprintf(szBuffer,ZMsg( MSG_LOBBY_WAITING ),pInfo->nPlayers );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZConsole.cpp

39
			strcpy(szMsg, &szInputStr[3]);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Gunz/
ZEffectStaticMesh.cpp

118
				strcat( buffer, pCObj->m_pSoundMaterial );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

111
		strcpy( szTitle, 
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

148
		strcpy(szMemberNames[i], pReplierNode->szName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZGameGuard.cpp

257
		mlog( "GameGuard callback message is overflow (length=%u)\n", strlen(szCallbackMsg));
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZMonsterBookInterface.cpp

335
				strcat( szHP, ZMsg(MSG_WORD_NORAML));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZMonsterBookInterface.cpp

333
				strcat( szHP, ZMsg(MSG_WORD_HARD));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZNHN_USA.cpp

190
		sprintf( szErrCode, "this ip address is invalid." );
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetAgreementBuilder.cpp

47
		strcpy(pNewReplier->szCharName, ppReplierNames[i]);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetAgreementBuilder.cpp

125
			strcpy(out, pReplier->szCharName);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetAgreementBuilder.cpp

47
		strcpy(pNewReplier->szCharName, ppReplierNames[i]);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetAgreementBuilder.cpp

125
			strcpy(out, pReplier->szCharName);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZNetAgreementBuilder.cpp

112
		strcpy(ppReplierNames[nCount], pReplier->szCharName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Gunz/
ZNetmarble.cpp

106
	int nSrcStrLen = (int)strlen(szSrcStr);
MEDIUM
Security


Avoid using 'strtok()'. This function directly modifies the first argument buffer, permanently erasing the delimiter character.

Stable/Gunz/
ZNetmarble.cpp

207
			token = strtok( NULL, seps );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Gunz/
ZNetmarble.cpp

153
		strcpy(arg[argcnt], token);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/Gunz/
ZNetmarble.cpp

189
			int nAge = atoi(szValue);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Gunz/
ZShopEquipItemConfirm.cpp

118
		int count = atoi(sz);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZSkill.cpp

698
			sprintf(szSoundName,"%s_2d",m_pDesc->szEffectSound);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/Gunz/
ZSurvival.cpp

1231
	sprintf(szText, "%d", nPoint);
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Locator/
MCountryCodeFilter.cpp

170
	dwPos1 = static_cast< DWORD >( atoi(szPos1) );
CRITICAL
Security

Input Validation


The `strncpy` family of functions do not properly handle strings that are not null terminated.

Stable/Locator/
MCountryCodeFilter.cpp

166
	strncpy( szPos4, &strIP[c + 1], strIP.length() - c - 1 );
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/Locator/
MCountryCodeFilter.cpp

170
	dwPos1 = static_cast< DWORD >( atoi(szPos1) );
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/Locator/
MCountryCodeFilter.cpp

172
	dwPos3 = static_cast< DWORD >( atoi(szPos3) );
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Locator/
MCountryCodeFilter.cpp

165
	strncpy( szPos3, &strIP[b + 1], c - b - 1 );
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MatchServer/
MBMatchAsyncDBJob_NetmarbleLogin.cpp

97
	strcpy(m_szUserID, szUserID);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchMonitor.cpp

221
	sprintf(strRunningTime, "RUN_TIME:%s:%s", szExeFileName, szRunningTime);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

119
		sprintf( szErrCode, "memberID is not HangameID." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchNHNAuth.cpp

127
		sprintf( szErrCode, "Not Defined." );
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MatchServer/
MBMatchServer.cpp

446
	sprintf(szTemp, "Release Date : %s", __DATE__);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MatchServer/
MBMatchServer_Item.cpp

984
		memcpy( pSendGItem->szName
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

699
			max = atoi(szBuffer);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

622
			_stprintf(szString, "%ld", pProp->lVal);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

706
			if (token != NULL) r = atoi(token);
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

616
			_tcscpy(szString, WSTRToTSTR(pProp->pwszVal) );
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

429
		if (strnicmp(psp->name.c_str(), cszDummyName, strlen(cszDummyName)) == 0)
MEDIUM
Security

Input Validation


The `atoi` family of functions can potentially overflow or underflow integer values.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

699
			max = atoi(szBuffer);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

968
			memcpy(&bbpos, bb, sizeof(dboundingbox));
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

558
					sprintf(strBuffer2, "%s%d", RTOK_RESTRICTION_AXIS, i);
MEDIUM
Security


Avoid using 'strtok()'. This function directly modifies the first argument buffer, permanently erasing the delimiter character.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

707
			token = strtok(NULL, ",");
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/BspExporter/
RSBspExporter.cpp

644
			_tcscpy(szString, "");	
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

187
			case ID_SP: wcscpy(buf, ID_MAP_SPECULAR);		break;
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

199
		wcscpy(buf, ID_MAP_GENERIC);
CRITICAL
Security

Input Validation


The `lstrcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/MCPlug/
MCPlug2_Mtrl.cpp

194
			case ID_RL: wcscpy(buf, ID_MAP_REFLECT);		break;
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

384
		strcpy(pCommand->szBuffer,g_RMLFile);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

376
		strcpy(pCommand->szBuffer,g_Destination);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

270
				case CRMLFILE		:	strcpy(g_RMLFile,pCommand->szBuffer);break;
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

49
				strcpy(pCommand->szBuffer,szFile);
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

49
				strcpy(pCommand->szBuffer,szFile);
CRITICAL
Security

Input Validation


Use sprintf_s, snprintf, or vsnprintf instead.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

151
		sprintf(buf,"%3.3f",g_pSelectedAnimation->fAnimationSpeed);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/RSBatchExporter/
BEWorkSheet.cpp

41
		char *ext=_strupr(szFile+strlen(szFile)-3);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/RSBatchExporter/
OpenDlg.cpp

92
	strcpy(szDir, pFileNames);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/RSBatchExporter/
OpenDlg.cpp

100
		nLen = strlen(pNextNames);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

219
	if(pBasePath[strlen(pBasePath)]!='\\') strcat(pBasePath,"\\");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

42
	int nLen = strlen(pFileName);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/MaxPlugIns/ss3exp/
FileInfo.cpp

247
	memcpy((char *)pHeader+sizeof(int), pReadData, min((int)nRealSize, (int)(nHeaderSize-sizeof(int))));
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/MaxPlugIns/ss3exp/
RSMObject.cpp

417
		strcpy(material->RMLName,material->name);
CRITICAL
Security

Input Validation


The `strncat` family of functions are easy to use incorrectly when calculating destination buffer sizes.

Stable/Mint2/Source/
MDrawContext.cpp

458
		strncat(pText, pSrc, nPos);				// ŭ ī
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/PatchInterface/PatchInterface/
ReloadServerConfigDlg.cpp

48
		memset( szLine, 0, 256 );
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/RealSpace2/Source/
RBspObject.cpp

1599
			strcat(fname,szContents);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject.cpp

2678
	memcpy(pVer,m_pOcVertices,sizeof(BSPVERTEX)*m_nVertices);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/RealSpace2/Source/
RBspObject.cpp

1618
					strcat(fname,".ani");
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3353
					memcpy(pNode->pInfo+k,&ttemp,sizeof(ttemp));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

2483
			memcpy(&pNode->bbTree,&pNode->Negative->bbTree,sizeof(rboundingbox));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

3347
					memcpy(pNode->pVertices+j*3,pNode->pVertices+k*3,sizeof(BSPVERTEX)*3);
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

72
			strcat(buffer,buffer2);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/RealSpace2/Source/
RBspObject_bsp.cpp

38
		memcpy(pVertices,source->pVertices,sizeof(rvector)*nCount); }
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/ServerKeeper/
MServerKeeper.cpp

330
	strcpy(szBat, szDir);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/ServerKeeper/
MServerKeeper.cpp

347
	if(file = fopen(setupFile, "r")){
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/ServerKeeper/
MServerKeeper.cpp

330
	strcpy(szBat, szDir);
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/ServerKeeper/
MServerKeeper.cpp

354
	if(file = fopen(upFile,"r")){
MEDIUM
Security

Insecure Storage


Usage of the `open` family of functions may hint at a potential Time Of Check Time Of Use (TOCTOU) vulnerability.

Stable/Utils/DDakzi/
Memo.cpp

97
		file=fopen(MEMO_FILE_NAME,"wb+");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/MEncrypt/
FFileList.cpp

26
				strcat(_path,file_t.cFileName);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/Utils/MEncrypt/
FFileList.cpp

22
				int len = strlen(path);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Utils/MEncrypt/
FFileList.cpp

24
				strcpy(_path,path);
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/Utils/MEncrypt/
FFileList.cpp

48
					strcat(temp_name,file_t.cFileName);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/ReplayAnalysis/GunzReplayConverter/
ReplayConverter.cpp

319
					memcpy( &nSize, pData+nDataCount, sizeof(nSize) );
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/Utils/ReplayAnalysis/GunzReplayConverter/
ReplayConverter.cpp

261
			memcpy(&nTotalSize, pData, sizeof(nTotalSize));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream3/
zfstream.cc

152
    strcpy(c_mode, "r");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Utils/ReplayAnalysis/InfluenceMapMaker/zlib/contrib/iostream3/
zfstream.cc

163
    strcat(c_mode, "b");
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/cml/source/
MArchive.cpp

95
	Add(szName, MAT_STRING, sz, strlen(sz)+1);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MArchive.cpp

49
	memcpy(pItem->szName, szName, MAITEM_NAME_LENGTH);
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MBlobArray.cpp

38
	memcpy(&nBlobCount, (unsigned char*)pBlob+sizeof(int), sizeof(nBlobCount));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MBlobArray.cpp

10
	memcpy(pBlob+sizeof(nBlobCount), &nBlobCount, sizeof(nOneBlobSize));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/cml/source/
MCrypt.cpp

16
	memcpy(m_Key, Key, sizeof(m_Key));
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/cml/source/
MInet.cpp

106
	memset(m_szRecvBuf, 0, sizeof(m_szRecvBuf));
CRITICAL
Security

Input Validation


The `memcpy` family of functions require the developer to validate that the destination buffer is the same size or larger than the source buffer.

Stable/sdk/maxsdk/howto/postfilters/nodetrak/
nodetrak.cpp

378
		memcpy(ptr,(void *)&data,sizeof(NODETRAKDATA_W));
CRITICAL
Security

Input Validation


Format specifiers can take optional field widths, which should be used to limit how many characters are copied into the target buffer.

Stable/CSCommon/Source/
MMatchMap.cpp

110
				sscanf(lightMaps, "%s : %s : %s : %s",tmp1,tmp2,tmp3,tmp4);
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer_Char.cpp

136
	mlog( ")  (len = %d)\n", (int)strlen( szCharName));
CRITICAL
Security

Input Validation


The `strlen` family of functions does not handle strings that are not null terminated.

Stable/CSCommon/Source/
MMatchServer_Ladder.cpp

243
		if ((strlen(pNode->szName) <= 0) || (strlen(pNode->szName) >= MATCHOBJECT_NAME_LENGTH)) return;
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MNJ_DBAgentClient.cpp

22
	memset(pNewPacket, 0, sizeof(NJ_PACKET));
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MQuestDropTable.cpp

230
		int nID = atoi(szAttrValue);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MQuestDropTable.cpp

137
	pDropSet->SetID(atoi(element->first_attribute(MTOK_DROPSET_ATTR_ID)->value()));
CRITICAL
Security

Input Validation


The `strcpy` family of functions do not provide the ability to limit or check buffer sizes before copying to a destination buffer.

Stable/CSCommon/Source/
MQuestMap.cpp

273
					strcpy(pSectorInfo->szTitle, szAttrValue);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MQuestMap.cpp

273
					strcpy(pSectorInfo->szTitle, szAttrValue);
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/CSCommon/Source/
MQuestMap.cpp

142
			strcpy(pMapsetInfo->szTitle, szAttrValue);
MEDIUM
Error prone


Avoid the 'ato*()' family of functions.

Stable/CSCommon/Source/
MQuestMap.cpp

269
					pSectorInfo->nID = atoi(szAttrValue);
MEDIUM
Security

Other


When handling sensitive information in a buffer, it's important to ensure that the data is securely erased before the buffer is deleted or reused.

Stable/CSCommon/Source/
MQuestNPCSpawnTrigger.cpp

65
	memset(&m_Info, 0, sizeof(SpawnTriggerInfo));
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

84
				strcat(szAnnounce, "Դϴ.");
CRITICAL
Security

Input Validation


The `StrCat` family of functions do not guarantee the final string to be null terminated.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

82
					strcat(szAnnounce, " ");
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/CSCommon/Source/
MTeamGameStrategy.cpp

429
				strcat(szWinnerMembers, " ");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZBirdDummyAI.cpp

307
						strcpy(m_szLastStage, pNode->szStageName);
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZEffectStaticMesh.cpp

118
				strcat( buffer, pCObj->m_pSoundMaterial );
CRITICAL
Security

Input Validation


The `strcat` family of functions are unable to limit how many bytes are copied to the destination buffer.

Stable/Gunz/
ZGameClient_Ladder.cpp

168
			if (i != nMemberCount-1) strcat(szMembers, ", ");
MEDIUM
Security


Finding triggers whenever there is a strcpy or strncpy used.

Stable/Gunz/
ZGameClient_Ladder.cpp

239
				strcpy(szMember[0], ZGetMyInfo()->GetCharName());
MEDIUM
Security


Finding triggers whenever there is a strcat or strncat used.

Stable/Gunz/
ZGameClient_Ladder.cpp

168
			if (i != nMemberCount-1) strcat(szMembers, ", ");
MEDIUM
Security
