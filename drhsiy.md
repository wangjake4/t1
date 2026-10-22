代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtoovvsrni.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtuqntdeha.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gtfohdqrhj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtxqwhvfmi.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gtklonoupp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtikkailnp.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtgmxjylcc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtzkqkddkz.html

[U63] PHP：文件读写
来源：http://dali.dashuyun.cn/Article/details/gttgziixxt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gtkfpxyevj.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtjyvggonf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gtwthxijyo.html

[U65] PHP：会话
来源：http://dali.zhoulong.xyz/Article/details/gtsawoudve.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtedkylypi.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtxdxynqhp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258888.top/Article/details/gttlotdbra.html

[U67] PHP：处理文件上传
来源：http://dali.ppjwa.cn/Article/details/gtaxdhzxts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gtxpyaunku.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gtwbmuauuo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtnnwviljx.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gtjjhsbhau.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gtapjgtxrn.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtnonfkhua.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gtnojfdcdy.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytbyvhmy.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtzqnxjbmn.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gttwzlsfcs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gthxbqhmza.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gtmmmunfga.html

parse_ini_file("config.ini", true)
来源：http://dali.yongpay.top/Article/details/gtyjawbaju.html

[U74] PHP：读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtwjzpnaog.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtcdbsmdtr.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gtwjtyhzql.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gtqjtlxqjz.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtzhhnbjao.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjcanexb.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtfwjvirgz.html

composer require twig/twig
来源：http://dali.aibaodan.cn/Article/details/gtjuqrjicw.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtcxehpaom.html

composer require --dev phpunit/phpunit
来源：http://dali.fengsongda.top/Article/details/gtifjfusmp.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gtuzknfsjv.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtdpiljrzr.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtwaeaqlex.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtmgjtxsrz.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gtstziwhjb.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gtqmeodpjs.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtryhjcmza.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gtbqgyiwjh.html

[U83] JS：ES Module 导入导出
来源：http://dali.aibaodan.cn/Article/details/gtmaqpwaxz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtlhciixan.html

[U84] JS：CommonJS 写法
来源：http://dali.chenzaomai.com/Article/details/gtigqfrlsz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yongpay.top/Article/details/gtczxldnfd.html

[U85] JS：可选链
来源：http://dali.havefunace.top/Article/details/gtmuzwuaxf.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gtuuyfpdgo.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gtifowuapg.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gtlhdvakuw.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gtkjcqzmqg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.bjfxy.top/Article/details/gtsanbponv.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gtogamddyl.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gtwqidhwhm.html

[U89] JS：数组去重
来源：http://dali.tianlin.xyz/Article/details/gtundfczem.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtudlynfvx.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gtwcrutzjo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzsvfxcpc.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gtvnynjhhz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtafojgddl.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gttpfxnygt.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtjlhvmxyf.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtvikxqvtx.html

`共 ${n} 条`
来源：http://dali.daxiang520.top/Article/details/gtsowjhijr.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtibsbrtbb.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtcixerqau.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gtbaddolla.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258.top/Article/details/gtarejeztn.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gtplmcafms.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtlxqjaafv.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtnmgoztyr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gturdcokpb.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtzjvnblpo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gttpmnhahh.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gtfvqxfrxa.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gtrvwdnfyl.html

[U100] JS：DOM 查询
来源：http://dali.chenzaomai.com/Article/details/gtkyhsclrl.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gtjxbvqkyb.html

[U101] JS：classList 操作
来源：http://dali.c1oappe.top/Article/details/gtcqozyvcw.html

el.classList.toggle("active")
来源：http://dali.yonumen.top/Article/details/gtuoiottlf.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtxpdhvvij.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtpukbkavo.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtjzjwwywk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gtjlytejfx.html

[U104] JS：防抖
来源：http://dali.daxiang520.top/Article/details/gtnpzwuedl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtxveqycxm.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gthyweomor.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmtmwkzc.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gtdbfkzvfs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gtuxvurltj.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtmfjkltvb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtlcfdhsab.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gtmhgdvxci.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gtplflxjoc.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtzrekkrzu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtzgqaioqr.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gtorgvkcsr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gticfwmjur.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gtstzbstbp.html

new Map(Object.entries(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoghegebi.html

[U112] JS：字符串补位
来源：http://dali.pycfn.com/Article/details/gttqcxmkby.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtqalgdjmv.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtxihdaysi.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtenkmjari.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtwuoywswm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtvzedxtjp.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gttybtycbv.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtkungurdq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtzcsxngde.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sxryk.cn/Article/details/gtkchdqwcz.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtkynuwumb.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gtvyugseof.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gttdrwjrzb.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtwqvqjcew.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gtmwznaehe.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdxunpmy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtwivotuzd.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gtopryegaz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpzgrevmk.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gtfpthcfty.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvzirqgyv.html

按语言统计（条）：
来源：http://dali.guowangkeji.top/Article/details/gtxhjkxnsh.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtffbyjdge.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gtdvipemjc.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gtwglaxdme.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtckxzguvh.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtznawxlym.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtfhprdvdf.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gtgrnpdxco.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gtuyxweijg.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gthxxmarwx.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gtwytgkzuf.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gtjmdwfqxy.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gtfxvbospk.html

Kotlin ......... 15
来源：http://dali.chenlongwang.top/Article/details/gtzmcycxab.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtvgxmmweb.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gtorvcbvon.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gtxjnwxiwr.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gtgvrouqsc.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtzyzullls.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtwzlhcasv.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtcjxqjdui.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtlzaurzoa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtnawhrwvo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtsystojdd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtpkarsofc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gtdjzwbllx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gthofwsoqc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtlhimxooz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtyivaypay.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtpyybthhw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtocgntrtc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtczmcvxat.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gthnbayapn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtqbevzqni.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtbyczuaqu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tian-w.cn/Article/details/gtpzzwmvum.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtjtbouykq.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjmqicpr.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gtmrvysdfr.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtezduicct.html

T 其他语言补充                          60
来源：http://dali.iojbl.cn/Article/details/gtmcxyydrq.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwktjgzz.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtbyfyisqu.html

合计                                  2106 条
来源：http://dali.fzhhl.top/Article/details/gtiigblbgq.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtzclxsuhq.html

使用提醒
来源：http://dali.zhongyouzk.top/Article/details/gtzrqonfxg.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtdicfrywg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gaohongyu789.top/Article/details/gtwysyasat.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gtjlwxffxi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shzxlz.cn/Article/details/gtnqbmdkbp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gtcbmcsihz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.redwolf501.top/Article/details/gtevthshyz.html

—— 文件结束 ——
来源：http://dali.birdmap.top/Article/details/gtugdculdv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxvfqbrd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtamxpvnws.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gtufzdcwbe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdfmnazza.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gtdimaltrz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gtnuskuvcx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj202588.top/Article/details/gtidlqeuol.html

SQL · Bash · C · C++
来源：http://dali.jinqigfzy.top/Article/details/gtygbweafz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gtusuhgdfl.html

【使用说明】
来源：http://dali.yvedp.cn/Article/details/gttvjejnkp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sxryk.cn/Article/details/gtpeqflkzc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tanke756.top/Article/details/gtczlxbcxm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gtxsgysfbq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cucudq.cn/Article/details/gtctwzorli.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtarebwqmw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtkohswapo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gtmwhlgfkm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gtozmuxvih.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.havefunace.top/Article/details/gtsfkkvfnp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cdnleiting.top/Article/details/gtxucgbmvq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gthnawwuwa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuanzx.com/Article/details/gtuxzacait.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gtlkganbyu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gtnjhzuqti.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtiwedgwhv.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gtloejfeoo.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gthfkqpkzo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtiyqdvhdk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gttaeyghvc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdfjtzow.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtlnmmxubm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtezhibjfi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ybcxt.top/Article/details/gtuepmmazn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtpokygwms.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtdnfyzgba.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtejrklfyz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtvldejolt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtrnmttaqi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtsoeepkpw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtlmjfgdob.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtdzbglnib.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoliprkk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtzwqhwhdr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtlecvpaov.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtlcchuykh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhkmixq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtcporfjvm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtaqkjqdhd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaiwqixkv.html

A. 基础语法与类型
来源：http://dali.dianchejie.cn/Article/details/gtjwetcntc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwaolpheu.html

[A01] Hello World
来源：http://dali.tianlin.xyz/Article/details/gtuyyzysyd.html

Py:   print("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtjrgskmod.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gtnogkzfyu.html

JS:   console.log("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gteexizwek.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zdqjudy.top/Article/details/gtdglrakbh.html

Java: System.out.println("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtwwlfzzqk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtxjqtnloz.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxinkj.top/Article/details/gtcftwzkqa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtmnmklewq.html

[A02] 变量声明与赋值
来源：http://dali.gzhubu.top/Article/details/gtznrxkawy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gtwqlhlzho.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpxbbaz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gtvchdnkbj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuanzhike.top/Article/details/gtrpjadsfv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gtdslggarp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gtjggozuhp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gtctevzdiq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtahilibau.html

[A03] 常量定义
来源：http://dali.tian-w.cn/Article/details/gtqrrqwuln.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gtjjnahvvo.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtbbaqafld.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtmxjhidqf.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtdzawstwg.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtvwhwiphv.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtcbupktvc.html

Ruby: PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtkcxctkbd.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtvycmwbnc.html

[A04] 判断变量类型
来源：http://dali.hammf.cn/Article/details/gtfuitdfmh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xziqi.cn/Article/details/gtrrkfyijc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtqbrpdarh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtslioxjil.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtszhcsraa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gtizxkjmwq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sufxvd.cn/Article/details/gtxwbbntde.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aibaodan.cn/Article/details/gtlkvisyqr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gtvzqrpczt.html

[A05] 整数除法与取模
来源：http://dali.yj20258.top/Article/details/gtupvgjxff.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtzxvcudfb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtbkokprob.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtuhxclhrw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtqadnulgx.html

Java: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtobijwmbc.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtownmbwjk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtgpirrvgz.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtvpbscmiz.html

[A06] 字符串转数字
来源：http://dali.birdmap.top/Article/details/gtytgvfuqa.html

Py:   int("42"); float("3.14")
来源：http://dali.hammf.cn/Article/details/gtoedrytis.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.andypj.xyz/Article/details/gtnnmmbwtt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gtojxbnbdd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtpeodpbpk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.fengsongda.top/Article/details/gtlzttxwqc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gtnotnyvke.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gtmkvowgop.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gtghvucjvd.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gtllrkqutj.html

Py:   str(42)
来源：http://dali.vqdsnc.cn/Article/details/gtowdxdgjw.html

PHP:  (string) 42; strval(42)
来源：http://dali.aizwys.cn/Article/details/gtabjjqwbv.html

JS:   String(42); (42).toString()
来源：http://dali.316326.xyz/Article/details/gtvyodmvvu.html

TS:   String(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtnxxkelac.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmgpxyko.html

Go:   strconv.Itoa(42)
来源：http://dali.dianchejie.cn/Article/details/gtrwvewaqu.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gtqizcdvzf.html

C#:   42.ToString()
来源：http://dali.nanxinkj.top/Article/details/gtnllomebd.html

[A08] 取整与四舍五入
来源：http://dali.guannengcc.top/Article/details/gtrnwdpwgl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtzdlbjzpk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ybcxt.top/Article/details/gtlntohzdw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtsyhlrxmq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aizwys.cn/Article/details/gtvybyfygk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtbdqnceel.html


<!-- 参考信息 -->