## Assembly report for Vanara.PInvoke.Shared.dll
### Classes
Class | Description
---- | ----
AssociateAttribute | Associates a Guid with an element.
CoTaskMemStringMarshaler | Marshals strings that are allocated by native code and must be freed using CoTaskMemFree after use.
FunctionHelper | 
HANDLE | Base class for all native handles.
IEnumFromIndexer<T> | Creates an enumerable class from a counter and an indexer. Useful if a class doesn't support `IEnumerable` or <see cref="T:System.Collections.Generic.IEnumerable`1" /> like some COM objects.
IEnumFromNext<T> | Creates an enumerable class from a get next method and a reset method. Useful if a class doesn't support `IEnumerable` or <see cref="T:System.Collections.Generic.IEnumerable`1" /> like some COM objects.
Lib | Holds string values for all used external API libraries.
Macros | Platform invokable enumerated types, constants and functions from windows.h
NullTermStringArrayMarshaler | 
OBJECT_TYPE_LIST | The <c>OBJECT_TYPE_LIST</c> structure identifies an object type element in a hierarchy of object types. The AccessCheckByType functions use an array of <c>OBJECT_TYPE_LIST</c> structures to define a hierarchy of an object and its subobjects, such as property sets and properties.
OverlappedAsync | Helper methods to work with asynchronous methods using `NativeOverlapped`.
OverlappedAsyncResult | Holds all pertinent information for handling results and errors in an overlapped set of method calls.
PInvokeDataAttribute | Captures information about P/Invoke calls.
PRECT | Defines the coordinates of the upper-left and lower-right corners of a rectangle.
PtrFunc<T> | 
SafeElementArray<T> | A safe unmanaged array of structures allocated on the global heap with a prefix type (usually a uint or int) that determines the count of elements.
SafeNativeArray<T> | A safe unmanaged array of structures allocated on the global heap. Array size determined by allocated memory size divided by size of structure.
SafeResourceId | Represents a system resource name that can identify as a string, integer, or pointer.
SBFunc<T> | 
SECURITY_ATTRIBUTES | The SECURITY_ATTRIBUTES structure contains the security descriptor for an object and specifies whether the handle retrieved by specifying this structure is inheritable. This structure provides security settings for objects created by various functions, such as CreateFile, CreatePipe, CreateProcess, RegCreateKeyEx, or RegSaveKeyEx.
SizeFunc<T> | 
TryGetNext | Delegate that gets the next value in an enumeration and returns true or returns false to indicate there are no more items in the enumeration.
WIN32_FIND_DATA | Contains information about the file that is found by the FindFirstFile, FindFirstFileEx, or FindNextFile function.
### Structures
Struct | Description
---- | ----
COLORREF | The COLORREF value is used to specify an RGB color in the form <c>0x00bbggrr</c>.
HACCEL | Provides a handle to an accelator table.
HBITMAP | Provides a handle to a bitmap.
HBRUSH | Provides a handle to a drawing brush.
HCURSOR | Provides a handle to a Windows cursor.
HDC | Provides a handle to a graphic device context.
HDESK | Provides a handle to a desktop.
HDPA | Provides a handle to a DPA.
HDROP | Provides a handle to a Windows drop operation.
HDSA | Provides a handle to a DSA.
HDWP | Provides a handle to a deferred windows position.
HENHMETAFILE | Provides a handle to an enhanced metafile.
HFILE | Provides a handle to a file.
HFONT | Provides a handle to a font.
HGDIOBJ | Provides a handle to a graphic device object.
HICON | Provides a handle to a Windows icon.
HIMAGELIST | Provides a handle to a Windows image list.
HINSTANCE | Provides a handle to a module or library instance.
HKEY | Provides a handle to a Windows registry key.
HMENU | Provides a handle to a menu.
HMETAFILE | Provides a handle to a metafile.
HMONITOR | Provides a handle to a monitor.
HPALETTE | Provides a handle to a palette.
HPEN | Provides a handle to a drawing pen.
HPROCESS | Provides a handle to a process.
HPROPSHEET | Provides a handle to a Windows property sheet.
HPROPSHEETPAGE | Provides a handle to a property sheet page.
HRESULT | Formal replacement for the Windows HRESULT definition. In windows.h, it is a defined UINT value. For .NET, this class strongly types the value.
HRGN | Provides a handle to a drawing region.
HTHEME | Provides a handle to a Windows theme.
HTHREAD | Provides a handle to a thread.
HTHUMBNAIL | Provides a handle to a Windows thumbnail.
HTOKEN | Provides a handle to an access token .
HWINSTA | Provides a handle to a windows station.
HWND | Provides a handle to a window or dialog.
LOGFONT | The LOGFONT structure defines the attributes of a font.
MSG | Contains message information from a thread's message queue.
NTStatus | Formal replacement for the Windows NTStatus definition. In ntstatus.h, it is a defined UINT value. For .NET, this class strongly types the value.
OBJECT_TYPE_LIST | The <c>OBJECT_TYPE_LIST</c> structure identifies an object type element in a hierarchy of object types. The AccessCheckByType functions use an array of <c>OBJECT_TYPE_LIST</c> structures to define a hierarchy of an object and its subobjects, such as property sets and properties.
PACE | Provides a pointer to an access control entry.
PACL | Provides a pointer to an access control list.
POINTS | The POINTS structure defines the coordinates of a point.
PRECT | Defines the coordinates of the upper-left and lower-right corners of a rectangle.
PSECURITY_DESCRIPTOR | Provides a pointer to a security descriptor.
PSID | Provides a pointer to a security identifier.
RECT | Defines the coordinates of the upper-left and lower-right corners of a rectangle.
ResourceId | Helper structure to use for a pointer that can morph into a string, pointer or integer.
SECURITY_ATTRIBUTES | The SECURITY_ATTRIBUTES structure contains the security descriptor for an object and specifies whether the handle retrieved by specifying this structure is inheritable. This structure provides security settings for objects created by various functions, such as CreateFile, CreatePipe, CreateProcess, RegCreateKeyEx, or RegSaveKeyEx.
SIZE | The <c>SIZE</c> structure specifies the width and height of a rectangle.
SizeT | Managed instance of the SIZE_T type.
SYSTEMTIME | Specifies a date and time, using individual members for the month, day, year, weekday, hour, minute, second, and millisecond. The time is either in coordinated universal time (UTC) or local time, depending on the function that is being called.
WIN32_FIND_DATA | Contains information about the file that is found by the FindFirstFile, FindFirstFileEx, or FindNextFile function.
Win32Error | Represents a Win32 Error Code. This can be used in place of a return value.
### Enumerations
Enum | Description | Values
---- | ---- | ----
ACCESS_MASK | Access flags. | SPECIFIC_RIGHTS_ALL, DELETE, STANDARD_RIGHTS_EXECUTE, STANDARD_RIGHTS_READ, READ_CONTROL, STANDARD_RIGHTS_WRITE, WRITE_DAC, WRITE_OWNER, STANDARD_RIGHTS_REQUIRED, SYNCHRONIZE, STANDARD_RIGHTS_ALL, ACCESS_SYSTEM_SECURITY, MAXIMUM_ALLOWED, GENERIC_ALL, GENERIC_EXECUTE, GENERIC_WRITE, GENERIC_READ
DrawTextFlags | The formatting options for DrawText. | DT_TOP, DT_LEFT, DT_CENTER, DT_RIGHT, DT_VCENTER, DT_BOTTOM, DT_WORDBREAK, DT_SINGLELINE, DT_EXPANDTABS, DT_TABSTOP, DT_NOCLIP, DT_EXTERNALLEADING, DT_CALCRECT, DT_NOPREFIX, DT_INTERNAL, DT_EDITCONTROL, DT_PATH_ELLIPSIS, DT_END_ELLIPSIS, DT_MODIFYSTRING, DT_RTLREADING, DT_WORD_ELLIPSIS, DT_NOFULLWIDTHCHARBREAK, DT_HIDEPREFIX, DT_PREFIXONLY
FacilityCode | Enumeration of facility codes | FACILITY_NULL, FACILITY_RPC, FACILITY_DISPATCH, FACILITY_STORAGE, FACILITY_ITF, FACILITY_WIN32, FACILITY_WINDOWS, FACILITY_SECURITY, FACILITY_SSPI, FACILITY_CONTROL, FACILITY_CERT, FACILITY_INTERNET, FACILITY_MEDIASERVER, FACILITY_MSMQ, FACILITY_SETUPAPI, FACILITY_SCARD, FACILITY_COMPLUS, FACILITY_AAF, FACILITY_URT, FACILITY_ACS, FACILITY_DPLAY, FACILITY_UMI, FACILITY_SXS, FACILITY_WINDOWS_CE, FACILITY_HTTP, FACILITY_USERMODE_COMMONLOG, FACILITY_USERMODE_FILTER_MANAGER, FACILITY_BACKGROUNDCOPY, FACILITY_CONFIGURATION, FACILITY_STATE_MANAGEMENT, FACILITY_METADIRECTORY, FACILITY_WINDOWSUPDATE, FACILITY_DIRECTORYSERVICE, FACILITY_GRAPHICS, FACILITY_SHELL, FACILITY_TPM_SERVICES, FACILITY_TPM_SOFTWARE, FACILITY_PLA, FACILITY_FVE, FACILITY_FWP, FACILITY_WINRM, FACILITY_NDIS, FACILITY_USERMODE_HYPERVISOR, FACILITY_CMI, FACILITY_USERMODE_VIRTUALIZATION, FACILITY_USERMODE_VOLMGR, FACILITY_BCD, FACILITY_USERMODE_VHD, FACILITY_SDIAG, FACILITY_WEBSERVICES, FACILITY_WINDOWS_DEFENDER, FACILITY_OPC
FacilityCode | Enumeration of facility codes | FACILITY_NULL, FACILITY_DEBUGGER, FACILITY_RPC_RUNTIME, FACILITY_RPC_STUBS, FACILITY_IO_ERROR_CODE, FACILITY_CODCLASS_ERROR_CODE, FACILITY_NTWIN32, FACILITY_NTCERT, FACILITY_NTSSPI, FACILITY_TERMINAL_SERVER, FACILTIY_MUI_ERROR_CODE, FACILITY_USB_ERROR_CODE, FACILITY_HID_ERROR_CODE, FACILITY_FIREWIRE_ERROR_CODE, FACILITY_CLUSTER_ERROR_CODE, FACILITY_ACPI_ERROR_CODE, FACILITY_SXS_ERROR_CODE, FACILITY_TRANSACTION, FACILITY_COMMONLOG, FACILITY_VIDEO, FACILITY_FILTER_MANAGER, FACILITY_MONITOR, FACILITY_GRAPHICS_KERNEL, FACILITY_DRIVER_FRAMEWORK, FACILITY_FVE_ERROR_CODE, FACILITY_FWP_ERROR_CODE, FACILITY_NDIS_ERROR_CODE, FACILITY_TPM, FACILITY_RTPM, FACILITY_HYPERVISOR, FACILITY_IPSEC, FACILITY_VIRTUALIZATION, FACILITY_VOLMGR, FACILITY_BCD_ERROR_CODE, FACILITY_WIN32K_NTUSER, FACILITY_WIN32K_NTGDI, FACILITY_RESUME_KEY_FILTER, FACILITY_RDBSS, FACILITY_BTH_ATT, FACILITY_SECUREBOOT, FACILITY_AUDIO_KERNEL, FACILITY_VSM, FACILITY_VOLSNAP, FACILITY_SDBUS, FACILITY_SHARED_VHDX, FACILITY_SMB, FACILITY_INTERIX, FACILITY_SPACES, FACILITY_SECURITY_CORE, FACILITY_SYSTEM_INTEGRITY, FACILITY_LICENSING, FACILITY_PLATFORM_MANIFEST, FACILITY_MAXIMUM_VALUE
FileFlagsAndAttributes | File attributes are metadata values stored by the file system on disk and are used by the system and are available to developers via various file I/O APIs. | SECURITY_ANONYMOUS, FILE_ATTRIBUTE_READONLY, FILE_ATTRIBUTE_HIDDEN, FILE_ATTRIBUTE_SYSTEM, FILE_ATTRIBUTE_DIRECTORY, FILE_ATTRIBUTE_ARCHIVE, FILE_ATTRIBUTE_DEVICE, FILE_ATTRIBUTE_NORMAL, FILE_ATTRIBUTE_TEMPORARY, FILE_ATTRIBUTE_SPARSE_FILE, FILE_ATTRIBUTE_REPARSE_POINT, FILE_ATTRIBUTE_COMPRESSED, FILE_ATTRIBUTE_OFFLINE, FILE_ATTRIBUTE_NOT_CONTENT_INDEXED, FILE_ATTRIBUTE_ENCRYPTED, FILE_ATTRIBUTE_INTEGRITY_STREAM, SECURITY_IDENTIFICATION, FILE_ATTRIBUTE_VIRTUAL, FILE_ATTRIBUTE_NO_SCRUB_DATA, SECURITY_IMPERSONATION, SECURITY_DELEGATION, FILE_ATTRIBUTE_EA, SECURITY_CONTEXT_TRACKING, FILE_FLAG_FIRST_PIPE_INSTANCE, SECURITY_EFFECTIVE_ONLY, FILE_FLAG_OPEN_NO_RECALL, SECURITY_SQOS_PRESENT, FILE_FLAG_OPEN_REPARSE_POINT, FILE_FLAG_SESSION_AWARE, FILE_FLAG_POSIX_SEMANTICS, FILE_FLAG_BACKUP_SEMANTICS, FILE_FLAG_DELETE_ON_CLOSE, FILE_FLAG_SEQUENTIAL_SCAN, FILE_FLAG_RANDOM_ACCESS, FILE_FLAG_NO_BUFFERING, FILE_FLAG_OVERLAPPED, FILE_FLAG_WRITE_THROUGH
FontFamily | Font families describe the look of a font in a general way. They are intended for specifying fonts when the exact typeface desired is not available. | FF_DONTCARE, FF_ROMAN, FF_SWISS, FF_MODERN, FF_SCRIPT, FF_DECORATIVE
FontPitch | Specifies information about the pitch, the technology, and the family of a physical font. | DEFAULT_PITCH, FIXED_PITCH, TMPF_FIXED_PITCH, VARIABLE_PITCH, TMPF_VECTOR, TMPF_TRUETYPE, MONO_FONT, TMPF_DEVICE
LogFontCharSet | The character set. | ANSI_CHARSET, DEFAULT_CHARSET, SYMBOL_CHARSET, MAC_CHARSET, SHIFTJIS_CHARSET, HANGUL_CHARSET, HANGEUL_CHARSET, JOHAB_CHARSET, GB2312_CHARSET, CHINESEBIG5_CHARSET, GREEK_CHARSET, TURKISH_CHARSET, VIETNAMESE_CHARSET, HEBREW_CHARSET, ARABIC_CHARSET, BALTIC_CHARSET, RUSSIAN_CHARSET, THAI_CHARSET, EASTEUROPE_CHARSET, OEM_CHARSET
LogFontClippingPrecision | The clipping precision defines how to clip characters that are partially outside the clipping region. | CLIP_DEFAULT_PRECIS, CLIP_CHARACTER_PRECIS, CLIP_STROKE_PRECIS, CLIP_MASK, CLIP_LH_ANGLES, CLIP_TT_ALWAYS, CLIP_DFA_OVERRIDE, CLIP_DFA_DISABLE, CLIP_EMBEDDED
LogFontOutputPrecision | The output precision. The output precision defines how closely the output must match the requested font's height, width, character orientation, escapement, pitch, and font type. | OUT_DEFAULT_PRECIS, OUT_STRING_PRECIS, OUT_CHARACTER_PRECIS, OUT_STROKE_PRECIS, OUT_TT_PRECIS, OUT_DEVICE_PRECIS, OUT_RASTER_PRECIS, OUT_TT_ONLY_PRECIS, OUT_OUTLINE_PRECIS, OUT_SCREEN_OUTLINE_PRECIS, OUT_PS_ONLY_PRECIS
LogFontOutputQuality | The output quality defines how carefully the graphics device interface (GDI) must attempt to match the logical-font attributes to those of an actual physical font. | DEFAULT_QUALITY, DRAFT_QUALITY, PROOF_QUALITY, NONANTIALIASED_QUALITY, ANTIALIASED_QUALITY, CLEARTYPE_QUALITY, CLEARTYPE_NATURAL_QUALITY
ObjectTypeListLevel | Valid values for the `level` field. | ACCESS_OBJECT_GUID, ACCESS_PROPERTY_SET_GUID, ACCESS_PROPERTY_GUID, ACCESS_MAX_LEVEL
PInvokeClient | Flags that determine the minimum supported client(s) for a P/Invoke function. | None, Windows2000, WindowsXP, WindowsXP_SP2, WindowsVista, WindowsVista_SP2, Windows7, Windows8, Windows81, Windows10
ProcessorArchitecture | Processor architecture | PROCESSOR_ARCHITECTURE_INTEL, PROCESSOR_ARCHITECTURE_MIPS, PROCESSOR_ARCHITECTURE_ALPHA, PROCESSOR_ARCHITECTURE_PPC, PROCESSOR_ARCHITECTURE_SHX, PROCESSOR_ARCHITECTURE_ARM, PROCESSOR_ARCHITECTURE_IA64, PROCESSOR_ARCHITECTURE_ALPHA64, PROCESSOR_ARCHITECTURE_MSIL, PROCESSOR_ARCHITECTURE_AMD64, PROCESSOR_ARCHITECTURE_IA32_ON_WIN64, PROCESSOR_ARCHITECTURE_NEUTRAL, PROCESSOR_ARCHITECTURE_ARM64, PROCESSOR_ARCHITECTURE_ARM32_ON_WIN64, PROCESSOR_ARCHITECTURE_UNKNOWN
ResourceType | Predefined resource types. | RT_CURSOR, RT_BITMAP, RT_ICON, RT_MENU, RT_DIALOG, RT_STRING, RT_FONTDIR, RT_FONT, RT_ACCELERATOR, RT_RCDATA, RT_MESSAGETABLE, RT_GROUP_CURSOR, RT_GROUP_ICON, RT_VERSION, RT_DLGINCLUDE, RT_PLUGPLAY, RT_VXD, RT_ANICURSOR, RT_ANIICON, RT_HTML, RT_MANIFEST
SECURITY_INFORMATION | The SECURITY_INFORMATION data type identifies the object-related security information being set or queried. This security information includes: | OWNER_SECURITY_INFORMATION, GROUP_SECURITY_INFORMATION, DACL_SECURITY_INFORMATION, SACL_SECURITY_INFORMATION, LABEL_SECURITY_INFORMATION, ATTRIBUTE_SECURITY_INFORMATION, SCOPE_SECURITY_INFORMATION, PROCESS_TRUST_LABEL_SECURITY_INFORMATION, BACKUP_SECURITY_INFORMATION, UNPROTECTED_SACL_SECURITY_INFORMATION, UNPROTECTED_DACL_SECURITY_INFORMATION, PROTECTED_SACL_SECURITY_INFORMATION, PROTECTED_DACL_SECURITY_INFORMATION
SeverityLevel | A value indicating whether an `HRESULT` is a success (Severity bit 31 equals 0). | Success, Fail
SeverityLevel | A value indicating the severity of an `NTStatus` value (bits 30-31). | STATUS_SEVERITY_SUCCESS, STATUS_SEVERITY_INFORMATIONAL, STATUS_SEVERITY_WARNING, STATUS_SEVERITY_ERROR
ShowWindowCommand | The flags that specify how an application is to be displayed when it is opened. | SW_HIDE, SW_SHOWNORMAL, SW_NORMAL, SW_SHOWMINIMIZED, SW_SHOWMAXIMIZED, SW_MAXIMIZE, SW_SHOWNOACTIVATE, SW_SHOW, SW_MINIMIZE, SW_SHOWMINNOACTIVE, SW_SHOWNA, SW_RESTORE, SW_SHOWDEFAULT, SW_FORCEMINIMIZE
STGM | The STGM constants are flags that indicate conditions for creating and deleting the object and access modes for the object. The STGM constants are included in the IStorage, IStream, and IPropertySetStorage interfaces and in the StgCreateDocfile, StgCreateStorageEx, StgCreateDocfileOnILockBytes, StgOpenStorage, and StgOpenStorageEx functions. <para> These elements are often combined using an OR operator. They are interpreted in groups as listed in the following table. It is not valid to use more than one element from a single group. | STGM_DIRECT, STGM_FAILIFTHERE, STGM_READ, STGM_WRITE, STGM_READWRITE, STGM_SHARE_EXCLUSIVE, STGM_SHARE_DENY_WRITE, STGM_SHARE_DENY_READ, STGM_SHARE_DENY_NONE, STGM_CREATE, STGM_TRANSACTED, STGM_CONVERT, STGM_PRIORITY, STGM_NOSCRATCH, STGM_NOSNAPSHOT, STGM_DIRECT_SWMR, STGM_DELETEONRELEASE, STGM_SIMPLE
SystemColorIndex | Color index used to get a system color from <c>GetSysColor</c>. | COLOR_SCROLLBAR, COLOR_BACKGROUND, COLOR_DESKTOP, COLOR_ACTIVECAPTION, COLOR_INACTIVECAPTION, COLOR_MENU, COLOR_WINDOW, COLOR_WINDOWFRAME, COLOR_MENUTEXT, COLOR_WINDOWTEXT, COLOR_CAPTIONTEXT, COLOR_ACTIVEBORDER, COLOR_INACTIVEBORDER, COLOR_APPWORKSPACE, COLOR_HIGHLIGHT, COLOR_HIGHLIGHTTEXT, COLOR_BTNFACE, COLOR_3DFACE, COLOR_BTNSHADOW, COLOR_3DSHADOW, COLOR_GRAYTEXT, COLOR_BTNTEXT, COLOR_INACTIVECAPTIONTEXT, COLOR_3DHILIGHT, COLOR_BTNHILIGHT, COLOR_BTNHIGHLIGHT, COLOR_3DHIGHLIGHT, COLOR_3DDKSHADOW, COLOR_3DLIGHT, COLOR_INFOTEXT, COLOR_INFOBK, COLOR_HOTLIGHT, COLOR_GRADIENTACTIVECAPTION, COLOR_GRADIENTINACTIVECAPTION, COLOR_MENUHILIGHT, COLOR_MENUBAR
SystemShutDownReason | Flags used in the ExitWindowsEx, InitiateShutdown and InitiateSystemShutdownEx functions. | SHTDN_REASON_MAJOR_OTHER, SHTDN_REASON_MINOR_OTHER, SHTDN_REASON_MAJOR_NONE, SHTDN_REASON_MINOR_MAINTENANCE, SHTDN_REASON_MINOR_INSTALLATION, SHTDN_REASON_MINOR_UPGRADE, SHTDN_REASON_MINOR_RECONFIG, SHTDN_REASON_MINOR_HUNG, SHTDN_REASON_MINOR_UNSTABLE, SHTDN_REASON_MINOR_DISK, SHTDN_REASON_MINOR_PROCESSOR, SHTDN_REASON_MINOR_NETWORKCARD, SHTDN_REASON_MINOR_POWER_SUPPLY, SHTDN_REASON_MINOR_CORDUNPLUGGED, SHTDN_REASON_MINOR_ENVIRONMENT, SHTDN_REASON_MINOR_HARDWARE_DRIVER, SHTDN_REASON_MINOR_OTHERDRIVER, SHTDN_REASON_MINOR_BLUESCREEN, SHTDN_REASON_MINOR_SERVICEPACK, SHTDN_REASON_MINOR_HOTFIX, SHTDN_REASON_MINOR_SECURITYFIX, SHTDN_REASON_MINOR_SECURITY, SHTDN_REASON_MINOR_NETWORK_CONNECTIVITY, SHTDN_REASON_MINOR_WMI, SHTDN_REASON_MINOR_SERVICEPACK_UNINSTALL, SHTDN_REASON_MINOR_HOTFIX_UNINSTALL, SHTDN_REASON_MINOR_SECURITYFIX_UNINSTALL, SHTDN_REASON_MINOR_MMC, SHTDN_REASON_MINOR_SYSTEMRESTORE, SHTDN_REASON_MINOR_TERMSRV, SHTDN_REASON_MINOR_DC_PROMOTION, SHTDN_REASON_MINOR_DC_DEMOTION, SHTDN_REASON_MINOR_NONE, SHTDN_REASON_UNKNOWN, SHTDN_REASON_MAJOR_HARDWARE, SHTDN_REASON_MAJOR_OPERATINGSYSTEM, SHTDN_REASON_MAJOR_SOFTWARE, SHTDN_REASON_MAJOR_APPLICATION, SHTDN_REASON_MAJOR_SYSTEM, SHTDN_REASON_MAJOR_POWER, SHTDN_REASON_MAJOR_LEGACY_API, SHTDN_REASON_FLAG_COMMENT_REQUIRED, SHTDN_REASON_FLAG_DIRTY_PROBLEM_ID_REQUIRED, SHTDN_REASON_FLAG_CLEAN_UI, SHTDN_REASON_FLAG_DIRTY_UI, SHTDN_REASON_FLAG_MOBILE_UI_RESERVED, SHTDN_REASON_FLAG_USER_DEFINED, SHTDN_REASON_FLAG_PLANNED, SHTDN_REASON_LEGACY_API
