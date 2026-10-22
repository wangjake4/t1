代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcmzwgob.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gt2uphvfmpc.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gt2lqpxoaia.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dftuiaec.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2zyjqtexi.html

"值: {$a}"
来源：http://dali.jlsjyb.cn/Article/details/gt2crfvpcob.html

[U58] PHP：数组三件套
来源：http://dali.pycfn.com/Article/details/gt2zddonayp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fengsongda.top/Article/details/gt2hnqqwwov.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gt2phdflvnf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2pnbhjwpm.html

[U60] PHP：JSON 编解码
来源：http://dali.ivvv.top/Article/details/gt2xszxzeyf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzxsuvvn.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gt2zfkcytgo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2lqqshneg.html

[U62] PHP：日期对象
来源：http://dali.sxryk.cn/Article/details/gt2vgducwgu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yueranfly.top/Article/details/gt2ebejhdks.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gt2kttfwiig.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yonumen.top/Article/details/gt2ownwggug.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gt2lcbluzaw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmnpkttx.html

[U65] PHP：会话
来源：http://dali.shuidangran.top/Article/details/gt2qaqksxml.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2bahzgnlp.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gt2tfpflvwv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gt2bzeaahpy.html

[U67] PHP：处理文件上传
来源：http://dali.ivvv.top/Article/details/gt2uvlqvxkp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zdqjudy.top/Article/details/gt2vhvqkazs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhqyrig.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuanzhike.top/Article/details/gt2rohxcslb.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gt2yrfaarti.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtgctolh.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gt2xyqzxygh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gt2bextjeyl.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gt2wgvccveo.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2lzjjucft.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gt2xzfalzup.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cheryme.top/Article/details/gt2gdspieks.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gt2vdtohzya.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gt2rqanucvc.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zywitjeg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gt2ianjtibc.html

[U75] PHP：依赖注入
来源：http://dali.sysykeji.top/Article/details/gt2zlzlrazt.html

composer require psr/container
来源：http://dali.cucudq.cn/Article/details/gt2mkszjmui.html

[U76] PHP：简单路由
来源：http://dali.hywenlv.cn/Article/details/gt2rtzccpyz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhcqyype.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkawjfcb.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwcbhthy.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzyvbpow.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gt2gkewrqrq.html

[U79] PHP：静态分析
来源：http://dali.havefunace.top/Article/details/gt2almkwuol.html

composer require --dev phpstan/phpstan
来源：http://dali.pycfn.com/Article/details/gt2zxvdqvzq.html

[U80] PHP：代码规范修复
来源：http://dali.haohaochexian.top/Article/details/gt2ntcekkqd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gt2xeydeeab.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gt2lstmcoau.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gt2zktlaxrv.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gt2apbdbnog.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olysmkxb.html

[U83] JS：ES Module 导入导出
来源：http://dali.quarkkingdee.top/Article/details/gt2hiauvmbg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2cnmamzfx.html

[U84] JS：CommonJS 写法
来源：http://dali.yanxiufei.cn/Article/details/gt2eqwundyn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gt2qgvyrxbh.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gt2hsrljwui.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2zrcebxsd.html

[U86] JS：空值合并
来源：http://dali.ppjwa.cn/Article/details/gt2loguaycy.html

a ?? b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqbcytqw.html

[U87] JS：解构默认值
来源：http://dali.hammf.cn/Article/details/gt2bbumozmp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gt2qobhxqcg.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gt2mnslodlt.html

{ ...a, ...b }
来源：http://dali.fengsongda.top/Article/details/gt2hdhzqsth.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2emajgtxt.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2jzfcukqb.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gt2thmibvld.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2xgmxdbkb.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gt2kkktkenx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgliptss.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2cjcafdks.html

structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2jsqzhbux.html

[U93] JS：模板字符串
来源：http://dali.ydzc1.top/Article/details/gt2kgbwgrxt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2avwtdsqw.html

[U94] JS：箭头函数
来源：http://dali.iojbl.cn/Article/details/gt2ztumqckj.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gt2ewrqxsod.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gt2stkfuffl.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gt2orwqzimo.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvppyxbk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2vvirpdnt.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gt2umgspcku.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2ymnpsedi.html

[U98] JS：fetch 带 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2jbckaore.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2lpuftjsp.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gt2kenaatft.html

el.addEventListener("click", e => {})
来源：http://dali.iojbl.cn/Article/details/gt2yrixjtnv.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gt2onxymaah.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gt2mvroerqz.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttcvirbz.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gt2zgutxneg.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gt2gcybmlic.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjimgwjl.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gt2dzbkteif.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gt2wqstntto.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gt2dvrdnebm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2xtugluaa.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gt2ntsqhtqv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gt2mtovxhtf.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2qykhrwnu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gt2yigyylrk.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2bptrepqx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2unmdjvxq.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gt2aabihmrh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gt2oacyxqzu.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gt2xryfqhmr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2mclrsrxb.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcphvtmz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oawxqtjy.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gt2kytudxvt.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gt2fobosdse.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gt2ybmibaag.html

"7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2gkjkhhmo.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gt2pwbknpzb.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2oholichv.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szntkwtc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2pwrqyxst.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gt2tudllnnw.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2qbxrffpq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yizgdjyx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2stteampn.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gt2cokpqlor.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2wcvwpmnq.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gt2woufdggt.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2tdvavbxy.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2vnqspybq.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gt2ebphdtvu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sysykeji.top/Article/details/gt2awdrxyyo.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gt2ogsexvmg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2cldqommf.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gt2ogzidaaf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wibosckx.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebusyjil.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdvzswxs.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gt2ppsnffai.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gt2apetxibk.html

TypeScript ..... 212
来源：http://dali.iojbl.cn/Article/details/gt2jyhndapq.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2llileakk.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2fqhhnxwu.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gt2cyhnowzg.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gt2ptvspxwr.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gt2pyltvpco.html

C++ ............ 30
来源：http://dali.cucudq.cn/Article/details/gt2cuafnyvh.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gt2datstqiz.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gt2ikzfjqwc.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxrujlle.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gt2dyzzxxfs.html

Lua ............ 10
来源：http://dali.dashuyun.cn/Article/details/gt2dhcvdbdm.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2rwhakoir.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcnotxeq.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2oshsfzvk.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gt2dxjjqgwb.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gt2rjsanxpw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2wbbxdwgs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gt2pnbkuxzd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gt2vriefqco.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gt2zmeeobeg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gt2urcuihas.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gt2qwzzbhho.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2nrdzryql.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2izwpacmx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2eljiitno.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gt2zoenqupp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2tkrgvpmt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2wqapvoob.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2fytprflm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gt2corqghif.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gt2dhckelsj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2lfhcmdzr.html

Q SQL 专题                              90
来源：http://dali.pengpengdd.cyou/Article/details/gt2huiawmli.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gt2sxitreju.html

S C / C++ 专题                          60
来源：http://dali.gogol.net.cn/Article/details/gt2zbstesti.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gt2lcnzyuiq.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gt2oypzreiz.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2nupafidx.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gt2mztusutz.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdgvydjz.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gt2abviuyrj.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2ltvepvdo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gt2kmlgdtga.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gt2ajzcowue.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gt2vqpijffm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gt2xatoocwg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yueranfly.top/Article/details/gt2bzibvbhc.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gt2qzpfrqfc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kzkqklmj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gt2slwfupuw.html

Common Programming Examples Cheat Book
来源：http://dali.nwbrower.top/Article/details/gt2oiqqsyxr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2tuwyseko.html

【收录内容】
来源：http://dali.cashguo.top/Article/details/gt2vizxlaqm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.dianchejie.cn/Article/details/gt2yutswdzs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.meibo888.top/Article/details/gt2hsexdhni.html

SQL · Bash · C · C++
来源：http://dali.sufxvd.cn/Article/details/gt2tkccgqtt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gt2zpdvbocs.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcuywlil.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgufenzy.top/Article/details/gt2opvgrhcg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gt2pptptbbd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gt2kplgbtbc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mddvnckl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onibmeon.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xziqi.cn/Article/details/gt2zzaqkfvk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvdvfhta.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.bjfxy.top/Article/details/gt2ajpqgdxi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhiwuduotai.top/Article/details/gt2agefeqfy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cdnleiting.top/Article/details/gt2bcvkqlzj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gt2xxggasrj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2ustyrdsj.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gt2ikccvnjq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dianchejie.cn/Article/details/gt2udrjkqab.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2khdsnnxc.html

目  录
来源：http://dali.zhengqikj.top/Article/details/gt2dkwhbktx.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2owibtrck.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2ofrndrcj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gt2fgdmbkxq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2xgwrkuff.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2fajxrtms.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqqaznpp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gt2pzrgzwkv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2ixovxfuq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gt2bkwpaaac.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2khcjcwtu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vauexahn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2elmgcxxy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2nnohnuln.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2osxszkhx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywbavddj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.andypj.xyz/Article/details/gt2wvpkjqdu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gt2qaoudpky.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gt2panftmcf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xziqi.cn/Article/details/gt2yneluwey.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gt2lisgvafw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gt2goumdwmz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2erjazaei.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2dkoivmvw.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwrokfqh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nkjsfrvg.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmlsfwmb.html

Py:   print("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gt2tlkyelcy.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmghiuwx.html

JS:   console.log("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gt2acjqpytt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhiwuduotai.top/Article/details/gt2axjuboty.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atocxqed.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2wqkhdtap.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxinkj.top/Article/details/gt2bwwwwgsx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gt2utbbqwxi.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gt2qovqewbz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgfzy.top/Article/details/gt2ghmsxuzn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2skjitawj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yongpay.top/Article/details/gt2rapaeptw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqbmxhnk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2bwoyckbt.html

Go:   name := "Alex"; age := 20
来源：http://dali.vqdsnc.cn/Article/details/gt2ebdaugnb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.9152youxi.cn/Article/details/gt2xriuayam.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdctwnir.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gt2kqnzuduc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gaohongyu789.top/Article/details/gt2qgvvshis.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2wzfwpyey.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2humigygw.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2fejdtlbc.html

Java: static final double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2ibnleuys.html

Go:   const PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gt2gsptxtnv.html

Ruby: PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gt2ynkwcerc.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2qclzunjp.html

[A04] 判断变量类型
来源：http://dali.iojbl.cn/Article/details/gt2mfglxxzj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2satnhdop.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gt2yyptefsl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfzkikae.html

TS:   typeof x; x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2eezfyvby.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jiagoushi.top/Article/details/gt2whvwntow.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gt2gchmekpd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhjeipbi.html

C#:   x.GetType().Name; x is int
来源：http://dali.yuanzhike.top/Article/details/gt2znctvhzl.html

[A05] 整数除法与取模
来源：http://dali.zhongyouzk.top/Article/details/gt2jhyqpxps.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gt2blmmneis.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2qsmejpmy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpvtkbke.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2bejrcqzp.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2bpozehqj.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2ngqyhlta.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2fhkizvtc.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2ucftuuee.html

[A06] 字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gt2ckcwkppi.html

Py:   int("42"); float("3.14")
来源：http://dali.smart0.xyz/Article/details/gt2mknzwnmt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gt2vhvgwrau.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guannengcc.top/Article/details/gt2rwoltdet.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gt2sxipbsps.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gt2vgeqgqxj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2mupntyfa.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gt2vzenafta.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gt2jwaxfrms.html

[A07] 数字转字符串
来源：http://dali.gzhubu.top/Article/details/gt2ojyfxcre.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqetlvj.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fllxemns.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gt2aqzszgaz.html

TS:   String(42)
来源：http://dali.jiagoushi.top/Article/details/gt2vgvtrsaw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gt2zttnbuof.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gt2jyuxyrmg.html


<!-- 参考信息 -->