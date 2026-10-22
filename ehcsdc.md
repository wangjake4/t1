代发 wailian999

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2bewnlxte.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2xtxdycut.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gt2dacsstgf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gt2eywanowu.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vylidbxu.html

public readonly string $name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbriosfz.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gt2jbqcyobc.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bxervxew.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gt2aprovuod.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gt2hjdgufsg.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gt2jnfwtiks.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2qwluqhhc.html

[U53] PHP：空合并运算符
来源：http://dali.ehwqpu.com/Article/details/gt2asxdhgxt.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gt2vdgosuxt.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gt2dxcbnepf.html

$obj?->method()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xohcxuum.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gt2motmzkoi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gt2jcicvjda.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gt2licbfuac.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2xhuebprn.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2rucjyluw.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gt2byryvjqg.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gt2bgunysto.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2yqskudkp.html

[U59] PHP：自定义排序
来源：http://dali.yanxiufei.cn/Article/details/gt2olsbtlar.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2njapuqlc.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gt2ppfvummv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gt2dsvpdufe.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gt2cjogtiil.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2vpcfsbgj.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrvidyab.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gt2eliuqxsl.html

[U63] PHP：文件读写
来源：http://dali.jianghu66.top/Article/details/gt2hmczytzq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gt2yefhgdrc.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gt2omdpnsjv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gt2mlojdtng.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gt2tloyphwp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2qlabrvcs.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gt2nnoozucr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gt2lgptomoj.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gt2dnmzusnz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gt2dztseixj.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gt2uqgwtxqc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gt2kyzicrir.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigfzy.top/Article/details/gt2eqdqsdty.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gt2xnjnoalj.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzbuovky.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gt2ayuwrrjl.html

[U71] PHP：抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2wviwtray.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2qpngraeq.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gt2fgzrrowz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gt2husetjbe.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gt2qkwrqesn.html

parse_ini_file("config.ini", true)
来源：http://dali.hnxiangtu.top/Article/details/gt2gctbmaiq.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2vdwmrdnm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gt2euiejoor.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gt2qdndrttt.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gt2qbjrohky.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gt2ijgimcyp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gt2awexgdci.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gt2xjozyqzi.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gt2ysithcos.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gt2xpsdqxhi.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gt2gztzwmql.html

[U79] PHP：静态分析
来源：http://dali.yonumen.top/Article/details/gt2oceyrkdx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezxrcfze.html

[U80] PHP：代码规范修复
来源：http://dali.hammf.cn/Article/details/gt2kmpvyqvl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gt2zycpfrim.html

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gt2vyzcddpu.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gt2okbwwvrn.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gt2waixhdkx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gt2vfyksgii.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gt2fewqerkl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2xuqcwrli.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gt2bwlzagrz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gt2ljestgcg.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2ozfpocsi.html

a?.b?.c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjacknph.html

[U86] JS：空值合并
来源：http://dali.9152youxi.cn/Article/details/gt2qelldqwa.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gt2khrexezx.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aufhktvl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gt2vpjjzvpw.html

[U88] JS：对象展开合并
来源：http://dali.xuanzx.com/Article/details/gt2ediuyhnc.html

{ ...a, ...b }
来源：http://dali.jiagoushi.top/Article/details/gt2fezcqejf.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbcgjdke.html

[...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2qgciruxc.html

[U90] JS：数字数组排序
来源：http://dali.mhx1999.top/Article/details/gt2wjrzupuu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2jkcyftch.html

[U91] JS：对象键值遍历
来源：http://dali.andypj.xyz/Article/details/gt2qmadwupj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gt2asoqyrdj.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gt2rhuirpqc.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2dmmuddme.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gt2yikhongr.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gt2tkgjpfmm.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gt2aqhoptqe.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycvknsil.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gt2hwytkmkp.html

new Promise((resolve, reject) => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnhigknj.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzesxzfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqitixab.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gt2apxzyxty.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2vnqiydtf.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2txcxbxcs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzlbpnlc.html

[U99] JS：事件监听
来源：http://dali.jinqigfzy.top/Article/details/gt2qgsgevki.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2owegffej.html

[U100] JS：DOM 查询
来源：http://dali.zhoulong.xyz/Article/details/gt2vhyokfqp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkqvuks.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gt2eyrmxpen.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gt2injtjahq.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gt2rnvjxvgf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gt2vcrnlnpl.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2rfrrsjti.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gt2hzlzjrkp.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gt2lhvgkttp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2acmdxepv.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gt2dswlybag.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gt2ddnnmjdt.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2yyiikdev.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2lhtrpsuz.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gt2bdxicrxt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dynxjrex.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gt2czooohgj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gt2ndkoysum.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gt2frymfshg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2xlcuowkj.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gt2fundnwnv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gseswrht.html

[U111] JS：对象转 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2iqlxdccx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yncloopa.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gt2zmlscudg.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2mkbzjlhl.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zblizalc.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2znqeeahp.html

[U114] JS：JSON 深比较
来源：http://dali.shzxlz.cn/Article/details/gt2mrhdgemg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2noknbxlx.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2ocbgcnyw.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2zwwoqvxg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gt2qbdbcbsl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xuulmbpu.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2abvdgwsz.html

npm i -D vitest;  npx vitest
来源：http://dali.shuidangran.top/Article/details/gt2ubvgucrv.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gt2dhppxpio.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gt2nnwplinl.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozyqzufs.html

npx vite build
来源：http://dali.xinyue.icu/Article/details/gt2cjinhkor.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gt2ispcmxey.html

import.meta.env.VITE_API_URL
来源：http://dali.zhoulong.xyz/Article/details/gt2wfkfghwj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2eowaimmd.html

统计汇总
来源：http://dali.gzhubu.top/Article/details/gt2zwqgxdqw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vupuckjw.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gt2aeyajwyz.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2wurbwatm.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsoqjnqt.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gt2pacjnwdp.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gt2mcxzqugi.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2xrvkbaga.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2cyagcxmh.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gt2cmrimqlt.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2xmqvxsvz.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gt2tlbysqps.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gt2lidmdeag.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnyzylyh.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gt2jwoukzoi.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gt2pesuppjp.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sufmoxsa.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gt2bvhuwzdw.html

Perl ........... 10
来源：http://dali.redwolf501.top/Article/details/gt2scbopnck.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gt2nwoendte.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2sfcunxzd.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2bxhcpknp.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gt2axgniapk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2bnpciaqe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gt2pkolxkqc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gt2ufaaidft.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2aaloouob.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yanxiufei.cn/Article/details/gt2dzfhpstx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2bfzkxtjs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2yztacmtl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gt2zyfrcgkl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2fxitmkkj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2bojzslit.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2gewmihug.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2thxfdjjy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyhyhdxd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gt2vwhcomvs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shzxlz.cn/Article/details/gt2nwndeebn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ocejhnnn.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gt2gsfnkfyx.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gt2bckocuqh.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gt2ggwlaxwq.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gt2yoloycms.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gt2wfpfrufg.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2xtsdurfs.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2csjrwhco.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxxfryvd.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptdywelj.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2lummmitw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gt2ystgldbu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.birdmap.top/Article/details/gt2ivhhcows.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gt2ryvublbw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gt2oxvhuvgn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gt2vprcoaco.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gt2gqfmsdci.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2gssnomsw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gt2gbkcoqcy.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gt2tsyveetq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gkesobuo.html

【收录内容】
来源：http://dali.hnxiangtu.top/Article/details/gt2qegbohhp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhyhkndx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gt2srjwxtup.html

SQL · Bash · C · C++
来源：http://dali.jinqigufen.top/Article/details/gt2vracmmea.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gt2avrutamc.html

【使用说明】
来源：http://dali.hammf.cn/Article/details/gt2xnugpcnt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gt2nekasain.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2vpzpxdah.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gt2wmbnclyt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gt2omvodwvu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cucudq.cn/Article/details/gt2ggbzxvbx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.316326.xyz/Article/details/gt2euhhvnbk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gt2utuhayyn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gt2xugqxjhv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gt2jprrjjxr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxinkj.top/Article/details/gt2siaxaatf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dashuyun.cn/Article/details/gt2ebiqmaib.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shzxlz.cn/Article/details/gt2krnqdrko.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gt2fymxgapx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sxryk.cn/Article/details/gt2jxfgycvi.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2haaqbdvt.html

目  录
来源：http://dali.hammf.cn/Article/details/gt2tvbncmuh.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2dpmgmoqs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gt2vyqhahky.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gt2epsreois.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2hdyrdyjp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gt2ornrniov.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gt2arvmbatz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gt2oldmjpca.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2krtfualn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2wsmolfus.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gt2gxflffng.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2cffygeid.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2dbspogne.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2likaaysx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2baivchez.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2umjcimky.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pycfn.com/Article/details/gt2mvdbkali.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gt2tjcqiuat.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gt2dqiaxwnq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyhybqwc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gt2uevfdzkp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gt2eoyyjlff.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2ufsacroj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2badzyapy.html

A. 基础语法与类型
来源：http://dali.yj20258.top/Article/details/gt2mjlcqaqh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qakgwrmf.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gt2yklkxuak.html

Py:   print("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gt2bwszjxdk.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gt2prlivqvr.html

JS:   console.log("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gt2giqtueqf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gt2ebdfcems.html

Java: System.out.println("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gt2fdqcholw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gt2naxyxita.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gt2fhxvgrsa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gt2uqcaegcr.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gt2xgafbxxt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zdqjudy.top/Article/details/gt2yuyjtskn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2pyiaknaq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2wuikunzm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gt2yojvczkf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gt2ywgsomgz.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gt2xaijyxxj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gt2xlnajnty.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gt2mhibzsyr.html

[A03] 常量定义
来源：http://dali.zhengqikj.top/Article/details/gt2miwdzwqr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj202588.top/Article/details/gt2tljobmnj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2jfwjsixb.html

JS:   const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2vapargwr.html

TS:   const PI: number = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2keyxlyzc.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2lnmrzmpt.html

Go:   const PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gt2dhmbbjga.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjgvmyef.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2vhxsuktz.html

[A04] 判断变量类型
来源：http://dali.jinqigufen.top/Article/details/gt2kezbsnri.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gt2clayvscx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2iwsemlxv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olhjxjua.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gt2qmivawwv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gt2qnqigedd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gt2pwciybpn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gt2sgetfuim.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gt2kyhswmlb.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gt2ymuutttd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jlsjyb.cn/Article/details/gt2jftcdfch.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2qsmnulsg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2cybtgeel.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2zzunsiam.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2yanxhlud.html

Go:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2uemtczha.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2tsotmmpd.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2okpnkhmb.html


<!-- 参考信息 -->