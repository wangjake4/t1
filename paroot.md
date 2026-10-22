代发 wailian999

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtloewsdwp.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gtlfurnzor.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtsulapbgh.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtrmtgyvfh.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gthfwvpcjp.html

[$a, $b] = $arr;
来源：http://dali.yueranfly.top/Article/details/gtvasdqelb.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtwwshglbl.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtdzlihqtz.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gtsvtqimra.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gtxopraejb.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtpmvcxyyu.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtxdnrfwte.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gtzrfmstgk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtmeagdsks.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gtupwdzuis.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtastzyvmx.html

[U57] PHP：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtntviepmp.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gtwhigdlwp.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtkwdytswa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtcdqohqxz.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gtpxxmwijb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtpcoeoltn.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtmagtnvoo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtyzcvrzjb.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtpvskxzde.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtbalvnaya.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtohnpcoqo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fzhhl.top/Article/details/gtwmrjymte.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gtmpkejsbo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgufenzy.top/Article/details/gtpukqzrlf.html

[U64] PHP：目录遍历
来源：http://dali.ybcxt.top/Article/details/gtgkbquxze.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtklwnoljp.html

[U65] PHP：会话
来源：http://dali.aizwys.cn/Article/details/gtbaphkvcx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtylbruznv.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gtqzsommfg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtjssyhxqx.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gtiqpqqlcg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtqtluwjqj.html

[U68] PHP：PDO 连接
来源：http://dali.hysaishi.cn/Article/details/gtpfvdzqpk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nwbrower.top/Article/details/gtngzvfyze.html

[U69] PHP：PDO 预处理
来源：http://dali.yangfankeji.com/Article/details/gtnbwtnadz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gtzvrmxyla.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gttcslesat.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gttmlgxvhd.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtjwpcbqhw.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtkdaqigpc.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gtxlwzbdvb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.feifeiyinyue.top/Article/details/gthshcubff.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtpnghnkoc.html

parse_ini_file("config.ini", true)
来源：http://dali.sufxvd.cn/Article/details/gtgtciwpnk.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtwhqfzaec.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gtoxoctgsy.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gtclxuubwm.html

composer require psr/container
来源：http://dali.guowangkeji.top/Article/details/gtkyonznnb.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gtdirzrtjc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gtsyvypasj.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gtnuuivkxh.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gtiswuqztr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtvsznthyo.html

composer require --dev phpunit/phpunit
来源：http://dali.bjfxy.top/Article/details/gteyyeejdy.html

[U79] PHP：静态分析
来源：http://dali.xinyue.icu/Article/details/gtrnyromvc.html

composer require --dev phpstan/phpstan
来源：http://dali.zycfv.cn/Article/details/gtdxhkqfxn.html

[U80] PHP：代码规范修复
来源：http://dali.chenjidiqi.icu/Article/details/gtromennhr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenjidiqi.icu/Article/details/gtrczzaelb.html

[U81] JS：初始化项目
来源：http://dali.hnxiangtu.top/Article/details/gtkljxyvir.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gtoqqijhqw.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gthontcedp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.smart0.xyz/Article/details/gttarbgxbf.html

[U83] JS：ES Module 导入导出
来源：http://dali.xinyue.icu/Article/details/gtmimfenqb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtuvsnqrzw.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gtbbzepboe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gthhwlhdmu.html

[U85] JS：可选链
来源：http://dali.nanxuanxn.top/Article/details/gtdgulcvzt.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtspfouebe.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtqxezdsre.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gtjoaqylld.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gtcyzxusbg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gtkrigaons.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gtruknonpu.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtxjwhgbdc.html

[U89] JS：数组去重
来源：http://dali.nanxinkj.top/Article/details/gtptoltlqa.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtkyyirzke.html

[U90] JS：数字数组排序
来源：http://dali.tian-w.cn/Article/details/gtlyufraxu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtsxbkzeyw.html

[U91] JS：对象键值遍历
来源：http://dali.xinyue.icu/Article/details/gtpeniiahs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtjvvhkpbp.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gtuujbudbi.html

structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtkebdvmxr.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtwxcejnui.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gtqkqzqnzk.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtqcobxnku.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtroacudwi.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtzmkceksn.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gtjgdukkag.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gtlzalwnoq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvavbmyu.html

[U97] JS：并发请求
来源：http://dali.mhx1999.top/Article/details/gtyvjtulju.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtvqoygsky.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gtaikfiiuo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aibaodan.cn/Article/details/gtanprluuo.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtvtetjqwy.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiepqzra.html

[U100] JS：DOM 查询
来源：http://dali.ybcxt.top/Article/details/gtjtoalcpr.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gtelcmfezt.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gtrzchjzfv.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gtbtehqmqu.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtwtbhvelp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtmafuckvm.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gtbptbdeoe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtuzifubmy.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gttvprirne.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtamtmdivq.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtxtviksqb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gteynqfhny.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtjvhycbaq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaisagow.html

[U107] JS：数字千分位
来源：http://dali.xinyue.icu/Article/details/gtrawpckjx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtyuaaaumh.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtbyeclhav.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gttcgltlpu.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtqfqijztx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtrsfvxxre.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gtzbasfafa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gthojszdhn.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtifbblomr.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gtvcbupimk.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtgnczmfti.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtxfoyqmiu.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtzubfnofe.html

s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtpqjjnuwo.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzkngxh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtptydoxmg.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtoutjnbag.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtaovqagst.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ppjwa.cn/Article/details/gtwcrvayiw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdouzlxse.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gtnrqdvvhq.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtnzclumaz.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtyhbhcbig.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjymfbdz.html

[U119] JS：生产构建
来源：http://dali.guannengcc.top/Article/details/gtlvbizgme.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtmsrmpcvz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gttjvuauji.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtwxseoucs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlughyghz.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gttsyubrwn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkhtineig.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtknxtxypr.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gtxycbbfrk.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtryobkruo.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtskobuqzb.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gtnudleqbo.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtsofzwjoy.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtmejvxbrq.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtiajuqojp.html

C# ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtighoxswu.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gteiypuike.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gtrchbaxta.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gteojytemu.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulwysecf.html

Kotlin ......... 15
来源：http://dali.cucudq.cn/Article/details/gtoksmyvwa.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtykuzfaoj.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gtynhymjjx.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtfcobxvbd.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtexiroocr.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtawpfzbvt.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gtabntzxsv.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gtztnggtme.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtooyofpwe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtfnrwwxrc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gthscpuvdf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtqixwrsls.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gtrrvqixrb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtwcrpcmmb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtmgskhubw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtorlsotqi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtbtfnzn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtzrlejggm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtawktuoam.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtcfcjbvqz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtocdrsuqn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtjnvmgzxq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gtvoqtlpwc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtnxjntayp.html

Q SQL 专题                              90
来源：http://dali.daxiang520.top/Article/details/gtkzhfotgp.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gtdkigahif.html

S C / C++ 专题                          60
来源：http://dali.tianlin.xyz/Article/details/gtofnzcmzh.html

T 其他语言补充                          60
来源：http://dali.svipenyu.cn/Article/details/gtjpkvxpde.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtwpfluuwe.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtvohxschm.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtahezaafh.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gthrllbocs.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gtwxcbasxs.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtbtxxnxac.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gtroasmsdn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gtiqvwkrna.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gtbvcjispl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fzhhl.top/Article/details/gtdgejzdnt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenlongwang.top/Article/details/gtcxyalicx.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gtskbhruhq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqfisxwnb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtannkakom.html

Common Programming Examples Cheat Book
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwwlxuls.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtseevzbfj.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gtnoayjbkj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtcragdbxe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoqcuaub.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gtqiwldyxh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gtcbxybzlc.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gtnypslxei.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ybcxt.top/Article/details/gtlqiysezq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gtdxgctqqr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gtkaybwtns.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtvwshxqts.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtacdstdps.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gtybxdaztj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gtarzerups.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gtbaedhvlh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbldjqain.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gtrqhtywre.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenzaomai.com/Article/details/gtqnqoczfk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ppjwa.cn/Article/details/gtsjdxpchy.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gtkcbrflfk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gtrxoxnyqd.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtkfvaqczp.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gtlbdjlrfw.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdctlozvb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtwdnabwcr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gttzqavkdm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gthlyplnfe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtwncaefwx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbplmssbr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gtusclltvy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtpkzzpmcq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtqvpmiddv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtxgvrqluc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtzyyykndu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtlpennrgz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtnldsihbn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtgxctforw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtqbtbtccw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtualgebxw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowctujqy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gtnaotxedp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtfpwsfqja.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.havefunace.top/Article/details/gtgbrepojc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtsegteppo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtyvmcowgs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgoeipvri.html

A. 基础语法与类型
来源：http://dali.havefunace.top/Article/details/gtepfufuwh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpjtxmcls.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gthdqcqxkf.html

Py:   print("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gtqfqfpzre.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gtbhrqhdez.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gthrkccrlp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gotoacloud.top/Article/details/gtyvwgzikg.html

Java: System.out.println("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtjbahhwkm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtajsbsxij.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gtodlknghw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtrrqpvdft.html

[A02] 变量声明与赋值
来源：http://dali.nanxinkj.top/Article/details/gtewouwfin.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gttzhlejwx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ivvv.top/Article/details/gtizcssnxy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtzuawunyn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtmosrhzft.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtucmgsimt.html

Go:   name := "Alex"; age := 20
来源：http://dali.snrcjt.cn/Article/details/gtmjeanuxm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gtoidguezf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtdipomkxx.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gtvaqokcby.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtkgbiouqi.html

PHP:  const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtktbcicmf.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtxvfvhmbm.html

TS:   const PI: number = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtsloiwlqs.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtpucpsnrh.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtdsggtlod.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbekagvw.html

C#:   const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtytgtghjn.html

[A04] 判断变量类型
来源：http://dali.havefunace.top/Article/details/gtbstcalrh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gtqanqdxyz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gtgzybkyai.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dashuyun.cn/Article/details/gtqljuxnak.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtmycmunsx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtzapzulze.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtzstupfob.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.0kj1m.cn/Article/details/gtboclemtx.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtfzxjwbbg.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheqdsdrj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gttcmuqumx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtubprvpjw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtitgfznko.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtjbdfbezt.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtwksqoffi.html

Go:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtxqjhktfo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtsjduicxy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtntpatwnn.html

[A06] 字符串转数字
来源：http://dali.ivvv.top/Article/details/gtxeflrquy.html

Py:   int("42"); float("3.14")
来源：http://dali.aizwys.cn/Article/details/gtnwbjcfnw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yvedp.cn/Article/details/gtbinarqyx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj20258.top/Article/details/gtdklbotpm.html


<!-- 参考信息 -->