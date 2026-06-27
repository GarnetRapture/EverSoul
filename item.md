# 아이템 전체 목록 (SNO 체계 기반, tbl_item x tbl_string_item JOIN)

## SNO 체계 설명

- tbl_item.name_sno → tbl_string_item.no_value → .kr / .en
- category_sno: 아이템 카테고리 (110001=재화/소모품, 110008=소울 기억 등)
- grade_sno: 등급 (110012=일반, 110014=레어, 110016=에픽, 110019=특수)

## 주요 재화 아이템 번호

| item_no | KR 이름 | EN 이름 | 비고 |
|---|---|---|---|
| 1 | 골드 | Gold | currency type 1 |
| 2 | 에버스톤 | Everstone | currency type 2 — 무료 에버스톤 |
| 3 | 마나 더스트 | Mana Dust | currency type 3 |
| 4 | 마나 크리스탈 | Mana Crystal | currency type 4 |
| 6 | 하트 | Heart | currency type 6 |
| 8 | 인공 시냅스 소자 | Artificial Synapse Module | spirit_tree 슬롯 개방 아이템, item_etc |
| 42 | 에버스톤 | Everstone | currency type 42 — 유료 에버스톤 |

## spirit_tree 슬롯 개방 비용 로직

1. item_no=8 (인공 시냅스 소자) life_essence_amount개 소비 (먼저)
2. currency_type=2 (무료 에버스톤) dia_amount만큼 차감
3. currency_type=42 (유료 에버스톤) 나머지 차감

## 아이템 전체 목록 (총 3676개)

| item_no | name_sno | category_sno | grade_sno | KR 이름 | EN 이름 |
|---|---|---|---|---|---|
| 1 | 210001 | 110001 | 110012 | 골드 | Gold |
| 2 | 210002 | 110001 | 110014 | 에버스톤 | Everstone |
| 3 | 210003 | 110001 | 110012 | 마나 더스트 | Mana Dust |
| 4 | 210004 | 110001 | 110014 | 마나 크리스탈 | Mana Crystal |
| 5 | 210005 | 110001 | 110012 | 플레이어 경험치 | Player EXP |
| 6 | 210006 | 110001 | 110012 | 하트 | Heart |
| 8 | 210008 | 110001 | 110012 | 인공 시냅스 소자 | Artificial Synapse Module |
| 9 | 210009 | 110001 | 110014 | 아레나 도전권 | Arena Challenge Ticket |
| 10 | 210010 | 110001 | 110012 | 미궁 코인 | Labyrinth Coin |
| 11 | 210011 | 110001 | 110012 | 레이드 코인 | Raid Coin |
| 12 | 210012 | 110001 | 110012 | 기억 조각 | Memory Shard |
| 13 | 210013 | 110001 | 110012 | 아레나 코인 | Arena Coin |
| 14 | 210014 | 110001 | 110012 | 유물 코인 | Artifact Coin |
| 16 | 210016 | 110001 | 110012 | 영지 코인 | Town Coin |
| 18 | 210018 | 110001 | 110012 | 악령 코인 | Evil Soul Coin |
| 19 | 210019 | 110001 | 110014 | 픽업 소환권 | Pick-Up Summon Ticket |
| 20 | 210020 | 110001 | 110012 | 유물석 | Artifact Stone |
| 21 | 210021 | 110001 | 110014 | 상급 유물석 | Advanced Artifact Stone |
| 22 | 210022 | 110001 | 110016 | 영광의 유물석 | Artifact Stone of Glory |
| 23 | 210023 | 110001 | 110016 | 본능의 유물석 | Artifact Stone of Instinct |
| 24 | 210024 | 110001 | 110016 | 조화의 유물석 | Artifact Stone of Harmony |
| 25 | 210025 | 110001 | 110016 | 불변의 유물석 | Artifact Stone of Constancy |
| 26 | 210026 | 110001 | 110016 | 희망의 유물석 | Artifact Stone of Hope |
| 27 | 210027 | 110001 | 110016 | 절망의 유물석 | Artifact Stone of Despair |
| 28 | 210028 | 110001 | 110014 | 일반 소환권 | Normal Summon Ticket |
| 29 | 210029 | 110001 | 110014 | 타입 소환권 | Type Summon Ticket |
| 30 | 210030 | 110008 | 110012 | 정령의 기억 (레어) | Soul's Memory (Rare) |
| 31 | 210031 | 110008 | 110014 | 정령의 기억 (에픽) | Soul's Memory (Epic) |
| 32 | 210032 | 110001 | 110012 | 예장 강화석 | Keepsake Enhance Stone |
| 33 | 210033 | 110001 | 110014 | 데이트 어 라이브 V 픽업 소환권 | Date A Live V Pick-Up Summon Ticket |
| 42 | 210042 | 110001 | 110014 | 에버스톤 | Everstone |
| 44 | 210044 | 110001 | 110014 | 챔피언스 아레나 도전권 | Champs Arena Challenge Ticket |
| 45 | 210045 | 110001 | 110014 | 유물 소환권 | Artifact Summon Ticket |
| 46 | 210046 | 110001 | 110014 | 에리카의 연금술 티켓 | Erika's Alchemy Ticket |
| 47 | 210047 | 110001 | 110012 | 승급 초기화권 | Ascension Reset Ticket |
| 48 | 210048 | 110001 | 110014 | 중급 예장 강화석 | Intermediate Keepsake Enhance Stone |
| 49 | 210049 | 110001 | 110016 | 상급 예장 강화석 | Advanced Keepsake Enhance Stone |
| 50 | 210050 | 110001 | 110014 | 성좌 포인트 | Zodiac Points |
| 51 | 210051 | 110001 | 110014 | 미궁 입장권 | Labyrinth Ticket |
| 52 | 210052 | 110001 | 110014 | 예장 초월석 | Keepsake Transcension Stone |
| 53 | 210053 | 110001 | 110014 | 악령 토벌 입장권 | Evil Soul Subjugation Ticket |
| 54 | 210054 | 110001 | 110019 | 세트 옵션 각인권 | Set Option Engraving Ticket |
| 55 | 210055 | 110001 | 110014 | 회랑 입장권 | Hall Ticket |
| 56 | 210056 | 110001 | 110014 | 작전 허가증 | Operation Permit |
| 57 | 210057 | 110001 | 110014 | 작전 기념 코인 | Operation Coin |
| 58 | 210058 | 110001 | 110014 | 타입 게이트 입장권 | Type Gate Ticket |
| 59 | 210059 | 110001 | 110014 | 기원의 탑 입장권 | Tower of Origin Ticket |
| 60 | 210060 | 110001 | 110014 | 양동 작전 티켓 | Decoy Operation Ticket |
| 61 | 210061 | 110001 | 110014 | 양동 작전 도전 모드 티켓 | Decoy Operation Challenge Mode Ticket |
| 62 | 210062 | 110001 | 110014 | 양동 작전 추가 티켓 | Extra Decoy Operation Ticket |
| 63 | 210063 | 110001 | 110014 | 양동 작전 도전 모드 추가 티켓 | Extra Decoy Operation Challenge Mode Ticket |
| 64 | 210064 | 110001 | 110016 | 태초의 유물석 | Artifact Stone of Primordium |
| 65 | 210065 | 110001 | 110012 | 오색의 결정 | Iridescent Crystal |
| 66 | 210066 | 110001 | 110014 | 지정 소환권 | Targeted Summon Ticket |
| 100 | 210100 | 110001 | 110014 | 에버스톤 | Everstone |
| 101 | 210101 | 110002 | 110011 | 빛바랜 시계 | Faded Watch |
| 102 | 210102 | 110002 | 110011 | 빛바랜 오르골 | Faded Orgel |
| 103 | 210103 | 110002 | 110011 | 빛바랜 거울 | Faded Mirror |
| 104 | 210104 | 110002 | 110011 | 빛바랜 열쇠 | Faded Key |
| 201 | 210201 | 110002 | 110012 | 추억이 담긴 시계 | Clock of Memories |
| 202 | 210202 | 110002 | 110012 | 추억이 담긴 오르골 | Orgel of Memories |
| 203 | 210203 | 110002 | 110012 | 추억이 담긴 거울 | Mirror of Memories |
| 204 | 210204 | 110002 | 110012 | 추억이 담긴 열쇠 | Key of Memories |
| 301 | 210301 | 110002 | 110013 | 비밀을 간직한 시계 | Clock of Secrets |
| 302 | 210302 | 110002 | 110013 | 비밀을 간직한 오르골 | Orgel of Secrets |
| 303 | 210303 | 110002 | 110013 | 비밀을 간직한 거울 | Mirror of Secrets |
| 304 | 210304 | 110002 | 110013 | 비밀을 간직한 열쇠 | Key of Secrets |
| 401 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 402 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 403 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 404 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 405 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 406 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 407 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 408 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 409 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 410 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 411 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 412 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 413 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 414 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 415 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 416 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 417 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 418 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 419 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 420 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 421 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 422 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 423 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 424 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 425 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 426 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 427 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 428 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 429 | 210401 | 110002 | 110014 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 430 | 210402 | 110002 | 110014 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 431 | 210403 | 110002 | 110014 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 432 | 210404 | 110002 | 110014 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 433 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 434 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 435 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 436 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 437 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 438 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 439 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 440 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 441 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 442 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 443 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 444 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 445 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 446 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 447 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 448 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 449 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 450 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 451 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 452 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 453 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 454 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 455 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 456 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 457 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 458 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 459 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 460 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 461 | 210405 | 110002 | 110014 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 462 | 210406 | 110002 | 110014 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 463 | 210407 | 110002 | 110014 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 464 | 210408 | 110002 | 110014 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 465 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 466 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 467 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 468 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 469 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 470 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 471 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 472 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 473 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 474 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 475 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 476 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 477 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 478 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 479 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 480 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 481 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 482 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 483 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 484 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 485 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 486 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 487 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 488 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 489 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 490 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 491 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 492 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 493 | 210409 | 110002 | 110014 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 494 | 210410 | 110002 | 110014 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 495 | 210411 | 110002 | 110014 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 496 | 210412 | 110002 | 110014 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 501 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 502 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 503 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 504 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 505 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 506 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 507 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 508 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 509 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 510 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 511 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 512 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 513 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 514 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 515 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 516 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 517 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 518 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 519 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 520 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 521 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 522 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 523 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 524 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 525 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 526 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 527 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 528 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 529 | 210501 | 110002 | 110015 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 530 | 210502 | 110002 | 110015 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 531 | 210503 | 110002 | 110015 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 532 | 210504 | 110002 | 110015 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 533 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 534 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 535 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 536 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 537 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 538 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 539 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 540 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 541 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 542 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 543 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 544 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 545 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 546 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 547 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 548 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 549 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 550 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 551 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 552 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 553 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 554 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 555 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 556 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 557 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 558 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 559 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 560 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 561 | 210505 | 110002 | 110015 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 562 | 210506 | 110002 | 110015 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 563 | 210507 | 110002 | 110015 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 564 | 210508 | 110002 | 110015 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 565 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 566 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 567 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 568 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 569 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 570 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 571 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 572 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 573 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 574 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 575 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 576 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 577 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 578 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 579 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 580 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 581 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 582 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 583 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 584 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 585 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 586 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 587 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 588 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 589 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 590 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 591 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 592 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 593 | 210509 | 110002 | 110015 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 594 | 210510 | 110002 | 110015 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 595 | 210511 | 110002 | 110015 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 596 | 210512 | 110002 | 110015 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 601 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 602 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 603 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 604 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 605 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 606 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 607 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 608 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 609 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 610 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 611 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 612 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 613 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 614 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 615 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 616 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 617 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 618 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 619 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 620 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 621 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 622 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 623 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 624 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 625 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 626 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 627 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 628 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 629 | 210601 | 110002 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 630 | 210602 | 110002 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 631 | 210603 | 110002 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 632 | 210604 | 110002 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 633 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 634 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 635 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 636 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 637 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 638 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 639 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 640 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 641 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 642 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 643 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 644 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 645 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 646 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 647 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 648 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 649 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 650 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 651 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 652 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 653 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 654 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 655 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 656 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 657 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 658 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 659 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 660 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 661 | 210629 | 110002 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 662 | 210630 | 110002 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 663 | 210631 | 110002 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 664 | 210632 | 110002 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 665 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 666 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 667 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 668 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 669 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 670 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 671 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 672 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 673 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 674 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 675 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 676 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 677 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 678 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 679 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 680 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 681 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 682 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 683 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 684 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 685 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 686 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 687 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 688 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 689 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 690 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 691 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 692 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 693 | 210657 | 110002 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 694 | 210658 | 110002 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 695 | 210659 | 110002 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 696 | 210660 | 110002 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 701 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 702 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 703 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 704 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 705 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 706 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 707 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 708 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 709 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 710 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 711 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 712 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 713 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 714 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 715 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 716 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 717 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 718 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 719 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 720 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 721 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 722 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 723 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 724 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 725 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 726 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 727 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 728 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 729 | 210701 | 110002 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 730 | 210702 | 110002 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 731 | 210703 | 110002 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 732 | 210704 | 110002 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 733 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 734 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 735 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 736 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 737 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 738 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 739 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 740 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 741 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 742 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 743 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 744 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 745 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 746 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 747 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 748 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 749 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 750 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 751 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 752 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 753 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 754 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 755 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 756 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 757 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 758 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 759 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 760 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 761 | 210729 | 110002 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 762 | 210730 | 110002 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 763 | 210731 | 110002 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 764 | 210732 | 110002 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 765 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 766 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 767 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 768 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 769 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 770 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 771 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 772 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 773 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 774 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 775 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 776 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 777 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 778 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 779 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 780 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 781 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 782 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 783 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 784 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 785 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 786 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 787 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 788 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 789 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 790 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 791 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 792 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 793 | 210757 | 110002 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 794 | 210758 | 110002 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 795 | 210759 | 110002 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 796 | 210760 | 110002 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 801 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 802 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 803 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 804 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 805 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 806 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 807 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 808 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 809 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 810 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 811 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 812 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 813 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 814 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 815 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 816 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 817 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 818 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 819 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 820 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 821 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 822 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 823 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 824 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 825 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 826 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 827 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 828 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 829 | 210801 | 110002 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 830 | 210802 | 110002 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 831 | 210803 | 110002 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 832 | 210804 | 110002 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 833 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 834 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 835 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 836 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 837 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 838 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 839 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 840 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 841 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 842 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 843 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 844 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 845 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 846 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 847 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 848 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 849 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 850 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 851 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 852 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 853 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 854 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 855 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 856 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 857 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 858 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 859 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 860 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 861 | 210829 | 110002 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 862 | 210830 | 110002 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 863 | 210831 | 110002 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 864 | 210832 | 110002 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 865 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 866 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 867 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 868 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 869 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 870 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 871 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 872 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 873 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 874 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 875 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 876 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 877 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 878 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 879 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 880 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 881 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 882 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 883 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 884 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 885 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 886 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 887 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 888 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 889 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 890 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 891 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 892 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 893 | 210857 | 110002 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 894 | 210858 | 110002 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 895 | 210859 | 110002 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 896 | 210860 | 110002 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 901 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 902 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 903 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 904 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 905 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 906 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 907 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 908 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 909 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 910 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 911 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 912 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 913 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 914 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 915 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 916 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 917 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 918 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 919 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 920 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 921 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 922 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 923 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 924 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 925 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 926 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 927 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 928 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 929 | 210901 | 110002 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 930 | 210902 | 110002 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 931 | 210903 | 110002 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 932 | 210904 | 110002 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 933 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 934 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 935 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 936 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 937 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 938 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 939 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 940 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 941 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 942 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 943 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 944 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 945 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 946 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 947 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 948 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 949 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 950 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 951 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 952 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 953 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 954 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 955 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 956 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 957 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 958 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 959 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 960 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 961 | 210929 | 110002 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 962 | 210930 | 110002 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 963 | 210931 | 110002 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 964 | 210932 | 110002 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 965 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 966 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 967 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 968 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 969 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 970 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 971 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 972 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 973 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 974 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 975 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 976 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 977 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 978 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 979 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 980 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 981 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 982 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 983 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 984 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 985 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 986 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 987 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 988 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 989 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 990 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 991 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 992 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 993 | 210957 | 110002 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 994 | 210958 | 110002 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 995 | 210959 | 110002 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 996 | 210960 | 110002 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 1001 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1002 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1003 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1004 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1005 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1006 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1007 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1008 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1009 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1010 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1011 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1012 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1013 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1014 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1015 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1016 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1017 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1018 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1019 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1020 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1021 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1022 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1023 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1024 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1025 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1026 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1027 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1028 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1029 | 211001 | 110002 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 1030 | 211002 | 110002 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 1031 | 211003 | 110002 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 1032 | 211004 | 110002 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 1033 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1034 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1035 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1036 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1037 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1038 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1039 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1040 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1041 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1042 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1043 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1044 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1045 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1046 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1047 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1048 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1049 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1050 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1051 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1052 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1053 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1054 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1055 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1056 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1057 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1058 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1059 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1060 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1061 | 211029 | 110002 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 1062 | 211030 | 110002 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 1063 | 211031 | 110002 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 1064 | 211032 | 110002 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 1065 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1066 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1067 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1068 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1069 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1070 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1071 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1072 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1073 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1074 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1075 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1076 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1077 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1078 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1079 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1080 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1081 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1082 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1083 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1084 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1085 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1086 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1087 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1088 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1089 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1090 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1091 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1092 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1093 | 211057 | 110002 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 1094 | 211058 | 110002 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 1095 | 211059 | 110002 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 1096 | 211060 | 110002 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 1101 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1102 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1103 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1104 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1105 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1106 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1107 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1108 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1109 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1110 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1111 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1112 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1113 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1114 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1115 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1116 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1117 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1118 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1119 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1120 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1121 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1122 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1123 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1124 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1125 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1126 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1127 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1128 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1129 | 211101 | 110002 | 110021 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 1130 | 211102 | 110002 | 110021 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 1131 | 211103 | 110002 | 110021 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 1132 | 211104 | 110002 | 110021 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 1133 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1134 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1135 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1136 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1137 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1138 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1139 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1140 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1141 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1142 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1143 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1144 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1145 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1146 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1147 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1148 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1149 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1150 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1151 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1152 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1153 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1154 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1155 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1156 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1157 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1158 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1159 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1160 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1161 | 211129 | 110002 | 110021 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 1162 | 211130 | 110002 | 110021 | 소원을 품은 오르골 | Orgel of Wishes |
| 1163 | 211131 | 110002 | 110021 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 1164 | 211132 | 110002 | 110021 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 1165 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1166 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1167 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1168 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1169 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1170 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1171 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1172 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1173 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1174 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1175 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1176 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1177 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1178 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1179 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1180 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1181 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1182 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1183 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1184 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1185 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1186 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1187 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1188 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1189 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1190 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1191 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1192 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1193 | 211157 | 110002 | 110021 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 1194 | 211158 | 110002 | 110021 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 1195 | 211159 | 110002 | 110021 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 1196 | 211160 | 110002 | 110021 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 1201 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1202 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1203 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1204 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1205 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1206 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1207 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1208 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1209 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1210 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1211 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1212 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1213 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1214 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1215 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1216 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1217 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1218 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1219 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1220 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1221 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1222 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1223 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1224 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1225 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1226 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1227 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1228 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1229 | 211201 | 110002 | 110022 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 1230 | 211202 | 110002 | 110022 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 1231 | 211203 | 110002 | 110022 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 1232 | 211204 | 110002 | 110022 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 1233 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1234 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1235 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1236 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1237 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1238 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1239 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1240 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1241 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1242 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1243 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1244 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1245 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1246 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1247 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1248 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1249 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1250 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1251 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1252 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1253 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1254 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1255 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1256 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1257 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1258 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1259 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1260 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1261 | 211229 | 110002 | 110022 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 1262 | 211230 | 110002 | 110022 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 1263 | 211231 | 110002 | 110022 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 1264 | 211232 | 110002 | 110022 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 1265 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1266 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1267 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1268 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1269 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1270 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1271 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1272 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1273 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1274 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1275 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1276 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1277 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1278 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1279 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1280 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1281 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1282 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1283 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1284 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1285 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1286 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1287 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1288 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1289 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1290 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1291 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1292 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1293 | 211257 | 110002 | 110022 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 1294 | 211258 | 110002 | 110022 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 1295 | 211259 | 110002 | 110022 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 1296 | 211260 | 110002 | 110022 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 1301 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1302 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1303 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1304 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1305 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1306 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1307 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1308 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1309 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1310 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1311 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1312 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1313 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1314 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1315 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1316 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1317 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1318 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1319 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1320 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1321 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1322 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1323 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1324 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1325 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1326 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1327 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1328 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1329 | 211301 | 110002 | 110023 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 1330 | 211302 | 110002 | 110023 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 1331 | 211303 | 110002 | 110023 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 1332 | 211304 | 110002 | 110023 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 1333 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1334 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1335 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1336 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1337 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1338 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1339 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1340 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1341 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1342 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1343 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1344 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1345 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1346 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1347 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1348 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1349 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1350 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1351 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1352 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1353 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1354 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1355 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1356 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1357 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1358 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1359 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1360 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1361 | 211329 | 110002 | 110023 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 1362 | 211330 | 110002 | 110023 | 월광을 머금은 오르골 | Moonlit Music Box |
| 1363 | 211331 | 110002 | 110023 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 1364 | 211332 | 110002 | 110023 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 1365 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1366 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1367 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1368 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1369 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1370 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1371 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1372 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1373 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1374 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1375 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1376 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1377 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1378 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1379 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1380 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1381 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1382 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1383 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1384 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1385 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1386 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1387 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1388 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1389 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1390 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1391 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1392 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1393 | 211357 | 110002 | 110023 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 1394 | 211358 | 110002 | 110023 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 1395 | 211359 | 110002 | 110023 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 1396 | 211360 | 110002 | 110023 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 1401 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1402 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1403 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1404 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1405 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1406 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1407 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1408 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1409 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1410 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1411 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1412 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1413 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1414 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1415 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1416 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1417 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1418 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1419 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1420 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1421 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1422 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1423 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1424 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1425 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1426 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1427 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1428 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1429 | 211401 | 110002 | 110024 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 1430 | 211402 | 110002 | 110024 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 1431 | 211403 | 110002 | 110024 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 1432 | 211404 | 110002 | 110024 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 1433 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1434 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1435 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1436 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1437 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1438 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1439 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1440 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1441 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1442 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1443 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1444 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1445 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1446 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1447 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1448 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1449 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1450 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1451 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1452 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1453 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1454 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1455 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1456 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1457 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1458 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1459 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1460 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1461 | 211429 | 110002 | 110024 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 1462 | 211430 | 110002 | 110024 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 1463 | 211431 | 110002 | 110024 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 1464 | 211432 | 110002 | 110024 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 1465 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1466 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1467 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1468 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1469 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1470 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1471 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1472 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1473 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1474 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1475 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1476 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1477 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1478 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1479 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1480 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1481 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1482 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1483 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1484 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1485 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1486 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1487 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1488 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1489 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1490 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1491 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1492 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1493 | 211457 | 110002 | 110024 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 1494 | 211458 | 110002 | 110024 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 1495 | 211459 | 110002 | 110024 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 1496 | 211460 | 110002 | 110024 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 1501 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1502 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1503 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1504 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1505 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1506 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1507 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1508 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1509 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1510 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1511 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1512 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1513 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1514 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1515 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1516 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1517 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1518 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1519 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1520 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1521 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1522 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1523 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1524 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1525 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1526 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1527 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1528 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1529 | 211501 | 110002 | 110025 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 1530 | 211502 | 110002 | 110025 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 1531 | 211503 | 110002 | 110025 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 1532 | 211504 | 110002 | 110025 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 1533 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1534 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1535 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1536 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1537 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1538 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1539 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1540 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1541 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1542 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1543 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1544 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1545 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1546 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1547 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1548 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1549 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1550 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1551 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1552 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1553 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1554 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1555 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1556 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1557 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1558 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1559 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1560 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1561 | 211529 | 110002 | 110025 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 1562 | 211530 | 110002 | 110025 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 1563 | 211531 | 110002 | 110025 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 1564 | 211532 | 110002 | 110025 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 1565 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1566 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1567 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1568 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1569 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1570 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1571 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1572 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1573 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1574 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1575 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1576 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1577 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1578 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1579 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1580 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1581 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1582 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1583 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1584 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1585 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1586 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1587 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1588 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1589 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1590 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1591 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1592 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1593 | 211557 | 110002 | 110025 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 1594 | 211558 | 110002 | 110025 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 1595 | 211559 | 110002 | 110025 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 1596 | 211560 | 110002 | 110025 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 1901 | 211901 | 110078 | 110020 | 1주년 약속의 회중시계 | 1st Anniversary Pocket Watch of Promise |
| 1902 | 211902 | 110078 | 110020 | 1주년 약속의 오르골 | 1st Anniversary Music Box of Promise |
| 1903 | 211903 | 110078 | 110020 | 1주년 약속의 접이거울 | 1st Anniversary Folding Mirror of Promise |
| 1904 | 211904 | 110078 | 110020 | 1주년 약속의 만능열쇠 | 1st Anniversary Master Key of Promise |
| 1905 | 211905 | 110078 | 110020 | 흑기사의 투구 | Dark Knight's Helmet |
| 1906 | 211906 | 110078 | 110020 | 1.5주년 약속의 모래시계 | 1.5-Year Anniversary Hourglass of Promise |
| 1907 | 211907 | 110078 | 110020 | 1.5주년 약속의 스노우볼 | 1.5-Year Anniversary Snow Globe of Promise |
| 1908 | 211908 | 110078 | 110020 | 1.5주년 약속의 손거울 | 1.5-Year Anniversary Hand Mirror of Promise |
| 1909 | 211909 | 110078 | 110020 | 1.5주년 약속의 마법열쇠 | 1.5-Year Anniversary Magic Key of Promise |
| 1910 | 211910 | 110078 | 110020 | 2주년 약속의 드레스 | 2-Year Anniversary Dress of Promise |
| 1911 | 211911 | 110078 | 110020 | 2주년 약속의 날개 | 2-Year Anniversary Wings of Promise |
| 1912 | 211912 | 110078 | 110020 | 2주년 약속의 장갑 | 2-Year Anniversary Gloves of Promise |
| 1913 | 211913 | 110078 | 110020 | 2주년 약속의 헤드셋 | 2-Year Anniversary Headset of Promise |
| 1914 | 211914 | 110078 | 110020 | 2.5주년 약속의 팬던트 | 2.5-Year Anniversary Pendant of Promise |
| 1915 | 211915 | 110078 | 110020 | 2.5주년 약속의 팔찌 | 2.5-Year Anniversary Bracelet of Promise |
| 1916 | 211916 | 110078 | 110020 | 2.5주년 약속의 구두 | 2.5-Year Anniversary Shoes of Promise |
| 1917 | 211917 | 110078 | 110020 | 2.5주년 약속의 스파클링 | 2.5-Year Anniversary Sparkling Wine of Promise |
| 1918 | 211918 | 110078 | 110020 | 1000번째 약속의 브로치 | Brooch of the 1,000th Promise |
| 1919 | 211919 | 110078 | 110020 | 1000번째 약속의 오너먼트 | Ornament of the 1,000th Promise |
| 1920 | 211920 | 110078 | 110020 | 1000번째 약속의 헤어리본 | Hair Bow of the 1,000th Promise |
| 1921 | 211921 | 110078 | 110020 | 1000번째 약속의 가터링 | Garter Ring of the 1,000th Promise |
| 1922 | 211922 | 110078 | 110020 | 3주년 약속의 동백 | 3-Year Anniversary Camellia of Promise |
| 1923 | 211923 | 110078 | 110020 | 3주년 약속의 노리개 | 3-Year Anniversary Charm of Promise |
| 1924 | 211924 | 110078 | 110020 | 3주년 약속의 비녀 | 3-Year Anniversary Hairpin of Promise |
| 1925 | 211925 | 110078 | 110020 | 3주년 약속의 종이부채 | 3-Year Anniversary Paper Fan of Promise |
| 1999 | 210101 | 110002 | 110011 | 빛바랜 시계 | Faded Watch |
| 2001 | 520101 | 110009 | 110014 | 방주 오퍼레이터 | Ark Operator |
| 2002 | 520102 | 110009 | 110014 | 오퍼레이터 파이브 | Operator Five |
| 2003 | 520103 | 110009 | 110014 | 고결한 이상 | Noble Ideal |
| 2004 | 520104 | 110009 | 110014 | 봄날의 너 | You Are Like Spring |
| 2005 | 520105 | 110009 | 110014 | 보석 수집가 | Jewelry Collector |
| 2006 | 520106 | 110009 | 110014 | 하늘빛 잔상 | Skylight Afterimage |
| 2007 | 520107 | 110009 | 110014 | 워커홀릭의 일상 | A Workaholic's Daily Life |
| 2008 | 520108 | 110009 | 110014 | 오퍼레이터 나인 | Operator Nine |
| 2009 | 520109 | 110009 | 110014 | 기도하는 마음 | Praying Heart |
| 2010 | 520110 | 110009 | 110014 | 위험: 인화성 물질 | DANGER: Flammable Material |
| 2011 | 520111 | 110009 | 110014 | 곰곰이 생각해 봐 | Bear with the Thoughts |
| 2012 | 520112 | 110009 | 110014 | 적화청운 | Red Flame and Blue Cloud |
| 2013 | 520113 | 110009 | 110014 | 이리 오너라 | Come Here |
| 2014 | 520114 | 110009 | 110014 | 거친 갈기 | Tough Mane |
| 2015 | 520115 | 110009 | 110014 | 달빛의 음색~♪ | Moonlight Tone~♪ |
| 2016 | 520116 | 110009 | 110014 | 별빛의 선율~♬ | Starlight Melody ♬ |
| 2017 | 520117 | 110009 | 110014 | 메릴 기본 코스튬 | Meryl's Basic Costume |
| 2018 | 520118 | 110009 | 110014 | HE 애호가 | HE Lover |
| 2019 | 520119 | 110009 | 110014 | 무영의 암살자 | Shadowless Assassin |
| 2020 | 520120 | 110009 | 110014 | 베테랑 사냥꾼 | Veteran Hunter |
| 2021 | 520121 | 110009 | 110014 | 열이 많은 체질 | Always Hot |
| 2022 | 520122 | 110009 | 110014 | 출출하신 분? | Anyone Hungry? |
| 2023 | 520123 | 110009 | 110014 | Mix and Match | Mix and Match |
| 2024 | 520124 | 110009 | 110014 | 이나 기본 코스튬 | Ina's Basic Costume |
| 2025 | 520125 | 110009 | 110014 | 아이언 피스트 | Iron Fist |
| 2026 | 520126 | 110009 | 110014 | 오직 별님뿐 | Only Star |
| 2027 | 520127 | 110009 | 110014 | 공주 등장! | Enter Princess! |
| 2028 | 520128 | 110009 | 110014 | 기사의 품격 | Knight's Dignity |
| 2029 | 520129 | 110009 | 110014 | 바람과 함께 | With the Wind |
| 2030 | 520130 | 110009 | 110014 | 초속 5킬로미터 | 5 km per Second |
| 2031 | 520131 | 110009 | 110014 | 예절 주입기 | Etiquette Injector |
| 2032 | 520132 | 110009 | 110014 | 왕실 근위대 | Royal Guard |
| 2033 | 520133 | 110009 | 110014 | 자는 거 아냐… | I'm Not Sleeping... |
| 2034 | 520134 | 110009 | 110014 | 살짝만 열어볼게 | Just a Peek |
| 2035 | 520135 | 110009 | 110014 | 사랑스런 소녀와 캐럿 | Lovely Girl and Carrot |
| 2036 | 520136 | 110009 | 110014 | 병약 소녀는 일어나지 않아 | A Sick Girl Stays in Bed |
| 2037 | 520137 | 110009 | 110014 | 산만한 태양의 구속복 | Gigantic Sun Straitjacket |
| 2038 | 520138 | 110009 | 110014 | 차분한 달의 구속복 | Calm Moon Straitjacket |
| 2039 | 520139 | 110009 | 110014 | 쇼는 끝나지 않아 | The Show Never Ends |
| 2040 | 520140 | 110009 | 110014 | MODEL_Prototype | MODEL_Prototype |
| 2041 | 520141 | 110009 | 110014 | 떠올리고 싶지 않은 과거 | Undesirable Past |
| 2042 | 520142 | 110009 | 110014 | 숨막히는 뒷태 | Breathtaking Rear |
| 2043 | 520143 | 110009 | 110014 | 망자의 등대 | Lighthouse of the Dead |
| 2044 | 520144 | 110009 | 110014 | 콩 콩 콩 | Poing Poing |
| 2045 | 520145 | 110009 | 110014 | 양파 아니랍니다 | Not an Onion |
| 2046 | 520146 | 110009 | 110014 | 심판을 받아라 | Be Judged |
| 2047 | 520147 | 110009 | 110014 | 사논 기본 코스튬 | Sanon's Basic Costume |
| 2048 | 213367 | 110009 | 110014 | 봉인된 이차원의 정수 | Sealed Essence of Another Dimension |
| 2049 | 520149 | 110009 | 110014 | 품격의 완성 | Peak Elegance |
| 2050 | 520150 | 110009 | 110014 | 붉은 실의 인연 | Intertwined With Red |
| 2051 | 520151 | 110009 | 110014 | 새로운 일상 | New Routine |
| 2052 | 520152 | 110009 | 110014 | 엘레간테 | Elegante |
| 2053 | 520153 | 110009 | 110014 | 만두필승! | Dumplings for Winners! |
| 2054 | 520154 | 110009 | 110014 | 엘리트의 품위 | Elite Dignity |
| 2055 | 520155 | 110009 | 110014 | 대장간의 노란 꽃 | Yellow Flower in the Forge |
| 2056 | 520156 | 110009 | 110014 | 그건 잔상입니다 | Just a Mirage |
| 2057 | 520157 | 110009 | 110014 | 영원한 태양의 예복 | Eternal Sun's Robe |
| 2058 | 520158 | 110009 | 110014 | 아카이토 | Akaito |
| 2059 | 520159 | 110009 | 110014 | 타락의 증표 | Token of Corruption |
| 2060 | 520160 | 110009 | 110014 | 블루 나이팅게일 | Blue Nightingale |
| 2061 | 520161 | 110009 | 110014 | 그렇지 물어와 | Fetch |
| 2062 | 520162 | 110009 | 110014 | 권력의 상징 | Symbol of Power |
| 2063 | 520163 | 110009 | 110014 | 광휘의 수호자 | Guardian of Radiance |
| 2064 | 520164 | 110009 | 110014 | 미래를 향한 파도 | Waves Facing the Future |
| 2065 | 520165 | 110009 | 110014 | 죽음의 심판관 | Judge of Death |
| 2066 | 520166 | 110009 | 110014 | 밤의 지배자 | Ruler of the Night |
| 2067 | 520167 | 110009 | 110014 | 바다의 소리 | Sea Sound |
| 2068 | 520168 | 110009 | 110014 | 흑야의 검은 매 | Blackhawk of the Black Night |
| 2069 | 520169 | 110009 | 110014 | 엘로힘 | Elohim |
| 2070 | 520170 | 110009 | 110014 | 아도나이 멜렉 | Adonai Melek |
| 2071 | 520171 | 110009 | 110014 | 코드: 디폴트 | Code: Basic |
| 2072 | 520172 | 110009 | 110014 | 선명한 녹음 | Vibrant Greenery |
| 2073 | 520173 | 110009 | 110014 | 돌아온 권력 | Reclaimed Might |
| 2074 | 520174 | 110009 | 110014 | 여명의 별빛 | Starlight of Dawn |
| 2075 | 520175 | 110009 | 110014 | 브리기트 기본 코스튬 | Brigid's Basic Costume |
| 2076 | 520176 | 110009 | 110014 | 홍염의 후예 | Descendant of Prominence |
| 2077 | 520177 | 110009 | 110014 | 일기당천 | Solitary Decimator |
| 2078 | 520178 | 110009 | 110014 | 서방의 백호 | White Tiger of the West |
| 2079 | 520179 | 110009 | 110014 | 파도의 주인 | Mistress of the Waves |
| 2080 | 520180 | 110009 | 110014 | 백은의 공주 | The Argent Princess |
| 2081 | 520181 | 110009 | 110014 | 결전 장비: 허영 | Endgame Gear: Vanity |
| 2082 | 520182 | 110009 | 110014 | 보좌관의 의무 | Assistant's Duty |
| 2083 | 520183 | 110009 | 110014 | 가온의 취검 | Gaon's Drunken Sword |
| 2084 | 520184 | 110009 | 110014 | 이오루의 수호자 | Guardian of Ioru |
| 2085 | 520185 | 110009 | 110014 | 마리오네트 엘레지 | Marionette Elegy |
| 2086 | 520186 | 110009 | 110014 | 억겁의 형벌 | Eons of Punishment |
| 2087 | 520187 | 110009 | 110014 | 황금의 날개 | Golden Wings |
| 2088 | 520188 | 110009 | 110014 | 쇼비즈 | Showbiz |
| 2089 | 520189 | 110009 | 110014 | 해방된 천사 | Liberated Angel |
| 2090 | 520190 | 110009 | 110014 | 영원한 종말의 의복 | Eternal End Ensemble |
| 2091 | 520191 | 110009 | 110014 | 망월기원 | Wishful Moongazing |
| 2201 | 520401 | 110009 | 110016 | 두근두근 분홍 젤리 | Fluttering Pink Jelly |
| 2202 | 520402 | 110009 | 110016 | 쫑긋쫑긋 파스텔 버니 | Perky Ears Pastel Bunny |
| 2203 | 520403 | 110009 | 110016 | 짓궂은 장난 | Cheeky Mischief |
| 2204 | 520404 | 110009 | 110016 | 푸른 늑대의 호위무사 | Blue Wolf's Guard Warrior |
| 2205 | 520405 | 110009 | 110016 | 고백의 순간 | Moment of Confession |
| 2206 | 520406 | 110009 | 110016 | 발포하겠어 | I'll Fire |
| 2207 | 520407 | 110009 | 110016 | 햇빛의 리듬~♩ | Sunshine's Rhythm~♩ |
| 2208 | 520408 | 110009 | 110016 | 앵사취설 | Cherry Blossoms and Snake |
| 2209 | 520409 | 110009 | 110016 | 일기 예보: 흐림 | Weather Forecast: Cloudy |
| 2210 | 520410 | 110009 | 110016 | 주의: 거리의 바람 | Caution: Street Wind |
| 2211 | 520411 | 110009 | 110016 | 베어 A LA MODE | Bear a la Mode |
| 2212 | 520412 | 110009 | 110016 | 축배의 푸른 밤 | Toast to a Blue Night |
| 2213 | 520413 | 110009 | 110016 | 나 한 입만 | Can I Have a Bite? |
| 2214 | 520414 | 110009 | 110016 | 폭신폭신 발망치 | Fluffy Paw Hammer |
| 2215 | 520415 | 110009 | 110016 | 밤의 미라쥬 | Night Mirage |
| 2216 | 520416 | 110009 | 110016 | 핑크 에트왈 | Pink Star |
| 2217 | 520417 | 110009 | 110016 | 메릴 인연 코스튬 이름 | Meryl's Bond Costume Name |
| 2218 | 520418 | 110009 | 110016 | 플린 인연 코스튬 이름 | Flynn's Bond Costume Name |
| 2219 | 520419 | 110009 | 110016 | 로즈 가든 | Rose Garden |
| 2220 | 520420 | 110009 | 110016 | 자작나무 숲의 그림자 | Shadow of the Birch Forest |
| 2221 | 520421 | 110009 | 110016 | 기분 좋은 꿈 | Good Dream |
| 2222 | 520422 | 110009 | 110016 | 풍요의 여신 | Goddess of Abundance |
| 2223 | 520423 | 110009 | 110016 | 아, 아픈 친구 있어? | Is, Is Anyone Sick? |
| 2224 | 520424 | 110009 | 110016 | 이나 인연 코스튬 이름 | Ina's Bond Costume Name |
| 2225 | 520425 | 110009 | 110016 | 마이 페어 레이디 | My Fair Lady |
| 2226 | 520426 | 110009 | 110016 | 한밤의 꿈꾸는 소녀 | Midnight Dreaming Girl |
| 2227 | 520427 | 110009 | 110016 | 마린 프린세스 | Marine Princess |
| 2228 | 520428 | 110009 | 110016 | 공주의 침실 | Princess's Room |
| 2229 | 520429 | 110009 | 110016 | 여유로운 한 때 | Moment of Leisure |
| 2230 | 520430 | 110009 | 110016 | 원초의 취옥 | Primordial Emerald |
| 2231 | 520431 | 110009 | 110016 | 거리의 셀레네 | Selene on the Street |
| 2232 | 520432 | 110009 | 110016 | 샤이닝 치어 걸 | Shining Cheerleader |
| 2233 | 520433 | 110009 | 110016 | 신록의 계절 | Season of Verdure |
| 2234 | 520434 | 110009 | 110016 | 주문은 유혹입니까 | Temptation Spell? |
| 2235 | 520435 | 110009 | 110016 | 고양이 보러 갈래? | Wanna See My Cat? |
| 2236 | 520436 | 110009 | 110016 | 불사의 레베카 | Rebecca the Immortal |
| 2237 | 520437 | 110009 | 110016 | 사관학교의 햇님 | Military Academy's Sun |
| 2238 | 520438 | 110009 | 110016 | 사관학교의 달님 | Military Academy's Moon |
| 2239 | 520439 | 110009 | 110016 | 베테랑 퍼레이드 리더 | Veteran Parade Leader |
| 2240 | 520440 | 110009 | 110016 | MODEL_DarkShadow | MODEL_DarkShadow |
| 2241 | 520441 | 110009 | 110016 | 시집과 가을의 너 | Poetry and Your Autumn |
| 2242 | 520442 | 110009 | 110016 | 꿈꾸는 무희 | Dreaming Dancer |
| 2243 | 520443 | 110009 | 110016 | 밤에 피는 나비 | Nocturnal Butterfly |
| 2244 | 520444 | 110009 | 110016 | 마이 컬러풀 걸프렌드 | My Colorful Girlfriend |
| 2245 | 520445 | 110009 | 110016 | 북극성의 흑조 | Black Swan of the North Star |
| 2246 | 520446 | 110009 | 110016 | 원더 히어로 | Wonder Hero |
| 2247 | 520447 | 110009 | 110016 | 사논 인연 코스튬 이름 | Sanon's Bond Costume Name |
| 2248 | 520448 | 110009 | 110016 | 헬레나 인연 코스튬 이름 | Helena's Bond Costume Name |
| 2249 | 520449 | 110009 | 110016 | 흑익의 천사 | Dark Angel |
| 2250 | 520450 | 110009 | 110016 | 행복한 맺음 | Happy Ending |
| 2251 | 520451 | 110009 | 110016 | 손안의 온기 | Palm of Warmth |
| 2252 | 520452 | 110009 | 110016 | 최고의 곰돌이 | Best Teddy |
| 2253 | 520453 | 110009 | 110016 | 이상한 꿈결의 원님 | Magistrate's Strange Dream |
| 2254 | 520454 | 110009 | 110016 | 이상한 꿈결의 여우 | Fox's Strange Dream |
| 2255 | 520455 | 110009 | 110016 | 스트릿 무드 | Street Mood |
| 2256 | 520456 | 110009 | 110016 | 순정 쇼콜라티에 | Pure Heart Chocolatier |
| 2257 | 520457 | 110009 | 110016 | 달콤살벌 메이드 | Sweet Savage Maid |
| 2258 | 520458 | 110009 | 110016 | 녹음의 행운 | Lush Luck |
| 2259 | 520459 | 110009 | 110016 | 풀내음과 함께 | Feel the Grassy Scent |
| 2260 | 520460 | 110009 | 110016 | 노히트 노런 | No-hitter |
| 2261 | 520461 | 110009 | 110016 | 벌점이야 | Demerits |
| 2262 | 520462 | 110009 | 110016 | 푹신푹신 학교 생활 | Comfy School Life |
| 2263 | 520463 | 110009 | 110016 | 매지컬 프린세스 | Magical Princess |
| 2264 | 520464 | 110009 | 110016 | 리틀 부케 | Little Bouquet |
| 2265 | 520465 | 110009 | 110016 | 와인 샤워 | Wine Shower |
| 2266 | 520466 | 110009 | 110016 | SHADOW_EX_MACHINA | SHADOW_EX_MACHINA |
| 2267 | 520467 | 110009 | 110018 | DAEMON_EX_MACHINA | DAEMON_EX_MACHINA |
| 2268 | 520468 | 110009 | 110016 | 오늘의 라이더 | Today's Rider |
| 2269 | 520469 | 110009 | 110016 | 퓨어하트 로맨스 | Pure Heart Romance |
| 2270 | 520470 | 110009 | 110016 | 죄악의 취옥 | Emerald of Iniquity |
| 2271 | 520471 | 110009 | 110018 | 유배된 취옥 | Emerald of Exile |
| 2272 | 520472 | 110009 | 110016 | 해변의 마녀 | Witch of the Sea |
| 2273 | 520473 | 110009 | 110016 | 묘지기의 여름 | Grave Keeper's Summer |
| 2274 | 520474 | 110009 | 110016 | 여름의 마성 | Summer Demon |
| 2275 | 520475 | 110009 | 110016 | 사무치는 그리움 | Poignant Yearning |
| 2276 | 520476 | 110009 | 110018 | 끝내 오지 않은 구원 | Never-Coming Salvation |
| 2277 | 520481 | 110009 | 110016 | 포효하는 광기 | Roaring Madness |
| 2278 | 520482 | 110009 | 110018 | 전율하는 광기 | Shivering Madness |
| 2279 | 520477 | 110009 | 110016 | 해변의 반짝임 | Sparkling Beach |
| 2280 | 520478 | 110009 | 110016 | 눈부신 마음 | Dazzling Feeling |
| 2281 | 520479 | 110009 | 110016 | 해중일화 | Under the Sea |
| 2282 | 520480 | 110009 | 110016 | 바다 지킴이 | Seakeeper |
| 2283 | 520483 | 110009 | 110016 | 비탄의 성녀 | Saint of Sorrow |
| 2284 | 520484 | 110009 | 110018 | 혼돈의 성녀 | Saint of Chaos |
| 2285 | 520485 | 110009 | 110016 | 춘추 벚꽃 | Blooming Cherry Blossom |
| 2286 | 520486 | 110009 | 110016 | 백의홍상 | White Scarlet |
| 2287 | 520487 | 110009 | 110016 | 달토끼 전설 | Legend of Moon Rabbit |
| 2288 | 520488 | 110009 | 110016 | 아찔한 일식 | Dazzling Solar Eclipse |
| 2289 | 520489 | 110009 | 110016 | 월하의 사냥꾼 | Moonlight Hunter |
| 2290 | 520490 | 110009 | 110016 | 만월의 리벤저 | Revenger of the Full Moon |
| 2291 | 520491 | 110009 | 110016 | 빨간 모자의 장난 | Mischievous Red Riding Hood |
| 2292 | 520492 | 110009 | 110016 | 굿바이 여름!! | Farewell Summer!! |
| 2293 | 520493 | 110009 | 110016 | 전쟁의 사도 | Apostle of War |
| 2294 | 520494 | 110009 | 110018 | 전쟁의 화신 | Incarnation of War |
| 2295 | 520495 | 110009 | 110016 | 밤의 비서 | Night Secretary |
| 2296 | 520496 | 110009 | 110016 | 멜티 버니 | Chocobunny |
| 2297 | 520497 | 110009 | 110016 | 눈꽃의 수녀 | Nun of Snowflakes |
| 2298 | 520498 | 110009 | 110016 | 성야의 백곰 | White Bear of Starry Night |
| 2299 | 520499 | 110009 | 110016 | 선물은 나♥ | The Gift Is Me♥ |
| 2300 | 520503 | 110009 | 110016 | 멜티 스위트 | Melty Sweets |
| 2301 | 520500 | 110009 | 110016 | 드리밍 블루 | Dreamy Blue |
| 2302 | 520501 | 110009 | 110016 | 하트풀 스텝 | Heartful Steps |
| 2303 | 520502 | 110009 | 110016 | 레이지 옐로 | Mellow Yellow |
| 2304 | 520504 | 110009 | 110016 | 라비앙 로즈 | La Vie en Rose |
| 2305 | 520505 | 110009 | 110016 | 모레노 옵시디언 | Morreno Obsidian |
| 2306 | 520506 | 110009 | 110016 | 라피아 다이아몬드 | Raffia Diamond |
| 2307 | 520507 | 110009 | 110016 | 다이난 사파이어 | Dynan Sapphire |
| 2308 | 520508 | 110009 | 110016 | 청천청화 | Sky Blue Bloom |
| 2309 | 520509 | 110009 | 110016 | 쇼콜라 퀸 | Chocolat Queen |
| 2310 | 520510 | 110009 | 110016 | 스위트 매직 | Sweet Magic |
| 2311 | 520511 | 110009 | 110016 | 레드벨벳 하트 | Red Velvet Heart |
| 2312 | 520512 | 110009 | 110016 | 메디컬 디렉터 | Medical Director |
| 2313 | 520513 | 110009 | 110016 | 붉은 달의 검귀 | Red Moon Sword Demon |
| 2314 | 520514 | 110009 | 110018 | 붉은 달의 연인 | Red Moon's Sweetheart |
| 2315 | 520515 | 110009 | 110016 | 입어줘, 세일러복! | Sailor Uniform On! |
| 2316 | 520516 | 110009 | 110016 | 영원의 학생회장 | Forever Student President |
| 2317 | 520517 | 110009 | 110016 | 단추 발사대 | Button Launcher |
| 2318 | 520518 | 110009 | 110016 | 회계부장(입후보 예정) | Bursar (Potential Candidate) |
| 2319 | 520519 | 110009 | 110018 | 흔들림 없는 마음 | Unwavering Heart |
| 2320 | 520520 | 110009 | 110016 | 한여름의 나팔꽃 | Midsummer Morning Glory |
| 2321 | 520521 | 110009 | 110016 | 한낮의 윤슬 | Midday Glimmer |
| 2322 | 520522 | 110009 | 110016 | 마르치알레 | Marziale |
| 2323 | 520523 | 110009 | 110016 | 설레는 새 학기 | Exciting New Semester |
| 2324 | 520524 | 110009 | 110016 | 생명의 윤회 | Cycle of Life |
| 2325 | 520525 | 110009 | 110016 | 황제의 왼팔 | The Left Arm of the Empress |
| 2326 | 520526 | 110009 | 110016 | 수상한 스카우터 | Suspicious Headhunter |
| 2327 | 520527 | 110009 | 110018 | 검은 매의 일상 | Blackhawk Daily Wear |
| 2328 | 520528 | 110009 | 110016 | 눈꽃의 서약 | Oath of Snowflakes |
| 2329 | 520529 | 110009 | 110016 | 스트로베리 허니문 | Strawberry Honeymoon |
| 2330 | 520530 | 110009 | 110016 | 시크릿 웨딩 바니 | Secret Wedding Bunny |
| 2331 | 520531 | 110009 | 110016 | 모드: 카모플라쥬 | Mode: Camouflage |
| 2332 | 520532 | 110009 | 110016 | 어두운 밤의 비너스 | Dark Night Venus |
| 2333 | 520533 | 110009 | 110016 | 거울 속의 고양이 | Cat in Mirror |
| 2334 | 520534 | 110009 | 110016 | 큐트·패닉·서머 | Cute Summer Panic |
| 2335 | 520535 | 110009 | 110016 | 매니저의 여름 | Manager's Summer |
| 2336 | 520536 | 110009 | 110016 | 칠흑의 파괴자 | Dark Destroyer |
| 2337 | 520537 | 110009 | 110018 | 칠흑의 대적자 | Dark Contender |
| 2338 | 520538 | 110009 | 110016 | 바니 헌터 | Bunny Hunter |
| 2339 | 520539 | 110009 | 110016 | 문라이트 댄서 | Moonlight Dancer |
| 2340 | 520540 | 110009 | 110016 | 나이트메어 쉽 | Nightmare Sheep |
| 2341 | 520541 | 110009 | 110016 | 살랑살랑 폭시 나이트 | Whimsical Foxy Nightwear |
| 2342 | 520542 | 110009 | 110020 | 로열 나인 | Royal Nine |
| 2343 | 520543 | 110009 | 110016 | 운명의 긴 그림자 | Looming Shadow of Destiny |
| 2344 | 520544 | 110009 | 110016 | 마이 페어 레이디 | My Fair Lady |
| 2345 | 520545 | 110009 | 110020 | 수줍은 개화 | Bashful Blossom |
| 2346 | 520546 | 110009 | 110018 | 입었노라, 세일러복! | Sailor Uniform Donned! |
| 2347 | 520547 | 110009 | 110020 | 아수라의 환상 | Asura's Illusion |
| 2348 | 520548 | 110009 | 110016 | 흑접지몽 | Black Butterfly's Dream |
| 2349 | 520549 | 110009 | 110018 | 악접지몽 | Evil Butterfly's Dream |
| 2350 | 520550 | 110009 | 110016 | 스노우 메르헨 | Snow Fantasy |
| 2351 | 520551 | 110009 | 110016 | 레디메이드 홀리데이 | Ready for the Holidays |
| 2352 | 520552 | 110009 | 110016 | 봄버 캐롤!! | Festive Bomber |
| 2353 | 520553 | 110009 | 110018 | 기만의 악마 | Demon of Deception |
| 2354 | 520554 | 110009 | 110020 | 한낮의 꽃잎 | Petals of Midday |
| 2355 | 520555 | 110009 | 110020 | 코드: 이머전시 | Code: Emergency |
| 2356 | 520556 | 110009 | 110016 | 자애의 햇살 | Gracious Sunlight |
| 2357 | 520557 | 110009 | 110016 | 재복의 도래 | Unfolding Fortune |
| 2358 | 520558 | 110009 | 110016 | 희망찬 한 걸음 | Hopeful First Step |
| 2359 | 520559 | 110009 | 110018 | 태양의 그늘 | Shade of the Sun |
| 2360 | 520560 | 110009 | 110020 | 심연의 마녀 | Witch of the Abyss |
| 2361 | 520561 | 110009 | 110016 | 새로운 봄바람 | Fresh Spring Breeze |
| 2362 | 520562 | 110009 | 110018 | 도원향 | Fragrant Peach Blossoms |
| 2363 | 520563 | 110009 | 110020 | 난공불락 | Impenetrable Protection |
| 2364 | 520564 | 110009 | 110016 | 장수의 마음 | Heart of a General |
| 2365 | 520565 | 110009 | 110016 | 속세 나들이 | Visiting the Outside World |
| 2366 | 520566 | 110009 | 110020 | 주단의 흑호 | Black Tiger in Silk |
| 2367 | 520567 | 110009 | 110016 | 프로젝트: 이데아 | Project: Idea |
| 2368 | 520568 | 110009 | 110016 | 미궁 브레이커 | Labyrinth Breaker |
| 2369 | 520569 | 110009 | 110018 | 청해의 인어 | Mermaid of the Blue Sea |
| 2370 | 520570 | 110009 | 110020 | 봄의 물보라 | Springtime Water Splash |
| 2371 | 520571 | 110009 | 110016 | 공주는 출장 중! | Princess on Official Business! |
| 2372 | 520572 | 110009 | 110018 | 실버 라이닝 | Silver Lining |
| 2373 | 520573 | 110009 | 110020 | 한밤중의 오로라 | Midnight Aurora |
| 2374 | 520574 | 110009 | 110016 | 현자의 제자 | Sage's Disciple |
| 2375 | 520575 | 110009 | 110018 | 모드: 오피스 | Mode: Office |
| 2376 | 520576 | 110009 | 110020 | 결전 장비: 백설 | Endgame Gear: White Snow |
| 2377 | 520577 | 110009 | 110016 | CODE NAME: ALL-IN | CODE NAME: ALL-IN |
| 2378 | 520578 | 110009 | 110020 | 깊은 구덩이 | Deep Pit |
| 2381 | 520581 | 110009 | 110016 | Maid In Perfection | Maid in Perfection |
| 2382 | 520582 | 110009 | 110016 | 햇님을 위한 메이드복 | Maid Uniform for the Sun |
| 2383 | 520583 | 110009 | 110016 | 달님을 위한 메이드복 | Maid Uniform for the Moon |
| 2384 | 520584 | 110009 | 110018 | 새출발의 발걸음 | Strides of a Fresh Start |
| 2385 | 520585 | 110009 | 110020 | 오지 않은 미래 | Unrealized Future |
| 2386 | 520586 | 110009 | 110018 | 데일리 언더테이크 | Daily Undertaker |
| 2387 | 520587 | 110009 | 110018 | 커버링 언더테이크 | Undertaker's Covering |
| 2388 | 520589 | 110009 | 110016 | 조소하는 자 | The Scorner |
| 2389 | 520590 | 110009 | 110020 | 사랑스러운 충동 | Lovely Impulse |
| 2390 | 520591 | 110009 | 110016 | 프리즈너스 홀리데이 | Prisoner's Holiday |
| 2391 | 520592 | 110009 | 110016 | 셀러브리티 홀리데이 | Celebrity Holiday |
| 2392 | 520593 | 110009 | 110016 | 로맨싱 섬머 | Romancing Summer |
| 2393 | 520594 | 110009 | 110016 | 모데스티 홀리데이 | Modesty Holiday |
| 2394 | 520595 | 110009 | 110016 | 코드 퍼플 | Code Purple |
| 2395 | 520588 | 110009 | 110020 | 밤의 마리오네트 | Marionette of Night |
| 2396 | 520596 | 110009 | 110016 | 글로리아 팝 | Gloria Pop |
| 2397 | 520597 | 110009 | 110016 | 러블리 팝 | Lovely Pop |
| 2398 | 520598 | 110009 | 110016 | 폴링시크 팝 | Falling Chic Pop |
| 2399 | 520599 | 110009 | 110016 | 백성의 생활 | Civilian Life |
| 2400 | 520600 | 110009 | 110020 | 고귀한 핏줄 | Noble Bloodline |
| 2401 | 520601 | 110009 | 110018 | 나이트로즈 | Night Rose |
| 2402 | 520602 | 110009 | 110020 | 파이어스타터 | Fire Starter |
| 2403 | 520603 | 110009 | 110016 | 심플 이즈 베스트 | Simple Is Best |
| 2404 | 520604 | 110009 | 110018 | 해상 취객 | Seafaring Drunkard |
| 2405 | 520605 | 110009 | 110020 | 뒷골목의 방랑자 | Backalley Drifter |
| 2406 | 520606 | 110009 | 110016 | 소매치기의 잔상 | Pickpocket Afterimage |
| 2407 | 520607 | 110009 | 110020 | 광휘의 그림자 | Shadow of Radiance |
| 2408 | 520608 | 110009 | 110020 | 타오르는 태양의 의복 | Blazing Sun Garment |
| 2409 | 520609 | 110009 | 110020 | 알레그로 비바체 | Allegro Vivace |
| 2410 | 520610 | 110009 | 110020 | 거짓된 수호의 증표 | False Token of Guardianship |
| 2411 | 520611 | 110009 | 110020 | 제국의 공작 | Imperial Duchess |
| 2412 | 520612 | 110009 | 110020 | 순결한 영혼 | Pure Spirit |
| 2413 | 520613 | 110009 | 110020 | 우주의 소리 | Cosmic Sound |
| 2414 | 520614 | 110009 | 110020 | 새로운 봄의 시작 | Beginning of New Spring |
| 2415 | 520615 | 110009 | 110018 | 마지막 선택 | Final Choice |
| 2416 | 520616 | 110009 | 110020 | 신벌의 불꽃 | Flames of Divine Retribution |
| 2417 | 520617 | 110009 | 110016 | 해피 바니 크리스마스 | Happy Bunny Christmas |
| 2418 | 520618 | 110009 | 110016 | 순백의 오퍼레이터 | Pure White Operator |
| 2419 | 520619 | 110009 | 110020 | 몽환의 화원 | Dreamy Flower Garden |
| 2420 | 520620 | 110009 | 110018 | 낮과 밤의 경계 | Between Day and Night |
| 2421 | 520621 | 110009 | 110020 | 추락하는 태양의 의복 | Falling Sun Garment |
| 2422 | 520622 | 110009 | 110016 | 새해의 아이돌 | New Year's Idol |
| 2423 | 520623 | 110009 | 110016 | 새로운 종말 | A New End |
| 2424 | 520624 | 110009 | 110018 | 월식악몽 | Lunar Eclipse Nightmare |
| 2425 | 520625 | 110009 | 110020 | 만월인연 | Full Moon Connection |
| 2700 | 0 | 110009 | 110011 |  |  |
| 2701 | 0 | 110009 | 110011 |  |  |
| 2702 | 0 | 110009 | 110011 |  |  |
| 2703 | 0 | 110009 | 110011 |  |  |
| 2704 | 0 | 110009 | 110011 |  |  |
| 2705 | 0 | 110009 | 110011 |  |  |
| 2706 | 0 | 110009 | 110011 |  |  |
| 2707 | 0 | 110009 | 110011 |  |  |
| 2708 | 0 | 110009 | 110011 |  |  |
| 2709 | 0 | 110009 | 110011 |  |  |
| 2710 | 0 | 110009 | 110011 |  |  |
| 2711 | 0 | 110009 | 110011 |  |  |
| 2712 | 0 | 110009 | 110011 |  |  |
| 2713 | 0 | 110009 | 110011 |  |  |
| 2714 | 0 | 110009 | 110011 |  |  |
| 2715 | 0 | 110009 | 110011 |  |  |
| 2716 | 0 | 110009 | 110011 |  |  |
| 2717 | 0 | 110009 | 110011 |  |  |
| 2718 | 0 | 110009 | 110011 |  |  |
| 2719 | 0 | 110009 | 110011 |  |  |
| 2720 | 0 | 110009 | 110011 |  |  |
| 2721 | 0 | 110009 | 110011 |  |  |
| 2722 | 0 | 110009 | 110011 |  |  |
| 2723 | 0 | 110009 | 110011 |  |  |
| 2724 | 0 | 110009 | 110011 |  |  |
| 2725 | 0 | 110009 | 110011 |  |  |
| 2726 | 0 | 110009 | 110011 |  |  |
| 2727 | 0 | 110009 | 110011 |  |  |
| 2728 | 0 | 110009 | 110011 |  |  |
| 2729 | 0 | 110009 | 110011 |  |  |
| 2730 | 0 | 110009 | 110011 |  |  |
| 2731 | 0 | 110009 | 110011 |  |  |
| 2732 | 0 | 110009 | 110011 |  |  |
| 2733 | 0 | 110009 | 110011 |  |  |
| 2734 | 0 | 110009 | 110011 |  |  |
| 2735 | 0 | 110009 | 110011 |  |  |
| 2736 | 0 | 110009 | 110011 |  |  |
| 2737 | 0 | 110009 | 110011 |  |  |
| 2738 | 0 | 110009 | 110011 |  |  |
| 2739 | 0 | 110009 | 110011 |  |  |
| 2740 | 0 | 110009 | 110011 |  |  |
| 2741 | 0 | 110009 | 110011 |  |  |
| 2742 | 0 | 110009 | 110011 |  |  |
| 2743 | 0 | 110009 | 110011 |  |  |
| 2744 | 0 | 110009 | 110011 |  |  |
| 2745 | 0 | 110009 | 110011 |  |  |
| 2746 | 0 | 110009 | 110011 |  |  |
| 2747 | 0 | 110009 | 110011 |  |  |
| 2748 | 0 | 110009 | 110011 |  |  |
| 2749 | 0 | 110009 | 110011 |  |  |
| 2750 | 0 | 110009 | 110011 |  |  |
| 2751 | 0 | 110009 | 110011 |  |  |
| 2752 | 0 | 110009 | 110011 |  |  |
| 2753 | 0 | 110009 | 110011 |  |  |
| 2754 | 0 | 110009 | 110011 |  |  |
| 2755 | 0 | 110009 | 110011 |  |  |
| 2756 | 0 | 110009 | 110011 |  |  |
| 2757 | 0 | 110009 | 110011 |  |  |
| 2758 | 0 | 110009 | 110011 |  |  |
| 2759 | 0 | 110009 | 110011 |  |  |
| 2760 | 0 | 110009 | 110011 |  |  |
| 2761 | 0 | 110009 | 110011 |  |  |
| 2762 | 0 | 110009 | 110011 |  |  |
| 2763 | 0 | 110009 | 110011 |  |  |
| 2764 | 0 | 110009 | 110011 |  |  |
| 2765 | 0 | 110009 | 110011 |  |  |
| 2766 | 0 | 110009 | 110011 |  |  |
| 2767 | 0 | 110009 | 110011 |  |  |
| 2768 | 0 | 110009 | 110011 |  |  |
| 2769 | 0 | 110009 | 110011 |  |  |
| 2770 | 0 | 110009 | 110011 |  |  |
| 2771 | 0 | 110009 | 110011 |  |  |
| 2772 | 0 | 110009 | 110011 |  |  |
| 2773 | 0 | 110009 | 110011 |  |  |
| 2774 | 0 | 110009 | 110011 |  |  |
| 2775 | 0 | 110009 | 110011 |  |  |
| 2776 | 0 | 110009 | 110011 |  |  |
| 2777 | 0 | 110009 | 110011 |  |  |
| 2778 | 0 | 110009 | 110011 |  |  |
| 2779 | 0 | 110009 | 110011 |  |  |
| 2780 | 0 | 110009 | 110011 |  |  |
| 2781 | 0 | 110009 | 110011 |  |  |
| 2782 | 0 | 110009 | 110011 |  |  |
| 2783 | 0 | 110009 | 110011 |  |  |
| 2784 | 0 | 110009 | 110011 |  |  |
| 2785 | 0 | 110009 | 110011 |  |  |
| 2786 | 0 | 110009 | 110011 |  |  |
| 2787 | 0 | 110009 | 110011 |  |  |
| 2788 | 0 | 110009 | 110011 |  |  |
| 2789 | 0 | 110009 | 110011 |  |  |
| 2790 | 0 | 110009 | 110011 |  |  |
| 2791 | 0 | 110009 | 110011 |  |  |
| 2792 | 0 | 110009 | 110011 |  |  |
| 2793 | 0 | 110009 | 110011 |  |  |
| 2794 | 0 | 110009 | 110011 |  |  |
| 2795 | 0 | 110009 | 110011 |  |  |
| 2796 | 0 | 110009 | 110011 |  |  |
| 2797 | 0 | 110009 | 110011 |  |  |
| 2798 | 0 | 110009 | 110011 |  |  |
| 2799 | 0 | 110009 | 110011 |  |  |
| 2800 | 0 | 110009 | 110011 |  |  |
| 2801 | 0 | 110009 | 110011 |  |  |
| 2802 | 0 | 110009 | 110011 |  |  |
| 2803 | 0 | 110009 | 110011 |  |  |
| 2804 | 0 | 110009 | 110011 |  |  |
| 2805 | 0 | 110009 | 110011 |  |  |
| 2806 | 0 | 110009 | 110011 |  |  |
| 2807 | 0 | 110009 | 110011 |  |  |
| 2808 | 0 | 110009 | 110011 |  |  |
| 2809 | 0 | 110009 | 110011 |  |  |
| 2810 | 0 | 110009 | 110011 |  |  |
| 2811 | 0 | 110009 | 110011 |  |  |
| 2812 | 0 | 110009 | 110011 |  |  |
| 2813 | 0 | 110009 | 110011 |  |  |
| 2814 | 0 | 110009 | 110011 |  |  |
| 2815 | 0 | 110009 | 110011 |  |  |
| 2816 | 0 | 110009 | 110011 |  |  |
| 2817 | 0 | 110009 | 110011 |  |  |
| 2818 | 0 | 110009 | 110011 |  |  |
| 2819 | 0 | 110009 | 110011 |  |  |
| 2820 | 0 | 110009 | 110011 |  |  |
| 2821 | 0 | 110009 | 110011 |  |  |
| 2822 | 0 | 110009 | 110011 |  |  |
| 2823 | 0 | 110009 | 110011 |  |  |
| 2824 | 0 | 110009 | 110011 |  |  |
| 2825 | 0 | 110009 | 110011 |  |  |
| 2826 | 0 | 110009 | 110011 |  |  |
| 2827 | 0 | 110009 | 110011 |  |  |
| 2828 | 0 | 110009 | 110011 |  |  |
| 2829 | 0 | 110009 | 110011 |  |  |
| 2830 | 0 | 110009 | 110011 |  |  |
| 2831 | 0 | 110009 | 110011 |  |  |
| 2832 | 0 | 110009 | 110011 |  |  |
| 2833 | 0 | 110009 | 110011 |  |  |
| 2834 | 0 | 110009 | 110011 |  |  |
| 2835 | 0 | 110009 | 110011 |  |  |
| 2836 | 0 | 110009 | 110011 |  |  |
| 2998 | 520998 | 110009 | 110016 | 밀키웨이 보이스 | Milky Way Voice |
| 2999 | 520999 | 110009 | 110016 | 스타라이트 리듬 | Starlight Rhythm |
| 3001 | 213001 | 110008 | 110011 | 방치 골드 (2시간) | Idle Gold (2 Hours) |
| 3002 | 213002 | 110008 | 110012 | 방치 골드 (6시간) | Idle Gold (6 Hours) |
| 3003 | 213003 | 110008 | 110014 | 방치 골드 (12시간) | Idle Gold (12 Hours) |
| 3004 | 213004 | 110008 | 110016 | 방치 골드 (24시간) | Idle Gold (24 Hours) |
| 3006 | 213006 | 110008 | 110011 | 방치 마나 더스트 (2시간) | Idle Mana Dust (2 Hours) |
| 3007 | 213007 | 110008 | 110012 | 방치 마나 더스트 (6시간) | Idle Mana Dust (6 Hours) |
| 3008 | 213008 | 110008 | 110014 | 방치 마나 더스트 (12시간) | Idle Mana Dust (12 Hours) |
| 3009 | 213009 | 110008 | 110016 | 방치 마나 더스트 (24시간) | Idle Mana Dust (24 Hours) |
| 3011 | 213011 | 110008 | 110014 | 방치 마나 크리스탈 (2시간) | Idle Mana Crystal (2 Hours) |
| 3012 | 213012 | 110008 | 110014 | 방치 마나 크리스탈 (6시간) | Idle Mana Crystal (6 Hours) |
| 3013 | 213013 | 110008 | 110014 | 방치 마나 크리스탈 (12시간) | Idle Mana Crystal (12 Hours) |
| 3014 | 213014 | 110008 | 110016 | 방치 마나 크리스탈 (24시간) | Idle Mana Crystal (24 Hours) |
| 3021 | 213021 | 110008 | 110014 | 재화 꾸러미 (2시간) | Resource Bundle (2 Hours) |
| 3022 | 213022 | 110008 | 110014 | 재화 꾸러미 (6시간) | Resource Bundle (6 Hours) |
| 3023 | 213023 | 110008 | 110014 | 재화 꾸러미 (12시간) | Resource Bundle (12 Hours) |
| 3024 | 213024 | 110008 | 110016 | 재화 꾸러미 (24시간) | Resource Bundle (24 Hours) |
| 3201 | 213201 | 110008 | 110012 | 정령의 기억: 리타 | Soul's Memory: Rita |
| 3202 | 213202 | 110008 | 110012 | 정령의 기억: 로제 | Soul's Memory: Rose |
| 3203 | 213203 | 110008 | 110012 | 정령의 기억: 샤링 | Soul's Memory: Sharinne |
| 3204 | 213204 | 110008 | 110012 | 정령의 기억: 루리 | Soul's Memory: Ruri |
| 3205 | 213205 | 110008 | 110012 | 정령의 기억: 알리샤 | Soul's Memory: Alisha |
| 3206 | 213206 | 110008 | 110012 | 정령의 기억: 르웨인 | Soul's Memory: Lewayne |
| 3207 | 213207 | 110008 | 110012 | 정령의 기억: 무명 | Soul's Memory: Nameless |
| 3208 | 213208 | 110008 | 110012 | 정령의 기억: 카렌 | Soul's Memory: Karen |
| 3301 | 213301 | 110008 | 110014 | 정령의 기억: 메피스토펠레스 | Soul's Memory: Mephistopheles |
| 3302 | 213302 | 110008 | 110014 | 정령의 기억: 벨레드 | Soul's Memory: Beleth |
| 3303 | 213303 | 110008 | 110014 | 정령의 기억: 클레르 | Soul's Memory: Claire |
| 3304 | 213304 | 110008 | 110014 | 정령의 기억: 아키 | Soul's Memory: Aki |
| 3305 | 213305 | 110008 | 110014 | 정령의 기억: 제이드 | Soul's Memory: Jade |
| 3306 | 213306 | 110008 | 110014 | 정령의 기억: 린지 | Soul's Memory: Linzy |
| 3307 | 213307 | 110008 | 110014 | 정령의 기억: 홍란 | Soul's Memory: Honglan |
| 3308 | 213308 | 110008 | 110014 | 정령의 기억: 순이 | Soul's Memory: Soonie |
| 3309 | 213309 | 110008 | 110014 | 정령의 기억: 아이라 | Soul's Memory: Aira |
| 3310 | 213310 | 110008 | 110014 | 정령의 기억: 시하 | Soul's Memory: Seeha |
| 3311 | 213311 | 110008 | 110014 | 정령의 기억: 미카 | Soul's Memory: Mica |
| 3312 | 213312 | 110008 | 110014 | 정령의 기억: 에리카 | Soul's Memory: Erika |
| 3313 | 213313 | 110008 | 110014 | 정령의 기억: 이나 | Soul's Memory: Ina |
| 3314 | 213314 | 110008 | 110014 | 정령의 기억: 르네 | Soul's Memory: Renee |
| 3315 | 213315 | 110008 | 110014 | 정령의 기억: 탈리아 | Soul's Memory: Talia |
| 3316 | 213316 | 110008 | 110014 | 정령의 기억: 칸나 | Soul's Memory: Kanna |
| 3317 | 213317 | 110008 | 110014 | 정령의 기억: 이디스 | Soul's Memory: Edith |
| 3318 | 213318 | 110008 | 110014 | 정령의 기억: 비올레트 | Soul's Memory: Violette |
| 3319 | 213319 | 110008 | 110014 | 정령의 기억: 가넷 | Soul's Memory: Garnet |
| 3320 | 213320 | 110008 | 110014 | 정령의 기억: 레베카 | Soul's Memory: Rebecca |
| 3321 | 213321 | 110008 | 110014 | 정령의 기억: 멜피스 | Soul's Memory: Melfice |
| 3322 | 213322 | 110008 | 110014 | 정령의 기억: 브라이스 | Soul's Memory: Bryce |
| 3323 | 213323 | 110008 | 110014 | 정령의 기억: 프림 | Soul's Memory: Prim |
| 3324 | 213324 | 110008 | 110014 | 정령의 기억: 클라우디아 | Soul's Memory: Claudia |
| 3325 | 213325 | 110008 | 110014 | 정령의 기억: 헬레나 | Soul's Memory: Helena |
| 3326 | 213326 | 110008 | 110014 | 정령의 기억: 벨라나 | Soul's Memory: Velanna |
| 3327 | 213327 | 110008 | 110014 | 정령의 기억: 아야메 | Soul's Memory: Ayame |
| 3328 | 213328 | 110008 | 110014 | 정령의 기억: 재클린 | Soul's Memory: Jacqueline |
| 3329 | 213329 | 110008 | 110014 | 정령의 기억: 나오미 | Soul's Memory: Naomi |
| 3330 | 213330 | 110008 | 110014 | 정령의 기억: 조앤 | Soul's Memory: Joanne |
| 3331 | 213331 | 110008 | 110014 | 정령의 기억: 메릴 | Soul's Memory: Meryl |
| 3332 | 213332 | 110008 | 110014 | 정령의 기억: 플린 | Soul's Memory: Flynn |
| 3333 | 213333 | 110008 | 110014 | 정령의 기억: 타샤 | Soul's Memory: Tasha |
| 3334 | 213334 | 110008 | 110014 | 정령의 기억: 니콜 | Soul's Memory: Nicole |
| 3335 | 213335 | 110008 | 110014 | 정령의 기억: 비비안 | Soul's Memory: Vivienne |
| 3336 | 213336 | 110008 | 110014 | 정령의 기억: 아드리안 | Soul's Memory: Adrianne |
| 3337 | 213337 | 110008 | 110014 | 정령의 기억: 사논 | Soul's Memory: Sanon |
| 3338 | 213338 | 110008 | 110014 | 정령의 기억: 리젤로테 | Soul's Memory: Lizelotte |
| 3339 | 213339 | 110008 | 110014 | 정령의 기억: 캐서린 | Soul's Memory: Catherine |
| 3340 | 213340 | 110008 | 110014 | 정령의 기억: 셰리 | Soul's Memory: Cherrie |
| 3341 | 213341 | 110008 | 110014 | 정령의 기억: 도라 | Soul's Memory: Dora |
| 3342 | 213342 | 110008 | 110014 | 정령의 기억: 하루 | Soul's Memory: Haru |
| 3343 | 213343 | 110008 | 110014 | 정령의 기억: 루테 | Soul's Memory: Lute |
| 3344 | 213344 | 110008 | 110014 | 정령의 기억: 클라라 | Soul's Memory: Clara |
| 3345 | 213345 | 110008 | 110014 | 정령의 기억: 미리암 | Soul's Memory: Miriam |
| 3346 | 213346 | 110008 | 110014 | 정령의 기억: 클로이 | Soul's Memory: Chloe |
| 3347 | 213347 | 110008 | 110014 | 정령의 기억: 나이아 | Soul's Memory: Naiah |
| 3348 | 213348 | 110008 | 110014 | 정령의 기억: 에루샤 | Soul's Memory: Erusha |
| 3349 | 213349 | 110008 | 110014 | 정령의 기억: 페트라 | Soul's Memory: Petra |
| 3350 | 213350 | 110008 | 110014 | 정령의 기억: 니니 | Soul's Memory: Nini |
| 3351 | 213351 | 110008 | 110014 | 정령의 기억: 지호 | Soul's Memory: Jiho |
| 3352 | 213352 | 110008 | 110014 | 정령의 기억: 헤이즐 | Soul's Memory: Hazel |
| 3353 | 213353 | 110008 | 110014 | 정령의 기억: 소연 | Soul's Memory: Xiaolian |
| 3354 | 213354 | 110008 | 110014 | 정령의 기억: 마농 | Soul's Memory: Manon |
| 3355 | 213355 | 110008 | 110014 | 정령의 기억: 다프네 | Soul's Memory: Daphne |
| 3357 | 213356 | 110008 | 110014 | 정령의 기억: 유리아 | Soul's Memory: Yuria |
| 3358 | 213358 | 110008 | 110014 | 정령의 기억: 에일린 | Soul's Memory: Eileen |
| 3359 | 213359 | 110008 | 110014 | 정령의 기억: 오토하 | Soul's Memory: Otoha |
| 3360 | 213360 | 110008 | 110014 | 정령의 기억: 이브 | Soul's Memory: Eve |
| 3361 | 213361 | 110008 | 110014 | 정령의 기억: 사쿠요 | Soul's Memory: Sakuyo |
| 3362 | 213362 | 110008 | 110014 | 정령의 기억: 캐서린(광휘) | Soul's Memory: Catherine (Radiance) |
| 3363 | 213363 | 110008 | 110014 | 정령의 기억: 도미니크 | Soul's Memory: Dominique |
| 3364 | 213364 | 110008 | 110014 | 정령의 기억: 토키사키 쿠루미 | Soul's Memory: Kurumi Tokisaki |
| 3365 | 213365 | 110008 | 110014 | 정령의 기억: 야토가미 토카 | Soul's Memory: Tohka Yatogami |
| 3366 | 213366 | 110008 | 110014 | 정령의 기억: 라리마 | Soul's Memory: Larimar |
| 3367 | 213367 | 110008 | 110014 | 봉인된 이차원의 정수 | Sealed Essence of Another Dimension |
| 3368 | 213368 | 110008 | 110014 | 정령의 기억: 시그리드 | Soul's Memory: Sigrid |
| 3369 | 213369 | 110008 | 110014 | 정령의 기억: 오닉스 | Soul's Memory: Onyx |
| 3370 | 213370 | 110008 | 110014 | 정령의 기억: 린지(타나토스) | Soul's Memory: Linzy (Thanatos) |
| 3371 | 213371 | 110008 | 110014 | 정령의 기억: 릴리트 | Soul's Memory: Lilith |
| 3372 | 213372 | 110008 | 110014 | 정령의 기억: 웨리 | Soul's Memory: Wheri |
| 3373 | 213373 | 110008 | 110014 | 정령의 기억: 사쿠요(업화) | Soul's Memory: Sakuyo (Inferno) |
| 3374 | 213374 | 110008 | 110014 | 정령의 기억: 메피스토펠레스(여명) | Soul's Memory: Mephistopheles (Dawn) |
| 3375 | 213375 | 110008 | 110014 | 정령의 기억: 바이스 | Soul's Memory: Weiss |
| 3376 | 213376 | 110008 | 110014 | 정령의 기억: 로제(홍염) | Soul's Memory: Rose (Prominence) |
| 3377 | 213377 | 110008 | 110014 | 정령의 기억: 지호(미르) | Soul's Memory: Jiho (Mir) |
| 3378 | 213378 | 110008 | 110014 | 정령의 기억: 홍란(무쌍) | Soul's Memory: Honglan (Peerless) |
| 3379 | 213379 | 110008 | 110014 | 정령의 기억: 하루(카무이) | Soul's Memory: Haru (Kamuy) |
| 3380 | 213380 | 110008 | 110014 | 정령의 기억: 르네(백은) | Soul's Memory: Renee (Argent) |
| 3381 | 213381 | 110008 | 110014 | 정령의 기억: 미리암(잔영) | Soul's Memory: Miriam (Afterimage) |
| 3382 | 213382 | 110008 | 110014 | 정령의 기억: 라우라 | Soul's Memory: Laura |
| 3383 | 213383 | 110008 | 110014 | 정령의 기억: 페트라(각혼) | Soul's Memory: Petra (Awakened Soul) |
| 3384 | 213384 | 110008 | 110014 | 정령의 기억: 가넷(열락) | Soul's Memory: Garnet (Rapture) |
| 3385 | 213385 | 110008 | 110014 | 정령의 기억: 한울 | Soul's Memory: Hanul |
| 3386 | 213386 | 110008 | 110014 | 정령의 기억: 카넬리안 | Soul's Memory: Carnelian |
| 3387 | 213387 | 110008 | 110014 | 정령의 기억: 니아 | Soul's Memory: Nia |
| 3388 | 213388 | 110008 | 110014 | 정령의 기억: 셰리(낭만) | Soul's Memory: Cherrie (Romantic) |
| 3389 | 213389 | 110008 | 110014 | 정령의 기억: 클라우디아(대천사) | Soul's Memory: Claudia (Archangel) |
| 3390 | 213390 | 110008 | 110014 | 정령의 기억: 유리아 (아폴리온) | Soul's Memory: Yuria (Apollyon) |
| 3391 | 213391 | 110008 | 110014 | 정령의 기억: 아야메 (츠쿠요미) | Soul's Memory: Ayame (Tsukuyomi) |
| 3501 | 213501 | 110008 | 110017 | 정령의 기억: 리타 (레전더리+) | Soul's Memory: Rita (Legendary+) |
| 3502 | 213502 | 110008 | 110017 | 정령의 기억: 로제 (레전더리+) | Soul's Memory: Rose (Legendary+) |
| 3503 | 213503 | 110008 | 110017 | 정령의 기억: 샤링 (레전더리+) | Soul's Memory: Sharinne (Legendary+) |
| 3504 | 213504 | 110008 | 110017 | 정령의 기억: 루리 (레전더리+) | Soul's Memory: Ruri (Legendary+) |
| 3505 | 213505 | 110008 | 110017 | 정령의 기억: 알리샤 (레전더리+) | Soul's Memory: Alisha (Legendary+) |
| 3506 | 213506 | 110008 | 110017 | 정령의 기억: 르웨인 (레전더리+) | Soul's Memory: Lewayne (Legendary+) |
| 3507 | 213507 | 110008 | 110017 | 정령의 기억: 무명 (레전더리+) | Soul's Memory: Nameless (Legendary+) |
| 3508 | 213508 | 110008 | 110017 | 정령의 기억: 카렌 (레전더리+) | Soul's Memory: Karen (Legendary+) |
| 3509 | 213509 | 110008 | 110015 | 정령의 기억: 로제 (에픽+) | Soul's Memory: Rose (Epic+) |
| 3510 | 213510 | 110008 | 110020 | 정령의 기억: 메피스토펠레스 (오리진) | Soul's Memory: Mephistopheles (Origin) |
| 3511 | 213511 | 110008 | 110017 | 정령의 기억: 도미니크 (레전더리+) | Soul's Memory: Dominique (Legendary+) |
| 3512 | 213512 | 110008 | 110017 | 정령의 기억: 시그리드(레전더리+) | Soul's Memory: Sigrid (Legendary+) |
| 3513 | 213513 | 110008 | 110017 | 정령의 기억: 벨레드 (레전더리+) | Soul's Memory: Beleth (Legendary+) |
| 4001 | 214001 | 110006 | 110018 | 추석 복주머니 | Chuseok Lucky Pouch |
| 4002 | 214002 | 110006 | 110014 | 예장 선택 상자 (에픽) | Keepsake Selection Chest (Epic) |
| 4003 | 214003 | 110006 | 110016 | 고급 유물석 상자 | Expert Artifact Stone Chest |
| 4004 | 214004 | 110006 | 110014 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 4005 | 214005 | 110006 | 110016 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 4006 | 214006 | 110006 | 110018 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 4007 | 214007 | 110006 | 110014 | 승리자의 전리품 | Winner's Trophy |
| 4008 | 214008 | 110006 | 110018 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 4009 | 214009 | 110006 | 110014 | 특정 에픽 정령 선택 상자 | Specific Epic Soul Selection Chest |
| 4010 | 214010 | 110006 | 110014 | 에픽 정령 소환권 선택 상자 | Epic Soul Summon Ticket Selection Chest |
| 4011 | 214011 | 110006 | 110012 | 레어 정령 소환권 선택 상자 | Rare Soul Summon Ticket Selection Chest |
| 4012 | 214012 | 110006 | 110014 | 에픽 정령 선택형 상자 (공격형) | Epic Soul Selection Chest (Attack) |
| 4013 | 214013 | 110006 | 110014 | 에픽 정령 선택형 상자 (방어형) | Epic Soul Selection Chest (Defense) |
| 4014 | 214014 | 110006 | 110014 | 에픽 정령 선택형 상자 (지원형) | Epic Soul Selection Chest (Support) |
| 4015 | 214015 | 110006 | 110014 | 에픽 정령 선택형 상자 D | Epic Soul Selection Chest D |
| 4016 | 214016 | 110006 | 110014 | 에픽 정령 선택 상자 | Epic Soul Selection Chest |
| 4017 | 214017 | 110006 | 110014 | 에덴 갓 탤런트 정령 상자 | Eden's Got Talent Soul Chest |
| 4018 | 214018 | 110006 | 110014 | 에픽 정령 선택형 상자 (1주년) | Epic Soul Selection Chest (1st Anniversary) |
| 4019 | 214019 | 110006 | 110012 | 설날 복주머니 | New Year's Lucky Pouch |
| 4020 | 214020 | 110006 | 110014 | 에픽 정령 선택 상자 (런칭) | Epic Soul Selection Chest (Launch) |
| 4101 | 214101 | 110006 | 110011 | 예장함 (일반) | Keepsake Chest (Common) |
| 4102 | 214102 | 110006 | 110012 | 예장함 (레어) | Keepsake Chest (Rare) |
| 4103 | 214103 | 110006 | 110013 | 예장함 (레어+) | Keepsake Chest (Rare+) |
| 4104 | 214104 | 110006 | 110014 | 예장함 (에픽) | Keepsake Chest (Epic) |
| 4105 | 214105 | 110006 | 110015 | 예장함 (에픽+) | Keepsake Chest (Epic+) |
| 4106 | 214106 | 110006 | 110016 | 예장함 (레전더리) | Keepsake Chest (Legendary) |
| 4107 | 214107 | 110006 | 110017 | 예장함 (레전더리+) | Keepsake Chest (Legendary+) |
| 4108 | 214108 | 110006 | 110018 | 예장함 (이터널) | Keepsake Chest (Eternal) |
| 4109 | 214109 | 110006 | 110019 | 예장함 (이터널+) | Keepsake Chest (Eternal+) |
| 4110 | 214110 | 110006 | 110020 | 예장함 (오리진) | Keepsake Chest (Origin) |
| 4112 | 214112 | 110006 | 110012 | 두근두근☆ 선물 뽑기 캡슐 | Pit-a-Pat☆ Gift Capsule |
| 4115 | 214115 | 110006 | 110016 | 애정 가득♡ 기념일 선물 상자 | Love Filled♡ Anniversary Gift Chest |
| 4117 | 214117 | 110006 | 110014 | 재화 선택 상자 (12시간) | Currency Selection Chest (12 Hours) |
| 4118 | 214118 | 110006 | 110016 | 재화 선택 상자 (24시간) | Currency Selection Chest (24 Hours) |
| 4119 | 214119 | 110006 | 110015 | 예장 선택 상자 (에픽+) | Keepsake Selection Chest (Epic+) |
| 4120 | 214120 | 110006 | 110012 | 사진기: 미카와 시하의 하루 | Camera: Mica and Seeha's Day |
| 4121 | 214121 | 110006 | 110018 | 힘 예장 선택 상자 (이터널) | STR Keepsake Selection Chest (Eternal) |
| 4122 | 214122 | 110006 | 110018 | 민첩 예장 선택 상자 (이터널) | DEX Keepsake Selection Chest (Eternal) |
| 4123 | 214123 | 110006 | 110016 | 숲지기의 선물 상자 | Forest Keeper's Gift Box |
| 4124 | 214124 | 110006 | 110018 | 세트 예장함 (이터널) | Set Keepsake Chest (Eternal) |
| 4125 | 214125 | 110006 | 110019 | 세트 예장함 (이터널+) | Set Keepsake Chest (Eternal+) |
| 4126 | 214126 | 110006 | 110016 | 종합 유물석 상자 | Artifact Stone Set Chest |
| 4127 | 214127 | 110006 | 110020 | 금형 선택 상자 (오리진) | Mold Selection Chest (Origin) |
| 4128 | 214128 | 110006 | 110020 | 금형 상자 (오리진) | Mold Chest (Origin) |
| 4129 | 214129 | 110006 | 110011 | 재화 선택 상자 (2시간) | Currency Selection Chest (2 Hours) |
| 4130 | 214130 | 110006 | 110012 | 재화 선택 상자 (6시간) | Currency Selection Chest (6 Hours) |
| 4131 | 214131 | 110006 | 110019 | 세트 예장 선택 상자 (이터널+) | Set Keepsake Selection Chest (Eternal+) |
| 4132 | 214132 | 110006 | 110014 | 프리미엄 선물 뽑기 캡슐 | Premium Gift Capsule |
| 4133 | 214133 | 110006 | 110019 | 특별 픽업 정령 선택 상자 | Special Pick-Up Soul Selection Chest |
| 4134 | 214134 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자(ver.1) | Special Epic Soul Selection Chest (Ver. 1) |
| 4135 | 214135 | 110006 | 110014 | 클래스 강화 회로 선택 상자 | Class Enhance Circuit Selection Chest |
| 4136 | 214136 | 110006 | 110014 | 클래스 강화 회로 랜덤 상자 | Class Enhance Circuit Random Chest |
| 4137 | 214137 | 110006 | 110018 | 세트 예장 선택 상자 (이터널) | Set Keepsake Selection Chest (Eternal) |
| 4138 | 214138 | 110006 | 110021 | 금형 선택 상자 (오리진+1) | Mold Selection Chest (Origin+1) |
| 4139 | 214139 | 110006 | 110021 | 금형 상자 (오리진+1) | Mold Chest (Origin+1) |
| 4140 | 214140 | 110006 | 110018 | 유물의 기억 선택 상자 | Artifact Memory Selection Chest |
| 4141 | 214141 | 110006 | 110017 | 정령 타입 선택 상자 (레전더리+) | Soul Type Selection Chest (Legendary+) |
| 4142 | 214142 | 110006 | 110017 | 세트 예장 선택 상자 (레전더리+) | Set Keepsake Selection Chest (Legendary+) |
| 4143 | 214143 | 110006 | 110019 | 특별 픽업 정령 선택 상자 (Season 2) | Special Pick-Up Soul Selection Chest (Season 2) |
| 4144 | 214144 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (1.5주년) | Special Epic Soul Selection Chest (1.5-Year) |
| 4145 | 214145 | 110006 | 110020 | 세트 예장 선택 상자 (오리진) | Set Keepsake Selection Chest (Origin) |
| 4146 | 214146 | 110006 | 110019 | 에픽 정령 선택 상자 (1.5주년) | Epic Soul Selection Chest (1.5-Year) |
| 4147 | 214147 | 110006 | 110020 | 메피스토펠레스 (오리진) 지원 상자 | Mephistopheles (Origin) Support Chest |
| 4148 | 214148 | 110006 | 110018 | 유물의 기억 선택 상자 (1.5주년) | Artifact Memory Selection Chest (1.5-Year) |
| 4149 | 214149 | 110006 | 110019 | 에픽 정령 선택 상자 (2023) | Epic Soul Selection Chest (2023) |
| 4150 | 214150 | 110006 | 110014 | 에픽 정령 선택 상자 (추석 기념) | Epic Soul Selection Chest (Chuseok Celebration) |
| 4151 | 214151 | 110006 | 110012 | 사진기: 에덴 갓 탤런트 | Camera: Eden's Got Talent |
| 4152 | 214152 | 110006 | 110018 | 유물의 기억 선택 상자 (Half-Anniv) | Artifact Memory Selection Chest (Half-Anniv) |
| 4153 | 214153 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (런칭) | Special Epic Soul Selection Chest (Launch) |
| 4154 | 214154 | 110006 | 110019 | 에픽 정령 선택 상자 (런칭) | Epic Soul Selection Chest (Launch) |
| 4155 | 214155 | 110006 | 110019 | 에픽 정령 선택 상자 (2주년) | Epic Soul Selection Chest (2-Year) |
| 4156 | 214156 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (2주년) | Special Epic Soul Selection Chest (2-Year) |
| 4157 | 214157 | 110006 | 110016 | 예장 성장 선택 상자 | Keepsake Upgrade Selection Chest |
| 4158 | 214158 | 110006 | 110018 | 고급 예장 성장 선택 상자 | Fine Keepsake Upgrade Selection Chest |
| 4159 | 214159 | 110006 | 110020 | 최고급 예장 성장 선택 상자 | Exquisite Keepsake Upgrade Selection Chest |
| 4160 | 214160 | 110006 | 110018 | 유물의 기억 선택 상자 (2주년) | Artifact Memory Selection Chest (2-Year) |
| 4161 | 214161 | 110006 | 110016 | 이브의 날 기념 치킨 박스 | Eve's Day Chicken Box |
| 4162 | 214162 | 110006 | 110019 | 에픽 정령 선택 상자 (신년) | Epic Soul Selection Chest (New Year) |
| 4163 | 214163 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (신년) | Special Epic Soul Selection Chest (New Year) |
| 4164 | 214164 | 110006 | 110018 | 유물의 기억 선택 상자 (신년) | Artifact Memory Selection Chest (New Year) |
| 4165 | 214165 | 110006 | 110020 | 사진기: 거미님 일러스트 | Camera: 거미's Illustration |
| 4166 | 214166 | 110006 | 110018 | 사진기: 주상절리님 일러스트 | Camera: 주상절리's Illustration |
| 4167 | 214167 | 110006 | 110016 | 사진기: yuugen님 일러스트 | Camera: yuugen's Illustration |
| 4168 | 214168 | 110006 | 110014 | 사진기: 귄터님 일러스트 | Camera: 귄터's Illustration |
| 4169 | 214169 | 110006 | 110014 | 사진기: 고꾸닥님 일러스트 | Camera: 고꾸닥's Illustration |
| 4170 | 214170 | 110006 | 110020 | 설날 기념 복주머니 | New Year's Lucky Pouch |
| 4171 | 214171 | 110006 | 110020 | 큼직한 세뱃돈 봉투 | Large Gift Envelope |
| 4172 | 214172 | 110006 | 110018 | 세뱃돈 봉투 (지정 소환권) | Gift Envelope (Targeted Summon Tickets) |
| 4173 | 214173 | 110006 | 110018 | 세뱃돈 봉투 (유물 소환권) | Gift Envelope (Artifact Summon Tickets) |
| 4174 | 214174 | 110006 | 110018 | 세뱃돈 봉투 (에리카의 연금술 티켓) | Gift Envelope (Erika's Alchemy Tickets) |
| 4175 | 214175 | 110006 | 110016 | 사랑의 날 기념 초콜릿 상자 | Love Day Chocolate Box |
| 4176 | 214176 | 110006 | 110018 | 사이드 이벤트 행운 상자 | Side Event Lucky Chest |
| 4177 | 214177 | 110006 | 110016 | 마농의 특별 선물 상자 | Manon's Special Gift Box |
| 4178 | 214178 | 110006 | 110020 | 큼직한 럭키 박스 | Huge Lucky Chest |
| 4179 | 214179 | 110006 | 110018 | 럭키 박스 (지정 소환권) | Lucky Chest (Targeted Summon Ticket) |
| 4180 | 214180 | 110006 | 110018 | 럭키 박스 (유물 소환권) | Lucky Chest (Artifact Summon Ticket) |
| 4181 | 214181 | 110006 | 110018 | 럭키 박스 (에리카의 연금술 티켓) | Lucky Chest (Erika's Alchemy Ticket) |
| 4182 | 214182 | 110006 | 110019 | 에픽 정령 선택 상자 (2025) | Epic Soul Selection Chest (2025) |
| 4183 | 214183 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (2025) | Special Epic Soul Selection Chest (2025) |
| 4184 | 214184 | 110006 | 110018 | 유물의 기억 선택 상자 (2025) | Artifact Memory Selection Chest (2025) |
| 4188 | 214188 | 110006 | 110020 | 세트 예장함 (오리진) | Set Keepsake Chest (Origin) |
| 4189 | 214189 | 110006 | 110019 | 에픽 정령 선택 상자 (2.5주년) | Epic Soul Selection Chest (2.5-Year) |
| 4190 | 214190 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (2.5주년) | Special Epic Soul Selection Chest (2.5-Year) |
| 4191 | 214191 | 110006 | 110018 | 유물의 기억 선택 상자 (2.5주년) | Artifact Memory Selection Chest (2.5-Year) |
| 4192 | 214192 | 110006 | 110022 | 금형 선택 상자 (오리진+2) | Mold Selection Chest (Origin+2) |
| 4193 | 214193 | 110006 | 110022 | 금형 상자 (오리진+2) | Mold Chest (Origin+2) |
| 4194 | 214194 | 110006 | 110023 | 금형 선택 상자 (오리진+3) | Mold Selection Chest (Origin+3) |
| 4195 | 214195 | 110006 | 110023 | 금형 상자 (오리진+3) | Mold Chest (Origin+3) |
| 4196 | 214196 | 110006 | 110022 | 세트 예장 선택 상자 (오리진+2) | Set Keepsake Selection Chest (Origin+2) |
| 4197 | 214197 | 110006 | 110023 | 세트 예장 선택 상자 (오리진+3) | Set Keepsake Selection Chest (Origin+3) |
| 4198 | 214198 | 110006 | 110021 | 세트 예장 선택 상자 (오리진+1) | Set Keepsake Selection Chest (Origin+1) |
| 4199 | 214199 | 110006 | 110022 | 공격력/가속 세트 예장 상자 랜덤 상자(오리진+2) | Random ATK/Speed Set Keepsake Chest (Origin+2) |
| 4200 | 214200 | 110006 | 110020 | 춘절 선물상자 |  |
| 4201 | 214201 | 110008 | 110012 | 인간형 정령소환권 (레어) | Humanlike Soul Summon Ticket (Rare) |
| 4202 | 214202 | 110008 | 110012 | 야수형 정령소환권 (레어) | Beast Soul Summon Ticket (Rare) |
| 4203 | 214203 | 110008 | 110012 | 요정형 정령소환권 (레어) | Fairy Soul Summon Ticket (Rare) |
| 4204 | 214204 | 110008 | 110012 | 불사형 정령소환권 (레어) | Undead Soul Summon Ticket (Rare) |
| 4205 | 214205 | 110008 | 110014 | 인간형 정령소환권 (에픽) | Humanlike Soul Summon Ticket (Epic) |
| 4206 | 214206 | 110008 | 110014 | 야수형 정령소환권 (에픽) | Beast Soul Summon Ticket (Epic) |
| 4207 | 214207 | 110008 | 110014 | 요정형 정령소환권 (에픽) | Fairy Soul Summon Ticket (Epic) |
| 4208 | 214208 | 110008 | 110014 | 불사형 정령소환권 (에픽) | Undead Soul Summon Ticket (Epic) |
| 4209 | 214209 | 110008 | 110014 | 천사형 정령소환권 (에픽) | Angel Soul Summon Ticket (Epic) |
| 4210 | 214210 | 110008 | 110014 | 악마형 정령소환권 (에픽) | Demon Soul Summon Ticket (Epic) |
| 4211 | 214211 | 110006 | 110011 | 재화 선택 상자 (2시간) | Currency Selection Chest (2 Hours) |
| 4212 | 214212 | 110006 | 110012 | 재화 선택 상자 (6시간) | Currency Selection Chest (6 Hours) |
| 4213 | 214213 | 110006 | 110014 | 재화 선택 상자 (12시간) | Currency Selection Chest (12 Hours) |
| 4214 | 214214 | 110006 | 110016 | 재화 선택 상자 (24시간) | Currency Selection Chest (24 Hours) |
| 4220 | 214220 | 110006 | 110020 | 알쏭달쏭 마나 크리스탈 봉투 | Intriguing Mana Crystal Envelope |
| 4221 | 214221 | 110006 | 110020 | 알쏭달쏭 방주 강화 봉투 | Intriguing Ark Enhancement Envelope |
| 4222 | 214222 | 110006 | 110020 | 알쏭달쏭 소환 티켓 봉투 | Intriguing Summon Ticket Envelope |
| 4223 | 214223 | 110006 | 110024 | 금형 선택 상자 (오리진+4) | Mold Selection Chest (Origin+4) |
| 4224 | 214224 | 110006 | 110024 | 금형 상자 (오리진+4) | Mold Chest (Origin+4) |
| 4225 | 214225 | 110006 | 110019 | 에픽 정령 선택 상자 (3주년) | Epic Soul Selection Chest (3-Year) |
| 4226 | 214226 | 110006 | 110020 | 스페셜 에픽 정령 선택 상자 (3주년) | Special Epic Soul Selection Chest (3-Year) |
| 4227 | 214227 | 110006 | 110020 | 연금술 정령 선택 상자 | Alchemy Soul Selection Chest |
| 4228 | 214228 | 110006 | 110020 | 데일리 패키지 상자1 | Daily Package Chest 1 |
| 4229 | 214229 | 110006 | 110020 | 데일리 패키지 상자2 | Daily Package Chest 2 |
| 4230 | 214230 | 110006 | 110020 | 데일리 패키지 상자3 | Daily Package Chest 3 |
| 5000 | 215000 | 110007 | 110011 | 아케나인 광장 | Arkenine Square |
| 5001 | 215001 | 110007 | 110011 | 아케나인 다리 | Arkenine Bridge |
| 5002 | 215002 | 110007 | 110011 | 콜브 초원 | Colve Meadow |
| 5003 | 215003 | 110007 | 110011 | 다이난 호수 | Lake Dynan |
| 5004 | 215004 | 110007 | 110011 | 하얀 울새 숲 | White Robin Forest |
| 5005 | 215005 | 110007 | 110011 | 베르트 산맥 | Vert Mountains |
| 5006 | 215006 | 110007 | 110011 | 렉타 황무지 | Rechtar Wasteland |
| 5007 | 215007 | 110007 | 110011 | 비노 협곡 | Vino Valley |
| 5008 | 215008 | 110007 | 110011 | 모레노 사막 | Morreno Desert |
| 5009 | 215009 | 110007 | 110011 | 아르코 이리스 | Arco Iris |
| 5010 | 215010 | 110007 | 110011 | 쿠르 사바나 | Cur Savannah |
| 5011 | 215011 | 110007 | 110011 | 반딧불이의 둥지 | Nest of Fireflies |
| 5012 | 215012 | 110007 | 110011 | 라피아 정글 | Raffia Jungle |
| 5013 | 215013 | 110007 | 110011 | 나델 고산지 | Nadel Mountains |
| 5014 | 215014 | 110007 | 110011 | 그림자 없는 땅 | Shadowless Lands |
| 5015 | 215015 | 110007 | 110011 | 유령도시 모르투스 | Ghost City Mortus |
| 5016 | 215016 | 110007 | 110011 | 버려진 항구 | Forsaken Harbor |
| 5017 | 215017 | 110007 | 110011 | 메티아스 호 갑판 | Mettias Deck |
| 5018 | 215018 | 110007 | 110011 | 가르디눔 대설원 | Gardinum Snowfield |
| 5019 | 215019 | 110007 | 110011 | 루푸스 요새 | Lupus Fortress |
| 5020 | 215020 | 110007 | 110011 | 칸델레로 얼음 산맥 | Candellero Mountains |
| 5110 | 215110 | 110007 | 110011 | 학교 교실 | School Classroom |
| 5111 | 215111 | 110007 | 110011 | 학교 옥상 | School Rooftop |
| 5112 | 215112 | 110007 | 110011 | 학교 복도 | School Corridor |
| 5120 | 215120 | 110007 | 110011 | 클라라의 농장 | Clara Farm |
| 5121 | 215121 | 110007 | 110011 | 꽃밭 | Flower Field |
| 5122 | 215122 | 110007 | 110011 | 행운꽃밭 | Lucky Flower Field |
| 5130 | 215130 | 110007 | 110011 | 탐관오리 클로이 성채 | Corrupt Official Chloe Fortress |
| 5131 | 215131 | 110007 | 110011 | 가온의 온천 | Gaon's Hot Spring |
| 5132 | 215132 | 110007 | 110011 | 가온의 전통 카페 | Gaon's Traditional Cafe |
| 5140 | 215140 | 110007 | 110011 | 병원 로비 | Hospital Lobby |
| 5141 | 215141 | 110007 | 110011 | 낮의 시장 | Daytime Market |
| 5142 | 215142 | 110007 | 110011 | 영지 거리 | Town Street |
| 5150 | 215150 | 110007 | 110011 | 낮의 해수욕장 | Daytime Bathing Beach |
| 5151 | 215151 | 110007 | 110011 | 노을진 해수욕장 | Bathing Beach at Sunset |
| 5152 | 215152 | 110007 | 110011 | 한밤의 해수욕장 | Midnight Beach |
| 5153 | 215153 | 110007 | 110011 | 해변 레스토랑 | Beach Restaurant |
| 5161 | 215161 | 110007 | 110011 | 공주의 처소 | Princess's Abode |
| 5162 | 215162 | 110007 | 110011 | 가온풍 궁전 복도 | Gaon Palace Corridor |
| 5171 | 215171 | 110007 | 110011 | 어두운 숲 | Dark Forest |
| 5172 | 215172 | 110007 | 110011 | 악몽의 들판 | Field of Nightmare |
| 5181 | 215181 | 110007 | 110011 | 눈 덮인 아케나인 광장 | Snow-Covered Arkenine Square |
| 5182 | 215182 | 110007 | 110011 | 눈 덮인 영지 거리 | Snow-Covered Town Street |
| 5191 | 215191 | 110007 | 110011 | 1주년 기념 선상 파티장 | 1st Anniversary Maritime Mirth Venue |
| 5201 | 215201 | 110007 | 110011 | 메이드 카페 | Maid Cafe |
| 5211 | 215211 | 110007 | 110011 | 어둠의 학교 교실 | Sinister School Classroom |
| 5212 | 215212 | 110007 | 110011 | 어둠의 학교 옥상 | Sinister School Rooftop |
| 5213 | 215213 | 110007 | 110011 | 어둠의 학교 복도 | Sinister School Corridor |
| 5221 | 215221 | 110007 | 110011 | 가온의 밤 축제 거리 | Gaon's Night Festival Street |
| 5231 | 215231 | 110007 | 110011 | 칼라르 설산 절벽 | Chalar Snow Mountain Cliff |
| 5232 | 215232 | 110007 | 110011 | 아케나인 예식장 | Arkenine Wedding Hall |
| 5241 | 215241 | 110007 | 110011 | 나무 미로 | Wooden Maze |
| 5251 | 215251 | 110007 | 110011 | 서커스 무대 | Circus Stage |
| 5261 | 215261 | 110007 | 110011 | 이브의 날 메카 컨벤션 | Eve's Day Mech Convention |
| 5271 | 215271 | 110007 | 110011 | 가온의 낮 신년제 거리 | Daytime Street of Gaon's New Year's Festival |
| 5281 | 215281 | 110007 | 110011 | 로제의 심상세계 | Rose's Imaginary World |
| 5291 | 215291 | 110007 | 110011 | 노심굴 | Reactor Core Cave |
| 5400 | 215400 | 110007 | 110011 | 방주 | The Ark |
| 5401 | 215401 | 110007 | 110011 | 낮의 해변가 | Beach (Daytime) |
| 5402 | 215402 | 110007 | 110011 | 밤의 해변가 | Night Beach |
| 5403 | 215403 | 110007 | 110011 | 낮의 성벽 산책로 | Wall Walkway (Daytime) |
| 5404 | 215404 | 110007 | 110011 | 밤의 성벽 산책로 | Wall Walkway (Nighttime) |
| 5405 | 215405 | 110007 | 110011 | 낮의 벚꽃 동산 | Cherry Blossom Hill (Daytime) |
| 5406 | 215406 | 110007 | 110011 | 낮의 종달새 숲 | Lark Forest (Daytime) |
| 5407 | 215407 | 110007 | 110011 | 밤의 종달새 숲 | Lark Forest (Nighttime) |
| 5408 | 215408 | 110007 | 110011 | 밤의 은하수 언덕 | Milky Way Hill (Nighttime) |
| 5409 | 215409 | 110007 | 110011 | 밤의 달빛 호숫가 | Moonlit Lakeside (Nighttime) |
| 5501 | 215501 | 110074 | 110011 | 프레임: 기본 | Frame: Basic |
| 5502 | 215502 | 110074 | 110011 | 프레임: 빨강 | Frame: Red |
| 5503 | 215503 | 110074 | 110011 | 프레임: 노랑 | Frame: Yellow |
| 5504 | 215504 | 110074 | 110011 | 프레임: 보라 | Frame: Purple |
| 5505 | 215505 | 110074 | 110011 | 프레임: 파랑 | Frame: Blue |
| 5506 | 215506 | 110074 | 110011 | 프레임: 녹색 | Frame: Green |
| 5507 | 215507 | 110074 | 110011 | 프레임: 검정 | Frame: Black |
| 5601 | 215601 | 110074 | 110012 | 프레임: 아르바이트의 시작 | Frame: Part-Time Job Begins |
| 5602 | 215602 | 110074 | 110014 | 프레임: 아르바이트 베테랑 | Frame: Part-Time Job Veteran |
| 5603 | 215603 | 110074 | 110016 | 프레임: 아르바이트 마스터 | Frame: Part-Time Job Master |
| 5611 | 215611 | 110074 | 110012 | 프레임: 원정의 시작 | Frame: Expedition Begins |
| 5612 | 215612 | 110074 | 110014 | 프레임: 원정 베테랑 | Frame: Expedition Veteran |
| 5613 | 215613 | 110074 | 110016 | 프레임: 원정 마스터 | Frame: Expedition Master |
| 5621 | 215621 | 110074 | 110012 | 프레임: 나누는 기쁨 | Frame: Sharing is Caring |
| 5622 | 215622 | 110074 | 110014 | 프레임: 아낌없는 나눔 | Frame: Endless Sharing |
| 5623 | 215623 | 110074 | 110016 | 프레임: 아가페 | Frame: Love |
| 5631 | 215631 | 110074 | 110012 | 프레임: 연애초보 | Frame: Dating Novice |
| 5632 | 215632 | 110074 | 110014 | 프레임: 연애달인 | Frame: Dating Expert |
| 5633 | 215633 | 110074 | 110016 | 프레임: 연애마스터 | Frame: Dating Master |
| 5641 | 215641 | 110074 | 110012 | 프레임: 약간의 유명세 | Frame: Small Fame |
| 5642 | 215642 | 110074 | 110014 | 프레임: 인플루언서 | Frame: Influencer |
| 5643 | 215643 | 110074 | 110016 | 프레임: 월드대스타 | Frame: World Star |
| 5651 | 215651 | 110074 | 110012 | 프레임: 사이좋게 지내요 | Frame: Friendship |
| 5652 | 215652 | 110074 | 110014 | 프레임: 인싸일지도 | Frame: Wannabe |
| 5653 | 215653 | 110074 | 110016 | 프레임: 인싸마스터 | Frame: Socialite |
| 5654 | 215654 | 110074 | 110012 | 프레임: 영지 파괴범 | Frame: Town Destroyer |
| 5655 | 215655 | 110074 | 110014 | 프레임: 파괴왕 | Frame: The Destroyer |
| 5656 | 215656 | 110074 | 110016 | 프레임: 파괴의 화신 | Frame: Incarnation of Destruction |
| 5657 | 215657 | 110074 | 110014 | 프레임: 종말을 부르는 인형을 저지한 자 | Frame: One Who Stopped the Doomsday Doll |
| 5658 | 215658 | 110074 | 110014 | 프레임: 종말을 부르는 인형을 정화한 자 | Frame: One Who Purified the Doomsday Doll |
| 5659 | 215659 | 110074 | 110016 | 프레임: 종말을 부르는 인형을 구원한 자 | Frame: One Who Saved the Doomsday Doll |
| 5660 | 215660 | 110074 | 110011 | 프레임: 마물 전문가 | Frame: Monster Expert |
| 5661 | 215661 | 110074 | 110011 | 프레임: 마물 베테랑 | Frame: Monster Veteran |
| 5662 | 215662 | 110074 | 110011 | 프레임: 마물 마스터 | Frame: Monster Master |
| 5663 | 215663 | 110074 | 110012 | 프레임: 마물을 사냥하는 자 | Frame: Monster Hunter |
| 5664 | 215664 | 110074 | 110014 | 프레임: 마물을 토벌하는 자 | Frame: Monster Subjugator |
| 5665 | 215665 | 110074 | 110016 | 프레임: 마물을 멸하는 자 | Frame: Monster Exterminator |
| 5666 | 215666 | 110074 | 110012 | 프레임: 멸망한 세계의 용사 | Frame: Warrior of the Doomed World |
| 5667 | 215667 | 110074 | 110012 | 프레임: 멸망한 세계의 수호자 | Frame: Guardian of the Doomed World |
| 5668 | 215668 | 110074 | 110012 | 프레임: 멸망한 세계의 인도자 | Frame: Leader of the Doomed World |
| 5669 | 215669 | 110074 | 110014 | 프레임: 멸망의 마녀를 저지한 자 | Frame: Stopped the Witch |
| 5670 | 215670 | 110074 | 110014 | 프레임: 멸망의 마녀를 정화한 자 | Frame: Purified the Witch |
| 5671 | 215671 | 110074 | 110016 | 프레임: 멸망의 마녀를 구원한 자 | Frame: Saved the Witch |
| 5672 | 215672 | 110074 | 110012 | 프레임: 원한이 가득한 세계의 용사 | Frame: Warrior of a World Full of Resentment |
| 5673 | 215673 | 110074 | 110012 | 프레임: 원한이 가득한 세계의 수호자 | Frame: Guardian of a World Full of Resentment |
| 5674 | 215674 | 110074 | 110012 | 프레임: 원한이 가득한 세계의 인도자 | Frame: Guide of a World Full of Resentment |
| 5675 | 215675 | 110074 | 110014 | 프레임: 피눈물을 흘리는 원귀를 저지한 자 | Frame: One Who Stopped the Ghost Who Weeps Bitter Tears |
| 5676 | 215676 | 110074 | 110014 | 프레임: 피눈물을 흘리는 원귀를 정화한 자 | Frame: One Who Purified the Ghost Who Weeps Bitter Tears |
| 5677 | 215677 | 110074 | 110016 | 프레임: 피눈물을 흘리는 원귀를 구원한 자 | Frame: One Who Saved the Ghost Who Weeps Bitter Tears |
| 5678 | 215678 | 110074 | 110012 | 프레임: 광기가 가득한 세계의 용사 | Frame: Warrior of a World Full of Madness |
| 5679 | 215679 | 110074 | 110012 | 프레임: 광기가 가득한 세계의 수호자 | Frame: Guardian of a World Full of Madness |
| 5680 | 215680 | 110074 | 110012 | 프레임: 광기가 가득한 세계의 인도자 | Frame: Guide of a World Full of Madness |
| 5681 | 215681 | 110074 | 110014 | 프레임: 광기에 물든 야수를 저지한 자 | Frame: One Who Stopped the Mad Beast |
| 5682 | 215682 | 110074 | 110014 | 프레임: 광기에 물든 야수를 정화한 자 | Frame: One Who Purified the Mad Beast |
| 5683 | 215683 | 110074 | 110016 | 프레임: 광기에 물든 야수를 구원한 자 | Frame: One Who Saved the Mad Beast |
| 5684 | 215684 | 110074 | 110012 | 프레임: 무너진 세계의 용사 | Frame: Warrior of the Collapsed World |
| 5685 | 215685 | 110074 | 110012 | 프레임: 무너진 세계의 수호자 | Frame: Guardian of the Collapsed World |
| 5686 | 215686 | 110074 | 110012 | 프레임: 무너진 세계의 인도자 | Frame: Leader of the Collapsed World |
| 5687 | 215687 | 110074 | 110012 | 프레임: 혼돈에 물든 세계의 용사 | Frame: Warrior of the Chaotic World |
| 5688 | 215688 | 110074 | 110012 | 프레임: 혼돈에 물든 세계의 수호자 | Frame: Guardian of the Chaotic World |
| 5689 | 215689 | 110074 | 110012 | 프레임: 혼돈에 물든 세계의 인도자 | Frame: Leader of the Chaotic World |
| 5690 | 215690 | 110074 | 110014 | 프레임: 비탄의 성녀를 저지한 자 | Frame: One Who Stopped the Saint of Sorrow |
| 5691 | 215691 | 110074 | 110014 | 프레임: 비탄의 성녀를 정화한 자 | Frame: One Who Purified the Saint of Sorrow |
| 5692 | 215692 | 110074 | 110016 | 프레임: 비탄의 성녀를 구원한 자 | Frame: One Who Saved the Saint of Sorrow |
| 5693 | 215693 | 110074 | 110012 | 프레임: 복을 부르는 자 | Frame: Lucky |
| 5694 | 215694 | 110074 | 110012 | 프레임: 전쟁이 가득한 세계의 용사 | Frame: Warrior of a World Full of War |
| 5695 | 215695 | 110074 | 110012 | 프레임: 전쟁이 가득한 세계의 수호자 | Frame: Guardian of a World Full of War |
| 5696 | 215696 | 110074 | 110012 | 프레임: 전쟁이 가득한 세계의 인도자 | Frame: Guide of a World Full of War |
| 5697 | 215697 | 110074 | 110014 | 프레임: 전쟁의 사도를 저지한 자 | Frame: One Who Stopped the Apostle of War |
| 5698 | 215698 | 110074 | 110014 | 프레임: 전쟁의 사도를 정화한 자 | Frame: One Who Purified the Apostle of War |
| 5699 | 215699 | 110074 | 110016 | 프레임: 전쟁의 사도를 구원한 자 | Frame: One Who Saved the Apostle of War |
| 5700 | 215700 | 110074 | 110020 | 프레임: 1주년 기념 프레임 | Frame: 1st Anniversary Frame |
| 5701 | 215701 | 110074 | 110020 | 프레임: 2주년 기념 프레임 | Frame: 2nd Anniversary Frame |
| 5702 | 215702 | 110074 | 110012 | 프레임 : 마물 사냥의 떠오르는 별 | Frame: Rising Star of Monster Hunting |
| 5703 | 215703 | 110074 | 110014 | 프레임 : 마물 사냥의 지배자 | Frame: Sovereign of Monster Hunting |
| 5704 | 215704 | 110074 | 110016 | 프레임 : 마물 사냥의 신 | Frame: God of Monster Hunting |
| 5705 | 215705 | 110074 | 110012 | 프레임: 피로 물든 세계의 용사 | Frame: Warrior of the Blood-Soaked World |
| 5706 | 215706 | 110074 | 110012 | 프레임: 피로 물든 세계의 수호자 | Frame: Guardian of the Blood-Soaked World |
| 5707 | 215707 | 110074 | 110012 | 프레임: 피로 물든 세계의 인도자 | Frame: Leader of the Blood-Soaked World |
| 5708 | 215708 | 110074 | 110014 | 프레임: 피에 물든 검귀를 저지한 자 | Frame: One Who Stopped the Blood-Soaked Sword Demon |
| 5709 | 215709 | 110074 | 110014 | 프레임: 피에 물든 검귀를 정화한 자 | Frame: One Who Purified the Blood-Soaked Sword Demon |
| 5710 | 215710 | 110074 | 110016 | 프레임: 피에 물든 검귀를 구원한 자 | Frame: One Who Saved the Blood-Soaked Sword Demon |
| 5711 | 215711 | 110074 | 110012 | 프레임: 타락한 세계의 용사 | Frame: Warrior of the Corrupted World |
| 5712 | 215712 | 110074 | 110012 | 프레임: 타락한 세계의 수호자 | Frame: Guardian of the Corrupted World |
| 5713 | 215713 | 110074 | 110012 | 프레임: 타락한 세계의 인도자 | Frame: Leader of the Corrupted World |
| 5714 | 215714 | 110074 | 110014 | 프레임: 종말을 찌르는 창을 저지한 자 | Frame: One Who Stopped the Doom Piercer |
| 5715 | 215715 | 110074 | 110014 | 프레임: 종말을 찌르는 창을 정화한 자 | Frame: One Who Purified the Doom Piercer |
| 5716 | 215716 | 110074 | 110016 | 프레임: 종말을 찌르는 창을 구원한 자 | Frame: One Who Saved the Doom Piercer |
| 5717 | 215717 | 110074 | 110012 | 프레임: 추악한 세계의 용사 | Frame: Warrior of the Repulsive World |
| 5718 | 215718 | 110074 | 110012 | 프레임: 추악한 세계의 수호자 | Frame: Guardian of the Repulsive World |
| 5719 | 215719 | 110074 | 110012 | 프레임: 추악한 세계의 인도자 | Frame: Leader of the Repulsive World |
| 5720 | 215720 | 110074 | 110014 | 프레임: 흉몽의 나비를 저지한 자 | Frame: One Who Stopped the Butterfly of An Ominous Dream |
| 5721 | 215721 | 110074 | 110014 | 프레임: 흉몽의 나비를 정화한 자 | Frame: One Who Purified the Butterfly of An Ominous Dream |
| 5722 | 215722 | 110074 | 110016 | 프레임: 흉몽의 나비를 구원한 자 | Frame: One Who Saved the Butterfly of An Ominous Dream |
| 5723 | 215723 | 110074 | 110012 | 프레임: 소중한 마음 | Frame: Cherished Heart |
| 5724 | 215724 | 110074 | 110020 | 프레임: 3주년 기념 프레임 | Frame: 3rd Anniversary Frame |
| 5799 | 215799 | 110074 | 110020 | 프레임: 춘절 기념 |  |
| 6001 | 216001 | 110011 | 110012 | 사진: 미카와 시하의 하루 | Photo: Mica and Seeha's Day |
| 6002 | 216002 | 110011 | 110014 | 일러스트: 데이트 어 소울 | Illustration: Date A Soul |
| 6003 | 216002 | 110011 | 110014 | 일러스트: 데이트 어 소울 | Illustration: Date A Soul |
| 6004 | 216002 | 110011 | 110014 | 일러스트: 데이트 어 소울 | Illustration: Date A Soul |
| 6005 | 216005 | 110011 | 110012 | 사진: 에덴 갓 탤런트 | Photo: Eden's Got Talent |
| 6006 | 216006 | 110011 | 110020 | 사진: 거미님 일러스트 | Photo: 거미's Illustration |
| 6007 | 216007 | 110011 | 110018 | 사진: 주상절리님 일러스트 | Photo: 주상절리's Illustration |
| 6008 | 216008 | 110011 | 110016 | 사진: yuugen님 일러스트 | Photo: yuugen's Illustration |
| 6009 | 216009 | 110011 | 110014 | 사진: 귄터님 일러스트 | Photo: 귄터's Illustration |
| 6010 | 216010 | 110011 | 110014 | 사진: 고꾸닥님 일러스트 | Photo: 고꾸닥's Illustration |
| 6101 | 216101 | 110077 | 110011 | 스티커: 트로이카 (브론즈) | Sticker: Troyca (Bronze) |
| 6102 | 216102 | 110077 | 110012 | 스티커: 트로이카 (실버) | Sticker: Troyca (Silver) |
| 6103 | 216103 | 110077 | 110014 | 스티커: 트로이카 (골드) | Sticker: Troyca (Gold) |
| 6104 | 216104 | 110077 | 110016 | 스티커: 트로이카 (플래티넘) | Sticker: Troyca (Platinum) |
| 6105 | 216105 | 110077 | 110018 | 스티커: 트로이카 (마스터) | Sticker: Troyca (Master) |
| 6106 | 216106 | 110077 | 110020 | 스티커: 트로이카 (챌린저) | Sticker: Troyca (Challenger) |
| 6107 | 216107 | 110077 | 110020 | 스티커: 트로이카<br>(레전더리) | Sticker: Troyca<br>(Legendary) |
| 6108 | 216108 | 110077 | 110020 | 스티커: 트로이카<br>(레전더리 3위) | Sticker: Troyca<br>(Legendary #3) |
| 6109 | 216109 | 110077 | 110020 | 스티커: 트로이카<br>(레전더리 2위) | Sticker: Troyca<br>(Legendary #2) |
| 6110 | 216110 | 110077 | 110020 | 스티커: 트로이카<br>(레전더리 1위) | Sticker: Troyca<br>(Legendary #1) |
| 6111 | 216111 | 110077 | 110011 | 스티커: 아우렐리아 (브론즈) | Sticker: Aurelia (Bronze) |
| 6112 | 216112 | 110077 | 110012 | 스티커: 아우렐리아 (실버) | Sticker: Aurelia (Silver) |
| 6113 | 216113 | 110077 | 110014 | 스티커: 아우렐리아 (골드) | Sticker: Aurelia (Gold) |
| 6114 | 216114 | 110077 | 110016 | 스티커: 아우렐리아 (플래티넘) | Sticker: Aurelia (Platinum) |
| 6115 | 216115 | 110077 | 110018 | 스티커: 아우렐리아 (마스터) | Sticker: Aurelia (Master) |
| 6116 | 216116 | 110077 | 110020 | 스티커: 아우렐리아 (챌린저) | Sticker: Aurelia (Challenger) |
| 6117 | 216117 | 110077 | 110020 | 스티커: 아우렐리아<br>(레전더리) | Sticker: Aurelia<br>(Legendary) |
| 6118 | 216118 | 110077 | 110020 | 스티커: 아우렐리아<br>(레전더리 3위) | Sticker: Aurelia<br>(Legendary #3) |
| 6119 | 216119 | 110077 | 110020 | 스티커: 아우렐리아<br>(레전더리 2위) | Sticker: Aurelia<br>(Legendary #2) |
| 6120 | 216120 | 110077 | 110020 | 스티커: 아우렐리아<br>(레전더리 1위) | Sticker: Aurelia<br>(Legendary #1) |
| 6121 | 216121 | 110077 | 110011 | 스티커: 타브리아 (브론즈) | Sticker: Tabria (Bronze) |
| 6122 | 216122 | 110077 | 110012 | 스티커: 타브리아 (실버) | Sticker: Tabria (Silver) |
| 6123 | 216123 | 110077 | 110014 | 스티커: 타브리아 (골드) | Sticker: Tabria (Gold) |
| 6124 | 216124 | 110077 | 110016 | 스티커: 타브리아 (플래티넘) | Sticker: Tabria (Platinum) |
| 6125 | 216125 | 110077 | 110018 | 스티커: 타브리아 (마스터) | Sticker: Tabria (Master) |
| 6126 | 216126 | 110077 | 110020 | 스티커: 타브리아 (챌린저) | Sticker: Tabria (Challenger) |
| 6127 | 216127 | 110077 | 110020 | 스티커: 타브리아<br>(레전더리) | Sticker: Tabria<br>(Legendary) |
| 6128 | 216128 | 110077 | 110020 | 스티커: 타브리아<br>(레전더리 3위) | Sticker: Tabria<br>(Legendary #3) |
| 6129 | 216129 | 110077 | 110020 | 스티커: 타브리아<br>(레전더리 2위) | Sticker: Tabria<br>(Legendary #2) |
| 6130 | 216130 | 110077 | 110020 | 스티커: 타브리아<br>(레전더리 1위) | Sticker: Tabria<br>(Legendary #1) |
| 6131 | 216131 | 110077 | 110011 | 스티커: 페이렌 (브론즈) | Sticker: Fayren (Bronze) |
| 6132 | 216132 | 110077 | 110012 | 스티커: 페이렌 (실버) | Sticker: Fayren (Silver) |
| 6133 | 216133 | 110077 | 110014 | 스티커: 페이렌 (골드) | Sticker: Fayren (Gold) |
| 6134 | 216134 | 110077 | 110016 | 스티커: 페이렌 (플래티넘) | Sticker: Fayren (Platinum) |
| 6135 | 216135 | 110077 | 110018 | 스티커: 페이렌 (마스터) | Sticker: Fayren (Master) |
| 6136 | 216136 | 110077 | 110020 | 스티커: 페이렌 (챌린저) | Sticker: Fayren (Challenger) |
| 6137 | 216137 | 110077 | 110020 | 스티커: 페이렌<br>(레전더리) | Sticker: Fayren<br>(Legendary) |
| 6138 | 216138 | 110077 | 110020 | 스티커: 페이렌<br>(레전더리 3위) | Sticker: Fayren<br>(Legendary #3) |
| 6139 | 216139 | 110077 | 110020 | 스티커: 페이렌<br>(레전더리 2위) | Sticker: Fayren<br>(Legendary #2) |
| 6140 | 216140 | 110077 | 110020 | 스티커: 페이렌<br>(레전더리 1위) | Sticker: Fayren<br>(Legendary #1) |
| 6141 | 216141 | 110077 | 110011 | 스티커: 칼라르 (브론즈) | Sticker: Chalar (Bronze) |
| 6142 | 216142 | 110077 | 110012 | 스티커: 칼라르 (실버) | Sticker: Chalar (Silver) |
| 6143 | 216143 | 110077 | 110014 | 스티커: 칼라르 (골드) | Sticker: Chalar (Gold) |
| 6144 | 216144 | 110077 | 110016 | 스티커: 칼라르 (플래티넘) | Sticker: Chalar (Platinum) |
| 6145 | 216145 | 110077 | 110018 | 스티커: 칼라르 (마스터) | Sticker: Chalar (Master) |
| 6146 | 216146 | 110077 | 110020 | 스티커: 칼라르 (챌린저) | Sticker: Chalar (Challenger) |
| 6147 | 216147 | 110077 | 110020 | 스티커: 칼라르<br>(레전더리) | Sticker: Chalar<br>(Legendary) |
| 6148 | 216148 | 110077 | 110020 | 스티커: 칼라르<br>(레전더리 3위) | Sticker: Chalar<br>(Legendary #3) |
| 6149 | 216149 | 110077 | 110020 | 스티커: 칼라르<br>(레전더리 2위) | Sticker: Chalar<br>(Legendary #2) |
| 6150 | 216150 | 110077 | 110020 | 스티커: 칼라르<br>(레전더리 1위) | Sticker: Chalar<br>(Legendary #1) |
| 6151 | 216151 | 110077 | 110011 | 스티커: 가온 (브론즈) | Sticker: Gaon (Bronze) |
| 6152 | 216152 | 110077 | 110012 | 스티커: 가온 (실버) | Sticker: Gaon (Silver) |
| 6153 | 216153 | 110077 | 110014 | 스티커: 가온 (골드) | Sticker: Gaon (Gold) |
| 6154 | 216154 | 110077 | 110016 | 스티커: 가온 (플래티넘) | Sticker: Gaon (Platinum) |
| 6155 | 216155 | 110077 | 110018 | 스티커: 가온 (마스터) | Sticker: Gaon (Master) |
| 6156 | 216156 | 110077 | 110020 | 스티커: 가온 (챌린저) | Sticker: Gaon (Challenger) |
| 6157 | 216157 | 110077 | 110020 | 스티커: 가온<br>(레전더리) | Sticker: Gaon<br>(Legendary) |
| 6158 | 216158 | 110077 | 110020 | 스티커: 가온<br>(레전더리 3위) | Sticker: Gaon<br>(Legendary #3) |
| 6159 | 216159 | 110077 | 110020 | 스티커: 가온<br>(레전더리 2위) | Sticker: Gaon<br>(Legendary #2) |
| 6160 | 216160 | 110077 | 110020 | 스티커: 가온<br>(레전더리 1위) | Sticker: Gaon<br>(Legendary #1) |
| 6161 | 216161 | 110077 | 110011 | 스티커: 솔레이 (브론즈) | Sticker: Solrey (Bronze) |
| 6162 | 216162 | 110077 | 110012 | 스티커: 솔레이 (실버) | Sticker: Solrey (Silver) |
| 6163 | 216163 | 110077 | 110014 | 스티커: 솔레이 (골드) | Sticker: Solrey (Gold) |
| 6164 | 216164 | 110077 | 110016 | 스티커: 솔레이 (플래티넘) | Sticker: Solrey (Platinum) |
| 6165 | 216165 | 110077 | 110018 | 스티커: 솔레이 (마스터) | Sticker: Solrey (Master) |
| 6166 | 216166 | 110077 | 110020 | 스티커: 솔레이 (챌린저) | Sticker: Solrey (Challenger) |
| 6167 | 216167 | 110077 | 110020 | 스티커: 솔레이<br>(레전더리) | Sticker: Solrey<br>(Legendary) |
| 6168 | 216168 | 110077 | 110020 | 스티커: 솔레이<br>(레전더리 3위) | Sticker: Solrey<br>(Legendary #3) |
| 6169 | 216169 | 110077 | 110020 | 스티커: 솔레이<br>(레전더리 2위) | Sticker: Solrey<br>(Legendary #2) |
| 6170 | 216170 | 110077 | 110020 | 스티커: 솔레이<br>(레전더리 1위) | Sticker: Solrey<br>(Legendary #1) |
| 6171 | 216171 | 110077 | 110020 | 스티커: 여름 합숙 훈련 | Sticker: Summer Training Camp |
| 6172 | 216172 | 110077 | 110020 | 스티커: 여름 합숙 훈련 (3위) | Sticker: Summer Training Camp (#3) |
| 6173 | 216173 | 110077 | 110020 | 스티커: 여름 합숙 훈련 (2위) | Sticker: Summer Training Camp (#2) |
| 6174 | 216174 | 110077 | 110020 | 스티커: 여름 합숙 훈련 (1위) | Sticker: Summer Training Camp (#1) |
| 6201 | 216201 | 110077 | 110011 | 스티커: 엘나스 | Sticker: Elnath |
| 6202 | 216202 | 110077 | 110011 | 스티커: 아케나인 | Sticker: Arkenine |
| 6203 | 216203 | 110077 | 110011 | 스티커: 콜브 초원 | Sticker: Colve Meadow |
| 6204 | 216204 | 110077 | 110011 | 스티커: 다이난 호수 | Sticker: Lake Dynan |
| 6205 | 216205 | 110077 | 110011 | 스티커: 하얀 울새 숲 | Sticker: White Robin Forest |
| 6206 | 216206 | 110077 | 110011 | 스티커: 베르트 산맥 | Sticker: Vert Mountains |
| 6207 | 216207 | 110077 | 110011 | 스티커: 비노 협곡 | Sticker: Vino Valley |
| 6208 | 216208 | 110077 | 110011 | 스티커: 렉타 황무지 | Sticker: Rechtar Wasteland |
| 6209 | 216209 | 110077 | 110011 | 스티커: 쿠르 사바나 | Sticker: Cur Savannah |
| 6210 | 216210 | 110077 | 110011 | 스티커: 아르코 이리스 | Sticker: Arco Iris |
| 6211 | 216211 | 110077 | 110011 | 스티커: 모레노 사막 | Sticker: Morreno Desert |
| 6212 | 216212 | 110077 | 110011 | 스티커: 라피아 정글 | Sticker: Raffia Jungle |
| 6213 | 216213 | 110077 | 110011 | 스티커: 반딧불이의 둥지 | Sticker: Nest of Fireflies |
| 6214 | 216214 | 110077 | 110011 | 스티커: 나델 고산지 | Sticker: Nadel Mountains |
| 6215 | 216215 | 110077 | 110011 | 스티커: 그림자 없는 땅 | Sticker: Shadowless Lands |
| 6216 | 216216 | 110077 | 110011 | 스티커: 유령도시 모르투스 | Sticker: Ghost City Mortus |
| 6217 | 216217 | 110077 | 110011 | 스티커: 버려진 항구 | Sticker: Forsaken Harbor |
| 6218 | 216218 | 110077 | 110011 | 스티커: 메티아스 호 갑판 | Sticker: Mettias Deck |
| 6219 | 216219 | 110077 | 110011 | 스티커: 가르디눔 대설원 | Sticker: Gardinum Snowfield |
| 6220 | 216220 | 110077 | 110011 | 스티커: 루푸스 요새 | Sticker: Lupus Fortress |
| 6221 | 216221 | 110077 | 110011 | 스티커: 칸델레로 얼음 산맥 | Sticker: Candellero Mountains |
| 6222 | 216222 | 110077 | 110011 | 스티커: 코르텍스 호 | Sticker: The Cortex |
| 6223 | 216223 | 110077 | 110011 | 스티커: 오레올 산맥 | Sticker: Aureole Mountains |
| 6224 | 216224 | 110077 | 110011 | 스티커: 시조의 연안 | Sticker: Founder's Coast |
| 6225 | 216225 | 110077 | 110011 | 스티커: 아페이온 해식동굴 | Sticker: Apeiron Sea Cave |
| 6226 | 216226 | 110077 | 110011 | 스티커: 루멘 성 입구 | Sticker: Lumen Castle Entrance |
| 6227 | 216227 | 110077 | 110011 | 스티커: 엠포리움 연구소 | Sticker: Emporium Laboratory |
| 6228 | 216228 | 110077 | 110011 | 스티커: 땅의 등대 | Sticker: Lighthouse of the Earth |
| 6229 | 216229 | 110077 | 110011 | 스티커: 아우렐리아 심해 유적 | Sticker: Aurelian Deep Sea Ruins |
| 6230 | 216230 | 110077 | 110011 | 스티커: 밤의 도시 | Sticker: Night City |
| 6231 | 216231 | 110077 | 110011 | 스티커: 연옥으로 가는 길 | Sticker: Road to Purgatory |
| 6232 | 216232 | 110077 | 110011 | 스티커: 별의 등대 | Sticker: Lighthouse of the Stars |
| 6233 | 216233 | 110077 | 110011 | 스티커: 별의 바다 | Sticker: Sea of Stars |
| 6234 | 216234 | 110077 | 110011 | 스티커: 하늘뱃길 | Sticker: Sky Fareway |
| 6235 | 216235 | 110077 | 110011 | 스티커: 침묵의 숲 | Sticker: Forest of Silence |
| 6236 | 216236 | 110077 | 110011 | 스티커: 아우렐리아 시가지 | Sticker: Downtown Aurelia |
| 6237 | 216237 | 110077 | 110011 | 스티커: 아우렐리아 대신전 | Sticker: Aurelia Great Temple |
| 6238 | 216238 | 110077 | 110011 | 스티커: 페이렌 외곽 | Sticker: Fayren Outskirts |
| 6239 | 216239 | 110077 | 110011 | 스티커: 페이렌 수정굴 | Sticker: Fayren Crystal Cave |
| 6301 | 216301 | 110077 | 110011 | 스티커: 에리카의 연금술 | Sticker: Erika's Alchemy |
| 6302 | 216302 | 110077 | 110016 | 스티커: 바삭바삭 닭다리 | Sticker: Crispy Drumstick |
| 6303 | 216303 | 110077 | 110016 | 스티커: 달콤한 초콜릿 | Sticker: Sweet Chocolate |
| 6401 | 216401 | 110077 | 110020 | 스티커: 종말을 부르는 인형 (1위) | Sticker: Doomsday Doll (#1) |
| 6402 | 216402 | 110077 | 110018 | 스티커: 종말을 부르는 인형 (2위) | Sticker: Doomsday Doll (#2) |
| 6403 | 216403 | 110077 | 110016 | 스티커: 종말을 부르는 인형 (3위) | Sticker: Doomsday Doll (#3) |
| 6404 | 216404 | 110077 | 110014 | 스티커: 종말을 부르는 인형 (상위) | Sticker: Doomsday Doll (Top Ranking) |
| 6405 | 216405 | 110077 | 110011 | 스티커: 종말을 부르는 인형 | Sticker: Doomsday Doll |
| 6406 | 216406 | 110077 | 110020 | 스티커: 비탄의 성녀 (1위) | Sticker: Saint of Sorrow (#1) |
| 6407 | 216407 | 110077 | 110018 | 스티커: 비탄의 성녀 (2위) | Sticker: Saint of Sorrow (#2) |
| 6408 | 216408 | 110077 | 110016 | 스티커: 비탄의 성녀 (3위) | Sticker: Saint of Sorrow (#3) |
| 6409 | 216409 | 110077 | 110014 | 스티커: 비탄의 성녀 (상위) | Sticker: Saint of Sorrow (Top Ranking) |
| 6410 | 216410 | 110077 | 110011 | 스티커: 비탄의 성녀 | Sticker: Saint of Sorrow |
| 6411 | 216411 | 110077 | 110020 | 스티커: 세계를 멸망시킨 마녀 (1위) | Sticker: Witch Who Destroyed the World (#1) |
| 6412 | 216412 | 110077 | 110018 | 스티커: 세계를 멸망시킨 마녀 (2위) | Sticker: Witch Who Destroyed the World (#2) |
| 6413 | 216413 | 110077 | 110016 | 스티커: 세계를 멸망시킨 마녀 (3위) | Sticker: Witch Who Destroyed the World (#3) |
| 6414 | 216414 | 110077 | 110014 | 스티커: 세계를 멸망시킨 마녀 (상위) | Sticker: Witch Who Destroyed the World (Top Ranking) |
| 6415 | 216415 | 110077 | 110011 | 스티커: 세계를 멸망시킨 마녀 | Sticker: Witch Who Destroyed the World |
| 6416 | 216416 | 110077 | 110020 | 스티커: 전쟁의 사도 (1위) | Sticker: Apostle of War (#1) |
| 6417 | 216417 | 110077 | 110018 | 스티커: 전쟁의 사도 (2위) | Sticker: Apostle of War (#2) |
| 6418 | 216418 | 110077 | 110016 | 스티커: 전쟁의 사도 (3위) | Sticker: Apostle of War (#3) |
| 6419 | 216419 | 110077 | 110014 | 스티커: 전쟁의 사도 (상위) | Sticker: Apostle of War (Top Ranking) |
| 6420 | 216420 | 110077 | 110011 | 스티커: 전쟁의 사도 | Sticker: Apostle of War |
| 6421 | 216421 | 110077 | 110020 | 스티커: 광기에 물든 야수 (1위) | Sticker: Mad Beast (#1) |
| 6422 | 216422 | 110077 | 110018 | 스티커: 광기에 물든 야수 (2위) | Sticker: Mad Beast (#2) |
| 6423 | 216423 | 110077 | 110016 | 스티커: 광기에 물든 야수 (3위) | Sticker: Mad Beast (#3) |
| 6424 | 216424 | 110077 | 110014 | 스티커: 광기에 물든 야수 (상위) | Sticker: Mad Beast (Top Ranking) |
| 6425 | 216425 | 110077 | 110011 | 스티커: 광기에 물든 야수 | Sticker: Mad Beast |
| 6426 | 216426 | 110077 | 110020 | 스티커: 피에 물든 검귀 (1위) | Sticker: Blood-Soaked Sword Demon (#1) |
| 6427 | 216427 | 110077 | 110018 | 스티커: 피에 물든 검귀 (2위) | Sticker: Blood-Soaked Sword Demon (#2) |
| 6428 | 216428 | 110077 | 110016 | 스티커: 피에 물든 검귀 (3위) | Sticker: Blood-Soaked Sword Demon (#3) |
| 6429 | 216429 | 110077 | 110014 | 스티커: 피에 물든 검귀 (상위) | Sticker: Blood-Soaked Sword Demon (Top Ranking) |
| 6430 | 216430 | 110077 | 110011 | 스티커: 피에 물든 검귀 | Sticker: Blood-Soaked Sword Demon |
| 6431 | 216431 | 110077 | 110020 | 스티커: 피눈물을 흘리는 원귀 (1위) | Sticker: Ghost Who Weeps Bitter Tears (#1) |
| 6432 | 216432 | 110077 | 110018 | 스티커: 피눈물을 흘리는 원귀 (2위) | Sticker: Ghost Who Weeps Bitter Tears (#2) |
| 6433 | 216433 | 110077 | 110016 | 스티커: 피눈물을 흘리는 원귀 (3위) | Sticker: Ghost Who Weeps Bitter Tears (#3) |
| 6434 | 216434 | 110077 | 110014 | 스티커: 피눈물을 흘리는 원귀 (상위) | Sticker: Ghost Who Weeps Bitter Tears (Top Ranking) |
| 6435 | 216435 | 110077 | 110011 | 스티커: 피눈물을 흘리는 원귀 | Sticker: Ghost Who Weeps Bitter Tears |
| 6436 | 216436 | 110077 | 110020 | 스티커: 종말을 찌르는 창 (1위) | Sticker: Doom Piercer (#1) |
| 6437 | 216437 | 110077 | 110018 | 스티커: 종말을 찌르는 창 (2위) | Sticker: Doom Piercer (#2) |
| 6438 | 216438 | 110077 | 110016 | 스티커: 종말을 찌르는 창 (3위) | Sticker: Doom Piercer (#3) |
| 6439 | 216439 | 110077 | 110014 | 스티커: 종말을 찌르는 창 (상위) | Sticker: Doom Piercer (Top Ranking) |
| 6440 | 216440 | 110077 | 110011 | 스티커: 종말을 찌르는 창 | Sticker: Doom Piercer |
| 6441 | 216441 | 110077 | 110020 | 스티커: 흉몽의 나비 (1위) | Sticker: Butterfly of An Ominous Dream (#1) |
| 6442 | 216442 | 110077 | 110018 | 스티커: 흉몽의 나비 (2위) | Sticker: Butterfly of An Ominous Dream (#2) |
| 6443 | 216443 | 110077 | 110016 | 스티커: 흉몽의 나비 (3위) | Sticker: Butterfly of An Ominous Dream (#3) |
| 6444 | 216444 | 110077 | 110014 | 스티커: 흉몽의 나비 (상위) | Sticker: Butterfly of An Ominous Dream (Top Ranking) |
| 6445 | 216445 | 110077 | 110011 | 스티커: 흉몽의 나비 | Sticker: Butterfly of An Ominous Dream |
| 6601 | 216601 | 110077 | 110011 | 스티커: 대난투! 미궁 올스타즈 | Sticker: Labyrinth All-Stars Brawl! |
| 6602 | 216602 | 110077 | 110020 | 스티커: 등대지기 (1위) | Sticker: Lighthouse Keeper (#1) |
| 6603 | 216603 | 110077 | 110018 | 스티커: 등대지기 (2위) | Sticker: Lighthouse Keeper (#2) |
| 6604 | 216604 | 110077 | 110016 | 스티커: 등대지기 (3위) | Sticker: Lighthouse Keeper (#3) |
| 6605 | 216605 | 110077 | 110014 | 스티커: 등대지기 (상위) | Sticker: Lighthouse Keeper (Top Ranking) |
| 6606 | 216606 | 110077 | 110011 | 스티커: 등대지기 | Sticker: Lighthouse Keeper |
| 6607 | 216607 | 110077 | 110020 | 스티커: 베히모스 (1위) | Sticker: Behemoth (#1) |
| 6608 | 216608 | 110077 | 110018 | 스티커: 베히모스 (2위) | Sticker: Behemoth (#2) |
| 6609 | 216609 | 110077 | 110016 | 스티커: 베히모스 (3위) | Sticker: Behemoth (#3) |
| 6610 | 216610 | 110077 | 110014 | 스티커: 베히모스 (상위) | Sticker: Behemoth (Top Ranking) |
| 6611 | 216611 | 110077 | 110011 | 스티커: 베히모스 | Sticker: Behemoth |
| 6612 | 216612 | 110077 | 110020 | 스티커: 케이린 (1위) | Sticker: Kayrin (#1) |
| 6613 | 216613 | 110077 | 110018 | 스티커: 케이린 (2위) | Sticker: Kayrin (#2) |
| 6614 | 216614 | 110077 | 110016 | 스티커: 케이린 (3위) | Sticker: Kayrin (#3) |
| 6615 | 216615 | 110077 | 110014 | 스티커: 케이린 (상위) | Sticker: Kayrin (Top Ranking) |
| 6616 | 216616 | 110077 | 110011 | 스티커: 케이린 | Sticker: Kayrin |
| 6701 | 216701 | 110077 | 110020 | 스티커: 1주년 기념 화환 | Sticker: 1st Anniversary Wreath |
| 6702 | 216702 | 110077 | 110018 | 스티커: 게임 오버 | Sticker: Game Over |
| 6703 | 216703 | 110077 | 110020 | 스티커: 야토가미 토카 | Sticker: Tohka Yatogami |
| 6704 | 216704 | 110077 | 110020 | 스티커: 토키사키 쿠루미 | Sticker: Kurumi Tokisaki |
| 6705 | 216705 | 110077 | 110020 | 스티커: 2주년 기념 화환 | Sticker: 2nd Anniversary Wreath |
| 6706 | 216706 | 110077 | 110020 | 스티커: 3주년 기념 딱지 | Sticker: 3rd Anniversary Paper Tile |
| 6801 | 216801 | 110077 | 110020 | 스티커: 기원의 증표 - 릴리트 | Sticker: Token of Origin - Lilith |
| 6802 | 216802 | 110077 | 110020 | 스티커: 기원의 증표 - 웨리 | Sticker: Token of Origin - Wheri |
| 6803 | 216803 | 110077 | 110020 | 스티커: 기원의 증표 - 사쿠요(업화) | Sticker: Token of Origin - Sakuyo (Inferno) |
| 6804 | 216804 | 110077 | 110020 | 스티커: 기원의 증표 - 메피스토펠레스(여명) | Sticker: Token of Origin - Mephistopheles (Dawn) |
| 6805 | 216805 | 110077 | 110020 | 스티커: 기원의 증표 - 바이스 | Sticker: Token of Origin - Weiss |
| 6806 | 216806 | 110077 | 110020 | 스티커: 기원의 증표 - 로제(홍염) | Sticker: Token of Origin - Rose (Prominence) |
| 6807 | 216807 | 110077 | 110020 | 스티커: 기원의 증표 - 홍란(무쌍) | Sticker: Token of Origin - Honglan (Peerless) |
| 6808 | 216808 | 110077 | 110020 | 스티커: 기원의 증표 - 한울 | Sticker: Token of Origin - Hanul |
| 6809 | 216809 | 110077 | 110020 | 스티커: 기원의 증표 - 지호(미르) | Sticker: Token of Origin - Jiho (Mir) |
| 6810 | 216810 | 110077 | 110020 | 스티커: 기원의 증표 - 르네(백은) | Sticker: Token of Origin - Renee (Argent) |
| 6811 | 216811 | 110077 | 110020 | 스티커: 기원의 증표 - 라우라 | Sticker: Token of Origin - Laura |
| 6812 | 216812 | 110077 | 110020 | 스티커: 기원의 증표 - 니아 | Sticker: Token of Origin - Nia |
| 6813 | 216813 | 110077 | 110020 | 스티커: 기원의 증표 - 하루(카무이) | Sticker: Token of Origin - Haru (Kamuy) |
| 6814 | 216814 | 110077 | 110020 | 스티커: 기원의 증표 - 미리암(잔영) | Sticker: Token of Origin - Miriam (Afterimage) |
| 6815 | 216815 | 110077 | 110020 | 스티커: 기원의 증표 - 페트라(각혼) | Sticker: Token of Origin - Petra (Awakened Soul) |
| 6816 | 216816 | 110077 | 110020 | 스티커: 기원의 증표 - 카넬리안 | Sticker: Token of Origin - Carnelian |
| 6817 | 216817 | 110077 | 110020 | 스티커: 기원의 증표 - 가넷(열락) | Sticker: Token of Origin - Garnet (Rapture) |
| 6818 | 216818 | 110077 | 110020 | 스티커: 기원의 증표 - | Sticker: Token of Origin - |
| 6819 | 216819 | 110077 | 110020 | 스티커: 기원의 증표 - 셰리(낭만) | Sticker: Token of Origin - Cherrie (Romantic) |
| 6820 | 216820 | 110077 | 110020 | 스티커: 기원의 증표 - 캐서린(광휘) | Sticker: Token of Origin - Catherine (Radiance) |
| 6821 | 216821 | 110077 | 110020 | 스티커: 기원의 증표 - 유리아 | Sticker: Token of Origin - Yuria |
| 6822 | 216822 | 110077 | 110020 | 스티커: 기원의 증표 - 클라우디아(대천사) | Sticker: Token of Origin - Claudia (Archangel) |
| 6823 | 216823 | 110077 | 110020 | 스티커: 기원의 증표 - 린지(타나토스) | Sticker: Token of Origin - Linzy (Thanatos) |
| 6824 | 216824 | 110077 | 110020 | 스티커: 기원의 증표 - 헤이즐 | Sticker: Token of Origin - Hazel |
| 6825 | 216825 | 110077 | 110020 | 스티커: 기원의 증표 - 이브 | Sticker: Token of Origin - Eve |
| 6826 | 216826 | 110077 | 110020 | 스티커: 기원의 증표 - 시그리드 | Sticker: Token of Origin - Sigrid |
| 6827 | 216827 | 110077 | 110020 | 스티커: 기원의 증표 - 라리마 | Sticker: Token of Origin - Larimar |
| 6828 | 216828 | 110077 | 110020 | 스티커: 기원의 증표 - 오닉스 | Sticker: Token of Origin - Onyx |
| 6829 | 216829 | 110077 | 110020 | 스티커: 기원의 증표 - 도미니크 | Sticker: Token of Origin - Dominique |
| 6830 | 216830 | 110077 | 110020 | 스티커: 기원의 증표 - 유리아(아폴리온) | Sticker: Token of Origin - Yuria (Apollyon) |
| 6831 | 216831 | 110077 | 110020 | 스티커: 기원의 증표 - 아야메 (츠쿠요미) | Sticker: Token of Origin - Ayame (Tsukuyomi) |
| 6901 | 216901 | 110077 | 110020 | 스티커: 썰매왕 슬레이봅 (1위) | Sticker: Sled King Sleighbob (#1) |
| 6902 | 216902 | 110077 | 110020 | 스티커: 썰매왕 슬레이봅 (2위) | Sticker: Sled King Sleighbob (#2) |
| 6903 | 216903 | 110077 | 110020 | 스티커: 썰매왕 슬레이봅 (3위) | Sticker: Sled King Sleighbob (#3) |
| 6904 | 216904 | 110077 | 110020 | 스티커: 썰매왕 슬레이봅 (챌린저) | Sticker: Sled King Sleighbob (Challenger) |
| 6905 | 216905 | 110077 | 110018 | 스티커: 썰매왕 슬레이봅 (마스터) | Sticker: Sled King Sleighbob (Master) |
| 6906 | 216906 | 110077 | 110016 | 스티커: 썰매왕 슬레이봅 (플래티넘) | Sticker: Sled King Sleighbob (Platinum) |
| 6907 | 216907 | 110077 | 110014 | 스티커: 썰매왕 슬레이봅 (골드) | Sticker: Sled King Sleighbob (Gold) |
| 6908 | 216908 | 110077 | 110012 | 스티커: 썰매왕 슬레이봅 (실버) | Sticker: Sled King Sleighbob (Silver) |
| 6909 | 216909 | 110077 | 110011 | 스티커: 썰매왕 슬레이봅 (브론즈) | Sticker: Sled King Sleighbob (Bronze) |
| 6910 | 216910 | 110077 | 110020 | 스티커: 메카이아 (1위) | Sticker: Mecha Gaia (#1) |
| 6911 | 216911 | 110077 | 110020 | 스티커: 메카이아 (2위) | Sticker: Mecha Gaia (#2) |
| 6912 | 216912 | 110077 | 110020 | 스티커: 메카이아 (3위) | Sticker: Mecha Gaia (#3) |
| 6913 | 216913 | 110077 | 110020 | 스티커: 메카이아 (챌린저) | Sticker: Mecha Gaia (Challenger) |
| 6914 | 216914 | 110077 | 110018 | 스티커: 메카이아 (마스터) | Sticker: Mecha Gaia (Master) |
| 6915 | 216915 | 110077 | 110016 | 스티커: 메카이아 (플래티넘) | Sticker: Mecha Gaia (Platinum) |
| 6916 | 216916 | 110077 | 110014 | 스티커: 메카이아 (골드) | Sticker: Mecha Gaia (Gold) |
| 6917 | 216917 | 110077 | 110012 | 스티커: 메카이아 (실버) | Sticker: Mecha Gaia (Silver) |
| 6918 | 216918 | 110077 | 110011 | 스티커: 메카이아 (브론즈) | Sticker: Mecha Gaia (Bronze) |
| 6919 | 216919 | 110077 | 110020 | 스티커: 떡공장장 순이 (1위) | Sticker: Rice Cake Factory Chief Soonie (#1) |
| 6920 | 216920 | 110077 | 110020 | 스티커: 떡공장장 순이 (2위) | Sticker: Rice Cake Factory Chief Soonie (#2) |
| 6921 | 216921 | 110077 | 110020 | 스티커: 떡공장장 순이 (3위) | Sticker: Rice Cake Factory Chief Soonie (#3) |
| 6922 | 216922 | 110077 | 110020 | 스티커: 떡공장장 순이 (챌린저) | Sticker: Rice Cake Factory Chief Soonie (Challenger) |
| 6923 | 216923 | 110077 | 110018 | 스티커: 떡공장장 순이 (마스터) | Sticker: Rice Cake Factory Chief Soonie (Master) |
| 6924 | 216924 | 110077 | 110016 | 스티커: 떡공장장 순이 (플래티넘) | Sticker: Rice Cake Factory Chief Soonie (Platinum) |
| 6925 | 216925 | 110077 | 110014 | 스티커: 떡공장장 순이 (골드) | Sticker: Rice Cake Factory Chief Soonie (Gold) |
| 6926 | 216926 | 110077 | 110012 | 스티커: 떡공장장 순이 (실버) | Sticker: Rice Cake Factory Chief Soonie (Silver) |
| 6927 | 216927 | 110077 | 110011 | 스티커: 떡공장장 순이 (브론즈) | Sticker: Rice Cake Factory Chief Soonie (Bronze) |
| 6928 | 216928 | 110077 | 110020 | 스티커: 기록되지 않은 미래(1위) | Sticker: The Unwritten Future (#1) |
| 6929 | 216929 | 110077 | 110020 | 스티커: 기록되지 않은 미래(2위) | Sticker: The Unwritten Future (#2) |
| 6930 | 216930 | 110077 | 110020 | 스티커: 기록되지 않은 미래(3위) | Sticker: The Unwritten Future (#3) |
| 6931 | 216931 | 110077 | 110020 | 스티커: 기록되지 않은 미래(챌린저) | Sticker: The Unwritten Future (Challenger) |
| 6932 | 216932 | 110077 | 110018 | 스티커: 기록되지 않은 미래(마스터) | Sticker: The Unwritten Future (Master) |
| 6933 | 216933 | 110077 | 110016 | 스티커: 기록되지 않은 미래(플래티넘) | Sticker: The Unwritten Future (Platinum) |
| 6934 | 216934 | 110077 | 110014 | 스티커: 기록되지 않은 미래(골드) | Sticker: The Unwritten Future (Gold) |
| 6935 | 216935 | 110077 | 110012 | 스티커: 기록되지 않은 미래(실버) | Sticker: The Unwritten Future (Silver) |
| 6936 | 216936 | 110077 | 110011 | 스티커: 기록되지 않은 미래(브론즈) | Sticker: The Unwritten Future (Bronze) |
| 6937 | 216937 | 110077 | 110020 | 스티커: 천리주단기(1위) | Sticker: Riding Alone for Thousands of Miles (#1) |
| 6938 | 216938 | 110077 | 110020 | 스티커: 천리주단기(2위) | Sticker: Riding Alone for Thousands of Miles (#2) |
| 6939 | 216939 | 110077 | 110020 | 스티커: 천리주단기(3위) | Sticker: Riding Alone for Thousands of Miles (#3) |
| 6940 | 216940 | 110077 | 110020 | 스티커: 천리주단기(챌린저) | Sticker: Riding Alone for Thousands of Miles (Challenger) |
| 6941 | 216941 | 110077 | 110018 | 스티커: 천리주단기(마스터) | Sticker: Riding Alone for Thousands of Miles (Master) |
| 6942 | 216942 | 110077 | 110016 | 스티커: 천리주단기(플래티넘) | Sticker: Riding Alone for Thousands of Miles (Platinum) |
| 6943 | 216943 | 110077 | 110014 | 스티커: 천리주단기(골드) | Sticker: Riding Alone for Thousands of Miles (Gold) |
| 6944 | 216944 | 110077 | 110012 | 스티커: 천리주단기(실버) | Sticker: Riding Alone for Thousands of Miles (Silver) |
| 6945 | 216945 | 110077 | 110011 | 스티커: 천리주단기(브론즈) | Sticker: Riding Alone for Thousands of Miles (Bronze) |
| 6946 | 216946 | 110077 | 110020 | 스티커: 사해파정(1위) | Sticker: Calm Waves of Four Seas (#1) |
| 6947 | 216947 | 110077 | 110020 | 스티커: 사해파정(2위) | Sticker: Calm Waves of Four Seas (#2) |
| 6948 | 216948 | 110077 | 110020 | 스티커: 사해파정(3위) | Sticker: Calm Waves of Four Seas (#3) |
| 6949 | 216949 | 110077 | 110020 | 스티커: 사해파정(챌린저) | Sticker: Calm Waves of Four Seas (Challenger) |
| 6950 | 216950 | 110077 | 110018 | 스티커: 사해파정(마스터) | Sticker: Calm Waves of Four Seas (Master) |
| 6951 | 216951 | 110077 | 110016 | 스티커: 사해파정(플래티넘) | Sticker: Calm Waves of Four Seas (Platinum) |
| 6952 | 216952 | 110077 | 110014 | 스티커: 사해파정(골드) | Sticker: Calm Waves of Four Seas (Gold) |
| 6953 | 216953 | 110077 | 110012 | 스티커: 사해파정(실버) | Sticker: Calm Waves of Four Seas (Silver) |
| 6954 | 216954 | 110077 | 110011 | 스티커: 사해파정(브론즈) | Sticker: Calm Waves of Four Seas (Bronze) |
| 6955 | 216955 | 110077 | 110020 | 스티커: 극광의 너머로(1위) | Sticker: Beyond the Extreme Light (#1) |
| 6956 | 216956 | 110077 | 110020 | 스티커: 극광의 너머로(2위) | Sticker: Beyond the Extreme Light (#2) |
| 6957 | 216957 | 110077 | 110020 | 스티커: 극광의 너머로(3위) | Sticker: Beyond the Extreme Light (#3) |
| 6958 | 216958 | 110077 | 110020 | 스티커: 극광의 너머로(챌린저) | Sticker: Beyond the Extreme Light (Challenger) |
| 6959 | 216959 | 110077 | 110018 | 스티커: 극광의 너머로(마스터) | Sticker: Beyond the Extreme Light (Master) |
| 6960 | 216960 | 110077 | 110016 | 스티커: 극광의 너머로(플래티넘) | Sticker: Beyond the Extreme Light (Platinum) |
| 6961 | 216961 | 110077 | 110014 | 스티커: 극광의 너머로(골드) | Sticker: Beyond the Extreme Light (Gold) |
| 6962 | 216962 | 110077 | 110012 | 스티커: 극광의 너머로(실버) | Sticker: Beyond the Extreme Light (Silver) |
| 6963 | 216963 | 110077 | 110011 | 스티커: 극광의 너머로(브론즈) | Sticker: Beyond the Extreme Light (Bronze) |
| 6964 | 216964 | 110077 | 110020 | 스티커: 폭주한 실베스터 조이 3세 (1위) | Sticker: Rampaging King Sylvester Joey III (#1) |
| 6965 | 216965 | 110077 | 110020 | 스티커: 폭주한 실베스터 조이 3세 (2위) | Sticker: Rampaging King Sylvester Joey III (#2) |
| 6966 | 216966 | 110077 | 110020 | 스티커: 폭주한 실베스터 조이 3세 (3위) | Sticker: Rampaging King Sylvester Joey III (#3) |
| 6967 | 216967 | 110077 | 110020 | 스티커: 폭주한 실베스터 조이 3세 (챌린저) | Sticker: Rampaging King Sylvester Joey III (Challenger) |
| 6968 | 216968 | 110077 | 110018 | 스티커: 폭주한 실베스터 조이 3세 (마스터) | Sticker: Rampaging King Sylvester Joey III (Master) |
| 6969 | 216969 | 110077 | 110016 | 스티커: 폭주한 실베스터 조이 3세 (플래티넘) | Sticker: Rampaging King Sylvester Joey III (Platinum) |
| 6970 | 216970 | 110077 | 110014 | 스티커: 폭주한 실베스터 조이 3세 (골드) | Sticker: Rampaging King Sylvester Joey III (Gold) |
| 6971 | 216971 | 110077 | 110012 | 스티커: 폭주한 실베스터 조이 3세 (실버) | Sticker: Rampaging King Sylvester Joey III (Silver) |
| 6972 | 216972 | 110077 | 110011 | 스티커: 폭주한 실베스터 조이 3세 (브론즈) | Sticker: Rampaging King Sylvester Joey III (Bronze) |
| 6973 | 216973 | 110077 | 110020 | 스티커: 아마'게'돈 (1위) | Sticker: CRABmageddon (#1) |
| 6974 | 216974 | 110077 | 110020 | 스티커: 아마'게'돈 (2위) | Sticker: CRABmageddon (#2) |
| 6975 | 216975 | 110077 | 110020 | 스티커: 아마'게'돈 (3위) | Sticker: CRABmageddon (#3) |
| 6976 | 216976 | 110077 | 110020 | 스티커: 아마'게'돈 (챌린저) | Sticker: CRABmageddon (Challenger) |
| 6977 | 216977 | 110077 | 110018 | 스티커: 아마'게'돈 (마스터) | Sticker: CRABmageddon (Master) |
| 6978 | 216978 | 110077 | 110016 | 스티커: 아마'게'돈 (플래티넘) | Sticker: CRABmageddon (Platinum) |
| 6979 | 216979 | 110077 | 110014 | 스티커: 아마'게'돈 (골드) | Sticker: CRABmageddon (Gold) |
| 6980 | 216980 | 110077 | 110012 | 스티커: 아마'게'돈 (실버) | Sticker: CRABmageddon (Silver) |
| 6981 | 216981 | 110077 | 110011 | 스티커: 아마'게'돈 (브론즈) | Sticker: CRABmageddon (Bronze) |
| 6982 | 216982 | 110077 | 110020 | 스티커: 환영을 꿰뚫는 탄환 (1위) | Sticker: Illusion-Piercing Bullet (#1) |
| 6983 | 216983 | 110077 | 110020 | 스티커: 환영을 꿰뚫는 탄환 (2위) | Sticker: Illusion-Piercing Bullet (#2) |
| 6984 | 216984 | 110077 | 110020 | 스티커: 환영을 꿰뚫는 탄환 (3위) | Sticker: Illusion-Piercing Bullet (#3) |
| 6985 | 216985 | 110077 | 110020 | 스티커: 환영을 꿰뚫는 탄환 (챌린저) | Sticker: Illusion-Piercing Bullet (Challenger) |
| 6986 | 216986 | 110077 | 110018 | 스티커: 환영을 꿰뚫는 탄환 (마스터) | Sticker: Illusion-Piercing Bullet (Master) |
| 6987 | 216987 | 110077 | 110016 | 스티커: 환영을 꿰뚫는 탄환 (플래티넘) | Sticker: Illusion-Piercing Bullet (Platinum) |
| 6988 | 216988 | 110077 | 110014 | 스티커: 환영을 꿰뚫는 탄환 (골드) | Sticker: Illusion-Piercing Bullet (Gold) |
| 6989 | 216989 | 110077 | 110012 | 스티커: 환영을 꿰뚫는 탄환 (실버) | Sticker: Illusion-Piercing Bullet (Silver) |
| 6990 | 216990 | 110077 | 110011 | 스티커: 환영을 꿰뚫는 탄환 (브론즈) | Sticker: Illusion-Piercing Bullet (Bronze) |
| 6991 | 216991 | 110077 | 110020 | 스티커: 아이돌 퀸 캐서린(1위) | Sticker: Idol Queen Catherine (#1) |
| 6992 | 216992 | 110077 | 110020 | 스티커: 아이돌 퀸 캐서린(2위) | Sticker: Idol Queen Catherine (#2) |
| 6993 | 216993 | 110077 | 110020 | 스티커: 아이돌 퀸 캐서린(3위) | Sticker: Idol Queen Catherine (#3) |
| 6994 | 216994 | 110077 | 110020 | 스티커: 아이돌 퀸 캐서린(챌린저) | Sticker: Idol Queen Catherine (Challenger) |
| 6995 | 216995 | 110077 | 110018 | 스티커: 아이돌 퀸 캐서린(마스터) | Sticker: Idol Queen Catherine (Master) |
| 6996 | 216996 | 110077 | 110016 | 스티커: 아이돌 퀸 캐서린(플래티넘) | Sticker: Idol Queen Catherine (Platinum) |
| 6997 | 216997 | 110077 | 110014 | 스티커: 아이돌 퀸 캐서린(골드) | Sticker: Idol Queen Catherine (Gold) |
| 6998 | 216998 | 110077 | 110012 | 스티커: 아이돌 퀸 캐서린(실버) | Sticker: Idol Queen Catherine (Silver) |
| 6999 | 216999 | 110077 | 110011 | 스티커: 아이돌 퀸 캐서린(브론즈) | Sticker: Idol Queen Catherine (Bronze) |
| 7001 | 217001 | 110004 | 110012 | 조각 케이크 | Sliced Cake |
| 7002 | 217002 | 110004 | 110012 | 스콘 | Scone |
| 7003 | 217003 | 110004 | 110012 | 쿠키 세트 | Cookie Set |
| 7004 | 217004 | 110004 | 110012 | 감자칩 | Potato Chips |
| 7005 | 217005 | 110004 | 110012 | 그린 샐러드 | Green Salad |
| 7006 | 217006 | 110004 | 110012 | 도시락 | Lunch Box |
| 7007 | 217007 | 110004 | 110012 | 피시 앤 칩스 | Fish & Chips |
| 7008 | 217008 | 110004 | 110012 | 꼬치구이 | Grilled Skewer |
| 7009 | 217009 | 110004 | 110012 | 커피 | Coffee |
| 7010 | 217010 | 110004 | 110012 | 꿀과 우유 | Honey and Milk |
| 7011 | 217011 | 110004 | 110012 | 허브티 | Herbal Tea |
| 7012 | 217012 | 110004 | 110012 | 과일 주스 | Fruit Juice |
| 7013 | 217013 | 110004 | 110012 | 헤어핀 | Hairclip |
| 7014 | 217014 | 110004 | 110012 | 키 링 | Key Ring |
| 7015 | 217015 | 110004 | 110012 | 향수 | Perfume |
| 7016 | 217016 | 110004 | 110012 | 빗과 거울 | Comb and Mirror |
| 7017 | 217017 | 110004 | 110012 | 수제 곰인형 | Handmade Teddy Bear |
| 7018 | 217018 | 110004 | 110012 | 드림 캐처 | Dreamcatcher |
| 7019 | 217019 | 110004 | 110012 | 탁상 액자 | Table Frame |
| 7020 | 217020 | 110004 | 110012 | 기념주화 | Commemorative Coin |
| 7021 | 217021 | 110004 | 110012 | 만년필 | Fountain Pen |
| 7022 | 217022 | 110004 | 110012 | 부채 | Fan |
| 7023 | 217023 | 110004 | 110012 | 단검 | Dagger |
| 7024 | 217024 | 110004 | 110012 | 마법 스크롤 | Magic Scroll |
| 7025 | 217025 | 110004 | 110012 | 쿠폰 | Coupon |
| 7026 | 217026 | 110004 | 110012 | 모종삽 | Trowel |
| 7027 | 217027 | 110004 | 110012 | 포션 | Potion |
| 7028 | 217028 | 110004 | 110012 | 손수건 | Handkerchief |
| 7029 | 217029 | 110004 | 110012 | 트럼프 카드 | Trump Card |
| 7030 | 217030 | 110004 | 110012 | 우쿨렐레 | Ukulele |
| 7031 | 217031 | 110004 | 110012 | 큐브 | Cube |
| 7032 | 217032 | 110004 | 110012 | 쿠션 | Cushion |
| 7033 | 217033 | 110004 | 110012 | 작은 화분 | Small Pot |
| 7034 | 217034 | 110004 | 110012 | 이야기책 | Story Book |
| 7035 | 217035 | 110004 | 110012 | 찻잔 세트 | Teacup Set |
| 7036 | 217036 | 110004 | 110014 | 영원꽃 | Eternity Flower |
| 7037 | 217037 | 110004 | 110016 | 행운의 꽃다발 | Lucky Bouquet |
| 7100 | 217100 | 110077 | 110020 | 스티커: 열락의 밤으로(1위) | Sticker: Into the Night of Rapture (#1) |
| 7101 | 217101 | 110077 | 110020 | 스티커: 열락의 밤으로(2위) | Sticker: Into the Night of Rapture (#2) |
| 7102 | 217102 | 110077 | 110020 | 스티커: 열락의 밤으로(3위) | Sticker: Into the Night of Rapture (#3) |
| 7103 | 217103 | 110077 | 110020 | 스티커: 열락의 밤으로(챌린저) | Sticker: Into the Night of Rapture (Challenger) |
| 7104 | 217104 | 110077 | 110018 | 스티커: 열락의 밤으로(마스터) | Sticker: Into the Night of Rapture (Master) |
| 7105 | 217105 | 110077 | 110016 | 스티커: 열락의 밤으로(플래티넘) | Sticker: Into the Night of Rapture (Platinum) |
| 7106 | 217106 | 110077 | 110014 | 스티커: 열락의 밤으로(골드) | Sticker: Into the Night of Rapture (Gold) |
| 7107 | 217107 | 110077 | 110012 | 스티커: 열락의 밤으로(실버) | Sticker: Into the Night of Rapture (Silver) |
| 7108 | 217108 | 110077 | 110011 | 스티커: 열락의 밤으로(브론즈) | Sticker: Into the Night of Rapture (Bronze) |
| 7109 | 217109 | 110077 | 110020 | 스티커: 낭만항로(1위) | Sticker: Romantic Voyage (#1) |
| 7110 | 217110 | 110077 | 110020 | 스티커: 낭만항로(2위) | Sticker: Romantic Voyage (#2) |
| 7111 | 217111 | 110077 | 110020 | 스티커: 낭만항로(3위) | Sticker: Romantic Voyage (#3) |
| 7112 | 217112 | 110077 | 110020 | 스티커: 낭만항로(챌린저) | Sticker: Romantic Voyage (Challenger) |
| 7113 | 217113 | 110077 | 110018 | 스티커: 낭만항로(마스터) | Sticker: Romantic Voyage (Master) |
| 7114 | 217114 | 110077 | 110016 | 스티커: 낭만항로(플래티넘) | Sticker: Romantic Voyage (Platinum) |
| 7115 | 217115 | 110077 | 110014 | 스티커: 낭만항로(골드) | Sticker: Romantic Voyage (Gold) |
| 7116 | 217116 | 110077 | 110012 | 스티커: 낭만항로(실버) | Sticker: Romantic Voyage (Silver) |
| 7117 | 217117 | 110077 | 110011 | 스티커: 낭만항로(브론즈) | Sticker: Romantic Voyage (Bronze) |
| 7118 | 217118 | 110077 | 110020 | 스티커: 소원 도둑 오닉스(1위) | Sticker: Wish Thief Onyx (#1) |
| 7119 | 217119 | 110077 | 110020 | 스티커: 소원 도둑 오닉스(2위) | Sticker: Wish Thief Onyx (#2) |
| 7120 | 217120 | 110077 | 110020 | 스티커: 소원 도둑 오닉스(3위) | Sticker: Wish Thief Onyx (#3) |
| 7121 | 217121 | 110077 | 110020 | 스티커: 소원 도둑 오닉스(챌린저) | Sticker: Wish Thief Onyx (Challenger) |
| 7122 | 217122 | 110077 | 110018 | 스티커: 소원 도둑 오닉스(마스터) | Sticker: Wish Thief Onyx (Master) |
| 7123 | 217123 | 110077 | 110016 | 스티커: 소원 도둑 오닉스(플래티넘) | Sticker: Wish Thief Onyx (Platinum) |
| 7124 | 217124 | 110077 | 110014 | 스티커: 소원 도둑 오닉스(골드) | Sticker: Wish Thief Onyx (Gold) |
| 7125 | 217125 | 110077 | 110012 | 스티커: 소원 도둑 오닉스(실버) | Sticker: Wish Thief Onyx (Silver) |
| 7126 | 217126 | 110077 | 110011 | 스티커: 소원 도둑 오닉스(브론즈) | Sticker: Wish Thief Onyx (Bronze) |
| 8001 | 318001 | 110075 | 110012 | 행복한 크마리스스 파티 꾸러미(종료) | Happy Kumawreaths Party Bundle (Expired) |
| 8002 | 318002 | 110075 | 110014 | 수집 이벤트 아이템(종료) | Collection Event Item (Expired) |
| 8003 | 318003 | 110075 | 110012 | 금빛 꿈주머니(종료) | Gold Dream Pouch (Expired) |
| 8004 | 318004 | 110075 | 110012 | 사랑의 묘약(종료) | Love Potion (Expired) |
| 8005 | 318005 | 110075 | 110012 | 행운의 꽃잎(종료) | Lucky Petal (Expired) |
| 8006 | 318006 | 110075 | 110012 | 에버스쿨 경품 메달(종료) | Everschool Prize Medal (Expired) |
| 8007 | 318007 | 110075 | 110012 | 체육부 딱지(종료) | P.E. Club Voucher (Expired) |
| 8008 | 318008 | 110075 | 110012 | 바른생활부 딱지(종료) | Ethics Club Voucher (Expired) |
| 8009 | 218009 | 110075 | 110014 | 이벤트 레이드 입장권 | Event Raid Ticket |
| 8010 | 218010 | 110075 | 110014 | 이벤트 스테이지 입장권 | Event Stage Ticket |
| 8011 | 318011 | 110075 | 110012 | 웨딩 부케(종료) | Wedding Bouquet (Expired) |
| 8012 | 318012 | 110075 | 110012 | 웨딩 리본(종료) | Wedding Ribbon (Expired) |
| 8013 | 318013 | 110075 | 110012 | 웨딩 와인(종료) | Wedding Wine (Expired) |
| 8014 | 218014 | 110075 | 110014 | 미니 게임 입장권 | Mini Game Ticket |
| 8015 | 318015 | 110075 | 110012 | 비비안의 경품 메달(종료) | Vivienne's Prize Medal (Expired) |
| 8016 | 318016 | 110075 | 110012 | 히비스커스 꽃(종료) | Hibiscus (Expired) |
| 8017 | 318017 | 110075 | 110012 | 시글래스 조각(종료) | Sea Glass Piece (Expired) |
| 8018 | 318018 | 110076 | 110014 | 에덴 갓 탤런트 투표권(종료) | Eden's Got Talent Vote (Expired) |
| 8019 | 318019 | 110075 | 110012 | 빙고 티켓(종료) | Bingo Ticket (Expired) |
| 8020 | 318020 | 110075 | 110012 | 아드리안의 경품 메달(종료) | Adrianne's Prize Medal (Expired) |
| 8021 | 318021 | 110075 | 110012 | 비치볼(종료) | Beach Ball (Expired) |
| 8022 | 318022 | 110075 | 110012 | 러버덕(종료) | Rubber Duck (Expired) |
| 8023 | 318023 | 110075 | 110012 | 보름달 별전(종료) | Full Moon Special Coin (Expired) |
| 8024 | 318024 | 110075 | 110012 | 화전(종료) | Flower Rice Pancake (Expired) |
| 8025 | 318025 | 110075 | 110012 | 송편(종료) | Half-Moon Rice Cake (Expired) |
| 8026 | 318026 | 110075 | 110012 | 할로윈 경품 메달(종료) | Halloween Prize Medal (Expired) |
| 8027 | 318027 | 110075 | 110012 | 빨간 모자 쿠폰(종료) | Red Riding Hood Coupon (Expired) |
| 8028 | 318028 | 110075 | 110012 | 나쁜 늑대 쿠폰(종료) | Bad Wolf Coupon (Expired) |
| 8029 | 318029 | 110075 | 110014 | 붉은 달의 악몽 입장권(종료) | Red Moon Nightmare Ticket (Expired) |
| 8030 | 318030 | 110075 | 110012 | 크리스마스 경품 메달(종료) | Christmas Prize Medal (Expired) |
| 8031 | 318031 | 110075 | 110012 | 도라 친구 배지(종료) | Dora Friend Badge (Expired) |
| 8032 | 318032 | 110075 | 110012 | 가넷 친구 배지(종료) | Garnet Friend Badge (Expired) |
| 8033 | 318033 | 110075 | 110014 | 크마리스스 대소동 입장권(종료) | Kumawreaths Kerfuffle Ticket (Expired) |
| 8034 | 218034 | 110075 | 110014 | 미궁 올스타즈 입장권 | Labyrinth All-Stars Ticket |
| 8035 | 218035 | 110075 | 110012 | 훈련 포인트 | Training Points |
| 8036 | 318003 | 110075 | 110012 | 금빛 꿈주머니(종료) | Gold Dream Pouch (Expired) |
| 8037 | 318037 | 110075 | 110014 | 탐관오리 클로이 입장권(종료) | Corrupt Official Chloe Ticket (Expired) |
| 8038 | 318019 | 110075 | 110012 | 빙고 티켓(종료) | Bingo Ticket (Expired) |
| 8039 | 318039 | 110075 | 110012 | 파티 경품 추첨권(종료) | Mirth Prize Ticket (Expired) |
| 8040 | 318040 | 110075 | 110012 | 별빛 메달(종료) | Starlight Medal (Expired) |
| 8041 | 318041 | 110075 | 110012 | 금빛 챔피언 휘장(종료) | Golden Champion Insignia (Expired) |
| 8042 | 318042 | 110075 | 110014 | 파티 레이드 입장권(종료) | Mirth Raid Ticket (Expired) |
| 8043 | 318004 | 110075 | 110012 | 사랑의 묘약(종료) | Love Potion (Expired) |
| 8044 | 318044 | 110075 | 110014 | 파라다이스 레이드 입장권(종료) | Paradise Raid Ticket (Expired) |
| 8045 | 318045 | 110075 | 110012 | 메이드 경품 코인(종료) | Maid Prize Coins (Expired) |
| 8046 | 318046 | 110075 | 110012 | 진상 퇴치 딱지 A(종료) | Troublemaker Purge Sticker A (Expired) |
| 8047 | 318047 | 110075 | 110012 | 진상 퇴치 딱지 B(종료) | Troublemaker Purge Sticker B (Expired) |
| 8048 | 318048 | 110075 | 110014 | 쇼콜라 퀸 레이드 입장권(종료) | Chocolat Queen Raid Ticket (Expired) |
| 8049 | 318005 | 110075 | 110012 | 행운의 꽃잎(종료) | Lucky Petal (Expired) |
| 8050 | 318050 | 110075 | 110014 | 하얀 울새 숲 미니 게임 입장권(종료) | White Robin Forest Mini Game Ticket (Expired) |
| 8051 | 318006 | 110075 | 110012 | 에버스쿨 경품 메달(종료) | Everschool Prize Medal (Expired) |
| 8052 | 318007 | 110075 | 110012 | 체육부 딱지(종료) | P.E. Club Voucher (Expired) |
| 8053 | 318008 | 110075 | 110012 | 바른생활부 딱지(종료) | Ethics Club Voucher (Expired) |
| 8054 | 318054 | 110075 | 110014 | 에버스쿨 레이드 입장권(종료) | Everschool Raid Ticket (Expired) |
| 8055 | 318055 | 110075 | 110012 | 어둠의 에버스쿨 경품 메달(종료) | Sinister Everschool Prize Medal (Expired) |
| 8056 | 318056 | 110075 | 110012 | 다프네의 바주카포 단추(종료) | Daphne's Bazooka Button (Expired) |
| 8057 | 318057 | 110075 | 110012 | 마농의 회계부장 딱지(종료) | Manon's Bursar Sticker (Expired) |
| 8058 | 318058 | 110075 | 110014 | 어둠의 학생회장 레이드 입장권(종료) | Sinister Student President Raid Ticket (Expired) |
| 8059 | 218011 | 110075 | 110012 | 웨딩 부케 | Wedding Bouquet |
| 8060 | 218012 | 110075 | 110012 | 웨딩 리본 | Wedding Ribbon |
| 8061 | 218013 | 110075 | 110012 | 웨딩 와인 | Wedding Wine |
| 8062 | 218062 | 110075 | 110014 | 부케 쟁탈전 레이드 입장권 | Bouquet Scramble Raid Ticket |
| 8063 | 218063 | 110075 | 110012 | 여름 축제 쿠폰 | Summer Festival Coupon |
| 8064 | 218064 | 110075 | 110014 | 가온 무투회 레이드 입장권 | Gaon Martial Arts Tournament Raid Ticket |
| 8065 | 218015 | 110075 | 110012 | 비비안의 경품 메달 | Vivienne's Prize Medal |
| 8066 | 218016 | 110075 | 110012 | 히비스커스 꽃 | Hibiscus |
| 8067 | 218017 | 110075 | 110012 | 시글래스 조각 | Sea Glass Piece |
| 8068 | 318068 | 110075 | 110014 | 여름 낙원 탈환 레이드 입장권(종료) | Getting Back Summer Paradise Raid Ticket (Expired) |
| 8069 | 318068 | 110075 | 110014 | 여름 낙원 탈환 레이드 입장권(종료) | Getting Back Summer Paradise Raid Ticket (Expired) |
| 8070 | 318050 | 110075 | 110014 | 하얀 울새 숲 미니 게임 입장권(종료) | White Robin Forest Mini Game Ticket (Expired) |
| 8071 | 218071 | 110075 | 110012 | 비밀스러운 코르사주 | Secretive Corsage |
| 8072 | 218072 | 110075 | 110012 | 비올레트의 웨딩 슈즈 | Violette's Wedding Shoes |
| 8073 | 218073 | 110075 | 110012 | 가넷의 웨딩 브로치 | Garnet's Wedding Brooch |
| 8074 | 218074 | 110075 | 110014 | 결혼전쟁 레이드 입장권 | Wedding War Raid Ticket |
| 8075 | 218018 | 110076 | 110014 | 에덴 갓 탤런트 투표권 | Eden's Got Talent Vote |
| 8076 | 218019 | 110075 | 110012 | 빙고 티켓 | Bingo Ticket |
| 8077 | 218077 | 110075 | 110012 | 시도 브로마이드 | Photo of Shido |
| 8078 | 218078 | 110075 | 110012 | 콩고물 빵 | Kinako Buns |
| 8079 | 218079 | 110075 | 110012 | 검은 고양이 인형 | Stuffed Black Cat |
| 8080 | 218080 | 110075 | 110014 | 배틀 어 라이브 레이드 입장권 | Battle A Live Raid Ticket |
| 8081 | 218020 | 110075 | 110012 | 아드리안의 경품 메달 | Adrianne's Prize Medal |
| 8082 | 218021 | 110075 | 110012 | 비치볼 | Beach Ball |
| 8083 | 218022 | 110075 | 110012 | 러버덕 | Rubber Duck |
| 8084 | 218084 | 110075 | 110014 | 잔혹한 천사의 밀당 레이드 입장권 | Cruel Angel's Play Raid Ticket |
| 8085 | 218084 | 110075 | 110014 | 잔혹한 천사의 밀당 레이드 입장권 | Cruel Angel's Play Raid Ticket |
| 8086 | 218086 | 110075 | 110012 | 유령 인형 | Ghost Effigy |
| 8087 | 218087 | 110075 | 110012 | 랜턴 | Lantern |
| 8088 | 218088 | 110075 | 110012 | 촬영 필름 | Film Reel |
| 8089 | 218089 | 110075 | 110014 | 미로 탈출 대소동 레이드 입장권 | Maze Maneuver Madness Raid Ticket |
| 8090 | 218023 | 110075 | 110012 | 보름달 별전 | Full Moon Special Coin |
| 8091 | 218024 | 110075 | 110012 | 화전 | Flower Rice Pancake |
| 8092 | 218025 | 110075 | 110012 | 송편 | Half-Moon Rice Cake |
| 8093 | 218093 | 110075 | 110014 | 위험한 혼례 레이드 입장권 | Dangerous Wedding Raid Ticket |
| 8094 | 318054 | 110075 | 110014 | 에버스쿨 레이드 입장권(종료) | Everschool Raid Ticket (Expired) |
| 8095 | 218026 | 110075 | 110012 | 할로윈 경품 메달 | Halloween Prize Medal |
| 8096 | 218027 | 110075 | 110012 | 빨간 모자 쿠폰 | Red Riding Hood Coupon |
| 8097 | 218028 | 110075 | 110012 | 나쁜 늑대 쿠폰 | Bad Wolf Coupon |
| 8098 | 218029 | 110075 | 110014 | 붉은 달의 악몽 입장권 | Red Moon Nightmare Ticket |
| 8099 | 218099 | 110075 | 110012 | 경품 티켓 | Prize Ticket |
| 8100 | 218100 | 110075 | 110012 | 바니바니 훈련 수료증 | Bunny Bunny Training Certificate |
| 8101 | 218101 | 110075 | 110012 | 문라이트 훈련 수료증 | Moonlight Training Certificate |
| 8102 | 218102 | 110075 | 110014 | 문라이트 퍼포먼스 레이드 입장권 | Moonlight Performance Raid Ticket |
| 8103 | 218093 | 110075 | 110014 | 위험한 혼례 레이드 입장권 | Dangerous Wedding Raid Ticket |
| 8104 | 218030 | 110075 | 110012 | 크리스마스 경품 메달 | Christmas Prize Medal |
| 8105 | 218031 | 110075 | 110012 | 도라 친구 배지 | Dora Friend Badge |
| 8106 | 218032 | 110075 | 110012 | 가넷 친구 배지 | Garnet Friend Badge |
| 8107 | 218033 | 110075 | 110014 | 크마리스스 대소동 입장권 | Kumawreaths Kerfuffle Ticket |
| 8108 | 218108 | 110075 | 110012 | 컨벤션 경품 교환권 | Convention Prize Ticket |
| 8109 | 218109 | 110075 | 110012 | 저지 작전 훈장 | Stopping Operation Medal |
| 8110 | 218110 | 110075 | 110012 | 수색 작전 훈장 | Search Operation Medal |
| 8111 | 218111 | 110075 | 110014 | 성야의 폭주 레이드 입장권 | Starry Night Frenzy Raid Ticket |
| 8112 | 218019 | 110075 | 110012 | 빙고 티켓 | Bingo Ticket |
| 8113 | 318037 | 110075 | 110014 | 탐관오리 클로이 입장권(종료) | Corrupt Official Chloe Ticket (Expired) |
| 8114 | 218114 | 110075 | 110012 | 떡주머니 | Rice Cake Pouch |
| 8115 | 218115 | 110075 | 110012 | 탁주 사발 | Rice Wine Bowl |
| 8116 | 218116 | 110075 | 110012 | 불꽃 노리개 | Firework Charm |
| 8117 | 218117 | 110075 | 110014 | 신년맞이 떡공장털이 레이드 입장권 | New Year's Rice Cake Factory Raid Ticket |
| 8118 | 218118 | 110075 | 110012 | 룰렛 티켓 (기록되지 않은 미래) | Spin Ticket (The Unwritten Future) |
| 8119 | 218119 | 110075 | 110014 | 심연의 경계 미니 게임 입장권 | Boundaries of the Abyss Mini Game Ticket |
| 8120 | 218044 | 110075 | 110014 | 파라다이스 레이드 입장권 | Paradise Raid Ticket |
| 8121 | 218121 | 110075 | 110012 | 룰렛 티켓 (천리주단기) | Spin Ticket (Riding Alone for Thousands of Miles) |
| 8122 | 218122 | 110075 | 110014 | 노심 방위전 미니 게임 입장권 | Reactor Core Defense Mini Game Ticket |
| 8123 | 218039 | 110075 | 110012 | 파티 경품 추첨권 | Mirth Prize Ticket |
| 8124 | 218040 | 110075 | 110012 | 별빛 메달 | Starlight Medal |
| 8125 | 218041 | 110075 | 110012 | 금빛 챔피언 휘장 | Golden Champion Insignia |
| 8126 | 218042 | 110075 | 110014 | 파티 레이드 입장권 | Mirth Raid Ticket |
| 8127 | 218063 | 110075 | 110012 | 여름 축제 쿠폰 | Summer Festival Coupon |
| 8128 | 218064 | 110075 | 110014 | 가온 무투회 레이드 입장권 | Gaon Martial Arts Tournament Raid Ticket |
| 8129 | 218045 | 110075 | 110012 | 메이드 경품 코인 | Maid Prize Coins |
| 8130 | 218046 | 110075 | 110012 | 진상 퇴치 딱지 A | Troublemaker Purge Sticker A |
| 8131 | 218047 | 110075 | 110012 | 진상 퇴치 딱지 B | Troublemaker Purge Sticker B |
| 8132 | 218048 | 110075 | 110014 | 쇼콜라 퀸 레이드 입장권 | Chocolat Queen Raid Ticket |
| 8133 | 218133 | 110075 | 110012 | 주사위(사해파정) | Dice (Calm Waves of Four Seas) |
| 8134 | 218134 | 110075 | 110014 | 궁기 길들이기 미니 게임 입장권 | Taming Unicat Mini Game Ticket |
| 8135 | 218055 | 110075 | 110012 | 어둠의 에버스쿨 경품 메달 | Sinister Everschool Prize Medal |
| 8136 | 218056 | 110075 | 110012 | 다프네의 바주카포 단추 | Daphne's Bazooka Button |
| 8137 | 218057 | 110075 | 110012 | 마농의 회계부장 딱지 | Manon's Bursar Sticker |
| 8138 | 218058 | 110075 | 110014 | 어둠의 학생회장 레이드 입장권 | Sinister Student President Raid Ticket |
| 8139 | 218062 | 110075 | 110014 | 부케 쟁탈전 레이드 입장권 | Bouquet Scramble Raid Ticket |
| 8140 | 218140 | 110075 | 110014 | 아케나인 방어전 미니 게임 입장권 | Defense of Arkenine Mini Game Ticket |
| 8141 | 218141 | 110075 | 110012 | 룰렛 티켓(회고록: 극광의 너머로) | Spin Ticket (Memoir: Beyond the Extreme Light) |
| 8142 | 218071 | 110075 | 110012 | 비밀스러운 코르사주 | Secretive Corsage |
| 8143 | 218072 | 110075 | 110012 | 비올레트의 웨딩 슈즈 | Violette's Wedding Shoes |
| 8144 | 218073 | 110075 | 110012 | 가넷의 웨딩 브로치 | Garnet's Wedding Brooch |
| 8145 | 218074 | 110075 | 110014 | 결혼전쟁 레이드 입장권 | Wedding War Raid Ticket |
| 8146 | 218146 | 110075 | 110012 | 흩어진 서류 뭉치 | Scattered Document Bundle |
| 8147 | 218147 | 110075 | 110012 | 왕궁 먼지떨이 | Royal Palace Duster |
| 8148 | 218148 | 110075 | 110012 | 최고급 식자재 | Top-Quality Ingredients |
| 8149 | 218149 | 110075 | 110014 | 개판 5분 전 레이드 입장권 | 5 Minutes to Fur-mageddon Raid Ticket |
| 8150 | 218086 | 110075 | 110012 | 유령 인형 | Ghost Effigy |
| 8151 | 218087 | 110075 | 110012 | 랜턴 | Lantern |
| 8152 | 218088 | 110075 | 110012 | 촬영 필름 | Film Reel |
| 8153 | 218089 | 110075 | 110014 | 미로 탈출 대소동 레이드 입장권 | Maze Maneuver Madness Raid Ticket |
| 8154 | 218019 | 110075 | 110012 | 빙고 티켓 | Bingo Ticket |
| 8155 | 218155 | 110075 | 110012 | 집게발 코인 | Pincer Coin |
| 8156 | 218156 | 110075 | 110012 | 사쿠요의 칭찬 도장 | Sakuyo's Stamp of Approval |
| 8157 | 218157 | 110075 | 110012 | 구원자의 칭찬 도장 | Savior's Stamp of Approval |
| 8158 | 218158 | 110075 | 110014 | 물 뜨라 부르는 소리 있도다 레이드 입장권 | Fetch Water, the Voice Calls Raid Ticket |
| 8159 | 218159 | 110075 | 110014 | 디모니크와 광기의 숲 미니 게임 입장권 | Dimonique and the Forest of Madness Mini Game Ticket |
| 8160 | 218160 | 110075 | 110012 | 팬텀의 특수 훈련 미니 게임 입장권 | Phantom's Special Training Mini Game Ticket |
| 8161 | 218161 | 110075 | 110012 | 주사위(환영을 꿰뚫는 탄환) | Dice (Illusion-Piercing Bullet) |
| 8162 | 218099 | 110075 | 110012 | 경품 티켓 | Prize Ticket |
| 8163 | 218100 | 110075 | 110012 | 바니바니 훈련 수료증 | Bunny Bunny Training Certificate |
| 8164 | 218101 | 110075 | 110012 | 문라이트 훈련 수료증 | Moonlight Training Certificate |
| 8165 | 218102 | 110075 | 110014 | 문라이트 퍼포먼스 레이드 입장권 | Moonlight Performance Raid Ticket |
| 8166 | 218162 | 110075 | 110012 | 아이돌 퀸 굿즈 추첨권 | Idol Queen Merch Raffle Ticket |
| 8167 | 218163 | 110075 | 110012 | 보컬 트레이닝 수료증 | Vocal Training Certificate |
| 8168 | 218164 | 110075 | 110012 | 댄스 트레이닝 수료증 | Dance Training Certificate |
| 8169 | 218165 | 110075 | 110014 | 아이돌 퀸의 특별 무대 레이드 입장권 | Idol Queen's Special Stage Raid Ticket |
| 8170 | 218019 | 110075 | 110012 | 빙고 티켓 | Bingo Ticket |
| 8171 | 218135 | 110075 | 110012 | 룰렛 티켓 (열락의 밤으로) | Spin Ticket (Into the Night of Rapture) |
| 8172 | 218136 | 110075 | 110012 | 낭만항로 이벤트 스테이지 입장권 | Romantic Voyage Event Stage Ticket |
| 8173 | 218137 | 110075 | 110012 | 룰렛 티켓(낭만항로) | Spin Ticket (Romantic Voyage) |
| 8174 | 218138 | 110075 | 110012 | 가슴 벅찬 해변의 비밀 데이트 입장권 | Heart-Stopping Secret Beach Date Ticket |
| 8175 | 218108 | 110075 | 110012 | 컨벤션 경품 교환권 | Convention Prize Ticket |
| 8176 | 218109 | 110075 | 110012 | 저지 작전 훈장 | Stopping Operation Medal |
| 8177 | 218110 | 110075 | 110012 | 수색 작전 훈장 | Search Operation Medal |
| 8178 | 218114 | 110075 | 110012 | 떡주머니 | Rice Cake Pouch |
| 8179 | 218115 | 110075 | 110012 | 탁주 사발 | Rice Wine Bowl |
| 8180 | 218116 | 110075 | 110012 | 불꽃 노리개 | Firework Charm |
| 8181 | 218117 | 110075 | 110014 | 신년맞이 떡공장털이 레이드 입장권 | New Year's Rice Cake Factory Raid Ticket |
| 8182 | 218111 | 110075 | 110014 | 성야의 폭주 레이드 입장권 | Starry Night Frenzy Raid Ticket |
| 8183 | 218166 | 110075 | 110012 | 빙고 티켓(3주년) | Bingo Ticket (3rd Anniversary) |
| 8184 | 218167 | 110075 | 110012 | 무사안녕 기원 복주머니 | Safety-Prayer Lucky Pouch |
| 8185 | 218168 | 110075 | 110012 | 운수대통 기원 복주머니 | Fortune's Favor Lucky Pouch |
| 8186 | 218169 | 110075 | 110012 | 만사형통 행운 복권 | Prospering Fortune Lottery Ticket |
| 8187 | 218170 | 110075 | 110014 | 소원 도둑을 잡아라! 레이드 입장권 | Catch the Wish Thief! Raid Ticket |
| 8188 | 218118 | 110075 | 110012 | 룰렛 티켓 (기록되지 않은 미래) | Spin Ticket (The Unwritten Future) |
| 8189 | 218119 | 110075 | 110014 | 심연의 경계 미니 게임 입장권 | Boundaries of the Abyss Mini Game Ticket |
| 8901 | 218901 | 110008 | 110014 | 마농팩 체험권 (7일) | Manon Pack Trial Ticket (7 Days) |
| 8902 | 218902 | 110008 | 110014 | 샤링팩 체험권 (7일) | Sharinne Pack Trial Ticket (7 Days) |
| 8903 | 218903 | 110008 | 110014 | 마농팩 체험권 (10일) | Manon Pack Trial Ticket (10 Days) |
| 8904 | 218904 | 110008 | 110014 | 샤링팩 체험권 (10일) | Sharinne Pack Trial Ticket (10 Days) |
| 9001 | 210601 | 110010 | 110016 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 9002 | 210602 | 110010 | 110016 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 9003 | 210603 | 110010 | 110016 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 9004 | 210604 | 110010 | 110016 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 9005 | 210629 | 110010 | 110016 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 9006 | 210630 | 110010 | 110016 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 9007 | 210631 | 110010 | 110016 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 9008 | 210632 | 110010 | 110016 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 9009 | 210657 | 110010 | 110016 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 9010 | 210658 | 110010 | 110016 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 9011 | 210659 | 110010 | 110016 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 9012 | 210660 | 110010 | 110016 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 9101 | 210701 | 110010 | 110017 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 9102 | 210702 | 110010 | 110017 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 9103 | 210703 | 110010 | 110017 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 9104 | 210704 | 110010 | 110017 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 9105 | 210729 | 110010 | 110017 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 9106 | 210730 | 110010 | 110017 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 9107 | 210731 | 110010 | 110017 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 9108 | 210732 | 110010 | 110017 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 9109 | 210757 | 110010 | 110017 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 9110 | 210758 | 110010 | 110017 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 9111 | 210759 | 110010 | 110017 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 9112 | 210760 | 110010 | 110017 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 9201 | 210801 | 110010 | 110018 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 9202 | 210802 | 110010 | 110018 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 9203 | 210803 | 110010 | 110018 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 9204 | 210804 | 110010 | 110018 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 9205 | 210829 | 110010 | 110018 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 9206 | 210830 | 110010 | 110018 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 9207 | 210831 | 110010 | 110018 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 9208 | 210832 | 110010 | 110018 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 9209 | 210857 | 110010 | 110018 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 9210 | 210858 | 110010 | 110018 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 9211 | 210859 | 110010 | 110018 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 9212 | 210860 | 110010 | 110018 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 9301 | 210901 | 110010 | 110019 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 9302 | 210902 | 110010 | 110019 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 9303 | 210903 | 110010 | 110019 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 9304 | 210904 | 110010 | 110019 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 9305 | 210929 | 110010 | 110019 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 9306 | 210930 | 110010 | 110019 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 9307 | 210931 | 110010 | 110019 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 9308 | 210932 | 110010 | 110019 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 9309 | 210957 | 110010 | 110019 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 9310 | 210958 | 110010 | 110019 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 9311 | 210959 | 110010 | 110019 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 9312 | 210960 | 110010 | 110019 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 9401 | 211001 | 110010 | 110020 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 9402 | 211002 | 110010 | 110020 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 9403 | 211003 | 110010 | 110020 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 9404 | 211004 | 110010 | 110020 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 9405 | 211029 | 110010 | 110020 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 9406 | 211030 | 110010 | 110020 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 9407 | 211031 | 110010 | 110020 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 9408 | 211032 | 110010 | 110020 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 9409 | 211057 | 110010 | 110020 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 9410 | 211058 | 110010 | 110020 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 9411 | 211059 | 110010 | 110020 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 9412 | 211060 | 110010 | 110020 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 10001 | 2110001 | 110003 | 110014 | 유물의 기억: 방주 메타트론 | Artifact Memory: Ark Metatron |
| 10002 | 2110002 | 110003 | 110014 | 유물의 기억: 방주 자드키엘 | Artifact Memory: Ark Zadkiel |
| 10003 | 2110003 | 110003 | 110014 | 유물의 기억: 잔다르크의 깃발 | Artifact Memory: Flag of Jeanne d'Arc |
| 10004 | 2110004 | 110003 | 110014 | 유물의 기억: 무라마사 | Artifact Memory: Muramasa |
| 10005 | 2110005 | 110003 | 110014 | 유물의 기억: 미다스의 손 | Artifact Memory: Hand of Midas |
| 10006 | 2110006 | 110003 | 110014 | 유물의 기억: 프라가라흐 | Artifact Memory: Fragarach |
| 10007 | 2110007 | 110003 | 110014 | 유물의 기억: 간디바 | Artifact Memory: Gandiva |
| 10008 | 2110008 | 110003 | 110014 | 유물의 기억: 요시모토 사몬지 | Artifact Memory: Yoshimoto Samonji |
| 10009 | 2110009 | 110003 | 110014 | 유물의 기억: 성해포 | Artifact Memory: Holy Shroud |
| 10010 | 2110010 | 110003 | 110014 | 유물의 기억: 신편귀독주 | Artifact Memory: Shinpen Kidoku |
| 10011 | 2110011 | 110003 | 110014 | 유물의 기억: 골디락스의 빈 그릇 | Artifact Memory: Bowl of Goldilocks |
| 10012 | 2110012 | 110003 | 110014 | 유물의 기억: 청룡언월도 | Artifact Memory: Green Dragon Crescent Blade |
| 10013 | 2110013 | 110003 | 110014 | 유물의 기억: 거북선 | Artifact Memory: Turtle Ship |
| 10014 | 2110014 | 110003 | 110014 | 유물의 기억: 다그다의 곤봉 | Artifact Memory: Dagda's Club |
| 10015 | 2110015 | 110003 | 110014 | 유물의 기억: 칼리오페의 소리굽쇠 | Artifact Memory: Tuning Fork of Calliope |
| 10016 | 2110016 | 110003 | 110014 | 유물의 기억: 오르페우스의 리라 | Artifact Memory: Lyre of Orpheus |
| 10017 | 2110017 | 110003 | 110014 | 유물의 기억: 레메게톤 | Artifact Memory: Lemegeton |
| 10018 | 2110018 | 110003 | 110014 | 유물의 기억: RPG-7 | Artifact Memory: RPG-7 |
| 10019 | 2110019 | 110003 | 110014 | 유물의 기억: 투탕카멘의 가면 | Artifact Memory: Tutankhamun's Mask |
| 10020 | 2110020 | 110003 | 110014 | 유물의 기억: 쿠투네시르카 | Artifact Memory: Kutune Shirka |
| 10021 | 2110021 | 110003 | 110014 | 유물의 기억: 모글레이 | Artifact Memory: Murgleys |
| 10022 | 2110022 | 110003 | 110014 | 유물의 기억: 코르누코피아 | Artifact Memory: Cornucopia |
| 10023 | 2110023 | 110003 | 110014 | 유물의 기억: 엘릭서 | Artifact Memory: Elixir of Life |
| 10024 | 2110024 | 110003 | 110014 | 유물의 기억: 하멜른의 피리 | Artifact Memory: Hameline's Flute |
| 10025 | 2110025 | 110003 | 110014 | 유물의 기억: 누아다의 의수 | Artifact Memory: Nuada Airgetlám |
| 10026 | 2110026 | 110003 | 110014 | 유물의 기억: 테트라비블로스 | Artifact Memory: Tetrabiblos |
| 10027 | 2110027 | 110003 | 110014 | 유물의 기억: 큐피드의 화살 | Artifact Memory: Cupid's Arrow |
| 10028 | 2110028 | 110003 | 110014 | 유물의 기억: 바리사다 | Artifact Memory: Balisarda |
| 10029 | 2110029 | 110003 | 110014 | 유물의 기억: 페일노트 | Artifact Memory: Failnaught |
| 10030 | 2110030 | 110003 | 110014 | 유물의 기억: 에메랄드 타블렛 | Artifact Memory: Emerald Tablet |
| 10031 | 2110031 | 110003 | 110014 | 유물의 기억: 7발의 마탄 | Artifact Memory: The Seventh Bullet |
| 10032 | 2110032 | 110003 | 110014 | 유물의 기억: 아이기스 | Artifact Memory: Aegis |
| 10033 | 2110033 | 110003 | 110014 | 유물의 기억: 잔트만의 꿈가루 | Artifact Memory: Dust of Sandman |
| 10034 | 2110034 | 110003 | 110014 | 유물의 기억: 판도라의 상자 | Artifact Memory: Pandora's Box |
| 10035 | 2110035 | 110003 | 110014 | 유물의 기억: 롱기누스의 창 | Artifact Memory: Longinus |
| 10036 | 2110036 | 110003 | 110014 | 유물의 기억: 게이 보 | Artifact Memory: Gáe Buide |
| 10037 | 2110037 | 110003 | 110014 | 유물의 기억: 아야무르 | Artifact Memory: Ayamur |
| 10038 | 2110038 | 110003 | 110014 | 유물의 기억: 야그루시 | Artifact Memory: Yagrush |
| 10039 | 2110039 | 110003 | 110014 | 유물의 기억: 카두세우스 | Artifact Memory: Caduceus |
| 10040 | 2110040 | 110003 | 110014 | 유물의 기억: 게 볼그 | Artifact Memory: Gáe Bulg |
| 10041 | 2110041 | 110003 | 110014 | 유물의 기억: 클라렌트 | Artifact Memory: Clarent |
| 10042 | 2110042 | 110003 | 110014 | 유물의 기억: 바즈라 | Artifact Memory: Vajra |
| 10043 | 2110043 | 110003 | 110014 | 유물의 기억: 반혼향 | Artifact Memory: Spirit-Calling Incense |
| 10044 | 2110044 | 110003 | 110014 | 유물의 기억: 호신부 | Artifact Memory: Amulet of Protection |
| 10045 | 2110045 | 110003 | 110014 | 유물의 기억: 묠니르 | Artifact Memory: Mjölnir |
| 10046 | 2110046 | 110003 | 110014 | 유물의 기억: 아스칼론 | Artifact Memory: Ascalon |
| 10047 | 2110047 | 110003 | 110014 | 유물의 기억: 다섯 번째 나팔 | Artifact Memory: Fifth Trumpet |
| 10048 | 2110048 | 110003 | 110014 | 유물의 기억: 오시리스의 지팡이 | Artifact Memory: Staff of Osiris |
| 10049 | 2110049 | 110003 | 110014 | 유물의 기억: 궁니르 | Artifact Memory: Gungnir |
| 10050 | 2110050 | 110003 | 110014 | 유물의 기억: 츠쿠요미의 백동거울 | Artifact Memory: Mirror of Tsukuyomi |
| 10051 | 2110051 | 110003 | 110014 | 유물의 기억: 만파식적 | Artifact Memory: Manpashikjeok |
| 10052 | 2110052 | 110003 | 110014 | 유물의 기억: 아스트라페 | Artifact Memory: Astrape |
| 10053 | 2110053 | 110003 | 110014 | 유물의 기억: 여의금고봉 | Artifact Memory: Ruyi Jingu Bang |
| 10054 | 2110054 | 110003 | 110014 | 유물의 기억: 엘도라도의 금화 | Artifact Memory: Gold Coins of El Dorado |
| 10055 | 2110055 | 110003 | 110014 | 유물의 기억: 헤파이스토스의 망치 | Artifact Memory: Hephaestus's Hammer |
| 10056 | 2110056 | 110003 | 110014 | 유물의 기억: 하르페 | Artifact Memory: Harpe |
| 10057 | 2110057 | 110003 | 110014 | 유물의 기억: 아메노하바키리 | Artifact Memory: Ame No Habakiri |
| 10058 | 2110058 | 110003 | 110014 | 유물의 기억: 운명의 서판 | Artifact Memory: Tablet of Fate |
| 10059 | 2110059 | 110003 | 110014 | 유물의 기억: 아조트 검 | Artifact Memory: Azoth |
| 10060 | 2110060 | 110003 | 110014 | 유물의 기억: 찬란한 광휘의 성해포 | Artifact Memory: Holy Shroud of Splendid Radiance |
| 10061 | 2110061 | 110003 | 110014 | 유물의 기억: 롱고미니아드 | Artifact Memory: Rhongomyniad |
| 10062 | 2110062 | 110003 | 110014 | 유물의 기억: 튀르핑 | Artifact Memory: Tyrfing |
| 10063 | 2110063 | 110003 | 110014 | 유물의 기억: 골든 레코드 | Artifact Memory: Golden Record |
| 10064 | 2110064 | 110003 | 110014 | 유물의 기억: 타나토스=프라가라흐 | Artifact Memory: Thanatos = Fragarach |
| 10065 | 2110065 | 110003 | 110014 | 유물의 기억: 방주 카마엘 | Artifact Memory: Ark Chamuel |
| 10066 | 2110066 | 110003 | 110014 | 유물의 기억: 미미르의 샘물 | Artifact Memory: Mimisbrunnr |
| 10067 | 2110067 | 110003 | 110014 | 유물의 기억: 요시모토 사몬지(업화) | Artifact Memory: Yoshimoto Samonji (Inferno) |
| 10068 | 2110068 | 110003 | 110014 | 유물의 기억: 여명의 방주 메타트론 | Artifact Memory: Ark of Dawn Metatron |
| 10069 | 2110069 | 110003 | 110014 | 유물의 기억: 솔로몬의 반지 | Artifact Memory: Solomon's Ring |
| 10070 | 2110070 | 110003 | 110014 | 유물의 기억: 태양의 왕관 | Artifact Memory: Crown of the Sun |
| 10071 | 2110071 | 110003 | 110014 | 유물의 기억: 만파식적(미르) | Artifact Memory: Manpashikjeok (Mir) |
| 10072 | 2110072 | 110003 | 110014 | 유물의 기억: 청룡언월도(무쌍) | Artifact Memory: Green Dragon Crescent Blade (Peerless) |
| 10073 | 2110073 | 110003 | 110014 | 유물의 기억: 쿠투네시르카(카무이) | Artifact Memory: Kutune Shirka (Kamuy) |
| 10074 | 2110074 | 110003 | 110014 | 유물의 기억: 누아다의 의수(백은) | Artifact Memory: Nuada Airgetlám (Argent) |
| 10075 | 2110075 | 110003 | 110014 | 유물의 기억: 7발의 마탄(잔영) | Artifact Memory: The Seventh Bullet (Afterimage) |
| 10076 | 2110076 | 110003 | 110014 | 유물의 기억: 소림사 탑림 | Artifact Memory: Shaolin Temple Pagoda Forest |
| 10077 | 2110077 | 110003 | 110014 | 유물의 기억: 반혼향(각혼) | Artifact Memory: Spirit-Calling Incense (Awakened Soul) |
| 10078 | 2110078 | 110003 | 110014 | 유물의 기억: 롱기누스의 창(열락) | Artifact Memory: Spear of Longinus (Rapture) |
| 10079 | 2110079 | 110003 | 110014 | 유물의 기억: 천부인의 검 | Artifact Memory: Divine Sword of the Three Heavenly Seals |
| 10080 | 2110080 | 110003 | 110014 | 유물의 기억: 호루스의 눈 | Artifact Memory: Eye of Horus |
| 10081 | 2110081 | 110003 | 110014 | 유물의 기억: 니드호그의 이빨 | Artifact Memory: Nidhogg's Fangs |
| 10082 | 2110082 | 110003 | 110014 | 유물의 기억: 신편귀독주(낭만) | Artifact Memory: Shinpen Kidoku (Romantic) |
| 10083 | 2110083 | 110003 | 110014 | 유물의 기억: 묠니르(대천사) | Artifact Memory: Mjölnir (Archangel) |
| 10084 | 2110084 | 110003 | 110014 | 유물의 기억: 종말의 나팔 | Artifact Memory: Trumpet of the End |
| 10085 | 2110085 | 110003 | 110014 | 유물의 기억: 아야메의 백동거울 | Artifact Memory: Mirror of Ayame |
| 11001 | 2111001 | 110012 | 110020 | 금형: 영원한 약속의 탁상시계 | Mold: Table Clock of Eternal Promise |
| 11002 | 2111002 | 110012 | 110020 | 금형: 영원한 약속의 뮤직박스 | Mold: Music Box of Eternal Promise |
| 11003 | 2111003 | 110012 | 110020 | 금형: 영원한 약속의 탁상거울 | Mold: Table Mirror of Eternal Promise |
| 11004 | 2111004 | 110012 | 110020 | 금형: 영원한 약속의 금고열쇠 | Mold: Safe Key of Eternal Promise |
| 11005 | 2111005 | 110012 | 110021 | 금형: 소원을 품은 탁상시계 | Mold: Table Clock of Wishes |
| 11006 | 2111006 | 110012 | 110021 | 금형: 소원을 품은 뮤직박스 | Mold: Music Box of Wishes |
| 11007 | 2111007 | 110012 | 110021 | 금형: 소원을 품은 탁상거울 | Mold: Table Mirror of Wishes |
| 11008 | 2111008 | 110012 | 110021 | 금형: 소원을 품은 금고열쇠 | Mold: Safe Key of Wishes |
| 11009 | 2111009 | 110012 | 110022 | 금형: 춤추는 별들의 탁상시계 | Mold: Table Clock of Dancing Stars |
| 11010 | 2111010 | 110012 | 110022 | 금형: 춤추는 별들의 뮤직박스 | Mold: Music Box of Dancing Stars |
| 11011 | 2111011 | 110012 | 110022 | 금형: 춤추는 별들의 탁상거울 | Mold: Table Mirror of Dancing Stars |
| 11012 | 2111012 | 110012 | 110022 | 금형: 춤추는 별들의 금고열쇠 | Mold: Safe Key of Dancing Stars |
| 11013 | 2111013 | 110012 | 110023 | 금형: 월광을 머금은 탁상시계 | Mold: Moonlit Table Clock |
| 11014 | 2111014 | 110012 | 110023 | 금형: 월광을 머금은 뮤직박스 | Mold: Moonlit Music Box |
| 11015 | 2111015 | 110012 | 110023 | 금형: 월광을 머금은 탁상거울 | Mold: Moonlit Table Mirror |
| 11016 | 2111016 | 110012 | 110023 | 금형: 월광을 머금은 금고열쇠 | Mold: Moonlit Safe Key |
| 11017 | 2111017 | 110012 | 110024 | 금형: 천일의 빛을 담은 탁상시계 | Mold: Table Clock of a Thousand Days of Light |
| 11018 | 2111018 | 110012 | 110024 | 금형: 천일의 빛을 담은 뮤직박스 | Mold: Music Box of a Thousand Days of Light |
| 11019 | 2111019 | 110012 | 110024 | 금형: 천일의 빛을 담은 탁상거울 | Mold: Table Mirror of a Thousand Days of Light |
| 11020 | 2111020 | 110012 | 110024 | 금형: 천일의 빛을 담은 금고열쇠 | Mold: Safe Key of a Thousand Days of Light |
| 11021 | 2111021 | 110012 | 110025 | 금형: 무한한 우주의 탁상시계 | Mold: Table Clock of Infinite Universe |
| 11022 | 2111022 | 110012 | 110025 | 금형: 무한한 우주의 뮤직박스 | Mold: Music Box of Infinite Universe |
| 11023 | 2111023 | 110012 | 110025 | 금형: 무한한 우주의 탁상거울 | Mold: Table Mirror of Infinite Universe |
| 11024 | 2111024 | 110012 | 110025 | 금형: 무한한 우주의 금고열쇠 | Mold: Safe Key of Infinite Universe |
| 11025 | 2111025 | 110012 | 110020 | 금형: 영원한 약속의 회중시계 | Mold: Pocket Watch of Eternal Promise |
| 11026 | 2111026 | 110012 | 110020 | 금형: 영원한 약속의 오르골 | Mold: Music Box of Eternal Promise |
| 11027 | 2111027 | 110012 | 110020 | 금형: 영원한 약속의 접이거울 | Mold: Folding Mirror of Eternal Promise |
| 11028 | 2111028 | 110012 | 110020 | 금형: 영원한 약속의 만능열쇠 | Mold: Master Key of Eternal Promise |
| 11029 | 2111029 | 110012 | 110021 | 금형: 소원을 품은 회중시계 | Mold: Pocket Watch of Wishes |
| 11030 | 2111030 | 110012 | 110021 | 금형: 소원을 품은 오르골 | Mold: Orgel of Wishes |
| 11031 | 2111031 | 110012 | 110021 | 금형: 소원을 품은 접이거울 | Mold: Folding Mirror of Wishes |
| 11032 | 2111032 | 110012 | 110021 | 금형: 소원을 품은 만능열쇠 | Mold: Master Key of Wishes |
| 11033 | 2111033 | 110012 | 110022 | 금형: 춤추는 별들의 회중시계 | Mold: Pocket Watch of Dancing Stars |
| 11034 | 2111034 | 110012 | 110022 | 금형: 춤추는 별들의 오르골 | Mold: Music Box of Dancing Stars |
| 11035 | 2111035 | 110012 | 110022 | 금형: 춤추는 별들의 접이거울 | Mold: Folding Mirror of Dancing Stars |
| 11036 | 2111036 | 110012 | 110022 | 금형: 춤추는 별들의 만능열쇠 | Mold: Master Key of Dancing Stars |
| 11037 | 2111037 | 110012 | 110023 | 금형: 월광을 머금은 회중시계 | Mold: Moonlit Pocket Watch |
| 11038 | 2111038 | 110012 | 110023 | 금형: 월광을 머금은 오르골 | Mold: Moonlit Music Box |
| 11039 | 2111039 | 110012 | 110023 | 금형: 월광을 머금은 접이거울 | Mold: Moonlit Folding Mirror |
| 11040 | 2111040 | 110012 | 110023 | 금형: 월광을 머금은 만능열쇠 | Mold: Moonlit Master Key |
| 11041 | 2111041 | 110012 | 110024 | 금형: 천일의 빛을 담은 회중시계 | Mold: Pocket Watch of a Thousand Days of Light |
| 11042 | 2111042 | 110012 | 110024 | 금형: 천일의 빛을 담은 오르골 | Mold: Music Box of a Thousand Days of Light |
| 11043 | 2111043 | 110012 | 110024 | 금형: 천일의 빛을 담은 접이거울 | Mold: Folding Mirror of a Thousand Days of Light |
| 11044 | 2111044 | 110012 | 110024 | 금형: 천일의 빛을 담은 만능열쇠 | Mold: Master Key of a Thousand Days of Light |
| 11045 | 2111045 | 110012 | 110025 | 금형: 무한한 우주의 회중시계 | Mold: Pocket Watch of Infinite Universe |
| 11046 | 2111046 | 110012 | 110025 | 금형: 무한한 우주의 오르골 | Mold: Music Box of Infinite Universe |
| 11047 | 2111047 | 110012 | 110025 | 금형: 무한한 우주의 접이거울 | Mold: Folding Mirror of Infinite Universe |
| 11048 | 2111048 | 110012 | 110025 | 금형: 무한한 우주의 만능열쇠 | Mold: Master Key of Infinite Universe |
| 11049 | 2111049 | 110012 | 110020 | 금형: 영원한 약속의 모래시계 | Mold: Hourglass of Eternal Promise |
| 11050 | 2111050 | 110012 | 110020 | 금형: 영원한 약속의 스노우볼 | Mold: Snow Globe of Eternal Promise |
| 11051 | 2111051 | 110012 | 110020 | 금형: 영원한 약속의 손거울 | Mold: Hand Mirror of Eternal Promise |
| 11052 | 2111052 | 110012 | 110020 | 금형: 영원한 약속의 마법열쇠 | Mold: Magic Key of Eternal Promise |
| 11053 | 2111053 | 110012 | 110021 | 금형: 소원을 품은 모래시계 | Mold: Hourglass of Wishes |
| 11054 | 2111054 | 110012 | 110021 | 금형: 소원을 품은 스노우볼 | Mold: Snow Globe of Wishes |
| 11055 | 2111055 | 110012 | 110021 | 금형: 소원을 품은 손거울 | Mold: Hand Mirror of Wishes |
| 11056 | 2111056 | 110012 | 110021 | 금형: 소원을 품은 마법열쇠 | Mold: Magic Key of Wishes |
| 11057 | 2111057 | 110012 | 110022 | 금형: 춤추는 별들의 모래시계 | Mold: Hourglass of Dancing Stars |
| 11058 | 2111058 | 110012 | 110022 | 금형: 춤추는 별들의 스노우볼 | Mold: Snow Globe of Dancing Stars |
| 11059 | 2111059 | 110012 | 110022 | 금형: 춤추는 별들의 손거울 | Mold: Hand Mirror of Dancing Stars |
| 11060 | 2111060 | 110012 | 110022 | 금형: 춤추는 별들의 마법열쇠 | Mold: Magic Key of Dancing Stars |
| 11061 | 2111061 | 110012 | 110023 | 금형: 월광을 머금은 모래시계 | Mold: Moonlit Hourglass |
| 11062 | 2111062 | 110012 | 110023 | 금형: 월광을 머금은 스노우볼 | Mold: Moonlit Snow Globe |
| 11063 | 2111063 | 110012 | 110023 | 금형: 월광을 머금은 손거울 | Mold: Moonlit Hand Mirror |
| 11064 | 2111064 | 110012 | 110023 | 금형: 월광을 머금은 마법열쇠 | Mold: Moonlit Magic Key |
| 11065 | 2111065 | 110012 | 110024 | 금형: 천일의 빛을 담은 모래시계 | Mold: Hourglass of a Thousand Days of Light |
| 11066 | 2111066 | 110012 | 110024 | 금형: 천일의 빛을 담은 스노우볼 | Mold: Snow Globe of a Thousand Days of Light |
| 11067 | 2111067 | 110012 | 110024 | 금형: 천일의 빛을 담은 손거울 | Mold: Hand Mirror of a Thousand Days of Light |
| 11068 | 2111068 | 110012 | 110024 | 금형: 천일의 빛을 담은 마법열쇠 | Mold: Magic Key of a Thousand Days of Light |
| 11069 | 2111069 | 110012 | 110025 | 금형: 무한한 우주의 모래시계 | Mold: Hourglass of Infinite Universe |
| 11070 | 2111070 | 110012 | 110025 | 금형: 무한한 우주의 스노우볼 | Mold: Snow Globe of Infinite Universe |
| 11071 | 2111071 | 110012 | 110025 | 금형: 무한한 우주의 손거울 | Mold: Hand Mirror of Infinite Universe |
| 11072 | 2111072 | 110012 | 110025 | 금형: 무한한 우주의 마법열쇠 | Mold: Magic Key of Infinite Universe |
| 12000 | 2112000 | 110012 | 110014 | 메인 강화 회로 | Main Enhance Circuit |
| 12001 | 2112001 | 110012 | 110014 |  |  |
| 12002 | 2112002 | 110012 | 110014 |  |  |
| 12003 | 2112003 | 110012 | 110014 |  |  |
| 12004 | 2112004 | 110012 | 110014 |  |  |
| 12005 | 2112005 | 110012 | 110014 |  |  |
| 12006 | 2112006 | 110012 | 110014 |  |  |
| 12007 | 2112007 | 110012 | 110014 | 강화 회로: 워리어 | Enhance Circuit: Warrior |
| 12008 | 2112008 | 110012 | 110014 | 강화 회로: 레인저 | Enhance Circuit: Ranger |
| 12009 | 2112009 | 110012 | 110014 | 강화 회로: 스트라이커 | Enhance Circuit: Striker |
| 12010 | 2112010 | 110012 | 110014 | 강화 회로: 캐스터 | Enhance Circuit: Caster |
| 12011 | 2112011 | 110012 | 110014 | 강화 회로: 서포터 | Enhance Circuit: Supporter |
| 12012 | 2112012 | 110012 | 110014 | 강화 회로: 디펜더 | Enhance Circuit: Defender |
| 20001 | 3100001 | 110001 | 110012 | 힘의 증표 | Token of Power |
| 20002 | 3100002 | 110001 | 110012 | 인내의 증표 | Token of Patience |
| 20003 | 3100003 | 110001 | 110012 | 지혜의 증표 | Token of Wisdom |
| 20004 | 3100004 | 110008 | 110014 | 에리카의 부활 포션 | Erika's Resurrection Potion |
| 20005 | 3100017 | 110001 | 110014 | 사원 열쇠 | Temple Key |
| 20006 | 3100017 | 110001 | 110014 | 사원 열쇠 | Temple Key |
| 20007 | 3100017 | 110001 | 110014 | 사원 열쇠 | Temple Key |
| 20008 | 3100017 | 110001 | 110014 | 사원 열쇠 | Temple Key |
| 20009 | 3100009 | 110001 | 110014 | 유물석 | Artifact Stone |
| 20010 | 3100009 | 110001 | 110014 | 유물석 | Artifact Stone |
| 20011 | 3100009 | 110001 | 110014 | 유물석 | Artifact Stone |
| 20012 | 3100009 | 110001 | 110014 | 유물석 | Artifact Stone |
| 20013 | 3100010 | 110001 | 110020 | 투쟁의 열쇠 | Key of Struggle |
| 20014 | 3100011 | 110001 | 110020 | 자비의 열쇠 | Key of Mercy |
| 20015 | 3100012 | 110001 | 110020 | 지배의 열쇠 | Key of Control |
| 20016 | 3100018 | 110001 | 110012 | 첫 번째 종말의 기억 | Memory of the First Apocalypse |
| 20017 | 3100019 | 110001 | 110012 | 두 번째 종말의 기억 | Memory of the Second Apocalypse |
| 20018 | 3100020 | 110001 | 110012 | 세 번째 종말의 기억 | Memory of the Third Apocalypse |
| 20019 | 3100021 | 110001 | 110012 | 네 번째 종말의 기억 | Memory of the Fourth Apocalypse |
| 20020 | 3100022 | 110001 | 110012 | 다섯 번째 종말의 기억 | Memory of the Fifth Apocalypse |
| 20021 | 3100023 | 110001 | 110012 | 기원 초기화 장치 | Origin Reset Device |
| 30001 | 2130001 | 110074 | 110011 |  |  |
| 30010 | 2130010 | 110074 | 110011 |  |  |
| 30020 | 2130020 | 110074 | 110011 |  |  |
| 30030 | 2130030 | 110074 | 110011 |  |  |
| 30040 | 2130040 | 110074 | 110011 |  |  |
| 30110 | 2130110 | 110074 | 110012 |  |  |
| 30120 | 2130120 | 110074 | 110012 |  |  |
| 30210 | 2130210 | 110074 | 110012 |  |  |
| 30220 | 2130220 | 110074 | 110012 |  |  |
| 30310 | 2130310 | 110074 | 110012 |  |  |
| 30320 | 2130320 | 110074 | 110012 |  |  |
| 30410 | 2130410 | 110074 | 110012 |  |  |
| 30420 | 2130420 | 110074 | 110012 |  |  |
| 31010 | 2131010 | 110074 | 110014 |  |  |
| 31020 | 2131020 | 110074 | 110014 |  |  |
| 31030 | 2131030 | 110074 | 110014 |  |  |
| 31040 | 2131040 | 110074 | 110014 |  |  |
| 31050 | 2131050 | 110074 | 110014 |  |  |
| 31060 | 2131060 | 110074 | 110014 |  |  |
| 31070 | 2131070 | 110074 | 110014 |  |  |
| 31080 | 2131080 | 110074 | 110014 |  |  |
| 31090 | 2131090 | 110074 | 110014 |  |  |
| 31100 | 2131100 | 110074 | 110014 |  |  |
| 31110 | 2131110 | 110074 | 110014 |  |  |
| 31120 | 2131120 | 110074 | 110014 |  |  |
| 31130 | 2131130 | 110074 | 110014 |  |  |
| 31140 | 2131140 | 110074 | 110014 |  |  |
| 31150 | 2131150 | 110074 | 110014 |  |  |
| 31160 | 2131160 | 110074 | 110014 |  |  |
| 31170 | 2131170 | 110074 | 110014 |  |  |
| 32010 | 2132010 | 110074 | 110014 |  |  |
| 32020 | 2132020 | 110074 | 110014 |  |  |
| 32030 | 2132030 | 110074 | 110014 |  |  |
| 32040 | 2132040 | 110074 | 110014 |  |  |
| 32050 | 2132050 | 110074 | 110014 |  |  |
| 32060 | 2132060 | 110074 | 110014 |  |  |
| 32070 | 2132070 | 110074 | 110014 |  |  |
| 32080 | 2132080 | 110074 | 110014 |  |  |
| 32090 | 2132090 | 110074 | 110014 |  |  |
| 32100 | 2132100 | 110074 | 110014 |  |  |
| 32110 | 2132110 | 110074 | 110014 |  |  |
| 32120 | 2132120 | 110074 | 110014 |  |  |
| 32130 | 2132130 | 110074 | 110014 |  |  |
| 32140 | 2132140 | 110074 | 110014 |  |  |
| 32150 | 2132150 | 110074 | 110014 |  |  |
| 32160 | 2132160 | 110074 | 110014 |  |  |
| 32170 | 2132170 | 110074 | 110014 |  |  |
| 33010 | 2133010 | 110074 | 110014 |  |  |
| 33020 | 2133020 | 110074 | 110014 |  |  |
| 33030 | 2133030 | 110074 | 110014 |  |  |
| 33040 | 2133040 | 110074 | 110014 |  |  |
| 33050 | 2133050 | 110074 | 110014 |  |  |
| 33060 | 2133060 | 110074 | 110014 |  |  |
| 33070 | 2133070 | 110074 | 110014 |  |  |
| 33080 | 2133080 | 110074 | 110014 |  |  |
| 33090 | 2133090 | 110074 | 110014 |  |  |
| 33100 | 2133100 | 110074 | 110014 |  |  |
| 33110 | 2133110 | 110074 | 110014 |  |  |
| 33120 | 2133120 | 110074 | 110014 |  |  |
| 33130 | 2133130 | 110074 | 110014 |  |  |
| 33140 | 2133140 | 110074 | 110014 |  |  |
| 33150 | 2133150 | 110074 | 110014 |  |  |
| 33160 | 2133160 | 110074 | 110014 |  |  |
| 33170 | 2133170 | 110074 | 110014 |  |  |
| 33180 | 2133180 | 110074 | 110014 |  |  |
| 34010 | 2134010 | 110074 | 110014 |  |  |
| 34020 | 2134020 | 110074 | 110014 |  |  |
| 34030 | 2134030 | 110074 | 110014 |  |  |
| 34040 | 2134040 | 110074 | 110014 |  |  |
| 34050 | 2134050 | 110074 | 110014 |  |  |
| 34060 | 2134060 | 110074 | 110014 |  |  |
| 34070 | 2134070 | 110074 | 110014 |  |  |
| 34080 | 2134080 | 110074 | 110014 |  |  |
| 34090 | 2134090 | 110074 | 110014 |  |  |
| 34100 | 2134100 | 110074 | 110014 |  |  |
| 34110 | 2134110 | 110074 | 110014 |  |  |
| 34120 | 2134120 | 110074 | 110014 |  |  |
| 34130 | 2134130 | 110074 | 110014 |  |  |
| 34140 | 2134140 | 110074 | 110014 |  |  |
| 34150 | 2134150 | 110074 | 110014 |  |  |
| 34160 | 2134160 | 110074 | 110014 |  |  |
| 34170 | 2134170 | 110074 | 110014 |  |  |
| 35010 | 2135010 | 110074 | 110014 |  |  |
| 35020 | 2135020 | 110074 | 110014 |  |  |
| 35030 | 2135030 | 110074 | 110014 |  |  |
| 35040 | 2135040 | 110074 | 110014 |  |  |
| 35060 | 2135060 | 110074 | 110014 |  |  |
| 35080 | 2135080 | 110074 | 110014 |  |  |
| 36010 | 2136010 | 110074 | 110014 |  |  |
| 36020 | 2136020 | 110074 | 110014 |  |  |
| 36030 | 2136030 | 110074 | 110014 |  |  |
| 36050 | 2136050 | 110074 | 110014 |  |  |
| 36060 | 2136060 | 110074 | 110014 |  |  |
| 36070 | 2136070 | 110074 | 110014 |  |  |
| 36510 | 2136510 | 110074 | 110014 |  |  |
| 36520 | 2136520 | 110074 | 110014 |  |  |
| 36530 | 2136530 | 110074 | 110014 |  |  |
| 36540 | 2136540 | 110074 | 110014 |  |  |
| 36980 | 2136980 | 110074 | 110014 |  |  |
| 36990 | 2136990 | 110074 | 110014 |  |  |
| 40001 | 2140001 | 110005 | 110011 | 분수 | Fountain |
| 40002 | 2140002 | 110005 | 110012 | 마녀의 솥 분수 | Witch's Pot Fountain |
| 40003 | 2140003 | 110005 | 110014 | 초콜릿 분수 | Chocolate Fountain |
| 40004 | 2140004 | 110005 | 110014 | 흑염룡 분수 | Black Flame Dragon Fountain |
| 40101 | 2140101 | 110005 | 110011 | 벤치 | Bench |
| 40102 | 2140102 | 110005 | 110012 | 구름 벤치 | Cloud Bench |
| 40103 | 2140103 | 110005 | 110014 | 쿠키 벤치 | Cookie Bench |
| 40104 | 2140104 | 110005 | 110012 | 전통 벤치 | Traditional Bench |
| 40201 | 2140201 | 110005 | 110012 | 무대 | Stage |
| 40202 | 2140202 | 110005 | 110012 | 아이돌 무대 | Idol Stage |
| 40203 | 2140203 | 110005 | 110014 | 마술 쇼 무대 | Magic Show Stage |
| 40301 | 2140301 | 110005 | 110012 | 양 울타리 | Sheep Fence |
| 40302 | 2140302 | 110005 | 110012 | 오리 집 | Duck House |
| 40303 | 2140303 | 110005 | 110014 | 텐트 모양 강아지 집 | Tent-Shaped Puppy House |
| 40304 | 2140304 | 110005 | 110014 | 나뭇잎 캣 타워 | Leafy Cat Tower |
| 40401 | 2140401 | 110005 | 110011 | 테이블 | Table |
| 40402 | 2140402 | 110005 | 110012 | 만찬 테이블 | Dinner Table |
| 40403 | 2140403 | 110005 | 110014 | 점성술 테이블 | Astrology Table |
| 40601 | 2140601 | 110005 | 110012 | 정원 | Garden |
| 40602 | 2140602 | 110005 | 110014 | 귀족의 정원 | Noble Garden |
| 40603 | 2140603 | 110005 | 110014 | 장미 정원 | Rose Garden |
| 40701 | 2140701 | 110005 | 110012 | 여신상 | Goddess Statue |
| 40702 | 2140702 | 110005 | 110012 | 깃발을 든 여인상 | Statue of Woman With a Flag |
| 40703 | 2140703 | 110005 | 110014 | 용기사 동상 | Dragon Knight Statue |
| 40704 | 2140704 | 110005 | 110014 | 방주 모형 | Ark Model |
| 40801 | 2140801 | 110005 | 110012 | 연못 | Pond |
| 40802 | 2140802 | 110005 | 110012 | 연꽃 연못 | Lotus Pond |
| 40803 | 2140803 | 110005 | 110014 | 요정의 연못 | Fairy Pond |
| 40804 | 2140804 | 110005 | 110014 | 물레방아 연못 | Waterwheel Pond |
| 40901 | 2140901 | 110005 | 110011 | 운동기구 | Workout Equipment |
| 40902 | 2140902 | 110005 | 110012 | 짚인형 | Straw Dummy |
| 40903 | 2140903 | 110005 | 110012 | 철갑옷 | Iron Armor |
| 40904 | 2140904 | 110005 | 110012 | 샌드백 | Punching Bag |
| 40905 | 2140905 | 110005 | 110014 | 목검세트(가로) | Wooden Sword Set (Horizontal) |
| 40906 | 2140906 | 110005 | 110014 | 목검세트(세로) | Wooden Sword Set (Vertical) |
| 41001 | 2141001 | 110005 | 110011 | 나무 | Tree |
| 41002 | 2141002 | 110005 | 110011 | 단풍나무 | Maple Tree |
| 41003 | 2141003 | 110005 | 110011 | 은행나무 | Ginkgo Tree |
| 41004 | 2141004 | 110005 | 110011 | 사과나무 | Apple Tree |
| 41005 | 2141005 | 110005 | 110011 | 오렌지나무 | Orange Tree |
| 41006 | 2141006 | 110005 | 110011 | 블루베리나무 | Blueberry Tree |
| 41050 | 2141050 | 110005 | 110012 | 벚나무 | Cherry Tree |
| 41051 | 2141051 | 110005 | 110012 | 황금 사과 나무 | Golden Apple Tree |
| 41052 | 2141052 | 110005 | 110014 | 솜사탕 나무 | Cotton Candy Tree |
| 41053 | 2141053 | 110005 | 110014 | 새장이 걸린 나무 | Tree with a Birdcage |
| 41054 | 2141054 | 110005 | 110014 | 둥실둥실 달콤 풍선 | Floating High Sweet Balloon |
| 41055 | 2141055 | 110005 | 110014 | 스위츠 트리 | Sweets Tree |
| 41101 | 2141101 | 110005 | 110011 | 가로등 | Street Lamp |
| 41102 | 2141102 | 110005 | 110011 | 가로등(빨간색) | Street Lamp (Red) |
| 41103 | 2141103 | 110005 | 110011 | 가로등(노란색) | Street Lamp (Yellow) |
| 41104 | 2141104 | 110005 | 110011 | 가로등(파란색) | Street Lamp (Blue) |
| 41105 | 2141105 | 110005 | 110011 | 가로등(녹색) | Street Lamp (Green) |
| 41106 | 2141106 | 110005 | 110011 | 가로등(보라색) | Street Lamp (Purple) |
| 41107 | 2141107 | 110005 | 110011 | 가로등(흰색) | Street Lamp (White) |
| 41108 | 2141108 | 110005 | 110012 | 카카오 가로등 | Cacao Street Lamp |
| 41201 | 2141201 | 110005 | 110011 | 목재 가로등 | Wooden Street Lamp |
| 41202 | 2141202 | 110005 | 110011 | 목재 가로등(빨간색) | Wooden Street Lamp (Red) |
| 41203 | 2141203 | 110005 | 110011 | 목재 가로등(노란색) | Wooden Street Lamp (Yellow) |
| 41204 | 2141204 | 110005 | 110011 | 목재 가로등(파란색) | Wooden Street Lamp (Blue) |
| 41205 | 2141205 | 110005 | 110011 | 목재 가로등(녹색) | Wooden Street Lamp (Green) |
| 41206 | 2141206 | 110005 | 110011 | 목재 가로등(보라색) | Wooden Street Lamp (Purple) |
| 41207 | 2141207 | 110005 | 110011 | 목재 가로등(흰색) | Wooden Street Lamp (White) |
| 41301 | 2141301 | 110005 | 110011 | 노란 꽃 덤불 | Yellow Flower Bush |
| 41302 | 2141302 | 110005 | 110011 | 빨간 꽃 덤불 | Red Flower Bush |
| 41303 | 2141303 | 110005 | 110011 | 파란 꽃 덤불 | Blue Flower Bush |
| 41304 | 2141304 | 110005 | 110011 | 보라 꽃 덤불 | Purple Flower Bush |
| 41305 | 2141305 | 110005 | 110011 | 흰 꽃 덤불 | White Flower Bush |
| 41401 | 2141401 | 110005 | 110011 | 가로수 | Street Tree |
| 41501 | 2141501 | 110005 | 110011 | 짚더미 | Pile of Straw |
| 41601 | 2141601 | 110005 | 110011 | 화분 | Flowerpot |
| 41701 | 2141701 | 110005 | 110011 | 흰색 촛대 | White Candlestick |
| 41702 | 2141702 | 110005 | 110011 | 빨간색 촛대 | Red Candlestick |
| 41703 | 2141703 | 110005 | 110011 | 오렌지색 촛대 | Orange Candlestick |
| 41704 | 2141704 | 110005 | 110011 | 녹색 촛대 | Green Candlestick |
| 41705 | 2141705 | 110005 | 110011 | 파란색 촛대 | Blue Candlestick |
| 41706 | 2141706 | 110005 | 110011 | 보라색 촛대 | Purple Candlestick |
| 41707 | 2141707 | 110005 | 110011 | 민트색 촛대 | Mint Candlestick |
| 41708 | 2141708 | 110005 | 110012 | 철제 촛대 | Iron Candlestick |
| 41709 | 2141709 | 110005 | 110012 | 놋쇠 촛대 | Brass Candlestick |
| 41710 | 2141710 | 110005 | 110014 | 황금 촛대 | Golden Candlestick |
| 41711 | 2141711 | 110005 | 110014 | 로즈골드 촛대 | Rose Gold Candlestick |
| 41712 | 2141712 | 110005 | 110012 | 달밤 전통 등잔 | Moonlight Traditional Oil Lamp |
| 41801 | 2141801 | 110005 | 110011 | 인간 깃발 | Human Flag |
| 41802 | 2141802 | 110005 | 110011 | 야수 깃발 | Beast Flag |
| 41803 | 2141803 | 110005 | 110011 | 요정 깃발 | Fairy Flag |
| 41804 | 2141804 | 110005 | 110011 | 불사 깃발 | Undead Flag |
| 41805 | 2141805 | 110005 | 110012 | 천사 깃발 | Angel Flag |
| 41806 | 2141806 | 110005 | 110012 | 악마 깃발 | Demon Flag |
| 41807 | 2141807 | 110005 | 110014 | 솔레이 깃발1 | Solrey Flag 1 |
| 41808 | 2141808 | 110005 | 110014 | 솔레이 깃발2 | Solrey Flag 2 |
| 41809 | 2141809 | 110005 | 110014 | 솔레이 깃발3 | Solrey Flag 3 |
| 41810 | 2141810 | 110005 | 110014 | 솔레이 깃발4 | Solrey Flag 4 |
| 41901 | 2141901 | 110005 | 110011 | 메일박스(오렌지) | Mailbox (Orange) |
| 41902 | 2141902 | 110005 | 110011 | 메일박스(노랑) | Mailbox (Yellow) |
| 41903 | 2141903 | 110005 | 110012 | 메일박스(파랑) | Mailbox (Blue) |
| 41904 | 2141904 | 110005 | 110012 | 메일박스(초록) | Mailbox (Green) |
| 41905 | 2141905 | 110005 | 110012 | 메일박스(민트) | Mailbox (Mint) |
| 41906 | 2141906 | 110005 | 110012 | 메일박스(핑크) | Mailbox (Pink) |
| 41907 | 2141907 | 110005 | 110012 | 메일박스(보라) | Mailbox (Purple) |
| 41908 | 2141908 | 110005 | 110012 | 메일박스(검정) | Mailbox (Black) |
| 41909 | 2141909 | 110005 | 110012 | 메일박스(흰색) | Mailbox (White) |
| 41910 | 2141910 | 110005 | 110012 | 메일박스(빨강) | Mailbox (Red) |
| 42001 | 2142001 | 110005 | 110011 | 로드사인(갈색) | Road Sign (Brown) |
| 42002 | 2142002 | 110005 | 110011 | 로드사인(밤색) | Road Sign (Nutbrown) |
| 42003 | 2142003 | 110005 | 110012 | 로드사인(빨강) | Road Sign (Red) |
| 42004 | 2142004 | 110005 | 110012 | 로드사인(오렌지) | Road Sign (Orange) |
| 42005 | 2142005 | 110005 | 110012 | 로드사인(노랑) | Road Sign (Yellow) |
| 42006 | 2142006 | 110005 | 110012 | 로드사인(초록) | Road Sign (Green) |
| 42007 | 2142007 | 110005 | 110012 | 로드사인(보라) | Road Sign (Purple) |
| 42008 | 2142008 | 110005 | 110012 | 로드사인(민트) | Road Sign (Mint) |
| 42009 | 2142009 | 110005 | 110014 | 로드사인(흰색) | Road Sign (White) |
| 42010 | 2142010 | 110005 | 110014 | 로드사인(핑크) | Road Sign (Pink) |
| 42011 | 2142011 | 110005 | 110014 | 로드사인(파랑) | Road Sign (Blue) |
| 42101 | 2142101 | 110005 | 110011 | 아치펜스(대리석) | Arch Fence (Marble) |
| 42102 | 2142102 | 110005 | 110011 | 아치펜스(벽돌) | Arch Fence (Brick) |
| 42103 | 2142103 | 110005 | 110011 | 아치펜스(철제) | Arch Fence (Iron) |
| 42104 | 2142104 | 110005 | 110012 | 아치펜스(빨강) | Arch Fence (Red) |
| 42105 | 2142105 | 110005 | 110012 | 아치펜스(파랑) | Arch Fence (Blue) |
| 42106 | 2142106 | 110005 | 110012 | 아치펜스(초록) | Arch Fence (Green) |
| 42107 | 2142107 | 110005 | 110012 | 아치펜스(보라) | Arch Fence (Purple) |
| 42108 | 2142108 | 110005 | 110012 | 아치펜스(핑크) | Arch Fence (Pink) |
| 42109 | 2142109 | 110005 | 110012 | 아치펜스(흰색) | Arch Fence (White) |
| 42110 | 2142110 | 110005 | 110014 | 아치펜스(민트) | Arch Fence (Mint) |
| 42111 | 2142111 | 110005 | 110012 | 꼬마 담장 | Kiddy Wall |
| 42112 | 2142112 | 110005 | 110012 | 파티션 로프 | Rope Partition |
| 42113 | 2142113 | 110005 | 110012 | 꼬마 담장(보급형) | Kiddy Wall (Economy) |
| 42201 | 2142201 | 110005 | 110011 | 아치(대리석) | Arch (Marble) |
| 42202 | 2142202 | 110005 | 110011 | 아치(벽돌) | Arch (Brick) |
| 42203 | 2142203 | 110005 | 110011 | 아치(철제) | Arch (Iron) |
| 42204 | 2142204 | 110005 | 110012 | 아치(빨강) | Arch (Red) |
| 42205 | 2142205 | 110005 | 110012 | 아치(파랑) | Arch (Blue) |
| 42206 | 2142206 | 110005 | 110012 | 아치(초록) | Arch (Green) |
| 42207 | 2142207 | 110005 | 110012 | 아치(보라) | Arch (Purple) |
| 42208 | 2142208 | 110005 | 110012 | 아치(핑크) | Arch (Pink) |
| 42209 | 2142209 | 110005 | 110012 | 아치(흰색) | Arch (White) |
| 42210 | 2142210 | 110005 | 110014 | 아치(민트) | Arch (Mint) |
| 42211 | 2142211 | 110005 | 110012 | 이리오너라 전통 대문 | Traditional Gates |
| 42301 | 2142301 | 110005 | 110011 | 바닥타일(흰색) | Floor Tile (White) |
| 42302 | 2142302 | 110005 | 110011 | 바닥타일(갈색) | Floor Tile (Brown) |
| 42303 | 2142303 | 110005 | 110012 | 우물마루 바닥 타일 A | Checkered Floor Tile A |
| 42304 | 2142304 | 110005 | 110012 | 우물마루 바닥 타일 B | Checkered Floor Tile B |
| 42305 | 2142305 | 110005 | 110012 | 전통 문양 바닥 타일 A | Traditional Floor Tile A |
| 42306 | 2142306 | 110005 | 110012 | 전통 문양 바닥 타일 B | Traditional Floor Tile B |
| 42307 | 2142307 | 110005 | 110012 | 초코 타일 A | Choco Tile A |
| 42308 | 2142308 | 110005 | 110012 | 초코 타일 B | Choco Tile B |
| 42309 | 2142309 | 110005 | 110012 | 바삭 타일 | Crunchy Tile |
| 42310 | 2142310 | 110005 | 110012 | 꽃길 타일 | Flowery Tile |
| 42311 | 2142311 | 110005 | 110012 | 잔디 타일 | Grass Tile |
| 42312 | 2142312 | 110005 | 110012 | 모래 타일 | Sand Tile |
| 42313 | 2142313 | 110005 | 110012 | 모래 타일(직선) | Sand Tile (Straight) |
| 42314 | 2142314 | 110005 | 110012 | 모래 타일(외곽) | Sand Tile (Outer) |
| 42315 | 2142315 | 110005 | 110012 | 모래 타일(모서리) | Sand Tile (Corner) |
| 42316 | 2142316 | 110005 | 110012 | 웨딩 카펫(모서리1) | Wedding Carpet (Corner 1) |
| 42317 | 2142317 | 110005 | 110012 | 웨딩 카펫(외곽선) | Wedding Carpet (Outline) |
| 42318 | 2142318 | 110005 | 110012 | 웨딩 카펫(모서리2) | Wedding Carpet (Corner 2) |
| 42319 | 2142319 | 110005 | 110012 | 웨딩 카펫(중앙) | Wedding Carpet (Center) |
| 42401 | 2142401 | 110005 | 110014 | 천하대장군 여우 장승 | Fox World General Jangseung |
| 42402 | 2142402 | 110005 | 110014 | 지하여장군 여우 장승 | Fox Underground General Jangseung |
| 42501 | 2142501 | 110005 | 110014 | 별빛 보료 | Starlight Mattress |
| 42601 | 2142601 | 110005 | 110012 | 전통 창호 파티션 | Traditional Korean Paper Partition |
| 42602 | 2142602 | 110005 | 110012 | 팬시 초코 파티션 | Fancy Choco Partition |
| 42603 | 2142603 | 110005 | 110012 | 전통 창호 파티션(보급형) | Traditional Korean Paper Partition (Economy) |
| 42701 | 2142701 | 110005 | 110012 | 전통문양 러그 | Traditional Rug |
| 42801 | 2142801 | 110005 | 110012 | 한 상 가득 자개소반 세트 | Full Meal Portable Table Set |
| 42901 | 2142901 | 110005 | 110014 | 과유불급 금은보화 수레 | Overfilled Treasure Cart |
| 43001 | 2143001 | 110005 | 110014 | 달의 누각 | Moon Castle |
| 43002 | 2143002 | 110005 | 110012 | 매화 분재 | Potted Apricot Tree |
| 43101 | 2143101 | 110005 | 110014 | 스낵 카트 | Snack Cart |
| 43102 | 2143102 | 110005 | 110014 | 티켓 부스 | Ticket Booth |
| 43103 | 2143103 | 110005 | 110014 | 순정 메리 고 라운드 | Pure Love Merry-Go-Round |
| 43104 | 2143104 | 110005 | 110012 | 문구 초콜릿 | Chocolate Text |
| 43105 | 2143105 | 110005 | 110014 | 홀로 초코 대관람차 | Chocolate Ferris Wheel |
| 43106 | 2143106 | 110005 | 110012 | 티라미수 테이블 | Tiramisu Table |
| 43107 | 2143107 | 110005 | 110012 | 롤케이크 스툴 | Roll Cake Stool |
| 43201 | 2143201 | 110005 | 110014 | 숲속의 나무집 | Forest Tree House |
| 43202 | 2143202 | 110005 | 110012 | 든든 그루터기 | Stout Tree Stump |
| 43203 | 2143203 | 110005 | 110012 | 잠자는 여우 | Sleeping Fox |
| 43204 | 2143204 | 110005 | 110014 | 흔들 해먹 그네 | Hammock Swing |
| 43205 | 2143205 | 110005 | 110012 | 나무줄기 화분 | Stem Pot |
| 43301 | 2143301 | 110005 | 110014 | 방과 후 체육 창고 | After-School Gym Storage |
| 43302 | 2143302 | 110005 | 110012 | 칠판 | Blackboard |
| 43303 | 2143303 | 110005 | 110012 | 철제 캐비닛(그린) | Metal Cabinet (Green) |
| 43304 | 2143304 | 110005 | 110012 | 철제 캐비닛(레드) | Metal Cabinet (Red) |
| 43305 | 2143305 | 110005 | 110012 | 교실 벽 | Classroom Wall |
| 43306 | 2143306 | 110005 | 110012 | 교실 창가 벽 | Classroom Windowed Wall |
| 43307 | 2143307 | 110005 | 110012 | 모범생 책상 세트 | Scholar's Desk Set |
| 43308 | 2143308 | 110005 | 110012 | 꾸러기 책상 세트 | Troublemaker's Desk Set |
| 43309 | 2143309 | 110005 | 110012 | 교탁 | Lecture Table |
| 43310 | 2143310 | 110005 | 110012 | 교실 기둥 | Classroom Pillar |
| 43311 | 2143311 | 110005 | 110012 | 축구 골대 | Goalpost |
| 43312 | 2143312 | 110005 | 110014 | 일반 자판기 | Normal Vending Machine |
| 43313 | 2143313 | 110005 | 110014 | 스낵 자판기 | Snack Vending Machine |
| 43401 | 2143401 | 110005 | 110014 | 메리 유 웨딩 스테이지 | Marry You Wedding Stage |
| 43402 | 2143402 | 110005 | 110014 | 웨딩 가제보 | Wedding Gazebo |
| 43403 | 2143403 | 110005 | 110014 | 메리 미 그랜드 피아노 | Marry Me Grand Piano |
| 43404 | 2143404 | 110005 | 110012 | 웨딩 테이블 | Wedding Table |
| 43405 | 2143405 | 110005 | 110012 | 웨딩 체어1 | Wedding Chair 1 |
| 43406 | 2143406 | 110005 | 110012 | 웨딩 체어2 | Wedding Chair 2 |
| 43407 | 2143407 | 110005 | 110012 | 러블리 웨딩 케이크 | Lovely Wedding Cake |
| 43408 | 2143408 | 110005 | 110012 | 블룸 플라워 울타리 | Blooming Flower Fence |
| 43501 | 2143501 | 110005 | 110018 | 비비안의 칵테일 바 | Vivienne's Cocktail Bar |
| 43502 | 2143502 | 110005 | 110014 | 터틀 풀장 | Turtle Pool |
| 43503 | 2143503 | 110005 | 110014 | 리조트 카트 | Resort Cart |
| 43504 | 2143504 | 110005 | 110014 | 스윔스파 | Swim Spa |
| 43505 | 2143505 | 110005 | 110012 | 라탄 과일 바구니 | Rattan Fruit Basket |
| 43506 | 2143506 | 110005 | 110012 | 야자수 가로등 | Palm Street Lamp |
| 43507 | 2143507 | 110005 | 110018 | 튜브 대여소 | Floaty Rental |
| 43508 | 2143508 | 110005 | 110012 | 캐노피 베드 | Canopy Bed |
| 43509 | 2143509 | 110005 | 110012 | 썸머 파티션 | Summer Partition |
| 43510 | 2143510 | 110005 | 110012 | 파라솔 테이블 | Parasol Table |
| 43511 | 2143511 | 110005 | 110012 | 선베드 | Sunbed |
| 43512 | 2143512 | 110005 | 110012 | 해먹 흔들의자 | Hammock Rocker |
| 43513 | 2143513 | 110005 | 110012 | 썸머 텐트 | Summer Tent |
| 43601 | 2143601 | 110005 | 110018 | 홍란의 해변 모래성 | Honglan's Sandcastle |
| 43602 | 2143602 | 110005 | 110014 | 비치발리볼 코트 | Beach Volleyball Court |
| 43603 | 2143603 | 110005 | 110014 | 해변 보트 식당 | Beach Boat Restaurant |
| 43604 | 2143604 | 110005 | 110018 | 서핑보드 대여소 | Surfboard Rental |
| 43605 | 2143605 | 110005 | 110012 | 해변 모래 타일(직선) | Beach Sand Tile (Straight) |
| 43606 | 2143606 | 110005 | 110012 | 해변 모래 타일(외곽) | Beach Sand Tile (Outer) |
| 43607 | 2143607 | 110005 | 110012 | 해변 모래 타일 | Beach Sand Tile |
| 43608 | 2143608 | 110005 | 110012 | 해변 모래 타일(내곽) | Beach Sand Tile (Inner) |
| 43609 | 2143609 | 110005 | 110012 | 바다 타일 | Sea Tile |
| 43610 | 2143610 | 110005 | 110014 | 모험 뗏목 | Adventure Raft |
| 43611 | 2143611 | 110005 | 110012 | 조가비 분수 | Shall Fountain |
| 43612 | 2143612 | 110005 | 110012 | 해변 매트 | Beach Mat |
| 43613 | 2143613 | 110005 | 110012 | 뱃머리 보물상자 | Bow Treasure Box |
| 43614 | 2143614 | 110005 | 110012 | 산호 바위 | Coral Rock |
| 43615 | 2143615 | 110005 | 110012 | 해파리 조명등 | Jellyfish Light |
| 43616 | 2143616 | 110005 | 110012 | 아기 해파리 조명등 | Baby Jellyfish Light |
| 43617 | 2143617 | 110005 | 110012 | 해변 이정표 | Beach Sign |
| 43701 | 2143701 | 110005 | 110014 | 달밤의 궁중 다과회 | Midnight Court Refreshments |
| 43702 | 2143702 | 110005 | 110018 | 아키의 명상정원 | Aki's Meditation Garden |
| 43703 | 2143703 | 110005 | 110014 | 월묘의 달떡 절구 | Moon Rice Cake Grinding Bowl |
| 43704 | 2143704 | 110005 | 110014 | 달밤의 궁중악단 | Midnight Court Band |
| 43705 | 2143705 | 110005 | 110012 | 정원 돌길 타일 | Garden Stone Tile |
| 43706 | 2143706 | 110005 | 110018 | 전통 가을 연못 | Autumn Pond |
| 43707 | 2143707 | 110005 | 110012 | 궁중 벽보판 | Court Board |
| 43708 | 2143708 | 110005 | 110012 | 궁궐 담벼락 | Palace Wall |
| 43709 | 2143709 | 110005 | 110012 | 궁궐 관문 | Palace Gate |
| 43710 | 2143710 | 110005 | 110012 | 도란도란 장독대 | Crock Platform |
| 43711 | 2143711 | 110005 | 110012 | 보름달 풍등 | Full Moon Lantern |
| 43712 | 2143712 | 110005 | 110012 | 주렁주렁 감나무 | Persimmon Tree |
| 43713 | 2143713 | 110005 | 110012 | 달안개 전통 향로 | Moon Fog Incense Burner |
| 43801 | 2143801 | 110005 | 110014 | 숲속의 그림자 극장 | Forest Shadow Theater |
| 43802 | 2143802 | 110005 | 110014 | 마녀의 연금 솥단지 | Witch's Alchemy Pot |
| 43803 | 2143803 | 110005 | 110014 | 장미 늑대 철창 | Wolf Cage With Roses |
| 43804 | 2143804 | 110005 | 110018 | 리젤로테의 흑백합 정원 | Lizelotte's Black Lily Garden |
| 43805 | 2143805 | 110005 | 110012 | 오싹오싹 테이블 | Spooky Table |
| 43806 | 2143806 | 110005 | 110012 | 오싹오싹 의자 | Spooky Chair |
| 43807 | 2143807 | 110005 | 110012 | 철제 펜스 | Iron Fence |
| 43808 | 2143808 | 110005 | 110012 | 철제 대문 | Iron Gates |
| 43809 | 2143809 | 110005 | 110012 | 기묘한 나무 | Strange Tree |
| 43810 | 2143810 | 110005 | 110012 | 어둠 속 가로등 | Spooky Street Lamp |
| 43811 | 2143811 | 110005 | 110018 | 음산한 극장 매표소 | Spooky Theater Box Office |
| 43812 | 2143812 | 110005 | 110012 | 흑백합 화분 | Black Lily Flowerpot |
| 43813 | 2143813 | 110005 | 110012 | 묘지기 유령 | Grave Keeper Ghost |
| 43901 | 2143901 | 110005 | 110014 | 눈길을 달리는 썰매 | Snow Sleigh |
| 43902 | 2143902 | 110005 | 110018 | 캐서린의 예배당 | Catherine's Chapel |
| 43903 | 2143903 | 110005 | 110014 | 푹신푹신 거대 곰인형 | Giant Fluffy Teddy Bear |
| 43904 | 2143904 | 110005 | 110014 | 찬란한 기도의 트리 | Radiant Prayer Tree |
| 43905 | 2143905 | 110005 | 110012 | 눈 덮인 벽돌 타일 | Snow-Covered Brick Tiles |
| 43906 | 2143906 | 110005 | 110012 | 눈 녹은 벽돌 타일 | Snow-Thawed Brick Tiles |
| 43907 | 2143907 | 110005 | 110012 | 반짝반짝 아치 | Dazzling Arch |
| 43908 | 2143908 | 110005 | 110012 | 두근두근 선물 꾸러미 | Suspenseful Gift Bundle |
| 43909 | 2143909 | 110005 | 110012 | 반짝반짝 선물 꾸러미 | Glamorous Gift Bundle |
| 43910 | 2143910 | 110005 | 110012 | 행복한 눈사람 | Happy Snowman |
| 43911 | 2143911 | 110005 | 110018 | 소원 가득 양말 | Wish-Filled Stocking |
| 43912 | 2143912 | 110005 | 110012 | 눈 뭉치 | Snowballs |
| 43913 | 2143913 | 110005 | 110012 | 꼬마 눈오리 | Snow Duckling |
| 43914 | 2143914 | 110005 | 110012 | 성탄 양초 | Christmas Candle |
| 43915 | 2143915 | 110005 | 110012 | 성야의 벤치 | Pew Bench of Starry Night |
| 44001 | 2144001 | 110005 | 110014 | 크루즈 선교 | Cruise Bridge |
| 44002 | 2144002 | 110005 | 110018 | 클라우디아의 피뢰탑 | Claudia's Lightning Tower |
| 44003 | 2144003 | 110005 | 110014 | 럭셔리 풀장 | Luxury Pool |
| 44004 | 2144004 | 110005 | 110014 | 별빛 항해사 | Starlight Voyager |
| 44005 | 2144005 | 110005 | 110012 | 대리석 타일 | Marble Tile |
| 44006 | 2144006 | 110005 | 110018 | 샴페인 타워 | Champagne Tower |
| 44007 | 2144007 | 110005 | 110012 | 그랜드 하프 | Grand Harp |
| 44008 | 2144008 | 110005 | 110012 | 럭셔리 펜스 | Luxury Fence |
| 44009 | 2144009 | 110005 | 110012 | 샹들리에 스탠드 | Chandelier Stand |
| 44101 | 2144101 | 110005 | 110014 | 로맨틱 라이브 스테이지 | Romantic Live Stage |
| 44102 | 2144102 | 110005 | 110014 | 앤티크 매직 턴테이블 | Antique Magic Turntable |
| 44103 | 2144103 | 110005 | 110014 | 스위트 피팅룸 | Sweet Fitting Room |
| 44104 | 2144104 | 110005 | 110018 | 소연의 초콜릿 팩토리 | Xiaolian's Chocolate Factory |
| 44105 | 2144105 | 110005 | 110012 | 스위트 테이블 | Sweet Table |
| 44106 | 2144106 | 110005 | 110012 | 스위트 소파 | Sweet Sofa |
| 44107 | 2144107 | 110005 | 110012 | 완벽한 트레이 | Perfect Tray |
| 44108 | 2144108 | 110005 | 110018 | 카페 진열대 | Cafe Display Case |
| 44109 | 2144109 | 110005 | 110012 | 봉봉 쇼콜라 | Bonbon Chocolat |
| 44201 | 2144201 | 110005 | 110014 | 푸른 하늘 조례대 | Blue Sky Lectern |
| 44202 | 2144202 | 110005 | 110014 | 폭신폭신 생태 사육장 | Fuzzy and Fluffy Critter Quarters |
| 44203 | 2144203 | 110005 | 110014 | 나른한 오후의 양호실 | Lazy Afternoon Infirmary |
| 44204 | 2144204 | 110005 | 110018 | 유리아의 학생회실 | Yuria's Student Council Office |
| 44205 | 2144205 | 110005 | 110012 | 음수대 | Water Fountain |
| 44206 | 2144206 | 110005 | 110012 | 소각로 | Waste Incinerator |
| 44207 | 2144207 | 110005 | 110018 | 시계탑 | Clock Tower |
| 44208 | 2144208 | 110005 | 110012 | 학교 교문 | School Gate |
| 44209 | 2144209 | 110005 | 110012 | 학교 담벼락 | School Wall |
| 44210 | 2144210 | 110005 | 110012 | 벚나무 벤치 | Cherry Tree Bench |
| 44211 | 2144211 | 110005 | 110012 | 벽돌 화단 | Brick Flower Bed |
| 44301 | 2144301 | 110005 | 110014 | 축제 무대 | Festival Stage |
| 44302 | 2144302 | 110005 | 110014 | 거대 인형 등불 | Giant Cat Lantern |
| 44303 | 2144303 | 110005 | 110014 | 연못 위 다리 | Bridge over a Pond |
| 44304 | 2144304 | 110005 | 110012 | 축제 가마 | Festival Palanquin |
| 44305 | 2144305 | 110005 | 110012 | 사격 노점 | Shooting Booth |
| 44306 | 2144306 | 110005 | 110012 | 가면 노점 | Mask Booth |
| 44307 | 2144307 | 110005 | 110012 | 낚시 노점 | Fishing Booth |
| 44308 | 2144308 | 110005 | 110012 | 문어빵 노점 | Takoyaki Booth |
| 44309 | 2144309 | 110005 | 110012 | 빙수 노점 | Shaved Ice Booth |
| 44310 | 2144310 | 110005 | 110012 | 간식 노점 | Snack Booth |
| 44311 | 2144311 | 110005 | 110012 | 단책 | Tanzaku |
| 44312 | 2144312 | 110005 | 110012 | 수국 화단 | Hydrangea Flowerbed |
| 44313 | 2144313 | 110005 | 110012 | 나팔꽃 벤치 | Morning Glory Bench |
| 44314 | 2144314 | 110005 | 110012 | 대나무 평상 | Bamboo Platform |
| 44315 | 2144315 | 110005 | 110012 | 축제 가로등 | Festival Street Lamp |
| 44316 | 2144316 | 110005 | 110012 | 축제 아치 | Festival Arch |
| 44401 | 2144401 | 110005 | 110014 | 신부 대기실 | Bridal Lounge |
| 44402 | 2144402 | 110005 | 110014 | 웨딩 스튜디오 | Wedding Studio |
| 44403 | 2144403 | 110005 | 110014 | 완벽한 프러포즈 | Perfect Proposal |
| 44404 | 2144404 | 110005 | 110018 | 비올레트의 새장 침실 | Violette's Birdcage Bedroom |
| 44405 | 2144405 | 110005 | 110012 | 웨딩 마차 | Wedding Carriage |
| 44406 | 2144406 | 110005 | 110012 | 레드 카펫(직선) | Red Carpet (Straight) |
| 44407 | 2144407 | 110005 | 110012 | 레드 카펫 | Red Carpet |
| 44408 | 2144408 | 110005 | 110012 | 웨딩 포토 스탠드 | Framed Wedding Photo |
| 44409 | 2144409 | 110005 | 110012 | 들러리 인형 | Bridesmaid Plushie |
| 44410 | 2144410 | 110005 | 110018 | 하트 욕조 | Heart Bathtub |
| 44411 | 2144411 | 110005 | 110012 | 웨딩 벤치 | Wedding Bench |
| 44412 | 2144412 | 110005 | 110012 | 웨딩 아치 | Wedding Arch |
| 44501 | 2144501 | 110005 | 110014 | 허수아비 귀신 | Ghostly Scarecrows |
| 44502 | 2144502 | 110005 | 110014 | 이름 없는 무덤 | Nameless Grave |
| 44503 | 2144503 | 110005 | 110014 | 잊혀진 성당 | Forgotten Cathedral |
| 44504 | 2144504 | 110005 | 110018 | 이브의 기이한 저택 | Eve's Eccentric Mansion |
| 44505 | 2144505 | 110005 | 110012 | 버려진 거울 | Discarded Mirror |
| 44506 | 2144506 | 110005 | 110012 | 낯선 자의 불빛 | Stranger's Light |
| 44507 | 2144507 | 110005 | 110012 | 저주받은 나무 | Cursed Tree |
| 44508 | 2144508 | 110005 | 110012 | 깊은 우물 | Deep Well |
| 44509 | 2144509 | 110005 | 110018 | 숲의 오두막 | Forest Cabin |
| 44510 | 2144510 | 110005 | 110012 | 나무 판자 울타리 | Wooden Fence |
| 44511 | 2144511 | 110005 | 110012 | 발자국 타일 | Footstep Tile |
| 44601 | 2144601 | 110005 | 110014 | 서커스 분장실 | Circus Dressing Room |
| 44602 | 2144602 | 110005 | 110014 | 서커스 마차 | Circus Carriage |
| 44603 | 2144603 | 110005 | 110014 | 아슬아슬 칼 던지기 | Thrilling Knife Throwing |
| 44604 | 2144604 | 110005 | 110018 | 루테의 판타스틱 쇼타임 | Lute's Fantastic Show Time |
| 44605 | 2144605 | 110005 | 110012 | 터진다! 대포 | Boom! Cannon |
| 44606 | 2144606 | 110005 | 110012 | 알록달록 풍선 카트 | Colorful Balloon Cart |
| 44607 | 2144607 | 110005 | 110012 | 사자 포토존 | Lion Photo Spot |
| 44608 | 2144608 | 110005 | 110012 | 환영해요! 풍선 인형 | Welcoming Balloon Figure |
| 44609 | 2144609 | 110005 | 110012 | 체크무늬 타일 | Checkerboard Tile |
| 44610 | 2144610 | 110005 | 110012 | 파이어 링 | Ring of Fire |
| 44611 | 2144611 | 110005 | 110012 | 깜짝 상자 | Jack-In-The-Box |
| 44612 | 2144612 | 110005 | 110018 | 서커스 열기구 | Circus Hot Air Balloon |
| 44701 | 2144701 | 110005 | 110014 | 행복을 나르는 기차 | The Happiness Locomotive |
| 44702 | 2144702 | 110005 | 110014 | 장난감 공장 | Toy Factory |
| 44703 | 2144703 | 110005 | 110014 | 꿈 가득 패키지 | Dreamful Package |
| 44704 | 2144704 | 110005 | 110018 | 라리마의 눈 내린 썰매 광장 | Larimar's Snowy Sledding Plaza |
| 44705 | 2144705 | 110005 | 110012 | 녹아버린 눈사람 | Melted Snowman |
| 44706 | 2144706 | 110005 | 110012 | 부쉬 드 노엘 | Yule Log |
| 44707 | 2144707 | 110005 | 110018 | 칼라르식 트리 | Chalar-Style Christmas Tree |
| 44708 | 2144708 | 110005 | 110012 | 크리스마스 노움 | Christmas Gnomes |
| 44709 | 2144709 | 110005 | 110012 | 달콤한 과자집 | Sweet Gingerbread House |
| 44710 | 2144710 | 110005 | 110012 | 새하얀 발자국 | White Footprints |
| 44711 | 2144711 | 110005 | 110012 | 장난감 병정 | Toy Soldier |
| 44801 | 2144801 | 110005 | 110014 | 동백 부티크 | Camellia Boutique |
| 44802 | 2144802 | 110005 | 110014 | 다 함께 놀이마당 | Life-Size Game Board |
| 44803 | 2144803 | 110005 | 110014 | 축제 단상 | Festival Podium |
| 44804 | 2144804 | 110005 | 110018 | 캐서린(광휘)의 사랑방 | Catherine (Radiance)'s Parlor |
| 44805 | 2144805 | 110005 | 110018 | 식혜 분수 | Sweet Rice Drink Fountain |
| 44806 | 2144806 | 110005 | 110012 | 동백 테이블 | Camellia Table |
| 44807 | 2144807 | 110005 | 110012 | 동백 의자 | Camellia Chair |
| 44808 | 2144808 | 110005 | 110012 | 화훼도 병풍 | Floral Motif Folding Screen |
| 44809 | 2144809 | 110005 | 110012 | 동백 좌등 | Camellia Lantern Stand |
| 44810 | 2144810 | 110005 | 110012 | 이채 타일 | Vibrant Tile |
| 44811 | 2144811 | 110005 | 110012 | 동백나무 | Camellia Tree |
| 44812 | 2144812 | 110005 | 110012 | 가야금 | Gayageum |
| 44813 | 2144813 | 110005 | 110012 | 떡 테이블 | Rice Cake Table |
| 44820 | 2144820 | 110005 | 110018 | 로제(홍염)의 심상의 시계탑 | Rose (Prominence)'s Imaginary World Clock Tower |
| 44821 | 2144821 | 110005 | 110018 | 홍란(무쌍)의 산속 쉼터 | Honglan (Peerless)'s Mountain Refuge |
| 44822 | 2144822 | 110005 | 110018 | 지호(미르)의 대영주 옥좌 | Jiho (Mir)'s High Seat of the Great Lord |
| 44823 | 2144823 | 110005 | 110018 | 르네(백은)의 은빛 성 | Renee (Argent)'s Silver Castle |
| 44824 | 2144824 | 110005 | 110018 | 메피스토펠레스(여명)의 구원의 방주 | Mephistopheles (Dawn)'s Ark of Salvation |
| 44825 | 2144825 | 110005 | 110018 | 미리암(잔영)의 전투훈련실 | Miriam (Afterimage)'s Combat Training Room |
| 44826 | 2144826 | 110005 | 110018 | 가넷의 카지노 | Garnet's Casino |
| 44827 | 2144827 | 110005 | 110018 | 셰리의 해적선 | Cherrie's Pirate Ship |
| 44901 | 2144901 | 110005 | 110014 | 유리 온실 | Glass Greenhouse |
| 44902 | 2144902 | 110005 | 110014 | 티타임 테이블 | Tea Table |
| 44903 | 2144903 | 110005 | 110014 | 럭셔리한 귀빈실 | Opulent Guest Room |
| 44904 | 2144904 | 110005 | 110018 | 린지(타나토스)의 서재 | Linzy (Thanatos)'s Study |
| 44905 | 2144905 | 110005 | 110018 | 메이드의 주방 | Maids' Kitchen |
| 44906 | 2144906 | 110005 | 110012 | 정원 토피어리 | Garden Topiary |
| 44907 | 2144907 | 110005 | 110012 | 실베스터 조이 3세의 샘 | King Sylvester Joey III's Basin |
| 44908 | 2144908 | 110005 | 110012 | 티타임 트롤리 | Tea Trolley |
| 44909 | 2144909 | 110005 | 110012 | 엘레강스 바닥 타일 | Elegant Floor Tile |
| 44910 | 2144910 | 110005 | 110012 | 메이드의 빨래터 | Maids' Laundry Area |
| 44911 | 2144911 | 110005 | 110012 | 정원 가로등 | Garden Street Lamp |
| 44912 | 2144912 | 110005 | 110012 | 정원 담벼락 | Garden Wall |
| 44913 | 2144913 | 110005 | 110012 | 정원 대문 | Garden Gate |
| 45001 | 2145001 | 110005 | 110014 | 안전요원 망루 | Lifeguard Tower |
| 45002 | 2145002 | 110005 | 110014 | 정글 폭포 | Jungle Waterfall |
| 45003 | 2145003 | 110005 | 110014 | 바위섬 항구 | Rock Island Port |
| 45004 | 2145004 | 110005 | 110018 | 니아의 오두막 | Nia's Cabin |
| 45005 | 2145005 | 110005 | 110018 | 카누 | Canoe |
| 45006 | 2145006 | 110005 | 110012 | 에메랄드 바다 타일 | Emerald Ocean Tile |
| 45007 | 2145007 | 110005 | 110012 | 꽃잎 해변 모래 타일(직선) | Petal Beach Sand Tile (Straight) |
| 45008 | 2145008 | 110005 | 110012 | 꽃잎 해변 모래 타일(외곽) | Petal Beach Sand Tile (Outer) |
| 45009 | 2145009 | 110005 | 110012 | 꽃잎 해변 모래 타일 | Petal Beach Sand Tile |
| 45010 | 2145010 | 110005 | 110012 | 꽃잎 해변 모래 타일(내곽) | Petal Beach Sand Tile (Inner) |
| 45011 | 2145011 | 110005 | 110012 | 음료 디스펜서 바 | Beverage Station |
| 45012 | 2145012 | 110005 | 110012 | 대형 도마뱀 튜브 | Large Lizard Pool Tube |
| 45013 | 2145013 | 110005 | 110012 | 야자수 | Palm Tree |
| 45014 | 2145014 | 110005 | 110012 | 꽃이 핀 야자수 | Blooming Palm Tree |
| 45015 | 2145015 | 110005 | 110012 | 바베큐 그릴 | Barbecue Grill |
| 45016 | 2145016 | 110005 | 110012 | 어탁 | Fish Rubbing |
| 45017 | 2145017 | 110005 | 110014 | 라이브 세션 밴드 | Live Band |
| 45018 | 2145018 | 110005 | 110014 | 아이돌의 포토존 | Idol Photo Spot |
| 45019 | 2145019 | 110005 | 110014 | 뮤직비디오 촬영 세트 | Music Video Filming Set |
| 45020 | 2145020 | 110005 | 110018 | 벨레드의 스페셜 스테이지 | Beleth's Special Stage |
| 45021 | 2145021 | 110005 | 110018 | 콘서트 티켓 부스 | Concert Ticket Booth |
| 45022 | 2145022 | 110005 | 110012 | 무대 의상 전시대 | Stage Costume Display Stand |
| 45023 | 2145023 | 110005 | 110012 | 굿즈 팝업 스토어 | Pop Up Merch Store |
| 45024 | 2145024 | 110005 | 110012 | 댄스 플로어 | Dance Floor |
| 45025 | 2145025 | 110005 | 110012 | 가로등 배너 | Street Lamp Banner |
| 45026 | 2145026 | 110005 | 110012 | 무대 바닥 타일 | Stage Platform Tile |
| 45027 | 2145027 | 110005 | 110012 | 콘서트장 입구 | Concert Hall Entrance |
| 45028 | 2145028 | 110005 | 110012 | 자이언트 붐박스 | Giant Boombox |
| 45029 | 2145029 | 110005 | 110012 | 공연장 좌석 | Concert Hall Seating |
| 45030 | 2145030 | 110005 | 110014 | 궁중 음악 스테이지 | Palace Music Stage |
| 45031 | 2145031 | 110005 | 110014 | 거대 당고 | Giant Dango |
| 45032 | 2145032 | 110005 | 110014 | 축제용 떡국 | Festival Rice Cake Soup |
| 45033 | 2145033 | 110005 | 110018 | 아폴리온의 새해 운세 뽑기 | Apollyon's New Year's Fortune Draw |
| 45034 | 2145034 | 110005 | 110018 | 연날리기 | Kite Flying |
| 45035 | 2145035 | 110005 | 110012 | 소원판 | Wish Plaque |
| 45036 | 2145036 | 110005 | 110012 | 구원자 등불 | Savior's Lamp |
| 45037 | 2145037 | 110005 | 110012 | 잔칫상 | Festival Banquet |
| 45038 | 2145038 | 110005 | 110012 | 새해 음식 상점 | New Year's Food Shop |
| 45039 | 2145039 | 110005 | 110012 | 복주머니 | Lucky Pouch |
| 47001 | 2147001 | 110005 | 110018 | 메피스토펠레스 석상 | Mephistopheles Statue |
| 47002 | 2147002 | 110005 | 110018 | 탈리아 석상 | Talia Statue |
| 47003 | 2147003 | 110005 | 110018 | 재클린 석상 | Jacqueline Statue |
| 47004 | 2147004 | 110005 | 110018 | 홍란 석상 | Honglan Statue |
| 47005 | 2147005 | 110005 | 110018 | 린지 석상 | Linzy Statue |
| 47006 | 2147006 | 110005 | 110018 | 아야메 석상 | Ayame Statue |
| 47007 | 2147007 | 110005 | 110018 | 니콜 석상 | Nicole Statue |
| 47008 | 2147008 | 110005 | 110018 | 비올레트 석상 | Violette Statue |
| 47009 | 2147009 | 110005 | 110018 | 구원자 석상 | Savior Statue |
| 47010 | 2147010 | 110005 | 110018 | 아드리안 석상 | Adrianne Statue |
| 47011 | 2147011 | 110005 | 110018 | 제이드 석상 | Jade Statue |
| 47012 | 2147012 | 110005 | 110018 | 클로이 석상 | Chloe Statue |
| 47013 | 2147013 | 110005 | 110018 | 프림 석상 | Prim Statue |
| 47014 | 2147014 | 110005 | 110018 | 리젤로테 석상 | Lizelotte Statue |
| 47015 | 2147015 | 110005 | 110018 | 순이 석상 | Soonie Statue |
| 47016 | 2147016 | 110005 | 110018 | 아키 석상 | Aki Statue |
| 47017 | 2147017 | 110005 | 110018 | 나이아 석상 | Naiah Statue |
| 47018 | 2147018 | 110005 | 110018 | 미카 석상 | Mica Statue |
| 47019 | 2147019 | 110005 | 110018 | 시하 석상 | Seeha Statue |
| 47020 | 2147020 | 110005 | 110018 | 클라우디아 석상 | Claudia's Statue |
| 47021 | 2147021 | 110005 | 110018 | 니니 석상 | Nini Statue |
| 47022 | 2147022 | 110005 | 110018 | 페트라 석상 | Petra Statue |
| 47023 | 2147023 | 110005 | 110018 | 클레르 석상 | Claire Statue |
| 47024 | 2147024 | 110005 | 110018 | 클라라 석상 | Clara Statue |
| 47100 | 2147100 | 110005 | 110018 | 1주년 기념 케이크 | 1st Anniversary Cake |
| 47101 | 2147101 | 110005 | 110014 | 산달폰 | Sandalphon |
| 47102 | 2147102 | 110005 | 110014 | 자프키엘 | Zafkiel |
| 47103 | 2147103 | 110005 | 110018 | 2주년 기념 케이크 | 2nd Anniversary Cake |
| 47104 | 2147104 | 110005 | 110018 | 파격적인 입간판 | Scandalous Sign |
| 47105 | 2147105 | 110005 | 110018 | 3주년 기념 케이크 | 3rd Anniversary Cake |
| 48001 | 2148001 | 110005 | 110011 | 소형 잡화점 | Small General Store |
| 48002 | 2148002 | 110005 | 110012 | 중형 잡화점 | Medium General Store |
| 48003 | 2148003 | 110005 | 110014 | 대형 잡화점 | Large General Store |
| 48011 | 2148011 | 110005 | 110011 | 소형 플라워숍 | Small Flower Shop |
| 48012 | 2148012 | 110005 | 110012 | 중형 플라워숍 | Medium Flower Shop |
| 48013 | 2148013 | 110005 | 110014 | 대형 플라워숍 | Large Flower Shop |
| 48021 | 2148021 | 110005 | 110011 | 소형 베이커리 | Small Bakery |
| 48022 | 2148022 | 110005 | 110012 | 중형 베이커리 | Medium Bakery |
| 48023 | 2148023 | 110005 | 110014 | 대형 베이커리 | Large Bakery |
| 48031 | 2148031 | 110005 | 110011 | 소형 레스토랑 | Small Restaurant |
| 48032 | 2148032 | 110005 | 110012 | 중형 레스토랑 | Medium Restaurant |
| 48033 | 2148033 | 110005 | 110014 | 대형 레스토랑 | Large Restaurant |
| 48041 | 2148041 | 110005 | 110011 | 소형 카페 | Small Cafe |
| 48042 | 2148042 | 110005 | 110012 | 중형 카페 | Medium Cafe |
| 48043 | 2148043 | 110005 | 110014 | 대형 카페 | Large Cafe |
| 48051 | 2148051 | 110005 | 110011 | 소형 도서관 | Small Library |
| 48052 | 2148052 | 110005 | 110012 | 중형 도서관 | Medium Library |
| 48053 | 2148053 | 110005 | 110014 | 대형 도서관 | Large Library |
| 48061 | 2148061 | 110005 | 110011 | 소형 성당 | Small Cathedral |
| 48062 | 2148062 | 110005 | 110012 | 중형 성당 | Medium Cathedral |
| 48063 | 2148063 | 110005 | 110014 | 대형 성당 | Large Cathedral |
| 48071 | 2148071 | 110005 | 110011 | 소형 아틀리에 | Small Atelier |
| 48072 | 2148072 | 110005 | 110012 | 중형 아틀리에 | Medium Atelier |
| 48073 | 2148073 | 110005 | 110014 | 대형 아틀리에 | Large Atelier |
| 48081 | 2148081 | 110005 | 110011 | 소형 대장간 | Small Forge |
| 48082 | 2148082 | 110005 | 110012 | 중형 대장간 | Medium Forge |
| 48083 | 2148083 | 110005 | 110014 | 대형 대장간 | Large Forge |
| 48091 | 2148091 | 110005 | 110018 | 유물 발굴터 | Artifact Excavation Site |
| 48092 | 2148092 | 110005 | 110018 | 기억의 돌 | Stone of Memory |
| 48093 | 2148093 | 110005 | 110018 | 고대 유물 발굴터 | Ancient Artifact Excavation Site |
| 48094 | 2148094 | 110005 | 110018 | 고대 기억의 돌 | Stone of Ancient Memory |
| 48095 | 2148095 | 110005 | 110018 | 마나석 발굴터 | Manastone Dig Site |
| 48096 | 2148096 | 110005 | 110018 | 강화석 정제소 | Enhance Stone Refinery |
| 49000 | 2149000 | 110005 | 110018 | 영주의 저택 | Lord's Manor |
| 49001 | 2149001 | 110005 | 110011 | 용맹의 소형 저택 | Small Manor of Valor |
| 49002 | 2149002 | 110005 | 110011 | 신념의 소형 저택 | Small Manor of Belief |
| 49003 | 2149003 | 110005 | 110011 | 불굴의 소형 저택 | Small Manor of Indomitability |
| 49011 | 2149011 | 110005 | 110012 | 용맹의 중형 저택 | Medium Manor of Valor |
| 49012 | 2149012 | 110005 | 110012 | 신념의 중형 저택 | Medium Manor of Belief |
| 49013 | 2149013 | 110005 | 110012 | 불굴의 중형 저택 | Medium Manor of Indomitability |
| 49021 | 2149021 | 110005 | 110014 | 용맹의 대형 저택 | Large Manor of Valor |
| 49022 | 2149022 | 110005 | 110014 | 신념의 대형 저택 | Large Manor of Belief |
| 49023 | 2149023 | 110005 | 110014 | 불굴의 대형 저택 | Large Manor of Indomitability |
| 49501 | 2149501 | 110005 | 110014 | 레이싱 서킷 시작 지점 | Race Track Starting Point |
| 49502 | 2149502 | 110005 | 110014 | 레이싱 서킷 종료 지점 | Race Track Finish Point |
| 49503 | 2149503 | 110005 | 110014 | 레이싱 서킷 중간 지점1 | Race Track Mid-Route Point 1 |
| 49504 | 2149504 | 110005 | 110014 | 레이싱 서킷 중간 지점2 | Race Track Mid-Route Point 2 |
| 49505 | 2149505 | 110005 | 110014 | 레이싱 서킷 중간 지점3 | Race Track Mid-Route Point 3 |
| 49506 | 2149506 | 110005 | 110014 | 레이싱 서킷 중간 지점4 | Race Track Mid-Route Point 4 |
| 49507 | 2149507 | 110005 | 110014 | 레이싱 서킷 중간 지점5 | Race Track Mid-Route Point 5 |
| 49508 | 2149508 | 110005 | 110014 |  |  |
| 49601 | 2149601 | 110079 | 110018 | 눈썰매 (플레이어 용) | Snow Sled (for Player) |
| 49602 | 2149602 | 110079 | 110018 | 눈썰매 (정령 용) | Snow Sled (for Souls) |
| 49603 | 2149603 | 110079 | 110018 | 오리배 (플레이어 용) | Duck Boat (for Player) |
| 49604 | 2149604 | 110079 | 110018 | 오리배 (정령 용) | Duck Boat (for Souls) |
| 49605 | 2149605 | 110079 | 110018 | 카트 (플레이어 용) | Go-Kart (for Player) |
| 49606 | 2149606 | 110079 | 110018 | 카트 (정령 용) | Go-Kart (for Souls) |
| 50000 | 2150000 | 110080 | 110020 | 발전의 재 | Ash of Progress |
| 51301 | 2151301 | 110801 | 110011 |  |  |
| 51302 | 2151302 | 110801 | 110011 |  |  |
| 60001 | 160001 | 110077 | 110020 | Shooting Star 프로듀서 | Shooting Star Producer |
| 60002 | 160002 | 110077 | 110020 | 두둥실 프로듀서 | Floating Producer |
| 60003 | 160003 | 110077 | 110020 | Love Note 프로듀서 | Love Note Producer |
| 60004 | 160004 | 110077 | 110020 | Yum 프로듀서 | Yum Producer |
| 60005 | 160005 | 110077 | 110020 | 나만의 별 | My Own Star |
| 60006 | 160006 | 110077 | 110020 | 오늘의 기분 두둥실 | Today's Mood Floating |
| 60007 | 160007 | 110077 | 110020 | 가득 채워줘 | Fill Me Up |
| 60008 | 160008 | 110077 | 110020 | 잊을 수 없는 마음 | Unforgettable Heart |
| 510101 | 21510101 | 110077 | 110012 | 스티커: 소중한 메피스토펠레스 | Sticker: Precious Mephistopheles |
| 510201 | 21510201 | 110077 | 110012 | 스티커: 소중한 벨레드 | Sticker: Precious Beleth |
| 510301 | 21510301 | 110077 | 110012 | 스티커: 소중한 클레르 | Sticker: Precious Claire |
| 510401 | 21510401 | 110077 | 110012 | 스티커: 소중한 아키 | Sticker: Precious Aki |
| 510501 | 21510501 | 110077 | 110012 | 스티커: 소중한 제이드 | Sticker: Precious Jade |
| 510601 | 21510601 | 110077 | 110012 | 스티커: 소중한 린지 | Sticker: Precious Linzy |
| 510701 | 21510701 | 110077 | 110012 | 스티커: 소중한 나오미 | Sticker: Precious Naomi |
| 510801 | 21510801 | 110077 | 110012 | 스티커: 소중한 릴리트 | Sticker: Precious Lilith |
| 510901 | 21510901 | 110077 | 110012 | 스티커: 소중한 캐서린 | Sticker: Precious Catherine |
| 511001 | 21511001 | 110077 | 110012 | 스티커: 소중한 셰리 | Sticker: Precious Cherrie |
| 511101 | 21511101 | 110077 | 110012 | 스티커: 소중한 도라 | Sticker: Precious Dora |
| 511201 | 21511201 | 110077 | 110012 | 스티커: 소중한 지호 | Sticker: Precious Jiho |
| 511301 | 21511301 | 110077 | 110012 | 스티커: 소중한 헤이즐 | Sticker: Precious Hazel |
| 511401 | 21511401 | 110077 | 110012 | 스티커: 소중한 에일린 | Sticker: Precious Eileen |
| 511501 | 21511501 | 110077 | 110012 | 스티커: 소중한 로제(홍염) | Sticker: Precious Rose (Prominence) |
| 511601 | 21511601 | 110077 | 110012 | 스티커: 소중한 지호(미르) | Sticker: Precious Jiho (Mir) |
| 511701 | 21511701 | 110077 | 110012 | 스티커: 소중한 셰리(낭만) | Sticker: Precious Cherrie (Romantic) |
| 520101 | 21520101 | 110077 | 110012 | 스티커: 소중한 홍란 | Sticker: Precious Honglan |
| 520201 | 21520201 | 110077 | 110012 | 스티커: 소중한 순이 | Sticker: Precious Soonie |
| 520301 | 21520301 | 110077 | 110012 | 스티커: 소중한 아이라 | Sticker: Precious Aira |
| 520401 | 21520401 | 110077 | 110012 | 스티커: 소중한 시하 | Sticker: Precious Seeha |
| 520501 | 21520501 | 110077 | 110012 | 스티커: 소중한 미카 | Sticker: Precious Mica |
| 520701 | 21520701 | 110077 | 110012 | 스티커: 소중한 플린 | Sticker: Precious Flynn |
| 520801 | 21520801 | 110077 | 110012 | 스티커: 소중한 타샤 | Sticker: Precious Tasha |
| 520901 | 21520901 | 110077 | 110012 | 스티커: 소중한 하루 | Sticker: Precious Haru |
| 521001 | 21521001 | 110077 | 110012 | 스티커: 소중한 루테 | Sticker: Precious Lute |
| 521101 | 21521101 | 110077 | 110012 | 스티커: 소중한 클라라 | Sticker: Precious Clara |
| 521201 | 21521201 | 110077 | 110012 | 스티커: 소중한 소연 | Sticker: Precious Xiaolian |
| 521301 | 21521301 | 110077 | 110012 | 스티커: 소중한 사쿠요 | Sticker: Precious Sakuyo |
| 521401 | 21521401 | 110077 | 110012 | 스티커: 소중한 오닉스 | Sticker: Precious Onyx |
| 521501 | 21521501 | 110077 | 110012 | 스티커: 소중한 사쿠요(업화) | Sticker: Precious Sakuyo (Inferno) |
| 521601 | 21521601 | 110077 | 110012 | 스티커: 소중한 홍란(무쌍) | Sticker: Precious Honglan (Peerless) |
| 521701 | 21521701 | 110077 | 110012 | 스티커: 소중한 하루(카무이) | Sticker: Precious Haru (Kamuy) |
| 530101 | 21530101 | 110077 | 110012 | 스티커: 소중한 에리카 | Sticker: Precious Erika |
| 530301 | 21530301 | 110077 | 110012 | 스티커: 소중한 르네 | Sticker: Precious Renee |
| 530401 | 21530401 | 110077 | 110012 | 스티커: 소중한 탈리아 | Sticker: Precious Talia |
| 530501 | 21530501 | 110077 | 110012 | 스티커: 소중한 칸나 | Sticker: Precious Kanna |
| 530601 | 21530601 | 110077 | 110012 | 스티커: 소중한 이디스 | Sticker: Precious Edith |
| 530701 | 21530701 | 110077 | 110012 | 스티커: 소중한 니콜 | Sticker: Precious Nicole |
| 530801 | 21530801 | 110077 | 110012 | 스티커: 소중한 비비안 | Sticker: Precious Vivienne |
| 530901 | 21530901 | 110077 | 110012 | 스티커: 소중한 미리암 | Sticker: Precious Miriam |
| 531001 | 21531001 | 110077 | 110012 | 스티커: 소중한 클로이 | Sticker: Precious Chloe |
| 531101 | 21531101 | 110077 | 110012 | 스티커: 소중한 나이아 | Sticker: Precious Naiah |
| 531201 | 21531201 | 110077 | 110012 | 스티커: 소중한 마농 | Sticker: Precious Manon |
| 531301 | 21531301 | 110077 | 110012 | 스티커: 소중한 다프네 | Sticker: Precious Daphne |
| 531401 | 21531401 | 110077 | 110012 | 스티커: 소중한 도미니크 | Sticker: Precious Dominique |
| 531501 | 21531501 | 110077 | 110012 | 스티커: 소중한 웨리 | Sticker: Precious Wheri |
| 531601 | 21531601 | 110077 | 110012 | 스티커: 소중한 르네(백은) | Sticker: Precious Renee (Argent) |
| 531701 | 21531701 | 110077 | 110012 | 스티커: 소중한 미리암(잔영) | Sticker: Precious Miriam (Afterimage) |
| 531801 | 21531801 | 110077 | 110012 | 스티커: 소중한 라우라 | Sticker: Precious Laura |
| 540101 | 21540101 | 110077 | 110012 | 스티커: 소중한 비올레트 | Sticker: Precious Violette |
| 540201 | 21540201 | 110077 | 110012 | 스티커: 소중한 가넷 | Sticker: Precious Garnet |
| 540301 | 21540301 | 110077 | 110012 | 스티커: 소중한 레베카 | Sticker: Precious Rebecca |
| 540401 | 21540401 | 110077 | 110012 | 스티커: 소중한 멜피스 | Sticker: Precious Melfice |
| 540501 | 21540501 | 110077 | 110012 | 스티커: 소중한 브라이스 | Sticker: Precious Bryce |
| 540601 | 21540601 | 110077 | 110012 | 스티커: 소중한 프림 | Sticker: Precious Prim |
| 540701 | 21540701 | 110077 | 110012 | 스티커: 소중한 재클린 | Sticker: Precious Jacqueline |
| 540801 | 21540801 | 110077 | 110012 | 스티커: 소중한 벨라나 | Sticker: Precious Velanna |
| 540901 | 21540901 | 110077 | 110012 | 스티커: 소중한 에루샤 | Sticker: Precious Erusha |
| 541001 | 21541001 | 110077 | 110012 | 스티커: 소중한 페트라 | Sticker: Precious Petra |
| 541101 | 21541101 | 110077 | 110012 | 스티커: 소중한 니니 | Sticker: Precious Nini |
| 541201 | 21541201 | 110077 | 110012 | 스티커: 소중한 오토하 | Sticker: Precious Otoha |
| 541301 | 21541301 | 110077 | 110012 | 스티커: 소중한 조앤 | Sticker: Precious Joanne |
| 541401 | 21541401 | 110077 | 110012 | 스티커: 소중한 시그리드 | Sticker: Precious Sigrid |
| 541501 | 21541501 | 110077 | 110012 | 스티커: 소중한 바이스 | Sticker: Precious Weiss |
| 541601 | 21541601 | 110077 | 110012 | 스티커: 소중한 페트라(각혼) | Sticker: Precious Petra (Awakened Soul) |
| 541701 | 21541701 | 110077 | 110012 | 스티커: 소중한 가넷(열락) | Sticker: Precious Garnet (Rapture) |
| 550101 | 21550101 | 110077 | 110012 | 스티커: 소중한 클라우디아 | Sticker: Precious Claudia |
| 550201 | 21550201 | 110077 | 110012 | 스티커: 소중한 아드리안 | Sticker: Precious Adrianne |
| 550301 | 21550301 | 110077 | 110012 | 스티커: 소중한 유리아 | Sticker: Precious Yuria |
| 550401 | 21550401 | 110077 | 110012 | 스티커: 소중한 한울 | Sticker: Precious Hanul |
| 550601 | 21550601 | 110077 | 110012 | 스티커: 소중한 카넬리안 | Sticker: Precious Carnelian |
| 550801 | 21550801 | 110077 | 110012 | 스티커: 소중한 클라우디아(대천사) | Sticker: Precious Claudia (Archangel) |
| 560101 | 21560101 | 110077 | 110012 | 스티커: 소중한 라리마 | Sticker: Precious Larimar |
| 560201 | 21560201 | 110077 | 110012 | 스티커: 소중한 리젤로테 | Sticker: Precious Lizelotte |
| 560301 | 21560301 | 110077 | 110012 | 스티커: 소중한 아야메 | Sticker: Precious Ayame |
| 560501 | 21560501 | 110077 | 110012 | 스티커: 소중한 이브 | Sticker: Precious Eve |
| 560601 | 21560601 | 110077 | 110012 | 스티커: 소중한 니아 | Sticker: Precious Nia |
| 560701 | 21560701 | 110077 | 110012 | 스티커: 소중한 아야메(츠쿠요미) | Sticker: Precious Ayame (Tsukuyomi) |
| 565101 | 21565101 | 110077 | 110012 | 스티커: 소중한 캐서린(광휘) | Sticker: Precious Catherine (Radiance) |
| 565201 | 21565201 | 110077 | 110012 | 스티커: 소중한 린지(타나토스) | Sticker: Precious Linzy (Thanatos) |
| 565301 | 21565301 | 110077 | 110012 | 스티커: 소중한 메피스토펠레스(여명) | Sticker: Precious Mephistopheles (Dawn) |
| 565401 | 21565401 | 110077 | 110012 | 스티커: 소중한 유리아(아폴리온) | Sticker: Precious Yuria (Apollyon) |
| 569801 | 21569801 | 110077 | 110012 | 스티커: 소중한 토키사키 쿠루미 | Sticker: Precious Kurumi Tokisaki |
| 569901 | 21569901 | 110077 | 110012 | 스티커: 소중한 야토가미 토카 | Sticker: Precious Tohka Yatogami |

## tbl_string_item 전체 (총 4909개)

| no_value(SNO) | KR | EN |
|---|---|---|
| 156107 | 트로이카 연합 훈장 | Troyca Alliance Medal |
| 156108 | 트로이카 연합 훈장(3위) | Troyca Alliance Medal (#3) |
| 156109 | 트로이카 연합 훈장(2위) | Troyca Alliance Medal (#2) |
| 156110 | 트로이카 연합 훈장(1위) | Troyca Alliance Medal (#1) |
| 156117 | 아우렐리아 연합 훈장 | Aurelia Alliance Medal |
| 156118 | 아우렐리아 연합 훈장(3위) | Aurelia Alliance Medal (#3) |
| 156119 | 아우렐리아 연합 훈장(2위) | Aurelia Alliance Medal (#2) |
| 156120 | 아우렐리아 연합 훈장(1위) | Aurelia Alliance Medal (#1) |
| 156127 | 타브리아 연합 훈장 | Tabria Alliance Medal |
| 156128 | 타브리아 연합 훈장(3위) | Tabria Alliance Medal (#3) |
| 156129 | 타브리아 연합 훈장(2위) | Tabria Alliance Medal (#2) |
| 156130 | 타브리아 연합 훈장(1위) | Tabria Alliance Medal (#1) |
| 156137 | 페이렌 연합 훈장 | Fayren Alliance Medal |
| 156138 | 페이렌 연합 훈장(3위) | Fayren Alliance Medal (#3) |
| 156139 | 페이렌 연합 훈장(2위) | Fayren Alliance Medal (#2) |
| 156140 | 페이렌 연합 훈장(1위) | Fayren Alliance Medal (#1) |
| 156147 | 칼라르 연합 훈장 | Chalar Alliance Medal |
| 156148 | 칼라르 연합 훈장(3위) | Chalar Alliance Medal (#3) |
| 156149 | 칼라르 연합 훈장(2위) | Chalar Alliance Medal (#2) |
| 156150 | 칼라르 연합 훈장(1위) | Chalar Alliance Medal (#1) |
| 156157 | 가온 연합 훈장 | Gaon Alliance Medal |
| 156158 | 가온 연합 훈장(3위) | Gaon Alliance Medal (#3) |
| 156159 | 가온 연합 훈장(2위) | Gaon Alliance Medal (#2) |
| 156160 | 가온 연합 훈장(1위) | Gaon Alliance Medal (#1) |
| 156167 | 솔레이 연합 훈장 | Solrey Alliance Medal |
| 156168 | 솔레이 연합 훈장(3위) | Solrey Alliance Medal (#3) |
| 156169 | 솔레이 연합 훈장(2위) | Solrey Alliance Medal (#2) |
| 156170 | 솔레이 연합 훈장(1위) | Solrey Alliance Medal (#1) |
| 156171 | 여름 합숙 훈련 | Summer Training Camp |
| 156172 | 여름 합숙 훈련 (3위) | Summer Training Camp (#3) |
| 156173 | 여름 합숙 훈련 (2위) | Summer Training Camp (#2) |
| 156174 | 여름 합숙 훈련 (1위) | Summer Training Camp (#1) |
| 156401 | 종말의 지배자 | Doomsday Ruler |
| 156402 | 종말의 수호자 | Doomsday Guardian |
| 156403 | 종말의 집행자 | Doomsday Enforcer |
| 156404 | 종말을 부르는 인형 | Doomsday Doll |
| 156406 | 비탄의 지배자 | Ruler of Sorrow |
| 156407 | 비탄의 수호자 | Guardian of Sorrow |
| 156408 | 비탄의 집행자 | Enforcer of Sorrow |
| 156409 | 비탄의 성녀 | Saint of Sorrow |
| 156411 | 멸망의 지배자 | Destruction Ruler |
| 156412 | 멸망의 수호자 | Destruction Guardian |
| 156413 | 멸망의 집행자 | Destruction Enforcer |
| 156414 | 세계를 멸망시킨 마녀 | Witch Who Destroyed the World |
| 156416 | 전쟁의 지배자 | Ruler of War |
| 156417 | 전쟁의 수호자 | Guardian of War |
| 156418 | 전쟁의 집행자 | Enforcer of War |
| 156419 | 전쟁의 사도 | Apostle of War |
| 156421 | 광기의 지배자 | Mad Ruler |
| 156422 | 광기의 수호자 | Mad Guardian |
| 156423 | 광기의 집행자 | Mad Enforcer |
| 156424 | 광기에 물든 야수 | Mad Beast |
| 156426 | 피의 지배자 | Blood Ruler |
| 156427 | 피의 수호자 | Blood Guardian |
| 156428 | 피의 집행자 | Blood Enforcer |
| 156429 | 피에 물든 검귀 | Blood-Soaked Sword Demon |
| 156431 | 원귀의 지배자 | Ghost Ruler |
| 156432 | 원귀의 수호자 | Ghost Guardian |
| 156433 | 원귀의 집행자 | Ghost Enforcer |
| 156434 | 피눈물을 흘리는 원귀 | Ghost Who Weeps Bitter Tears |
| 156436 | 창의 지배자 | Piercing Ruler |
| 156437 | 창의 수호자 | Piercing Guardian |
| 156438 | 창의 집행자 | Piercing Enforcer |
| 156439 | 종말을 찌르는 창 | Doom Piercer |
| 156441 | 흉몽의 지배자 | Ominous Dream Ruler |
| 156442 | 흉몽의 수호자 | Ominous Dream Guardian |
| 156443 | 흉몽의 집행자 | Ominous Dream Enforcer |
| 156444 | 흉몽의 나비 | Butterfly of An Ominous Dream |
| 156602 | 등대지기의 지배자 | Lighthouse Keeper Ruler |
| 156603 | 등대지기의 집행자 | Lighthouse Keeper Enforcer |
| 156604 | 등대지기의 처형자 | Lighthouse Keeper Executioner |
| 156605 | 등대지기 | Lighthouse Keeper |
| 156607 | 베히모스의 지배자 | Behemoth Ruler |
| 156608 | 베히모스의 집행자 | Behemoth Enforcer |
| 156609 | 베히모스의 처형자 | Behemoth Executioner |
| 156610 | 베히모스 | Behemoth |
| 156612 | 케이린의 지배자 | Kayrin Ruler |
| 156613 | 케이린의 집행자 | Kayrin Enforcer |
| 156614 | 케이린의 처형자 | Kayrin Executioner |
| 156615 | 케이린 | Kayrin |
| 156701 | 1주년 기념 화환 | 1st Anniversary Wreath |
| 156705 | 2주년 기념 화환 | 2nd Anniversary Wreath |
| 156706 | 3주년 기념 딱지 | 3rd Anniversary Paper Tile |
| 156801 | 릴리트의 증표 | Lilith's Token |
| 156802 | 웨리의 증표 | Wheri's Token |
| 156803 | 사쿠요(업화)의 증표 | Sakuyo (Infernal Blaze)'s Token |
| 156804 | 메피스토펠레스(여명)의 증표 | Mephistopheles (Dawn)'s Token |
| 156805 | 바이스의 증표 | Weiss's Token |
| 156806 | 로제(홍염)의 증표 | Rose (Prominence)'s Token |
| 156807 | 홍란(무쌍)의 증표 | Honglan (Peerless)'s Token |
| 156808 | 한울의 증표 | Hanul's Token |
| 156809 | 지호(미르)의 증표 | Jiho (Mir)'s Token |
| 156810 | 르네(백은)의 증표 | Renee (Argent)'s Token |
| 156811 | 라우라의 증표 | Laura's Token |
| 156812 | 니아의 증표 | Nia's Token |
| 156813 | 하루(카무이)의 증표 | Haru (Kamuy)'s Token |
| 156814 | 미리암(잔영)의 증표 | Miriam (Afterimage)'s Token |
| 156815 | 페트라(각혼)의 증표 | Petra (Awakened Soul)'s Token |
| 156816 | 카넬리안의 증표 | Carnelian's Token |
| 156817 | 가넷(열락)의 증표 | Garnet (Rapture)'s Token |
| 156818 |  |  |
| 156819 | 셰리(낭만)의 증표 | Cherrie (Romantic)'s Token |
| 156820 | 캐서린(광휘)의 증표 | Catherine (Radiance)'s Token |
| 156821 | 유리아의 증표 | Yuria's Token |
| 156822 | 클라우디아(대천사)의 증표 | Claudia (Archangel)'s Token |
| 156823 | 린지(타나토스)의 증표 | Linzy (Thanatos)'s Token |
| 156824 | 헤이즐의 증표 | Hazel's Token |
| 156825 | 이브의 증표 | Eve's Token |
| 156826 | 시그리드의 증표 | Sigrid's Token |
| 156827 | 라리마의 증표 | Larimar's Token |
| 156828 | 오닉스의 증표 | Onyx's Token |
| 156829 | 도미니크의 증표 | Dominique's Token |
| 156830 | 유리아(아폴리온)의 증표 | Yuria (Apollyon)'s Token |
| 156831 | 아야메(츠쿠요미)의 증표 | Ayame (Tsukuyomi)'s Token |
| 156901 | 썰매왕 슬레이봅 (1위) | Sled King Sleighbob (#1) |
| 156902 | 썰매왕 슬레이봅 (2위) | Sled King Sleighbob (#2) |
| 156903 | 썰매왕 슬레이봅 (3위) | Sled King Sleighbob (#3) |
| 156910 | 메카이아 (1위) | Mecha Gaia (#1) |
| 156911 | 메카이아 (2위) | Mecha Gaia (#2) |
| 156912 | 메카이아 (3위) | Mecha Gaia (#3) |
| 156919 | 떡공장장 순이 (1위) | Rice Cake Factory Chief Soonie (#1) |
| 156920 | 떡공장장 순이 (2위) | Rice Cake Factory Chief Soonie (#2) |
| 156921 | 떡공장장 순이 (3위) | Rice Cake Factory Chief Soonie (#3) |
| 156928 | 기록되지 않은 미래의 정복자 | The Unwritten Future Conqueror |
| 156929 | 기록되지 않은 미래의 개척자 | The Unwritten Future Pioneer |
| 156930 | 기록되지 않은 미래의 발견자 | The Unwritten Future Discoverer |
| 156937 | 천리주단기의 정복자 | Riding Alone for Thousands of Miles Conqueror |
| 156938 | 천리주단기의 개척자 | Riding Alone for Thousands of Miles Pioneer |
| 156939 | 천리주단기의 발견자 | Riding Alone for Thousands of Miles Discoverer |
| 156946 | 사해파정의 정복자 | Calm Waves of Four Seas Conqueror |
| 156947 | 사해파정의 개척자 | Calm Waves of Four Seas Pioneer |
| 156948 | 사해파정의 발견자 | Calm Waves of Four Seas Discoverer |
| 156955 | 극광의 정복자 | Extreme Light Conqueror |
| 156956 | 극광의 개척자 | Extreme Light Pioneer |
| 156957 | 극광의 발견자 | Extreme Light Discoverer |
| 156964 | 폭주한 실베스터 조이 3세(1위) | Rampaging King Sylvester Joey III (#1) |
| 156965 | 폭주한 실베스터 조이 3세(2위) | Rampaging King Sylvester Joey III (#2) |
| 156966 | 폭주한 실베스터 조이 3세(3위) | Rampaging King Sylvester Joey III (#3) |
| 156973 | 아마'게'돈(1위) | CRABmageddon (#1) |
| 156974 | 아마'게'돈(2위) | CRABmageddon (#2) |
| 156975 | 아마'게'돈(3위) | CRABmageddon (#3) |
| 156982 | 환영을 꿰뚫는 탄환의 정복자 | Illusion-Piercing Bullet Conqueror |
| 156983 | 환영을 꿰뚫는 탄환의 개척자 | Illusion-Piercing Bullet Pioneer |
| 156984 | 환영을 꿰뚫는 탄환의 발견자 | Illusion-Piercing Bullet Discoverer |
| 156985 | 아이돌 퀸 캐서린(1위) | Idol Queen Catherine (#1) |
| 156986 | 아이돌 퀸 캐서린(2위) | Idol Queen Catherine (#2) |
| 156987 | 아이돌 퀸 캐서린(3위) | Idol Queen Catherine (#3) |
| 157100 | 열락의 밤으로(1위) | Into the Night of Rapture (#1) |
| 157101 | 열락의 밤으로(2위) | Into the Night of Rapture (#2) |
| 157102 | 열락의 밤으로(3위) | Into the Night of Rapture (#3) |
| 157109 | 낭만항로(1위) | Romantic Voyage (#1) |
| 157110 | 낭만항로(2위) | Romantic Voyage (#2) |
| 157111 | 낭만항로(3위) | Romantic Voyage (#3) |
| 157118 | 소원 도둑 오닉스(1위) | Wish Thief Onyx (#1) |
| 157119 | 소원 도둑 오닉스(2위) | Wish Thief Onyx (#2) |
| 157120 | 소원 도둑 오닉스(3위) | Wish Thief Onyx (#3) |
| 160001 | Shooting Star 프로듀서 | Shooting Star Producer |
| 160002 | 두둥실 프로듀서 | Floating Producer |
| 160003 | Love Note 프로듀서 | Love Note Producer |
| 160004 | Yum 프로듀서 | Yum Producer |
| 160005 | 나만의 별 | My Own Star |
| 160006 | 오늘의 기분 두둥실 | Today's Mood Floating |
| 160007 | 가득 채워줘 | Fill Me Up |
| 160008 | 잊을 수 없는 마음 | Unforgettable Heart |
| 210001 | 골드 | Gold |
| 210002 | 에버스톤 | Everstone |
| 210003 | 마나 더스트 | Mana Dust |
| 210004 | 마나 크리스탈 | Mana Crystal |
| 210005 | 플레이어 경험치 | Player EXP |
| 210006 | 하트 | Heart |
| 210008 | 인공 시냅스 소자 | Artificial Synapse Module |
| 210009 | 아레나 도전권 | Arena Challenge Ticket |
| 210010 | 미궁 코인 | Labyrinth Coin |
| 210011 | 레이드 코인 | Raid Coin |
| 210012 | 기억 조각 | Memory Shard |
| 210013 | 아레나 코인 | Arena Coin |
| 210014 | 유물 코인 | Artifact Coin |
| 210016 | 영지 코인 | Town Coin |
| 210018 | 악령 코인 | Evil Soul Coin |
| 210019 | 픽업 소환권 | Pick-Up Summon Ticket |
| 210020 | 유물석 | Artifact Stone |
| 210021 | 상급 유물석 | Advanced Artifact Stone |
| 210022 | 영광의 유물석 | Artifact Stone of Glory |
| 210023 | 본능의 유물석 | Artifact Stone of Instinct |
| 210024 | 조화의 유물석 | Artifact Stone of Harmony |
| 210025 | 불변의 유물석 | Artifact Stone of Constancy |
| 210026 | 희망의 유물석 | Artifact Stone of Hope |
| 210027 | 절망의 유물석 | Artifact Stone of Despair |
| 210028 | 일반 소환권 | Normal Summon Ticket |
| 210029 | 타입 소환권 | Type Summon Ticket |
| 210030 | 정령의 기억 (레어) | Soul's Memory (Rare) |
| 210031 | 정령의 기억 (에픽) | Soul's Memory (Epic) |
| 210032 | 예장 강화석 | Keepsake Enhance Stone |
| 210033 | 데이트 어 라이브 V 픽업 소환권 | Date A Live V Pick-Up Summon Ticket |
| 210042 | 에버스톤 | Everstone |
| 210044 | 챔피언스 아레나 도전권 | Champs Arena Challenge Ticket |
| 210045 | 유물 소환권 | Artifact Summon Ticket |
| 210046 | 에리카의 연금술 티켓 | Erika's Alchemy Ticket |
| 210047 | 승급 초기화권 | Ascension Reset Ticket |
| 210048 | 중급 예장 강화석 | Intermediate Keepsake Enhance Stone |
| 210049 | 상급 예장 강화석 | Advanced Keepsake Enhance Stone |
| 210050 | 성좌 포인트 | Zodiac Points |
| 210051 | 미궁 입장권 | Labyrinth Ticket |
| 210052 | 예장 초월석 | Keepsake Transcension Stone |
| 210053 | 악령 토벌 입장권 | Evil Soul Subjugation Ticket |
| 210054 | 세트 옵션 각인권 | Set Option Engraving Ticket |
| 210055 | 회랑 입장권 | Hall Ticket |
| 210056 | 작전 허가증 | Operation Permit |
| 210057 | 작전 기념 코인 | Operation Coin |
| 210058 | 타입 게이트 입장권 | Type Gate Ticket |
| 210059 | 기원의 탑 입장권 | Tower of Origin Ticket |
| 210060 | 양동 작전 티켓 | Decoy Operation Ticket |
| 210061 | 양동 작전 도전 모드 티켓 | Decoy Operation Challenge Mode Ticket |
| 210062 | 양동 작전 추가 티켓 | Extra Decoy Operation Ticket |
| 210063 | 양동 작전 도전 모드 추가 티켓 | Extra Decoy Operation Challenge Mode Ticket |
| 210064 | 태초의 유물석 | Artifact Stone of Primordium |
| 210065 | 오색의 결정 | Iridescent Crystal |
| 210066 | 지정 소환권 | Targeted Summon Ticket |
| 210067 | 쿠폰 | Coupon |
| 210100 | 에버스톤 | Everstone |
| 210101 | 빛바랜 시계 | Faded Watch |
| 210102 | 빛바랜 오르골 | Faded Orgel |
| 210103 | 빛바랜 거울 | Faded Mirror |
| 210104 | 빛바랜 열쇠 | Faded Key |
| 210201 | 추억이 담긴 시계 | Clock of Memories |
| 210202 | 추억이 담긴 오르골 | Orgel of Memories |
| 210203 | 추억이 담긴 거울 | Mirror of Memories |
| 210204 | 추억이 담긴 열쇠 | Key of Memories |
| 210301 | 비밀을 간직한 시계 | Clock of Secrets |
| 210302 | 비밀을 간직한 오르골 | Orgel of Secrets |
| 210303 | 비밀을 간직한 거울 | Mirror of Secrets |
| 210304 | 비밀을 간직한 열쇠 | Key of Secrets |
| 210401 | 마나가 깃든 탁상시계 | Mana-Imbued Table Clock |
| 210402 | 마나가 깃든 뮤직박스 | Mana-Imbued Music Box |
| 210403 | 마나가 깃든 탁상거울 | Mana-Imbued Table Mirror |
| 210404 | 마나가 깃든 금고열쇠 | Mana-Imbued Safe Key |
| 210405 | 마나가 깃든 회중시계 | Mana-Imbued Pocket Watch |
| 210406 | 마나가 깃든 오르골 | Mana-Imbued Orgel |
| 210407 | 마나가 깃든 접이거울 | Mana-Imbued Folding Mirror |
| 210408 | 마나가 깃든 만능열쇠 | Mana-Imbued Master Key |
| 210409 | 마나가 깃든 모래시계 | Mana-Imbued Hourglass |
| 210410 | 마나가 깃든 스노우볼 | Mana-Imbued Snow Globe |
| 210411 | 마나가 깃든 손거울 | Mana-Imbued Hand Mirror |
| 210412 | 마나가 깃든 마법열쇠 | Mana-Imbued Magic Key |
| 210501 | 마력이 넘치는 탁상시계 | Magic-Overflowing Table Clock |
| 210502 | 마력이 넘치는 뮤직박스 | Magic-Overflowing Music Box |
| 210503 | 마력이 넘치는 탁상거울 | Magic-Overflowing Table Mirror |
| 210504 | 마력이 넘치는 금고열쇠 | Magic-Overflowing Safe Key |
| 210505 | 마력이 넘치는 회중시계 | Magic-Overflowing Pocket Watch |
| 210506 | 마력이 넘치는 오르골 | Magic-Overflowing Orgel |
| 210507 | 마력이 넘치는 접이거울 | Magic-Overflowing Folding Mirror |
| 210508 | 마력이 넘치는 만능열쇠 | Magic-Overflowing Master Key |
| 210509 | 마력이 넘치는 모래시계 | Magic-Overflowing Hourglass |
| 210510 | 마력이 넘치는 스노우볼 | Magic-Overflowing Snow Globe |
| 210511 | 마력이 넘치는 손거울 | Magic-Overflowing Hand Mirror |
| 210512 | 마력이 넘치는 마법열쇠 | Magic-Overflowing Magic Key |
| 210601 | 정교하게 각인된 탁상시계 | Exquisitely Engraved Table Clock |
| 210602 | 정교하게 각인된 뮤직박스 | Exquisitely Engraved Music Box |
| 210603 | 정교하게 각인된 탁상거울 | Exquisitely Engraved Table Mirror |
| 210604 | 정교하게 각인된 금고열쇠 | Exquisitely Engraved Safe Key |
| 210629 | 정교하게 각인된 회중시계 | Exquisitely Engraved Pocket Watch |
| 210630 | 정교하게 각인된 오르골 | Exquisitely Engraved Orgel |
| 210631 | 정교하게 각인된 접이거울 | Exquisitely Engraved Folding Mirror |
| 210632 | 정교하게 각인된 만능열쇠 | Exquisitely Engraved Master Key |
| 210657 | 정교하게 각인된 모래시계 | Exquisitely Engraved Hourglass |
| 210658 | 정교하게 각인된 스노우볼 | Exquisitely Engraved Snow Globe |
| 210659 | 정교하게 각인된 손거울 | Exquisitely Engraved Hand Mirror |
| 210660 | 정교하게 각인된 마법열쇠 | Exquisitely Engraved Magic Key |
| 210701 | 화려하게 세공된 탁상시계 | Lavishly Crafted Table Clock |
| 210702 | 화려하게 세공된 뮤직박스 | Lavishly Crafted Music Box |
| 210703 | 화려하게 세공된 탁상거울 | Lavishly Crafted Table Mirror |
| 210704 | 화려하게 세공된 금고열쇠 | Lavishly Crafted Safe Key |
| 210729 | 화려하게 세공된 회중시계 | Lavishly Crafted Pocket Watch |
| 210730 | 화려하게 세공된 오르골 | Lavishly Crafted Orgel |
| 210731 | 화려하게 세공된 접이거울 | Lavishly Crafted Folding Mirror |
| 210732 | 화려하게 세공된 만능열쇠 | Lavishly Crafted Master Key |
| 210757 | 화려하게 세공된 모래시계 | Lavishly Crafted Hourglass |
| 210758 | 화려하게 세공된 스노우볼 | Lavishly Crafted Snow Globe |
| 210759 | 화려하게 세공된 손거울 | Lavishly Crafted Hand Mirror |
| 210760 | 화려하게 세공된 마법열쇠 | Lavishly Crafted Magic Key |
| 210801 | 찬란한 꽃잎의 탁상시계 | Table Clock of Dazzling Petals |
| 210802 | 찬란한 꽃잎의 뮤직박스 | Music Box of Dazzling Petals |
| 210803 | 찬란한 꽃잎의 탁상거울 | Table Mirror of Dazzling Petals |
| 210804 | 찬란한 꽃잎의 금고열쇠 | Safe Key of Dazzling Petals |
| 210829 | 찬란한 꽃잎의 회중시계 | Pocket Watch of Dazzling Petals |
| 210830 | 찬란한 꽃잎의 오르골 | Orgel of Dazzling Petals |
| 210831 | 찬란한 꽃잎의 접이거울 | Folding Mirror of Dazzling Petals |
| 210832 | 찬란한 꽃잎의 만능열쇠 | Master Key of Dazzling Petals |
| 210857 | 찬란한 꽃잎의 모래시계 | Hourglass of Dazzling Petals |
| 210858 | 찬란한 꽃잎의 스노우볼 | Snow Globe of Dazzling Petals |
| 210859 | 찬란한 꽃잎의 손거울 | Hand Mirror of Dazzling Petals |
| 210860 | 찬란한 꽃잎의 마법열쇠 | Magic Key of Dazzling Petals |
| 210901 | 달콤한 입맞춤의 탁상시계 | Table Clock of Sweet Kisses |
| 210902 | 달콤한 입맞춤의 뮤직박스 | Music Box of Sweet Kisses |
| 210903 | 달콤한 입맞춤의 탁상거울 | Table Mirror of Sweet Kisses |
| 210904 | 달콤한 입맞춤의 금고열쇠 | Safe Key of Sweet Kisses |
| 210929 | 달콤한 입맞춤의 회중시계 | Pocket Watch of Sweet Kisses |
| 210930 | 달콤한 입맞춤의 오르골 | Orgel of Sweet Kisses |
| 210931 | 달콤한 입맞춤의 접이거울 | Folding Mirror of Sweet Kisses |
| 210932 | 달콤한 입맞춤의 만능열쇠 | Master Key of Sweet Kisses |
| 210957 | 달콤한 입맞춤의 모래시계 | Hourglass of Sweet Kisses |
| 210958 | 달콤한 입맞춤의 스노우볼 | Snow Globe of Sweet Kisses |
| 210959 | 달콤한 입맞춤의 손거울 | Hand Mirror of Sweet Kisses |
| 210960 | 달콤한 입맞춤의 마법열쇠 | Magic Key of Sweet Kisses |
| 211001 | 영원한 약속의 탁상시계 | Table Clock of Eternal Promise |
| 211002 | 영원한 약속의 뮤직박스 | Music Box of Eternal Promise |
| 211003 | 영원한 약속의 탁상거울 | Table Mirror of Eternal Promise |
| 211004 | 영원한 약속의 금고열쇠 | Safe Key of Eternal Promise |
| 211029 | 영원한 약속의 회중시계 | Pocket Watch of Eternal Promise |
| 211030 | 영원한 약속의 오르골 | Orgel of Eternal Promise |
| 211031 | 영원한 약속의 접이거울 | Folding Mirror of Eternal Promise |
| 211032 | 영원한 약속의 만능열쇠 | Master Key of Eternal Promise |
| 211057 | 영원한 약속의 모래시계 | Hourglass of Eternal Promise |
| 211058 | 영원한 약속의 스노우볼 | Snow Globe of Eternal Promise |
| 211059 | 영원한 약속의 손거울 | Hand Mirror of Eternal Promise |
| 211060 | 영원한 약속의 마법열쇠 | Magic Key of Eternal Promise |
| 211101 | 소원을 품은 탁상시계 | Table Clock of Wishes |
| 211102 | 소원을 품은 뮤직박스 | Music Box of Wishes |
| 211103 | 소원을 품은 탁상거울 | Table Mirror of Wishes |
| 211104 | 소원을 품은 금고열쇠 | Safe Key of Wishes |
| 211129 | 소원을 품은 회중시계 | Pocket Watch of Wishes |
| 211130 | 소원을 품은 오르골 | Orgel of Wishes |
| 211131 | 소원을 품은 접이거울 | Folding Mirror of Wishes |
| 211132 | 소원을 품은 만능열쇠 | Master Key of Wishes |
| 211157 | 소원을 품은 모래시계 | Hourglass of Wishes |
| 211158 | 소원을 품은 스노우볼 | Snow Globe of Wishes |
| 211159 | 소원을 품은 손거울 | Hand Mirror of Wishes |
| 211160 | 소원을 품은 마법열쇠 | Magic Key of Wishes |
| 211201 | 춤추는 별들의 탁상시계 | Table Clock of Dancing Stars |
| 211202 | 춤추는 별들의 뮤직박스 | Music Box of Dancing Stars |
| 211203 | 춤추는 별들의 탁상거울 | Table Mirror of Dancing Stars |
| 211204 | 춤추는 별들의 금고열쇠 | Safe Key of Dancing Stars |
| 211229 | 춤추는 별들의 회중시계 | Pocket Watch of Dancing Stars |
| 211230 | 춤추는 별들의 오르골 | Music Box of Dancing Stars |
| 211231 | 춤추는 별들의 접이거울 | Folding Mirror of Dancing Stars |
| 211232 | 춤추는 별들의 만능열쇠 | Master Key of Dancing Stars |
| 211257 | 춤추는 별들의 모래시계 | Hourglass of Dancing Stars |
| 211258 | 춤추는 별들의 스노우볼 | Snow Globe of Dancing Stars |
| 211259 | 춤추는 별들의 손거울 | Hand Mirror of Dancing Stars |
| 211260 | 춤추는 별들의 마법열쇠 | Magic Key of Dancing Stars |
| 211301 | 월광을 머금은 탁상시계 | Moonlit Table Clock |
| 211302 | 월광을 머금은 뮤직박스 | Moonlit Music Box |
| 211303 | 월광을 머금은 탁상거울 | Moonlit Table Mirror |
| 211304 | 월광을 머금은 금고열쇠 | Moonlit Safe Key |
| 211329 | 월광을 머금은 회중시계 | Moonlit Pocket Watch |
| 211330 | 월광을 머금은 오르골 | Moonlit Music Box |
| 211331 | 월광을 머금은 접이거울 | Moonlit Folding Mirror |
| 211332 | 월광을 머금은 만능열쇠 | Moonlit Master Key |
| 211357 | 월광을 머금은 모래시계 | Moonlit Hourglass |
| 211358 | 월광을 머금은 스노우볼 | Moonlit Snow Globe |
| 211359 | 월광을 머금은 손거울 | Moonlit Hand Mirror |
| 211360 | 월광을 머금은 마법열쇠 | Moonlit Magic Key |
| 211401 | 천일의 빛을 담은 탁상시계 | Table Clock of a Thousand Days of Light |
| 211402 | 천일의 빛을 담은 뮤직박스 | Music Box of a Thousand Days of Light |
| 211403 | 천일의 빛을 담은 탁상거울 | Table Mirror of a Thousand Days of Light |
| 211404 | 천일의 빛을 담은 금고열쇠 | Safe Key of a Thousand Days of Light |
| 211429 | 천일의 빛을 담은 회중시계 | Pocket Watch of a Thousand Days of Light |
| 211430 | 천일의 빛을 담은 오르골 | Music Box of a Thousand Days of Light |
| 211431 | 천일의 빛을 담은 접이거울 | Folding Mirror of a Thousand Days of Light |
| 211432 | 천일의 빛을 담은 만능열쇠 | Master Key of a Thousand Days of Light |
| 211457 | 천일의 빛을 담은 모래시계 | Hourglass of a Thousand Days of Light |
| 211458 | 천일의 빛을 담은 스노우볼 | Snow Globe of a Thousand Days of Light |
| 211459 | 천일의 빛을 담은 손거울 | Hand Mirror of a Thousand Days of Light |
| 211460 | 천일의 빛을 담은 마법열쇠 | Magic Key of a Thousand Days of Light |
| 211501 | 무한한 우주의 탁상시계 | Table Clock of Infinite Universe |
| 211502 | 무한한 우주의 뮤직박스 | Music Box of Infinite Universe |
| 211503 | 무한한 우주의 탁상거울 | Table Mirror of Infinite Universe |
| 211504 | 무한한 우주의 금고열쇠 | Safe Key of Infinite Universe |
| 211529 | 무한한 우주의 회중시계 | Pocket Watch of Infinite Universe |
| 211530 | 무한한 우주의 오르골 | Music Box of Infinite Universe |
| 211531 | 무한한 우주의 접이거울 | Folding Mirror of Infinite Universe |
| 211532 | 무한한 우주의 만능열쇠 | Master Key of Infinite Universe |
| 211557 | 무한한 우주의 모래시계 | Hourglass of Infinite Universe |
| 211558 | 무한한 우주의 스노우볼 | Snow Globe of Infinite Universe |
| 211559 | 무한한 우주의 손거울 | Hand Mirror of Infinite Universe |
| 211560 | 무한한 우주의 마법열쇠 | Magic Key of Infinite Universe |
| 211901 | 1주년 약속의 회중시계 | 1st Anniversary Pocket Watch of Promise |
| 211902 | 1주년 약속의 오르골 | 1st Anniversary Music Box of Promise |
| 211903 | 1주년 약속의 접이거울 | 1st Anniversary Folding Mirror of Promise |
| 211904 | 1주년 약속의 만능열쇠 | 1st Anniversary Master Key of Promise |
| 211905 | 흑기사의 투구 | Dark Knight's Helmet |
| 211906 | 1.5주년 약속의 모래시계 | 1.5-Year Anniversary Hourglass of Promise |
| 211907 | 1.5주년 약속의 스노우볼 | 1.5-Year Anniversary Snow Globe of Promise |
| 211908 | 1.5주년 약속의 손거울 | 1.5-Year Anniversary Hand Mirror of Promise |
| 211909 | 1.5주년 약속의 마법열쇠 | 1.5-Year Anniversary Magic Key of Promise |
| 211910 | 2주년 약속의 드레스 | 2-Year Anniversary Dress of Promise |
| 211911 | 2주년 약속의 날개 | 2-Year Anniversary Wings of Promise |
| 211912 | 2주년 약속의 장갑 | 2-Year Anniversary Gloves of Promise |
| 211913 | 2주년 약속의 헤드셋 | 2-Year Anniversary Headset of Promise |
| 211914 | 2.5주년 약속의 팬던트 | 2.5-Year Anniversary Pendant of Promise |
| 211915 | 2.5주년 약속의 팔찌 | 2.5-Year Anniversary Bracelet of Promise |
| 211916 | 2.5주년 약속의 구두 | 2.5-Year Anniversary Shoes of Promise |
| 211917 | 2.5주년 약속의 스파클링 | 2.5-Year Anniversary Sparkling Wine of Promise |
| 211918 | 1000번째 약속의 브로치 | Brooch of the 1,000th Promise |
| 211919 | 1000번째 약속의 오너먼트 | Ornament of the 1,000th Promise |
| 211920 | 1000번째 약속의 헤어리본 | Hair Bow of the 1,000th Promise |
| 211921 | 1000번째 약속의 가터링 | Garter Ring of the 1,000th Promise |
| 211922 | 3주년 약속의 동백 | 3-Year Anniversary Camellia of Promise |
| 211923 | 3주년 약속의 노리개 | 3-Year Anniversary Charm of Promise |
| 211924 | 3주년 약속의 비녀 | 3-Year Anniversary Hairpin of Promise |
| 211925 | 3주년 약속의 종이부채 | 3-Year Anniversary Paper Fan of Promise |
| 213001 | 방치 골드 (2시간) | Idle Gold (2 Hours) |
| 213002 | 방치 골드 (6시간) | Idle Gold (6 Hours) |
| 213003 | 방치 골드 (12시간) | Idle Gold (12 Hours) |
| 213004 | 방치 골드 (24시간) | Idle Gold (24 Hours) |
| 213005 | 방치 골드 (48시간) | Idle Gold (48 Hours) |
| 213006 | 방치 마나 더스트 (2시간) | Idle Mana Dust (2 Hours) |
| 213007 | 방치 마나 더스트 (6시간) | Idle Mana Dust (6 Hours) |
| 213008 | 방치 마나 더스트 (12시간) | Idle Mana Dust (12 Hours) |
| 213009 | 방치 마나 더스트 (24시간) | Idle Mana Dust (24 Hours) |
| 213010 | 방치 마나 더스트 (48시간) | Idle Mana Dust (48 Hours) |
| 213011 | 방치 마나 크리스탈 (2시간) | Idle Mana Crystal (2 Hours) |
| 213012 | 방치 마나 크리스탈 (6시간) | Idle Mana Crystal (6 Hours) |
| 213013 | 방치 마나 크리스탈 (12시간) | Idle Mana Crystal (12 Hours) |
| 213014 | 방치 마나 크리스탈 (24시간) | Idle Mana Crystal (24 Hours) |
| 213015 | 방치 마나 크리스탈 (48시간) | Idle Mana Crystal (48 Hours) |
| 213021 | 재화 꾸러미 (2시간) | Resource Bundle (2 Hours) |
| 213022 | 재화 꾸러미 (6시간) | Resource Bundle (6 Hours) |
| 213023 | 재화 꾸러미 (12시간) | Resource Bundle (12 Hours) |
| 213024 | 재화 꾸러미 (24시간) | Resource Bundle (24 Hours) |
| 213101 | 정령의 기억: 아이린 | Soul's Memory: Irene |
| 213102 | 정령의 기억: 캐니 | Soul's Memory: Canney |
| 213103 | 정령의 기억: 픽시 | Soul's Memory: Pixie |
| 213104 | 정령의 기억: 캐스퍼 | Soul's Memory: Casper |
| 213201 | 정령의 기억: 리타 | Soul's Memory: Rita |
| 213202 | 정령의 기억: 로제 | Soul's Memory: Rose |
| 213203 | 정령의 기억: 샤링 | Soul's Memory: Sharinne |
| 213204 | 정령의 기억: 루리 | Soul's Memory: Ruri |
| 213205 | 정령의 기억: 알리샤 | Soul's Memory: Alisha |
| 213206 | 정령의 기억: 르웨인 | Soul's Memory: Lewayne |
| 213207 | 정령의 기억: 무명 | Soul's Memory: Nameless |
| 213208 | 정령의 기억: 카렌 | Soul's Memory: Karen |
| 213301 | 정령의 기억: 메피스토펠레스 | Soul's Memory: Mephistopheles |
| 213302 | 정령의 기억: 벨레드 | Soul's Memory: Beleth |
| 213303 | 정령의 기억: 클레르 | Soul's Memory: Claire |
| 213304 | 정령의 기억: 아키 | Soul's Memory: Aki |
| 213305 | 정령의 기억: 제이드 | Soul's Memory: Jade |
| 213306 | 정령의 기억: 린지 | Soul's Memory: Linzy |
| 213307 | 정령의 기억: 홍란 | Soul's Memory: Honglan |
| 213308 | 정령의 기억: 순이 | Soul's Memory: Soonie |
| 213309 | 정령의 기억: 아이라 | Soul's Memory: Aira |
| 213310 | 정령의 기억: 시하 | Soul's Memory: Seeha |
| 213311 | 정령의 기억: 미카 | Soul's Memory: Mica |
| 213312 | 정령의 기억: 에리카 | Soul's Memory: Erika |
| 213313 | 정령의 기억: 이나 | Soul's Memory: Ina |
| 213314 | 정령의 기억: 르네 | Soul's Memory: Renee |
| 213315 | 정령의 기억: 탈리아 | Soul's Memory: Talia |
| 213316 | 정령의 기억: 칸나 | Soul's Memory: Kanna |
| 213317 | 정령의 기억: 이디스 | Soul's Memory: Edith |
| 213318 | 정령의 기억: 비올레트 | Soul's Memory: Violette |
| 213319 | 정령의 기억: 가넷 | Soul's Memory: Garnet |
| 213320 | 정령의 기억: 레베카 | Soul's Memory: Rebecca |
| 213321 | 정령의 기억: 멜피스 | Soul's Memory: Melfice |
| 213322 | 정령의 기억: 브라이스 | Soul's Memory: Bryce |
| 213323 | 정령의 기억: 프림 | Soul's Memory: Prim |
| 213324 | 정령의 기억: 클라우디아 | Soul's Memory: Claudia |
| 213325 | 정령의 기억: 헬레나 | Soul's Memory: Helena |
| 213326 | 정령의 기억: 벨라나 | Soul's Memory: Velanna |
| 213327 | 정령의 기억: 아야메 | Soul's Memory: Ayame |
| 213328 | 정령의 기억: 재클린 | Soul's Memory: Jacqueline |
| 213329 | 정령의 기억: 나오미 | Soul's Memory: Naomi |
| 213330 | 정령의 기억: 조앤 | Soul's Memory: Joanne |
| 213331 | 정령의 기억: 메릴 | Soul's Memory: Meryl |
| 213332 | 정령의 기억: 플린 | Soul's Memory: Flynn |
| 213333 | 정령의 기억: 타샤 | Soul's Memory: Tasha |
| 213334 | 정령의 기억: 니콜 | Soul's Memory: Nicole |
| 213335 | 정령의 기억: 비비안 | Soul's Memory: Vivienne |
| 213336 | 정령의 기억: 아드리안 | Soul's Memory: Adrianne |
| 213337 | 정령의 기억: 사논 | Soul's Memory: Sanon |
| 213338 | 정령의 기억: 리젤로테 | Soul's Memory: Lizelotte |
| 213339 | 정령의 기억: 캐서린 | Soul's Memory: Catherine |
| 213340 | 정령의 기억: 셰리 | Soul's Memory: Cherrie |
| 213341 | 정령의 기억: 도라 | Soul's Memory: Dora |
| 213342 | 정령의 기억: 하루 | Soul's Memory: Haru |
| 213343 | 정령의 기억: 루테 | Soul's Memory: Lute |
| 213344 | 정령의 기억: 클라라 | Soul's Memory: Clara |
| 213345 | 정령의 기억: 미리암 | Soul's Memory: Miriam |
| 213346 | 정령의 기억: 클로이 | Soul's Memory: Chloe |
| 213347 | 정령의 기억: 나이아 | Soul's Memory: Naiah |
| 213348 | 정령의 기억: 에루샤 | Soul's Memory: Erusha |
| 213349 | 정령의 기억: 페트라 | Soul's Memory: Petra |
| 213350 | 정령의 기억: 니니 | Soul's Memory: Nini |
| 213351 | 정령의 기억: 지호 | Soul's Memory: Jiho |
| 213352 | 정령의 기억: 헤이즐 | Soul's Memory: Hazel |
| 213353 | 정령의 기억: 소연 | Soul's Memory: Xiaolian |
| 213354 | 정령의 기억: 마농 | Soul's Memory: Manon |
| 213355 | 정령의 기억: 다프네 | Soul's Memory: Daphne |
| 213356 | 정령의 기억: 유리아 | Soul's Memory: Yuria |
| 213358 | 정령의 기억: 에일린 | Soul's Memory: Eileen |
| 213359 | 정령의 기억: 오토하 | Soul's Memory: Otoha |
| 213360 | 정령의 기억: 이브 | Soul's Memory: Eve |
| 213361 | 정령의 기억: 사쿠요 | Soul's Memory: Sakuyo |
| 213362 | 정령의 기억: 캐서린(광휘) | Soul's Memory: Catherine (Radiance) |
| 213363 | 정령의 기억: 도미니크 | Soul's Memory: Dominique |
| 213364 | 정령의 기억: 토키사키 쿠루미 | Soul's Memory: Kurumi Tokisaki |
| 213365 | 정령의 기억: 야토가미 토카 | Soul's Memory: Tohka Yatogami |
| 213366 | 정령의 기억: 라리마 | Soul's Memory: Larimar |
| 213367 | 봉인된 이차원의 정수 | Sealed Essence of Another Dimension |
| 213368 | 정령의 기억: 시그리드 | Soul's Memory: Sigrid |
| 213369 | 정령의 기억: 오닉스 | Soul's Memory: Onyx |
| 213370 | 정령의 기억: 린지(타나토스) | Soul's Memory: Linzy (Thanatos) |
| 213371 | 정령의 기억: 릴리트 | Soul's Memory: Lilith |
| 213372 | 정령의 기억: 웨리 | Soul's Memory: Wheri |
| 213373 | 정령의 기억: 사쿠요(업화) | Soul's Memory: Sakuyo (Inferno) |
| 213374 | 정령의 기억: 메피스토펠레스(여명) | Soul's Memory: Mephistopheles (Dawn) |
| 213375 | 정령의 기억: 바이스 | Soul's Memory: Weiss |
| 213376 | 정령의 기억: 로제(홍염) | Soul's Memory: Rose (Prominence) |
| 213377 | 정령의 기억: 지호(미르) | Soul's Memory: Jiho (Mir) |
| 213378 | 정령의 기억: 홍란(무쌍) | Soul's Memory: Honglan (Peerless) |
| 213379 | 정령의 기억: 하루(카무이) | Soul's Memory: Haru (Kamuy) |
| 213380 | 정령의 기억: 르네(백은) | Soul's Memory: Renee (Argent) |
| 213381 | 정령의 기억: 미리암(잔영) | Soul's Memory: Miriam (Afterimage) |
| 213382 | 정령의 기억: 라우라 | Soul's Memory: Laura |
| 213383 | 정령의 기억: 페트라(각혼) | Soul's Memory: Petra (Awakened Soul) |
| 213384 | 정령의 기억: 가넷(열락) | Soul's Memory: Garnet (Rapture) |
| 213385 | 정령의 기억: 한울 | Soul's Memory: Hanul |
| 213386 | 정령의 기억: 카넬리안 | Soul's Memory: Carnelian |
| 213387 | 정령의 기억: 니아 | Soul's Memory: Nia |
| 213388 | 정령의 기억: 셰리(낭만) | Soul's Memory: Cherrie (Romantic) |
| 213389 | 정령의 기억: 클라우디아(대천사) | Soul's Memory: Claudia (Archangel) |
| 213390 | 정령의 기억: 유리아 (아폴리온) | Soul's Memory: Yuria (Apollyon) |
| 213391 | 정령의 기억: 아야메 (츠쿠요미) | Soul's Memory: Ayame (Tsukuyomi) |
| 213501 | 정령의 기억: 리타 (레전더리+) | Soul's Memory: Rita (Legendary+) |
| 213502 | 정령의 기억: 로제 (레전더리+) | Soul's Memory: Rose (Legendary+) |
| 213503 | 정령의 기억: 샤링 (레전더리+) | Soul's Memory: Sharinne (Legendary+) |
| 213504 | 정령의 기억: 루리 (레전더리+) | Soul's Memory: Ruri (Legendary+) |
| 213505 | 정령의 기억: 알리샤 (레전더리+) | Soul's Memory: Alisha (Legendary+) |
| 213506 | 정령의 기억: 르웨인 (레전더리+) | Soul's Memory: Lewayne (Legendary+) |
| 213507 | 정령의 기억: 무명 (레전더리+) | Soul's Memory: Nameless (Legendary+) |
| 213508 | 정령의 기억: 카렌 (레전더리+) | Soul's Memory: Karen (Legendary+) |
| 213509 | 정령의 기억: 로제 (에픽+) | Soul's Memory: Rose (Epic+) |
| 213510 | 정령의 기억: 메피스토펠레스 (오리진) | Soul's Memory: Mephistopheles (Origin) |
| 213511 | 정령의 기억: 도미니크 (레전더리+) | Soul's Memory: Dominique (Legendary+) |
| 213512 | 정령의 기억: 시그리드(레전더리+) | Soul's Memory: Sigrid (Legendary+) |
| 213513 | 정령의 기억: 벨레드 (레전더리+) | Soul's Memory: Beleth (Legendary+) |
| 214001 | 추석 복주머니 | Chuseok Lucky Pouch |
| 214002 | 예장 선택 상자 (에픽) | Keepsake Selection Chest (Epic) |
| 214003 | 고급 유물석 상자 | Expert Artifact Stone Chest |
| 214004 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 214005 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 214006 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 214007 | 승리자의 전리품 | Winner's Trophy |
| 214008 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 214009 | 특정 에픽 정령 선택 상자 | Specific Epic Soul Selection Chest |
| 214010 | 에픽 정령 소환권 선택 상자 | Epic Soul Summon Ticket Selection Chest |
| 214011 | 레어 정령 소환권 선택 상자 | Rare Soul Summon Ticket Selection Chest |
| 214012 | 에픽 정령 선택형 상자 (공격형) | Epic Soul Selection Chest (Attack) |
| 214013 | 에픽 정령 선택형 상자 (방어형) | Epic Soul Selection Chest (Defense) |
| 214014 | 에픽 정령 선택형 상자 (지원형) | Epic Soul Selection Chest (Support) |
| 214015 | 에픽 정령 선택형 상자 D | Epic Soul Selection Chest D |
| 214016 | 에픽 정령 선택 상자 | Epic Soul Selection Chest |
| 214017 | 에덴 갓 탤런트 정령 상자 | Eden's Got Talent Soul Chest |
| 214018 | 에픽 정령 선택형 상자 (1주년) | Epic Soul Selection Chest (1st Anniversary) |
| 214019 | 설날 복주머니 | New Year's Lucky Pouch |
| 214020 | 에픽 정령 선택 상자 (런칭) | Epic Soul Selection Chest (Launch) |
| 214101 | 예장함 (일반) | Keepsake Chest (Common) |
| 214102 | 예장함 (레어) | Keepsake Chest (Rare) |
| 214103 | 예장함 (레어+) | Keepsake Chest (Rare+) |
| 214104 | 예장함 (에픽) | Keepsake Chest (Epic) |
| 214105 | 예장함 (에픽+) | Keepsake Chest (Epic+) |
| 214106 | 예장함 (레전더리) | Keepsake Chest (Legendary) |
| 214107 | 예장함 (레전더리+) | Keepsake Chest (Legendary+) |
| 214108 | 예장함 (이터널) | Keepsake Chest (Eternal) |
| 214109 | 예장함 (이터널+) | Keepsake Chest (Eternal+) |
| 214110 | 예장함 (오리진) | Keepsake Chest (Origin) |
| 214111 | 미확인 유물의 기억 | Unidentified Artifact Memory |
| 214112 | 두근두근☆ 선물 뽑기 캡슐 | Pit-a-Pat☆ Gift Capsule |
| 214115 | 애정 가득♡ 기념일 선물 상자 | Love Filled♡ Anniversary Gift Chest |
| 214116 | 미확인 유물의 기억 상자 | Unidentified Artifact Memory Box |
| 214117 | 재화 선택 상자 (12시간) | Currency Selection Chest (12 Hours) |
| 214118 | 재화 선택 상자 (24시간) | Currency Selection Chest (24 Hours) |
| 214119 | 예장 선택 상자 (에픽+) | Keepsake Selection Chest (Epic+) |
| 214120 | 사진기: 미카와 시하의 하루 | Camera: Mica and Seeha's Day |
| 214121 | 힘 예장 선택 상자 (이터널) | STR Keepsake Selection Chest (Eternal) |
| 214122 | 민첩 예장 선택 상자 (이터널) | DEX Keepsake Selection Chest (Eternal) |
| 214123 | 숲지기의 선물 상자 | Forest Keeper's Gift Box |
| 214124 | 세트 예장함 (이터널) | Set Keepsake Chest (Eternal) |
| 214125 | 세트 예장함 (이터널+) | Set Keepsake Chest (Eternal+) |
| 214126 | 종합 유물석 상자 | Artifact Stone Set Chest |
| 214127 | 금형 선택 상자 (오리진) | Mold Selection Chest (Origin) |
| 214128 | 금형 상자 (오리진) | Mold Chest (Origin) |
| 214129 | 재화 선택 상자 (2시간) | Currency Selection Chest (2 Hours) |
| 214130 | 재화 선택 상자 (6시간) | Currency Selection Chest (6 Hours) |
| 214131 | 세트 예장 선택 상자 (이터널+) | Set Keepsake Selection Chest (Eternal+) |
| 214132 | 프리미엄 선물 뽑기 캡슐 | Premium Gift Capsule |
| 214133 | 특별 픽업 정령 선택 상자 | Special Pick-Up Soul Selection Chest |
| 214134 | 스페셜 에픽 정령 선택 상자(ver.1) | Special Epic Soul Selection Chest (Ver. 1) |
| 214135 | 클래스 강화 회로 선택 상자 | Class Enhance Circuit Selection Chest |
| 214136 | 클래스 강화 회로 랜덤 상자 | Class Enhance Circuit Random Chest |
| 214137 | 세트 예장 선택 상자 (이터널) | Set Keepsake Selection Chest (Eternal) |
| 214138 | 금형 선택 상자 (오리진+1) | Mold Selection Chest (Origin+1) |
| 214139 | 금형 상자 (오리진+1) | Mold Chest (Origin+1) |
| 214140 | 유물의 기억 선택 상자 | Artifact Memory Selection Chest |
| 214141 | 정령 타입 선택 상자 (레전더리+) | Soul Type Selection Chest (Legendary+) |
| 214142 | 세트 예장 선택 상자 (레전더리+) | Set Keepsake Selection Chest (Legendary+) |
| 214143 | 특별 픽업 정령 선택 상자 (Season 2) | Special Pick-Up Soul Selection Chest (Season 2) |
| 214144 | 스페셜 에픽 정령 선택 상자 (1.5주년) | Special Epic Soul Selection Chest (1.5-Year) |
| 214145 | 세트 예장 선택 상자 (오리진) | Set Keepsake Selection Chest (Origin) |
| 214146 | 에픽 정령 선택 상자 (1.5주년) | Epic Soul Selection Chest (1.5-Year) |
| 214147 | 메피스토펠레스 (오리진) 지원 상자 | Mephistopheles (Origin) Support Chest |
| 214148 | 유물의 기억 선택 상자 (1.5주년) | Artifact Memory Selection Chest (1.5-Year) |
| 214149 | 에픽 정령 선택 상자 (2023) | Epic Soul Selection Chest (2023) |
| 214150 | 에픽 정령 선택 상자 (추석 기념) | Epic Soul Selection Chest (Chuseok Celebration) |
| 214151 | 사진기: 에덴 갓 탤런트 | Camera: Eden's Got Talent |
| 214152 | 유물의 기억 선택 상자 (Half-Anniv) | Artifact Memory Selection Chest (Half-Anniv) |
| 214153 | 스페셜 에픽 정령 선택 상자 (런칭) | Special Epic Soul Selection Chest (Launch) |
| 214154 | 에픽 정령 선택 상자 (런칭) | Epic Soul Selection Chest (Launch) |
| 214155 | 에픽 정령 선택 상자 (2주년) | Epic Soul Selection Chest (2-Year) |
| 214156 | 스페셜 에픽 정령 선택 상자 (2주년) | Special Epic Soul Selection Chest (2-Year) |
| 214157 | 예장 성장 선택 상자 | Keepsake Upgrade Selection Chest |
| 214158 | 고급 예장 성장 선택 상자 | Fine Keepsake Upgrade Selection Chest |
| 214159 | 최고급 예장 성장 선택 상자 | Exquisite Keepsake Upgrade Selection Chest |
| 214160 | 유물의 기억 선택 상자 (2주년) | Artifact Memory Selection Chest (2-Year) |
| 214161 | 이브의 날 기념 치킨 박스 | Eve's Day Chicken Box |
| 214162 | 에픽 정령 선택 상자 (신년) | Epic Soul Selection Chest (New Year) |
| 214163 | 스페셜 에픽 정령 선택 상자 (신년) | Special Epic Soul Selection Chest (New Year) |
| 214164 | 유물의 기억 선택 상자 (신년) | Artifact Memory Selection Chest (New Year) |
| 214165 | 사진기: 거미님 일러스트 | Camera: 거미's Illustration |
| 214166 | 사진기: 주상절리님 일러스트 | Camera: 주상절리's Illustration |
| 214167 | 사진기: yuugen님 일러스트 | Camera: yuugen's Illustration |
| 214168 | 사진기: 귄터님 일러스트 | Camera: 귄터's Illustration |
| 214169 | 사진기: 고꾸닥님 일러스트 | Camera: 고꾸닥's Illustration |
| 214170 | 설날 기념 복주머니 | New Year's Lucky Pouch |
| 214171 | 큼직한 세뱃돈 봉투 | Large Gift Envelope |
| 214172 | 세뱃돈 봉투 (지정 소환권) | Gift Envelope (Targeted Summon Tickets) |
| 214173 | 세뱃돈 봉투 (유물 소환권) | Gift Envelope (Artifact Summon Tickets) |
| 214174 | 세뱃돈 봉투 (에리카의 연금술 티켓) | Gift Envelope (Erika's Alchemy Tickets) |
| 214175 | 사랑의 날 기념 초콜릿 상자 | Love Day Chocolate Box |
| 214176 | 사이드 이벤트 행운 상자 | Side Event Lucky Chest |
| 214177 | 마농의 특별 선물 상자 | Manon's Special Gift Box |
| 214178 | 큼직한 럭키 박스 | Huge Lucky Chest |
| 214179 | 럭키 박스 (지정 소환권) | Lucky Chest (Targeted Summon Ticket) |
| 214180 | 럭키 박스 (유물 소환권) | Lucky Chest (Artifact Summon Ticket) |
| 214181 | 럭키 박스 (에리카의 연금술 티켓) | Lucky Chest (Erika's Alchemy Ticket) |
| 214182 | 에픽 정령 선택 상자 (2025) | Epic Soul Selection Chest (2025) |
| 214183 | 스페셜 에픽 정령 선택 상자 (2025) | Special Epic Soul Selection Chest (2025) |
| 214184 | 유물의 기억 선택 상자 (2025) | Artifact Memory Selection Chest (2025) |
| 214185 | 에픽 정령 선택 상자 (1주년) | Epic Soul Selection Chest (1-Year) |
| 214186 | 스페셜 에픽 정령 선택 상자 (1주년) | Special Epic Soul Selection Chest (1-Year) |
| 214187 | 유물의 기억 선택 상자 (1주년) | Artifact Memory Selection Chest (1-Year) |
| 214188 | 세트 예장함 (오리진) | Set Keepsake Chest (Origin) |
| 214189 | 에픽 정령 선택 상자 (2.5주년) | Epic Soul Selection Chest (2.5-Year) |
| 214190 | 스페셜 에픽 정령 선택 상자 (2.5주년) | Special Epic Soul Selection Chest (2.5-Year) |
| 214191 | 유물의 기억 선택 상자 (2.5주년) | Artifact Memory Selection Chest (2.5-Year) |
| 214192 | 금형 선택 상자 (오리진+2) | Mold Selection Chest (Origin+2) |
| 214193 | 금형 상자 (오리진+2) | Mold Chest (Origin+2) |
| 214194 | 금형 선택 상자 (오리진+3) | Mold Selection Chest (Origin+3) |
| 214195 | 금형 상자 (오리진+3) | Mold Chest (Origin+3) |
| 214196 | 세트 예장 선택 상자 (오리진+2) | Set Keepsake Selection Chest (Origin+2) |
| 214197 | 세트 예장 선택 상자 (오리진+3) | Set Keepsake Selection Chest (Origin+3) |
| 214198 | 세트 예장 선택 상자 (오리진+1) | Set Keepsake Selection Chest (Origin+1) |
| 214199 | 공격력/가속 세트 예장 상자 랜덤 상자(오리진+2) | Random ATK/Speed Set Keepsake Chest (Origin+2) |
| 214200 | 춘절 선물상자 |  |
| 214201 | 인간형 정령소환권 (레어) | Humanlike Soul Summon Ticket (Rare) |
| 214202 | 야수형 정령소환권 (레어) | Beast Soul Summon Ticket (Rare) |
| 214203 | 요정형 정령소환권 (레어) | Fairy Soul Summon Ticket (Rare) |
| 214204 | 불사형 정령소환권 (레어) | Undead Soul Summon Ticket (Rare) |
| 214205 | 인간형 정령소환권 (에픽) | Humanlike Soul Summon Ticket (Epic) |
| 214206 | 야수형 정령소환권 (에픽) | Beast Soul Summon Ticket (Epic) |
| 214207 | 요정형 정령소환권 (에픽) | Fairy Soul Summon Ticket (Epic) |
| 214208 | 불사형 정령소환권 (에픽) | Undead Soul Summon Ticket (Epic) |
| 214209 | 천사형 정령소환권 (에픽) | Angel Soul Summon Ticket (Epic) |
| 214210 | 악마형 정령소환권 (에픽) | Demon Soul Summon Ticket (Epic) |
| 214211 | 재화 선택 상자 (2시간) | Currency Selection Chest (2 Hours) |
| 214212 | 재화 선택 상자 (6시간) | Currency Selection Chest (6 Hours) |
| 214213 | 재화 선택 상자 (12시간) | Currency Selection Chest (12 Hours) |
| 214214 | 재화 선택 상자 (24시간) | Currency Selection Chest (24 Hours) |
| 214220 | 알쏭달쏭 마나 크리스탈 봉투 | Intriguing Mana Crystal Envelope |
| 214221 | 알쏭달쏭 방주 강화 봉투 | Intriguing Ark Enhancement Envelope |
| 214222 | 알쏭달쏭 소환 티켓 봉투 | Intriguing Summon Ticket Envelope |
| 214223 | 금형 선택 상자 (오리진+4) | Mold Selection Chest (Origin+4) |
| 214224 | 금형 상자 (오리진+4) | Mold Chest (Origin+4) |
| 214225 | 에픽 정령 선택 상자 (3주년) | Epic Soul Selection Chest (3-Year) |
| 214226 | 스페셜 에픽 정령 선택 상자 (3주년) | Special Epic Soul Selection Chest (3-Year) |
| 214227 | 연금술 정령 선택 상자 | Alchemy Soul Selection Chest |
| 214228 | 데일리 패키지 상자1 | Daily Package Chest 1 |
| 214229 | 데일리 패키지 상자2 | Daily Package Chest 2 |
| 214230 | 데일리 패키지 상자3 | Daily Package Chest 3 |
| 215000 | 아케나인 광장 | Arkenine Square |
| 215001 | 아케나인 다리 | Arkenine Bridge |
| 215002 | 콜브 초원 | Colve Meadow |
| 215003 | 다이난 호수 | Lake Dynan |
| 215004 | 하얀 울새 숲 | White Robin Forest |
| 215005 | 베르트 산맥 | Vert Mountains |
| 215006 | 렉타 황무지 | Rechtar Wasteland |
| 215007 | 비노 협곡 | Vino Valley |
| 215008 | 모레노 사막 | Morreno Desert |
| 215009 | 아르코 이리스 | Arco Iris |
| 215010 | 쿠르 사바나 | Cur Savannah |
| 215011 | 반딧불이의 둥지 | Nest of Fireflies |
| 215012 | 라피아 정글 | Raffia Jungle |
| 215013 | 나델 고산지 | Nadel Mountains |
| 215014 | 그림자 없는 땅 | Shadowless Lands |
| 215015 | 유령도시 모르투스 | Ghost City Mortus |
| 215016 | 버려진 항구 | Forsaken Harbor |
| 215017 | 메티아스 호 갑판 | Mettias Deck |
| 215018 | 가르디눔 대설원 | Gardinum Snowfield |
| 215019 | 루푸스 요새 | Lupus Fortress |
| 215020 | 칸델레로 얼음 산맥 | Candellero Mountains |
| 215110 | 학교 교실 | School Classroom |
| 215111 | 학교 옥상 | School Rooftop |
| 215112 | 학교 복도 | School Corridor |
| 215120 | 클라라의 농장 | Clara Farm |
| 215121 | 꽃밭 | Flower Field |
| 215122 | 행운꽃밭 | Lucky Flower Field |
| 215130 | 탐관오리 클로이 성채 | Corrupt Official Chloe Fortress |
| 215131 | 가온의 온천 | Gaon's Hot Spring |
| 215132 | 가온의 전통 카페 | Gaon's Traditional Cafe |
| 215140 | 병원 로비 | Hospital Lobby |
| 215141 | 낮의 시장 | Daytime Market |
| 215142 | 영지 거리 | Town Street |
| 215150 | 낮의 해수욕장 | Daytime Bathing Beach |
| 215151 | 노을진 해수욕장 | Bathing Beach at Sunset |
| 215152 | 한밤의 해수욕장 | Midnight Beach |
| 215153 | 해변 레스토랑 | Beach Restaurant |
| 215161 | 공주의 처소 | Princess's Abode |
| 215162 | 가온풍 궁전 복도 | Gaon Palace Corridor |
| 215171 | 어두운 숲 | Dark Forest |
| 215172 | 악몽의 들판 | Field of Nightmare |
| 215181 | 눈 덮인 아케나인 광장 | Snow-Covered Arkenine Square |
| 215182 | 눈 덮인 영지 거리 | Snow-Covered Town Street |
| 215191 | 1주년 기념 선상 파티장 | 1st Anniversary Maritime Mirth Venue |
| 215201 | 메이드 카페 | Maid Cafe |
| 215211 | 어둠의 학교 교실 | Sinister School Classroom |
| 215212 | 어둠의 학교 옥상 | Sinister School Rooftop |
| 215213 | 어둠의 학교 복도 | Sinister School Corridor |
| 215221 | 가온의 밤 축제 거리 | Gaon's Night Festival Street |
| 215231 | 칼라르 설산 절벽 | Chalar Snow Mountain Cliff |
| 215232 | 아케나인 예식장 | Arkenine Wedding Hall |
| 215241 | 나무 미로 | Wooden Maze |
| 215251 | 서커스 무대 | Circus Stage |
| 215261 | 이브의 날 메카 컨벤션 | Eve's Day Mech Convention |
| 215271 | 가온의 낮 신년제 거리 | Daytime Street of Gaon's New Year's Festival |
| 215281 | 로제의 심상세계 | Rose's Imaginary World |
| 215291 | 노심굴 | Reactor Core Cave |
| 215400 | 방주 | The Ark |
| 215401 | 낮의 해변가 | Beach (Daytime) |
| 215402 | 밤의 해변가 | Night Beach |
| 215403 | 낮의 성벽 산책로 | Wall Walkway (Daytime) |
| 215404 | 밤의 성벽 산책로 | Wall Walkway (Nighttime) |
| 215405 | 낮의 벚꽃 동산 | Cherry Blossom Hill (Daytime) |
| 215406 | 낮의 종달새 숲 | Lark Forest (Daytime) |
| 215407 | 밤의 종달새 숲 | Lark Forest (Nighttime) |
| 215408 | 밤의 은하수 언덕 | Milky Way Hill (Nighttime) |
| 215409 | 밤의 달빛 호숫가 | Moonlit Lakeside (Nighttime) |
| 215501 | 프레임: 기본 | Frame: Basic |
| 215502 | 프레임: 빨강 | Frame: Red |
| 215503 | 프레임: 노랑 | Frame: Yellow |
| 215504 | 프레임: 보라 | Frame: Purple |
| 215505 | 프레임: 파랑 | Frame: Blue |
| 215506 | 프레임: 녹색 | Frame: Green |
| 215507 | 프레임: 검정 | Frame: Black |
| 215601 | 프레임: 아르바이트의 시작 | Frame: Part-Time Job Begins |
| 215602 | 프레임: 아르바이트 베테랑 | Frame: Part-Time Job Veteran |
| 215603 | 프레임: 아르바이트 마스터 | Frame: Part-Time Job Master |
| 215611 | 프레임: 원정의 시작 | Frame: Expedition Begins |
| 215612 | 프레임: 원정 베테랑 | Frame: Expedition Veteran |
| 215613 | 프레임: 원정 마스터 | Frame: Expedition Master |
| 215621 | 프레임: 나누는 기쁨 | Frame: Sharing is Caring |
| 215622 | 프레임: 아낌없는 나눔 | Frame: Endless Sharing |
| 215623 | 프레임: 아가페 | Frame: Love |
| 215631 | 프레임: 연애초보 | Frame: Dating Novice |
| 215632 | 프레임: 연애달인 | Frame: Dating Expert |
| 215633 | 프레임: 연애마스터 | Frame: Dating Master |
| 215641 | 프레임: 약간의 유명세 | Frame: Small Fame |
| 215642 | 프레임: 인플루언서 | Frame: Influencer |
| 215643 | 프레임: 월드대스타 | Frame: World Star |
| 215651 | 프레임: 사이좋게 지내요 | Frame: Friendship |
| 215652 | 프레임: 인싸일지도 | Frame: Wannabe |
| 215653 | 프레임: 인싸마스터 | Frame: Socialite |
| 215654 | 프레임: 영지 파괴범 | Frame: Town Destroyer |
| 215655 | 프레임: 파괴왕 | Frame: The Destroyer |
| 215656 | 프레임: 파괴의 화신 | Frame: Incarnation of Destruction |
| 215657 | 프레임: 종말을 부르는 인형을 저지한 자 | Frame: One Who Stopped the Doomsday Doll |
| 215658 | 프레임: 종말을 부르는 인형을 정화한 자 | Frame: One Who Purified the Doomsday Doll |
| 215659 | 프레임: 종말을 부르는 인형을 구원한 자 | Frame: One Who Saved the Doomsday Doll |
| 215660 | 프레임: 마물 전문가 | Frame: Monster Expert |
| 215661 | 프레임: 마물 베테랑 | Frame: Monster Veteran |
| 215662 | 프레임: 마물 마스터 | Frame: Monster Master |
| 215663 | 프레임: 마물을 사냥하는 자 | Frame: Monster Hunter |
| 215664 | 프레임: 마물을 토벌하는 자 | Frame: Monster Subjugator |
| 215665 | 프레임: 마물을 멸하는 자 | Frame: Monster Exterminator |
| 215666 | 프레임: 멸망한 세계의 용사 | Frame: Warrior of the Doomed World |
| 215667 | 프레임: 멸망한 세계의 수호자 | Frame: Guardian of the Doomed World |
| 215668 | 프레임: 멸망한 세계의 인도자 | Frame: Leader of the Doomed World |
| 215669 | 프레임: 멸망의 마녀를 저지한 자 | Frame: Stopped the Witch |
| 215670 | 프레임: 멸망의 마녀를 정화한 자 | Frame: Purified the Witch |
| 215671 | 프레임: 멸망의 마녀를 구원한 자 | Frame: Saved the Witch |
| 215672 | 프레임: 원한이 가득한 세계의 용사 | Frame: Warrior of a World Full of Resentment |
| 215673 | 프레임: 원한이 가득한 세계의 수호자 | Frame: Guardian of a World Full of Resentment |
| 215674 | 프레임: 원한이 가득한 세계의 인도자 | Frame: Guide of a World Full of Resentment |
| 215675 | 프레임: 피눈물을 흘리는 원귀를 저지한 자 | Frame: One Who Stopped the Ghost Who Weeps Bitter Tears |
| 215676 | 프레임: 피눈물을 흘리는 원귀를 정화한 자 | Frame: One Who Purified the Ghost Who Weeps Bitter Tears |
| 215677 | 프레임: 피눈물을 흘리는 원귀를 구원한 자 | Frame: One Who Saved the Ghost Who Weeps Bitter Tears |
| 215678 | 프레임: 광기가 가득한 세계의 용사 | Frame: Warrior of a World Full of Madness |
| 215679 | 프레임: 광기가 가득한 세계의 수호자 | Frame: Guardian of a World Full of Madness |
| 215680 | 프레임: 광기가 가득한 세계의 인도자 | Frame: Guide of a World Full of Madness |
| 215681 | 프레임: 광기에 물든 야수를 저지한 자 | Frame: One Who Stopped the Mad Beast |
| 215682 | 프레임: 광기에 물든 야수를 정화한 자 | Frame: One Who Purified the Mad Beast |
| 215683 | 프레임: 광기에 물든 야수를 구원한 자 | Frame: One Who Saved the Mad Beast |
| 215684 | 프레임: 무너진 세계의 용사 | Frame: Warrior of the Collapsed World |
| 215685 | 프레임: 무너진 세계의 수호자 | Frame: Guardian of the Collapsed World |
| 215686 | 프레임: 무너진 세계의 인도자 | Frame: Leader of the Collapsed World |
| 215687 | 프레임: 혼돈에 물든 세계의 용사 | Frame: Warrior of the Chaotic World |
| 215688 | 프레임: 혼돈에 물든 세계의 수호자 | Frame: Guardian of the Chaotic World |
| 215689 | 프레임: 혼돈에 물든 세계의 인도자 | Frame: Leader of the Chaotic World |
| 215690 | 프레임: 비탄의 성녀를 저지한 자 | Frame: One Who Stopped the Saint of Sorrow |
| 215691 | 프레임: 비탄의 성녀를 정화한 자 | Frame: One Who Purified the Saint of Sorrow |
| 215692 | 프레임: 비탄의 성녀를 구원한 자 | Frame: One Who Saved the Saint of Sorrow |
| 215693 | 프레임: 복을 부르는 자 | Frame: Lucky |
| 215694 | 프레임: 전쟁이 가득한 세계의 용사 | Frame: Warrior of a World Full of War |
| 215695 | 프레임: 전쟁이 가득한 세계의 수호자 | Frame: Guardian of a World Full of War |
| 215696 | 프레임: 전쟁이 가득한 세계의 인도자 | Frame: Guide of a World Full of War |
| 215697 | 프레임: 전쟁의 사도를 저지한 자 | Frame: One Who Stopped the Apostle of War |
| 215698 | 프레임: 전쟁의 사도를 정화한 자 | Frame: One Who Purified the Apostle of War |
| 215699 | 프레임: 전쟁의 사도를 구원한 자 | Frame: One Who Saved the Apostle of War |
| 215700 | 프레임: 1주년 기념 프레임 | Frame: 1st Anniversary Frame |
| 215701 | 프레임: 2주년 기념 프레임 | Frame: 2nd Anniversary Frame |
| 215702 | 프레임 : 마물 사냥의 떠오르는 별 | Frame: Rising Star of Monster Hunting |
| 215703 | 프레임 : 마물 사냥의 지배자 | Frame: Sovereign of Monster Hunting |
| 215704 | 프레임 : 마물 사냥의 신 | Frame: God of Monster Hunting |
| 215705 | 프레임: 피로 물든 세계의 용사 | Frame: Warrior of the Blood-Soaked World |
| 215706 | 프레임: 피로 물든 세계의 수호자 | Frame: Guardian of the Blood-Soaked World |
| 215707 | 프레임: 피로 물든 세계의 인도자 | Frame: Leader of the Blood-Soaked World |
| 215708 | 프레임: 피에 물든 검귀를 저지한 자 | Frame: One Who Stopped the Blood-Soaked Sword Demon |
| 215709 | 프레임: 피에 물든 검귀를 정화한 자 | Frame: One Who Purified the Blood-Soaked Sword Demon |
| 215710 | 프레임: 피에 물든 검귀를 구원한 자 | Frame: One Who Saved the Blood-Soaked Sword Demon |
| 215711 | 프레임: 타락한 세계의 용사 | Frame: Warrior of the Corrupted World |
| 215712 | 프레임: 타락한 세계의 수호자 | Frame: Guardian of the Corrupted World |
| 215713 | 프레임: 타락한 세계의 인도자 | Frame: Leader of the Corrupted World |
| 215714 | 프레임: 종말을 찌르는 창을 저지한 자 | Frame: One Who Stopped the Doom Piercer |
| 215715 | 프레임: 종말을 찌르는 창을 정화한 자 | Frame: One Who Purified the Doom Piercer |
| 215716 | 프레임: 종말을 찌르는 창을 구원한 자 | Frame: One Who Saved the Doom Piercer |
| 215717 | 프레임: 추악한 세계의 용사 | Frame: Warrior of the Repulsive World |
| 215718 | 프레임: 추악한 세계의 수호자 | Frame: Guardian of the Repulsive World |
| 215719 | 프레임: 추악한 세계의 인도자 | Frame: Leader of the Repulsive World |
| 215720 | 프레임: 흉몽의 나비를 저지한 자 | Frame: One Who Stopped the Butterfly of An Ominous Dream |
| 215721 | 프레임: 흉몽의 나비를 정화한 자 | Frame: One Who Purified the Butterfly of An Ominous Dream |
| 215722 | 프레임: 흉몽의 나비를 구원한 자 | Frame: One Who Saved the Butterfly of An Ominous Dream |
| 215723 | 프레임: 소중한 마음 | Frame: Cherished Heart |
| 215724 | 프레임: 3주년 기념 프레임 | Frame: 3rd Anniversary Frame |
| 215799 | 프레임: 춘절 기념 |  |
| 215900 | 낮의 방주 | Ark (Daytime) |
| 215901 | 낮의 종달새 숲 | Lark Forest (Daytime) |
| 215902 | 낮의 해변가 | Beach (Daytime) |
| 215903 | 낮의 벚꽃 동산 | Cherry Blossom Hill (Daytime) |
| 215904 | 낮의 성벽 산책로 | Wall Walkway (Daytime) |
| 215905 | 밤의 달빛 호숫가 | Moonlit Lakeside (Nighttime) |
| 215906 | 밤의 은하수 언덕 | Milky Way Hill (Nighttime) |
| 215907 | 밤의 해변가 | Night Beach |
| 215908 | 밤의 종달새 숲 | Lark Forest (Nighttime) |
| 215909 | 밤의 성벽 산책로 | Wall Walkway (Nighttime) |
| 216001 | 사진: 미카와 시하의 하루 | Photo: Mica and Seeha's Day |
| 216002 | 일러스트: 데이트 어 소울 | Illustration: Date A Soul |
| 216005 | 사진: 에덴 갓 탤런트 | Photo: Eden's Got Talent |
| 216006 | 사진: 거미님 일러스트 | Photo: 거미's Illustration |
| 216007 | 사진: 주상절리님 일러스트 | Photo: 주상절리's Illustration |
| 216008 | 사진: yuugen님 일러스트 | Photo: yuugen's Illustration |
| 216009 | 사진: 귄터님 일러스트 | Photo: 귄터's Illustration |
| 216010 | 사진: 고꾸닥님 일러스트 | Photo: 고꾸닥's Illustration |
| 216101 | 스티커: 트로이카 (브론즈) | Sticker: Troyca (Bronze) |
| 216102 | 스티커: 트로이카 (실버) | Sticker: Troyca (Silver) |
| 216103 | 스티커: 트로이카 (골드) | Sticker: Troyca (Gold) |
| 216104 | 스티커: 트로이카 (플래티넘) | Sticker: Troyca (Platinum) |
| 216105 | 스티커: 트로이카 (마스터) | Sticker: Troyca (Master) |
| 216106 | 스티커: 트로이카 (챌린저) | Sticker: Troyca (Challenger) |
| 216107 | 스티커: 트로이카<br>(레전더리) | Sticker: Troyca<br>(Legendary) |
| 216108 | 스티커: 트로이카<br>(레전더리 3위) | Sticker: Troyca<br>(Legendary #3) |
| 216109 | 스티커: 트로이카<br>(레전더리 2위) | Sticker: Troyca<br>(Legendary #2) |
| 216110 | 스티커: 트로이카<br>(레전더리 1위) | Sticker: Troyca<br>(Legendary #1) |
| 216111 | 스티커: 아우렐리아 (브론즈) | Sticker: Aurelia (Bronze) |
| 216112 | 스티커: 아우렐리아 (실버) | Sticker: Aurelia (Silver) |
| 216113 | 스티커: 아우렐리아 (골드) | Sticker: Aurelia (Gold) |
| 216114 | 스티커: 아우렐리아 (플래티넘) | Sticker: Aurelia (Platinum) |
| 216115 | 스티커: 아우렐리아 (마스터) | Sticker: Aurelia (Master) |
| 216116 | 스티커: 아우렐리아 (챌린저) | Sticker: Aurelia (Challenger) |
| 216117 | 스티커: 아우렐리아<br>(레전더리) | Sticker: Aurelia<br>(Legendary) |
| 216118 | 스티커: 아우렐리아<br>(레전더리 3위) | Sticker: Aurelia<br>(Legendary #3) |
| 216119 | 스티커: 아우렐리아<br>(레전더리 2위) | Sticker: Aurelia<br>(Legendary #2) |
| 216120 | 스티커: 아우렐리아<br>(레전더리 1위) | Sticker: Aurelia<br>(Legendary #1) |
| 216121 | 스티커: 타브리아 (브론즈) | Sticker: Tabria (Bronze) |
| 216122 | 스티커: 타브리아 (실버) | Sticker: Tabria (Silver) |
| 216123 | 스티커: 타브리아 (골드) | Sticker: Tabria (Gold) |
| 216124 | 스티커: 타브리아 (플래티넘) | Sticker: Tabria (Platinum) |
| 216125 | 스티커: 타브리아 (마스터) | Sticker: Tabria (Master) |
| 216126 | 스티커: 타브리아 (챌린저) | Sticker: Tabria (Challenger) |
| 216127 | 스티커: 타브리아<br>(레전더리) | Sticker: Tabria<br>(Legendary) |
| 216128 | 스티커: 타브리아<br>(레전더리 3위) | Sticker: Tabria<br>(Legendary #3) |
| 216129 | 스티커: 타브리아<br>(레전더리 2위) | Sticker: Tabria<br>(Legendary #2) |
| 216130 | 스티커: 타브리아<br>(레전더리 1위) | Sticker: Tabria<br>(Legendary #1) |
| 216131 | 스티커: 페이렌 (브론즈) | Sticker: Fayren (Bronze) |
| 216132 | 스티커: 페이렌 (실버) | Sticker: Fayren (Silver) |
| 216133 | 스티커: 페이렌 (골드) | Sticker: Fayren (Gold) |
| 216134 | 스티커: 페이렌 (플래티넘) | Sticker: Fayren (Platinum) |
| 216135 | 스티커: 페이렌 (마스터) | Sticker: Fayren (Master) |
| 216136 | 스티커: 페이렌 (챌린저) | Sticker: Fayren (Challenger) |
| 216137 | 스티커: 페이렌<br>(레전더리) | Sticker: Fayren<br>(Legendary) |
| 216138 | 스티커: 페이렌<br>(레전더리 3위) | Sticker: Fayren<br>(Legendary #3) |
| 216139 | 스티커: 페이렌<br>(레전더리 2위) | Sticker: Fayren<br>(Legendary #2) |
| 216140 | 스티커: 페이렌<br>(레전더리 1위) | Sticker: Fayren<br>(Legendary #1) |
| 216141 | 스티커: 칼라르 (브론즈) | Sticker: Chalar (Bronze) |
| 216142 | 스티커: 칼라르 (실버) | Sticker: Chalar (Silver) |
| 216143 | 스티커: 칼라르 (골드) | Sticker: Chalar (Gold) |
| 216144 | 스티커: 칼라르 (플래티넘) | Sticker: Chalar (Platinum) |
| 216145 | 스티커: 칼라르 (마스터) | Sticker: Chalar (Master) |
| 216146 | 스티커: 칼라르 (챌린저) | Sticker: Chalar (Challenger) |
| 216147 | 스티커: 칼라르<br>(레전더리) | Sticker: Chalar<br>(Legendary) |
| 216148 | 스티커: 칼라르<br>(레전더리 3위) | Sticker: Chalar<br>(Legendary #3) |
| 216149 | 스티커: 칼라르<br>(레전더리 2위) | Sticker: Chalar<br>(Legendary #2) |
| 216150 | 스티커: 칼라르<br>(레전더리 1위) | Sticker: Chalar<br>(Legendary #1) |
| 216151 | 스티커: 가온 (브론즈) | Sticker: Gaon (Bronze) |
| 216152 | 스티커: 가온 (실버) | Sticker: Gaon (Silver) |
| 216153 | 스티커: 가온 (골드) | Sticker: Gaon (Gold) |
| 216154 | 스티커: 가온 (플래티넘) | Sticker: Gaon (Platinum) |
| 216155 | 스티커: 가온 (마스터) | Sticker: Gaon (Master) |
| 216156 | 스티커: 가온 (챌린저) | Sticker: Gaon (Challenger) |
| 216157 | 스티커: 가온<br>(레전더리) | Sticker: Gaon<br>(Legendary) |
| 216158 | 스티커: 가온<br>(레전더리 3위) | Sticker: Gaon<br>(Legendary #3) |
| 216159 | 스티커: 가온<br>(레전더리 2위) | Sticker: Gaon<br>(Legendary #2) |
| 216160 | 스티커: 가온<br>(레전더리 1위) | Sticker: Gaon<br>(Legendary #1) |
| 216161 | 스티커: 솔레이 (브론즈) | Sticker: Solrey (Bronze) |
| 216162 | 스티커: 솔레이 (실버) | Sticker: Solrey (Silver) |
| 216163 | 스티커: 솔레이 (골드) | Sticker: Solrey (Gold) |
| 216164 | 스티커: 솔레이 (플래티넘) | Sticker: Solrey (Platinum) |
| 216165 | 스티커: 솔레이 (마스터) | Sticker: Solrey (Master) |
| 216166 | 스티커: 솔레이 (챌린저) | Sticker: Solrey (Challenger) |
| 216167 | 스티커: 솔레이<br>(레전더리) | Sticker: Solrey<br>(Legendary) |
| 216168 | 스티커: 솔레이<br>(레전더리 3위) | Sticker: Solrey<br>(Legendary #3) |
| 216169 | 스티커: 솔레이<br>(레전더리 2위) | Sticker: Solrey<br>(Legendary #2) |
| 216170 | 스티커: 솔레이<br>(레전더리 1위) | Sticker: Solrey<br>(Legendary #1) |
| 216171 | 스티커: 여름 합숙 훈련 | Sticker: Summer Training Camp |
| 216172 | 스티커: 여름 합숙 훈련 (3위) | Sticker: Summer Training Camp (#3) |
| 216173 | 스티커: 여름 합숙 훈련 (2위) | Sticker: Summer Training Camp (#2) |
| 216174 | 스티커: 여름 합숙 훈련 (1위) | Sticker: Summer Training Camp (#1) |
| 216201 | 스티커: 엘나스 | Sticker: Elnath |
| 216202 | 스티커: 아케나인 | Sticker: Arkenine |
| 216203 | 스티커: 콜브 초원 | Sticker: Colve Meadow |
| 216204 | 스티커: 다이난 호수 | Sticker: Lake Dynan |
| 216205 | 스티커: 하얀 울새 숲 | Sticker: White Robin Forest |
| 216206 | 스티커: 베르트 산맥 | Sticker: Vert Mountains |
| 216207 | 스티커: 비노 협곡 | Sticker: Vino Valley |
| 216208 | 스티커: 렉타 황무지 | Sticker: Rechtar Wasteland |
| 216209 | 스티커: 쿠르 사바나 | Sticker: Cur Savannah |
| 216210 | 스티커: 아르코 이리스 | Sticker: Arco Iris |
| 216211 | 스티커: 모레노 사막 | Sticker: Morreno Desert |
| 216212 | 스티커: 라피아 정글 | Sticker: Raffia Jungle |
| 216213 | 스티커: 반딧불이의 둥지 | Sticker: Nest of Fireflies |
| 216214 | 스티커: 나델 고산지 | Sticker: Nadel Mountains |
| 216215 | 스티커: 그림자 없는 땅 | Sticker: Shadowless Lands |
| 216216 | 스티커: 유령도시 모르투스 | Sticker: Ghost City Mortus |
| 216217 | 스티커: 버려진 항구 | Sticker: Forsaken Harbor |
| 216218 | 스티커: 메티아스 호 갑판 | Sticker: Mettias Deck |
| 216219 | 스티커: 가르디눔 대설원 | Sticker: Gardinum Snowfield |
| 216220 | 스티커: 루푸스 요새 | Sticker: Lupus Fortress |
| 216221 | 스티커: 칸델레로 얼음 산맥 | Sticker: Candellero Mountains |
| 216222 | 스티커: 코르텍스 호 | Sticker: The Cortex |
| 216223 | 스티커: 오레올 산맥 | Sticker: Aureole Mountains |
| 216224 | 스티커: 시조의 연안 | Sticker: Founder's Coast |
| 216225 | 스티커: 아페이온 해식동굴 | Sticker: Apeiron Sea Cave |
| 216226 | 스티커: 루멘 성 입구 | Sticker: Lumen Castle Entrance |
| 216227 | 스티커: 엠포리움 연구소 | Sticker: Emporium Laboratory |
| 216228 | 스티커: 땅의 등대 | Sticker: Lighthouse of the Earth |
| 216229 | 스티커: 아우렐리아 심해 유적 | Sticker: Aurelian Deep Sea Ruins |
| 216230 | 스티커: 밤의 도시 | Sticker: Night City |
| 216231 | 스티커: 연옥으로 가는 길 | Sticker: Road to Purgatory |
| 216232 | 스티커: 별의 등대 | Sticker: Lighthouse of the Stars |
| 216233 | 스티커: 별의 바다 | Sticker: Sea of Stars |
| 216234 | 스티커: 하늘뱃길 | Sticker: Sky Fareway |
| 216235 | 스티커: 침묵의 숲 | Sticker: Forest of Silence |
| 216236 | 스티커: 아우렐리아 시가지 | Sticker: Downtown Aurelia |
| 216237 | 스티커: 아우렐리아 대신전 | Sticker: Aurelia Great Temple |
| 216238 | 스티커: 페이렌 외곽 | Sticker: Fayren Outskirts |
| 216239 | 스티커: 페이렌 수정굴 | Sticker: Fayren Crystal Cave |
| 216301 | 스티커: 에리카의 연금술 | Sticker: Erika's Alchemy |
| 216302 | 스티커: 바삭바삭 닭다리 | Sticker: Crispy Drumstick |
| 216303 | 스티커: 달콤한 초콜릿 | Sticker: Sweet Chocolate |
| 216401 | 스티커: 종말을 부르는 인형 (1위) | Sticker: Doomsday Doll (#1) |
| 216402 | 스티커: 종말을 부르는 인형 (2위) | Sticker: Doomsday Doll (#2) |
| 216403 | 스티커: 종말을 부르는 인형 (3위) | Sticker: Doomsday Doll (#3) |
| 216404 | 스티커: 종말을 부르는 인형 (상위) | Sticker: Doomsday Doll (Top Ranking) |
| 216405 | 스티커: 종말을 부르는 인형 | Sticker: Doomsday Doll |
| 216406 | 스티커: 비탄의 성녀 (1위) | Sticker: Saint of Sorrow (#1) |
| 216407 | 스티커: 비탄의 성녀 (2위) | Sticker: Saint of Sorrow (#2) |
| 216408 | 스티커: 비탄의 성녀 (3위) | Sticker: Saint of Sorrow (#3) |
| 216409 | 스티커: 비탄의 성녀 (상위) | Sticker: Saint of Sorrow (Top Ranking) |
| 216410 | 스티커: 비탄의 성녀 | Sticker: Saint of Sorrow |
| 216411 | 스티커: 세계를 멸망시킨 마녀 (1위) | Sticker: Witch Who Destroyed the World (#1) |
| 216412 | 스티커: 세계를 멸망시킨 마녀 (2위) | Sticker: Witch Who Destroyed the World (#2) |
| 216413 | 스티커: 세계를 멸망시킨 마녀 (3위) | Sticker: Witch Who Destroyed the World (#3) |
| 216414 | 스티커: 세계를 멸망시킨 마녀 (상위) | Sticker: Witch Who Destroyed the World (Top Ranking) |
| 216415 | 스티커: 세계를 멸망시킨 마녀 | Sticker: Witch Who Destroyed the World |
| 216416 | 스티커: 전쟁의 사도 (1위) | Sticker: Apostle of War (#1) |
| 216417 | 스티커: 전쟁의 사도 (2위) | Sticker: Apostle of War (#2) |
| 216418 | 스티커: 전쟁의 사도 (3위) | Sticker: Apostle of War (#3) |
| 216419 | 스티커: 전쟁의 사도 (상위) | Sticker: Apostle of War (Top Ranking) |
| 216420 | 스티커: 전쟁의 사도 | Sticker: Apostle of War |
| 216421 | 스티커: 광기에 물든 야수 (1위) | Sticker: Mad Beast (#1) |
| 216422 | 스티커: 광기에 물든 야수 (2위) | Sticker: Mad Beast (#2) |
| 216423 | 스티커: 광기에 물든 야수 (3위) | Sticker: Mad Beast (#3) |
| 216424 | 스티커: 광기에 물든 야수 (상위) | Sticker: Mad Beast (Top Ranking) |
| 216425 | 스티커: 광기에 물든 야수 | Sticker: Mad Beast |
| 216426 | 스티커: 피에 물든 검귀 (1위) | Sticker: Blood-Soaked Sword Demon (#1) |
| 216427 | 스티커: 피에 물든 검귀 (2위) | Sticker: Blood-Soaked Sword Demon (#2) |
| 216428 | 스티커: 피에 물든 검귀 (3위) | Sticker: Blood-Soaked Sword Demon (#3) |
| 216429 | 스티커: 피에 물든 검귀 (상위) | Sticker: Blood-Soaked Sword Demon (Top Ranking) |
| 216430 | 스티커: 피에 물든 검귀 | Sticker: Blood-Soaked Sword Demon |
| 216431 | 스티커: 피눈물을 흘리는 원귀 (1위) | Sticker: Ghost Who Weeps Bitter Tears (#1) |
| 216432 | 스티커: 피눈물을 흘리는 원귀 (2위) | Sticker: Ghost Who Weeps Bitter Tears (#2) |
| 216433 | 스티커: 피눈물을 흘리는 원귀 (3위) | Sticker: Ghost Who Weeps Bitter Tears (#3) |
| 216434 | 스티커: 피눈물을 흘리는 원귀 (상위) | Sticker: Ghost Who Weeps Bitter Tears (Top Ranking) |
| 216435 | 스티커: 피눈물을 흘리는 원귀 | Sticker: Ghost Who Weeps Bitter Tears |
| 216436 | 스티커: 종말을 찌르는 창 (1위) | Sticker: Doom Piercer (#1) |
| 216437 | 스티커: 종말을 찌르는 창 (2위) | Sticker: Doom Piercer (#2) |
| 216438 | 스티커: 종말을 찌르는 창 (3위) | Sticker: Doom Piercer (#3) |
| 216439 | 스티커: 종말을 찌르는 창 (상위) | Sticker: Doom Piercer (Top Ranking) |
| 216440 | 스티커: 종말을 찌르는 창 | Sticker: Doom Piercer |
| 216441 | 스티커: 흉몽의 나비 (1위) | Sticker: Butterfly of An Ominous Dream (#1) |
| 216442 | 스티커: 흉몽의 나비 (2위) | Sticker: Butterfly of An Ominous Dream (#2) |
| 216443 | 스티커: 흉몽의 나비 (3위) | Sticker: Butterfly of An Ominous Dream (#3) |
| 216444 | 스티커: 흉몽의 나비 (상위) | Sticker: Butterfly of An Ominous Dream (Top Ranking) |
| 216445 | 스티커: 흉몽의 나비 | Sticker: Butterfly of An Ominous Dream |
| 216601 | 스티커: 대난투! 미궁 올스타즈 | Sticker: Labyrinth All-Stars Brawl! |
| 216602 | 스티커: 등대지기 (1위) | Sticker: Lighthouse Keeper (#1) |
| 216603 | 스티커: 등대지기 (2위) | Sticker: Lighthouse Keeper (#2) |
| 216604 | 스티커: 등대지기 (3위) | Sticker: Lighthouse Keeper (#3) |
| 216605 | 스티커: 등대지기 (상위) | Sticker: Lighthouse Keeper (Top Ranking) |
| 216606 | 스티커: 등대지기 | Sticker: Lighthouse Keeper |
| 216607 | 스티커: 베히모스 (1위) | Sticker: Behemoth (#1) |
| 216608 | 스티커: 베히모스 (2위) | Sticker: Behemoth (#2) |
| 216609 | 스티커: 베히모스 (3위) | Sticker: Behemoth (#3) |
| 216610 | 스티커: 베히모스 (상위) | Sticker: Behemoth (Top Ranking) |
| 216611 | 스티커: 베히모스 | Sticker: Behemoth |
| 216612 | 스티커: 케이린 (1위) | Sticker: Kayrin (#1) |
| 216613 | 스티커: 케이린 (2위) | Sticker: Kayrin (#2) |
| 216614 | 스티커: 케이린 (3위) | Sticker: Kayrin (#3) |
| 216615 | 스티커: 케이린 (상위) | Sticker: Kayrin (Top Ranking) |
| 216616 | 스티커: 케이린 | Sticker: Kayrin |
| 216701 | 스티커: 1주년 기념 화환 | Sticker: 1st Anniversary Wreath |
| 216702 | 스티커: 게임 오버 | Sticker: Game Over |
| 216703 | 스티커: 야토가미 토카 | Sticker: Tohka Yatogami |
| 216704 | 스티커: 토키사키 쿠루미 | Sticker: Kurumi Tokisaki |
| 216705 | 스티커: 2주년 기념 화환 | Sticker: 2nd Anniversary Wreath |
| 216706 | 스티커: 3주년 기념 딱지 | Sticker: 3rd Anniversary Paper Tile |
| 216801 | 스티커: 기원의 증표 - 릴리트 | Sticker: Token of Origin - Lilith |
| 216802 | 스티커: 기원의 증표 - 웨리 | Sticker: Token of Origin - Wheri |
| 216803 | 스티커: 기원의 증표 - 사쿠요(업화) | Sticker: Token of Origin - Sakuyo (Inferno) |
| 216804 | 스티커: 기원의 증표 - 메피스토펠레스(여명) | Sticker: Token of Origin - Mephistopheles (Dawn) |
| 216805 | 스티커: 기원의 증표 - 바이스 | Sticker: Token of Origin - Weiss |
| 216806 | 스티커: 기원의 증표 - 로제(홍염) | Sticker: Token of Origin - Rose (Prominence) |
| 216807 | 스티커: 기원의 증표 - 홍란(무쌍) | Sticker: Token of Origin - Honglan (Peerless) |
| 216808 | 스티커: 기원의 증표 - 한울 | Sticker: Token of Origin - Hanul |
| 216809 | 스티커: 기원의 증표 - 지호(미르) | Sticker: Token of Origin - Jiho (Mir) |
| 216810 | 스티커: 기원의 증표 - 르네(백은) | Sticker: Token of Origin - Renee (Argent) |
| 216811 | 스티커: 기원의 증표 - 라우라 | Sticker: Token of Origin - Laura |
| 216812 | 스티커: 기원의 증표 - 니아 | Sticker: Token of Origin - Nia |
| 216813 | 스티커: 기원의 증표 - 하루(카무이) | Sticker: Token of Origin - Haru (Kamuy) |
| 216814 | 스티커: 기원의 증표 - 미리암(잔영) | Sticker: Token of Origin - Miriam (Afterimage) |
| 216815 | 스티커: 기원의 증표 - 페트라(각혼) | Sticker: Token of Origin - Petra (Awakened Soul) |
| 216816 | 스티커: 기원의 증표 - 카넬리안 | Sticker: Token of Origin - Carnelian |
| 216817 | 스티커: 기원의 증표 - 가넷(열락) | Sticker: Token of Origin - Garnet (Rapture) |
| 216818 | 스티커: 기원의 증표 - | Sticker: Token of Origin - |
| 216819 | 스티커: 기원의 증표 - 셰리(낭만) | Sticker: Token of Origin - Cherrie (Romantic) |
| 216820 | 스티커: 기원의 증표 - 캐서린(광휘) | Sticker: Token of Origin - Catherine (Radiance) |
| 216821 | 스티커: 기원의 증표 - 유리아 | Sticker: Token of Origin - Yuria |
| 216822 | 스티커: 기원의 증표 - 클라우디아(대천사) | Sticker: Token of Origin - Claudia (Archangel) |
| 216823 | 스티커: 기원의 증표 - 린지(타나토스) | Sticker: Token of Origin - Linzy (Thanatos) |
| 216824 | 스티커: 기원의 증표 - 헤이즐 | Sticker: Token of Origin - Hazel |
| 216825 | 스티커: 기원의 증표 - 이브 | Sticker: Token of Origin - Eve |
| 216826 | 스티커: 기원의 증표 - 시그리드 | Sticker: Token of Origin - Sigrid |
| 216827 | 스티커: 기원의 증표 - 라리마 | Sticker: Token of Origin - Larimar |
| 216828 | 스티커: 기원의 증표 - 오닉스 | Sticker: Token of Origin - Onyx |
| 216829 | 스티커: 기원의 증표 - 도미니크 | Sticker: Token of Origin - Dominique |
| 216830 | 스티커: 기원의 증표 - 유리아(아폴리온) | Sticker: Token of Origin - Yuria (Apollyon) |
| 216831 | 스티커: 기원의 증표 - 아야메 (츠쿠요미) | Sticker: Token of Origin - Ayame (Tsukuyomi) |
| 216901 | 스티커: 썰매왕 슬레이봅 (1위) | Sticker: Sled King Sleighbob (#1) |
| 216902 | 스티커: 썰매왕 슬레이봅 (2위) | Sticker: Sled King Sleighbob (#2) |
| 216903 | 스티커: 썰매왕 슬레이봅 (3위) | Sticker: Sled King Sleighbob (#3) |
| 216904 | 스티커: 썰매왕 슬레이봅 (챌린저) | Sticker: Sled King Sleighbob (Challenger) |
| 216905 | 스티커: 썰매왕 슬레이봅 (마스터) | Sticker: Sled King Sleighbob (Master) |
| 216906 | 스티커: 썰매왕 슬레이봅 (플래티넘) | Sticker: Sled King Sleighbob (Platinum) |
| 216907 | 스티커: 썰매왕 슬레이봅 (골드) | Sticker: Sled King Sleighbob (Gold) |
| 216908 | 스티커: 썰매왕 슬레이봅 (실버) | Sticker: Sled King Sleighbob (Silver) |
| 216909 | 스티커: 썰매왕 슬레이봅 (브론즈) | Sticker: Sled King Sleighbob (Bronze) |
| 216910 | 스티커: 메카이아 (1위) | Sticker: Mecha Gaia (#1) |
| 216911 | 스티커: 메카이아 (2위) | Sticker: Mecha Gaia (#2) |
| 216912 | 스티커: 메카이아 (3위) | Sticker: Mecha Gaia (#3) |
| 216913 | 스티커: 메카이아 (챌린저) | Sticker: Mecha Gaia (Challenger) |
| 216914 | 스티커: 메카이아 (마스터) | Sticker: Mecha Gaia (Master) |
| 216915 | 스티커: 메카이아 (플래티넘) | Sticker: Mecha Gaia (Platinum) |
| 216916 | 스티커: 메카이아 (골드) | Sticker: Mecha Gaia (Gold) |
| 216917 | 스티커: 메카이아 (실버) | Sticker: Mecha Gaia (Silver) |
| 216918 | 스티커: 메카이아 (브론즈) | Sticker: Mecha Gaia (Bronze) |
| 216919 | 스티커: 떡공장장 순이 (1위) | Sticker: Rice Cake Factory Chief Soonie (#1) |
| 216920 | 스티커: 떡공장장 순이 (2위) | Sticker: Rice Cake Factory Chief Soonie (#2) |
| 216921 | 스티커: 떡공장장 순이 (3위) | Sticker: Rice Cake Factory Chief Soonie (#3) |
| 216922 | 스티커: 떡공장장 순이 (챌린저) | Sticker: Rice Cake Factory Chief Soonie (Challenger) |
| 216923 | 스티커: 떡공장장 순이 (마스터) | Sticker: Rice Cake Factory Chief Soonie (Master) |
| 216924 | 스티커: 떡공장장 순이 (플래티넘) | Sticker: Rice Cake Factory Chief Soonie (Platinum) |
| 216925 | 스티커: 떡공장장 순이 (골드) | Sticker: Rice Cake Factory Chief Soonie (Gold) |
| 216926 | 스티커: 떡공장장 순이 (실버) | Sticker: Rice Cake Factory Chief Soonie (Silver) |
| 216927 | 스티커: 떡공장장 순이 (브론즈) | Sticker: Rice Cake Factory Chief Soonie (Bronze) |
| 216928 | 스티커: 기록되지 않은 미래(1위) | Sticker: The Unwritten Future (#1) |
| 216929 | 스티커: 기록되지 않은 미래(2위) | Sticker: The Unwritten Future (#2) |
| 216930 | 스티커: 기록되지 않은 미래(3위) | Sticker: The Unwritten Future (#3) |
| 216931 | 스티커: 기록되지 않은 미래(챌린저) | Sticker: The Unwritten Future (Challenger) |
| 216932 | 스티커: 기록되지 않은 미래(마스터) | Sticker: The Unwritten Future (Master) |
| 216933 | 스티커: 기록되지 않은 미래(플래티넘) | Sticker: The Unwritten Future (Platinum) |
| 216934 | 스티커: 기록되지 않은 미래(골드) | Sticker: The Unwritten Future (Gold) |
| 216935 | 스티커: 기록되지 않은 미래(실버) | Sticker: The Unwritten Future (Silver) |
| 216936 | 스티커: 기록되지 않은 미래(브론즈) | Sticker: The Unwritten Future (Bronze) |
| 216937 | 스티커: 천리주단기(1위) | Sticker: Riding Alone for Thousands of Miles (#1) |
| 216938 | 스티커: 천리주단기(2위) | Sticker: Riding Alone for Thousands of Miles (#2) |
| 216939 | 스티커: 천리주단기(3위) | Sticker: Riding Alone for Thousands of Miles (#3) |
| 216940 | 스티커: 천리주단기(챌린저) | Sticker: Riding Alone for Thousands of Miles (Challenger) |
| 216941 | 스티커: 천리주단기(마스터) | Sticker: Riding Alone for Thousands of Miles (Master) |
| 216942 | 스티커: 천리주단기(플래티넘) | Sticker: Riding Alone for Thousands of Miles (Platinum) |
| 216943 | 스티커: 천리주단기(골드) | Sticker: Riding Alone for Thousands of Miles (Gold) |
| 216944 | 스티커: 천리주단기(실버) | Sticker: Riding Alone for Thousands of Miles (Silver) |
| 216945 | 스티커: 천리주단기(브론즈) | Sticker: Riding Alone for Thousands of Miles (Bronze) |
| 216946 | 스티커: 사해파정(1위) | Sticker: Calm Waves of Four Seas (#1) |
| 216947 | 스티커: 사해파정(2위) | Sticker: Calm Waves of Four Seas (#2) |
| 216948 | 스티커: 사해파정(3위) | Sticker: Calm Waves of Four Seas (#3) |
| 216949 | 스티커: 사해파정(챌린저) | Sticker: Calm Waves of Four Seas (Challenger) |
| 216950 | 스티커: 사해파정(마스터) | Sticker: Calm Waves of Four Seas (Master) |
| 216951 | 스티커: 사해파정(플래티넘) | Sticker: Calm Waves of Four Seas (Platinum) |
| 216952 | 스티커: 사해파정(골드) | Sticker: Calm Waves of Four Seas (Gold) |
| 216953 | 스티커: 사해파정(실버) | Sticker: Calm Waves of Four Seas (Silver) |
| 216954 | 스티커: 사해파정(브론즈) | Sticker: Calm Waves of Four Seas (Bronze) |
| 216955 | 스티커: 극광의 너머로(1위) | Sticker: Beyond the Extreme Light (#1) |
| 216956 | 스티커: 극광의 너머로(2위) | Sticker: Beyond the Extreme Light (#2) |
| 216957 | 스티커: 극광의 너머로(3위) | Sticker: Beyond the Extreme Light (#3) |
| 216958 | 스티커: 극광의 너머로(챌린저) | Sticker: Beyond the Extreme Light (Challenger) |
| 216959 | 스티커: 극광의 너머로(마스터) | Sticker: Beyond the Extreme Light (Master) |
| 216960 | 스티커: 극광의 너머로(플래티넘) | Sticker: Beyond the Extreme Light (Platinum) |
| 216961 | 스티커: 극광의 너머로(골드) | Sticker: Beyond the Extreme Light (Gold) |
| 216962 | 스티커: 극광의 너머로(실버) | Sticker: Beyond the Extreme Light (Silver) |
| 216963 | 스티커: 극광의 너머로(브론즈) | Sticker: Beyond the Extreme Light (Bronze) |
| 216964 | 스티커: 폭주한 실베스터 조이 3세 (1위) | Sticker: Rampaging King Sylvester Joey III (#1) |
| 216965 | 스티커: 폭주한 실베스터 조이 3세 (2위) | Sticker: Rampaging King Sylvester Joey III (#2) |
| 216966 | 스티커: 폭주한 실베스터 조이 3세 (3위) | Sticker: Rampaging King Sylvester Joey III (#3) |
| 216967 | 스티커: 폭주한 실베스터 조이 3세 (챌린저) | Sticker: Rampaging King Sylvester Joey III (Challenger) |
| 216968 | 스티커: 폭주한 실베스터 조이 3세 (마스터) | Sticker: Rampaging King Sylvester Joey III (Master) |
| 216969 | 스티커: 폭주한 실베스터 조이 3세 (플래티넘) | Sticker: Rampaging King Sylvester Joey III (Platinum) |
| 216970 | 스티커: 폭주한 실베스터 조이 3세 (골드) | Sticker: Rampaging King Sylvester Joey III (Gold) |
| 216971 | 스티커: 폭주한 실베스터 조이 3세 (실버) | Sticker: Rampaging King Sylvester Joey III (Silver) |
| 216972 | 스티커: 폭주한 실베스터 조이 3세 (브론즈) | Sticker: Rampaging King Sylvester Joey III (Bronze) |
| 216973 | 스티커: 아마'게'돈 (1위) | Sticker: CRABmageddon (#1) |
| 216974 | 스티커: 아마'게'돈 (2위) | Sticker: CRABmageddon (#2) |
| 216975 | 스티커: 아마'게'돈 (3위) | Sticker: CRABmageddon (#3) |
| 216976 | 스티커: 아마'게'돈 (챌린저) | Sticker: CRABmageddon (Challenger) |
| 216977 | 스티커: 아마'게'돈 (마스터) | Sticker: CRABmageddon (Master) |
| 216978 | 스티커: 아마'게'돈 (플래티넘) | Sticker: CRABmageddon (Platinum) |
| 216979 | 스티커: 아마'게'돈 (골드) | Sticker: CRABmageddon (Gold) |
| 216980 | 스티커: 아마'게'돈 (실버) | Sticker: CRABmageddon (Silver) |
| 216981 | 스티커: 아마'게'돈 (브론즈) | Sticker: CRABmageddon (Bronze) |
| 216982 | 스티커: 환영을 꿰뚫는 탄환 (1위) | Sticker: Illusion-Piercing Bullet (#1) |
| 216983 | 스티커: 환영을 꿰뚫는 탄환 (2위) | Sticker: Illusion-Piercing Bullet (#2) |
| 216984 | 스티커: 환영을 꿰뚫는 탄환 (3위) | Sticker: Illusion-Piercing Bullet (#3) |
| 216985 | 스티커: 환영을 꿰뚫는 탄환 (챌린저) | Sticker: Illusion-Piercing Bullet (Challenger) |
| 216986 | 스티커: 환영을 꿰뚫는 탄환 (마스터) | Sticker: Illusion-Piercing Bullet (Master) |
| 216987 | 스티커: 환영을 꿰뚫는 탄환 (플래티넘) | Sticker: Illusion-Piercing Bullet (Platinum) |
| 216988 | 스티커: 환영을 꿰뚫는 탄환 (골드) | Sticker: Illusion-Piercing Bullet (Gold) |
| 216989 | 스티커: 환영을 꿰뚫는 탄환 (실버) | Sticker: Illusion-Piercing Bullet (Silver) |
| 216990 | 스티커: 환영을 꿰뚫는 탄환 (브론즈) | Sticker: Illusion-Piercing Bullet (Bronze) |
| 216991 | 스티커: 아이돌 퀸 캐서린(1위) | Sticker: Idol Queen Catherine (#1) |
| 216992 | 스티커: 아이돌 퀸 캐서린(2위) | Sticker: Idol Queen Catherine (#2) |
| 216993 | 스티커: 아이돌 퀸 캐서린(3위) | Sticker: Idol Queen Catherine (#3) |
| 216994 | 스티커: 아이돌 퀸 캐서린(챌린저) | Sticker: Idol Queen Catherine (Challenger) |
| 216995 | 스티커: 아이돌 퀸 캐서린(마스터) | Sticker: Idol Queen Catherine (Master) |
| 216996 | 스티커: 아이돌 퀸 캐서린(플래티넘) | Sticker: Idol Queen Catherine (Platinum) |
| 216997 | 스티커: 아이돌 퀸 캐서린(골드) | Sticker: Idol Queen Catherine (Gold) |
| 216998 | 스티커: 아이돌 퀸 캐서린(실버) | Sticker: Idol Queen Catherine (Silver) |
| 216999 | 스티커: 아이돌 퀸 캐서린(브론즈) | Sticker: Idol Queen Catherine (Bronze) |
| 217001 | 조각 케이크 | Sliced Cake |
| 217002 | 스콘 | Scone |
| 217003 | 쿠키 세트 | Cookie Set |
| 217004 | 감자칩 | Potato Chips |
| 217005 | 그린 샐러드 | Green Salad |
| 217006 | 도시락 | Lunch Box |
| 217007 | 피시 앤 칩스 | Fish & Chips |
| 217008 | 꼬치구이 | Grilled Skewer |
| 217009 | 커피 | Coffee |
| 217010 | 꿀과 우유 | Honey and Milk |
| 217011 | 허브티 | Herbal Tea |
| 217012 | 과일 주스 | Fruit Juice |
| 217013 | 헤어핀 | Hairclip |
| 217014 | 키 링 | Key Ring |
| 217015 | 향수 | Perfume |
| 217016 | 빗과 거울 | Comb and Mirror |
| 217017 | 수제 곰인형 | Handmade Teddy Bear |
| 217018 | 드림 캐처 | Dreamcatcher |
| 217019 | 탁상 액자 | Table Frame |
| 217020 | 기념주화 | Commemorative Coin |
| 217021 | 만년필 | Fountain Pen |
| 217022 | 부채 | Fan |
| 217023 | 단검 | Dagger |
| 217024 | 마법 스크롤 | Magic Scroll |
| 217025 | 쿠폰 | Coupon |
| 217026 | 모종삽 | Trowel |
| 217027 | 포션 | Potion |
| 217028 | 손수건 | Handkerchief |
| 217029 | 트럼프 카드 | Trump Card |
| 217030 | 우쿨렐레 | Ukulele |
| 217031 | 큐브 | Cube |
| 217032 | 쿠션 | Cushion |
| 217033 | 작은 화분 | Small Pot |
| 217034 | 이야기책 | Story Book |
| 217035 | 찻잔 세트 | Teacup Set |
| 217036 | 영원꽃 | Eternity Flower |
| 217037 | 행운의 꽃다발 | Lucky Bouquet |
| 217100 | 스티커: 열락의 밤으로(1위) | Sticker: Into the Night of Rapture (#1) |
| 217101 | 스티커: 열락의 밤으로(2위) | Sticker: Into the Night of Rapture (#2) |
| 217102 | 스티커: 열락의 밤으로(3위) | Sticker: Into the Night of Rapture (#3) |
| 217103 | 스티커: 열락의 밤으로(챌린저) | Sticker: Into the Night of Rapture (Challenger) |
| 217104 | 스티커: 열락의 밤으로(마스터) | Sticker: Into the Night of Rapture (Master) |
| 217105 | 스티커: 열락의 밤으로(플래티넘) | Sticker: Into the Night of Rapture (Platinum) |
| 217106 | 스티커: 열락의 밤으로(골드) | Sticker: Into the Night of Rapture (Gold) |
| 217107 | 스티커: 열락의 밤으로(실버) | Sticker: Into the Night of Rapture (Silver) |
| 217108 | 스티커: 열락의 밤으로(브론즈) | Sticker: Into the Night of Rapture (Bronze) |
| 217109 | 스티커: 낭만항로(1위) | Sticker: Romantic Voyage (#1) |
| 217110 | 스티커: 낭만항로(2위) | Sticker: Romantic Voyage (#2) |
| 217111 | 스티커: 낭만항로(3위) | Sticker: Romantic Voyage (#3) |
| 217112 | 스티커: 낭만항로(챌린저) | Sticker: Romantic Voyage (Challenger) |
| 217113 | 스티커: 낭만항로(마스터) | Sticker: Romantic Voyage (Master) |
| 217114 | 스티커: 낭만항로(플래티넘) | Sticker: Romantic Voyage (Platinum) |
| 217115 | 스티커: 낭만항로(골드) | Sticker: Romantic Voyage (Gold) |
| 217116 | 스티커: 낭만항로(실버) | Sticker: Romantic Voyage (Silver) |
| 217117 | 스티커: 낭만항로(브론즈) | Sticker: Romantic Voyage (Bronze) |
| 217118 | 스티커: 소원 도둑 오닉스(1위) | Sticker: Wish Thief Onyx (#1) |
| 217119 | 스티커: 소원 도둑 오닉스(2위) | Sticker: Wish Thief Onyx (#2) |
| 217120 | 스티커: 소원 도둑 오닉스(3위) | Sticker: Wish Thief Onyx (#3) |
| 217121 | 스티커: 소원 도둑 오닉스(챌린저) | Sticker: Wish Thief Onyx (Challenger) |
| 217122 | 스티커: 소원 도둑 오닉스(마스터) | Sticker: Wish Thief Onyx (Master) |
| 217123 | 스티커: 소원 도둑 오닉스(플래티넘) | Sticker: Wish Thief Onyx (Platinum) |
| 217124 | 스티커: 소원 도둑 오닉스(골드) | Sticker: Wish Thief Onyx (Gold) |
| 217125 | 스티커: 소원 도둑 오닉스(실버) | Sticker: Wish Thief Onyx (Silver) |
| 217126 | 스티커: 소원 도둑 오닉스(브론즈) | Sticker: Wish Thief Onyx (Bronze) |
| 218001 | 행복한 크마리스스 파티 꾸러미 | Happy Kumawreaths Party Bundle |
| 218002 | 수집 이벤트 아이템 | Collection Event Item |
| 218003 | 금빛 꿈주머니 | Gold Dream Pouch |
| 218004 | 사랑의 묘약 | Love Potion |
| 218005 | 행운의 꽃잎 | Lucky Petal |
| 218006 | 에버스쿨 경품 메달 | Everschool Prize Medal |
| 218007 | 체육부 딱지 | P.E. Club Voucher |
| 218008 | 바른생활부 딱지 | Ethics Club Voucher |
| 218009 | 이벤트 레이드 입장권 | Event Raid Ticket |
| 218010 | 이벤트 스테이지 입장권 | Event Stage Ticket |
| 218011 | 웨딩 부케 | Wedding Bouquet |
| 218012 | 웨딩 리본 | Wedding Ribbon |
| 218013 | 웨딩 와인 | Wedding Wine |
| 218014 | 미니 게임 입장권 | Mini Game Ticket |
| 218015 | 비비안의 경품 메달 | Vivienne's Prize Medal |
| 218016 | 히비스커스 꽃 | Hibiscus |
| 218017 | 시글래스 조각 | Sea Glass Piece |
| 218018 | 에덴 갓 탤런트 투표권 | Eden's Got Talent Vote |
| 218019 | 빙고 티켓 | Bingo Ticket |
| 218020 | 아드리안의 경품 메달 | Adrianne's Prize Medal |
| 218021 | 비치볼 | Beach Ball |
| 218022 | 러버덕 | Rubber Duck |
| 218023 | 보름달 별전 | Full Moon Special Coin |
| 218024 | 화전 | Flower Rice Pancake |
| 218025 | 송편 | Half-Moon Rice Cake |
| 218026 | 할로윈 경품 메달 | Halloween Prize Medal |
| 218027 | 빨간 모자 쿠폰 | Red Riding Hood Coupon |
| 218028 | 나쁜 늑대 쿠폰 | Bad Wolf Coupon |
| 218029 | 붉은 달의 악몽 입장권 | Red Moon Nightmare Ticket |
| 218030 | 크리스마스 경품 메달 | Christmas Prize Medal |
| 218031 | 도라 친구 배지 | Dora Friend Badge |
| 218032 | 가넷 친구 배지 | Garnet Friend Badge |
| 218033 | 크마리스스 대소동 입장권 | Kumawreaths Kerfuffle Ticket |
| 218034 | 미궁 올스타즈 입장권 | Labyrinth All-Stars Ticket |
| 218035 | 훈련 포인트 | Training Points |
| 218037 | 탐관오리 클로이 입장권 | Corrupt Official Chloe Ticket |
| 218039 | 파티 경품 추첨권 | Mirth Prize Ticket |
| 218040 | 별빛 메달 | Starlight Medal |
| 218041 | 금빛 챔피언 휘장 | Golden Champion Insignia |
| 218042 | 파티 레이드 입장권 | Mirth Raid Ticket |
| 218044 | 파라다이스 레이드 입장권 | Paradise Raid Ticket |
| 218045 | 메이드 경품 코인 | Maid Prize Coins |
| 218046 | 진상 퇴치 딱지 A | Troublemaker Purge Sticker A |
| 218047 | 진상 퇴치 딱지 B | Troublemaker Purge Sticker B |
| 218048 | 쇼콜라 퀸 레이드 입장권 | Chocolat Queen Raid Ticket |
| 218050 | 하얀 울새 숲 미니 게임 입장권 | White Robin Forest Mini Game Ticket |
| 218054 | 에버스쿨 레이드 입장권 | Everschool Raid Ticket |
| 218055 | 어둠의 에버스쿨 경품 메달 | Sinister Everschool Prize Medal |
| 218056 | 다프네의 바주카포 단추 | Daphne's Bazooka Button |
| 218057 | 마농의 회계부장 딱지 | Manon's Bursar Sticker |
| 218058 | 어둠의 학생회장 레이드 입장권 | Sinister Student President Raid Ticket |
| 218062 | 부케 쟁탈전 레이드 입장권 | Bouquet Scramble Raid Ticket |
| 218063 | 여름 축제 쿠폰 | Summer Festival Coupon |
| 218064 | 가온 무투회 레이드 입장권 | Gaon Martial Arts Tournament Raid Ticket |
| 218068 | 여름 낙원 탈환 레이드 입장권 | Getting Back Summer Paradise Raid Ticket |
| 218071 | 비밀스러운 코르사주 | Secretive Corsage |
| 218072 | 비올레트의 웨딩 슈즈 | Violette's Wedding Shoes |
| 218073 | 가넷의 웨딩 브로치 | Garnet's Wedding Brooch |
| 218074 | 결혼전쟁 레이드 입장권 | Wedding War Raid Ticket |
| 218077 | 시도 브로마이드 | Photo of Shido |
| 218078 | 콩고물 빵 | Kinako Buns |
| 218079 | 검은 고양이 인형 | Stuffed Black Cat |
| 218080 | 배틀 어 라이브 레이드 입장권 | Battle A Live Raid Ticket |
| 218084 | 잔혹한 천사의 밀당 레이드 입장권 | Cruel Angel's Play Raid Ticket |
| 218086 | 유령 인형 | Ghost Effigy |
| 218087 | 랜턴 | Lantern |
| 218088 | 촬영 필름 | Film Reel |
| 218089 | 미로 탈출 대소동 레이드 입장권 | Maze Maneuver Madness Raid Ticket |
| 218093 | 위험한 혼례 레이드 입장권 | Dangerous Wedding Raid Ticket |
| 218099 | 경품 티켓 | Prize Ticket |
| 218100 | 바니바니 훈련 수료증 | Bunny Bunny Training Certificate |
| 218101 | 문라이트 훈련 수료증 | Moonlight Training Certificate |
| 218102 | 문라이트 퍼포먼스 레이드 입장권 | Moonlight Performance Raid Ticket |
| 218108 | 컨벤션 경품 교환권 | Convention Prize Ticket |
| 218109 | 저지 작전 훈장 | Stopping Operation Medal |
| 218110 | 수색 작전 훈장 | Search Operation Medal |
| 218111 | 성야의 폭주 레이드 입장권 | Starry Night Frenzy Raid Ticket |
| 218114 | 떡주머니 | Rice Cake Pouch |
| 218115 | 탁주 사발 | Rice Wine Bowl |
| 218116 | 불꽃 노리개 | Firework Charm |
| 218117 | 신년맞이 떡공장털이 레이드 입장권 | New Year's Rice Cake Factory Raid Ticket |
| 218118 | 룰렛 티켓 (기록되지 않은 미래) | Spin Ticket (The Unwritten Future) |
| 218119 | 심연의 경계 미니 게임 입장권 | Boundaries of the Abyss Mini Game Ticket |
| 218121 | 룰렛 티켓 (천리주단기) | Spin Ticket (Riding Alone for Thousands of Miles) |
| 218122 | 노심 방위전 미니 게임 입장권 | Reactor Core Defense Mini Game Ticket |
| 218133 | 주사위(사해파정) | Dice (Calm Waves of Four Seas) |
| 218134 | 궁기 길들이기 미니 게임 입장권 | Taming Unicat Mini Game Ticket |
| 218135 | 룰렛 티켓 (열락의 밤으로) | Spin Ticket (Into the Night of Rapture) |
| 218136 | 낭만항로 이벤트 스테이지 입장권 | Romantic Voyage Event Stage Ticket |
| 218137 | 룰렛 티켓(낭만항로) | Spin Ticket (Romantic Voyage) |
| 218138 | 가슴 벅찬 해변의 비밀 데이트 입장권 | Heart-Stopping Secret Beach Date Ticket |
| 218140 | 아케나인 방어전 미니 게임 입장권 | Defense of Arkenine Mini Game Ticket |
| 218141 | 룰렛 티켓(회고록: 극광의 너머로) | Spin Ticket (Memoir: Beyond the Extreme Light) |
| 218146 | 흩어진 서류 뭉치 | Scattered Document Bundle |
| 218147 | 왕궁 먼지떨이 | Royal Palace Duster |
| 218148 | 최고급 식자재 | Top-Quality Ingredients |
| 218149 | 개판 5분 전 레이드 입장권 | 5 Minutes to Fur-mageddon Raid Ticket |
| 218155 | 집게발 코인 | Pincer Coin |
| 218156 | 사쿠요의 칭찬 도장 | Sakuyo's Stamp of Approval |
| 218157 | 구원자의 칭찬 도장 | Savior's Stamp of Approval |
| 218158 | 물 뜨라 부르는 소리 있도다 레이드 입장권 | Fetch Water, the Voice Calls Raid Ticket |
| 218159 | 디모니크와 광기의 숲 미니 게임 입장권 | Dimonique and the Forest of Madness Mini Game Ticket |
| 218160 | 팬텀의 특수 훈련 미니 게임 입장권 | Phantom's Special Training Mini Game Ticket |
| 218161 | 주사위(환영을 꿰뚫는 탄환) | Dice (Illusion-Piercing Bullet) |
| 218162 | 아이돌 퀸 굿즈 추첨권 | Idol Queen Merch Raffle Ticket |
| 218163 | 보컬 트레이닝 수료증 | Vocal Training Certificate |
| 218164 | 댄스 트레이닝 수료증 | Dance Training Certificate |
| 218165 | 아이돌 퀸의 특별 무대 레이드 입장권 | Idol Queen's Special Stage Raid Ticket |
| 218166 | 빙고 티켓(3주년) | Bingo Ticket (3rd Anniversary) |
| 218167 | 무사안녕 기원 복주머니 | Safety-Prayer Lucky Pouch |
| 218168 | 운수대통 기원 복주머니 | Fortune's Favor Lucky Pouch |
| 218169 | 만사형통 행운 복권 | Prospering Fortune Lottery Ticket |
| 218170 | 소원 도둑을 잡아라! 레이드 입장권 | Catch the Wish Thief! Raid Ticket |
| 218901 | 마농팩 체험권 (7일) | Manon Pack Trial Ticket (7 Days) |
| 218902 | 샤링팩 체험권 (7일) | Sharinne Pack Trial Ticket (7 Days) |
| 218903 | 마농팩 체험권 (10일) | Manon Pack Trial Ticket (10 Days) |
| 218904 | 샤링팩 체험권 (10일) | Sharinne Pack Trial Ticket (10 Days) |
| 219000 | 지정된 예장에서 일정 확률로 세트 옵션이 부여됩니다. | Has a chance to grant set option to a Keepsake. |
| 220001 | 솔레이 왕국에서 발행된 금화.<br>다양한 곳에서 사용된다. | A gold coin issued by the Kingdom of Solrey.<br>Widely used in various places. |
| 220002 | 마력이 내재된 특별한 보석.<br>대량의 마력이 필요한 곳에 사용된다. | A special gem embedded with magic.<br>Used where a large amount of magic is required. |
| 220003 | 마나가 깃든 가루.<br>정령의 레벨업에 사용된다. | Mana Powder.<br>Used to level up Souls. |
| 220004 | 마나가 응축된 결정.<br>정령의 레벨업에 사용된다. | A crystal composed of condensed Mana.<br>Used to level up Souls. |
| 220005 | 경험이 축적된 두루마리.<br>플레이어의 레벨업에 사용된다. | A scroll of accumulated experience.<br>Used to level up the player. |
| 220006 | 친구와 주고 받는 우정의 증표.<br>우정 소환에 사용된다. | A token of friendship exchanged with friends.<br>Used for Friendship Summon. |
| 220008 | 레벨 동기화 슬롯 확장에 사용된다. | Used for expanding Level Sync slots. |
| 220009 | 아레나에서 상대에게 도전을 할 때,<br>무료 도전 횟수가 없으면 대신 사용된다.<br>(도전권은 아레나 보상 이벤트 혜택 미적용) | Used for challenging an opponent in the Arena<br>when all free challenges have been used up.<br>(Arena reward event perks do not apply to Challenge Tickets) |
| 220010 | 미궁에서 습득 가능한 주화.<br>미궁 상점에서 사용할 수 있다. | A coin obtained in the Labyrinth.<br>Can be used in the Labyrinth Shop. |
| 220011 | 강력한 보스와의 전투로 습득 가능한 주화.<br>레이드 상점에서 사용할 수 있다. | A coin obtained from battles with powerful bosses.<br>Can be used in the Raid Shop. |
| 220012 | 정령이 해방되며 남기는 결정.<br>해방 상점에서 사용할 수 있다. | A crystal Souls leave behind when they are Released.<br>Can be used in the Release Shop. |
| 220013 | 아레나, 챔피언스 아레나에서 지급되는 화폐.<br>아레나 상점에서 사용할 수 있다. | Currency issued in the Arena and the Champs Arena.<br>Can be used in the Arena Shop. |
| 220014 | 기억의 회랑 보상 혹은 유물의 기억을 분해하여 얻을 수 있는 주화<br>유물 상점에서 사용할 수 있다. | Currency obtained from Hall of Memories Rewards or by dismantling Artifact Memories.<br>Can be used in the Artifact Shop. |
| 220016 | 아르바이트 보수로 지급되는 화폐.<br>영지 상점에서 사용할 수 있다. | Currency paid for part-time jobs.<br>Can be used in the Town Shop. |
| 220018 | 악령 토벌에서 습득 가능한 주화.<br>악령 상점에서 사용할 수 있다. | A coin obtained from the Evil Soul Subjugation.<br>Can be used in the Evil Soul Shop. |
| 220019 | 픽업 소환에서 정령을 1회 소환할 수 있다. | Used to summon a Soul once in Pick-Up Summon. |
| 220020 | 유물 강화에 사용됩니다. <br>1~10레벨까지 사용 가능합니다. | Used for enhancing Artifacts.<br>Available from Level 1 to 10. |
| 220021 | 유물 강화에 사용됩니다. <br>11~20레벨까지 사용 가능합니다. | Used for enhancing Artifacts.<br>Available from Level 11 to 20. |
| 220022 | 인간형 타입 정령의 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing Artifacts of Humanlike Souls.<br>Applicable for enhancing to Levels 21–45. |
| 220023 | 야수형 타입 정령의 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing Artifacts of Beast Souls.<br>Applicable for enhancing to Levels 21–45. |
| 220024 | 요정형 타입 정령의 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing Artifacts of Fairy Souls.<br>Applicable for enhancing to Levels 21–45. |
| 220025 | 불사형 타입 정령의 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing Artifacts of Undead Souls.<br>Applicable for enhancing to Levels 21–45. |
| 220026 | 천사형 타입 정령의 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing Artifacts of Angel Souls.<br>Applicable for enhancing to Levels 21–45. |
| 220027 | 악마형 타입 정령의 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing Artifacts of Demon Souls.<br>Applicable for enhancing to Levels 21–45. |
| 220028 | 일반 소환에서 정령을 1회 소환할 수 있다. | Used to summon a Soul once in Normal Summon. |
| 220029 | 타입 소환에서 정령을 1회 소환할 수 있다. | Used to summon a Soul once in Type Summon. |
| 220030 | 정령의 기억(레어)을 60개 수집하여 사용시 랜덤으로 레어 정령을 획득 가능 | Collect 60 Soul's Memories (Rare) and use them to obtain a random Rare Soul. |
| 220031 | 정령의 기억(에픽)을 60개 수집하여 사용시 랜덤으로 에픽 정령을 획득 가능 | Collect 60 Soul's Memories (Epic) and use them to obtain a random Epic Soul. |
| 220032 | 예장 강화 시 사용되며 사용 시 예장 경험치 10을 획득할 수 있다. | Used for enhancing a Keepsake, applying 10 Keepsake EXP. |
| 220033 | 데이트 어 라이브 V 픽업 소환에서 정령을 1회 소환할 수 있다.<br>데이트 어 라이브 V 픽업이 모두 종료 시 픽업 소환권으로 변경됩니다. | Used to summon a Soul once in Date A Live V Pick-Up Summon.<br>Will be changed into a regular Pick-Up Summon Ticket after all Date A Live V Pick-Up events end. |
| 220044 | 아레나에서 상대에게 도전을 할 때,<br>무료 도전 횟수가 없으면 대신 사용된다. | Used for challenging an opponent in the Arena<br>when all free challenges have been used up. |
| 220045 | 일반 유물 소환에서 유물을 1회 소환할 수 있다. | Used to summon an Artifact once in Normal Artifact Summon. |
| 220046 | 에리카의 연금술을 이용할 수 있는 티켓 | A ticket that allows you to use Erika's Alchemy. |
| 220047 | 승급 초기화를 즉시 사용할 수 있는 이용권<br>재사용 일정에 관계없이 승급 초기화를 1회 이용할 수 있다. | A ticket that allows immediate use of Reset Ascension.<br>Grants 1 use of Reset Ascension regardless of its recharge schedule. |
| 220048 | 예장 강화 시 사용되며 사용 시 예장 경험치 250을 획득할 수 있다. | Used for enhancing a Keepsake, applying 250 Keepsake EXP. |
| 220049 | 예장 강화 시 사용되며 사용 시 예장 경험치 1000을 획득할 수 있다. | Used for enhancing a Keepsake, applying 1,000 Keepsake EXP. |
| 220050 | 성좌 능력을 획득하는 데 사용되는 포인트. 플레이어 레벨이 오를 때마다 1씩 획득한다. | Points used for unlocking Zodiac buffs. Every player level increase grants 1 Zodiac Point. |
| 220051 | 조각난 차원의 미궁 입장에 필요한 입장권.<br>조각난 차원의 미궁을 1회 이용할 수 있다.<br><br>(입장권을 통한 입장은 미궁 이벤트 적용에서 제외됩니다.) | A ticket needed for entering the Dimensional Labyrinth.<br>You can enter the Dimensional Labyrinth once with this ticket.<br><br>(Entering with a ticket does not count towards Dimensional Labyrinth events.) |
| 220052 | 이터널+ 등급 이상의 예장 초월시 사용됩니다. | Used when transcending an Eternal+ or higher grade Keepsake. |
| 220053 | 악령 토벌에 필요한 입장권.<br>악령 토벌을 1회 이용할 수 있다.<br><br>(악령 토벌 종료 시 소멸됩니다) | A ticket for entering the Evil Soul Subjugation.<br>Can be used for 1 entry to the Evil Soul Subjugation.<br><br>(Disappears when the Evil Soul Subjugation ends.) |
| 220054 | 이터널+ 이상 등급의 예장 세트 옵션을 랜덤하게 변경 가능한 아이템 | An item that allows you to randomly change the set option of an Eternal+ or higher grade keepsake. |
| 220055 | 기억의 회랑 입장에 필요한 입장권.<br>기억의 회랑을 1회 이용할 수 있다.<br><br>(입장권을 통한 입장은 회랑 이벤트 적용에서 제외됩니다.) | A ticket needed for entering the Hall of Memories.<br>You can enter the Hall of Memories once with this ticket.<br><br>(Entering with a ticket does not count towards Dimensional Labyrinth events.) |
| 220056 | 에덴 연합 작전의 무한 작전에서 제약을 해금할 수 있는 허가증. 보유한 수량에 따라 제약이 해금된다.<br>(에덴 연합 작전 종료 시 소멸된다.) | A permit that allows you to lift restrictions for the Infinite Operations of Operation Eden Alliance. Restrictions are lifted depending on the amount of permits you have.<br>(Disappears when Operation Eden Alliance ends.) |
| 220057 | 에덴연합작전의 임무를 수행한 자에게 주어지는 작전 기념 주화. 연합 상점에서 사용할 수 있다. | A coin given to those who complete the Operation Eden Alliance missions. Can be used at the Operation Shop. |
| 220058 | 자유 타입 게이트를 제외한 타입 게이트 입장에 필요한 입장권,<br>하루에 5씩 최대 35개까지 충전된다.<br>타입 게이트 1회 승리 시 1개 소모된다. | A ticket needed for entering into a Type Gate, excluding Unlimited Gates.<br>You can add up to 35 tickets per day, 5 each time.<br>Each win at the Type Gate consumes 1 ticket. |
| 220059 | 기원의 탑 입장에 필요한 입장권,<br>하루에 5씩 최대 35개까지 충전된다.<br>기원의 탑 1회 승리 시 1개 소모된다. | A ticket needed for entering into the Tower of Origin.<br>You can add up to 35 tickets per day, 5 each time.<br>Each win at the Tower of Origin consumes 1 ticket. |
| 220060 | 양동 작전 입장에 필요한 티켓입니다.<br>하루에 3개씩 최대 3개까지 충전되며<br>양동 작전 클리어 시 1개씩 소모됩니다. | A ticket needed to enter the Decoy Operation.<br>You get up to 3 for free each day.<br>One ticket is consumed when you complete the Decoy Operation. |
| 220061 | 양동 작전 도전 모드 입장에 필요한 티켓입니다.<br>일주일에 한번 1개씩 최대 1개까지 충전되며<br>양동 작전 도전 모드 클리어 시 1개씩 소모됩니다. | A ticket needed to enter the Decoy Operation Challenge Mode.<br>You get 1 for free each week.<br>One ticket is consumed when you complete the Decoy Operation Challenge Mode. |
| 220062 | 양동 작전 추가 입장에 필요한 티켓입니다.<br>양동 작전 티켓이 모두 소비된 후<br>양동 작전 클리어 시 1개씩 소모됩니다. | A ticket that gives you an extra entry to the Decoy Operation.<br>One ticket is consumed when you complete the Decoy Operation Challenge Mode<br>after using up all the Decoy Operation Challenge Mode Tickets. |
| 220063 | 양동 작전 도전 모드 추가 입장에 필요한 티켓입니다.<br>양동 작전 도전 모드 티켓이 모두 소비된 후<br>양동 작전 도전 모드 클리어 시 1개씩 소모됩니다. | A ticket that gives you an extra entry to the Decoy Operation Challenge Mode.<br>One ticket is consumed when you complete the Decoy Operation Challenge Mode<br>after using up all the Decoy Operation Challenge Mode Tickets. |
| 220064 | 유물 강화에 사용됩니다. <br>21~45레벨까지 사용 가능합니다. | Used for enhancing artifacts.<br>Applicable for enhancing to Levels 21–45. |
| 220065 | 오색의 비경에서 획득할 수 있는 결정.<br>정령의 잠재능력 개화와 변경에 사용된다. | Crystal obtained in the Iridescent Scenic Instance.<br>Used for unlocking and changing a Soul's Potentials. |
| 220066 | 지정 소환에서 정령을 1회 소환할 수 있다. | Used to summon a Soul once in Targeted Summon. |
| 220067 | 게임 내에서 상품을 교환할 수 있습니다.<br>RMB와 쿠폰의 교환 비율은 1:10입니다. | Can be exchanged for in-game items.<br>The exchange rate is 1 RMB to 10 coupons. |
| 220101 | 빛이 바랜 나무 소재의 낡은 시계.<br>한때는 누군가의 손목에 자리했던 물건이지만<br>이제는 시침이 멈춘 지 오래 되었다. | A faded wooden watch.<br>Once placed on someone's wrist everyday, now ticks no more. |
| 220102 | 빛이 바랜 나무 소재의 낡은 오르골. <br>태엽을 돌리니 느린 멜로디가 흘러나온다.<br>듣고 있으니 졸음이 밀려온다… | A faded wooden orgel.<br>It plays such a slow melody that it makes you sleepy... |
| 220103 | 빛이 바랜 나무 프레임의 낡은 거울. <br>표면에 금이 갔지만 사물을 비추는 것엔 무리가 없다.<br><br>「그렇네요. <br>완벽하지 않아도 괜찮은 거군요…」 | A faded wooden mirror.<br>The mirror is cracked but it still functions.<br><br>"I see. It's okay to be imperfect..." |
| 220104 | 빛이 바랜 나무 소재의 낡은 열쇠. <br>만듦새는 나쁘지 않지만, 험하게 다루면 부러질 것 같다.<br><br>무엇을 열었던 열쇠인지는 알 수 없지만, <br>아마 다시 사용하게 될 일은 없을 것이다. | A faded wooden key.<br>It's well made, but could break if used carelessly.<br><br>Not sure what it used to be for,<br>but it surely won't be used ever again. |
| 220201 | 금속 소재의 시계. <br>낡은 시계지만 시곗바늘을 조작하면 사용할 수 있다.<br>누군가가 아주 소중히 관리해온듯 하다. | Metallic clock.<br>It's an old clock, but it's still usable after adjusting the hands.<br>Someone took good care of it. |
| 220202 | 금속 소재의 오르골. <br>오르골 밑면에 무언가 적혀있다. <br><br>「오지 않는 연인을 기다리며.<br>생일 축하해. 너의 마지막 사랑 K로부터.」 | Metallic orgel.<br>There's an inscription under it.<br><br>"To my love who does not return.<br>Happy Birthday. Your last love, K. |
| 220203 | 금속 소재의 거울. <br>오래된 물건이지만 먼지를 닦자 반짝반짝 새 것 같다.<br>깨지지 않게 조심히 다루자. | Metallic mirror.<br>It's an old piece, but looks brand new after a good scrub.<br>Be careful not to break it. |
| 220204 | 금속 소재의 열쇠.<br>아이가 평범하던 금속 열쇠에 리본을 달자<br>세상에서 단 하나뿐인 열쇠가 되었다! | Metallic key.<br>A child wrapped a ribbon around the key, making it a one of a kind key! |
| 220301 | 철금속 소재의 회중시계.<br>멈춘 시계를 열어보니 접힌 종이 조각이 있다.<br>종이는 마모되어 내용 확인이 불가능하다. | Pocket watch made of ferrous metal.<br>A note is within the stopped watch.<br>The message is no longer readable. |
| 220302 | 철금속 소재의 오르골.<br>태엽을 감자 생소한 노래가 흘러나온다.<br><br>「이 노래를 들은 건 네가 처음일 걸.<br>이건 널 위해 만든 노래니까.」 | Orgel made of ferrous metal.<br>It plays a song you've never heard of.<br><br>"You're probably the first to hear this song. Because it was made for you." |
| 220303 | 철금속 소재의 접이식 거울<br>케이스에 흠집이 나있다.<br>거울의 표면이 아주 어두워서 잘 보이지 않는다. | Folding mirror made of ferrous metal.<br>There's a dent in the case, and the mirror is too dark to see anything. |
| 220304 | 철금속 소재의 열쇠.<br>아주 깊숙한 곳에 보관되어있던 물건인 듯 하다.<br><br>“잘 들어. 창고는 절대로 열면 안 돼.<br>이 열쇠의 존재는 그냥 잊어버려!” | Key made of ferrous metal.<br>Looks like it was kept somewhere deep.<br><br>"Listen. You must never open the storehouse. Just forget about the key!" |
| 220401 | 중후한 스타일의 탁상시계. <br><br>시계를 제작한 것은 한 마법사로, <br>은은하게 마나가 깃들어있다. | Vintage table clock.<br><br>It was made by a magician<br>and has some mana in it. |
| 220402 | 중후한 스타일의 뮤직박스.<br><br>흘러나오는 노래는 유명한 클래식이다.<br>본래 바이올린으로 연주되었던 노래는, 오르골의 구슬 같은 멜로디로 다시금 재해석 된다. | Vintage music box.<br><br>It plays a famous classic.<br>Originally a violin piece, the music feels more resonating when played by an orgel. |
| 220403 | 중후한 스타일의 탁상거울.<br><br>단순한 거울 같지만, 사실은 원하는 곳의 전경을 볼 수 있는 마법 도구.<br>도구에 깃든 마나가 약해 지금은 사용할 수 없다. | Vintage table mirror.<br><br>Looks like an ordinary mirror, but it is a tool to view any scenery one wishes.<br>However, it doesn't have enough mana to function anymore. |
| 220404 | 중후한 스타일의 열쇠.<br><br>자격이 있는 자만이 사용할 수 있는 마도구.<br>열쇠 안의 마나와 사용자의 마나를 함께 흘려 넣어야 비로소 본 능력을 발휘할 수 있다 | Vintage key.<br><br>A magic tool only the worthy can use.<br>The mana within the key and the users mana must both flow for the key to properly work. |
| 220405 | 대기 중의 마나가 깃든 회중시계.<br><br>만약 마나를 느끼는 것에 재능이 있다면, 시계를 손 안에 쥐어보자.<br>희미한 마나가 느껴질 것이다. | Pocket watch with environmental mana imbued within.<br><br>If you have the gift to detect mana, hold it in your hand.<br>You'll feel the faint flow of mana. |
| 220406 | 대기 중의 마나가 깃든 오르골.<br><br>마법사의 자질을 구별하기 위해 사용되는 마도구. 마나를 감지하면 뚜껑이 열린다. | Orgel with environmental mana imbued within.<br><br>Tool used to test the aptitude of magicians. The lid opens when magic is detected. |
| 220407 | 대기 중의 마나가 깃든 접이거울.<br><br>거울 표면에 무언가 묻은 듯 혼탁하다. <br>마나를 흘려넣자 거울이 순간 맑게 반짝인다. | Mirror with environmental mana imbued within.<br><br>The surface is at first opaque.<br>It becomes shiny clear when mana is flown into it. |
| 220408 | 대기 중의 마나가 깃든 도구.<br><br>열쇠처럼 보이지만 사실은 장식품이다. <br>마나를 감지하면 희미하게 빛난다. | Tool with environmental mana imbued within.<br><br>Looks like a key, but it is a decorative ornament.<br>Gives a faint glow when mana is detected. |
| 220409 | 누군가의 염원이 깃든 모래시계.<br><br>조용히 쌓이는 모래알엔 각자의 소원이 담겨있다.<br>어쩌면 당신의 소원도 이 모래알에 깃들었을까? | Hourglass imbued with someone's hopes.<br><br>Each quietly falling sand particle holds a wish.<br>Perhaps your wish is in one of them? |
| 220410 | 누군가의 염원이 깃든 스노우볼.<br><br>작은 소원들이 마나라는 매개를 통해 물건에 깃들었다.<br>귀를 기울이자 소망의 목소리가 들린다. | Snow globe imbued with someone's hopes.<br><br>Small wishes have settled in this item via mana.<br>Listen close to hear someone's wish. |
| 220411 | 누군가의 염원이 깃든 거울.<br><br>간절한 소망을 품고 응시하면 거울이 답을 준다는 소문이 있다.<br>나아가야 할 길이 보일지도 모른다. | Mirror imbued with someone's hopes.<br><br>Rumor has it the mirror answers when you peer into it with a desperate wish in mind.<br>It could show you the path you need to take. |
| 220412 | 누군가의 염원이 깃든 열쇠.<br><br>미약한 마나의 기운이 느껴진다.<br>아무것도 열 수 없지만, 또 뭐든지 열 수 있는 열쇠이기도 하다. | Key imbued with someone's hopes.<br><br>Weak mana can be felt from it.<br>It can open nothing and everything. |
| 220501 | 마력이 흘러넘치는 신비로운 시계.<br><br>지상의 시간 개념이 아닌 우주의 시공을 측정하는 시계로,<br>멈춰있는 것처럼 보여도 끊임없이 운동하고 있다. | Mysterious clock with mana overflowing from within.<br><br>It measures the spacetime continuum of space, and although it may look like it's stopped, it's continuously moving. |
| 220502 | 마력이 흘러넘치는 신비로운 뮤직박스.<br><br>작은 성운에서 별이 탄생한다. <br>신비로운 음악 속에서 갓 태어난 별은 주변의 작은 마력을 흡수하며 성장한다. | Mysterious music box with mana overflowing from within.<br><br>Stars are born from within nebulas.<br>Stars newly born from mysterious music grows by absorbing mana around it. |
| 220503 | 마력이 흘러넘치는 신비로운 탁상거울.<br><br>일견 평범한 거울로 보일 수 있으나, 사실은 성좌를 관측하기 위한 마도구이다. 해가 진 뒤 밤하늘을 향해 거울을 비추면 된다. | Mysterious table mirror with mana overflowing from within.<br><br>Looks like an ordinary mirror, but it was made to research constellations. Face the mirror at the sky at night. |
| 220504 | 마력이 흘러넘치는 신비로운 열쇠.<br><br>우주에 떠도는 은하 조각을 세공하여 만든 마도구로, 자세히 들여다보면 흐르는 우주의 강줄기를 엿볼 수 있다. | Mysterious key with mana overflowing from within.<br><br>A magical tool made from a galaxy fragment. Look closely to see the flow of space. |
| 220505 | 누군가의 마력이 담긴 회중시계.<br><br>은하 토끼의 애장품. <br>항상 바쁜 우주의 안내원에겐 시간 체크가 필수이다.<br>「앗, 또 별 하나가 사라졌잖아!」 | Pocket watch imbued with someone's mana.<br><br>Treasure of a galaxy rabbit.<br>Checking the time is crucial for the ever busy space guides.<br>"Oh, another star just vanished!" |
| 220506 | 누군가의 마력이 담긴 오르골.<br><br>오르골의 뚜껑을 연 소녀는 그만 우주로 빨려 들어가 버렸다.<br>어디까지 가야 할까? 그저 별빛에 의지해 걸어갈 뿐이다. | Orgel imbued with someone's mana.<br><br>The girl who opened the orgel was sucked into space.<br>How far should she go? She walks the path lit by stars. |
| 220507 | 누군가의 마력이 담긴 거울.<br><br>배가 고픈 소녀가 밤하늘의 별조각을 깨물어 먹자, 순식간에 몸이 거대해졌다!<br>거울을 본 소녀는 울상을 짓고 말았다. | Mirror imbued with someone's mana.<br><br>The hungry girl took a bite out of a star in the night sky and suddenly became humungous!<br>She became sad when she looked in the mirror. |
| 220508 | 누군가의 마력이 담긴 열쇠.<br><br>「그 열쇠에 딱 맞는 별을 찾으렴. <br>그러면 집으로 돌아갈 수 있을 거야.」 | Key imbued with someone's mana.<br><br>"Find the star that perfectly fits the key. Then you'll be able to return home." |
| 220509 | 별의 기운이 넘치는 모래시계.<br><br>유성의 잔해로 만들어진 모래시계.<br>소멸하기 전 발광하는 빛의 가루들이 조용히 부유하고 있다. | Hourglass overflowing with star energy.<br><br>This hourglass is made with meteorite pieces.<br>Light fragments silently float within, refusing to dissipate. |
| 220510 | 별의 기운이 넘치는 스노우볼.<br><br>유성이 떨어지자 모두가 손을 모아 간절한 소원을 빌었다.<br>하늘 위 빛나는 별까지 닿도록. | Snow globe overflowing with star energy.<br><br>When the meteor fell, everyone made their wishes, hoping they would reach the stars. |
| 220511 | 별의 기운이 넘치는 손거울.<br>거울에 비치는 건 마른 팔다리뿐. 유성에 빈 소원은 단 한 가지였다.<br>「제 병이 낫게 해주세요.」 | Hand mirror overflowing with star energy.<br><br>Only her scrawny arms and legs could be seen in the mirror. She had just one wish.<br>"Please cure my disease." |
| 220512 | 별의 기운이 넘치는 마법열쇠.<br>작은 별이 눈을 감았다. 그리고 곧 다시 태어날 것이다.<br>「이제 잘 시간이야. 내일 일어나면 모든 게 달라져 있을 거야.」 | Magic key overflowing with star energy.<br><br>The small star closed its eyes. It will be reborn soon.<br>"It's time to sleep. Everything will be different tomorrow." |
| 220601 | 아기곰이 좋아하는 탁상시계.<br><br>곰 인형의 소원은 진짜 곰이 되는 것.<br>곰 인형의 몸으론 아이에게 말을 걸어줄 수 없으니까. | Table clock adored by a baby bear.<br><br>The teddy bear only wishes to become a real bear.<br>A doll cannot talk to a child, you see. |
| 220602 | 아기곰이 좋아하는 뮤직박스.<br><br>비록 진짜 곰처럼 사나운 울음소리를 낼 순 없어도,<br>소중한 아이에게 노래를 불러줄 수는 있었다. | Music box adored by a baby bear.<br><br>Though it couldn't growl like a real bear,<br>it could sing for its precious child. |
| 220603 | 아기곰이 좋아하는 거울.<br><br>곰 인형은 거울에 비친 자신의 뭉툭한 손을 바라보았다.<br>「이런 몸으로는 안아줄 수가 없네.」 곰 인형은 그만 울상을 짓고 말았다. | Mirror adored by a baby bear.<br><br>The teddy bear looked at its stubby hands in the mirror.<br>"I cannot give a hug in this body." Then it became sad. |
| 220604 | 아기곰이 좋아하는 열쇠.<br><br>곰 인형은 자신의 리본을 사랑했다. 이건 바로 곰 인형이 아이의 단 하나뿐인 곰이라는 증표였기 때문이다! | Key adored by a baby bear.<br><br>The teddy bear loved its ribbon. It was the proof that it was the child's only teddy bear. |
| 220605 | 짐승의 무늬가 각인된 회중시계.<br><br>빠르게 흘러가는 초침을 바라보고 있으니 눈이 빙글빙글 돈다…<br>이 속도는… 어림잡아 시속 50km 정도는 될지도 모른다! | Pocket watch with beast pattern carvings.<br><br>Staring at the fast hand makes you dizzy...<br>This... Is going at least 50km per hour! |
| 220606 | 짐승의 장식이 올라간 오르골.<br><br>위풍당당한 표범 엠블럼이 멋스럽다.<br>고양잇과는 모두 높은 곳을 좋아하나? | Orgel with a beast decoration on top.<br><br>The leopard emblem is marvelous.<br>Do all cats like high places? |
| 220607 | 짐승의 눈동자가 각인된 접이거울.<br><br>세로로 긴 동공이 형형하게 빛나고 있다. <br>밤눈이 밝으니 등 뒤를 주의하는 게 좋다. | Folding mirror with a beast's eye carved into it.<br><br>The vertically split pupil shines bright.<br>It sees well in the dark, so mind you back. |
| 220608 | 짐승의 발바닥이 각인된 만능열쇠.<br><br>말랑말랑해 보이지만 의외로 날카로운 발톱을 가지고 있다. <br>자꾸 누르면 손등을 긁혀버릴지도 모르니 조심하자. | Master key with a beast paw design.<br><br>Looks soft, but it hides sharp claws.<br>Keep pressing it and you'll get scratched. |
| 220609 | 정교한 각인의 모래시계. <br><br>거대한 날개가 하늘을 자유롭게 가로지르니, 이것을 「자유」라고 부르기로 하였다. | Hourglass with exquisite markings.<br><br>Giant wings cut through the air freely. We called this "Freedom". |
| 220610 | 정교한 각인의 스노우볼.<br><br>손 안의 세계에서 파도가 치고 대기가 순환한다. <br>눈 내리는 바다는 영원히 얼지 않을 것이다. | Snow globe with exquisite markings.<br><br>Waves crash and the air flows in the palm of your hands.<br>The snowy sea will never freeze. |
| 220611 | 정교한 각인의 손거울. <br><br>독수리의 커다란 날개가 거울을 둥글게 감싸고 있다. <br>힘찬 날갯짓은 모두를 미래로 인도하는 힘이 된다. | Hand mirror with exquisite markings.<br><br>Giant wings of an eagle envelopes the mirror.<br>Its powerful thrusts guide all into the future. |
| 220612 | 정교한 각인의 마법열쇠.<br><br>고결하고 거룩한 지혜의 상징. 지혜는 비밀의 문을 여는 열쇠이다. <br>「그러니 문 너머를 두려워하지 말라.」 | Magic key with exquisite markings.<br><br>A symbol of nobility and holiness. Wisdom is the key to opening the secret door.<br>"Therefore, do not fear what is beyond the door." |
| 220701 | 가넷이 세공된 화려한 탁상시계.<br><br>피처럼 붉은 가넷을 보고 있자면 사랑으로 가득한 누군가를 떠올리게 된다.<br>「후후, 영원히 나만 봐줘야 해?」 | Table clock decorated with a garnet.<br><br>The blood red garnet reminds you of someone full of love.<br>"Haha, keep your eyes on me, forever." |
| 220702 | 가넷이 세공된 화려한 뮤직박스.<br><br>태엽을 돌리자 들리는 건 유명한 사랑 노래.<br>오르골의 멜로디가 귓가에 끈적하게 달라붙어 도무지 떨어지지 않는다… | Music box decorated with a garnet.<br><br>A famous love song is played.<br>The melody sticks to your ears and refuses to let go. |
| 220703 | 가넷이 세공된 화려한 탁상거울.<br><br>3면의 거울에 비친 시선이 전부 한 곳을 향하고 있다. 타인을 향한 맹목적인 집착은 어쩌면 결핍의 한 종류일지도 모른다. | Table mirror decorated with a garnet.<br><br>The 3 sided mirrors all face the same direction. Obsession for someone is a form of deficiency. |
| 220704 | 가넷이 세공된 화려한 금고열쇠.<br><br>열쇠와 함께 받은 상자, 열어봐도 괜찮을까?<br>…진짜로 괜찮으려나? | Safe key decorated with a garnet.<br><br>A box given with its key. Is it okay to open it?<br>...Is it really okay? |
| 220705 | 시트린이 세공된 회중시계.<br><br>황색의 시트린은 밤에도 그 빛을 잃지 않는다.<br>그 때문에 어느 부족은 시트린은 아주 신성한 돌로 여겼다고 한다. | Pocket watch decorated with a topaz.<br><br>Yellow topaz does not lost its glow even at night.<br>Probably why some tribes thought of topaz as sacred stones. |
| 220706 | 시트린이 세공된 오르골.<br><br>어느 황제의 무덤에서 발견된 부장품. <br>수십 세기가 지났음에도 변치 않는 광택을 지니고 있다. 열쇠가 없으면 조작이 불가능하다. | Orgel decorated with a topaz.<br><br>Discovered in an emperor's tomb.<br>Its glow has not faded after several centuries. Needs a key to operate. |
| 220707 | 시트린이 세공된 접이거울. <br><br>모든 것을 보는 태양의 눈. <br>어둠 속에서도 빛을 잃지 않는 시선은 사물의 본질을 꿰뚫는다. | Folding mirror decorated with a topaz.<br><br>The eye of the sun to see all.<br>The sight of light penetrates the essence of items. |
| 220708 | 시트린이 세공된 열쇠.<br><br>부장품인 오르골을 기동하기 위한 열쇠. 사막의 한 유목민에 의해 발굴되었다. <br>오르골과 열쇠가 함께 묻히지 않은 이유는 아직도 수수께끼이다. | Key decorated with a topaz.<br><br>The key needed to operate the emperor's orgel. It was excavated by desert nomads.<br>It's still a mystery why they were not buried together. |
| 220709 | 사파이어가 세공된 모래시계.<br><br>시릴 만큼 푸른 물빛 액체가 벽을 타고 흘러내린다.<br>마치 이 세상의 물건이 아닌 듯한 신비로운 느낌이 든다. | Hourglass decorated with a sapphire.<br><br>The cold blue light of the sapphire flows down the walls.<br>It feels like something otherworldly. |
| 220710 | 사파이어가 세공된 스노우볼. <br><br>내부가 불투명한 사파이어 장식품. <br>신전을 그대로 옮겨놓은 듯한 고결한 외형이다. <br>유리 표면에 손을 대면 한기가 느껴진다. | Snow globe decorated with a sapphire.<br><br>An opaque sapphire ornament.<br>It looks like a temple made of sapphire.<br>It feels cold to the touch. |
| 220711 | 사파이어가 세공된 손거울.<br><br>거울에 비치는 여러 개의 상은 하늘과 지상을 연결하는 문이다. <br>이 성스러운 도구에는 어떠한 부정과 탐욕도 가까이할 수 없다고 한다. | Hand mirror decorated with a sapphire.<br><br>The many images shown in the mirror is the gateway between the heavens and below.<br>This holy relic cannot be held by those of evil and greed. |
| 220712 | 사파이어가 세공된 마법열쇠.<br><br>문이 존재한다면 열쇠도 존재하는 법. <br>다만 사용할 수 있는 건 단 한 명의 대현자뿐이라고 한다. | Magic key decorated with a sapphire.<br><br>A door must have a key.<br>This key, however, can only be used by a single sage of great wisdom. |
| 220801 | 튤립이 만개한 탁상시계.<br><br>갓 핀 사랑의 꽃봉오리에선 수줍은 향기가 난다.<br>사랑을 시작한 모든 이들의 마음이 담겨있다. | Table clock with blooming tulips.<br><br>Shy aroma emanates from the young flower of love.<br>It holds the heart of all those who just began their love. |
| 220802 | 튤립이 만개한 뮤직박스.<br><br>갓 만개한 튤립이 풋사랑을 노래하고 있다.<br>「첫사랑은 이루어지기 힘들대.<br>그러니까 나를 사랑하도록 해.」 | Music box with blooming tulips.<br><br>The blooming tulips sing on young love.<br>"First loves never come to be.<br>So love me." |
| 220803 | 튤립이 만개한 거울.<br><br>매일매일 누군가를 생각하지만<br>상대방에겐 좋아하는 이가 있는 듯하다. | Mirror with blooming tulips.<br><br>You think of someone everyday,<br>but they already have someone else in their mind. |
| 220804 | 튤립이 만개한 열쇠. <br><br>겨울에 심고 봄에 만개하는 꽃. <br>지금 당장 피어나지 않아도 괜찮다. <br>당신의 사랑이 보답받을 날이 오길. | Key with blooming tulips.<br><br>A flower that blooms in spring after the cold winter.<br>They need not bloom right now.<br>Your love will be returned someday. |
| 220805 | 찬란한 장미 꽃잎이 피어있는 회중시계.<br><br>뾰족한 시곗바늘이 마치 장미의 가시처럼 보인다.<br>누군가를 아주 오래 기다리고 있다. | Pocket watch with brilliant roses.<br><br>The sharp hands are like thorns of roses.<br>It has long awaited for someone. |
| 220806 | 찬란한 장미 꽃잎이 피어있는 오르골.<br><br>설령 다른 이름으로 불리게 되더라도 <br>그 향기에는 변함이 없겠지. | Orgel with brilliant roses.<br><br>Even if it's called a different name,<br>its fragrance will be unchanged. |
| 220807 | 찬란한 장미꽃잎이 피어있는 접이거울.<br><br>단잠에 빠진 아름다운 얼굴을 굽어보자 증오심이 끓어올랐다.<br>「나를 사랑에 빠지게 하다니,<br>그럼에도 아무도 사랑하지 않다니!」 | Folding mirror with brilliant roses.<br><br>Rage built up as you look upon the beautiful sleeping face.<br>"How dare you make me fall in love,<br>yet you love no one!" |
| 220808 | 찬란한 장미꽃잎이 피어있는 열쇠.<br><br>섣불리 만지면 살이 베일만큼 날카롭지만, <br>사실은 잠긴 문을 열어주길 바라고 있다. | Key with brilliant roses.<br><br>It's sharp enough to cut on touch,<br>but it desires for you to open the door. |
| 220809 | 새하얀 꽃잎을 머금은 모래시계.<br><br>마지막 모래가 전부 흘러내리자 여자는 모래시계를 다시 한번 뒤집었다.<br>그리고 그것을 몇 번이고 반복하였다. | Hourglass with snow white petals.<br><br>When the last of the sand trickled down, the woman flipped it again.<br>She did so again and again. |
| 220810 | 새하얀 꽃잎을 머금은 스노우볼.<br><br>연인을 잃은 여자의 눈물이 땅에 닿자, 그 자리에 찬란한 흰색의 꽃이 피어났다.<br>신은 이 꽃을 꺾어 구름의 뒤편에 장식해두었다. | Snow globe with snow white petals.<br><br>Radiant white flowers bloomed where the abandoned girl's tears soaked the ground.<br>God picked these flowers and hid them behind the clouds. |
| 220811 | 새하얀 꽃잎을 머금은 거울.<br><br>수면 위로 연인의 초상이 떠올랐다. <br>여자는 오랫동안 수면을 바라보았다.<br>그러자 똑같은 얼굴도 그녀를 바라보았다. | Mirror with snow white petals.<br><br>The face of her lover appeared on the surface.<br>She stared at the water for a long time.<br>And then the same face stared back at her. |
| 220812 | 새하얀 꽃잎을 머금은 마법열쇠.<br><br>상자에 심장을 담고 자물쇠를 걸었다.<br>열쇠는 곧 호수의 밑바닥으로 깊이 가라앉았다. | Magic key with snow white petals.<br><br>The heart was place in the box, then locked up.<br>The key sank to the bottom of the lake. |
| 220901 | 맛있는 빵과 과자로 만든 탁상시계.<br><br>시침은 금가루를 입힌 설탕공예 작품이다.<br>즉, 전부 먹을 수 있다! | Table clock made with bread and cookies.<br><br>The hands are made with melted sugar.<br>Meaning, all of it is edible! |
| 220902 | 맛있는 빵과 과자로 만든 뮤직박스.<br><br>도넛의 맛에 따라 다른 멜로디가 흐른다.<br>참고로, 손잡이도 먹을 수 있다. | Music box made with bread and cookies.<br><br>The flavor of the donut used determines the tune.<br>The handle is also edible. |
| 220903 | 맛있는 빵과 과자로 만든 탁상거울.<br><br>맛있어 보인다고 먹어버리면 안 된다.<br>아, 이미 먹어버렸군… | Table mirror made with bread and cookies.<br><br>Don't eat it because it looks tasty.<br>Oh, you already did... |
| 220904 | 맛있는 빵과 과자로 만든 열쇠.<br><br>열쇠의 기둥도 먹음직스러운 과자로 만들어져 있다.<br>…도넛 부분은 먹어도 괜찮지 않을까? | Key made with bread and cookies.<br><br>The stem is made with a delicious snack.<br>...The donut part should be okay to eat, right? |
| 220905 | 초콜릿과 쿠키로 장식한 시계.<br><br>귀와 발을 초콜릿에 퐁당 적신 곰 인형 회중시계.<br>동그란 눈과 초콜릿 색 작은 코가 앙증맞다. | Watch decorated with chocolate and cookies.<br><br>A teddy bear pocket watch with its ears and feat dipped in chocolate.<br>Its round eyes and small chocolate nose are adorable. |
| 220906 | 초콜릿과 쿠키로 장식한 쿠키 세트.<br><br>다채롭게 구성된 수제 초콜릿 쿠키. 뚜껑을 열자마자 고소하고 달콤한 향기가 퍼진다.<br>일단은 우정 쿠키라고 한다. 일단은. | Cookie Set decorated with chocolate and cookies.<br><br>Handmade assorted cookies. Sweet aroma fills the air as soon as you open it.<br>These are friendship cookies. For now. |
| 220907 | 초콜릿과 쿠키로 장식한 접이식 거울.<br><br>어느 세계에선 마음에 둔 상대에게 초콜릿을 주는 문화가 있다고 한다.<br>이 문화는 곧 유행처럼 퍼져 온 도시가 달콤한 향으로 가득 차게 되었다. | Folding mirror decorated with chocolate and cookies.<br><br>There used to be a tradition of giving chocolate to someone you fancy.<br>This tradition would soon fill an entire city with the aroma of chocolate. |
| 220908 | 초콜릿과 쿠키로 장식한 열쇠.<br><br>귀여운 고양이 모양의 쿠키 열쇠.<br>다른 쿠키를 굽고 남은 반죽으로 만들었지만, 꽤 마음에 드는 결과물이 나왔다. | Key decorated with chocolate and cookies.<br><br>Cute cat shaped cookie key.<br>It was made with left over dough, but it turned out to be pretty good. |
| 220909 | 알록달록한 색감의 모래시계.<br><br>색색의 별사탕이 알알이 쏟아져 내린다.<br>누군가를 기다리는 시간. 별사탕을 삼킨 듯 목구멍이 간지럽고 심장은 두근대고 있다. | Colorful hourglass.<br><br>Candies of various colors pour down.<br>The time spent waiting for someone. Your heart races as if you've just had a sweet candy. |
| 220910 | 알록달록한 색감의 스노우볼.<br><br>색색의 사탕들이 눈처럼 부유하고 있다.<br>진심이 담긴 선물에 대한 보답.<br>그 안에 담긴 건 우정일까? 아니면 사랑일까? | Colorful snow globe.<br><br>Candies of various colors float around like snowflakes.<br>Something in return for a sincere gift.<br>Is it filled with friendship? Or love? |
| 220911 | 알록달록한 색감의 손거울.<br><br>색색의 사탕으로 장식한 유리 거울에 수줍은 표정이 비친다. <br>어떤 표정을 하더라도 결코 속일 수 없는 마음이 있다. | Colorful hand mirror.<br><br>Mirror decorated with colorful candy reflects a shy face.<br>Some emotions cannot be hidden by facial expressions. |
| 220912 | 알록달록한 색감의 지팡이 모양 열쇠. <br><br>손 안의 온기에 녹아버리는 달콤한 사탕은, <br>고백에 대한 답변이라고 봐도 좋을 것이다. | Colorful cane shaped key.<br><br>The sweet candy melted by the warmth of the hand<br>is an answer to someone's question of love. |
| 221001 | 눈부시게 빛나는 다이아몬드 시계.<br>양쪽의 균형이 정확히 맞는 정교한 장식품.<br>부식되거나 길들지 않는 고고한 영원의 상징. | Radiant diamond clock.<br>A perfectly symmetrical decoration.<br>A symbol of eternity, untouched by corrosion nor tamed. |
| 221002 | 눈부시게 빛나는 다이아몬드 뮤직박스.<br><br>보석 꽃을 가공하여 만든 이 물건은, 서로의 마음이 일치해야만 움직인다는 소문이 있다. <br>연인이 영원을 맹세하기 전 마음을 확인하는 용도로 사용된다고 한다. | Radiant diamond music box.<br><br>This item made from jewel flowers is said to only operate when the minds connect.<br>It is used to check the commitment of others before they make the eternal vow. |
| 221003 | 눈부시게 빛나는 다이아몬드 거울.<br><br>상을 비추는 것은 유리가 아닌 다이아몬드이다.<br>그 정교한 세공력에 걸맞게, 평범한 이는 구경조차 할 수 없는 값어치를 지니고 있다. | Radiant diamond mirror.<br><br>The reflection is made by diamonds, not glass.<br>This level of craftsmanship calls for a price ordinary people can only imagine. |
| 221004 | 눈부시게 빛나는 다이아몬드 열쇠.<br><br>경이로울 정도로 정교한 열쇠 장식품. <br>고귀하고 희귀한 사랑의 가치. 아무도 찾지 않는 원석을 가공하자 눈부신 보석이 되었다. | Radiant diamond key.<br><br>Unimaginably detailed key ornament.<br>A noble token of love. An unwanted ore became a shining piece of jewelry after refinement. |
| 221005 | 소중한 기다림의 회중시계.<br><br>사랑하는 연인을 전쟁터에 떠나보낸 공주의 물건. <br>시침이 돌아가는 소리조차 심장을 저미는 그리움이 있었다. | Pocket watch of precious waiting.<br><br>Item of a princess who sent her loved one to war.<br>Every tick pulls at the yearning heart. |
| 221006 | 소중한 기다림의 오르골.<br><br>개선식의 성대한 음악이 울려 퍼지자, 거리는 꽃으로 뒤덮였다.<br>붉은 융단 위를 걸어오는 연인의 웃는 얼굴을 보았다. | Orgel of precious waiting.<br><br>When the trumpets sang, the street was filled with petals.<br>A couple smiled as they walked down the red carpet. |
| 221007 | 소중한 기다림의 거울.<br><br>이 문을 지나면 연인은 서로의 반려가 된다.<br>아득한 환호성과 눈 부신 빛 속에서 만백성이 그들의 행복을 빌었다. | Mirror of precious waiting.<br><br>Two lovers will become a couple once they pass this door.<br>The people celebrated their love with thunderous applause in the bright sunlight. |
| 221008 | 소중한 기다림의 열쇠.<br><br>작약으로 장식한 약속의 증표.<br>믿음은 영원히, 사랑은 무한히.<br>행복한 우리가 여기에 있다. | A key of precious waiting.<br><br>A token of promise decorated with peony.<br>Trust forever, love endlessly.<br>Our happiness is here. |
| 221009 | 베일에 감싸인 영원의 모래시계.<br><br>시간이라는 모래알이 바람의 실루엣을 타고 흘러내린다.<br>삶이 다할 때까지 함께할 수 있기를. | Hourglass of veiled eternity.<br><br>Sand of time flows down the path of the wind.<br>May you be together until your life is extinguished. |
| 221010 | 베일에 감싸인 영원의 스노우볼.<br><br>함께 있어야 완전해지는 사랑의 실루엣.<br>하나뿐이었던 날개는 둘이 되자 비로소 한 쌍의 날개가 되었다. | Snow globe of veiled eternity.<br><br>A silhouette completed only when there are two.<br>The wing became a pair once it met its match. |
| 221011 | 베일에 감싸인 영원의 거울.<br><br>진정한 인연을 약속하는 손거울.<br>거울이 영원히 빛나는 행복의 상을 비춘다. | Mirror of veiled eternity.<br><br>Hand mirror promising sincere bonds.<br>The mirror shines upon eternal happiness. |
| 221012 | 베일에 감싸인 영원의 열쇠.<br><br>맑은 종소리가 울려 퍼지는 영원의 증표. <br>손에 쥐는 순간 서로가 서로의 교리가 되었다.<br>「우리 영원을 믿기로 해.」 | Key of veiled eternity.<br><br>A token of eternity made in the clear rings of bells.<br>Once held, they each became the creed for the other.<br>"Our trust will be forever." |
| 221101 | 누군가의 소원을 품은 탁상시계.<br><br>광기에 사로잡힌 고대 왕의 애장품.<br>첨예한 시곗바늘이 끝의 도래를 알리고 있다. | A table clock that contains someone's precious wish.<br><br>Treasure that belonged to an ancient king tormented by madness.<br>The sharp hands of the clock indicate the end of times. |
| 221102 | 누군가의 소원을 품은 뮤직박스.<br><br>영리한 소녀가 왕에게 가로되,<br>그 흥미로운 설화에 왕은 곧장 빠져들고 말았다. | A music box that contains someone's precious wish.<br><br>A clever girl tells the king an interesting fable,<br>which captivates the king. |
| 221103 | 누군가의 소원을 품은 탁상거울.<br><br>왕을 배신한 죄로 처형당한 전 왕비의 유산.<br>화려하고 정교하지만 어쩐지 불길한 기운이 느껴진다. | A table mirror that contains someone's precious wish.<br><br>A legacy left behind by the previous queen who was executed for betraying the king.<br>It looks fancy and sophisticated, yet gives off an ominous energy. |
| 221104 | 누군가의 소원을 품은 금고열쇠.<br><br>태양이 뜰 때부터 시작된 이야기는<br>천 개의 달이 차고 기울 때까지 계속되었다. | A safe key that contains someone's precious wish.<br><br>The story that began ever since the first sunrise<br>continues on even after thousands of moonrises and moonsets. |
| 221105 | 누군가의 소원을 품은 회중시계.<br><br>혼돈의 바다 위에 핀 연꽃을 본떠 만든 시계. <br>마치 꽃잎이 호흡하듯 생명의 고동이 느껴진다. | A pocket watch that contains someone's precious wish.<br><br>Modeled after a lotus floating on top of the Sea of Chaos.<br>The petals beat softly as if they're breathing. |
| 221106 | 누군가의 소원을 품은 오르골.<br><br>터키석으로 만들어진 작은 장식품.<br>오래전 명계의 신에게 바쳐졌던 보물이다. | An orgel that contains someone's precious wish.<br><br>A small decorative piece made with turquoise.<br>It was once offered to a god in the underworld a very long time ago. |
| 221107 | 누군가의 소원을 품은 접이거울.<br><br>호수처럼 고요한 연꽃 모양의 거울.<br>꽃봉오리가 개화하며 열리고, 낙화와 함께 닫힌다. | A folding mirror that contains someone's precious wish.<br><br>It reminds you of a lotus found on top of a silent lake.<br>It opens up like a blooming flower, then closes like petals falling to the ground. |
| 221108 | 누군가의 소원을 품은 열쇠.<br><br>생명과 죽음, 불운과 행운의 상징.<br>지상과 지하를 잇는 명계의 문을 열 수 있다. | A key that contains someone's precious wish.<br><br>It symbolizes life and death, misfortune and luck.<br>It opens up a door to the underworld. |
| 221109 | 누군가의 소원을 품은 모래시계.<br><br>중앙에 새겨진 신의 눈이 은은히 빛나고 있다.<br>모든 거짓과 교만을 꿰뚫어 볼 수 있다. | An hourglass that contains someone's precious wish.<br><br>The eyes of the god carved in the center of it shine softly.<br>It can see right through all lies and arrogance. |
| 221110 | 누군가의 소원을 품은 스노우볼.<br><br>무한한 영광을 염원하는 마음을 담은 장식품.<br>혼탁을 정화한다는 설화가 있는 주구이다. | A snow globe that contains someone's precious wish.<br><br>A decorative piece that contains desires for infinite glory.<br>Legends say that it contains purifying powers. |
| 221111 | 누군가의 소원을 품은 손거울.<br><br>권위와 힘, 지혜의 상징.<br>예언의 거울이 나아갈 미래를 가리키고 있다. | A hand mirror that contains someone's precious wish.<br><br>It symbolizes authority, power, and wisdom.<br>The mirror of prophecy is reflecting the future. |
| 221112 | 누군가의 소원을 품은 마법열쇠.<br><br>기나긴 탈피를 끝마친 뱀 장식이 새겨진 열쇠.<br>치유와 영생을 바라는 고대 인류의 소망이 담겨있다. | A magic key that contains someone's precious wish.<br><br>A key decorated with patterns of a slithering snake.<br>It contains ancient civilization's hope for healing and eternal life. |
| 221201 | 춤추는 별들의 탁상시계<br><br>광기에 휩싸인 고대의 힘이 더욱 강렬한 기운을 뿜어낸다.<br>시곗바늘이 운명의 끝을 예고하며, 시간마저 삼킬 듯한 위용을 드러낸다. | Table Clock of Dancing Stars<br><br>The ancient power shrouded in madness surges with even greater force.<br>The clock's hands point to the fateful end of times, revealing a presence poised to consume time itself. |
| 221202 | 춤추는 별들의 뮤직박스<br><br>소녀의 이야기가 더욱 널리 퍼진다.<br>광기를 사로잡은 설화는 이제 듣는 모든 이를 깊은 환상 속으로 끌어들인다. | Music Box of Dancing Stars<br><br>The story of the little girl spreads even further.<br>The fable of madness now lures every listener into a deep illusion. |
| 221203 | 춤추는 별들의 탁상거울<br><br>사랑과 배신의 유산이 더욱 불길한 기운을 뿜어낸다.<br>화려한 장식 속에 숨겨진 그림자가 소원의 어두운 면모를 비춘다. | Table Mirror of Dancing Stars<br><br>The legacy of love and betrayal gives off an even more ominous energy.<br>Beneath the fancy adornments, a lurking shadow reflects the wish's darker side. |
| 221204 | 춤추는 별들의 금고열쇠<br><br>태양의 여명부터 천 개의 달이 기운 시간 속에서 이야기는 더욱 깊어져, 듣는 이는 얼마의 세월이 흘렀는지도 몰랐다. | Safe Key of Dancing Stars<br><br>From the dawn of the sun to the waning of a thousand moons, the tale wove itself ever deeper into the fabric of time, making the listener completely lose track of it. |
| 221205 | 춤추는 별들의 회중시계<br><br>혼돈 위에 핀 연꽃의 형상이 더욱 생생히 빛나는 시계. <br>생명의 고동이 강렬히 울리며, 마치 심장이 뛰듯 소원의 맥박을 전달한다. | Pocket Watch of Dancing Stars<br><br>The lotus blooming atop the Sea of Chaos glows more brilliantly than ever on this clock.<br>The fierce thrum of life delivers the pulse of a wish like a heartbeat. |
| 221206 | 춤추는 별들의 오르골<br><br>청록색 광채가 더욱 깊어진 장식품. <br>명계의 신에게 바쳐졌던 보물의 힘이 깨어나, 신비로운 선율로 영혼을 어루만진다. | Music Box of Dancing Stars<br><br>The teal shimmer of the ornament has deepened even more.<br>Once an offering to the god of the underworld, its power has awakened to soothe souls with a mystical melody. |
| 221207 | 춤추는 별들의 접이거울<br><br>호수의 고요함을 담은 연꽃이 더욱 찬란히 개화한다.<br>꽃봉오리의 열림과 닫힘이 운명의 흐름을 조율하며 소원을 비춘다. | Folding Mirror of Dancing Stars<br><br>Bearing the tranquil silence of the lake, the lotus blossoms even more radiantly.<br>Its petals open and close to guide the course of fate as it reflects the wish. |
| 221208 | 춤추는 별들의 열쇠<br><br>생명과 죽음, 불운과 행운의 상징이 더욱 강력해진 열쇠.<br>지상과 지하를 잇는 명계의 문을 여는 힘이 깊어져, 운명을 뒤바꾼다. | Key of Dancing Stars<br><br>This key symbolizes life and death, misfortune and luck even more powerfully.<br>With its power to open up a door to the underworld also enhanced, it can now change fate. |
| 221209 | 춤추는 별들의 모래시계<br><br>중앙에 새겨진 신의 눈이 더욱 강렬한 빛으로 타오른다.<br>모든 거짓과 교만을 꿰뚫는 힘을 강화하며 시간의 흐름마저 뒤바꾼다. | Hourglass of Dancing Stars<br><br>The eyes of the god, carved in the center, glow more intensely.<br>With its power to see through all lies and arrogance enhanced, it can now even alter the course of time. |
| 221210 | 춤추는 별들의 스노우볼<br><br>무한한 영광을 염원하는 마음이 더욱 강렬히 빛나는 장식품. 혼탁을 정화하는 이야기가 깊은 울림으로 현실이 되며, 순수한 빛으로 주위를 감싼다. | Snow Globe of Dancing Stars<br><br>The desires for infinite glory glow more intensely in this decorative piece. The legend of purifying chaos becomes reality with its deep resonance, enveloping its surroundings with pure light. |
| 221211 | 춤추는 별들의 손거울<br><br>권위와 힘, 지혜의 기운이 더욱 강력해진 거울. <br>예언의 빛이 미래의 길을 더욱 선명히 비추며, 운명의 방향을 제시한다. | Hand Mirror of Dancing Stars<br><br>The energy of authority, power, and wisdom has become even stronger in this mirror.<br>The light of prophecy shines on the path of the future even more brightly, guiding the direction of fate. |
| 221212 | 춤추는 별들의 마법열쇠<br><br>기나긴 탈피를 마친 뱀 장식이 더욱 생생히 꿈틀거리는 열쇠. 치유와 영생을 바라는 고대 인류의 소망이 강력한 마력으로 응집되어, 생명의 문을 연다. | Magic Key of Dancing Stars<br><br>The snake, finally molted, is slithering even more vividly on this key. The ancient civilization's hope for healing and eternal life has condensed into powerful mana, opening the gate of life. |
| 221301 | 월광을 머금은 탁상시계<br><br>영원한 광기의 현물.<br>시곗바늘은 이제 종말의 순간을 넘어 새로운 시작을 알리며, 영원한 소망을 시간의 경계 너머로 이끈다. | Moonlit Table Clock<br><br>A manifestation of eternal madness.<br>The clock hands point to a new start beyond the moment of the end, guiding the eternal wish across the bounds of time. |
| 221302 | 월광을 머금은 뮤직박스<br><br>무한으로 흘러드는 이야기가 흐른다.그 신비로움은 광기를 넘어 세상의 모든 영혼을 매혹하며, 영원한 환상 속에 살게 한다. | Moonlit Music Box<br><br>The story flows into infinity. Its mysticism surpasses the madness and charms all souls in the world, letting them settle into an eternal illusion. |
| 221303 | 월광을 머금은 탁상거울<br><br>영원한 사랑이 저주의 기운으로 변한 유산.<br>광기를 사랑한 여인의 기운이 영원히 비명을 지르고 있다. | Moonlit Table Mirror<br><br>A legacy of eternal love turned into a curse.<br>The essence of a woman who loved madness is screaming forever. |
| 221304 | 월광을 머금은 금고열쇠<br><br>영겁의 이야기가 소망을 완성하며, 그 찬란한 빚은 영원히 지지 않는다. | Moonlit Safe Key<br><br>The story of eons fulfills the wish, and its radiant light will never fade. |
| 221305 | 월광을 머금은 회중시계<br><br>연꽃이 무한한 빛으로 물들어 혼돈을 초월한 시계. <br>생명의 고동은 이제 우주의 리듬과 조화를 이루며, 소원을 실현하는 시간을 새긴다. | Moonlit Pocket Watch<br><br>The lotus is infused with infinite light, transcending even chaos.<br>The pulse of life now harmonizes with the rhythm of the universe, carving the time for the wish to be fulfilled. |
| 221306 | 월광을 머금은 오르골<br><br>명계의 빛을 품은 장식품.신에게 바쳐진 보물의 힘은 이제 영원을 초월한 영감을 부여한다. | Moonlit Music Box<br><br>A decorative piece containing the light of the underworld. The power of this treasure offered to a god now inspires beyond eternity. |
| 221307 | 월광을 머금은 접이거울<br><br>신성한 빛으로 피어나는 거울. <br>개화와 낙화가 운명을 흔들며, 일렁이는 호수의 표면은 미래를 비춘다. | Moonlit Folding Mirror<br>This mirror blooms in sacred light.<br><br>The opening and closing of its petals shake fate, and the rippling lake surface reflects the future. |
| 221308 | 월광을 머금은 열쇠<br><br>생명과 죽음의 상징 명계의 문을 완전히 지배한다. <br>삶과 죽음의 흐름을 이끌며, 영원한 소망으로 안내한다. | Moonlit Key<br><br>As a symbol of life and death, it completely dominates the gate of the underworld.<br>It directs the course of life and death, guiding it to an eternal wish. |
| 221309 | 월광을 머금은 모래시계<br><br>신의 눈이 영원의 빛으로 물들어, 모든 거짓과 교만을 초월하는 절대적인 통찰을 선사하며, 영원에 한 걸음 더 다가선다. | Moonlit Hourglass<br><br>The eyes of the god are infused with the light of eternity, offering absolute insight surpassing all lies and arrogance, bringing you one step closer to eternity. |
| 221310 | 월광을 머금은 스노우볼<br><br>신비롭고도 장엄한 힘으로 혼탁을 완전히 소멸시키는 신성한 빛을 발한다. <br>영원한 순수함이 세상을 정화하며 영광을 약속한다. | Moonlit Snow Globe<br><br>Emanates sacred light that totally obliterates chaos with a mystical, sublime power.<br>An eternal innocence purifies the world and promises glory. |
| 221311 | 월광을 머금은 손거울<br><br>절대적인 권위와 지혜의 현물.<br>예언의 힘으로 미래를 재편한다. 운명의 흐름을 손에 쥐고 소망을 실현한다. | Moonlit Hand Mirror<br><br>A manifestation of absolute authority and wisdom.<br>Reconstructs the future with the power of prophecy. With the course of fate in its grasp, it fulfills the wish. |
| 221312 | 월광을 머금은 마법열쇠<br><br>무한한 생명을 상징하며 빛나는 이 열쇠는 치유와 영생의 힘을 극대화한다. <br>고대의 소원을 초월해 불멸의 문을 여는 궁극의 마법을 품고 있다. | Moonlit Magic Key<br><br>Glowing in its representation of infinite life, this key maximizes the power of healing and eternal life.<br>Harbors the ultimate magic that can open the gate to immortality, surpassing the ancient wish. |
| 221401 | 천일의 빛을 품은 탁상시계<br><br>긴 기다림 끝에 피어난 시간의 문장.<br>시곗바늘은 어둠을 벗고 새벽의 숨결을 받아, 운명의 흐름을 다시 쓰기 시작한다. | Table Clock of a Thousand Days of Light<br><br>After a long, tedious wait, the crest of time blooms into being.<br>The hands of the clock escape the shadows, take in dawn's gentle breath, and set about reshaping fate's current. |
| 221402 | 천일의 빛을 품은 뮤직박스<br><br>끝없는 선율이 맑은 기적처럼 흘러든다.<br>그 신비로운 울림은 영혼을 감싸며, 수많은 이야기를 새로운 빛으로 되살린다. | Music Box of a Thousand Days of Light<br><br>An endless melody flows in like a radiant miracle.<br>Its ethereal echo envelops the soul and rekindles countless tales with fresh light. |
| 221403 | 천일의 빛을 품은 탁상거울<br><br>빛에 물든 거울 속에는 잊힌 그리움이 여전히 숨 쉬며, 주인을 기다린다. | Table Mirror of a Thousand Days of Light<br><br>Forgotten longing still stirs within the light-touched mirror, waiting for its master. |
| 221404 | 천일의 빛을 품은 금고열쇠<br><br>잠들어 있던 소망은 광휘 아래 완성되어, 세상에 다시 발을 내딛는다. | Safe Key of a Thousand Days of Light<br><br>The long-dormant wish awakens in the light and steps into the world once more. |
| 221405 | 천일의 빛을 품은 회중시계<br><br>빛의 심장은 혼돈을 정화하며, 소망의 순간을 영원 속에 기록한다. | Pocket Watch of a Thousand Days of Light<br><br>The heart of light cleanses the chaos and etches the wish's moment into eternity. |
| 221406 | 천일의 빛을 품은 오르골<br><br>신에게 닿던 그 울림은 이제 영원한 영감을 부여하며, 잊힌 꿈들을 일깨운다. | Orgel of a Thousand Days of Light<br><br>The resonance that once reached the divine now grants endless inspiration, awakening forgotten dreams. |
| 221407 | 천일의 빛을 품은 접이거울<br><br>흔들리는 운명과 흐르는 시간을 담고, 새로운 길을 비춘다. | Folding Mirror of a Thousand Days of Light<br><br>Harboring shifting destinies and the passage of time, it illuminates a new path. |
| 221408 | 천일의 빛을 품은 열쇠<br><br>삶과 죽음의 파동을 조율하며, 영원의 문 너머로 나아간다. | Key of a Thousand Days of Light<br><br>Guiding the tides of life and death, it opens the way to step beyond the gate of eternity. |
| 221409 | 천일의 빛을 품은 모래시계<br><br>빛에 물든 모래는 거짓을 비추고 진실을 드러내며, 영원으로 나아가는 길을 제시한다. | Hourglass of a Thousand Days of Light<br><br>The light-touched sand shines upon falsehood and unveils truth, guiding the way to eternity. |
| 221410 | 천일의 빛을 품은 스노우볼<br><br>세상의 혼탁을 맑게 씻어내는 순백의 광휘.<br>천일의 기적은 어둠을 가르고, 깨끗한 미래를 약속한다. | Snow Globe of a Thousand Days of Light<br><br>A pure white light that cleanses the filth of chaos in the world.<br>The miracle of a thousand days cuts through the darkness, promising an unspoiled future. |
| 221411 | 천일의 빛을 품은 손거울<br><br>예언의 흔적은 거울의 끝에서 피어오르며, 운명을 새롭게 엮어 나간다. | Hand Mirror of a Thousand Days of Light<br><br>The traces of a prophecy spill from the tip of the mirror, weaving new fates. |
| 221412 | 천일의 빛을 품은 마법열쇠<br><br>고대의 마법은 천일의 빛과 함께 부활해, 불멸로 향하는 길을 열어 준다. | Magic Key of a Thousand Days of Light<br><br>Ancient magic awakens in the thousand-day light, opening the way to immortality. |
| 221501 | [(힘/오리진+5/시계)예장의 설명문] |  |
| 221502 | [(힘/오리진+5/오르골)예장의 설명문] |  |
| 221503 | [(힘/오리진+5/거울)예장의 설명문] |  |
| 221504 | [(힘/오리진+5/열쇠)예장의 설명문] |  |
| 221505 | [(민첩/오리진+5/시계)예장의 설명문] |  |
| 221506 | [(민첩/오리진+5/오르골)예장의 설명문] |  |
| 221507 | [(민첩/오리진+5/거울)예장의 설명문] |  |
| 221508 | [(민첩/오리진+5/열쇠)예장의 설명문] |  |
| 221509 | [(지능/오리진+5/시계)예장의 설명문] |  |
| 221510 | [(지능/오리진+5/오르골)예장의 설명문] |  |
| 221511 | [(지능/오리진+5/거울)예장의 설명문] |  |
| 221512 | [(지능/오리진+5/열쇠)예장의 설명문] |  |
| 221901 | ('초월', '강화 재료로 사용' 불가)<br><br>1주년을 기념하는 회중시계.<br><br>파티 시작 20분 전. 살짝 늦게 도착하더라도 문제없다.<br>오늘의 주인공은 바로 당신이니까! | (Can't be used as an enhancing or transcending material)<br><br>A commemorative pocket watch for the 1st Anniversary.<br><br>There's twenty minutes left until the party, but it's fine to be fashionably late.<br>You're the guest of honor, after all! |
| 221902 | ('초월', '강화 재료로 사용' 불가)<br><br>1주년을 기념하는 오르골.<br><br>파티의 대미를 장식할 기념 케이크.<br>풍선과 콘페티가 흩날리는 화려한 파티장 안, 각자의 내일이 별처럼 빛나고 있다. | (Can't be used as an enhancing or transcending material)<br><br>A commemorative music box for the 1st Anniversary.<br><br>Fashioned as a cake to mark the climax of the party.<br>Surrounded by the spectacle of balloons and confetti in the party hall, everyone's future shines brightly like a star. |
| 221903 | ('초월', '강화 재료로 사용' 불가)<br><br>1주년을 기념하는 접이거울.<br><br>언제 어디든 옷매무새를 체크할 수 있는 거울. 특별한 날을 맞이해 잔뜩 차려입은 당신을 비추고 있다.<br>목깃을 장식하는 리본이 풀리지 않게 꽉 묶고, 한 걸음 내디뎌보자. | (Can't be used as an enhancing or transcending material)<br><br>A commemorative folding mirror for the 1st Anniversary.<br><br>With this mirror, you can check your appearance anytime, anywhere. It shows you in your finest attire, ready for a special occasion.<br>Make sure your bowtie is securely fixed, then take a step forward. |
| 221904 | ('초월', '강화 재료로 사용' 불가)<br><br>1주년을 기념하는 만능열쇠<br><br>말하지 않아도 전해지는 마음이 있다.<br>당신의 사랑이 있었기에 모두가 여기에 있는 것처럼.<br>앞으로도 계속 함께야! | (Can't be used as an enhancing or transcending material)<br><br>A commemorative master key for the 1st Anniversary.<br><br>Words aren't always needed to express deep feelings.<br>Like how your love has brought us all here.<br>We'll always be together forever! |
| 221905 | ('초월', '강화 재료로 사용' 불가)<br><br>흑기사가 사용했다는 투구.<br><br>흑기사의 침공을 막아내지 못했다면 어땠을까?<br>거짓말 같은 이야기가 다른 세계에선 이루어졌을지도.<br>상상만으로 식은땀이 흐른다. | (Can't be used as an enhancing or transcending material)<br><br>The Dark Knight's old helmet.<br><br>What would have happened if we had failed to stop the Dark Knight's invasion?<br>Unspeakable events may have unfolded in an alternate reality.<br>The mere thought of that happening chills to the bone. |
| 221906 | ('초월', '강화 재료로 사용' 불가)<br><br>1.5주년을 기념하는 모래시계.<br><br>비밀스러운 코르사주로 장식된 모래시계.<br>보랏빛 꽃장식은 아찔하고 달콤한 사랑의 증명. | (Can't be used as an enhancing or transcending material)<br><br>A commemorative hourglass for the 1.5-Year Anniversary.<br><br>Adorned with a subtle corsage.<br>The purple floral embellishment is a heady, sweet testament to love. |
| 221907 | ('초월', '강화 재료로 사용' 불가)<br><br>1.5주년을 기념하는 스노우볼.<br><br>영원을 약속하는 스노우볼.<br>당신과 신부를 닮은 인형이 언제까지고 서로를 바라보고 있다. | (Can't be used as an enhancing or transcending material)<br><br>A commemorative snow globe for the 1.5-Year Anniversary.<br><br>Symbolizes a commitment for eternity.<br>Figurines resembling you and your bride gaze into each other's eyes forever. |
| 221908 | ('초월', '강화 재료로 사용' 불가)<br><br>1.5주년을 기념하는 손거울.<br><br>결혼식 단상 위, 부케를 들고 당신을 기다리는 신부의 모습이 보인다.<br>영원히 깨지지 않을 맹세의 입맞춤을 선물하자. | (Can't be used as an enhancing or transcending material)<br><br>A commemorative hand mirror for the 1.5-Year Anniversary.<br><br>The bride with her bouquet waiting for you can be seen on top of the wedding altar.<br>Offer her a kiss for an eternal vow that will never shatter. |
| 221909 | ('초월', '강화 재료로 사용' 불가)<br><br>1.5주년을 기념하는 마법열쇠.<br><br>심장을 닮은 보석이 마치 꺼지지 않는 불꽃처럼 온기를 채워주고 있다.<br>사막의 더위도 설산의 추위도, 당신과 함께라면 두렵지 않다. | (Can't be used as an enhancing or transcending material)<br><br>A commemorative magic key for the 1.5-Year Anniversary.<br><br>A heart-like gem radiates warmth like an everlasting flame.<br>Together, we can brave the desert's heat or the snowy mountain's frost without fear. |
| 221910 | ('초월', '강화 재료로 사용' 불가)<br><br>특수한 재질의 강화 아머.<br>빛 한 점 들지 않는 심연에서도, 시릴 정도로 따스한 푸른 꽃이 피었다. | (Can't be used as an enhancing or transcending material)<br><br>Reinforced armor made from rare material.<br>Even in the pitch-black abyss, a blue flower blooms, exuding a chill that feels oddly warm. |
| 221911 | ('초월', '강화 재료로 사용' 불가)<br><br>특수한 재질의 기동형 기체.<br>드넓은 우주를 마치 유성처럼 유영한다.<br>당신을 만나기 위해, 아득한 별의 바다를 넘어서. | (Can't be used as an enhancing or transcending material)<br><br>A mobile unit made from rare material.<br>It traverses the vast expanse of space like a meteor.<br>It journeyed across the distant sea of stars to meet you. |
| 221912 | ('초월', '강화 재료로 사용' 불가)<br><br>특수한 재질의 강화 장갑.<br>오랜 시간이 지나 다시 맞잡은 손에서 느껴지는 것은,<br>한 번도 잊어본 적 없는 따스한 약속의 온기이다. | (Can't be used as an enhancing or transcending material)<br><br>Reinforced gloves made from rare material.<br>The warmth felt in the hands clasped once more after years apart<br>is the enduring memory of a promise never forgotten. |
| 221913 | ('초월', '강화 재료로 사용' 불가)<br><br>특수한 재질의 센서 모듈.<br>아무리 멀리 있어도 당신의 기척을 선명하게 느낄 수 있다. | (Can't be used as an enhancing or transcending material)<br><br>A sensor module made from rare material.<br>No matter how far, your presence can be clearly felt. |
| 221914 | 2.5주년을 기념하는 팬던트<br>파스텔빛 조개와 소라가 달린 팬던트.<br>팬던트에 귀를 기울이면, 우리의 추억이 파도 소리처럼 밀려온다. | A pendant celebrating the 2.5-year anniversary.<br>Adorned with a pastel-colored seashell and a piece of coral.<br>Held close to your ear, our fond memories wash over you like the tide. |
| 221915 | 2.5주년을 기념하는 팔찌<br>꽃과 장식이 달린 귀여운 팔찌.<br>비록 작은 액세서리지만, 당신에게 보여지는 모든 것 중 어느 하나도 허투루 고른 것은 없다. | A bracelet celebrating the 2.5-year anniversary.<br>An adorable bracelet strung together with flowers and beads.<br>It may be small, but everything shown to you was picked with care. |
| 221916 | 2.5주년을 기념하는 구두<br>로맨틱하게 만발한 꽃들로 장식된 구두.<br>모든 파티 준비를 마쳤으니, 남은 건 당신에게 한 발짝 다가가는 것뿐. | A pair of sandals celebrating the 2.5-year anniversary.<br>Adorned with romantic blossoms.<br>Everything's set for the party. All that's left is to take that one step closer to you. |
| 221917 | 2.5주년을 기념하는 스파클링.<br>당신이 우리와 처음으로 만난 날을 기념하며. 치어스! | Sparkling wine celebrating the 2.5-year anniversary.<br>Let's toast to the day we first met. Cheers! |
| 221918 | 1000일을 기념하며 캐서린이 준비한 브로치.<br>캐서린이 무대에 오를 때 착용한 브로치와 똑같다.<br>개성있는 디자인으로 당신의 마음을 사로잡을 것이다. | A brooch Catherine has prepared in celebration of the 1,000th day.<br>It is identical to the one she wore on the stage.<br>The unique design will surely captivate your heart. |
| 221919 | 1000일을 기념하며 캐서린이 준비한 오너먼트.<br>어딘가에 달려있던 장식이 빛을 받아<br>눈부시게 반짝거린다.<br>마치 누군가의 꿈과 희망처럼. | An ornament Catherine has prepared in celebration of the 1,000th day.<br>Catching the light,<br>the dangling trinket dazzles brightly.<br>Like someone's dreams and hopes. |
| 221920 | 1000일을 기념하며 벨레드가 준비한 헤어리본.<br>예쁜 장식이 달려있는 헤어핀에서 정성이 느껴진다.<br>누군가를 생각하는 마음은 이렇게나 아름다운 거구나. | A hair bow prepared by Beleth in celebration of the 1,000th day.<br>The delicately decorated hair barrette shows her thoughtful care.<br>So beautiful is the heart when it tends to someone. |
| 221921 | 1000일을 기념하며 아키가 준비한 가터링.<br>고급스러운 가죽 재질의 가터링이 빛을 받아 반짝인다.<br>보기만 해도 무대에 대한 동경이 생기는 것 같다. | A garter ring prepared by Aki in celebration of the 1,000th day.<br>A fine leather garter ring shines under the light.<br>Just looking at it inspires a dream of the stage. |
| 221922 | ('초월', '강화 재료로 사용' 불가)<br><br>3주년을 기념하는 푸른 동백꽃.<br><br>꽃말이 '누구보다 그대를 사랑합니다'인 걸로 보아, 당신에게 이 간절한 마음을 전하고 싶은 이가 있는 모양이다. | (Can't be used as an enhancing or transcending material)<br><br>A blue camellia flower commemorating the 3rd anniversary.<br><br>With its message of "I love you more than anyone," it seems that someone wishes to share their earnest feelings with you. |
| 221923 | ('초월', '강화 재료로 사용' 불가)<br><br>3주년을 기념하는 노리개.<br><br>누군가가 아주 정성스럽게 만든 듯한 모양새다.<br>누구에게 전해주기 위한 정성 어린 마음이었을까? | (Can't be used as an enhancing or transcending material)<br><br>A charm commemorating the 3rd anniversary.<br><br>It seems to have been crafted with utter devotion.<br>Perhaps it holds heartfelt feelings meant for someone special. |
| 221924 | ('초월', '강화 재료로 사용' 불가)<br><br>3주년을 기념하는 비녀.<br><br>고급스러운 금빛으로 반짝거린다.<br>당신에게 예쁘게 보이고 싶은 누군가의 마음이 느껴진다. | (Can't be used as an enhancing or transcending material)<br><br>A hairpin commemorating the 3rd anniversary.<br><br>Glimmers in a refined golden sheen.<br>You can sense someone's desire to look beautiful in your eyes. |
| 221925 | ('초월', '강화 재료로 사용' 불가)<br><br>3주년을 기념하는 종이부채.<br><br>차분한 톤의 자연물이 그려진 종이 부채를 보고 있으면 마음이 편안해지는 것 같다.<br>언제까지나 이 평화가 이어지기를. | (Can't be used as an enhancing or transcending material)<br><br>A paper fan commemorating the 3rd anniversary.<br><br>Gazing upon this paper fan, adorned with a serene painting of nature, brings a sense of calm.<br>May this peace last forever. |
| 223001 | 즉시 자동 사냥 2시간의 골드를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold worth 2 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223002 | 즉시 자동 사냥 6시간의 골드를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold worth 6 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223003 | 즉시 자동 사냥 12시간의 골드를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold worth 12 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223004 | 즉시 자동 사냥 24시간의 골드를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold worth 24 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223005 | 즉시 자동 사냥 48시간의 골드를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold worth 48 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223006 | 즉시 자동 사냥 2시간의 마나 더스트를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Dust worth 2 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223007 | 즉시 자동 사냥 6시간의 마나 더스트를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Dust worth 6 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223008 | 즉시 자동 사냥 12시간의 마나 더스트를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Dust worth 12 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223009 | 즉시 자동 사냥 24시간의 마나 더스트를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Dust worth 24 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223010 | 즉시 자동 사냥 48시간의 마나 더스트를 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Dust worth 48 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223011 | 즉시 자동 사냥 2시간의 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Crystal worth 2 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223012 | 즉시 자동 사냥 6시간의 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Crystal worth 6 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223013 | 즉시 자동 사냥 12시간의 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Crystal worth 12 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223014 | 즉시 자동 사냥 24시간의 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Crystal worth 24 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223015 | 즉시 자동 사냥 48시간의 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Mana Crystal worth 48 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223021 | 즉시 자동 사냥 2시간의 골드, 마나 더스트, 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold, Mana Dust, and Mana Crystal worth 2 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223022 | 즉시 자동 사냥 6시간의 골드, 마나 더스트, 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold, Mana Dust, and Mana Crystal worth 6 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223023 | 즉시 자동 사냥 12시간의 골드, 마나 더스트, 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold, Mana Dust, and Mana Crystal worth 12 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223024 | 즉시 자동 사냥 24시간의 골드, 마나 더스트, 마나 크리스탈을 획득한다.<br>(시간 재화는 버프를 적용하지 않습니다.) | Immediately obtain Gold, Mana Dust, and Mana Crystal worth 24 hours of auto-hunting.<br>(Currency increase buffs not applied.) |
| 223101 | 파편 60개 수집시 레어 정령 아이린 소환 가능 | Collect 60 fragments to summon Rare Soul Irene. |
| 223102 | 파편 60개 수집시 레어 정령 캐니 소환 가능 | Collect 60 fragments to summon Rare Soul Canney. |
| 223103 | 파편 60개 수집시 레어 정령 픽시 소환 가능 | Collect 60 fragments to summon Rare Soul Pixie. |
| 223104 | 파편 60개 수집시 레어 정령 캐스퍼 소환 가능 | Collect 60 fragments to summon Rare Soul Casper. |
| 223201 | 파편 60개 수집시 레어 정령 리타 소환 가능 | Collect 60 fragments to summon Rare Soul Rita. |
| 223202 | 파편 60개 수집시 레어 정령 로제 소환 가능 | Collect 60 fragments to summon Rare Soul Rose. |
| 223203 | 파편 60개 수집시 레어 정령 샤링 소환 가능 | Collect 60 fragments to summon Rare Soul Sharinne. |
| 223204 | 파편 60개 수집시 레어 정령 루리 소환 가능 | Collect 60 fragments to summon Rare Soul Ruri. |
| 223205 | 파편 60개 수집시 레어 정령 알리샤 소환 가능 | Collect 60 fragments to summon Rare Soul Alisha. |
| 223206 | 파편 60개 수집시 레어 정령 르웨인 소환 가능 | Collect 60 fragments to summon Rare Soul Lewayne. |
| 223207 | 파편 60개 수집시 레어 정령 무명 소환 가능 | Collect 60 fragments to summon Rare Soul Nameless. |
| 223208 | 파편 60개 수집시 레어 정령 카렌 소환 가능 | Collect 60 fragments to summon Rare Soul Karen. |
| 223301 | 파편 60개 수집시 에픽 정령 메피스토펠레스 소환 가능 | Collect 60 fragments to summon Epic Soul Mephistopheles. |
| 223302 | 파편 60개 수집시 에픽 정령 벨레드 소환 가능 | Collect 60 fragments to summon Epic Soul Beleth. |
| 223303 | 파편 60개 수집시 에픽 정령 클레르 소환 가능 | Collect 60 fragments to summon Epic Soul Claire. |
| 223304 | 파편 60개 수집시 에픽 정령 아키 소환 가능 | Collect 60 fragments to summon Epic Soul Aki. |
| 223305 | 파편 60개 수집시 에픽 정령 제이드 소환 가능 | Collect 60 fragments to summon Epic Soul Jade. |
| 223306 | 파편 60개 수집시 에픽 정령 린지 소환 가능 | Collect 60 fragments to summon Epic Soul Linzy. |
| 223307 | 파편 60개 수집시 에픽 정령 홍란 소환 가능 | Collect 60 fragments to summon Epic Soul Honglan. |
| 223308 | 파편 60개 수집시 에픽 정령 순이 소환 가능 | Collect 60 fragments to summon Epic Soul Soonie. |
| 223309 | 파편 60개 수집시 에픽 정령 아이라 소환 가능 | Collect 60 fragments to summon Epic Soul Aira. |
| 223310 | 파편 60개 수집시 에픽 정령 시하 소환 가능 | Collect 60 fragments to summon Epic Soul Seeha. |
| 223311 | 파편 60개 수집시 에픽 정령 미카 소환 가능 | Collect 60 fragments to summon Epic Soul Mica. |
| 223312 | 파편 60개 수집시 에픽 정령 에리카 소환 가능 | Collect 60 fragments to summon Epic Soul Erika. |
| 223313 | 파편 60개 수집시 에픽 정령 이나 소환 가능 | Collect 60 fragments to summon Epic Soul Ina. |
| 223314 | 파편 60개 수집시 에픽 정령 르네 소환 가능 | Collect 60 fragments to summon Epic Soul Renee. |
| 223315 | 파편 60개 수집시 에픽 정령 탈리아 소환 가능 | Collect 60 fragments to summon Epic Soul Talia. |
| 223316 | 파편 60개 수집시 에픽 정령 칸나 소환 가능 | Collect 60 fragments to summon Epic Soul Kanna. |
| 223317 | 파편 60개 수집시 에픽 정령 이디스 소환 가능 | Collect 60 fragments to summon Epic Soul Edith. |
| 223318 | 파편 60개 수집시 에픽 정령 비올레트 소환 가능 | Collect 60 fragments to summon Epic Soul Violette. |
| 223319 | 파편 60개 수집시 에픽 정령 가넷 소환 가능 | Collect 60 fragments to summon Epic Soul Garnet. |
| 223320 | 파편 60개 수집시 에픽 정령 레베카 소환 가능 | Collect 60 fragments to summon Epic Soul Rebecca. |
| 223321 | 파편 60개 수집시 에픽 정령 멜피스 소환 가능 | Collect 60 fragments to summon Epic Soul Melfice. |
| 223322 | 파편 60개 수집시 에픽 정령 브라이스 소환 가능 | Collect 60 fragments to summon Epic Soul Bryce. |
| 223323 | 파편 60개 수집시 에픽 정령 프림 소환 가능 | Collect 60 fragments to summon Epic Soul Prim. |
| 223324 | 파편 60개 수집시 에픽 정령 클라우디아 소환 가능 | Collect 60 fragments to summon Epic Soul Claudia. |
| 223325 | 파편 60개 수집시 에픽 정령 헬레나 소환 가능 | Collect 60 fragments to summon Epic Soul Helena. |
| 223326 | 파편 60개 수집시 에픽 정령 벨라나 소환 가능 | Collect 60 fragments to summon Epic Soul Velanna. |
| 223327 | 파편 60개 수집시 에픽 정령 아야메 소환 가능 | Collect 60 fragments to summon Epic Soul Ayame. |
| 223328 | 파편 60개 수집시 에픽 정령 재클린 소환 가능 | Collect 60 fragments to summon Epic Soul Jacqueline. |
| 223329 | 파편 60개 수집시 에픽 정령 나오미 소환 가능 | Collect 60 fragments to summon Epic Soul Naomi. |
| 223330 | 파편 60개 수집시 에픽 정령 조앤 소환 가능 | Collect 60 fragments to summon Epic Soul Joanne. |
| 223331 | 파편 60개 수집시 에픽 정령 메릴 소환 가능 | Collect 60 fragments to summon Epic Soul Meryl. |
| 223332 | 파편 60개 수집시 에픽 정령 플린 소환 가능 | Collect 60 fragments to summon Epic Soul Flynn. |
| 223333 | 파편 60개 수집시 에픽 정령 타샤 소환 가능 | Collect 60 fragments to summon Epic Soul Tasha. |
| 223334 | 파편 60개 수집시 에픽 정령 니콜 소환 가능 | Collect 60 fragments to summon Epic Soul Nicole. |
| 223335 | 파편 60개 수집시 에픽 정령 비비안 소환 가능 | Collect 60 fragments to summon Epic Soul Vivienne. |
| 223336 | 파편 60개 수집시 에픽 정령 아드리안 소환 가능 | Collect 60 fragments to summon Epic Soul Adrianne. |
| 223337 | 파편 60개 수집시 에픽 정령 사논 소환 가능 | Collect 60 fragments to summon Epic Soul Sanon. |
| 223338 | 파편 60개 수집시 에픽 정령 리젤로테 소환 가능 | Collect 60 fragments to summon Epic Soul Lizelotte. |
| 223339 | 파편 60개 수집시 에픽 정령 캐서린 소환 가능 | Collect 60 fragments to summon Epic Soul Catherine. |
| 223340 | 파편 60개 수집시 에픽 정령 셰리 소환 가능 | Collect 60 fragments to summon Epic Soul Cherrie. |
| 223341 | 파편 60개 수집시 에픽 정령 도라 소환 가능 | Collect 60 fragments to summon Epic Soul Dora. |
| 223342 | 파편 60개 수집시 에픽 정령 하루 소환 가능 | Collect 60 fragments to summon Epic Soul Haru. |
| 223343 | 파편 60개 수집시 에픽 정령 루테 소환 가능 | Collect 60 fragments to summon Epic Soul Lute. |
| 223344 | 파편 60개 수집시 에픽 정령 클라라 소환 가능 | Collect 60 fragments to summon Epic Soul Clara. |
| 223345 | 파편 60개 수집시 에픽 정령 미리암 소환 가능 | Collect 60 fragments to summon Epic Soul Miriam. |
| 223346 | 파편 60개 수집시 에픽 정령 클로이 소환 가능 | Collect 60 fragments to summon Epic Soul Chloe. |
| 223347 | 파편 60개 수집시 에픽 정령 나이아 소환 가능 | Collect 60 fragments to summon Epic Soul Naiah. |
| 223348 | 파편 60개 수집시 에픽 정령 에루샤 소환 가능 | Collect 60 fragments to summon Epic Soul Erusha. |
| 223349 | 파편 60개 수집시 에픽 정령 페트라 소환 가능 | Collect 60 fragments to summon Epic Soul Petra. |
| 223350 | 파편 60개 수집시 에픽 정령 니니 소환 가능 | Collect 60 fragments to summon Epic Soul Nini. |
| 223351 | 파편 60개 수집시 에픽 정령 지호 소환 가능 | Collect 60 fragments to summon Epic Soul Jiho. |
| 223352 | 파편 60개 수집시 에픽 정령 헤이즐 소환 가능 | Collect 60 fragments to summon Epic Soul Hazel. |
| 223353 | 파편 60개 수집시 에픽 정령 소연 소환 가능 | Collect 60 fragments to summon Epic Soul Xiaolian. |
| 223354 | 파편 60개 수집시 에픽 정령 마농 소환 가능 | Collect 60 fragments to summon Epic Soul Manon. |
| 223355 | 파편 60개 수집시 에픽 정령 다프네 소환 가능 | Collect 60 fragments to summon Epic Soul Daphne. |
| 223356 | 파편 60개 수집시 에픽 정령 유리아 소환 가능 | Collect 60 fragments to summon Epic Soul Yuria. |
| 223358 | 파편 60개 수집시 에픽 정령 에일린 소환 가능 | Collect 60 fragments to summon Epic Soul Eileen. |
| 223359 | 파편 60개 수집시 에픽 정령 오토하 소환 가능 | Collect 60 fragments to summon Epic Soul Otoha. |
| 223360 | 파편 60개 수집시 에픽 정령 이브 소환 가능 | Collect 60 fragments to summon Epic Soul Eve. |
| 223361 | 파편 60개 수집시 에픽 정령 사쿠요 소환 가능 | Collect 60 fragments to summon Epic Soul Sakuyo. |
| 223362 | 파편 60개 수집시 에픽 정령 캐서린(광휘) 소환 가능 | Collect 60 fragments to summon Epic Soul Catherine (Radiance). |
| 223363 | 파편 60개 수집시 에픽 정령 도미니크 소환 가능 | Collect 60 fragments to summon Epic Soul Dominique. |
| 223364 | 파편 60개 수집시 에픽 정령 토키사키 쿠루미 소환 가능<br>토키사키 쿠루미를 보유 중인 경우 이차원의 정령 승급재료인 이차원의 정수를 획득합니다. | Collect 60 fragments to summon Epic Soul Kurumi Tokisaki.<br>If you already have Kurumi Tokisaki, you will get Essence of Another Dimension instead, which can be used for ascending Souls of Another Dimension. |
| 223365 | 파편 60개 수집시 에픽 정령 야토가미 토카 소환 가능<br>야토가미 토카를 보유 중인 경우 이차원의 정령 승급재료인 이차원의 정수를 획득합니다. | Collect 60 fragments to summon Epic Soul Tohka Yatogami.<br>If you already have Tohka Yatogami, you will get Essence of Another Dimension instead, which can be used for ascending Souls of Another Dimension. |
| 223366 | 파편 60개 수집시 에픽 정령 라리마 소환 가능 | Collect 60 fragments to summon Epic Soul Larimar. |
| 223367 | 사용시 차원을 건너온 방문객을 승급할 수 있는 귀중한 재료인 이차원의 정수를 획득합니다.<br>누군가의 소망으로 이루어진 별의 정수가 어두운 우주를 밝히고 있다. | Use to obtain Essence of Another Dimension, a valuable resource used for ascending visitors from a foreign realm.<br>The essence of a star formed by someone's wish illuminates the dark universe. |
| 223368 | 파편 60개 수집시 에픽 정령 시그리드 소환 가능 | Collect 60 fragments to summon Epic Soul Sigrid. |
| 223369 | 파편 60개 수집시 에픽 정령 오닉스 소환 가능 | Collect 60 fragments to summon Epic Soul Onyx. |
| 223370 | 파편 60개 수집시 에픽 정령 린지(타나토스) 소환 가능 | Collect 60 fragments to summon Epic Soul Linzy (Thanatos). |
| 223371 | 파편 60개 수집시 에픽 정령 릴리트 소환 가능 | Collect 60 fragments to summon Epic Soul Lilith. |
| 223372 | 파편 60개 수집시 에픽 정령 웨리 소환 가능 | Collect 60 fragments to summon Epic Soul Wheri. |
| 223373 | 파편 60개 수집시 에픽 정령 사쿠요(업화) 소환 가능 | Collect 60 fragments to summon Epic Soul Sakuyo (Inferno). |
| 223374 | 파편 60개 수집시 에픽 정령 메피스토펠레스(여명) 소환 가능 | Collect 60 fragments to summon Epic Soul Mephistopheles (Dawn). |
| 223375 | 파편 60개 수집시 에픽 정령 바이스 소환 가능 | Collect 60 fragments to summon Epic Soul Weiss. |
| 223376 | 파편 60개 수집시 에픽 정령 로제(홍염) 소환 가능 | Collect 60 fragments to summon Epic Soul Rose (Prominence). |
| 223377 | 파편 60개 수집시 에픽 정령 지호(미르) 소환 가능 | Collect 60 fragments to summon Epic Soul Jiho (Mir). |
| 223378 | 파편 60개 수집시 에픽 정령 홍란(무쌍) 소환 가능 | Collect 60 fragments to summon Epic Soul Honglan (Peerless). |
| 223379 | 파편 60개 수집시 에픽 정령 하루(카무이) 소환 가능 | Collect 60 fragments to summon Epic Soul Haru (Kamuy). |
| 223380 | 파편 60개 수집시 에픽 정령 르네(백은) 소환 가능 | Collect 60 fragments to summon Epic Soul Renee (Argent). |
| 223381 | 파편 60개 수집시 에픽 정령 미리암(잔영) 소환 가능 | Collect 60 fragments to summon Epic Soul Miriam (Afterimage). |
| 223382 | 파편 60개 수집시 에픽 정령 라우라 소환 가능 | Collect 60 fragments to summon Epic Soul Laura. |
| 223383 | 파편 60개 수집시 에픽 정령 페트라(각혼) 소환 가능 | Collect 60 fragments to summon Epic Soul Petra (Awakened Soul). |
| 223384 | 파편 60개 수집시 에픽 정령 가넷(열락) 소환 가능 | Collect 60 fragments to summon Epic Soul Garnet (Rapture). |
| 223385 | 파편 60개 수집시 에픽 정령 한울 소환 가능 | Collect 60 fragments to summon Epic Soul Hanul. |
| 223386 | 파편 60개 수집시 에픽 정령 카넬리안 소환 가능 | Collect 60 fragments to summon Epic Soul Carnelian. |
| 223387 | 파편 60개 수집시 에픽 정령 니아 소환 가능 | Collect 60 fragments to summon Epic Soul Nia. |
| 223388 | 파편 60개 수집시 에픽 정령 셰리(낭만) 소환 가능 | Collect 60 fragments to summon Epic Soul Cherrie (Romantic). |
| 223389 | 파편 60개 수집시 에픽 정령 클라우디아(대천사) 소환 가능 | Collect 60 fragments to summon Epic Soul Claudia (Archangel). |
| 223390 | 파편 60개 수집시 에픽 정령 유리아 (아폴리온) 소환 가능 | Collect 60 fragments to summon Epic Soul Yuria (Apollyon). |
| 223391 | 파편 60개 수집시 에픽 정령 아야메(츠쿠요미) 소환 가능 | Collect 60 fragments to summon Epic Soul Ayame (Tsukuyomi). |
| 223501 | 파편 60개 수집시 정령 리타 (레전더리+) 소환 가능 | Collect 60 fragments to summon Rita (Legendary+). |
| 223502 | 파편 60개 수집시 정령 로제 (레전더리+) 소환 가능 | Collect 60 fragments to summon Rose (Legendary+). |
| 223503 | 파편 60개 수집시 정령 샤링 (레전더리+) 소환 가능 | Collect 60 fragments to summon Sharinne (Legendary+). |
| 223504 | 파편 60개 수집시 정령 루리 (레전더리+) 소환 가능 | Collect 60 fragments to summon Ruri (Legendary+). |
| 223505 | 파편 60개 수집시 정령 알리샤 (레전더리+) 소환 가능 | Collect 60 fragments to summon Alisha (Legendary+). |
| 223506 | 파편 60개 수집시 정령 르웨인 (레전더리+) 소환 가능 | Collect 60 fragments to summon Lewayne (Legendary+). |
| 223507 | 파편 60개 수집시 정령 무명 (레전더리+) 소환 가능 | Collect 60 fragments to summon Nameless (Legendary+). |
| 223508 | 파편 60개 수집시 정령 카렌 (레전더리+) 소환 가능 | Collect 60 fragments to summon Karen (Legendary+). |
| 223509 | 파편 60개 수집시 정령 로제 (에픽+) 소환 가능 | Collect 60 fragments to summon Rose (Epic+). |
| 223510 | 파편 60개 수집시 정령 메피스토펠레스 (오리진) 소환 가능 | Collect 60 fragments to summon Soul Mephistopheles (Origin). |
| 223511 | 파편 60개 수집시 정령 도미니크 (레전더리+) 소환 가능 | Collect 60 fragments to summon Dominique (Legendary+). |
| 223512 | 파편 60개 수집시 정령 시그리드 (레전더리+) 소환 가능 | Collect 60 fragments to summon Sigrid (Legendary+). |
| 223513 | 파편 60개 수집시 정령 벨레드 (레전더리+) 소환 가능 | Collect 60 fragments to summon Beleth (Legendary+). |
| 224001 | 탐관오리 클로이가 떨어뜨린 복주머니<br>어떤 물건이 들어있을까? | What's in the lucky pouch<br>that Corrupt Official Chloe has dropped? |
| 224002 | 에픽 예장을 선택하여 획득할 수 있는 상자 | A chest from which you can obtain an Epic Keepsake of your choice. |
| 224003 | 일반적으로 획득하기 어려운 고급 유물석이 들어있는 상자 | A chest containing an Expert Artifact Stone which is hard to obtain. |
| 224004 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 224005 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 224006 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 224007 | 아레나의 승리자에게 간혹 지급되는 보상 | An occasional reward granted to the champion of the Arena. |
| 224008 | 미사용 상자 (추후 교체 사용) | Unused Chest (Will be switched later) |
| 224009 | 에픽 정령을 선택하여 획득할 수 있는 상자 | A chest from which you can obtain an Epic Soul of your choice. |
| 224010 | 에픽 정령 타입을 선택할 수 있는 상자 | A chest from which you can select an Epic Soul. |
| 224011 | 레어 정령 타입을 선택할 수 있는 상자 | A chest from which you can select a Rare Soul. |
| 224012 | 공격 특화 에픽 정령 중 하나를 선택할 수 있는 상자 | A chest from which you can select an Epic Soul specialized for attacking. |
| 224013 | 방어 특화 에픽 정령 중 하나를 선택할 수 있는 상자 | A chest from which you can select an Epic Soul specialized for defending. |
| 224014 | 지원 특화 에픽 정령 중 하나를 선택할 수 있는 상자 | A chest from which you can select an Epic Soul specialized for supporting. |
| 224015 | 에픽 레인저 정령 중 하나를 선택할 수 있는 상자 | A chest from which you can select an Epic Ranger Soul. |
| 224016 | 에픽 정령을 선택하여 획득할 수 있는 상자<br>천사형 정령과 악마형 정령은 포함되어 있지 않습니다. | A chest from which you can obtain an Epic Soul of your choice.<br>Doesn't include Angel Souls or Demon Souls. |
| 224017 | 에덴 갓 탤런트 영광의 1등~3등을 차지한 정령 3명을 모두 지급하는 상자 | A chest that contains all three Souls who placed 1st through 3rd on Eden's Got Talent. |
| 224018 | 천사형, 악마형 정령을 제외한 런칭~에일린까지의 에픽 정령 중 선택 가능한 상자 | A chest from which you can choose an Epic Soul. Contains all Souls who were released up until Eileen, excluding Angel and Demon Souls. |
| 224019 | 청룡의 기운이 담긴 복주머니<br>어떤 물건이 들어있을까? | A lucky pouch containing the aura of the Blue Dragon<br>What could be inside? |
| 224020 | 에픽 정령을 선택하여 획득할 수 있는 상자<br>천사형 정령과 악마형 정령은 포함되어 있지 않습니다. | A chest from which you can obtain an Epic Soul of your choice.<br>Doesn't include Angel Souls or Demon Souls. |
| 224101 | 커먼 예장을 획득할 수 있는 상자.<br>커먼 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain a Common Keepsake.<br>Randomly obtain 1 Common Keepsake. |
| 224102 | 레어 예장을 획득할 수 있는 상자.<br>레어 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain a Rare Keepsake.<br>Randomly obtain 1 Rare Keepsake. |
| 224103 | 레어+ 예장을 획득할 수 있는 상자.<br>레어+ 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain a Rare+ Keepsake.<br>Randomly obtain 1 Rare+ Keepsake. |
| 224104 | 에픽 예장을 획득할 수 있는 상자.<br>에픽 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Epic Keepsake.<br>Randomly obtain 1 Epic Keepsake. |
| 224105 | 에픽+ 예장을 획득할 수 있는 상자.<br>에픽+ 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Epic+ Keepsake.<br>Randomly obtain 1 Epic+ Keepsake. |
| 224106 | 레전더리 예장을 획득할 수 있는 상자.<br>레전더리 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain a Legendary Keepsake.<br>Randomly obtain 1 Legendary Keepsake. |
| 224107 | 레전더리+ 예장을 획득할 수 있는 상자.<br>레전더리+ 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain a Legendary+ Keepsake.<br>Randomly obtain 1 Legendary+ Keepsake. |
| 224108 | 이터널 예장을 획득할 수 있는 상자.<br>이터널 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Eternal Keepsake.<br>Randomly obtain 1 Eternal Keepsake. |
| 224109 | 이터널+ 예장을 획득할 수 있는 상자.<br>이터널+ 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Eternal+ Keepsake.<br>Randomly obtain 1 Eternal+ Keepsake. |
| 224110 | 오리진 예장을 획득할 수 있는 상자.<br>오리진 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Origin Keepsake.<br>Randomly obtain 1 Origin Keepsake. |
| 224111 | 아직 정보가 확인되지 않은 유물의 기억. 랜덤한 유물의 기억을 얻을 수 있다고 한다. | A memory of an unidentified Artifact. Can obtain a random Artifact Memory. |
| 224112 | 정령들이 좋아하는 선물로 구성된 뽑기 캡슐!<br>어떤 선물이 나올까? | A capsure containing gifts Souls like!<br>What could be inside? |
| 224113 | (미사용) | (Unused) |
| 224114 | (미사용) | (Unused) |
| 224115 | 화려한 장식으로 포장 된 큰 선물 상자. | A big gift box wrapped with fancy decorations. |
| 224116 | 아직 정보가 확인되지 않은 유물의 기억 상자. 랜덤한 유물의 기억 10개를 얻을 수 있다고 한다. | A memory box of an unidentified Artifact. Can obtain 10 random Artifact Memories. |
| 224117 | 골드와 마나 더스트 중 하나를 선택하여 얻습니다. (방치 12시간) | Choose between Gold or Mana Dust. (Idle for 12 hours) |
| 224118 | 골드와 마나 더스트 중 하나를 선택하여 얻습니다. (방치 24시간) | Choose between Gold or Mana Dust. (Idle for 24 hours) |
| 224119 | 에픽+ 예장을 획득할 수 있는 상자.<br>에픽+ 예장중 1개를 선택하여 얻습니다. | A chest from which you can obtain an Epic+ Keepsake.<br>Select 1 Epic+ Keepsake. |
| 224120 | 사진: 미카와 시하의 하루를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다. | Camera that took the Photo: Mica and Seeha's Day.<br>Use to obtain an illustration. |
| 224121 | 힘 타입의 이터널 예장을 선택하여 획득할 수 있는 상자.<br>세트 예장은 포함하지 않습니다. | A chest from which you can obtain an Eternal STR Keepsake of your choice.<br>Does not include set Keepsakes. |
| 224122 | 민첩 타입의 이터널 예장을 선택하여 획득할 수 있는 상자.<br>세트 예장은 포함하지 않습니다. | A chest from which you can obtain an Eternal DEX Keepsake of your choice.<br>Does not include set Keepsakes. |
| 224123 | 정령들이 좋아하는 다양한 선물을 획득할 수 있습니다. | You can obtain various gifts that Souls like. |
| 224124 | 이터널 세트 예장을 획득할 수 있는 상자.<br>이터널 세트 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Eternal Set Keepsake.<br>Randomly obtain 1 Eternal Set Keepsake. |
| 224125 | 이터널+ 세트 예장을 획득할 수 있는 상자.<br>이터널+ 세트 예장중 1개를 랜덤으로 획득한다. | A chest from which you can obtain an Eternal+ Set Keepsake.<br>Randomly obtain 1 Eternal+ Set Keepsake. |
| 224126 | 모든 종류의 유물석 중 하나를 선택하여 획득 할 수 있는 상자 | You can select an artifact stone from this chest. It contains all types of artifact stones to choose from. |
| 224127 | 오리진 등급의 금형 중 하나를 선택하여 획득할 수 있는 상자. | You can select an Origin grade mold from this chest. |
| 224128 | 오리진 등급의 금형 중 하나를 랜덤하게 획득할 수 있는 상자. | You can randomly obtain an Origin grade mold from this chest. |
| 224129 | 골드와 마나 더스트 중 하나를 선택하여 얻습니다. (방치 2시간) | Choose between Gold or Mana Dust. (Idle for 2 hours) |
| 224130 | 골드와 마나 더스트 중 하나를 선택하여 얻습니다. (방치 6시간) | Choose between Gold or Mana Dust. (Idle for 6 hours) |
| 224131 | 이터널+ 세트 예장을 획득할 수 있는 상자.<br>이터널+ 세트 예장중 1개를 선택하여 획득한다. | A chest from which you can obtain an Eternal+ Set Keepsake.<br>Select 1 Eternal+ Set Keepsake. |
| 224132 | 프리미엄 선물 뽑기 캡슐!<br>영원꽃과 행운의 꽃다발이 포함되어 있어요! | A Premium Gift Capsule!<br>May contain an Eternity Flower or a Lucky Bouquet. |
| 224133 | 특별 픽업에 등장하는 정령(메피스토펠레스/지호/아키/홍란/에리카/벨라나) 중 하나를 선택할 수 있는 상자 | A chest from which you can select a Special Pick-Up Soul (Mephistopheles/Jiho/Aki/Honglan/Erika/Velanna). |
| 224134 | 원하는 정령을 선택하여 획득할 수 있는 상자<br>(클라우디아 픽업 이전까지의 정령만 포함됩니다.) | A chest from which you can obtain a Soul of your choice.<br>(Only includes Souls prior to Claudia's pick-up summons.) |
| 224135 | 원하는 클래스 강화 회로를 선택하여 획득할 수 있는 상자 | A chest from which you can obtain a Class Enhance Circuit of your choice. |
| 224136 | 클래스 강화 회로 중 1개를 랜덤으로 획득할 수 있는 상자 | A chest from which you can obtain a random Class Enhance Circuit. |
| 224137 | 이터널 세트 예장을 획득할 수 있는 상자.<br>이터널 세트 예장중 1개를 선택하여 획득한다. | A chest from which you can obtain an Eternal Set Keepsake.<br>You can select 1 Eternal Set Keepsake. |
| 224138 | 오리진+1 등급의 금형 중 하나를 선택하여 획득할 수 있는 상자. | You can select an Origin+1 grade mold from this chest. |
| 224139 | 오리진+1 등급의 금형 중 하나를 랜덤하게 획득할 수 있는 상자. | You can randomly obtain an Origin+1 grade mold from this chest. |
| 224140 | 런칭~오토하까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you could choose an Artifact Memory of any Soul released up until Otoha's release. |
| 224141 | 태생 레어 정령인 리타, 샤링, 알리샤, 무명 중 하나를 선택하여 레전더리+ 등급으로 획득할 수 있는 상자. | Select a Soul (Rita, Sharinne, Alisha, and Nameless) that was originally Rare to obtain her at Legendary+ grade. |
| 224142 | 레전더리+ 세트 예장을 획득할 수 있는 상자.<br>레전더리+ 세트 예장중 1개를 선택하여 획득한다. | A chest containing a Legendary+ Set Keepsake.<br>Offers 1 Legendary+ Set Keepsake of your choice. |
| 224143 | 픽업 선택 소환 Season 2에 등장하는 정령 중 하나를 선택할 수 있는 상자 | A chest from which you can select a Soul featured in Pick-Up Choice Summon Season 2. |
| 224144 | 런칭~사쿠요까지 출시 된 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Sakuyo. |
| 224145 | 오리진 세트 예장을 획득할 수 있는 상자.<br>오리진 세트 예장중 1개를 선택하여 획득한다. | A chest containing an Origin Set Keepsake.<br>Offers 1 Origin Set Keepsake of your choice. |
| 224146 | 런칭~사쿠요까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Sakuyo, excluding Angel, Demon, and Chaotic Souls. |
| 224147 | 메피스토펠레스를 오리진 등급으로 바로 획득할 수 있는 정령의 기억과, 승급 초기화권이 함께 들어있는 상자.<br><br>레전더리 등급 이상 성장 시킨 메피스토펠레스를 이미 보유 중일 경우, 승급 초기화를 진행하여야 승급의 재료로 사용하거나 상급 해방이 가능한 점 참고 부탁드립니다. | A chest containing Soul's Memory that offers an Origin Mephistopheles along with an Ascension Reset ticket.<br><br>Please note that if you already have a Legendary or better Mephistopheles, you must use Reset Ascension on her to use her as an Ascension material or proceed with Advanced Release. |
| 224148 | 런칭~사쿠요까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Sakuyo. |
| 224149 | 런칭~오토하까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Otoha, excluding Angel, Demon, and Chaotic Souls. |
| 224150 | 런칭~라리마까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Larimar, excluding Chaotic Souls. |
| 224151 | 사진: 에덴 갓 탤런트를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다. | Camera that took the Photo: Eden's Got Talent.<br>Use to obtain an illustration. |
| 224152 | 런칭~마농까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Manon. |
| 224153 | 모든 런칭 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released at launch. |
| 224154 | 런칭 정령 중 천사형, 악마형을 제외한 모든 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released at launch, excluding Angel and Demon Souls. |
| 224155 | 런칭~오닉스까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Onyx, excluding Angel, Demon, and Chaotic Souls. |
| 224156 | 런칭~오닉스까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Onyx, excluding Chaotic Souls. |
| 224157 | 예장 성장에 필요한 아이템을 선택하여 획득할 수 있는 상자 | A chest from which you can obtain a Keepsake upgrade item of your choice. |
| 224160 | 런칭~오닉스까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Onyx. |
| 224161 | 구원자를 위해 정령들이 준비한 특별한 이브 데이 선물.<br>"구원자가 살던 곳에서는 이 시기에 이런 걸 먹는구나!"<br>친한 정령들과 함께 나눠 먹으면 더욱 맛있다! | A special Eve's Day present for the Savior from the Souls.<br>"So, this is what they ate for this occasion back in Savior's time!"<br>It tastes even better when shared with close Souls! |
| 224162 | 런칭~브라이스까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Bryce, excluding Angel, Demon, and Chaotic Souls. |
| 224163 | 런칭~브라이스까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Bryce, excluding Chaotic Souls. |
| 224164 | 런칭~브라이스까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Bryce. |
| 224165 | 사진: 거미님 일러스트를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 대상 당선작입니다. | Camera that took a photo of an illustration by 거미.<br>Use to obtain the illustration.<br>This illustration is the grand prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 224166 | 사진: 주상절리님 일러스트를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 금상 당선작입니다. | Camera that took a photo of an illustration by 주상절리.<br>Use to obtain the illustration.<br>This illustration is the gold prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 224167 | 사진: yuugen님 일러스트를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 은상 당선작입니다. | Camera that took a photo of an illustration by yuugen.<br>Use to obtain the illustration.<br>This illustration is the silver prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 224168 | 사진: 귄터님 일러스트를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 특별상 당선작입니다. | Camera that took a photo of an illustration by 귄터.<br>Use to obtain the illustration.<br>This illustration is the special prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 224169 | 사진: 고꾸닥님 일러스트를 찍은 사진기입니다.<br>사용 시 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 특별상 당선작입니다. | Camera that took a photo of an illustration by 고꾸닥.<br>Use to obtain the illustration.<br>This illustration is the special prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 224170 | 신년을 기념하여 마련한 에버스톤 복주머니!<br>사용 시 100~300 무료 에버스톤을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>에버스톤(무료) 300개: 5%<br>에버스톤(무료) 250개: 10%<br>에버스톤(무료) 200개: 15%<br>에버스톤(무료) 150개: 30%<br>에버스톤(무료) 100개: 40% | New Year's Everstone lucky pouch!<br>Contains 100 to 300 free Everstones.<br><br>[Probabilities]<br>300 Everstones (Free): 5%<br>250 Everstones (Free): 10%<br>200 Everstones (Free): 15%<br>150 Everstones (Free): 30%<br>100 Everstones (Free): 40% |
| 224171 | 신년을 기념하여 마련한 소환권 세뱃돈 봉투!<br>운이 좋다면 픽업 소환권이 들어있을 지도...?<br>사용 시 구성품 중 1종을 선택하여 획득할 수 있습니다. | A New Year's gift envelope containing Summon Tickets!<br>If you're lucky, it may give you Pick-Up Summon Tickets!<br>Use it to select and obtain 1 item from the available options. |
| 224172 | 신년을 기념하여 마련한 지정 소환권 세뱃돈 봉투!<br>운이 좋다면 픽업 소환권이 들어있을 지도...?<br>사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>픽업 소환권 50개: 1%<br>지정 소환권 20개: 4%<br>지정 소환권 15개: 5%<br>지정 소환권 10개: 35%<br>지정 소환권 5개: 55% | A New Year's gift envelope containing Targeted Summon Tickets!<br>If you're lucky, it may give you Pick-Up Summon Tickets instead!<br>Use it to obtain one of the following options:<br><br>[Probabilities]<br>50 Pick-Up Summon Tickets: 1%<br>20 Targeted Summon Tickets: 4%<br>15 Targeted Summon Tickets: 5%<br>10 Targeted Summon Tickets: 35%<br>5 Targeted Summon Tickets: 55% |
| 224173 | 신년을 기념하여 마련한 유물 소환권 세뱃돈 봉투!<br>운이 좋다면 픽업 소환권이 들어있을 지도...?<br>사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>픽업 소환권 50개: 1%<br>유물 소환권 35개: 4%<br>유물 소환권 25개: 5%<br>유물 소환권 20개: 35%<br>유물 소환권 15개: 55% | A New Year's gift envelope containing Artifact Summon Tickets!<br>If you're lucky, it may give you Pick-Up Summon Tickets instead!<br>Use it to obtain one of the following options:<br><br>[Probabilities]<br>50 Pick-Up Summon Tickets: 1%<br>35 Artifact Summon Tickets: 4%<br>25 Artifact Summon Tickets: 5%<br>20 Artifact Summon Tickets: 35%<br>15 Artifact Summon Tickets: 55% |
| 224174 | 신년을 기념하여 마련한 연금술 소환권 세뱃돈 봉투!<br>운이 좋다면 픽업 소환권이 들어있을 지도...?<br>사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>픽업 소환권 50개: 1%<br>에리카의 연금술 티켓 15개: 4%<br>에리카의 연금술 티켓 10개: 5%<br>에리카의 연금술 티켓 5개: 35%<br>에리카의 연금술 티켓 3개: 55% | A New Year's gift envelope containing Alchemy Summon Tickets!<br>If you're lucky, it may give you Pick-Up Summon Tickets instead!<br>Use it to obtain one of the following options:<br><br>[Probabilities]<br>50 Pick-Up Summon Tickets: 1%<br>15 Erika's Alchemy Tickets: 4%<br>10 Erika's Alchemy Tickets: 5%<br>5 Erika's Alchemy Tickets: 35%<br>3 Erika's Alchemy Tickets: 55% |
| 224175 | 사랑의 날을 기념하여 맛있는 초콜릿을 포장한 상자.<br>달콤한 향기 덕에 보고만 있어도 행복한 기분이 든다. | A box of delectable chocolates, packed in celebration of Love Day.<br>Just the sweet scent is enough to bring joy. |
| 224176 | 사이드 이벤트를 기념하여 준비한 행운 상자입니다.<br>사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[구성품 확률]<br>에리카의 연금술 티켓 70장: 1%<br>유물 소환권 30장: 3%<br>유물 소환권 20장: 4%<br>유물 소환권 15장: 7%<br>유물 소환권 10장: 35%<br>유물 소환권 5장: 50% | A lucky chest prepared in celebration of our side event.<br>Contains one of the following options based on chance.<br><br>[Content Probabilities]<br>70 Erika's Alchemy Tickets: 1%<br>30 Artifact Summon Tickets: 3%<br>20 Artifact Summon Tickets: 4%<br>15 Artifact Summon Tickets: 7%<br>10 Artifact Summon Tickets: 35%<br>5 Artifact Summon Tickets: 50% |
| 224177 | 마농이 5월을 맞이하며 모아온 특별한 아이템이 가득 담긴 상자. | A box full of special items Manon gathered to welcome May. |
| 224178 | 운이 좋다면 픽업 소환권이 들어있을 지도...?<br>사용 시 구성품 중 1종을 선택하여 획득할 수 있습니다. | If you're lucky, it may give you Pick-Up Summon Tickets!<br>Use it to select and obtain 1 item from the available options. |
| 224179 | 사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>픽업 소환권 50개: 1%<br>지정 소환권 20개: 4%<br>지정 소환권 15개: 5%<br>지정 소환권 10개: 35%<br>지정 소환권 5개: 55% | Use it to obtain one of the following options:<br><br>[Probabilities]<br>50 Pick-Up Summon Tickets: 1%<br>20 Targeted Summon Tickets: 4%<br>15 Targeted Summon Tickets: 5%<br>10 Targeted Summon Tickets: 35%<br>5 Targeted Summon Tickets: 55% |
| 224180 | 사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>픽업 소환권 50개: 1%<br>유물 소환권 35개: 4%<br>유물 소환권 25개: 5%<br>유물 소환권 20개: 35%<br>유물 소환권 15개: 55% | Use it to obtain one of the following options:<br><br>[Probabilities]<br>50 Pick-Up Summon Tickets: 1%<br>35 Artifact Summon Tickets: 4%<br>25 Artifact Summon Tickets: 5%<br>20 Artifact Summon Tickets: 35%<br>15 Artifact Summon Tickets: 55% |
| 224181 | 사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>픽업 소환권 50개: 1%<br>에리카의 연금술 티켓 15개: 4%<br>에리카의 연금술 티켓 10개: 5%<br>에리카의 연금술 티켓 5개: 35%<br>에리카의 연금술 티켓 3개: 55% | Use it to obtain one of the following options:<br><br>[Probabilities]<br>50 Pick-Up Summon Tickets: 1%<br>15 Erika's Alchemy Tickets: 4%<br>10 Erika's Alchemy Tickets: 5%<br>5 Erika's Alchemy Tickets: 35%<br>3 Erika's Alchemy Tickets: 55% |
| 224182 | 런칭~바이스까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Weiss, excluding Angel, Demon, and Chaotic Souls. |
| 224183 | 런칭~바이스까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Weiss, excluding Chaotic Souls. |
| 224184 | 런칭~바이스까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Weiss. |
| 224185 | 런칭~유리아까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Yuria, excluding Angel, Demon, and Chaotic Souls. |
| 224186 | 런칭~유리아까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Yuria, excluding Chaotic Souls. |
| 224187 | 런칭~유리아까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Yuria. |
| 224188 | 오리진 세트 예장을 획득할 수 있는 상자.<br>오리진 세트 예장중 1개를 랜덤으로 획득한다. | A chest containing an Origin Set Keepsake.<br>Offers 1 random Origin Set Keepsake. |
| 224189 | 런칭~홍란(무쌍)까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Honglan (Peerless), excluding Angel, Demon, and Chaotic Souls. |
| 224190 | 런칭~한울까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Hanul, excluding Chaotic Souls. |
| 224191 | 런칭~한울까지 출시 된 모든 정령의 유물의 기억 중 선택 가능한 상자. | A chest from which you can choose the Artifact Memory of any Soul released up to Hanul. |
| 224192 | 오리진+2 등급의 금형 중 하나를 선택하여 획득할 수 있는 상자. | You can select an Origin+2 grade mold from this chest. |
| 224193 | 오리진+2 등급의 금형 중 하나를 랜덤하게 획득할 수 있는 상자. | You can randomly obtain an Origin+2 grade mold from this chest. |
| 224194 | 오리진+3 등급의 금형 중 하나를 선택하여 획득할 수 있는 상자. | You can select an Origin+3 grade mold from this chest. |
| 224195 | 오리진+3 등급의 금형 중 하나를 랜덤하게 획득할 수 있는 상자. | You can randomly obtain an Origin+3 grade mold from this chest. |
| 224196 | 오리진+2 세트 예장을 획득할 수 있는 상자.<br>오리진+2 세트 예장중 1개를 선택하여 획득한다. | A chest containing an Origin+2 Set Keepsake.<br>Offers 1 Origin+2 Set Keepsake of your choice. |
| 224197 | 오리진+3 세트 예장을 획득할 수 있는 상자.<br>오리진+3 세트 예장중 1개를 선택하여 획득한다. | A chest containing an Origin+3 Set Keepsake.<br>Offers 1 Origin+3 Set Keepsake of your choice. |
| 224198 | 오리진+1 세트 예장을 획득할 수 있는 상자.<br>오리진+1 세트 예장중 1개를 선택하여 획득한다. | A chest containing an Origin+1 Set Keepsake.<br>Offers 1 Origin+1 Set Keepsake of your choice. |
| 224199 | 오리진+2 공격력/가속 세트 예장을 획득할 수 있는 상자.<br>오리진+2 공격력/가속 세트 예장중 1개를 랜덤으로 획득한다. | A chest containing an Origin+2 ATK/Speed Set Keepsake.<br>Offers 1 random Origin+2 ATK/Speed Set Keepsake. |
| 224200 | 2026년 새해 축복이 가득한 선물상자! |  |
| 224201 | 인간형 타입의 레어 정령을 소환합니다. | Summons a Rare Humanlike Soul. |
| 224202 | 야수형 타입의 레어 정령을 소환합니다. | Summons a Rare Beast Soul. |
| 224203 | 요정형 타입의 레어 정령을 소환합니다. | Summons a Rare Fairy Soul. |
| 224204 | 불사형 타입의 레어 정령을 소환합니다. | Summons a Rare Undead Soul. |
| 224205 | 인간형 타입의 에픽 정령을 소환합니다. | Summons an Epic Humanlike Soul. |
| 224206 | 야수형 타입의 에픽 정령을 소환합니다. | Summons an Epic Beast Soul. |
| 224207 | 요정형 타입의 에픽 정령을 소환합니다. | Summons an Epic Fairy Soul. |
| 224208 | 불사형 타입의 에픽 정령을 소환합니다. | Summons an Epic Undead Soul. |
| 224209 | 천사형 타입의 에픽 정령을 소환합니다. | Summons an Epic Angel Soul. |
| 224210 | 악마형 타입의 에픽 정령을 소환합니다. | Summons an Epic Demon Soul. |
| 224211 | 골드와 마나 더스트 그리고 마나 크리스탈 중 하나를 선택하여 얻습니다. (방치 2시간) | Choose between Gold, Mana Dust, or Mana Crystal. (Idle for 2 hours) |
| 224212 | 골드와 마나 더스트 그리고 마나 크리스탈 중 하나를 선택하여 얻습니다. (방치 6시간) | Choose between Gold, Mana Dust, or Mana Crystal. (Idle for 6 hours) |
| 224213 | 골드와 마나 더스트 그리고 마나 크리스탈 중 하나를 선택하여 얻습니다. (방치 12시간) | Choose between Gold, Mana Dust, or Mana Crystal. (Idle for 12 hours) |
| 224214 | 골드와 마나 더스트 그리고 마나 크리스탈 중 하나를 선택하여 얻습니다. (방치 24시간) | Choose between Gold, Mana Dust, or Mana Crystal. (Idle for 24 hours) |
| 224220 | 사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>마나 크리스탈 40000개: 20%<br>마나 크리스탈 30000개: 50%<br>마나 크리스탈 20000개: 30% | Use it to obtain one of the following options:<br><br>[Probabilities]<br>40,000 Mana Crystals: 20%<br>30,000 Mana Crystals: 50%<br>20,000 Mana Crystals: 30% |
| 224221 | 사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>메인 강화 회로 80개: 20%<br>메인 강화 회로 60개: 50%<br>메인 강화 회로 40개: 30% | Use it to obtain one of the following options:<br><br>[Probabilities]<br>80 Main Enhance Circuits: 20%<br>60 Main Enhance Circuits: 50%<br>40 Main Enhance Circuits: 30% |
| 224222 | 사용 시 아래 구성품을 확률에 따라 획득합니다.<br><br>[획득 확률]<br>에리카의 연금술 티켓 5개: 5%<br>픽업 소환권 5개: 10%<br>지정 소환권 5개: 10%<br>에리카의 연금술 티켓 3개: 15%<br>픽업 소환권 3개: 15%<br>지정 소환권 3개: 15%<br>에리카의 연금술 티켓 1개: 10%<br>픽업 소환권 1개: 10%<br>지정 소환권 1개: 10% | Use it to obtain one of the following options:<br><br>[Probabilities]<br>5 Erika's Alchemy Tickets: 5%<br>5 Pick-Up Summon Tickets: 10%<br>5 Targeted Summon Tickets: 10%<br>3 Erika's Alchemy Tickets: 15%<br>3 Pick-Up Summon Tickets: 15%<br>3 Targeted Summon Tickets: 15%<br>1 Erika's Alchemy Ticket: 10%<br>1 Pick-Up Summon Ticket: 10%<br>1 Targeted Summon Ticket: 10% |
| 224223 | 오리진+4 등급의 금형 중 하나를 선택하여 획득할 수 있는 상자. | You can select an Origin+4 grade mold from this chest. |
| 224224 | 오리진+4 등급의 금형 중 하나를 랜덤하게 획득할 수 있는 상자. | You can randomly obtain an Origin+4 grade mold from this chest. |
| 224225 | 런칭~페트라(각혼)까지 출시 된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Petra (Awakened Soul), excluding Angel, Demon, and Chaotic Souls. |
| 224226 | 런칭~페트라(각혼)까지 출시 된 정령 중 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Petra (Awakened Soul), excluding Chaotic Souls. |
| 224227 | 런칭~셰리(낭만)까지 에리카의 연금술에 포함되어있던 모든 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released up to Cherrie (Romantic) that's been included in Erika's Alchemy. |
| 224228 | 사용 시 구성품을 모두 획득할 수 있습니다. | Use it to obtain all items contained within. |
| 224229 | 사용 시 구성품을 모두 획득할 수 있습니다. | Use it to obtain all items contained within. |
| 224230 | 사용 시 구성품을 모두 획득할 수 있습니다. | Use it to obtain all items contained within. |
| 225000 | 로비 배경을 변경할 수 있습니다. (아케나인 광장)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Arkenine Square)<br><br>Can be obtained as an area completion achievement reward |
| 225001 | 로비 배경을 변경할 수 있습니다. (아케나인 다리)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Arkenine Bridge)<br><br>Can be obtained as an area completion achievement reward |
| 225002 | 로비 배경을 변경할 수 있습니다. (콜브 초원)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Colve Meadow)<br><br>Can be obtained as an area completion achievement reward |
| 225003 | 로비 배경을 변경할 수 있습니다. (다이난 호수)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Lake Dynan)<br><br>Can be obtained as an area completion achievement reward |
| 225004 | 로비 배경을 변경할 수 있습니다. (하얀 울새 숲)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (White Robin Forest)<br><br>Can be obtained as an area completion achievement reward |
| 225005 | 로비 배경을 변경할 수 있습니다. (베르트 산맥)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Vert Mountains)<br><br>Can be obtained as an area completion achievement reward |
| 225006 | 로비 배경을 변경할 수 있습니다. (렉타 황무지)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Rechtar Wasteland)<br><br>Can be obtained as an area completion achievement reward |
| 225007 | 로비 배경을 변경할 수 있습니다. (비노 협곡)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Vino Valley)<br><br>Can be obtained as an area completion achievement reward |
| 225008 | 로비 배경을 변경할 수 있습니다. (모레노 사막)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Morreno Desert)<br><br>Can be obtained as an area completion achievement reward |
| 225009 | 로비 배경을 변경할 수 있습니다. (아르코 이리스)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Arco Iris)<br><br>Can be obtained as an area completion achievement reward |
| 225010 | 로비 배경을 변경할 수 있습니다. (쿠르 사바나)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Cur Savannah)<br><br>Can be obtained as an area completion achievement reward |
| 225011 | 로비 배경을 변경할 수 있습니다. (반딧불이의 둥지)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nest of Fireflies)<br><br>Can be obtained as an area completion achievement reward |
| 225012 | 로비 배경을 변경할 수 있습니다. (라피아 정글)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Raffia Jungle)<br><br>Can be obtained as an area completion achievement reward |
| 225013 | 로비 배경을 변경할 수 있습니다. (나델 고산지)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nadel Mountains)<br><br>Can be obtained as an area completion achievement reward |
| 225014 | 로비 배경을 변경할 수 있습니다. (그림자 없는 땅)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Shadowless Lands)<br><br>Can be obtained as an area completion achievement reward |
| 225015 | 로비 배경을 변경할 수 있습니다. (유령도시 모르투스)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Ghost City Mortus)<br><br>Can be obtained as an area completion achievement reward |
| 225016 | 로비 배경을 변경할 수 있습니다. (버려진 항구)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Forsaken Harbor)<br><br>Can be obtained as an area completion achievement reward |
| 225017 | 로비 배경을 변경할 수 있습니다. (메티아스 호 갑판)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Mettias Deck)<br><br>Can be obtained as an area completion achievement reward |
| 225018 | 로비 배경을 변경할 수 있습니다. (대설원)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Snowfield)<br><br>Can be obtained as an area completion achievement reward |
| 225019 | 로비 배경을 변경할 수 있습니다. (냉대삼림)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Cold Forest)<br><br>Can be obtained as an area completion achievement reward |
| 225020 | 로비 배경을 변경할 수 있습니다. (극지)<br><br>지역 클리어 업적 보상으로 획득 가능 | You can change the background of the lobby. (Polar Region)<br><br>Can be obtained as an area completion achievement reward |
| 225110 | 로비 배경을 변경할 수 있습니다. (학교 교실) | You can change the background of the lobby. (School Classroom) |
| 225111 | 로비 배경을 변경할 수 있습니다. (학교 옥상) | You can change the background of the lobby. (School Rooftop) |
| 225112 | 로비 배경을 변경할 수 있습니다. (학교 복도) | You can change the background of the lobby. (School Corridor) |
| 225120 | 로비 배경을 변경할 수 있습니다. (클라라의 농장) | You can change the background of the lobby. (Clara Farm) |
| 225121 | 로비 배경을 변경할 수 있습니다. (꽃밭) | You can change the background of the lobby. (Flower Field) |
| 225122 | 로비 배경을 변경할 수 있습니다. (행운꽃밭) | You can change the background of the lobby. (Lucky Flower Field) |
| 225130 | 로비 배경을 변경할 수 있습니다. (탐관오리 클로이 성채) | You can change the background of the lobby. (Corrupt Official Chloe Fortress) |
| 225131 | 로비 배경을 변경할 수 있습니다. (가온의 온천) | You can change the background of the lobby. (Gaon's Hot Spring) |
| 225132 | 로비 배경을 변경할 수 있습니다. (가온의 전통 카페) | You can change the background of the lobby. (Gaon's Traditional Cafe) |
| 225140 | 로비 배경을 변경할 수 있습니다. (병원 로비) | You can change the background of the lobby. (Hospital Lobby) |
| 225141 | 로비 배경을 변경할 수 있습니다. (낮의 시장)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Market)<br><br>Can be obtained as an outing achievement reward |
| 225142 | 로비 배경을 변경할 수 있습니다. (영지 거리)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Town Street)<br><br>Can be obtained as an outing achievement reward |
| 225150 | 로비 배경을 변경할 수 있습니다. (낮의 해수욕장)<br><br>마녀는 쉬고 싶어!! 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Bathing Beach)<br><br>Can be obtained as a Wicked Vacation!! Event Story reward |
| 225151 | 로비 배경을 변경할 수 있습니다. (노을진 해수욕장)<br><br>마녀는 쉬고 싶어!! 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Bathing Beach at Sunset)<br><br>Can be obtained as a Wicked Vacation!! Event Story reward |
| 225152 | 로비 배경을 변경할 수 있습니다. (한밤의 해수욕장)<br><br>엔들리스 서머 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Midnight Beach)<br><br>Can be obtained as a reward for viewing the Endless Summer Event Story. |
| 225153 | 로비 배경을 변경할 수 있습니다. (해변 레스토랑)<br><br>엔들리스 서머 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Beach Restaurant)<br><br>Can be obtained as a reward for viewing the Endless Summer Event Story. |
| 225161 | 로비 배경을 변경할 수 있습니다. (공주의 처소)<br><br>달려라! 달밤의 토끼 질주! 이벤트 스토리 전투 보상으로 획득 가능 | You can change the background of the lobby. (Princess's Abode)<br><br>Can be obtained as a battle reward for the RUN, RABBIT! GO ON A MIDNIGHT RUN! Event Story. |
| 225162 | 로비 배경을 변경할 수 있습니다. (가온풍 궁전 복도)<br><br>달려라! 달밤의 토끼 질주! 이벤트 스토리 전투 보상으로 획득 가능 | You can change the background of the lobby. (Gaon Palace Corridor)<br><br>Can be obtained as a battle reward for the RUN, RABBIT! GO ON A MIDNIGHT RUN! Event Story. |
| 225171 | 로비 배경을 변경할 수 있습니다. (어두운 숲)<br><br><빨간 모자와 나쁜 늑대> 이벤트 스토리 전투 보상으로 획득 가능 | You can change the background of the lobby (Dark Forest).<br><br>Can be obtained as a battle reward for the "Red Riding Hood and the Bad Wolf" Event Story. |
| 225172 | 로비 배경을 변경할 수 있습니다. (악몽의 들판)<br><br><빨간 모자와 나쁜 늑대> 이벤트 스토리 전투 보상으로 획득 가능 | You can change the background of the lobby (Field of Nightmare).<br><br>Can be obtained as a battle reward for the "Red Riding Hood and the Bad Wolf" Event Story. |
| 225181 | 로비 배경을 변경할 수 있습니다. (눈 덮인 아케나인 광장)<br><br><푹신 따끈 크마리스스!> 이벤트 스토리 전투 보상으로 획득 가능 | You can change the background of the lobby. (Snow-Covered Arkenine Square)<br><br>Can be obtained as a reward for viewing the A Cozy Kumawreaths! Event Story. |
| 225182 | 로비 배경을 변경할 수 있습니다. (눈 덮인 영지 거리)<br><br><푹신 따끈 크마리스스!> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Snow-Covered Town Street)<br><br>Can be obtained as a reward for viewing the A Cozy Kumawreaths! Event Story. |
| 225191 | 로비 배경을 변경할 수 있습니다. (1주년 기념 선상 파티장)<br><br><선상 파티 대소동> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (1st Anniversary Maritime Mirth Venue)<br><br>Can be obtained as a reward for viewing the "Maritime Mirth and Mayhem" Event Story. |
| 225201 | 로비 배경을 변경할 수 있습니다. (메이드 카페)<br><br><맛있어져라! 메이드 대작전> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Maid Cafe)<br><br>Can be obtained as a reward for viewing the Taste Perfection Operation Maid Event Story. |
| 225211 | 로비 배경을 변경할 수 있습니다. (어둠의 학교 교실)<br><br><에버스쿨! ~타도! 어둠의 학생회장~> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Sinister School Classroom)<br><br>Can be obtained as a reward for viewing the Everschool! ~Vanquish the Sinister Student President!~ Event Story. |
| 225212 | 로비 배경을 변경할 수 있습니다. (어둠의 학교 옥상)<br><br><에버스쿨! ~타도! 어둠의 학생회장~> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Sinister School Rooftop)<br><br>Can be obtained as a reward for viewing the Everschool! ~Vanquish the Sinister Student President!~ Event Story. |
| 225213 | 로비 배경을 변경할 수 있습니다. (어둠의 학교 복도)<br><br><에버스쿨! ~타도! 어둠의 학생회장~> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Sinister School Corridor)<br><br>Can be obtained as a reward for viewing the Everschool! ~Vanquish the Sinister Student President!~ Event Story. |
| 225221 | 로비 배경을 변경할 수 있습니다. (가온의 밤 축제 거리)<br><br><가온 여름 축제> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Gaon's Night Festival Street)<br><br>Can be obtained as a reward for viewing the Gaon Summer Festival Event Story. |
| 225231 | 로비 배경을 변경할 수 있습니다. (칼라르 설산 절벽)<br><br><메리해피메리 ~결혼 전쟁~> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Chalar Snow Mountain Cliff)<br><br>Can be obtained as a reward for viewing the Merry Happy Marry ~Wedding War~ Event Story. |
| 225232 | 로비 배경을 변경할 수 있습니다. (아케나인 예식장)<br><br><메리해피메리 ~결혼 전쟁~> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Arkenine Wedding Hall)<br><br>Can be obtained as a reward for viewing the Merry Happy Marry ~Wedding War~ Event Story. |
| 225241 | 로비 배경을 변경할 수 있습니다. (나무 미로)<br><br><오싹오싹! 미로 탈출 대소동> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Wooden Maze)<br><br>Can be obtained as a reward for viewing the Spooktacular! Maze Maneuver Madness Event Story. |
| 225251 | 로비 배경을 변경할 수 있습니다. (서커스 무대)<br><br><문라이트 바니 서커스> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Circus Stage)<br><br>Can be obtained as a reward for viewing the Moonlight Bunny Circus Event Story. |
| 225261 | 로비 배경을 변경할 수 있습니다. (이브의 날 메카 컨벤션)<br><br><고요한 Bomb 거룩한 Bomb> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Eve's Day Mech Convention)<br><br>Can be obtained as a reward for viewing the Silent Bomb, Holy Bomb Event Story. |
| 225271 | 로비 배경을 변경할 수 있습니다. (가온의 낮 신년제 거리)<br><br><만사형통?! 가온 신년제> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Street of Gaon's New Year's Festival)<br><br>Can be obtained as a reward for viewing the Gaon New Year's Festival Event Story. |
| 225281 | 로비 배경을 변경할 수 있습니다. (로제의 심상세계)<br><br><기록 되지 않은 미래> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Rose's Imaginary World)<br><br>Can be obtained as a reward for viewing The Unwritten Future Event Story. |
| 225291 | 로비 배경을 변경할 수 있습니다. (노심굴)<br><br><천리주단기> 이벤트 스토리 열람 보상으로 획득 가능 | You can change the background of the lobby. (Reactor Core Cave)<br><br>Can be obtained as a reward for viewing the Riding Alone for Thousands of Miles Event Story. |
| 225400 | 로비 배경을 변경할 수 있습니다. (방주)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Ark)<br><br>Can be obtained as an outing achievement reward |
| 225401 | 로비 배경을 변경할 수 있습니다. (낮의 해변가)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Beach)<br><br>Can be obtained as an outing achievement reward |
| 225402 | 로비 배경을 변경할 수 있습니다. (밤의 해변가)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Beach)<br><br>Can be obtained as an outing achievement reward |
| 225403 | 로비 배경을 변경할 수 있습니다. (낮의 성벽 산책로)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Castle Wall Trail)<br><br>Can be obtained as an outing achievement reward |
| 225404 | 로비 배경을 변경할 수 있습니다. (밤의 성벽 산책로)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Castle Wall Trail)<br><br>Can be obtained as an outing achievement reward |
| 225405 | 로비 배경을 변경할 수 있습니다. (낮의 벚꽃 동산)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Cherry Blossom Hill)<br><br>Can be obtained as an outing achievement reward |
| 225406 | 로비 배경을 변경할 수 있습니다. (낮의 종달새 숲)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Skylark Forest)<br><br>Can be obtained as an outing achievement reward |
| 225407 | 로비 배경을 변경할 수 있습니다. (밤의 종달새 숲)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Skylark Forest)<br><br>Can be obtained as an outing achievement reward |
| 225408 | 로비 배경을 변경할 수 있습니다. (밤의 은하수 언덕)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Milky Way Hill)<br><br>Can be obtained as an outing achievement reward |
| 225409 | 로비 배경을 변경할 수 있습니다. (밤의 달빛 호숫가)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Moonlit Lakeside)<br><br>Can be obtained as an outing achievement reward |
| 225501 | 기본 제공되는 프레임 | Basic Frame |
| 225502 | 기본 제공되는 프레임 | Basic Frame |
| 225503 | 기본 제공되는 프레임 | Basic Frame |
| 225504 | 기본 제공되는 프레임 | Basic Frame |
| 225505 | 기본 제공되는 프레임 | Basic Frame |
| 225506 | 기본 제공되는 프레임 | Basic Frame |
| 225507 | 기본 제공되는 프레임 | Basic Frame |
| 225601 | 아르바이트 100회 달성 시 획득하는 프레임 | Frame reward for completing 100 Part-Time Jobs. |
| 225602 | 아르바이트 1500회 달성 시 획득하는 프레임 | Frame reward for completing 1500 Part-Time Jobs. |
| 225603 | 아르바이트 10000회 달성 시 획득하는 프레임 | Frame reward for completing 10000 Part-Time Jobs. |
| 225611 | 원정 10회 달성 시 획득하는 프레임 | Frame reward for completing 10 Expeditions. |
| 225612 | 원정 150회 달성 시 획득하는 프레임 | Frame reward for completing 150 Expeditions. |
| 225613 | 원정 1200회 달성 시 획득하는 프레임 | Frame reward for completing 1200 Expeditions. |
| 225621 | 선물하기 20회 달성 시 획득하는 프레임 | Frame reward for giving 20 gifts. |
| 225622 | 선물하기 200회 달성 시 획득하는 프레임 | Frame reward for giving 200 gifts. |
| 225623 | 선물하기 1000회 달성 시 획득하는 프레임 | Frame reward for giving 1000 gifts. |
| 225631 | 인연 스토리 엔딩을 클리어한 정령 2개 달성 시 획득하는 프레임 | Frame obtained upon reaching a Love Story ending with 2 Souls |
| 225632 | 인연 스토리 엔딩을 클리어한 정령 15개 달성 시 획득하는 프레임 | Frame obtained upon reaching a Love Story ending with 15 Souls |
| 225633 | 인연 스토리 엔딩을 클리어한 정령 31개 달성 시 획득하는 프레임 | Frame obtained upon reaching a Love Story ending with 31 Souls |
| 225641 | 좋아요 받기 50회 달성 시 획득하는 프레임 | Frame reward for receiving 50 likes. |
| 225642 | 좋아요 받기 100회 달성 시 획득하는 프레임 | Frame reward for receiving 100 likes. |
| 225643 | 좋아요 받기 200회 달성 시 획득하는 프레임 | Frame reward for receiving 200 likes. |
| 225651 | 좋아요 주기 50회 달성 시 획득하는 프레임 | Frame reward for giving 50 likes. |
| 225652 | 좋아요 주기 100회 달성 시 획득하는 프레임 | Frame reward for giving 100 likes. |
| 225653 | 좋아요 주기 200회 달성 시 획득하는 프레임 | Frame reward for giving 200 likes. |
| 225654 | 상업지구 내 오브젝트 파괴 2000회 달성 시 획득하는 프레임 | Frame reward for destroying 2000 obstructions within the Commercial District. |
| 225655 | 상업지구 내 오브젝트 파괴 5800회 달성 시 획득하는 프레임 | Frame reward for destroying 5800 obstructions within the Commercial District. |
| 225656 | 상업지구 내 오브젝트 파괴 15500회 달성 시 획득하는 프레임 | Frame reward for destroying 15500 obstructions within the Commercial District. |
| 225657 | 악령 토벌(종말을 부르는 인형 재클린) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 3 in Evil Soul Subjugation (Doomsday Doll Jacqueline) |
| 225658 | 악령 토벌(종말을 부르는 인형 재클린) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 2 in Evil Soul Subjugation (Doomsday Doll Jacqueline) |
| 225659 | 악령 토벌(종말을 부르는 인형 재클린) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing the first place in Evil Soul Subjugation (Doomsday Doll Jacqueline) |
| 225660 | 미니 게임(몰려와요 마물의 숲) 완료 시 획득하는 프레임 | Frame obtained upon completing the Mini Game (Waving Forest of Monsters) |
| 225661 | 미니 게임(몰려와요 마물의 숲) 포인트 랭킹 501~1000위 달성 시 획득하는 프레임 | Frame obtained upon being ranked 501–1000 in the Mini Game (Waving Forest of Monsters) |
| 225662 | 미니 게임(몰려와요 마물의 숲) 포인트 랭킹 201~500위 이내 달성 시 획득하는 프레임 | Frame obtained upon being ranked 201–500 in the Mini Game (Waving Forest of Monsters) |
| 225663 | 미니 게임(몰려와요 마물의 숲) 포인트 랭킹 3위 달성 시 획득하는 프레임<br><br>획득 가능 기간 종료(~2024. 01) | Frame obtained upon ranking third in the Mini Game (Waving Forest of Monsters)<br><br>No longer available (since the end of January 2024) |
| 225664 | 미니 게임(몰려와요 마물의 숲) 포인트 랭킹 2위 달성 시 획득하는 프레임<br><br>획득 가능 기간 종료(~2024. 01) | Frame obtained upon ranking second in the Mini Game (Waving Forest of Monsters)<br><br>No longer available (since the end of January 2024) |
| 225665 | 미니 게임(몰려와요 마물의 숲) 포인트 랭킹 1위 달성 시 획득하는 프레임<br><br>획득 가능 기간 종료(~2024. 01) | Frame obtained upon ranking first in the Mini Game (Waving Forest of Monsters)<br><br>No longer available (since the end of January 2024) |
| 225666 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 1,000 in Evil Soul Subjugation (Vivienne, the Witch who destroyed the world) |
| 225667 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 300 in Evil Soul Subjugation (Vivienne, the Witch who destroyed the world) |
| 225668 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 100 in Evil Soul Subjugation (Vivienne, the Witch who destroyed the world) |
| 225669 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 3 in Evil Soul Subjugation (Vivienne, the Witch who destroyed the world) |
| 225670 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 2 in Evil Soul Subjugation (Vivienne, the Witch who destroyed the world) |
| 225671 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing the first place in Evil Soul Subjugation (Vivienne, the Witch who destroyed the world) |
| 225672 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 1,000 in Evil Soul Subjugation (Ayame, the ghost who weeps bitter tears) |
| 225673 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 300 in Evil Soul Subjugation (Ayame, the ghost who weeps bitter tears) |
| 225674 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 100 in Evil Soul Subjugation (Ayame, the ghost who weeps bitter tears) |
| 225675 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 3 in Evil Soul Subjugation (Ayame, the ghost who weeps bitter tears) |
| 225676 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 2 in Evil Soul Subjugation (Ayame, the ghost who weeps bitter tears) |
| 225677 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing the first place  in Evil Soul Subjugation (Ayame, the ghost who weeps bitter tears) |
| 225678 | 악령 토벌(광기에 물든 야수 아이라) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 1,000 in Evil Soul Subjugation (Mad Beast Aira) |
| 225679 | 악령 토벌(광기에 물든 야수 아이라) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 300 in Evil Soul Subjugation (Mad Beast Aira) |
| 225680 | 악령 토벌(광기에 물든 야수 아이라) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 100 in Evil Soul Subjugation (Mad Beast Aira) |
| 225681 | 악령 토벌(광기에 물든 야수 아이라) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 3 in Evil Soul Subjugation (Mad Beast Aira) |
| 225682 | 악령 토벌(광기에 물든 야수 아이라) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 2 in Evil Soul Subjugation (Mad Beast Aira) |
| 225683 | 악령 토벌(광기에 물든 야수 아이라) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing the first place in Evil Soul Subjugation (Mad Beast Aira) |
| 225684 | 악령 토벌(종말을 부르는 인형 재클린) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 1,000 in Evil Soul Subjugation (Doomsday Doll Jacqueline) |
| 225685 | 악령 토벌(종말을 부르는 인형 재클린) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 300 in Evil Soul Subjugation (Doomsday Doll Jacqueline) |
| 225686 | 악령 토벌(종말을 부르는 인형 재클린) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 100 in Evil Soul Subjugation (Doomsday Doll Jacqueline) |
| 225687 | 악령 토벌(비탄의 성녀 캐서린) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 1,000 in Evil Soul Subjugation (Saint of Sorrow Catherine) |
| 225688 | 악령 토벌(비탄의 성녀 캐서린) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 300 in Evil Soul Subjugation (Saint of Sorrow Catherine) |
| 225689 | 악령 토벌(비탄의 성녀 캐서린) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 100 in Evil Soul Subjugation (Saint of Sorrow Catherine) |
| 225690 | 악령 토벌(비탄의 성녀 캐서린) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 3 in Evil Soul Subjugation (Saint of Sorrow Catherine) |
| 225691 | 악령 토벌(비탄의 성녀 캐서린) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 2 in Evil Soul Subjugation (Saint of Sorrow Catherine) |
| 225692 | 악령 토벌(비탄의 성녀 캐서린) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing the first place in Evil Soul Subjugation (Saint of Sorrow Catherine) |
| 225693 | 돌아온 이상한 꿈결의 클로이 최대 피해 보상 3000만 달성 시 획득하는 프레임 | Frame obtained upon reaching 30 million of max damage reward for Chloe's Strange Dream Is Back |
| 225694 | 악령 토벌(전쟁의 사도 아드리안) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 1,000 in Evil Soul Subjugation (Adrianne, the Apostle of War) |
| 225695 | 악령 토벌(전쟁의 사도 아드리안) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 300 in Evil Soul Subjugation (Adrianne, the Apostle of War) |
| 225696 | 악령 토벌(전쟁의 사도 아드리안) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 100 in Evil Soul Subjugation (Adrianne, the Apostle of War) |
| 225697 | 악령 토벌(전쟁의 사도 아드리안) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 3 in Evil Soul Subjugation (Adrianne, the Apostle of War) |
| 225698 | 악령 토벌(전쟁의 사도 아드리안) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within top 2 in Evil Soul Subjugation (Adrianne, the Apostle of War) |
| 225699 | 악령 토벌(전쟁의 사도 아드리안) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing first place in Evil Soul Subjugation (Adrianne, the Apostle of War) |
| 225700 | 1주년 기념 특별 보상으로 획득하는 프레임 | A frame that can be obtained as a special 1st anniversary reward. |
| 225701 | 2주년 기념 특별 보상으로 획득하는 프레임 | A frame that can be obtained as a special 2nd anniversary reward. |
| 225702 | 미니 게임(몰려와요!? 마물의 숲) 포인트 랭킹 101~200위 달성 시 획득하는 프레임 | Frame obtained upon being ranked 101–200 in the Mini Game (Waving Forest of Monsters) |
| 225703 | 미니 게임(몰려와요!? 마물의 숲) 포인트 랭킹 51~100위 달성 시 획득하는 프레임 | Frame obtained upon being ranked 51–100 in the Mini Game (Waving Forest of Monsters) |
| 225704 | 미니 게임(몰려와요!? 마물의 숲) 포인트 랭킹 1~50위 달성 시 획득하는 프레임 | Frame obtained upon being ranked 1–50 in the Mini Game (Waving Forest of Monsters) |
| 225705 | 악령 토벌(피에 물든 검귀 아키) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 1,000 in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) |
| 225706 | 악령 토벌(피에 물든 검귀 아키) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 300 in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) |
| 225707 | 악령 토벌(피에 물든 검귀 아키) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 100 in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) |
| 225708 | 악령 토벌(피에 물든 검귀 아키) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 3 in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) |
| 225709 | 악령 토벌(피에 물든 검귀 아키) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 2 in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) |
| 225710 | 악령 토벌(피에 물든 검귀 아키) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing First Place in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) |
| 225711 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 1,000 in Evil Soul Subjugation (Doom Piercer Lizelotte) |
| 225712 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 300 in Evil Soul Subjugation (Doom Piercer Lizelotte) |
| 225713 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 100 in Evil Soul Subjugation (Doom Piercer Lizelotte) |
| 225714 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 3 in Evil Soul Subjugation (Doom Piercer Lizelotte) |
| 225715 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 2 in Evil Soul Subjugation (Doom Piercer Lizelotte) |
| 225716 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing First Place in Evil Soul Subjugation (Doom Piercer Lizelotte) |
| 225717 | 악령 토벌(흉몽의 나비 나이아) 최종 1000위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 1,000 in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) |
| 225718 | 악령 토벌(흉몽의 나비 나이아) 최종 300위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 300 in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) |
| 225719 | 악령 토벌(흉몽의 나비 나이아) 최종 100위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 100 in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) |
| 225720 | 악령 토벌(흉몽의 나비 나이아) 최종 3위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 3 in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) |
| 225721 | 악령 토벌(흉몽의 나비 나이아) 최종 2위 이내 달성 시 획득하는 프레임 | Frame obtained upon securing a place within the Top 2 in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) |
| 225722 | 악령 토벌(흉몽의 나비 나이아) 최종 1위 달성 시 획득하는 프레임 | Frame obtained upon securing first place in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) |
| 225723 | 인형으로 꾸며진 애정 가득한 프레임 | A frame decorated with stuffed toys, overflowing with affection |
| 225724 | 3주년 기념 특별 보상으로 획득하는 프레임 | A frame that can be obtained as a special 3rd anniversary reward. |
| 225799 | 춘절을 기념하여 제작된 특별한 프레임 |  |
| 225900 | 로비 배경을 변경할 수 있습니다. (낮의 방주)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Ark)<br><br>Can be obtained as an outing achievement reward |
| 225901 | 로비 배경을 변경할 수 있습니다. (낮의 종달새 숲)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Skylark Forest)<br><br>Can be obtained as an outing achievement reward |
| 225902 | 로비 배경을 변경할 수 있습니다. (낮의 해변가)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Beach)<br><br>Can be obtained as an outing achievement reward |
| 225903 | 로비 배경을 변경할 수 있습니다. (낮의 벚꽃 동산)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Cherry Blossom Hill)<br><br>Can be obtained as an outing achievement reward |
| 225904 | 로비 배경을 변경할 수 있습니다. (낮의 성벽 산책로)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Daytime Castle Wall Trail)<br><br>Can be obtained as an outing achievement reward |
| 225905 | 로비 배경을 변경할 수 있습니다. (밤의 달빛 호숫가)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Moonlit Lakeside)<br><br>Can be obtained as an outing achievement reward |
| 225906 | 로비 배경을 변경할 수 있습니다. (밤의 은하수 언덕)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Milky Way Hill)<br><br>Can be obtained as an outing achievement reward |
| 225907 | 로비 배경을 변경할 수 있습니다. (밤의 해변가)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Beach)<br><br>Can be obtained as an outing achievement reward |
| 225908 | 로비 배경을 변경할 수 있습니다. (밤의 종달새 숲)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Skylark Forest)<br><br>Can be obtained as an outing achievement reward |
| 225909 | 로비 배경을 변경할 수 있습니다. (밤의 성벽 산책로)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Castle Wall Trail)<br><br>Can be obtained as an outing achievement reward |
| 225910 | 로비 배경을 변경할 수 있습니다. (밤의 종달새 숲)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Skylark Forest)<br><br>Can be obtained as an outing achievement reward |
| 225911 | 로비 배경을 변경할 수 있습니다. (밤의 성벽 산책로)<br><br>나들이 업적 보상으로 획득 가능 | You can change the background of the lobby. (Nighttime Castle Wall Trail)<br><br>Can be obtained as an outing achievement reward |
| 226001 | 미카와 시하의 하루의 일러스트를 획득합니다. | Obtain Mica and Seeha's Day illustration. |
| 226002 | 데이트 어 소울 이벤트 스토리의 일러스트를 획득합니다. | Unlocks an illustration of the Date A Soul event story. |
| 226005 | 에덴 갓 탤런트의 일러스트를 획득합니다. | Unlocks an illustration of Eden's Got Talent. |
| 226006 | 거미님 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 대상 당선작입니다. | Contains an illustration by 거미.<br>This illustration is the grand prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 226007 | 주상절리님 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 금상 당선작입니다. | Contains an illustration by 주상절리.<br>This illustration is the gold prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 226008 | yuugen님 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 은상 당선작입니다. | Contains an illustration by yuugen.<br>This illustration is the silver prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 226009 | 귄터님 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 특별상 당선작입니다. | Contains an illustration by 귄터.<br>This illustration is the special prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 226010 | 고꾸닥님 일러스트를 획득합니다.<br>해당 일러스트는 2024년 에버소울 크리에이티브 컨테스트 일러스트 부문 특별상 당선작입니다. | Contains an illustration by 고꾸닥.<br>This illustration is the special prize-winning entry in the illustration category of the 2024 Eversoul Creative Contest. |
| 226101 | 에덴 연합 작전: 트로이카 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Bronze tier in [Operation Eden Alliance] Troyca. |
| 226102 | 에덴 연합 작전: 트로이카 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Silver tier in [Operation Eden Alliance] Troyca. |
| 226103 | 에덴 연합 작전: 트로이카 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Gold tier in [Operation Eden Alliance] Troyca. |
| 226104 | 에덴 연합 작전: 트로이카 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Platinum tier in [Operation Eden Alliance] Troyca. |
| 226105 | 에덴 연합 작전: 트로이카 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Master tier in [Operation Eden Alliance] Troyca. |
| 226106 | 에덴 연합 작전: 트로이카 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Challenger tier in [Operation Eden Alliance] Troyca. |
| 226107 | 에덴 연합 작전: 트로이카 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Troyca. |
| 226108 | 에덴 연합 작전: 트로이카 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Troyca. |
| 226109 | 에덴 연합 작전: 트로이카 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Troyca. |
| 226110 | 에덴 연합 작전: 트로이카 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Troyca. |
| 226111 | 에덴 연합 작전: 아우렐리아 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Bronze tier in [Operation Eden Alliance] Aurelia. |
| 226112 | 에덴 연합 작전: 아우렐리아 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Silver tier in [Operation Eden Alliance] Aurelia. |
| 226113 | 에덴 연합 작전: 아우렐리아 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Gold tier in [Operation Eden Alliance] Aurelia. |
| 226114 | 에덴 연합 작전: 아우렐리아 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Platinum tier in [Operation Eden Alliance] Aurelia. |
| 226115 | 에덴 연합 작전: 아우렐리아 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Master tier in [Operation Eden Alliance] Aurelia. |
| 226116 | 에덴 연합 작전: 아우렐리아 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Challenger tier in [Operation Eden Alliance] Aurelia. |
| 226117 | 에덴 연합 작전: 아우렐리아 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Aurelia. |
| 226118 | 에덴 연합 작전: 아우렐리아 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Aurelia. |
| 226119 | 에덴 연합 작전: 아우렐리아 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Aurelia. |
| 226120 | 에덴 연합 작전: 아우렐리아 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Aurelia. |
| 226121 | 에덴 연합 작전: 타브리아 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Bronze tier in [Operation Eden Alliance] Tabria. |
| 226122 | 에덴 연합 작전: 타브리아 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Silver tier in [Operation Eden Alliance] Tabria. |
| 226123 | 에덴 연합 작전: 타브리아 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Gold tier in [Operation Eden Alliance] Tabria. |
| 226124 | 에덴 연합 작전: 타브리아 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Platinum tier in [Operation Eden Alliance] Tabria. |
| 226125 | 에덴 연합 작전: 타브리아 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Master tier in [Operation Eden Alliance] Tabria. |
| 226126 | 에덴 연합 작전: 타브리아 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching the Challenger tier in [Operation Eden Alliance] Tabria. |
| 226127 | 에덴 연합 작전: 타브리아 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Tabria. |
| 226128 | 에덴 연합 작전: 타브리아 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Tabria. |
| 226129 | 에덴 연합 작전: 타브리아 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Tabria. |
| 226130 | 에덴 연합 작전: 타브리아 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Tabria. |
| 226131 | 에덴 연합 작전: 페이렌 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Bronze tier in [Operation Eden Alliance] Fayren. |
| 226132 | 에덴 연합 작전: 페이렌 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Silver tier in [Operation Eden Alliance] Fayren. |
| 226133 | 에덴 연합 작전: 페이렌 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Gold tier in [Operation Eden Alliance] Fayren. |
| 226134 | 에덴 연합 작전: 페이렌 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Platinum tier in [Operation Eden Alliance] Fayren. |
| 226135 | 에덴 연합 작전: 페이렌 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Master tier in [Operation Eden Alliance] Fayren. |
| 226136 | 에덴 연합 작전: 페이렌 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Challenger tier in [Operation Eden Alliance] Fayren. |
| 226137 | 에덴 연합 작전: 페이렌 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Fayren. |
| 226138 | 에덴 연합 작전: 페이렌 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Fayren. |
| 226139 | 에덴 연합 작전: 페이렌 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Fayren. |
| 226140 | 에덴 연합 작전: 페이렌 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Fayren. |
| 226141 | 에덴 연합 작전: 칼라르 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Bronze tier in [Operation Eden Alliance] Chalar. |
| 226142 | 에덴 연합 작전: 칼라르 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Silver tier in [Operation Eden Alliance] Chalar. |
| 226143 | 에덴 연합 작전: 칼라르 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Gold tier in [Operation Eden Alliance] Chalar. |
| 226144 | 에덴 연합 작전: 칼라르 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Platinum tier in [Operation Eden Alliance] Chalar. |
| 226145 | 에덴 연합 작전: 칼라르 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Master tier in [Operation Eden Alliance] Chalar. |
| 226146 | 에덴 연합 작전: 칼라르 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Challenger tier in [Operation Eden Alliance] Chalar. |
| 226147 | 에덴 연합 작전: 칼라르 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Chalar. |
| 226148 | 에덴 연합 작전: 칼라르 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Chalar. |
| 226149 | 에덴 연합 작전: 칼라르 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Chalar. |
| 226150 | 에덴 연합 작전: 칼라르 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Chalar. |
| 226151 | 에덴 연합 작전: 가온 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Bronze tier in [Operation Eden Alliance] Gaon. |
| 226152 | 에덴 연합 작전: 가온 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Silver tier in [Operation Eden Alliance] Gaon. |
| 226153 | 에덴 연합 작전: 가온 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Gold tier in [Operation Eden Alliance] Gaon. |
| 226154 | 에덴 연합 작전: 가온 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Platinum tier in [Operation Eden Alliance] Gaon. |
| 226155 | 에덴 연합 작전: 가온 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Master tier in [Operation Eden Alliance] Gaon. |
| 226156 | 에덴 연합 작전: 가온 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Challenger tier in [Operation Eden Alliance] Gaon. |
| 226157 | 에덴 연합 작전: 가온 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Gaon. |
| 226158 | 에덴 연합 작전: 가온 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Gaon. |
| 226159 | 에덴 연합 작전: 가온 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Gaon. |
| 226160 | 에덴 연합 작전: 가온 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Gaon. |
| 226161 | 에덴 연합 작전: 솔레이 편에서 브론즈 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Bronze tier in [Operation Eden Alliance] Solrey. |
| 226162 | 에덴 연합 작전: 솔레이 편에서 실버 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Silver tier in [Operation Eden Alliance] Solrey. |
| 226163 | 에덴 연합 작전: 솔레이 편에서 골드 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Gold tier in [Operation Eden Alliance] Solrey. |
| 226164 | 에덴 연합 작전: 솔레이 편에서 플래티넘 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Platinum tier in [Operation Eden Alliance] Solrey. |
| 226165 | 에덴 연합 작전: 솔레이 편에서 마스터 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Master tier in [Operation Eden Alliance] Solrey. |
| 226166 | 에덴 연합 작전: 솔레이 편에서 챌린저 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Challenger tier in [Operation Eden Alliance] Solrey . |
| 226167 | 에덴 연합 작전: 솔레이 편에서 레전더리 티어 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Legendary tier in [Operation Eden Alliance] Solrey. |
| 226168 | 에덴 연합 작전: 솔레이 편에서 레전더리 티어 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in Legendary tier in [Operation Eden Alliance] Solrey. |
| 226169 | 에덴 연합 작전: 솔레이 편에서 레전더리 티어 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in Legendary tier in [Operation Eden Alliance] Solrey. |
| 226170 | 에덴 연합 작전: 솔레이 편에서 레전더리 티어 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in Legendary tier in [Operation Eden Alliance] Solrey. |
| 226171 | 에덴 연합 작전: 여름 합숙 훈련 편에서 획득 가능한 스티커. | A sticker that can be obtained in Operation Eden Alliance: Summer Training Camp. |
| 226172 | 에덴 연합 작전: 여름 합숙 훈련 편 본선전에서 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching third place in the Finals of [Operation Eden Alliance] Summer Training Camp. |
| 226173 | 에덴 연합 작전: 여름 합숙 훈련 편 본선전에서 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching second place in the Finals of [Operation Eden Alliance] Summer Training Camp. |
| 226174 | 에덴 연합 작전: 여름 합숙 훈련 편 본선전에서 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching first place in the Finals of [Operation Eden Alliance] Summer Training Camp. |
| 226201 | 엘나스 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Elnath. |
| 226202 | 아케나인 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Arkenine. |
| 226203 | 콜브 초원 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Colve Meadow. |
| 226204 | 다이난 호수 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Lake Dynan. |
| 226205 | 하얀 울새 숲 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying White Robin Forest. |
| 226206 | 베르트 산맥 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Vert Mountains. |
| 226207 | 비노 협곡 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Vino Valley. |
| 226208 | 렉타 황무지 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Rechtar Wasteland. |
| 226209 | 쿠르 사바나 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Cur Savannah. |
| 226210 | 아르코 이리스 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Arco Iris. |
| 226211 | 모레노 사막 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Morreno Desert. |
| 226212 | 라피아 정글 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Raffia Jungle. |
| 226213 | 반딧불이의 둥지 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Nest of Fireflies. |
| 226214 | 나델 고산지 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Nadel Mountains. |
| 226215 | 그림자 없는 땅 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Shadowless Lands. |
| 226216 | 유령도시 모르투스 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Ghost City Mortus. |
| 226217 | 버려진 항구 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Forsaken Harbor. |
| 226218 | 메티아스 호 갑판 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Mettias Deck. |
| 226219 | 가르디눔 대설원 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Gardinum Snowfield. |
| 226220 | 루푸스 요새 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Lupus Fortress. |
| 226221 | 칸델레로 얼음 산맥 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Candellero Mountains. |
| 226222 | 코르텍스 호 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying The Cortex. |
| 226223 | 오레올 산맥 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Aureole Mountains. |
| 226224 | 시조의 연안 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Founder's Coast. |
| 226225 | 아페이온 해식동굴 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Apeiron Sea Cave. |
| 226226 | 루멘 성 입구 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Lumen Castle Entrance. |
| 226227 | 엠포리움 연구소 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Emporium Laboratory. |
| 226228 | 땅의 등대 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Lighthouse of the Earth. |
| 226229 | 아우렐리아 심해 유적 지역 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Aurelian Deep Sea Ruins. |
| 226230 | 밤의 도시 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Night City. |
| 226231 | 연옥으로 가는 길 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Road to Purgatory. |
| 226232 | 별의 등대 점령 시 획득 가능한 스티커. | A sticker that can be obtained upon occupying the Lighthouse of the Stars. |
| 226233 | 별의 바다 점령 시 획득 가능한 스티커 | A sticker that can be obtained upon occupying the Sea of Stars. |
| 226234 | 하늘뱃길 점령 시 획득 가능한 스티커. | A sticker that can be obtained upon occupying the Sky Fareway. |
| 226235 | 침묵의 숲 점령 시 획득 가능한 스티커. | A sticker that can be obtained upon occupying the Forest of Silence. |
| 226236 | 아우렐리아 시가지 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Downtown Aurelia. |
| 226237 | 아우렐리아 대신전 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Aurelia Great Temple. |
| 226238 | 페이렌 외곽 점령 시 획득 가능한 스티커. | A sticker that can be obtained when occupying Fayren Outskirts. |
| 226239 | 페이렌 수정굴 점령 시 획득 가능한 스티커. | A sticker that can be obtained upon occupying the Fayren Crystal Cave. |
| 226301 | 에리카의 연금술 최초 80회 이용 시 획득 가능한 스티커. | A sticker that can be obtained after the initial 80th time you use Erika's Alchemy. |
| 226302 | 정령들과 보낸 즐거운 한때를 기념하는 스티커.<br>함께 먹은 치킨이 유난히 맛있었던 건 <br>특별한 애정이 들어있기 때문이겠지. | A sticker to remember a joyful time spent with Souls.<br>The chicken tasted better than ever,<br>probably thanks to the special bond we shared. |
| 226303 | 부드럽고 달콤한 맛이 나는 초콜릿 모양의 스티커. | A sticker designed to look like smooth, sweet chocolate. |
| 226401 | 악령 토벌(종말을 부르는 인형 재클린) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doomsday Doll Jacqueline) in first place. |
| 226402 | 악령 토벌(종말을 부르는 인형 재클린) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doomsday Doll Jacqueline) in second place. |
| 226403 | 악령 토벌(종말을 부르는 인형 재클린) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doomsday Doll Jacqueline) in third place. |
| 226404 | 악령 토벌(종말을 부르는 인형 재클린) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doomsday Doll Jacqueline) in 4th–100th place. |
| 226405 | 악령 토벌(종말을 부르는 인형 재클린) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Doomsday Doll Jacqueline). |
| 226406 | 악령 토벌(비탄의 성녀 캐서린) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Saint of Sorrow Catherine) in first place. |
| 226407 | 악령 토벌(비탄의 성녀 캐서린) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Saint of Sorrow Catherine) in second place. |
| 226408 | 악령 토벌(비탄의 성녀 캐서린) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Saint of Sorrow Catherine) in third place. |
| 226409 | 악령 토벌(비탄의 성녀 캐서린) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Saint of Sorrow Catherine) in 4th–100th place. |
| 226410 | 악령 토벌(비탄의 성녀 캐서린) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Saint of Sorrow Catherine). |
| 226411 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Witch Who Destroyed the World Vivienne) in first place. |
| 226412 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Witch Who Destroyed the World Vivienne) in second place. |
| 226413 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Witch Who Destroyed the World Vivienne) in third place. |
| 226414 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Witch Who Destroyed the World Vivienne) in 4th–100th place. |
| 226415 | 악령 토벌(세계를 멸망시킨 마녀 비비안) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Witch Who Destroyed the World Vivienne). |
| 226416 | 악령 토벌(전쟁의 사도 아드리안) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Apostle of War Adrianne) in First Place. |
| 226417 | 악령 토벌(전쟁의 사도 아드리안) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Apostle of War Adrianne) in Second Place. |
| 226418 | 악령 토벌(전쟁의 사도 아드리안) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Apostle of War Adrianne) in Third Place. |
| 226419 | 악령 토벌(전쟁의 사도 아드리안) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Apostle of War Adrianne) in 4th–100th place. |
| 226420 | 악령 토벌(전쟁의 사도 아드리안) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Apostle of War Adrianne). |
| 226421 | 악령 토벌(광기에 물든 야수 아이라) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Mad Beast Aira) in first place. |
| 226422 | 악령 토벌(광기에 물든 야수 아이라) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Mad Beast Aira) in second place. |
| 226423 | 악령 토벌(광기에 물든 야수 아이라) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Mad Beast Aira) in third place. |
| 226424 | 악령 토벌(광기에 물든 야수 아이라) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Mad Beast Aira) in 4th–100th place. |
| 226425 | 악령 토벌(광기에 물든 야수 아이라) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Mad Beast Aira). |
| 226426 | 악령 토벌(피에 물든 검귀 아키) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) in First Place. |
| 226427 | 악령 토벌(피에 물든 검귀 아키) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) in Second Place. |
| 226428 | 악령 토벌(피에 물든 검귀 아키) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) in Third Place. |
| 226429 | 악령 토벌(피에 물든 검귀 아키) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Blood-Soaked Sword Demon Aki) in 4th–100th place. |
| 226430 | 악령 토벌(피에 물든 검귀 아키) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Blood-Soaked Sword Demon Aki). |
| 226431 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Ghost Who Weeps Bitter Tears Ayame) in First Place. |
| 226432 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Ghost Who Weeps Bitter Tears Ayame) in Second Place. |
| 226433 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Ghost Who Weeps Bitter Tears Ayame) in Third Place. |
| 226434 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Ghost Who Weeps Bitter Tears Ayame) in 4th–100th Place. |
| 226435 | 악령 토벌(피눈물을 흘리는 원귀 아야메) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Ghost Who Weeps Bitter Tears Ayame). |
| 226436 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doom Piercer Lizelotte) in first place. |
| 226437 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doom Piercer Lizelotte) in second place. |
| 226438 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doom Piercer Lizelotte) in third place. |
| 226439 | 악령 토벌(종말을 찌르는 창 리젤로테) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Doom Piercer Lizelotte) in 4th–100th place. |
| 226440 | 악령 토벌(종말을 찌르는 창 리젤로테) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Doom Piercer Lizelotte). |
| 226441 | 악령 토벌(흉몽의 나비 나이아) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) in first place. |
| 226442 | 악령 토벌(흉몽의 나비 나이아) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) in second place. |
| 226443 | 악령 토벌(흉몽의 나비 나이아) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) in third place. |
| 226444 | 악령 토벌(흉몽의 나비 나이아) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah) in 4th–100th place. |
| 226445 | 악령 토벌(흉몽의 나비 나이아) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in Evil Soul Subjugation (Butterfly of An Ominous Dream Naiah). |
| 226601 | 대난투! 미궁 올스타즈에서 획득 가능한 스티커. | A sticker that can be obtained in Labyrinth All-Stars Brawl! |
| 226602 | 월드 보스(등대지기) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Lighthouse Keeper) event in first place. |
| 226603 | 월드 보스(등대지기) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Lighthouse Keeper) event in second place. |
| 226604 | 월드 보스(등대지기) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Lighthouse Keeper) event in third place. |
| 226605 | 월드 보스(등대지기) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Lighthouse Keeper) event in 4th–100th place. |
| 226606 | 월드 보스(등대지기) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in a World Boss (Lighthouse Keeper) event in third place. |
| 226607 | 월드 보스(베히모스) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Behemoth) event in first place. |
| 226608 | 월드 보스(베히모스) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Behemoth) event in second place. |
| 226609 | 월드 보스(베히모스) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Behemoth) event in third place. |
| 226610 | 월드 보스(베히모스) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Behemoth) event in 4th–100th place. |
| 226611 | 월드 보스(베히모스) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in a World Boss (Behemoth) event. |
| 226612 | 월드 보스(케이린) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Kayrin) event in first place. |
| 226613 | 월드 보스(케이린) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Kayrin) event in second place. |
| 226614 | 월드 보스(케이린) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Kayrin) event in third place. |
| 226615 | 월드 보스(케이린) 최종 4위~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing a World Boss (Kayrin) event in 4th–100th place. |
| 226616 | 월드 보스(케이린) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in a World Boss (Kayrin) event. |
| 226701 | 1주년 기념 특별 보상으로 획득 가능한 스티커. | A sticker that can be obtained as a special 1st anniversary reward. |
| 226702 | 최종장: 에덴 최후의 날 이벤트 스토리 열람 보상으로 획득 가능한 스티커. | A sticker that can be obtained as a reward for viewing the Final Chapter: Eden's Doomsday Event Story |
| 226703 | 차원을 뛰어넘은 특별한 만남을 기념하는 스티커. <br>강력한 힘의 늠름한 공주 정령이 당신과 함께합니다. | A sticker celebrating a special interdimensional encounter.<br>A might and valiant princess Soul joins you. |
| 226704 | 차원을 뛰어넘은 특별한 만남을 기념하는 스티커. <br>최악최흉의 정령이 당신과 함께합니다. | A sticker celebrating a special interdimensional encounter.<br>The so-called worst Soul ever joins you. |
| 226705 | 2주년 기념 특별 보상으로 획득 가능한 스티커. | A sticker that can be obtained as a special 2nd anniversary reward. |
| 226706 | 3주년 기념 특별 보상으로 획득 가능한 스티커. | A sticker that can be obtained as a special 3rd anniversary reward. |
| 226801 | 릴리트 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"후훗, 제가 완벽한 건 당연하죠?" | A sticker that can be obtained as a free reward for reaching Origin on Lilith Ascension Pass.<br><br>"Of course, it is no wonder that I'm perfect." |
| 226802 | 웨리 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"당신과 함께하니 더 즐겁네요." | A sticker that can be obtained as a free reward for reaching Origin on Wheri Ascension Pass.<br><br>"Being with you makes everything more fun." |
| 226803 | 사쿠요(업화) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"어떠냐? 짐의 실력이 너무 뛰어나서 말문이 막혔느냐?" | A sticker that can be obtained as a free reward for reaching Origin on Sakuyo (Inferno) Ascension Pass.<br><br>"So? Has my overwhelming prowess rendered you speechless?" |
| 226804 | 메피스토펠레스(여명) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"구원자님의 오퍼레이터 원, 메피스토펠레스입니다." | A sticker that can be obtained as a free reward for reaching Origin on Mephistopheles (Dawn) Ascension Pass.<br><br>"Your Operator One, Mephistopheles at your service." |
| 226805 | 바이스 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"최강! 무적! 대폭발! 그게 바로 우리가 추구하는 아름다움이다!" | A sticker that can be obtained as a free reward for reaching Origin on Weiss Ascension Pass.<br><br>"Unrivaled strength! Unmatched prowess! Massive explosions! That's the beauty we strive for!" |
| 226806 | 로제(홍염) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"구원자님, 제가 만든 포토푀예요. 같이 드시겠어요?" | A sticker that can be obtained as a free reward for reaching Origin on Rose (Prominence) Ascension Pass.<br><br>"Savior, would you like to try some pot-au-feu I made?" |
| 226807 | 홍란(무쌍) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"깡총~깡총~ 토끼를 따라하고 있어요~" | A sticker that can be obtained as a free reward for reaching Origin on Honglan (Peerless) Ascension Pass.<br><br>"Hippity-hop! I'm pretending to be a bunny!" |
| 226808 | 한울 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"이런, 미안해. 바람이 너무 좋아서 잠들었나봐." | A sticker that can be obtained as a free reward for reaching Origin on Hanul Ascension Pass.<br><br>"Oops, sorry. I guess the sweet breeze lulled me to sleep." |
| 226809 | 지호(미르) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"꺄악! 시하 너무 좋아!" | A sticker that can be obtained as a free reward for reaching Origin on Jiho (Mir) Ascension Pass.<br><br>"Squee! I love Siha so much!" |
| 226810 | 르네(백은) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"무엇 하나 변함 없는 나... 라고 하기엔 너무 갭이 큰가? 후후." | A sticker that can be obtained as a free reward for reaching Origin on Renee (Argent) Ascension Pass.<br><br>"I'm still the same as ever...or maybe not?" |
| 226811 | 라우라 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"하암~ 이제야 오셨슴까? 기다리다 잠들 뻔했슴다." | A sticker that can be obtained as a free reward for reaching Origin on Laura Ascension Pass.<br><br>"Yaaawn. Took you long enough, huh? I nearly dozed off waitin' for you." |
| 226812 | 니아 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커.<br><br>"으응…? 머리를 묶어 주고 싶어?" | A sticker that can be obtained as a free reward for reaching Origin on Nia Ascension Pass.<br><br>"Huh? You want to tie my hair?" |
| 226813 | 하루(카무이) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"나, 난 구원자가 없으면 안 되는 거… 아, 알지?" | A sticker that can be obtained as a free reward for reaching Origin on Haru (Kamuy) Ascension Pass.<br><br>"You do know I can't live without you, right?" |
| 226814 | 미리암(잔영) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"일도 끝났으니 맛있는 거나 먹으러 가자구." | A sticker that can be obtained as a free reward for reaching Origin on Miriam (Afterimage) Ascension Pass.<br><br>"Job's done. Let's get some yummy food." |
| 226815 | 페트라(각혼) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"봐, 구원자… 구원자 모양 눈사람, 만들었어." | A sticker that can be obtained as a free reward for reaching Origin on Petra (Awakened Soul) Ascension Pass.<br><br>"Look, Savior. I made a snowman version of you." |
| 226816 | 카넬리안 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"그럼, 둘만의 시간인가?" | A sticker that can be obtained as a free reward for reaching Origin on Carnelian Ascension Pass.<br><br>"Just the two of us now?" |
| 226817 | 가넷 (열락) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"한없이 달콤한 사랑이라는 맹독. 맛은 어때?" | A sticker that can be obtained as a free reward for reaching Origin on Garnet (Rapture) Ascension Pass.<br><br>"This deadly poison is called endlessly sweet love. How do you like it?" |
| 226818 |  |  |
| 226819 | 셰리 (낭만) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"구원자!! 나 데리러 온 거야?!" | A sticker that can be obtained as a free reward for reaching Origin on Cherrie (Romantic) Ascension Pass.<br><br>"Savior! Ya here to pick me up?" |
| 226820 |  |  |
| 226821 | 유리아 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"구원자님과 둘만의 시간… 기대해도 되는 걸까요?" | A sticker that can be obtained as a free reward for reaching Origin on Yuria Ascension Pass.<br><br>"I can't help but look forward to...some time alone with you, Savior." |
| 226822 | 클라우디아(대천사) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"구원자님을 위해 기도할게요." | A sticker that can be obtained as a free reward for reaching Origin on Claudia (Archangel) Ascension Pass.<br><br>"I'll be praying for you, Savior." |
| 226823 | 린지(타나토스) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"우리는 죽음조차 극복했어요. 그렇죠?" | A sticker that can be obtained as a free reward for reaching Origin on Linzy (Thanatos) Ascension Pass.<br><br>"We've overcome death, even. Right?" |
| 226824 | 헤이즐 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"아, 아직은… 이르다고 생각한다만…!" | A sticker that can be obtained as a free reward for reaching Origin on Hazel Ascension Pass.<br><br>"I, I don't think we're ready for this yet...!" |
| 226825 | 이브 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"역시… 나로는 불만인가?" | A sticker that can be obtained as a free reward for reaching Origin on Eve Ascension Pass.<br><br>"So, you're not happy with just me?" |
| 226826 | 시그리드 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"나를 어떤 방식으로 즐겁게 만들어주려고? | A sticker that can be obtained as a free reward for reaching Origin on Sigrid Ascension Pass.<br><br>"How do you plan on entertaining me?" |
| 226827 | 라리마 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"자아, 이 라리마는 준비가 됐답니다?" | A sticker that can be obtained as a free reward for reaching Origin on Larimar Ascension Pass.<br><br>"Now, I'm ready for anything." |
| 226828 | 오닉스 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"집중! 집중해달라구, 인간!!" | A sticker that can be obtained as a free reward for reaching Origin on Onyx Ascension Pass.<br><br>"Focus! I need you to focus, human!" |
| 226829 | 도미니크 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"바, 방금 건 정말 실수… 실수였는데에…!" | A sticker that can be obtained as a free reward for reaching Origin on Dominique Ascension Pass.<br><br>"Oh, that was totally unintentional! I mean it!" |
| 226830 | 유리아(아폴리온) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"그저, 모든 것을 사랑하고 싶었어요." | A sticker that can be obtained as a free reward for reaching Origin on Yuria (Apollyon) Ascension Pass.<br><br>"I just wanted to embrace everything with love." |
| 226831 | 아야메(츠쿠요미) 승급 패스 오리진 달성 무료 보상으로 획득 가능한 스티커. <br><br>"소녀, 낭군님을 뵈옵니다." | A sticker that can be obtained as a free reward for reaching Origin on Ayame (Tsukuyomi) Ascension Pass.<br><br>"I'm honored to behold my one and only lord." |
| 226901 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in first place. |
| 226902 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in second place. |
| 226903 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in third place. |
| 226904 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in 4th–10th place. |
| 226905 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in 11th–100th place. |
| 226906 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in 101st–500th place. |
| 226907 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in 501st–1000th place. |
| 226908 | 인피니티 보스 레이드(썰매왕 슬레이봅) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Raid (Sled King Sleighbob) in 1001st–2000th place. |
| 226909 | 인피니티 보스 레이드(썰매왕 슬레이봅) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Raid (Sled King Sleighbob). |
| 226910 | 인피니티 보스 챌린지(메카이아) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in first place. |
| 226911 | 인피니티 보스 챌린지(메카이아) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in second place. |
| 226912 | 인피니티 보스 챌린지(메카이아) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in third place. |
| 226913 | 인피니티 보스 챌린지(메카이아) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in 4th–10th place. |
| 226914 | 인피니티 보스 챌린지(메카이아) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in 11th–100th place. |
| 226915 | 인피니티 보스 챌린지(메카이아) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in 101st–500th place. |
| 226916 | 인피니티 보스 챌린지(메카이아) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in 501st–1000th place. |
| 226917 | 인피니티 보스 챌린지(메카이아) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Mecha Gaia) in 1001st–2000th place. |
| 226918 | 인피니티 보스 챌린지(메카이아) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Mecha Gaia). |
| 226919 | 인피니티 보스 챌린지(떡공장장 순이) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in first place. |
| 226920 | 인피니티 보스 챌린지(떡공장장 순이) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in second place. |
| 226921 | 인피니티 보스 챌린지(떡공장장 순이) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in third place. |
| 226922 | 인피니티 보스 챌린지(떡공장장 순이) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in 4th–10th place. |
| 226923 | 인피니티 보스 챌린지(떡공장장 순이) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in 11th–100th place. |
| 226924 | 인피니티 보스 챌린지(떡공장장 순이) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in 101st–500th place. |
| 226925 | 인피니티 보스 챌린지(떡공장장 순이) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in 501st–1000th place. |
| 226926 | 인피니티 보스 챌린지(떡공장장 순이) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rice Cake Factory Chief Soonie) in 1001st–2000th place. |
| 226927 | 인피니티 보스 챌린지(떡공장장 순이) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Rice Cake Factory Chief Soonie). |
| 226928 | 인피니티 보스 챌린지(심상세계의 로제) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in first place. |
| 226929 | 인피니티 보스 챌린지(심상세계의 로제) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in second place. |
| 226930 | 인피니티 보스 챌린지(심상세계의 로제) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in third place. |
| 226931 | 인피니티 보스 챌린지(심상세계의 로제) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in 4th–10th place. |
| 226932 | 인피니티 보스 챌린지(심상세계의 로제) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in 11th–100th place. |
| 226933 | 인피니티 보스 챌린지(심상세계의 로제) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in 101st–500th place. |
| 226934 | 인피니티 보스 챌린지(심상세계의 로제) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in 501st–1000th place. |
| 226935 | 인피니티 보스 챌린지(심상세계의 로제) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rose(Imaginary World)) in 1001st–2000th place. |
| 226936 | 인피니티 보스 챌린지(심상세계의 로제) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Rose(Imaginary World)). |
| 226937 | 인피니티 보스 챌린지(노심) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in first place. |
| 226938 | 인피니티 보스 챌린지(노심) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in second place. |
| 226939 | 인피니티 보스 챌린지(노심) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in third place. |
| 226940 | 인피니티 보스 챌린지(노심) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in 4th–10th place. |
| 226941 | 인피니티 보스 챌린지(노심) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in 11th–100th place. |
| 226942 | 인피니티 보스 챌린지(노심) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in 101st–500th place. |
| 226943 | 인피니티 보스 챌린지(노심) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in 501st–1000th place. |
| 226944 | 인피니티 보스 챌린지(노심) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Reactor Core) event in 1001st–2000th place. |
| 226945 | 인피니티 보스 챌린지(노심) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Reactor Core) event. |
| 226946 | 인피니티 보스 챌린지(시련의 환영) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in first place. |
| 226947 | 인피니티 보스 챌린지(시련의 환영) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in second place. |
| 226948 | 인피니티 보스 챌린지(시련의 환영) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in third place. |
| 226949 | 인피니티 보스 챌린지(시련의 환영) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in 4th–10th place. |
| 226950 | 인피니티 보스 챌린지(시련의 환영) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in 11th–100th place. |
| 226951 | 인피니티 보스 챌린지(시련의 환영) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in 101st–500th place. |
| 226952 | 인피니티 보스 챌린지(시련의 환영) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in 501st–1000th place. |
| 226953 | 인피니티 보스 챌린지(시련의 환영) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion of Ordeal) event in 1001st–2000th place. |
| 226954 | 인피니티 보스 챌린지(눈의 현자) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Sage of the Snow) event. |
| 226955 | 인피니티 보스 챌린지(눈의 현자) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in first place. |
| 226956 | 인피니티 보스 챌린지(눈의 현자) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in second place. |
| 226957 | 인피니티 보스 챌린지(눈의 현자) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in third place. |
| 226958 | 인피니티 보스 챌린지(눈의 현자) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in 4th–10th place. |
| 226959 | 인피니티 보스 챌린지(눈의 현자) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in 11th–100th place. |
| 226960 | 인피니티 보스 챌린지(눈의 현자) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in 101st–500th place. |
| 226961 | 인피니티 보스 챌린지(눈의 현자) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in 501st–1000th place. |
| 226962 | 인피니티 보스 챌린지(눈의 현자) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Sage of the Snow) event in 1001st–2000th place. |
| 226963 | 인피니티 보스 챌린지(눈의 현자) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Sage of the Snow) event. |
| 226964 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in first place. |
| 226965 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in second place. |
| 226966 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in third place. |
| 226967 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in 4th–10th place. |
| 226968 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in 11th–100th place. |
| 226969 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in 101st–500th place. |
| 226970 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in 501st–1000th place. |
| 226971 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event in 1001st–2000th place. |
| 226972 | 인피니티 보스 챌린지(폭주한 실베스터 조이 3세) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Rampaging King Sylvester Joey III) event. |
| 226973 | 인피니티 보스 챌린지(아마'게'돈) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in first place. |
| 226974 | 인피니티 보스 챌린지(아마'게'돈) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in second place. |
| 226975 | 인피니티 보스 챌린지(아마'게'돈) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in third place. |
| 226976 | 인피니티 보스 챌린지(아마'게'돈) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in 4th–10th place. |
| 226977 | 인피니티 보스 챌린지(아마'게'돈) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in 11th–100th place. |
| 226978 | 인피니티 보스 챌린지(아마'게'돈) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in 101st–500th place. |
| 226979 | 인피니티 보스 챌린지(아마'게'돈) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in 501st–1000th place. |
| 226980 | 인피니티 보스 챌린지(아마'게'돈) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (CRABmageddon) event in 1001st–2000th place. |
| 226981 | 인피니티 보스 챌린지(아마'게'돈) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (CRABmageddon) event. |
| 226982 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in first place. |
| 226983 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in second place. |
| 226984 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in third place. |
| 226985 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in 4th–10th place. |
| 226986 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in 11th–100th place. |
| 226987 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in 101st–500th place. |
| 226988 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in 501st–1000th place. |
| 226989 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Illusion-Piercing Bullet) event in 1001st–2000th place. |
| 226990 | 인피니티 보스 챌린지(환영을 꿰뚫는 탄환) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Illusion-Piercing Bullet) event. |
| 226991 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in first place. |
| 226992 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in second place. |
| 226993 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in third place. |
| 226994 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in 4th–10th place. |
| 226995 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in 11th–100th place. |
| 226996 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in 101st–500th place. |
| 226997 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in 501st–1000th place. |
| 226998 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Idol Queen Catherine) event in 1001st–2000th place. |
| 226999 | 인피니티 보스 챌린지(아이돌 퀸 캐서린) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Idol Queen Catherine) event. |
| 227001 | 달콤한 생크림과 폭신한 시트가 인상적인 간식. | An impressive snack with sweet fresh cream and soft layers. |
| 227002 | 고소한 버터 냄새와 잼, 크림이 조화로운 간식. | A buttery snack that pairs well with jam and cream. |
| 227003 | 여러 종류의 과자가 가득해서 질리지 않는 간식. | A snack full of various kinds of cookies that nobody would ever get sick of. |
| 227004 | 적당한 짠 맛과 바삭한 식감이 중독적인 간식. | A slightly salty and crunchy addictive snack. |
| 227005 | 건강을 생각해 신선한 각종 채소로 만든 요리. | A healthy dish made with a variety of fresh vegetables. |
| 227006 | 반찬과 밥의 균형을 생각하여 정성스럽게 만든 한 그릇 요리. | Food carefully prepared with a fine balance of side dishes and rice. |
| 227007 | 감자와 생선을 튀겨 소금이나 식초를 뿌려 먹는 요리. | A dish of deep-fried potatoes and fish, that goes well with salt or vinegar. |
| 227008 | 꼬치에 양념을 한 고기와 가니시를 끼워 구운 요리. | Seasoned meat and garnish grilled on a skewer. |
| 227009 | 향기롭지만 조금 쓴, 어른스러움이 느껴지는 음료. | A fragrant but slightly bitter drink that adults would enjoy. |
| 227010 | 고소한 우유에 달콤한 꿀을 추가한 음료. | Milk with added sweet honey. |
| 227011 | 기분 좋은 향기의 허브와 꽃내음이 가득 담긴 음료. | A drink filled with the pleasant scent of herbs and flowers. |
| 227012 | 맛있는 과일을 그대로 갈아 만든 상큼한 음료. | A refreshing drink made with freshly grounded up fruits. |
| 227013 | 도자기로 만든 예쁜 꽃 모양 장식이 달린 머리 장식. | A hair accessory made of porcelain with a pretty flower-shaped ornament. |
| 227014 | 귀여운 챰과 하늘하늘한 리본이 달린 실용적인 소품. | A practical prop with a lovely charm and a ribbon. |
| 227015 | 기분 전환에 좋은 향료가 담긴 우아한 소품. | An elegant prop filled with invigorating perfume. |
| 227016 | 숙녀의 몸단장에 필수라고 할 수 있는 소품. | An essential prop for ladies. |
| 227017 | 한땀한땀 손으로 만들어 더 귀여운 곰 모양 인형. | An adorable handmade bear doll. |
| 227018 | 머리 맡에 두면 악몽을 꾸지 않는다고 전해지는 물건. | An item that is said to prevent nightmares if placed by the bedside. |
| 227019 | 고상한 그림이나 추억을 간직할 수 있는 앤틱한 액자. | An antique picture frame to keep noble pictures and memories. |
| 227020 | 유리아의 모습을 본 떠 만들어진 한정판 수집품. | A limited edition collector's item modeled after Yuria's profile. |
| 227021 | 보다 멋진 서명을 위해 고급 펜촉을 끼워 만든 필기구. | A writing instrument made with a fine nib perfect for signing signatures. |
| 227022 | 접고 펼칠 때마다 기분 좋은 소리가 나는 나무 부채. | A wooden fan that makes a pleasant sound every time it is folded and unfolded. |
| 227023 | 보조 무기로 사용하기 좋게 만들여진 고급 단검. | A fine dagger made to be used as a secondary weapon. |
| 227024 | 알 수 없는 마법의 주문이 잠들어 있다는 스크롤. | A scroll believed to be infused with an unknown magic spell. |
| 227025 | 상점가의 점포들이 연합해 주민들에게 배포한 쿠폰 북. | A coupon book distributed to the residents by a union of stores in the shopping district. |
| 227026 | 작은 식물을 파내거나 심는 데 쓸 수 있는 작은 삽. | A small shovel that can be used to dig up or plant small plants. |
| 227027 | 순간적인 부상에 대처할 수 있는 신비한 물약. | A mysterious potion that lets you instantly treat injuries. |
| 227028 | 차분하고 소박한 들꽃이 수 놓인 단아한 손수건. | An elegant handkerchief embroidered with simple wild flowers. |
| 227029 | 여러가지 보드 게임을 즐길 수 있는 트럼프 카드 세트. | A set of playing cards that can be used to play various board games. |
| 227030 | 접근성이 좋고 기분 좋은 울림을 내는 현악기. | An easily accessible string instrument that makes a pleasant sound. |
| 227031 | 여러 방향으로 돌려 모든 면의 색상을 맞추는 퍼즐. | A puzzle where you match colors on all sides by turning them in different directions. |
| 227032 | 끌어안으면 잠이 솔솔 오는 아주 포근한 쿠션. | A very snug cushion that makes you fall asleep when you cuddle it. |
| 227033 | 창문 가에 둘 수 있을 만한 크기의 귀여운 허브 화분. | A cute herb pot that's small enough to be placed by the window. |
| 227034 | 잠들기 전에 읽으면 좋을 재미있는 이야기가 가득 쓰여진 책. | A book filled with interesting stories worth reading before going to bed. |
| 227035 | 장인의 손길로 만들어진 가볍고 고운 색상의 찻잔 세트. | A set of light teacups in beautiful colors, crafted by artisans. |
| 227036 | 이 별의 영혼이 보석으로 피어난 듯 영롱한 광채의 진귀한 꽃. | A rare flower with dazzling brilliance as if the soul of a star bloomed into a jewel. |
| 227037 | 행운의 꽃을 깔끔하게 묶어 만든 꽃다발.<br>주변의 행운을 크게 불러올 것만 같다. | A simple bouquet of Lucky Flowers.<br>It may bring great luck. |
| 227100 | 인피니티 보스 챌린지(열락의 밤으로) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in first place. |
| 227101 | 인피니티 보스 챌린지(열락의 밤으로) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in second place. |
| 227102 | 인피니티 보스 챌린지(열락의 밤으로) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in third place. |
| 227103 | 인피니티 보스 챌린지(열락의 밤으로) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in 4th–10th place. |
| 227104 | 인피니티 보스 챌린지(열락의 밤으로) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in 11th–100th place. |
| 227105 | 인피니티 보스 챌린지(열락의 밤으로) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in 101st–500th place. |
| 227106 | 인피니티 보스 챌린지(열락의 밤으로) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in 501st–1000th place. |
| 227107 | 인피니티 보스 챌린지(열락의 밤으로) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Into the Night of Rapture) event in 1001st–2000th place. |
| 227108 | 인피니티 보스 챌린지(열락의 밤으로) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Into the Night of Rapture) event. |
| 227109 | 인피니티 보스 챌린지(낭만항로) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in first place. |
| 227110 | 인피니티 보스 챌린지(낭만항로) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in second place. |
| 227111 | 인피니티 보스 챌린지(낭만항로) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in third place. |
| 227112 | 인피니티 보스 챌린지(낭만항로) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in 4th–10th place. |
| 227113 | 인피니티 보스 챌린지(낭만항로) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in 11th–100th place. |
| 227114 | 인피니티 보스 챌린지(낭만항로) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in 101st–500th place. |
| 227115 | 인피니티 보스 챌린지(낭만항로) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in 501st–1000th place. |
| 227116 | 인피니티 보스 챌린지(낭만항로) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Romantic Voyage) in 1001st–2000th place. |
| 227117 | 인피니티 보스 챌린지(낭만항로) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Romantic Voyage). |
| 227118 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 1위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in first place. |
| 227119 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 2위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in second place. |
| 227120 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 3위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in third place. |
| 227121 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 4~10위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in 4th–10th place. |
| 227122 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 11~100위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in 11th–100th place. |
| 227123 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 101~500위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in 101st–500th place. |
| 227124 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 501~1000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in 501st–1000th place. |
| 227125 | 인피니티 보스 챌린지(소원 도둑 오닉스) 최종 1001~2000위 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon finishing an Infinity Boss Challenge (Wish Thief Onyx) in 1001st–2000th place. |
| 227126 | 인피니티 보스 챌린지(소원 도둑 오닉스) 참여 시 획득 가능한 스티커. | A sticker that can be obtained upon participating in an Infinity Boss Challenge (Wish Thief Onyx). |
| 228001 | 성대한 크마리스스 파티를 위해 열심히 모은 식재료를 한 곳에 모은 바구니입니다.<br>크마리스스 축제 기간 동안 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A basket filled with various ingredients collected for a grand Kumawreaths party.<br>You can exchange it for various items during the period of the Kumawreaths Festival.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228002 | 수집 이벤트 전용 아이템입니다.<br>수집 이벤트에서 다양한 아이템으로 교환할 수 있습니다. | Item exclusive for a collection event.<br>You can exchange it for various items in collection events. |
| 228003 | 탐관오리 클로이가 소중하게 가지고 있던 꿈주머니. 꿈가루가 가득 들어있다.<br>나이아의 꿈 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A pouch preciously kept by the corrupt official Chloe. It's filled with Dream Powder.<br>You can exchange it for various items at Naiah's Dream Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228004 | 한 입 먹는 순간 사랑에 빠져버리고 만다는 묘약. 특별한 날이 되면 정령들 간 암암리에 거래가 성행한다고 한다.<br>재클린의 쇼콜라 샵에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A gulp of this potion will make you instantly fall in love. It looks like quite a few Souls have been trading this potion in secret on special occasions.<br>You can exchange it for various items at Jacqueline's Chocolat Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228005 | 황금빛으로 빛나는 꽃잎.<br>소유자에게 행운을 불러온다고 한다.<br>클라라의 농장에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A shiny golden petal.<br>They say it brings good luck to its owner.<br>You can exchange it for various items at Naiah's Dream Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228006 | 학생회에서 발행한 특별 메달.<br>에버스쿨 경품 교환기에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A special medal issued from the Student Council.<br>Can be used at the Everschool Prize Machine.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228007 | 체육부 부장 클레르의 모습이 그려진 딱지.<br>체육부 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A voucher with a picture of P.E. Manager Claire's face on it.<br>Can be exchanged for various items at the P.E. Club Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228008 | 바른생활부 부장 린지의 모습이 그려진 딱지.<br>바른생활부 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A voucher with a picture of Ethics Director Linzy's face on it.<br>Can be exchanged for various items at the Ethics Club Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228009 | 이벤트 레이드의 입장에 필요한 입장권.<br>이벤트 레이드를 1회 이용할 수 있다.<br><br>(이벤트 교환 기간에는 사용이 불가능하며, 이벤트가 종료될 경우 소멸됩니다.) | A ticket needed for entering into the event raid.<br>Allows you to access the event raid once.<br><br>(Cannot be used during the event exchange period, and disappears when the event is over.) |
| 228010 | 이벤트 스테이지의 입장에 필요한 입장권.<br>이벤트 스테이지를 1회 이용할 수 있다.<br><br>(이벤트 교환 기간에는 사용이 불가능하며, 이벤트가 종료될 경우 소멸됩니다.) | A ticket needed for entering into the event stage.<br>Allows you to access the event stage once.<br><br>(Cannot be used during the event exchange period, and disappears when the event is over.) |
| 228011 | 여러 송이의 아름다운 꽃을 묶어 만든 꽃다발.<br>부케를 받은 이는 좋은 일이 있다고 전해지는데...<br>행복 교환소에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A bouquet made of beautiful flowers.<br>They say something good happens to those who receive the bouquet...<br>Can be exchanged for various items at the Happiness Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228012 | 프릴 장식과 더불어 소녀를 더욱 귀엽게 해주는 아이템.<br>에버웨딩 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A frilled item that makes a girl cuter.<br>Can be exchanged for various items at the Everwedding Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228013 | 생애 가장 행복한 순간에 어울릴 법한 와인.<br>에버웨딩 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A wine that would be suitable for the happiest moment of one's life.<br>Can be exchanged for various items at the Everwedding Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228014 | 미니 게임의 입장에 필요한 입장권.<br>미니 게임을 1회 이용할 수 있다. | A ticket needed for entering into the mini game.<br>Allows you to access the mini game once. |
| 228015 | 여름의 마녀가 잃어버린 경품 메달.<br>낙원 경품 교환소에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A prize medal that the Summer Witch has lost.<br>Can be used at the Paradise Prize Exchange.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228016 | 낙원의 해변가에서 찾아낸 향기롭고 화려한 붉은 꽃.<br>선셋 비치 마켓에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A fragrant, dazzling red flower that was found at the Paradise Beach.<br>Can be exchanged for various items at the Sunset Beach Market.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228017 | 낙원의 모래사장에서 주운 투명하고 동글동글한 유리 조각.<br>선셋 비치 마켓에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A transparent, round piece of glass that was picked up at the Paradise Sandy Beach.<br>Can be exchanged for various items at the Sunset Beach Market.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228018 | 제 1회 에덴 갓 탤런트에서 사용할 수 있는 투표권.<br>에덴 갓 탤런트 이벤트는 전선 5-10 클리어 시 참여 가능합니다.<br><br>(이벤트 기간 종료 후 사라집니다.) | Allows you to vote for the 1st Eden's Got Talent event.<br>You can participate in the Eden's Got Talent event after you clear Battlefront 5-10.<br><br>(Disappears after the event ends.) |
| 228019 | 빙고 게임 이용에 필요한 티켓.<br>보너스 빙고를 1회 이용할 수 있습니다.<br><br>(이벤트 기간 종료 후 사라집니다.) | A ticket used for a shot at the Bingo game.<br>Grants a 1-time use of the Bonus Bingo.<br><br>(Disappears after the event ends.) |
| 228020 | 아드리안이 흘리고 간 경품 메달.<br>영원 경품 교환소에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A prize medal that Adrianne left behind.<br>Can be used at the Eternal Prize Exchange.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228021 | 홍란의 숨결이 담겨있는 탱글탱글한 물놀이 공.<br>영원 플리 마켓에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A bouncy ball for water activities. It contains the breath of Honglan.<br>Can be exchanged for various items at the Eternal Flea Market.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228022 | 캐서린의 온기가 느껴지는 귀여운 오리 모양의 장난감.<br>영원 플리 마켓에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A cute toy in the shape of a duck. You can feel Catherine's warmth from it.<br>Can be exchanged for various items at the Eternal Flea Market.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228023 | 보름달의 날을 맞이하여 주조한 기념화폐.<br>왕실의 고명딸인 루테 공주가 각별히 아끼는 물건. 신부의 혼수품으로 사용되기도 한다.<br><br>보름달 경품 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A special coin created to celebrate the Full Moon Day.<br>It's something very precious to Lute, the only daughter in the royal family. It's also used for wedding gifts for the bride.<br><br>Can be used at the Full Moon Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228024 | 식용 꽃으로 장식한 화전. <br>진달래 화채와 함께 즐기면 금상첨화라고 한다.<br><br>보름달 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Flower rice pancake decorated with edible flowers.<br>It goes extremely well with salad.<br><br>Can be exchanged for various items at the Full Moon Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228025 | 고운 빛깔의 쫄깃한 송편.<br>달콤한 깨 송편에 고소한 밤 송편까지! 다양한 맛을 즐겨보자.<br><br>보름달 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A shiny delicious looking half-moon rice cake.<br>Sesame and chestnut flavors! Try them all.<br><br>Can be exchanged for various items at the Full Moon Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228026 | 악몽의 사냥꾼 리젤로테를 처치하고 얻은 경품 메달.<br><br>할로윈 경품 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Prize medal obtained from defeating Hunter of Nightmare Lizelotte.<br><br>Can be used at the Halloween Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228027 | 빨간 모자를 도와 얻은 쿠폰.<br><br>할로윈 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Coupon obtained from helping Red Riding Hood.<br><br>Can be exchanged for various items at the Halloween Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228028 | 나쁜 늑대를 도와 얻은 쿠폰.<br><br>할로윈 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Coupon obtained from helping the Bad Wolf.<br><br>Can be exchanged for various items at the Halloween Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228029 | 이벤트 레이드의 입장에 필요한 입장권.<br>이벤트 레이드를 1회 이용할 수 있다.<br><br>이벤트 교환 기간에도 사용이 가능하다.<br><br>(교환 기간 종료 후 개당 810,000 골드로 환산되어 우편함으로 지급됩니다.) | A ticket needed for entering into the event raid.<br>Allows you to access the event raid once.<br><br>(After the exchange period ends, each will be converted to 810,000 gold and sent to your mail.) |
| 228030 | 썰매왕 슬레이봅을 처치하고 얻은 경품 메달.<br><br>크리스마스 경품 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A prize medal earned from defeating Sled King Sleighbob.<br><br>Can be used at the Christmas Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228031 | 도라를 도와주고 얻은 친구 배지.<br><br>크리스마스 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A friend badge obtained upon helping out Dora.<br><br>Can be exchanged for various items at the Christmas Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228032 | 가넷을 도와주고 얻은 친구 배지.<br><br>크리스마스 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A friend badge obtained upon helping out Garnet.<br><br>Can be exchanged for various items at the Christmas Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 gold and sent to your mail.) |
| 228034 | 미궁 올스타즈 입장에 필요한 입장권.<br>미궁 올스타즈를 1회 이용할 수 있다.<br><br>(이벤트 종료 후 최종 클리어 단계의 보상으로 환산되어 우편함으로 지급됩니다.) | A ticket needed for entering Labyrinth All-Stars.<br>Grants 1-time access to Labyrinth All-Stars.<br><br>(After the event ends, each will be converted to a reward for the last level you cleared and will be sent to your mail.) |
| 228035 | 미궁 올스타즈 훈련에 사용되는 포인트.<br>미궁 올스타즈 훈련을 1회 이용할 수 있습니다.<br><br>(이벤트 기간 종료 후 사라집니다.) | Points used for Labyrinth All-Stars Training.<br>Grants a 1-time use of Labyrinth All-Stars Training.<br><br>(Disappears after the event ends.) |
| 228039 | 숙취에 시달린 클라우디아를 구원하고 얻은 파티 경품 추첨권.<br><br>파티 경품 교환소에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A mirth prize ticket obtained after saving Claudia from her hangover.<br><br>Can be used at the Mirth Prize Exchange.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228040 | "슈팅스타" 탈리아를 압도한 파티의 승자에게 주어지는 메달.<br><br>파티 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A medal awarded to the victor of the mirth after subduing "Shooting Star" Talia.<br><br>Can be exchanged for various items at the Mirth Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228041 | "퀸 오브 사바나" 아이라를 제압한 증표로 수여받은 휘장.<br><br>파티 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | An insignia earned as proof of subduing "Queen of Savannah" Aira.<br><br>Can be exchanged for various items at the Mirth Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228045 | 메이드 나라에서 사용 가능한 코인. <br>'메이드 카페는 꿈의 나라이기 때문에, 그에 맞는 전용 화폐를 사용하고 있다'라는 설정이라고 한다.<br><br>메이드 경품 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A coin that can be used in Maid Land.<br>Because the maid cafe is a land of dreams, it supposedly has its own special currency.<br><br>Can be used at the Maid Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228046 | 「술은 주점에 가서 찾으시라고요!!」<br>메이드 카페에서 알코올을 찾는 익명의 진상 손님을 퇴치하고 얻은 딱지.<br><br>메이드 카페 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | "Go to a bar if you want alcohol!"<br>A Sticker obtained after kicking out an anonymous customer causing trouble by demanding booze at the maid cafe.<br><br>Can be exchanged for various items at the Maid Cafe Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228047 | 「자릿세? 계약 내용과 다르잖아~!!」<br>메이드 카페의 자릿세를 받아내려는 익명의 진상 손님을 퇴치하고 얻은 딱지.<br><br>메이드 카페 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | "Street tax? That wasn't in the contract!"<br>A Sticker obtained after kicking out an anonymous customer causing trouble by demanding street tax at the maid cafe.<br><br>Can be exchanged for various items at the Maid Cafe Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228050 | 「위험천만?! 하얀 울새 숲」 미니 게임 입장에 필요한 입장권.<br>미니 게임을 1회 이용할 수 있다. | A ticket needed for entering the Dangerous White Robin Forest mini game.<br>Allows you to access the mini game once. |
| 228055 | 어둠의 기운이 담긴 학생회 메달. 누가, 무슨 목적으로 발행한 메달인지는 알 수 없다…<br>학생회 비품 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A student council medal imbued with sinister energy. No one knows who made it or why they did.<br>Can be used at the Student Council Supply Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228056 | 다프네가 발사하는 교복 단추. 학교에 걸린 봉인 때문에 아무리 단추를 발사해도 다시 재생된다고 한다…<br>에버스쿨 비밀 매점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A uniform button launched by Daphne. Due to a magical seal on the school, her buttons keep regenerating no matter how many she pops.<br>Can be exchanged for various items at the Everschool Secret Stand.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228057 | 회계부장(이 되고 싶은) 마농의 모습이 그려진 딱지. 마농이 크레파스로 직접 그렸다.<br>에버스쿨 비밀 매점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A sticker with a picture of (aspiring) Bursar Manon, drawn by Manon herself with crayons.<br>Can be exchanged for various items at the Everschool Secret Stand.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228063 | 여름 축제를 즐긴 만큼 도장을 찍어주는 축제 쿠폰. 아쉽지 않을 만큼 잔뜩 모아보자!<br>축제 교환 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A festival coupon that gets stamped for every fun activity enjoyed at the Summer Festival.<br>Can be exchanged for various items at the Festival Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228071 | 누군가 떨어뜨린 웨딩용 코르사주.<br>왜인지 결혼을 해야만 할 것 같은 오싹한 느낌이 든다…<br>언약의 경품 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A wedding corsage dropped by someone.<br>Eerily makes you feel the urge to get married for some reason...<br>Can be used at the Wedding Vow Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228072 | 비올레트가 흘리고 간 웨딩 슈즈.<br>발끝에 맹세의 입맞춤을 바라며 맞춤 제작했다고 한다.<br>순백의 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Wedding shoes left behind by Violette.<br>Tailor-made with the hope of a vow-sealing kiss at the toes.<br>Can be exchanged for various items at the Pure White Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228073 | 가넷이 잃어버린 웨딩 브로치.<br>결코 깨지지 않는 사랑을 상징하듯 견고한 재질이다.<br>순백의 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A wedding brooch misplaced by Garnet.<br>It is made of solid material as if to represent a love that will never be broken.<br>Can be exchanged for various items at the Pure White Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228075 | 제 2회 에덴 갓 탤런트에서 사용할 수 있는 투표권.<br>에덴 갓 탤런트 이벤트는 전선 5-10 클리어 시 참여 가능합니다.<br><br>(이벤트 기간 종료 후 사라집니다.) | Allows you to vote for the 2nd Eden's Got Talent event.<br>You can participate in the Eden's Got Talent event after you clear Battlefront 5-10.<br><br>(Disappears after the event ends.) |
| 228077 | 토카와 쿠루미의 소중한 '그 소년'의 브로마이드. <br>시간의 유희장에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A poster of the boy who is very dear to Tohka and Kurumi.<br>Can be exchanged for various items at the Playground of Time.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228078 | 토카가 좋아하는 콩고물 빵. <br>토카를 위해 유리아 일행이 열심히 구워 맛있는 냄새가 풍긴다. <br>힘의 전당에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Tohka's favorite bread made with roasted soy flour.<br>Lovingly baked by Yuria and other Souls for Tohka, it emanates a tantalizing smell.<br>Can be exchanged for various items at the Chamber of Strength.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228079 | 쿠루미를 닮은 검은 고양이 인형.<br>아키와 메피스토펠레스가 쿠루미와 친해지기 위해 준비했다고 하는데…<br>힘의 전당에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A black cat toy that somewhat resembles Kurumi.<br>Apparently, Aki and Mephistopheles got it in their efforts to get closer to Kurumi...<br>Can be exchanged for various items at the Chamber of Strength.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228086 | 으스스한 유령 인형.<br>마치 누군가를 찾고 있는 듯하다.<br>기묘한 상점에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A spooky ghost effigy.<br>Seems to be looking for someone to haunt.<br>Can be used at the Eccentric Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228087 | 어두운 숲길을 밝히는 랜턴.<br>불이 꺼지는 순간 세상은 칠흑 같은 어둠에 잠겨버린다. <br>베스티 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A lantern for illuminating the gloomy forest path.<br>Should the flame flicker out, the world is enveloped in absolute darkness.<br>Can be exchanged for various items at the Bestie Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail. |
| 228088 | 방송 촬영용 필름.<br>현상하기 전 까진 무엇이 찍혔는지 확인할 수 없다.<br>베스티 교환 상점에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A film reel for recording video.<br>What's recorded remains a mystery until the video is done processing.<br>Can be exchanged for various items at the Bestie Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228099 | 서커스 관람객에게 지급되는 랜덤 경품 티켓.<br>행운의 주인공은 누굴까?<br>[문라이트 경품 상점]에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A random prize ticket issued to circus attendees.<br>Who would be the lucky winner?<br>Can be used at the Moonlight Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228100 | 서커스 훈련을 무사히 수료한 단원에게 지급하는 영광스러운 바니바니 훈련 수료증.<br>[바니바니 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A prestigious Bunny Bunny Training Certificate awarded to performers who have successfully completed circus training.<br>Can be exchanged for various items at the Bunny Bunny Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228101 | 서커스 훈련을 무사히 수료한 단원에게 지급하는 영광스러운 문라이트 훈련 수료증.<br>[바니바니 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A prestigious Moonlight Training Certificate awarded to performers who have successfully completed circus training.<br>Can be exchanged for various items at the Bunny Bunny Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228108 | 컨벤션에 일어난 사고를 막아준 관람객에게 지급되는 경품 교환권.<br>과연 어떤 경품이 나올까?<br>[컨벤션 경품 상점]에서 사용할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A prize ticket awarded to the valiant attendee who stepped in to stop a convention mishap.<br><br>Can be used at the Convention Prize Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228109 | 폭주하는 메카 베어를 저지한 관람객에게 지급되는 저지 작전 훈장.<br>[작전 훈장 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A Stopping Operation Medal awarded to the valiant attendee who stopped the rampaging Mech Bears.<br>Can be exchanged for various items at the Operation Medal Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228110 | 도둑 수색 작전에 참여한 관람객에게 지급되는 수색 작전 훈장.<br>[작전 훈장 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br><br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A Search Operation Medal awarded to the valiant attendee who participated in the operation after a thief.<br>Can be exchanged for various items at the Operation Medal Exchange Shop.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228114 | 순이의 떡공장에서 훔쳐… 얻어 온 떡주머니. <br>맛있어 보이는 떡이 가득하다.<br><br>[떡공장 공판장]에서 사용할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A pouch of rice cakes, stolen... nay, sourced from Soonie's rice cake factory.<br>It is packed with tasty-looking rice cakes.<br>Can be used at the Rice Cake Factory Market.<br><br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228115 | 외국에서 온 손님이 연거푸 들이키던 가온의 전통주용 사발.  <br><br>[축제 물품 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A traditional rice wine bowl of Gaon, eagerly gulped down by tourists from abroad.<br><br>Can be exchanged for various items at the Festival Goods Exchange Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228116 | 신년 불꽃놀이를 기념해 만들어진 가온의 전통 장신구. <br><br>[축제 물품 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Traditional accessory from Gaon, celebrating the New Year fireworks.<br><br>Can be exchanged for various items at the Festival Goods Exchange Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228118 | 룰렛 이용에 필요한 티켓.<br>이벤트 룰렛에 사용하여 보상을 획득할 수 있습니다.<br><br>(이벤트 종료 후 개당 300,000 골드로 환산되어 우편함으로 지급됩니다.) | A ticket needed to spin the wheel.<br>Use it on the Event Wheel to claim rewards.<br><br>(After the event ends, each will be converted to 300,000 Gold and sent to your mail.) |
| 228119 | 미니 게임 입장에 필요한 입장권.<br>미니 게임을 1회 이용할 수 있다.<br><br>(이벤트 종료 후 개당 810,000 골드로 환산되어 우편함으로 지급됩니다.) | A ticket needed for entering the Mini Game.<br>Grants a 1-time access to the Mini Game.<br><br>(After the event ends, each will be converted to 810,000 Gold and sent to your mail.) |
| 228133 | 이벤트 진행에 사용되는 주사위 아이템.<br>이벤트 주사위에 사용하여 보상을 획득할 수 있습니다.<br><br>(이벤트 종료 후 개당 600,000 골드로 환산되어 우편함으로 지급됩니다.) | A dice used in the event.<br>Use it to roll the dice and claim event rewards.<br><br>(After the event ends, each will be converted to 600,000 Gold and sent to your mail.) |
| 228146 | 폭주한 실베스터 조이 3세가 여기저기 흩트려둔 서류들.<br>궁기의 기운이 아주 약간 남아 있다.<br><br>[개이득 경품 상점]에서 사용할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Documents scattered everywhere by Rampaging King Sylvester Joey III.<br>These papers still carry a faint trace of the Unicat's energy<br><br>Can be used at the Paw-some Prize Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228147 | 부드러운 깃털이 잔뜩 꽂혀 있는 먼지떨이.<br>고급 자재로 이루어져 있다.<br><br>[메이드의 물물교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A duster filled with soft feathers.<br>Made from high-quality materials.<br><br>Can be exchanged for various items at the Maid's Goods Exchange Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228148 | 클라라의 농장에서 특별히 공수해 온 식재료들.<br>반짝반짝 윤기가 흘러 탐스럽다.<br><br>[메이드의 물물교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | Ingredients specially sourced from Clara Farm.<br>Their glossy sheen makes them look incredibly appetizing.<br><br>Can be exchanged for various items at the Maid's Goods Exchange Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228155 | 커다란 집게발이 번득이는 동전. 바닷속 게들만의 화폐일까?.<br><br>[속삭이는 바다의 경품 상점]에서 사용할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A coin glinting with the image of large pincers. Perhaps a currency of underwater crabs?<br><br>Can be used at the Whispering Ocean Prize Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228156 | 사쿠요가 그려진 도장. 뭔가 칭찬받는 기분이다<br><br>[여름 합숙 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A stamp with an image of Sakuyo. Feels like a reward for something.<br><br>Can be exchanged for various items at the Summer Training Camp Exchange Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228157 | 구원자가 그려진 도장. 뭔가 칭찬받는 기분이다.<br><br>[여름 합숙 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A stamp with an image of Savior.<br><br>Can be exchanged for various items at the Summer Training Camp Exchange Shop.<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228158 | 바이스에게 전달받은 칼라르 토큰.<br>칼라르 내부에서 자유롭게 사용할 수 있다. | A Chalar token received from Weiss.<br>Can be freely used within Chalar. |
| 228159 | 아이돌 퀸의 특별 무대 관람객에게 지급되는<br>랜덤 아이돌 퀸 굿즈 추첨권.<br>행운의 주인공은 누굴까?<br>[에덴 스테이지 경품 상점]에서 사용할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A raffle ticket for idol queen merch offered to<br>the audience of the Idol Queen special stage.<br>Who will be the lucky winner?<br>Can be used at the [Eden Stage Prize Shop.]<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228160 | 보컬 트레이닝을 수료한 연습생에게 지급하는<br>영광스러운 보컬 트레이닝 수료증.<br>[에덴 스테이지 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A glorious certificate of completion offered to trainees<br>who have successfully finished their vocal training.<br>Can be exchanged for various items at the [Eden Stage Exchange Shop.]<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228161 | 댄스 트레이닝을 수료한 연습생에게 지급하는<br>영광스러운 댄스 트레이닝 수료증.<br>[에덴 스테이지 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다.<br>(교환 기간 종료 후 개당 3000 골드로 환산되어 우편함으로 지급됩니다.) | A glorious certificate of completion offered to trainees<br>who have successfully finished their dance training.<br>Can be exchanged for various items at the [Eden Stage Exchange Shop.]<br>(After the exchange period ends, each will be converted to 3,000 Gold and sent to your mail.) |
| 228162 | 신년 축제를 맞아 무사안녕의 기원을 담은 복주머니입니다.<br>안에는 돌멩이가 담겨있는 것처럼 묵직합니다.<br>[축제 물품 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다. | A lucky pouch carrying a prayer for safety, made to celebrate the New Year's festival.<br>It's surprisingly heavy, as if filled with stones.<br>Exchange them for various items at the "Festival Goods Exchange Shop." |
| 228163 | 신년 축제를 맞아 운수대통의 기원을 담은 복주머니입니다.<br>안에는 돌멩이가 담겨있는 것처럼 묵직합니다.<br>[축제 물품 교환 상점]에서 다양한 아이템으로 교환할 수 있습니다. | A lucky pouch carrying a prayer for fortune's favor, made to celebrate the New Year's festival.<br>It's surprisingly heavy, as if filled with stones.<br>Exchange them for various items at the "Festival Goods Exchange Shop." |
| 228164 | 새해의 길조와 행운을 가득 머금은 복권입니다.<br>왜인지 대길의 기운이 감도는 것 같기도...<br>[신년 운세뽑기 상점]에서 사용할 수 있습니다. | A lottery ticket packed with the New Year's auspicious signs and fortune.<br>Somehow, it feels infused with the aura of great fortune...<br>Can be used at the "New Year's Fortune Draw Shop." |
| 228901 | 마농팩(월정액)을 7일 간 체험할 수 있는 티켓.<br>이미 보유하고 있을 경우 기간이 연장된다.<br>(월정액 즉시 보상은 지급되지 않음.) | A ticket that gives 7-day trial access to the Monthly Sub Manon Pack.<br>Extends the subscription period if already subscribed.<br>(Does not include the Monthly Sub's instant reward.) |
| 228902 | 샤링팩(월정액)을 7일 간 체험할 수 있는 티켓.<br>이미 보유하고 있을 경우 기간이 연장된다.<br>(월정액 즉시 보상은 지급되지 않음.) | A ticket that gives 7-day trial access to the Monthly Sub Sharinne Pack.<br>Extends the subscription period if already subscribed.<br>(Does not include the Monthly Sub's instant reward.) |
| 228903 | 마농팩(월정액)을 10일 간 체험할 수 있는 티켓.<br>이미 보유하고 있을 경우 기간이 연장된다.<br>(월정액 즉시 보상은 지급되지 않음.) | A ticket that gives 10-day trial access to the Monthly Sub Manon Pack.<br>Extends the subscription period if already subscribed.<br>(Does not include the Monthly Sub's instant reward.) |
| 228904 | 샤링팩(월정액)을 10일 간 체험할 수 있는 티켓.<br>이미 보유하고 있을 경우 기간이 연장된다.<br>(월정액 즉시 보상은 지급되지 않음.) | A ticket that gives 10-day trial access to the Monthly Sub Sharinne Pack.<br>Extends the subscription period if already subscribed.<br>(Does not include the Monthly Sub's instant reward.) |
| 260001 | Shooting Star 퍼펙트 달성!<br>당신에게서 샛별같은 재능이 느껴집니다! | Perfect score on Shooting Star!<br>You've got the talent of a rising star! |
| 260002 | 두둥실 퍼펙트 달성!<br>벅찬 마음이 하늘 높이 두둥실! | Perfect score on Floating!<br>Heart full of excitement, floating high up in the sky! |
| 260003 | Love Note 퍼펙트 달성!<br>사랑하는 이에게 두근거리는 이 마음이 닿을 수 있기를… | Perfect score on Love Note!<br>May this fluttering heart reach the loved one... |
| 260004 | Yum 퍼펙트 달성!<br>자신의 한계를 깨고 나와 더 넓은 에덴으로! | Perfect score on Yum!<br>Push past your limits and step into a wider Eden! |
| 260005 | Shooting Star 스테이지에서 시그니처 댄스 타임!<br>나만의 빛나는 별, 누구보다 빛나는 스타! | Spotlight dance on the Shooting Star Stage!<br>My own radiant star, outshining everyone else! |
| 260006 | 두둥실 스테이지에서 시그니처 댄스 타임!<br>당신의 기분을 두둥실, 설레게 만들 윙크! | Spotlight dance on the Floating Stage!<br>With winks that will make your spirits float in excitement! |
| 260007 | Love Note 스테이지에서 시그니처 댄스 타임!<br>내 하트의 반쪽! 당신이 가득 채워주지 않을래요? | Spotlight dance on the Love Note Stage!<br>Would you fill up the missing half of my heart? |
| 260008 | Yum 스테이지에서 시그니처 댄스 타임!<br>잊을 수 없는 마음을 담아, 당신에게 잊지 못할 시간을! | Spotlight dance on the Yum Stage!<br>Offering you an indelible moment with this unforgettable heart! |
| 318001 | 행복한 크마리스스 파티 꾸러미(종료) | Happy Kumawreaths Party Bundle (Expired) |
| 318002 | 수집 이벤트 아이템(종료) | Collection Event Item (Expired) |
| 318003 | 금빛 꿈주머니(종료) | Gold Dream Pouch (Expired) |
| 318004 | 사랑의 묘약(종료) | Love Potion (Expired) |
| 318005 | 행운의 꽃잎(종료) | Lucky Petal (Expired) |
| 318006 | 에버스쿨 경품 메달(종료) | Everschool Prize Medal (Expired) |
| 318007 | 체육부 딱지(종료) | P.E. Club Voucher (Expired) |
| 318008 | 바른생활부 딱지(종료) | Ethics Club Voucher (Expired) |
| 318009 | 이벤트 레이드 입장권(종료) | Event Raid Ticket (Expired) |
| 318010 | 이벤트 스테이지 입장권(종료) | Event Stage Ticket (Expired) |
| 318011 | 웨딩 부케(종료) | Wedding Bouquet (Expired) |
| 318012 | 웨딩 리본(종료) | Wedding Ribbon (Expired) |
| 318013 | 웨딩 와인(종료) | Wedding Wine (Expired) |
| 318014 | 미니 게임 입장권(종료) | Mini Game Ticket (Expired) |
| 318015 | 비비안의 경품 메달(종료) | Vivienne's Prize Medal (Expired) |
| 318016 | 히비스커스 꽃(종료) | Hibiscus (Expired) |
| 318017 | 시글래스 조각(종료) | Sea Glass Piece (Expired) |
| 318018 | 에덴 갓 탤런트 투표권(종료) | Eden's Got Talent Vote (Expired) |
| 318019 | 빙고 티켓(종료) | Bingo Ticket (Expired) |
| 318020 | 아드리안의 경품 메달(종료) | Adrianne's Prize Medal (Expired) |
| 318021 | 비치볼(종료) | Beach Ball (Expired) |
| 318022 | 러버덕(종료) | Rubber Duck (Expired) |
| 318023 | 보름달 별전(종료) | Full Moon Special Coin (Expired) |
| 318024 | 화전(종료) | Flower Rice Pancake (Expired) |
| 318025 | 송편(종료) | Half-Moon Rice Cake (Expired) |
| 318026 | 할로윈 경품 메달(종료) | Halloween Prize Medal (Expired) |
| 318027 | 빨간 모자 쿠폰(종료) | Red Riding Hood Coupon (Expired) |
| 318028 | 나쁜 늑대 쿠폰(종료) | Bad Wolf Coupon (Expired) |
| 318029 | 붉은 달의 악몽 입장권(종료) | Red Moon Nightmare Ticket (Expired) |
| 318030 | 크리스마스 경품 메달(종료) | Christmas Prize Medal (Expired) |
| 318031 | 도라 친구 배지(종료) | Dora Friend Badge (Expired) |
| 318032 | 가넷 친구 배지(종료) | Garnet Friend Badge (Expired) |
| 318033 | 크마리스스 대소동 입장권(종료) | Kumawreaths Kerfuffle Ticket (Expired) |
| 318034 | 미궁 올스타즈 입장권(종료) | Labyrinth All-Stars Ticket (Expired) |
| 318035 | 훈련 포인트(종료) | Training Point (Expired) |
| 318037 | 탐관오리 클로이 입장권(종료) | Corrupt Official Chloe Ticket (Expired) |
| 318039 | 파티 경품 추첨권(종료) | Mirth Prize Ticket (Expired) |
| 318040 | 별빛 메달(종료) | Starlight Medal (Expired) |
| 318041 | 금빛 챔피언 휘장(종료) | Golden Champion Insignia (Expired) |
| 318042 | 파티 레이드 입장권(종료) | Mirth Raid Ticket (Expired) |
| 318044 | 파라다이스 레이드 입장권(종료) | Paradise Raid Ticket (Expired) |
| 318045 | 메이드 경품 코인(종료) | Maid Prize Coins (Expired) |
| 318046 | 진상 퇴치 딱지 A(종료) | Troublemaker Purge Sticker A (Expired) |
| 318047 | 진상 퇴치 딱지 B(종료) | Troublemaker Purge Sticker B (Expired) |
| 318048 | 쇼콜라 퀸 레이드 입장권(종료) | Chocolat Queen Raid Ticket (Expired) |
| 318050 | 하얀 울새 숲 미니 게임 입장권(종료) | White Robin Forest Mini Game Ticket (Expired) |
| 318054 | 에버스쿨 레이드 입장권(종료) | Everschool Raid Ticket (Expired) |
| 318055 | 어둠의 에버스쿨 경품 메달(종료) | Sinister Everschool Prize Medal (Expired) |
| 318056 | 다프네의 바주카포 단추(종료) | Daphne's Bazooka Button (Expired) |
| 318057 | 마농의 회계부장 딱지(종료) | Manon's Bursar Sticker (Expired) |
| 318058 | 어둠의 학생회장 레이드 입장권(종료) | Sinister Student President Raid Ticket (Expired) |
| 318062 | 부케 쟁탈전 레이드 입장권(종료) | Bouquet Scramble Raid Ticket (Expired) |
| 318063 | 여름 축제 쿠폰(종료) | Summer Festival Coupon (Expired) |
| 318064 | 가온 무투회 레이드 입장권(종료) | Gaon Martial Arts Tournament Raid Ticket (Expired) |
| 318068 | 여름 낙원 탈환 레이드 입장권(종료) | Getting Back Summer Paradise Raid Ticket (Expired) |
| 318071 | 비밀스러운 코르사주(종료) | Secretive Corsage (Expired) |
| 318072 | 비올레트의 웨딩 슈즈(종료) | Violette's Wedding Shoes (Expired) |
| 318073 | 가넷의 웨딩 브로치(종료) | Garnet's Wedding Brooch (Expired) |
| 318074 | 결혼전쟁 레이드 입장권(종료) | Wedding War Raid Ticket (Expired) |
| 318075 | 시도 브로마이드(종료) | Photo of Shido (Expired) |
| 318076 | 콩고물 빵(종료) | Kinako Bun (Expired) |
| 318077 | 검은 고양이 인형(종료) | Stuffed Black Cat (Expired) |
| 318078 | 배틀 어 라이브 레이드 입장권(종료) | Battle A Live Raid Ticket (Expired) |
| 520101 | 방주 오퍼레이터 | Ark Operator |
| 520102 | 오퍼레이터 파이브 | Operator Five |
| 520103 | 고결한 이상 | Noble Ideal |
| 520104 | 봄날의 너 | You Are Like Spring |
| 520105 | 보석 수집가 | Jewelry Collector |
| 520106 | 하늘빛 잔상 | Skylight Afterimage |
| 520107 | 워커홀릭의 일상 | A Workaholic's Daily Life |
| 520108 | 오퍼레이터 나인 | Operator Nine |
| 520109 | 기도하는 마음 | Praying Heart |
| 520110 | 위험: 인화성 물질 | DANGER: Flammable Material |
| 520111 | 곰곰이 생각해 봐 | Bear with the Thoughts |
| 520112 | 적화청운 | Red Flame and Blue Cloud |
| 520113 | 이리 오너라 | Come Here |
| 520114 | 거친 갈기 | Tough Mane |
| 520115 | 달빛의 음색~♪ | Moonlight Tone~♪ |
| 520116 | 별빛의 선율~♬ | Starlight Melody ♬ |
| 520117 | 메릴 기본 코스튬 | Meryl's Basic Costume |
| 520118 | HE 애호가 | HE Lover |
| 520119 | 무영의 암살자 | Shadowless Assassin |
| 520120 | 베테랑 사냥꾼 | Veteran Hunter |
| 520121 | 열이 많은 체질 | Always Hot |
| 520122 | 출출하신 분? | Anyone Hungry? |
| 520123 | Mix and Match | Mix and Match |
| 520124 | 이나 기본 코스튬 | Ina's Basic Costume |
| 520125 | 아이언 피스트 | Iron Fist |
| 520126 | 오직 별님뿐 | Only Star |
| 520127 | 공주 등장! | Enter Princess! |
| 520128 | 기사의 품격 | Knight's Dignity |
| 520129 | 바람과 함께 | With the Wind |
| 520130 | 초속 5킬로미터 | 5 km per Second |
| 520131 | 예절 주입기 | Etiquette Injector |
| 520132 | 왕실 근위대 | Royal Guard |
| 520133 | 자는 거 아냐… | I'm Not Sleeping... |
| 520134 | 살짝만 열어볼게 | Just a Peek |
| 520135 | 사랑스런 소녀와 캐럿 | Lovely Girl and Carrot |
| 520136 | 병약 소녀는 일어나지 않아 | A Sick Girl Stays in Bed |
| 520137 | 산만한 태양의 구속복 | Gigantic Sun Straitjacket |
| 520138 | 차분한 달의 구속복 | Calm Moon Straitjacket |
| 520139 | 쇼는 끝나지 않아 | The Show Never Ends |
| 520140 | MODEL_Prototype | MODEL_Prototype |
| 520141 | 떠올리고 싶지 않은 과거 | Undesirable Past |
| 520142 | 숨막히는 뒷태 | Breathtaking Rear |
| 520143 | 망자의 등대 | Lighthouse of the Dead |
| 520144 | 콩 콩 콩 | Poing Poing |
| 520145 | 양파 아니랍니다 | Not an Onion |
| 520146 | 심판을 받아라 | Be Judged |
| 520147 | 사논 기본 코스튬 | Sanon's Basic Costume |
| 520148 | 헬레나 기본 코스튬 | Helena's Basic Costume |
| 520149 | 품격의 완성 | Peak Elegance |
| 520150 | 붉은 실의 인연 | Intertwined With Red |
| 520151 | 새로운 일상 | New Routine |
| 520152 | 엘레간테 | Elegante |
| 520153 | 만두필승! | Dumplings for Winners! |
| 520154 | 엘리트의 품위 | Elite Dignity |
| 520155 | 대장간의 노란 꽃 | Yellow Flower in the Forge |
| 520156 | 그건 잔상입니다 | Just a Mirage |
| 520157 | 영원한 태양의 예복 | Eternal Sun's Robe |
| 520158 | 아카이토 | Akaito |
| 520159 | 타락의 증표 | Token of Corruption |
| 520160 | 블루 나이팅게일 | Blue Nightingale |
| 520161 | 그렇지 물어와 | Fetch |
| 520162 | 권력의 상징 | Symbol of Power |
| 520163 | 광휘의 수호자 | Guardian of Radiance |
| 520164 | 미래를 향한 파도 | Waves Facing the Future |
| 520165 | 죽음의 심판관 | Judge of Death |
| 520166 | 밤의 지배자 | Ruler of the Night |
| 520167 | 바다의 소리 | Sea Sound |
| 520168 | 흑야의 검은 매 | Blackhawk of the Black Night |
| 520169 | 엘로힘 | Elohim |
| 520170 | 아도나이 멜렉 | Adonai Melek |
| 520171 | 코드: 디폴트 | Code: Basic |
| 520172 | 선명한 녹음 | Vibrant Greenery |
| 520173 | 돌아온 권력 | Reclaimed Might |
| 520174 | 여명의 별빛 | Starlight of Dawn |
| 520175 | 브리기트 기본 코스튬 | Brigid's Basic Costume |
| 520176 | 홍염의 후예 | Descendant of Prominence |
| 520177 | 일기당천 | Solitary Decimator |
| 520178 | 서방의 백호 | White Tiger of the West |
| 520179 | 파도의 주인 | Mistress of the Waves |
| 520180 | 백은의 공주 | The Argent Princess |
| 520181 | 결전 장비: 허영 | Endgame Gear: Vanity |
| 520182 | 보좌관의 의무 | Assistant's Duty |
| 520183 | 가온의 취검 | Gaon's Drunken Sword |
| 520184 | 이오루의 수호자 | Guardian of Ioru |
| 520185 | 마리오네트 엘레지 | Marionette Elegy |
| 520186 | 억겁의 형벌 | Eons of Punishment |
| 520187 | 황금의 날개 | Golden Wings |
| 520188 | 쇼비즈 | Showbiz |
| 520189 | 해방된 천사 | Liberated Angel |
| 520190 | 영원한 종말의 의복 | Eternal End Ensemble |
| 520191 | 망월기원 | Wishful Moongazing |
| 520401 | 두근두근 분홍 젤리 | Fluttering Pink Jelly |
| 520402 | 쫑긋쫑긋 파스텔 버니 | Perky Ears Pastel Bunny |
| 520403 | 짓궂은 장난 | Cheeky Mischief |
| 520404 | 푸른 늑대의 호위무사 | Blue Wolf's Guard Warrior |
| 520405 | 고백의 순간 | Moment of Confession |
| 520406 | 발포하겠어 | I'll Fire |
| 520407 | 햇빛의 리듬~♩ | Sunshine's Rhythm~♩ |
| 520408 | 앵사취설 | Cherry Blossoms and Snake |
| 520409 | 일기 예보: 흐림 | Weather Forecast: Cloudy |
| 520410 | 주의: 거리의 바람 | Caution: Street Wind |
| 520411 | 베어 A LA MODE | Bear a la Mode |
| 520412 | 축배의 푸른 밤 | Toast to a Blue Night |
| 520413 | 나 한 입만 | Can I Have a Bite? |
| 520414 | 폭신폭신 발망치 | Fluffy Paw Hammer |
| 520415 | 밤의 미라쥬 | Night Mirage |
| 520416 | 핑크 에트왈 | Pink Star |
| 520417 | 메릴 인연 코스튬 이름 | Meryl's Bond Costume Name |
| 520418 | 플린 인연 코스튬 이름 | Flynn's Bond Costume Name |
| 520419 | 로즈 가든 | Rose Garden |
| 520420 | 자작나무 숲의 그림자 | Shadow of the Birch Forest |
| 520421 | 기분 좋은 꿈 | Good Dream |
| 520422 | 풍요의 여신 | Goddess of Abundance |
| 520423 | 아, 아픈 친구 있어? | Is, Is Anyone Sick? |
| 520424 | 이나 인연 코스튬 이름 | Ina's Bond Costume Name |
| 520425 | 마이 페어 레이디 | My Fair Lady |
| 520426 | 한밤의 꿈꾸는 소녀 | Midnight Dreaming Girl |
| 520427 | 마린 프린세스 | Marine Princess |
| 520428 | 공주의 침실 | Princess's Room |
| 520429 | 여유로운 한 때 | Moment of Leisure |
| 520430 | 원초의 취옥 | Primordial Emerald |
| 520431 | 거리의 셀레네 | Selene on the Street |
| 520432 | 샤이닝 치어 걸 | Shining Cheerleader |
| 520433 | 신록의 계절 | Season of Verdure |
| 520434 | 주문은 유혹입니까 | Temptation Spell? |
| 520435 | 고양이 보러 갈래? | Wanna See My Cat? |
| 520436 | 불사의 레베카 | Rebecca the Immortal |
| 520437 | 사관학교의 햇님 | Military Academy's Sun |
| 520438 | 사관학교의 달님 | Military Academy's Moon |
| 520439 | 베테랑 퍼레이드 리더 | Veteran Parade Leader |
| 520440 | MODEL_DarkShadow | MODEL_DarkShadow |
| 520441 | 시집과 가을의 너 | Poetry and Your Autumn |
| 520442 | 꿈꾸는 무희 | Dreaming Dancer |
| 520443 | 밤에 피는 나비 | Nocturnal Butterfly |
| 520444 | 마이 컬러풀 걸프렌드 | My Colorful Girlfriend |
| 520445 | 북극성의 흑조 | Black Swan of the North Star |
| 520446 | 원더 히어로 | Wonder Hero |
| 520447 | 사논 인연 코스튬 이름 | Sanon's Bond Costume Name |
| 520448 | 헬레나 인연 코스튬 이름 | Helena's Bond Costume Name |
| 520449 | 흑익의 천사 | Dark Angel |
| 520450 | 행복한 맺음 | Happy Ending |
| 520451 | 손안의 온기 | Palm of Warmth |
| 520452 | 최고의 곰돌이 | Best Teddy |
| 520453 | 이상한 꿈결의 원님 | Magistrate's Strange Dream |
| 520454 | 이상한 꿈결의 여우 | Fox's Strange Dream |
| 520455 | 스트릿 무드 | Street Mood |
| 520456 | 순정 쇼콜라티에 | Pure Heart Chocolatier |
| 520457 | 달콤살벌 메이드 | Sweet Savage Maid |
| 520458 | 녹음의 행운 | Lush Luck |
| 520459 | 풀내음과 함께 | Feel the Grassy Scent |
| 520460 | 노히트 노런 | No-hitter |
| 520461 | 벌점이야 | Demerits |
| 520462 | 푹신푹신 학교 생활 | Comfy School Life |
| 520463 | 매지컬 프린세스 | Magical Princess |
| 520464 | 리틀 부케 | Little Bouquet |
| 520465 | 와인 샤워 | Wine Shower |
| 520466 | SHADOW_EX_MACHINA | SHADOW_EX_MACHINA |
| 520467 | DAEMON_EX_MACHINA | DAEMON_EX_MACHINA |
| 520468 | 오늘의 라이더 | Today's Rider |
| 520469 | 퓨어하트 로맨스 | Pure Heart Romance |
| 520470 | 죄악의 취옥 | Emerald of Iniquity |
| 520471 | 유배된 취옥 | Emerald of Exile |
| 520472 | 해변의 마녀 | Witch of the Sea |
| 520473 | 묘지기의 여름 | Grave Keeper's Summer |
| 520474 | 여름의 마성 | Summer Demon |
| 520475 | 사무치는 그리움 | Poignant Yearning |
| 520476 | 끝내 오지 않은 구원 | Never-Coming Salvation |
| 520477 | 해변의 반짝임 | Sparkling Beach |
| 520478 | 눈부신 마음 | Dazzling Feeling |
| 520479 | 해중일화 | Under the Sea |
| 520480 | 바다 지킴이 | Seakeeper |
| 520481 | 포효하는 광기 | Roaring Madness |
| 520482 | 전율하는 광기 | Shivering Madness |
| 520483 | 비탄의 성녀 | Saint of Sorrow |
| 520484 | 혼돈의 성녀 | Saint of Chaos |
| 520485 | 춘추 벚꽃 | Blooming Cherry Blossom |
| 520486 | 백의홍상 | White Scarlet |
| 520487 | 달토끼 전설 | Legend of Moon Rabbit |
| 520488 | 아찔한 일식 | Dazzling Solar Eclipse |
| 520489 | 월하의 사냥꾼 | Moonlight Hunter |
| 520490 | 만월의 리벤저 | Revenger of the Full Moon |
| 520491 | 빨간 모자의 장난 | Mischievous Red Riding Hood |
| 520492 | 굿바이 여름!! | Farewell Summer!! |
| 520493 | 전쟁의 사도 | Apostle of War |
| 520494 | 전쟁의 화신 | Incarnation of War |
| 520495 | 밤의 비서 | Night Secretary |
| 520496 | 멜티 버니 | Chocobunny |
| 520497 | 눈꽃의 수녀 | Nun of Snowflakes |
| 520498 | 성야의 백곰 | White Bear of Starry Night |
| 520499 | 선물은 나♥ | The Gift Is Me♥ |
| 520500 | 드리밍 블루 | Dreamy Blue |
| 520501 | 하트풀 스텝 | Heartful Steps |
| 520502 | 레이지 옐로 | Mellow Yellow |
| 520503 | 멜티 스위트 | Melty Sweets |
| 520504 | 라비앙 로즈 | La Vie en Rose |
| 520505 | 모레노 옵시디언 | Morreno Obsidian |
| 520506 | 라피아 다이아몬드 | Raffia Diamond |
| 520507 | 다이난 사파이어 | Dynan Sapphire |
| 520508 | 청천청화 | Sky Blue Bloom |
| 520509 | 쇼콜라 퀸 | Chocolat Queen |
| 520510 | 스위트 매직 | Sweet Magic |
| 520511 | 레드벨벳 하트 | Red Velvet Heart |
| 520512 | 메디컬 디렉터 | Medical Director |
| 520513 | 붉은 달의 검귀 | Red Moon Sword Demon |
| 520514 | 붉은 달의 연인 | Red Moon's Sweetheart |
| 520515 | 입어줘, 세일러복! | Sailor Uniform On! |
| 520516 | 영원의 학생회장 | Forever Student President |
| 520517 | 단추 발사대 | Button Launcher |
| 520518 | 회계부장(입후보 예정) | Bursar (Potential Candidate) |
| 520519 | 흔들림 없는 마음 | Unwavering Heart |
| 520520 | 한여름의 나팔꽃 | Midsummer Morning Glory |
| 520521 | 한낮의 윤슬 | Midday Glimmer |
| 520522 | 마르치알레 | Marziale |
| 520523 | 설레는 새 학기 | Exciting New Semester |
| 520524 | 생명의 윤회 | Cycle of Life |
| 520525 | 황제의 왼팔 | The Left Arm of the Empress |
| 520526 | 수상한 스카우터 | Suspicious Headhunter |
| 520527 | 검은 매의 일상 | Blackhawk Daily Wear |
| 520528 | 눈꽃의 서약 | Oath of Snowflakes |
| 520529 | 스트로베리 허니문 | Strawberry Honeymoon |
| 520530 | 시크릿 웨딩 바니 | Secret Wedding Bunny |
| 520531 | 모드: 카모플라쥬 | Mode: Camouflage |
| 520532 | 어두운 밤의 비너스 | Dark Night Venus |
| 520533 | 거울 속의 고양이 | Cat in Mirror |
| 520534 | 큐트·패닉·서머 | Cute Summer Panic |
| 520535 | 매니저의 여름 | Manager's Summer |
| 520536 | 칠흑의 파괴자 | Dark Destroyer |
| 520537 | 칠흑의 대적자 | Dark Contender |
| 520538 | 바니 헌터 | Bunny Hunter |
| 520539 | 문라이트 댄서 | Moonlight Dancer |
| 520540 | 나이트메어 쉽 | Nightmare Sheep |
| 520541 | 살랑살랑 폭시 나이트 | Whimsical Foxy Nightwear |
| 520542 | 로열 나인 | Royal Nine |
| 520543 | 운명의 긴 그림자 | Looming Shadow of Destiny |
| 520544 | 마이 페어 레이디 | My Fair Lady |
| 520545 | 수줍은 개화 | Bashful Blossom |
| 520546 | 입었노라, 세일러복! | Sailor Uniform Donned! |
| 520547 | 아수라의 환상 | Asura's Illusion |
| 520548 | 흑접지몽 | Black Butterfly's Dream |
| 520549 | 악접지몽 | Evil Butterfly's Dream |
| 520550 | 스노우 메르헨 | Snow Fantasy |
| 520551 | 레디메이드 홀리데이 | Ready for the Holidays |
| 520552 | 봄버 캐롤!! | Festive Bomber |
| 520553 | 기만의 악마 | Demon of Deception |
| 520554 | 한낮의 꽃잎 | Petals of Midday |
| 520555 | 코드: 이머전시 | Code: Emergency |
| 520556 | 자애의 햇살 | Gracious Sunlight |
| 520557 | 재복의 도래 | Unfolding Fortune |
| 520558 | 희망찬 한 걸음 | Hopeful First Step |
| 520559 | 태양의 그늘 | Shade of the Sun |
| 520560 | 심연의 마녀 | Witch of the Abyss |
| 520561 | 새로운 봄바람 | Fresh Spring Breeze |
| 520562 | 도원향 | Fragrant Peach Blossoms |
| 520563 | 난공불락 | Impenetrable Protection |
| 520564 | 장수의 마음 | Heart of a General |
| 520565 | 속세 나들이 | Visiting the Outside World |
| 520566 | 주단의 흑호 | Black Tiger in Silk |
| 520567 | 프로젝트: 이데아 | Project: Idea |
| 520568 | 미궁 브레이커 | Labyrinth Breaker |
| 520569 | 청해의 인어 | Mermaid of the Blue Sea |
| 520570 | 봄의 물보라 | Springtime Water Splash |
| 520571 | 공주는 출장 중! | Princess on Official Business! |
| 520572 | 실버 라이닝 | Silver Lining |
| 520573 | 한밤중의 오로라 | Midnight Aurora |
| 520574 | 현자의 제자 | Sage's Disciple |
| 520575 | 모드: 오피스 | Mode: Office |
| 520576 | 결전 장비: 백설 | Endgame Gear: White Snow |
| 520577 | CODE NAME: ALL-IN | CODE NAME: ALL-IN |
| 520578 | 깊은 구덩이 | Deep Pit |
| 520579 | 나이트로즈 | Night Rose |
| 520580 | 파이어스타터 | Fire Starter |
| 520581 | Maid In Perfection | Maid in Perfection |
| 520582 | 햇님을 위한 메이드복 | Maid Uniform for the Sun |
| 520583 | 달님을 위한 메이드복 | Maid Uniform for the Moon |
| 520584 | 새출발의 발걸음 | Strides of a Fresh Start |
| 520585 | 오지 않은 미래 | Unrealized Future |
| 520586 | 데일리 언더테이크 | Daily Undertaker |
| 520587 | 커버링 언더테이크 | Undertaker's Covering |
| 520588 | 밤의 마리오네트 | Marionette of Night |
| 520589 | 조소하는 자 | The Scorner |
| 520590 | 사랑스러운 충동 | Lovely Impulse |
| 520591 | 프리즈너스 홀리데이 | Prisoner's Holiday |
| 520592 | 셀러브리티 홀리데이 | Celebrity Holiday |
| 520593 | 로맨싱 섬머 | Romancing Summer |
| 520594 | 모데스티 홀리데이 | Modesty Holiday |
| 520595 | 코드 퍼플 | Code Purple |
| 520596 | 글로리아 팝 | Gloria Pop |
| 520597 | 러블리 팝 | Lovely Pop |
| 520598 | 폴링시크 팝 | Falling Chic Pop |
| 520599 | 백성의 생활 | Civilian Life |
| 520600 | 고귀한 핏줄 | Noble Bloodline |
| 520601 | 나이트로즈 | Night Rose |
| 520602 | 파이어스타터 | Fire Starter |
| 520603 | 심플 이즈 베스트 | Simple Is Best |
| 520604 | 해상 취객 | Seafaring Drunkard |
| 520605 | 뒷골목의 방랑자 | Backalley Drifter |
| 520606 | 소매치기의 잔상 | Pickpocket Afterimage |
| 520607 | 광휘의 그림자 | Shadow of Radiance |
| 520608 | 타오르는 태양의 의복 | Blazing Sun Garment |
| 520609 | 알레그로 비바체 | Allegro Vivace |
| 520610 | 거짓된 수호의 증표 | False Token of Guardianship |
| 520611 | 제국의 공작 | Imperial Duchess |
| 520612 | 순결한 영혼 | Pure Spirit |
| 520613 | 우주의 소리 | Cosmic Sound |
| 520614 | 새로운 봄의 시작 | Beginning of New Spring |
| 520615 | 마지막 선택 | Final Choice |
| 520616 | 신벌의 불꽃 | Flames of Divine Retribution |
| 520617 | 해피 바니 크리스마스 | Happy Bunny Christmas |
| 520618 | 순백의 오퍼레이터 | Pure White Operator |
| 520619 | 몽환의 화원 | Dreamy Flower Garden |
| 520620 | 낮과 밤의 경계 | Between Day and Night |
| 520621 | 추락하는 태양의 의복 | Falling Sun Garment |
| 520622 | 새해의 아이돌 | New Year's Idol |
| 520623 | 새로운 종말 | A New End |
| 520624 | 월식악몽 | Lunar Eclipse Nightmare |
| 520625 | 만월인연 | Full Moon Connection |
| 520998 | 밀키웨이 보이스 | Milky Way Voice |
| 520999 | 스타라이트 리듬 | Starlight Rhythm |
| 530101 | 특수 소재로 만든 첨단 의류.<br>착용자의 신체 사이즈에 맞게 자동으로 변화한다. | A hi-tech garment made from special materials.<br>It changes flexibly to fit the wearer's body size. |
| 530102 | 잘 오염되지 않는 특수 소재로 만들어진 첨단 메이드복.<br>심하게 오염된 곳이어도 이 메이드복과 함께라면<br>더러워지지 않고 청소할 수 있다. | A high-tech maid uniform crafted from a unique, stain-resistant material.<br>With this outfit, even the grimiest spots can be tackled<br>without fear of getting dirty. |
| 530103 | 순결한 기사의 마음처럼 빛나는 갑옷.<br>백합에 맺힌 이슬처럼 경건하게 반짝인다. | A suit of armor that shines like the heart of an innocent knight.<br>It shines reverently like dew on a lily. |
| 530104 | 봄의 두근거림이 느껴지는 옷.<br>꽃 피는 계절의 아름다움이 고스란히 담겨있다. | A garment that reminds you about the excitement of spring.<br>It exudes the beauty of the blooming season. |
| 530105 | 금과 보석으로 치장한 럭셔리 드레스.<br>섬세한 금장식과 실크, 황금 구두로 이루어져 있다. | A luxurious dress adorned with gold and jewels.<br>It consists of delicate gold ornaments, silk, and golden shoes. |
| 530106 | 날렵한 움직임을 고려한 단정한 의복.<br>단추 하나의 오차도 허용하지 않는 완벽함이 돋보인다. | A neat garment flexible for agile movement.<br>It's perfect, without a single button that's misaligned. |
| 530107 | 전체적으로 심플하지만 과감한 포인트도 겸비한 오피스룩.<br>깔끔한 배색으로 고급스러움까지 자아낸 디자인이다. | A simple office look with bold detailing.<br>The arrangement of colors adds elegance to the design. |
| 530108 | 특수 소재로 만든 첨단 의류.<br>인간의 왕을 섬기며 헌신을 바치는<br>그 모습은 언제나 완벽하고, 때로는 냉혹하다. | A high-tech garment made from special fabric.<br>Its wearer shows flawless dedication to serving the ruler of humans,<br>sometimes with a touch of icy ruthlessness. |
| 530109 | 긴 베일과 카라가 인상적인 수도자의 옷.<br>팔락이는 치맛자락에 애교 섞인 귀여움이 한 스푼 더해졌다. | A nun's costume with an impressive long veil and collar.<br>A spoonful of adorableness was added to the fluttering skirt hem. |
| 530110 | 진한 럼주 대신 샴페인의 상쾌함이 느껴지는 옷.<br>바닷사람의 상징이라는 높은 모자와 부츠, 피스톨을 모두 갖추었다. | A costume that feels fresh like champagne rather than dark like rum.<br>It is fully equipped with a tall hat, boots, and a pistol, which are the symbols of a seaman. |
| 530111 | 귀여운 곰돌이 모자와 동그란 손발이 인상적인 의상.<br>따스하고 포근한 데다가 편안하다! | A costume with a rounded bear hat and padded hands and feet.<br>It's soft and comfy! |
| 530112 | 붉은 천에 금사로 용이 수 놓인 편안한 의상.<br>푸른 구름 위의 아름다운 한 떨기 꽃과 다름없다. | A comfortable costume embroidered with a dragon in gold thread on a red cloth.<br>It's like a beautiful lone flower standing tall on top of a cloud. |
| 530113 | 목화처럼 부푼 치마와 작은 털 방울 장식이 귀여운 의상.<br>떨잠을 닮은 작은 거북이 친구도 잊지 마시라! | A fluffy dress with small cotton ball decorations.<br>Don't forget the ornamental little turtle! |
| 530114 | 거친 털과 가죽으로 무두질 한 옷.<br>무서워 보이지만 특징이 확실한 머리 장식이 자랑거리다. | A costume with coarse fur and tanned leather.<br>It looks scary but works perfectly well as a unique head decoration. |
| 530115 | 따듯한 푸른빛이 아름다운 무대 의상.<br>밤의 노래는 안락한 낮은 음자리의 목소리를 타고 퍼져나간다. | A beautiful blue stage costume.<br>Songs of the night resound through a low-pitched comforting voice. |
| 530116 | 스포트라이트보다 더 빛나는 무대 의상.<br>무대 위 빛나는 모습은 높은 음자리의 선율처럼 경쾌하다. | A stage costume that shines brighter than the spotlight.<br>Its shining figure on the stage feels cheerful like a melody with high notes. |
| 530117 | 메릴 기본 코스튬 설명 | Meryl's Basic Costume Description |
| 530118 | 매캐한 연기와 불 냄새가 밴 스포티한 의상.<br>손에 묻은 검댕을 대충 문질러 닦아도 티가 나지 않는다. | A sporty outfit permeated by the strong smell of acrid smoke and fire.<br>Even if you rub this outfit roughly with your sooted hands, it doesn't leave a mark. |
| 530119 | 타샤의 가벼운 활동복.<br>천을 최소화해 바람에 스치는 소리조차 나지 않는다. | Tasha's light activewear.<br>The minimal fabric makes no sound even against the wind. |
| 530120 | 문양과 머리 장식이 독특한 사냥꾼 의상.<br>두 귀가 감춰질 만큼 커다란 후드가 인상적이다. | A hunter costume with a unique pattern and hair accessory.<br>It has an impressive-looking hood that's large enough to cover both ears. |
| 530121 | 통풍의 기능성을 극대화한 갑옷.<br>금속이 살에 닿는 부위는 폭신한 양털로 마감했다. | A suit of armor that maximizes the functionality of ventilation.<br>The parts where the metal touches the skin is finished with a fluffy fleece. |
| 530122 | 다정다감한 데이지 꽃이 생각나는 원피스.<br>수제 피크닉 바구니에선 빵 냄새와 들꽃 향기가 가득하다. | A dress reminiscent of a friendly daisy flower.<br>The handmade picnic basket is full of the smell of bread and the fragrance of wildflowers. |
| 530123 | 활동성과 보온을 중시한 아틀리에 연구원 복장.<br>걸음마다 각양각색의 시약들이 찰랑거리는 소리가 들린다. | Atelier researcher attire made for activity and warmth.<br>You can hear the various reagents clink together when walking around in this outfit. |
| 530124 | 이나 기본 코스튬 설명 | Ina's Basic Costume Description |
| 530125 | 머플러로 포인트를 준 캐주얼한 옷.<br>바람을 타고 춤추는, 긴 궤적의 독보적인 멋이 살아있다. | A casual costume highlighted with a scarf.<br>It dances and waves around in the wind. |
| 530126 | 별님을 향한 기도가 담긴 의상.<br>포근한 망토는 별똥별의 긴 꼬리처럼 살랑거린다. | A costume that contains prayers for the stars.<br>The snug cloak rustles like the long tail of a shooting star. |
| 530127 | 칸나 입맛대로 개조된 귀여운 제복.<br>소매의 프릴 장식이 포인트로, 칸나가 직접 골랐다고 한다. | A cute uniform customized to Kanna's taste.<br>Highlighted by frilly sleeves, a detail that Kanna picked out herself. |
| 530128 | 이디스는 기억한다. 옷을 갖춰 입음으로써 생기는 품격은 무시할 수 없다는 말을. 그래서 공주에서 기사가 되었어도 그녀는 여전히 옷차림을 신경 쓰고 있다. | Edith still remembers these words: "You can't ignore the elegance you get from dressing nicely." That's why she still cares about her attire even after she's become a knight. |
| 530129 | 숲을 수호하는 베테랑 숲지기인 니콜이 애용하는 활동복. <br>보기보다 신축성이 강하고 활동하기도 편하다. | Veteran Forest Keeper Nicole's favorite activewear.<br>Offers surprising flexibility and ease of movement. |
| 530130 | 여러 가지 의미로 시원해 보이는 마법사 의상.<br>마녀가 꼭 나쁜 것도, 검은 옷을 입어야 하는 것도 아니란다. | A witch's costume that looks cool in many ways.<br>A witch doesn't have to always be mean, and doesn't always have to wear black. |
| 530131 | 실전 활동보다 예식에 어울리는 제복.<br>법과 규칙, 그리고 이것 앞에서는 모두가 평등하다. | A uniform that's suitable for ceremonies rather than actual activities.<br>Everyone is equal before laws, rules, and this uniform. |
| 530132 | 가벼운 금속에 보호대로 튼튼함을 더한 의복.<br>절대 꺾이지 않는 다부진 의지와 용기가 느껴진다. | A garment made of lightweight metal reinforced with a protector.<br>Strong will and courage will never be broken. |
| 530133 | 금방이라도 날아오를 듯 가벼운 잠옷.<br>나이트 캡에서 풍기는 라벤더 향기가 은은하다. | A pair of pajamas that are so light they might float into the air.<br>The nightcap has a subtle lavender scent. |
| 530134 | 짙은 어둠을 닮은, 매력적인 실루엣의 드레스.<br>검게 피어난 꽃봉오리 속에는 달콤한 속삭임이 가득하다. | A dress with a charming silhouette that resembles thick darkness.<br>The black buds are full of sweet whispers. |
| 530135 | 귀여운 스티치와 리본이 장식된 드레스.<br>사랑스러운 얼굴로 상처 가득한 인형을 안고 있는 모습이 묘한 호기심을 자극한다. | A ribbon dress and a cute stitched doll.<br>Her smiling with a doll full of stitches raises many questions. |
| 530136 | 하늘하늘한 셔링으로 멋을 낸 편안한 드레스.<br>넉넉한 실루엣에 초커. 공단으로 만든 리본이 독특한 느낌이다. | A comfortable dress styled with fluffy shirring.<br>The choker with a loose silhouette and the ribbon made of satin feels unique. |
| 530137 | 금색과 분홍색으로 포인트를 준 새하얀 의상.<br>금속 장신구들과 구속구가 어딘가 위험한 인상을 풍긴다. | A pure-white outfit accentuated with gold and pink detailing.<br>The metal accessories and harnesses give off a somewhat dangerous vibe. |
| 530138 | 금색과 분홍색으로 포인트를 준 새하얀 의상.<br>몸의 일부를 구속하는 검은 가죽 끈은 숨겨진 광기를 억제한다. | A pure-white outfit accentuated with gold and pink detailing.<br>The black leather straps restrict parts of her body, suppressing her latent lunacy. |
| 530139 | 피부톤과 잘 어울리는 푸른 색상의 마술쇼 의상.<br>허리에 달려있는 하늘하늘 커다란 리본이 관객의 시선을 사로잡는다. | Blue magic show costume that goes well with your skin tone.<br>The large fluttering blue ribbon on the waist catches the eyes of the audience. |
| 530140 | 단단한 금속 전신과 조립 부가 고스란히 드러난 조형.<br>철제 외피를 탄성 높은 천으로 감싸 보호해 안정성을 높였다. | A formative piece that clearly exposes the solid metal body and the assembly parts.<br>Its steel outer shell is wrapped with highly elastic cloth for better stability. |
| 530141 | 차가운 흑색 갑주가 곁들어진 어두운 의상.<br>벗어나고 싶지만, 벗어날 수 없는 과거의 흔적을 그대로 품고 있다. | Dark costume with cold black armor attached to it.<br>Displays a past you wish to but cannot escape. |
| 530142 | 얇고 가벼운 천으로 제작된 전통 댄스 의상.<br>엉덩이와 팔, 허리를 드러내 춤을 출 때 더욱 매력적이다. | A traditional dance costume made of thin, light fabric.<br>It really stands out when dancing with the hips, arms, and waist exposed. |
| 530143 | 가죽 벨트로 포인트를 준 오버사이즈 핏 의상.<br>음산한 빛을 발하는 랜턴이 망자들을 은은하게 위로해준다. | Oversize fit costume with a leather belt.<br>The creepy light from the lantern consoles the spirits of the dead. |
| 530144 | 신비한 문양이 그려진 긴 소매가 눈에 띄는 의상.<br>독특한 머리 장식과, 봉긋한 속바지. 귀여운 매듭 장식이 달려있다. | A costume with remarkable long sleeves bearing a mysterious pattern.<br>With a unique hair accessory and puffy underpants. Decorated with cute Macramé Knots. |
| 530145 | 백조를 닮은 실루엣에 깃털 머리 장식을 단 의상.<br>머리 위의 헤일로와 부활절 달걀이 떠오르는 하의가 특징이다. | A costume with a feathered hair accessory in a silhouette like a swan.<br>It features an overhead halo and bottoms reminiscent of Easter eggs. |
| 530146 | 새의 날개를 상징하는 장식에 황동 갑주가 더해진 의상.<br>결의와 정의로운 마음으로 다져진 갑옷은 어떤 적 앞에서도 당당하다. | A costume with brass armor added to a decoration that symbolizes the wings of a bird.<br>The armor, crafted with a resolute will and a righteous heart, maintains its dignified appearance in the face of any enemy. |
| 530147 | 사논 기본 코스튬 설명 | Sanon's Basic Costume Description |
| 530148 | 헬레나 기본 코스튬 설명 | Helena's Basic Costume Description |
| 530149 | 검은 나비가 눈가에 내려앉은 칠흑의 드레스.<br>품격이 느껴지는 검은 드레스에 시선을 사로잡는 붉은 브로치가 공존한다. | A pitch dark dress accented with a black butterfly.<br>The black dress oozes elegance, and its red brooch is an eye-catcher. |
| 530150 | 피안화와 달이 수놓인 고풍적인 의상.<br>오비의 매듭에 달린 거울 장식과 붉은 양산은 신비로운 분위기를 자아낸다. | A vintage costume decorated with Nirvana flowers and the moon.<br>The mirror ornament and red parasol creates a mysterious look. |
| 530151 | 한 때 지호가 살았던 나라의 복장을 새롭게 재해석한 의상.<br>고전적인 아름다움과 현대적인 발랄함의 공존이 조화롭다. | A costume that reinterprets an attire from a country where Jiho once lived.<br>It features the harmony between classic beauty and modern vividness. |
| 530152 | 헤이즐의 예복. 절제된 컬러감에서 우아함이 느껴진다.<br>재단사가 품격과 활동성을 고려해 만든 의상이라고 한다. | Hazel's ceremonial attire. The toned-down colors exude elegance.<br>The tailor supposedly designed it to offer both sophistication and functionality. |
| 530153 | 「대성만두」 일등 배달부의 통통 튀는 매력이 느껴지는 복장.<br>언제 어디서든 따끈한 만두를 집어 먹을 수 있도록 지참한 개인 젓가락에서 만두에 대한 진심을 엿볼 수 있다. | A charming outfit of Daesung Dumplings' number 1 delivery Soul.<br>Her chopsticks are always ready for her to eat dumplings whenever and wherever she wants to. |
| 530154 | 고급스러운 원단과 단정한 디자인이 돋보이는 복식.<br>작은 포인트 장식들이 단조로움을 잡아주고 있다. | A neatly designed costume made of refined fabric.<br>It doesn't look dull thanks to its little details. |
| 530155 | 신축성 있고 편안한 소재로 만들어진 대장장이 의상.<br>귀여운 노란색 포인트들이 마치 대장간에 피어난 한송이 꽃같다. | A comfortable blacksmith outfit made of stretchable material.<br>The yellow decoration looks like a flower blooming in the forge. |
| 530156 | 에일린의 일상복. 옷소매가 네 개인 건 상대를 방심시키기 위해서라고 한다. | Eileen's everyday clothing. She says there's four sleeves on it so that she can confuse others. |
| 530157 | 성스러운 태양의 가호가 함께하는 찬란한 전투복.<br>여왕 유리아는 항상 이 의상을 입고 늠름하게 전장으로 향했다. | Combat suit blessed with the holy Protection of the Sun.<br>Yuria always wore this whenever she bravely entered into the battlefield. |
| 530158 | 붉은 색과 하얀 프릴, 그리고 검은색의 조합이 인상적인 가온풍 의상. <br>누가 뭐라고 하건 자신이 좋을 대로 하겠다는 오토하의 강렬한 성격이 드러나고 있다. | A Gaon outfit with white frills, and a harmonious mix of red and black colors.<br>It really brings out Otoha's "I do what I want" personality. |
| 530159 | 수많은 피의 기억에 물들어 타락한 이브의 모습.<br>아무리 세상이 그녀를 악이라 매도한들, 세상은 그녀를 원하기를 멈출 수 없다. | Eve, tarnished by an ocean of bloody memories.<br>The world may label her vile, yet its yearning for her never ceases. |
| 530160 | 검고 푸른 색이 특징적인 칼라르 암즈 코퍼레이션의 의료부 제복. <br>어둠 속에서도 안전하게 녹아들어 적들의 습격에 대비할 수 있다. | Uniform of the Chalar Arms Corporation's medical team in striking black and blue.<br>Designed to meld into the shadows, it ensures readiness against any surprise attack. |
| 530161 | 그림자와 매의 깃털을 표현한 의상.<br>매력적인 옷을 입어도, 누군가에겐 커다란 횃대일 뿐이다. | A costume that captures the essence of shadows and hawk feathers.<br>No matter how fashionably Nicole dresses, she's still just a walking perch in the eyes of a particular hawk. |
| 530162 | 화려한 색감과 사치스러운 장식이 돋보이는 가온풍 의상.<br>옷의 주인이 영주의 자리에 오르자마자 주문한 옷이라고 한다. | A Gaon style outfit distinguished by its brilliant colors and extravagant embellishments.<br>Reportedly, it was commissioned by its owner immediately upon ascending to lordship. |
| 530163 | 태양의 가호를 받아 찬란하게 빛나는 순백의 전투복.<br>모두를 지키고자 하는 강한 결의는 정화의 홍염으로 변할지어니. | Pure white battle suit dazzling with the sun's blessing.<br>The firm resolve to protect everyone will turn into purifying flames. |
| 530164 | 도미니크가 공식석상에서 입는 예복.<br>트로이카의 바다와 항구가 떠오르는 디자인이다. | Dominique's formal attire for public events.<br>The design seems to allude to the sea and ports of Troyca. |
| 530165 | 죽음의 기운을 두른 라리마의 의상.<br>심판관의 가면은 먼저 떠나간 이들의 모습을 본떠 추억하고 있다. | Larimar's outfit, shrouded in the aura of death.<br>The mask of the judge reflects and honors the faces of the dear departed. |
| 530166 | 광활한 지하 세계, 밤의 도시를 다스리는 지배자의 의상.<br>어둠 속에 녹아드는 우아함, 그리고 위험한 대범함이 느껴진다. | Outfit of the ruler of Night City, the expansive underworld.<br>It captures the elegance and dangerous boldness of those who fade into the darkness. |
| 530167 | 오닉스의 일상복.<br>언제 어디서나 바다에 뛰어들 수 있도록 방수 원단으로 만든 수영복이다.<br>안이 비치는 파격적인 디자인이지만, 오닉스는 신경 쓰지 않는 듯하다. | Onyx's daily wear.<br>Crafted from waterproof material, this swimsuit is perfect for spontaneous dips in the ocean.<br>Onyx doesn't seem to mind its bold see-through design. |
| 530168 | 죽음의 권능을 품고 다시 태어난 린지의 새로운 전투복.<br>원래도 뛰어났던 린지의 기동력을 극한까지 보조하는 초경장이다. | New battlesuit of Linzy, who was reborn with the power of death.<br>This ultra-light armor boosts her natural agility to unprecedented levels. |
| 530169 | 피처럼 붉은색과 그림자 같은 검은색으로 구성된 영력 드레스. <br>그 불길하면서도 우아한 모습은 달콤한 몽마의 유혹을 연상시킨다. | Spiritual dress in crimson red and shadow-like black.<br>The ominous yet graceful design hints at the temptation of a sweet demon of dreams. |
| 530170 | 견고한 갑옷과 빛의 막으로 구성된 공녀형 영장. <br>인간이 행할 수 있는 물리적인 폭력으로는 그 옷깃조차 찢을 수 없다. | Spiritual dress for a noble lady featuring sturdy armor and a veil of light.<br>Human hands alone cannot even tear its hem. |
| 530171 | 칼라르 공화국의 수장이자 에덴 최대 규모 군수 기업의 CEO를 대표하는 기본 복식.<br>손가락 끝에 이르기까지 철저하게 계산된 카리스마가 대중을 압도한다. | The basic attire for the leader of the Republic of Chalar and CEO of Eden's largest military supplier.<br>Charisma engineered to perfection, right down to the fingertips, captivates the masses. |
| 530172 | 한여름의 눈부신 녹음처럼 아름다운 의상.<br>풍성한 소매로 웨리에게 우아함을 더해준다. | A stunning outfit reminiscent of midsummer's vibrant greenery.<br>Its flowing sleeves lend an air of grace to Wheri. |
| 530173 | 검은색과 붉은색이 강렬하게 조화를 이루는 가온풍 의상.<br>아수라의 기운을 받아 기존 형태에서 변형되었다고 한다. | A Gaon-style outfit showcasing a bold fusion of black and red.<br>It was apparently reshaped under the influence of Asura's energy. |
| 530174 | 아득한 은하 너머에서 돌아온 메피스토펠레스의 새 의상. <br>방주 메타트론 시스템과 일체화되어 보다 뛰어난 착용감을 자랑한다. | New attire of Mephistopheles, back from the depths of the far galaxy.<br>Seamlessly integrated with Ark Metatron's system, it offers exceptional comfort. |
| 530175 | 브리기트 임시 | Brigid Temporary |
| 530176 | 태양의 힘을 극대화하는 로제의 의복. <br>소중한 이들을 지키고 싶다는 소망이 느껴진다. | Rose's outfit, which maximizes the power of the sun.<br>Her desire to protect her loved ones can be felt. |
| 530177 | 전장을 가로지르는 용맹무쌍한 영웅의 의상.<br>단신으로 천 명의 적을 쓰러트리는 그 모습은 가히 무쌍이라. | The outfit of a hero of peerless valor.<br>Witness the unmatched power as she conquers a thousand enemies alone. |
| 530178 | 한울이 가온 사방신으로 활동할 때 입는 복장.<br>소탈하면서도 위엄 있는 모습이, <br>그녀의 인품을 잘 표현하고 있다. | Hanul's public attire as a divine guardian of Gaon.<br>The modest yet commanding design<br>captures the essence of her noble character. |
| 530179 | 대영주가 된 지호의 예복.<br>청량한 푸른빛 천과 고급스러운 금빛 자수가 조화를 이룬다. | Jiho's formal attire as a Great Lord.<br>Vibrant blue fabric and exquisite gold embroidery come together in perfect harmony. |
| 530180 | 과거 백은의 공주라 불렸던 시절의 르네의 모습.<br>눈처럼 새하얗고, 얼음처럼 투명하며, 백은처럼 빛난다. | Renee from her past days, when she was known as the Argent Princess.<br>Snow-white, ice-clear, and luminous as silver. |
| 530181 | 미리암을 위해 특별히 제작된 결전 장비.<br>마력 운용을 최적화할 수 있는 신기술은 물론,<br>본래의 전투 스타일에 걸맞는 각종 무기가 준비되었다. | Endgame gear specially crafted for Miriam.<br>It features new technology to optimize mana usage<br>as well as various weapons suited to her original combat style. |
| 530182 | 보좌관의 업무용 유니폼.<br>웨리의 옷과 비슷하게 디자인된 의상으로, 멀리서 봐도 누가 웨리의 보좌관인지 한눈에 알 수 있다. | An assistant's official uniform.<br>Designed to resemble Wheri's attire, it clearly marks its wearer as Wheri's assistant even from a distance. |
| 530183 | 술과 유희, 그리고 낭만을 가득 품은 취검의 복장.<br>취했다고 방심했다간, 목이 날아갈지도 모른다. | An outfit of a drunken swordfighter steeped in booze, merriment, and romance.<br>Don't be fooled by her inebriation. It could cost you your head. |
| 530184 | 이오루를 지키는 자의 의복. <br>이 옷의 주인은 몇백 년, 어쩌면 몇천 년간 변함없이 고향을 지켜왔다. | The attire of the Guardian of Ioru.<br>Its wearer has unwaveringly stood watch over their homeland for centuries, if not for millennia. |
| 530185 | 페트라가 과거, 용병단 스웜프 소속이었던 시절에 입었던 의상.<br>페트라가 아닌 누군가의 고풍스러운 취향이 잔뜩 담겨 있다. | Petra's old outfit from her Swamp days.<br>The vintage flair clearly reflects someone else's taste, not hers. |
| 530186 | 니아가 세계수에 봉인된 후 입게 된 의상.<br>용서받지 못할 죄를 저지른 자는 영원토록 유령처럼 떠도는 형벌을 받게 되었다. | Nia's outfit donned after she was sealed in the World Tree.<br>The punishment for committing an unforgivable sin is endless wandering like a ghost. |
| 530187 | 아우렐리아의 군단장 카넬리안의 위엄이 드러나는 황금의 갑주.<br>태양처럼 빛나는 모습이야말로 영원한 승리의 상징이다. | Golden armor proclaiming Carnelian's dignity as the Commander of the Paladins of Aurelia.<br>The sun-like radiance is the mark of eternal victory. |
| 530188 | 선명한 붉은색이 뇌쇄적인 바니걸 복장.<br>오직 당신과의 유희를 위한 달콤한 독이다. | A seductive red bunny suit.<br>An alluring poison meant only for playful moments with you. |
| 530189 | 자신을 옥죄는 굴레와 숙명에서 벗어나 영혼을 오롯이 구원자에게 바친 클라우디아.<br>구원자와의 계약으로 구원받았다. | Freed from the fetters of destiny that constrained her, Claudia surrendered her soul wholly to Savior.<br>Through the contract with Savior, she found salvation. |
| 530190 | 섭리에 따라 종말의 때가 오면<br>이 의복을 입은 한 정령이 나타나 모든 것을 끝냈다고 전해진다. | It is said that when the time for the End came as ordained by the laws,<br>a Soul donning this garment appeared and ended everything. |
| 530191 | 아주 긴 시간 동안 바라던 '연'이 맺어진<br>달의 신녀를 위한 성스러운 의복. | Sacred attire for a priestess of the moon,<br>marking her long-awaited union of destiny. |
| 530401 | 커다란 고양이 귀 후드가 달린 캐주얼한 잠옷.<br>가슴의 프린팅과 오버니삭스까지 완벽한 고양이 팬의 모습이다. | A pair of casual pajamas with a large hood with cat ears.<br>The print on the chest and the knee-high socks create the perfect look of a cat fan. |
| 530402 | 커다란 토끼 귀 후드가 달린 러블리한 잠옷.<br>원래는 구원자에게 입히기 위해 산 비장의 잠옷이었으나,<br>사이즈가 맞지 않아 벨레드가 직접 입게 되었다고 한다. | Lovely pajamas adorned with large bunny ears on the hood.<br>Originally bought for the Savior, but the size didn't fit.<br>And so, Beleth wears them now. |
| 530403 | 활동성을 보장하면서도 섹시한 느낌을 주는 스포티한 비키니.<br>원래는 래시가드 수영복이었으나 누군가가 마법으로 살짝 장난을 쳐놨다. | A sporty bikini that promises both free range of motion and charming allure.<br>It was originally a rash guard swimsuit but has been magically altered as a prank. |
| 530404 | 아키가 좋아하는 로맨스 소설의 주인공이 한 때 입었던 의상.<br>색다른 헤어스타일과 푸른 하오리가 평소의 아키와는 사뭇 다른 차분함을 연출한다. | A costume once worn by the protagonist of the romance novel Aki likes.<br>The different hairstyle and blue haori gives Aki a calm demeanor. |
| 530405 | 소중한 상대에게 드디어 마음을 전하는 중요한 날. 매력적으로 보이고 싶어 고심 끝에 고른 최고의 한 벌.<br>평소랑 다르게 세팅한 헤어에 우아함을 더했다. | The perfect outfit for a day to charm and confess your feelings for someone special.<br>It features a unique hairstyle that also adds elegance to the overall look. |
| 530406 | 안전제일! 평소보다 더욱 활동성을 중시한 의상.<br>엄격. 근엄. 진지. 보기만 해도 선량한 시민이 되고 싶어질 것 같다. | Safety First! A costume that focuses on activity more than usual.<br>Strict, solemn, and serious. Just looking at it kind of makes you want to become a good citizen. |
| 530407 | 한낮의 햇살처럼 화사한 무대의상.<br>무대 위에서 빛나는 미소는 모두의 시선을 빼앗는다. | A stage outfit as bright as the sunshine.<br>When she's on the stage, her smile catches everyone's eyes. |
| 530408 | 흩날리는 벚꽃잎과 뱀이 그려진 붉은 점퍼.<br>셰리의 자유분방함이 물씬 드러난다.<br>가온의 스트리트 패션 중 하나라고 한다. | A red jumper with fluttering cherry petals and a snake.<br>Showcases Cherrie's carefree spirit.<br>A representation of Gaon's street fashion. |
| 530409 | 흰 셔츠에 검은 스커트가 단정한 오피스 레이디의 세미 정장.<br>단정하게 묶은 머리와 사원증, 샛노란 하이힐은 작지만 확실한 개성이다. | A semi-formal suit with a white shirt and black skirt, perfect for a neat office lady look.<br>Neatly tied hair, employee ID, and bright yellow high heels create a subtle yet definite appeal. |
| 530410 | 진지함이라곤 찾아볼 수 없는 날라리들의 옷.<br>가벼운 언행과 발그스름한 뺨에는 버튼 풀린 핫팬츠와 화려한 자수 스카쟌이 어울린다. | Clothes worn by punks who are never serious.<br>The unbuttoned hot pants and colorfully embroidered sukajan go well with their casual demeanor and reddish cheeks. |
| 530411 | 꿀에 의한, 꿀을 위한 꿀과자 베이커리 유니폼. 도라가 특별하게 어레인지한 초콜릿색 곰 귀 헤드드레스는 용기와 희망을 준다. 허리에 매달린 곰돌이는 시식 담당. | The honey dessert bakery uniform. The chocolate-colored bear ear headdress, especially arranged by Dora, represents courage and hope. The teddy bear on the waist samples the desserts. |
| 530412 | 아름다운 밤의 하늘을 고스란히 담은 연회용 서양 의복.<br>어깨를 감싸는 풍성한 모피와 영롱한 금빛이 입은 이의 품격을 드높인다. | A western formal suit for banquets. It reminds you of the beautiful night sky.<br>The rich fur that wraps around the shoulders and the dazzling gold color enhance the dignity of those who wear this suit. |
| 530413 | 교복 블라우스 위에 재킷 대신 넉넉한 카디건을 걸친 의상.<br>편안한 운동화와 단정하게 매인 분홍 리본, 거북이 핀이 깜찍함을 더한다. | A school uniform blouse matched with a voluminous cardigan instead of a jacket.<br>The pair of comfortable sneakers, the neatly tied pink ribbon, and the turtle hairpin add a cute look. |
| 530414 | 산뜻한 원피스에 작은 가죽 가방을 크로스로 맨 의상.<br>깔끔하게 정돈해 핀까지 꽂은 헤어스타일로 이미지 변신에 성공했다. | An outfit with a small leather cross-body bag featuring a dress with a fresh look.<br>With a neatly arranged and pinned hairstyle, the overall style gives the wearer a completely different look. |
| 530415 | 밤을 닮은 우아하고 고풍스러운 무대 의상.<br>달빛의 노래를 따라가 보면 환상적인 신기루가 기다리고 있을 것만 같다. | An elegant vintage-style stage costume that resembles the night.<br>Follow the moonlit song and you might find a mirage waiting for you. |
| 530416 | 달콤하고 사랑스러운 핑크빛 무대 의상.<br>한껏 꾸민 소녀는 솜사탕처럼 부푼 마음을 안고 무대 위로 올라선다. | A lovely and sweet pink stage costume.<br>The girl in her prettiest dress, full of dreams sweet like cotton candy, walks on to the stage. |
| 530417 | 메릴 인연 코스튬 설명 | Meryl's Bond Costume Description |
| 530418 | 플린 인연 코스튬 설명 | Flynn's Bond Costume Description |
| 530419 | 구원자가 타샤에게 선물한 화려한 드레스.<br>장미 장식으로 포인트를 주어 수많은 이들 사이에서도 눈에 띈다. | A splendid dress the Savior gave to Tasha as a gift.<br>Adorned with rose accents, it stands out, even in a crowd. |
| 530420 | 마른 가지 사이를 지나는 데 최적화된 사냥꾼 의복.<br>몇 겹씩 덧입은 옷은 바람을 막아주고, 설산에서 체온이 떨어지는 것을 방지한다. | A hunter's garment optimized for passing through dry branches.<br>Its layered clothes protect the body from the wind and keep it warm even in the snowy mountains. |
| 530421 | 포근하면서도 이상하게 통풍이 잘되는 터틀넥.<br>몸에 열이 많은 루테가 잠옷으로 입기 위해 직접 리폼했다고 한다. | A cozy yet breathable polo neck.<br>Lute, who has high body temperature, altered it herself to wear it as a pajama. |
| 530422 | 풍년을 기리며 클라라가 직접 만든 의상.<br>무시무시한 흉작이라도 이겨낼 수 있을 듯한 성스러움이 깃들어 있다. | An outfit personally made by Clara hoping for a bountiful harvest.<br>It bears a divine aura strong enough to withstand the fiercest famine. |
| 530423 | 용기를 내서 한 걸음! 친구들을 위해 에리카가 준비한 구급상자와 간호 복장.<br>어디가 아프냐고 덜덜 떨리는 목소리로 물어오지만, 물약 효과는 완벽하다. 씩씩하게 꿀꺽 삼키고, 한숨 자고 일어나서 다 같이 놀자. | Be brave and take a step forward! Erika has prepared a nurse uniform and a first-aid kit for her friends.<br>Her voice trembles as she asks them where it hurts, but there's no need to worry as the potion is effective. Take the potion, and let's have fun together after a good rest. |
| 530424 | 이나 인연 코스튬 설명 | Ina's Bond Costume Description |
| 530425 | 칼라르 공화국의 상류 계급인 르네가 공식 석상에 등장할 때 입는 예복. <br>새하얀 눈을 연상시키는 흰색이 어딘가 다가가기 어려운 고귀함을 풍긴다. | Ceremonial attire that Renee wears to state functions as a member of the upper echelons of the Republic of Chalar.<br>Its snow-white color exudes an aura of unapproachable nobility. |
| 530426 | 솜사탕처럼 엷은 색감의 베이비돌 원피스.<br>별님을 닮은 머리핀과, 통통한 뺨의 토끼 인형은 좋은 꿈을 약속한다. | A baby doll dress with a light color scheme like cotton candy.<br>The star-shaped hairpin and bunny doll with plump cheeks promise good dreams. |
| 530427 | 시원한 바닷바람이 떠오르는 해군풍 제복.<br>어떤 바다에서도 당당하고 귀여운 공주가 되고픈 칸나의 마음이 담겼다. | A navy-style uniform evoking the fresh ocean breeze.<br>It reflects Kanna's wish to be a bold and adorable princess wherever the waves may take her. |
| 530428 | 이디스의 어머니가 고심 끝에 고른 잠옷. 고급스러운 실크 재질이 몸을 부드럽게 감싸 숙면을 유도한다. <br>디자인이 조금 외설스럽지 않냐는 누군가의 의견도 있었지만, 잠옷은 가벼울수록 좋다는 어머니의 말에 아무런 반박도 하지 못했다고. | Pajamas selected by Edith's mother after much deliberation. The luxurious silk softly envelops the body, ensuring a comfortable sleep.<br>While some thought the design was a bit indecent, no one could argue against her mother's opinion that lighter pajamas are best. |
| 530429 | 니콜이 조금 더 편하게 입는 일상복.<br>타이트한 바지와 대비되는 루즈한 셔츠가 매력적이다. | Nicole's casual wear for daily comfort.<br>The form-fitting pants and the relaxed, flowing shirt cast an alluring contrast. |
| 530430 | 비비안이 솔레이 왕국의 궁정 마도사였던 시절 입었던 의상. <br>지금의 비비안과 비슷하면서도, 사뭇 다른 냉철한 분위기가 느껴진다. | An outfit Vivienne used to wear back when she was a court mage in Solrey.<br>While similar to her current style, it exudes a markedly different aura with a cooler, more calculated demeanor. |
| 530431 | 어두운 거리에 잘 어울리는 테크웨어 의상.<br>그녀의 도시에선, 항상 뒷골목의 탄창 소리를 주의해야 한다. | A techwear costume that fits the dark streets.<br>In her city, you always need to pay attention to the sound of magazines coming from the back alleys. |
| 530432 | 발랄한 건강미가 느껴지는 응원단장 의상. <br>아무리 어려운 상황에도 기죽지 않고 힘찬 목소리로 경기장을 제압한다. <br>쉽게 포기하지 마. 늘 너를 응원해! | A lively cheerleader costume. <br>No matter how tough the situation is, this outfit will empower her to shout out powerfully across the stadium.<br>Don't give up so easily. I'm always cheering for you! |
| 530433 | 파릇파릇한 새싹의 기운이 느껴지는 의복.<br>상쾌한 복장만큼 발걸음도 가벼워, 숲의 요정으로 다시 태어난 것만 같다. | A costume that gives off the same energy as green sprouts.<br>Her footsteps will feel so light in this fresh costume, almost as if she were reborn as a fairy in a forest. |
| 530434 | 신비로운 보랏빛의 웨이트리스 의상.<br>정석 대신 앞이 과감하게 트인 스커트를 작은 에이프런으로 감쌌다. | A mysterious purple waitress outfit.<br>It features a boldly vented skirt wrapped with a small apron. |
| 530435 | 동화 속 주인공처럼 파란 드레스에 흰 에이프런을 두른 의상.<br>토끼를 쫓던 소녀는 이상한 나라에서 이상한 고양이를 만났다고 한다. | A blue dress with a white apron, like what a princess would wear in a fairy tale.<br>They say a girl followed a rabbit into Wonderland, where she met a strange cat. |
| 530436 | 레베카가 타브리아 황제의 암부였던 시절의 옷.<br>우아하고 고고한 소녀의 모습이지만, 누군가에게는 진짜 악마보다 두려운 존재였다. | The uniform Rebecca wore when she was part of the Tabria Empress's assassin squad.<br>While she looked like a delicate little girl of nobility, to some, she was more terrifying than the devil himself. |
| 530437 | 격식 있는 명문 사관 학교의 교복. <br>움직이기 편한 소매와 신발에서 멜피스의 활발함이 느껴진다. | An elite military academy uniform.<br>The comfortable sleeves and shoes show Melfice's active personality. |
| 530438 | 격식 있는 사관 학교의 교복.<br>구두와 리본에서 브라이스의 메르헨한 취향이 엿보인다. | A military academy uniform.<br>The shoes and ribbons show Bryce's preference for fantasy dress-up fashion. |
| 530439 | 작은 트럼펫을 찬 퍼레이드 악단 의상.<br>테마파크의 꽃은 밤의 퍼레이드. 키 큰 모자와 재킷이 있다면 쇼는 어디에서든 계속된다. | A parade band costume with a small trumpet.<br>What would a theme park be without a night parade? With a tall hat and a jacket, the parade show never ends. |
| 530440 | 전신 스텔스 재의 특수 외형.<br>그림자보다 은밀하고, 전갈보다 조용하며, 비수보다 치명적이다. | A special outfit made of full-body stealth materials.<br>It makes you stealthier than a shadow, quieter than a scorpion, and deadlier than a dagger. |
| 530441 | 가을의 정취가 묻어나는 세련된 의상.<br>선연한 단풍 아래 늦게 핀 가을 장미가 홀로 서 있다. | A refined outfit for the autumn mood.<br>A late-blooming autumn rose stands alone under the autumn leaves. |
| 530442 | 티아라와 섬세한 레이스 장식이 돋보이는 파티용 드레스.<br>그 무도회장에서 무희는 어떤 꿈을 꾸었을까? | A party dress adorned with intricate lace trim, complete with a tiara.<br>In that ballroom, what dreams twirled through the dancer's mind? |
| 530443 | 칠흑 같은 어둠 속에서 피어난 아름다운 신부 드레스.<br>영혼마저 묶어버리는 사랑의 언약은, 조금은 오싹하고 더없이 사랑스럽다. | A beautiful bridal gown bloomed in pitch-black darkness.<br>The soul-binding vow of love is overwhelmingly lovely if a bit creepy. |
| 530444 | 헐렁한 셔츠 위로 커다란 점퍼를 걸친 보이프렌드 룩.<br>누군가에게는 단정치 못하게, 또 누군가에게는 더없이 사랑스럽게 보인다. | An oversized jumper with a baggy shirt underneath, together called the "boyfriend look."<br>It may look untidy to some but irresistibly lovely to others. |
| 530445 | 클라우디아가 격식을 갖추는 자리에서 입는, 별하늘의 가호가 함께하는 특별한 정장.<br>정령 연합군의 간부인 그녀의 품격에 걸맞은 아주 귀한 재료로 제작되어 있다. | Claudia's special formal clothes blessed by the stars.<br>It was created with extremely rare material, giving it a dignified look perfect for someone like Claudia. |
| 530446 | 아드리안이 동경하는 슈퍼 히어로의 옷을 본따 만든 의상.<br>그녀의 불타오르는 정의감을 표현하고 싶었던 것일까, 유난히 정열적으로 붉게 빛나는 옷은 세상의 이목을 끌기 충분하다. | A costume made in the image of the super hero Adrianne looks up to.<br>The fire red of the costume, representing Adrianne's desire for justice, is more than enough to draw attention. |
| 530447 | 사논 인연 코스튬 설명 | Sanon's Bond Costume Description |
| 530448 | 헬레나 인연 코스튬 설명 | Helena's Bond Costume Description |
| 530449 | 하얀 나비가 눈가에 내려앉은 순백의 드레스 의상.<br>순수하고 투명한 하양과 칠흑 같은 검은 날개가 공존한다. | A pure white dress accented with a white butterfly.<br>The pure white and pitch dark wings mix together harmoniously. |
| 530450 | 먼 옛날 아야메가 지냈던 마을의 전통 혼례복.<br>다소곳이 올린 머리와 새하얀 순백의 천 위에 수놓인 흰색 피안화가 인상적이다.<br>흰색 피안화에는 사랑하는 이와 다시 만나 행복할 날을 기다리는 아야메의 소망이 담겨있다. | Traditional bridal wear of the village Ayame lived in a long time ago.<br>The unique hairstyle and the white Nirvana flowers embroidered on the white cloth is intriguing.<br>The flowers represent Ayame's hopes of meeting her loved one again someday. |
| 530451 | 순백의 드레스를 입은 캐서린.<br>베일이 마치 눈꽃처럼 반짝이고 있다. | Catherine wearing a white dress.<br>The veil sparkles like snowflakes. |
| 530452 | 최고의 곰돌이로 변신한 도라.<br>캐서린이 머리를 땋아주고, 로제가 후드 리본을 묶어주었으며, 클로이가 골라온 멋진 니트를 입고, 린지가 옷매무새를 만져주자 마침내 에덴에서 가장 귀여운 최고의 백곰이 되었다! | Dora transformed into the Best Teddy.<br>Catherine braided her hair, Rose tied the ribbon for her hood, Chloe picked the cool sweater, and Linzy gave the final touches to create the cutest white bear of Eden! |
| 530453 | 이상한 꿈결에 휘말려든 클로이의 원님 의상.<br>원래의 꿈에선 어진 마을 원님의 복식이었는데, 꿈이 뒤틀리는 바람에 탐관오리의 상징이 들어가 있다. 클로이의 꿈결 복식이 이렇게 바뀐 이유는 오직 꿈을 뒤튼 자만이 아는 일이다. | Chloe's magistrate costume in the strange dream.<br>It was the clothes of a wise magistrate in the original dream, but the dream was twisted and changed the markings into that of a corrupt official. Only the one who twisted the dream knows what happened to these clothes. |
| 530454 | 이상한 꿈결에 휘말려든 나이아의 구미호 의상.<br>원래의 꿈에선 어진 마을 원님과 애틋한 사랑을 나눴던 구미호의 복식이었는데, 꿈이 뒤틀리는 바람에 나이아가 구미호의 옷을 입게 되었다. 나이아의 꿈결 복식이 이렇게 바뀐 이유는 오직 꿈을 뒤튼 자만이 아는 일이다. | Naiah's nine-tailed fox costume in the strange dream.<br>It was the clothes of a nine-tailed fox that loved the village magistrate, but the dream was twisted and changed it to being worn by Naiah. Only the one who twisted the dream knows what happened to these clothes. |
| 530455 | 톡톡 튀는 컬러감의 활동성 높은 복장.<br>실수로 뒷골목에 잘못 들어와 잔뜩 겁먹은 당신을 쾌활한 미소와 함께 다정하게 구해줄 것이다.<br>큰 길로 나가기 전에, 고양이와 인사하자. | A colorful outfit for highly active lives.<br>If you stray into a dark alley by mistake, she will kindly save you with a bright smile.<br>Don't forget to greet the cat before you go leave the alley. |
| 530456 | 오늘만큼은 순정 쇼콜라티에. 초콜릿에 담긴 순수한 애정을 지키기 위해 보이지 않는 곳에서 고군분투하고 있다. | Today is the day to become a pure heart chocolatier. Struggle behind the scenes to protect the pure love that chocolate hides. |
| 530457 | 핑크색 프릴을 입은 기계 메이드.<br>아주 달콤하고 살짝 살벌한 맛의 절묘한 밸런스가 완벽하게 어우러진다. | A machine maid on a pink-frilled dress.<br>A mixture of over-the-top sweetness and a pinch of savageness results in a perfect balance. |
| 530458 | 꽃내음이 느껴지는 숲지기 복장.<br>어차피 흔한 들꽃일 뿐이라며 툴툴대지만, 발갛게 물든 볼은 감출 수 없다. | A Forest Keeper's outfit with flowery scent.<br>She says these wildflowers are nothing special, but her flushed cheeks tell otherwise. |
| 530459 | 숲속 피크닉 드레스. <br>중요한 건 마음가짐! 설령 돌부리에 걸려 넘어진다고 하더라도, 햇살 아래 반짝반짝 빛나는 마음은 꺾이지 않는다. | A forest picnic dress.<br>It is your mind that counts! Even if you stumble over a stone, it won't break your shiny mind. |
| 530460 | 활동성이 느껴지는 교복 의상.<br>셔츠 안쪽에 받쳐입은 스포츠탑에서 체육계의 매력을 볼 수 있다. | A uniform made for activity.<br>The top inside the shirt completes the sporty look. |
| 530461 | 몸에 딱 맞는 핏의 엄격한 교복 의상.<br>바른생활부장은 펜싱부와 사격부 활동도 겸하고 있다는 무서운 소문이 있다… | A form-fitting school uniform.<br>There's a chilling rumor that the Ethics Director is into both fencing and going to shooting ranges... |
| 530462 | 박시한 소매가 귀엽게 손등을 덮고 있는 교복 의상.<br>무던하고 성실한 학생이지만, 매점의 케이크 매출에 지대한 공헌을 하고 있다고 한다. | A school uniform with adorable boxy sleeves.<br>Its wearer is easygoing and diligent, and also contributes greatly to the cafeteria's cake sales. |
| 530463 | 마농이 즐겨보는 애니메이션 '쥬얼포스 매지컬 프린세스'의 주인공 '골드테일'이 입는 마법소녀 옷이다. | A magical girl outfit that "Gold Tail," the protagonist of Manon's favorite animation "Jewel Force Magical Princess," wears. |
| 530464 | 리본과 프릴장식이 사랑스러운 벨벳 화이트 웨딩드레스.<br>동경하던 미소를 머금은 신부의 손에서 행복을 엮은 부케가 멀리 날고 있다. | A lovely white velvet wedding dress decorated with ribbons and frills.<br>The bride tosses her bouquet of happiness with a smile. |
| 530465 | 섹시하면서 세련된 순백의 미니 웨딩드레스.<br>익명의 누군가 말하기를, 「신부란 말야, 장미와 샤르도네, 그리고 알코올로 완성되는 거야…」 라고 한다.<br><br>…너무 진지하게 생각하지 않는 게 낫다. | A sensual yet sophisticated white mini wedding dress.<br>"A bride becomes complete with roses, Chardonnay, and alcohol..." said an anonymous.<br><br>...You should not take these words seriously. |
| 530466 | 마나 오염으로 인해 심각한 에러가 발생한 결과, 대부분의 리소스를 파괴에 할애하게 된 재클린의 모습.<br>수많은 파괴의 흔적이 나타나기 전에는 반드시 검은 그림자를 두른 기계 인형이 목격되었다고 한다. | Jacqueline dedicated most of her resources to destruction due to a serious error from polluted Mana.<br>They say a machine doll casted by shadows would always be seen before numerous traces of destruction would appear. |
| 530467 | 마나 오염으로 인해 심각한 에러가 발생한 결과, 모든 리소스를 파괴에만 할애하게 된 재클린의 모습.<br>세계의 모든 감정을 배제하고자 한 기계 인형은 파괴를 거듭해, 이윽고 종말을 불렀다. | Jacqueline dedicated all of her resources to destruction due to a serious error from polluted Mana.<br>The machine doll continuously brought down destruction to get rid of all emotions of the world, eventually bringing forth the end of it all. |
| 530468 | 신속 배달, 외상 사절! 불러만 준다면 어디든 달려가는 오늘의 라이더 복장.<br>음식도 사랑도 갓 만든 그대로 따끈따끈 식지 않게 배달해드립니다. | "Fast delivery and no credit!" The outfit of Today's Rider. Call her and she will be there wherever you are.<br>The one and only rider who delivers both food and love on time. |
| 530469 | 멋쟁이 해결사가 추천해준 청순가련한 데이트복. <br>좋아하는 상대의 마음을 붙잡기 위해 준비한, 가녀린 덫이다. | A girly dress for dating recommended by the most stylish troubleshooter.<br>A delicate trap for capturing the heart of her lover. |
| 530470 | 세계의 종말을 막기 위한 다양한 방책이 전부 실패해, 결국 세상에 멸망을 초래해버리고 만 비비안의 모습.<br>초월적인 지혜를 지닌 마녀가 품었던 순간의 오만함은 돌이킬 수 없는 죄가 되고 말았다. | All plans to prevent the End failed, and Vivienne finally destroyed the world.<br>The arrogance that the Witch with transcendental wisdom bore for a moment became an irrevocable sin. |
| 530471 | 세상을 멸망시켜버리고 만 비비안이 오랜 세월 동안 차원을 떠돈 모습.<br>돌이킬 수 없는 죄를 품은 마녀는 그저 자신을 단죄해, 구원할 존재를 계속 찾아 헤맬 뿐이었다. | Vivienne destroyed the world and roamed the dimensions for a long time.<br>The Witch who committed an irrevocable sin kept searching for someone who would condemn her and save her. |
| 530472 | 비비안이 큰맘 먹고 마련한 바캉스용 비키니.<br>평소와는 다른 산뜻한 노란색으로 이미지 대변신! 오늘만큼은 심술도 비밀주의도 없단다? | Vivienne really went all out in this bikini for her summer vacation.<br>The splash of yellow really gives her a completely different look! There's no way she'll be cranky in this outfit! |
| 530473 | 페트라에게 잘 어울리는 하얀색 프릴 투피스 수영복 세트. <br>페트라가 이 귀여운 모래 놀이 세트로 만든 모래성은 엄청난 걸작이었다고 하는데… | This frilled two-piece swimsuit set looks perfect on Petra.<br>They say Petra created a sand castle masterpiece using the cute little tools that come with it. |
| 530474 | 아야메라면 절대 고르지 않을 파격적인 노출도의 검은색 비키니.<br>본인의 의사와는 무관하게, 충격적일 정도로 잘 어울린다. 그야말로 마성! | A shockingly revealing black bikini that one would never imagine Ayame would choose to wear.<br>It looks devilishly good on her. |
| 530475 | 눈물을 계속 흘려 피눈물이 흐를 때까지 님을 그리던 아야메가 입었던 의상.<br>사랑하는 님을 맞이하고자 어여삐 단장한 신부 의상은 영겁의 시간 끝에 검게 물들었다. | The outfit Ayame wore as she yearned for her lover, weeping bitter tears.<br>The outfit of the bride who had dressed up to meet her lover was tinted black after an eternal wait. |
| 530476 | 끝내 오지 않은 구원으로 인해 절망해, 원귀가 되어버려 폭주하게 된 아야메의 의상.<br>그녀가 사랑하는 님을 맞이하고자 준비했던 고운 신부복은, 절망으로 인해 칠흑으로 물들었다. | An outfit of Ayame who has become a vengeful ghost and gone out of control as she could not be saved.<br>The beautiful bridal outfit she wore to meet her lover was tinted black by her despair. |
| 530477 | 아드리안에게 어울리는 스포티한 디자인의 비키니.<br>반짝이는 파도를 시원하게 가르며 바다를 유영하는 그 모습은 그야말로 바다의 천사! | A sporty bikini set for Adrianne.<br>Look at her swim in the sea through the dazzling waves like an angel of the sea! |
| 530478 | 캐서린에게 어울리는 청순한 디자인의 프릴 비키니. <br>시원한 파란색과 눈부신 하얀색의 조화가 깔끔한 인상을 준다. | A feminine frilled bikini set for Catherine.<br>The combination of blue and white makes it look neat. |
| 530479 | 홍란이 직접 고른 파격적인 디자인의 수영복. <br>가슴께에 있는 푸른 꽃무늬와 링 버클 장식이 시선을 끈다. <br>여러모로 아슬아슬한 게, 홍란답긴 할지도? | A bikini set of a rather unconventional design chosen by Honglan.<br>The blue flower pattern and the ring decoration in the bikini top catch one's attention.<br>One could say that this bikini resembles its wearer. |
| 530480 | 순이가 어쩌다가 입게 된 귀여운 원피스형 수영복. <br>비비안 왈, "그래도 나름 실용적인 디자인"이라고 한다. <br>막상 입어보니 편해서, 가끔 순이가 바다 순찰 때 입는다고 하는데… | A cute swim dress Soonie wore by accident.<br>According to Vivienne, "it has a practical design."<br>Soonie found it comfortable and now wears it from time to time when patrolling the beach. |
| 530481 | 초인류에게 봉인당해, 세상을 향해 저주를 내뱉으며 포효하던 아이라의 모습. <br>그녀가 지닌 생과 사의 힘은 유폐된 그녀에게 죽음의 안식조차 허락치 않았다. | Aira roars in madness, cursing towards the world as she is sealed by the Dominas.<br>She remains confined, and her powers of life and death keep her away from the sweet release of death. |
| 530482 | 이성을 잃고 광기에 물들어, 마침내 모든 것을 파괴해버린 아이라의 모습. <br>구원자 살해라는 죄를 저질러 광기에 잠식된 사자는 기어코 세상의 모든 생명을 말살해버리고 말았다. | Aira's madness completely overtakes her, making her destroy everything in her sight.<br>She murdered the Savior, and became engulfed in complete madness, laying waste to all life in the world. |
| 530483 | 소중한 자를 잃고 비애에 잠긴 성녀의 의상.<br>모든 걸 되찾기 위해, 그녀는 타락을 택했다. | The outfit of a sorrowful saint who lost her beloved one.<br>She chose the path of corruption to get everything she had lost back. |
| 530484 | 자신의 소중한 존재를 되찾기 위해 자신의 욕망을 해방한 성녀의 의상. <br>그녀는 모든 것을 되찾을 것이다. 그 어떤 것을 희생해서라도. | The outfit of a saint who freed her desires to get her beloved one back.<br>She will get everything she lost back, no matter what it takes. |
| 530485 | 벚꽃이 흐드러지게 수놓인 아름다운 검객 의상.<br>영원히 지지 않는 벚꽃은 방랑 무사의 강인함을 나타낸다. | A beautiful swordsman outfit embroidered with cherry blossoms in full bloom.<br>The never-fading cherry blossoms represent the strength of a wandering warrior. |
| 530486 | 반투명한 노방 저고리와 담홍색 치마가 고풍스러운 의상.<br>순수한 미소 아래 비치는 고귀한 성품은 숨길 수 없다. | An antique looking outfit with a translucent top with a rose pink skirt.<br>It exudes a noble presence. |
| 530487 | 말간 분홍빛이 사랑스러운 의상.<br>작은 모자와 꽃댕기로 쫑긋 튀어나온 귀를 가릴 수 있다.<br>물론, 가리지 않은 게 훨씬 귀엽다. | A lovely pink outfit.<br>The small hat can cover her ears.<br>But of course, showing the ears would be more adorable. |
| 530488 | 유리아가 이미지 변신을 위해 준비한 검은색 데이트 복장.<br>구원자가 살던 시대의 젊은 여성들이 입던 섹시한 패션을 참고 했다고 한다. | A black date outfit Yuria prepared to try out a new look.<br>She says she referred to sexy outfits young women wore in the Savior's world. |
| 530489 | 늑대를 노리는 밤의 사냥꾼 의상.<br>사냥감을 노리는 자색 눈동자가 칠흑 같은 어둠 속에서도 날카로이 빛나고 있다. | An outfit that belongs to a hunter on the hunt for a wolf.<br>The violet eyes shine through the darkness. The eyes look fiercely for prey. |
| 530490 | 야성미가 느껴지는 늑대인간 의상.<br>복수심으로 벼린 첨예한 눈빛과 고고한 용모가 마치 철창에 피어난 장미를 연상시킨다. | A werewolf outfit with a wild look.<br>The eyes filled with a thirst for revenge somehow remind you of a rose that blossomed inside a steel cage. |
| 530491 | 귀여운 빨간 모자와 리본이 돋보이는 의상.<br>소심한 아이도 장난스러운 아이도, 오늘만큼은 마음껏 즐길 수 있기를! | A red riding hood outfit with a cute little ribbon.<br>Timid kids and mischievous kids will all enjoy this outfit! |
| 530492 | 뜨거운 여름 더위를 펑!펑!! 날려줄 플린의 송하제 패션. 플린이 취향대로 사 모은 캔뱃지와 키링이 포인트다. | Flynn's Songha Festival outfit that will blow away the heat of summer! The badges and keyring bring out Flynn's taste in fashion. |
| 530493 | 부름에 답해 전쟁의 사도로 각성한 아드리안의 모습.<br>순백으로 빛나던 날개는 검게 물들고, 수호의 빛이 감싸던 창은 피로 붉게 물들었다. | Adrianne awakened as the Apostle of War upon answering her call.<br>Her pure-white wings have turned black and her shiny spear has been smeared with blood. |
| 530494 | 수없이 많은 전투 끝에 전쟁의 사도에서 전쟁의 화신으로 거듭난 아드리안의 모습. <br>이 모습을 한 그녀를 보았다면, 단념하라. 전쟁은 이미 시작되었다. | The Apostle of War Adrianne awakened as the Incarnation of War upon countless wars.<br>Surrender if you ever see her. The war has already begun. |
| 530495 | 평범한 비서 복장을 개량한 에일린의 특수복. 무기를 수납하기 좋은 벨트로 이뤄져 있다. | An ordinary secretary outfit remodeled as Eileen's special outfit. There's also a bet that's perfect for holding weapons. |
| 530496 | 달콤한 컬러와 아찔한 디자인의 조합이 인상적인, 오토하가 직접 만든 사복.<br>놀랍게도 이 의상은 여러 의미로 '전투복'이라고 한다. | An outfit Otoha made herself. The dark colors and the addition of punk bunnies really stand out.<br>Surprisingly, it's used as a "combat outfit." |
| 530497 | 포근한 겨울을 닮은 순백의 드레스. 베일이 마치 눈꽃처럼 반짝이고 있다.<br>소중한 이들이 영원히 행복하기를 바라는 수녀님의 기도는 오늘도 계속되고 있다. | A pure white dress reminiscent of a cozy winter. The veil glitters like snowflakes.<br>The nun's prayers for her loved ones' everlasting happiness continue even today. |
| 530498 | 귀여운 백곰으로 변신한 도라의 겨울 의상.<br>캐서린이 머리를 땋아주고, 가넷이 후드 리본을 묶어주었으며, <br>다 함께 고른 멋진 니트를 입자 마침내 에덴 최고의 곰돌이가 되었다! | Dora's winter outfit for her adorable white bear form.<br>Donning the stylish knit they picked out together with the hair braided by Catherine<br>and the hood strings tied into a neat bow by Garnet, she turned into Eden's famous teddy bear! |
| 530499 | 착한 아이에게 선물을 전해주는 성자의 의상. 귀여운 캐럿도 순록 옷을 맞춰 입었다.<br>굴뚝을 통해 리본을 잔뜩 두른 누군가가 무단침입할지도 모르니, 오늘 밤은 경비에 주의하도록 하자… | The garb of a saint who brings presents to good children. Adorable Carrot is in matching reindeer attire, too.<br>Tonight calls for extra security since a bow-clad intruder might come down the chimney uninvited... |
| 530500 | 하늘색 리본이 사랑스러운 아이돌 의상.<br>무대 아래에서는 쿨하고 침착한 소녀이지만, 무대 위에서는 전력을 다하는 점이 그야말로 완벽한 아이돌! | An idol outfit adorned with a charming light blue bow.<br>Off the stage, she's cool and composed, but on the stage, she gives her all, embodying the perfect idol! |
| 530501 | 마음은 언제나 하트풀! 소녀의 순정이 가득 담긴 아이돌 의상. <br>객석을 메운 모두에게 설레는 고동이 전해지길 바라는 마음이 담겨있다. | Always full of heart! This idol outfit embodies a young girl's earnest affection.<br>It holds her aspiration to send a pulse of excitement to everyone in the audience. |
| 530502 | 오후의 햇빛을 닮아 따뜻하게 반짝이는 아이돌 의상.<br>느긋하고 나른해 보이는 모습이 어쩐지 유혹적. 여유로운 노랫소리는 모든 관객의 마음을 사로잡는다. | An idol costume gleaming with the warmth of the afternoon sunlight.<br>Its relaxed and leisurely style has an inexplicably seductive charm. The mellow tune captures the hearts of the entire audience. |
| 530503 | 달콤한 컬러와 아찔한 디자인의 조합이 인상적인, 오토하가 직접 만든 사복.<br>마스크를 벗고 무장해제한, 청순한 모습은 특별한 누군가에게만 보이고 싶다. | An outfit Otoha made herself. The dark colors and the addition of punk bunnies really stand out.<br>Her innocent appearance, unmasked and unarmed, is meant for the eyes of a special someone only. |
| 530504 | 모든 것이 장밋빛 같았던, 찬란한 시절의 이브.<br>아름답게 단장한 그녀를 본 순간, 인류는 사랑에 빠진 듯한 황홀감을 느꼈다. | Eve from a glorious time when everything seemed rosy.<br>The moment humanity laid eyes on her beautifully adorned figure, they felt a bliss as if they had fallen in love. |
| 530505 | 모레노 사막에서 발견되는 흑요석처럼 아름다운 검은 천이 인상적인 파티 드레스. <br>그 어떤 말썽꾸러기라도 이 드레스를 입는 순간, 매력적인 레이디로 변신한다. | A party dress with eye-catching black fabric as beautiful as the obsidian found in the Morreno Desert.<br>Even the most rambunctious tomboy transforms into a charming lady upon donning this garb. |
| 530506 | 라피아 정글 깊숙한 곳에서 발견되는 최상급 다이아의 이름을 딴 럭셔리한 파티 드레스. <br>깐깐한 디자이너가 만든 이 드레스를 입을 자격을 지닌 자는 에덴 전체를 봐도 손에 꼽을 정도라고 한다. | The epitome of luxury, this party dress bears the name of the exquisite diamond discovered in the depths of Raffia Jungle.<br>Only a select few out of the entire realm of Eden are deemed worthy to wear this masterpiece crafted by a discerning designer. |
| 530507 | 다이난 호수의 아름다운 푸른 색을 모티프로 삼은 세련된 디자인의 드레스. <br>깜찍함도, 섹시함도, 우아함도 전부 다 놓칠 수 없는 욕심쟁이를 위한 베스트 셀렉션. | An exquisite dress, meticulously crafted with a design inspired by the mesmerizing blue shades of Lake Dynan.<br>It's the top choice for those with insatiable desires for charm, allure, and elegance all at once. |
| 530508 | 청룡을 상징하는 푸른 의상. 모두의 일상에 맑게 개인 푸른 하늘 같은 행운이 찾아오기를. | An azure outfit symbolizing the Blue Dragon. May it usher in luck as bright and clear as the blue sky for all. |
| 530509 | 금속 장식으로 포인트를 준 섹시한 메이드복.<br>입어본 적 없는 구조의 의상이라 착용에 매우 애를 먹었다는 소문이 있다. | A sexy maid uniform accented with metal notions.<br>Apparently, putting it on was quite a challenge because of the novel design. |
| 530510 | 귀여운 프릴이 잔뜩 달린 메이드복.<br>한입 베어 물자마자 녹아버릴 듯한 달콤한 마술을 선사한다. | A maid uniform adorned with an abundance of cute frills.<br>It promises a sweet magic spell that feels like it will melt in your mouth the moment you take a bite. |
| 530511 | 가죽 스트랩으로 장식한 퓨전 메이드복.<br>달콤한 다크초콜릿 컬러와 선명한 레드 벨벳 컬러의 조합이 시선을 사로잡는다. | A fusion-style maid uniform featuring leather straps.<br>The combination of deep dark chocolate and bold red velvet hues captivates the eye. |
| 530512 | 첨단 기술로 제작된 정령 연합군의 의료 장교용 제복.<br>강한 권한에는 강한 책임이 따른다. | Medical officer uniform of the Soul Alliance, crafted with cutting-edge technology.<br>With great power also comes great responsibility. |
| 530513 | 구원자 시해의 죄를 저질러 검귀가 된 아키의 모습. <br>종말조차 그녀를 구원해주지 않았다. 멸망한 세계의 붉은 달빛만이 그녀와 함께하리라. | Aki, turned into a Sword Demon by the grave sin of slaying the Savior.<br>Even the apocalypse could not save her. Only the gaze of the red moon of a doomed world is left by her side. |
| 530514 | 붉은 달빛 아래에서, 오로지 사랑을 갈구했던 한 소녀의 모습. <br>사랑하는 이의 손에 의해 스러지고 싶다는 단 하나의 소원을 이루고자, 그녀는 무한한 시공을 초월했다. | The figure of a girl who yearned only for love under the glow of the red moon.<br>Driven by a wish to meet her end at her beloved's hand, she crossed endless dimensions of time and space. |
| 530515 | 벨레드가 방주의 창고에서 발견한 세일러복.<br>출처 미상의 옷이지만, 옷의 주인에게 잘 어울린다. | A sailor uniform found by Beleth in the ark's storeroom.<br>While its origin is a mystery, it suits the owner perfectly. |
| 530516 | 한 치의 흐트러짐도 없이 정갈한 교복.<br>학생회장의 교복으로 2천년, 아니 4천년의 세월을 보내는 동안 신비로운 힘이 깃들었을지도…? | Flawless and immaculate uniform.<br>Maybe it possesses some mysterious powers now after having served the Student President for two thousand—no, four thousand years... |
| 530517 | 에덴스쿨의 시크릿 바주카, 다프네의 교복.<br>무지막지한 피지컬을 감당하는 단추들의 아우성이 여기까지 들리는 것 같다… | Uniform of Daphne, Edenschool's secret bazooka.<br>One can almost hear the buttons' anguish, straining under her formidable physique... |
| 530518 | 에덴스쿨 중등부의 깜찍한 교복.<br>특수 잠금 장치가 달린 가방 안에는 마농의 용돈 운용 계획서가 들어 있다고 한다. | Adorable uniform of Edenschool Junior High.<br>Rumor has it that the bag has a special lock and contains Manon's allowance management plan. |
| 530519 | 캐서린이 예배 시 입는 고위 성직자의 예복.<br>비록 세상이 내일 멸망할지언정, 그녀의 정의는 흔들리지 않을 것이다. | High priestess attire Catherine wears during worship.<br>Even if the world were to end tomorrow, her unwavering commitment to justice would not waver. |
| 530520 | 검은 매 기사단장의 새로운 모습을 엿볼 수 있는 축제 유카타.<br>나팔꽃 무늬와 하늘하늘한 옷의 재질이 자연스러운 청순함을 돋보이게 한다. | A festival yukata showcasing the Commander of the Order of Blackhawk's new look.<br>The morning glory pattern and breezy fabric bring out a natural, innocent charm. |
| 530521 | 꽃과 금붕어 무늬로 하나의 정원을 옮겨 놓은 듯한 화려한 축제 유카타.<br>축제 여기저기를 누비기 위해 짧은 기장으로 활동성을 더했다. | A stunning festival yukata, decorated with floral and goldfish patterns, creating the illusion of a garden.<br>The short length ensures easy movement for festival activities. |
| 530522 | 헤이즐의 전투복. 몸을 보호하기 위해 덧댄 금속 장식들이 고급스러운 느낌을 준다.<br>타브리아 제국에서는 중요한 행사 때 전투복을 입고 참석하는 문화가 있다고 한다. | Hazel's battlesuit. The protective metal embellishments lend an air of luxury.<br>In the Tabria Empire, it is customary to wear battlesuits to significant events. |
| 530523 | 도미니크가 설립한 트로이카 공립 학교의 교복.<br>에메랄드를 닮은 녹색이 차분하면서도 싱그러운 느낌을 준다. | Uniform of the Troyca Public School founded by Dominique.<br>The emerald green hue gives off a calm yet refreshing vibe. |
| 530524 | 까마득히 먼 추억 속, 라리마의 태초의 모습.<br>과거의 그녀는 삶과 죽음 사이에 놓인 모든 영혼을 사랑으로 이끌었다. | What Larimar used to look like in the distant past.<br>Back then, she guided every soul at the threshold of life and death with love. |
| 530525 | 시그리드가 공적으로 브리기트 대제를 보필할 때 착용하는 예복.<br>화려하고 아름다운 꽃은 위험한 독을 품고 있는 법이다. | Sigrid's formal attire donned when she officially assists Empress Brigid.<br>Vibrant, beautiful flowers often harbor deadly toxins. |
| 530526 | 오닉스가 정체를 숨기기 위해 변장 용도로 입는 복장.<br>신원을 속인 채, 프로덕션 인재를 발굴하기 위해 입은 옷이지만…<br>오히려 과하게 화려한 탓에 오닉스의 정체가 들통난 적도 있다고 한다. | An outfit Onyx wears to mask her identity.<br>Intended for scouting production talent incognito,<br>but its excessive flamboyance has occasionally blown her cover. |
| 530527 | 린지가 새로운 전투 스타일에 맞춰서 새로 조달한 일상복.<br>하지만 거의 새로운 기사단 제복처럼 사용되고 있는 모양이다. | Linzy's new everyday attire, adapted for her new combat style.<br>Apparently, it has almost become the Order's new uniform. |
| 530528 | 고귀한 서약을 위한 비올레트의 웨딩드레스.<br>눈부신 모습을 마주한 순간,<br>어떠한 맹세도 속삭일 수 있을 것 같다. | Violette's wedding dress for a noble oath.<br>The glorious sight would make one<br>commit to any kind of oath. |
| 530529 | 단 한 사람만을 위한 가넷의 웨딩드레스.<br>보는 이로 하여금 아찔한 저주에 걸리듯,<br>영원한 사랑을 약속하고 싶어진다. | Garnet's wedding dress meant for her one and only.<br>The breathtaking sight would bind any onlooker<br>to a promise of eternal love. |
| 530530 | 조금은 특별한 에일린의 웨딩드레스.<br>신부는 사랑을 거머쥐기 위해 싸움도 마다하지 않을 준비가 되어 있다. | Eileen's somewhat unique wedding dress.<br>The bride is ready to fight for her love. |
| 530531 | 자칭 '평범하기 그지없는 연구원'의 외출용 사복.<br>멋쟁이 지인에게 추천받은 코디를 한번에 세트로 구매했다고 한다. | Casual wear for a self-proclaimed "utterly ordinary researcher" when going out.<br>Apparently, she bought the whole outfit as a set, recommended by a fashionable acquaintance. |
| 530532 | 트로이카의 해양 연구를 위해 마련한 이브의 연구용 수영복.<br>효율을 중시한 단순한 의상임에도, 망자마저 매혹하는 요염함이 느껴진다. | Eve's research swimsuit, designed for studying the seas of Troyca.<br>Despite its simple design favoring efficiency, its allure is potent enough to enchant even the deceased. |
| 530533 | 시하가 직접 고른 심플한 네이비 비키니.<br>겁을 잔뜩 먹은 채 동료의 손을 잡고 있는 모습이 보호본능을 일으킨다.<br>잡은 손이 동료의 손이 아니라는 사실은 굳이 이야기해 주지 않아도 되겠지… | Simply styled navy bikini, personally selected by Seeha.<br>The sight of her gripping a colleague's hand in utter fear stirs protective urges.<br>Perhaps it's best left unsaid that the hand she holds isn't her colleague's, after all... |
| 530534 | 미카의 발랄한 분위기와 어울리는 레드 스트라이프 비키니.<br>담력 시험을 위해 귀여운 비명을 엄청나게 연습했지만, <br>역시 현실은 언제나 계획대로 되진 않는 모양이다. | A red-striped bikini that matches Mica's lively spirit.<br>Despite her diligent practice of making cute screams for the fear challenge,<br>reality seldom follows the script. |
| 530535 | 여름을 맞이해 마련한 나오미의 비키니.<br>"화려한 디자인보다는 수수한 디자인이 좋지!" 라고 했지만… <br>입었을 때의 파괴력은 전혀 수수하지 않은 것 같다. | Naomi's bikini chosen for summer.<br>She claimed to prefer something simple over flashy,<br>but the actual effect when this is worn seems to be anything but simple. |
| 530536 | 칠흑처럼 검은 갑옷을 두르고 결전에 임하는 리젤로테의 모습.<br>그녀의 기원에 제일 깊게 새겨진 것은 바로 종말과의 싸움이었다. | Clad in pitch-black armor, Lizelotte prepares for the final battle.<br>The fight against the apocalypse left the deepest mark on her origin. |
| 530537 | 칠흑처럼 검은 갑옷을 두르고 결전에 임하는 리젤로테의 모습.<br>그녀가 진정으로 바란 것은 고독하게 휘두르는 힘이 아닌, <br>절망적인 싸움에 함께할 동료였을지도 모른다. | Clad in pitch-black armor, Lizelotte prepares for the final battle.<br>Perhaps what she truly desired was not the power she wielded in solitude<br>but companions to stand with her in the direst battles. |
| 530538 | 밤의 숲을 지키는 바니 헌터 의상.<br>니콜은 조금 부끄러워하고 있긴 하지만, 의외로 활동하기엔 편하다고 한다.<br>매돌이도 새로운 분장이 마음에 드는 것 같다. | Bunny Hunter outfit for guarding the forest at night.<br>Although a bit embarrassed, Nicole admits it's surprisingly comfortable for physical activity.<br>Even Maedori seems to approve of the new look. |
| 530539 | 공연의 마지막을 장식하는 아름다운 디바의 의상.<br>슬픔도 괴로움도 모두 날려버릴 화려한 무대의 막이 지금 오른다. | The diva's gorgeous costume for the show's grand finale.<br>The curtain rises on a spectacular stage, ready to wash away all grief and anguish. |
| 530540 | 사슬과 스타킹이 섹시한 의상. 핑크빛 리본으로 큐트함을 더했다.<br>루테의 말을 인용하자면 '인간에게 잡혀 온 악몽의 검은 양'…이라는 컨셉이라는 듯하다. | A bold outfit featuring chains and stockings with a dash of cuteness from pink accents.<br>According to Lute, it represents a black sheep of nightmare captured by a human. |
| 530541 | 커다란 여우 귀 후드가 달린 오버핏 잠옷.<br>선임 오퍼레이터들이 선물해 준 귀여운 잠옷… 이지만,<br>릴리트가 골라 두었던 파격적인 디자인의 잠옷과 함께 입어 독특한 매력이 생겨났다. | An oversized pajama set featuring a large fox ear hood.<br>Originally a cute gift from the senior operators,<br>it took on an unusual charm upon being paired with Lilith's bold sleepwear. |
| 530542 | 매우 특수한 소재로 만든 첨단 의류.<br>멸망해가는 세상에 몇 번의 종말이 찾아오더라도,<br>그녀는 언제나 변함없이 인간의 왕을 위해 헌신할 것이다. | Cutting-edge apparel crafted from an exceptionally unique material.<br>No matter how many times the world succumbs to ruin,<br>her devotion to the ruler of humans will never waver. |
| 530543 | 우리가 만나게 된 것은 운명이었을까?<br>가늘게 이어진 그림자 속에서 탄생한 웨리의 의상.<br>섹시하지만 치명적인 독을 품고 있다. | Was our meeting destined?<br>Wheri's outfit born from a thin veil of shadow.<br>Sexy, but laced with a deadly poison. |
| 530544 | 칼라르에서 의외로 높은 신분을 지닌 르네의 숙녀 같은 사복. <br>평소의 전투 의상과는 달리 자연스러운 우아함이 드러난다. | Casual wear fit for a lady of Renee's surprising rank in Chalar.<br>It reveals a natural elegance, a contrast to her usual battle gear. |
| 530545 | 부드러운 봄날의 꽃처럼 피어난 웨리의 의상.<br>누군가를 향한 수줍은 마음이 페이렌에 봄을 가져왔다. | Wheri's outfit, blooming like a flower on a delicate spring day.<br>A bashful heart has brought the season of spring to Fayren. |
| 530546 | 옷의 주인은 훌쩍 커버렸지만,<br>가엽게도 옷은 주인을 따라가지 못했다. | The wearer has grown up considerably<br>while the clothes couldn't grow along with her. |
| 530547 | 사쿠요가 바라던 모습으로 현현한 아수라.<br>열망을 보여주는 환상은 먹잇감을 집요하게 기다린다. | Asura manifesting in the form Sakuyo wished for.<br>This illusion of yearning waits tenaciously for its prey. |
| 530548 | 악몽 속을 표류하는 꿈의 유배자가 착용한 의상.<br>스스로를 잃어버린 채 어둠 속을 떠돌고 있다. | An outfit worn by a dream exile drifting through nightmares.<br>Having lost her sense of self, she roams aimlessly in the dark. |
| 530549 | 악몽을 건너온 꿈의 나비를 형상화한 의상.<br>그저 사랑받기 위해서, 자신과 연관된 모든 추악함을 제거하고 '정화'하려 한다. | Attire fashioned after the dream butterfly traversing a nightmare.<br>Desperate for love, it she seeks to cleanse herself of every trace of ugliness. |
| 530550 | 정체를 숨기고 이브의 날을 조사하기 위해 마련한 라리마의 사복.<br>아이들에게 줄 선물을 가득 사서 신이 난 날개짓이 평소보다 빠른 것 같다. | Larimar's casual outfit for her undercover investigation of Eve's Day.<br>Her wings seem to beat faster than usual, possibly brimming with joy as she bought lots of gifts for children. |
| 530551 | 이브의 날 메카 컨벤션에 참여한 르네의 이벤트 의상.<br>매력적인 상품 소개부터 우아한 귀빈 안내까지, 뭐든지 맡겨주시길. | Renee's special outfit for the Eve's Day Mech Convention.<br>Whether it is presenting exciting merchandise or welcoming esteemed guests, she's up for the task. |
| 530552 | 이브의 날 메카 컨벤션에 참여한 플린의 이벤트 의상.<br>루돌프 뿔이 달린 고글만 내리면 폭탄 터트릴 준비 끝! | Flynn's special outfit for the Eve's Day Mech Convention.<br>She just needs to flip down the goggles with Rudolph antlers to blow things up! |
| 530553 | 메피스토펠레스가 기만의 악마로써 지닌 모든 기능을 해금한 모습. <br>강대한 힘을 제어하기 위해선 <br>어떤 일에도 흔들리지 않는 강한 사명감이 필요하다. | Mephistopheles, with all her powers as the Demon of Deception fully unleashed.<br>Harnessing such overwhelming might requires<br>a firm resolve that stands strong, no matter what. |
| 530554 | 메피스토펠레스가 기분 전환을 위해 커스텀한 의상. <br>새파란 여명의 하늘도 좋지만, <br>가끔은 따사로운 오후를 만끽하는 것도 좋지 않을까. | An outfit customized by Mephistopheles for a change of pace.<br>The crisp blue skies of dawn are beautiful,<br>but basking in a cozy afternoon has its charms, too. |
| 530555 | 에덴 최대 규모 군수 기업의 CEO가 비상 작전 시 착용하는 복식. <br>연구직을 상징하는 푸른색이 아닌 전투직을 상징하는 붉은색 기조로 되어있다. | The emergency operations attire of the CEO of Eden's largest military supplier.<br>Instead of the blue theme symbolizing research roles, it adopts the red theme of combat roles. |
| 530556 | 찬란한 햇살로 물든 듯 화사한 가온의 전통 복장.<br>새해에는 평화를 염원하는 경건한 바람이 꼭 이루어지기를. | A dazzling traditional outfit of Gaon, shimmering as if touched by radiant sunlight.<br>May the new year fulfill the solemn hope for lasting peace. |
| 530557 | 금빛으로 화려하게 장식된 가온의 전통 복장.<br>새해에는 모두가 바라던 성과를 얻을 수 있기를. | Traditional attire of Gaon, lavishly adorned with golden accents.<br>May everyone achieve their dreams this new year. |
| 530558 | 이디스의 재기발랄함이 돋보이는 가온의 전통 복장.<br>새해에는 누구나 노력한 만큼 성장할 수 있기를. | Traditional garb of Gaon, showcasing Edith's cheerful nature.<br>May everyone flourish through their hard work in the new year. |
| 530559 | 어두운 진실을 알게 된 로제의 사복.<br>떠나간 이들에 대한 애도와 지친 이들을 안아 주고 싶은 마음이 담겨 있다. | The outfit Rose wears after discovering a dark truth.<br>Her sorrow for those who are gone and a deep wish to comfort the weary can be felt. |
| 530560 | 고통도 절망도 없는 세계에 물든 로제의 모습.<br>환상과 현실의 경계에서 수녀는 진실을 거부했다. | Rose, lost in a realm where neither pain nor despair exists.<br>Standing at the edge of illusion and reality, the nun refused to accept the truth. |
| 530561 | 선선한 봄바람만큼이나 산뜻함이 느껴지는 클로이의 사복.<br>어디로든 갈 수 있도록 활동성을 갖춘 의상이다. | Chloe's casual wear, light and breezy like a spring breeze.<br>Designed for ease of movement, ready for any journey. |
| 530562 | 홍란이 공식적인 자리에서 입는 예복.<br>흐드러지게 피어난 수천 송이의 복숭아 꽃처럼 아름답지만,<br>홍란은 불편하고 갑갑한 듯 하다. | The formal attire Honglan dons for official events.<br>While it is as gorgeous as a field of peach blossoms in full bloom,<br>Honglan seems uncomfortable and constrained by it. |
| 530563 | 전장을 수호하는 냉정하고 강인한 수호신의 의상.<br>수많은 적이 공격해 와도, <br>차분하고 침착하게 <br>지켜야 할 장소를 지켜내리라. | The outfit of a steadfast guardian who watches over the battlefield.<br>Even in the face of countless enemies,<br>she will stand firm,<br>protecting her post with calm determination. |
| 530564 | 미늘을 이어 붙여 활동성과 방어력을 모두 챙긴 갑옷.<br>모두를 지키기 위해 한 발자국 더 앞으로 나서는 순이의 용기가 담겨있다. | A suit of armor forged with interwoven scales, balancing agility and defense.<br>It carries Soonie's bravery, stepping forward to shield those in need. |
| 530565 | 한울이 속세에 외출하기 위해 준비한 복장.<br>"요즘 아이들은 이런 걸 좋아한다며…?" <br>살짝 향수가 느껴지는 패션이란 건 비밀로 하자. | Hanul picked out this outfit for her visit to the outside world.<br>"I heard this is trendy with the kids now, right...?"<br>Let's not bring up the fact that it's got a bit of a retro vibe. |
| 530566 | 보다 강력한 존재감을 발하는 한울의 의복.<br>평화를 원하기에, 때로는 <br>싸움을 피할 수 없는 법이다. | A garment that amplifies Hanul's formidable presence.<br>Though she seeks peace,<br>there are times when she cannot avoid a fight. |
| 530567 | 이상의 모습으로 다시 태어난 재클린.<br>칼라르 암즈 코퍼레이션의 최신 기술, 르네의 심미안,<br>구원자의 진실한 애정이 한데 모여 만들어낸 기적 같은 모습이다. | Jacqueline reborn in her ideal form.<br>A miraculous creation born from<br>Chalar Arms Corporation's cutting-edge technology, Renee's artistic vision, and Savior's genuine affection. |
| 530568 | "이딴 미궁, 전부 부숴버리겠사와요!" <br>누군가의 망상이 만들어낸, 폭주 모드 이디스. <br>화려한 배팅 실력으로 전부 해치워버리겠사와요! | "I shall wreck this stupid labyrinth!"<br>Edith in rampage mode, conjured from someone's delusion.<br>She'll demolish everything with her fierce and flashy bat strikes! |
| 530569 | 프릴과 조개로 사랑스럽게 꾸며진 지호의 수영복.<br>걸을 때마다 파레오가 잔잔하게 흔들려,<br>바다를 유영하는 인어의 꼬리처럼 보인다. | Jiho's swimsuit, sweetly decorated with frills and seashells.<br>As she walks, the wrap sways gently,<br>like a mermaid's tail dancing through the water. |
| 530570 | 4월의 새싹들처럼 싱그럽게 물든 지호의 예복.<br>포근하고 따뜻한 봄의 햇살이 언제나 가온을 비추길. | Jiho's formal attire, tinged with the lively green of April buds.<br>Wishing that the gentle spring sunshine forever shines on Gaon. |
| 530571 | 첫 가온 출장을 기념해 칸나가 야심차게 준비한 가온 전통 의상.<br>섹시도 큐트도 포기하지 못한 끝에 다소 골때리는(?) 디자인이 되어 버렸다. | Gaon's traditional attire, ambitiously prepared by Kanna to celebrate her first visit to Gaon.<br>Torn between sexy and cute, the final look ended up being...delightfully chaotic. |
| 530572 | 르네를 위해 준비된 암즈 코퍼레이션의 새로운 제복.<br>깔끔하게 떨어지는 실루엣이 심플하게 멋스럽다. | Arms Corporation's new uniform prepared for Renee.<br>The silhouette flows gracefully, offering simple elegance. |
| 530573 | 밤의 오로라처럼 신비롭게 빛나는 르네의 의상.<br>평소와는 다른 일면을 볼 수 있을지도…? | Renee's outfit, shining mysteriously like an aurora at night.<br>Perhaps you'll be able to glimpse a different side of her... |
| 530574 | 과거 바이스가 현자의 제자로 활동했던 시절의 모습. <br>당시에는 나름 위엄을 갖춘다고 애쓴 모습이지만, <br>지금와서 보면 살짝 귀여움이 과할지도 모른다. | Weiss from her past days as a disciple of a sage.<br>She tried so hard to look dignified back then,<br>but looking at it now...maybe it's a little too cute. |
| 530575 | 미리암이 내근이나 외부 미팅을 할 때 입는 정장.<br>솜씨 좋은 중간 관리직 답게 <br>군더더기 없이 스타일리시하다. | Miriam's business attire, worn for internal duties or outside meetings.<br>Befitting a competent middle manager,<br>it's sleek and stylish. |
| 530576 | 미리암을 위해 특별히 제작된 결전 장비.<br>칼라르에서 극히 최근에 발명한 신소재로 제작되어<br>보다 가볍고 빠르게 움직일 수 있다. | Endgame gear specially crafted for Miriam.<br>It uses a newly developed material from Chalar.<br>The design allows for lighter and faster movement. |
| 530577 | 라우라의 잠입 수사용 파티웨어.<br>의심받지 않는 비결은 바로 자신감 넘치는 표정과 자연스러운 제스처다. | Partywear used by Laura for undercover missions.<br>The key to avoiding suspicion lies in her confident expression and natural movements. |
| 530578 | 라우라의 악몽과 닮아있는 의상.<br>이 추락은 언제쯤 멈추는 걸까? | An outfit resembling Laura's nightmares.<br>When will this fall come to an end? |
| 530579 | 가넷이 밤의 일족으로 활동할 때 입는 간부 예복.<br>여린 꽃잎처럼 가련하고, <br>가시처럼 위험한 매력을 품고 있다. | A uniform worn by Garnet while serving as an officer of the Nightbloods.<br>Delicate as flower petals,<br>but hiding a dangerously alluring charm like thorns. |
| 530580 | 당신의 마음을 불태우는<br>클래식한 검은 바니걸 복장.<br>위험하면서도 황홀한 이 시간을 영원히. | A classic black bunny outfit<br>that ignites passion.<br>May this dangerous but blissful moment last forever. |
| 530581 | 메이드 일을 지휘하기 위해 현장에 뛰어든 메이드장 린지를 위한 의상.<br>클래식한 메이드복 아래에는 쌍둥이의 돌발 행동도<br>단숨에 제압 가능한 장비들이 숨겨져 있다. | An outfit for Linzy, the head maid who manages the other maids.<br>Beneath the classic maid dress are tools<br>ready to instantly handle the twins' unexpected antics. |
| 530582 | 누군가의 의뢰를 받아 오토하가 특별히 제작한 멜피스의 메이드복.<br>활기찬 움직임에도 풍성한 치마가 흐트러지지 않도록<br>가터벨트를 매치했다. | A custom maid outfit for Melfice, specially made by Otoha at someone's request.<br>A garter belt was added to keep the skirt<br>in place during dynamic movement. |
| 530583 | 누군가의 의뢰를 받아 오토하가 특별히 제작한 브라이스의 메이드복.<br>짧은 원피스와 허벅지 벨트로 절제된 실루엣을 강조했다. | A custom maid outfit for Bryce, specially made by Otoha at someone's request.<br>The short dress and thigh belt enhance its sharp, minimalist design. |
| 530584 | 새로운 세계를 찾아온 자를 위한 옷.<br>앞으로는 사랑받을 일만 남은 미래를 위한 것인 듯, 러블리한 장식으로 가득하다. | An outfit made for the one who has come looking for a new world.<br>It is adorned with adorable details as though tailored for a future where only love awaits. |
| 530585 | 어쩌면 도래했을지도 모르는 미래를 연상시키는 모습.<br>검게 물든 머리카락엔 상상조차 어려운 심연의 어둠이 일렁인다. | A look reminiscent of a future that could have come.<br>The blackened hair ripples with the darkness of an abyss too deep to imagine. |
| 530586 | 페트라가 새로 장만한 용병 활동복이자 평상복 의상.<br>묘지의 흙으로 옷이 더러워지는 일이 잦은 만큼, 세탁에 용이한 특수 소재로 만들어졌다. | Petra's new outfit serving as both her mercenary gear and everyday wear.<br>Given how often her clothes get stained with cemetery dirt, this is made with a specialized fabric known for easy cleaning. |
| 530587 | 페트라가 새로 장만한 용병 활동복이자 평상복 의상.<br>특수한 소재의 원단으로 마안을 가리고 있다. | Petra's new outfit serving as both her mercenary gear and everyday wear.<br>A fabric of special material covers her evil eye. |
| 530588 | 페트라가 과거, 용병단 스웜프 소속이었던 시절에 입었던 의상.<br>허리를 조이는 코르셋 때문인지, 옷을 입을 때마다 묘하게 답답함이 느껴진다고 한다. | Petra's old outfit from her Swamp days.<br>The waist-cinching corset makes it feel uncomfortably tight whenever she wears it. |
| 530589 | 과거, 니아가 세계수에 봉인되기 전의 의상.<br>'페이렌의 재앙'이라고 일컬어지던 모습이기에, 많은 이들은 이 모습을 잊고 싶어 했다. | Nia's outfit from the past before she was sealed in the World Tree.<br>Known as "Calamity of Fayren," it is a look many wished to forget. |
| 530590 | 니아가 지닌 충동이 실체화 된 의상.<br>누구보다 잔혹함과 동시에 거부할 수 없을 정도로 사랑스럽다. | Nia's impulses have materialized into this outfit.<br>Ruthlessly cruel, yet irresistibly lovely at the same time. |
| 530591 | 어딘가 엄청난 해방감을 자랑하는 니아의 트라이키니 수영복.<br>이런 걸 입고 날아다니면, 모든 사람들이 쳐다보지 않을까? | Nia's boldly liberating trikini swimsuit.<br>If she flies in this, all eyes will be on her for sure. |
| 530592 | 되찾은 육신의 매력을 한껏 뽐내는, 사쿠요의 여름 패션.<br>과감한 레드 컬러와 드러낸 살결이 한낮의 태양 아래 말갛게 빛난다. | Sakuyo's summer outfit gratuitously showcasing the glamour of her reclaimed body.<br>The bold red color and the striking skin exposure gleam under the midday sun. |
| 530593 | 구원자와의 여름을 위해 메피스토펠레스가 고르고 조달한 수영복.<br>가볍게 비치는 프릴의 하늘색 색감이 사랑스러움을 더한다. | Mephistopheles handpicked and prepared this swimsuit for a summer with Savior.<br>The semi-sheer light blue frills add a lovely air. |
| 530594 | 아무래도 과감한 의상은 부끄럽다며 고른 도미니크의 비키니.<br>길게 늘어뜨린 머리와 새하얀 피부가 햇살 아래 더 돋보인다. | Feeling shy about anything too revealing, Dominique settled on this bikini.<br>Her long, flowing hair and fair skin shine all the brighter under the sun. |
| 530595 | 의료 지원이 아닌 외부 업무를 위한 택티컬 유니폼.<br>몸에 딱 달라붙는 바디슈트로 디자인되어, 활동성과 기능성을 살렸다. | A tactical uniform intended for external operations rather than medical aid.<br>It is designed as a form-fitting bodysuit to maximize freedom of movement and practical performance. |
| 530596 | 성스럽고 희망찬 느낌을 살린 아이돌 의상. 자애로운 모두의 아이돌, 누구보다 빛나는 리더! | An idol outfit with a holy, hopeful air. Everybody's gracious idol, the shining leader above all! |
| 530597 | 사랑스럽고 발랄한 느낌을 살린 아이돌 의상. 귀엽고 순수한 매력의 아이돌은 언제나 인기만점! | An idol costume designed to capture a lovely and playful vibe. An idol with innocent cuteness is always adored! |
| 530598 | 시크하고 섹시한 느낌을 살린 아이돌 의상. 매혹적이고 매력적인 아이돌은 언제나 수요층 폭발! | An idol costume designed to capture a chic and sultry vibe. An idol with an irresistible allure is forever in high demand! |
| 530599 | 아우렐리아의 군단장 카넬리안의⋯민간 사찰 복장?<br>입어보니 많이 편하지만, 절대로 임무 때문에 내려온 것이다. 절대로! | Aurelia's Commander of the Paladins Carnelian's... undercover attire for observing civilians?<br>It does feel very comfortable, but she's only donning it for the mission! |
| 530600 | 아우렐리아의 군단장 카넬리안의 고귀함이 돋보이는 청금의 갑주.<br>예로부터 위대한 핏줄을 이은 이들은 스스로를 '푸른 피'라 불러왔다. | Metallic blue armor showcasing Carnelian's dignity as the Commander of the Paladins of Aurelia.<br>Throughout history, those of great bloodlines have referred to themselves as blue blood. |
| 530601 | 가넷이 밤의 일족으로 활동할 때 입는 간부 예복.<br>여린 꽃잎처럼 가련하고, <br>가시처럼 위험한 매력을 품고 있다. | A uniform worn by Garnet while serving as an officer of the Nightbloods.<br>Delicate as flower petals,<br>but hiding a dangerously alluring charm like thorns. |
| 530602 | 당신의 마음을 불태우는, <br>클래식한 검은 바니걸 복장.<br>위험하면서도 황홀한 이 시간을 영원히. | A classic black bunny outfit<br>that ignites passion.<br>May this dangerous but blissful moment last forever. |
| 530603 | 검은색 하이레그로 은근한 섹시함을 뽐내며, 쫑긋 솟은 귀로 깜찍함까지 챙긴 모습.<br>정석 중의 정석이라 할까. 단순하지만 완벽하다. | A black high-leg outfit exuding subtle sexy vibes, paired with cute, perky ears.<br>The textbook definition of classic. Minimal but perfect. |
| 530604 | 가온을 떠나 항해하던 어느 여름날, 셰리는 태양이 너무 뜨거워 견딜 수 없었다.<br>더위는 그녀를 더욱 취하게 만들었고 결국 바다에 뛰어들었다. | While sailing away from Gaon one summer day, Cherrie could no longer endure the blazing sun.<br>The heat only heightened her intoxication, and she ended up diving into the ocean. |
| 530605 | 가온의 밤거리를 홀로 거닐던 방랑자의 복장.<br>술에 취해 비틀거리며, 오늘도 밤거리를 헤맨다. | The outfit of a lone drifter through Gaon's night alleys.<br>Drunk and swaying, she roams the streets tonight as usual. |
| 530606 | 승부사가 되기 전 에일린의 과거가 담긴 일상복. 낭만을 즐기는 당신의 옆에는 언제나 도둑이 함께라는 사실을 잊지 말기를. | Eileen's everyday wear from her days before becoming a gambler. Never forget: just as you enjoy romance, a thief is always by you. |
| 530607 | 밤에도 밝게 빛나는 자신이 주변 정령들에게 피해를 줄까 싶어 스스로 만들어낸 그림자 진 의복. 바래져 버린 머리만은 그대로라 어둠 속에서도 그녀를 알아볼 수 있다. | Worried that her brilliance, undimmed even at night, might harm other Souls around her, she crafted this shadowy outfit. Her faded hair remains unchanged, making her recognizable even in the dark. |
| 530608 | 강렬하게 타오르는 태양의 가호가 깃든 의복.<br>솔레이 왕국의 지지 않는 태양을 상징하듯, 아름답고 화려한 복식이다. | An outfit imbued with the protection of the blazing sun.<br>Its lavish beauty seems to represent the unsetting sun of the Kingdom of Solrey. |
| 530609 | 헤이즐의 의복. 승리를 축하하기 위한 파티를 위한 화려함만을 강조한 의상.<br>눈이 멀 듯한 화려함이 더더욱 전쟁의 승리를 고조시킨다. | Hazel's extensively lavish garment, designed specifically for victory celebrations.<br>Its dazzling ornamentation heightens the thrill of triumph in war. |
| 530610 | 한때는 천사형 정령이었다는 것을 되새겨주는 이브의 모습.<br>그러나 주의하라. 이 모습에 매료되는 순간 그녀의 영혼이 타락했음을 다시 한번 깨닫게 될 테니. | This appearance reminds you of Eve's past as an Angel Soul.<br>You'd better be wary. The moment you are charmed by this form, you'll realize once more how her soul was corrupted. |
| 530611 | 타브리아 제국의 공작 직위를 나타내듯, 우아하고 기품 있는 의상.<br>어둠 속에 녹아드는 고급스러운 빛깔이 그녀의 품격을 드러낸다. | An elegant, graceful outfit befitting her title as a duchess of the Tabria Empire.<br>Its refined colors melt into the darkness, underscoring her dignity. |
| 530612 | 순결한 기운을 두른 라리마의 의상.<br>생명 그 자체의 아름다움과 순결함을 상징하는 맑은 빛을 품고 있다. | Larimar's outfit, emanating an aura of innocence.<br>A bright light shines from it, symbolizing life's beauty and purity. |
| 530613 | 오닉스의 주장에 의하면 우주의 신호를 잘 느낄 수 있도록 설계된 옷이라고 한다.<br>우주의 신호와 노출이 무슨 상관일까 싶지만, 반드시 온몸으로 우주의 신호를 받아야만 한다는데…? 루- | Onyx claims this outfit was designed to help her sense signals from outer space.<br>While the link between outer space signals and exposed skin seems questionable, she insists that it's important to receive the signal with her entire body. Ru? |
| 530614 | 트로이카의 찬란한 봄을 품은 예복. 새로운 시작을 상징하듯 아름다운 봄의 색을 담은 디자인이다 | A ceremonial outfit that embodies Troyca's resplendent spring. Its beautiful spring colors hint at a new beginning. |
| 530615 | 진정한 구원을 행할 아우렐리아의 천사여, 의무를 따르라.<br><부름>의 목소리만을 듣는 천사의 마지막 선택. | Angel of Aurelia, destined to bring forth true salvation, fulfill your duty.<br>The final choice of an angel who only heeds the voice of the "Call." |
| 530616 | 새빨간 불꽃과 함께 타오르는 신벌의 불꽃.<br>예로부터 전지전능한 이들은 불벼락으로 지상의 죄인을 태웠다고 전해진다. | Flames of divine retribution, burning fiercely with a crimson blaze.<br>It is said that almighty beings of old struck sinners on earth with firebolts. |
| 530617 | 착한 아이에게 선물을 주기 위한 비비안의 바니걸 의상.<br>기품 있는 마녀지만, 특별한 날을 위한 변신도 마다하지 않는단다. | Vivienne's bunny girl outfit, worn when delivering presents to good children.<br>Though a dignified witch, she is willing to dress up for special occasions. |
| 530618 | 눈부시게 아름다운 순백의 의상.<br>깨끗하고 순결한 마음으로 당신의 곁을 보좌할 것이다. | A pure white outfit of dazzling beauty.<br>She will always stay close, serving you with an untarnished, innocent heart. |
| 530619 | 현실과 동떨어진 듯한 분위기의 린지의 의상.<br>익숙하면서도 낯선 기분을 들게 한다. | Linzy's outfit, looking totally cut off from the real world.<br>Feels eerily familiar and utterly strange at the same time. |
| 530620 | 빛에도 어둠에도 오롯하게 속하지 못한 자.<br>스스로를 부정할 수밖에 없는 삶은 얼마나 괴로운가. | One who does not fully belong to light or darkness.<br>How agonizing it must be to live in denial of oneself. |
| 530621 | 그곳에 떠있던 것은 영원한 태양이 아니었다.<br>비밀을 숨긴 태양은 아무도 모르는 새에 추락하고 있었다. | What hung above was not the eternal sun.<br>The sun, hiding a secret, was falling without anyone realizing it. |
| 530622 | 오닉스의 독창성이 돋보이는 가온의 전통 복장.<br>새해에는 삐뽓하고 뽀삣할 수 있기를! | Traditional garb of Gaon, showcasing Onyx's creative spirit.<br>May the new year be full of beepity-boopity-boop! |
| 530623 | 아폴리온의 신비롭고 몽환적인 매력이 돋보이는 가온의 전통 복장.<br>새해에는 종말을 선사하기를... | Traditional garb of Gaon, showcasing the mystical, dreamlike charm of Apollyon.<br>May the End finally come in the new year... |
| 530624 | 피에 물든 과오를 마주하라.<br>어둠마저 가라앉는 밤이 되면 끝나지 않을 악몽이 찾아온다. | Face the bloodstained sins of the past.<br>On a night when even darkness drowns, an eternal nightmare will descend. |
| 530625 | 벚꽃이 물든 달의 의복.<br>만월 아래에서 영원을 맹세한 인연의 소망이 깃들었다. | A lunar outfit steeped in cherry blossoms.<br>It is imbued with the wish of a fated connection that pledged forever under the full moon. |
| 530998 | 단정하게 차려입은 명문 사립학교 교복 의상.<br>성적우수. 품행단정. 조용한 팔방 미녀가 밴드부 실의 문을 두드리게 된 까닭은 무엇일까? | A prestigious private school uniform that makes one look neatly dressed up.<br>Excellent grades. Good conduct. Why would a quiet Jill of all trades knock on the door of the band club? |
| 530999 | 자신만의 개성이 귀여운 공립학교 교복 의상.<br>교내 최고의 분위기 메이커. 깜찍한 소녀 기타리스트, 이번에는 밴드부의 에이스를 노린다! | A cute public school uniform with a unique look.<br>She's the life of the party, a cute guitarist now aiming to become the star of the band! |
| 700001 | 메인_주인공과 메피스토1 | 메인_주인공과 메피스토1 |
| 700002 | 메인_주인공과 메피스토2 | 메인_주인공과 메피스토2 |
| 700003 | 메인_메피스토일반 | 메인_메피스토일반 |
| 700004 | 메인_유리아기도 | 메인_유리아기도 |
| 700005 | 메인_유리아달빛 | 메인_유리아달빛 |
| 800001 | 인연_메피스토_이벤트1 | 인연_메피스토_이벤트1 |
| 800002 | 인연_메피스토_이벤트2 | 인연_메피스토_이벤트2 |
| 800003 | 인연_메피스토_엔딩 | 인연_메피스토_엔딩 |
| 800004 | 인연_제이드_이벤트1 | 인연_제이드_이벤트1 |
| 800005 | 인연_제이드_이벤트2 | 인연_제이드_이벤트2 |
| 800006 | 인연_제이드_엔딩 | 인연_제이드_엔딩 |
| 2110001 | 유물의 기억: 방주 메타트론 | Artifact Memory: Ark Metatron |
| 2110002 | 유물의 기억: 방주 자드키엘 | Artifact Memory: Ark Zadkiel |
| 2110003 | 유물의 기억: 잔다르크의 깃발 | Artifact Memory: Flag of Jeanne d'Arc |
| 2110004 | 유물의 기억: 무라마사 | Artifact Memory: Muramasa |
| 2110005 | 유물의 기억: 미다스의 손 | Artifact Memory: Hand of Midas |
| 2110006 | 유물의 기억: 프라가라흐 | Artifact Memory: Fragarach |
| 2110007 | 유물의 기억: 간디바 | Artifact Memory: Gandiva |
| 2110008 | 유물의 기억: 요시모토 사몬지 | Artifact Memory: Yoshimoto Samonji |
| 2110009 | 유물의 기억: 성해포 | Artifact Memory: Holy Shroud |
| 2110010 | 유물의 기억: 신편귀독주 | Artifact Memory: Shinpen Kidoku |
| 2110011 | 유물의 기억: 골디락스의 빈 그릇 | Artifact Memory: Bowl of Goldilocks |
| 2110012 | 유물의 기억: 청룡언월도 | Artifact Memory: Green Dragon Crescent Blade |
| 2110013 | 유물의 기억: 거북선 | Artifact Memory: Turtle Ship |
| 2110014 | 유물의 기억: 다그다의 곤봉 | Artifact Memory: Dagda's Club |
| 2110015 | 유물의 기억: 칼리오페의 소리굽쇠 | Artifact Memory: Tuning Fork of Calliope |
| 2110016 | 유물의 기억: 오르페우스의 리라 | Artifact Memory: Lyre of Orpheus |
| 2110017 | 유물의 기억: 레메게톤 | Artifact Memory: Lemegeton |
| 2110018 | 유물의 기억: RPG-7 | Artifact Memory: RPG-7 |
| 2110019 | 유물의 기억: 투탕카멘의 가면 | Artifact Memory: Tutankhamun's Mask |
| 2110020 | 유물의 기억: 쿠투네시르카 | Artifact Memory: Kutune Shirka |
| 2110021 | 유물의 기억: 모글레이 | Artifact Memory: Murgleys |
| 2110022 | 유물의 기억: 코르누코피아 | Artifact Memory: Cornucopia |
| 2110023 | 유물의 기억: 엘릭서 | Artifact Memory: Elixir of Life |
| 2110024 | 유물의 기억: 하멜른의 피리 | Artifact Memory: Hameline's Flute |
| 2110025 | 유물의 기억: 누아다의 의수 | Artifact Memory: Nuada Airgetlám |
| 2110026 | 유물의 기억: 테트라비블로스 | Artifact Memory: Tetrabiblos |
| 2110027 | 유물의 기억: 큐피드의 화살 | Artifact Memory: Cupid's Arrow |
| 2110028 | 유물의 기억: 바리사다 | Artifact Memory: Balisarda |
| 2110029 | 유물의 기억: 페일노트 | Artifact Memory: Failnaught |
| 2110030 | 유물의 기억: 에메랄드 타블렛 | Artifact Memory: Emerald Tablet |
| 2110031 | 유물의 기억: 7발의 마탄 | Artifact Memory: The Seventh Bullet |
| 2110032 | 유물의 기억: 아이기스 | Artifact Memory: Aegis |
| 2110033 | 유물의 기억: 잔트만의 꿈가루 | Artifact Memory: Dust of Sandman |
| 2110034 | 유물의 기억: 판도라의 상자 | Artifact Memory: Pandora's Box |
| 2110035 | 유물의 기억: 롱기누스의 창 | Artifact Memory: Longinus |
| 2110036 | 유물의 기억: 게이 보 | Artifact Memory: Gáe Buide |
| 2110037 | 유물의 기억: 아야무르 | Artifact Memory: Ayamur |
| 2110038 | 유물의 기억: 야그루시 | Artifact Memory: Yagrush |
| 2110039 | 유물의 기억: 카두세우스 | Artifact Memory: Caduceus |
| 2110040 | 유물의 기억: 게 볼그 | Artifact Memory: Gáe Bulg |
| 2110041 | 유물의 기억: 클라렌트 | Artifact Memory: Clarent |
| 2110042 | 유물의 기억: 바즈라 | Artifact Memory: Vajra |
| 2110043 | 유물의 기억: 반혼향 | Artifact Memory: Spirit-Calling Incense |
| 2110044 | 유물의 기억: 호신부 | Artifact Memory: Amulet of Protection |
| 2110045 | 유물의 기억: 묠니르 | Artifact Memory: Mjölnir |
| 2110046 | 유물의 기억: 아스칼론 | Artifact Memory: Ascalon |
| 2110047 | 유물의 기억: 다섯 번째 나팔 | Artifact Memory: Fifth Trumpet |
| 2110048 | 유물의 기억: 오시리스의 지팡이 | Artifact Memory: Staff of Osiris |
| 2110049 | 유물의 기억: 궁니르 | Artifact Memory: Gungnir |
| 2110050 | 유물의 기억: 츠쿠요미의 백동거울 | Artifact Memory: Mirror of Tsukuyomi |
| 2110051 | 유물의 기억: 만파식적 | Artifact Memory: Manpashikjeok |
| 2110052 | 유물의 기억: 아스트라페 | Artifact Memory: Astrape |
| 2110053 | 유물의 기억: 여의금고봉 | Artifact Memory: Ruyi Jingu Bang |
| 2110054 | 유물의 기억: 엘도라도의 금화 | Artifact Memory: Gold Coins of El Dorado |
| 2110055 | 유물의 기억: 헤파이스토스의 망치 | Artifact Memory: Hephaestus's Hammer |
| 2110056 | 유물의 기억: 하르페 | Artifact Memory: Harpe |
| 2110057 | 유물의 기억: 아메노하바키리 | Artifact Memory: Ame No Habakiri |
| 2110058 | 유물의 기억: 운명의 서판 | Artifact Memory: Tablet of Fate |
| 2110059 | 유물의 기억: 아조트 검 | Artifact Memory: Azoth |
| 2110060 | 유물의 기억: 찬란한 광휘의 성해포 | Artifact Memory: Holy Shroud of Splendid Radiance |
| 2110061 | 유물의 기억: 롱고미니아드 | Artifact Memory: Rhongomyniad |
| 2110062 | 유물의 기억: 튀르핑 | Artifact Memory: Tyrfing |
| 2110063 | 유물의 기억: 골든 레코드 | Artifact Memory: Golden Record |
| 2110064 | 유물의 기억: 타나토스=프라가라흐 | Artifact Memory: Thanatos = Fragarach |
| 2110065 | 유물의 기억: 방주 카마엘 | Artifact Memory: Ark Chamuel |
| 2110066 | 유물의 기억: 미미르의 샘물 | Artifact Memory: Mimisbrunnr |
| 2110067 | 유물의 기억: 요시모토 사몬지(업화) | Artifact Memory: Yoshimoto Samonji (Inferno) |
| 2110068 | 유물의 기억: 여명의 방주 메타트론 | Artifact Memory: Ark of Dawn Metatron |
| 2110069 | 유물의 기억: 솔로몬의 반지 | Artifact Memory: Solomon's Ring |
| 2110070 | 유물의 기억: 태양의 왕관 | Artifact Memory: Crown of the Sun |
| 2110071 | 유물의 기억: 만파식적(미르) | Artifact Memory: Manpashikjeok (Mir) |
| 2110072 | 유물의 기억: 청룡언월도(무쌍) | Artifact Memory: Green Dragon Crescent Blade (Peerless) |
| 2110073 | 유물의 기억: 쿠투네시르카(카무이) | Artifact Memory: Kutune Shirka (Kamuy) |
| 2110074 | 유물의 기억: 누아다의 의수(백은) | Artifact Memory: Nuada Airgetlám (Argent) |
| 2110075 | 유물의 기억: 7발의 마탄(잔영) | Artifact Memory: The Seventh Bullet (Afterimage) |
| 2110076 | 유물의 기억: 소림사 탑림 | Artifact Memory: Shaolin Temple Pagoda Forest |
| 2110077 | 유물의 기억: 반혼향(각혼) | Artifact Memory: Spirit-Calling Incense (Awakened Soul) |
| 2110078 | 유물의 기억: 롱기누스의 창(열락) | Artifact Memory: Spear of Longinus (Rapture) |
| 2110079 | 유물의 기억: 천부인의 검 | Artifact Memory: Divine Sword of the Three Heavenly Seals |
| 2110080 | 유물의 기억: 호루스의 눈 | Artifact Memory: Eye of Horus |
| 2110081 | 유물의 기억: 니드호그의 이빨 | Artifact Memory: Nidhogg's Fangs |
| 2110082 | 유물의 기억: 신편귀독주(낭만) | Artifact Memory: Shinpen Kidoku (Romantic) |
| 2110083 | 유물의 기억: 묠니르(대천사) | Artifact Memory: Mjölnir (Archangel) |
| 2110084 | 유물의 기억: 종말의 나팔 | Artifact Memory: Trumpet of the End |
| 2110085 | 유물의 기억: 아야메의 백동거울 | Artifact Memory: Mirror of Ayame |
| 2111001 | 금형: 영원한 약속의 탁상시계 | Mold: Table Clock of Eternal Promise |
| 2111002 | 금형: 영원한 약속의 뮤직박스 | Mold: Music Box of Eternal Promise |
| 2111003 | 금형: 영원한 약속의 탁상거울 | Mold: Table Mirror of Eternal Promise |
| 2111004 | 금형: 영원한 약속의 금고열쇠 | Mold: Safe Key of Eternal Promise |
| 2111005 | 금형: 소원을 품은 탁상시계 | Mold: Table Clock of Wishes |
| 2111006 | 금형: 소원을 품은 뮤직박스 | Mold: Music Box of Wishes |
| 2111007 | 금형: 소원을 품은 탁상거울 | Mold: Table Mirror of Wishes |
| 2111008 | 금형: 소원을 품은 금고열쇠 | Mold: Safe Key of Wishes |
| 2111009 | 금형: 춤추는 별들의 탁상시계 | Mold: Table Clock of Dancing Stars |
| 2111010 | 금형: 춤추는 별들의 뮤직박스 | Mold: Music Box of Dancing Stars |
| 2111011 | 금형: 춤추는 별들의 탁상거울 | Mold: Table Mirror of Dancing Stars |
| 2111012 | 금형: 춤추는 별들의 금고열쇠 | Mold: Safe Key of Dancing Stars |
| 2111013 | 금형: 월광을 머금은 탁상시계 | Mold: Moonlit Table Clock |
| 2111014 | 금형: 월광을 머금은 뮤직박스 | Mold: Moonlit Music Box |
| 2111015 | 금형: 월광을 머금은 탁상거울 | Mold: Moonlit Table Mirror |
| 2111016 | 금형: 월광을 머금은 금고열쇠 | Mold: Moonlit Safe Key |
| 2111017 | 금형: 천일의 빛을 담은 탁상시계 | Mold: Table Clock of a Thousand Days of Light |
| 2111018 | 금형: 천일의 빛을 담은 뮤직박스 | Mold: Music Box of a Thousand Days of Light |
| 2111019 | 금형: 천일의 빛을 담은 탁상거울 | Mold: Table Mirror of a Thousand Days of Light |
| 2111020 | 금형: 천일의 빛을 담은 금고열쇠 | Mold: Safe Key of a Thousand Days of Light |
| 2111021 | 금형: 무한한 우주의 탁상시계 | Mold: Table Clock of Infinite Universe |
| 2111022 | 금형: 무한한 우주의 뮤직박스 | Mold: Music Box of Infinite Universe |
| 2111023 | 금형: 무한한 우주의 탁상거울 | Mold: Table Mirror of Infinite Universe |
| 2111024 | 금형: 무한한 우주의 금고열쇠 | Mold: Safe Key of Infinite Universe |
| 2111025 | 금형: 영원한 약속의 회중시계 | Mold: Pocket Watch of Eternal Promise |
| 2111026 | 금형: 영원한 약속의 오르골 | Mold: Music Box of Eternal Promise |
| 2111027 | 금형: 영원한 약속의 접이거울 | Mold: Folding Mirror of Eternal Promise |
| 2111028 | 금형: 영원한 약속의 만능열쇠 | Mold: Master Key of Eternal Promise |
| 2111029 | 금형: 소원을 품은 회중시계 | Mold: Pocket Watch of Wishes |
| 2111030 | 금형: 소원을 품은 오르골 | Mold: Orgel of Wishes |
| 2111031 | 금형: 소원을 품은 접이거울 | Mold: Folding Mirror of Wishes |
| 2111032 | 금형: 소원을 품은 만능열쇠 | Mold: Master Key of Wishes |
| 2111033 | 금형: 춤추는 별들의 회중시계 | Mold: Pocket Watch of Dancing Stars |
| 2111034 | 금형: 춤추는 별들의 오르골 | Mold: Music Box of Dancing Stars |
| 2111035 | 금형: 춤추는 별들의 접이거울 | Mold: Folding Mirror of Dancing Stars |
| 2111036 | 금형: 춤추는 별들의 만능열쇠 | Mold: Master Key of Dancing Stars |
| 2111037 | 금형: 월광을 머금은 회중시계 | Mold: Moonlit Pocket Watch |
| 2111038 | 금형: 월광을 머금은 오르골 | Mold: Moonlit Music Box |
| 2111039 | 금형: 월광을 머금은 접이거울 | Mold: Moonlit Folding Mirror |
| 2111040 | 금형: 월광을 머금은 만능열쇠 | Mold: Moonlit Master Key |
| 2111041 | 금형: 천일의 빛을 담은 회중시계 | Mold: Pocket Watch of a Thousand Days of Light |
| 2111042 | 금형: 천일의 빛을 담은 오르골 | Mold: Music Box of a Thousand Days of Light |
| 2111043 | 금형: 천일의 빛을 담은 접이거울 | Mold: Folding Mirror of a Thousand Days of Light |
| 2111044 | 금형: 천일의 빛을 담은 만능열쇠 | Mold: Master Key of a Thousand Days of Light |
| 2111045 | 금형: 무한한 우주의 회중시계 | Mold: Pocket Watch of Infinite Universe |
| 2111046 | 금형: 무한한 우주의 오르골 | Mold: Music Box of Infinite Universe |
| 2111047 | 금형: 무한한 우주의 접이거울 | Mold: Folding Mirror of Infinite Universe |
| 2111048 | 금형: 무한한 우주의 만능열쇠 | Mold: Master Key of Infinite Universe |
| 2111049 | 금형: 영원한 약속의 모래시계 | Mold: Hourglass of Eternal Promise |
| 2111050 | 금형: 영원한 약속의 스노우볼 | Mold: Snow Globe of Eternal Promise |
| 2111051 | 금형: 영원한 약속의 손거울 | Mold: Hand Mirror of Eternal Promise |
| 2111052 | 금형: 영원한 약속의 마법열쇠 | Mold: Magic Key of Eternal Promise |
| 2111053 | 금형: 소원을 품은 모래시계 | Mold: Hourglass of Wishes |
| 2111054 | 금형: 소원을 품은 스노우볼 | Mold: Snow Globe of Wishes |
| 2111055 | 금형: 소원을 품은 손거울 | Mold: Hand Mirror of Wishes |
| 2111056 | 금형: 소원을 품은 마법열쇠 | Mold: Magic Key of Wishes |
| 2111057 | 금형: 춤추는 별들의 모래시계 | Mold: Hourglass of Dancing Stars |
| 2111058 | 금형: 춤추는 별들의 스노우볼 | Mold: Snow Globe of Dancing Stars |
| 2111059 | 금형: 춤추는 별들의 손거울 | Mold: Hand Mirror of Dancing Stars |
| 2111060 | 금형: 춤추는 별들의 마법열쇠 | Mold: Magic Key of Dancing Stars |
| 2111061 | 금형: 월광을 머금은 모래시계 | Mold: Moonlit Hourglass |
| 2111062 | 금형: 월광을 머금은 스노우볼 | Mold: Moonlit Snow Globe |
| 2111063 | 금형: 월광을 머금은 손거울 | Mold: Moonlit Hand Mirror |
| 2111064 | 금형: 월광을 머금은 마법열쇠 | Mold: Moonlit Magic Key |
| 2111065 | 금형: 천일의 빛을 담은 모래시계 | Mold: Hourglass of a Thousand Days of Light |
| 2111066 | 금형: 천일의 빛을 담은 스노우볼 | Mold: Snow Globe of a Thousand Days of Light |
| 2111067 | 금형: 천일의 빛을 담은 손거울 | Mold: Hand Mirror of a Thousand Days of Light |
| 2111068 | 금형: 천일의 빛을 담은 마법열쇠 | Mold: Magic Key of a Thousand Days of Light |
| 2111069 | 금형: 무한한 우주의 모래시계 | Mold: Hourglass of Infinite Universe |
| 2111070 | 금형: 무한한 우주의 스노우볼 | Mold: Snow Globe of Infinite Universe |
| 2111071 | 금형: 무한한 우주의 손거울 | Mold: Hand Mirror of Infinite Universe |
| 2111072 | 금형: 무한한 우주의 마법열쇠 | Mold: Magic Key of Infinite Universe |
| 2112000 | 메인 강화 회로 | Main Enhance Circuit |
| 2112007 | 강화 회로: 워리어 | Enhance Circuit: Warrior |
| 2112008 | 강화 회로: 레인저 | Enhance Circuit: Ranger |
| 2112009 | 강화 회로: 스트라이커 | Enhance Circuit: Striker |
| 2112010 | 강화 회로: 캐스터 | Enhance Circuit: Caster |
| 2112011 | 강화 회로: 서포터 | Enhance Circuit: Supporter |
| 2112012 | 강화 회로: 디펜더 | Enhance Circuit: Defender |
| 2114100 | 에픽 정령 선택 상자 (런칭) | Epic Soul Selection Chest (Launch) |
| 2114101 | 런칭 기념 패키지 선물 박스1 | Launch Celebration Pack Gift Chest 1 |
| 2114102 | 런칭 기념 패키지 선물 박스2 | Launch Celebration Pack Gift Chest 2 |
| 2114103 | 런칭 기념 패키지 선물 박스3 | Launch Celebration Pack Gift Chest 3 |
| 2114104 | 런칭 기념 패키지 선물 박스4 | Launch Celebration Pack Gift Chest 4 |
| 2140001 | 분수 | Fountain |
| 2140002 | 마녀의 솥 분수 | Witch's Pot Fountain |
| 2140003 | 초콜릿 분수 | Chocolate Fountain |
| 2140004 | 흑염룡 분수 | Black Flame Dragon Fountain |
| 2140101 | 벤치 | Bench |
| 2140102 | 구름 벤치 | Cloud Bench |
| 2140103 | 쿠키 벤치 | Cookie Bench |
| 2140104 | 전통 벤치 | Traditional Bench |
| 2140201 | 무대 | Stage |
| 2140202 | 아이돌 무대 | Idol Stage |
| 2140203 | 마술 쇼 무대 | Magic Show Stage |
| 2140301 | 양 울타리 | Sheep Fence |
| 2140302 | 오리 집 | Duck House |
| 2140303 | 텐트 모양 강아지 집 | Tent-Shaped Puppy House |
| 2140304 | 나뭇잎 캣 타워 | Leafy Cat Tower |
| 2140401 | 테이블 | Table |
| 2140402 | 만찬 테이블 | Dinner Table |
| 2140403 | 점성술 테이블 | Astrology Table |
| 2140601 | 정원 | Garden |
| 2140602 | 귀족의 정원 | Noble Garden |
| 2140603 | 장미 정원 | Rose Garden |
| 2140701 | 여신상 | Goddess Statue |
| 2140702 | 깃발을 든 여인상 | Statue of Woman With a Flag |
| 2140703 | 용기사 동상 | Dragon Knight Statue |
| 2140704 | 방주 모형 | Ark Model |
| 2140801 | 연못 | Pond |
| 2140802 | 연꽃 연못 | Lotus Pond |
| 2140803 | 요정의 연못 | Fairy Pond |
| 2140804 | 물레방아 연못 | Waterwheel Pond |
| 2140901 | 운동기구 | Workout Equipment |
| 2140902 | 짚인형 | Straw Dummy |
| 2140903 | 철갑옷 | Iron Armor |
| 2140904 | 샌드백 | Punching Bag |
| 2140905 | 목검세트(가로) | Wooden Sword Set (Horizontal) |
| 2140906 | 목검세트(세로) | Wooden Sword Set (Vertical) |
| 2141001 | 나무 | Tree |
| 2141002 | 단풍나무 | Maple Tree |
| 2141003 | 은행나무 | Ginkgo Tree |
| 2141004 | 사과나무 | Apple Tree |
| 2141005 | 오렌지나무 | Orange Tree |
| 2141006 | 블루베리나무 | Blueberry Tree |
| 2141050 | 벚나무 | Cherry Tree |
| 2141051 | 황금 사과 나무 | Golden Apple Tree |
| 2141052 | 솜사탕 나무 | Cotton Candy Tree |
| 2141053 | 새장이 걸린 나무 | Tree with a Birdcage |
| 2141054 | 둥실둥실 달콤 풍선 | Floating High Sweet Balloon |
| 2141055 | 스위츠 트리 | Sweets Tree |
| 2141101 | 가로등 | Street Lamp |
| 2141102 | 가로등(빨간색) | Street Lamp (Red) |
| 2141103 | 가로등(노란색) | Street Lamp (Yellow) |
| 2141104 | 가로등(파란색) | Street Lamp (Blue) |
| 2141105 | 가로등(녹색) | Street Lamp (Green) |
| 2141106 | 가로등(보라색) | Street Lamp (Purple) |
| 2141107 | 가로등(흰색) | Street Lamp (White) |
| 2141108 | 카카오 가로등 | Cacao Street Lamp |
| 2141201 | 목재 가로등 | Wooden Street Lamp |
| 2141202 | 목재 가로등(빨간색) | Wooden Street Lamp (Red) |
| 2141203 | 목재 가로등(노란색) | Wooden Street Lamp (Yellow) |
| 2141204 | 목재 가로등(파란색) | Wooden Street Lamp (Blue) |
| 2141205 | 목재 가로등(녹색) | Wooden Street Lamp (Green) |
| 2141206 | 목재 가로등(보라색) | Wooden Street Lamp (Purple) |
| 2141207 | 목재 가로등(흰색) | Wooden Street Lamp (White) |
| 2141301 | 노란 꽃 덤불 | Yellow Flower Bush |
| 2141302 | 빨간 꽃 덤불 | Red Flower Bush |
| 2141303 | 파란 꽃 덤불 | Blue Flower Bush |
| 2141304 | 보라 꽃 덤불 | Purple Flower Bush |
| 2141305 | 흰 꽃 덤불 | White Flower Bush |
| 2141401 | 가로수 | Street Tree |
| 2141501 | 짚더미 | Pile of Straw |
| 2141601 | 화분 | Flowerpot |
| 2141701 | 흰색 촛대 | White Candlestick |
| 2141702 | 빨간색 촛대 | Red Candlestick |
| 2141703 | 오렌지색 촛대 | Orange Candlestick |
| 2141704 | 녹색 촛대 | Green Candlestick |
| 2141705 | 파란색 촛대 | Blue Candlestick |
| 2141706 | 보라색 촛대 | Purple Candlestick |
| 2141707 | 민트색 촛대 | Mint Candlestick |
| 2141708 | 철제 촛대 | Iron Candlestick |
| 2141709 | 놋쇠 촛대 | Brass Candlestick |
| 2141710 | 황금 촛대 | Golden Candlestick |
| 2141711 | 로즈골드 촛대 | Rose Gold Candlestick |
| 2141712 | 달밤 전통 등잔 | Moonlight Traditional Oil Lamp |
| 2141801 | 인간 깃발 | Human Flag |
| 2141802 | 야수 깃발 | Beast Flag |
| 2141803 | 요정 깃발 | Fairy Flag |
| 2141804 | 불사 깃발 | Undead Flag |
| 2141805 | 천사 깃발 | Angel Flag |
| 2141806 | 악마 깃발 | Demon Flag |
| 2141807 | 솔레이 깃발1 | Solrey Flag 1 |
| 2141808 | 솔레이 깃발2 | Solrey Flag 2 |
| 2141809 | 솔레이 깃발3 | Solrey Flag 3 |
| 2141810 | 솔레이 깃발4 | Solrey Flag 4 |
| 2141901 | 메일박스(오렌지) | Mailbox (Orange) |
| 2141902 | 메일박스(노랑) | Mailbox (Yellow) |
| 2141903 | 메일박스(파랑) | Mailbox (Blue) |
| 2141904 | 메일박스(초록) | Mailbox (Green) |
| 2141905 | 메일박스(민트) | Mailbox (Mint) |
| 2141906 | 메일박스(핑크) | Mailbox (Pink) |
| 2141907 | 메일박스(보라) | Mailbox (Purple) |
| 2141908 | 메일박스(검정) | Mailbox (Black) |
| 2141909 | 메일박스(흰색) | Mailbox (White) |
| 2141910 | 메일박스(빨강) | Mailbox (Red) |
| 2142001 | 로드사인(갈색) | Road Sign (Brown) |
| 2142002 | 로드사인(밤색) | Road Sign (Nutbrown) |
| 2142003 | 로드사인(빨강) | Road Sign (Red) |
| 2142004 | 로드사인(오렌지) | Road Sign (Orange) |
| 2142005 | 로드사인(노랑) | Road Sign (Yellow) |
| 2142006 | 로드사인(초록) | Road Sign (Green) |
| 2142007 | 로드사인(보라) | Road Sign (Purple) |
| 2142008 | 로드사인(민트) | Road Sign (Mint) |
| 2142009 | 로드사인(흰색) | Road Sign (White) |
| 2142010 | 로드사인(핑크) | Road Sign (Pink) |
| 2142011 | 로드사인(파랑) | Road Sign (Blue) |
| 2142101 | 아치펜스(대리석) | Arch Fence (Marble) |
| 2142102 | 아치펜스(벽돌) | Arch Fence (Brick) |
| 2142103 | 아치펜스(철제) | Arch Fence (Iron) |
| 2142104 | 아치펜스(빨강) | Arch Fence (Red) |
| 2142105 | 아치펜스(파랑) | Arch Fence (Blue) |
| 2142106 | 아치펜스(초록) | Arch Fence (Green) |
| 2142107 | 아치펜스(보라) | Arch Fence (Purple) |
| 2142108 | 아치펜스(핑크) | Arch Fence (Pink) |
| 2142109 | 아치펜스(흰색) | Arch Fence (White) |
| 2142110 | 아치펜스(민트) | Arch Fence (Mint) |
| 2142111 | 꼬마 담장 | Kiddy Wall |
| 2142112 | 파티션 로프 | Rope Partition |
| 2142113 | 꼬마 담장(보급형) | Kiddy Wall (Economy) |
| 2142201 | 아치(대리석) | Arch (Marble) |
| 2142202 | 아치(벽돌) | Arch (Brick) |
| 2142203 | 아치(철제) | Arch (Iron) |
| 2142204 | 아치(빨강) | Arch (Red) |
| 2142205 | 아치(파랑) | Arch (Blue) |
| 2142206 | 아치(초록) | Arch (Green) |
| 2142207 | 아치(보라) | Arch (Purple) |
| 2142208 | 아치(핑크) | Arch (Pink) |
| 2142209 | 아치(흰색) | Arch (White) |
| 2142210 | 아치(민트) | Arch (Mint) |
| 2142211 | 이리오너라 전통 대문 | Traditional Gates |
| 2142301 | 바닥타일(흰색) | Floor Tile (White) |
| 2142302 | 바닥타일(갈색) | Floor Tile (Brown) |
| 2142303 | 우물마루 바닥 타일 A | Checkered Floor Tile A |
| 2142304 | 우물마루 바닥 타일 B | Checkered Floor Tile B |
| 2142305 | 전통 문양 바닥 타일 A | Traditional Floor Tile A |
| 2142306 | 전통 문양 바닥 타일 B | Traditional Floor Tile B |
| 2142307 | 초코 타일 A | Choco Tile A |
| 2142308 | 초코 타일 B | Choco Tile B |
| 2142309 | 바삭 타일 | Crunchy Tile |
| 2142310 | 꽃길 타일 | Flowery Tile |
| 2142311 | 잔디 타일 | Grass Tile |
| 2142312 | 모래 타일 | Sand Tile |
| 2142313 | 모래 타일(직선) | Sand Tile (Straight) |
| 2142314 | 모래 타일(외곽) | Sand Tile (Outer) |
| 2142315 | 모래 타일(모서리) | Sand Tile (Corner) |
| 2142316 | 웨딩 카펫(모서리1) | Wedding Carpet (Corner 1) |
| 2142317 | 웨딩 카펫(외곽선) | Wedding Carpet (Outline) |
| 2142318 | 웨딩 카펫(모서리2) | Wedding Carpet (Corner 2) |
| 2142319 | 웨딩 카펫(중앙) | Wedding Carpet (Center) |
| 2142401 | 천하대장군 여우 장승 | Fox World General Jangseung |
| 2142402 | 지하여장군 여우 장승 | Fox Underground General Jangseung |
| 2142501 | 별빛 보료 | Starlight Mattress |
| 2142601 | 전통 창호 파티션 | Traditional Korean Paper Partition |
| 2142602 | 팬시 초코 파티션 | Fancy Choco Partition |
| 2142603 | 전통 창호 파티션(보급형) | Traditional Korean Paper Partition (Economy) |
| 2142701 | 전통문양 러그 | Traditional Rug |
| 2142801 | 한 상 가득 자개소반 세트 | Full Meal Portable Table Set |
| 2142901 | 과유불급 금은보화 수레 | Overfilled Treasure Cart |
| 2143001 | 달의 누각 | Moon Castle |
| 2143002 | 매화 분재 | Potted Apricot Tree |
| 2143101 | 스낵 카트 | Snack Cart |
| 2143102 | 티켓 부스 | Ticket Booth |
| 2143103 | 순정 메리 고 라운드 | Pure Love Merry-Go-Round |
| 2143104 | 문구 초콜릿 | Chocolate Text |
| 2143105 | 홀로 초코 대관람차 | Chocolate Ferris Wheel |
| 2143106 | 티라미수 테이블 | Tiramisu Table |
| 2143107 | 롤케이크 스툴 | Roll Cake Stool |
| 2143201 | 숲속의 나무집 | Forest Tree House |
| 2143202 | 든든 그루터기 | Stout Tree Stump |
| 2143203 | 잠자는 여우 | Sleeping Fox |
| 2143204 | 흔들 해먹 그네 | Hammock Swing |
| 2143205 | 나무줄기 화분 | Stem Pot |
| 2143301 | 방과 후 체육 창고 | After-School Gym Storage |
| 2143302 | 칠판 | Blackboard |
| 2143303 | 철제 캐비닛(그린) | Metal Cabinet (Green) |
| 2143304 | 철제 캐비닛(레드) | Metal Cabinet (Red) |
| 2143305 | 교실 벽 | Classroom Wall |
| 2143306 | 교실 창가 벽 | Classroom Windowed Wall |
| 2143307 | 모범생 책상 세트 | Scholar's Desk Set |
| 2143308 | 꾸러기 책상 세트 | Troublemaker's Desk Set |
| 2143309 | 교탁 | Lecture Table |
| 2143310 | 교실 기둥 | Classroom Pillar |
| 2143311 | 축구 골대 | Goalpost |
| 2143312 | 일반 자판기 | Normal Vending Machine |
| 2143313 | 스낵 자판기 | Snack Vending Machine |
| 2143401 | 메리 유 웨딩 스테이지 | Marry You Wedding Stage |
| 2143402 | 웨딩 가제보 | Wedding Gazebo |
| 2143403 | 메리 미 그랜드 피아노 | Marry Me Grand Piano |
| 2143404 | 웨딩 테이블 | Wedding Table |
| 2143405 | 웨딩 체어1 | Wedding Chair 1 |
| 2143406 | 웨딩 체어2 | Wedding Chair 2 |
| 2143407 | 러블리 웨딩 케이크 | Lovely Wedding Cake |
| 2143408 | 블룸 플라워 울타리 | Blooming Flower Fence |
| 2143501 | 비비안의 칵테일 바 | Vivienne's Cocktail Bar |
| 2143502 | 터틀 풀장 | Turtle Pool |
| 2143503 | 리조트 카트 | Resort Cart |
| 2143504 | 스윔스파 | Swim Spa |
| 2143505 | 라탄 과일 바구니 | Rattan Fruit Basket |
| 2143506 | 야자수 가로등 | Palm Street Lamp |
| 2143507 | 튜브 대여소 | Floaty Rental |
| 2143508 | 캐노피 베드 | Canopy Bed |
| 2143509 | 썸머 파티션 | Summer Partition |
| 2143510 | 파라솔 테이블 | Parasol Table |
| 2143511 | 선베드 | Sunbed |
| 2143512 | 해먹 흔들의자 | Hammock Rocker |
| 2143513 | 썸머 텐트 | Summer Tent |
| 2143601 | 홍란의 해변 모래성 | Honglan's Sandcastle |
| 2143602 | 비치발리볼 코트 | Beach Volleyball Court |
| 2143603 | 해변 보트 식당 | Beach Boat Restaurant |
| 2143604 | 서핑보드 대여소 | Surfboard Rental |
| 2143605 | 해변 모래 타일(직선) | Beach Sand Tile (Straight) |
| 2143606 | 해변 모래 타일(외곽) | Beach Sand Tile (Outer) |
| 2143607 | 해변 모래 타일 | Beach Sand Tile |
| 2143608 | 해변 모래 타일(내곽) | Beach Sand Tile (Inner) |
| 2143609 | 바다 타일 | Sea Tile |
| 2143610 | 모험 뗏목 | Adventure Raft |
| 2143611 | 조가비 분수 | Shall Fountain |
| 2143612 | 해변 매트 | Beach Mat |
| 2143613 | 뱃머리 보물상자 | Bow Treasure Box |
| 2143614 | 산호 바위 | Coral Rock |
| 2143615 | 해파리 조명등 | Jellyfish Light |
| 2143616 | 아기 해파리 조명등 | Baby Jellyfish Light |
| 2143617 | 해변 이정표 | Beach Sign |
| 2143701 | 달밤의 궁중 다과회 | Midnight Court Refreshments |
| 2143702 | 아키의 명상정원 | Aki's Meditation Garden |
| 2143703 | 월묘의 달떡 절구 | Moon Rice Cake Grinding Bowl |
| 2143704 | 달밤의 궁중악단 | Midnight Court Band |
| 2143705 | 정원 돌길 타일 | Garden Stone Tile |
| 2143706 | 전통 가을 연못 | Autumn Pond |
| 2143707 | 궁중 벽보판 | Court Board |
| 2143708 | 궁궐 담벼락 | Palace Wall |
| 2143709 | 궁궐 관문 | Palace Gate |
| 2143710 | 도란도란 장독대 | Crock Platform |
| 2143711 | 보름달 풍등 | Full Moon Lantern |
| 2143712 | 주렁주렁 감나무 | Persimmon Tree |
| 2143713 | 달안개 전통 향로 | Moon Fog Incense Burner |
| 2143801 | 숲속의 그림자 극장 | Forest Shadow Theater |
| 2143802 | 마녀의 연금 솥단지 | Witch's Alchemy Pot |
| 2143803 | 장미 늑대 철창 | Wolf Cage With Roses |
| 2143804 | 리젤로테의 흑백합 정원 | Lizelotte's Black Lily Garden |
| 2143805 | 오싹오싹 테이블 | Spooky Table |
| 2143806 | 오싹오싹 의자 | Spooky Chair |
| 2143807 | 철제 펜스 | Iron Fence |
| 2143808 | 철제 대문 | Iron Gates |
| 2143809 | 기묘한 나무 | Strange Tree |
| 2143810 | 어둠 속 가로등 | Spooky Street Lamp |
| 2143811 | 음산한 극장 매표소 | Spooky Theater Box Office |
| 2143812 | 흑백합 화분 | Black Lily Flowerpot |
| 2143813 | 묘지기 유령 | Grave Keeper Ghost |
| 2143901 | 눈길을 달리는 썰매 | Snow Sleigh |
| 2143902 | 캐서린의 예배당 | Catherine's Chapel |
| 2143903 | 푹신푹신 거대 곰인형 | Giant Fluffy Teddy Bear |
| 2143904 | 찬란한 기도의 트리 | Radiant Prayer Tree |
| 2143905 | 눈 덮인 벽돌 타일 | Snow-Covered Brick Tiles |
| 2143906 | 눈 녹은 벽돌 타일 | Snow-Thawed Brick Tiles |
| 2143907 | 반짝반짝 아치 | Dazzling Arch |
| 2143908 | 두근두근 선물 꾸러미 | Suspenseful Gift Bundle |
| 2143909 | 반짝반짝 선물 꾸러미 | Glamorous Gift Bundle |
| 2143910 | 행복한 눈사람 | Happy Snowman |
| 2143911 | 소원 가득 양말 | Wish-Filled Stocking |
| 2143912 | 눈 뭉치 | Snowballs |
| 2143913 | 꼬마 눈오리 | Snow Duckling |
| 2143914 | 성탄 양초 | Christmas Candle |
| 2143915 | 성야의 벤치 | Pew Bench of Starry Night |
| 2144001 | 크루즈 선교 | Cruise Bridge |
| 2144002 | 클라우디아의 피뢰탑 | Claudia's Lightning Tower |
| 2144003 | 럭셔리 풀장 | Luxury Pool |
| 2144004 | 별빛 항해사 | Starlight Voyager |
| 2144005 | 대리석 타일 | Marble Tile |
| 2144006 | 샴페인 타워 | Champagne Tower |
| 2144007 | 그랜드 하프 | Grand Harp |
| 2144008 | 럭셔리 펜스 | Luxury Fence |
| 2144009 | 샹들리에 스탠드 | Chandelier Stand |
| 2144101 | 로맨틱 라이브 스테이지 | Romantic Live Stage |
| 2144102 | 앤티크 매직 턴테이블 | Antique Magic Turntable |
| 2144103 | 스위트 피팅룸 | Sweet Fitting Room |
| 2144104 | 소연의 초콜릿 팩토리 | Xiaolian's Chocolate Factory |
| 2144105 | 스위트 테이블 | Sweet Table |
| 2144106 | 스위트 소파 | Sweet Sofa |
| 2144107 | 완벽한 트레이 | Perfect Tray |
| 2144108 | 카페 진열대 | Cafe Display Case |
| 2144109 | 봉봉 쇼콜라 | Bonbon Chocolat |
| 2144201 | 푸른 하늘 조례대 | Blue Sky Lectern |
| 2144202 | 폭신폭신 생태 사육장 | Fuzzy and Fluffy Critter Quarters |
| 2144203 | 나른한 오후의 양호실 | Lazy Afternoon Infirmary |
| 2144204 | 유리아의 학생회실 | Yuria's Student Council Office |
| 2144205 | 음수대 | Water Fountain |
| 2144206 | 소각로 | Waste Incinerator |
| 2144207 | 시계탑 | Clock Tower |
| 2144208 | 학교 교문 | School Gate |
| 2144209 | 학교 담벼락 | School Wall |
| 2144210 | 벚나무 벤치 | Cherry Tree Bench |
| 2144211 | 벽돌 화단 | Brick Flower Bed |
| 2144301 | 축제 무대 | Festival Stage |
| 2144302 | 거대 인형 등불 | Giant Cat Lantern |
| 2144303 | 연못 위 다리 | Bridge over a Pond |
| 2144304 | 축제 가마 | Festival Palanquin |
| 2144305 | 사격 노점 | Shooting Booth |
| 2144306 | 가면 노점 | Mask Booth |
| 2144307 | 낚시 노점 | Fishing Booth |
| 2144308 | 문어빵 노점 | Takoyaki Booth |
| 2144309 | 빙수 노점 | Shaved Ice Booth |
| 2144310 | 간식 노점 | Snack Booth |
| 2144311 | 단책 | Tanzaku |
| 2144312 | 수국 화단 | Hydrangea Flowerbed |
| 2144313 | 나팔꽃 벤치 | Morning Glory Bench |
| 2144314 | 대나무 평상 | Bamboo Platform |
| 2144315 | 축제 가로등 | Festival Street Lamp |
| 2144316 | 축제 아치 | Festival Arch |
| 2144401 | 신부 대기실 | Bridal Lounge |
| 2144402 | 웨딩 스튜디오 | Wedding Studio |
| 2144403 | 완벽한 프러포즈 | Perfect Proposal |
| 2144404 | 비올레트의 새장 침실 | Violette's Birdcage Bedroom |
| 2144405 | 웨딩 마차 | Wedding Carriage |
| 2144406 | 레드 카펫(직선) | Red Carpet (Straight) |
| 2144407 | 레드 카펫 | Red Carpet |
| 2144408 | 웨딩 포토 스탠드 | Framed Wedding Photo |
| 2144409 | 들러리 인형 | Bridesmaid Plushie |
| 2144410 | 하트 욕조 | Heart Bathtub |
| 2144411 | 웨딩 벤치 | Wedding Bench |
| 2144412 | 웨딩 아치 | Wedding Arch |
| 2144501 | 허수아비 귀신 | Ghostly Scarecrows |
| 2144502 | 이름 없는 무덤 | Nameless Grave |
| 2144503 | 잊혀진 성당 | Forgotten Cathedral |
| 2144504 | 이브의 기이한 저택 | Eve's Eccentric Mansion |
| 2144505 | 버려진 거울 | Discarded Mirror |
| 2144506 | 낯선 자의 불빛 | Stranger's Light |
| 2144507 | 저주받은 나무 | Cursed Tree |
| 2144508 | 깊은 우물 | Deep Well |
| 2144509 | 숲의 오두막 | Forest Cabin |
| 2144510 | 나무 판자 울타리 | Wooden Fence |
| 2144511 | 발자국 타일 | Footstep Tile |
| 2144601 | 서커스 분장실 | Circus Dressing Room |
| 2144602 | 서커스 마차 | Circus Carriage |
| 2144603 | 아슬아슬 칼 던지기 | Thrilling Knife Throwing |
| 2144604 | 루테의 판타스틱 쇼타임 | Lute's Fantastic Show Time |
| 2144605 | 터진다! 대포 | Boom! Cannon |
| 2144606 | 알록달록 풍선 카트 | Colorful Balloon Cart |
| 2144607 | 사자 포토존 | Lion Photo Spot |
| 2144608 | 환영해요! 풍선 인형 | Welcoming Balloon Figure |
| 2144609 | 체크무늬 타일 | Checkerboard Tile |
| 2144610 | 파이어 링 | Ring of Fire |
| 2144611 | 깜짝 상자 | Jack-In-The-Box |
| 2144612 | 서커스 열기구 | Circus Hot Air Balloon |
| 2144701 | 행복을 나르는 기차 | The Happiness Locomotive |
| 2144702 | 장난감 공장 | Toy Factory |
| 2144703 | 꿈 가득 패키지 | Dreamful Package |
| 2144704 | 라리마의 눈 내린 썰매 광장 | Larimar's Snowy Sledding Plaza |
| 2144705 | 녹아버린 눈사람 | Melted Snowman |
| 2144706 | 부쉬 드 노엘 | Yule Log |
| 2144707 | 칼라르식 트리 | Chalar-Style Christmas Tree |
| 2144708 | 크리스마스 노움 | Christmas Gnomes |
| 2144709 | 달콤한 과자집 | Sweet Gingerbread House |
| 2144710 | 새하얀 발자국 | White Footprints |
| 2144711 | 장난감 병정 | Toy Soldier |
| 2144801 | 동백 부티크 | Camellia Boutique |
| 2144802 | 다 함께 놀이마당 | Life-Size Game Board |
| 2144803 | 축제 단상 | Festival Podium |
| 2144804 | 캐서린(광휘)의 사랑방 | Catherine (Radiance)'s Parlor |
| 2144805 | 식혜 분수 | Sweet Rice Drink Fountain |
| 2144806 | 동백 테이블 | Camellia Table |
| 2144807 | 동백 의자 | Camellia Chair |
| 2144808 | 화훼도 병풍 | Floral Motif Folding Screen |
| 2144809 | 동백 좌등 | Camellia Lantern Stand |
| 2144810 | 이채 타일 | Vibrant Tile |
| 2144811 | 동백나무 | Camellia Tree |
| 2144812 | 가야금 | Gayageum |
| 2144813 | 떡 테이블 | Rice Cake Table |
| 2144820 | 로제(홍염)의 심상의 시계탑 | Rose (Prominence)'s Imaginary World Clock Tower |
| 2144821 | 홍란(무쌍)의 산속 쉼터 | Honglan (Peerless)'s Mountain Refuge |
| 2144822 | 지호(미르)의 대영주 옥좌 | Jiho (Mir)'s High Seat of the Great Lord |
| 2144823 | 르네(백은)의 은빛 성 | Renee (Argent)'s Silver Castle |
| 2144824 | 메피스토펠레스(여명)의 구원의 방주 | Mephistopheles (Dawn)'s Ark of Salvation |
| 2144825 | 미리암(잔영)의 전투훈련실 | Miriam (Afterimage)'s Combat Training Room |
| 2144826 | 가넷의 카지노 | Garnet's Casino |
| 2144827 | 셰리의 해적선 | Cherrie's Pirate Ship |
| 2144901 | 유리 온실 | Glass Greenhouse |
| 2144902 | 티타임 테이블 | Tea Table |
| 2144903 | 럭셔리한 귀빈실 | Opulent Guest Room |
| 2144904 | 린지(타나토스)의 서재 | Linzy (Thanatos)'s Study |
| 2144905 | 메이드의 주방 | Maids' Kitchen |
| 2144906 | 정원 토피어리 | Garden Topiary |
| 2144907 | 실베스터 조이 3세의 샘 | King Sylvester Joey III's Basin |
| 2144908 | 티타임 트롤리 | Tea Trolley |
| 2144909 | 엘레강스 바닥 타일 | Elegant Floor Tile |
| 2144910 | 메이드의 빨래터 | Maids' Laundry Area |
| 2144911 | 정원 가로등 | Garden Street Lamp |
| 2144912 | 정원 담벼락 | Garden Wall |
| 2144913 | 정원 대문 | Garden Gate |
| 2145001 | 안전요원 망루 | Lifeguard Tower |
| 2145002 | 정글 폭포 | Jungle Waterfall |
| 2145003 | 바위섬 항구 | Rock Island Port |
| 2145004 | 니아의 오두막 | Nia's Cabin |
| 2145005 | 카누 | Canoe |
| 2145006 | 에메랄드 바다 타일 | Emerald Ocean Tile |
| 2145007 | 꽃잎 해변 모래 타일(직선) | Petal Beach Sand Tile (Straight) |
| 2145008 | 꽃잎 해변 모래 타일(외곽) | Petal Beach Sand Tile (Outer) |
| 2145009 | 꽃잎 해변 모래 타일 | Petal Beach Sand Tile |
| 2145010 | 꽃잎 해변 모래 타일(내곽) | Petal Beach Sand Tile (Inner) |
| 2145011 | 음료 디스펜서 바 | Beverage Station |
| 2145012 | 대형 도마뱀 튜브 | Large Lizard Pool Tube |
| 2145013 | 야자수 | Palm Tree |
| 2145014 | 꽃이 핀 야자수 | Blooming Palm Tree |
| 2145015 | 바베큐 그릴 | Barbecue Grill |
| 2145016 | 어탁 | Fish Rubbing |
| 2145017 | 라이브 세션 밴드 | Live Band |
| 2145018 | 아이돌의 포토존 | Idol Photo Spot |
| 2145019 | 뮤직비디오 촬영 세트 | Music Video Filming Set |
| 2145020 | 벨레드의 스페셜 스테이지 | Beleth's Special Stage |
| 2145021 | 콘서트 티켓 부스 | Concert Ticket Booth |
| 2145022 | 무대 의상 전시대 | Stage Costume Display Stand |
| 2145023 | 굿즈 팝업 스토어 | Pop Up Merch Store |
| 2145024 | 댄스 플로어 | Dance Floor |
| 2145025 | 가로등 배너 | Street Lamp Banner |
| 2145026 | 무대 바닥 타일 | Stage Platform Tile |
| 2145027 | 콘서트장 입구 | Concert Hall Entrance |
| 2145028 | 자이언트 붐박스 | Giant Boombox |
| 2145029 | 공연장 좌석 | Concert Hall Seating |
| 2145030 | 궁중 음악 스테이지 | Palace Music Stage |
| 2145031 | 거대 당고 | Giant Dango |
| 2145032 | 축제용 떡국 | Festival Rice Cake Soup |
| 2145033 | 아폴리온의 새해 운세 뽑기 | Apollyon's New Year's Fortune Draw |
| 2145034 | 연날리기 | Kite Flying |
| 2145035 | 소원판 | Wish Plaque |
| 2145036 | 구원자 등불 | Savior's Lamp |
| 2145037 | 잔칫상 | Festival Banquet |
| 2145038 | 새해 음식 상점 | New Year's Food Shop |
| 2145039 | 복주머니 | Lucky Pouch |
| 2147001 | 메피스토펠레스 석상 | Mephistopheles Statue |
| 2147002 | 탈리아 석상 | Talia Statue |
| 2147003 | 재클린 석상 | Jacqueline Statue |
| 2147004 | 홍란 석상 | Honglan Statue |
| 2147005 | 린지 석상 | Linzy Statue |
| 2147006 | 아야메 석상 | Ayame Statue |
| 2147007 | 니콜 석상 | Nicole Statue |
| 2147008 | 비올레트 석상 | Violette Statue |
| 2147009 | 구원자 석상 | Savior Statue |
| 2147010 | 아드리안 석상 | Adrianne Statue |
| 2147011 | 제이드 석상 | Jade Statue |
| 2147012 | 클로이 석상 | Chloe Statue |
| 2147013 | 프림 석상 | Prim Statue |
| 2147014 | 리젤로테 석상 | Lizelotte Statue |
| 2147015 | 순이 석상 | Soonie Statue |
| 2147016 | 아키 석상 | Aki Statue |
| 2147017 | 나이아 석상 | Naiah Statue |
| 2147018 | 미카 석상 | Mica Statue |
| 2147019 | 시하 석상 | Seeha Statue |
| 2147020 | 클라우디아 석상 | Claudia's Statue |
| 2147021 | 니니 석상 | Nini Statue |
| 2147022 | 페트라 석상 | Petra Statue |
| 2147023 | 클레르 석상 | Claire Statue |
| 2147024 | 클라라 석상 | Clara Statue |
| 2147100 | 1주년 기념 케이크 | 1st Anniversary Cake |
| 2147101 | 산달폰 | Sandalphon |
| 2147102 | 자프키엘 | Zafkiel |
| 2147103 | 2주년 기념 케이크 | 2nd Anniversary Cake |
| 2147104 | 파격적인 입간판 | Scandalous Sign |
| 2147105 | 3주년 기념 케이크 | 3rd Anniversary Cake |
| 2148001 | 소형 잡화점 | Small General Store |
| 2148002 | 중형 잡화점 | Medium General Store |
| 2148003 | 대형 잡화점 | Large General Store |
| 2148011 | 소형 플라워숍 | Small Flower Shop |
| 2148012 | 중형 플라워숍 | Medium Flower Shop |
| 2148013 | 대형 플라워숍 | Large Flower Shop |
| 2148021 | 소형 베이커리 | Small Bakery |
| 2148022 | 중형 베이커리 | Medium Bakery |
| 2148023 | 대형 베이커리 | Large Bakery |
| 2148031 | 소형 레스토랑 | Small Restaurant |
| 2148032 | 중형 레스토랑 | Medium Restaurant |
| 2148033 | 대형 레스토랑 | Large Restaurant |
| 2148041 | 소형 카페 | Small Cafe |
| 2148042 | 중형 카페 | Medium Cafe |
| 2148043 | 대형 카페 | Large Cafe |
| 2148051 | 소형 도서관 | Small Library |
| 2148052 | 중형 도서관 | Medium Library |
| 2148053 | 대형 도서관 | Large Library |
| 2148061 | 소형 성당 | Small Cathedral |
| 2148062 | 중형 성당 | Medium Cathedral |
| 2148063 | 대형 성당 | Large Cathedral |
| 2148071 | 소형 아틀리에 | Small Atelier |
| 2148072 | 중형 아틀리에 | Medium Atelier |
| 2148073 | 대형 아틀리에 | Large Atelier |
| 2148081 | 소형 대장간 | Small Forge |
| 2148082 | 중형 대장간 | Medium Forge |
| 2148083 | 대형 대장간 | Large Forge |
| 2148091 | 유물 발굴터 | Artifact Excavation Site |
| 2148092 | 기억의 돌 | Stone of Memory |
| 2148093 | 고대 유물 발굴터 | Ancient Artifact Excavation Site |
| 2148094 | 고대 기억의 돌 | Stone of Ancient Memory |
| 2148095 | 마나석 발굴터 | Manastone Dig Site |
| 2148096 | 강화석 정제소 | Enhance Stone Refinery |
| 2149000 | 영주의 저택 | Lord's Manor |
| 2149001 | 용맹의 소형 저택 | Small Manor of Valor |
| 2149002 | 신념의 소형 저택 | Small Manor of Belief |
| 2149003 | 불굴의 소형 저택 | Small Manor of Indomitability |
| 2149011 | 용맹의 중형 저택 | Medium Manor of Valor |
| 2149012 | 신념의 중형 저택 | Medium Manor of Belief |
| 2149013 | 불굴의 중형 저택 | Medium Manor of Indomitability |
| 2149021 | 용맹의 대형 저택 | Large Manor of Valor |
| 2149022 | 신념의 대형 저택 | Large Manor of Belief |
| 2149023 | 불굴의 대형 저택 | Large Manor of Indomitability |
| 2149501 | 레이싱 서킷 시작 지점 | Race Track Starting Point |
| 2149502 | 레이싱 서킷 종료 지점 | Race Track Finish Point |
| 2149503 | 레이싱 서킷 중간 지점1 | Race Track Mid-Route Point 1 |
| 2149504 | 레이싱 서킷 중간 지점2 | Race Track Mid-Route Point 2 |
| 2149505 | 레이싱 서킷 중간 지점3 | Race Track Mid-Route Point 3 |
| 2149506 | 레이싱 서킷 중간 지점4 | Race Track Mid-Route Point 4 |
| 2149507 | 레이싱 서킷 중간 지점5 | Race Track Mid-Route Point 5 |
| 2149601 | 눈썰매 (플레이어 용) | Snow Sled (for Player) |
| 2149602 | 눈썰매 (정령 용) | Snow Sled (for Souls) |
| 2149603 | 오리배 (플레이어 용) | Duck Boat (for Player) |
| 2149604 | 오리배 (정령 용) | Duck Boat (for Souls) |
| 2149605 | 카트 (플레이어 용) | Go-Kart (for Player) |
| 2149606 | 카트 (정령 용) | Go-Kart (for Souls) |
| 2150000 | 발전의 재 | Ash of Progress |
| 2210001 | 메피스토펠레스의 유물, 방주 메타트론의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Mephistopheles. The Memory of Metatron.<br>Used to obtain or ascend Artifacts. |
| 2210002 | 벨레드의 유물, 방주 자드키엘의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Beleth. The Memory of Ark Zadkiel.<br>Used to obtain or ascend Artifacts. |
| 2210003 | 클레르의 유물, 잔다르크의 깃발의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Claire. The Memory of the Flag of Jeanne d'Arc.<br>Used to obtain or ascend Artifacts. |
| 2210004 | 아키의 유물, 무라마사의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Aki. The Memory of Muramasa.<br>Used to obtain or ascend Artifacts. |
| 2210005 | 제이드의 유물, 미다스의 손의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Jade. The Memory of the Hand of Midas.<br>Used to obtain or ascend Artifacts. |
| 2210006 | 린지의 유물, 프라가라흐의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Linzy. The Memory of Fragarach.<br>Used to obtain or ascend Artifacts. |
| 2210007 | 나오미의 유물, 간디바의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Naomi. The Memory of Gandiva.<br>Used to obtain or ascend Artifacts. |
| 2210008 | 사쿠요의 유물, 요시모토 사몬지의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Sakuyo. The Memory of Yoshimoto Samonji.<br>Used to obtain or ascend Artifacts. |
| 2210009 | 캐서린의 유물, 성해포의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Catherine. The Memory of a Holy Shroud.<br>Used to obtain or ascend Artifacts. |
| 2210010 | 셰리의 유물, 신편귀독주의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Cherrie. The Memory of Shinpen Kidoku.<br>Used to obtain or ascend Artifacts. |
| 2210011 | 도라의 유물, 골디락스의 빈 그릇의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Dora. The Memory of the Bowl of Goldilocks.<br>Used to obtain or ascend Artifacts. |
| 2210012 | 홍란의 유물, 청룡언월도의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Honglan. The Memory of the Green Dragon Crescent Blade.<br>Used to obtain or ascend Artifacts. |
| 2210013 | 순이의 유물, 거북선의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Soonie. The Memory of a Turtle Ship.<br>Used to obtain or ascend Artifacts. |
| 2210014 | 아이라의 유물, 다그다의 곤봉의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Aira. The Memory of Dagda's Club.<br>Used to obtain or ascend Artifacts. |
| 2210015 | 시하의 유물, 칼리오페의 소리굽쇠의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Seeha. The Memory of the Tuning Fork of Calliope.<br>Used to obtain or ascend Artifacts. |
| 2210016 | 미카의 유물, 오르페우스의 리라의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Mica. The Memory of the Lyre of Orpheus.<br>Used to obtain or ascend Artifacts. |
| 2210017 | 메릴의 유물, 레메게톤의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Meryl. The Memory of the Lemegeton.<br>Used to obtain or ascend Artifacts. |
| 2210018 | 플린의 유물, RPG-7의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Flynn. The Memory of the RPG-7.<br>Used to obtain or ascend Artifacts. |
| 2210019 | 타샤의 유물, 투탕카멘의 가면의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Tasha. The Memory of Tutankhamun's Mask.<br>Used to obtain or ascend Artifacts. |
| 2210020 | 하루의 유물, 쿠투네시르카의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Haru. The Memory of Kutune Shirka.<br>Used to obtain or ascend Artifacts. |
| 2210021 | 루테의 유물, 모글레이의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Lute. The Memory of Murgleys.<br>Used to obtain or ascend Artifacts. |
| 2210022 | 클라라의 유물, 코르누코피아의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Clara. The Memory of a Cornucopia.<br>Used to obtain or ascend Artifacts. |
| 2210023 | 에리카의 유물, 엘릭서의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Erika. The Memory of the Elixir of Life.<br>Used to obtain or ascend Artifacts. |
| 2210024 | 이나의 유물, 하멜른의 피리의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Ina. The Memory of Hameline's Flute.<br>Used to obtain or ascend Artifacts. |
| 2210025 | 르네의 유물, 누아다의 의수의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Renee. The Memory of Nuada Airgetlám.<br>Used to obtain or ascend Artifacts. |
| 2210026 | 탈리아의 유물, 테트라비블로스의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Talia. The Memory of Tetrabiblos.<br>Used to obtain or ascend Artifacts. |
| 2210027 | 칸나의 유물, 큐피드의 화살의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Kanna. The Memory of Cupid's Arrow.<br>Used to obtain or ascend Artifacts. |
| 2210028 | 이디스의 유물, 바리사다의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Edith. The Memory of Balisarda.<br>Used to obtain or ascend Artifacts. |
| 2210029 | 니콜의 유물, 페일노트의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Nicole. The Memory of Failnaught.<br>Used to obtain or ascend Artifacts. |
| 2210030 | 비비안의 유물, 에메랄드 타블렛의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Vivienne. The Memory of an Emerald Tablet.<br>Used to obtain or ascend Artifacts. |
| 2210031 | 미리암의 유물, 7발의 마탄의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Miriam. The Memory of the Seventh Bullet.<br>Used to obtain or ascend Artifacts. |
| 2210032 | 클로이의 유물, 아이기스의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Chloe. The Memory of the Aegis.<br>Used to obtain or ascend Artifacts. |
| 2210033 | 나이아의 유물, 잔트만의 꿈가루의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Naiah. The Memory of the Dust of Sandman.<br>Used to obtain or ascend Artifacts. |
| 2210034 | 비올레트의 유물, 판도라의 상자의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Violette. The Memory of Pandora's Box.<br>Used to obtain or ascend Artifacts. |
| 2210035 | 가넷의 유물, 롱기누스의 창의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Garnet. The Memory of Longinus.<br>Used to obtain or ascend Artifacts. |
| 2210036 | 레베카의 유물, 게이 보의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Rebecca. The Memory of Gáe Buide.<br>Used to obtain or ascend Artifacts. |
| 2210037 | 멜피스의 유물, 아야무르의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Melfice. The Memory of Ayamur.<br>Used to obtain or ascend Artifacts. |
| 2210038 | 브라이스의 유물, 야그루시의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Bryce. The Memory of Yagrush.<br>Used to obtain or ascend Artifacts. |
| 2210039 | 프림의 유물, 카두세우스의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Prim. The Memory of the Caduceus.<br>Used to obtain or ascend Artifacts. |
| 2210040 | 재클린의 유물, 게 볼그의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Jacqueline. The Memory of Gáe Bulg.<br>Used to obtain or ascend Artifacts. |
| 2210041 | 벨라나의 유물, 클라렌트의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Velanna. The Memory of Clarent.<br>Used to obtain or ascend Artifacts. |
| 2210042 | 에루샤의 유물, 바즈라의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Erusha. The Memory of the Vajra.<br>Used to obtain or ascend Artifacts. |
| 2210043 | 페트라의 유물, 반혼향의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Petra. The Memory of the Spirit-Calling Incense.<br>Used to obtain or ascend Artifacts. |
| 2210044 | 니니의 유물, 호신부의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Nini. The Memory of an Amulet of Protection.<br>Used to obtain or ascend Artifacts. |
| 2210045 | 클라우디아의 유물, 묠니르의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Claudia. The Memory of Mjölnir.<br>Used to obtain or ascend Artifacts. |
| 2210046 | 아드리안의 유물, 아스칼론의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Adrianne. The Memory of Ascalon.<br>Used to obtain or ascend Artifacts. |
| 2210047 | 유리아의 유물, 다섯 번째 나팔의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Yuria. The memory of the Fifth Trumpet.<br>Used to obtain or ascend Artifacts. |
| 2210048 | 라리마의 유물, 오시리스의 지팡이의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Larimar. The Memory of Osiris's Staff.<br>Used to obtain or ascend Artifacts. |
| 2210049 | 리젤로테의 유물, 궁니르의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Lizelotte. The Memory of Gungnir.<br>Used to obtain or ascend Artifacts. |
| 2210050 | 아야메의 유물, 츠쿠요미의 백동거울의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Ayame. The Memory of the Mirror of Tsukuyomi.<br>Used to obtain or ascend Artifacts. |
| 2210051 | 지호의 유물, 만파식적의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Jiho. The Memory of the Manpashikjeok.<br>Used to obtain or ascend Artifacts. |
| 2210052 | 헤이즐의 유물, 아스트라페의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Hazel. The Memory of Astrape.<br>Used to obtain or ascend Artifacts. |
| 2210053 | 소연의 유물, 여의금고봉의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Xiaolian. The Memory of Ruyi Jingu Bang.<br>Used to obtain or ascend Artifacts. |
| 2210054 | 마농의 유물, 엘도라도의 금화의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Manon. The Memory of the Gold Coins of El Dorado.<br>Used to obtain or ascend Artifacts. |
| 2210055 | 다프네의 유물, 헤파이스토스의 망치의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Daphne. Hephaestus's Hammer.<br>Used to obtain or ascend Artifacts. |
| 2210056 | 에일린의 유물, 하르페의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Eileen. The Memory of Harpe.<br>Used to obtain or ascend Artifacts. |
| 2210057 | 오토하의 유물, 아메노하바키리의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Otoha. The Memory of Ame No Habakiri.<br>Used to obtain or ascend Artifacts. |
| 2210058 | 이브의 유물, 운명의 서판의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Eve. The Memory of Tablet of Fate.<br>Used to obtain or ascend Artifacts. |
| 2210059 | 조앤의 유물, 아조트 검의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Joanne. The Memory of Azoth.<br>Used to obtain or ascend Artifacts. |
| 2210060 | 캐서린(광휘)의 유물, 찬란한 광휘의 성해포의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Catherine (Radiance). The Memory of the Holy Shroud of Splendid Radiance.<br>Used to obtain or ascend Artifacts. |
| 2210061 | 도미니크의 유물, 롱고미니아드의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Dominique. The Memory of Rhongomyniad.<br>Used to obtain or ascend Artifacts. |
| 2210062 | 시그리드의 유물, 튀르핑의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Sigrid. The Memory of Tyrfing.<br>Used to obtain or ascend Artifacts. |
| 2210063 | 오닉스의 유물, 골든 레코드의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Onyx. The Memory of the Golden Record.<br>Used to obtain or ascend Artifacts. |
| 2210064 | 린지(타나토스)의 유물, 타나토스=프라가라흐의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Linzy (Thanatos). The Memory of Thanatos = Fragarach.<br>Used to obtain or ascend Artifacts. |
| 2210065 | 릴리트의 유물, 방주 카마엘의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Lilith. The Memory of Ark Chamuel.<br>Used to obtain or ascend Artifacts. |
| 2210066 | 웨리의 유물, 미미르의 샘물의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Wheri. The Memory of Mimisbrunnr.<br>Used to obtain or ascend Artifacts. |
| 2210067 | 사쿠요(업화)의 유물, 요시모토 사몬지(업화)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Sakuyo (Inferno). The Memory of the Yoshimoto Samonji (Inferno).<br>Used to obtain or ascend Artifacts. |
| 2210068 | 메피스토펠레스(여명)의 유물, 여명의 방주 메타트론의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Mephistopheles (Dawn). The Memory of the Ark of Dawn Metatron.<br>Used to obtain or ascend Artifacts. |
| 2210069 | 바이스의 유물, 솔로몬의 반지의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Weiss. The Memory of Solomon's Ring.<br>Used to obtain or ascend Artifacts. |
| 2210070 | 로제(홍염)의 유물, 태양의 왕관의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Rose (Prominence). The Memory of the Crown of the Sun.<br>Used to obtain or ascend Artifacts. |
| 2210071 | 지호(미르)의 유물, 만파식적(미르)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Jiho (Mir). The Memory of the Manpashikjeok (Mir).<br>Used to obtain or ascend Artifacts. |
| 2210072 | 홍란(무쌍)의 유물, 청룡언월도(무쌍)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Honglan (Peerless). The Memory of the Green Dragon Crescent Blade.<br>Used to obtain or ascend Artifacts. |
| 2210073 | 하루(카무이)의 유물, 쿠투네시르카(카무이)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Haru (Kamuy). The Memory of the Kutune Shirka (Kamuy).<br>Used to obtain or ascend Artifacts. |
| 2210074 | 르네(백은)의 유물, 누아다의 의수(백은)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Renee (Argent). The Memory of the Nuada Airgetlám (Argent).<br>Used to obtain or ascend Artifacts. |
| 2210075 | 미리암(잔영)의 유물, 7발의 마탄(잔영)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Miriam (Afterimage). The Memory of The Seventh Bullet (Afterimage).<br>Used to obtain or ascend Artifacts. |
| 2210076 | 라우라의 유물, 소림사 탑림의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Laura. The Memory of Shaolin Temple Pagoda Forest.<br>Used to obtain or ascend Artifacts. |
| 2210077 | 페트라(각혼)의 유물, 반혼향(각혼)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Petra (Awakened Soul). The Memory of the Spirit-Calling Incense (Awakened Soul).<br>Used to obtain or ascend Artifacts. |
| 2210078 | 가넷(열락)의 유물, 롱기누스의 창(열락)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Garnet (Rapture). The Memory of the Spear of Longinus (Rapture).<br>Used to obtain or ascend Artifacts. |
| 2210079 | 한울의 유물, 천부인의 검의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Hanul. The Memory of Divine Sword of the Three Heavenly Seals.<br>Used to obtain or ascend Artifacts. |
| 2210080 | 카넬리안의 유물, 호루스의 눈의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Carnelian. The Memory of the Eye of Horus.<br>Used to obtain or ascend Artifacts. |
| 2210081 | 니아의 유물, 니드호그의 이빨의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Nia. Nidhogg's Fangs.<br>Used to obtain or ascend Artifacts. |
| 2210082 | 셰리(낭만)의 유물, 신편귀독주(낭만)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Cherrie (Romantic). The Memory of the Shinpen Kidoku (Romantic).<br>Used to obtain or ascend Artifacts. |
| 2210083 | 클라우디아(대천사)의 유물, 묠니르(대천사)의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Claudia (Archangel). The Memory of the Mjölnir (Archangel).<br>Used to obtain or ascend Artifacts. |
| 2210084 | 유리아(아폴리온)의 유물, 종말의 나팔의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Yuria (Apollyon). The Memory of the Trumpet of the End.<br>Used to obtain or ascend Artifacts. |
| 2210085 | 아야메(츠쿠요미)의 유물, 아야메의 백동거울의 기억입니다.<br>유물을 획득하거나 승급에 사용됩니다. | Artifact of Ayame (Tsukuyomi). The Memory of the Mirror of Ayame.<br>Used to obtain or ascend Artifacts. |
| 2211001 | 이터널+ 등급, 힘 특성의 예장인 '달콤한 입맞춤의 탁상시계'의 초월시 사용됩니다. | Used when transcending an Eternal+ STR "Table Clock of Sweet Kisses." |
| 2211002 | 이터널+ 등급, 힘 특성의 예장인 '달콤한 입맞춤의 뮤직박스'의 초월시 사용됩니다. | Used when transcending an Eternal+ STR "Music Box of Sweet Kisses." |
| 2211003 | 이터널+ 등급, 힘 특성의 예장인 '달콤한 입맞춤의 탁상거울'의 초월시 사용됩니다. | Used when transcending an Eternal+ STR "Table Mirror of Sweet Kisses." |
| 2211004 | 이터널+ 등급, 힘 특성의 예장인 '달콤한 입맞춤의 금고열쇠'의 초월시 사용됩니다. | Used when transcending an Eternal+ STR "Safe Key of Sweet Kisses." |
| 2211005 | 오리진 등급, 힘 특성의 예장인 '영원한 약속의 탁상시계'의 초월시 사용됩니다. | Used when transcending an Origin STR "Table Clock of Eternal Promise." |
| 2211006 | 오리진 등급, 힘 특성의 예장인 '영원한 약속의 뮤직박스'의 초월시 사용됩니다. | Used when transcending an Origin STR "Music Box of Eternal Promise." |
| 2211007 | 오리진 등급, 힘 특성의 예장인 '영원한 약속의 탁상거울'의 초월시 사용됩니다. | Used when transcending an Origin STR "Table Mirror of Eternal Promise." |
| 2211008 | 오리진 등급, 힘 특성의 예장인 '영원한 약속의 금고열쇠'의 초월시 사용됩니다. | Used when transcending an Origin STR "Safe Key of Eternal Promise." |
| 2211009 | 오리진+1 등급, 힘 특성의 예장인 '소원을 품은 탁상시계'의 초월시 사용됩니다. | Used when transcending an Origin+1 STR "Table Clock of Wishes." |
| 2211010 | 오리진+1 등급, 힘 특성의 예장인 '소원을 품은 뮤직박스'의 초월시 사용됩니다. | Used when transcending an Origin+1 STR "Music Box of Wishes." |
| 2211011 | 오리진+1 등급, 힘 특성의 예장인 '소원을 품은 탁상거울'의 초월시 사용됩니다. | Used when transcending an Origin+1 STR "Table Mirror of Wishes." |
| 2211012 | 오리진+1 등급, 힘 특성의 예장인 '소원을 품은 금고열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+1 STR "Safe Key of Wishes." |
| 2211013 | 오리진+2 등급, 힘 특성의 예장인 '춤추는 별들의 탁상시계'의 초월시 사용됩니다. | Used when transcending an Origin+2 STR "Table Clock of Dancing Stars." |
| 2211014 | 오리진+2 등급, 힘 특성의 예장인 '춤추는 별들의 뮤직박스'의 초월시 사용됩니다. | Used when transcending an Origin+2 STR "Music Box of Dancing Stars." |
| 2211015 | 오리진+2 등급, 힘 특성의 예장인 '춤추는 별들의 탁상거울'의 초월시 사용됩니다. | Used when transcending an Origin+2 STR "Table Mirror of Dancing Stars." |
| 2211016 | 오리진+2 등급, 힘 특성의 예장인 '춤추는 별들의 금고열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+2 STR "Safe Key of Dancing Stars." |
| 2211017 | 오리진+3 등급, 힘 특성의 예장인 '월광을 머금은 탁상시계'의 초월시 사용됩니다. | Used when transcending an Origin+3 STR "Moonlit Table Clock." |
| 2211018 | 오리진+3 등급, 힘 특성의 예장인 '월광을 머금은 뮤직박스'의 초월시 사용됩니다. | Used when transcending an Origin+3 STR "Moonlit Music Box." |
| 2211019 | 오리진+3 등급, 힘 특성의 예장인 '월광을 머금은 탁상거울'의 초월시 사용됩니다. | Used when transcending an Origin+3 STR "Moonlit Table Mirror." |
| 2211020 | 오리진+3 등급, 힘 특성의 예장인 '월광을 머금은 금고열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+3 STR "Moonlit Safe Key." |
| 2211021 | 오리진+4 등급, 힘 특성의 예장인 '천일의 빛을 담은 탁상시계'의 초월시 사용됩니다. | Used when transcending an Origin+4 STR "Table Clock of a Thousand Days of Light." |
| 2211022 | 오리진+4 등급, 힘 특성의 예장인 '천일의 빛을 담은 뮤직박스'의 초월시 사용됩니다. | Used when transcending an Origin+4 STR "Music Box of a Thousand Days of Light." |
| 2211023 | 오리진+4 등급, 힘 특성의 예장인 '천일의 빛을 담은 탁상거울'의 초월시 사용됩니다. | Used when transcending an Origin+4 STR "Table Mirror of a Thousand Days of Light." |
| 2211024 | 오리진+4 등급, 힘 특성의 예장인 '천일의 빛을 담은 금고열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+4 STR "Safe Key of a Thousand Days of Light." |
| 2211025 | 이터널+ 등급, 민첩 특성의 예장인 '달콤한 입맞춤의 회중시계'의 초월시 사용됩니다. | Used when transcending an Eternal+ DEX "Pocket Watch of Sweet Kisses." |
| 2211026 | 이터널+ 등급, 민첩 특성의 예장인 '달콤한 입맞춤의 오르골'의 초월시 사용됩니다. | Used when transcending an Eternal+ DEX "Music Box of Sweet Kisses." |
| 2211027 | 이터널+ 등급, 민첩 특성의 예장인 '달콤한 입맞춤의 접이거울'의 초월시 사용됩니다. | Used when transcending an Eternal+ DEX "Folding Mirror of Sweet Kisses." |
| 2211028 | 이터널+ 등급, 민첩 특성의 예장인 '달콤한 입맞춤의 만능열쇠'의 초월시 사용됩니다. | Used when transcending an Eternal+ DEX "Master Key of Sweet Kisses." |
| 2211029 | 오리진 등급, 민첩 특성의 예장인 '영원한 약속의 회중시계'의 초월시 사용됩니다. | Used when transcending an Origin DEX "Pocket Watch of Eternal Promise." |
| 2211030 | 오리진 등급, 민첩 특성의 예장인 '영원한 약속의 오르골'의 초월시 사용됩니다. | Used when transcending an Origin DEX "Music Box of Eternal Promise." |
| 2211031 | 오리진 등급, 민첩 특성의 예장인 '영원한 약속의 접이거울'의 초월시 사용됩니다. | Used when transcending an Origin DEX "Folding Mirror of Eternal Promise." |
| 2211032 | 오리진 등급, 민첩 특성의 예장인 '영원한 약속의 만능열쇠'의 초월시 사용됩니다. | Used when transcending an Origin DEX "Master Key of Eternal Promise." |
| 2211033 | 오리진+1 등급, 민첩 특성의 예장인 '소원을 품은 회중시계'의 초월시 사용됩니다. | Used when transcending an Origin+1 DEX "Pocket Watch of Wishes." |
| 2211034 | 오리진+1 등급, 민첩 특성의 예장인 '소원을 품은 오르골'의 초월시 사용됩니다. | Used when transcending an Origin+1 DEX "Orgel of Wishes." |
| 2211035 | 오리진+1 등급, 민첩 특성의 예장인 '소원을 품은 접이거울'의 초월시 사용됩니다. | Used when transcending an Origin+1 DEX "Folding Mirror of Wishes." |
| 2211036 | 오리진+1 등급, 민첩 특성의 예장인 '소원을 품은 만능열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+1 DEX "Master Key of Wishes." |
| 2211037 | 오리진+2 등급, 민첩 특성의 예장인 '춤추는 별들의 회중시계'의 초월시 사용됩니다. | Used when transcending an Origin+2 DEX "Pocket Watch of Dancing Stars." |
| 2211038 | 오리진+2 등급, 민첩 특성의 예장인 '춤추는 별들의 오르골'의 초월시 사용됩니다. | Used when transcending an Origin+2 DEX "Music Box of Dancing Stars." |
| 2211039 | 오리진+2 등급, 민첩 특성의 예장인 '춤추는 별들의 접이거울'의 초월시 사용됩니다. | Used when transcending an Origin+2 DEX "Folding Mirror of Dancing Stars." |
| 2211040 | 오리진+2 등급, 민첩 특성의 예장인 '춤추는 별들의 만능열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+2 DEX "Master Key of Dancing Stars." |
| 2211041 | 오리진+3 등급, 민첩 특성의 예장인 '월광을 머금은 회중시계'의 초월시 사용됩니다. | Used when transcending an Origin+3 DEX "Moonlit Pocket Watch." |
| 2211042 | 오리진+3 등급, 민첩 특성의 예장인 '월광을 머금은 오르골'의 초월시 사용됩니다. | Used when transcending an Origin+3 DEX "Moonlit Music Box." |
| 2211043 | 오리진+3 등급, 민첩 특성의 예장인 '월광을 머금은 접이거울'의 초월시 사용됩니다. | Used when transcending an Origin+3 DEX "Moonlit Folding Mirror." |
| 2211044 | 오리진+3 등급, 민첩 특성의 예장인 '월광을 머금은 만능열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+3 DEX "Moonlit Master Key." |
| 2211045 | 오리진+4 등급, 민첩 특성의 예장인 '천일의 빛을 담은 회중시계'의 초월시 사용됩니다. | Used when transcending an Origin+4 DEX "Pocket Watch of a Thousand Days of Light." |
| 2211046 | 오리진+4 등급, 민첩 특성의 예장인 '천일의 빛을 담은 오르골'의 초월시 사용됩니다. | Used when transcending an Origin+4 DEX "Music Box of a Thousand Days of Light." |
| 2211047 | 오리진+4 등급, 민첩 특성의 예장인 '천일의 빛을 담은 접이거울'의 초월시 사용됩니다. | Used when transcending an Origin+4 DEX "Folding Mirror of a Thousand Days of Light." |
| 2211048 | 오리진+4 등급, 민첩 특성의 예장인 '천일의 빛을 담은 만능열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+4 DEX "Master Key of a Thousand Days of Light." |
| 2211049 | 이터널+ 등급, 지능 특성의 예장인 '달콤한 입맞춤의 모래시계'의 초월시 사용됩니다. | Used when transcending an Eternal+ INT "Hourglass of Sweet Kisses." |
| 2211050 | 이터널+ 등급, 지능 특성의 예장인 '달콤한 입맞춤의 스노우볼'의 초월시 사용됩니다. | Used when transcending an Eternal+ INT "Snow Globe of Sweet Kisses." |
| 2211051 | 이터널+ 등급, 지능 특성의 예장인 '달콤한 입맞춤의 손거울'의 초월시 사용됩니다. | Used when transcending an Eternal+ INT "Hand Mirror of Sweet Kisses." |
| 2211052 | 이터널+ 등급, 지능 특성의 예장인 '달콤한 입맞춤의 마법열쇠'의 초월시 사용됩니다. | Used when transcending an Eternal+ INT "Magic Key of Sweet Kisses." |
| 2211053 | 오리진 등급, 지능 특성의 예장인 '영원한 약속의 모래시계'의 초월시 사용됩니다. | Used when transcending an Origin INT "Hourglass of Eternal Promise." |
| 2211054 | 오리진 등급, 지능 특성의 예장인 '영원한 약속의 스노우볼'의 초월시 사용됩니다. | Used when transcending an Origin INT "Snow Globe of Eternal Promise." |
| 2211055 | 오리진 등급, 지능 특성의 예장인 '영원한 약속의 손거울'의 초월시 사용됩니다. | Used when transcending an Origin INT "Hand Mirror of Eternal Promise." |
| 2211056 | 오리진 등급, 지능 특성의 예장인 '영원한 약속의 마법열쇠'의 초월시 사용됩니다. | Used when transcending an Origin INT "Magic Key of Eternal Promise." |
| 2211057 | 오리진+1 등급, 지능 특성의 예장인 '소원을 품은 모래시계'의 초월시 사용됩니다. | Used when transcending an Origin+1 INT "Hourglass of Wishes." |
| 2211058 | 오리진+1 등급, 지능 특성의 예장인 '소원을 품은 스노우볼'의 초월시 사용됩니다. | Used when transcending an Origin+1 INT "Snow Globe of Wishes." |
| 2211059 | 오리진+1 등급, 지능 특성의 예장인 '소원을 품은 손거울'의 초월시 사용됩니다. | Used when transcending an Origin+1 INT "Hand Mirror of Wishes." |
| 2211060 | 오리진+1 등급, 지능 특성의 예장인 '소원을 품은 마법열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+1 INT "Magic Key of Wishes." |
| 2211061 | 오리진+2 등급, 지능 특성의 예장인 '춤추는 별들의 모래시계'의 초월시 사용됩니다. | Used when transcending an Origin+2 INT "Hourglass of Dancing Stars." |
| 2211062 | 오리진+2 등급, 지능 특성의 예장인 '춤추는 별들의 스노우볼'의 초월시 사용됩니다. | Used when transcending an Origin+2 INT "Snow Globe of Dancing Stars." |
| 2211063 | 오리진+2 등급, 지능 특성의 예장인 '춤추는 별들의 손거울'의 초월시 사용됩니다. | Used when transcending an Origin+2 INT "Hand Mirror of Dancing Stars." |
| 2211064 | 오리진+2 등급, 지능 특성의 예장인 '춤추는 별들의 마법열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+2 INT "Magic Key of Dancing Stars." |
| 2211065 | 오리진+3 등급, 지능 특성의 예장인 '월광을 머금은 모래시계'의 초월시 사용됩니다. | Used when transcending an Origin+3 INT "Moonlit Hourglass." |
| 2211066 | 오리진+3 등급, 지능 특성의 예장인 '월광을 머금은 스노우볼'의 초월시 사용됩니다. | Used when transcending an Origin+3 INT "Moonlit Snow Globe." |
| 2211067 | 오리진+3 등급, 지능 특성의 예장인 '월광을 머금은 손거울'의 초월시 사용됩니다. | Used when transcending an Origin+3 INT "Moonlit Hand Mirror." |
| 2211068 | 오리진+3 등급, 지능 특성의 예장인 '월광을 머금은 마법열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+3 INT "Moonlit Magic Key." |
| 2211069 | 오리진+4 등급, 지능 특성의 예장인 '천일의 빛을 담은 모래시계'의 초월시 사용됩니다. | Used when transcending an Origin+4 INT "Hourglass of a Thousand Days of Light." |
| 2211070 | 오리진+4 등급, 지능 특성의 예장인 '천일의 빛을 담은 스노우볼'의 초월시 사용됩니다. | Used when transcending an Origin+4 INT "Snow Globe of a Thousand Days of Light." |
| 2211071 | 오리진+4 등급, 지능 특성의 예장인 '천일의 빛을 담은 손거울'의 초월시 사용됩니다. | Used when transcending an Origin+4 INT "Hand Mirror of a Thousand Days of Light." |
| 2211072 | 오리진+4 등급, 지능 특성의 예장인 '천일의 빛을 담은 마법열쇠'의 초월시 사용됩니다. | Used when transcending an Origin+4 INT "Magic Key of a Thousand Days of Light." |
| 2212000 | 초인류의 방주 제조 시설에서 발견된 1호 방주 메타트론용 예비 회로.<br>방주의 메인 시스템을 강화할 때 사용합니다. | Ark Metatron's backup circuit, found from an ark manufacturing facility of the Dominas.<br>Used to enhance the Ark's main system. |
| 2212007 | 초인류 문명 유적에서 발견된 방주용 예비 회로.<br>이를 사용해 방주 메타트론의 <color="#2d9b00">워리어 보조 시스템</color>을 강화할 수 있습니다. | An ark backup circuit found from the ruins of the Dominas civilization.<br>Can be used to enhance Ark Metatron's <color="#2d9b00">Warrior Assistance System</color>. |
| 2212008 | 초인류 문명 유적에서 발견된 방주용 예비 회로.<br>이를 사용해 방주 메타트론의 <color="#2d9b00">레인저 보조 시스템</color>을 강화할 수 있습니다. | An ark backup circuit found from the ruins of the Dominas civilization.<br>Can be used to enhance Ark Metatron's <color="#2d9b00">Ranger Assistance System</color>. |
| 2212009 | 초인류 문명 유적에서 발견된 방주용 예비 회로.<br>이를 사용해 방주 메타트론의 <color="#2d9b00">스트라이커 보조 시스템</color>을 강화할 수 있습니다. | An ark backup circuit found from the ruins of the Dominas civilization.<br>Can be used to enhance Ark Metatron's <color="#2d9b00">Striker Assistance System</color>. |
| 2212010 | 초인류 문명 유적에서 발견된 방주용 예비 회로.<br>이를 사용해 방주 메타트론의 <color="#2d9b00">캐스터 보조 시스템</color>을 강화할 수 있습니다. | An ark backup circuit found from the ruins of the Dominas civilization.<br>Can be used to enhance Ark Metatron's <color="#2d9b00">Caster Assistance System</color>. |
| 2212011 | 초인류 문명 유적에서 발견된 방주용 예비 회로.<br>이를 사용해 방주 메타트론의 <color="#2d9b00">서포터 보조 시스템</color>을 강화할 수 있습니다. | An ark backup circuit found from the ruins of the Dominas civilization.<br>Can be used to enhance Ark Metatron's <color="#2d9b00">Supporter Assistance System</color>. |
| 2212012 | 초인류 문명 유적에서 발견된 방주용 예비 회로.<br>이를 사용해 방주 메타트론의 <color="#2d9b00">디펜더 보조 시스템</color>을 강화할 수 있습니다. | An ark backup circuit found from the ruins of the Dominas civilization.<br>Can be used to enhance Ark Metatron's <color="#2d9b00">Defender Assistance System</color>. |
| 2214100 | 런칭 시점에 출시된 정령 중 천사형, 악마형, 혼돈형을 제외한 모든 정령의 정령의 기억 중 선택 가능한 상자. | A chest from which you can choose the Soul's Memory of any Soul released at launch, excluding Angel, Demon, and Chaotic Souls. |
| 2214101 | 사용 시 다음 물품을 획득합니다. | Contains the following items: |
| 2240001 | 물을 뿜어내는 분수.<br><br><color="#2d9b00">전리품 골드를 1% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A fountain that spouts water.<br><br>Offers <color="#2d9b00">1% more Gold in loot</color>.<br>(Max: 3) |
| 2240002 | 위험한 녹색 물이 떨어지는 분수.<br><br><color="#2d9b00">전리품 2% 골드를 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A fountain from which dangerous green water flows down.<br><br>Offers <color="#2d9b00">2% more Gold in loot</color>.<br>(Max: 3) |
| 2240003 | 달콤한 초콜릿이 흘러나오는 분수.<br><br><color="#2d9b00">전리품 골드를 5% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A fountain that flows with sweet chocolate.<br><br>Offers <color="#2d9b00">5% more Gold in loot</color>.<br>(Max: 3) |
| 2240004 | 위풍당당한 용 모양의 분수.<br><br><color="#2d9b00">전리품 골드를 5% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A fountain in the shape of a majestic dragon.<br><br>Offers <color="#2d9b00">5% more Gold in loot</color>.<br>(Max: 3) |
| 2240101 | 나무로 된 벤치. 영지에 배치할 수 있습니다. | A wooden bench. It can be placed in the town. |
| 2240102 | 푹신푹신해 보이는 구름 모양 벤치. 영지에 배치할 수 있습니다. | A cloud-shaped bench that looks fluffy. It can be placed in the town. |
| 2240103 | 맛있어 보이는 벤치. 영지에 배치할 수 있습니다. | A bench that looks tasty. It can be placed in the town. |
| 2240104 | 전통적인 양식의 나무 벤치 | Wooden bench made in a traditional design. |
| 2240201 | 커다란 스테이지. 영지에 배치할 수 있습니다. | A big stage. It can be placed in the town. |
| 2240202 | 화려한 조명이 나를 비출 것 같은 스테이지. 영지에 배치할 수 있습니다. | A stage where colorful lights would seem to shine on me. It can be placed in the town. |
| 2240203 | 마술 맛을 볼 수 있을 것 같은 스테이지. 영지에 배치할 수 있습니다. | A stage that would make you feel a taste of magic. It can be placed in the town. |
| 2240301 | 양이 살고 있는 울타리. 영지에 배치하면 영지 내에 양이 돌아다닙니다. 영지에 배치할 수 있습니다. | A fenced area where sheep live. Place it in the town, and a sheep will roam around. |
| 2240302 | 오리가 살고 있는 집. 영지에 배치하면 영지 내에 오리가 돌아다닙니다. 영지에 배치할 수 있습니다. | A house where ducks live. Place it in the town, and a duck will roam around. |
| 2240303 | 강아지가 살고 있는 집. 영지에 배치하면 영지 내에 강아지가 돌아다닙니다. 영지에 배치할 수 있습니다. | A house where puppies live. Place it in the town, and a puppy will roam around. |
| 2240304 | 고양이를 위한 캣타워. 영지에 배치하면 영지 내에 고양이가 돌아다닙니다. 영지에 배치할 수 있습니다. | A cat tower for cats. Place it in the town, and a cat will roam around. |
| 2240401 | 나무로 된 테이블. 영지에 배치할 수 있습니다. | A wooden table. It can be placed in the town. |
| 2240402 | 맛있는 음식이 잔뜩 올려진 테이블. 영지에 배치할 수 있습니다. | A table full of delicious food. It can be placed in the town. |
| 2240403 | 미래가 보일 것 같은 테이블. 영지에 배치할 수 있습니다. | A table where you can vaguely see the future. It can be placed in the town. |
| 2240501 | 나무 아래에서 고백하면 이루어질 것 같은 벚나무. 영지에 배치할 수 있습니다. | A cherry tree under which one's wish will apparently come true. It can be placed in the town. |
| 2240502 | 황금 사과가 열리는 천계의 나무. 영지에 배치할 수 있습니다. | A celestial tree that bears golden apples. It can be placed in the town. |
| 2240503 | 맛있는 솜사탕이 열리는 나무. 영지에 배치할 수 있습니다. | A tree that bears sweet cotton candies. It can be placed in the town. |
| 2240504 | 기괴한 모습의 새장이 걸린 나무. 영지에 배치할 수 있습니다. | A tree with a bizarre cage. It can be placed in the town. |
| 2240601 | 정원. 영지에 배치할 수 있습니다. | A garden. It can be placed in the town. |
| 2240602 | 고풍스러운 정원. 영지에 배치할 수 있습니다. | A vintage-style garden. It can be placed in the town. |
| 2240603 | 장미꽃이 만발한 아름다운 정원. 영지에 배치할 수 있습니다. | A beautiful garden full of roses. It can be placed in the town. |
| 2240701 | 여신의 힘이 깃든 여신상.<br><br><color="#2d9b00">전리품 마나 더스트를 1% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A statue of a goddess imbued with power.<br><br>Offers <color="#2d9b00">1% more Mana Dust in loot</color>.<br>(Max: 3) |
| 2240702 | 자유를 향한 깃발을 든 여인상.<br><br><color="#2d9b00">전리품 마나 더스트를 2% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A statue with a woman bearing a flag of liberty.<br><br>Offers <color="#2d9b00">2% more Mana Dust in loot</color>.<br>(Max: 3) |
| 2240703 | 용을 쓰러트린 기사의 동상.<br><br><color="#2d9b00">전리품 마나 더스트를 5% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A statue of a knight who defeated a dragon.<br><br>Offers <color="#2d9b00">5% more Mana Dust in loot</color>.<br>(Max: 3) |
| 2240704 | 방주의 모양을 본뜬 석상.<br><br><color="#2d9b00">전리품 마나 더스트를 5% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A stone statue in the shape of an Ark.<br><br>Offers <color="#2d9b00">5% more Mana Dust in loot</color>.<br>(Max: 3) |
| 2240801 | 고요한 연못.<br><br><color="#2d9b00">전리품 마나 크리스탈을 0.5% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A serene pond.<br><br>Offers <color="#2d9b00">0.5% more Mana Crystals in loot</color>.<br>(Max: 3) |
| 2240802 | 연꽃이 피어 있는 연못. <br><br><color="#2d9b00">전리품 마나 크리스탈을 1% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A pond with lotus flowers.<br><br>Offers <color="#2d9b00">1% more Mana Crystals in loot</color>.<br>(Max: 3) |
| 2240803 | 요정들이 살 것 같은 연못. <br><br><color="#2d9b00">전리품 마나 크리스탈을 2.5% 추가로 획득</color>할 수 있습니다.<br>( 보유 가능 개수: 3 ) | A pond where fairies likely live.<br><br>Offers <color="#2d9b00">2.5% more Mana Crystals in loot</color>.<br>(Max: 3) |
| 2240804 | 조경용 작은 연못.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A small, decorative pond.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2240901 | 간단한 운동기구. 영지에 배치할 수 있습니다. | A set of simple workout equipment. It can be placed in the town. |
| 2240902 | 타격 연습을 할 수 있는 운동기구. 영지에 배치할 수 있습니다. | A set of workout equipment to help you practice hitting. It can be placed in the town. |
| 2240903 | 검술 훈련을 할 수 있는 운동기구. 영지에 배치할 수 있습니다. | A set of workout equipment to help you practice swordsmanship. It can be placed in the town. |
| 2240904 | 권법 연습을 할 수 있는 운동기구. 영지에 배치할 수 있습니다. | A set of workout equipment to help you practice martial arts. It can be placed in the town. |
| 2240905 | 목검이 세워져 있는 운동기구. 영지에 배치할 수 있습니다. | A set of workout equipment with a wooden sword set upright. It can be placed in the town. |
| 2240906 | 목검이 세워져 있는 운동기구. 영지에 배치할 수 있습니다. | A set of workout equipment with a wooden sword set upright. It can be placed in the town. |
| 2241001 | 어디서나 볼 수 있는 흔한 나무. 영지에 배치할 수 있습니다. | A common tree that can be seen everywhere. It can be placed in the town. |
| 2241002 | 붉은 단풍잎이 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with red maple leaves. It can be placed in the town. |
| 2241003 | 노란 은행잎이 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with yellow ginkgo leaves. It can be placed in the town. |
| 2241004 | 먹음직스러운 사과가 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with appetizing apples. It can be placed in the town. |
| 2241005 | 먹음직스러운 오렌지가 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with appetizing oranges. It can be placed in the town. |
| 2241006 | 먹음직스러운 블루베리가 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with appetizing blueberries. It can be placed in the town. |
| 2241050 | 분홍빛 벚꽃이 만개한 나무. 영지에 배치할 수 있습니다. | A tree in full bloom with pink cherry blossoms. It can be placed in the town. |
| 2241051 | 황금빛 열매가 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with golden fruits. It can be placed in the town. |
| 2241052 | 달콤한 솜사탕이 달려 있는 나무. 영지에 배치할 수 있습니다. | A tree with sweet cotton candies. It can be placed in the town. |
| 2241053 | 으스스한 분위기를 내는 나무. 영지에 배치할 수 있습니다. | A tree that emits a spooky aura. It can be placed in the town. |
| 2241054 | 스프링클과 각종 토핑으로 꾸며진 달콤한 풍선.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A sweet balloon with sprinkles and various toppings.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2241055 | 각종 초콜릿과 디저트로 구성된 달콤한 트리.<br>밤에는 환하게 반짝인다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A tree filled with various chocolates and desserts as ornaments.<br>It shines brightly at night.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2241101 | 철재 가로등. 영지에 배치할 수 있습니다. | An iron street lamp. It can be placed in the town. |
| 2241102 | 빨간색의 철재 가로등. 영지에 배치할 수 있습니다. | A red iron street lamp. It can be placed in the town. |
| 2241103 | 노란색의 철재 가로등. 영지에 배치할 수 있습니다. | A yellow iron street lamp. It can be placed in the town. |
| 2241104 | 파란색의 철재 가로등. 영지에 배치할 수 있습니다. | A blue iron street lamp. It can be placed in the town. |
| 2241105 | 녹색의 철재 가로등. 영지에 배치할 수 있습니다. | A green iron street lamp. It can be placed in the town. |
| 2241106 | 보라색의 철재 가로등. 영지에 배치할 수 있습니다. | A purple iron street lamp. It can be placed in the town. |
| 2241107 | 흰색의 철재 가로등. 영지에 배치할 수 있습니다. | A white iron street lamp. It can be placed in the town. |
| 2241108 | 카카오 열매 가로등 | Cacao Fruit Street Lamp |
| 2241201 | 목재 가로등. 영지에 배치할 수 있습니다. | A wooden street lamp. It can be placed in the town. |
| 2241202 | 빨간색의 목재 가로등. 영지에 배치할 수 있습니다. | A red wooden street lamp. It can be placed in the town. |
| 2241203 | 노란색의 목재 가로등. 영지에 배치할 수 있습니다. | A yellow wooden street lamp. It can be placed in the town. |
| 2241204 | 파란색의 목재 가로등. 영지에 배치할 수 있습니다. | A blue wooden street lamp. It can be placed in the town. |
| 2241205 | 녹색의 목재 가로등. 영지에 배치할 수 있습니다. | A green wooden street lamp. It can be placed in the town. |
| 2241206 | 보라색의 목재 가로등. 영지에 배치할 수 있습니다. | A purple wooden street lamp. It can be placed in the town. |
| 2241207 | 흰색의 목재 가로등. 영지에 배치할 수 있습니다. | A white wooden street lamp. It can be placed in the town. |
| 2241301 | 노란 꽃이 피어 있는 덤불. 영지에 배치할 수 있습니다. | A bush with yellow flowers in bloom. It can be placed in the town. |
| 2241302 | 빨간 꽃이 피어 있는 덤불. 영지에 배치할 수 있습니다. | A bush with red flowers in bloom. It can be placed in the town. |
| 2241303 | 파란 꽃이 피어 있는 덤불. 영지에 배치할 수 있습니다. | A bush with blue flowers in bloom. It can be placed in the town. |
| 2241304 | 보라색 꽃이 피어 있는 덤불. 영지에 배치할 수 있습니다. | A bush with purple flowers in bloom. It can be placed in the town. |
| 2241305 | 흰색 꽃이 피어 있는 덤불. 영지에 배치할 수 있습니다. | A bush with white flowers in bloom. It can be placed in the town. |
| 2241401 | 예쁘게 정돈된 가로수. 영지에 배치할 수 있습니다. | A beautifully organized street tree. It can be placed in the town. |
| 2241501 | 수확을 하고 남은 잔해. 영지에 배치할 수 있습니다. | A pile of remnants left after a harvest. It can be placed in the town. |
| 2241601 | 꽃이 피어 있는 화분. 영지에 배치할 수 있습니다. | A flowerpot with flowers in bloom. It can be placed in the town. |
| 2241701 | 평범한 흰색의 촛대. 영지에 배치할 수 있습니다. | A plain white candlestick. It can be placed in the town. |
| 2241702 | 평범한 빨간색의 촛대. 영지에 배치할 수 있습니다. | A plain red candlestick. It can be placed in the town. |
| 2241703 | 평범한 오렌지색의 촛대. 영지에 배치할 수 있습니다. | A plain orange candlestick. It can be placed in the town. |
| 2241704 | 평범한 녹색의 촛대. 영지에 배치할 수 있습니다. | A plain green candlestick. It can be placed in the town. |
| 2241705 | 평범한 파란색의 촛대. 영지에 배치할 수 있습니다. | A plain blue candlestick. It can be placed in the town. |
| 2241706 | 평범한 보라색의 촛대. 영지에 배치할 수 있습니다. | A plain purple candlestick. It can be placed in the town. |
| 2241707 | 평범한 민트색의 촛대. 영지에 배치할 수 있습니다. | A plain mint candlestick. It can be placed in the town. |
| 2241708 | 철로 만들어진 특별한 촛대. 영지에 배치할 수 있습니다. | A special candlestick made of iron. It can be placed in the town. |
| 2241709 | 놋쇠로 만들어진 특별한 촛대. 영지에 배치할 수 있습니다. | A special candlestick made of brass. It can be placed in the town. |
| 2241710 | 황금으로 만들어진 고귀한 촛대. 영지에 배치할 수 있습니다. | A noble candlestick made of gold. It can be placed in the town. |
| 2241711 | 로즈골드로 만들어진 고귀한 촛대. 영지에 배치할 수 있습니다. | A noble candlestick made of rose gold. It can be placed in the town. |
| 2241712 | 단아하고 아름다운 등잔 | Elegant Oil Lamp |
| 2241801 | 인간형의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Humanlike Type. It can be placed in the town. |
| 2241802 | 야수형의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Beast Type. It can be placed in the town. |
| 2241803 | 요정형의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Fairy Type. It can be placed in the town. |
| 2241804 | 불사형의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Undead Type. It can be placed in the town. |
| 2241805 | 천사형의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Angel Type. It can be placed in the town. |
| 2241806 | 악마형의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Demon Type. It can be placed in the town. |
| 2241807 | 솔레이 왕국의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Kingdom of Solrey. It can be placed in the town. |
| 2241808 | 솔레이 왕국의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Kingdom of Solrey. It can be placed in the town. |
| 2241809 | 솔레이 왕국의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Kingdom of Solrey. It can be placed in the town. |
| 2241810 | 솔레이 왕국의 심볼이 새겨진 깃발. 영지에 배치할 수 있습니다. | A flag printed with the symbol of the Kingdom of Solrey. It can be placed in the town. |
| 2241901 | 오렌지색 메일박스. 영지에 배치할 수 있습니다. | An orange mailbox. It can be placed in the town. |
| 2241902 | 노랑색 메일박스. 영지에 배치할 수 있습니다. | A yellow mailbox. It can be placed in the town. |
| 2241903 | 파랑색 메일박스. 영지에 배치할 수 있습니다. | A blue mailbox. It can be placed in the town. |
| 2241904 | 초록색 메일박스. 영지에 배치할 수 있습니다. | A green mailbox. It can be placed in the town. |
| 2241905 | 민트색 메일박스. 영지에 배치할 수 있습니다. | A mint mailbox. It can be placed in the town. |
| 2241906 | 핑크색 메일박스. 영지에 배치할 수 있습니다. | A pink mailbox. It can be placed in the town. |
| 2241907 | 보라색 메일박스. 영지에 배치할 수 있습니다. | A purple mailbox. It can be placed in the town. |
| 2241908 | 검정색 메일박스. 영지에 배치할 수 있습니다. | A black mailbox. It can be placed in the town. |
| 2241909 | 흰색 메일박스. 영지에 배치할 수 있습니다. | A white mailbox. It can be placed in the town. |
| 2241910 | 빨강색 메일박스. 영지에 배치할 수 있습니다. | A red mailbox. It can be placed in the town. |
| 2242001 | 갈색 로드사인. 영지에 배치할 수 있습니다. | A brown road sign. It can be placed in the town. |
| 2242002 | 밤색 로드사인. 영지에 배치할 수 있습니다. | A nutbrown road sign. It can be placed in the town. |
| 2242003 | 빨강색 로드사인. 영지에 배치할 수 있습니다. | A red road sign. It can be placed in the town. |
| 2242004 | 오렌지색 로드사인. 영지에 배치할 수 있습니다. | An orange road sign. It can be placed in the town. |
| 2242005 | 노랑색 로드사인. 영지에 배치할 수 있습니다. | A yellow road sign. It can be placed in the town. |
| 2242006 | 초록색 로드사인. 영지에 배치할 수 있습니다. | A green road sign. It can be placed in the town. |
| 2242007 | 보라색 로드사인. 영지에 배치할 수 있습니다. | A purple road sign. It can be placed in the town. |
| 2242008 | 민트색 로드사인. 영지에 배치할 수 있습니다. | A mint road sign. It can be placed in the town. |
| 2242009 | 흰색 로드사인. 영지에 배치할 수 있습니다. | A white road sign. It can be placed in the town. |
| 2242010 | 핑크색 로드사인. 영지에 배치할 수 있습니다. | A pink road sign. It can be placed in the town. |
| 2242011 | 파랑색 로드사인. 영지에 배치할 수 있습니다. | A blue road sign. It can be placed in the town. |
| 2242101 | 대리석 아치펜스. 영지에 배치할 수 있습니다. | A marble arch fence. It can be placed in the town. |
| 2242102 | 벽돌 아치펜스. 영지에 배치할 수 있습니다. | A brick arch fence. It can be placed in the town. |
| 2242103 | 철제 아치펜스. 영지에 배치할 수 있습니다. | An iron arch fence. It can be placed in the town. |
| 2242104 | 빨강색 아치펜스. 영지에 배치할 수 있습니다. | A red arch fence. It can be placed in the town. |
| 2242105 | 파랑색 아치펜스. 영지에 배치할 수 있습니다. | A blue arch fence. It can be placed in the town. |
| 2242106 | 초록색 아치펜스. 영지에 배치할 수 있습니다. | A green arch fence. It can be placed in the town. |
| 2242107 | 보라색 아치펜스. 영지에 배치할 수 있습니다. | A purple arch fence. It can be placed in the town. |
| 2242108 | 핑크색 아치펜스. 영지에 배치할 수 있습니다. | A pink arch fence. It can be placed in the town. |
| 2242109 | 흰색 아치펜스. 영지에 배치할 수 있습니다. | A white arch fence It can be placed in the town. |
| 2242110 | 민트색 아치펜스. 영지에 배치할 수 있습니다. | A mint arch fence. It can be placed in the town. |
| 2242111 | 작은 기와 담장 | Small Tiled Wall |
| 2242112 | 고풍스러운 파티션 폴. | Vintage partition poles. |
| 2242113 | 보급형 작은 기와 담장. | Economy level small tiled wall. |
| 2242201 | 대리석 아치. 영지에 배치할 수 있습니다. | A marble arch. It can be placed in the town. |
| 2242202 | 벽돌 아치. 영지에 배치할 수 있습니다. | A brick arch. It can be placed in the town. |
| 2242203 | 철제 아치. 영지에 배치할 수 있습니다. | An iron arch. It can be placed in the town. |
| 2242204 | 빨강색 아치. 영지에 배치할 수 있습니다. | A red arch. It can be placed in the town. |
| 2242205 | 파랑색 아치. 영지에 배치할 수 있습니다. | A blue arch. It can be placed in the town. |
| 2242206 | 초록색 아치. 영지에 배치할 수 있습니다. | A green arch. It can be placed in the town. |
| 2242207 | 보라색 아치. 영지에 배치할 수 있습니다. | A purple arch. It can be placed in the town. |
| 2242208 | 핑크색 아치. 영지에 배치할 수 있습니다. | A pink arch. It can be placed in the town. |
| 2242209 | 흰색 아치. 영지에 배치할 수 있습니다. | A white arch. It can be placed in the town. |
| 2242210 | 민트색 아치. 영지에 배치할 수 있습니다. | A mint arch. It can be placed in the town. |
| 2242211 | 앞에 서면 괜히 '이리 오너라~'를 외치고 싶어지는 전통 양식의 대문 | Large gate built in a traditional design. |
| 2242301 | 흰색의 타일 바닥. 영지에 배치할 수 있습니다. | A white tile floor. It can be placed in the town. |
| 2242302 | 갈색의 타일 바닥. 영지에 배치할 수 있습니다. | A brown tile floor. It can be placed in the town. |
| 2242303 | 단정한 우물마루 바닥 타일.<br>꼼꼼히 옻칠이 되어 있어 윤이 난다. | Simple checkered floor tile.<br>It shines due to the lacquer layer. |
| 2242304 | 단정한 우물마루 바닥 타일.<br>꼼꼼히 옻칠이 되어 있어 윤이 난다. | Simple checkered floor tile.<br>It shines due to the lacquer layer. |
| 2242305 | 전통 문양이 새겨진 바닥 타일.<br>섬세한 조형이 돋보인다. | Traditional design tile.<br>Boasts a delicate design. |
| 2242306 | 전통 문양이 새겨진 바닥 타일.<br>섬세한 조형이 돋보인다. | Traditional design tile.<br>Boasts a delicate design. |
| 2242307 | 초콜릿 모양의 바닥 타일. <br>밟아도 녹지 않는다. | Chocolate shaped floor tile.<br>Does not melt when you step on it. |
| 2242308 | 초콜릿 모양의 바닥 타일. <br>밟아도 녹지 않는다. | Chocolate shaped floor tile.<br>Does not melt when you step on it. |
| 2242309 | 바삭바삭한 바닥 타일.<br>밟아도 부서지지 않는다. | Crunchy floor tile.<br>Does not break when you step on it. |
| 2242310 | 풀 사이사이 들꽃이 피어있는 잔디 타일. | A grass tile with wild flowers growing on top. |
| 2242311 | 조경용 잔디 타일. | Grass tile used for landscaping. |
| 2242312 | 운동장 모래 바닥 타일. | Schoolyard sand floor tile. |
| 2242313 | 잔디가 있는 운동장 모래 바닥 타일. | Schoolyard sand floor tile with grass. |
| 2242314 | 외곽에 잔디가 있는 운동장 모래 바닥 타일. | Schoolyard sand floor tile with grass on the edges. |
| 2242315 | 모서리에 잔디가 있는 운동장 모래 바닥 타일. | Schoolyard sand floor tile with grass on the corners. |
| 2242316 | 고급스러운 벨벳 재질의 웨딩 카펫. | A luxurious velvet wedding carpet. |
| 2242317 | 고급스러운 벨벳 재질의 웨딩 카펫. | A luxurious velvet wedding carpet. |
| 2242318 | 고급스러운 벨벳 재질의 웨딩 카펫. | A luxurious velvet wedding carpet. |
| 2242319 | 고급스러운 벨벳 재질의 웨딩 카펫. | A luxurious velvet wedding carpet. |
| 2242401 | 귀여운 얼굴을 한 여우 모양의 천하대장군 장승.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | World General jangseung with a cute fox face.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2242402 | 귀여운 얼굴을 한 여우 모양의 지하여장군 장승.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | Underground General jangseung with a cute fox face.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2242501 | 최고급 원단으로 제작된 고급스러운 보료 세트. 푹신한 침구에 몸을 뉘면 바로 잠에 빠져들 것만 같다. <br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | Luxurious mattress made with the finest materials. Soft enough to make you sleep instantly.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2242601 | 창호지로 만든 전통식 파티션. 전통 풍경화로 그려진 자연 경관이 운치를 더한다. | Partition made with traditional Korean paper. The vista drawn in a traditional method is elegant. |
| 2242602 | 팬시한 초코 파티션.<br>판초콜릿 위에 색색의 스프링클이 잔뜩 뿌려져 있다. | Fancy chocolate themed partition.<br>The slab of chocolate is decorated with multi-colored sprinkles. |
| 2242603 | 창호지로 만든 보급형 전통식 파티션. 전통 풍경화로 그려진 자연 경관이 운치를 더한다. | Economy level partition made with traditional Korean paper. The vista drawn in a traditional method is elegant. |
| 2242701 | 전통 문양이 인쇄된 러그. 질 좋은 원단을 사용해 고급스럽고 우아하다. | Rug made in a traditional design. Made with high quality materials in an elegant design. |
| 2242801 | 새해맞이 음식이 가득 차려진 상과 전통 문양 방석이 돋보이는 자개소반 세트. 건강과 장수를 기원하며, 소중한 이를 대접하고 싶은 마음이 담겨 있다. | A table set meal filled with traditional new year's food and fitted with traditional cushions. It holds the wishes for good health and longevity for your loved ones. |
| 2242901 | 수레에 다 싣지도 못하는 어마어마한 금은보화 꾸러미. 지나친 탐욕은 화를 부를지도 모르니 조심하자.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A great pile of treasure overflowing the cart. When the well is full, it will run over.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243001 | 달의 모양을 닮은 아름다운 누각. 순백의 여우는 달의 꿈을 꾸고 있다. <br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A castle shaped like the moon. The white fox dreams of the moon.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243002 | 작은 매화나무가 심어진 분재용 화분. 우아하고 고급스러운 절제미가 돋보인다. | A small pot with an apricot tree. The small tree represents grace and self-control. |
| 2243101 | 발렌타인 스위츠를 판매하는 푸드 가판대.<br>달콤하고 화려한 디저트가 가득하다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A food stand selling Valentine's Day sweets.<br>It's filled with sweet and fancy desserts.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243102 | 입장권을 구매할 수 있는 티켓 판매 부스.<br>받은 티켓을 잃어버리지 않게 조심하자.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A ticket booth where you can buy tickets.<br>Be careful not to lose your ticket.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243103 | 둥실둥실 돌아가는 회전목마.<br>서로를 쫓아 회전하는 목마를 바라보고 있으니, <br>어쩌면 사랑도 이렇게 영원할 것만 같다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A spinning merry-go-round.<br>Watching the horses spinning endlessly<br>reminds you of eternal love.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243104 | LOVE 문구 모양의 초콜릿 조형물<br>달콤한 초콜릿맛 사랑이 느껴지는 것만 같다 | Chocolate decoration in the shape of LOVE.<br>You can almost taste the chocolate flavored love. |
| 2243105 | 사랑을 싣고 회전하는 대관람차<br>꼭대기에 도달했을 때 사랑이 깊어진다는 소문이 있다.<br>절대로 흔들다리 효과같은 게 아니다!<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A great wheel carrying love.<br>Rumor has it love deepens when you reach the top.<br>The shaking is not an intended feature!<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243106 | 싱싱한 딸기를 아낌없이 잔뜩 얹은 딸기 티라미수 테이블.<br>폭신한 크림이 흘러내리고 있다. | A strawberry tiramisu table filled with fresh strawberries.<br>Soft cream is oozing from it. |
| 2243107 | 등받이가 없는 스툴. <br>롤케이크 단면의 모양을 하고 있다. | A stool with no back support.<br>Shaped like a cut roll cake. |
| 2243201 | 고목을 활용하여 만든 아지트. <br>살랑살랑 불어오는 바람을 맞으며 누워있으면 모든 고민을 잊을 수 있을 것만 같다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A hideout built on an old tree.<br>Lie down and feel the gentle wind to forget all your worries.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243202 | 뿌리를 단단히 내린 그루터기. <br>평범한 나무 그루터기를 아기자기한 티 테이블로 꾸몄다. | A tree stump rooted deeply into the ground.<br>The ordinary tree stump was decorated into an adorable tea table. |
| 2243203 | 덤불 속에서 자고 있는 어린 여우. 깨우지 않게 조심하자. | A young fox sleeping inside a bush. Careful not to wake her up! |
| 2243204 | 나무로 만든 가로대에 줄을 매어 만든 흔들 해먹. <br>매우 푹신푹신하다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A hammock swing installed on a wooden bar.<br>It's really comfy.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243205 | 썩은 나무줄기에서 비가 내리고 꽃이 피어 만들어진 자연 화분. <br>숲의 생명력이 느껴진다. | A natural pot made from a flower blooming in the cracks of a rotten tree trunk.<br>You can feel the energy of the forest. |
| 2243301 | 살짝 무서운 학생들의 비밀스러운 쉼터.<br>이제는 체육 창고라기보단 아지트가 되어버린지 오래다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A secret hideout where scary students gather.<br>It's more of a hideout than a gym storage now.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243302 | 여러 가지 낙서가 그려진 칠판. <br>어째서인지 하늘색 분필이 부러져있다… | A chalkboard with scribbles on it.<br>A sky blue chalk appears to be broken... |
| 2243303 | 녹색 철제 캐비닛. 가끔 러브레터가 들어있기도 하다. | A metal cabinet. Sometimes it contains love letters. |
| 2243304 | 붉은색 철제 캐비닛. 가끔 러브레터가 들어있기도 하다. | A metal cabinet. Sometimes it contains love letters. |
| 2243305 | 평범한 교실 벽. 낙서는 절대 금지! | An ordinary classroom wall. Do not vandalize! |
| 2243306 | 창문이 달린 교실 벽. <br>창문을 열어두면 흰 커튼이 바람에 살랑살랑 흩날린다. | A classroom wall with a window.<br>The white curtains wave around if you leave the window opened. |
| 2243307 | 용모단정, 성적우수! 깔끔한 2인용 책상. | Clean-cut! Straight A's! A neat 2-seater desk. |
| 2243308 | 각종 물건이 난잡하게 널려있는 너저분한 2인용 책상. | A messy 2-seater desk with various objects sitting on top. |
| 2243309 | 평범한 교탁. 아침 조회는 무조건 짧은 게 좋아. | An ordinary podium. Morning assemblies should be short. |
| 2243310 | 교실 벽과 벽 사이를 잇는 기둥. | A pillar that connects classroom walls. |
| 2243311 | 튼튼한 축구 골대. 회오리 슛을 넣어도 찢어지지 않는다. | A sturdy soccer goalpost. No matter how powerful the shots on goal are, the nets will never rip. |
| 2243312 | 음료와 과자가 진열된 교내 자판기.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A vending machine containing drinks and snacks.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243313 | 프리미엄 음료와 고급 과자가 진열된 교내 자판기.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A vending machine containing premium drinks and snacks.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243401 | 사랑을 약속하는 웨딩 단상.<br>기쁠 때나 슬플 때나 서로를 존중하며 함께 할 것을 맹세합니까?<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A wedding platform for oaths of love.<br>Do you swear to be with each other, for better or for worse?<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243402 | 꽃으로 장식한 가제보. 웨딩 촬영 장소로 인기 만점.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A gazebo decorated with flowers. A popular spot for wedding photos.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243403 | 순백색의 그랜드 피아노. <br>감미로운 음악소리와 함께하면 프로포즈 성공률이 올라갈지도.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A pure white grand piano.<br>Playing a beautiful piece may increase your odds of a successful proposal.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243404 | 꽃으로 장식한 웨딩 테이블. 우아한 커틀러리가 놓여있다. <br>어떤 정령의 강력한 요청으로 샴페인도 추가되었다고 한다… | A wedding table decorated with flowers. A beautiful cutlery set sits on top.<br>Due to a particular Soul's rather strong request, champagne was also added. |
| 2243405 | 꽃으로 장식한 웨딩 체어. 하객들을 생각하는 마음이 가득 담겨있다. | A wedding chair decorated with flowers. It's perfect for wedding guests. |
| 2243406 | 꽃으로 장식한 웨딩 체어. 하객들을 생각하는 마음이 가득 담겨있다. | A wedding chair decorated with flowers. It's perfect for wedding guests. |
| 2243407 | 탑처럼 쌓인 화려한 케이크. 당연하지만 한번에 먹지 않아도 된다. | A fancy cake, tall like a tower. Don't worry, you don't have to finish it in one sitting. |
| 2243408 | 꽃이 만발한 울타리.<br>만개한 꽃이 한걸음 한걸음 행복으로 인도하고 있다. | A fence blooming with flowers.<br>The flowers will guide you to a happy path. |
| 2243501 | 화려한 비쥬얼의 칵테일 바. 입간판엔 여름의 미녀가 그려져 있다. <br>요염한 마녀의 능수능란한 입담에 넘어가 과음해 버리지 않도록 주의할 것. <br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다. <br><br>비비안을 오브제에 배치하면 <color="#2d9b00">비비안의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A luxurious cocktail bar. The Summer Witch is drawn on its signboard.<br>Be careful not to overdrink, falling for what the charming witch says.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Vivienne to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2243502 | 거북이도 좋아하는 워터 슬라이드.<br>배 모양 워터 버킷에서 쏟아지는 엄청난 양의 물 폭포를 맞으면 정신이 번쩍 든다고 한다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A water slide that everyone loves, including turtles.<br>Getting soaked by the immense amount of water that falls from the ship-shaped bucket will clear your mind.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243503 | 편리한 이동이 가능한 리조트 카트.<br>무거운 짐은 짐칸에 맡기고 마음 편히 주변 풍경을 감상하자.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A convenient resort cart.<br>Put the heavy load on the trunk and enjoy the surrounding scenery.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243504 | 실내외 겸용 스윔스파. <br>잔잔한 수면은 낮에는 바다를, 밤에는 별하늘을 옮겨놓은 듯 아름답게 일렁이고 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A swim spa that can be used both indoors and outdoors.<br>The ruffling water will remind you of the sea during the day, and a sky full of stars at night.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243505 | 형형색색의 열대과일이 담긴 라탄 바구니.<br>컬러풀한 색상과 맛이 보는 눈과 먹는 입에 행복을 선물한다. | A rattan basket with colorful tropical fruits.<br>Their radiating colors and flavor will satisfy both your eyes and palate. |
| 2243506 | 열대 지방의 상징인 야자수에 조명을 달아 만든 가로등.<br>밤에 보면 더욱 예쁘다. | A street lamp made by attaching a light to a palm tree, a symbol of tropical regions.<br>It looks prettier at night. |
| 2243507 | 여러 가지 튜브를 빌려주는 튜브 대여소. <br>귀여운 동물 튜브부터 형형색색의 비치볼까지! 없는 게 없으니 마음껏 골라보자. | A floaty rental that offers various types of floaty.<br>From cute animal floaties to colorful beach balls! Just pick what you want! |
| 2243508 | 햇빛 걱정 없는 캐노피 베드. <br>바람이 불 때마다 살랑거리는 리넨 캐노피가 빛나는 여름에 운치를 더한다. | A canopy bed that protects you from sunlight.<br>Feel the summer with the linen canopy moving gently in the wind. |
| 2243509 | 매듭을 엮어 장식한 마크라메 파티션. <br>한 땀 한 땀 엮은 매듭에서 장인의 손길이 느껴진다. | A macramé partition curtain decorated with knots.<br>The quality of the knots shows the craftsmanship of a master artisan. |
| 2243510 | 햇살을 피해 쉴 수 있는 2인용 파라솔 테이블. 파라솔 패턴이 멋스럽다. | A parasol table for two where you can cool yourself from the heat. The pattern looks stylish. |
| 2243511 | 여름의 라탄 선베드. <br>건강한 구릿빛 피부도 좋지만, 자외선은 위험하니 선크림을 꼭 바르도록 하자. | Summer rattan sunbed.<br>Tanned skin makes you look healthy, but don't forget to wear sunscreen as UV rays can be dangerous. |
| 2243512 | 푹신한 쿠션이 놓인 흔들의자. <br>불어오는 여름 바람을 맞으며 앉아있으면 나도 모르게 잠에 빠져버릴 것만 같다. | A rocker with a soft cushion.<br>You might fall asleep despite yourself as you sit on this chair and feel the summer breeze. |
| 2243513 | 트로피컬 느낌이 물씬! 아늑하고 포근한 여름 텐트.<br>좋아하는 친구와 밤새도록 도란도란 비밀 이야기를 속삭여 보자. | A cozy summer tent that exudes a tropical atmosphere.<br>Share your secret stories with your favorite friends all night. |
| 2243601 | 해변의 황금빛 거대 모래성.<br>익숙한 모양을 하고 있지만, 어쩐지 기억과 달리 지나치게 화려한 것 같다.<br>햇볕을 받아 따끈한 모래성 위에 누워있으면 잠이 솔솔 쏟아진다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다. <br><br>홍란을 오브제에 배치하면 <color="#2d9b00">홍란의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A giant golden sandcastle on the beach.<br>Although it looks familiar, it feels much more extravagant.<br>Lying on the sandcastle warmed by the sun will make you sleepy.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Honglan to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2243602 | 모래사장 위에서 펼쳐지는 불꽃 튀는 랠리!<br>푹푹 빠지는 모랫바닥도 선수들의 승리욕을 막을 수 없다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A fierce rally at a sandy beach starts!<br>Nothing can stop these competitive players, not even the sinking sand!<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243603 | 선박을 개조해 만든 보트 식당.<br>다양한 해산물 요리를 맛볼 수 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A boat converted into a restaurant.<br>It offers many different seafood dishes.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243604 | 여러 가지 서핑보드를 빌려주는 서핑보드 대여소.<br>오늘은 내가 이 바다의 주인공! 없는 게 없으니 마음껏 골라보자. | A surfboard rental that offers a wide variety of surfboards.<br>Today, I own the sea! You will find anything you want in this rental. |
| 2243605 | 모래알이 반짝거리는 해변 모래 타일. | A beach sand tile with glittering sand. |
| 2243606 | 모래알이 반짝거리는 해변 모래 타일. | A beach sand tile with glittering sand. |
| 2243607 | 모래알이 반짝거리는 해변 모래 타일. | A beach sand tile with glittering sand. |
| 2243608 | 모래알이 반짝거리는 해변 모래 타일. | A beach sand tile with glittering sand. |
| 2243609 | 빛 그물이 아름다운 바다 타일. | A sea tile with beautiful webs of light. |
| 2243610 | 정의로운 선장이 손수 제작한 모험 뗏목.<br>파란 돛이 바람에 따라 펄럭이고 있다. 보물섬은 어디에 있을까?<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | Adventure raft built by a righteous captain.<br>Its blue sail is fluttering in the wind. Where is the treasure island?<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243611 | 조개로 장식한 아름다운 분수.<br>떨어지는 물방울이 진주처럼 반짝거리고 있다. | A beautiful fountain decorated with shells.<br>The water drops are shining like pearls. |
| 2243612 | 뙤약볕으로부터 피부를 보호해 줄 파라솔과 매트.<br>허기를 달래줄 간식거리에서 수녀님의 다정한 센스가 엿보인다. | A beach parasol and mat that will protect your skin from the sun.<br>The little snacks show Sister's kindness. |
| 2243613 | 보물을 가득 담은 작은 조각배.<br>지도에 표시된 장소는 혹시 환상의 보물섬일까? | A small boat full of treasures.<br>What's marked on the map could be a treasure island. |
| 2243614 | 형형색색의 산호 바위.<br>산호와 말미잘 사이로 열대어들이 드나드는 광경을 볼 수 있다. | A colorful coral rock.<br>Tropical fish is swimming through the corals and anemones. |
| 2243615 | 해파리 모양의 풍등.<br>허공에 떠있다. | A sky lantern in the shape of a jellyfish.<br>It's floating in the air. |
| 2243616 | 해파리 모양의 풍등.<br>허공에 떠있다. | A sky lantern in the shape of a jellyfish.<br>It's floating in the air. |
| 2243617 | 해변의 길을 알려주는 이정표.<br>바닷바람이 불어오는 길을 따라 달려가 보자. | A sign that shows you the way to the beach.<br>Let's run down the road and feel the sea breeze. |
| 2243701 | 일국의 공주가 이방인 일행을 위해 준비한 화려한 다과상.<br>음악과 시와 춤이 있으니, 이곳이 바로 극락일지어다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | Refreshments prepared by the princess for foreigners.<br>There's music, poetry, and festivities. What more could one ask for in paradise?<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243702 | 늦은 오후, 가을의 명상 정원.<br>떠돌이 무사는 수행을 통해 깨달음에 다다르고, 결국 한계를 초월한 경지에 이른다…<br>그런 주인공이 나오는 로맨스 소설이 어딘가에 존재할지도 모른다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다. <br><br>아키를 오브제에 배치하면 <color="#2d9b00">아키의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | An autumn meditation garden.<br>A wandering warrior can find enlightenment upon training, and break through his limits...<br>Who knows? There could be a romantic novel about such a character.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Aki to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2243703 | 달떡을 만들 수 있는 절구.<br>달빛을 충분히 받은 쫄깃한 반죽에 별가루를 잔뜩 넣어 만든 달떡은 월묘만이 만들 수 있는 일미이다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A grinding bowl for making special moon rice cakes.<br>Only moon rabbits can create the delicious moon rice cake by adding star powder to the special moonlit mix.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243704 | 왕실의 가무를 책임지는 궁중 악단.<br>귀여워 보이지만 공주를 위한 연회 음악부터 장엄한 제례 의식까지 담당하고 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | The royal family's special band.<br>The adorable band handles festival music for the princess and also handles music for more serious ritual ceremonies.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243705 | 궁중 정원의 돌바닥 타일.<br>색색의 가을 잎사귀들이 돌바닥을 수놓고 있다. | Stone tiles for the court garden.<br>The vibrant autumn leaves cover the stones. |
| 2243706 | 전통 양식을 따른 궁중 가을 연못.<br>연못 중앙의 작은 인공 정원으로 가을의 정취를 물씬 느낄 수 있다. | An autumn pond that follows tradition.<br>The small garden at the center exudes the feeling of autumn. |
| 2243707 | 나라의 대소사를 접할 수 있는 벽보판.<br>정체를 알 수 없는 아름다운 자의 초상화와 토끼의 수배지가 걸려있다.<br>…저렇게 생긴 이가 정말 실존하긴 하는 걸까? | A board that displays all the major events going around the nation.<br>There's a portrait of someone beautiful and also a wanted post for a rabbit.<br>... Someone really looks like that? |
| 2243708 | 우아한 양식의 궁궐 담벼락.<br>빈틈 없이 쌓아 올린 벽돌과 섬세하게 새겨넣은 문양이 멋스럽다. | An elegant looking wall.<br>The details of the patterns give it a sophisticated look. |
| 2243709 | 우아한 양식의 궁궐 관문.<br>멋대로 들어가면 수문장에게 끌려갈지도 모르니 주의하자. | An elegant looking gate.<br>Trespass, and the gatekeeper might take you away. |
| 2243710 | 거리에서 심심치 않게 볼 수 있는 장독대.<br>몸집이 작은 정령 한 명쯤은 거뜬히 들어갈 것 같다. | A platform for crocks.<br>It's large enough for a Soul to go on top of it. |
| 2243711 | 밤하늘의 보름달을 그대로 가져온 듯한 보름달 풍등.<br>달에는 토끼가 산다는 소문이 진짜일까? | A full moon lantern that resembles the full moon of the night skies.<br>Could it really be true that a rabbit lives on the moon? |
| 2243712 | 탐스러운 감이 주렁주렁 달린 감나무.<br>다섯 가지 덕목을 모두 갖춰 문무충효절의 나무라고도 불린다고 한다. | A persimmon tree with delicious persimmons hanging on it.<br>They say it represent loyalty and filial piety. |
| 2243713 | 궁궐 전통 향로.<br>연기가 피어오르는 모습이 달안개를 닮았다 하여 달안개 향로라는 이름이 붙여졌다. | A traditional incense burner.<br>Its name comes from how the rising smoke resembles fog. |
| 2243801 | 깊은 숲속의 그림자 극장. 무대 위에선 그림자 늑대와 그림자 헌터가 싸우고 있다.<br>무수히 많은 객석 사이 관객은 나 혼자뿐이다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A shadow wolf and a shadow hunter fight on top of the stage of the shadow theater.<br>There are countless seats, yet I am the only audience.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243802 | 마녀의 특제 연금 솥단지. 마녀의 곰돌이 조수가 열심히 솥을 휘젓고 있다.<br>「다음에 넣을 재료는… 웨어울프의 손톱과 헌터의 뿔이군.」<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | The witch's teddy assistant is stirring the pot.<br>"The next ingredient we need is a werewolf's fingernail and a hunter's horns."<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243803 | 사납고 고독한 늑대를 가둬두기 위한 철창.<br>피보다 붉은 장미 넝쿨이 시리도록 차가운 창살을 뱀처럼 휘감고 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A cage used to trap wild, lonely wolves.<br>The blood-colored red roses are wrapped around the cold bars of the cage.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243804 | 흑백합이 만개한 정원.<br>떠도는 소문으로, 정원의 흑백합은 유명한 흑백합 농원에서 최고급 품종만을 공수한 것이라고 한다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다. <br><br>리젤로테를 오브제에 배치하면 <color="#2d9b00">리젤로테의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A garden filled with black lilies.<br>Rumors say that the lilies in this garden are top-quality lilies that come from a famous lily plantation.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Lizelotte to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2243805 | 부드러운 벨벳 보가 깔린 고풍스러운 테이블.<br>피처럼 붉은 포도주와 음식들을 입에 머금자 어쩐지 조금 비릿한 맛이 느껴진다… | An antique table with a soft velvet cloth.<br>There's something about the blood-colored wine and food that taste a little...bloody. |
| 2243806 | 고풍스러운 벨벳 의자. 만찬의 손님을 위해 준비되었다.<br>기꺼이 착석해 밤의 만찬을 즐겨보도록 하자. | An antique velvet chair prepared for a guest at a feast.<br>Have a seat and enjoy the feast. |
| 2243807 | 앤티크한 양식의 철제 펜스.<br>첨예하게 벼려진 철제 장식을 보고 있으면 뒷목이 서늘해진다. | An antique iron fence.<br>There's something creepy about the iron decorations that make your hair stand. |
| 2243808 | 앤티크한 양식의 철제 대문.<br>가까이 다가가면 소름 끼치는 쇳소리가 방문객을 반겨준다. | Antique iron gates.<br>The gates open up with a chilling sound that will send chills down your spine. |
| 2243809 | 기묘한 생김새의 나무.<br>멀리서 바라보면 마치 머리카락을 풀어 헤친 여인의 모습처럼 보인다. | A tree with a strange appearance.<br>From afar, it looks like a woman, her hair untied and disheveled. |
| 2243810 | 어둠을 밝혀주는 가로등.<br>암흑 속의 유일한 불빛을 따라가 보자. 단, 절대 뒤돌아보지 말 것. | A lamp that brightens the dark.<br>Follow the only light in the darkness, but make sure you don't look back. |
| 2243811 | 음산한 분위기의 극장 매표소.<br>아무런 인기척도 느껴지지 않는다. | A somber box office.<br>There seems to be no one inside. |
| 2243812 | 흐드러지게 핀 흑백합 화분.<br>앤티크한 화분 모양이 고풍스럽다. | A flowerpot with blooming black lilies.<br>It's antique shape feels stylish. |
| 2243813 | 랜턴을 들고 있는 묘지기 유령. 암흑 속에서 불쑥 나타나 방문객을 놀라게 하곤 하지만,<br>사실은 그저 발밑을 밝혀주고 싶었던 것뿐이라고 한다. | A Grave Keeper Ghost holding a flashlight. It suddenly appears from the darkness and surprises you,<br>but it's only trying to flashlight on your steps. |
| 2243901 | 에덴의 모든 착한 정령들에게 선물을 준다는 성자聖者의 썰매.<br>어마어마한 선물 꾸러미를 싣고 우주를 횡단해야 하는 순록 역할은 귀여운 캐럿이 맡았다.<br>힘내라, 캐럿!<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | The sleigh of a saint who brings presents to all good Souls in Eden.<br>Adorable Carrot has bravely taken up the role of the reindeer, crossing the universe with a huge load of presents.<br>You can do it, Carrot!<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243902 | 상냥하고 따스한 어느 수녀님의 기도 장소.<br>온 거리가 축제 불빛으로 가득 찬 날에도, 모두의 행복과 평화를 비는 수녀님의 기도는 계속되고 있다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다. <br><br>캐서린을 오브제에 배치하면 <color="#2d9b00">캐서린의 체력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | The prayer space of a kind and warm-hearted nun.<br>Even on days when the streets are filled with festive lights, the nun's prayers for everyone's happiness and peace continue.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Catherine to it to <color="#2d9b00">increase her HP by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2243903 | 익숙한 모양의 푹신푹신 거대 곰인형.<br>아주 많은 포옹과 가장 좋아하는 벌꿀 케이크를 선물 받은 곰인형이 행복한 표정을 짓고 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A giant teddy bear, fluffy and cuddly in its familiar form.<br>Showered with countless hugs and its favorite honey cake, the bear is beaming with happiness.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2243904 | 황홀한 겨울의 빛, 소원이 담긴 아름다운 트리.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A tree bathed in the mesmerizing light of winter, resplendent with heartfelt wishes.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2243905 | 밤사이 내린 눈으로 덮인 벽돌 타일.<br>미끄러지지 않게 조심하는 게 좋다. | Brick tiles covered with overnight snow.<br>Caution is advised to prevent slipping. |
| 2243906 | 밤사이 내린 눈으로 덮인 벽돌 타일.<br>미끄러지지 않게 조심하는 게 좋다. | Brick tiles covered with overnight snow.<br>Caution is advised to prevent slipping. |
| 2243907 | 별빛 모빌이 반짝반짝 빛나는 아치.<br>밤에 보면 더욱 아름답다. | An arch adorned with dazzling starlight mobiles.<br>It's even more beautiful at night. |
| 2243908 | 모양이 제각각인 선물 꾸러미.<br>크다고 무조건 좋은 선물이 아님을 명심하자! | Each gift bundle comes in its own unique shape.<br>Remember, bigger doesn't always mean better! |
| 2243909 | 모양이 제각각인 선물 꾸러미.<br>크다고 무조건 좋은 선물이 아님을 명심하자! | Each gift bundle comes in its own unique shape.<br>Remember, bigger doesn't always mean better! |
| 2243910 | 눈이 오나 비가 오나 항상 행복한 눈사람.<br>설령 녹아 없어진대도 언제나 당신의 친구일 것이다. | This happy snowman remains cheerful through snow and rain.<br>Even if it melts away, it will always be your friend. |
| 2243911 | 벽난로에 장식된 소원 양말.<br>머리맡에 원하는 선물을 적은 쪽지를 두고 잠에 들면, 다음 날 누군가가 양말 속에 바라던 선물을 담아둔다고 한다. | A stocking adorning the fireplace, filled with wishes.<br>It is said that if you go to sleep with a note of your desired gift by your bedside, someone will place the wished-for gift in your stocking the next day. |
| 2243912 | 눈싸움의 필승 전략은 바로 물량 공세!<br>여러 가지 모양의 눈덩이들을 잔뜩 만들어 보자. | The key to winning a snowball fight is stockpiling your ammo!<br>Let's make an assortment of uniquely shaped snowballs. |
| 2243913 | 멋들어진 리본을 두른 귀여운 눈오리.<br>어쩐지 등에 올라타고 싶어진다. | An adorable snow duckling with a fancy bow.<br>Seems perfect for a playful ride. |
| 2243914 | 호랑가시나무로 장식한 양초.<br>작은 불빛이 따스하게, 또 환하게 밤을 밝히고 있다. | A candle decorated with holly.<br>Its small flame illuminates the night with its warm, gentle glow. |
| 2243915 | 교회의 벤치.<br>흔하게 볼 수 있는 벤치이지만, 오늘만큼은 리본과 꽃다발로 잔뜩 꾸며놓았다. | A church pew bench.<br>Originally a common simple bench, now transformed with an abundance of bows and flowers. |
| 2244001 | 크루즈의 선교.<br>최신 마도 공학 기술을 아낌없이 사용해 제작한 대형 스크린에서 마치 밤하늘을 그대로 옮겨온 듯한 생생함을 느낄 수 있다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | Cruise bridge.<br>The massive screen was built with cutting-edge Magitechnology, displaying a lifelike view of the night sky.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244002 | 정교하게 설계된 피뢰탑. 거대한 혼천의는 특수한 장치로 제작되어 뇌운을 감지할 수 있다고 한다.<br>정상에 설치된 피뢰침은 낙뢰의 방향을 유도하고 그로 인해 발생한 전기 에너지를 저장하는 역할을 하고 있다.<br>축적된 에너지는 어느 강력한 정령의 에너지원이 되기도 한다고.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>클라우디아를 오브제에 배치하면 <color="#2d9b00">클라우디아의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | An intricately designed lightning tower. The armillary sphere is supposedly engineered with a special device that can detect storm clouds.<br>The rod at the peak not only redirects lightning strikes but also harvests the resultant electrical power.<br>The stored energy can sometimes energize a certain powerful Soul.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Claudia to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244003 | 크루즈 갑판 위의 야외 수영장. 화이트 대리석 프레임이 고급스럽다.<br>수영장 바닥에 깔린 금가루가 빛을 반사해 반짝거리는 모습을 볼 수 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | An outdoor swimming pool on the cruise deck. The white marble frame is exquisite.<br>The bottom of the pool, sprinkled with gold dust, glistens as it reflects the light.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244004 | 별빛을 가르는 선장의 항해실. 최신 마도 공학으로 제작된 패널에서 별자리 항로가 반짝이고 있다.<br>자, 다음 목적지는 어딜까?<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | The captain's cabin, where they navigate through the stars. Constellation routes light up on a panel crafted with state-of-the-art Magitech engineering.<br>What's the next stop?<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244005 | 고급스러운 대리석 타일. 젖은 발로 걸으면 미끄럽다. | Luxurious marble tile. Very slippery when walked on with wet feet. |
| 2244006 | 황금빛 샴페인이 담긴 쿠페 잔을 높게 쌓은 화려한 샴페인 타워.<br>춤추자, 마시자, 즐기자! | A magnificent champagne tower, stacked high with coupe glasses brimming with golden champagne.<br>Let's dance, drink, and enjoy! |
| 2244007 | 크루즈 파티의 분위기를 장식하는 그랜드 하프.<br>때때로 양손으로 현을 튕기는 것보다 페달을 연주하는 것이 더 힘들다고 한다. | A grand harp, the centerpiece of the cruise party's ambiance.<br>It is said that, sometimes, mastering its pedals can be more challenging than strumming its strings. |
| 2244008 | 고급스러운 대리석 재질의 크루즈 펜스.<br>의외로 틈이 넓으니 몸을 너무 기대지 말자. | A luxurious marble cruise fence.<br>The gaps are wider than they seem, so avoid leaning on it too much. |
| 2244009 | 화려한 스탠드 조명. 눈부신 불빛에 낮과 밤도 잊어버릴 것만 같다. | An ornate stand light. Its dazzling light could make you lose track of day and night. |
| 2244101 | 스페셜 메뉴 주문 시 제공되는 라이브 퍼포먼스 무대.<br>귀여운 메이드들이 선사하는 최고의 서비스를 받아보자!<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A live performance stage provided when ordering a special menu.<br>Experience the best service offered by cute maids!<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244102 | 사랑스러운 마술사의 앤티크 턴테이블.<br>마술쇼에 어울리는 신나는 음악이 흘러나오고 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A lovely magician's antique turntable.<br>Fills the air with lively music perfect for a magic spectacle.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244103 | 평범한 소녀에서, 당신만을 위한 메이드로 변신할 수 있는 특별한 공간.<br>당연하지만, 훔쳐보기는 금지!<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A special space where an ordinary girl can transform into your personal maid.<br>Needless to say, peeping is a definite no-no!<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244104 | 소연과 구원자가 세운 초콜릿 생산 공장. 비경 내부에 자리 잡고 있다.<br>참고로, 현재 소연은 「나 혹시… 제이드 상단을 뛰어넘는 억만장자가 돼버리는 거 아냐? 대, 대성만두는 어떡하지?」라며 걱정하고 있다고 한다.<br>…누군가는 진실을 이야기해 주는 게 좋겠지?<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>소연을 오브제에 배치하면 <color="#2d9b00">소연의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | Xiaolian and Savior's chocolate factory, nestled within a Scenic Instance.<br>By the way, Xiaolian is fretting over the possibility of becoming a billionaire with their business surpassing the Jade's Merchants' Guild and wondering about what might happen with the Daesung Dumplings.<br>Maybe...somebody should set the record straight.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Xiaolian to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244105 | 앤티크한 디자인의 디저트 카페 테이블.<br>맛있어지는 주문은 특별한 서비스. | A dessert cafe table with an antique design.<br>Casting a spell for taste perfection is part of a special service. |
| 2244106 | 메이드가 주인님을 위해 준비한 고풍스러운 벨벳 소파.<br>기꺼이 착석해 최고의 접대를 받아보자. | An elegant vintage velvet sofa prepared by the maid for the master.<br>Sit back and savor the epitome of refined service. |
| 2244107 | 주인님을 위해 메이드가 애정을 듬뿍 담아 준비한 디저트 트레이.<br>완벽한 티 타임을 위해 메이드는 오늘도 노력한다. | A dessert tray lovingly crafted by the maid for the master.<br>The maid works hard every day for a perfect tea time. |
| 2244108 | 앤티크한 디자인의 카페 진열대.<br>보는 것만으로도 달콤한 향기가 느껴지는 디저트들이 잔뜩 진열되어 있다. | A cafe display case with an antique design.<br>Overflows with desserts whose sweet aromas fill the air. |
| 2244109 | 초콜릿 봉봉이 들어있는 귀여운 상자.<br>모양도 맛도 완벽하다. | A cute box containing chocolate bonbons.<br>Flawless in design and divine in taste. |
| 2244201 | 운동장 중앙에 위치한 무대 겸 조례대.<br>벚꽃이 흩날리는 입학식, 아름다운 학생회장의 연설과 함께 우리의 청춘이 시작되고 있다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A lectern on a stage in the center of the school's sports field.<br>Another school year begins for the youth, accompanied by fluttering cherry blossoms and a beautiful speech from the student president.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244202 | 손재주가 좋은 어느 학생이 관리하는 교내 생태 사육장.<br>셔츠 단추 관리는 서툴어도, 사육장 관리는 맡겨만 주시라.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | An animal facility run by a resourceful student.<br>While she may be clumsy when it comes to her shirt buttons, she provides exceptional care for all the critters.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244203 | 교내 양호실. 털털하고 유능한 양호 선생님이 상주하고 있다.<br>꾀병은 금방 들킨다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | The school infirmary staffed by an easygoing and competent nurse.<br>Nobody can fool her with a fake sickness.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244204 | 영원한 학생회장, 유리아의 학생회실.<br>학교의 수호자는 오랜 기다림으로 인해 어둠에 삼켜져 버리고 말았다.<br>자, 참회하라, 무릎을 꿇어라, 총무부장이여…!<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>유리아를 오브제에 배치하면 <color="#2d9b00">유리아의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | The student council office, where Yuria, the everlasting student president, presides.<br>The guardian of the school has been consumed by darkness after a long wait.<br>Now, repent and kneel, Student Secretary...!<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Yuria to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244205 | 운동 후의 갈증을 달래줄 학교 음수대.<br>우연히 마주친 체육부의 그 아이, 나에게 관심이 있는 걸까? | The school's water fountain, where students can quench their thirst after exercise.<br>Could the PE club member I ran into there be interested in me? |
| 2244206 | 교정 뒤편에 있는 소각로.<br>생활 쓰레기 외 다른 물건을 넣으면 안 된다. | A waste incinerator behind the schoolyard.<br>Only general school waste is permitted inside. |
| 2244207 | 화단에 둘러싸인 학교 시계탑.<br>왜인지 시곗바늘이 3시 30분에 멈춰있다. | The school's clock tower, encircled by flower beds.<br>For some reason, the clock hands are stuck at 3:30. |
| 2244208 | 학교 교문. <br>신입생 여러분, 에버스쿨에 오신 것을 환영합니다! | The school gate.<br>New students, welcome to Everschool! |
| 2244209 | 학교 담벼락.<br>지각생들이 자주 넘나들기 때문에 바른생활부장이 항상 감시하고 있다. | School wall.<br>It is under constant surveillance by the Ethics Director since tardy students often climb over it. |
| 2244210 | 벚나무를 둘러싼 벤치. 점심시간의 인기 장소다. | Bench surrounding a cherry tree. It is a popular lunch spot. |
| 2244211 | 꽃이 만발한 벽돌 화단.<br>미화부의 세심한 관리로 항상 생기가 넘친다. | Brick flower bed in full bloom.<br>Always kept lush thanks to the dutiful care of the School Aesthetics Club. |
| 2244301 | 날이 저물면 축제의 하이라이트 행사가 개최되는 무대.<br>보는 이를 압도하는 화려함이 인상적이다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A stage where the festival's main event is held as the evening sets in.<br>Its magnificent splendor captivates and impresses all who see it.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244302 | 액운을 쫓아내기 위한 거대 고양이 인형 등불.<br>형형색색의 종이를 이어 붙여 만든 수공예 작품으로, 섬세함과 박력이 느껴진다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A giant cat lantern to ward off bad luck.<br>A handcrafted piece made by attaching colorful pieces of paper, exuding refinement and vitality.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244303 | 운치 있는 대나무 연못 다리.<br>형형색색의 비단잉어가 유유히 헤엄치고 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A scenic bamboo bridge over a pond.<br>Vibrantly colored koi swim leisurely beneath it.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244304 | 보통 신이 타고 있다고 여겨지는 축제 가마.<br>이번 여름 축제에서는 특별한 게스트를 위해 준비되었다. | A festival palanquin often thought to be carrying gods.<br>It's been prepared for special guests at this Summer Festival. |
| 2244305 | 푸짐한 경품이 가득한 사격 노점.<br>좋아하는 사람에게 멋진 모습을 보여줄 수 있는 찬스. 반드시 1등상을 노린다! | A shooting booth offering numerous prizes.<br>This is a chance to impress your crush. Aim for the first prize! |
| 2244306 | 다양한 가면이 진열된 노점.<br>두근거리는 마음은 가면으로 숨길 수 없지만, 잔뜩 핀 홍조 정도는 가릴 수 있을지도 모른다. | A booth displaying various masks.<br>While a mask can't fully hide what's in the heart, it may at least cover a deep blush. |
| 2244307 | 물풍선 낚시와 금붕어 낚시를 할 수 있는 낚시 노점.<br>쉬워 보이지만 의외로 매우 어렵다고 한다. 용돈을 전부 탕진하지 않도록 주의하자. | A fishing booth where you can try water balloon fishing and goldfish scooping.<br>It looks easy but is surprisingly difficult. Don't blow all your allowance in one go. |
| 2244308 | 문어빵을 판매하는 노점.<br>푸짐한 토핑이 잔뜩 들어간 동그란 문어빵! 축제의 명물이라고 할 수 있다. | A booth selling octopus balls.<br>Round takoyaki loaded with tasty toppings is a true festival staple. |
| 2244309 | 빙수를 판매하는 노점.<br>곱게 간 얼음 위에 시럽을 뿌린 단순한 빙수지만 어쩐지 계속 먹게 된다. | A booth selling shaved ice.<br>The finely shaved ice topped with syrup is simple but irresistibly delicious. |
| 2244310 | 디저트를 판매하는 노점.<br>사과 사탕을 먹을 때는 이를 다치지 않도록 조심하자. | A booth selling sweet treats.<br>Just remember to be careful with the candy apples to avoid any dental disasters. |
| 2244311 | 소원을 적어 대나무에 장식한 단책.<br>그 아이와 오래오래 함께하게 해주세요. | A piece of paper containing wishes hanging on bamboo.<br>May this relationship last as long as possible. |
| 2244312 | 수국이 만개한 화단.<br>비가 오면 더욱 아름답다. | A flowerbed of hydrangeas in full bloom.<br>Looks even more beautiful when it rains. |
| 2244313 | 나팔꽃이 피어있는 대나무 벤치.<br>아침 이슬을 잔뜩 머금었다. | A bamboo bench surrounded by morning glories.<br>The flowers are sparkling with morning dew. |
| 2244314 | 대나무로 만들어진 시원한 여름 평상.<br>평상 위에 누워 먹는 수박은 행복의 맛! | A breezy bamboo platform for summer.<br>Eating watermelon while lying on it is pure bliss! |
| 2244315 | 밤길을 환하게 비춰주는 등불 가로등.<br>가로등 빛이 닿는 얼굴마다 환한 웃음꽃이 피어 있다. | A street lamp with a lantern illuminating the night.<br>Every illuminated face is filled with a joyful smile. |
| 2244316 | 방문객들을 가장 먼저 맞이하는 축제 아치.<br>모두에게 잊을 수 없는 축제가 되길 바라는 마음으로 자리를 지키고 있다. | An archway that is the first thing to greet festival-goers.<br>It holds its place with the hope that the festival will be unforgettable for everyone. |
| 2244401 | 결혼식의 주인공, 신부의 대기실.<br>예식이 시작되기 전, 하객과 신부가 처음 마주하는 장소이기도 하다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | The waiting room of the bride, the most celebrated person of the wedding.<br>This is where the bride meets the guests before the ceremony begins.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244402 | 웨딩 포토 스튜디오.<br>행복한 순간을 사진으로 기록할 수 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | Wedding photo studio.<br>The place where happy moments are captured in photographs.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244403 | 세 정령을 향한 구원자의 완벽한 프로포즈 존.<br>성공의 비법 하나, 가장 적절한 타이밍으로 상대의 마음을 사로잡을 것. <br>자, 하트를 노려라!<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | Savior's perfect proposal spot for any of the three Souls.<br>The trick is to find the most opportune time to win her heart.<br>Aim to win her heart!<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244404 | 세 신부가 특수 제작한 결혼 예물. 마치 거대한 새장처럼 보인다.<br>아름다운 디자인과 달리 섬뜩한 구속구가 달려있다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>비올레트를 오브제에 배치하면 <color="#2d9b00">비올레트의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A unique wedding present crafted by the three brides. Looks like a giant birdcage.<br>While beautifully designed, it also features an ominous restraining device.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Violette to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244405 | 꽃길을 거니는 웨딩 마차.<br>느리게 달리는 마차 주변으로 들러리 아르바이트생이 꽃가루를 뿌리고 있다. | A wedding carriage upon a floral trail.<br>Hired flower girls are scattering petals around the leisurely pace of the carriage. |
| 2244406 | 고급스러운 벨벳 재질의 직선 레드 카펫. | A straight red carpet of a luxurious velvet material. |
| 2244407 | 고급스러운 벨벳 재질의 단색 레드 카펫. | A solid red carpet of a luxurious velvet material. |
| 2244408 | 웨딩 사진이 걸려있는 스탠드형 액자.<br>예식장에 들어선 하객들이 가장 먼저 마주하는 사랑의 증표. | A freestanding frame displaying a wedding photo.<br>The first symbol of love guests see upon entering the wedding hall. |
| 2244409 | 들러리로 취직한 캐럿 인형.<br>몸이 둘로 나뉘었지만 바쁜 건 여전하다. 소문으론 무급 아르바이트라고 한다. | Carrot serving as the bridesmaid.<br>Still busy as ever even when divided into two. Apparently, she's not getting paid for this gig. |
| 2244410 | 하트 모양의 2인용 욕조.<br>따뜻한 욕조에 몸을 담근 채 칵테일 한잔을 기울여보자. | A 2-person bathtub shaped like a heart.<br>Sip on a cocktail while immersed in a warm bath. |
| 2244411 | 꽃으로 장식한 웨딩 벤치.<br>많은 인원을 수용할 수 있다. | A wedding bench adorned with flowers.<br>Seats quite a few people. |
| 2244412 | 예식장 입구를 장식하는 웨딩 아치.<br>바람에 울려 퍼지는 종소리가 하객들을 반기고 있다. | A decorative wedding arch framing the entrance of the wedding hall.<br>The gentle toll of bells carried by the wind welcomes the guests. |
| 2244501 | 무언가를 지키고 서 있는 허수아비 무리.<br>뜻을 알 수 없는 문양이 그려진 부적이 이리저리 널려있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A cluster of scarecrows standing guard over something.<br>Charms bearing mysterious symbols are strewn about.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244502 | 누군가의 무덤. 아주 오래전부터 존재했던 것 같다.<br>묘비에 적힌 이름은 풍화되어 알아볼 수 없다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A seemingly ancient grave of someone.<br>The name on the tombstone has eroded beyond recognition.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244503 | 이제는 아무도 찾아오지 않는 빛바랜 성당.<br>곧 무너질 것 같은 이질적인 양식의 건물 내부에는 아름다운 여신상만이 홀로 서 있다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A derelict cathedral abandoned by all.<br>Within its crumbling, oddly styled walls, a lone statue of a goddess stands, exuding beauty.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244504 | 낡고 기이한 저택. 오래 방치된 듯하다.<br>바람 때문인지, 아무도 없는 저택 중앙에 놓인 흔들의자가 느리게 흔들리고 있다. <br>그래. 지금 들리는 피아노 연주도, 아마 바람 때문이겠지…<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>이브를 오브제에 배치하면 <color="#2d9b00">이브의 체력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A decrepit and eccentric mansion, seemingly abandoned for ages.<br>Amidst its solitude, a rocking chair in the center moves slowly, possibly stirred by the wind.<br>The sound of the piano is probably just another trick of the breeze...<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Eve to it to <color="#2d9b00">increase her HP by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244505 | 숲 한가운데 버려진 거울.<br>깨진 조각마다 비치는 얼굴이 당신을 쳐다보고 있다.<br>너무 오래 바라보지는 말자. | A discarded mirror in the middle of a forest.<br>In every broken piece, a face peers back at you.<br>Best not to stare back for too long. |
| 2244506 | 밤길을 밝히는 낯선 자의 불빛.<br>마치 길 잃은 나그네를 부르는 손짓 같기도 하다. | A stranger's light illuminating the night path.<br>It almost looks to be beckoning to a lost traveler. |
| 2244507 | 밀짚인형이 묶여있는 기묘한 나무.<br>매일 밤, 긴 머리의 여자가 찾아와 나무에 못질한다는 소문이 있다. | An eerie tree bound with a straw effigy.<br>Rumor has it that each night, a woman with long, straight hair visits to hammer nails into the wood. |
| 2244508 | 귀신이 나올 것 같은 우물. 실수로 빠지기라도 하면 큰일이다.<br>설마 이런 외진 곳에서 우물에 빠지는 사람은 없겠지? | A well that seems haunted. An accidental plunge could be disastrous.<br>Surely, no one would meet such a fate in this secluded spot? |
| 2244509 | 깊은 숲속에서 발견한 폐가.<br>녹슨 도끼와 쇠사슬이 섬뜩하다. | An abandoned cabin discovered deep within the woods.<br>The rusted axe and chains cast a sinister air. |
| 2244510 | 낡은 나무 울타리. 이상하게 시선이 느껴지는 것 같다. | A weathered wooden fence. Strangely, it feels like it's watching me. |
| 2244511 | 발자국이 찍힌 흙바닥. 깊은 숲속으로 이어져 있다.<br>발자국의 주인공은 어디로 가고 있는 걸까? | A tile of soil with footprints, leading deep into the forest.<br>Where could the traveler be headed? |
| 2244601 | 환상적인 서커스가 시작되는 중요한 장소, 분장실.<br>화장품, 거울, 깃털, 가면 등 필요한 모든 것이 준비되어 있다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | The dressing room, a vital spot where the circus magic comes alive.<br>Stocked with cosmetics, mirrors, feathers, masks, and everything else one could need.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244602 | 화려하고 아름다운 서커스 마차.<br>창문에 찍힌 손자국은 누구의 손자국일까?<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A stunningly ornate circus carriage.<br>Whose handprint is that on the window?<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244603 | 서커스의 하이라이트, 칼 던지기를 위한 무대.<br>묘기의 희생양은 누군가를 닮은 토끼 인형.<br>어지러울 수 있으니 돌아가는 원판을 오래 보지 말자.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A stage for thrilling knife-throwing, the highlight of the circus.<br>The target is a stuffed bunny that looks oddly familiar.<br>Avoid looking at the spinning wheel too long, or you might get dizzy.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244604 | 바니 서커스단의 쇼가 시작되는 화려한 무대.<br>아슬아슬한 중심 잡기 쇼가 시작되면 박수가 절로 쏟아질 것이다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>루테를 오브제에 배치하면 <color="#2d9b00">루테의 방어력이 12% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A spectacular stage where the Bunny Circus troupe's show takes flight.<br>When the breathtaking balancing act begins, the applause will be unstoppable.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Lute to it to <color="#2d9b00">increase her DEF by 12%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244605 | 알록달록 장식된 대포.<br>언제 터질지 모르니 조심해야 한다. | A cannon with colorful decorations.<br>Watch out since you never know when it might go off. |
| 2244606 | 풍선을 판매하는 카트.<br>동심으로 돌아간 기분을 느낄 수 있다. | A cart selling balloons.<br>Makes you feel like a kid again. |
| 2244607 | 사자에게 잡아먹힐 수 있는 포토존.<br>패널 뒤쪽으로 가면 얼굴을 넣어볼 수 있다.<br>사자의 얼굴이 어쩐지 익숙한 것 같은데...? | A photo spot where you can look like a lion's next meal.<br>Stand behind the panel and place your face through the hole.<br>That lion's face seems oddly familiar... |
| 2244608 | 손님을 환영하는 풍선 인형.<br>귀여운 가면을 쓰고 있지만 그 가면 뒤엔… | A balloon figure welcoming visitors.<br>Behind that adorable mask, however... |
| 2244609 | 흑백 체크무늬 타일.<br>어떤 장소도 화려한 분위기로 만들어준다. | Black-and-white checkered tiles.<br>Bring a touch of elegance to any space. |
| 2244610 | 묘기를 위해 준비된 불타는 링.<br>하지만 어쩐지 뜨겁지 않다. 예산이 부족한 걸까? | A fiery ring set up for daring stunts.<br>For some reason, it doesn't feel hot. Budget cuts, perhaps? |
| 2244611 | 레버를 돌리면 인형이 튀어나오는 깜짝 상자와 장난감.<br>나만의 미니 서커스 공연을 해보자! | Crank the handle, and a surprise figure pops out.<br>Perfect for staging your own little circus act! |
| 2244612 | 서커스 천막 앞에 설치된 열기구.<br>열기구를 타고 하늘로 올라가면 세상이 다르게 보인다. | A hot air balloon stationed by the circus tent.<br>Float up high in the air, and the world takes on a whole new view. |
| 2244701 | 장난감을 가득 실은 기차.<br>칙칙폭폭! 다음엔 누구에게 선물을 줄까?<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A train packed with toys.<br>Choo-choo! Who will be the next to get a present?<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244702 | 선물 상자 속 장난감이 만들어지는 공장.<br>잘못 건드리면 고장 날 수 있으니 조심하자.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A factory producing toys for gift boxes.<br>Handle with care, as any mistake could cause a malfunction.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244703 | 집 모양 패키지 상자.<br>상자 안에 들어가면 장난감이 된 기분을 느낄 수 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A package box shaped like a house.<br>Stepping inside can make one feel like a toy.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244704 | 산타가 선물을 나눠주는 크리스마스 광장.<br>썰매를 끄는 두 마리의 양이 아주 귀엽다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>라리마를 오브제에 배치하면 <color="#2d9b00">라리마의 체력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A Christmas plaza where Santa hands out presents.<br>The two sheep pulling his sleigh are irresistibly cute.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Larimar to it to <color="#2d9b00">increase her HP by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244705 | 따뜻한 날씨에 녹아버린 눈사람.<br>태양을 올려다보는 눈이 슬퍼 보인다. | A snowman melting away in the warmth of the day.<br>Its sad eyes are fixed on the sun. |
| 2244706 | 겨울 명절에 만날 수 있는 통나무 모양 케이크.<br>귀여운 쿠키 장식이 올려져 있다. | A log-shaped cake for the winter holidays.<br>It is garnished with adorable cookies. |
| 2244707 | 칼라르 기술로 만든 특별한 트리.<br>아슬아슬 위험해 보이지만 정확하게 계산된 각도로 유리가 쌓아 올려져 있으니 모두 안심하시길! | A special Christmas tree built with Chalar technology.<br>Although it may appear unstable, every glass layer is meticulously arranged at exact angles. |
| 2244708 | 정원을 지키는 노움들.<br>그들의 표정을 읽을 수 있는 정령은 아무도 없다. | Gnomes guarding the garden.<br>No Soul can read their faces. |
| 2244709 | 달콤한 과자로 지어진 집.<br>산타클로스도 오늘 밤은 기둥이 부서지지 않게 조심해야 한다. | A house made of sweet treats.<br>Santa had better watch his step tonight to keep the walls intact. |
| 2244710 | 새하얀 눈에 찍힌 동물의 발자국.<br>눈으로 만든 도화지에 자국을 남기고 싶다면 발이 빨라야 한다. | Animal pawprints left on pristine white snow.<br>One needs to move fast to leave their own mark on this frosty canvas. |
| 2244711 | 커다란 장난감 병정 인형.<br>그는 언제나 꼿꼿하게 허리를 펴고 서 있다. | A large toy soldier figure.<br>Standing proud and tall, his back is always straight. |
| 2244801 | 신년제를 맞이해 제이드가 마련한 드레스 부티크.<br>진열된 드레스는 단 한 벌뿐인 한정 상품으로, 아름다운 디자인뿐만 아니라 우수한 품질을 자랑한다고.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A dress boutique opened by Jade in celebration of the New Year's Festival.<br>Each dress on display is a one-of-a-kind limited item, boasting stunning designs and top-notch quality.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244802 | 대형 윷놀이판. 직접 윷말이 되어 움직이는 「윷말 체험」이 가능하다.<br>소문으로는, 원래는 「윷말 체험」이 아닌 「윷 체험」이었다고 한다.<br>당연히 위험성이 높아 기각되었다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A life-sized yutnori board where you can play as a yut token yourself.<br>Rumor has it that the initial concept involved players becoming the yut sticks instead,<br>but it was rejected for obvious safety reasons.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244803 | 개회사를 위해 준비된 단상.<br>각국 수장들의 카리스마 있는 연설에 장내의 모두가 주목했다고 한다.<br>다만, 바들바들 떠는 금발의 국왕만은 예외였다는 모양이다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A podium set for the opening ceremony.<br>While the charismatic speeches of leaders from various nations captivated the audience,<br>the trembling blonde queen stood out as the exception.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244804 | 가온에서 주최한 서예 대회장.<br>가장 아름다운 붓글씨를 쓴 자를 가리는 대회로, 예선전을 통과한 도전자는 캐서린과의 대결을 펼칠 수 있다.<br>참고로, 아직 캐서린을 넘은 우승자는 없다고 한다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>캐서린(광휘)를 오브제에 배치하면 <color="#2d9b00">캐서린(광휘)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A calligraphy contest venue of Gaon.<br>Participants vie for the title of the finest brush artist. Those who make it through the preliminaries earn the chance to challenge Catherine,<br>though it's worth noting that no one has ever bested her.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Catherine (Radiance) to it to increase <color="#2d9b00">her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244805 | 식혜가 흐르는 떡 분수. <br>달짝지근한 식혜와 함께라면 끊임없이 떡을 먹을 수 있다! | A rice cake fountain with streams of a sweet rice drink.<br>With every bite of rice cake paired with the sweet rice drink, the feast never ends! |
| 2244806 | 동백의 절개가 느껴지는 단아한 테이블. | A refined table exuding the steadfast dignity of the camellia flower. |
| 2244807 | 동백의 절개가 느껴지는 단아한 의자. | A refined chair exuding the steadfast dignity of the camellia flower. |
| 2244808 | 동백꽃이 그려진 아름다운 병풍.<br>장인이 손수 만든 고급품이다. | A beautiful folding screen featuring painted camellia flowers.<br>It is a masterpiece crafted by a skilled artisan. |
| 2244809 | 깔끔한 디자인의 동백 좌등.<br>흐드러지게 핀 동백이 축제의 밤을 밝혀준다. | An elegantly simple camellia lantern stand.<br>The flourishing camellias cast a warm glow over the festive evening. |
| 2244810 | 신비로운 색상의 대리석 타일. | A marble tile of mystical colors. |
| 2244811 | 추위에도 지지 않고 붉게 핀 동백나무.<br>동백나무는 꽃이 질 때 꽃잎이 아닌 꽃송이 째로 떨어진다는 특징이 있는데, 이는 절개를 상징한다고 한다. | Even in the cold, the camellia tree blooms a vibrant red.<br>Its unique trait of flowers dropping whole rather than shedding petals is often seen as a symbol of steadfast dignity. |
| 2244812 | 동백꽃 향기가 함께하는 가야금.<br>음악과 함께 축제 분위기가 무르익어 간다. | A camellia-scented gayageum.<br>Its music enriches the lively spirit of the festival. |
| 2244813 | 축제를 찾은 귀빈들에게 제공되는 원형 떡 테이블.<br>가온에서만 맛볼 수 있는 고급스러운 디저트들로 가득하다. | A round table of rice cakes offered to the distinguished guests of the festival.<br>It features an array of refined desserts unique to Gaon. |
| 2244820 | 로제의 마음이 만들어 낸 시계탑. <br>세계의 규율을 깨뜨리고, 기록되지 않은 미래를 관측하려는 자의 염원이 담겨 있다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>로제(홍염)을 오브제에 배치하면 <color="#2d9b00">로제(홍염)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A clock tower manifested from Rose's mind.<br>It holds the desire of one who dares to shatter the world's order and glimpse an unwritten future.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Rose (Prominence) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244821 | 한때 홍란이 머물렀던 어느 산속의 쉼터.<br>포근한 구름으로 가득해, 마치 번잡한 속세와 단절된 꿈처럼 느껴진다.<br>중앙의 정자에선 홍란과 아기 토끼가 새근새근 낮잠을 자고 있다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>홍란(무쌍)을 오브제에 배치하면 <color="#2d9b00">홍란(무쌍)의 체력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A tranquil mountain refuge where Honglan once found rest.<br>Surrounded by fluffy clouds, it feels like a dream untouched by the busy world.<br>In the pavilion at the center, Honglan and a baby rabbit are peacefully napping.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Honglan (Peerless) to it to <color="#2d9b00">increase her HP by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244822 | 가온의 대영주로 새롭게 등극한 지호가 공무를 보는 옥좌. <br>지호의 취임을 기념하여 일류 장인이 제작했다. <br>원래는 훨씬 더 호화롭게 만들려 했지만, 지호가 한사코 거부해 지금의 형태가 되었다는 소문이 있다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>지호(미르)를 오브제에 배치하면 <color="#2d9b00">지호(미르)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | Jiho's official seat as the new Great Lord of Gaon.<br>It was crafted by a renowned artisan to honor the occasion.<br>Rumors say it was planned to be far more extravagant, but Jiho's firm refusal led to this modest design.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Jiho (Mir) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244823 | 동화에 나오는 백은의 공주가 살았다고 하는 성. <br>밤하늘의 북극성처럼 찬란하고 아름답게 빛났다고 한다. <br>르네가 말하길, 사실 이렇게 호화롭지는 않았다는데…<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>르네(백은)을 오브제에 배치하면 <color="#2d9b00">르네(백은)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | The castle said to be home to the Argent Princess of fairy tales.<br>It supposedly shone as brilliantly as the North Star.<br>Renee mentions, though, that in reality, it wasn't nearly so grand...<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Renee (Argent) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244824 | 파괴된 메타트론호를 그리워하는 메피스토펠레스를 위해 구원자가 제작해준 조형물.<br>메피스토펠레스는 이 조형물을 무척 좋아해서 자주 시간을 보내러 찾아온다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>메피스토펠레스(여명)을 오브제에 배치하면 <color="#2d9b00">메피스토펠레스(여명)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | Seeing Mephistopheles miss Metatron after its destruction, Savior built this structure.<br>Mephistopheles is very fond of it and often spends time visiting it.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Mephistopheles (Dawn) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244825 | 미리암과 미리암의 델타 전투 팀이 훈련에 사용하는 공간입니다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>미리암(잔영)을 오브제에 배치하면 <color="#2d9b00">미리암(잔영)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | Miriam and her Delta Team use this place for combat training.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Miriam (Afterimage) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244826 | 가넷이 사랑하는 구원자를 위해 만든 열락의 카지노입니다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>가넷(열락)을 오브제에 배치하면 <color="#2d9b00">가넷(열락)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | Garnet built this casino of rapture for her beloved Savior.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Garnet (Rapture) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244827 | 선원 모두 잠든 새벽, 항해 일지에 어김없이 한 줄이 더 생긴다.<br>누구의 글씨인지는 아직 아무도 모른다.<br><br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>셰리(낭만)을 오브제에 배치하면 <color="#2d9b00">셰리(낭만)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | With the ship's crew asleep in the dead of night, another line is added to the ship's log.<br>Nobody knows whose handwriting it is yet.<br><br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Cherrie (Romantic) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244901 | 햇살이 부드럽게 스며드는 궁중 정원의 온실.<br>잘 가꾸어진 꽃이 형형색색 피어 있다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A palace garden greenhouse where sunlight gently seeps in.<br>Well-tended flowers bloom in a variety of vivid colors.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2244902 | 퍼걸러 아래 차려진 홍차와 디저트 세트.<br>아름다운 정원에서 느긋한 티타임을 즐기기 좋은 곳이다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A tea and dessert set prepared under the pergola.<br>The perfect place for a relaxing tea break in a lovely garden.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244903 | 아케나인 성에 준비된 귀빈 전용 객실.<br>메이드들의 손길로 언제나 반듯하게 정돈되어 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A guest room reserved for honored guests in Arkenine Palace.<br>Always spotless thanks to the maids.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2244904 | 아케나인 성의 한 편, 린지(타나토스)가 업무를 처리하는 조용하고 깔끔한 서재.<br>책과 서류로 가득하지만, 어쩐지 마음이 차분해지는 편안한 공간이다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>린지(타나토스)를 오브제에 배치하면 <color="#2d9b00">린지(타나토스)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A quiet and tidy study in Arkenine Palace where Linzy (Thanatos) handles her work.<br>It is filled with books and documents, yet it somehow feels like a calming and comfortable space<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Linzy (Thanatos) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2244905 | 메이드들이 손수 고른 재료들로 정성껏 식사를 준비하는 주방.<br>맛있는 냄새가 풍겨온다. | A kitchen where the maids carefully prepare meals using handpicked ingredients.<br>A delicious aroma fills the air. |
| 2244906 | 정성스럽게 다듬어진 강아지 모양의 토피어리.<br>실베스터 조이 3세의 사랑스러운 모습이 그대로 담겨 있다. | A dog-shaped topiary, trimmed with great attention.<br>It perfectly captures King Sylvester Joey III's loveliness. |
| 2244907 | 정원에 놓인 수반으로, 실베스터 조이 3세의 조각이 우뚝 서 있다.<br>맑은 물 위에 싱그러운 꽃이 떠다닌다. | A garden basin with a statue of King Sylvester Joey III standing tall.<br>Fresh flowers float on the clear water. |
| 2244908 | 완벽한 티타임을 위해 메이드들이 준비한 애프터눈 티 세트.<br>달콤한 향기와 따뜻한 차가 휴식 시간을 특별하게 만들어준다. | An afternoon tea set prepared by the maids for the perfect teatime.<br>The sweet scent and warm tea make the break feel special. |
| 2244909 | 하얀 대리석 위에 금색 문양이 반짝이는 고풍스러운 바닥 타일. | An elegant floor tile with golden patterns sparkling on white marble. |
| 2244910 | 성 뒤편에 자리잡은 빨래터.<br>따뜻한 햇살 아래, 깨끗해진 메이드복이 바람에 살랑이며 다음 임무를 기다리고 있다. | A laundry spot located behind the castle.<br>Clean maid outfits flutter gently in the sunlight, ready for duty. |
| 2244911 | 고급스러우면서도 아기자기한 정원 가로등.<br>꽃과 식물이 어우러져 마치 정원의 한 부분처럼 빛을 내고 있다. | A garden lamp post that is both luxurious and cute.<br>Surrounded by flowers and plants, it lights up as if it's part of the garden itself. |
| 2244912 | 정원을 둘러싸고 있는 담벼락.<br>펜스에는 넝쿨과 꽃들이 자랐다. | A wall that surrounds the garden.<br>The fence is covered with vines and flowers. |
| 2244913 | 정원에 출입하기 위한 대문.<br>고급스러운 철제 문 너머에는 아름다운 정원의 모습이 보인다. | A gate used to enter the garden.<br>Beyond the elegant iron gate lies the view of a beautiful garden. |
| 2245001 | 즐거운 휴가를 위해서는 안전수칙을 지키는 게 중요하다.<br>다치는 이가 없도록, 안전요원이 철두철미하게 감시하고 있다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | Following safety rules is essential for a fun vacation.<br>The lifeguard stands vigilant, making sure no one gets hurt.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2245002 | 아름다운 자연을 느낄 수 있는 폭포.<br>폭포 아래서, 모든 근심걱정을 잊어버리자.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A gorgeous waterfall, displaying the beauty of nature.<br>Stand beneath it, and let every care wash away.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2245003 | 자연적인 지형으로 형성된 항구.<br>천혜의 자연을 고스란히 만끽할 수 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A naturally formed port.<br>Offers a splendid view of the raw beauty of nature.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2245004 | 거대한 나무 아래, 휴식을 위한 작은 집이 마련되어 있다.<br>그 오두막에서 어떤 일이 벌어질지는 아무도 모른다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>니아를 오브제에 배치하면 <color="#2d9b00">니아의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | A cozy little cabin built under a giant tree.<br>Nobody knows what might happen inside.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Nia to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2245005 | 꽃으로 가득 채워진 카누. <br>이 배를 타고 두둥실 나아간다면, 분명 기분 좋은 일이 일어날 것 같다. | A canoe filled with flowers.<br>Floating in it feels like something good is going to happen. |
| 2245006 | 쨍한 페이렌의 바다를 닮은 타일. | A tile that resembles the clear ocean of Fayren. |
| 2245007 | 꽃잎이 박혀 있는 해변 모래 타일. | A beach sand tile embedded with petals. |
| 2245008 | 꽃잎이 박혀 있는 해변 모래 타일. | A beach sand tile embedded with petals. |
| 2245009 | 꽃잎이 박혀 있는 해변 모래 타일. | A beach sand tile embedded with petals. |
| 2245010 | 꽃잎이 박혀 있는 해변 모래 타일. | A beach sand tile embedded with petals. |
| 2245011 | 신선한 과일로 만든 음료를 즉석에서 맛볼 수 있다.<br>주위가 끈적끈적해지지 않도록 청결에 유의하자. | Offers freshly prepared fruit drinks.<br>Just be careful to keep things clean so the area doesn't get sticky. |
| 2245012 | 누군가의 취향이 묻어나는 대형 도마뱀 튜브.<br>먼 나라에서 가져온 애착 튜브라고 한다. | A giant lizard-shaped inflatable tube reflecting someone's personal taste.<br>Apparently, it's a cherished tube brought all the way from a distant land. |
| 2245013 | 무더운 기후가 느껴지는 야자수.<br>호기심 많아 보이는 새가 앉아 있다. | A palm tree with the vibe of a hot, humid climate.<br>A curious-looking bird is perched on it. |
| 2245014 | 무더운 기후가 느껴지는 야자수.<br>눈부신 색상의 꽃이 피어 있다. | A palm tree with the vibe of a hot, humid climate.<br>A dazzling flower is in bloom. |
| 2245015 | 훈제향을 그대로 느낄 수 있는 바베큐 그릴.<br>신선한 해산물의 풍미를 즐겨 보자. | A grill that brings out the full smoky scent of barbecue.<br>Time to indulge in the savory taste of fresh seafood. |
| 2245016 | 물고기에 먹물을 바르고 그대로 찍어낸 그림.<br>그런데 물고기가 아니라 정체불명의 생물체가 찍힌 듯하다. | A picture made by coating a fish in ink and pressing it onto paper.<br>This one does not look like a fish, though. |
| 2245017 | 라이브 세션 밴드를 위한 사이드 스테이지.<br>이곳에서 무대를 더욱 돋보이게 하기 위한 음악을 연주한다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A side stage for live bands.<br>It's where music is played to elevate the stage to greater heights.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2245018 | 아이돌의 자켓 앨범 화보 촬영을 위해 만들어진 포토존.<br>밝은 조명 때문에 눈이 부시다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A photo spot set up to shoot album covers for idols.<br>The bright lights are almost blinding.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2245019 | 불후의 명곡, 'Love Note'를 촬영한 뮤직비디오 촬영 세트.<br>보기만 해도 사랑스러운 기분이 든다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | The set used to shoot the music video of Love Note, a timeless classic.<br>Just looking at it fills you with love.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2245020 | 모든 연습생들이 서길 바라는 꿈의 스테이지.<br>이곳에서 당신의 아이돌인 벨레드가 무대를 선보이고 있다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>벨레드를 오브제에 배치하면 <color="#2d9b00">벨레드의 체력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | The dream stage all trainees aspire to stand upon.<br>Your idol Beleth is performing here.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Beleth to this structure to <color="#2d9b00">increase her HP by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2245021 | 콘서트의 티켓을 판매하는 부스.<br>티켓을 구매하러 온 정령들로 북적일 때가 많다. | A booth for selling concert tickets.<br>It is often crowded with Souls wanting to buy tickets. |
| 2245022 | 아이돌의 무대 의상을 전시해두기 위한 마네킹 전시대.<br>일상에서는 입을 수 없는 디자인의 옷이 전시되어있다. | A mannequin stand for showcasing the stage costumes of idols.<br>Outfits with designs far too extravagant for everyday wear are on display. |
| 2245023 | 인기 아이돌의 굿즈를 파는 팝업 스토어.<br>굿즈를 사기 위해서는 새벽부터 줄을 선다는 소문이 있다. | A pop-up store selling merch of popular idols.<br>Rumor says fans line up before sunrise for a chance to purchase them. |
| 2245024 | 아이돌들이 댄스 배틀로 서로의 실력을 겨뤄볼 수 있는 무대.<br>연습생들도 자주 이용하는 것처럼 보인다. | A stage where idols pit their dance skills against one another.<br>Trainees seem to make use of it quite often as well. |
| 2245025 | 콘서트장 앞에 세워진 가로등.<br>콘서트 홍보 배너가 붙어 있다. | A street lamp in front of a concert hall.<br>It bears a banner promoting a concert. |
| 2245026 | 평범한 검은색 바닥 타일.<br>자세히 보면 광택이 난다. | Ordinary black floor tile.<br>There is a subtle sheen that can be seen upon a closer look. |
| 2245027 | 에덴 갓 탤런트의 파이널 무대로 향하는 길을 안내하기 위한 게이트.<br>화려하게 꾸며져있어 누가 봐도 입구처럼 보인다. | A gate leading to the final stage of Eden's Got Talent.<br>The lavish adornment makes it clear as the entrance. |
| 2245028 | 신나는 음악이 흘러나오는 DJ부스 겸 스피커.<br>너무 가까이 가면 귀가 아플지도… | A DJ booth that serves as speakers, playing upbeat music.<br>May hurt your ears if you get too close to it. |
| 2245029 | 아이돌 퀸의 콘서트를 관람하기 위해 앉는 공연장 좌석.<br>그렇게 푹신하진 않은 것 같다. | Concert seating for the audience at the Idol Queen's concert.<br>Does not seem all that comfy. |
| 2245030 | 가온신년제를 더욱 신명나게 해주는 놀이판<br>많은 정령들이 춤을 추고 놀 수 있다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A platform that boosts the cheerful energy of Gaon New Year's Festival.<br>Many Souls can dance and play on it.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2245031 | 신년제를 기념하여 제작한 거대한 당고<br>모두가 먹을 수 있을 만큼 거대하다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A giant dango made to celebrate the New Year's festival.<br>It is big enough to feed everyone.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2245032 | 신년제를 기념하여 특별 조리한 거대한 떡국<br>모두가 먹을 수 있을 만큼 거대하다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A massive pot of rice cake soup, specially prepared to celebrate the New Year's festival.<br>There is enough to feed everyone.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2245033 | 새로운 해를 맞이하여, 한해의 운세를 점치는 행사를 진행한다.<br><br><color="#2d9b00">특별한 아르바이트를 진행</color>할 수 있습니다.<br><br>유리아(아폴리온)을 오브제에 배치하면 <color="#2d9b00">유리아(아폴리온)의 공격력이 10% 증가</color>합니다. <br>(다른 오브제에 중복 배치 불가) | Celebrate the new year here with a fortune reading.<br><br>Unlocks a <color="#2d9b00">special part-time job</color>.<br><br>Assign Yuria (Apollyon) to it to <color="#2d9b00">increase her ATK by 10%</color>.<br>(Each Soul can occupy only one structure.) |
| 2245034 | 연을 높게 띄워 보내어 새해의 재액을 멀리 쫓아 버린다.<br>손에서 떨어진 연들도 바람을 따라서 계속해서 움직인다. | Send your kite soaring high to chase away the new year's misfortune.<br>Even the kites released from your hand keep gliding along with the wind. |
| 2245035 | 새해의 소원을 나무판에 적어 소원이 이뤄지기를 기도하며 걸어둔다. | Write your wish for the new year on a wooden plaque and hang it, praying for it to come true. |
| 2245036 | 축제를 기념하여 만든 구원자 모양의 등불 | A lamp made in the likeness of Savior, crafted to celebrate the festival. |
| 2245037 | 모두가 나눠 먹을 수 있을 정도로 쌓인 잔칫상이다 | A banquet with a vast spread of food, enough for everyone to enjoy. |
| 2245038 | 새해를 기념하는 음식들을 판매하는 상점이다. | A shop selling dishes made to celebrate the new year. |
| 2245039 | 복을 가득 담은 거대한 복주머니<br>축제에 온 모두가 나눠 가질 수 있을 만큼 많은 복이 담겨있다. | A giant pouch filled with fortune.<br>It has enough to share with everyone at the festival. |
| 2247001 | 메피스토펠레스의 모습을 본따 만든 석상. | A stone statue made after Mephistopheles. |
| 2247002 | 탈리아의 모습을 본따 만든 석상. | A stone statue made after Talia. |
| 2247003 | 재클린의 모습을 본따 만든 석상. | A stone statue made after Jacqueline. |
| 2247004 | 홍란의 모습을 본따 만든 석상. | A stone statue made after Honglan. |
| 2247005 | 린지의 모습을 본따 만든 석상. | A stone statue made after Linzy. |
| 2247006 | 아야메의 모습을 본따 만든 석상. | A stone statue made after Ayame. |
| 2247007 | 니콜의 모습을 본따 만든 석상. | A stone statue made after Nicole. |
| 2247008 | 비올레트의 모습을 본따 만든 석상. | A stone statue made after Violette. |
| 2247009 | 구원자의 모습을 본따 만든 석상.<br>영지를 아끼는 구원자에 대한 고마움이 담겨있다.<br><br><color="#2d9b00">전리품 골드를 +15/분, 전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A statue of the Savior.<br>It is filled with appreciation for the Savior taking care of the town.<br><br>Offers <color="#2d9b00">15 more Gold and 20 more Mana Dust per min in loot</color>. |
| 2247010 | 아드리안의 모습을 본따 만든 석상. | A stone statue made after Adrianne. |
| 2247011 | 제이드의 모습을 본따 만든 석상. | A stone statue made after Jade. |
| 2247012 | 클로이의 모습을 본따 만든 석상. | A stone statue made after Chloe. |
| 2247013 | 프림의 모습을 본따 만든 석상. | A stone statue made after Prim. |
| 2247014 | 리젤로테의 모습을 본따 만든 석상. | A stone statue made after Lizelotte. |
| 2247015 | 순이의 모습을 본따 만든 석상. | A stone statue made after Soonie. |
| 2247016 | 아키의 모습을 본따 만든 석상. | A stone statue made after Aki. |
| 2247017 | 나이아의 모습을 본따 만든 석상. | A stone statue made after Naiah. |
| 2247018 | 미카의 모습을 본따 만든 석상. | A stone statue made after Mica. |
| 2247019 | 시하의 모습을 본따 만든 석상. | A stone statue made after Seeha. |
| 2247020 | 클라우디아의 모습을 본따 만든 석상. | A stone statue made after Claudia. |
| 2247021 | 니니의 모습을 본따 만든 석상. | A stone statue made after Nini. |
| 2247022 | 페트라의 모습을 본따 만든 석상. | A stone statue made after Petra. |
| 2247023 | 클레르의 모습을 본따 만든 석상. | A stone statue made after Claire. |
| 2247024 | 클라라의 모습을 본따 만든 석상. | A stone statue made after Clara. |
| 2247100 | 1주년을 기념하는 파티 케이크. 딸기 토핑이 가득 들어있다.<br>케이크 커팅식을 시작하며 지난 1년간의 추억을 되돌아보자. | A party cake celebrating the 1st anniversary, topped generously with strawberries.<br>Let's walk down the memory lane of the past year as we begin cutting the cake. |
| 2247101 | 토카가 소환하는 거대한 옥좌 형태의 천사를 본뜬 모형.<br>주로 등받이에 꽂혀있는 대검을 사용하지만, 옥좌 자체에도 숨겨진 힘이 존재한다고 한다.<br><br><color="#2d9b00">전리품 골드를 +15/분 추가로 획득</color>할 수 있습니다. | A model of the giant throne-shaped angel summoned by Tohka.<br>She usually uses the heavy sword on her back, but this throne itself supposedly has its own hidden powers as well.<br><br>Offers <color="#2d9b00">15 more Gold per min in loot</color>. |
| 2247102 | 쿠루미가 소환하는 거대한 시계 형태의 천사를 본뜬 모형.<br>그녀가 사용하는 총기는 이 시계의 장침과 단침이라고 한다.<br><br><color="#2d9b00">전리품 마나 더스트를 +20/분 추가로 획득</color>할 수 있습니다. | A model of the giant clock-shaped angel summoned by Kurumi.<br>Apparently, the firearms she uses are the hands from this clock.<br><br>Offers <color="#2d9b00">20 more Mana Dust per min in loot</color>. |
| 2247103 | 2주년을 기념하는 파티 케이크. <br>어떤 약속은 영원히 변치 않는다. 당신이 함께하는 한! | A party cake for celebrating the 2nd anniversary.<br>Some promises remain unchanged forever. As long as you're there! |
| 2247104 | 사쿠요(업화)의 새로운 의상으로 입간판이 만들어졌다.<br>누가 만들었는지는 모르지만 신사일지도? | A free-standing sign featuring Sakuyo (Infernal Blaze)'s new outfit.<br>Whoever made it must be a man of culture. |
| 2247105 | 3주년을 기념하는 파티 케이크.<br>어느새 벌써 3년! 함께 나눴던 그 약속은 언제나 그 자리에. | A cake for the 3rd anniversary party.<br>Three years have flown by! The promise we once shared still remains steadfast. |
| 2248001 | 소소한 물건을 파는 잡화점. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>재료채집(커먼)<br>인형만들기(커먼)<br>마법약제조(커먼) | A general store that sells general items. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Material Gathering (Common)<br>Doll-Making (Common)<br>Potion-Making (Common) |
| 2248002 | 구색이 잘 갖추어진 잡화점. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>재료채집(레어)<br>인형만들기(레어)<br>마법약제조(레어) | A general store with a nice assortment of goods for sale. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Material Gathering (Rare)<br>Doll-Making (Rare)<br>Potion-Making (Rare) |
| 2248003 | 없는 물건이 없는 잡화점. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>재료채집(에픽)<br>인형만들기(에픽)<br>마법약제조(에픽) | A general store with everything you need. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Material Gathering (Epic)<br>Doll-Making (Epic)<br>Potion-Making (Epic) |
| 2248011 | 작은 플라워숍. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>꽃다발 만들기(커먼)<br>화분 만들기(커먼)<br>노상판매(커먼) | A small flower shop. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Bouquet-Making (Common)<br>Flowerpot-Making (Common)<br>Sidewalk Sales (Common) |
| 2248012 | 다양한 꽃을 파는 플라워숍. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>꽃다발 만들기(레어)<br>화분 만들기(레어)<br>노상판매(레어) | A flower shop that sells a variety of flowers. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Bouquet-Making (Rare)<br>Flowerpot-Making (Rare)<br>Sidewalk Sales (Rare) |
| 2248013 | 전문적으로 운영하는 플라워숍. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>꽃다발 만들기(에픽)<br>화분 만들기(에픽)<br>노상판매(에픽) | A professionally run flower shop. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Bouquet-Making (Epic)<br>Flowerpot-Making (Epic)<br>Sidewalk Sales (Epic) |
| 2248021 | 빵을 파는 베이커리. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>반죽하기(커먼)<br>케이크 장식하기(커먼)<br>빵 배달하기(커먼) | A bakery that sells bread. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Dough-Making (Common)<br>Cake-Decoration (Common)<br>Bread Delivery (Common) |
| 2248022 | 빵과 과자를 파는 베이커리. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>반죽하기(레어)<br>케이크 장식하기(레어)<br>빵 배달하기(레어) | A bakery that sells bread and cookies. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Dough-Making (Rare)<br>Cake-Decoration (Rare)<br>Bread Delivery (Rare) |
| 2248023 | 모든 디저트를 파는 베이커리. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>반죽하기(에픽)<br>케이크 장식하기(에픽)<br>빵 배달하기(에픽) | A bakery that sells all kinds of desserts. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Dough-Making (Epic)<br>Cake-Decoration (Epic)<br>Bread Delivery (Epic) |
| 2248031 | 저렴하고 맛있는 레스토랑. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>설거지하기(커먼)<br>감자깎기(커먼)<br>요리하기(커먼) | A restaurant that serves affordable and delicious food. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Washing the Dishes (Common)<br>Potato-Peeling (Common)<br>Cooking (Common) |
| 2248032 | 기분 전환하기 좋은 레스토랑. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>설거지하기(레어)<br>감자깎기(레어)<br>요리하기(레어) | A restaurant that's good for cheering yourself up. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Washing the Dishes (Rare)<br>Potato-Peeling (Rare)<br>Cooking (Rare) |
| 2248033 | 큰 맘 먹어야 갈만한 고급 레스토랑. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>설거지하기(에픽)<br>감자깎기(에픽)<br>요리하기(에픽) | A premium restaurant that serves very expensive dishes. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Washing the Dishes (Epic)<br>Potato-Peeling (Epic)<br>Cooking (Epic) |
| 2248041 | 소담한 카페. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>호객하기(커먼)<br>커피 그라인드(커먼)<br>커피 내리기(커먼) | A small and cozy cafe. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Soliciting (Common)<br>Coffee-Grinding (Common)<br>Coffee-Brewing (Common) |
| 2248042 | 산뜻한 카페. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>호객하기(레어)<br>커피 그라인드(레어)<br>커피 내리기(레어) | A fresh and neat cafe. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Soliciting (Rare)<br>Coffee-Grinding (Rare)<br>Coffee-Brewing (Rare) |
| 2248043 | 고급스러운 카페. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>호객하기(에픽)<br>커피 그라인드(에픽)<br>커피 내리기(에픽) | A premium cafe. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Soliciting (Epic)<br>Coffee-Grinding (Epic)<br>Coffee-Brewing (Epic) |
| 2248051 | 작은 도서관. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>책 반납받기(커먼)<br>책 정리하기(커먼)<br>필사하기(커먼) | A small library. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Taking Returned Books (Common)<br>Organizing Books (Common)<br>Transcribing (Common) |
| 2248052 | 양질의 책이 많은 도서관. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>책 반납받기(레어)<br>책 정리하기(레어)<br>필사하기(레어) | A library with lots of quality books. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Taking Returned Books (Rare)<br>Organizing Books (Rare)<br>Transcribing (Rare) |
| 2248053 | 다양한 서적이 비치된 도서관. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>책 반납받기(에픽)<br>책 정리하기(에픽)<br>필사하기(에픽) | A library with a variety of books. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Taking Returned Books (Epic)<br>Organizing Books (Epic)<br>Transcribing (Epic) |
| 2248061 | 조용한 성당. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>청소하기(커먼)<br>빨래하기(커먼)<br>바느질하기(커먼) | A silent cathedral. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Cleaning (Common)<br>Laundry (Common)<br>Sewing (Common) |
| 2248062 | 아름다운 성당. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>청소하기(레어)<br>빨래하기(레어)<br>바느질하기(레어) | A beautiful cathedral. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Cleaning (Rare)<br>Laundry (Rare)<br>Sewing (Rare) |
| 2248063 | 거룩한 규모의 성당. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>청소하기(에픽)<br>빨래하기(에픽)<br>바느질하기(에픽) | A cathedral of holy scale. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Cleaning (Epic)<br>Laundry (Epic)<br>Sewing (Epic) |
| 2248071 | 소박한 아틀리에. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>그림 그리기(커먼)<br>도자기 만들기(커먼)<br>석상 만들기(커먼) | A simple atelier. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Drawing (Common)<br>Pottery-Making (Common)<br>Statue-Making (Common) |
| 2248072 | 현대적인 느낌의 아틀리에. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>그림 그리기(레어)<br>도자기 만들기(레어)<br>석상 만들기(레어) | A modern atelier. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Drawing (Rare)<br>Pottery-Making (Rare)<br>Statue-Making (Rare) |
| 2248073 | 대 예술가의 전문적인 아틀리에. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>그림 그리기(에픽)<br>도자기 만들기(에픽)<br>석상 만들기(에픽) | A professional atelier of great artists. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Drawing (Epic)<br>Pottery-Making (Epic)<br>Statue-Making (Epic) |
| 2248081 | 농기구를 만드는 작은 대장간. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>풀무질하기(커먼)<br>칼날갈기(커먼)<br>망치질하기(커먼) | A small forge that makes farming tools. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Working the Bellows (Common)<br>Blade Sharpening (Common)<br>Hammering (Common) |
| 2248082 | 농기구와 무기류를 만드는 대장간. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>풀무질하기(레어)<br>칼날갈기(레어)<br>망치질하기(레어) | A forge that makes farming tools and weapons. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Working the Bellows (Rare)<br>Blade Sharpening (Rare)<br>Hammering (Rare) |
| 2248083 | 모든 금속제품을 취급하는 대장간. 아르바이트를 진행할 수 있습니다.<br>( 보유 가능 개수: 1 )<br><br>▶ 진행 가능 아르바이트<br>풀무질하기(에픽)<br>칼날갈기(에픽)<br>망치질하기(에픽) | A forge that handles all kinds of metal products. Unlocks certain part-time jobs.<br>(Max: 1)<br><br>▶ Offered Part-Time Jobs:<br>Working the Bellows (Epic)<br>Blade Sharpening (Epic)<br>Hammering (Epic) |
| 2248091 | 오래된 정령의 유물이 묻혀 있는 발굴터. 아르바이트를 진행할 수 있습니다.<br><br>▶ 진행 가능 아르바이트<br>유물 수집하기(커먼)<br>유물 수집하기(레어)<br>유물 수집하기(에픽)<br>유물 정리하기(커먼)<br>유물 정리하기(레어)<br>유물 정리하기(에픽)<br>유물 판독하기(커먼)<br>유물 판독하기(레어)<br>유물 판독하기(에픽) | An excavation site where the old artifacts of Souls are buried. Unlocks certain part-time jobs.<br><br>▶ Offered Part-Time Jobs:<br>Collecting Artifacts (Common)<br>Collecting Artifacts (Rare)<br>Collecting Artifacts (Epic)<br>Organizing Artifacts (Common)<br>Organizing Artifacts (Rare)<br>Organizing Artifacts (Epic)<br>Deciphering Artifacts (Common)<br>Deciphering Artifacts (Rare)<br>Deciphering Artifacts (Epic) |
| 2248092 | 정령의 기억을 품은 돌, 아르바이트를 진행할 수 있습니다.<br><br>▶ 진행 가능 아르바이트<br>기억 수집하기(커먼)<br>기억 수집하기(레어)<br>기억 수집하기(에픽)<br>기억 정리하기(커먼)<br>기억 정리하기(레어)<br>기억 정리하기(에픽)<br>기억 판독하기(커먼)<br>기억 판독하기(레어)<br>기억 판독하기(에픽) | A stone that bears the memory of Souls. Unlocks certain part-time jobs.<br><br>▶ Offered Part-Time Jobs:<br>Collecting Memories (Common)<br>Collecting Memories (Rare)<br>Collecting Memories (Epic)<br>Organizing Memories (Common)<br>Organizing Memories (Rare)<br>Organizing Memories (Epic)<br>Deciphering Memories (Common)<br>Deciphering Memories (Rare)<br>Deciphering Memories (Epic) |
| 2248093 | 매우 오래된 정령의 유물이 묻혀 있는 발굴터. 아르바이트를 진행할 수 있습니다.<br><br>▶ 진행 가능 아르바이트<br>고대유물 수집하기(커먼)<br>고대유물 수집하기(레어)<br>고대유물 수집하기(에픽)<br>고대유물 정리하기(커먼)<br>고대유물 정리하기(레어)<br>고대유물 정리하기(에픽)<br>고대유물 판독하기(커먼)<br>고대유물 판독하기(레어)<br>고대유물 판독하기(에픽) | An excavation site where the ancient artifacts of Souls are buried. Unlocks certain part-time jobs.<br><br>▶ Offered Part-Time Jobs:<br>Collecting Ancient Artifacts (Common)<br>Collecting Ancient Artifacts (Rare)<br>Collecting Ancient Artifacts (Epic)<br>Organizing Ancient Artifacts (Common)<br>Organizing Ancient Artifacts (Rare)<br>Organizing Ancient Artifacts (Epic)<br>Deciphering Ancient Artifacts (Common)<br>Deciphering Ancient Artifacts (Rare)<br>Deciphering Ancient Artifacts (Epic) |
| 2248094 | 오래된 정령의 기억을 품은 돌, 아르바이트를 진행할 수 있습니다.<br><br>▶ 진행 가능 아르바이트<br>고대 기억 수집하기(커먼)<br>고대 기억 수집하기(레어)<br>고대 기억 수집하기(에픽)<br>고대 기억 정리하기(커먼)<br>고대 기억 정리하기(레어)<br>고대 기억 정리하기(에픽)<br>고대 기억 판독하기(커먼)<br>고대 기억 판독하기(레어)<br>고대 기억 판독하기(에픽) | A stone that bears the memory of ancient Souls. Unlocks certain part-time jobs.<br><br>▶ Offered Part-Time Jobs:<br>Collecting Ancient Memories (Common)<br>Collecting Ancient Memories (Rare)<br>Collecting Ancient Memories (Epic)<br>Organizing Ancient Memories (Common)<br>Organizing Ancient Memories (Rare)<br>Organizing Ancient Memories (Epic)<br>Deciphering Ancient Memories (Common)<br>Deciphering Ancient Memories (Rare)<br>Deciphering Ancient Memories (Epic) |
| 2248095 | 마나석이 묻혀 있는 발굴터. 아르바이트를 진행할 수 있습니다.<br><br>▶ 진행 가능 아르바이트<br>마나석 수집하기(커먼)<br>마나석 수집하기(레어)<br>마나석 수집하기(에픽) | A dig site with deposits of Manastones. Unlocks certain part-time jobs.<br><br>▶ Offered Part-Time Jobs:<br>Collecting Manastones (Common)<br>Collecting Manastones (Rare)<br>Collecting Manastones (Epic) |
| 2248096 | 예장 강화석을 만드는 정제소. 아르바이트를 진행할 수 있습니다.<br><br>▶ 진행 가능 아르바이트<br>강화석 정제하기(커먼)<br>강화석 정제하기(레어)<br>강화석 정제하기(에픽) | A refinery for producing Keepsake Enhance Stones. Unlocks certain part-time jobs.<br><br>▶ Offered Part-Time Jobs:<br>Refine Enhance Stones (Common)<br>Refine Enhance Stones (Rare)<br>Refine Manastones (Epic) |
| 2249000 | 홈 스위트 마이 홈 | Home Sweet My Home |
| 2249001 | 작은 정령의 집. 정령을 배치하면 정령의 공격력이 <color="#2d9b00">3%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A little house for Souls. Assigning a Soul to it increases the Soul's ATK by <color="#2d9b00">3%</color>.<br>(Max: 3) |
| 2249002 | 작은 정령의 집. 정령을 배치하면 정령의 방어력이<color="#2d9b00">3.6%</color> 증가합니다.<br>( 보유 가능 개수: 3 ) | A little house for Souls. Assigning a Soul to it increases the Soul's DEF by <color="#2d9b00">3.6%</color>.<br>(Max: 3) |
| 2249003 | 작은 정령의 집. 정령을 배치하면 정령의 체력이 <color="#2d9b00">3%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A little house for Souls. Assigning a Soul to it increases the Soul's HP by <color="#2d9b00">3%</color>.<br>(Max: 3) |
| 2249011 | 조금 큰 정령의 집. 정령을 배치하면 정령의 공격력이 <color="#2d9b00">5%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A slightly bigger house for Souls. Assigning a Soul to it increases the Soul's ATK by <color="#2d9b00">5%</color>.<br>(Max: 3) |
| 2249012 | 조금 큰 정령의 집. 정령을 배치하면 정령의 방어력이 <color="#2d9b00">6%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A slightly bigger house for Souls. Assigning a Soul to it increases the Soul's DEF by <color="#2d9b00">6%</color>.<br>(Max: 3) |
| 2249013 | 조금 큰 정령의 집. 정령을 배치하면 정령의 체력이 <color="#2d9b00">5%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A slightly bigger house for Souls. Assigning a Soul to it increases the Soul's HP by <color="#2d9b00">5%</color>.<br>(Max: 3) |
| 2249021 | 매우 큰 정령의 집. 정령을 배치하면 정령의 공격력이 <color="#2d9b00">10%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A very big house for Souls. Assigning a Soul to it increases the Soul's ATK by <color="#2d9b00">10%</color>.<br>(Max: 3) |
| 2249022 | 매우 큰 정령의 집. 정령을 배치하면 정령의 방어력이 <color="#2d9b00">12%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A very big house for Souls. Assigning a Soul to it increases the Soul's DEF by <color="#2d9b00">12%</color>.<br>(Max: 3) |
| 2249023 | 매우 큰 정령의 집. 정령을 배치하면 정령의 체력이 <color="#2d9b00">10%</color>증가합니다.<br>( 보유 가능 개수: 3 ) | A very big house for Souls. Assigning a Soul to it increases the Soul's HP by <color="#2d9b00">10%</color>.<br>(Max: 3) |
| 2249501 | 레이싱 서킷 시작 지점 설명 | Race Track Starting Point description |
| 2249502 | 레이싱 서킷 종료 지점 설명 | Race Track Finish Point description |
| 2249503 | 레이싱 서킷 중간 지점1 설명 | Race Track Mid-Route Point 1 description |
| 2249504 | 레이싱 서킷 중간 지점2 설명 | Race Track Mid-Route Point 2 description |
| 2249505 | 레이싱 서킷 중간 지점3 설명 | Race Track Mid-Route Point 3 description |
| 2249506 | 레이싱 서킷 중간 지점4 설명 | Race Track Mid-Route Point 4 description |
| 2249507 | 레이싱 서킷 중간 지점5 설명 | Race Track Mid-Route Point 5 description |
| 2249601 | 눈썰매_플레이어 설명 | Snow Sled_Player description |
| 2249602 | 눈썰매_정령 설명 | Snow Sled_Soul description |
| 2249603 | 오리배_플레이어 설명 | Duck Boat_Player description |
| 2249604 | 오리배_정령 설명 | Duck Boat_Soul description |
| 2249605 | 카트_플레이어 설명 | Go-Kart_Player description |
| 2249606 | 카트_정령 설명 | Go-Kart_Soul description |
| 2250000 | 오브제에 깃든 기운을 정제하여 만든 재.<br>보유하고 있으면 영지 발전도가 증가합니다.<br><br>일반 오브제 소각 시, 획득할 수 있습니다. | Ash produced by refining the essence imbued in objects.<br>Possessing it increases the town's Progress.<br><br>Obtained upon incinerating regular objects. |
| 3100001 | 힘의 증표 | Token of Power |
| 3100002 | 인내의 증표 | Token of Patience |
| 3100003 | 지혜의 증표 | Token of Wisdom |
| 3100004 | 에리카의 부활 포션 | Erika's Resurrection Potion |
| 3100005 | 사념의 조각 1 | Piece of Vicious Mind 1 |
| 3100006 | 사념의 조각 2 | Piece of Vicious Mind 2 |
| 3100007 | 사념의 조각 3 | Piece of Vicious Mind 3 |
| 3100008 | 사념의 조각 4 | Piece of Vicious Mind 4 |
| 3100009 | 유물석 | Artifact Stone |
| 3100010 | 투쟁의 열쇠 | Key of Struggle |
| 3100011 | 자비의 열쇠 | Key of Mercy |
| 3100012 | 지배의 열쇠 | Key of Control |
| 3100017 | 사원 열쇠 | Temple Key |
| 3100018 | 첫 번째 종말의 기억 | Memory of the First Apocalypse |
| 3100019 | 두 번째 종말의 기억 | Memory of the Second Apocalypse |
| 3100020 | 세 번째 종말의 기억 | Memory of the Third Apocalypse |
| 3100021 | 네 번째 종말의 기억 | Memory of the Fourth Apocalypse |
| 3100022 | 다섯 번째 종말의 기억 | Memory of the Fifth Apocalypse |
| 3100023 | 기원 초기화 장치 | Origin Reset Device |
| 3200001 | 힘의 증명을 통해 획득한 증표. 유적 최심부의 제단을 활성화시킬 수 있다. | A token obtained through proof of power. It allows you to activate the altar in the innermost depths of the ruins. |
| 3200002 | 인내의 증명을 통해 획득한 증표. 유적 최심부의 제단을 활성화시킬 수 있다. | A token obtained through proof of patience. It allows you to activate the altar in the innermost depths of the ruins. |
| 3200003 | 지혜의 증명을 통해 획득한 증표. 유적 최심부의 제단을 활성화시킬 수 있다. | A token obtained through proof of wisdom. It allows you to activate the altar in the innermost depths of the ruins. |
| 3200004 | 던전 전용 아이템.<br>던전에서 정령을 부활시키거나 완전히 회복시킬 수 있습니다. | Dungeon-exclusive items.<br>You can use these items to revive or fully recover a Soul in a dungeon. |
| 3200005 | 정령의 사념이 깃든 첫 번째 조각. 중앙 제단에 주입하면 유물의 기억을 확인할 수 있다. | The first piece imbued with the vicious mind of a Soul. Put it in the central altar to check the Artifact Memory. |
| 3200006 | 정령의 사념이 깃든 두 번째 조각. 중앙 제단에 주입하면 유물의 기억을 확인할 수 있다. | The second piece imbued with the vicious mind of a Soul. Put it in the central altar to check the Artifact Memory. |
| 3200007 | 정령의 사념이 깃든 세 번째 조각. 중앙 제단에 주입하면 유물의 기억을 확인할 수 있다. | The third piece imbued with the vicious mind of a Soul. Put it in the central altar to check the Artifact Memory. |
| 3200008 | 정령의 사념이 깃든 네 번째 조각. 중앙 제단에 주입하면 유물의 기억을 확인할 수 있다. | The fourth piece imbued with the vicious mind of a Soul. Put it in the central altar to check the Artifact Memory. |
| 3200009 | 정령의 혼이 깃든 첫 번째 유물석.<br>가온국 유물 사원에 보관되어 있다. | First Artifact Stone imbued with the spirit of a Soul.<br>Stored at the Temple of Artifacts of Gaon. |
| 3200010 | 정령의 혼이 깃든 두 번째 유물석.<br>가온국 유물 사원에 보관되어 있다. | Second Artifact Stone imbued with the spirit of a Soul.<br>Stored at the Temple of Artifacts of Gaon. |
| 3200011 | 정령의 혼이 깃든 세 번째 유물석.<br>가온국 유물 사원에 보관되어 있다. | Third Artifact Stone imbued with the spirit of a Soul.<br>Stored at the Temple of Artifacts of Gaon. |
| 3200012 | 정령의 혼이 깃든 네 번째 유물석.<br>가온국 유물 사원에 보관되어 있다. | Fourth Artifact Stone imbued with the spirit of a Soul.<br>Stored at the Temple of Artifacts of Gaon. |
| 3200013 | 미궁에 세 개 존재한다는 전설의 중 하나,<br>모두 모으면 특별한 공간으로 이동 가능한 권한이 부여된다고 한다. | One of the three legendary keys that are known to exist in the Labyrinth.<br>Collecting the three keys will give you the power to transport to somewhere special. |
| 3200014 | 초인류의 언어로 '투쟁'이라는 단어가 각인된 열쇠.<br>'투쟁', '자비', '지배'의 열쇠를 모으면 금지된 구역으로 통하는 길이 열린다. | A key made by Dominas. Collecting the key of "Struggle," "Mercy," and "Control" will open the way to the forbidden district. |
| 3200015 | 초인류의 언어로 '자비'라는 단어가 각인된 열쇠.<br>'투쟁', '자비', '지배'의 열쇠를 모으면 금지된 구역으로 통하는 길이 열린다. | A key made by Dominas. Collecting the key of "Struggle," "Mercy," and "Control" will open the way to the forbidden district. |
| 3200016 | 초인류의 언어로 '지배'라는 단어가 각인된 열쇠.<br>'투쟁', '자비', '지배'의 열쇠를 모으면 금지된 구역으로 통하는 길이 열린다. | A key made by Dominas. Collecting the key of "Struggle," "Mercy," and "Control" will open the way to the forbidden district. |
| 3200017 | 사원 열쇠.<br>가온국 유물 사원의 통로를 개방하는데 사용된다. | Temple Key.<br>Used to open the passage to the Temple of Artifacts of Gaon. |
| 3200018 | 아폴리온의 기원 중 '첫 번째 종말'을 다루는 메모리 카드. 사용 시 해당 기원 데이터가 재밍된다. | A memory card used for Apollyon's "First Apocalypse" origin. Jams-up the origin's data upon use. |
| 3200019 | 아폴리온의 기원 중 '두 번째 종말'을 다루는 메모리 카드. 사용 시 해당 기원이 데이터가 재밍된다. | A memory card used for Apollyon's "Second Apocalypse" origin. Jams-up the origin's data upon use. |
| 3200020 | 아폴리온의 기원 중 '세 번째 종말'을 다루는 메모리 카드. 사용 시 해당 기원 데이터가 재밍된다. | A memory card used for Apollyon's "Third Apocalypse" origin. Jams-up the origin's data upon use. |
| 3200021 | 아폴리온의 기원 중 '네 번째 종말'을 다루는 메모리 카드. 사용 시 해당 기원 데이터가 재밍된다. | A memory card used for Apollyon's "Fourth Apocalypse" origin. Jams-up the origin's data upon use. |
| 3200022 | 아폴리온의 기원 중 '다섯 번째 종말'을 다루는 메모리 카드. 사용 시 해당 기원 데이터가 재밍된다. | A memory card used for Apollyon's "Fifth Apocalypse" origin. Jams-up the origin's data upon use. |
| 3200023 | 기원의 탑에서 사용 가능한 초기화 장치. <br>사용할 경우 1회에 한해 기원의 탑에서 얻은 데이터들을 초기화할 수 있다. | A reset device that can be used at the Tower of Origin.<br>Can be used to wipe out all of the data from the Tower of Origin (1-time only). |
| 15510101 | 소중한 메피스토펠레스 | Precious Mephistopheles |
| 15510201 | 소중한 벨레드 | Precious Beleth |
| 15510301 | 소중한 클레르 | Precious Claire |
| 15510401 | 소중한 아키 | Precious Aki |
| 15510501 | 소중한 제이드 | Precious Jade |
| 15510601 | 소중한 린지 | Precious Linzy |
| 15510701 | 소중한 나오미 | Precious Naomi |
| 15510801 | 소중한 릴리트 | Precious Lilith |
| 15510901 | 소중한 캐서린 | Precious Catherine |
| 15511001 | 소중한 셰리 | Precious Cherrie |
| 15511101 | 소중한 도라 | Precious Dora |
| 15511201 | 소중한 지호 | Precious Jiho |
| 15511301 | 소중한 헤이즐 | Precious Hazel |
| 15511401 | 소중한 에일린 | Precious Eileen |
| 15511501 | 소중한 로제(홍염) | Precious Rose (Prominence) |
| 15511601 | 소중한 지호(미르) | Precious Jiho (Mir) |
| 15511701 | 소중한 셰리(낭만) | Precious Cherrie (Romantic) |
| 15520101 | 소중한 홍란 | Precious Honglan |
| 15520201 | 소중한 순이 | Precious Soonie |
| 15520301 | 소중한 아이라 | Precious Aira |
| 15520401 | 소중한 시하 | Precious Seeha |
| 15520501 | 소중한 미카 | Precious Mica |
| 15520701 | 소중한 플린 | Precious Flynn |
| 15520801 | 소중한 타샤 | Precious Tasha |
| 15520901 | 소중한 하루 | Precious Haru |
| 15521001 | 소중한 루테 | Precious Lute |
| 15521101 | 소중한 클라라 | Precious Clara |
| 15521201 | 소중한 소연 | Precious Xiaolian |
| 15521301 | 소중한 사쿠요 | Precious Sakuyo |
| 15521401 | 소중한 오닉스 | Precious Onyx |
| 15521501 | 소중한 사쿠요(업화) | Precious Sakuyo (Infernal Blaze) |
| 15521601 | 소중한 홍란(무쌍) | Precious Honglan (Peerless) |
| 15521701 | 소중한 하루(카무이) | Precious Haru (Kamuy) |
| 15530101 | 소중한 에리카 | Precious Erika |
| 15530301 | 소중한 르네 | Precious Renee |
| 15530401 | 소중한 탈리아 | Precious Talia |
| 15530501 | 소중한 칸나 | Precious Kanna |
| 15530601 | 소중한 이디스 | Precious Edith |
| 15530701 | 소중한 니콜 | Precious Nicole |
| 15530801 | 소중한 비비안 | Precious Vivienne |
| 15530901 | 소중한 미리암 | Precious Miriam |
| 15531001 | 소중한 클로이 | Precious Chloe |
| 15531101 | 소중한 나이아 | Precious Naiah |
| 15531201 | 소중한 마농 | Precious Manon |
| 15531301 | 소중한 다프네 | Precious Daphne |
| 15531401 | 소중한 도미니크 | Precious Dominique |
| 15531501 | 소중한 웨리 | Precious Wheri |
| 15531601 | 소중한 르네(백은) | Precious Renee (Argent) |
| 15531701 | 소중한 미리암(잔영) | Precious Miriam (Afterimage) |
| 15531801 | 소중한 라우라 | Precious Laura |
| 15540101 | 소중한 비올레트 | Precious Violette |
| 15540201 | 소중한 가넷 | Precious Garnet |
| 15540301 | 소중한 레베카 | Precious Rebecca |
| 15540401 | 소중한 멜피스 | Precious Melfice |
| 15540501 | 소중한 브라이스 | Precious Bryce |
| 15540601 | 소중한 프림 | Precious Prim |
| 15540701 | 소중한 재클린 | Precious Jacqueline |
| 15540801 | 소중한 벨라나 | Precious Velanna |
| 15540901 | 소중한 에루샤 | Precious Erusha |
| 15541001 | 소중한 페트라 | Precious Petra |
| 15541101 | 소중한 니니 | Precious Nini |
| 15541201 | 소중한 오토하 | Precious Otoha |
| 15541301 | 소중한 조앤 | Precious Joanne |
| 15541401 | 소중한 시그리드 | Precious Sigrid |
| 15541501 | 소중한 바이스 | Precious Weiss |
| 15541601 | 소중한 페트라(각혼) | Precious Petra (Awakened Soul) |
| 15541701 | 소중한 가넷(열락) | Precious Garnet (Rapture) |
| 15550101 | 소중한 클라우디아 | Precious Claudia |
| 15550201 | 소중한 아드리안 | Precious Adrianne |
| 15550301 | 소중한 유리아 | Precious Yuria |
| 15550401 | 소중한 한울 | Precious Hanul |
| 15550601 | 소중한 카넬리안 | Precious Carnelian |
| 15550801 | 소중한 클라우디아(대천사) | Precious Claudia (Archangel) |
| 15560101 | 소중한 라리마 | Precious Larimar |
| 15560201 | 소중한 리젤로테 | Precious Lizelotte |
| 15560301 | 소중한 아야메 | Precious Ayame |
| 15560501 | 소중한 이브 | Precious Eve |
| 15560601 | 소중한 니아 | Precious Nia |
| 15565101 | 소중한 캐서린(광휘) | Precious Catherine (Radiance) |
| 15565201 | 소중한 린지(타나토스) | Precious Linzy (Thanatos) |
| 15565301 | 소중한 메피스토펠레스(여명) | Precious Mephistopheles (Dawn) |
| 15565401 | 소중한 유리아(아폴리온) | Precious Yuria (Apollyon) |
| 15569801 | 소중한 토키사키 쿠루미 | Precious Kurumi Tokisaki |
| 15569901 | 소중한 야토가미 토가 | Precious Tohka Yatogami |
| 21510101 | 스티커: 소중한 메피스토펠레스 | Sticker: Precious Mephistopheles |
| 21510201 | 스티커: 소중한 벨레드 | Sticker: Precious Beleth |
| 21510301 | 스티커: 소중한 클레르 | Sticker: Precious Claire |
| 21510401 | 스티커: 소중한 아키 | Sticker: Precious Aki |
| 21510501 | 스티커: 소중한 제이드 | Sticker: Precious Jade |
| 21510601 | 스티커: 소중한 린지 | Sticker: Precious Linzy |
| 21510701 | 스티커: 소중한 나오미 | Sticker: Precious Naomi |
| 21510801 | 스티커: 소중한 릴리트 | Sticker: Precious Lilith |
| 21510901 | 스티커: 소중한 캐서린 | Sticker: Precious Catherine |
| 21511001 | 스티커: 소중한 셰리 | Sticker: Precious Cherrie |
| 21511101 | 스티커: 소중한 도라 | Sticker: Precious Dora |
| 21511201 | 스티커: 소중한 지호 | Sticker: Precious Jiho |
| 21511301 | 스티커: 소중한 헤이즐 | Sticker: Precious Hazel |
| 21511401 | 스티커: 소중한 에일린 | Sticker: Precious Eileen |
| 21511501 | 스티커: 소중한 로제(홍염) | Sticker: Precious Rose (Prominence) |
| 21511601 | 스티커: 소중한 지호(미르) | Sticker: Precious Jiho (Mir) |
| 21511701 | 스티커: 소중한 셰리(낭만) | Sticker: Precious Cherrie (Romantic) |
| 21520101 | 스티커: 소중한 홍란 | Sticker: Precious Honglan |
| 21520201 | 스티커: 소중한 순이 | Sticker: Precious Soonie |
| 21520301 | 스티커: 소중한 아이라 | Sticker: Precious Aira |
| 21520401 | 스티커: 소중한 시하 | Sticker: Precious Seeha |
| 21520501 | 스티커: 소중한 미카 | Sticker: Precious Mica |
| 21520701 | 스티커: 소중한 플린 | Sticker: Precious Flynn |
| 21520801 | 스티커: 소중한 타샤 | Sticker: Precious Tasha |
| 21520901 | 스티커: 소중한 하루 | Sticker: Precious Haru |
| 21521001 | 스티커: 소중한 루테 | Sticker: Precious Lute |
| 21521101 | 스티커: 소중한 클라라 | Sticker: Precious Clara |
| 21521201 | 스티커: 소중한 소연 | Sticker: Precious Xiaolian |
| 21521301 | 스티커: 소중한 사쿠요 | Sticker: Precious Sakuyo |
| 21521401 | 스티커: 소중한 오닉스 | Sticker: Precious Onyx |
| 21521501 | 스티커: 소중한 사쿠요(업화) | Sticker: Precious Sakuyo (Inferno) |
| 21521601 | 스티커: 소중한 홍란(무쌍) | Sticker: Precious Honglan (Peerless) |
| 21521701 | 스티커: 소중한 하루(카무이) | Sticker: Precious Haru (Kamuy) |
| 21530101 | 스티커: 소중한 에리카 | Sticker: Precious Erika |
| 21530301 | 스티커: 소중한 르네 | Sticker: Precious Renee |
| 21530401 | 스티커: 소중한 탈리아 | Sticker: Precious Talia |
| 21530501 | 스티커: 소중한 칸나 | Sticker: Precious Kanna |
| 21530601 | 스티커: 소중한 이디스 | Sticker: Precious Edith |
| 21530701 | 스티커: 소중한 니콜 | Sticker: Precious Nicole |
| 21530801 | 스티커: 소중한 비비안 | Sticker: Precious Vivienne |
| 21530901 | 스티커: 소중한 미리암 | Sticker: Precious Miriam |
| 21531001 | 스티커: 소중한 클로이 | Sticker: Precious Chloe |
| 21531101 | 스티커: 소중한 나이아 | Sticker: Precious Naiah |
| 21531201 | 스티커: 소중한 마농 | Sticker: Precious Manon |
| 21531301 | 스티커: 소중한 다프네 | Sticker: Precious Daphne |
| 21531401 | 스티커: 소중한 도미니크 | Sticker: Precious Dominique |
| 21531501 | 스티커: 소중한 웨리 | Sticker: Precious Wheri |
| 21531601 | 스티커: 소중한 르네(백은) | Sticker: Precious Renee (Argent) |
| 21531701 | 스티커: 소중한 미리암(잔영) | Sticker: Precious Miriam (Afterimage) |
| 21531801 | 스티커: 소중한 라우라 | Sticker: Precious Laura |
| 21540101 | 스티커: 소중한 비올레트 | Sticker: Precious Violette |
| 21540201 | 스티커: 소중한 가넷 | Sticker: Precious Garnet |
| 21540301 | 스티커: 소중한 레베카 | Sticker: Precious Rebecca |
| 21540401 | 스티커: 소중한 멜피스 | Sticker: Precious Melfice |
| 21540501 | 스티커: 소중한 브라이스 | Sticker: Precious Bryce |
| 21540601 | 스티커: 소중한 프림 | Sticker: Precious Prim |
| 21540701 | 스티커: 소중한 재클린 | Sticker: Precious Jacqueline |
| 21540801 | 스티커: 소중한 벨라나 | Sticker: Precious Velanna |
| 21540901 | 스티커: 소중한 에루샤 | Sticker: Precious Erusha |
| 21541001 | 스티커: 소중한 페트라 | Sticker: Precious Petra |
| 21541101 | 스티커: 소중한 니니 | Sticker: Precious Nini |
| 21541201 | 스티커: 소중한 오토하 | Sticker: Precious Otoha |
| 21541301 | 스티커: 소중한 조앤 | Sticker: Precious Joanne |
| 21541401 | 스티커: 소중한 시그리드 | Sticker: Precious Sigrid |
| 21541501 | 스티커: 소중한 바이스 | Sticker: Precious Weiss |
| 21541601 | 스티커: 소중한 페트라(각혼) | Sticker: Precious Petra (Awakened Soul) |
| 21541701 | 스티커: 소중한 가넷(열락) | Sticker: Precious Garnet (Rapture) |
| 21550101 | 스티커: 소중한 클라우디아 | Sticker: Precious Claudia |
| 21550201 | 스티커: 소중한 아드리안 | Sticker: Precious Adrianne |
| 21550301 | 스티커: 소중한 유리아 | Sticker: Precious Yuria |
| 21550401 | 스티커: 소중한 한울 | Sticker: Precious Hanul |
| 21550601 | 스티커: 소중한 카넬리안 | Sticker: Precious Carnelian |
| 21550801 | 스티커: 소중한 클라우디아(대천사) | Sticker: Precious Claudia (Archangel) |
| 21560101 | 스티커: 소중한 라리마 | Sticker: Precious Larimar |
| 21560201 | 스티커: 소중한 리젤로테 | Sticker: Precious Lizelotte |
| 21560301 | 스티커: 소중한 아야메 | Sticker: Precious Ayame |
| 21560501 | 스티커: 소중한 이브 | Sticker: Precious Eve |
| 21560601 | 스티커: 소중한 니아 | Sticker: Precious Nia |
| 21560701 | 스티커: 소중한 아야메(츠쿠요미) | Sticker: Precious Ayame (Tsukuyomi) |
| 21565101 | 스티커: 소중한 캐서린(광휘) | Sticker: Precious Catherine (Radiance) |
| 21565201 | 스티커: 소중한 린지(타나토스) | Sticker: Precious Linzy (Thanatos) |
| 21565301 | 스티커: 소중한 메피스토펠레스(여명) | Sticker: Precious Mephistopheles (Dawn) |
| 21565401 | 스티커: 소중한 유리아(아폴리온) | Sticker: Precious Yuria (Apollyon) |
| 21569801 | 스티커: 소중한 토키사키 쿠루미 | Sticker: Precious Kurumi Tokisaki |
| 21569901 | 스티커: 소중한 야토가미 토카 | Sticker: Precious Tohka Yatogami |
| 22510101 | 메피스토펠레스의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Mephistopheles Bond Level 40. |
| 22510201 | 벨레드의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Beleth Bond Level 40. |
| 22510301 | 클레르의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Claire Bond Level 40. |
| 22510401 | 아키의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Aki Bond Level 40. |
| 22510501 | 제이드의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Jade Bond Level 40. |
| 22510601 | 린지의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Linzy Bond Level 40. |
| 22510701 | 나오미의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Naomi Bond Level 40. |
| 22510801 | 릴리트의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Lilith Bond Level 40. |
| 22510901 | 캐서린의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Catherine Bond Level 40. |
| 22511001 | 셰리의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Cherrie Bond Level 40. |
| 22511101 | 도라의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Dora Bond Level 40. |
| 22511201 | 지호의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Jiho Bond Level 40. |
| 22511301 | 헤이즐의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Hazel Bond Level 40. |
| 22511401 | 에일린의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Eileen Bond Level 40. |
| 22511501 | 로제(홍염)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Rose (Prominence) Bond Level 40. |
| 22511601 | 지호(미르)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Jiho (Mir) Bond Level 40. |
| 22511701 | 셰리(낭만)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Cherrie (Romantic) Bond Level 40. |
| 22520101 | 홍란의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Honglan Bond Level 40. |
| 22520201 | 순이의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Soonie Bond Level 40. |
| 22520301 | 아이라의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Aira Bond Level 40. |
| 22520401 | 시하의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Seeha Bond Level 40. |
| 22520501 | 미카의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Mica Bond Level 40. |
| 22520701 | 플린의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Flynn Bond Level 40. |
| 22520801 | 타샤의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Tasha Bond Level 40. |
| 22520901 | 하루의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Haru Bond Level 40. |
| 22521001 | 루테의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Lute Bond Level 40. |
| 22521101 | 클라라의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Clara Bond Level 40. |
| 22521201 | 소연의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Xiaolian Bond Level 40. |
| 22521301 | 사쿠요의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Sakuyo Bond Level 40. |
| 22521401 | 오닉스의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Onyx Bond Level 40. |
| 22521501 | 사쿠요(업화)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Sakuyo (Inferno) Bond Level 40. |
| 22521601 | 홍란(무쌍)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Honglan (Peerless) Bond Level 40. |
| 22521701 | 하루(카무이)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Haru (Kamuy) Bond Level 40. |
| 22530101 | 에리카의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Erika Bond Level 40. |
| 22530301 | 르네의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Renee Bond Level 40. |
| 22530401 | 탈리아의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Talia Bond Level 40. |
| 22530501 | 칸나의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Kanna Bond Level 40. |
| 22530601 | 이디스의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Edith Bond Level 40. |
| 22530701 | 니콜의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Nicole Bond Level 40. |
| 22530801 | 비비안의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Vivienne Bond Level 40. |
| 22530901 | 미리암의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Miriam Bond Level 40. |
| 22531001 | 클로이의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Chloe Bond Level 40. |
| 22531101 | 나이아의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Naiah Bond Level 40. |
| 22531201 | 마농의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Manon Bond Level 40. |
| 22531301 | 다프네의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Daphne Bond Level 40. |
| 22531401 | 도미니크의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Dominique Bond Level 40. |
| 22531501 | 웨리의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Wheri Bond Level 40. |
| 22531601 | 르네(백은)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Renee (Argent) Bond Level 40. |
| 22531701 | 미리암(잔영)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Miriam (Afterimage) Bond Level 40. |
| 22531801 | 라우라의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Laura Bond Level 40. |
| 22540101 | 비올레트의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Violette Bond Level 40. |
| 22540201 | 가넷의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Garnet Bond Level 40. |
| 22540301 | 레베카의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Rebecca Bond Level 40. |
| 22540401 | 멜피스의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Melfice Bond Level 40. |
| 22540501 | 브라이스의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Bryce Bond Level 40. |
| 22540601 | 프림의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Prim Bond Level 40. |
| 22540701 | 재클린의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Jacqueline Bond Level 40. |
| 22540801 | 벨라나의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Velanna Bond Level 40. |
| 22540901 | 에루샤의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Erusha Bond Level 40. |
| 22541001 | 페트라의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Petra Bond Level 40. |
| 22541101 | 니니의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Nini Bond Level 40. |
| 22541201 | 오토하의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Otoha Bond Level 40. |
| 22541301 | 조앤의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Joanne Bond Level 40. |
| 22541401 | 시그리드의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Sigrid Bond Level 40. |
| 22541501 | 바이스의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Weiss Bond Level 40. |
| 22541601 | 페트라(각혼)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Petra (Awakened Soul) Bond Level 40. |
| 22541701 | 가넷(열락)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Garnet (Rapture) Bond Level 40. |
| 22550101 | 클라우디아의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Claudia Bond Level 40. |
| 22550201 | 아드리안의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Adrianne Bond Level 40. |
| 22550301 | 유리아의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Yuria Bond Level 40. |
| 22550401 | 한울의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Hanul Bond Level 40. |
| 22550601 | 카넬리안의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Carnelian Bond Level 40. |
| 22550801 | 클라우디아(대천사)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Claudia (Archangel) Bond Level 40. |
| 22560101 | 라리마의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Larimar Bond Level 40. |
| 22560201 | 리젤로테의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Lizelotte Bond Level 40. |
| 22560301 | 아야메의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Ayame Bond Level 40. |
| 22560501 | 이브의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Eve Bond Level 40. |
| 22560601 | 니아의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Nia Bond Level 40. |
| 22560701 | 아야메(츠쿠요미)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Ayame (Tsukuyomi) Bond Level 40. |
| 22565101 | 캐서린(광휘)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Catherine (Radiance) Bond Level 40. |
| 22565201 | 린지(타나토스)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Linzy (Thanatos) Bond Level 40. |
| 22565301 | 메피스토펠레스(여명)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Mephistopheles (Dawn) Bond Level 40. |
| 22565401 | 유리아(아폴리온)의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Yuria (Apollyon) Bond Level 40. |
| 22569801 | 토키사키 쿠루미의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Kurumi Tokisaki Bond Level 40. |
| 22569901 | 야토가미 토카의 인연 레벨 40 달성 시 획득 가능한 스티커. | A sticker that can be obtained upon reaching Tohka Yatogami Bond Level 40. |
