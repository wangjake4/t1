代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2qavxagrw.html

throw new RuntimeException("失败", 500);
来源：http://dali.xziqi.cn/Article/details/gt2kqheggyq.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awpadcbq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gt2tmfmuqjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2wytxgkir.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gt2elkszhub.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2aithgcgl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gt2sgybmdlt.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gt2rcuaimur.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gt2cnhqyccz.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gt2odxroyyz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gt2xaslnsef.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2qfnlyuus.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gt2uvxdwpoi.html

[U78] PHP：单元测试
来源：http://dali.c1oappe.top/Article/details/gt2ffewcqll.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahggbdzx.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gt2edupogpi.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gt2simdpipb.html

[U80] PHP：代码规范修复
来源：http://dali.xziqi.cn/Article/details/gt2mtctajst.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gt2wfaxapoo.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivvmbess.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gt2sxbmtbki.html

[U82] JS：package.json 脚本
来源：http://dali.xuanzx.com/Article/details/gt2ssefsqcb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aibaodan.cn/Article/details/gt2velgrpkl.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258.top/Article/details/gt2rysycfvd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gt2yziwekcz.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gt2lcemgadr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shangyingyoupin.top/Article/details/gt2smnpicje.html

[U85] JS：可选链
来源：http://dali.yueranfly.top/Article/details/gt2rvjgyfug.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkhcihwr.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gt2adkbuowr.html

a ?? b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djpeowsb.html

[U87] JS：解构默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aujkbdcj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gt2wfxkhfdn.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gt2mvxtgdik.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gt2yoxnrbgq.html

[U89] JS：数组去重
来源：http://dali.cashguo.top/Article/details/gt2wxxqdydn.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2dqrfmkog.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gt2nqffimaz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2yctdwpme.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gt2qwxetrgu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gt2sfbbkghr.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2cmlcxvqj.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2mzjnvkgp.html

[U93] JS：模板字符串
来源：http://dali.zdqjudy.top/Article/details/gt2uoxfswzt.html

`共 ${n} 条`
来源：http://dali.iojbl.cn/Article/details/gt2alozwaoq.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gt2togpjlmr.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gt2xthwtzaa.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gt2vdohyqbf.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gt2mvbvvtrx.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gt2zxphxvyu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qdygxopv.html

[U97] JS：并发请求
来源：http://dali.daxiang520.top/Article/details/gt2odnhjgwm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2hwzxnylw.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gt2iburdsim.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2jzopezxz.html

[U99] JS：事件监听
来源：http://dali.yuanzhike.top/Article/details/gt2fhdrevha.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gt2ypsesyqu.html

[U100] JS：DOM 查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruprdjkf.html

document.querySelector(".item")
来源：http://dali.hnxiangtu.top/Article/details/gt2bgtsczkh.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gt2aqmvkgyf.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gt2niecpzep.html

[U102] JS：本地存储
来源：http://dali.jinqigfzy.top/Article/details/gt2pcmlwfmp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gt2bnqyhxee.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gt2cdonoigf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gt2iamdalzb.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gt2bngvihoy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2qlfkupcy.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gt2htsvhwmp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gt2kqbnaitd.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2juhosakj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gt2bagcuzkm.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2prhazidk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2imhdyode.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gt2ckgosbge.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gt2hfddldta.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2edlebrmw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2yvfpdheq.html

[U110] JS：数组分块
来源：http://dali.jinqigufen.top/Article/details/gt2iyfjlhoy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhoulong.xyz/Article/details/gt2rvizzfty.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gt2txccbsoo.html

new Map(Object.entries(obj))
来源：http://dali.guannengcc.top/Article/details/gt2vasjnlim.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gt2picuaazz.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2tyxzppin.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gt2zntpwhis.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2ksykqlni.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gt2siwxbqjb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gt2mrirwjkd.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2ojwjalwl.html

crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2csjykdme.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gt2sjxcujkr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ngkvivhq.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gt2jdrqxvkx.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gt2urozushs.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gt2uotpzotb.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gt2oyqqduks.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wstptibg.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gt2thmrfhnc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.andypj.xyz/Article/details/gt2uwwlszzv.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gt2zqzxpmyl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fosdmzsn.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gt2frrydnuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbitcrtk.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gt2dokiighg.html

Python ......... 252
来源：http://dali.fengsongda.top/Article/details/gt2takcyjrb.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gt2udjnsbsz.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2mtvoepgw.html

TypeScript ..... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwgnugpr.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gt2qbkwsjld.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2munvpype.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2ybxwqpir.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yomgotlt.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gt2znmixmit.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gt2bxtzhsop.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gt2dngkutoo.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gt2xleeaaus.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gt2umkflwhk.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afqnajln.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnwlafin.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gt2gvjulicg.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gt2krycifzl.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuogtzmv.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2zqcpnvbn.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkdmnhsj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gt2ppebqqgr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gt2siulshuj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2ntacmbxh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gt2wwsclvxs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urasiirt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2gnezfzkq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2amigkfrm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnhgrcny.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2hzpyzchg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gt2vpmodvlr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2ghxxcxqz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2nhpuwsbc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2xipqthdq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gt2sjrpzdjl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gt2piexxbyq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2sqxgkpiv.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gt2ysslmlce.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gt2vgodqpyf.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhmulfzz.html

T 其他语言补充                          60
来源：http://dali.guowangkeji.top/Article/details/gt2tcfplwei.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gt2prcbbkzh.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2egepbaxj.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gt2nyqvuanc.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2dscshqii.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gt2qdftrgpt.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2tmbenvzw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fengsongda.top/Article/details/gt2tprsoxhu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shuidangran.top/Article/details/gt2lvqzorsi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gt2ptyphvfx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugsliwql.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gt2xexkuvhh.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gt2zgewtisy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vacwcdql.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gt2tdumntsy.html

Common Programming Examples Cheat Book
来源：http://dali.aibaodan.cn/Article/details/gt2ukqlfyde.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2krrtrvyx.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gt2qywqimnj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gt2qpvgbpsv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jyoumei.cn/Article/details/gt2tnswiqgv.html

SQL · Bash · C · C++
来源：http://dali.cdnleiting.top/Article/details/gt2oybmvrqj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jlsjyb.cn/Article/details/gt2jzozinpf.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gt2mslvmqkq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhdmduqk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tanke756.top/Article/details/gt2rhnrtlhg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nwbrower.top/Article/details/gt2sdbwtoru.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nujixymu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cqqwz.cn/Article/details/gt2eujexgne.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gt2rtcdtzvq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hysaishi.cn/Article/details/gt2cimbbrcv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hysaishi.cn/Article/details/gt2elrehwma.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2kfcchgbk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gt2kmiwnyum.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cashguo.top/Article/details/gt2zuglqfaz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxinkj.top/Article/details/gt2bfeaehom.html

【文件统计】
来源：http://dali.bjfxy.top/Article/details/gt2qosftxhq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gt2lkdqxdkp.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aewapstr.html

目  录
来源：http://dali.ybcxt.top/Article/details/gt2knzybcbj.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evhrxhuv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gt2pddxblby.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2qziwnupj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2xdaasjzg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2rbiepbuu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.birdmap.top/Article/details/gt2mwjwoolk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gt2exceocop.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2xbxagalv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gt2vqhrdiyq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2lazbzaxl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsptryke.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2kxnuwcjj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2kktlaclb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2eqgkwygd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gt2esuxzgbi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gt2wroqnidq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2xlmhddzz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jyoumei.cn/Article/details/gt2jyxtevzf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2qidmukwr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xylfe.cn/Article/details/gt2hfvxesry.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2yjpjoxcg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gt2spudejkf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fobxmpwr.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gt2emzdgcrf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2yyzkigjr.html

[A01] Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2kadacdpz.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gt2ucpajyse.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gt2abviglxf.html

JS:   console.log("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2bilmtvan.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gt2tnlmjifx.html

Java: System.out.println("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2dxbpcxcc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gt2icpitlmq.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gt2etprldzz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofscjaem.html

[A02] 变量声明与赋值
来源：http://dali.svipenyu.cn/Article/details/gt2jytlrhsa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ivvv.top/Article/details/gt2pjvmdrjr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gt2awtcsxvx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2bjqcwzcm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2auqfgjsl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2vnojhzjd.html

Go:   name := "Alex"; age := 20
来源：http://dali.dashuyun.cn/Article/details/gt2xhofhhqt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mugsvkac.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykjtbltx.html

[A03] 常量定义
来源：http://dali.316326.xyz/Article/details/gt2cxkivhmz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xylfe.cn/Article/details/gt2pqlbmhul.html

PHP:  const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2kqcgwsxl.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2qjtktqcj.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2xildwjod.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2yqgnrzoh.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gt2oaykvbrq.html

Ruby: PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gt2yjrfwhfy.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uymgdwkl.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvqydzkl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.andypj.xyz/Article/details/gt2qcokqkfq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gt2tijsrofy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2ukfajoxc.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkmsfdir.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gt2nxwprkbl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fengsongda.top/Article/details/gt2urgfuvdi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gt2lihgfofb.html

C#:   x.GetType().Name; x is int
来源：http://dali.daxiang520.top/Article/details/gt2sfyztaml.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gt2clfbhtaf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gt2mtftzmsb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2vycemmoi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2eidajhne.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2ylzuuzim.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2lekgtfer.html

Go:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2zctdyfoo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2nxpjzryq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxxomjxp.html

[A06] 字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gt2kcfkrhvu.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gt2jwhhhril.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hammf.cn/Article/details/gt2hkewdzwb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osijqvne.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.birdmap.top/Article/details/gt2vfxgjerx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gt2aygonczc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hammf.cn/Article/details/gt2szmcccmz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gt2wcroepnf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2adseiodl.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gt2gxjofstd.html

Py:   str(42)
来源：http://dali.xinyue.icu/Article/details/gt2matbbrdt.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohkxrldd.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gt2xapozwyx.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gt2hvcvyhzh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gt2zhloherh.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gt2yvnmnrsn.html

Ruby: 42.to_s
来源：http://dali.birdmap.top/Article/details/gt2crwzlpxw.html

C#:   42.ToString()
来源：http://dali.pycfn.com/Article/details/gt2cdtxvlhd.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gt2aguzgqnd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2metojdox.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gt2xhuchdzx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2fdcbepuv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zdqjudy.top/Article/details/gt2pbkyaugp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2hhavdfbn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2dlvlekuv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.meibo888.top/Article/details/gt2tvnsqhts.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2wdppawoc.html

[A09] 绝对值与最大最小值
来源：http://dali.jiagoushi.top/Article/details/gt2mwqtymaq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2brmzrkxz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2tbrgxyll.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2rhbrdlmu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2ekulsslq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2ypwyelao.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenzaomai.com/Article/details/gt2itiaknpt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbmsjrfx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2arvvjtzw.html

[A10] 生成随机数
来源：http://dali.yonumen.top/Article/details/gt2kadumfzs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jiagoushi.top/Article/details/gt2htkxbwgm.html

PHP:  random_int(1, 100);
来源：http://dali.shuidangran.top/Article/details/gt2ojhzpeyx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gt2rzbtwkkq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gt2dshwobxe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aizwys.cn/Article/details/gt2mmzvubnc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigfzy.top/Article/details/gt2imkqxbos.html

Ruby: rand(1..100)
来源：http://dali.nanxuanxn.top/Article/details/gt2kxgfpdwc.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gt2ydcdtmfk.html

[A11] 条件表达式（三元）
来源：http://dali.pycfn.com/Article/details/gt2ciprczir.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhpjeber.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2zzxbdqvt.html


<!-- 参考信息 -->