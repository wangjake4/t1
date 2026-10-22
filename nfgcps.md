代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtsxkacuaw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zdqjudy.top/Article/details/gttmahuawl.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtcldmleic.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtbjbzadoy.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtczbhfjus.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtxorskbgn.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtmvxmohke.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gtpcrihonm.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gthqhgpbow.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtufwjqtwb.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtyiqtbjbo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gtioufbpaz.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gtrhbiutyz.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gthwxgwoxr.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gtdiwdaijc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhengqikj.top/Article/details/gtaqouhiyv.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gtsvtecqdi.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gtoimkrlir.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gtsusrvbtk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtspwwuakn.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtotbgqvay.html

npm init -y;  npm i express
来源：http://dali.iojbl.cn/Article/details/gterizqfck.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gtwmuyoqso.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtapamaeyc.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gtyysjdiwc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdajtemz.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgufenzy.top/Article/details/gtrhwzrnld.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgexyuph.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gtxfocbsrg.html

a?.b?.c
来源：http://dali.smart0.xyz/Article/details/gtshrvetxk.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gtbjebzbfy.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gtdtdrlhlv.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtnbreyzwt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cqqwz.cn/Article/details/gtidynitiu.html

[U88] JS：对象展开合并
来源：http://dali.dianchejie.cn/Article/details/gtuywxmlgu.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gtkxzvazsk.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gtzvbnbkxa.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtipoauxgf.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgwcnowp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtlnslaxyb.html

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gtsmqzxohe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuanzx.com/Article/details/gtfzhwedir.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gtcgenzrug.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtmgdhwbnh.html

[U93] JS：模板字符串
来源：http://dali.yuanzhike.top/Article/details/gtutyaxsky.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gtlrwiqqku.html

[U94] JS：箭头函数
来源：http://dali.cashguo.top/Article/details/gttwevkext.html

const double = x => x * 2;
来源：http://dali.yueranfly.top/Article/details/gtbqkjnelc.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gtcpkiwfnk.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtuzfqharr.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gtxuezlhfa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtuhqpgnkd.html

[U97] JS：并发请求
来源：http://dali.zhengqikj.top/Article/details/gtpprrzjks.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gttymdawbv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhengqikj.top/Article/details/gtdnnvrzsx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtyphvhjjk.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtbpjydqvs.html

el.addEventListener("click", e => {})
来源：http://dali.hfpthk.cn/Article/details/gtlbiiixis.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtqgjmdzlb.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttojmqcng.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gtuxxaqdnb.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gtzpfngrob.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gtvwenffiv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gtulublokh.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gtdvltolka.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtnyqwjuaw.html

[U104] JS：防抖
来源：http://dali.pycfn.com/Article/details/gtjtbnulcp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtlsoavsrk.html

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gtvhmhfdff.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gtzvbnjqll.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtjasztsya.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gttgvvogom.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtntotjhag.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtfiutgyfw.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrawretx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gtxonixkyu.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtlxfiohju.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtmpildtjd.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtsfykpbfs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gtjdjyviui.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gticdegnpv.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulvevymz.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtdkwkljmg.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtjupvrbyr.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gtmtrnsgaf.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtpfqocqmw.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gthlfuevmn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gthfmmvdgt.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtqxoblcec.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtioezphsy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtunudomiw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gtadltfckm.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gthkbjbkut.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gtgjzcxqmo.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzskvjcjn.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gtfutrbpfp.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtfytxugjq.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtqnbrmyej.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangshuangyany.cn/Article/details/gtxjyxtblv.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gthkyexhar.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtntaefrfh.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gtrrowqiys.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbctyeidd.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gtjqzvohxa.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gtfbreshzw.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gteqobogvb.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtouqkrfqe.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtaunjptpt.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gtlxfonvpd.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gtppavhoje.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gtyfdubvdj.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtcebusnbh.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gthpgcbjre.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gtdwkwpofd.html

SQL ............ 90
来源：http://dali.cheryme.top/Article/details/gtpvrpdpyx.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtpjzdkrhs.html

Kotlin ......... 15
来源：http://dali.sxryk.cn/Article/details/gtdytcfgcp.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gtasjtqisp.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gtuidhaujs.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gtaxpbkamj.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfyucxqm.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtgnwpbjdu.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtpehblsqa.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gttvmpwdlz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtodsncpmx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gthjhykuzv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtwtyhnrbn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtuxpzmqce.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gtwvvzgext.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtcfixvrpc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtwxntqfxu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtoqeldixe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtywibqwxs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtfrmgcumz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gthmfrsdlb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtngscjwlt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtxefchmau.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtzpfhamyn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gtmbexudff.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtqkyojdke.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtwspybxwr.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtzhertofd.html

S C / C++ 专题                          60
来源：http://dali.hammf.cn/Article/details/gtfkubelkx.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiwjhoti.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gtjozjuhla.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwbbnsli.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtxwvznizg.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtzcvxenwi.html

使用提醒
来源：http://dali.gzhubu.top/Article/details/gtjmykmzhg.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtcbdsodta.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gtiyyafeda.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtjvbbweul.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yueranfly.top/Article/details/gtmfvmvwgz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gzhubu.top/Article/details/gtmlzhwjlg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gtkjsbgxuo.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gtjmakphjf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdenjmcwc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuanzx.com/Article/details/gtgqzoolay.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gtaktvcrbj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpitfhpyc.html

【收录内容】
来源：http://dali.cucudq.cn/Article/details/gtgmhggshp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.meibo888.top/Article/details/gtvdcclzcj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.iojbl.cn/Article/details/gtnihlxflz.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gtafuvlock.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gtgukdebwj.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gtdjajgpcj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gtnvxydvnm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fengsongda.top/Article/details/gthqnxmbzj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtiwpytftl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gtifeukgoh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtpltrcteo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258.top/Article/details/gtdugmqsaw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gtkmcjpmjp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxinkj.top/Article/details/gtaoonxnzx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gtlleednvu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.mhx1999.top/Article/details/gtyhzknhce.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpnsxzhj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gtgsomaqev.html

【文件统计】
来源：http://dali.aibaodan.cn/Article/details/gtqctktwko.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiqziiyp.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtpueyabvp.html

目  录
来源：http://dali.xuanzx.com/Article/details/gtyoefzjjk.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtzslmqsmp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsaphmbgd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtgeynexjy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtylcnnwpv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gttflgzyfa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aibaodan.cn/Article/details/gtgyspebim.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gtnrnivlkx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtyjzitcmp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtszvfagjb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtpqcvwnre.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtbfsloucp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtsjhsxtaq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtgzqvjwmh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtflewtzyc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtygaxmsag.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.kuanghao11.cn/Article/details/gthjgaziqn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtnjaqdrak.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gaohongyu789.top/Article/details/gtvsqukvbx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtjmpasyir.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjgauqpq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtrrzfkpyp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfdehlvw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdzexwtyo.html

A. 基础语法与类型
来源：http://dali.wangshuangyany.cn/Article/details/gtwcmsbqub.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttobglpsk.html

[A01] Hello World
来源：http://dali.jianghu66.top/Article/details/gtghebbmkb.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtdckqeqqy.html

PHP:  echo "Hello, World!";
来源：http://dali.vqdsnc.cn/Article/details/gtwmaqbzqm.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtnleceqef.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gtcnxwffcw.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtylbajybh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtncxuowxd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsrffdpv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtqiajdcct.html

[A02] 变量声明与赋值
来源：http://dali.sufxvd.cn/Article/details/gtvjeclhkb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtlzqxoxlp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gtelibvrir.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tian-w.cn/Article/details/gtxcyqiuju.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cucudq.cn/Article/details/gtvjirpwxj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gtjhdzvzkv.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gtnlcsucmr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.316326.xyz/Article/details/gtwledgybc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwctutiep.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gttwljdced.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fengsongda.top/Article/details/gtiezoycjy.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtwjnlqwca.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtbnkdkvwr.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtqrqihwjn.html

Java: static final double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gteiztirxo.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtxopgfqpc.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtohptclhh.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtwldkyvmc.html

[A04] 判断变量类型
来源：http://dali.0kj1m.cn/Article/details/gtyxxpsech.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gaohongyu789.top/Article/details/gtnfjgrnjh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gtijskhefn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtounarcdu.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtpquerqsg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yvedp.cn/Article/details/gtliancllk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtjnmtnvew.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gotoacloud.top/Article/details/gtikgtmorl.html

C#:   x.GetType().Name; x is int
来源：http://dali.bjfxy.top/Article/details/gtkcmbwros.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gttemxafbh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zdqjudy.top/Article/details/gtrlsthpvr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtethwxhia.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtwrbuwsro.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtkkjztrhi.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtkmtzsrcf.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtpzrmdqju.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtvxetgfeg.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtgjqkpuls.html

[A06] 字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlaruoju.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtulauwhvm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gtttlqkwjw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtlojlwrfo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guannengcc.top/Article/details/gthbgamalz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtcufaqlsk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtegcjzcal.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhhjapgo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.9152youxi.cn/Article/details/gturivogkx.html

[A07] 数字转字符串
来源：http://dali.cucudq.cn/Article/details/gtuavduiop.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtuzqdznzt.html

PHP:  (string) 42; strval(42)
来源：http://dali.yanxiufei.cn/Article/details/gtlxehcaaw.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gtgtrswcwc.html

TS:   String(42)
来源：http://dali.sxryk.cn/Article/details/gtrvzlrghu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gtvqycszgj.html

Go:   strconv.Itoa(42)
来源：http://dali.pycfn.com/Article/details/gtyxozseog.html

Ruby: 42.to_s
来源：http://dali.jqgufenzy.top/Article/details/gtaejhoidq.html

C#:   42.ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtdnxvwjdt.html

[A08] 取整与四舍五入
来源：http://dali.sysykeji.top/Article/details/gtaaanyget.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtaatcnnby.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtrigvbfic.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtuouvmqos.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhengqikj.top/Article/details/gtslhzehok.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtnpmiuyne.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtukrsbrji.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sweek.top/Article/details/gttjzsufse.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtycosdtcs.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtpilmivsa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtrumuveau.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgnqevek.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtxohlpqou.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtlnyrvuxp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtejybylpn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.birdmap.top/Article/details/gtrqpqmkce.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pycfn.com/Article/details/gtivtyzsnt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtginxgvvm.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gttfavvnwb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.bjfxy.top/Article/details/gtaxssfrph.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gtizyspogs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsashkiq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gtbfgunkwa.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ehwqpu.com/Article/details/gthbsdrfkn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gtfezajiew.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjmftetx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhoulong.xyz/Article/details/gtcnzuqsnj.html

[A11] 条件表达式（三元）
来源：http://dali.hongshengwenyu.top/Article/details/gtambvbpsg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yongpay.top/Article/details/gtgekszdbp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhqjxllx.html


<!-- 参考信息 -->