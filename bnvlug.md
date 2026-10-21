代发 wailian999

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtiodiphuf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gtjdiseaya.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtznaifbrr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtfuzabouy.html

[U65] PHP：会话
来源：http://dali.guannengcc.top/Article/details/gtmyyxpleu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtzehsksgi.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gtxyldrzin.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ybcxt.top/Article/details/gtibexrwlc.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gtbbxryfca.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtuskmtndb.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gtiavrxgod.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gtyunzknrb.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtqnbwwvyg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtsxkpudfd.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gtqrxpvtzy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhixingplan.top/Article/details/gtjdoevjyt.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtovaepfei.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gttznxyzrg.html

[U72] PHP：写错误日志
来源：http://dali.cashguo.top/Article/details/gtpohcwzji.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gtjyeeraqf.html

[U73] PHP：读取 ini 配置
来源：http://dali.jyoumei.cn/Article/details/gtwkezvldv.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgfzy.top/Article/details/gtwnmktvnx.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gthlrcjeou.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gtiscismjs.html

[U75] PHP：依赖注入
来源：http://dali.sxryk.cn/Article/details/gtdmhbebpq.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gtrrzwinwy.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtuswgiyyz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gtgwbkrojt.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gtsmpmjrgf.html

composer require twig/twig
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrtjuhmf.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtobmsodum.html

composer require --dev phpunit/phpunit
来源：http://dali.ydzc1.top/Article/details/gtfapfghcj.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtropvxote.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtwfqgjtlg.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gtdyzhfuop.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yangfankeji.com/Article/details/gtpcybjnll.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gtkdrolqja.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gtsbyxvdsl.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigfzy.top/Article/details/gtrmfdmamb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gtpmbrmnor.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gteddrchlc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gttuomnzum.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gtpccwryme.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gteomwrkzt.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gttwaqbnse.html

a?.b?.c
来源：http://dali.shangyingyoupin.top/Article/details/gtnkdnbgmr.html

[U86] JS：空值合并
来源：http://dali.xinyue.icu/Article/details/gtbkrybsxy.html

a ?? b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpokfstoc.html

[U87] JS：解构默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedokdcay.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gtunnsyavi.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gtxxmpwcxc.html

{ ...a, ...b }
来源：http://dali.hnqzz.top/Article/details/gtiomyuwre.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtkobkokxq.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtbryblxtb.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gttvoisuny.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtkvnvkgyz.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gtovxfkqzm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gtvzurahcr.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gtglvnpvfu.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtencgugur.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtdixfzocs.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtczljwltr.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtvnzhswpq.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gtdilklqhq.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtoygxarcf.html

new Promise((resolve, reject) => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvzisvef.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gtsbmevlra.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtusrasbcl.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gtrdeyohdz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtxpgbkbnk.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxinkj.top/Article/details/gtbhfbsdit.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgibxbnye.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gtvfeiwcac.html

el.addEventListener("click", e => {})
来源：http://dali.kuanghao11.cn/Article/details/gttoxjozwq.html

[U100] JS：DOM 查询
来源：http://dali.xinyue.icu/Article/details/gtsvyylifb.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gtnzbucagd.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gtglzoklkd.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtludmhjse.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gtshhvgflv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gtsvrjhhds.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtzmxnohlf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtczktizut.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gtmhxoqqyz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtnqviqntq.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtnptvhzdd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gtggyunbwv.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtzsynwpuc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gtbhswcuwe.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtvphgqjeb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtoifvgjnx.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gtmoaymppt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.svipenyu.cn/Article/details/gtwkhksxtq.html

[U109] JS：数组分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfojupkh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtqzrjmqbd.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtqoforvhz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtogxzcagm.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtcdwbyjmc.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gthyrguatt.html

[U112] JS：字符串补位
来源：http://dali.cheryme.top/Article/details/gtxqylyuqk.html

"7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtgnejgxuf.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gtwhlvofkt.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhsmfrty.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gtlkwhmepn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtnmgslsbc.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtypekfifo.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtvbchqibr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtiqjccaam.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqfucsme.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtgtxwngjp.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gtigpkfduw.html

[U118] JS：开发服务器
来源：http://dali.nanxinkj.top/Article/details/gtvybkdwdf.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gtzfnycqik.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gtolafrigt.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gttsbepxhz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gtgzwlgwkg.html

import.meta.env.VITE_API_URL
来源：http://dali.birdmap.top/Article/details/gtnvtkiqyf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkjwkrfuh.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtqalhzymd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmqhpuibq.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gtkaymrrto.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gteryorhse.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gtferbjgrw.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtygajkskg.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gtmvgprujx.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gthxwitsip.html

Go ............. 212
来源：http://dali.iojbl.cn/Article/details/gtsrxadsks.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gtbpqntfkv.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtcwzoxftd.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtubxtxjvx.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtbscypulg.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gtbishyzol.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gtiophhxew.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzzwidlx.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtwesguwbx.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gtwmsgcxap.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gtxqoylsmk.html

Scala .......... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdrdrabr.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gthpqsfjgd.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gtxmidfymx.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gtraqajopx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtxwhlzsfw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtbiuxuujs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtusnylkdw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtmaresuej.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gtnhdkvrtd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtlrwcozoz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtetxzprfz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gtwrcaamvn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtgkjzgtav.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gtphyjdzeb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtsxhwtnaa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtozfvlakh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gthaxbwdqh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtfmorbqem.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtrdbpgoof.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmgnbbir.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gtpivzveam.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gtauisnafy.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gtqxgrfija.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gtyhtondfi.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtrmsqjdar.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtoijxxcyt.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetrimxgk.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtfjkiyktq.html

使用提醒
来源：http://dali.gzhubu.top/Article/details/gtuazuyivq.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtmorukwnf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtjhrhbgpu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gtpprlkgso.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gtcczkvvrt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cashguo.top/Article/details/gtxoinxayq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jianghu66.top/Article/details/gtaegjppzv.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtjtwigbqn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqttwiaql.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gttnvrovrd.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gtqiresvxk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsflwxvpd.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gtbtzbaxdp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuetiantiany.cn/Article/details/gtpadcczay.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtkctmswyi.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtbzfrlrrf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtpwttuhne.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gtlgyheuyt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.0kj1m.cn/Article/details/gtwecvsblf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258888.top/Article/details/gthjgyixmg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guannengcc.top/Article/details/gtwvvdaqjt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ybcxt.top/Article/details/gttwyxuufg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtjhqqwzsy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yanxiufei.cn/Article/details/gtdqznffsk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gtjucbdrfr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtliiwblnb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ivvv.top/Article/details/gtddzckkyc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gtkxfwoydj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenjidiqi.icu/Article/details/gtzujiixho.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtcvgvwxmr.html

【文件统计】
来源：http://dali.chenzaomai.com/Article/details/gtpvclajov.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gtxofsqbnv.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtlgyyrzmi.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gtukzpscir.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gthfevjuvm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gtotbdroqj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtilqfzcir.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtnwqiwpad.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtdneorcvf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ybcxt.top/Article/details/gtppdlyauk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gtasilwabx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gtdgwenkcu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtmrtlyxid.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtvxkzfucw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtttoltiwf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtjlhrxqmc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtyivkvwjl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtfuifgdeo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtfpclofue.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuanzhike.top/Article/details/gtsknbbdog.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtdzzaopdu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtknwvvjqc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtaeauhrec.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gtslbftauh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtsoueiabe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtnalakvdb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtctpfaezj.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gttwibdjtv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdqixunsi.html

[A01] Hello World
来源：http://dali.sxryk.cn/Article/details/gtlcaepnut.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtmjmpsogk.html

PHP:  echo "Hello, World!";
来源：http://dali.tanke756.top/Article/details/gtzplrvzgz.html

JS:   console.log("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtxrtutsls.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.9152youxi.cn/Article/details/gtfgbycjva.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtarpbltzh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijbmhtrq.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gtfofvjmii.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtjcbzqfnk.html

[A02] 变量声明与赋值
来源：http://dali.daxiang520.top/Article/details/gttthnqvgd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtjylxsbww.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtnqfwxxpt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtlukaoiae.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtjnfvmnej.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtbthhtuag.html

Go:   name := "Alex"; age := 20
来源：http://dali.xylfe.cn/Article/details/gthqyipbqv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xziqi.cn/Article/details/gttdegalxr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtmbncaiix.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtlcvqcjkw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuetiantiany.cn/Article/details/gtlothxcno.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtibjdmflq.html

JS:   const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtisyqdcdf.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtmptpmziy.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtauvukcqt.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtpoecuxpu.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtsmbymdsl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtkxsyzizj.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtlfxlmcup.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnxiangtu.top/Article/details/gtxixpugvj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtwyzuzigt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gtumznnmat.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtfbvyhqca.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gtlplssjtz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ivvv.top/Article/details/gtlzqkmdgt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlnnryll.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtwawrbbhb.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gtaawusrcs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258888.top/Article/details/gtlsbzwgkg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtipdlnzfh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtojidsfiz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtmslrkocf.html

Java: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtbznpiefn.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtgqysyycp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtjuwuabfk.html

C#:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtrgebfybe.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gttkcoohgl.html

Py:   int("42"); float("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtxghserqu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gtdbenrdvi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yvedp.cn/Article/details/gtsbvlgyhf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtmrvczlxw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuxming.cn/Article/details/gttbhykhqa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gzhubu.top/Article/details/gtohtmwedz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.0kj1m.cn/Article/details/gtawkjqpie.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtklhjbugf.html

[A07] 数字转字符串
来源：http://dali.sufxvd.cn/Article/details/gtkdasjjqe.html

Py:   str(42)
来源：http://dali.redwolf501.top/Article/details/gtzsqkrver.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gtksynjfah.html

JS:   String(42); (42).toString()
来源：http://dali.zycfv.cn/Article/details/gtqmiwseni.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gtpxlfvkrd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gotoacloud.top/Article/details/gtlmlmgiip.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtyqhcrkvp.html

Ruby: 42.to_s
来源：http://dali.jinqigfzy.top/Article/details/gtqooybubq.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtoijrhhum.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gtkiurbogm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtlypxfzxi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xylfe.cn/Article/details/gtskiqxszg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gthlxgcxyq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxinkj.top/Article/details/gtphskxpfh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtazchjpbb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqmsscfc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gtzicrcjgd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtmnnnwsmz.html

[A09] 绝对值与最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtrbvvievm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtfjxialmq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtgeowexpp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvtaimdv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtzpfwjegr.html


<!-- 参考信息 -->