Core Roku Objects
-----------------
roArray
roAssociativeArray
roBoolean
roBrSub
roByteArray
roDouble
roFloat
roFunction
roGlobal
roInt
roIntrinsicDouble
roInvalid
roList
roMessagePort
roString
roXMLElement
roXMLList

ro(Global|XML(Element|List)|MessagePort|B(yteArray|oolean|rSub)|String|In(t|valid)|Float|List|A(ssociativeArray|rray))

roArray Interfaces and Methods
------------------------------
ifArray
- Peek() As Dynamic
- Pop() As Dynamic
- Push(a As Dynamic)
- Shift() As Dynamic
- Unshift(a As Dynamic)
- Delete(a As Integer) As Boolean
- Count() As Integer
- Clear()
- Append(a As Object)
ifEnum
- Reset()
- Next() As Dynamic
- IsNext() As Boolean
- IsEmpty() As Boolean
ifArrayGet
- GetEntry(a As Integer) As Dynamic
ifArraySet
- SetEntry(a As Integer, b As Dynamic)


roAssociativeArray Interfaces and Methods
-----------------------------------------
ifEnum
- Reset() As Void
- Next() As Dynamic
- IsNext() As Boolean
- IsEmpty() As Boolean
ifAssociativeArray
- AddReplace(key As String, value As Object) As Void
- Lookup(key As String) As Object
- DoesExist(key As String) As Boolean
- Delete(key As String) As Boolean
- Clear() As Void
- SetModeCaseSensitive() As Void
- LookupCi(a As String) As Dynamic
- Append(a As Object) As Void

Core Interfaces
----------
ifArray
ifAssociativeArray
ifBoolean
ifBrSub
ifByteArray
ifEnum
ifFloat
ifInt
ifList
ifMessagePort
ifString
ifStringOps
ifXMLElement
ifXMLList


Core Object Functions
---------------------
AddAttribute
AddBodyElement
AddCircleRegion
AddDNSServer
AddElement
AddElementWithBody
AddEvent
AddHead
AddHeader
AddMilliseconds
AddRectangleRegion
AddRectangle_region
AddReplace
AddSeconds
AddTail
Append
AppendFile
AppendString
Apply
As
Asc
AsyncFlush
AsyncGetToFile
AsyncGetToString
AsyncHead
AsyncPostFromFile
AsyncPostFromString
AtEof
Boolean
Chr
Clear
ClearEvents
ClearRegion
Cls
Count
CurrentPosition
Delete
DisplayFile
DisplayFileEx
DisplayPreload
DoesExist
Double
Dynamic
EnableCursor
EnableInput
EnableOutput
EnableRegion
EnableRollover
Exists
FindIndex
Float
Flush
FromAsciiString
FromBase64String
FromHexString
Function
GenXML
GenXMLHeader
GetAttributes
GetBody
GetBoolean
GetBootVersion
GetBootVersionNumber
GetByteArray
GetBytesPerBlock
GetChildElements
GetControls
GetCurrentConfig
GetCurrentControlValue
GetCurrentInput
GetCurrentStandard
GetData
GetDay
GetDayOfWeek
GetDescription
GetDeviceBootCount
GetDeviceName
GetDeviceUniqueId
GetDeviceUptime
GetEntityEncode
GetEntry
GetFailureReason
GetFamily
GetFileSystemType
GetFloat
GetFreeInMegabytes
GetHead
GetHeight
GetHostName
GetHour
GetIdentity
GetIndex
GetInputs
GetInt
GetKeyList
GetLocalDateTime
GetMessage
GetMillisecond
GetMinute
GetMode
GetModel
GetMonth
GetName
GetNamedElements
GetNextArticle
GetResource
GetResponseCode
GetResponseHeaders
GetSafeHeight
GetSafeWidth
GetSafeY
GetSafeX
GetSecond
GetSectionList
GetSignedByte
GetSizeInMegabytes
GetSourceHost
GetSourceIdentity
GetSourcePort
GetStandards
GetStatusByte
GetStorageCardInfo
GetString
GetStringCount
GetSub
GetTail
GetText
GetTimeServer
GetTimeZone
GetTitle
GetToFile
GetToString
GetUsedInMegabytes
GetUserData
GetUtcDateTime
GetValue
GetVersion
GetVersionNumber
GetWholeState
GetWidth
GetX
GetY
GetYear
GetZoneDateTime
HasAttribute
Head
Hide
Instr
Integer
Interface
Invalid
IsEmpty
IsInputActive
IsLittleEndianCPU
IsMousePresent
IsName
IsNext
IsValid
Left
Len
Lookup
MapDigitalOutput
MapStereoOutput
MapStereoOutputAux
MD5
Mid
Next
Normalize
Object
Parse
ParseFile
ParseString
Peek
Play
PlayFile
PlayStaticImage
Pop
PopString
PopStrings
PostFromFile
PostFromString
PostMessage
PreloadFile
PreloadFileEx
Push
PushString
Read
ReadBlock
ReadByte
ReadByteIfAvailable
ReadFile
ReadLine
RemoveHead
RemoveIndex
RemoveTail
Reset
ResetIndex
Right
ScanWiFi
SeekAbsolute
SeekRelative
SeekToEnd
Send
SendBlock
SendByte
SendLine
SendRawMessage
SetAudioMode
SetAudioModeAux
SetAudioOutput
SetAudioOutputAux
SetAudioStream
SetAudioStreamAux
SetBackgroundBitmap
SetBackgroundColor
SetBaudRate
SetBody
SetBoolean
SetByteEventPort
SetChannelVolumes
SetChannelVolumesAux
SetControlValue
SetCursorBitmap
SetCursorPos
SetCursorPosition
SetDate
SetDateTime
SetDay
SetDayOfWeek
SetDefaultMode
SetDefaultTransistion
SetDestination
SetDHCP
SetDomain
SetEcho
SetEntry
SetEol
SetFlashRate
SetFloat
SetFont
SetForegroundColor
SetForgroundColor
SetHeight
SetHostName
SetHour
SetInput
SetInt
SetIP4Address
SetIP4Broadcast
SetIP4Gateway
SetIP4Netmask
SetLauguage
SetLineEventPort
SetLocalDateTime
SetLoopMode
SetMillisecond
SetMinimumTransferRate
SetMinute
SetMode
SetModeCaseSensitive
SetMonth
SetMultiscreenBezel
SetName
SetOutputState
SetPassword
SetPort
SetPowerSaveMode
SetProxy
SetReceiveEol
SetRectangle
SetResize
SetResolution
SetRollOverRegion
SetSafeTextRegion
SetSecond
SetSendEol
SetStandard
SetString
SetSub
SetTime
SetTimeServer
SetTimeZone
SetUrl
SetUserAndPassword
SetUserData
SetUtcDateTime
SetViewMode
SetVolume
SetVolumeAux
SetWholeState
SetWidth
SetWiFiESSID
SetWiFiPassphrase
SetX
SetY
SetYear
Shift
Show
Simplify
Start
Stop
StopClear
StopDisplay
Str
Stri
String
SubtractMilliseconds
SubtractSeconds
TestInterface
TestInternetConnectivity
ToAsciiString
ToBase64String
ToHexString
Tokenize
Trim
UCase
Unpack
Unshift
Void
WaitMessage
While
Write
WriteFile



