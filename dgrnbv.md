代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gtdqcfkmnd.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtzrkynuze.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdvgtauz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.316326.xyz/Article/details/gtcjdlvtit.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtzcnkhdxq.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtiyqjntsf.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gtkyjuujdy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sxryk.cn/Article/details/gtfvjmcswl.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtiggrvlha.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtbanpoiyf.html

[U78] PHP：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gteguluxyp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gtkqfdpllo.html

[U79] PHP：静态分析
来源：http://dali.zhixingplan.top/Article/details/gtaduowycs.html

composer require --dev phpstan/phpstan
来源：http://dali.xylfe.cn/Article/details/gtgaiodjif.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigufen.top/Article/details/gttvpinfni.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gtiuwblymi.html

[U81] JS：初始化项目
来源：http://dali.yvedp.cn/Article/details/gtcaxvopat.html

npm init -y;  npm i express
来源：http://dali.meibo888.top/Article/details/gtvrhqimmg.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtshyywjnn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gtcduzaufl.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gtjiybarln.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtmokqzuih.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gtkxysfxeo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gtwhncheln.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gtvslljdkf.html

a?.b?.c
来源：http://dali.hnxiangtu.top/Article/details/gtzppqclrq.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtfpxagugh.html

a ?? b
来源：http://dali.cucudq.cn/Article/details/gtfdilunzx.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gtnrwduqup.html

const { a = 1, b = 2 } = obj;
来源：http://dali.c1oappe.top/Article/details/gtxjafvlli.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtilzonhtj.html

{ ...a, ...b }
来源：http://dali.zhiwuduotai.top/Article/details/gtwgryditg.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gttdctctgu.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtqvilwjsh.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtspgyttmx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtjrebxqrw.html

[U91] JS：对象键值遍历
来源：http://dali.mhx1999.top/Article/details/gtfonhfwnl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtcvuxynve.html

[U92] JS：深拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtqmhxfnhe.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gthqtseeyh.html

[U93] JS：模板字符串
来源：http://dali.zdqjudy.top/Article/details/gtpaxpkznu.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtzlgjzeer.html

[U94] JS：箭头函数
来源：http://dali.sweek.top/Article/details/gtfqozwcew.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtkevabbzd.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtkgrsrkev.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtjjlwrdgn.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtthcnffem.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gthomlbzvz.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gthqvjzqyt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtsgvzmxsf.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnqzz.top/Article/details/gtnsuapvua.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtapgfdhuv.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gtnjsdkaqr.html

el.addEventListener("click", e => {})
来源：http://dali.quarkkingdee.top/Article/details/gthkcawgks.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gtjdiayjxh.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gtlxabrnbr.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gttwchavxm.html

el.classList.toggle("active")
来源：http://dali.hongshengwenyu.top/Article/details/gtorykctoq.html

[U102] JS：本地存储
来源：http://dali.ydzc1.top/Article/details/gtyrucikmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnapnxkoe.html

[U103] JS：定时器
来源：http://dali.gotoacloud.top/Article/details/gtvfkogvkz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gtfsagsdbe.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gtbxeuamto.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtbhiuoxdy.html

[U105] JS：节流
来源：http://dali.shuidangran.top/Article/details/gtmqpbmkch.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gtmckhwzme.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gthjhpvwoi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guowangkeji.top/Article/details/gtprfgfepc.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtlfmynwnk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtceqlsxhj.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gtjvkkgjzp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258.top/Article/details/gtkxhnrcqu.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gtqaezjjff.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtobucdcrg.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gtjkiptrti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gtkigpoydo.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gtvuzbczhs.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gtmyuprwkv.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gtfajqqwch.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjazumflq.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtfngcbnpi.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtrlsukctj.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtwenzusum.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtfczhvfyj.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtmrjajwmz.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtzafstotp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtdzycacxv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gtnwivkwbu.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtaxljtkhz.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtmofiyjnw.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gtlesieifq.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gttjbefmtr.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gtncdjwujm.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtlthacwzl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtwjckszlq.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gtumapgdhx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwtwtzxww.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtxgyoucvp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtlxzosxei.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuzvyimk.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gtruurhjup.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gterhwvglo.html

JavaScript ..... 252
来源：http://dali.zhongyouzk.top/Article/details/gtmcgqxgmp.html

TypeScript ..... 212
来源：http://dali.ybcxt.top/Article/details/gtwzlmrsrm.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtihdkzhyi.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtqhejjtez.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtglvcjypx.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtbmkigfjx.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkdvzivk.html

C++ ............ 30
来源：http://dali.meibo888.top/Article/details/gtebqcdnic.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtujhioesg.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gthrsfeuck.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gtnsmlrayx.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gtvcjmupxp.html

Lua ............ 10
来源：http://dali.shangyingyoupin.top/Article/details/gtfoduufao.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtikvvmciv.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtdftsaiom.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvltsesux.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gtoaznefnp.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gtqecwjlwi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtoivghxtg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtcxohejdd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtztzpqbpp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gthvhbzzpt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtlhkitlgm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtpbynutdj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gttoxjzuvo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtuygvowea.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtewhrivqs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfeqmqyf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtdhwvputd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gthhrxucad.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuelvxvdx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtrnojlaiz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtfyafppnt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtgiuienyt.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gtbnsfihuy.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gtpyucxhcg.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gttylxgjtl.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gtwmthlhnv.html

U 高频实用片段                         120
来源：http://dali.shuidangran.top/Article/details/gtfklkmodq.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gthcfsznnp.html

合计                                  2106 条
来源：http://dali.yonumen.top/Article/details/gtdpieckkc.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gthkralbss.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtvvoayrtk.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcopsred.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gtehjwedsb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gteemnscgx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gtadwrpbpb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnxiangtu.top/Article/details/gtdsczsdww.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gtsgzlcwol.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gtzfrgojjl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtufubkqjo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gtnxemtdfv.html

Common Programming Examples Cheat Book
来源：http://dali.yonumen.top/Article/details/gtzxlhuysb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcmbdfxhb.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gtssmhojpo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.dianchejie.cn/Article/details/gtvhbrspnu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gtcrirywiq.html

SQL · Bash · C · C++
来源：http://dali.zycfv.cn/Article/details/gtnwwbcqqu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gtbdxesznd.html

【使用说明】
来源：http://dali.nanxinkj.top/Article/details/gtksjrexfy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gtuxcpcyhc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ehwqpu.com/Article/details/gtyiakuueh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangtech.top/Article/details/gtwidhudwo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gtfsuxxkyb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gtkqwgdxyr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gtgxqtranp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ppjwa.cn/Article/details/gtjwdrdkzq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhoulong.xyz/Article/details/gtibzvcsre.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hysaishi.cn/Article/details/gtkcxqdjcc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jyoumei.cn/Article/details/gtestezdpq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuanzhike.top/Article/details/gtipfcpqol.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gtokpnogtq.html

【文件统计】
来源：http://dali.sweek.top/Article/details/gtihwwvqxg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gtdrpwavoh.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtixhxfygm.html

目  录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihgonhvx.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtmujmzvpe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtxpqmftmp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtpkjnrmdn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtsllwuior.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtkmbxzkjq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.bjfxy.top/Article/details/gtasmejjiy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtcqkzymuf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtlsgwyehi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtioyqsoql.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtqjcudgvu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtbcfvyglo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtwjowmpkc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtzpwdixxh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtsxcreghz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gtbthecxcn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtvmrnfnwp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtlsqjqaza.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuanzx.com/Article/details/gtsulmnfqo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gtzomjsywk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gteklrxcqr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtszpjrcdr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtijfxvtnm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvmwicsdw.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gtkkcembno.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtojfznomw.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gtnclidwhm.html

Py:   print("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gtjswywddn.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gtgldnahcy.html

JS:   console.log("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtfescjpae.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhtcqbsh.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtcookcvns.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gttzfjncpm.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtihfxhgtv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtistpgudl.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gtreiayqsa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gogol.net.cn/Article/details/gtinmnzmnx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sweek.top/Article/details/gtzlrbdcnj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtkqoxkbwf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhixingplan.top/Article/details/gtmealpgqb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gthfmkmdvi.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenjidiqi.icu/Article/details/gtdkraecfq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gtxbhnkyug.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gteciwzvht.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtpsxhycui.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.feifeiyinyue.top/Article/details/gtxsfxdpha.html

PHP:  const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtcyzudmjl.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtlhejadcq.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttswrgero.html

Java: static final double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsntbrbsf.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gthcgwsnrk.html

Ruby: PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtbeiwqrtm.html

C#:   const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrapezfys.html

[A04] 判断变量类型
来源：http://dali.jyoumei.cn/Article/details/gtobffjutl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtyxrzficb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gtpbqkmwhm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtlcbxljot.html

TS:   typeof x; x instanceof Date
来源：http://dali.sweek.top/Article/details/gtyjkkzowe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigfzy.top/Article/details/gtsjezmmbu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258.top/Article/details/gtxtndfzxg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuvfizvy.html

C#:   x.GetType().Name; x is int
来源：http://dali.meibo888.top/Article/details/gtcohcihle.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gtiilhrrkc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtzkjhsbgj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtphlluyrd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gttvhffvcn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtbhukgdhm.html

Java: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtihryjrbj.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqvckgqn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtfhvkckha.html

C#:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtxecethdt.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtefbkesnm.html

Py:   int("42"); float("3.14")
来源：http://dali.smart0.xyz/Article/details/gtcbykeeyn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xylfe.cn/Article/details/gtnnswxhcp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gttjglnomn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gthpnlzlsm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtoyivzbcj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.kuanghao11.cn/Article/details/gtqeoetwxi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gtcnmxjvhz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtxkvwdbhr.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gtnbwttqjq.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtnorsoneg.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gtumocefjl.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexslygal.html

TS:   String(42)
来源：http://dali.kuanghao11.cn/Article/details/gtdxeqvnxd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gtwwhewzfv.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigufen.top/Article/details/gtqefnzrye.html

Ruby: 42.to_s
来源：http://dali.cheryme.top/Article/details/gtekbxjzkv.html

C#:   42.ToString()
来源：http://dali.ppjwa.cn/Article/details/gtnvflndvx.html

[A08] 取整与四舍五入
来源：http://dali.hongshengwenyu.top/Article/details/gteiuqezib.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtbnamokhj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shangyingyoupin.top/Article/details/gtopihfspx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtmwdhansi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gtucgvjfgk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtcillfnzi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtrgmxlgwr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gthrpahiup.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtafqwbbhl.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtioprmgvk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtchstoyzt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzkymrgj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtqcrxvzfs.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbbndfco.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtfuyirvon.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gtotnwhdxb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gthukyypkg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtapjhepzg.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gtwuqxmecg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jiagoushi.top/Article/details/gtatmhostu.html

PHP:  random_int(1, 100);
来源：http://dali.sxryk.cn/Article/details/gttbegztdk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigufen.top/Article/details/gtlyepetbu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtfhdiwdev.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nwbrower.top/Article/details/gtpzopkwsd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hysaishi.cn/Article/details/gtwoowivya.html

Ruby: rand(1..100)
来源：http://dali.hammf.cn/Article/details/gtuksrbyot.html

C#:   new Random().Next(1, 101)
来源：http://dali.haohaochexian.top/Article/details/gtahihxbrb.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gtasokztlr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sufxvd.cn/Article/details/gtqokozpff.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtfpculqfg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gtdrhzrnav.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbqhfbnv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtbqsparot.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yuanzhike.top/Article/details/gtuelqhtpx.html


<!-- 参考信息 -->