# MC3DS-Options-Documentation
- **Documentation for Minecraft 3DS's options.txt, amongst other configuration files.**

## Understanding the Value(s):
```
-1      : Always (force) False       *Not All Settings (Bolean)
0       : False                      *Not All Settings (Bolean)
1       : True                       *Not All Settings (Bolean)
2       : Always (force) True        *Not All Settings (Bolean)
[]      : Single List
#[]     : Combo List (multiple)
```

## Understanding Language(s):
```
de_DE   : German    - Germany
en_GB   : English   - Great Britain (UK)
en_US   : English   - United States (US)
es_ES   : Spanish   - Spain
es_MX   : Spanish   - Mexico
fr_CA   : French    - Canada
fr_FR   : French    - France
it_IT   : Italian   - Italy
jp_JP   : Japanses  - Japan
ko_KR   : Korean    - Korea
nl_NL   : Dutch     - Netherlands
pt_PT   : Portugues - Portugal
pt_BR   : Portugues - Brazil
ru_RU   : Russian   - Russia
zh_CN   : Zhongwen  - China
zh_TW   : Zhongwen  - Tiwan
```

## Setting(s) List:
```
game_difficulty_new                     - Defualt Difficulty when Creating New World.              (Value: Int 0 - 4)
game_thirdperson                        - Turn on/off thirdperson when opening a world.            (Value: Bolean)
gfx_dpadscale                           - Scalability for the DPAD (input multiplied).             (Value: Int 0 - 1 *Decimal)
mp_server_visible                       - Is server avaliable for people to players.               (Value: Bolean)
mp_xboxlive_visible                     - Is server available over Xbox Live.                      (Value: Bolean *Does NOT affect Game)
game_flatworldlayers                    - How many layers (and ID's of blocks for flatworld).      (Value: List)
game_limitworldsize                     - Should Game Limit World Size.                            (Value: Bolean *Does NOT affect Game)
game_language                           - What language should be displayed/used.                  (Value: Character String *Language String Above)
game_skintypefull                       - Name of Skin in use by player.                           (Value: Character String *Internal Skin Naming)
game_lastcustomskinnew                  - Is last skin customized/new or bought.                   (Value: Bolean)
game_recentskin1                        - Sets Skin to this String if Defualt isn't found.         (Value: Character String *Internal Skin Naming)
game_recentskin2                        - Sets Skin to this String if 'recentskin1' isn't found.   (Value: Character String *Internal Skin Naming)
game_recentskin3                        - Sets Skin to this String if 'recentskin2' isn't found.   (Value: Character String *Internal Skin Naming)
game_automationserverretrytime          - Retry/refresh server list time (in Milliseconds).        (Value: Int 1 - 100)  
game_haseverloggedintoxbl               - Is server logged into XBL.                               (Value: Bolean *Does NOT affect Game)
game_haschosennottosignintoxbl          - Is server chosen to not log into XBL.                    (Value: Bolean *Does NOT affect Game)
game_hasBeenShownXbLiveSignInSurvey     - Has server owner been shown Forum for XBL.               (Value: Bolean *Does NOT affect Game)
ctrl_sensitivity                        - Camera Panning Sensitivity.                              (Value: Int 0 - 5 *Decimal)
ctrl_invertmouse:
ctrl_islefthanded:
ctrl_usetouchscreen:
ctrl_usetouchjoypad:
ctrl_swapjumpandsneak:
feedback_vibration:
ctrl_autojump:
ctrl_keyboardlayout:
ctrl_gamePadMap:
gfx_renderdistance_new:
gfx_particleviewdistance:
gfx_viewbobbing:
gfx_fancygraphics:
gfx_transparentleaves:
gfx_fancyskies:
gfx_hidegui:
gfx_field_of_view:
gfx_msaa:
gfx_texel_aa_2:
gfx_gamma:
gfx_fullscreen:
gfx_guiscale:
audio_sound:
audio_music:
dev_autoloadlevel:
dev_showchunkmap:
dev_disablefilesystem:
dev_enable_profiler:
dev_uselocalserver:
dev_connection_quality:
dev_createRealmWithoutPurchase:
dev_flushOrphanedRealmsPurchases:
dev_offersUnlocked:
dev_resetClientId:
dev_logflushimmediate:
dev_logtimestamp:
dev_logtrace:
dev_logappend:
dev_priorityfilter:
dev_areafilter:
old_game_version_major:
old_game_version_minor:
old_game_version_patch:
old_game_version_beta:
realms_show_friend_invites_only:
```
