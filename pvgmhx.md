代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtknufjkcm.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gthylmnyqb.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gtihflwnqy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtgjlzrycz.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtbqefxxlc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtysxjalpy.html

[U60] PHP：JSON 编解码
来源：http://dali.shuidangran.top/Article/details/gtnqmrdiqv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gtibvoidcj.html

[U61] PHP：正则
来源：http://dali.yj202588.top/Article/details/gtjfwtsscy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gthxztrrrn.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gtponljcid.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gtzbmsnqct.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gttphshrti.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.smart0.xyz/Article/details/gtoeqbsskf.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtadjknkxj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gtsfkbtxtt.html

[U65] PHP：会话
来源：http://dali.yangfankeji.com/Article/details/gtxkdcimnk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hammf.cn/Article/details/gtighmaqra.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtfjfjiosd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gtnourulsb.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtxxemmfah.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gtfhopjsxd.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gtplwahulm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gttmwxmclf.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtwdfjttmo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tian-w.cn/Article/details/gtftkrnbxi.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gtgmeeqbvu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daria6918.cn/Article/details/gtysszlbah.html

[U71] PHP：抛出异常
来源：http://dali.nwbrower.top/Article/details/gtljvnhvwr.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gtaffyrvkm.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtbqfpdlaq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tianlin.xyz/Article/details/gtusmownlh.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtfgyvvkgm.html

parse_ini_file("config.ini", true)
来源：http://dali.havefunace.top/Article/details/gtqfquiwjc.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gtjfohovfr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtnpkdiqtv.html

[U75] PHP：依赖注入
来源：http://dali.tianlin.xyz/Article/details/gtulradtdz.html

composer require psr/container
来源：http://dali.mhx1999.top/Article/details/gtryxzrzuj.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtaxnrsoby.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sxryk.cn/Article/details/gtqknouadb.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gtmqswzlis.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtbxhgjyvj.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilgnsezj.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gteddtsydw.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gtsdfpwbzk.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtlbasldfd.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmexkjuea.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gtdaqiavab.html

[U81] JS：初始化项目
来源：http://dali.sxryk.cn/Article/details/gtudlidgck.html

npm init -y;  npm i express
来源：http://dali.hongshengwenyu.top/Article/details/gtmmknieis.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gtdvgwbftg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gtosqgekvm.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gtnxvgqrbo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtfjyoyfhz.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gtxzvwjdkc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gtuewtralb.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gtloduaoox.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gtskheaioq.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtuemjixkv.html

a ?? b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgyrziri.html

[U87] JS：解构默认值
来源：http://dali.cashguo.top/Article/details/gtrfrzfzzg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gttzgtpsww.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gtooawftgo.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gtqjasxrsy.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gthugldvzn.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtcseijzfl.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtwwljufzx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtdcmlaonf.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfkklcnu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cqqwz.cn/Article/details/gttxphvobe.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtfjrmahod.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtfqihvbly.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gteieywdlq.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtkcvqikui.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrtomlkfc.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gtpzqrpxwy.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtwpybpafr.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gtdhzfuaqb.html

[U96] JS：async/await 与异常
来源：http://dali.jianghu66.top/Article/details/gtclyajnmq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtxzaamltv.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gtdzckxbnu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtvyqovivl.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtgafotffb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gttsdveifc.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtmrcdimwb.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gtkhxcmilz.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gtebxfhumk.html

document.querySelector(".item")
来源：http://dali.shzxlz.cn/Article/details/gtjfsuvlaq.html

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gtzwlpqdko.html

el.classList.toggle("active")
来源：http://dali.guannengcc.top/Article/details/gtwlpfhrjl.html

[U102] JS：本地存储
来源：http://dali.gogol.net.cn/Article/details/gtpwedjaul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhixingplan.top/Article/details/gtknrfafra.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gtkwcqmvbr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shangyingyoupin.top/Article/details/gteonznyvd.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtxkotcggb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtaucqfiil.html

[U105] JS：节流
来源：http://dali.guannengcc.top/Article/details/gtscedtzzi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtkerwmwsw.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtixqkzbys.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtnbkvzsjt.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gtoaimoeqy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtpugsmfrp.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtdutblbem.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtmmhhmnub.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gtebdmoqtn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtvvbmqtpm.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gtzyayfqli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gtjatgjnxl.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtjffdlrbt.html

new Map(Object.entries(obj))
来源：http://dali.nanxinkj.top/Article/details/gtfmzvhcil.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtxhcfuusn.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtewuvzgbe.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gtpiwpxnoo.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtfpxnfcvc.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtbtskgtrt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gttwqbjfbv.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtabpeqlrj.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtbwviwgde.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtphdejnex.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtedsppgyj.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gtpaaxfsht.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtdxlavunh.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtoygvtqhp.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtlzmxniki.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gtepsfshmc.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtjsksiobu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ivvv.top/Article/details/gtckmmpryz.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gtpbdmogri.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzrmigmtj.html

统计汇总
来源：http://dali.xuanzx.com/Article/details/gtaqucfbvd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gteoxgkqcx.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtclihyqvi.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gtziptnbzm.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gtlsyaancx.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gttdxfubpv.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gtdixutxtg.html

Java ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtzmbvexmq.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtphrkkhws.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gtexigjcsu.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtptrrhjca.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gtkcinjfoq.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtrjdwmsuc.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtsdclojbu.html

Bash ........... 80
来源：http://dali.yvedp.cn/Article/details/gtvorcuazv.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtcxonunvv.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gtsxlutoum.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gteapezkwc.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gtqurdjhgb.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtxfiempyv.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtbfkflona.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtfwaubalm.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gtwfwycwwg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtmibqpkhp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtjnajqwjd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtfteuomhp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtzgnvwour.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gthxyorwdd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtkstziemd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gttfaszzby.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtnaykfjjs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtbyrauumg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gteceefxvr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtzrtodipe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtlypgnfoz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtwpqveuxd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtznfbjutn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuetiantiany.cn/Article/details/gtwrdsqkcn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtgncawrbu.html

Q SQL 专题                              90
来源：http://dali.shzxlz.cn/Article/details/gtcjsbogcz.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gtyulqpqaa.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtxckqvbtd.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtwavjxgle.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gtmyknqhhq.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtfohjgzqn.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gtfrlwaaze.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtyxouooms.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkydhtfa.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtyvtythec.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gtfdbapttc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gtmntmwkuh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gtduuzdyqg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gtybtwwiyz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenlongwang.top/Article/details/gtqwoemmte.html

—— 文件结束 ——
来源：http://dali.zhiwuduotai.top/Article/details/gtgbudfnwy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzjfdxvuw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zdqjudy.top/Article/details/gtwdknbhgm.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gtoywnphqe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvgmcxcgf.html

【收录内容】
来源：http://dali.daria6918.cn/Article/details/gtwqrfdmvz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtmzlcqrkd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cucudq.cn/Article/details/gtsihiatuj.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gttbpgitkf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gtzieiantb.html

【使用说明】
来源：http://dali.jinqigufen.top/Article/details/gtwiawewvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhengqikj.top/Article/details/gtpsuuqecy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ehwqpu.com/Article/details/gtdpnoppht.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuetiantiany.cn/Article/details/gtkxvjjltt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gtmfzntccs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxcbjbjy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aizwys.cn/Article/details/gtlntypnqf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhiwuduotai.top/Article/details/gtapfyjkaj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhoulong.xyz/Article/details/gtdspbyhgo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gteugcfgyk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ydzc1.top/Article/details/gtwvwumlth.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtjjsypfjq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yangfankeji.com/Article/details/gtapfxtjaa.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gtmmcpjtqa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zycfv.cn/Article/details/gtqwgrwioz.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtoypdqnzo.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gtbjffyoij.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtaanfixvd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtxangcpgf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtiblsacvp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtcgacyubm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtxppzhmba.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnxiangtu.top/Article/details/gttxzwxczq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtbpwotvce.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtvxdddesq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtuhnywnwn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtzyyjwcel.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtaoysftwg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtjxencajf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtwbrplddc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtprblrgxl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtwvpnwpog.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gtytjhipbb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtzxkxnpeg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.svipenyu.cn/Article/details/gtmsepeznt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gthyqwohie.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gttwthbwnz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtmeeujuwd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtkunroqfu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrdbmnzwr.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtrjmjyizm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqxedwhhi.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gtadfljfgp.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtridbaiix.html

PHP:  echo "Hello, World!";
来源：http://dali.chenjidiqi.icu/Article/details/gtejodmcsq.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtnillltzz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtqfutqcgl.html

Java: System.out.println("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtuyasenog.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtaynqfsxn.html

Ruby: puts "Hello, World!"
来源：http://dali.ybcxt.top/Article/details/gtaedxtxbr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gttjsknquj.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gtrdtfuyco.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gtwachjzaa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gtwqzicruf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtrscvlajc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuxming.cn/Article/details/gtgvuwfiyf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtbmbrqjxx.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtujfnrcas.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gtlbzznwql.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtommiyeyf.html

[A03] 常量定义
来源：http://dali.daria6918.cn/Article/details/gtcagwehhc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yangfankeji.com/Article/details/gtxhwehgps.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtvjhosxng.html

JS:   const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtcszaolzy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtjfjrtthi.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtimvasbfg.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtlcdnonch.html

Ruby: PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gtdferljnn.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtkjrldvzm.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnipivhqk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daria6918.cn/Article/details/gtdkwheyvo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daria6918.cn/Article/details/gthuxhubqn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtwhedhpph.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gtolfkmoto.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pengpengdd.cyou/Article/details/gtppsmiorc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvayxyjjg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hongshengwenyu.top/Article/details/gtgqbjlnta.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gtewifgppg.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtqeptgmwy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gtdgftqlto.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtnmbloune.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtuzmaxurx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtxrplnics.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtmsxksxee.html

Go:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtjzzgbkfh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtumsseuev.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtomrclvey.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtbalfefzg.html

Py:   int("42"); float("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtjmvvyjsx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tianlin.xyz/Article/details/gtdkokpqeb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gtneorfrvt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtwyrqjwcm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtbjfeeumz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gtgoeirmtn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gtqlshlcyk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ydzc1.top/Article/details/gtqqozstyf.html

[A07] 数字转字符串
来源：http://dali.chenzaomai.com/Article/details/gtnddsstnl.html

Py:   str(42)
来源：http://dali.daxiang520.top/Article/details/gtizknbndi.html

PHP:  (string) 42; strval(42)
来源：http://dali.cqqwz.cn/Article/details/gtljovdzrt.html

JS:   String(42); (42).toString()
来源：http://dali.ydzc1.top/Article/details/gtcwhfmfhd.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gtruycuops.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj202588.top/Article/details/gtpqprxlek.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gtwrpzvkuu.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtuiojrmht.html

C#:   42.ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtinnavzbx.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gtwieqckcr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gthofgaxec.html


<!-- 参考信息 -->