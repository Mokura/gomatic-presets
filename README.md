# Gauge-O-Matic Presets
Fancy new gauges for your favorite Final Fantasy XIV jobs.  Some gauges might arrive later, largely due to personal lack of skill with some jobs.  Suggestions are welcome!

## How to Use
1. Open the Gauge-O-Matic menu with `/gomatic`.
2. Click on the icon for the job you want gauges for.
3. Look for the gauge you want below.  After a description of the gauge's function, there's a code block with ~~absolute nonsense~~ encoded settings text.  Copy it to your clipboard (Github should have a button for this, too.)
4. Go back to the Gauge-O-Matic options, and press the "presets" button.
5. Press the Import from Clipboard" button.
6. Press the "Overwrite Current" button.  This will overwrite any current Gauge-O-Matic preset you may already be using.  Please, backup accordingly.
7. Close the settings window and enjoy.


## Notes
- These gauges were made using Material UI Reborn, with Silver parameter bars.  You might want to tweak positioning on other UI (including vanilla).
- (currently) All gauges are anchored to your parameter bars, at 100% scale.
- By default, all gauges are hidden except during combat or duty.  Gauges for mechanics you are underleveled for will also be hidden.

## Color Splash gauges

### Progress
**Currently Available:** PLD, DRK, NIN, DNC, RDM, SMN  
**In Progress:** WAR, GNB, DRG, SAM, SCH, SGE, MCH  
**Skill Issue:** RPR, WHM, AST, BRD, BLM, PCT  
**Code/Gauge Issue:** MNK, VPR

### Paladin
![image](https://github.com/user-attachments/assets/8d7528b9-2ffc-4878-9a23-efa371a639a4)

- Background swirl: Iron Will (tank stance) de/activated.
- Top markers: Requiescat stacks, hides when empty.
- Middle gauge: Oath Gauge.  Sound effect at 100.
- Bottom left markers (1): Divine Might, highlights when proc'd.
- Bottom left markers (2, 3, 4): Atonement combo highlights.

```
H4sIAAAAAAAACt2VbW/bNhDHv0pxr7lAz5L5rnbSNFjSGlOAbC2CgpKOMlFJNCSqWWv4uw+kZNmWPBRGuyGNCRjkn+QdT787cgPvWIlAYSELWb+K1wVrVq+Wt5dA4L5m6WesG6AfN/AgshzVQlZc5EA3EItyXeCc1Qtuxg8iUyugdmBdWATm18YeUAi5bugDgTc1K3GnB55unAOBOyaqncx5EnqZka+PZMsy4mU9Unt92RbNYBvdGQvcke4AhcwOXC80E7csweIe/1bLWq4bHYEeAAUgcFWxpMAMKGdFgwSWshFKyAroZktg77376Q1ZPjg3whtZKaB214nFNwRqRwReFyKvgHpbAu/a8sj74FPV7bFL+FNvvrC+73rGI9dPjByv5NM831mb58c4hjP2R/MJ3FRfsFZDyHr/B6zl/hvUmIrGnMg6iK+PyN8SuBMFNkpWeP91jWbVKIjANbnxF9DfbNsyAcWyrbJuvd2PBjNAbbOmy7xu0T7tYEvgVpRC3eIXLP5gVY67aN+KDN+3qhEZLmSZMHXZqq+7yT6pe3PvmVpdszbHXgYCr7NMVn1RfFoynbMK6+4Qh7nRmTPe70QF1PW3ZAM3CsubDKgThC6ZFM2SFagULpHVRV83c9Z04y5d/qVEuh1af9D57Yde2E1ccY6pauzTsjOS92bmx7W2M3NadkZyvGapqHKgjqOBxikrMF4JrlPiYsrdnw3cQ6fD3hm4k5ngAuuTpA+/1c+BHSum2ubHSQfeIWnbDaKfSFrHc1Wu9zH8J+gDL/F5MEE/lZ2RfDZ6Z1Lyvzb7SLMf0/6dfcOSKSniJymblXaGA/X0c1bLtaavX1KL2Lv2SIbZe1EpPXt4Px989Zkf+mk27nIescA3XY+nrt4HjwQWhWwzbay7uU0EJ/52K01OGN/GUmTpdmb3kUD8hLje25rxkCc/Fsc4lfz96+HoVBonzSkIOnn+v+fg6FqYWc5zfwC8LAlYOrkFprIzks+8BQLbeVEPQBgcknYjJ3zupA9K7PipH8vOSD6XtOu9bNLRcyedsCBKownpqeyM5PhM0n7w0kg/bv8B71ve6w4PAAA=
```

### Warrior

### Dark Knight
![image](https://github.com/user-attachments/assets/e04a7f06-fd0c-405e-9906-176d45d298cb)

- Background swirl: Grit (tank stance) de/activated.
- Background spinner: Living Shadow de/activated.
- Top markers: Blood Weapon stacks, hides when empty.
- Top gauge: Blood Gauge.  Sound effect at 100.
- Bottom gauge: Darkside buff timer.
- Bottom markers: Shadowbringer uses remaining.

```
H4sIAAAAAAAACu1WbWvbOhT+K+N81i1+iWPH35r0ZWXtFuZAt13KRbGPHFFbCrbcbiv570PyW+J6XEazDcYsMNLjoyOd85xH8hO8pTlCCAuZyeJVtM1ouXl19v4NEFgVNL7HooTw3ye45UmKaiEF4ymETxDxfJvhnBYLZsa3PFEbCO2pdWIRmF8afxCCz3RDDwhcFDTHFp9OdGMMCNxQLloYPd/1XQNf7sGMWZYBz4oB2uDLKis73+jO6NQd4A6EkNhTd+KbD9d0jdkKP6tlIbeljkAPIAQgcC7oOsMEQkazEgksZckVlwLCpx2BfvX60ROStFvcABdSKAjtuhPxrwihHRA4zXgqIJzsCLyt8oPVuzVVUR0uCR/0ZJ3VjxD+48xOrP/fxIwFrrc2cLSRj/O09TtPD4npdtts0iNwJR6wUF3wev4nLGSfjQJjXpq9WXuRNrF5OwI3PMNSSYGrL1s0VoNwpq7fxmM7rgkokpVIanu7GXVuILSNTV2DtVFfgLAjcM1zrq7xAbP3VKTYRvuaJ/iuUiVPcCHzNVVnlfrSfmzKu3E3z6RMLmmVYoMDgdMkkaLRx39LqstXYVHvYr9Man9m+RsuIJw6O/LLFLOm0yAO/ipmRDF/gE6sTie2dWLtfrIIzmhxr+2OpAPX0jq4UphfJRD6E4c8E8WSZqgULpEWWaOLOS3rcV0O35GAjuo83/aR1C604W19j0z82vKcMYxVaY/DzgDu3cwPr6PWzTjsDOBoS2MuUggdRzMYxTTDaMOZroGTEaIt69mBWHu4kQlnHIvRM3A/e8epgEhRVZVHoN7bp97xfM8/Ivk/heuZ53tx8ozr57AzgH+Qay/oLj/f/o1Un8Z6Uy+nemZUPuT2ggtebq5iKRpmTZ71v+T+iRpYujEGdzoLqN3bJmcrjDffOdm9oNeKVf8NmZSbtJnHGSav38xxUnfNH7hIow1N5OPLExiMJvAN/Yo5VZJHj1KWGy1M7EQS3yeF3Gqx6IxaxG7bHem+rrhQw3zvVe14l7GATj3TnbDY1fM0N4tMVol2Vt9tJoKRV2vZc33I8o90dUU8Im57XzPms/XL4hiWkrd37I7dr2Mk6BL6hT+Wu7vdNzQmr9elDQAA
```

### Gunblade
![image](https://github.com/user-attachments/assets/3e7a6f2d-0458-400f-924f-11d6110bc72a)

- Background swirl: Royal Guard (tank stance) de/activated.  **Note:** Currently animates the swirl when you gain a cartridge charge.  This is unintended, but cool, I suppose.
- Top markers (1, 2): Aurora uses remaining.
- Top markers (3): Heart of Stone un/available.
- Middle gauge: Time until Gnashing Fang combo is ready (ready when full).  **Note:** Currently fills the bar to the recast timer for the rest of the combo before properly tracking the cooldown.
- Bottom markers (1, 2, 3): Powder gauge.
- Bottom markers (4): Bloodfest un/available.

```
H4sIAAAAAAAACt1VW2/aMBT+K9N59qrcA3kr9LJqbYcWpO4iNJn4OFgNMUpMWYvy3yfnBgSqlfVh3bCEnM/2uX3fsddwS+cIAQxlIrN34SKh+ezd5e0ACIwzGt1jlkPwfQ13gsWohjLlIoZgDR/pE86pkiJcSZnPQkUVDnm5NKDRPcvkYkBz1IcNYjZjQtrVsUiVXgWf68E5EOC8Rz23nPZd341Yd7q1weGRrc/BhMAwkUumjXGa5EhUtjz41+wscy19l5Z6hh5HTicEwhXiYmOrz30+fV0eI5kLJWSqq/gFAtc1TgwCXyF4b1rGiVEUpOZh/LjQpB0iAQoCHwTDT0uVC4ZDOZ9SdbZUjxCUhWhorU2M5IphdkmXMdYLQOCUMZnWwvgxohmdo8Kscg0EzlM6TZBVBguyhiuF8ysGgemZjkf2tBKK+SLBAc1qgdwJpmZ6d5ne4LKsIQS1EtAFAhfaZ4N7jh5ltW6oSBuY86nvVPW83IGNiquzrIPW+GiZ5K1ttPvUszu4BQEw07MdzQuBazrFZIw/1SiTi1xnoD8ggO1aVNLbprAgsPFe/fQBFrfOS+BCpgoCs5qE4gkhMHsEThMRpxA4BYGr9AEz1fB3u5zvxLLDxp6GzN6J8ftA+rxnu9MSDmdyNYgba4N4l5w24jpQdxNdXQB9/htmclORDCORlxEZW9nW+bkFgRuRYK5kipUmjb0kPHvTCKZuBAKhXKasPQiBWaI73dHKTrfEtZgLdY0PmHymaYxNfkd0ymmkI/qzJiFQur4RKQSe0WkZz9lvmRFNUCkcIc2S9lrNq+9KLM80SHVC43da3a7v+NXCOecYqdw8DFsdeGNmUC3Yvr1j5jBsdeBwQSORxhBYliYwjGiC4UxwLYGTAzy7XsOzbz1Hc2v1RjLBBWYHyd8u4Nvi3/c0/2+bcM+ZutzbI3wftjrwkYS7feNFhGtQd4vf/1vsv/qd3JaA3b0CXPOtXwE9M/J7u2YOw1YHPloR1guu+n/9DnDc7hvw5gXgsKlHoz0B7MNWBz72DbDbN+A/FoDXKybFLyREMnp9DQAA
```

### Monk

### Dragoon

### Ninja
![ffxiv_dx11_05-29-2025_19-12-37](https://github.com/user-attachments/assets/3f18a216-1111-4b55-b4c0-bec725df6c11)

- Background swirl: Kazematoi available
- Top markers: Kazematoi stacks.  Sound effect at 5/5.
- Middle gauge: Ninki gauge.  Sound effect at 100.
- Bottom markers: Mudra stacks.

```
H4sIAAAAAAAACs1Va2/aMBT9K9X97FV5kAT8rdDH0ApDC1L3EJpMch2sJjFKTLsW8d8nOyFAYN2qatNiKbKPfc/1zTl21jBmGQKFgUxlcRYuU1YuzsbDMRCYFiy6x6IE+m0NdyJOUA1kzkUCdA2hyJYp9lkx4GZ8J2K1AGr71rlFoH9j+IBCwHVDDwhcFyzDLe53dOMcCIyYyLcweoEbuAa+2YM5tywDXhYttMYnq7RsuNHtMd9t4Q5QiG3f7QRm4pbNMZ3iDzUp5LLUFegBUAACVzmbpxgD5SwtkcBElkIJmQNdbwjsslePDoiTJrkBrmWugNpVJxTPCNTuErhIRZID7WwIjFfZQfYmpypWhynhsw4+t36fuse7rjc3cLiQj/1ky9ZPDuVo9lhvzSMwzB+wUE3JOv4rFnL3DQqMRGl2ZO3VV1fkbQiMRIqlkjlOn5ZoVrWK8F3jjS9A39m2ZQoK5SqPq/V2PWpogNpmTeW8atHOdrAhcCsyoW7xAdNPLE9wW23t2zpiLPJ7ccNWCdY4ELiIY5nXxv8+YdqXCosq0b7+FZ/JMBI5UN/ZkOOjMGEpKoUTZEVan4Y+K6txZYJfGL+K0PhdZf1OUE1ccY6RKu3TsNOCdzR9oDBnfjfqHtCchp0WHC5ZJPIEqONomcKIpRguBNdCnx+r6fWcIzUrhpGMBRdYnBRw/2P9sYYf2DNmTEnxdgm9jpZwqDAbxrpUr0f+c0E78dxn0ZGgx7DTgl8taHM8A+fv6nkR6bxvF9O1Tp3Hxi3ho5TlIlRMYSNjdB8Xcqnl1P81i9jbNiPN7FTkSs/u35Y9L/Ci+IUu513me6bb4ZGr42BGYJDKVazJqnvUVHDitV1pVDe5DVPX0u2V3RmB8BFxuePq8YDP31bHpGUWb3eXO/r0t31xSoQX/PFexPhxpUoR40Bmc6YuV+rpX1wGs81PsRZ4fQMJAAA=
```

### Samurai

### Reaper

### Viper

### White Mage

### Scholar

### Astrologian

### Sage

### Bard

### Machinist

### Dancer
![image](https://github.com/user-attachments/assets/ea66d6a5-44ae-4ab8-a33e-1a49b72465ea)

- Background swirl: Current dance step color.  Changes color based on step required to continue.
- Top gauge: Esprit Gauge.  Sound effect at 100.
- Bottom gauge: Standard finish buff timer.
- Bottom left markers (1, 2, 3, 4): Fourfold Feathers.  Sound effect at 4/4.
- Bottom left markers (5): Threefold Fan Dance, highlight + sound effect when proc'd.

```
H4sIAAAAAAAACu1WWW/bMAz+KwOftcJHbCd+W9JjxdoumAt0B4pBsSlHqGMZstyuDfLfB8lHHC87ug7bMCwCAukjRYriR8pruKArhBBmIhPyWVRktFw+O7yYAYFLSeMblCWEH9ZwxZMU1UzkjKcQriHiqyLDKZUzZtZXPFFLCG3fOrAITE+MPQghYHqgBwSOJV1hi/sjPRgDAueU5y3M2CIYJQY+2YEty4CHcoA2+LzKys42uhPquwPcgRAS23dHgRGc0QVml/hJzaUoSh2BXkAIQOAop4sMEwgZzUokMBclV1zkEK43BLbe65/ekKSdcwMci1xBaNeTiD8ghPaYwIuMpzmEow2Bi2q1473zqWS16xLe6s36Vt9B+NyZHFjfP8SEjV1vYeBoKe6maWt3mu4mpjttc0iPwGl+i1J1wev971GK7W1IjHlpzmb1Im1i8zYEznmGpRI5Xt4XaLQG4fhu0MZjO64JKBJVntT6drPqzEBoG52ag7XSloCwIXDGV1yd4S1mb2ieYhvtS57g60qVPMGZWC2oOqzUfSts6N2YOyoLydUJrVJsBEDgRZKIvCmQj3Oq+atQ1sfo86Q2aPyf8xzCwN+QNZwqXJ0mOnmOTX5XAY3tOBjX8P8C2i2gf6BsrK5sbOvA2nyzJh5B/khRVZU/x3vN9CG35zRDpXCOVGYNvae0rNd1Vr/C5HqHxq80Db1gFNSCI8YwVqW9H3YG8NbMdLckWjP7YWcARwWNeZ5C6Dj63qOYZhgtOdOZO/gyPd540qYncH6sqXU+zkXCGUe5t9X1r/PXdLtjUUkmsuTprc61Bq3OIn85HXqfGH06fAk7A/iRdPCD4Pt00JcWTP4UDZ5S930S+Oa9G6b9FX3AFVWCR3dClEvtDLv0xzeJFIWmgf6+tIjdjmvSSS95rrS033TRC9ygfpr80cJjvpn2iraXsBGLXb0PrgnMMlEl2ljdjk0Ee/5aTcMW47u2b+nxyOk1gegOsdjamrCALZ4Wx3zQc7ztk+DsexL2JeHXkOeQ5jFGCoun88f2NtebzwLxAaGLDAAA
```

### Black Mage

### Summoner
![image](https://github.com/user-attachments/assets/6331a28f-e454-47b5-91dd-fdbb2451826c)

- Background swirl: Current active summon.
- Top markers: Aetherflow.  Hidden when empty.
- Middle gauge: Time remaining on summon.  **Note:** Currently, timers for Bahamut, Phoenix, and Solar Bahamut are not tracked, due to some weirdness in how summon phase tracking works.
- Bottom markers: (Ifrit, Titan, Garuda only) Elementally attuned Rite/Catastrophe actions remaining, followed by Primal's Favor action in/active.  Hidden when empty.

```
H4sIAAAAAAAACu1X72+bSBD9V6r5vLX4jc232E170SU5q1hKe1V0WmDWXhVYC9bNJZH/99MCxhicixo7iSMnSBE8dobdfW9mn+/hkiYIHoxELLIP/jym+eyDf3EJBCYZDX9iloP34x6ueDRFORIp41Pw7sHnyTzGIc1GrHi+4pGcgac7Wk8jMPxS5AMPXKYutIHA54wmuMIdS12MAYELytMV3NdDt1/CXxqwxQI9iAr4U9bAAzawLK3Ax4s4r7OjOaCO2cIN8CDSHdNyixfnNMB4gv/KcSbmuVqDegAPgMBpSoMYI/AYjXMkMBY5l1yk4N0vSblX4AGr/lRANK0/XgCfRSrB08sbn98heHqfwEnMpyl41pLAHzzC02Qub8GT2QIJXC6SjenUkyhfN+YA31S2nvb4XAasb9pBAfszcTOcrrINp5sM1ZOu5moTOEt/YSbrPVDxf2Mm1puSYcjzYkZaY8HVEu0lgQseYy5FipPbORajWotwzEIu38H7qOtaT1suSaW0MmItM6h27K+FzHmEI5EEVH5arHevUmsVd5pgRuOoAoHASRSJtNL6P2OqpCgxK7/VJFwlW5Ku3sc0RilxjDSLK8kPaV4+lzw/oO4OzWUKNfBKKdV2LbccecoYhjLXt8NGC16nGW7WzSrNdthowf6chjydgmcYigk/pDH6M84Ul70uYfagJsw1CgFWCS5ExBnHrAhrs9jcvJcm8kxichaBZ7iGTY6G1pMso+kUE6yK8jGaz+mtWMhznsui238Hz7AVflXxWZBfxm5AltXTltfdunb7K5kM3JeQiS+pXOT7K/c/6R0mVAru3wiRz1R6rPUR/owyMVc6UWejTvRrUqMTnkqFNttqzcs1gVEsFpEaUDZR9f0VWrBexJZRmrrKKP8Gcb5+P2AuC7q51X6dpTSU/Bc+cGrY9rrhGtsa7raFv3bvfSavwVjgWqWpePca717jyV5jIub07micRqNqmkdSFzZa8KE7jR1prH1G3zbJ0ZD67jMOyGfUvDyDz2jmPhCfsee++0wuA23XdM2jcBnvpmJ/puLrIrjdy49e680dRmi7jut0DiO0Xdu1O4dRI81rH0am+bYPo8PXxaqTtnTRgo0W/LvOsz94Wee5n1o3tbdX6gF1+mG/Q2kXNlrwjqX+TfXrHUrd1Qabbf+4jWdda89gPJu5D8R47lavOzChEX11PcKIFQUODYvbge3aYdS+ZaxPnfI0tVhoqrgH2Nv27zFGf+f2f9m3nriOV1CFv0gSkT5RF9fL/wC6B663ih0AAA==
```

### Red Mage
![image](https://github.com/user-attachments/assets/319eb241-9fb2-44f5-9dea-5f7379df2a85)

- Background swirl: Manafication active.  I'd like to replace this with Balance Gauge later.
- Top markers: Magicked Swordplay.  Hidden when empty.
- Top gauge: White Mana Gauge.
- Bottom gauge: Black Mana Gauge.
- Bottom markers: Mana Stacks.

```
H4sIAAAAAAAACu1Wa2+bMBT9K9P97EU8Qgh8a9LHqjVdVCJlD0WTA9fEKuAInHZtxH+fzCuEZJq6ZQ9Ny5UifMy918fnYNjCLY0RXBiLSKSvvHVEs9Wru/MJEJil1L/HNAP30xbmPAhRjkXCeAjuFjweryMc0XTMivGcB3IFrj7QehqB0VVRD1ywmQq0gMBlSmOs8UFfBWNAYEJ5UsOoqSjgqxbMmFaC52kHrfDpJsqa2mg6dGB2cANcCPSB2beLiRu6xGiGX+Q0FetMMVADcAEIXCR0GWEALqNRhgSmIuOSiwTcbU5g1738qYQgbJoXwKVIJLh6eeHxZwRXHxI4i3iYgNvPCdxu4r3uTU+ZbvZbwnuVrHb1A7ivDaenfX8RDhua1rKAvZV4HIV13VG4L0yz2mqRFoHr5AFT2ZBX+R8xFbvdSNHnWbE2rcW04mblBCY8wkyKBGdPayzu6tAZmHbNRzfMnpbnpDJYmbFzF+QE3vAA321kxgMci3hJ5flGPtWEKpNWefMVlzihCa1gIHAWBCKpTP55SpUHJaZlt7bWqlxOfpvRHcu2/OC/0Y8Y/R+wt9bYW9dOaO9RRP3709p7SiOUEqdI06hy+Ihm5bgU9htmLjMUPldOtOy+XU5cMIa+zPTjsNGBd2VG5YRpm3tljsNGB/bW1OdJCK5hqK33fBqht+JMidc7VMgaOrVCtlE4riowEQFnHNMirStbe6+Ucjc85vIGHzC6o0mItWYvEFRp6Unq3/+YoASK7hOegDsYKnmvJcbXAbjm0LbI6cRWlC7i9Y7GL1HfdoYDf3mg/iFsdOCXqu84+6+fPyW/J6ncZCfQXmtrrzu2fqj9W/qMMZWCe49CZCvVGhsP+PdBKtbKC+prTyN6HQvSzM54ItVs+2htPYGtL7cWytjS7pevuT7zTZUHCwLjSGwCVaw8dAs+R/7qOwuHFL2LSkNNxQsvFwS8R8T1rpbDbLb8OR7TjrGs3cFvHDv4j4nw11lpkX8FJrsO1BYMAAA=
```

### Pictomancer
