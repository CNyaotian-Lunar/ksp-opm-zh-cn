# KSP Outer Planets Mod 简体中文补丁

为《坎巴拉太空计划》(KSP) 的 **Outer Planets Mod** 提供简体中文本地化，覆盖全部 2313 条本地化条目。

**本仓库只包含翻译文本。不包含任何原模组的模型、纹理、代码或配置。使用前请自行安装 Outer Planets Mod。**

A Simplified Chinese localization for **Outer Planets Mod** (KSP), covering all 2313 localization entries.

**This repository contains translation text only. It does not include any assets from the original mod. You must install Outer Planets Mod separately.**

---

## 覆盖范围 / Scope

| 文件 / File | 条目数 / Entries |
|---|---|
| `GameData/0001_OPM_CN/OPM-zh-cn.cfg` | 2313 |

包含：天体名称、天体描述、生物群系名称、实验报告文本、KSPedia 相关条目。
Includes: body names, body descriptions, biome names, experiment reports, KSPedia entries.

---

## 安装 / Installation

1. 确认已安装 Outer Planets Mod。
2. 将本仓库的 `GameData/0001_OPM_CN/` 目录复制到 KSP 安装目录的 `GameData/` 下。
3. 启动游戏，语言设为简体中文。

```
Kerbal Space Program/
└── GameData/
    ├── OPM/                    (原模组 / original mod)
    └── 0001_OPM_CN/            (本补丁 / this patch)
        └── OPM-zh-cn.cfg
```

1. Make sure Outer Planets Mod is installed.
2. Copy `GameData/0001_OPM_CN/` into your KSP `GameData/` directory.
3. Launch the game with language set to Simplified Chinese.

本补丁尚未收录进 CKAN，请使用手动安装。CKAN listing is not available yet.

---

## 翻译约定 / Translation conventions

- **天体名称保留英文原文**，不音译：`Sarnus`、`Urlum`、`Neidon`、`Plock`、`Hale`、`Ovok`、`Slate`、`Tekto`、`Polta`、`Priax`、`Wal`、`Tal`、`Thatmo`、`Nissee`、`Karen` 等一律不译。
  Celestial body names stay in English and are never transliterated.
- **生物群系名称音译**，涉及其他作品的梗按对应官方中文译名：`Vader Crater` → `维达撞击坑`、`Ryloth Region` → `赖洛思区域`。
  Biome names are transliterated; references to other works follow their official Chinese names.
- **格式控制符原样保留**：`\n`、`^N`、`<i>`、`</i>`、`<br>`。
  Format control sequences are preserved verbatim.
- **实验报告口语化**，保留原文的幽默与吐槽语气。
  Experiment reports keep the original colloquial and humorous tone.

完整生物群系译名表见 `TERMS-biome-map.json`。
The full biome mapping is in `TERMS-biome-map.json`.

---

## 兼容性 / Compatibility

- 游戏版本 / Game version：KSP 1.12.5
- Outer Planets Mod：2.2.12（更早版本可能有条目缺失 / earlier versions may miss some entries）

---

## 已知问题 / Known issues

- 上游新增文本时对应条目回退英文，等待本补丁同步。
- 翻译由 AI 辅助初翻，格式、条目完整性与术语一致性经过程序校验；个别语句可能生硬，欢迎在 issue 报告（请注明 localization key）。
- New upstream strings fall back to English until this patch is updated.
- Translation was produced with AI assistance and machine-verified for format and completeness. Reports of awkward phrasing are welcome.

---

## 许可 / License

翻译文本继承 Outer Planets Mod 的许可：**CC BY-NC-SA 4.0**。详见 `LICENSE`。

The translation text inherits Outer Planets Mod's license: **CC BY-NC-SA 4.0**. See `LICENSE`.

### 致谢 / Credits

- Outer Planets Mod — Poodmund 及其贡献者
- 翻译与校验 — CNyaotian-Lunar

---

## 贡献 / Contributing

发现错误请开 issue，注明 key（形如 `LOC_OPM_Planets_Sarnus_description`）。上游更新后同步新条目的 PR 欢迎。
Open an issue for errors with the localization key. PRs syncing new upstream entries are welcome.
