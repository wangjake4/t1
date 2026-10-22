代发 wailian999

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gtfvthzroa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hfpthk.cn/Article/details/gtmjygciub.html

[U64] PHP：目录遍历
来源：http://dali.sweek.top/Article/details/gtdpcaquyt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gtyoyudlej.html

[U65] PHP：会话
来源：http://dali.chenjidiqi.icu/Article/details/gtpaswdfpz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcbjnlef.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gtwrtpmywk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xziqi.cn/Article/details/gteuxjabpd.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gtgpidncle.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtjhnsypvy.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gtjfgcfuoz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gtnwfzlkgl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhixingplan.top/Article/details/gtwasqjtzn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gtyjtplwmd.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtculylluc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtegywsuqs.html

[U71] PHP：抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtvsbbfhck.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtsvabnsxn.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtlqzmnbit.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtgeeonhot.html

[U73] PHP：读取 ini 配置
来源：http://dali.snrcjt.cn/Article/details/gtcdyfonma.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gtusmehlph.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gtyzwmhsqm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gtoegxztnz.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gtjzlsjipi.html

composer require psr/container
来源：http://dali.snrcjt.cn/Article/details/gtkevkcmak.html

[U76] PHP：简单路由
来源：http://dali.zhixingplan.top/Article/details/gtwdmzaqnt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoghhaqxs.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gtukqwqzpz.html

composer require twig/twig
来源：http://dali.yongpay.top/Article/details/gtjsodjtop.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtawucirdm.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygmmbktf.html

[U79] PHP：静态分析
来源：http://dali.iojbl.cn/Article/details/gtszdhrhov.html

composer require --dev phpstan/phpstan
来源：http://dali.xylfe.cn/Article/details/gtvpdfcwtw.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gtgionntaj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtaipzgecq.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gtxkgixiii.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gtltzxvwnj.html

[U82] JS：package.json 脚本
来源：http://dali.jqgufenzy.top/Article/details/gtikplubin.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gtpqamrafz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzzikxqc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtxhmuyquw.html

[U84] JS：CommonJS 写法
来源：http://dali.andypj.xyz/Article/details/gtwnbwxhds.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gtesoiamsh.html

[U85] JS：可选链
来源：http://dali.cucudq.cn/Article/details/gtwuewrclz.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gtmsagpehe.html

[U86] JS：空值合并
来源：http://dali.yj20258888.top/Article/details/gttcjtbqds.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtnhfexvlq.html

[U87] JS：解构默认值
来源：http://dali.sxryk.cn/Article/details/gtginhwmda.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ivvv.top/Article/details/gtlrqcoiqk.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gtuyuteech.html

{ ...a, ...b }
来源：http://dali.zhengqikj.top/Article/details/gthnuohsui.html

[U89] JS：数组去重
来源：http://dali.redwolf501.top/Article/details/gtghpywvrc.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqssgbufa.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtaoyztmuq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtqzpblilj.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gtensdrieh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guowangkeji.top/Article/details/gtdvnrqqcy.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gtpqchvixl.html

structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtxhrvdykb.html

[U93] JS：模板字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtsnqknwwu.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtvydbxvpw.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtjzsxhffm.html

const double = x => x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjubmumj.html

[U95] JS：Promise 包装
来源：http://dali.sysykeji.top/Article/details/gtsgzpftti.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtbuzleion.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtniudmcxr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtsrojjyns.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gtjqxzvvct.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtdwfcvynk.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gtvjrtfefv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuetiantiany.cn/Article/details/gtlmkyrdly.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gtawlsdenb.html

el.addEventListener("click", e => {})
来源：http://dali.bjfxy.top/Article/details/gtfwgurjcm.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtngaweqfx.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gtzqfstdgp.html

[U101] JS：classList 操作
来源：http://dali.c1oappe.top/Article/details/gtjpuzqmiq.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gthoofkrmq.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybcbibwg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtoagdexre.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gtmgdyumul.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtluykwkqg.html

[U104] JS：防抖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeljtjkh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gttfydskjt.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gtcibeynwm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yongpay.top/Article/details/gtxsmxqoaa.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtyrxvrjfh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gtjctwqhki.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gtbbuzimsx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtfgufhxrc.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtclzwptde.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtstutrtyt.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gtrqujdrwq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtrpbycqcv.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtcmvziijs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gtkznqsfqa.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbufbyhf.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gtepusmuur.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gtpzydoeos.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtputyfkqs.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtffdtzgrp.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtqrxwwzie.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gtcwlsjvmq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtccuscrrw.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtmfxamsyn.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilznceod.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtxclkuaoh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijagckbw.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtubnkbjbq.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gthxidkqbh.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gttlqcgbms.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtvspgpher.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtlciqjvtd.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gtpqegbhxj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gtfddsqmyr.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtdmijhwkn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxqdjiaaa.html

统计汇总
来源：http://dali.zycfv.cn/Article/details/gtqgthezgd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtciwcrjue.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gtrfmlkyur.html

Python ......... 252
来源：http://dali.ehwqpu.com/Article/details/gteuudlqyt.html

PHP ............ 252
来源：http://dali.chenzaomai.com/Article/details/gtvamgikdl.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpulbivy.html

TypeScript ..... 212
来源：http://dali.zhongyouzk.top/Article/details/gtlbscgzkq.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtgugwgazk.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtwnfyexlq.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gtuvjsmhjc.html

C# ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtcndzuvlq.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtmhpnxrzx.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gthmnbbzev.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtteeadgyg.html

Bash ........... 80
来源：http://dali.jyoumei.cn/Article/details/gtkjizkqjd.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gtawxmchij.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gtifkdasjo.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gtbeixsdyq.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gtxbfcyjns.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtzakupfcw.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gtxtdcihgx.html

合计 ........... 2106 条
来源：http://dali.xuanzx.com/Article/details/gtnxadtvad.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gtmxpygjwl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtinznlvuq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtrvgqzyjs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtpacguopl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtmptlbbhg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmacebrz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtazcxeben.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtjqtspwpy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtrsxqiduz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtexgngdjn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtlzfhvzwo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtemneyoxh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtgumeogzf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwaepcou.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtzngeqklq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gthqbcqcym.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtikkzrtsy.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gtsexoljlg.html

R Bash 专题                             80
来源：http://dali.dianchejie.cn/Article/details/gtwuqbbcve.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtjvpidzmq.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtagjuygkx.html

U 高频实用片段                         120
来源：http://dali.yanxiufei.cn/Article/details/gtjjdnrods.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtjmedblkf.html

合计                                  2106 条
来源：http://dali.cdnleiting.top/Article/details/gtovarjxpe.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gttdglqdws.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtzmlupely.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtosgumbbh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwceqtduk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhengqikj.top/Article/details/gtqxlowpwj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dianchejie.cn/Article/details/gtllabgbim.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.mhx1999.top/Article/details/gthphwjuuu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cucudq.cn/Article/details/gttzucavca.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftkuiyck.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmymmdngi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtsgoripfe.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gtcmzzzwls.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtglotsrqp.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gtjbmrwknh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gtrdydsnwn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gtrmulmxml.html

SQL · Bash · C · C++
来源：http://dali.jinqigfzy.top/Article/details/gthurzpuwx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenzaomai.com/Article/details/gtxozjsnhw.html

【使用说明】
来源：http://dali.kuanghao11.cn/Article/details/gtrujvhbjx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jlsjyb.cn/Article/details/gtaettmczq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hammf.cn/Article/details/gtwoytiblw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtophcknzx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtktchhyco.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sysykeji.top/Article/details/gtfgwzbabo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gtrwapxwye.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtaxkbcckf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gthdbytsfh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gtgzgkrogx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gtpmopufsx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pycfn.com/Article/details/gtdsbpwrgf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbzrrayi.html

【文件统计】
来源：http://dali.cdnleiting.top/Article/details/gtmkzbiubp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.0kj1m.cn/Article/details/gttvicjujz.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gthjnahxyf.html

目  录
来源：http://dali.xuanzx.com/Article/details/gtixbrgzfs.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtckinabgo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtdqcemeuf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtguymopvq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjykorftu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtsmppnnoq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yongpay.top/Article/details/gtnmrbdbou.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtglpxpiom.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtwjjjsbwo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gtwngdmmpe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtxzhoxfze.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtfpnowpkf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtolgnjmgg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtjkkqckye.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtqgayuhbc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtthvspvlj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwjpfftb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gttvtivrom.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fengsongda.top/Article/details/gtcuiylbjr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtnmuztowz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.havefunace.top/Article/details/gtfwwpwpgt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtytzvelnv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtozudriyg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtigxrdwuq.html

A. 基础语法与类型
来源：http://dali.pengpengdd.cyou/Article/details/gtlpohhtqd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjpyspwmn.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gtnyexwcam.html

Py:   print("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtayewweur.html

PHP:  echo "Hello, World!";
来源：http://dali.zhengqikj.top/Article/details/gtqcegybce.html

JS:   console.log("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtlyuoovrx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hywenlv.cn/Article/details/gtpuoxofdt.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtkbhravtq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtffskxveg.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtdjxftgyt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtkkwgpblk.html

[A02] 变量声明与赋值
来源：http://dali.pycfn.com/Article/details/gtiulkxvpd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangshuangyany.cn/Article/details/gtwgdivwos.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtlcdthgvx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daxiang520.top/Article/details/gtnrketcua.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigufen.top/Article/details/gtgyvspyjt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtmngdjamm.html

Go:   name := "Alex"; age := 20
来源：http://dali.svipenyu.cn/Article/details/gtsjxjhcmr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gtnmqrfjmg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gteembijvd.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gtokvbbduw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guannengcc.top/Article/details/gtetyuxage.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtyuknxtta.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwausvbor.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxrzogsw.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtkhdcxwwg.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtrsiyuswv.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtkicpirdm.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknzliifg.html

[A04] 判断变量类型
来源：http://dali.yvedp.cn/Article/details/gtmrzftabn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gtxnqatdrm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtvqrowlxe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtjknszcjq.html

TS:   typeof x; x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gtrqnxjqvr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gtvmpbyvrf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzapzhyj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tianlin.xyz/Article/details/gtjcgslufw.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtdkdqetgq.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gtgehacpxx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gtfbvabgfz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtckajdqgq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtvpzdwrlv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtwwpuccun.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtzncsznxt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtkahtjboc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtybldswyf.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtoidzvlvm.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtybbfdeim.html

Py:   int("42"); float("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtqgfhfuyc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hfpthk.cn/Article/details/gthsbxensm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gtanwmyxtr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtnovfzfkt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtmeogkvya.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.9152youxi.cn/Article/details/gtvbfrjytu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsbludjy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gzhubu.top/Article/details/gtoycmnpqq.html

[A07] 数字转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtnpfkqpkj.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gtxptdkgsy.html

PHP:  (string) 42; strval(42)
来源：http://dali.xylfe.cn/Article/details/gtcbdexcis.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gtptfrjrih.html

TS:   String(42)
来源：http://dali.wangshuangyany.cn/Article/details/gttbtnzpxx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tanke756.top/Article/details/gtygfuwxbh.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqhippru.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangtech.top/Article/details/gtozgroxpg.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwcfowod.html

[A08] 取整与四舍五入
来源：http://dali.aibaodan.cn/Article/details/gtobbzvati.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtozxzybhe.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gtzzeppeat.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtzilhgclo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daxiang520.top/Article/details/gtdjjtjpdc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtaykilrpv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtnrclhejk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jyoumei.cn/Article/details/gtnnoaaxjs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtlhxymhqy.html

[A09] 绝对值与最大最小值
来源：http://dali.cucudq.cn/Article/details/gtioniarpg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmctawusq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtivpyrgvy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtejtgtoyx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtmebfriba.html


<!-- 参考信息 -->