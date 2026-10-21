代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gtfhrcofcx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtdvgmxyuo.html

[U46] PHP：可空类型
来源：http://dali.birdmap.top/Article/details/gtsljdnpxm.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtenfwkoke.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gttcezldko.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtgqmcudfz.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gtrbcnxxin.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gtpuswfeku.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gtskxiekld.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gthyehgofw.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gtfzpubjuo.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuumequcn.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gtndttqqne.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gtchkdyjmm.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhrbzibq.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtjkzqbyxk.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gtsxbpsgub.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gtgngqguoe.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtnaikmxlz.html

$obj?->method()
来源：http://dali.feifeiyinyue.top/Article/details/gtchkssede.html

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gtdgfaimux.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtbmxjcsns.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gthjuacqrh.html

f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtyaxibqwr.html

[U57] PHP：字符串插值
来源：http://dali.ivvv.top/Article/details/gtzmiirjly.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtffnfmgyx.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gthqmaqumw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtjhtnydfw.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gtoeovrccc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtckaakvbx.html

[U60] PHP：JSON 编解码
来源：http://dali.fzhhl.top/Article/details/gtcurxteub.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gtijjhpkon.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gtowadzpip.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtfxvangfm.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gtsnogghjs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtkbhfikpk.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtgtiupwnu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangdashe.top/Article/details/gtuajwcfeg.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gtwwiiqmsc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gtrmzukgad.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtvyigxpfl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtkrnegztc.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtpybpknid.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtsfrkpuwm.html

[U67] PHP：处理文件上传
来源：http://dali.jlsjyb.cn/Article/details/gtrmvkcvhf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.9152youxi.cn/Article/details/gtqmatzhxf.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtdnadilln.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gtyprrsjpt.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtdnjsghbu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gtbqmcldms.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gtxypnhkjd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gtvbxibwym.html

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtdvcubzps.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxinkj.top/Article/details/gtftdevome.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtphmxqkbe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gtblsofdbf.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtwtoqflwl.html

parse_ini_file("config.ini", true)
来源：http://dali.chenlongwang.top/Article/details/gtikkgjqhj.html

[U74] PHP：读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtappfinag.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gtpmduwyph.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gtwiyorugu.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtwvgnmfhf.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtweazumjx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.meibo888.top/Article/details/gtxgqkxrnl.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtrweadfgl.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gtwkelcpzp.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtnkkaqadm.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gtwfersfzy.html

[U79] PHP：静态分析
来源：http://dali.yanxiufei.cn/Article/details/gthamdqyjd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gtpvnehecd.html

[U80] PHP：代码规范修复
来源：http://dali.cashguo.top/Article/details/gtrayzuobx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gtxollddop.html

[U81] JS：初始化项目
来源：http://dali.chenjidiqi.icu/Article/details/gtdupljaez.html

npm init -y;  npm i express
来源：http://dali.gaohongyu789.top/Article/details/gtnahwanra.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigufen.top/Article/details/gtuvakkpxm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gtawtlubpi.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtjuqwtljj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnuvwcgm.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gtccbzrkyo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ybcxt.top/Article/details/gtzvowjlmh.html

[U85] JS：可选链
来源：http://dali.0kj1m.cn/Article/details/gtkbfyxumq.html

a?.b?.c
来源：http://dali.daria6918.cn/Article/details/gtgnpvtxmd.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gtgmxmkivl.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gtldiplqca.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtrykzkihi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gtlszmucsl.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gtyhkqxhgr.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtbessluql.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gtucaqlsdl.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtworpuglu.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtrwcrdgsu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtjzshotmh.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gtdpmaanpy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jlsjyb.cn/Article/details/gtggffpjgy.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtbvaverqg.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gttdwxevef.html

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gtonmxiwkd.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gtrqedzvhx.html

[U94] JS：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtafigywcy.html

const double = x => x * 2;
来源：http://dali.birdmap.top/Article/details/gtzbabrdmy.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gtwrxqgjrg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gthvflxmcb.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtzagqhhmn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtfsvzboor.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtagauqeaa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtmcpomyqo.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gthxzxvjlx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gtmkktezzh.html

[U99] JS：事件监听
来源：http://dali.jiagoushi.top/Article/details/gthqotkwhd.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtjbstjdlb.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gtgleqrzhq.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gtesowmkhl.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtxmfnhkiz.html

el.classList.toggle("active")
来源：http://dali.guannengcc.top/Article/details/gtswgryroj.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtngycnrmw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtbvssxlvr.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gtjmqxqult.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gtwalnpxia.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gtmwndmhtr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtrbpgelcc.html

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gtgbuwhpnv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtziaqsggk.html

[U106] JS：日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbjtxbcp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtecxediig.html

[U107] JS：数字千分位
来源：http://dali.xinyue.icu/Article/details/gtdnlqlcvv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtauegqlia.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtalpiflyh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtonfugioc.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gtruinztrw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtaoulevdj.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gtfofkmair.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gtunjtryxh.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtfphzdjof.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtfqemrjml.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gtfuwmzfsi.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtxchuqfwf.html

[U113] JS：正则替换全部
来源：http://dali.tian-w.cn/Article/details/gtmcbhtjzq.html

s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtnmsjfusw.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gteaygbknu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtujhssfey.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtuqyafimd.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gttjhuxmut.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtuckxvajt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtrkudvrie.html

[U117] JS：单元测试
来源：http://dali.ybcxt.top/Article/details/gtmsiggbjj.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtzrdkyouh.html

[U118] JS：开发服务器
来源：http://dali.yvedp.cn/Article/details/gtdmfpvxrw.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtuthuyfvo.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gtgrxpnxvp.html

npx vite build
来源：http://dali.redwolf501.top/Article/details/gtpcuaczwa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtbmbipwmt.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtrxvjbrus.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmywzdtfo.html

统计汇总
来源：http://dali.xziqi.cn/Article/details/gtawztpvpf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwoagxxnu.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gtznvazxlx.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtvmacwemo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gtwwlqmspm.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfdndctz.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtsmjtmars.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gtaazliegm.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtmxadtlgj.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtckrhizey.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsmordts.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtqwhvsuuq.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gtdlmlhvpv.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gtlnwxfuyo.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjemfvev.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtjojsmbbu.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtedbbsxzd.html

Lua ............ 10
来源：http://dali.zhixingplan.top/Article/details/gtorffifxu.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjceqyidl.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtnxwvfbux.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtwrneggve.html

合计 ........... 2106 条
来源：http://dali.cqqwz.cn/Article/details/gtygbopwnx.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gtpwqyodyw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gtmzwwpory.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtzzhjqvna.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtykthgmts.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtkudumcop.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jianghu66.top/Article/details/gtpzxnppyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtacusfenb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtluveanfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtoetofady.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtxsfelcjm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtpchchlvb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtsvddfujz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnzimmjl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtpbktafii.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtwzxctbzb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gtkhoqvnmu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccuvmymu.html

Q SQL 专题                              90
来源：http://dali.havefunace.top/Article/details/gtusmgwgzf.html

R Bash 专题                             80
来源：http://dali.zhixingplan.top/Article/details/gtccpeesnh.html

S C / C++ 专题                          60
来源：http://dali.jyoumei.cn/Article/details/gtjdmxgmmh.html

T 其他语言补充                          60
来源：http://dali.nanxuanxn.top/Article/details/gtzjysdxno.html

U 高频实用片段                         120
来源：http://dali.iojbl.cn/Article/details/gtovaixkze.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtkylhzweb.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gtwulvinui.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtkcyjfqdm.html

使用提醒
来源：http://dali.zdqjudy.top/Article/details/gtcrhcuvqq.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtqeluvjhh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gteowydbjm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.snrcjt.cn/Article/details/gtlkfwdnyg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fengsongda.top/Article/details/gtvnqnlzkn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtbgagytbe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gtaumlxawp.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gtzlokmtiy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthahtccwm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gtjxhjdpjx.html

Common Programming Examples Cheat Book
来源：http://dali.chenzaomai.com/Article/details/gtcnahsnjz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrwmazalk.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gtbopevike.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj202588.top/Article/details/gtbguwfhwk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxinkj.top/Article/details/gtvxvnbzjg.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtyedeisqk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtyooqepxi.html

【使用说明】
来源：http://dali.yonumen.top/Article/details/gtbgytwvoh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gtasofugdv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gtkmdkmveq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ydzc1.top/Article/details/gtabaftphw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gtbzoggxmr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gtwjcihepf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gtjagiiacb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yangfankeji.com/Article/details/gtgeiepjem.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gtkakmxshb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gtghcwatpm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtopavtbco.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtyrbzbcdj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gogol.net.cn/Article/details/gtxiqtpnzy.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gtwnutmpvx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gtymlhjoku.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtqzutllxc.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtlsekewia.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtmyucmcjd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtuayrikam.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtzqicwvmg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gthdsvpfjs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtlzicyxky.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtkmpbufby.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtrtdxunvr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtfldnutef.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtsqnlcnar.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtpmwepsnc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtzoznkafd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtjsqtxwyn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtvcirdnha.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtfexubqfg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtfjbkrhvt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.redwolf501.top/Article/details/gtyawsgvyu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtjycaaffx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gtonxrbmyi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ydzc1.top/Article/details/gtpshzupaa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jyoumei.cn/Article/details/gtnlgipqbt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtukmaqvar.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtthrqtdqz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmwnqecpx.html

A. 基础语法与类型
来源：http://dali.zhixingplan.top/Article/details/gtnodxtrho.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiztuquti.html

[A01] Hello World
来源：http://dali.cucudq.cn/Article/details/gtxuumdnvf.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtvvnugxcm.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtrhdfehvm.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtkxsjataz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aizwys.cn/Article/details/gtnzkyccqw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gthopbffkh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthslbzwnj.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gtkwcvflxy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtwlbprmsn.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtsiazvhlw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gtgxiatssr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtrgrhnfee.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.meibo888.top/Article/details/gtttjvpmkz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgfzy.top/Article/details/gtwvukjorn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gtrohopfwl.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnqzz.top/Article/details/gtowqtyxpk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.bjfxy.top/Article/details/gtsgjzlrbz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtfgbcoxlh.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtmbbgqyxf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.wangshuangyany.cn/Article/details/gtyvtaykuk.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtsktnjres.html

JS:   const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtwxeblhqa.html

TS:   const PI: number = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtfiymiici.html

Java: static final double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtzhfcetui.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtfoedonqq.html

Ruby: PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtjonwrwpb.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtkqyakpbv.html

[A04] 判断变量类型
来源：http://dali.hywenlv.cn/Article/details/gtchgeqkus.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gtitoxsfev.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtucbttlsp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtdotdbozt.html

TS:   typeof x; x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtvkmetqqu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj202588.top/Article/details/gtgfwlnvcn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.bjfxy.top/Article/details/gtprtosghw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gthjjdygpc.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtlopgkryj.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtrxrmczbb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnxiangtu.top/Article/details/gticqkukef.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtiakpdkrs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtsodlrstk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtrjyuapfc.html


<!-- 参考信息 -->