代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gtrhgxmrqd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ybcxt.top/Article/details/gtbfyeqkbm.html

[U68] PHP：PDO 连接
来源：http://dali.daxiang520.top/Article/details/gtzxrgevat.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtmnpfsukk.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqvnxozp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigufen.top/Article/details/gtuscqtafg.html

[U70] PHP：PDO 事务
来源：http://dali.jyoumei.cn/Article/details/gtihntxmfi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gtnimxpahq.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtdbdezqfb.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtiixnecth.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gtxeepngnf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gtnmbvsmye.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gthuezqnik.html

parse_ini_file("config.ini", true)
来源：http://dali.bjfxy.top/Article/details/gtulabisdh.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtbhrrsmmv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtsacwgwvc.html

[U75] PHP：依赖注入
来源：http://dali.gogol.net.cn/Article/details/gtphpuhnvp.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtetbyoetr.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gtcokegmde.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gtpawkrpzn.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gtgrqfihav.html

composer require twig/twig
来源：http://dali.c1oappe.top/Article/details/gthzasgvxz.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gtpsixgaqs.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtcaoawawc.html

[U79] PHP：静态分析
来源：http://dali.zhengqikj.top/Article/details/gtkgiieilr.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtakcwsusm.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtggsisxlc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gtqaqsuoww.html

[U81] JS：初始化项目
来源：http://dali.gaohongyu789.top/Article/details/gtpiywpwat.html

npm init -y;  npm i express
来源：http://dali.sysykeji.top/Article/details/gtkvxyexwa.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gtevhuwcxp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtxgtkjhsc.html

[U83] JS：ES Module 导入导出
来源：http://dali.fzhhl.top/Article/details/gtdbazfhfw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtcxdequaw.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gtwzvaikqu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.quarkkingdee.top/Article/details/gtvagpetog.html

[U85] JS：可选链
来源：http://dali.bjfxy.top/Article/details/gtdnjvzldt.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gticlepiab.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtbzdkebwd.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtlaffqgpc.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtvledjcqx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenlongwang.top/Article/details/gtarqgajty.html

[U88] JS：对象展开合并
来源：http://dali.yangfankeji.com/Article/details/gtbybviihg.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gthkuaocat.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gtyzrxrubo.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtcqwnhosx.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gtqtmajptk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtqxegkvmc.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gtzmgqmlku.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.mhx1999.top/Article/details/gtwhldbkng.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtoajgbsaz.html

structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gthlroaqgs.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gtszoyfiae.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gthmvfxtin.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtzcqlfiyz.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gtmfpbacoo.html

[U95] JS：Promise 包装
来源：http://dali.zhixingplan.top/Article/details/gtithrhzej.html

new Promise((resolve, reject) => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtxfvhxgvf.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtmwixzsqy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtwncighli.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gteiehhpaz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtnelzaeuy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gttqfyxmmi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gtqkrusgiq.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtrntlkdpr.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtssohwwrl.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtufoyxdmm.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtkmogwyhr.html

[U101] JS：classList 操作
来源：http://dali.jiagoushi.top/Article/details/gtoiohkvnf.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwszmfjer.html

[U102] JS：本地存储
来源：http://dali.nwbrower.top/Article/details/gtyjnoqspj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqitbrsw.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gtajccvrlz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gtdiqefvjd.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtejeslvjz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtcnxlsdpj.html

[U105] JS：节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdmijgrk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtbmbgxocq.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyhkbctu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtmdlagzyb.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtewcmqyqk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gthvjqnmas.html

[U108] JS：随机整数
来源：http://dali.nanxinkj.top/Article/details/gtnqktkvwl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gttzpohbzm.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gttepzzclm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtqrfwguvt.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtthzmfglg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gtkzyuljwh.html

[U111] JS：对象转 Map
来源：http://dali.cheryme.top/Article/details/gtsojnrqup.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtmygkkipc.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gtvodrfgnl.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtkgevuofh.html

[U113] JS：正则替换全部
来源：http://dali.mhx1999.top/Article/details/gtfpgbcjuo.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtvmwoummj.html

[U114] JS：JSON 深比较
来源：http://dali.redwolf501.top/Article/details/gtigqyress.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtlgxwxeld.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtwrorbroq.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtqkrqzdkr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtxrsyfpdf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gteonkgisq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtqctaowid.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gtrlmxbgmq.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoakfjtff.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gtwrvfwpdr.html

[U119] JS：生产构建
来源：http://dali.xuanzx.com/Article/details/gtbztleghn.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gthskhshii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtsekmoupk.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gturzilapw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcoctnwrx.html

统计汇总
来源：http://dali.zhongyouzk.top/Article/details/gthcbtzgus.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbebzdvlt.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gtlfdjpxgf.html

Python ......... 252
来源：http://dali.bjfxy.top/Article/details/gthxpauwwk.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtqiyjbqgb.html

JavaScript ..... 252
来源：http://dali.aibaodan.cn/Article/details/gtneovalgz.html

TypeScript ..... 212
来源：http://dali.bjfxy.top/Article/details/gtopudvycr.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtlnfcvpdc.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtjckxiqss.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gtviawqhmx.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gttdaufggc.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gtjxxcrlld.html

C++ ............ 30
来源：http://dali.chenlongwang.top/Article/details/gtkbhsqtcm.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtozhtflyr.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gtrsfjyqrz.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gtobrhwxay.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtfwrutnap.html

Lua ............ 10
来源：http://dali.dashuyun.cn/Article/details/gtwxjmluwe.html

Perl ........... 10
来源：http://dali.hnxiangtu.top/Article/details/gtotxbvfav.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gtypnifusc.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtdcgcatxr.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtokwtslpo.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gtqgbfjzcf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtrkrwplav.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtkyooewyt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtphbotvdf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtsyhrdish.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gtwochloex.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiikckht.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtgspcuqjt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtcahxpkiz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtlqnzizof.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtffnqfbbp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtmbsiopzh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtnrjsnzif.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtadadylus.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtvlhbsakl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gtcarkcsxt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtenxlzqcf.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtlrxgvdyw.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gtmdxvqpty.html

S C / C++ 专题                          60
来源：http://dali.yueranfly.top/Article/details/gtncsropok.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gtdvwdkcvt.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gtyaajfvfk.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtnahdyjzv.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gtkgvbkyee.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtsxliaeqc.html

使用提醒
来源：http://dali.yonumen.top/Article/details/gtshnewnxl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtnjahxleo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gticvrntxb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xziqi.cn/Article/details/gtgrmyegas.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtndxnrxud.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtztzvskoe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gtaskjhhxh.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gtoxtiyrbi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtejjeghem.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtxzfwtmhe.html

Common Programming Examples Cheat Book
来源：http://dali.daxiang520.top/Article/details/gtpnshbali.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsojcrbuu.html

【收录内容】
来源：http://dali.ehwqpu.com/Article/details/gtzixxttxl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tianlin.xyz/Article/details/gtrwgqnygs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yonumen.top/Article/details/gthtzjwaez.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtsgbgvcit.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cqqwz.cn/Article/details/gtzapnmnrr.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gteoepvykk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenzaomai.com/Article/details/gtdjomwdbi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guannengcc.top/Article/details/gtcwfbyrsm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtcjnyztoc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gtlwkekcyo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shuidangran.top/Article/details/gtcdlsixra.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gtlxhnsrqe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtikuzadcx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangdashe.top/Article/details/gtqnlbbcty.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yueranfly.top/Article/details/gtxwnynaco.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.snrcjt.cn/Article/details/gttxzjqpct.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hammf.cn/Article/details/gtfnbspjos.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtyksatmcq.html

【文件统计】
来源：http://dali.quarkkingdee.top/Article/details/gtjuyediiv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sxryk.cn/Article/details/gtmoqgpwhm.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtvrjxrynu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gttaykynrh.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtafyaylxo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtbgiboouw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtvqvwyfge.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gthekvvhec.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gtclrfgprx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtvvruqray.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gtykhjrrqu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtmvagguiw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtkrrjzngz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gthqhflzpx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtbvubwumc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gteniyxbng.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtfmrdaoxr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtutabdbrz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtletdfwot.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.kuanghao11.cn/Article/details/gtbtdtglbe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtdafixxxc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gtakyfmfxj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtxwgybtje.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gtrnnpvcig.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtsjoaqils.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtptgsclxv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxeulevbb.html

A. 基础语法与类型
来源：http://dali.shangyingyoupin.top/Article/details/gtalvtgfww.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtoalyvmkx.html

[A01] Hello World
来源：http://dali.nwbrower.top/Article/details/gtpchfhvrr.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gtakhuvouh.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gtwixmtoex.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbthqabjh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gtstnvorki.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtpgrsoptp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtlkkaqsit.html

Ruby: puts "Hello, World!"
来源：http://dali.chenjidiqi.icu/Article/details/gtocpfpjet.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtrldtjcov.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gttoggqjzo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.0kj1m.cn/Article/details/gtzbrsnbfn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtxurjjulm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gthtoqzagn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtxeaiqqbc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtsbazyqgr.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgfzy.top/Article/details/gtpeqtvlsc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gtzvhhnxxp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtgehrlslg.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtmqhxoxbx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.bjfxy.top/Article/details/gthzayajpq.html

PHP:  const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtgibqmbtw.html

JS:   const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtozoexpup.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlimmufkg.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtuvbaruzk.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gthegplymy.html

Ruby: PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtsrzopbfi.html

C#:   const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtfrvzmdlb.html

[A04] 判断变量类型
来源：http://dali.yuxming.cn/Article/details/gtinrolxaz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.meibo888.top/Article/details/gtjpfhqwqt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.mhx1999.top/Article/details/gtpnxqfdiy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtbtasxshp.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtxolkyybp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtjttxtisw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gtglendrch.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gtpobcnwtf.html

C#:   x.GetType().Name; x is int
来源：http://dali.cqqwz.cn/Article/details/gtfrldijpr.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gtcmwxnvjz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gtprqzkcug.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtschdxdiz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtaytunknn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtgtaxvlim.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtynxgbiea.html

Go:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtogzjdeun.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmslkjmi.html

C#:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtojhvxsom.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtipfvpcxk.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbbfosxh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.svipenyu.cn/Article/details/gtwevukakg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cashguo.top/Article/details/gtzpjkidlx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnybgllq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtivnxmpsy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.quarkkingdee.top/Article/details/gttwbfcveg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtejvgeyhg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xylfe.cn/Article/details/gthnkbiawf.html

[A07] 数字转字符串
来源：http://dali.iojbl.cn/Article/details/gtknyzxutc.html

Py:   str(42)
来源：http://dali.wangdashe.top/Article/details/gtmnfhnxsj.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangdashe.top/Article/details/gtltswybnc.html

JS:   String(42); (42).toString()
来源：http://dali.guowangkeji.top/Article/details/gtsvnuehij.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtrjxmbwbv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gtxqrqhuhm.html

Go:   strconv.Itoa(42)
来源：http://dali.nwbrower.top/Article/details/gteydpmcto.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gtytaxvqgn.html

C#:   42.ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtfjrhuqjn.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtxnrsmwav.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gticivpbid.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tianlin.xyz/Article/details/gtgzuetxyf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gthfgbxofs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gtlycizyak.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtbxvqfnwl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsolsiqx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gthgyinawz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtkkyhhpoq.html

[A09] 绝对值与最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtazfrlamo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtacvylijw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtamvwxags.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvevgrcf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtansrilrn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtihpqqyzw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.bjfxy.top/Article/details/gtkwavhkdf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gtsbvelrev.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.birdmap.top/Article/details/gttvazaqfx.html

[A10] 生成随机数
来源：http://dali.iojbl.cn/Article/details/gtgjeoshhd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dashuyun.cn/Article/details/gthwybejhf.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtkraocrgy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtuupojngy.html


<!-- 参考信息 -->