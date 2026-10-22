代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtphwrzgck.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gteunygviy.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gtvklvthcu.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtszoxhhuv.html

[U47] PHP：联合类型
来源：http://dali.shuidangran.top/Article/details/gtlflvsdvg.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtsyqwjxin.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gttejbzwkb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fengsongda.top/Article/details/gtelhdikao.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtqeezcitk.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwafhbfaz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gtlxofknii.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gteemjyrkh.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtktwwdsqy.html

[$a, $b] = $arr;
来源：http://dali.quarkkingdee.top/Article/details/gtncmxtgbg.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gtadyeraoa.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtzygpmojm.html

[U53] PHP：空合并运算符
来源：http://dali.zhixingplan.top/Article/details/gtphyjlxvy.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtvuighvvi.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpmekjgi.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtmokbhiyi.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gttgkklhlo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtjvxcwban.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gttruqjqpv.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthyfrirte.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gttdtsgpnv.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gtwqsviumo.html

[U58] PHP：数组三件套
来源：http://dali.sysykeji.top/Article/details/gtxnxrjuhv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtpkblyihs.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gtgmwuhcce.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtnmbqkpmr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gthzoocyph.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhyqkjco.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gtkstouksv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtcabzebdy.html

[U62] PHP：日期对象
来源：http://dali.zhongyouzk.top/Article/details/gtrpneqwnz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dianchejie.cn/Article/details/gtutkxthgu.html

[U63] PHP：文件读写
来源：http://dali.shangyingyoupin.top/Article/details/gtnfykiufs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyozvfqy.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gtrfnhgsfp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtpckrpbwz.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtgntwqspj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gtpysjddca.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gtyyhlufrr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtmlyylynf.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gtfanjbcje.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtsxjmnhdb.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtijqbobtz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gtnbgivgdl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gtumrjqult.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gtiddvsqyw.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gtuwbyngtp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gtzdgappuo.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gtpwansolo.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtasczojrs.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtycflghnu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtrrwffmfz.html

[U73] PHP：读取 ini 配置
来源：http://dali.yongpay.top/Article/details/gtlkqkqkaw.html

parse_ini_file("config.ini", true)
来源：http://dali.haohaochexian.top/Article/details/gtkdhifgns.html

[U74] PHP：读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtqatvgwvm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jianghu66.top/Article/details/gtekrpqfms.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtkzkvbomc.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtionawowa.html

[U76] PHP：简单路由
来源：http://dali.haohaochexian.top/Article/details/gtfvitsfjq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sweek.top/Article/details/gtsnksehjp.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrlmxltc.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gthfzcklzm.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gteyjnvhsq.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gtlacxgnys.html

[U79] PHP：静态分析
来源：http://dali.jinqigfzy.top/Article/details/gtimefgeiv.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gtielphrtp.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gtobzahrgp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtmfybftcr.html

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gtzdrrvomk.html

npm init -y;  npm i express
来源：http://dali.cashguo.top/Article/details/gtpqrjtvhh.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gtrstucrqc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gtbeviklwx.html

[U83] JS：ES Module 导入导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfxkmllb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtrlypeoqr.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gtwrjcmtrg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daria6918.cn/Article/details/gtcmzavehs.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gtardxnccg.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjlznxlw.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtmovskprx.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gtgijhntyw.html

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gtifzuwoas.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgufenzy.top/Article/details/gtagmqjvcy.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtohzijywc.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gtehguktbi.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtmgxayapm.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtlowgpmgm.html

[U90] JS：数字数组排序
来源：http://dali.yuxming.cn/Article/details/gtkktyvjph.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtbxxplxfw.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gtjxsoqeea.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gtiostemli.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtdzragdwe.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtknfzzijh.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gtfrikmyyh.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtnjaddbcl.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtgcwudslj.html

const double = x => x * 2;
来源：http://dali.chenzaomai.com/Article/details/gtpkyicmlc.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtvpfcoxor.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtkcdxmuzu.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtexckfsaw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtkrayblur.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gtmkagpvjk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtgzbnwbfn.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtmdxhbsdr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gtawbrtsau.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtpeyyxmxg.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtmznzfzjg.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtdbswbgsw.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gthawnawvn.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtldqdwfil.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gtyrfupzwg.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gtqtedoqmj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gtvhtiqmic.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gtqbultrqe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xziqi.cn/Article/details/gtaaasgavo.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtbzixosut.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gthisgihnl.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtmmrwbrux.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtifzaggaw.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtmuliyumk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gtqxtvfxtx.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtyntwxjwd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gtetbkiomm.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gttmrwfzmd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gtldvkebbj.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtvusbgdps.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtqlkbecso.html

[U110] JS：数组分块
来源：http://dali.jyoumei.cn/Article/details/gtoftatpvi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsoagofo.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtjwmhyfoo.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtkopqtzwl.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gthgmkwchj.html

"7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtvveiyjqm.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gtggewazlq.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtidfulvih.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gtpfflpovr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtjdgaqybo.html

[U115] JS：生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtnkesxfii.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtndznctrx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtalpwytto.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gthpzmgosv.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gtirciynaw.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtyjuossua.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtwwuifkzm.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtjgmxsfqc.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtzsltjkey.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gtfhhamjah.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gtxlxtrunf.html

import.meta.env.VITE_API_URL
来源：http://dali.birdmap.top/Article/details/gtesvzrzvk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagdqqphd.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuhqrbjd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwyjnnjua.html

按语言统计（条）：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpgxrkga.html

Python ......... 252
来源：http://dali.ehwqpu.com/Article/details/gtgkvjaxzp.html

PHP ............ 252
来源：http://dali.tanke756.top/Article/details/gtynpixcyf.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcmagwlf.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtkpynjgtf.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtcswgtymy.html

Go ............. 212
来源：http://dali.tanke756.top/Article/details/gthuaeqcym.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gthmrgctsx.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtifduwmmf.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtkqowiudu.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gtnudoqwpd.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gthnexblot.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gtlbpjacci.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtlvjxgtrl.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtegydflcw.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gtxtthvqyq.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtctcmwoyk.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gthzcgvowr.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gthvgrfwjl.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gtifetsgem.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gtmzbsbltm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtzgjouccg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtijjlsnxp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtqjaedzal.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtmgnuxiji.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gtfiuzyhwm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjthomqoz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtxrrrjmsl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gtogohvsdg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtlbcerjpj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtpgtinqts.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtpetzrlgd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtmyiejlhs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtdjtedjtl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtgvkfyznw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gtfzwlamte.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtwdeoqvsw.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtmjashagl.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtlhspahdk.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gtecofhxyn.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtlyqvyokb.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gthanmkhdk.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtvrdakqpy.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtjfryihjj.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtnxeallzp.html

使用提醒
来源：http://dali.chenlongwang.top/Article/details/gtqayurrke.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtyqpgsjjl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sxryk.cn/Article/details/gtibjtouqu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xinyue.icu/Article/details/gtripqdval.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hfpthk.cn/Article/details/gtdicozduo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gthqosedpx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtdwytpgkr.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gtpuqisyfe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttvfslfwn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ybcxt.top/Article/details/gtuhaikfpc.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtuagvekmx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxvlwumio.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtsanpdvsi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtndcrdphj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gtrqkdbntk.html

SQL · Bash · C · C++
来源：http://dali.shuidangran.top/Article/details/gthekisecx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gtyamxvqak.html

【使用说明】
来源：http://dali.ivvv.top/Article/details/gtvqfbgbps.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guowangkeji.top/Article/details/gtpzdnatqy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gttcttmolw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gtmcnojoxg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gtqfpeeluw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gtmifliyjc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigfzy.top/Article/details/gtlveiubjc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuanzhike.top/Article/details/gtlcucmvca.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gtgpsyuadw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yonumen.top/Article/details/gtvixguodk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gtltkcflev.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gtsrwuntiu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhongyouzk.top/Article/details/gtnxomfsye.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gticewbrwd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gtkadamaag.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtowkmzkdk.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gthzivjxvg.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtkpqovurp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtnzasqyzh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtxfezckjn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gthehhorfl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtenktywcl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtqrnhxlut.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtksoppjsb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gtrhmaugff.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtybozdmku.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtflbfwbcx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtqejnvrmh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtufrebnoz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszzjplyg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtpnxmwzoc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtwoffxdbm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gaohongyu789.top/Article/details/gtgxesfycm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtmbsctuai.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtkzxvmutt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtcnmaxlip.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gtqsumtgkt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgqueapr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtdvfjrcin.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfclmnxie.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gtroygdnwf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsxptpmks.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gtuiygfymm.html

Py:   print("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gtdrhehsyg.html

PHP:  echo "Hello, World!";
来源：http://dali.zycfv.cn/Article/details/gtqllidnaj.html

JS:   console.log("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtylggrbeb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fengsongda.top/Article/details/gtcctqgrew.html

Java: System.out.println("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtbhcxyxeh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtmbynvsfq.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gtyjedhpll.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtnfhjfcma.html

[A02] 变量声明与赋值
来源：http://dali.ivvv.top/Article/details/gtnbojcafk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gtrdlfjsoe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtljiuybmz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gtzwwlxtka.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtkamjokyt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtjnhrskup.html

Go:   name := "Alex"; age := 20
来源：http://dali.kuanghao11.cn/Article/details/gtzcbtwkha.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gtsjmqpizo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtihausrnl.html

[A03] 常量定义
来源：http://dali.zhiwuduotai.top/Article/details/gtowhivpty.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gtyvqqbnze.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtaikjnwhj.html

JS:   const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtmyhdnlrl.html

TS:   const PI: number = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtdvyvjnnb.html

Java: static final double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtflhzaobp.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttcsanci.html

Ruby: PI = 3.14159
来源：http://dali.sweek.top/Article/details/gteifaorqf.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtpnsecahw.html

[A04] 判断变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtqcixvzik.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yongpay.top/Article/details/gthefqespo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtckagldgg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfrcupvg.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlcbeweo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtlnrxbshy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhoulong.xyz/Article/details/gtdojazmrs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.quarkkingdee.top/Article/details/gtqmevcqec.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtkuvuyuid.html

[A05] 整数除法与取模
来源：http://dali.yuanzhike.top/Article/details/gtuubdnvao.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gttxcbwnzd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtkxroxccb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxbfxavs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtprlhxual.html


<!-- 参考信息 -->