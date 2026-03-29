---
# https://vitepress.dev/reference/default-theme-home-page

layout: home

hero:
  name: "Hardware_show_my_works"
  text: "Design_&_Debug"
  tagline: My project tagline
  actions:
    - theme: brand
      text: 查看核心项目(DCDC)
      link: /lcc-converter
    - theme: alt
      text: 简历下载 / 联系方式
      link: /gressp.pdf
      # 留空或后续替换为简历文件的路径，例如 /resume.pdf

features:
  - title: AHB 脉冲电流源
    details: 独立设计。实现脉冲电流可控，输出可达 800A@4ms，采用不对称半桥结构。
    link: /ahb-current-source
    linkText: 查看详情
  - title: LCC 谐振变换器
    details: 独立设计。峰值效率达 96%，实现充电全过程低环流 ZVS 边界运行。
    link: /lcc-converter
    linkText: 查看详情
  - title: Marx 脉冲电源
    details: 参与设计。负责光纤隔离驱动设计、单片机主控板原理图与 PCB 设计。
    link: /marx-generator
    linkText: 查看详情
---