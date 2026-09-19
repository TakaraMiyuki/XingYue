# 星月 (Xing Yue)

**Minecraft Java 26.2 + NeoForge 26.2.0.88** 的原创武器模组（**测试版**）。

**"星月"是一把蓄力爆发之剑**：长按右键蓄力（弓姿势），蓄力 45 刻自动爆发——对周围 3 格内实体造成 4 点伤害并击退，自身跃起约 5 格（落地免摔），迸发星月粒子。

- 稀有度稀有、耐久 1680、面板 7 点攻击伤害，创造物品栏"战斗"分类
- 支持风爆附魔（与下坠攻击联动）
- 与盾牌共持时无法蓄力，盾牌可正常格挡
- 安装[飞翔模组](https://github.com/TakaraMiyuki/Flying)并给星月附魔"飞翔"后：跃起时按跳跃键可在空中向前上方突进

## ⚠️ 测试版说明

本模组处于 **0.1.1-beta** 阶段，功能仍在完善：

- 后续版本可能调整数值、特效与机制
- 升级 0.1.1-beta 前请备份存档（mod id 由 examplemod 改名为 xingyue，旧测试存档中的星月物品会消失）
- 反馈问题请开 [Issue](https://github.com/TakaraMiyuki/XingYue/issues)

## 获取

从 [Releases](https://github.com/TakaraMiyuki/XingYue/releases) 下载 `xingyue-0.1.1-beta.jar` 放入 `mods/`。

## 联动模组：飞翔 (Flying)

[飞翔](https://github.com/TakaraMiyuki/Flying)是重锤专属的机动性附魔（公开已发布）。两个模组**互相独立、互为可选依赖**——通过共享物品标签 `#xingyue:enchantable/flying` 联动，任意安装组合均正确工作：双装时星月与重锤都可附魔"飞翔"并空中突进。

## 构建

```bash
./gradlew build    # 产物在 build/libs/
```

要求 JDK 25。

## License

[MIT](LICENSE)。星月的像素贴图为原创作品。
