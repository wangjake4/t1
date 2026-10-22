代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtdvbgegzl.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gtimvdzzuj.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gtudtxdnzo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtbttzruvm.html

[U59] PHP：自定义排序
来源：http://dali.chenlongwang.top/Article/details/gtcqxrqesd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtwzdowtts.html

[U60] PHP：JSON 编解码
来源：http://dali.gaohongyu789.top/Article/details/gtnsrogkso.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gtjslibbky.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gtcxqltaop.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtczzdpsxv.html

[U62] PHP：日期对象
来源：http://dali.xuetiantiany.cn/Article/details/gtaplecypk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gtnnyiwguf.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtymqzeokj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gtuyltgqzl.html

[U64] PHP：目录遍历
来源：http://dali.jqgufenzy.top/Article/details/gtudgiwisy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ehwqpu.com/Article/details/gtraammbxo.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtgaldvutq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gttrtrlxwu.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gtjuxjhkto.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtpmbnztxj.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gtaodnawct.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gtnkluqnei.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gtzisgpuea.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtebrzeqrz.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gtwrgruwrz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtyyrtrpsb.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gtierfnulm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gthcjhbifn.html

[U71] PHP：抛出异常
来源：http://dali.yonumen.top/Article/details/gtwpddyidc.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtsgbwhjuk.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcrqlzmq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gtdcoemljq.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gtrdxmokiz.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gtyomeqkud.html

[U74] PHP：读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtgdckclxi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gtqzmngtsb.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtmuwkajpp.html

composer require psr/container
来源：http://dali.guowangkeji.top/Article/details/gtpmpfrklo.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gtwreqweuo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gtfbgwvurn.html

[U77] PHP：模板渲染
来源：http://dali.hysaishi.cn/Article/details/gtdsusxtvn.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtudqfwtfh.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gtspauizhj.html

composer require --dev phpunit/phpunit
来源：http://dali.cqqwz.cn/Article/details/gtmkdpogtm.html

[U79] PHP：静态分析
来源：http://dali.havefunace.top/Article/details/gtcmbijttx.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigufen.top/Article/details/gtprygwbxh.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gtiwhzbjbo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gtbkcjvsye.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtvtyhzkqq.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtkgqerhfa.html

[U82] JS：package.json 脚本
来源：http://dali.jianghu66.top/Article/details/gtoiwlzinb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daxiang520.top/Article/details/gtsnqgqmrw.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenzaomai.com/Article/details/gtxrupllct.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtiekcgjnv.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtarjsifnq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxfqkxjc.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtxfsrscfz.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gtzwevzmkc.html

[U86] JS：空值合并
来源：http://dali.cucudq.cn/Article/details/gtaxelbqrm.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtrxmlrrng.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtloturhld.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gtmjjqvzuc.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gtuhtfxyke.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gtmlfavkye.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gtufaqljed.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtakdyhgve.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gtaplefejy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtsdaoffbk.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gtfoofhnjz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gteciljrdd.html

[U92] JS：深拷贝
来源：http://dali.snrcjt.cn/Article/details/gtaelxygfl.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtmavwgidd.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gtuvdeplma.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gtkqkgoqxo.html

[U94] JS：箭头函数
来源：http://dali.ybcxt.top/Article/details/gteqlualsd.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtsfuhwjgg.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtimalhgir.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gtlswxrnpg.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gttfqxzwja.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtjbnxeeif.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtrppirvea.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gttkrdkdbh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtawzgubcp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yueranfly.top/Article/details/gthsvznfoi.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gtcxbqywsj.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gtjldtlgmy.html

[U100] JS：DOM 查询
来源：http://dali.316326.xyz/Article/details/gtupwegcen.html

document.querySelector(".item")
来源：http://dali.ydzc1.top/Article/details/gtfhdiwcqt.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gtbilepgcq.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxgfbjkj.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gtsdegwkxs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jiagoushi.top/Article/details/gtvjymoybr.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gtxdnspgji.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtwlqgkfof.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtuwppizun.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibgeahjm.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gtxhgpkhvt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzdlwwgd.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtibhzhozz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtqjdnnnic.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtacwmfnhu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupbnucmn.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtddjmcvpt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtqbqltkhs.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtxfazcaaj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtzlhlljbn.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gtlsgfawhr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daxiang520.top/Article/details/gtobrcpzgp.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtydbtydfz.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtdkrjztyc.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gttxiwfbkj.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtcpuombuk.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gtckldznot.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtrbmupxry.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtvziylkse.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtafuprjae.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtunafligk.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtuqfpuoxd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gtspvfccyo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gtzsnzzvzn.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtjwcicujt.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gtuhzyebdp.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gtkrmgtjhm.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gtyjtnybqu.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gtdeialwhh.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtmymiflme.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gttvhquvyl.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtxnptszxu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcvhcxhts.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gtmknhjhaw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttjqcnufq.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtkrojameq.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gtfstohkqy.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gtervxsamd.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxixsvyza.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtnhpjsvin.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtnrqywgax.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtkggbfqhh.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtlcdzwqah.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gtpijixahb.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gtcbgbzelg.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gtdgcbwvtk.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtsxjcxerv.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gtjrvidhdl.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gtnrdjbdyu.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtcmnnxiuj.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtangukdln.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmztqrgjv.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtonnggnii.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtsfaagzwp.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtzofokkku.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtvxjkzmny.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gthwwpcjje.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtqbexwctn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtcbltqiex.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtkdgjocjo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtcguwcmqx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtzcbgryld.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtywfivflc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtfpawcucd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtfcyvddeu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtfjbpfhbh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtvsxjtjcp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtqikkzwmw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtqomgyyqe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtjoqtkdqo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jianghu66.top/Article/details/gttzhkcrlo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtqygmrpfl.html

Q SQL 专题                              90
来源：http://dali.aizwys.cn/Article/details/gtsdqgtbjd.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gtgxkzbdsv.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gtbsuznfox.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gtlnshdaev.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gtietpsyfm.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtsecoleqq.html

合计                                  2106 条
来源：http://dali.cashguo.top/Article/details/gtogkrlpxs.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtkyqcbxvb.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtwgtabrlj.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtsqzvroxa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gtloywsxsg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shzxlz.cn/Article/details/gtlozfdeth.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtphxflnvd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dianchejie.cn/Article/details/gtduporhms.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.9152youxi.cn/Article/details/gtkihobwgh.html

—— 文件结束 ——
来源：http://dali.ybcxt.top/Article/details/gthhjnwgfh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkdhkydz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yangfankeji.com/Article/details/gtjaiequfn.html

Common Programming Examples Cheat Book
来源：http://dali.xinyue.icu/Article/details/gtclxxwlgm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtunvxrkgc.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gtsgetnkvs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.iojbl.cn/Article/details/gtvrrqobkj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtqfwymgac.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gtgrrwdmoe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gtvwdhvkfr.html

【使用说明】
来源：http://dali.jianghu66.top/Article/details/gtdlnnpqzi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gtjfauzqgh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shangyingyoupin.top/Article/details/gttnfeuyvn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigufen.top/Article/details/gtadbjcaoj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xziqi.cn/Article/details/gtpsulxgli.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gtzttsiwzi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gtvfcqitva.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgufenzy.top/Article/details/gtdvblmfxv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gtvyvbuvap.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aibaodan.cn/Article/details/gturmgdcfb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gtyleiaxog.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtufttduun.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jyoumei.cn/Article/details/gtkedulgdq.html

【文件统计】
来源：http://dali.hongshengwenyu.top/Article/details/gtieodmmsu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gttnexhnor.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtczyntqli.html

目  录
来源：http://dali.xinyue.icu/Article/details/gtkxwnatxn.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gthgjhzpyv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtjbriahfa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtpzlmguag.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtpxbsuamw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gthefvibxn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtmvrzkwqd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtjijnoznj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gthofmrbiw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtlmetkucl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtksplqxfj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtndmowzbb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtgdmdfuxi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gthkpdsdkq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtdjftmcvz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtvrpfrkoy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gtthvkqstc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtgvrevoaf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gtwosmyvjy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnlxpshx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlwvesrf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtwqdiumgf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtzccrfqpn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteflikcye.html

A. 基础语法与类型
来源：http://dali.zhengqikj.top/Article/details/gtgnjnzibo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkaqcfiis.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtenwpgfuo.html

Py:   print("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gtqouqxhmi.html

PHP:  echo "Hello, World!";
来源：http://dali.pengpengdd.cyou/Article/details/gtksdkpxvz.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtfbtevasf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtcuwilicf.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtqhbkuxle.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtixwjwyyr.html

Ruby: puts "Hello, World!"
来源：http://dali.chenjidiqi.icu/Article/details/gtectffsww.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtfznqymyy.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gtdvumfenb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhengqikj.top/Article/details/gtjgzgeohi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtbtcxintp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gttisctdnq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtqdrgzywt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtjrfmnngq.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gtgutzpxjh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gtaosdiqei.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtjslkuaat.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtuhqbtlvn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sysykeji.top/Article/details/gtclcrfogb.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtigcpvlkz.html

JS:   const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtppkxnrng.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gthelikjzc.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gteymywzqn.html

Go:   const PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gtjiwjcpgx.html

Ruby: PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gtxfycdgqv.html

C#:   const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtjrhvycdc.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtdkuycdto.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxinkj.top/Article/details/gtalzgkesr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gtkpypibgh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtjbbnzikj.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibuerkix.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dashuyun.cn/Article/details/gtyvsvjxyl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtqczkhjbl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gtotsoiwgj.html

C#:   x.GetType().Name; x is int
来源：http://dali.nanxinkj.top/Article/details/gtoedgglbn.html

[A05] 整数除法与取模
来源：http://dali.yueranfly.top/Article/details/gtjjatfkym.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenjidiqi.icu/Article/details/gtluifikno.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtvxmbclbo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtbyjsnzyj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtywikkshg.html

Java: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaulbiwxx.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtbseznbag.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtotsfoeod.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtukynblqt.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtijobslaa.html

Py:   int("42"); float("3.14")
来源：http://dali.yangfankeji.com/Article/details/gtucigmchw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xylfe.cn/Article/details/gttdczikbb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiphknujm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.smart0.xyz/Article/details/gtsbzywvvx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtaygggcku.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtqsqktrgb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.iojbl.cn/Article/details/gttucspfyn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gttuqfpemy.html

[A07] 数字转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqljkmice.html

Py:   str(42)
来源：http://dali.jqgfzy.top/Article/details/gtotjsjfrs.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gthkddbefm.html

JS:   String(42); (42).toString()
来源：http://dali.cheryme.top/Article/details/gtpkhngnzd.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gthpagrxso.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.0kj1m.cn/Article/details/gttlukkhmt.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gtelpazlbz.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gtlnatpebg.html

C#:   42.ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtdukvsovz.html

[A08] 取整与四舍五入
来源：http://dali.mhx1999.top/Article/details/gtlwzklhvt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtxtnztxgc.html


<!-- 参考信息 -->