# Beam_blockage_radar_Thai
โค้ดไพธอนสำหรับใช้ในการวิเคราะห์ลำบีมของเรดาร์ตรวจอากาศ ว่ามีการบดบังโดยภูมิประเทศรอบข้างอย่างไรหรือไม่ ใช้พิจารณาเรดาร์ของกรมอุตุนิยมวิทยา โดยมีกรณีศึกษาการย้ายเรดาร์เขาเขียวไปสตอ.ปราจีนบุรี ก่อนย้ายต้องมีการวิเคราะห์ว่าสถานีเดิมกับสถานีใหม่ มีความแตกต่างของการสังเกตการณ์จากลำบีมในแต่ละมุมยกอย่างไร โค้ดดังกล่าวนี้ดัดแปลงมาจาก ไลบราลีเรดาร์รหัสเปิด wradlib สามารถศึกษาเพิ่มเติมได้จาก https://debug-docs.readthedocs.io/en/test/notebooks/beamblockage/wradlib_beamblock.html นอกจากนี้ยังได้มีการนำโค้ดดังกล่าวมาใช้ในงานวิจัยในการพิจารณาบดบังของลำบีม ก่อนทำการวิเคราะห์ข้อมูลเรดาร์ตรวจอากาศของกรมอุตุนิยมวิทยา ผู้สนใจสามารถศึกษาอ่านผลงานวิจัยของ รองศาสตราจารย์ ดร.นัฐพล มหาวิค ได้จาก https://www.scopus.com/authid/detail.uri?authorId=55583236600 หรือ อีเมล nattaponm@nu.ac.th

อ่านบทความวิจัยเรื่องนี้ได้จาก https://www.researchgate.net/publication/386567714_Spatial_Measurement_Quality_of_Ground-Based_Weather_Radar_Using_Surrounding_Terrain_with_Open-Source_Radar_Library


In Eng:
This Python code is designed to analyze the beam propagation of weather radar systems and assess whether it is obstructed by surrounding terrain. The analysis focuses on the radar systems operated by the Thai Meteorological Department (TMD), with a case study comparing the relocation of the Khao Khiao radar to Prachinburi. Before relocation, it is crucial to evaluate how the beam blockage differs between the original and new stations at various elevation angles.

The code is adapted from the open-source radar library wradlib, which provides advanced tools for analyzing beam propagation and blockage effects. More details on wradlib's beam blockage analysis can be found here:
https://debug-docs.readthedocs.io/en/test/notebooks/beamblockage/wradlib_beamblock.html.

This methodology has also been applied in research analyzing beam blockage effects before conducting radar data interpretation for the Thai Meteorological Department's weather radar network. Those interested in further details can explore the research work of Associate Professor Dr. Nattapon Mahavik via Scopus:
https://www.scopus.com/authid/detail.uri?authorId=55583236600
or contact him via email: nattaponm@nu.ac.th.

Read the full research article here:
https://www.researchgate.net/publication/386567714_Spatial_Measurement_Quality_of_Ground-Based_Weather_Radar_Using_Surrounding_Terrain_with_Open-Source_Radar_Library.
