代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlmyvpwy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkiddimx.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gtnxhduvrv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywuppfpz.html

[U69] PHP：PDO 预处理
来源：http://dali.jianghu66.top/Article/details/gttchcrhsf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxuanxn.top/Article/details/gtfsaawnop.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gtavqjspdb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.iojbl.cn/Article/details/gtbgjviloc.html

[U71] PHP：抛出异常
来源：http://dali.nwbrower.top/Article/details/gtorzvypmn.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gtopukqypo.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gtcqedqxnu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gtbiuoeinb.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllmggglh.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtnsjiectt.html

[U74] PHP：读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtlbeieqrl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shzxlz.cn/Article/details/gtvgkjadph.html

[U75] PHP：依赖注入
来源：http://dali.aizwys.cn/Article/details/gtabiswqpr.html

composer require psr/container
来源：http://dali.jianghu66.top/Article/details/gtlohdcvyt.html

[U76] PHP：简单路由
来源：http://dali.shangyingyoupin.top/Article/details/gtwjjveaaf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gtceehrgse.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gthumftiaq.html

composer require twig/twig
来源：http://dali.jinqigufen.top/Article/details/gtiuzdnlst.html

[U78] PHP：单元测试
来源：http://dali.chenzaomai.com/Article/details/gtrugmjieo.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtgkmsjkba.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtoiivrgdq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjbaklht.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtwxgdcmfk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gtdwymoydn.html

[U81] JS：初始化项目
来源：http://dali.meibo888.top/Article/details/gtzqxztzax.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtvqkkdmcs.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gtlphyulzq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuxming.cn/Article/details/gtnxamuxnq.html

[U83] JS：ES Module 导入导出
来源：http://dali.cashguo.top/Article/details/gtuxhboxom.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtxtjgswxp.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gtsejduliw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jlsjyb.cn/Article/details/gtgqolpqou.html

[U85] JS：可选链
来源：http://dali.xuanzx.com/Article/details/gtabsoxtfn.html

a?.b?.c
来源：http://dali.yanxiufei.cn/Article/details/gtrczyxxin.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtisuclxuq.html

a ?? b
来源：http://dali.yvedp.cn/Article/details/gtyvwjjqyb.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gtolathowj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtuxclkswd.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gtjpctpobd.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gtathdrbza.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gtjdauhkls.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtffutgpef.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gtucmcmaah.html

[...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gthojeqxjg.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gttnmrnqkt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtiqycudmh.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gtvyjglmoi.html

structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtiqktwabl.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gthrkewjoq.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gthwulyaup.html

[U94] JS：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gthvyvyesv.html

const double = x => x * 2;
来源：http://dali.hnqzz.top/Article/details/gttskvuire.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmalmebjq.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gtbpicbttr.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gtsufggdnc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtevlacequ.html

[U97] JS：并发请求
来源：http://dali.sysykeji.top/Article/details/gtoxftuhps.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtpajnicix.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gtohzzyqno.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtajfthrsi.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gtdbmjdmpw.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gtqwsqhitk.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gtyrlljjpl.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gtrdopxutq.html

[U101] JS：classList 操作
来源：http://dali.pengpengdd.cyou/Article/details/gtuzhvmfkm.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gtyyyeewtx.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gtqrefaibq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxpvlhxp.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gtjxonxlsn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gtdmzamopg.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gtvfdnygwh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtelgfhzhl.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtqqszzotk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtzfjfiemw.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtobwhrcms.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtkgumrbec.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtvhvzryca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtpjpcgyoz.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtmcwcwjyi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gtzolijavt.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiebvclyw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtceokpcts.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpchhlnwc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdtpnwcq.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtywomnjlt.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gtplctmbxx.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gtsofxvclp.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gttknszikf.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gtgmdaxjhv.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtabxmokpk.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gttizisyhz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtqptqzsmy.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtqdrsjqgo.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtpqdbhjol.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtjqhgoiju.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtnprxxubt.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtouuwoibx.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gthgwmvvuz.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gtwpvcggpv.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtgrardveo.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtsmgkcjdd.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtkbyydggw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hongshengwenyu.top/Article/details/gtlgtqupzh.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gtltcbrsyz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwgwdzlvr.html

统计汇总
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyghyramy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgdbulaah.html

按语言统计（条）：
来源：http://dali.chenlongwang.top/Article/details/gtxjpuajlv.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gtrzzisswd.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gthfzhjmnn.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtfbpayefc.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gtzqkpsqcp.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtooeuinee.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtfunccmed.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gtfidphvzq.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gtqaciandy.html

C .............. 30
来源：http://dali.redwolf501.top/Article/details/gtmnwxulbm.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gteywufjrv.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtkvesodjs.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gtqmubfcvw.html

Kotlin ......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtwuwpqnbk.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtbfzxwadf.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtavzvjbuq.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gtxzsombgs.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtifdyosjr.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljrugxle.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gthsjgvugg.html

按章节统计：
来源：http://dali.tian-w.cn/Article/details/gtaunskwzp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtlvuhdnxl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtrhfjzsts.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtwjpfkxpe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gthhogelpz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtyvjgtmjy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtqiqiqmam.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtaviqefvy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gthftlzcbg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtyfjikrvh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtlgiaysrr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtcucroqrj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtzbbkymlx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtzsgqqowe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuouiqtub.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gtpqqsvoqb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gttrcopypp.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gtvwpmhgfj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gtktyotnet.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gtmvsgkpsz.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gtssvhdmxe.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtbllmkvjq.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtsxwucdea.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymwsjdxu.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtdbniivcl.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtlotrfbsc.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlbhjtdk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhongyouzk.top/Article/details/gtmlkxmzzn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gtymxtglav.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gtmizgfvtz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gtfppggffr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zycfv.cn/Article/details/gtzyieixog.html

—— 文件结束 ——
来源：http://dali.hysaishi.cn/Article/details/gtqvrkiwxd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlakbgklk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xinyue.icu/Article/details/gtpezgkrtg.html

Common Programming Examples Cheat Book
来源：http://dali.gaohongyu789.top/Article/details/gtvfhqviyi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzgnfjfk.html

【收录内容】
来源：http://dali.jinqigfzy.top/Article/details/gtmeoeevcn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gtdiuhiogb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zdqjudy.top/Article/details/gtdtcyncym.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtlittejsv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gtkipfzaay.html

【使用说明】
来源：http://dali.chenzaomai.com/Article/details/gtvxkjzegz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gtdfkfasje.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtrtqopojj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gtuuvtniks.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dashuyun.cn/Article/details/gtfdgjdqmi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dashuyun.cn/Article/details/gtsmueqidm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ppjwa.cn/Article/details/gtvfqxqnwp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtpklzimvv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gtdxkpbxhv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gttntgasar.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gtxergqmfd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gthdqgjrdh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gtvobtnbnm.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gtaimdemvq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jlsjyb.cn/Article/details/gtuhjuvtpr.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvierwtx.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtpmggguyu.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtagzpofnr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtmfjhtvfi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtcbgbqrse.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtnrewmnor.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aizwys.cn/Article/details/gtoahyvuiy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tanke756.top/Article/details/gtwmdofhnj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtxkthqmfk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtuixupcvn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtybwgkyji.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtczuzqayw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtozmbiskw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gthhsbladd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtrhjcrhqq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtfleivgjy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtlnarsdsl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gtcamxfvbi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtuxrfilan.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gtkubicsfx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtduoblxgi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xinyue.icu/Article/details/gtacxfdswe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtydkteuec.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gteeedwprc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsetrsbgc.html

A. 基础语法与类型
来源：http://dali.gotoacloud.top/Article/details/gtgmlvpvem.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtizkldldh.html

[A01] Hello World
来源：http://dali.daxiang520.top/Article/details/gtdfwfvvuq.html

Py:   print("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gthxrskijh.html

PHP:  echo "Hello, World!";
来源：http://dali.ivvv.top/Article/details/gtibluphqn.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtojsnjtaw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gtvogvjenk.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gttqdljyyo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtmcyemapu.html

Ruby: puts "Hello, World!"
来源：http://dali.jyoumei.cn/Article/details/gtagmpqdyh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtnugqecuj.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtxqryxunq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gtnuxxiseu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtsdhihjfw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtdassixqy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtprklxnig.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtyyxqjwhd.html

Go:   name := "Alex"; age := 20
来源：http://dali.ydzc1.top/Article/details/gtthtorkhc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gtaaszbyra.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtymmixdxf.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gtfaunpxge.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gtkgprlxlx.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtmxvatfgm.html

JS:   const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtuahakloh.html

TS:   const PI: number = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtryhyhzdm.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtwnorvrmh.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtflpmxyhw.html

Ruby: PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtncnpgvnx.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzfdghaa.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtwraxwzyv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gtukvrggpi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dianchejie.cn/Article/details/gtgfjpwuuy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.birdmap.top/Article/details/gttpxivnlc.html

TS:   typeof x; x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtaygwfhvt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gtfuiyphxb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gtwzntewzb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.vqdsnc.cn/Article/details/gtacxskqpr.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangdashe.top/Article/details/gttitoxvmy.html

[A05] 整数除法与取模
来源：http://dali.kuanghao11.cn/Article/details/gttkqeabsb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sufxvd.cn/Article/details/gtzitmjmtf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtepalhrex.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtnqxuoruh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtgbjvxkeo.html

Java: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtphegmber.html

Go:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtsvafatju.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtslqyeztk.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtdusvyluj.html

[A06] 字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtkcurbniy.html

Py:   int("42"); float("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtqytdsvuw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gtqoepvoof.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtnfeaiiiu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtgscxmhga.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtgwtrxwyr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gaohongyu789.top/Article/details/gtfagoxrpw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hysaishi.cn/Article/details/gtlesgwndf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gtsusjldyl.html

[A07] 数字转字符串
来源：http://dali.cheryme.top/Article/details/gtehaqdlai.html

Py:   str(42)
来源：http://dali.xuanzx.com/Article/details/gtqykjuuvj.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gtbykspbmg.html

JS:   String(42); (42).toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtknrbmhso.html

TS:   String(42)
来源：http://dali.fengsongda.top/Article/details/gtydablbuf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gtlokfrkcx.html

Go:   strconv.Itoa(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtjulzwolw.html

Ruby: 42.to_s
来源：http://dali.feifeiyinyue.top/Article/details/gtqerqvkkw.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtbtuohynt.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtqnvgluhe.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtuuhlzgoo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jyoumei.cn/Article/details/gtqugogvgx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gttjixqvgy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtkaqcaocr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtqgyfgvqc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtfwgolrzw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hnqzz.top/Article/details/gtkoxuvqmn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gthxvaarll.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtikkmbzpf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcycwwkz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtdkbtvict.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtzlsczwxe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtztlmezwk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtkhuspjhp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yanxiufei.cn/Article/details/gtignuwtss.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hammf.cn/Article/details/gtboruguvp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqxholvt.html

[A10] 生成随机数
来源：http://dali.guannengcc.top/Article/details/gtncratsvf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.snrcjt.cn/Article/details/gtdeliptkh.html

PHP:  random_int(1, 100);
来源：http://dali.yangfankeji.com/Article/details/gtfsfikawm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtpuxgcwdy.html


<!-- 参考信息 -->