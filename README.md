# cannot-all-minecraft
You cannot ALL MINECRAFT SYSTEM! (korean version)

This file if skript files.
You can edit sorce code and you need put "sorce code by doyun shin" text.

sorce :

on join:
	set join message to "&e%player% 님이 멸망해가는 섬에 입국하셨습니다"

on death:
	broadcast "&e%player% 님이 멸망해가는 곳에서 살아남지 못하고 죽었습니다"

on eat:
	cancel event
	message "알고보니 이 곳에선 방사능이 모든 음식에 퍼져서 먹지 않는게 좋을거 같다."

on chat:
	cancel event
	message "알고보니 무전기가 고장났다."

on inventory click:
	cancel event
	message "아이템에 벌레가 있으니 조금 있다가 정리하자."
