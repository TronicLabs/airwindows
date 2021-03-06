cmake_minimum_required(VERSION 3.9)
project(airwindows_ports)

set(CMAKE_CXX_STANDARD 14)
add_compile_options(-O2 -D__cdecl=)

include(Helpers.cmake)

add_subdirectory(include/vstsdk)
add_airwindows_plugin(Acceleration)
add_airwindows_plugin(AtmosphereBuss)
add_airwindows_plugin(AtmophereChannel)
add_airwindows_plugin(Aura)
add_airwindows_plugin(BitShiftGain)
add_airwindows_plugin(C5RawBuss)
add_airwindows_plugin(C5RawChannel)
add_airwindows_plugin(Channel5)
add_airwindows_plugin(CrunchyGrooveWear)
add_airwindows_plugin(ElectroHat)
add_airwindows_plugin(EQ)
add_airwindows_plugin(GrooveWear)
add_airwindows_plugin(HardVacuum)
add_airwindows_plugin(NonlinearSpace)
add_airwindows_plugin(OneCornerClip)
add_airwindows_plugin(PDBuss)
add_airwindows_plugin(PDChannel)
add_airwindows_plugin(PurestConsoleBuss)
add_airwindows_plugin(PurestConsoleChannel)
add_airwindows_plugin(PurestDrive)
add_airwindows_plugin(PurestGain)
add_airwindows_plugin(Slew)
add_airwindows_plugin(Slew2)
add_airwindows_plugin(SlewOnly)
add_airwindows_plugin(TPDFDither)
add_airwindows_plugin(VoiceOfTheStarship)
add_airwindows_plugin(Wider)
