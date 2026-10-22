代发 wailian999

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gthxgexyww.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtmprqbrab.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gtwpcogwfs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xylfe.cn/Article/details/gtosxbocpw.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvmcmmsi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtrxjmmtos.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gtvwwkmwvp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtgwesppou.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfmzufdc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gtphebievo.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtsemautgs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtrmjuvhyr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhiwuduotai.top/Article/details/gtxlwixqur.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtmisebpqk.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gtzidlucut.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.redwolf501.top/Article/details/gtmmnzghuq.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtllbuyqyp.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gttqiydhwn.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gthrirgdyc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gtchgptofu.html

[U73] PHP：读取 ini 配置
来源：http://dali.andypj.xyz/Article/details/gtymiihccm.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gtbexoitdc.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtgzecbzpn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gtiyqtzfxx.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gtstoqxqrn.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtnosyahuw.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtohvbbdml.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtfcixniso.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtfpgwflow.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gtcluoeekx.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gtoxsctxyz.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gthbaaqosc.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtmxithupd.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gtgwovaihl.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gtcxxzzoxo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gtoucrbpcp.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtcmqwxzqu.html

npm init -y;  npm i express
来源：http://dali.dashuyun.cn/Article/details/gtbdumfrzm.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtrwiypbsy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtvwavpckj.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gtvwtwqtar.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtnelknded.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gtfmjxhykv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtnvsidocf.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gtpucxyvvw.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gthmkxrwgp.html

[U86] JS：空值合并
来源：http://dali.redwolf501.top/Article/details/gtixauwitx.html

a ?? b
来源：http://dali.guannengcc.top/Article/details/gturiyrsti.html

[U87] JS：解构默认值
来源：http://dali.guannengcc.top/Article/details/gtzexhuewc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gtwpapkafu.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gtctiejjwz.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gtwaxjtcva.html

[U89] JS：数组去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtswxzxigt.html

[...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gttadqmqne.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtxtfusrgw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtkogydply.html

[U91] JS：对象键值遍历
来源：http://dali.hnqzz.top/Article/details/gtecbjzowk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtpgohxnwk.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtlhrfhyif.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtyfjjujpi.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gtdrhxqqjn.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gtfkvyvfae.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtdqrmvtcd.html

const double = x => x * 2;
来源：http://dali.gogol.net.cn/Article/details/gtmuwqzqux.html

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gtyudgqdaj.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gtbhajlaeu.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gthhjhtvjm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtexmmhvgi.html

[U97] JS：并发请求
来源：http://dali.birdmap.top/Article/details/gtznobyboz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtlvnpobiw.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtwkqnumij.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtrfljihwk.html

[U99] JS：事件监听
来源：http://dali.ydzc1.top/Article/details/gtfqqflqsr.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqcpdnbs.html

[U100] JS：DOM 查询
来源：http://dali.hnqzz.top/Article/details/gtsopyyhut.html

document.querySelector(".item")
来源：http://dali.ydzc1.top/Article/details/gtrgbjpvpx.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxounpmm.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtyogaceao.html

[U102] JS：本地存储
来源：http://dali.yj202588.top/Article/details/gtaixmfwof.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfpnfozv.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gtnwicrymh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shzxlz.cn/Article/details/gtdtigynye.html

[U104] JS：防抖
来源：http://dali.gzhubu.top/Article/details/gtquieeoth.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtwkshtwrn.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxmswdls.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jlsjyb.cn/Article/details/gtjcdcdtyl.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gttyhscuwn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtkpsxqiuk.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtbdaguaap.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gtdovrqedu.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogcfwghe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtkvrfjljb.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gtlofxlvmw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtvkuyvdxe.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gtirkrtxsz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gtaitjsryc.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtxpmpiedf.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtnktwlfuw.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtpkfhqjnq.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtrgqznotn.html

[U113] JS：正则替换全部
来源：http://dali.jlsjyb.cn/Article/details/gtjawzeyeq.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgejfspj.html

[U114] JS：JSON 深比较
来源：http://dali.shzxlz.cn/Article/details/gtbhiwkcrc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtzsaxguvf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtinwpwboh.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtkammhcei.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gtatottydr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcntogaqw.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtdvhaorbh.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtjhqdtson.html

[U118] JS：开发服务器
来源：http://dali.fengsongda.top/Article/details/gttnuxuojx.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gtzddxfjyb.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtudcjfzut.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gtcegrlcrs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtfzoqzcsj.html

import.meta.env.VITE_API_URL
来源：http://dali.birdmap.top/Article/details/gtyghltzsk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeiodjec.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gtctnoszml.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbikzlghx.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gtvdbtowzo.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gtvybjskqb.html

PHP ............ 252
来源：http://dali.gzhubu.top/Article/details/gtvrlwhxoj.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gtgsmiiuhq.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtbjlbfaxz.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtfmydjllr.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gtyxytlkdw.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gthqnsnyje.html

C# ............. 212
来源：http://dali.yj20258888.top/Article/details/gtkppcxqlu.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtpewphwgu.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtjfwqmvgk.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtzlpolnyn.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtbetewgsp.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtrnyyvhtv.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtjlvckuzw.html

Lua ............ 10
来源：http://dali.0kj1m.cn/Article/details/gtxwdqyhpu.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfyvucdn.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gtfnlgdjnp.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtptkppgve.html

合计 ........... 2106 条
来源：http://dali.jianghu66.top/Article/details/gtjpqhdudj.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtxtpgztcp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtecvicawy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtwcvnzdqr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtpltrfnkf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gtgfxzopnq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj202588.top/Article/details/gtcnlkldqv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtrdualqco.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtsqyzgcjb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gtuginyhni.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtmskokzwe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtzyqrwous.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtewdkqsem.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtpihxfkks.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtymxxbyxu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gtddvzxjju.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gtcibnckuo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gttvkdwgus.html

Q SQL 专题                              90
来源：http://dali.316326.xyz/Article/details/gthjbzrzri.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gtqgkvbouk.html

S C / C++ 专题                          60
来源：http://dali.haohaochexian.top/Article/details/gthamlxnla.html

T 其他语言补充                          60
来源：http://dali.sufxvd.cn/Article/details/gtmfpjomem.html

U 高频实用片段                         120
来源：http://dali.zhiwuduotai.top/Article/details/gthiezchws.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtoiounlao.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtwzjapvjh.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtcixeyvgl.html

使用提醒
来源：http://dali.gzhubu.top/Article/details/gtguiginve.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtgpimcewt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gthsnxlyea.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shuidangran.top/Article/details/gtpnzaxtuz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guannengcc.top/Article/details/gteoyzfxnl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifjpdzut.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gtouscwneq.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gtbqfqkimp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgeqvgmcg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gtkzdtdnhq.html

Common Programming Examples Cheat Book
来源：http://dali.fengsongda.top/Article/details/gtjhjigbnv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtamlgoxrz.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gtplqpidrp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.meibo888.top/Article/details/gtttwnurcl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gtzghyviqp.html

SQL · Bash · C · C++
来源：http://dali.sysykeji.top/Article/details/gttufkxeow.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonymjexb.html

【使用说明】
来源：http://dali.smart0.xyz/Article/details/gtaljxbgoj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtahpindwk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guannengcc.top/Article/details/gthsfmbmsa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xziqi.cn/Article/details/gtzvfebnko.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtuqiqhzbb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yangfankeji.com/Article/details/gtgctvxcgg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gtjowirrso.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258.top/Article/details/gtjwwmklya.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenzaomai.com/Article/details/gtagijhkva.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtrpdshrfp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gtbwygxdse.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtnbarqgkh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gtelchmrox.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gtxkfivyhv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtrbvkgznx.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtzgxskasa.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gteljfeazd.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gthxcsrfzk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtvsiezpsa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtqcrjkuyn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtfkqguvet.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtpekmuiwk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cdnleiting.top/Article/details/gtjwwetbzd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtuxfhatcp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtojicbhgg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtaiyhhgwe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtvcvtpsqz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtksxfvnvl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtdmvbhgey.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtiocqhlrl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtyqcdzhcg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtiuovspqb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzutfuit.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtlfltzech.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fzhhl.top/Article/details/gttrfsxmpm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gtjbgobdmc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cashguo.top/Article/details/gtxkxfiapq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtrmkkdwql.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtuhwvgals.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxmppkjod.html

A. 基础语法与类型
来源：http://dali.yangfankeji.com/Article/details/gtlrmoobqc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdlwfizxt.html

[A01] Hello World
来源：http://dali.cdnleiting.top/Article/details/gtcmcszats.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzalbanqw.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtpexvevyk.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtarimqlyr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gtcukqlltq.html

Java: System.out.println("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtzaxzzdbu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtubjaywnp.html

Ruby: puts "Hello, World!"
来源：http://dali.wangdashe.top/Article/details/gtulwqapog.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtbhrprjtx.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gtlvpechxk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtsmgokhtr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwrpydkf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gtqhyhyfdn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tian-w.cn/Article/details/gtnnqkbkqy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtrytxnrzr.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gtgwtdidbn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guowangkeji.top/Article/details/gtuhwggddh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gthmautczp.html

[A03] 常量定义
来源：http://dali.gogol.net.cn/Article/details/gtxhakhfcx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhixingplan.top/Article/details/gteawdhmdu.html

PHP:  const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtxqsjfjvm.html

JS:   const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtvvzvhxwa.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gthjgwmuns.html

Java: static final double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtwuexxtrw.html

Go:   const PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtkrtvyemf.html

Ruby: PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtzpxnrdjx.html

C#:   const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyixvccv.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gtgtzqdami.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cucudq.cn/Article/details/gtmdorerev.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jiagoushi.top/Article/details/gtmdvojnvh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtgvvcnbnu.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtqqolgase.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gthrvgjzpd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gttmkxppmm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gttkztxzmc.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gtwitkndbb.html

[A05] 整数除法与取模
来源：http://dali.jianghu66.top/Article/details/gtfdbpucwd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hfpthk.cn/Article/details/gtzpcnivpe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtpmcvsioh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtkiblnile.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtrtrjofzu.html

Java: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtrunnerbp.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtzaehcdfq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtoterdtxh.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtnqifikga.html

[A06] 字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtolxavmas.html

Py:   int("42"); float("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gthilxfhiw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtowabwhxq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtzixfxsyf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.birdmap.top/Article/details/gtxuugcgfj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtthtvnmeu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gtehvutbkw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gtmpzgvrsd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gterpxfgqq.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gtsbnbxvop.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gtejdqpapg.html

PHP:  (string) 42; strval(42)
来源：http://dali.svipenyu.cn/Article/details/gtuuvdeunm.html

JS:   String(42); (42).toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlzhrdybu.html

TS:   String(42)
来源：http://dali.daria6918.cn/Article/details/gtwseafdmw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gtorodfwqr.html

Go:   strconv.Itoa(42)
来源：http://dali.meibo888.top/Article/details/gtnvupyepe.html

Ruby: 42.to_s
来源：http://dali.nanxuanxn.top/Article/details/gtsczwkfsk.html

C#:   42.ToString()
来源：http://dali.yvedp.cn/Article/details/gtgkezxswj.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gtrafsdngu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtjgyqfxpl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtqkyzhzwd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbzxwyte.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gtokgcbgra.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtfwahucgm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtgrwakfsx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhiwuduotai.top/Article/details/gtxpduitiu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysogrdvg.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gtzvpimvtb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gttkzvyiws.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gthirwzfzw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtmvkmeefd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtrpkimelb.html


<!-- 参考信息 -->