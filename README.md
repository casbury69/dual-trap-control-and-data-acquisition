# dual-trap-control-and-data-acquisition

Asbury Lab software for laser trap control and data acquisition.

Please see the Wiki (https://github.com/casbury69/dual-trap-control-and-data-acquisition/wiki) for more information about this software.

ForceClamp.llb > DoubleTrapForceClamp.vi -- This is the main program (virtual instrument) we use for dual-trap control and data acquisition.  All the other programs (virtual instruments) listed below are subroutines used by DoubleTrapForceClamp.vi.

ForceClamp.llb
		MakeDateDir.vi
		GetCoupledForcesForDoubleTrap.vi
		ProjectionInDirOfForce.vi
		GetSeparationXaxisOnly.vi
		GetMoveXaxisOnly.vi
		CheckStageLimits.vi
		GetMean&LPfilteredCoords.vi
		DecimateDualTrapData.vi
		AddUnloadedBeadPosToCalFile.vi
		CommentsDialog.vi

CalibratePSD.llb
	CircleSetup.vi
	Calib+RotVoltArray.vi

ConfigFile.llb
	Read Stiffness Calibration Estimates.vi
	Read Position Calibration Coefficients.vi

ChipsUserModPIcommands.vi
	userPOS?_1axis.vi
	userPOS?.vi
	userMOV_1axis.vi
	userMOV.vi

Normalize Maud's PSD Signals.vi
Normalize PSD Signals.vi
