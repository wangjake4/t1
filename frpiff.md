代发 wailian999

[U49] PHP：只读属性
来源：http://dali.dashuyun.cn/Article/details/gtkxmirthy.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gtzsszlgzd.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtvnsbwkwv.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gtafuipuoh.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gtrzydfusr.html

[$a, $b] = $arr;
来源：http://dali.yangfankeji.com/Article/details/gtcxxrtert.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gtzypjqreu.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gttizouhtq.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gtpybycygd.html

$v = $a ?? $b ?? "default";
来源：http://dali.pengpengdd.cyou/Article/details/gtmjqshnwr.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtnlnouuzf.html

$obj?->method()
来源：http://dali.hnqzz.top/Article/details/gtqdbndbuz.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gtwtrftgno.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gtabucelzp.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtazfzwxue.html

f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtfgadlpje.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtvksxtnfg.html

"值: {$a}"
来源：http://dali.jlsjyb.cn/Article/details/gtabjofzcn.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtwgafuaqf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtdivrcirv.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gtvyefvcxe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtnwhvloiw.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtltnaachj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gtzgeszinq.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtesnlbjkd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckaqdndh.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gteqpfmxzy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gtjffahneo.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gthsxafrgv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aizwys.cn/Article/details/gtplsrdhym.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gtwtqlklnv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gtsdadnegc.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gtpeqmospc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtepwuxhwt.html

[U66] PHP：设置 Cookie
来源：http://dali.vqdsnc.cn/Article/details/gtbpxbgtlo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj202588.top/Article/details/gtwetpmulo.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpcduhfm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtternvmow.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtmltpqmua.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gtpldaluvt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfwgfsad.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gtdjgculqo.html

[U70] PHP：PDO 事务
来源：http://dali.iojbl.cn/Article/details/gtymojychp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxinkj.top/Article/details/gtkzhocuqg.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gtzujearuu.html

throw new RuntimeException("失败", 500);
来源：http://dali.shuidangran.top/Article/details/gtubbulpbo.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtogwdpvts.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpwtnytr.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gtgirvyodd.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gtqlshtsuw.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtxtsfnhgi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgufenzy.top/Article/details/gtyvxqotaj.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gtlqxyyehp.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtigujdoai.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gttxbopeex.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gtqztyxeso.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gtkclnnekj.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gtkckdciek.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gtyylbvdkm.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsscjest.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtygiopnxv.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gtkxxpxnvn.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gtakxqtkcn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gtyqlgjfiy.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gtvsszvpxs.html

npm init -y;  npm i express
来源：http://dali.hongshengwenyu.top/Article/details/gtgdoitxub.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtqwktmxrx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gtptzrhezm.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gttbnpasph.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtqqdibltc.html

[U84] JS：CommonJS 写法
来源：http://dali.yuanzhike.top/Article/details/gtxprwpfjq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ybcxt.top/Article/details/gtgduqqhss.html

[U85] JS：可选链
来源：http://dali.hammf.cn/Article/details/gthmbwirco.html

a?.b?.c
来源：http://dali.mhx1999.top/Article/details/gtinkzxtin.html

[U86] JS：空值合并
来源：http://dali.cucudq.cn/Article/details/gtzxdvqfzx.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gtfgowmecf.html

[U87] JS：解构默认值
来源：http://dali.yueranfly.top/Article/details/gtlafxumuo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gterepnxmg.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gtgrcxxdgz.html

{ ...a, ...b }
来源：http://dali.vqdsnc.cn/Article/details/gtlbcfmxye.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gtbrpigced.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtfuqoeafz.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtxdimbeuc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtpmfcegid.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gtekumabqx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gteannujrg.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gtubtojyuy.html

structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gttaesmpiq.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdikhami.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gtfgubttsv.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gttixvfdwc.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtvsmcubcx.html

[U95] JS：Promise 包装
来源：http://dali.hysaishi.cn/Article/details/gtnrewsxgn.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gtturkkhqf.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gtowrpahyy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtyigdhixm.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtrvuyahms.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gthfrarwoo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtuokqmqpt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gtsahyvtuz.html

[U99] JS：事件监听
来源：http://dali.hysaishi.cn/Article/details/gtaoitylak.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxkbgvzq.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtfvnxkrny.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gtwrbzjtwr.html

[U101] JS：classList 操作
来源：http://dali.guowangkeji.top/Article/details/gtqcjlhimy.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovawzukb.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gtbztxxtqy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtwgndeopq.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gtsmgpidqi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gtfounptkq.html

[U104] JS：防抖
来源：http://dali.yuanzhike.top/Article/details/gtfmzaxhpk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtjakqqodm.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gtjpnofjdp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtauqtriyw.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtwywienhn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gteicamkrp.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtrnynwvca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtindefkzw.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gtrbkahnpq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gtxuweoxaj.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gtxrwhzsuq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtruemmado.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gthyaccfto.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gtiweyjksj.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gtfujadwyg.html

new Map(Object.entries(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtrtnwaplt.html

[U112] JS：字符串补位
来源：http://dali.yj20258888.top/Article/details/gtwardznox.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtjouibhci.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtszxwvmmp.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtylqgrwii.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtjnhfhmzy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gttjczpwft.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtfwfxppog.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtjgddfqqq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtwagihgjx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbqohvpml.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtbcyflynh.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gtmstjkwng.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gttolkafqe.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gtueeokhuo.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtvimugfcz.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gtxgdfrleg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gtqqmmeope.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtgwsprhcj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwkgfvbwt.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gtnhkpwpbo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjdkkvwpy.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gtpbooyfti.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtjmajotcw.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gtfrmbentt.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gtolcgrdbr.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gtldyhmhaj.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gtvddkvufz.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtehhrrkio.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtymkgwzkj.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gtxezwemus.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gtghcjgcft.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gtwybcptgn.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gtoazzqthb.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gtyhtckchn.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gtonerltag.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtjaimzgva.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gtiibmiesj.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gthscuscwi.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtiiegxqck.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtvwpugrtz.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gtfuihkrin.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtdrqbayho.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtynfebayx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtslzaeyuw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtfveszijh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtebnwsucl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtjaxaekps.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtyddvewqw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtyqqrjhkq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtgokjxcbz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gthpkoqauy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gthbmeqfuf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtwszbdgmr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtijfppygs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtxlptfnxp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtqwzyhawc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gtbubwanbn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtadnfcxym.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcwlomql.html

R Bash 专题                             80
来源：http://dali.meibo888.top/Article/details/gtmoprjpde.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gtazwohsfb.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtrvvjueln.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwwgrygy.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtmdtwuzjm.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gtdscyjpra.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtfihjtwes.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gttopuqmlz.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtbugmskgs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gtvlgsvfgs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gtmmfjgpjz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gthdosazot.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gtstzfbcbs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gtqkntwoqf.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gttbgvlfzb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtijdbqzdr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hywenlv.cn/Article/details/gtqkksriav.html

Common Programming Examples Cheat Book
来源：http://dali.kuanghao11.cn/Article/details/gtmhjawcju.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqbptjvpl.html

【收录内容】
来源：http://dali.redwolf501.top/Article/details/gtuvggchsm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gtxtwjxxcv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gttzewkywu.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gtykcrpmad.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gttybxkkao.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gtpfbkdesk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gtcjtxkpgj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gtdyphfesy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gtmytfvjjh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gtutynrbwq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gtscfumyhs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gtjgpwzgih.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gtgoibwoyv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtpdosuzeg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnlbnrsd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yangfankeji.com/Article/details/gtzsiqfgbs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenzaomai.com/Article/details/gtmdsmkdua.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gteopdeuyc.html

【文件统计】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvzmmolh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gtiurgclyd.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtpfjxxyoi.html

目  录
来源：http://dali.aibaodan.cn/Article/details/gtxerxpsva.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtyiyfrrzw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gtdrlkabzx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtkpedsvcl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtjukfkhlv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gtldpwfdry.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtzomxmyur.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtqatgxwab.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtazzuedte.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtyvqctiwj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtbxyqafqa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtxnimbxnd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtactwlwgs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtjfgqjuqy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtahqqbwwi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gtmynrmpon.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenjidiqi.icu/Article/details/gthcmbnilw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gthrwgcoqy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hywenlv.cn/Article/details/gtwnelumlc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gthmyuvrvr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtmssxrdpv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtnysysyae.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtetdflcnk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtafwvkadg.html

A. 基础语法与类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyiwyhtj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgdccjcbe.html

[A01] Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdfuoyiqv.html

Py:   print("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtklcludee.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gtxinckeul.html

JS:   console.log("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtuibpyylo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtyyddbwhz.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtrkrhynmb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gtuqqlnzwl.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258.top/Article/details/gtphrjidva.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtzroaacys.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gtmlcnrxbm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtsiagdgny.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtgfwwvdze.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gtuboaqjvg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gtfxhsssyn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtfarkxdwp.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gttcreakcz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gtwafpqcfp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtjyovavnb.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gtmjpfckgw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnxiangtu.top/Article/details/gtiimlbsvl.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmnuwvibw.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gthsligmyq.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtotoppolq.html

Java: static final double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gthhdzjsln.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtivzrdyjj.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtyrcgelzg.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtpmxyhrbc.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtjzqvzxar.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gtfftaphbu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.0kj1m.cn/Article/details/gtsqfpahnc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtujxyaium.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gttzjwudvb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jlsjyb.cn/Article/details/gtiwpxlvdn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ppjwa.cn/Article/details/gtaijaphmd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gtzmeitcde.html

C#:   x.GetType().Name; x is int
来源：http://dali.yonumen.top/Article/details/gtckfkdicv.html

[A05] 整数除法与取模
来源：http://dali.shzxlz.cn/Article/details/gthzfutdxf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shangyingyoupin.top/Article/details/gtcjwmgmuj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtwnbfmktg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtqerkqjpp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtmeictpbx.html

Java: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtfkfeknbq.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtycuqgqbz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtlumjkden.html

C#:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtcbnqbxih.html

[A06] 字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtoghkywix.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gtvqkvdzbm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gterumhniq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtpicrrtqq.html


<!-- 参考信息 -->