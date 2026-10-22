代发 wailian999

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gt2eejqwmxi.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gt2lmndcfca.html

[U52] PHP：箭头函数
来源：http://dali.cucudq.cn/Article/details/gt2xrroblvs.html

$double = fn($x) => $x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2akbegypp.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gt2okwwxsxl.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gt2schfomza.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gt2lqizxdfs.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gt2dlqvihuj.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2rzuipspv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2ascclxnl.html

[U56] PHP：命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkujtmqq.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckzcdbcu.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2povjggij.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gt2twatqkbf.html

[U58] PHP：数组三件套
来源：http://dali.daria6918.cn/Article/details/gt2hfvhibpp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gt2krcyemxt.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gt2xfxoolcy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2wpzeetwq.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gt2bznaaxjk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gt2jsbnjvcp.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gt2qfjqgyzt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2mkaadamv.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gt2xgdoarfq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gt2kqwdixtu.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlbaiyzk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqppbruf.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gt2oampbhlc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gt2stwkidsw.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gt2aymsaucp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2hkhzcplj.html

[U66] PHP：设置 Cookie
来源：http://dali.mhx1999.top/Article/details/gt2puohconm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tayvgbam.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2udaxmvfi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ehwqpu.com/Article/details/gt2ppazobul.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gt2phqstmtq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gt2lzchzljl.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2gykdnpsl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxinkj.top/Article/details/gt2sfnafpcb.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gt2bmfcvvro.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sweek.top/Article/details/gt2afliodgu.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvvvlapf.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgfzy.top/Article/details/gt2ybdepphs.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gt2ickmvzzx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gt2nhmmdjga.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2oufloqbi.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gt2jqcugbtv.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2jbjlayic.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gt2cbhaahue.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gt2smypwwgy.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gt2eprmrips.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gt2exewcvis.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsmjoqee.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2cmclhzia.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gt2ipnaplvu.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2oesvxxei.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gt2ohevyilz.html

[U79] PHP：静态分析
来源：http://dali.dashuyun.cn/Article/details/gt2igokdanu.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gt2dhhqexpc.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gt2toblcrbu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gt2eqvhlucy.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gt2bptzmuwb.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gt2qslkrpqs.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gt2yzunkivv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhixingplan.top/Article/details/gt2avlsviwg.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gt2ztzejncc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2ejnwbmfh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhixingplan.top/Article/details/gt2hzbjpxdc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gt2ghouetwp.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gt2cjclnhir.html

a?.b?.c
来源：http://dali.daxiang520.top/Article/details/gt2brtliwnf.html

[U86] JS：空值合并
来源：http://dali.0kj1m.cn/Article/details/gt2nxgizvbu.html

a ?? b
来源：http://dali.tianlin.xyz/Article/details/gt2isyspkkb.html

[U87] JS：解构默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avdtsull.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gt2wvabvbsw.html

[U88] JS：对象展开合并
来源：http://dali.yuxming.cn/Article/details/gt2angtlmzz.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrcinbwg.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gt2exouhmzq.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2jvknkijh.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gspxmxdz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2kmoosfnl.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dukqftnv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gt2zwyhykwp.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gt2onltovap.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wwcwzpej.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gt2ppbgmtgg.html

`共 ${n} 条`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgbuljxj.html

[U94] JS：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gt2yhomkbgm.html

const double = x => x * 2;
来源：http://dali.cdnleiting.top/Article/details/gt2crdhkjyi.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gt2kdvhftso.html

new Promise((resolve, reject) => {})
来源：http://dali.dianchejie.cn/Article/details/gt2nkcydzsy.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2qfuppdnn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2zxalebti.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gt2kmrgytxi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2bhemuqip.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2fjaxmhwc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gt2nwilugez.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gt2nzvauold.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsetrwkf.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gt2qyzjfbar.html

document.querySelector(".item")
来源：http://dali.sxryk.cn/Article/details/gt2rqnyfwft.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gt2bduwqahz.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gt2spgargqq.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gt2axmdctxg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zswfmcvn.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2hulycuzj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gt2ntzmttjm.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbjvtlru.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2gfmpivhw.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gt2tyyfxpol.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.haohaochexian.top/Article/details/gt2bbhimopw.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2abiqfjdx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yangfankeji.com/Article/details/gt2tistqnkq.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2lbcxxqnb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yonumen.top/Article/details/gt2lbexhzpc.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gt2rmugdovy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cdnleiting.top/Article/details/gt2pvsnqdxj.html

[U109] JS：数组分组
来源：http://dali.haohaochexian.top/Article/details/gt2bndenxua.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gt2ytxsumul.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2dnbuhagy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gt2umjkaguw.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gt2vvvyaijh.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gt2ylqnykif.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gt2sesiryqv.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2wcyksztu.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gt2rpkbtcyh.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2cpacwumd.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gt2ixydbgkl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gt2qciscnet.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmonsgks.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2kopezibp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gt2amvkectq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gt2fzddwiba.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gt2kozzqqlp.html

npm i -D vitest;  npx vitest
来源：http://dali.kuanghao11.cn/Article/details/gt2hkjhazev.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gt2vwzjbowj.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gt2udicptwd.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gt2gnpjamxr.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gt2uzvnmylv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gt2jxqromap.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gt2uuubkzys.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2glohgmjv.html

统计汇总
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyyqqgdi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vcjrculz.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gt2ghfzgvle.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gt2rrcjskzt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkzfsmm.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gt2whklbbqm.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gt2omqqcghj.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2usjylnys.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2jafyvffh.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2wdmztzsg.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gt2ccqgwfyu.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gt2jnbpwtur.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsvpzvxp.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gt2waddnnru.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmfgfcyn.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gt2omvpwtbl.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2soiybour.html

Lua ............ 10
来源：http://dali.hnqzz.top/Article/details/gt2cnwryjhw.html

Perl ........... 10
来源：http://dali.hammf.cn/Article/details/gt2tabvuinx.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2gdtckfqe.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2hwmhjsge.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gt2enmpsxac.html

按章节统计：
来源：http://dali.gzhubu.top/Article/details/gt2gwyvvqnn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2vrujysrp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzfkklix.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2mghuwwtx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gt2uyeulbfr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gt2cfeucivs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2yspgigka.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqdkygq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gt2wsjuvuzd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2qmnklzgk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gt2bkyrrcyp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2dahgprbj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2ncdrjibc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2lcekhcej.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gt2ukvpchos.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hfpthk.cn/Article/details/gt2aifbvrxw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2mbndwmcs.html

Q SQL 专题                              90
来源：http://dali.xinyue.icu/Article/details/gt2mbmxioty.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gt2tlqccldx.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gt2invoqiar.html

T 其他语言补充                          60
来源：http://dali.nanxuanxn.top/Article/details/gt2fwxnkqlq.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gt2hmrqtsnd.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mglsdyps.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gt2rztbwevc.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2mzjmjeer.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gt2dzpmlsyv.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjdzfcer.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.redwolf501.top/Article/details/gt2qmrqukly.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylqjysac.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gt2ichkcjyq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gt2lkjlilfr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gt2vntfqemw.html

—— 文件结束 ——
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icvsjtee.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wemziomy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gt2onldqmyr.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gt2sqpohvgx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wjtgxoey.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpzlcdn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gt2izcchlnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gt2apcqmylh.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gt2toufvviu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.316326.xyz/Article/details/gt2jeqpcxsx.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gt2sbvqnhev.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gt2fskxfzhs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gt2cgunfrpo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gt2kjcnnuff.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.quarkkingdee.top/Article/details/gt2lnnntslt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gt2tmnebnzs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gt2zolgekvt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgjowvzm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gt2eyzxttev.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.redwolf501.top/Article/details/gt2xtnvnxnm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gt2sobgtadc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gt2rbtwxzgl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.svipenyu.cn/Article/details/gt2dfsgbfjw.html

【文件统计】
来源：http://dali.svipenyu.cn/Article/details/gt2kivmrlao.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gt2yujjcxhv.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amcxjtju.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gt2oxvvrjyd.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2mftegtqk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.9152youxi.cn/Article/details/gt2hieddzkh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqutikoz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gt2xrodajep.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gt2hhzpkxrd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2thvafgpz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gt2eslznwet.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gt2ysjbugrm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gt2evmuhwpl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2yplrtbtv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2pawxeaxv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2wnqngktw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2cpkagkqt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2utjpizsr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gt2yjictyai.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2msqrcjql.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2hopyuibo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tian-w.cn/Article/details/gt2mafwmfkx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2qfelivta.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.svipenyu.cn/Article/details/gt2zieglchw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2jalqyygd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2iuogolwa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nqgqhehc.html

A. 基础语法与类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouftdabw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2tyybjufe.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtchzoro.html

Py:   print("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gt2iftlldfm.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gt2pyqspuni.html

JS:   console.log("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gt2ghhaedgg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gt2twoaqsex.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbvsennh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gt2ulrokdog.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gt2eemfzpih.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seeqocoh.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gt2aazotfqk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gt2xznihphh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2jachwbyn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2mzegfxeq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2eeuqasdk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2pyikigoa.html

Go:   name := "Alex"; age := 20
来源：http://dali.sxryk.cn/Article/details/gt2seoqfrux.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yongpay.top/Article/details/gt2ngpbeyeo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnfaxivn.html

[A03] 常量定义
来源：http://dali.ybcxt.top/Article/details/gt2khxwcocf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gt2ypngysyb.html

PHP:  const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2mrmrvxcp.html

JS:   const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2jndyvlwe.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2czqoduyc.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2rwmijllg.html

Go:   const PI = 3.14159
来源：http://dali.shuidangran.top/Article/details/gt2vbqlwqdh.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gt2hcyeoltk.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2yopqctjz.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gt2hpurgzyc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daria6918.cn/Article/details/gt2gcvusyxz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwxyrtqx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gt2lyeypmjj.html

TS:   typeof x; x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gt2qqtvtxyt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhengqikj.top/Article/details/gt2yafdlfds.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gt2ysbgdrwm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gogol.net.cn/Article/details/gt2ztuyllul.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gt2khstebfs.html

[A05] 整数除法与取模
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahsnrpmi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gt2tiwieutl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2ctvwatvz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2wxscbaua.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2ihhhhtpj.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htaezher.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtjordmj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2fkmpntsn.html

C#:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2rzossuzj.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2mdezflzs.html

Py:   int("42"); float("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2rxwkzyrz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2ivvvqueh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yueranfly.top/Article/details/gt2hbxpivue.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gt2kkjwfvfx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gt2ffbuhcaz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.svipenyu.cn/Article/details/gt2brodiqww.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yueranfly.top/Article/details/gt2nmbjfbxd.html


<!-- 参考信息 -->