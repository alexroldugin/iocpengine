# iocpengine
iocpengine

�������� �����-�� ����� �� ��������� ��������� � ����� FabianKantereit.
���� ����� ���� - ����� ���������� (IOCP): https://habrahabr.ru/post/59282/
��������� ������� �� ��� ����:
http://www.diocp.org/
https://github.com/ymofen/diocp-v5
https://github.com/ymofen

FastMM4: https://github.com/pleriche/FastMM4/

��������� FastMM4:

{ Group the options you use for release and debug versions below }
{$IFDEF Release}
{ Specify the options you use for release versions below }
{$DEFINE Align16Bytes}
{$DEFINE UseCustomFixedSizeMoveRoutines}
{$DEFINE UseCustomVariableSizeMoveRoutines}
{$UNDEF NeverUninstall}
{$UNDEF NoMessageBoxes}
{$UNDEF CheckHeapForCorruption}
{$UNDEF DetectMMOperationsAfterUninstall}
{$UNDEF FullDebugMode}
{$UNDEF RawStackTraces}
{$UNDEF CatchUseOfFreedInterfaces}
{$UNDEF LogErrorsToFile}
{$UNDEF LogMemoryLeakDetailToFile}
{$UNDEF ClearLogFileOnStartup}
{$UNDEF AlwaysAllocateTopDown}
{$DEFINE DisableLoggingOfMemoryDumps}
{$UNDEF SuppressFreeMemErrorsInsideException}
{$UNDEF EnableMemoryLeakReporting}
{$UNDEF ClearMemoryBeforeReturningToOS}
{$UNDEF AlwaysClearFreedMemory}
{$ELSE}
{ Specify the options you use for debugging below }
{$DEFINE NeverUninstall}
{$DEFINE NoMessageBoxes}
{$DEFINE CheckHeapForCorruption}
{$DEFINE DetectMMOperationsAfterUninstall}
{$DEFINE FullDebugMode}
{$DEFINE RawStackTraces}
{$DEFINE CatchUseOfFreedInterfaces}
{$DEFINE LogErrorsToFile}
{$DEFINE LogMemoryLeakDetailToFile}
{$DEFINE ClearLogFileOnStartup}
{$DEFINE AlwaysAllocateTopDown}
{$DEFINE DisableLoggingOfMemoryDumps}
{$DEFINE SuppressFreeMemErrorsInsideException}
{$DEFINE EnableMemoryLeakReporting}
{$DEFINE ClearMemoryBeforeReturningToOS}
{$DEFINE AlwaysClearFreedMemory}
{$ENDIF}