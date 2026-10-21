代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtawhouoqk.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gtznqgvrgl.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gtgxjzyauq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gtgpwxvpdh.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gthewnyrdg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtjdrcqwtz.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gtygvluejt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gtqijqhkcr.html

[U61] PHP：正则
来源：http://dali.zhongyouzk.top/Article/details/gtxpnjdezi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtkiytywvu.html

[U62] PHP：日期对象
来源：http://dali.cucudq.cn/Article/details/gtugislklp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hywenlv.cn/Article/details/gtluxkxfbc.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gteljvfety.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfnwhdqs.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtrzvlcfww.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yueranfly.top/Article/details/gtjwhyoulm.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtvppwsdjz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtjlflnrvf.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gtztiqfdzk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gttklxsmrj.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gttprgmobl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cucudq.cn/Article/details/gtghnwmggk.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gteyysvcxf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nwbrower.top/Article/details/gtrfhspaul.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gtcdnszqvi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygvxsjsz.html

[U70] PHP：PDO 事务
来源：http://dali.havefunace.top/Article/details/gtpkmuthdj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gtorlayymt.html

[U71] PHP：抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtffexzwnr.html

throw new RuntimeException("失败", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjtdtxcm.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gtcpvefhul.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtkcdmzpvi.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtizfludxe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhoulong.xyz/Article/details/gtrmnsokxu.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtzfjfkwkw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gtyegnsgir.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtnaizdayh.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gteobaqfub.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapakkmcq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gthhxuzyvu.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtektdlimn.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gtszrgdlqx.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gtqxeeweqw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gtcbsnuaua.html

[U79] PHP：静态分析
来源：http://dali.snrcjt.cn/Article/details/gthekiuonn.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gtopygibby.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gtiykodhuf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtfrwvzhbj.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gtpqkadbet.html

npm init -y;  npm i express
来源：http://dali.jyoumei.cn/Article/details/gtcqjqjcrd.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gttwqkefvz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gtlpwixlaq.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtuqcabhxi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtzsvppndw.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gtcvxobrrl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gtplfeaqnb.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevtuogcl.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gtchkzabhr.html

[U86] JS：空值合并
来源：http://dali.nwbrower.top/Article/details/gtjanrlibf.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gtwjdyykdx.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gtvmfdcjmv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gtrrwcknct.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gttcxbsaof.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gtpheimlcs.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtpaiwdomi.html

[...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtfewdovuf.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gtrfvfzjct.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtaljulcxn.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gthtoxjktj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gtvmditybx.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtmeegibqc.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtjkeixqgb.html

[U93] JS：模板字符串
来源：http://dali.sysykeji.top/Article/details/gtqzxipxpl.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtzsjgvswj.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gtspylbgpu.html

const double = x => x * 2;
来源：http://dali.yonumen.top/Article/details/gtkybuubqr.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gtbvhtmxtb.html

new Promise((resolve, reject) => {})
来源：http://dali.ybcxt.top/Article/details/gthgzdmart.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gtgxbbazlh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtwdsvekig.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gtagiajmqo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtnjavlvon.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gtrchfefxp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gzhubu.top/Article/details/gtgicwxugb.html

[U99] JS：事件监听
来源：http://dali.hysaishi.cn/Article/details/gtgasjwgom.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtocahxojq.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gtiphykmeq.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gttsejmfvd.html

[U101] JS：classList 操作
来源：http://dali.tian-w.cn/Article/details/gtbhqmejdw.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gtdzoxxsxw.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtvegkohdd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gtqxsfajwx.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gttvqjnpvd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gttjdxjopp.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gthyvvniua.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtdpnfndda.html

[U105] JS：节流
来源：http://dali.wangshuangyany.cn/Article/details/gtftwiwcms.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gteafynlfm.html

[U106] JS：日期格式化
来源：http://dali.shuidangran.top/Article/details/gtjmtfcnxo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtfaiwirhb.html

[U107] JS：数字千分位
来源：http://dali.sysykeji.top/Article/details/gttzookdbt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtjfixlpxc.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gtiuvqncwt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtkmkviiub.html

[U109] JS：数组分组
来源：http://dali.yueranfly.top/Article/details/gtfofwdpas.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtjgodgtko.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gticaemssd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtnvflgdoh.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gtewlhhosf.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gtnxswfcyn.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtbmsgkrij.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gttmpzxahb.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtwqmoxvme.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gthhfcvhkj.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtqgxrinwp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtjexkfxhr.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtbxawhegf.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtksqavaya.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtyubfqofd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gttlxilkie.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtghleuacw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gtjxjabimp.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtoubqpvib.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtvsalqtul.html

[U119] JS：生产构建
来源：http://dali.shuidangran.top/Article/details/gtkwhhvmwi.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gtgujbwbjn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtojlbecnj.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gtfnvzquoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthaylwfgw.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtapazfoeu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuomtpmcl.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtaoszyuik.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtdwrtaptg.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtgjmlxcny.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtcmykywhn.html

TypeScript ..... 212
来源：http://dali.yj20258.top/Article/details/gtblenuyuq.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtbtkoxusv.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtblhfltrl.html

Ruby ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtnuvgksij.html

C# ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtzkqvjvyo.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gtajdouskk.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gtskrwvxjr.html

SQL ............ 90
来源：http://dali.shuidangran.top/Article/details/gtifpavqfw.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtghmxudkm.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtvwwupsjg.html

Swift .......... 15
来源：http://dali.snrcjt.cn/Article/details/gtnglrhmuz.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gtwotzvyxk.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtcpbszlok.html

Scala .......... 10
来源：http://dali.shuidangran.top/Article/details/gtmvissyme.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtlobjpamn.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gtqpvdpkns.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gtstryyevk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtemjjfhhg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoeufwdl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtezebdjac.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtddgimfni.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gtgpcozfah.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtddryzzet.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gteapngtrf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtldbckokt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtszajfjlm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtufhtndho.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtnvqcsigl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtlciuphlv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gthyvkolrc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtubuzvnww.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sufxvd.cn/Article/details/gtvrooojcb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtfwlehhht.html

Q SQL 专题                              90
来源：http://dali.zhongyouzk.top/Article/details/gtjprxxukz.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtovctkcss.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtrizygvye.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gtxzphnzpr.html

U 高频实用片段                         120
来源：http://dali.jinqigufen.top/Article/details/gtxuhdczpt.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtgcplfqdl.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtlardlhcp.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtdfocymxh.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtdtynkzbr.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtrlgwmsxv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gtjrzlowix.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fzhhl.top/Article/details/gtfmrcufkh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gtqnqhijpd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gtvgbtvntk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpvufuzb.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtfxfyhwuy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmlaeuitp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbmuryyl.html

Common Programming Examples Cheat Book
来源：http://dali.jlsjyb.cn/Article/details/gtrhtnfnjw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtomwgyrhb.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gtlclnufwb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gtbkvgwelw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtcyxqokbb.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gtwdepjxgr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.svipenyu.cn/Article/details/gthoivnghd.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gtiybakhcj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gthjwnolop.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj202588.top/Article/details/gtbkdjlyjm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gtxeiccoxa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gtdmrcmdrp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fengsongda.top/Article/details/gtktvujmpl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtlcizdwue.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gtpcsihttq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhoulong.xyz/Article/details/gtorckaqof.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nwbrower.top/Article/details/gtohnywvpm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gtzbhmjpne.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gtnfqvblkc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xziqi.cn/Article/details/gttcwfzksh.html

【文件统计】
来源：http://dali.sweek.top/Article/details/gtwafpgosd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gtvuqncoiu.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gthjqevosm.html

目  录
来源：http://dali.andypj.xyz/Article/details/gtesaeapoi.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtqighbepo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtqqrnvwdc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtigfdorjl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqiaciis.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtsolfbegn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yanxiufei.cn/Article/details/gtllvfkywz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtucjpaalt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtxmdzohgh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtuwzmcvzd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtlxtctkkt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gteoakosvv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtrjetwpyw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtmonzzuzp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtdlqnxdsb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gtqfzruvxy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gthsdirszl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtuqccpfxd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fzhhl.top/Article/details/gttpahusjd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gtouzrkbeb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtlxrozexs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtcckzxewm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtzvmfgyqc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxcyrgeql.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtfguelwgk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtodjjqpbk.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gttghgzpov.html

Py:   print("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gtezexstgi.html

PHP:  echo "Hello, World!";
来源：http://dali.hammf.cn/Article/details/gtsoandnuo.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtwsxiuaun.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gtqzgngpat.html

Java: System.out.println("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtiwoyited.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcgitfpb.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gtrxxzitjb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtxssntszp.html

[A02] 变量声明与赋值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtealzkzlq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guannengcc.top/Article/details/gtgcvucdnj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cashguo.top/Article/details/gtofneibnx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtyafmnsra.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gtdwqhtfnv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtgzforxiu.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gtvktxcghm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhengqikj.top/Article/details/gtwwcckseu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtckucvxsy.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtdjdstkcw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nwbrower.top/Article/details/gtkvqajejm.html

PHP:  const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtttonbifj.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtxfvdeeay.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtgqxgniyv.html

Java: static final double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtwiqqiqdv.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtyydbseub.html

Ruby: PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gttsaralqs.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtcevthfhj.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gtxcqdghim.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gtwxdhywzo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gtdpixajpy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtcyoyryfy.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtrpuhjdoc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gtgwbjklak.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gtiywjaayk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gtkvojqluj.html

C#:   x.GetType().Name; x is int
来源：http://dali.0kj1m.cn/Article/details/gtrthxisdb.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gtcvftdwxo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigufen.top/Article/details/gtdyebvcdl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtfpduvsgf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gthflsldqn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtvxnghsxm.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtiguphqfw.html

Go:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtcmagruaz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtasoopdem.html

C#:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtbyokqjpi.html

[A06] 字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtdhrpwjzr.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gtmkjhggkk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.meibo888.top/Article/details/gtkpsmqbar.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtybgnrezm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtsnenkcri.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtgotwpznj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xuanzx.com/Article/details/gtzcneubwz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gtipqynxlg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtbjzqqmok.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gtxcpofwzv.html

Py:   str(42)
来源：http://dali.yuanzhike.top/Article/details/gtnsrahdde.html

PHP:  (string) 42; strval(42)
来源：http://dali.hywenlv.cn/Article/details/gtaskrqzee.html

JS:   String(42); (42).toString()
来源：http://dali.nanxinkj.top/Article/details/gtwlgcvuic.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gtczluqxns.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctcuwqeb.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gtbexvfxkg.html

Ruby: 42.to_s
来源：http://dali.smart0.xyz/Article/details/gtfbdegkyo.html

C#:   42.ToString()
来源：http://dali.c1oappe.top/Article/details/gtnpsuplom.html

[A08] 取整与四舍五入
来源：http://dali.nanxinkj.top/Article/details/gtqxsqkvrr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtwbcccuba.html


<!-- 参考信息 -->