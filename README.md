Use Unicode's [private use
area](https://en.wikipedia.org/wiki/Private_Use_Areas) to provide standard
glyphs for use on the linux command line.

We use the `U+E000..U+F8FF` range, with 6,400 possible glyphs. We try not to
include brands or specific tools. The glyph for "github" for example, might be
better served by a generic VCS glyph.

The goal is to create a standard for unicode icon glyphs that isn't as strict as
unicode, and that can be made generally available to developers.

Glyphs representing types of tools (eg: and eyedropper tool) or specific
concepts (eg: a difference operation on a set) are welcome, as long as they're
clear.
The goal is to create "timeless" glyphs instead of glyphs for a whole bunch of
different applications/products that may not exist in 50 years.

Brand-icon glyphs and product glyphs are fine, but aren't the primary focus of this project.
They should live in the `U+F0000..U+FFFFD` namespace, called `Supplemental Private Use
Area-A`. If you'd like to register a code point for the use of a brand or a tool,
you're welcome to do so here. Just include an appropriate SVG in the `brands/`
folder, starting with a unique 7-digit number.

`Supplemental Private Use Area-B` will be reservered for large third-party
custom icon sets.

The glyphs from 0000-0257 are built from the MIT-licensed [feather
icons](https://feathericons.com/).


# Glyphs

|Symbol|Char|Name|Hex|File|
|:----:|:--:|----|---|----|
|![](featherIcons/0000_activity.svg)||activity|0xe000|featherIcons/0000_activity.svg|
|![](featherIcons/0001_airplay.svg)||airplay|0xe001|featherIcons/0001_airplay.svg|
|![](featherIcons/0002_alert-circle.svg)||alert-circle|0xe002|featherIcons/0002_alert-circle.svg|
|![](featherIcons/0003_alert-octagon.svg)||alert-octagon|0xe003|featherIcons/0003_alert-octagon.svg|
|![](featherIcons/0004_alert-triangle.svg)||alert-triangle|0xe004|featherIcons/0004_alert-triangle.svg|
|![](featherIcons/0005_align-center.svg)||align-center|0xe005|featherIcons/0005_align-center.svg|
|![](featherIcons/0006_align-justify.svg)||align-justify|0xe006|featherIcons/0006_align-justify.svg|
|![](featherIcons/0007_align-left.svg)||align-left|0xe007|featherIcons/0007_align-left.svg|
|![](featherIcons/0008_align-right.svg)||align-right|0xe008|featherIcons/0008_align-right.svg|
|![](featherIcons/0009_anchor.svg)||anchor|0xe009|featherIcons/0009_anchor.svg|
|![](featherIcons/0010_aperture.svg)||aperture|0xe00a|featherIcons/0010_aperture.svg|
|![](featherIcons/0011_archive.svg)||archive|0xe00b|featherIcons/0011_archive.svg|
|![](featherIcons/0012_arrow-down-circle.svg)||arrow-down-circle|0xe00c|featherIcons/0012_arrow-down-circle.svg|
|![](featherIcons/0013_arrow-down-left.svg)||arrow-down-left|0xe00d|featherIcons/0013_arrow-down-left.svg|
|![](featherIcons/0014_arrow-down-right.svg)||arrow-down-right|0xe00e|featherIcons/0014_arrow-down-right.svg|
|![](featherIcons/0015_arrow-down.svg)||arrow-down|0xe00f|featherIcons/0015_arrow-down.svg|
|![](featherIcons/0016_arrow-left-circle.svg)||arrow-left-circle|0xe010|featherIcons/0016_arrow-left-circle.svg|
|![](featherIcons/0017_arrow-left.svg)||arrow-left|0xe011|featherIcons/0017_arrow-left.svg|
|![](featherIcons/0018_arrow-right-circle.svg)||arrow-right-circle|0xe012|featherIcons/0018_arrow-right-circle.svg|
|![](featherIcons/0019_arrow-right.svg)||arrow-right|0xe013|featherIcons/0019_arrow-right.svg|
|![](featherIcons/0020_arrow-up-circle.svg)||arrow-up-circle|0xe014|featherIcons/0020_arrow-up-circle.svg|
|![](featherIcons/0021_arrow-up-left.svg)||arrow-up-left|0xe015|featherIcons/0021_arrow-up-left.svg|
|![](featherIcons/0022_arrow-up-right.svg)||arrow-up-right|0xe016|featherIcons/0022_arrow-up-right.svg|
|![](featherIcons/0023_arrow-up.svg)||arrow-up|0xe017|featherIcons/0023_arrow-up.svg|
|![](featherIcons/0024_at-sign.svg)||at-sign|0xe018|featherIcons/0024_at-sign.svg|
|![](featherIcons/0025_award.svg)||award|0xe019|featherIcons/0025_award.svg|
|![](featherIcons/0026_bar-chart-2.svg)||bar-chart-2|0xe01a|featherIcons/0026_bar-chart-2.svg|
|![](featherIcons/0027_bar-chart.svg)||bar-chart|0xe01b|featherIcons/0027_bar-chart.svg|
|![](featherIcons/0028_battery-charging.svg)||battery-charging|0xe01c|featherIcons/0028_battery-charging.svg|
|![](featherIcons/0029_battery.svg)||battery|0xe01d|featherIcons/0029_battery.svg|
|![](featherIcons/0030_bell-off.svg)||bell-off|0xe01e|featherIcons/0030_bell-off.svg|
|![](featherIcons/0031_bell.svg)||bell|0xe01f|featherIcons/0031_bell.svg|
|![](featherIcons/0032_bluetooth.svg)||bluetooth|0xe020|featherIcons/0032_bluetooth.svg|
|![](featherIcons/0033_bold.svg)||bold|0xe021|featherIcons/0033_bold.svg|
|![](featherIcons/0034_book-open.svg)||book-open|0xe022|featherIcons/0034_book-open.svg|
|![](featherIcons/0035_book.svg)||book|0xe023|featherIcons/0035_book.svg|
|![](featherIcons/0036_bookmark.svg)||bookmark|0xe024|featherIcons/0036_bookmark.svg|
|![](featherIcons/0037_box.svg)||box|0xe025|featherIcons/0037_box.svg|
|![](featherIcons/0038_briefcase.svg)||briefcase|0xe026|featherIcons/0038_briefcase.svg|
|![](featherIcons/0039_calendar.svg)||calendar|0xe027|featherIcons/0039_calendar.svg|
|![](featherIcons/0040_camera-off.svg)||camera-off|0xe028|featherIcons/0040_camera-off.svg|
|![](featherIcons/0041_camera.svg)||camera|0xe029|featherIcons/0041_camera.svg|
|![](featherIcons/0042_cast.svg)||cast|0xe02a|featherIcons/0042_cast.svg|
|![](featherIcons/0043_check-circle.svg)||check-circle|0xe02b|featherIcons/0043_check-circle.svg|
|![](featherIcons/0044_check-square.svg)||check-square|0xe02c|featherIcons/0044_check-square.svg|
|![](featherIcons/0045_check.svg)||check|0xe02d|featherIcons/0045_check.svg|
|![](featherIcons/0046_chevron-down.svg)||chevron-down|0xe02e|featherIcons/0046_chevron-down.svg|
|![](featherIcons/0047_chevron-left.svg)||chevron-left|0xe02f|featherIcons/0047_chevron-left.svg|
|![](featherIcons/0048_chevron-right.svg)||chevron-right|0xe030|featherIcons/0048_chevron-right.svg|
|![](featherIcons/0049_chevron-up.svg)||chevron-up|0xe031|featherIcons/0049_chevron-up.svg|
|![](featherIcons/0050_chevrons-down.svg)||chevrons-down|0xe032|featherIcons/0050_chevrons-down.svg|
|![](featherIcons/0051_chevrons-left.svg)||chevrons-left|0xe033|featherIcons/0051_chevrons-left.svg|
|![](featherIcons/0052_chevrons-right.svg)||chevrons-right|0xe034|featherIcons/0052_chevrons-right.svg|
|![](featherIcons/0053_chevrons-up.svg)||chevrons-up|0xe035|featherIcons/0053_chevrons-up.svg|
|![](featherIcons/0054_circle.svg)||circle|0xe036|featherIcons/0054_circle.svg|
|![](featherIcons/0055_clipboard.svg)||clipboard|0xe037|featherIcons/0055_clipboard.svg|
|![](featherIcons/0056_clock.svg)||clock|0xe038|featherIcons/0056_clock.svg|
|![](featherIcons/0057_cloud-drizzle.svg)||cloud-drizzle|0xe039|featherIcons/0057_cloud-drizzle.svg|
|![](featherIcons/0058_cloud-lightning.svg)||cloud-lightning|0xe03a|featherIcons/0058_cloud-lightning.svg|
|![](featherIcons/0059_cloud-off.svg)||cloud-off|0xe03b|featherIcons/0059_cloud-off.svg|
|![](featherIcons/0060_cloud-rain.svg)||cloud-rain|0xe03c|featherIcons/0060_cloud-rain.svg|
|![](featherIcons/0061_cloud-snow.svg)||cloud-snow|0xe03d|featherIcons/0061_cloud-snow.svg|
|![](featherIcons/0062_cloud.svg)||cloud|0xe03e|featherIcons/0062_cloud.svg|
|![](featherIcons/0063_code.svg)||code|0xe03f|featherIcons/0063_code.svg|
|![](featherIcons/0064_command.svg)||command|0xe040|featherIcons/0064_command.svg|
|![](featherIcons/0065_compass.svg)||compass|0xe041|featherIcons/0065_compass.svg|
|![](featherIcons/0066_copy.svg)||copy|0xe042|featherIcons/0066_copy.svg|
|![](featherIcons/0067_corner-down-left.svg)||corner-down-left|0xe043|featherIcons/0067_corner-down-left.svg|
|![](featherIcons/0068_corner-down-right.svg)||corner-down-right|0xe044|featherIcons/0068_corner-down-right.svg|
|![](featherIcons/0069_corner-left-down.svg)||corner-left-down|0xe045|featherIcons/0069_corner-left-down.svg|
|![](featherIcons/0070_corner-left-up.svg)||corner-left-up|0xe046|featherIcons/0070_corner-left-up.svg|
|![](featherIcons/0071_corner-right-down.svg)||corner-right-down|0xe047|featherIcons/0071_corner-right-down.svg|
|![](featherIcons/0072_corner-right-up.svg)||corner-right-up|0xe048|featherIcons/0072_corner-right-up.svg|
|![](featherIcons/0073_corner-up-left.svg)||corner-up-left|0xe049|featherIcons/0073_corner-up-left.svg|
|![](featherIcons/0074_corner-up-right.svg)||corner-up-right|0xe04a|featherIcons/0074_corner-up-right.svg|
|![](featherIcons/0075_cpu.svg)||cpu|0xe04b|featherIcons/0075_cpu.svg|
|![](featherIcons/0076_credit-card.svg)||credit-card|0xe04c|featherIcons/0076_credit-card.svg|
|![](featherIcons/0077_crop.svg)||crop|0xe04d|featherIcons/0077_crop.svg|
|![](featherIcons/0078_crosshair.svg)||crosshair|0xe04e|featherIcons/0078_crosshair.svg|
|![](featherIcons/0079_database.svg)||database|0xe04f|featherIcons/0079_database.svg|
|![](featherIcons/0080_delete.svg)||delete|0xe050|featherIcons/0080_delete.svg|
|![](featherIcons/0081_disc.svg)||disc|0xe051|featherIcons/0081_disc.svg|
|![](featherIcons/0082_dollar-sign.svg)||dollar-sign|0xe052|featherIcons/0082_dollar-sign.svg|
|![](featherIcons/0083_download-cloud.svg)||download-cloud|0xe053|featherIcons/0083_download-cloud.svg|
|![](featherIcons/0084_download.svg)||download|0xe054|featherIcons/0084_download.svg|
|![](featherIcons/0085_droplet.svg)||droplet|0xe055|featherIcons/0085_droplet.svg|
|![](featherIcons/0086_edit-2.svg)||edit-2|0xe056|featherIcons/0086_edit-2.svg|
|![](featherIcons/0087_edit-3.svg)||edit-3|0xe057|featherIcons/0087_edit-3.svg|
|![](featherIcons/0088_edit.svg)||edit|0xe058|featherIcons/0088_edit.svg|
|![](featherIcons/0089_external-link.svg)||external-link|0xe059|featherIcons/0089_external-link.svg|
|![](featherIcons/0090_eye-off.svg)||eye-off|0xe05a|featherIcons/0090_eye-off.svg|
|![](featherIcons/0091_eye.svg)||eye|0xe05b|featherIcons/0091_eye.svg|
|![](featherIcons/0092_fast-forward.svg)||fast-forward|0xe05c|featherIcons/0092_fast-forward.svg|
|![](featherIcons/0093_feather.svg)||feather|0xe05d|featherIcons/0093_feather.svg|
|![](featherIcons/0094_file-minus.svg)||file-minus|0xe05e|featherIcons/0094_file-minus.svg|
|![](featherIcons/0095_file-plus.svg)||file-plus|0xe05f|featherIcons/0095_file-plus.svg|
|![](featherIcons/0096_file-text.svg)||file-text|0xe060|featherIcons/0096_file-text.svg|
|![](featherIcons/0097_file.svg)||file|0xe061|featherIcons/0097_file.svg|
|![](featherIcons/0098_film.svg)||film|0xe062|featherIcons/0098_film.svg|
|![](featherIcons/0099_filter.svg)||filter|0xe063|featherIcons/0099_filter.svg|
|![](featherIcons/0100_flag.svg)||flag|0xe064|featherIcons/0100_flag.svg|
|![](featherIcons/0101_folder-minus.svg)||folder-minus|0xe065|featherIcons/0101_folder-minus.svg|
|![](featherIcons/0102_folder-plus.svg)||folder-plus|0xe066|featherIcons/0102_folder-plus.svg|
|![](featherIcons/0103_folder.svg)||folder|0xe067|featherIcons/0103_folder.svg|
|![](featherIcons/0104_gift.svg)||gift|0xe068|featherIcons/0104_gift.svg|
|![](featherIcons/0105_git-branch.svg)||git-branch|0xe069|featherIcons/0105_git-branch.svg|
|![](featherIcons/0106_git-commit.svg)||git-commit|0xe06a|featherIcons/0106_git-commit.svg|
|![](featherIcons/0107_git-merge.svg)||git-merge|0xe06b|featherIcons/0107_git-merge.svg|
|![](featherIcons/0108_git-pull-request.svg)||git-pull-request|0xe06c|featherIcons/0108_git-pull-request.svg|
|![](featherIcons/0109_globe.svg)||globe|0xe06d|featherIcons/0109_globe.svg|
|![](featherIcons/0110_grid.svg)||grid|0xe06e|featherIcons/0110_grid.svg|
|![](featherIcons/0111_hard-drive.svg)||hard-drive|0xe06f|featherIcons/0111_hard-drive.svg|
|![](featherIcons/0112_hash.svg)||hash|0xe070|featherIcons/0112_hash.svg|
|![](featherIcons/0113_headphones.svg)||headphones|0xe071|featherIcons/0113_headphones.svg|
|![](featherIcons/0114_heart.svg)||heart|0xe072|featherIcons/0114_heart.svg|
|![](featherIcons/0115_help-circle.svg)||help-circle|0xe073|featherIcons/0115_help-circle.svg|
|![](featherIcons/0116_home.svg)||home|0xe074|featherIcons/0116_home.svg|
|![](featherIcons/0117_image.svg)||image|0xe075|featherIcons/0117_image.svg|
|![](featherIcons/0118_inbox.svg)||inbox|0xe076|featherIcons/0118_inbox.svg|
|![](featherIcons/0119_info.svg)||info|0xe077|featherIcons/0119_info.svg|
|![](featherIcons/0120_italic.svg)||italic|0xe078|featherIcons/0120_italic.svg|
|![](featherIcons/0121_layers.svg)||layers|0xe079|featherIcons/0121_layers.svg|
|![](featherIcons/0122_layout.svg)||layout|0xe07a|featherIcons/0122_layout.svg|
|![](featherIcons/0123_life-buoy.svg)||life-buoy|0xe07b|featherIcons/0123_life-buoy.svg|
|![](featherIcons/0124_link-2.svg)||link-2|0xe07c|featherIcons/0124_link-2.svg|
|![](featherIcons/0125_link.svg)||link|0xe07d|featherIcons/0125_link.svg|
|![](featherIcons/0126_list.svg)||list|0xe07e|featherIcons/0126_list.svg|
|![](featherIcons/0127_loader.svg)||loader|0xe07f|featherIcons/0127_loader.svg|
|![](featherIcons/0128_lock.svg)||lock|0xe080|featherIcons/0128_lock.svg|
|![](featherIcons/0129_log-in.svg)||log-in|0xe081|featherIcons/0129_log-in.svg|
|![](featherIcons/0130_log-out.svg)||log-out|0xe082|featherIcons/0130_log-out.svg|
|![](featherIcons/0131_mail.svg)||mail|0xe083|featherIcons/0131_mail.svg|
|![](featherIcons/0132_map-pin.svg)||map-pin|0xe084|featherIcons/0132_map-pin.svg|
|![](featherIcons/0133_map.svg)||map|0xe085|featherIcons/0133_map.svg|
|![](featherIcons/0134_maximize-2.svg)||maximize-2|0xe086|featherIcons/0134_maximize-2.svg|
|![](featherIcons/0135_maximize.svg)||maximize|0xe087|featherIcons/0135_maximize.svg|
|![](featherIcons/0136_menu.svg)||menu|0xe088|featherIcons/0136_menu.svg|
|![](featherIcons/0137_message-circle.svg)||message-circle|0xe089|featherIcons/0137_message-circle.svg|
|![](featherIcons/0138_message-square.svg)||message-square|0xe08a|featherIcons/0138_message-square.svg|
|![](featherIcons/0139_mic-off.svg)||mic-off|0xe08b|featherIcons/0139_mic-off.svg|
|![](featherIcons/0140_mic.svg)||mic|0xe08c|featherIcons/0140_mic.svg|
|![](featherIcons/0141_minimize-2.svg)||minimize-2|0xe08d|featherIcons/0141_minimize-2.svg|
|![](featherIcons/0142_minimize.svg)||minimize|0xe08e|featherIcons/0142_minimize.svg|
|![](featherIcons/0143_minus-circle.svg)||minus-circle|0xe08f|featherIcons/0143_minus-circle.svg|
|![](featherIcons/0144_minus-square.svg)||minus-square|0xe090|featherIcons/0144_minus-square.svg|
|![](featherIcons/0145_minus.svg)||minus|0xe091|featherIcons/0145_minus.svg|
|![](featherIcons/0146_monitor.svg)||monitor|0xe092|featherIcons/0146_monitor.svg|
|![](featherIcons/0147_moon.svg)||moon|0xe093|featherIcons/0147_moon.svg|
|![](featherIcons/0148_more-horizontal.svg)||more-horizontal|0xe094|featherIcons/0148_more-horizontal.svg|
|![](featherIcons/0149_more-vertical.svg)||more-vertical|0xe095|featherIcons/0149_more-vertical.svg|
|![](featherIcons/0150_move.svg)||move|0xe096|featherIcons/0150_move.svg|
|![](featherIcons/0151_music.svg)||music|0xe097|featherIcons/0151_music.svg|
|![](featherIcons/0152_navigation-2.svg)||navigation-2|0xe098|featherIcons/0152_navigation-2.svg|
|![](featherIcons/0153_navigation.svg)||navigation|0xe099|featherIcons/0153_navigation.svg|
|![](featherIcons/0154_octagon.svg)||octagon|0xe09a|featherIcons/0154_octagon.svg|
|![](featherIcons/0155_package.svg)||package|0xe09b|featherIcons/0155_package.svg|
|![](featherIcons/0156_paperclip.svg)||paperclip|0xe09c|featherIcons/0156_paperclip.svg|
|![](featherIcons/0157_pause-circle.svg)||pause-circle|0xe09d|featherIcons/0157_pause-circle.svg|
|![](featherIcons/0158_pause.svg)||pause|0xe09e|featherIcons/0158_pause.svg|
|![](featherIcons/0159_percent.svg)||percent|0xe09f|featherIcons/0159_percent.svg|
|![](featherIcons/0160_phone-call.svg)||phone-call|0xe0a0|featherIcons/0160_phone-call.svg|
|![](featherIcons/0161_phone-forwarded.svg)||phone-forwarded|0xe0a1|featherIcons/0161_phone-forwarded.svg|
|![](featherIcons/0162_phone-incoming.svg)||phone-incoming|0xe0a2|featherIcons/0162_phone-incoming.svg|
|![](featherIcons/0163_phone-missed.svg)||phone-missed|0xe0a3|featherIcons/0163_phone-missed.svg|
|![](featherIcons/0164_phone-off.svg)||phone-off|0xe0a4|featherIcons/0164_phone-off.svg|
|![](featherIcons/0165_phone-outgoing.svg)||phone-outgoing|0xe0a5|featherIcons/0165_phone-outgoing.svg|
|![](featherIcons/0166_phone.svg)||phone|0xe0a6|featherIcons/0166_phone.svg|
|![](featherIcons/0167_pie-chart.svg)||pie-chart|0xe0a7|featherIcons/0167_pie-chart.svg|
|![](featherIcons/0168_play-circle.svg)||play-circle|0xe0a8|featherIcons/0168_play-circle.svg|
|![](featherIcons/0169_play.svg)||play|0xe0a9|featherIcons/0169_play.svg|
|![](featherIcons/0170_plus-circle.svg)||plus-circle|0xe0aa|featherIcons/0170_plus-circle.svg|
|![](featherIcons/0171_plus-square.svg)||plus-square|0xe0ab|featherIcons/0171_plus-square.svg|
|![](featherIcons/0172_plus.svg)||plus|0xe0ac|featherIcons/0172_plus.svg|
|![](featherIcons/0173_power.svg)||power|0xe0ad|featherIcons/0173_power.svg|
|![](featherIcons/0174_printer.svg)||printer|0xe0ae|featherIcons/0174_printer.svg|
|![](featherIcons/0175_radio.svg)||radio|0xe0af|featherIcons/0175_radio.svg|
|![](featherIcons/0176_refresh-ccw.svg)||refresh-ccw|0xe0b0|featherIcons/0176_refresh-ccw.svg|
|![](featherIcons/0177_refresh-cw.svg)||refresh-cw|0xe0b1|featherIcons/0177_refresh-cw.svg|
|![](featherIcons/0178_repeat.svg)||repeat|0xe0b2|featherIcons/0178_repeat.svg|
|![](featherIcons/0179_rewind.svg)||rewind|0xe0b3|featherIcons/0179_rewind.svg|
|![](featherIcons/0180_rotate-ccw.svg)||rotate-ccw|0xe0b4|featherIcons/0180_rotate-ccw.svg|
|![](featherIcons/0181_rotate-cw.svg)||rotate-cw|0xe0b5|featherIcons/0181_rotate-cw.svg|
|![](featherIcons/0182_rss.svg)||rss|0xe0b6|featherIcons/0182_rss.svg|
|![](featherIcons/0183_save.svg)||save|0xe0b7|featherIcons/0183_save.svg|
|![](featherIcons/0184_scissors.svg)||scissors|0xe0b8|featherIcons/0184_scissors.svg|
|![](featherIcons/0185_search.svg)||search|0xe0b9|featherIcons/0185_search.svg|
|![](featherIcons/0186_send.svg)||send|0xe0ba|featherIcons/0186_send.svg|
|![](featherIcons/0187_server.svg)||server|0xe0bb|featherIcons/0187_server.svg|
|![](featherIcons/0188_settings.svg)||settings|0xe0bc|featherIcons/0188_settings.svg|
|![](featherIcons/0189_share-2.svg)||share-2|0xe0bd|featherIcons/0189_share-2.svg|
|![](featherIcons/0190_share.svg)||share|0xe0be|featherIcons/0190_share.svg|
|![](featherIcons/0191_shield-off.svg)||shield-off|0xe0bf|featherIcons/0191_shield-off.svg|
|![](featherIcons/0192_shield.svg)||shield|0xe0c0|featherIcons/0192_shield.svg|
|![](featherIcons/0193_shopping-bag.svg)||shopping-bag|0xe0c1|featherIcons/0193_shopping-bag.svg|
|![](featherIcons/0194_shopping-cart.svg)||shopping-cart|0xe0c2|featherIcons/0194_shopping-cart.svg|
|![](featherIcons/0195_shuffle.svg)||shuffle|0xe0c3|featherIcons/0195_shuffle.svg|
|![](featherIcons/0196_sidebar.svg)||sidebar|0xe0c4|featherIcons/0196_sidebar.svg|
|![](featherIcons/0197_skip-back.svg)||skip-back|0xe0c5|featherIcons/0197_skip-back.svg|
|![](featherIcons/0198_skip-forward.svg)||skip-forward|0xe0c6|featherIcons/0198_skip-forward.svg|
|![](featherIcons/0199_slack.svg)||slack|0xe0c7|featherIcons/0199_slack.svg|
|![](featherIcons/0200_slash.svg)||slash|0xe0c8|featherIcons/0200_slash.svg|
|![](featherIcons/0201_sliders.svg)||sliders|0xe0c9|featherIcons/0201_sliders.svg|
|![](featherIcons/0202_smartphone.svg)||smartphone|0xe0ca|featherIcons/0202_smartphone.svg|
|![](featherIcons/0203_speaker.svg)||speaker|0xe0cb|featherIcons/0203_speaker.svg|
|![](featherIcons/0204_square.svg)||square|0xe0cc|featherIcons/0204_square.svg|
|![](featherIcons/0205_star.svg)||star|0xe0cd|featherIcons/0205_star.svg|
|![](featherIcons/0206_stop-circle.svg)||stop-circle|0xe0ce|featherIcons/0206_stop-circle.svg|
|![](featherIcons/0207_sun.svg)||sun|0xe0cf|featherIcons/0207_sun.svg|
|![](featherIcons/0208_sunrise.svg)||sunrise|0xe0d0|featherIcons/0208_sunrise.svg|
|![](featherIcons/0209_sunset.svg)||sunset|0xe0d1|featherIcons/0209_sunset.svg|
|![](featherIcons/0210_tablet.svg)||tablet|0xe0d2|featherIcons/0210_tablet.svg|
|![](featherIcons/0211_tag.svg)||tag|0xe0d3|featherIcons/0211_tag.svg|
|![](featherIcons/0212_target.svg)||target|0xe0d4|featherIcons/0212_target.svg|
|![](featherIcons/0213_terminal.svg)||terminal|0xe0d5|featherIcons/0213_terminal.svg|
|![](featherIcons/0214_thermometer.svg)||thermometer|0xe0d6|featherIcons/0214_thermometer.svg|
|![](featherIcons/0215_thumbs-down.svg)||thumbs-down|0xe0d7|featherIcons/0215_thumbs-down.svg|
|![](featherIcons/0216_thumbs-up.svg)||thumbs-up|0xe0d8|featherIcons/0216_thumbs-up.svg|
|![](featherIcons/0217_toggle-left.svg)||toggle-left|0xe0d9|featherIcons/0217_toggle-left.svg|
|![](featherIcons/0218_toggle-right.svg)||toggle-right|0xe0da|featherIcons/0218_toggle-right.svg|
|![](featherIcons/0219_trash-2.svg)||trash-2|0xe0db|featherIcons/0219_trash-2.svg|
|![](featherIcons/0220_trash.svg)||trash|0xe0dc|featherIcons/0220_trash.svg|
|![](featherIcons/0221_trending-down.svg)||trending-down|0xe0dd|featherIcons/0221_trending-down.svg|
|![](featherIcons/0222_trending-up.svg)||trending-up|0xe0de|featherIcons/0222_trending-up.svg|
|![](featherIcons/0223_triangle.svg)||triangle|0xe0df|featherIcons/0223_triangle.svg|
|![](featherIcons/0224_truck.svg)||truck|0xe0e0|featherIcons/0224_truck.svg|
|![](featherIcons/0225_tv.svg)||tv|0xe0e1|featherIcons/0225_tv.svg|
|![](featherIcons/0226_type.svg)||type|0xe0e2|featherIcons/0226_type.svg|
|![](featherIcons/0227_umbrella.svg)||umbrella|0xe0e3|featherIcons/0227_umbrella.svg|
|![](featherIcons/0228_underline.svg)||underline|0xe0e4|featherIcons/0228_underline.svg|
|![](featherIcons/0229_unlock.svg)||unlock|0xe0e5|featherIcons/0229_unlock.svg|
|![](featherIcons/0230_upload-cloud.svg)||upload-cloud|0xe0e6|featherIcons/0230_upload-cloud.svg|
|![](featherIcons/0231_upload.svg)||upload|0xe0e7|featherIcons/0231_upload.svg|
|![](featherIcons/0232_user-check.svg)||user-check|0xe0e8|featherIcons/0232_user-check.svg|
|![](featherIcons/0233_user-minus.svg)||user-minus|0xe0e9|featherIcons/0233_user-minus.svg|
|![](featherIcons/0234_user-plus.svg)||user-plus|0xe0ea|featherIcons/0234_user-plus.svg|
|![](featherIcons/0235_user-x.svg)||user-x|0xe0eb|featherIcons/0235_user-x.svg|
|![](featherIcons/0236_user.svg)||user|0xe0ec|featherIcons/0236_user.svg|
|![](featherIcons/0237_users.svg)||users|0xe0ed|featherIcons/0237_users.svg|
|![](featherIcons/0238_video-off.svg)||video-off|0xe0ee|featherIcons/0238_video-off.svg|
|![](featherIcons/0239_video.svg)||video|0xe0ef|featherIcons/0239_video.svg|
|![](featherIcons/0240_voicemail.svg)||voicemail|0xe0f0|featherIcons/0240_voicemail.svg|
|![](featherIcons/0241_volume-1.svg)||volume-1|0xe0f1|featherIcons/0241_volume-1.svg|
|![](featherIcons/0242_volume-2.svg)||volume-2|0xe0f2|featherIcons/0242_volume-2.svg|
|![](featherIcons/0243_volume-x.svg)||volume-x|0xe0f3|featherIcons/0243_volume-x.svg|
|![](featherIcons/0244_volume.svg)||volume|0xe0f4|featherIcons/0244_volume.svg|
|![](featherIcons/0245_watch.svg)||watch|0xe0f5|featherIcons/0245_watch.svg|
|![](featherIcons/0246_wifi-off.svg)||wifi-off|0xe0f6|featherIcons/0246_wifi-off.svg|
|![](featherIcons/0247_wifi.svg)||wifi|0xe0f7|featherIcons/0247_wifi.svg|
|![](featherIcons/0248_wind.svg)||wind|0xe0f8|featherIcons/0248_wind.svg|
|![](featherIcons/0249_x-circle.svg)||x-circle|0xe0f9|featherIcons/0249_x-circle.svg|
|![](featherIcons/0250_x-square.svg)||x-square|0xe0fa|featherIcons/0250_x-square.svg|
|![](featherIcons/0251_x.svg)||x|0xe0fb|featherIcons/0251_x.svg|
|![](featherIcons/0252_zap-off.svg)||zap-off|0xe0fc|featherIcons/0252_zap-off.svg|
|![](featherIcons/0253_zap.svg)||zap|0xe0fd|featherIcons/0253_zap.svg|
|![](featherIcons/0254_zoom-in.svg)||zoom-in|0xe0fe|featherIcons/0254_zoom-in.svg|
|![](featherIcons/0255_zoom-out.svg)||zoom-out|0xe0ff|featherIcons/0255_zoom-out.svg|


## Building

We use python to generate a `fontManifest.yaml` for use with 
[glyphs2font](https://github.com/rse/glyphs2font).

We use j2cli to build documentation


```bash
python generateFontManifest.py
glyphs2font fontManifest.yaml
j2 template_README.md fontManifest.yaml > README.md #Build docs

```