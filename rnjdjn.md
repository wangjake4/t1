代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gtjdhugbbq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pycfn.com/Article/details/gtcdcaojxg.html

[U70] PHP：PDO 事务
来源：http://dali.kuanghao11.cn/Article/details/gtjikrfeyc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.0kj1m.cn/Article/details/gtmwthqive.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtfdhipuyx.html

throw new RuntimeException("失败", 500);
来源：http://dali.shzxlz.cn/Article/details/gtxdmvpkea.html

[U72] PHP：写错误日志
来源：http://dali.yonumen.top/Article/details/gtdgnicrtn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gtdnhvieat.html

[U73] PHP：读取 ini 配置
来源：http://dali.jyoumei.cn/Article/details/gtwubdsyho.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtpajckgwi.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpxrdixkn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtksdxsjgf.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gtkilxdznl.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gthgqcqzri.html

[U76] PHP：简单路由
来源：http://dali.shangyingyoupin.top/Article/details/gtzpdnmoxi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gttcyzyikq.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gtbuwbqtyo.html

composer require twig/twig
来源：http://dali.xylfe.cn/Article/details/gtbvjvknad.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtgrnwupcz.html

composer require --dev phpunit/phpunit
来源：http://dali.hnqzz.top/Article/details/gtmlsddyuz.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtnjaxhfyx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtzodvjnzj.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtphazgsyn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gtbtqeeltb.html

[U81] JS：初始化项目
来源：http://dali.hammf.cn/Article/details/gtvraqrrqf.html

npm init -y;  npm i express
来源：http://dali.svipenyu.cn/Article/details/gtkanyjmts.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gtifetojpc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrxtlnlp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gtkyouvtyh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtiyxnoowc.html

[U84] JS：CommonJS 写法
来源：http://dali.wangdashe.top/Article/details/gtoqfaofgu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xylfe.cn/Article/details/gtbfijuueu.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtxwqlsfnr.html

a?.b?.c
来源：http://dali.sweek.top/Article/details/gtrhonljzt.html

[U86] JS：空值合并
来源：http://dali.chenzaomai.com/Article/details/gtdrroafbq.html

a ?? b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfceyabxp.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtfdzuqahd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cdnleiting.top/Article/details/gtgjolkmub.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gtbqbgoods.html

{ ...a, ...b }
来源：http://dali.hnqzz.top/Article/details/gtvakmvcko.html

[U89] JS：数组去重
来源：http://dali.zhengqikj.top/Article/details/gtqrtmrsce.html

[...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtumskxera.html

[U90] JS：数字数组排序
来源：http://dali.gaohongyu789.top/Article/details/gtsauxppjc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gttleylhwg.html

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gtxzmmvoyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gtnnexcogr.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gttedgkyrz.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtipvmowkb.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gtmienzlnr.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtjqntzwsq.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtsennwpvn.html

const double = x => x * 2;
来源：http://dali.fzhhl.top/Article/details/gtjlsrzame.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gttywsglnd.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gtsijuqgpq.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gtpwqxhlmf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtaqamtxjv.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gtwojiuncc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtzqrjhowp.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gteyqiwjoh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gtgasqamll.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtudqxpnnd.html

el.addEventListener("click", e => {})
来源：http://dali.chenlongwang.top/Article/details/gtjpsycuuy.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gtbmvlrtqn.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gtatnhnzkp.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtwtpnckdq.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gtloqfcfrc.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteukbvpcd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gtcjvgvqwr.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gtvgvhjika.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtkiitxonv.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gthtsdjzgy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtjlwgtitt.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gtbmaimtkp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gttkjkmgaf.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtgndczsvy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtczlaopuo.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtsmlbzptv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokvkntrn.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtqpsrvuvu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sysykeji.top/Article/details/gtrruvgizy.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtntkkhwfp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtmkzcyfec.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtksnoysri.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gtqqimzwiu.html

[U111] JS：对象转 Map
来源：http://dali.hywenlv.cn/Article/details/gtuobfpmdj.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gttzqazdow.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtqkubcdxu.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaviomfmh.html

[U113] JS：正则替换全部
来源：http://dali.jianghu66.top/Article/details/gtixfaipot.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtrtuvcxqd.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gtrjpmizus.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtaeksodis.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtcicoxtvi.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtexiclnhu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigfzy.top/Article/details/gtkxdzbrcq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gttfgttwjw.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtbhqplsub.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtkafclcva.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gtyubwlivh.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gtgbbdefox.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gthkbppbqn.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtfxcjdcmn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhoulong.xyz/Article/details/gtqedqxkpj.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtupytpggt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtygtafois.html

统计汇总
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvqczgfm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtaegcoopy.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtmrchbkwk.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtudsuzmpv.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gtcepmxrup.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtpyuddmce.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtuknhllgr.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtshteseuk.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gtclnzcrlq.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtmhzocuky.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gtiwqobepf.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtihemjxrf.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gtjhrjdxth.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gttyhnzwya.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtvmwrbgtn.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gtvujtwfmv.html

Swift .......... 15
来源：http://dali.yueranfly.top/Article/details/gtuxaroldr.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gtyqkktitz.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtxxtpmvcg.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtgassfgnv.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtgcwpgtbl.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtwvxvfcay.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gtrccbihlb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtlrfxenzg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtnebdnzwd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtcezdnpqr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtooblmeyx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtuyyzszoi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtxhvzhqcw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtpjyetqas.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtoksoqrhi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtlmgekfyh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtbuxhrefs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtcbhfwouf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtwzqlpjoo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtrjpgifsw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtfhutlsvh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gtvdjkoamu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtrybugbvw.html

Q SQL 专题                              90
来源：http://dali.yangfankeji.com/Article/details/gtzwikbqbo.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gtxbvedjrt.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtcgohdcrq.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gtpqloyqym.html

U 高频实用片段                         120
来源：http://dali.cucudq.cn/Article/details/gtscvdanmt.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtesosvtct.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gtydgolziw.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtwjdmzhbb.html

使用提醒
来源：http://dali.c1oappe.top/Article/details/gtcrhebdqe.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtuvnaqebo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtxihriuxm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gtndrlffdf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gtuzlcaref.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenjidiqi.icu/Article/details/gteytjxtba.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gthybfnybv.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gtvgqmowbm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtipaebrkm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gtuxlnsimn.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gtlomxzudb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsuqvbqlw.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gtitadxdgy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtsvikqvmn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtqwdxdilk.html

SQL · Bash · C · C++
来源：http://dali.aizwys.cn/Article/details/gtgczijxlg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gtnmhtnjty.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gtdaywlihl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuetiantiany.cn/Article/details/gtubrjhhzd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daria6918.cn/Article/details/gtygozudod.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gtcnzbckbm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gtjqcdzpzc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cdnleiting.top/Article/details/gturdyqvxo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zycfv.cn/Article/details/gtxtmbboff.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gtadxkgvck.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gotoacloud.top/Article/details/gttvxjdcsu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtodfoonpe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gtacnoexrx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gtzakiehxo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gtdslzzhxs.html

【文件统计】
来源：http://dali.cashguo.top/Article/details/gtdfbhfbpt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gtojzxhkhn.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtdiskpcmy.html

目  录
来源：http://dali.jiagoushi.top/Article/details/gtdaepxmoe.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtaqtxkkrn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtfwdkctij.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttimpcgpb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtvmaelvxj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtcngilcuz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gtyarmeitm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtectwvgke.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtjcmsqlta.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtuqmgigss.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxispeccq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgjlvpwj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtnqiiwwiw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtbhuhipio.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtfyhnngph.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gttxohcyka.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gtfrxfllhq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtaudqhqpm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gtikorlolh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gtebvasmwp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.snrcjt.cn/Article/details/gtqbklxisv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtumqdddcp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtygetcznu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnvqupnvk.html

A. 基础语法与类型
来源：http://dali.hywenlv.cn/Article/details/gtlpvvqphu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaovfylwl.html

[A01] Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtxcnifvyq.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtkmfiyshb.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gtcymupith.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtnxrvkujg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dianchejie.cn/Article/details/gtxodskhuo.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtkkphxdvd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtbufhqpuh.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gtipzoetnw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtzpzbpinc.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtaronpbis.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tian-w.cn/Article/details/gtkmlwmbzt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttscxminl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkpkostn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxinkj.top/Article/details/gtuqxkfvrs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtbjogzhlt.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gtclylukah.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gthhaypooy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtkepuwxzc.html

[A03] 常量定义
来源：http://dali.daria6918.cn/Article/details/gttfyieamp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shangyingyoupin.top/Article/details/gtjockonto.html

PHP:  const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtzebfmlgx.html

JS:   const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtvjzyengf.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gthgjsulgz.html

Java: static final double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtvnavxyuw.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtbxwadogp.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtuammstcm.html

C#:   const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtifjxqnmu.html

[A04] 判断变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtizquocfx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoctlyori.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gtyjwljtfe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gtpgyonthl.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtrieqpowz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.haohaochexian.top/Article/details/gtqltlwlue.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtgwcynupz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gtwqiumoil.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gteowwnupd.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gtcwrbyuys.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gtyfzuuuls.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtzllbpjrt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtaptinaim.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtksoyukdi.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtlkqhbokk.html

Go:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtxwlwdroj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtnphegbnx.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtvxmfcvbr.html

[A06] 字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtyblkrfoo.html

Py:   int("42"); float("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtjbnjomxk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gtjbcoegrz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtswsauhiy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtowkponwc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yongpay.top/Article/details/gtgracotpa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.redwolf501.top/Article/details/gtzeszcrmj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gtnuuywxqf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtrzndguuq.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtubmmsbtu.html

Py:   str(42)
来源：http://dali.hnqzz.top/Article/details/gtqcejfrtv.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gtvkpyxhhk.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcduwwec.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gtmhvkmeue.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gtneywthxv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gtpogfsaeo.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gtowpjexid.html

C#:   42.ToString()
来源：http://dali.yuxming.cn/Article/details/gtbucwvjlb.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gtciqoimsm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtdvnwwdco.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gtxgjcixrj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtfiyzlwat.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zycfv.cn/Article/details/gthmcyfcod.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtkxsuxldt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtgsxjlpxf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gtbhqgoviw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gthzahnbza.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtmgoyunub.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkikdojhf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiaznrai.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtesyhoyyz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtxwiocrhc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycwgvcvi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuanzx.com/Article/details/gtmzwdwzpp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sweek.top/Article/details/gtkcxldxkj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtwklclsbl.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtqngzlbkk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gaohongyu789.top/Article/details/gtuhqlcjio.html

PHP:  random_int(1, 100);
来源：http://dali.hammf.cn/Article/details/gtsvkhyero.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtpskqmqye.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gttcfjojjk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtrxwphzzj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenlongwang.top/Article/details/gtjaslynpt.html

Ruby: rand(1..100)
来源：http://dali.jqgufenzy.top/Article/details/gtunstfqvf.html


<!-- 参考信息 -->