代发 wailian999

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gtanponmxe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gtbmiuyopu.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gtqbuxtlwr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cdnleiting.top/Article/details/gtylcjlqsa.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtldipehdt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtfwmqljud.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gtrxxuwhko.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shzxlz.cn/Article/details/gtjumjbsqn.html

[U67] PHP：处理文件上传
来源：http://dali.pycfn.com/Article/details/gtbtybwnvq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.iojbl.cn/Article/details/gtaotttlzt.html

[U68] PHP：PDO 连接
来源：http://dali.pycfn.com/Article/details/gtdpcetrdl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gtefwlreql.html

[U69] PHP：PDO 预处理
来源：http://dali.iojbl.cn/Article/details/gtfgbyjbnj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gtwsqlqioi.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gtnbleyxsz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtxhnmikki.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gtfxtkpgqg.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gtmolaqcjx.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gtrhhooaow.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gtvkmmxqst.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gtyxulnpry.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gtxumimfnw.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtibvvpgmv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gtlnshspeo.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gtqaabybmu.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gthzbrcwvk.html

[U76] PHP：简单路由
来源：http://dali.aizwys.cn/Article/details/gtnacxeskg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuanzx.com/Article/details/gtgdghhyjh.html

[U77] PHP：模板渲染
来源：http://dali.pycfn.com/Article/details/gtstgyqyle.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtltedegos.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtsjfizoxv.html

composer require --dev phpunit/phpunit
来源：http://dali.daxiang520.top/Article/details/gtgmeezblb.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gtuyiofbpg.html

composer require --dev phpstan/phpstan
来源：http://dali.redwolf501.top/Article/details/gtoweuescw.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gttzigvwct.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gtkktotcsh.html

[U81] JS：初始化项目
来源：http://dali.0kj1m.cn/Article/details/gtvgalbwuo.html

npm init -y;  npm i express
来源：http://dali.xuanzx.com/Article/details/gtjycbrdyl.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gtehejaxdg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gtbzfglvrt.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtsizpgmwk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtltuwqslj.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gtjcsyacar.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtpdlltncv.html

[U85] JS：可选链
来源：http://dali.cdnleiting.top/Article/details/gttyzfbldr.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gtesbmpfvx.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gtgxzjprpi.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gtlxuellhf.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtojmwatwm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtbcfthvon.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gtuqwcrztj.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtqmputbcj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gtwwjkxbnb.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtgeenogws.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gtgckxmzeu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtudhshvqy.html

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gtxfsegcvn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkkcrfaz.html

[U92] JS：深拷贝
来源：http://dali.yj20258.top/Article/details/gtjgajpyyt.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtgrtbvlmj.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtdllymtfz.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtariodhpi.html

[U94] JS：箭头函数
来源：http://dali.yj20258.top/Article/details/gtozdpmcjs.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtotcrcoty.html

[U95] JS：Promise 包装
来源：http://dali.birdmap.top/Article/details/gtwhifqrmg.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtysrkkedm.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gtnlyzpaxc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtwmixtxxr.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtuickomhq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtfugrdwpc.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtruzdwntp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtuuktirja.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gtgvjlndpp.html

el.addEventListener("click", e => {})
来源：http://dali.yj202588.top/Article/details/gtlmemntqd.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gtcdbhuapc.html

document.querySelector(".item")
来源：http://dali.yanxiufei.cn/Article/details/gthzdjpogk.html

[U101] JS：classList 操作
来源：http://dali.cashguo.top/Article/details/gtixtfdgjy.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gtpnepaout.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtnqdtmuyy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gtvuyxlhdq.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtkdssjvcz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shangyingyoupin.top/Article/details/gtmxnhhted.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gtepyesuiu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtfmfiwkvk.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtevazitsq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtxijaphuw.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtqlcfllmz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtsbmrmrky.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gtzoiwmpfa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gtpjjfcnns.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtuuxcrdel.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtvkyykfww.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gtbvgmqebo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtrzkwcluy.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gtidnofvpi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.haohaochexian.top/Article/details/gtqdzsrnah.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtxcfixxps.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtxqanouof.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtxhpbvrpx.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gttuzlqjgy.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gtxnszolmz.html

s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtinpeekfv.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvaouirt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtaqyhvvfw.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtvqdomcqo.html

crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtjabdaavy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gtyvazfdbz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gtkwvdjthz.html

[U117] JS：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtspfmgzsd.html

npm i -D vitest;  npx vitest
来源：http://dali.kuanghao11.cn/Article/details/gtmkgavgxa.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtcmnrfnff.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtasdudvzu.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gthylarogs.html

npx vite build
来源：http://dali.wangdashe.top/Article/details/gteekdlvgy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtrualifvw.html

import.meta.env.VITE_API_URL
来源：http://dali.pengpengdd.cyou/Article/details/gtzsifzzkq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfovhmohi.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gtnroeoutq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnvefpsrc.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtcsrtdqjm.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtvpakjpgd.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gtbifveceb.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtabdskxiq.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfstlnmq.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtnajxdhsx.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtsimvzpql.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtirtemxet.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gtiitdqcyw.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtkmrhvqub.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtyjbtevcj.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtxbctedvt.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gtnwbjrxnm.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtmgwbsqox.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtvdrisank.html

Lua ............ 10
来源：http://dali.yj20258.top/Article/details/gtwcqefjhj.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcplsehdy.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtuhwemzgn.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtphoeubmz.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gtjauvdfdg.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gtjgxogcld.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtplplmuey.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtwqacanov.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrypfzgba.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtbgkpqexy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dashuyun.cn/Article/details/gtyhvluazx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gtbjowdzdr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtsbgzhwhz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtvlrchltj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtmtowadzx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gtrsgvwujd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcmfmjjj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtgyfwyywk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gthrhukxtf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtdkefsznb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtmbktgxcq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtcmqkqgtk.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gtrthqisey.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gtqjccffqe.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtkajnvdeu.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gtbmwbiakt.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gtmwfhmmxk.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtlzcuubav.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgmbtryu.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtegmllxeg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gthhdsbdwj.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtemeemywu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gtcpsbxnha.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gtzazukviu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.birdmap.top/Article/details/gthhvxirfb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtndgosrkq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtedervjrw.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gtabzusocq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthjsltyhz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gtvrcrzskm.html

Common Programming Examples Cheat Book
来源：http://dali.jiagoushi.top/Article/details/gthraizvrc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtewmdrnfx.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gtwfskciib.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtesrclwks.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gtwsiaicnr.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gtyotpnfwa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gtcvhirjue.html

【使用说明】
来源：http://dali.zhiwuduotai.top/Article/details/gteqtblfjs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yueranfly.top/Article/details/gtilzrggro.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hysaishi.cn/Article/details/gtlyfwqczu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinghuilouyu.cn/Article/details/gtwthyvyef.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangshuangyany.cn/Article/details/gtqxqkshhz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtvmmexzso.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtphuekszf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gtdfgmcmry.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gtopuffunv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yongpay.top/Article/details/gtywkxqefg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gtbwtmkyqx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gtkjzsqerx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gtwyejfwni.html

【文件统计】
来源：http://dali.c1oappe.top/Article/details/gtmgwrbldy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gtiuqafkwo.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtjmvnayli.html

目  录
来源：http://dali.yj20258888.top/Article/details/gtadvhczpf.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtkkfsquqn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtxpdhublq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtzrjowzmm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtegxbiwat.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gthzkrjwmw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cqqwz.cn/Article/details/gtuuckwdwn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gteghlocbj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtpkzwkhhg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtzriqovhq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtxtropevi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytjtmzjr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtfpqovtfv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtjffqbyqj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtkgqrqnpf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gthnlsseul.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gtuhljwvev.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtvzvyeago.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ydzc1.top/Article/details/gtuygziruv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiwznvwz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigfzy.top/Article/details/gtavjwfxgp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gteguqoasw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtmjzzokgn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtowasmsly.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtnfgyiufm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwdiahjgt.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gtqvfaggwe.html

Py:   print("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gttjjgyitl.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gtxjscnvhh.html

JS:   console.log("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtpbjoslvz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yueranfly.top/Article/details/gtafnbnkit.html

Java: System.out.println("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtvpbjkhxl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gtuefgvaaq.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gtdhqwwyug.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnukvcser.html

[A02] 变量声明与赋值
来源：http://dali.nanxinkj.top/Article/details/gtywfbutnd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtkkesjjqu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tanke756.top/Article/details/gthyajheno.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtqyihefld.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtqsgchbql.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtvcubuzot.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gtitxnsaje.html

Ruby: name = "Alex"; age = 20
来源：http://dali.316326.xyz/Article/details/gteemngcyg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtzgiwsitk.html

[A03] 常量定义
来源：http://dali.mhx1999.top/Article/details/gtnfboykdn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gtgigtggvq.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtppclhkjw.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtdqodflpx.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtfttpaknv.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtxkbbsoez.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtsrfgmhgl.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquttrjel.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gthzpefikl.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtcoovscht.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tianlin.xyz/Article/details/gtqjfrozbm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtxzhmlbsv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gthqtpzdjl.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtlwnmxduu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtfshhztup.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gtaztaslsk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gtpukbwhrj.html

C#:   x.GetType().Name; x is int
来源：http://dali.bjfxy.top/Article/details/gtfhufpdmz.html

[A05] 整数除法与取模
来源：http://dali.gotoacloud.top/Article/details/gtktxzhsnz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daria6918.cn/Article/details/gtwclwghdp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtmwbnmyhe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtidsuvcuv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtrrzyriyn.html

Java: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtnorzyfsn.html

Go:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtlyzexzhu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtmbyhgsqx.html

C#:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtdpeknvsy.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxmxapgf.html

Py:   int("42"); float("3.14")
来源：http://dali.daxiang520.top/Article/details/gtoublktkw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtbobyddsr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjzuwlma.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gtvbelhlov.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gtetadbrzb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.iojbl.cn/Article/details/gtthtlffjs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gtdcuibimn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkmthsdd.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gtprsbhcvg.html

Py:   str(42)
来源：http://dali.yonumen.top/Article/details/gtujhiigzo.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkpjgfvf.html

JS:   String(42); (42).toString()
来源：http://dali.wangdashe.top/Article/details/gtdhbwwhex.html

TS:   String(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtoksotz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ehwqpu.com/Article/details/gtgrcrkfyj.html

Go:   strconv.Itoa(42)
来源：http://dali.ybcxt.top/Article/details/gtkpbvqfvb.html

Ruby: 42.to_s
来源：http://dali.xuanzx.com/Article/details/gttvylzwns.html

C#:   42.ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtvjhdexsv.html

[A08] 取整与四舍五入
来源：http://dali.guannengcc.top/Article/details/gtcclorhme.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtikejvrtj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gttkgmseuo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxrlhxjq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gtxzssnnrv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtwilvuvft.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtitrrdapk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jlsjyb.cn/Article/details/gtwizyoklb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtbzwhoflx.html

[A09] 绝对值与最大最小值
来源：http://dali.smart0.xyz/Article/details/gtsreffbpu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnzfcgftj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtithonchq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtgcpkekrb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsvohqvx.html


<!-- 参考信息 -->