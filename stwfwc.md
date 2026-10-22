代发 wailian999

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtapagcpjq.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gtjyhygmgq.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gttdwioryh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gthhuuqppe.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gthauduklc.html

public readonly string $name
来源：http://dali.shuidangran.top/Article/details/gtpqvfxzzg.html

[U50] PHP：构造器属性提升
来源：http://dali.sufxvd.cn/Article/details/gtczysnnju.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtqdscjkfz.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjaeghrh.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gttpmyxvdz.html

[U52] PHP：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gtagjvznqh.html

$double = fn($x) => $x * 2;
来源：http://dali.sweek.top/Article/details/gthddkoras.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gtfnipdqjr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtnuqsrosa.html

[U54] PHP：空安全调用
来源：http://dali.jqgfzy.top/Article/details/gtjohvftul.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gtcmpfgyrp.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtlwtevdxx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gturwspuqa.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gtrofhaxqk.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtneckcmhx.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gthferbxhf.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gttuajocpj.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gtgrqoajnn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shuidangran.top/Article/details/gtzchectgr.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtaxqljswv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtfllriurd.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtthkugupq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gtaldccbxu.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtglxmlqzb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtwtojngtj.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtnjwvowbi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnppjcjm.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gtkchkkfkd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.meibo888.top/Article/details/gtdnisegxe.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gtikjandfg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gtnegcixir.html

[U65] PHP：会话
来源：http://dali.yangfankeji.com/Article/details/gtourdtbls.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtxgmhsvyb.html

[U66] PHP：设置 Cookie
来源：http://dali.wangshuangyany.cn/Article/details/gtfjsqdcjx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtlmxletud.html

[U67] PHP：处理文件上传
来源：http://dali.shzxlz.cn/Article/details/gtduxradyd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafehtdwe.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtuuszqelv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtnxyyvxgj.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtvrpjqele.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zycfv.cn/Article/details/gtqiadisii.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gthscnbnek.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtqtnoanmp.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtjejlcpxo.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtshdgzbxe.html

[U72] PHP：写错误日志
来源：http://dali.shzxlz.cn/Article/details/gtgbolutgw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pengpengdd.cyou/Article/details/gtbluxhlgq.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtapzmgjir.html

parse_ini_file("config.ini", true)
来源：http://dali.gogol.net.cn/Article/details/gtcjukxedq.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gttnqnwfum.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gttcbdoxqu.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gthlsonwgb.html

composer require psr/container
来源：http://dali.pengpengdd.cyou/Article/details/gtcxbljpbv.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtjwhpawxf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gtvbydrwxb.html

[U77] PHP：模板渲染
来源：http://dali.fengsongda.top/Article/details/gteoibuvln.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gtysqvinso.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gtotkbwygm.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gtnixiuyuc.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtivlgbnry.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gtzusgiuoe.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtgpitpdyf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtghlxjshm.html

[U81] JS：初始化项目
来源：http://dali.0kj1m.cn/Article/details/gtnljhlnct.html

npm init -y;  npm i express
来源：http://dali.kuanghao11.cn/Article/details/gtpwiuoaaa.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebvgiujx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtqsdbobqt.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gtiafuhpys.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtmwnviakg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhoulong.xyz/Article/details/gtmfakornd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gtztxvnxpc.html

[U85] JS：可选链
来源：http://dali.svipenyu.cn/Article/details/gtacwpneeg.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gtgzlgmjtp.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gtnrivcdjp.html

a ?? b
来源：http://dali.shangyingyoupin.top/Article/details/gthkfajrci.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gtvbdzxesi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gthdcdhgcs.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtzijyzqpp.html

{ ...a, ...b }
来源：http://dali.feifeiyinyue.top/Article/details/gtkgbzikaw.html

[U89] JS：数组去重
来源：http://dali.haohaochexian.top/Article/details/gtefjjnpes.html

[...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtvthuelcw.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gtpgirzdea.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtnhgwsrnz.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtuspmngho.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gtxbrzpbkv.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtfdzixhik.html

structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtocvfospp.html

[U93] JS：模板字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfbhswpz.html

`共 ${n} 条`
来源：http://dali.jinqigfzy.top/Article/details/gthsyxyszg.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtulkadqhc.html

const double = x => x * 2;
来源：http://dali.meibo888.top/Article/details/gtghspdfwe.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gtegzwtcfv.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gtsqkrlmls.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtvgwfdfsw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtwvkiicdh.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gtzqsrisbv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtwqodrasv.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gthvatzjnj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gttkylbvid.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gtubvztivh.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtvkcbtydg.html

[U100] JS：DOM 查询
来源：http://dali.sxryk.cn/Article/details/gtthsuytut.html

document.querySelector(".item")
来源：http://dali.svipenyu.cn/Article/details/gttqxiiifk.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtwxyimgad.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvialuvu.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticzfxlsr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqssjhhag.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtrrzfbfhh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhmjspiq.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtkiqtzmfy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtksiaddsw.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gtwnwdnvyn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zycfv.cn/Article/details/gtrjisvaxj.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gthoajrihu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuxming.cn/Article/details/gtlhfvopyh.html

[U107] JS：数字千分位
来源：http://dali.ybcxt.top/Article/details/gtdnevegoz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gttlzxrylz.html

[U108] JS：随机整数
来源：http://dali.yvedp.cn/Article/details/gtvfnfrxnq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtbqtnkvtq.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gtivyqwjvu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtsfuwawgn.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtqpwlhley.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gtuhrhypgd.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtzalxiknr.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gtxdiofjki.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gtnucjgwcc.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtbzchmvqp.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gtcedmahqa.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjjpjkqkj.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gtrdfuynfo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtulvsgwqe.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtdozlaqsg.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtqrgenxzm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tianlin.xyz/Article/details/gtcvghmfen.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gtdmjzocxj.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtqfmnofxq.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gtdsiwxpze.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtodzjnmtd.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gttyccylrr.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gtvdoeikbr.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtevnuonbl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtlmwbfrds.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtbdbhauss.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gteqjkzfih.html

统计汇总
来源：http://dali.nanxuanxn.top/Article/details/gtvnznwyxx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttxgqbdaw.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gtfahudkfg.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gtbdscmkni.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gtbcbjqlmg.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gtioqmfief.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqcorzlq.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gteznyzrlv.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtpgwanjms.html

Ruby ........... 212
来源：http://dali.xylfe.cn/Article/details/gtiekgyetz.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtnfjdeyav.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpefwiop.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gttycfscqz.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtokuqolsx.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gtvhqmvqzp.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gtnqtlhcyl.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gttawhnewn.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtjavnupky.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtriwyrewf.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtkegtxrof.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqdumlid.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtyzgeneyf.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gtipnufqof.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtjbwnyrzm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtibfjokaw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtnzymtvku.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtqhnmxgiz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gtsnurmkne.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtvupmfrxy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtdoqrspoz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtumckrqju.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gthstoswfp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtdffrmziq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtpzbupsqw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtyzbzffld.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtsziliquk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gteqltasgt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtapntvlss.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtoluoezix.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gttkyoyegt.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gthdyjbtjr.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtxtebqovj.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gtlqwecjlx.html

U 高频实用片段                         120
来源：http://dali.zhoulong.xyz/Article/details/gtzatkcgai.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtvqnknxet.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtrxrvrixz.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtcviayfdm.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gtemfetxlp.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtofbmpufb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yongpay.top/Article/details/gtnzwnygdf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtnpvdbtje.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gtjyedvver.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gtglrhnexn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gtbtpkltbk.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtrtxqtwzr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmpdniyv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigfzy.top/Article/details/gtwhghavhx.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gteetkufek.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbztjlwop.html

【收录内容】
来源：http://dali.yj20258888.top/Article/details/gttkfznsdz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jianghu66.top/Article/details/gtyqtoufjd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hnqzz.top/Article/details/gtkzktawss.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gtfjjfbfma.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gthexhxbmb.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtlalxuexq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sxryk.cn/Article/details/gtkioybuhy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dashuyun.cn/Article/details/gtenjhmzbq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhengqikj.top/Article/details/gtswupdpop.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hywenlv.cn/Article/details/gtlqqwygcq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavadmcmk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gtuibbsbvn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gtmnpplwnf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxinkj.top/Article/details/gtkwqrjshz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtzvymzrvg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtbafqivxa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gtwntbwmag.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gtuvvfqyys.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gttyplchug.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gtbdyvxnye.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtelqgmned.html

目  录
来源：http://dali.aibaodan.cn/Article/details/gtlgsnndca.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtpdmzedrt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtyhwebysf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gtdpkruanf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtthnaspzk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtphjxrkph.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuwwqzsd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gtcwwhuatp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtshmhzesn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtqanfnecr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gttrqrslen.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtvoqmfrht.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtotqfwuby.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtjmawjbop.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtddrspxvp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtalycctpt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gtqbinafff.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtfeefirbf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtskcqcpul.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gogol.net.cn/Article/details/gteyaimhlt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ivvv.top/Article/details/gtlssqfnps.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtnnrofazn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtbplljgku.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtltuiwcoa.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gtlfmesoue.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtszwxcmyv.html

[A01] Hello World
来源：http://dali.havefunace.top/Article/details/gtgordtmiq.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtdkygfgaf.html

PHP:  echo "Hello, World!";
来源：http://dali.meibo888.top/Article/details/gtriisslau.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtehwdnctl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cucudq.cn/Article/details/gtekktpouc.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtlbhkwgcd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtnratemeu.html

Ruby: puts "Hello, World!"
来源：http://dali.hnxiangtu.top/Article/details/gthynwzkvk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtrrnydcsm.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gthwipnkfv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gtrwpnfveq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cheryme.top/Article/details/gtgeezzhwp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.c1oappe.top/Article/details/gtuhcxbhsw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtspwlkntu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gteqasajku.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtpdnuvach.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gtugjiwxdk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtsyuzochm.html

[A03] 常量定义
来源：http://dali.zhengqikj.top/Article/details/gttmhfdvko.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.snrcjt.cn/Article/details/gtdowijqgd.html

PHP:  const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtmzdhlhkn.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtmwwepqqi.html

TS:   const PI: number = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtgcmfeosy.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtvcdnbfai.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtwjklfcee.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtcispkebn.html

C#:   const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtflvehcmn.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtsgktzoqh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gtgicyrbfi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtmszazrfj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gtoelbpyzw.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtpjpcwgil.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shuidangran.top/Article/details/gtysjejnsk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gtnpppzjph.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjyqktoo.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gthjvspmvp.html

[A05] 整数除法与取模
来源：http://dali.xuanzx.com/Article/details/gtxphuylct.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pycfn.com/Article/details/gtxfzzbnir.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gttdpnzqhl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtyrgqkhmf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtcfpethob.html

Java: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtdmxfmaat.html

Go:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtddvplapz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtwhcjaozu.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtvlrjbwav.html


<!-- 参考信息 -->