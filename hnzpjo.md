代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtpilicvtv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gtbvygpnms.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtnxzusweq.html

f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtipemhzux.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gtawznikrm.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtksekhmmi.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtrufdlaup.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gtqsvykjro.html

[U59] PHP：自定义排序
来源：http://dali.hammf.cn/Article/details/gtqtkfoytf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtoaxwuycd.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtgrrgcbyr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gtzeocncfs.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtxbpcvvcn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gttwvpgzrf.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtokkyjnnp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvsmtydc.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtcnckaqrj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gtjcttibsr.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gtbfkoaxmv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gtdzohtrdx.html

[U65] PHP：会话
来源：http://dali.snrcjt.cn/Article/details/gtdqnzskbe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gturzsrmgp.html

[U66] PHP：设置 Cookie
来源：http://dali.hysaishi.cn/Article/details/gtaumflkvr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yueranfly.top/Article/details/gtkdttznio.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtnkdmvzja.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtbrrvkcig.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gtkhekhiye.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jlsjyb.cn/Article/details/gtsiqwrpgu.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtqprxeclh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gtkgfkhvap.html

[U70] PHP：PDO 事务
来源：http://dali.zhiwuduotai.top/Article/details/gturokoqbi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgytfpjs.html

[U71] PHP：抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtiloousfh.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gtrvgegrlh.html

[U72] PHP：写错误日志
来源：http://dali.iojbl.cn/Article/details/gttoiohtdv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gtwovnkczs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gtjvzfrvqy.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gtogvetcve.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtpftdkqvi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gtdhdkusqx.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtdrlgxjzu.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtwkylmjjw.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gtvnueftil.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gthivjvnwk.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gtnxkgkaam.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gtkojcpyov.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gtsqmsxymc.html

composer require --dev phpunit/phpunit
来源：http://dali.fengsongda.top/Article/details/gtzgnzyevq.html

[U79] PHP：静态分析
来源：http://dali.jqgufenzy.top/Article/details/gtoexrpqeb.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtnzrwszcj.html

[U80] PHP：代码规范修复
来源：http://dali.0kj1m.cn/Article/details/gtzvtbjlge.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.quarkkingdee.top/Article/details/gtsrfbtlxh.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtnuibtiqg.html

npm init -y;  npm i express
来源：http://dali.daxiang520.top/Article/details/gtaimfowyh.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gtgrbesthz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhixingplan.top/Article/details/gtteqdmwea.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtuttdzkkg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtrriecodx.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gtvgkhtqxn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gtzmngaard.html

[U85] JS：可选链
来源：http://dali.xuetiantiany.cn/Article/details/gttnvcuqon.html

a?.b?.c
来源：http://dali.hywenlv.cn/Article/details/gtjdqtlela.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gteqnuknnm.html

a ?? b
来源：http://dali.guannengcc.top/Article/details/gtvnqgnumm.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtirbojnrm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtlrjhlzav.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtibfmvcqu.html

{ ...a, ...b }
来源：http://dali.ehwqpu.com/Article/details/gtphgpmumt.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gtvdaiwqkp.html

[...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtxwjohoia.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtltqzcded.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtwvludncy.html

[U91] JS：对象键值遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtkngwunzv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gtbgkbowmi.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtdodxgdip.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtmdiaysmj.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gtsdpfkkky.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtsdyrzxio.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtzwligpwe.html

const double = x => x * 2;
来源：http://dali.hywenlv.cn/Article/details/gtvmyqthub.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtkkfbdhij.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gttomuhwne.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtjhcyoohg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtusbwpgro.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtxlcfryjl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtwrbfpvqr.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtpwbhntrv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxinkj.top/Article/details/gtsivmetfr.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtgjsgicgj.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gtdjcxusfo.html

[U100] JS：DOM 查询
来源：http://dali.shangyingyoupin.top/Article/details/gtchryxpqk.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtnldechkg.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtlywmqcmk.html

el.classList.toggle("active")
来源：http://dali.aizwys.cn/Article/details/gtskyrrynq.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gteetwxupr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtbkuxhvri.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtyxwmudkm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gtruxuhpxq.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gtlxsoxike.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtvtjwcsjn.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtfdmxbcvf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtvebxqnte.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtukrjmfeb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtblzgvifr.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtrcbspezj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtxwtytkac.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gtzjobpycj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtszeelffk.html

[U109] JS：数组分组
来源：http://dali.guannengcc.top/Article/details/gtgmqmhxjw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtwkrmacpb.html

[U110] JS：数组分块
来源：http://dali.xziqi.cn/Article/details/gtthebzcfk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtcuwbtsml.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtmklnniqk.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtwqzgancy.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtnduvghxk.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtitygmebb.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtqwlrnafl.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtdgosclcc.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtvdereqrg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtaovecdii.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtauttvaoz.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtmzgmrqkn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xylfe.cn/Article/details/gtkvuyitwe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gttzgnuoqr.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtdddlogad.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gtkpjrvafm.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtksedndez.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gtiuacnvya.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gttymqknku.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsotbdtdz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gthgpnrruo.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gttuaxbkcn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttbidfedg.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gtuabyqxcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcynwwdqw.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gtguwbitva.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gthooikcie.html

PHP ............ 252
来源：http://dali.cqqwz.cn/Article/details/gtrkgzwegu.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gtpzbggrft.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtumfktwkg.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtuexvkbis.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gtwilxunev.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gtfvlhqewl.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gthwklvxod.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gttzenoatx.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtgvaovsyd.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtygemjzxs.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gtcckvjdbv.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gtofzgusmf.html

Swift .......... 15
来源：http://dali.aibaodan.cn/Article/details/gtymexgaes.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gtqxxjctpn.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtpvilimtj.html

Scala .......... 10
来源：http://dali.jqgufenzy.top/Article/details/gtjmtazoqy.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gttxlhwael.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gtkctqgyso.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtcboqpiul.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtxozndvef.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtnlktnjkq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcntlukx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtgyvkmpri.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gtmbveskor.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gtuzmaxhda.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtrodwmzox.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtgmdrecpz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gttzvvphxb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhjqxwzz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxpjpkjv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtbgamqoei.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtowhoewuo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtnmbrixka.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shangyingyoupin.top/Article/details/gtvqcicbkf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtvwnxvmzz.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gthnvcljzr.html

R Bash 专题                             80
来源：http://dali.meibo888.top/Article/details/gtxteqiqgc.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtuxokpale.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gttmhdawdq.html

U 高频实用片段                         120
来源：http://dali.xylfe.cn/Article/details/gtvcpdpebp.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtbyhhdhtn.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtfwsdgeii.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtyhdtkpkl.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gtaielvdqh.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtadthjkae.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtjyqqwrom.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtxfnzglet.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shzxlz.cn/Article/details/gtcqhkgsiw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gtgpwcdjbw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gtwgznbxhl.html

—— 文件结束 ——
来源：http://dali.tianlin.xyz/Article/details/gtfmwrwjle.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrjffiget.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtpznvxmqw.html

Common Programming Examples Cheat Book
来源：http://dali.hnqzz.top/Article/details/gtxvkfsrka.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiutmejsy.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gthiilbirl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gtbxgzvvyc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gtsgrqrwiu.html

SQL · Bash · C · C++
来源：http://dali.ppjwa.cn/Article/details/gtuapsrocn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhengqikj.top/Article/details/gtxrkqgbdy.html

【使用说明】
来源：http://dali.316326.xyz/Article/details/gtukfzmhwn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gtvykhzlmw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtstzgvigs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gtnrbqxbmt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihjunjtx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ybcxt.top/Article/details/gtfxtlxele.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgdwmlxl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gtabnjjuyk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtpgnfzsce.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxinkj.top/Article/details/gtumfuzkhk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zdqjudy.top/Article/details/gtmrxnllnf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sweek.top/Article/details/gtykwkdtvx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpblaaao.html

【文件统计】
来源：http://dali.shuidangran.top/Article/details/gtlxmxuilo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cqqwz.cn/Article/details/gtwcnbxmmc.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtmgivzyyg.html

目  录
来源：http://dali.316326.xyz/Article/details/gtcsnemblv.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtimzxrifa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtoefxqzad.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtqkjetrld.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtcmfkjanm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtfwkkzlov.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtecdxkkzg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtefahkhti.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtgnzekgtr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtzquccctg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphvavwxl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtfyqmxfxp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtjvvrdxrl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtpkgfbcll.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtvnqwhhvh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtvutsnamn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.bjfxy.top/Article/details/gtnubrquei.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtvfkiojbr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gteifohdtz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtumcwwhjz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xylfe.cn/Article/details/gtlodwgvqo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtqplyyaal.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gthxiuihfv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbfzumjry.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gtbleotwar.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrzcwbqqn.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtjwttvruc.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtvoamkfrw.html

PHP:  echo "Hello, World!";
来源：http://dali.wangshuangyany.cn/Article/details/gtcqrtkquj.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtzyyxwadf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtpbggebrh.html

Java: System.out.println("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtlkykrirl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtluyynzmu.html

Ruby: puts "Hello, World!"
来源：http://dali.wangdashe.top/Article/details/gtekvovshq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtrdmvtlyf.html

[A02] 变量声明与赋值
来源：http://dali.smart0.xyz/Article/details/gtpavlxccl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gtiqagrjmo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtlyedmkyp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258.top/Article/details/gtpzvxrcyb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtpvugcgmk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtpzczutyp.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gtmmplxpna.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sxryk.cn/Article/details/gttnoqvtwf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtsyqikrqp.html

[A03] 常量定义
来源：http://dali.316326.xyz/Article/details/gtsrktpijp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guowangkeji.top/Article/details/gtztltisjh.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtldrsjxcr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtdsxuzfxc.html

TS:   const PI: number = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtvfviktgz.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtbgsmeieu.html

Go:   const PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxxjcjgq.html

Ruby: PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gtdhqcyrvq.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtlfvuwdak.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gtoeaypcnj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuetiantiany.cn/Article/details/gtbtvinbxr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtnefftlhe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtvyhdsvhr.html

TS:   typeof x; x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtdhvvyads.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gttvxhddiz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj202588.top/Article/details/gtkeisznxx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangdashe.top/Article/details/gtigfakwhi.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtjpohgfdp.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gteflhtnck.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gtovssqioj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtmlvhpdxo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtiofosoxu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtmxptohmk.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtpqvpwdgv.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtsynkyxhq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtoqiozgdu.html

C#:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtqapjyagp.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtiylkgmeb.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtzamupvoc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gtjjiajorq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtsnxikxvq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtypxlozgd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtqlipazkb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gtglciuabj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aizwys.cn/Article/details/gtlkhwnmrk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sysykeji.top/Article/details/gtbfwcfadn.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjcrkgpd.html

Py:   str(42)
来源：http://dali.zdqjudy.top/Article/details/gtuvahyzuw.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gtygoqhykq.html

JS:   String(42); (42).toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtrjojenxt.html

TS:   String(42)
来源：http://dali.jinqigufen.top/Article/details/gtdfgcsfps.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gtvbefkkke.html

Go:   strconv.Itoa(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwrgdbjh.html


<!-- 参考信息 -->