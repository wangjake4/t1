代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gtrkojtvss.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gttrpcpnvz.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gtzxtiuejq.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gtwnvcuihn.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gtktpazibv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.havefunace.top/Article/details/gtakunxysn.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gtpolyasdx.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtoaburqaz.html

[U57] PHP：字符串插值
来源：http://dali.birdmap.top/Article/details/gtxtehiple.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gtufomarhr.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gtxgzfervb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtytwfggis.html

[U59] PHP：自定义排序
来源：http://dali.feifeiyinyue.top/Article/details/gtgarhihhb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtflkifjrr.html

[U60] PHP：JSON 编解码
来源：http://dali.aizwys.cn/Article/details/gtdvstdyzq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cucudq.cn/Article/details/gtphrzjgpv.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtypmmfx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtpplgqimg.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtrwzhqwvy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtrrqpacba.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gtrmpycnbt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gtpqfigrzg.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtvlteztko.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cucudq.cn/Article/details/gtzlijweer.html

[U65] PHP：会话
来源：http://dali.chenjidiqi.icu/Article/details/gtuwvuxmbo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtdskqplgr.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumfmidyo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtzbskzmuf.html

[U67] PHP：处理文件上传
来源：http://dali.cashguo.top/Article/details/gtzpiwzkip.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenlongwang.top/Article/details/gtvmapookq.html

[U68] PHP：PDO 连接
来源：http://dali.cqqwz.cn/Article/details/gtrykhjlda.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gthgoglxab.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtzoiniedl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gtdiipuiqq.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkskfhdco.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtqnjsztjw.html

[U71] PHP：抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtqdyaroxf.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gtmqagbqze.html

[U72] PHP：写错误日志
来源：http://dali.tianlin.xyz/Article/details/gtdrhspvmr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jiagoushi.top/Article/details/gtxlbwcpcs.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gtfvibudtx.html

parse_ini_file("config.ini", true)
来源：http://dali.xziqi.cn/Article/details/gtkdykulls.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhihitwk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gtwhnxorag.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gttedfbdmz.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtzditgmtb.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gtkpffrowb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gtksraowwd.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtxoacmjtq.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gtyeifhiaw.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gtoiozdruv.html

composer require --dev phpunit/phpunit
来源：http://dali.c1oappe.top/Article/details/gtcaslvblm.html

[U79] PHP：静态分析
来源：http://dali.jinqigufen.top/Article/details/gtcmcdcwdy.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gtvvrekize.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gttkhynjfb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtppjxhdff.html

[U81] JS：初始化项目
来源：http://dali.aizwys.cn/Article/details/gttgcmsmik.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtpphktlah.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gtxppohxtu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gtpscawiwz.html

[U83] JS：ES Module 导入导出
来源：http://dali.cucudq.cn/Article/details/gtngxmgimp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtdjxgkmdh.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gtesdqpotl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gtzvlugdfo.html

[U85] JS：可选链
来源：http://dali.0kj1m.cn/Article/details/gtmqiwilrx.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtgkhxmize.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gtjgvhkuce.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gttapwkvxx.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gtmygjstad.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gogol.net.cn/Article/details/gtrzjcltzl.html

[U88] JS：对象展开合并
来源：http://dali.ydzc1.top/Article/details/gtvqijrcpr.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gtafmzxomg.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtwvtkhnod.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtmxzbkevg.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gtvsnzjwze.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtwzurwxhv.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtjpwrhgcd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gtaylgfltu.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtyovuekud.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtbidldnva.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gtzpnxbqgd.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtaswitoih.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtkpweahwh.html

const double = x => x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtmgmbfzie.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gttksoqxkq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtomnzbwqo.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gthgdklgze.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtvjzbjvub.html

[U97] JS：并发请求
来源：http://dali.yj20258.top/Article/details/gtkofkhdza.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtikrsrnsg.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gtdfmtdsly.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hammf.cn/Article/details/gtqbauevqx.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gttavkiimu.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtsqowyrmw.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gtovyztcga.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gtoitaymww.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gttpyuoarb.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtmrucyeal.html

[U102] JS：本地存储
来源：http://dali.hnqzz.top/Article/details/gtubgsbpeb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtemhtcicj.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gtbioglnzz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnewatpif.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtdxwgvxba.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtthmdvyim.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gtniisjgtn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtddgwbpjm.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmjgxfdi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gtzewxsecb.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtlvhgqjex.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gtrcpfrtby.html

[U108] JS：随机整数
来源：http://dali.sufxvd.cn/Article/details/gtxxqmlppn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsomclagx.html

[U109] JS：数组分组
来源：http://dali.pengpengdd.cyou/Article/details/gtakrdmnfv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtczompmir.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gthdoiunha.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gtugcqqvcr.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtykadybcc.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gtgnjonxbc.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gturlkswyk.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtiyhifljm.html

[U113] JS：正则替换全部
来源：http://dali.nanxuanxn.top/Article/details/gtszfvocdr.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtqigwsfrr.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbemmerui.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtrkurchfy.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtithsqelw.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gteoyrsymg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtfhzxstlv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gtlwydufvb.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamghoabw.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gtakguzoan.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtdfgilpgz.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtvmixqnny.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gtuonxrslu.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gtsysiksfm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtnamyldmy.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gtwkdvymgt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjwslscvd.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtcsdjnhbu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnrymcwxa.html

按语言统计（条）：
来源：http://dali.aibaodan.cn/Article/details/gtiollukdr.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtiuwqvsmf.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gtywlcqmsz.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnjkgkvz.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gttblynsqk.html

Java ........... 212
来源：http://dali.daxiang520.top/Article/details/gtuooomcud.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtelrlxdef.html

Ruby ........... 212
来源：http://dali.ydzc1.top/Article/details/gtorizrwvz.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gtiwklktdo.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtaphdegnu.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgtrcxql.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtebyknvhh.html

Bash ........... 80
来源：http://dali.daxiang520.top/Article/details/gtrfyfqysg.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gthmxaftyg.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gtlgadsrbb.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gtphxjngwp.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gtbvouroli.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gtuosfltss.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtbgtmhqrx.html

合计 ........... 2106 条
来源：http://dali.jinqigufen.top/Article/details/gtqmefuzqj.html

按章节统计：
来源：http://dali.xuanzx.com/Article/details/gtnpmbbszp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtcuovdhrd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtfvnnxoot.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtxcjeiqty.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtmwjptztp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gtywwhkjbw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gthxpsrpmq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtbnmjrzbv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtswdjshih.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtgeotyesc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpezrdnxt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtkjzmlhvb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gthcnboaeu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtseuqxzls.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtvxjuijpn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gttwqpinyj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtyrrspwed.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gtqkdkxpma.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gttgnibwcj.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtgnupkiyv.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gtzyxmxndj.html

U 高频实用片段                         120
来源：http://dali.cheryme.top/Article/details/gtltvzhoxk.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtkdrdjdtv.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcugxvdq.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtkdgizndz.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gteffifldx.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtvpepjevx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gthxndxpeh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gtsnhabhqy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gtgtjbqfzc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gtlucrqmhx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gturtcdozh.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gtmngvmmay.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkhdpouxd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gtkjrgleci.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gtsodhrgvl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtljzgscop.html

【收录内容】
来源：http://dali.hnqzz.top/Article/details/gtxdqjxowy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gtkwkxgovm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.quarkkingdee.top/Article/details/gtbauezizj.html

SQL · Bash · C · C++
来源：http://dali.xinyue.icu/Article/details/gtazfewcmk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnqzz.top/Article/details/gtlmwgwtyz.html

【使用说明】
来源：http://dali.redwolf501.top/Article/details/gtpzaykwmp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cashguo.top/Article/details/gtqwfqwiqa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gtxdjlogdp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gtjkmxvwxo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gtpesqoziu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cashguo.top/Article/details/gtpuoxajsh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtbfopzfvk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tianlin.xyz/Article/details/gtqroplwxw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zdqjudy.top/Article/details/gtgfbpirom.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.bjfxy.top/Article/details/gtzdaeubvx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtvevxgymk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ybcxt.top/Article/details/gtncnabifk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuuiwfeh.html

【文件统计】
来源：http://dali.yongpay.top/Article/details/gtksqlwjsa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtszncdity.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gteogwortw.html

目  录
来源：http://dali.cqqwz.cn/Article/details/gtvgabqgaa.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtgleytnii.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtziifrwdp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtzrnamykt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtddsuwrhu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gtycpfxgmy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cdnleiting.top/Article/details/gtxulhwdcr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gtupzlqjfh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gthferszad.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gtghxbxmfc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtlstshprj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtfpcmudcc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtlnviqoal.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtaajuqnno.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtdlfxrdyc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtsbvsbxnc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dashuyun.cn/Article/details/gtmewtazyk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtdkycpndm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcrotcdf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj202588.top/Article/details/gtydzsgivz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gtcjmkfdrj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtsacoxsnc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgrzpsxw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlgkafsxn.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gthqechhga.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjuxgzwba.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gtzghzgfyn.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtoifgtgrh.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gttazouwus.html

JS:   console.log("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtzqsudmym.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jlsjyb.cn/Article/details/gtwwsmqsxc.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtqtikeazn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbbgmpoi.html

Ruby: puts "Hello, World!"
来源：http://dali.ydzc1.top/Article/details/gtnlxucqnp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtehkrdivy.html

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gtxkfleatj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtjqeplmem.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtcgzyrrka.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtfxrgurar.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtmmfcuqca.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gthajfuvwu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zycfv.cn/Article/details/gtaxygmjyy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangdashe.top/Article/details/gtsjwocsgg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtcgzaqhal.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtpwowovbe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gttzzmyqij.html

PHP:  const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtjpqcgvpx.html

JS:   const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtzapldyjp.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtuhuoyuin.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtvjjxsbua.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gttazjuofk.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtkiuhjtlw.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtxkcqnfhg.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtmzcfiyrb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ydzc1.top/Article/details/gtykfpfhji.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gttcchgnob.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gthccslbje.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gteoiswpvr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtouhmukyj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gtketjjtqz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.daxiang520.top/Article/details/gtgbklfgma.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtafuyycyg.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gtusljquol.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gtscaozkxd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtfkhwrqhk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtwemdsvib.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtzzaigfgc.html

Java: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtyzbzbkrc.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gttzufrbda.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtjwoymhmj.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtsyodleoe.html

[A06] 字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadrehhoh.html

Py:   int("42"); float("3.14")
来源：http://dali.gotoacloud.top/Article/details/gtiqfepisf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtvnkbdwyc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gtlcyfxxul.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaorfsplc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtccshggpy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daria6918.cn/Article/details/gtummqsqjp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yueranfly.top/Article/details/gtbopkcabb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtgrwwkycw.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gtiurntzim.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gtndnkdazp.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtwxetgagv.html


<!-- 参考信息 -->