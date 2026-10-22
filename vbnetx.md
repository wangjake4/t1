代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtdvenpbqk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gtyxzmqdrq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gtptefelao.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gttburovfu.html

[U43] PHP：声明命名空间
来源：http://dali.yuxming.cn/Article/details/gthqujklvx.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gthihoplch.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtcoqjzsbw.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gtpgbdlmhy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gtpphoehrq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtucfoticn.html

[U46] PHP：可空类型
来源：http://dali.tanke756.top/Article/details/gtbmvfkgda.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnczmokj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gtlljrllao.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtguimwekh.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gtvstvuiji.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gtcglhyvbs.html

[U49] PHP：只读属性
来源：http://dali.shuidangran.top/Article/details/gtbmrytfva.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtjekknniv.html

[U50] PHP：构造器属性提升
来源：http://dali.dashuyun.cn/Article/details/gtrausdehh.html

public function __construct(private int $id) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbfxmocrs.html

[U51] PHP：数组解构
来源：http://dali.chenlongwang.top/Article/details/gtxyowariu.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gtithdizhz.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtdlowykiz.html

$double = fn($x) => $x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtyrpcxhkb.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gtzalgaixu.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gtpiuosryg.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtxzammzmi.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gtskzijncl.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gthmotvvut.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtghncownj.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gthvrqcsnc.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtildqslkw.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtenxlketh.html

"值: {$a}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuyzrfkv.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncutootc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.meibo888.top/Article/details/gtngifdpnq.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtiezqymbk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gtwumfpgsi.html

[U60] PHP：JSON 编解码
来源：http://dali.svipenyu.cn/Article/details/gtmhbrtkcu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtdolumszg.html

[U61] PHP：正则
来源：http://dali.ydzc1.top/Article/details/gturjbtufh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwelavdyh.html

[U62] PHP：日期对象
来源：http://dali.shzxlz.cn/Article/details/gtyxwcmicl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtoxxyeudh.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gtculmcmlc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gtxwknjney.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gtvjlzwnog.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtzhjusxct.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gtkykzqqpe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtsokoruli.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtuqoennrl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdfwqyeok.html

[U67] PHP：处理文件上传
来源：http://dali.ivvv.top/Article/details/gtyrmrztkv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtmgptsaaw.html

[U68] PHP：PDO 连接
来源：http://dali.ehwqpu.com/Article/details/gtyfdvyldb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtcxvgqzcv.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtxgydtjzu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxinkj.top/Article/details/gtuftlgefu.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvwpfoky.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtfiziimya.html

[U71] PHP：抛出异常
来源：http://dali.yonumen.top/Article/details/gtxslrnyeg.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtznzyfcoi.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtalzkxonx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gtsycpsnqb.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtgbqlxsvi.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gtitwlleki.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtfevpjgio.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gtjtqvhgsn.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gtjagudcky.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gtslfifuml.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupnnpoag.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258.top/Article/details/gtxtigcqpd.html

[U77] PHP：模板渲染
来源：http://dali.yuxming.cn/Article/details/gttlopdgvx.html

composer require twig/twig
来源：http://dali.cqqwz.cn/Article/details/gtavtszqwi.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtjuepnist.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gtfiahtsaq.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gtdviqxffr.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqreunhxz.html

[U80] PHP：代码规范修复
来源：http://dali.zhoulong.xyz/Article/details/gtrdwmpxci.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gtnxjcsjfd.html

[U81] JS：初始化项目
来源：http://dali.daxiang520.top/Article/details/gtmqzqxwqb.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gtbnxiocnw.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gtkgchgmik.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gttjyqttem.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gtoazngevt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtuohhgius.html

[U84] JS：CommonJS 写法
来源：http://dali.quarkkingdee.top/Article/details/gtjbccdupo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gtccwjabxq.html

[U85] JS：可选链
来源：http://dali.yanxiufei.cn/Article/details/gtzuimgxht.html

a?.b?.c
来源：http://dali.snrcjt.cn/Article/details/gtkvcxnnnw.html

[U86] JS：空值合并
来源：http://dali.zycfv.cn/Article/details/gtrowkefjs.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gtfguysqeu.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gtiaeqtuui.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryosdsla.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtauuhmmfu.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gttlwkopmu.html

[U89] JS：数组去重
来源：http://dali.haohaochexian.top/Article/details/gtbulfglbh.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtyfogslph.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gtxbrujspw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtdfbtdzze.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgnhxkjj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gtcwelggep.html

[U92] JS：深拷贝
来源：http://dali.tianlin.xyz/Article/details/gtfpqhsqxy.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvktravzf.html

[U93] JS：模板字符串
来源：http://dali.chenlongwang.top/Article/details/gtlijwgdhp.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gtdkmdwpza.html

[U94] JS：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtlzntiwem.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtmrvoktmj.html

[U95] JS：Promise 包装
来源：http://dali.chenjidiqi.icu/Article/details/gtijlkckwa.html

new Promise((resolve, reject) => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpxozlxy.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gtlcjhnlfs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtcrvcxesh.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtrnuptbdz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtvcxcabjo.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtqytuetoe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gtekrowwjz.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtduylaxbe.html

el.addEventListener("click", e => {})
来源：http://dali.hfpthk.cn/Article/details/gtvpflxjlm.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtecjzmegw.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtzbwxrlgd.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gtftazqpyp.html

el.classList.toggle("active")
来源：http://dali.ydzc1.top/Article/details/gtmozbfivw.html

[U102] JS：本地存储
来源：http://dali.hfpthk.cn/Article/details/gtgjowqpge.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtzgeaubvm.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtkfnmzqlq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gtatitujen.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gtkotbnfqn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtgpmvcwjr.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtfcbdkbvt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxnvgafq.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtrivgqnew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtpssbkuni.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtsbvggadh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcftiogpm.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtaziedryl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gttovirogt.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gthdfyfhcg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtkxdqotqa.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gtvgpdutxf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohlkuzrl.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtuhoqokue.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gtzzinfkmq.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtgirgrrvx.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtsjdznowm.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtfuagkllg.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtxcirrgie.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gtgmdnnzfh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbihcekgl.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtgogpnuhu.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtckxwqtif.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gttdryduox.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hysaishi.cn/Article/details/gtiwcqdbqt.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gtxwrpfdkg.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtxnkkymqu.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtwjitqcwo.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleuhnohh.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gtxzroxkxd.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gtsupguaig.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtgzjpesvf.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtcxcbosla.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gteicjzqnw.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtsgfwuefq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrdynruxy.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gtfgohzmge.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtfaclwqqw.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gteotozrpg.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gtarxvunsh.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtnswbcudv.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtlnhhoqak.html

Go ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterzrzgiu.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gtnufckvzv.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtpaxgafof.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gtvofbeigh.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtrydapvnz.html

SQL ............ 90
来源：http://dali.aizwys.cn/Article/details/gtfuyeovtx.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtruwjqvll.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtjmzyiypa.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtbmgramch.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfbeanvy.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtdzwxotil.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtunuosxtn.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtzpcmcxba.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gtjazgxxla.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gturltzjzi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtzkxbnrrf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtovduwjsx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtwgcvlngz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtshqcnqej.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtryybzbie.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtfwgziidm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtqokatepz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtubhivwjv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtnekbomel.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtkahduydz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtusuxfzud.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtflnlutik.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtjotpyhkm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtxdeaetkb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gtxpkikcus.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtyngpsnjy.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtlbwcfwra.html

R Bash 专题                             80
来源：http://dali.fzhhl.top/Article/details/gtfcmrvvrz.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gtwbweqxqr.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gtdojmkkah.html

U 高频实用片段                         120
来源：http://dali.cucudq.cn/Article/details/gttjhbkree.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtzxjkblig.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtubkyjqhx.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtxzkxfyql.html

使用提醒
来源：http://dali.yongpay.top/Article/details/gtyoxppikp.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtptghqzqu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtsfqgxxxf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyllumcu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gtaragjrrh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guowangkeji.top/Article/details/gtnpjwwqsl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtzkdqglwm.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gteailcemc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxhdmqyxz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daria6918.cn/Article/details/gtewrdunrl.html

Common Programming Examples Cheat Book
来源：http://dali.hammf.cn/Article/details/gtuymlynfp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrjojcfxu.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gtxjbibqpf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gtfdrswcgq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtvmrhwzhz.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtemjijygh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hammf.cn/Article/details/gtwexnqvyr.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gtjmekwbbp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gzhubu.top/Article/details/gturjqecbz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwtrdlek.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shangyingyoupin.top/Article/details/gtptbqtuha.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gtfvbkvtfb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gtyxtncwny.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.svipenyu.cn/Article/details/gtszkzypgh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtqxqgblpv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gtosfsfzvp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtxevufkyw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxinkj.top/Article/details/gtmjodjdyx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtawlzjciw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gtcmpftkpq.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gtjvpzogig.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xinyue.icu/Article/details/gtekoxtsfb.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtryexlkqh.html

目  录
来源：http://dali.yueranfly.top/Article/details/gtqqnzdlzv.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtcqonvfjm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtpsmxusju.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtnnpxxlcv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtpabgsqec.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtaabxvrnw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258.top/Article/details/gttbqkmfgs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtbiazgxxq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gteihgahol.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtkidmgoke.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtyhqgayqq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtgbomahwj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtqxvttrnq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtbciwxekx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtdspcdsbs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtuhvsxxya.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuxming.cn/Article/details/gtzzkienuf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtfssesndg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gtjulwmajz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesofymwt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gtqvuefxrj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtjoxhpwrg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtuudmntiu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfnnvgoay.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtamhgalmu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmrbuoaye.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtxmcpvxbs.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtvtugpkdu.html

PHP:  echo "Hello, World!";
来源：http://dali.jlsjyb.cn/Article/details/gtrlfbtxjs.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gteflleltg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqyslify.html

Java: System.out.println("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtbiyhajlt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtritvsjua.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxwnwfic.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtastxtzwc.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gtkycxhhzt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yanxiufei.cn/Article/details/gtytbyvcmo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shuidangran.top/Article/details/gtjqobfqpf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtjcoreelc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xinyue.icu/Article/details/gtptgkmjpo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtsehqbqgf.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gtszhtowfz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gtbqyeoqij.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtdhghvypl.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gtlsgxcshf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tian-w.cn/Article/details/gteemvflib.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtvqkfiaep.html

JS:   const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtgcvrhwvu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtsgtuobrp.html

Java: static final double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtzehmuroh.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtdsfdnarj.html

Ruby: PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtkyornewz.html

C#:   const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtslbzhyam.html

[A04] 判断变量类型
来源：http://dali.daria6918.cn/Article/details/gtbdswcput.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aizwys.cn/Article/details/gtysoqsfps.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sysykeji.top/Article/details/gtntmsflas.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtfnrhstkf.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gtdekhvtga.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gotoacloud.top/Article/details/gtjhspbazb.html


<!-- 参考信息 -->