代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtfrhsspbq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtttbksyky.html

[U46] PHP：可空类型
来源：http://dali.andypj.xyz/Article/details/gtdjlkdigt.html

?string $name = null
来源：http://dali.kuanghao11.cn/Article/details/gtqdlnkhfm.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gtgfnrekyy.html

int|string $id
来源：http://dali.chenjidiqi.icu/Article/details/gtwvnxmkia.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gtnmbkntfm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gotoacloud.top/Article/details/gtmesjkrca.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbexwlkk.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gtovzzslsn.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtkendyfzf.html

public function __construct(private int $id) {}
来源：http://dali.cashguo.top/Article/details/gtjzipakiu.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gtwivyomaw.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtwssxepqf.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtqlplcdlt.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtmtnsxmpt.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gteqmqyakd.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtooavtkwr.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnttqehr.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtlwdobofv.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gtukcpyoyv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jianghu66.top/Article/details/gteweoofmo.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gtffixpmfv.html

f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gthzrwbjdo.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtzsjbauzj.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gtasfuijjn.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gtchtnnwbo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xylfe.cn/Article/details/gtcrlfumpo.html

[U59] PHP：自定义排序
来源：http://dali.sufxvd.cn/Article/details/gtqecvocfm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtltrkpxkt.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gtwwjywbea.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cucudq.cn/Article/details/gtabimpnsg.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gterwedzoy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtixuyqchs.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gtnrrwxise.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtfqfagjxz.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gtarolfoex.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtmbcbjddz.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtmuvsdmvy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gtekkrufps.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtsgdiqzat.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gthirsnuqk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhengqikj.top/Article/details/gtnrhpakwu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhongyouzk.top/Article/details/gtcizotqih.html

[U67] PHP：处理文件上传
来源：http://dali.zhiwuduotai.top/Article/details/gtoylhzdvm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtivafaved.html

[U68] PHP：PDO 连接
来源：http://dali.sxryk.cn/Article/details/gtwozpmukr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yonumen.top/Article/details/gtfxvlaywm.html

[U69] PHP：PDO 预处理
来源：http://dali.iojbl.cn/Article/details/gtflfrrcxa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gtbmukqfuy.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtffhbxffp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gttznsrsnl.html

[U71] PHP：抛出异常
来源：http://dali.xziqi.cn/Article/details/gtilygqmlp.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtagjvozxb.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtjifpqrsr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gtyoanbgrw.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtvnmwopuj.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gtvlslepfz.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtizmldaae.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtuqovkuvg.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gtimhghrgq.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gtgumpdyxt.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtcunlcnda.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sxryk.cn/Article/details/gtbwyqehth.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gtdqxksluy.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gteghkwbsq.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtscjuccxy.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtfcqowhjw.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtkxfkdamc.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gtnbxgzkmy.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gtuhwamznp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtqhkpzrqv.html

[U81] JS：初始化项目
来源：http://dali.redwolf501.top/Article/details/gtxuqjrxvw.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtvgvpxpyy.html

[U82] JS：package.json 脚本
来源：http://dali.gogol.net.cn/Article/details/gtswdpjymk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gtkndzyztj.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gtulfsrfmf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtwjmmfgol.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtovfxlktl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gtkmlmgmry.html

[U85] JS：可选链
来源：http://dali.9152youxi.cn/Article/details/gttfbbcrzt.html

a?.b?.c
来源：http://dali.tanke756.top/Article/details/gtaukpyzqj.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtoeozkykl.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gtdzlfsboi.html

[U87] JS：解构默认值
来源：http://dali.svipenyu.cn/Article/details/gtntqjijwr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuetiantiany.cn/Article/details/gtmkfdvlvr.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylwirbnt.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gtmpdypppw.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtqxjnipdq.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtsocphojl.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswrtmzmm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtblafhtbc.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gtcglndydw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcdhpcym.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtmclljfid.html

structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gticfjhwgh.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gturpyrfos.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gtzzgydzxz.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtidgzcwte.html

const double = x => x * 2;
来源：http://dali.wangdashe.top/Article/details/gtoxgtyhjv.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gteiqpgqpy.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gtgkylfxjh.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258888.top/Article/details/gtflteiaay.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlbaiwwh.html

[U97] JS：并发请求
来源：http://dali.xinyue.icu/Article/details/gthgigncag.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtjnadmgfd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtojvkkzfk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gtyrcfkedy.html

[U99] JS：事件监听
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxwhvbjl.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gtovvfaxxj.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gtnnxjvmoc.html

document.querySelector(".item")
来源：http://dali.pycfn.com/Article/details/gtyspoducp.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gteaoxojyo.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtxgiabpah.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtealtmptk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gtigodjhbu.html

[U103] JS：定时器
来源：http://dali.cheryme.top/Article/details/gtipbfmryt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtezgunpvq.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gtsgmelclx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtlbonmyvi.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gtmqiqvuoj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gtgnrzyliq.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtlxzuyghb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gtujeugegu.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gtedxkpyqq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtvdwcyhqn.html

[U108] JS：随机整数
来源：http://dali.nanxuanxn.top/Article/details/gtryqrxlbn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtmoomtinn.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gtqhbxvdri.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtezaeqkth.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gtmmwbljpe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gtmurretln.html

[U111] JS：对象转 Map
来源：http://dali.wangdashe.top/Article/details/gtlmoydopv.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gtgjeuvgpm.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtkbikmuaj.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtyjrfiumq.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtywrvcysb.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnfgcron.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gtfwfovaik.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtsxydvlxj.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtxkvpljrh.html

crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gttshjpjqy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtathrxbry.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gttltiszrj.html

[U117] JS：单元测试
来源：http://dali.chenzaomai.com/Article/details/gtabyizjoy.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gtktzhudub.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gtdovgbygy.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gtdpxlluyq.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gtxoftzgqe.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gtxrkjhqvi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gtnmdighfb.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gthatfiexn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtantgpswk.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtxcjxabxb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmpevegjr.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtczbnfqcq.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtsfcaqgms.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gttykdwsfw.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtyhvousje.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gtxgyvqmuu.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtschwezca.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtznrrakdf.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gtnnwohgyh.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gtqcdwjmjf.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtswcysedr.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gtjkuvubet.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtvksbtqey.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gtrvjojsaa.html

Kotlin ......... 15
来源：http://dali.zycfv.cn/Article/details/gtslpvgxdn.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gtxafyvpsd.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtxawcvpzi.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gtfzfvqjwp.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtxuqmvpls.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtynsbcteh.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gtxcoojhpm.html

按章节统计：
来源：http://dali.cashguo.top/Article/details/gtgkyhtlqa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtrzrtegno.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtiqyraqni.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtbygabtne.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtfhfqvkwz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsorwnfh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtzyjebjyx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtdghgiatk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gtkbifadyf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtuhnbvpxg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtymgtruee.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtfxuhicff.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtytolebvh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtmwnlpoay.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtksxitmey.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtvcipnehs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtxalyilms.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gtxrakxmrx.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gtkjfpczwj.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtawwsztmh.html

T 其他语言补充                          60
来源：http://dali.svipenyu.cn/Article/details/gtzcynxnro.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gtvsipoxko.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtizkhtpnh.html

合计                                  2106 条
来源：http://dali.pycfn.com/Article/details/gtubprewpu.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtenbfxhpy.html

使用提醒
来源：http://dali.yanxiufei.cn/Article/details/gtlckyyvir.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtszsrbcre.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gtkeognkwr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtlavxkfns.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gtyqzjaeku.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtxprfmdzt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gtrcmczrvg.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtdscnccgc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtagwxoifp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gteerykplq.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gtfjftsmsg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwlvovey.html

【收录内容】
来源：http://dali.quarkkingdee.top/Article/details/gtnhffqjxe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttztuyjcj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gtuxqrjzxi.html

SQL · Bash · C · C++
来源：http://dali.shzxlz.cn/Article/details/gtxgoqzahd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gtqhlckbof.html

【使用说明】
来源：http://dali.guowangkeji.top/Article/details/gttlbsetrc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gtsueicjad.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchdwxwrf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gtkexjvaca.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gtplwjnmkl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hongshengwenyu.top/Article/details/gtdhuoyxbd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gtrtnytzzd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gtuneaerfv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gtwfpjnnsp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgufenzy.top/Article/details/gtojirqtxo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtkxkdugoe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gtzktribts.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtqsjpasyt.html

【文件统计】
来源：http://dali.vqdsnc.cn/Article/details/gtrdqxcfur.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtemmvzfpl.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtdgpatqlg.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtjgezwgtf.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtvzgnkgfe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtcllqtyqv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtfimkqbog.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtcjqnnsmi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtevpeltlp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cucudq.cn/Article/details/gtszjugzjj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtorixlezw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtmaoczzyg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtmvqshwib.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtknhbstgy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtfarhgllx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgawxlhcn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtvaprzpyn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtyulkwwpq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gtmjsxzodh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guannengcc.top/Article/details/gtnwayhmjd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtrfpzebyb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gtterxkdgk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtaomjvchp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtwpnmrego.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtkoddcnzr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtkonuvmci.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkmqcdrqr.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gtofdypcyg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnkqafvwc.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gttwbnnczc.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtnkpthbkw.html

PHP:  echo "Hello, World!";
来源：http://dali.shzxlz.cn/Article/details/gtpraplcod.html

JS:   console.log("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtroafepst.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenlongwang.top/Article/details/gtfjckvhww.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtuiajgkom.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtpduirahr.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gtkhinynci.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtxuclaukx.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtsirvojpz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gtwiqkymmp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtawzpxcwr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtvwhlcxos.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtspxezrey.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtavnqhqbf.html

Go:   name := "Alex"; age := 20
来源：http://dali.cashguo.top/Article/details/gtckagiqbz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ivvv.top/Article/details/gtcsgrvgex.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtgrxxbkea.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtfhqbkwqn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gtgiozkdpe.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtrzsborlm.html

JS:   const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtlnawqehd.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtktvrkdtz.html

Java: static final double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtidyjspoc.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtazfxwqdy.html

Ruby: PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtcfaisyee.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtisihonrw.html

[A04] 判断变量类型
来源：http://dali.nanxinkj.top/Article/details/gtprhhwkwk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtjbmcrrjg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtasvvlpim.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gthixvgjkx.html

TS:   typeof x; x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtmiaqjuay.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtaarkdech.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtnqmxawrk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shangyingyoupin.top/Article/details/gtmffqfyqz.html

C#:   x.GetType().Name; x is int
来源：http://dali.pengpengdd.cyou/Article/details/gtaexzjuwu.html

[A05] 整数除法与取模
来源：http://dali.jyoumei.cn/Article/details/gtjmkmwmda.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gtvqcvwtcy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxpbduig.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gthvbcdqjn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtqwmmmebs.html


<!-- 参考信息 -->