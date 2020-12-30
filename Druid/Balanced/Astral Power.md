## This will display all the Astral Power in 1 bar. You can choose the String version or the LUA Table version, you only need 1 version. (do not copy this line)
### STRING (copy below this)

!WA:2!1v1tVTrruCVArfvlfuRbknsv0qLO0a0iAHMcfAt86yx7sQT74nTPOISNDNXEh66DwnZS5pvCG6t9S)eG8zo5lCJd5tWilKGZ9aFaYNaEZSMK0QYk5vV3BF))979StTsdlrkrEX1NitXIN(igrf9(hyPB1VVKQ22rSxov91)5TD)Lcfki2pxWfNItcJ4I2CwIkOs1M(vrZSMI4kSIXtCsp7RWFFoH6vEl)wESqEsVrkbBWaQq(oxwmN8F8u7NsdKG(zYxkZcO7qtuDY63NT30Uvk3XVBh)YiFKvoQnFxQyejtyDFPRDqMK2vgX3TcxQ6nYWLLWu9ezjwd8Wzk(4uJvM4C2rYuACCdIS4rXQTGcXc1PD1n3eLGhsLf9m(iingVpvmZ4ZJCqVjeAaKC(aTOE1nBxBRnhNLmVykMEwCOITd1pN3u()wHjMAVBipMlUNl8Ci09OIeC8dHobufpymoHn0wqRIGgHqv7akws7Oe0KbQO3wVGxcpHo7)k7UMmriPGBjYrgvnPJEzVHywsn9vad0lR)u9NP)C9Yb9zjmz0Rl2tr3tfnkalQytS6R9x2N)U(A)XhAFCDHAvcJfiO0OtcrESZeO5HOdGCrERZPxykgucCvx43loxAjJVHPcMW3D7CtChBLzEDPpon9mNqJ847444(YCP04(weM(0PVRvIzgA6pHw0QxzG9q7hG5gLyf(8z5qZhNhoNdSF)NYKkw)91NAIWaiP(GqVMTAwvVGaQaJotSkE8Wjpp7ZtuPNPMG9SLEqgMaDa8s((VsHnpsxOqEO2HjzbX0EZSC7YfKhjWPJE0CIzh5wZOYRjmoN3eoXk1KgnBwf1DZQ18t)OJ6xGvcO67M2vXgcqrbnKzGnUPl(g0jNazuLCCq7WEgDX5TO5teN0l()fcY(WAalm6fVN(gU6vpOSujWXlz39030oQ0FT(06VrFl93(C935OVT(u67OxdayRRlFV2UFXkRwFTF)dSpUUApDf9gxOGUM(U6Q903BAEHIAC36(666g6wlQB78gQNK5eamoIYgeb3KUtH3cojvihpAgOzcA6vAywP6JdPpPcgM5jd8WINSvJREm3v7ymWlMJjpCSzNomglL5NmGJcH98mVVCGeupM6IgMfRyfrwTUS(jOnqB1yd9pw0tc9YZbeVuM7qAcXSNF9YBSr6zaVvMyGDucLCF8ErJpgoFkH54aSYSQ(tkQxPOhSyQa3mKZvrTf8bckKqVUpyjrte2vn7nN5BAtm7(mR3kod2pG5AR0C2X2ZnsgHISn4aGTpBqXP28ToJqOjOMvFyv0Cj2g7TfQ8EPOofhhWvxpJrMgT8tl)97S8n3(XiVNX5dDqwt6nrXd3j)615D6o(smIgDyo8QMaoHAs1GovqvR2eHJtJWUODnRP1xNTKZVcJVP9nQbx4Gnl38)kQYr7GcwIX50i7LZo8mri9cfMYfm4CT9c4K6Tqn(Hwn9lV5uctAUu3au98N2V7uwsoMbuR4Hb4WNoqWZsihDMXGoVrjj6lx5AR8vL25p3(Fp

---
### LUA Table (do not copy this line)

```
{
    ["sparkWidth"] = 10,
    ["iconSource"] = -1,
    ["xOffset"] = 453.50085449219,
    ["yOffset"] = 15,
    ["anchorPoint"] = "CENTER",
    ["sparkRotation"] = 0,
    ["sparkRotationMode"] = "AUTO",
    ["backgroundColor"] = {
        [1] = 0,
        [2] = 0,
        [3] = 0,
        [4] = 0.5,
    },
    ["triggers"] = {
        [1] = {
            ["trigger"] = {
                ["type"] = "status",
                ["subeventSuffix"] = "_CAST_START",
                ["use_showCost"] = true,
                ["duration"] = "1",
                ["event"] = "Power",
                ["use_unit"] = true,
                ["unevent"] = "auto",
                ["powertype"] = 8,
                ["spellIds"] = {
                },
                ["unit"] = "player",
                ["names"] = {
                },
                ["subeventPrefix"] = "SPELL",
                ["use_powertype"] = true,
                ["debuffType"] = "HELPFUL",
            },
            ["untrigger"] = {
            },
        },
        ["activeTriggerMode"] = -10,
    },
    ["icon_color"] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
    },
    ["internalVersion"] = 40,
    ["animation"] = {
        ["start"] = {
            ["type"] = "none",
            ["easeStrength"] = 3,
            ["duration_type"] = "seconds",
            ["easeType"] = "none",
        },
        ["main"] = {
            ["type"] = "none",
            ["easeStrength"] = 3,
            ["duration_type"] = "seconds",
            ["easeType"] = "none",
        },
        ["finish"] = {
            ["type"] = "none",
            ["easeStrength"] = 3,
            ["duration_type"] = "seconds",
            ["easeType"] = "none",
        },
    },
    ["text"] = false,
    ["barColor"] = {
        [1] = 0.37254901960784,
        [2] = 0.11764705882353,
        [3] = 1,
        [4] = 1,
    },
    ["desaturate"] = false,
    ["displayIcon"] = 611423,
    ["sparkOffsetY"] = 0,
    ["subRegions"] = {
        [1] = {
            ["type"] = "aurabar_bar",
        },
        [2] = {
            ["text_shadowXOffset"] = 1,
            ["text_text"] = "%p",
            ["text_shadowColor"] = {
                [1] = 0,
                [2] = 0,
                [3] = 0,
                [4] = 1,
            },
            ["text_selfPoint"] = "AUTO",
            ["text_automaticWidth"] = "Auto",
            ["text_fixedWidth"] = 64,
            ["anchorYOffset"] = 0,
            ["text_justify"] = "CENTER",
            ["rotateText"] = "NONE",
            ["type"] = "subtext",
            ["text_color"] = {
                [1] = 1,
                [2] = 1,
                [3] = 1,
                [4] = 1,
            },
            ["text_font"] = "Friz Quadrata TT",
            ["text_shadowYOffset"] = -1,
            ["text_fontType"] = "None",
            ["text_wordWrap"] = "WordWrap",
            ["text_visible"] = true,
            ["text_anchorPoint"] = "INNER_LEFT",
            ["text_text_format_p_time_precision"] = 1,
            ["text_text_format_p_format"] = "timed",
            ["text_fontSize"] = 12,
            ["anchorXOffset"] = 0,
            ["text_text_format_p_time_dynamic"] = false,
        },
        [3] = {
            ["text_shadowXOffset"] = 1,
            ["text_text"] = "Astral Power",
            ["text_shadowColor"] = {
                [1] = 0,
                [2] = 0,
                [3] = 0,
                [4] = 1,
            },
            ["text_selfPoint"] = "AUTO",
            ["text_automaticWidth"] = "Auto",
            ["text_fixedWidth"] = 64,
            ["anchorYOffset"] = 0,
            ["text_justify"] = "CENTER",
            ["rotateText"] = "NONE",
            ["type"] = "subtext",
            ["text_color"] = {
                [1] = 0.6,
                [2] = 0.090196078431373,
                [3] = 1,
                [4] = 1,
            },
            ["text_font"] = "Friz Quadrata TT",
            ["text_shadowYOffset"] = -1,
            ["text_wordWrap"] = "WordWrap",
            ["text_visible"] = true,
            ["text_anchorPoint"] = "INNER_RIGHT",
            ["text_text_format_n_format"] = "none",
            ["text_fontSize"] = 12,
            ["anchorXOffset"] = 0,
            ["text_fontType"] = "None",
        },
    },
    ["height"] = 30.000061035156,
    ["load"] = {
        ["use_class"] = true,
        ["use_spec"] = true,
        ["class"] = {
            ["single"] = "DRUID",
            ["multi"] = {
            },
        },
        ["spec"] = {
            ["single"] = 1,
            ["multi"] = {
            },
        },
        ["size"] = {
            ["multi"] = {
            },
        },
    },
    ["sparkBlendMode"] = "ADD",
    ["useAdjustededMax"] = false,
    ["sparkColor"] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
    },
    ["icon"] = true,
    ["smoothProgress"] = true,
    ["useAdjustededMin"] = false,
    ["regionType"] = "aurabar",
    ["actions"] = {
        ["start"] = {
        },
        ["init"] = {
        },
        ["finish"] = {
        },
    },
    ["sparkOffsetX"] = 0,
    ["icon_side"] = "RIGHT",
    ["authorOptions"] = {
    },
    ["sparkHeight"] = 30,
    ["texture"] = "Healbot",
    ["alpha"] = 1,
    ["zoom"] = 0,
    ["spark"] = true,
    ["width"] = 201.00019836426,
    ["id"] = "Astral Power",
    ["sparkHidden"] = "NEVER",
    ["frameStrata"] = 1,
    ["anchorFrameType"] = "SCREEN",
    ["sparkTexture"] = "Interface\\\\CastingBar\\\\UI-CastingBar-Spark",
    ["uid"] = "h)kAKv)7XYR",
    ["inverse"] = false,
    ["config"] = {
    },
    ["orientation"] = "HORIZONTAL",
    ["conditions"] = {
    },
    ["information"] = {
    },
    ["selfPoint"] = "CENTER",
}
```
