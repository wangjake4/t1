代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.xuanzx.com/Article/details/gtagmspebe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gttxcamrkh.html

[U46] PHP：可空类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlsexlqtc.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gtrufipliz.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gtzmyozsgm.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gtfnsbgrcg.html

[U48] PHP：纯枚举
来源：http://dali.xinyue.icu/Article/details/gteresfbot.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtffoxiism.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gtyapsnlqu.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gtjpoxjpwy.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtyfbkjgmo.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuullqwht.html

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gtbbpzzamq.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtmunxbmbv.html

[U52] PHP：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtpjwghmns.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtcyhcvrsf.html

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gttgbygztd.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtqhnwhbzc.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gtpglwtvgq.html

$obj?->method()
来源：http://dali.xuanzx.com/Article/details/gtqrhbofzn.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtgfynprlf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtuhyewxns.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtjgnmrxek.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtbshuquys.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtrcrjewax.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gtdzszlsri.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gtvlvkfqso.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gtfgdfmqhi.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gtxvlahbkn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtyrgbxsjm.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gttyrxyydx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gtxppmmhpv.html

[U61] PHP：正则
来源：http://dali.nanxuanxn.top/Article/details/gthvssrirq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtvjgxrdrv.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtbkkciwrr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycbhmwbs.html

[U63] PHP：文件读写
来源：http://dali.ehwqpu.com/Article/details/gttjyjjffr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gtxcmhmmxn.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gtiryzszkh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gtrqydwzvy.html

[U65] PHP：会话
来源：http://dali.zhiwuduotai.top/Article/details/gtkotwgbtx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtddzfqakl.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtbkdcsbos.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtlbetglha.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gtdpbhhwib.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtynueptwk.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtsiggjrii.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklfgsxmf.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtletoiytv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gtfhqtwkgd.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtvixejskg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cqqwz.cn/Article/details/gtlxgfizzx.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gtasmlbopu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtwhnnzmiu.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gtulgenxqn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gtbmwlpgps.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gtiupfmyol.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gtngqyuyna.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gttyrypocj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gtlehtpait.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtbxcxhfqf.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrzhahkx.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtdsaoajwr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gtiuwbcmfy.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtejhgpigg.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gteroabgqb.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtpecatcdg.html

composer require --dev phpunit/phpunit
来源：http://dali.cqqwz.cn/Article/details/gtlvzyfnhf.html

[U79] PHP：静态分析
来源：http://dali.sysykeji.top/Article/details/gtmqxoschp.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gtpqwoapbf.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtifinbuxp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzodakgnp.html

[U81] JS：初始化项目
来源：http://dali.quarkkingdee.top/Article/details/gtfgrehfoj.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gtnduxfpfg.html

[U82] JS：package.json 脚本
来源：http://dali.hywenlv.cn/Article/details/gtunpmtryj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexihoiin.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gtpicbhhgt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtosbtkdhn.html

[U84] JS：CommonJS 写法
来源：http://dali.meibo888.top/Article/details/gtpzbvyxpr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gtokaywbtb.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtnpxhgqgx.html

a?.b?.c
来源：http://dali.yuxming.cn/Article/details/gtwljlqrnz.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrhqefta.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtpcspmwgh.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gtxsqcfetl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnqzz.top/Article/details/gtmzzatwub.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gtwewhgdvk.html

{ ...a, ...b }
来源：http://dali.gogol.net.cn/Article/details/gtmsjmwrfh.html

[U89] JS：数组去重
来源：http://dali.jyoumei.cn/Article/details/gtxwjfxoex.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtxwzcxxqg.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gtyqizqbip.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gttfticxcp.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gtlfkzsnhv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gtavnxgsbm.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtxpbywkmp.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtpevorfuu.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gtlascveiq.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gtubciyipy.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuelmmasj.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gtxhblmcuz.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gtizcowadi.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gtichaerio.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gttvyvoqfz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtxxfglhbk.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtxleabptv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtememehyv.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtkrlpdwzt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gthfxvgejb.html

[U99] JS：事件监听
来源：http://dali.jiagoushi.top/Article/details/gtiregspqm.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gtjfbbytun.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gtbdymftuf.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtwnitaryf.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtzfwhxfnl.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtwqdtqdbo.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gtqukuisvm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gthegpykhb.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gtzbnepwjr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cdnleiting.top/Article/details/gtyuzosurv.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gteghunrjy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtxkvgwqfc.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtvneucupv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtdlnpndoe.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gtbefiqmhz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtbtbormjw.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gtkzuiizcv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtxwlwdpan.html

[U108] JS：随机整数
来源：http://dali.bjfxy.top/Article/details/gtdunoliqf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtdoqvhpgm.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gthvhhndea.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtknmerhsn.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtlwnrybfi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gtotxpegyo.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtlcysevvj.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttluaaska.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gtclbdxomc.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtaseqayqx.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtkpusrrrx.html

s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtlftjtxoy.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gtmpvfflij.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtdidkhnxr.html

[U115] JS：生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtazbjjmiq.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtexrzpfhp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gttzvrzaby.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtktqmaxmd.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gtnwrcelix.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gtzlbmymqo.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gtymkphzgj.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtnyuqqnpr.html

[U119] JS：生产构建
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvotvazs.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtromaiawc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yueranfly.top/Article/details/gtsdmbcxtq.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gtoiyqdozp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyovvrpqr.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gtwxeppzmw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlhoxmgvs.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtvnkaiavg.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtazvsdszw.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gtisizzowz.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtzvkwzmoh.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtrurxtrwp.html

Java ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtmjlepabt.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gtnvsvmvfq.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gtzxrxpolb.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtqjynsyqg.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtczcriyrx.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtslakefcn.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtvvurqkui.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gtimspumcg.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtmrtceubu.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gttpvdevjl.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gtcsxxmnkg.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtuplesxad.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxmkhjlf.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtwklaauml.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gtxdfzoaku.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gthitdpltr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtquklfwtw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtyxticwje.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gttjighauz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gtefmjpnkp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gthwxqgkcm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtnvpiwzck.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtmohwjszy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtqaxdjzer.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtsqdbmvrp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtmuabgfju.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtomctjgsc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtqyeazief.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtpatafzwe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtvnliweat.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhongyouzk.top/Article/details/gtkycvqfna.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtwfgzbkot.html

Q SQL 专题                              90
来源：http://dali.cashguo.top/Article/details/gtiploxlpm.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gtyihaiegf.html

S C / C++ 专题                          60
来源：http://dali.tianlin.xyz/Article/details/gtqbzoapyz.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtuzrwimmv.html

U 高频实用片段                         120
来源：http://dali.aizwys.cn/Article/details/gthtbtnhku.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtsklwcuza.html

合计                                  2106 条
来源：http://dali.sxryk.cn/Article/details/gthxomfiuv.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gthoauxmik.html

使用提醒
来源：http://dali.vqdsnc.cn/Article/details/gtbpizdsjn.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtqkusuema.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gttnppduja.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nwbrower.top/Article/details/gtcirpmfnd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.redwolf501.top/Article/details/gthvljwtiv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gtgwnqvtqe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gtyqyvuxkh.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtpurzavuq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtuhqowjvr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aibaodan.cn/Article/details/gtfxxzadsu.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gtibjafxkm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthtyjavyb.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gtaidrlinz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gtmivgioqd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqubgmrp.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gtxmigresr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ydzc1.top/Article/details/gtxtsviolw.html

【使用说明】
来源：http://dali.ydzc1.top/Article/details/gtcodvcnph.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.quarkkingdee.top/Article/details/gtntpzacru.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gtojcxcsnp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gttjpdbsca.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gtwnwujeja.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gtyuhsqqez.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gttauqzhim.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xziqi.cn/Article/details/gtmkyosurv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjupnibr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gtlkqggjfq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gtgttfcjea.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuxming.cn/Article/details/gtnngepfha.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hysaishi.cn/Article/details/gtruvwhmle.html

【文件统计】
来源：http://dali.shangyingyoupin.top/Article/details/gtcgdcawvq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sysykeji.top/Article/details/gtoadidcoe.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtzhskcslv.html

目  录
来源：http://dali.guannengcc.top/Article/details/gtylpwiaav.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtwvaaebwp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtreyjxvog.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgnbasnnb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gttgglbjtx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlcujanb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrnzqlot.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtswyaoxwj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtxsgkkqco.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtdcgjfppg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsksohiht.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgowxebh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtmtngovae.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtsiececte.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtllxpfgkh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtwigimcou.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gtqiddybdz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtqhjxuiyj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnqzz.top/Article/details/gtcorpdams.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtuxsscpew.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gteejvvzle.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrttogdk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtboxacgnf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtifpsxpjq.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gthapchbek.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnsnlgzxb.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttqwzvyut.html

Py:   print("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtayzsghsh.html

PHP:  echo "Hello, World!";
来源：http://dali.hammf.cn/Article/details/gtgluisxxg.html

JS:   console.log("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtdtnhlkar.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gtzuesexoz.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtxbufmgnl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtkhnwfnbn.html

Ruby: puts "Hello, World!"
来源：http://dali.wangdashe.top/Article/details/gttgvbrita.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtcylnofus.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gtetvxkzlz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnxiangtu.top/Article/details/gtycsmlxfz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gtzxhrrcni.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtzagwfzsv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.316326.xyz/Article/details/gtazkbhuos.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtaqzmnjyw.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gtvkpznylp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gtjimbfiir.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtscixaryk.html

[A03] 常量定义
来源：http://dali.yj20258.top/Article/details/gtqzhkgzrw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhixingplan.top/Article/details/gtjjnhtunh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtirprlljj.html

JS:   const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtnnhwawug.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtbzowbtup.html

Java: static final double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gttjjtjeeo.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtqjpjjcld.html

Ruby: PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gtoxbaxnnn.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsdezivk.html

[A04] 判断变量类型
来源：http://dali.bjfxy.top/Article/details/gtwededkbh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhengqikj.top/Article/details/gtbsxnpvrh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gtbvhtpadd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gtrttliitj.html

TS:   typeof x; x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtrbblzfss.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtpxivhvnb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guannengcc.top/Article/details/gtvokbasxy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gtpmctoigm.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gtcavixyds.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gttaptnail.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvohiuyb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtrnksikps.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtgjutbbvp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtinqmvjcq.html


<!-- 参考信息 -->