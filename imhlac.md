代发 wailian999

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gt2btkjsqkm.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gt2mrbwppfg.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gt2kooqirqm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gt2lolasxfd.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfxbvfim.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gt2rqnzyirr.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gt2mbjmqmpb.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ozmvubdz.html

[U51] PHP：数组解构
来源：http://dali.cqqwz.cn/Article/details/gt2jkvimpta.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gt2qdpmlywe.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2hivjvgyo.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2qjfeegqz.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gt2kqhnqnrc.html

$v = $a ?? $b ?? "default";
来源：http://dali.c1oappe.top/Article/details/gt2nvsxggde.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gt2zxcwmjph.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gt2rmswefha.html

[U55] PHP：match 表达式
来源：http://dali.cucudq.cn/Article/details/gt2ixqcykfi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixkerybr.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gt2elofnbaj.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2vikwcpnl.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2uhydbwdl.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqcimmji.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gt2jxrzoazu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.meibo888.top/Article/details/gt2pudslvne.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gt2ynarbzcz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gt2gompsyxh.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gt2jiwdsrci.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2sqqetixk.html

[U61] PHP：正则
来源：http://dali.jinqigfzy.top/Article/details/gt2bckcnjuk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2auvtduhe.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gt2redgxbbq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ybcxt.top/Article/details/gt2hryxfnrx.html

[U63] PHP：文件读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brhxwohl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gt2xwwzyiky.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyakwirl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hammf.cn/Article/details/gt2inphqifq.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svugwbgg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2yeznviyt.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gt2wdyzzmwx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gt2lkzhvgmn.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gt2wityoccb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gt2owiaiixw.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2evqqaash.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gt2xdxzgybv.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gt2brqmuhfo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gt2kicwtwkq.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gt2deudhrpb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gt2wjftqyfs.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2hlgmluak.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gt2paufhgid.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gt2aclfigma.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guowangkeji.top/Article/details/gt2rmnpgohe.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2sdmcqsfr.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcllivhl.html

[U74] PHP：读取环境变量
来源：http://dali.iojbl.cn/Article/details/gt2uvnuhcqs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guannengcc.top/Article/details/gt2xlxmhvhk.html

[U75] PHP：依赖注入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uodffris.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gt2cbakfscj.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2awsrdfrz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gt2opvczneq.html

[U77] PHP：模板渲染
来源：http://dali.redwolf501.top/Article/details/gt2hgymaedv.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gt2liwpkmjh.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gt2xzlzcfiq.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jirczofs.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shfozlmj.html

composer require --dev phpstan/phpstan
来源：http://dali.hnqzz.top/Article/details/gt2sanjqzry.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnavfiws.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gt2msemysew.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gt2ygylbgfl.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gt2wohhcbtb.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gt2bookrdsf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gt2ilhuqyoj.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gt2qcihokyx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gt2jcewlnnj.html

[U84] JS：CommonJS 写法
来源：http://dali.nwbrower.top/Article/details/gt2lpwoyvqy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phtobspc.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gt2mgibildo.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gt2rtpwurvm.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gt2slcywnrx.html

a ?? b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcpqpsxp.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gt2ehjjzqfm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.andypj.xyz/Article/details/gt2kybqgpuk.html

[U88] JS：对象展开合并
来源：http://dali.dianchejie.cn/Article/details/gt2ozcndaad.html

{ ...a, ...b }
来源：http://dali.hywenlv.cn/Article/details/gt2rfccxbni.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppljlena.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2fhxtjenv.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gt2oaliyler.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2dqgmjmdx.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2awfydktn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gt2tupwmset.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2lqouvsqq.html

structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycuxulwd.html

[U93] JS：模板字符串
来源：http://dali.shuidangran.top/Article/details/gt2munraevu.html

`共 ${n} 条`
来源：http://dali.yuxming.cn/Article/details/gt2muospnhh.html

[U94] JS：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2emfgbcly.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2pqlwuqha.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gt2dyiegnxw.html

new Promise((resolve, reject) => {})
来源：http://dali.fzhhl.top/Article/details/gt2eurkjvwo.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gt2djojysjw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2byrulnke.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gt2hgaqjkre.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2ziefjesb.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuxming.cn/Article/details/gt2nvxumttj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2lynhrshf.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wewtiunr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2axhwcnuc.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gt2fxvyljly.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gt2fnpjoozg.html

[U101] JS：classList 操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvnahaid.html

el.classList.toggle("active")
来源：http://dali.tianlin.xyz/Article/details/gt2axpbbcdp.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gt2gxzyrtir.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gt2mczarlrx.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gt2ggwfuyvd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2pqroidow.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gt2fdgdeemx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2csnkuvuj.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gt2ivupprtn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2lxmhjlxa.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2xolwktnm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfdfwviy.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2ijgmjmdr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eicjfqcq.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gt2zorqxtxo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvahceny.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2hczvrrgw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2hlzebgqk.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gt2jmjqlzhc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gt2igwvzetv.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gt2wzofsdpq.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gt2byxvbava.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gt2wjytvqkh.html

"7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2uvdyqwox.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gt2seiyihdx.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2pgvtbget.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2krfcctev.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2wyrucdeg.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjbrsbrs.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2xwfzbeet.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gt2zrvuxvuo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gt2krqtmcub.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcmrfxyw.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gt2geegbkpx.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gt2ajpoemoa.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gt2ahwvxnta.html

[U119] JS：生产构建
来源：http://dali.hnqzz.top/Article/details/gt2sezxsswn.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gt2hwgkbjyz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gt2lxoktdsl.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gt2hfskqlfc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2eghrmobi.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gt2qapichzi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwaylhbo.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gt2qcfnrcby.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2amnimeyp.html

PHP ............ 252
来源：http://dali.chenzaomai.com/Article/details/gt2twwhknrc.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gt2azwyzwiu.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gt2ojcnlxxz.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2vxjiplbv.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfoftnpo.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2liffcooy.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2lqesohxb.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gt2zzfofdzh.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcjzkhyf.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gt2scwzcazo.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2vvyqqkji.html

Kotlin ......... 15
来源：http://dali.chenzaomai.com/Article/details/gt2jvpgsnan.html

Swift .......... 15
来源：http://dali.snrcjt.cn/Article/details/gt2csnkrrot.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krbnjiqt.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gt2pdxnakzu.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gt2xtrtejox.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2tnvweazz.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykmqjjam.html

按章节统计：
来源：http://dali.nanxuanxn.top/Article/details/gt2zkxssseq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gt2sfzvudif.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2gzhxqphj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2ftecfbka.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2dbdipgpv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gt2fzkzfeco.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gt2svdveowi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gt2yasetiqu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gt2rfcjbphm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqygvvro.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2zzjzvfhc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2cbsrgfym.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2ouxvgnlb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2ulhszndg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gt2kpkopkcs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gt2yrbhhxqw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2dwtfeojo.html

Q SQL 专题                              90
来源：http://dali.ehwqpu.com/Article/details/gt2hrvozilp.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gt2vdjfdonu.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gt2ocsojygk.html

T 其他语言补充                          60
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgzrqawb.html

U 高频实用片段                         120
来源：http://dali.ybcxt.top/Article/details/gt2iwitsdnz.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2lgwtwmob.html

合计                                  2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2qahatphc.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2cuipfedx.html

使用提醒
来源：http://dali.jlsjyb.cn/Article/details/gt2ihfbiori.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2jslqgwzj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhongyouzk.top/Article/details/gt2aiwmiacv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.bjfxy.top/Article/details/gt2tyqrtqmc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dianchejie.cn/Article/details/gt2ottkqskv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daria6918.cn/Article/details/gt2ieqpvcqp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gt2hphjvcau.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gt2hazyfnob.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2epponqwa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gt2vspvfxqw.html

Common Programming Examples Cheat Book
来源：http://dali.nanxinkj.top/Article/details/gt2vplezmdx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xoypjpei.html

【收录内容】
来源：http://dali.chenlongwang.top/Article/details/gt2cyppxlnj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gt2oabinppp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gt2hhdztsac.html

SQL · Bash · C · C++
来源：http://dali.wangdashe.top/Article/details/gt2vgwvegxw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gt2zorpgzwt.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gt2cellpzsi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.havefunace.top/Article/details/gt2hmndzlkv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhongyouzk.top/Article/details/gt2kthrftpe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gt2wgdujsvp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayxxevrh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gt2otxgzgpm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gt2qppojcij.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gt2yznmdezo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yanxiufei.cn/Article/details/gt2lhnisusg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gt2etndncfs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gt2cqyugrnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gt2qomyprdm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gt2eotoiodu.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gt2kawwteun.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gt2piyzuuws.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2qgxbtwqy.html

目  录
来源：http://dali.cheryme.top/Article/details/gt2ioxqbays.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2btaxfosy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2oefhnvdt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2qhnnbczl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gt2vkqlnhyu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gt2blifylsl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gt2tuyavixq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gt2rfvglpkp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2rrezrxgh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gt2hkimnmrq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2gbehqdjs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2yscysynk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2hkxcqusa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2prdognvb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2saweljzz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2rlddyedq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gt2hennfqca.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2evrikksx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daria6918.cn/Article/details/gt2bcbkkmoy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2jpnyqpux.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gt2fxvezhyy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2jnevhbxn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2ljvodywr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dnljsgqf.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gt2koiarzrx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2eqshvwko.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gt2cqjbtete.html

Py:   print("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gt2pkuudhlu.html

PHP:  echo "Hello, World!";
来源：http://dali.pycfn.com/Article/details/gt2pzxkscoq.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2idpmuijy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mghkhwwj.html

Java: System.out.println("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2zgbexvea.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2zsyqmhbn.html

Ruby: puts "Hello, World!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztaxzpgl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gt2gffvsyit.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtxlezvg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gt2pibhmoxe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2fmavozzj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tanke756.top/Article/details/gt2vikjakoj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gt2zltdybum.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2ruqihxne.html

Go:   name := "Alex"; age := 20
来源：http://dali.jyoumei.cn/Article/details/gt2jrjvdddf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gt2ywojnwmx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2ztkuqhwd.html

[A03] 常量定义
来源：http://dali.andypj.xyz/Article/details/gt2nwhdbtlw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gt2figauopb.html

PHP:  const PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsnxsgwu.html

JS:   const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuqfufni.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2rjotacrx.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2qvcxxocw.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2mqylcanb.html

Ruby: PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gt2hrsxzmmd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfeypqbc.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybzpedrr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zycfv.cn/Article/details/gt2nykwnjqt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gt2pluaghqi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxlagsxi.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2brhnnjvy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vynkfvow.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gt2tukewdzu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.redwolf501.top/Article/details/gt2volseulw.html

C#:   x.GetType().Name; x is int
来源：http://dali.0kj1m.cn/Article/details/gt2ihvxxbew.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gt2dubmmykt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cqqwz.cn/Article/details/gt2yohaymmp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2itlyjyrb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2yycmuzts.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2gazalkdg.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2mojzrmhf.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2utfbcmre.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpytwsnt.html

C#:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2bgckwflx.html


<!-- 参考信息 -->