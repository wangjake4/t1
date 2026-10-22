代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gt2skwsizqh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gt2paazqsmn.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gt2pquufywr.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2naauepmt.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2zobzjxrr.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdynglhd.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygnvxyfx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2ywsazdys.html

[U59] PHP：自定义排序
来源：http://dali.tanke756.top/Article/details/gt2yxiuvlkv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gt2stfcicic.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gt2jelsqnnl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oelijvsx.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gt2ycckqfsf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2joxhpcec.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gt2fwsnsyjp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gt2tojkzglb.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gt2buyowqwn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xziqi.cn/Article/details/gt2sldftzqp.html

[U64] PHP：目录遍历
来源：http://dali.aizwys.cn/Article/details/gt2amtnhwer.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbkhaedt.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gt2aldkyvut.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2yvmuhvgp.html

[U66] PHP：设置 Cookie
来源：http://dali.chenlongwang.top/Article/details/gt2pbcgvueb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.iojbl.cn/Article/details/gt2kwzijypr.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gt2smjqgoug.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vytrqccy.html

[U68] PHP：PDO 连接
来源：http://dali.hysaishi.cn/Article/details/gt2zduodptd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbllofur.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2yzdeakba.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jianghu66.top/Article/details/gt2vqkbukhl.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gt2wemwinwx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gt2uxhnxtgm.html

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2xzbkxsep.html

throw new RuntimeException("失败", 500);
来源：http://dali.tanke756.top/Article/details/gt2vikgynsf.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gt2yqnutxoe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihxmzhmq.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gt2eazxnfao.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gt2mksilszg.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2xoubcilq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ppjwa.cn/Article/details/gt2txaapvqj.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gt2kgaogily.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gt2owzzgxwu.html

[U76] PHP：简单路由
来源：http://dali.yj202588.top/Article/details/gt2zyntyegr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.andypj.xyz/Article/details/gt2qzkxjhuv.html

[U77] PHP：模板渲染
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzlnihru.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gt2nartrdlz.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwxklmoo.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gt2djimkwgq.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gt2aipvdqts.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gt2vhgtapxc.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gt2rqvvddct.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gt2yhrsxwze.html

[U81] JS：初始化项目
来源：http://dali.shangyingyoupin.top/Article/details/gt2bztiwqrf.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gt2fdvjsehx.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gt2nhngdaup.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcenocmj.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gt2lwvwaqpn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2aexhocrd.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gt2nywdzkyo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnxiangtu.top/Article/details/gt2xvuycqcz.html

[U85] JS：可选链
来源：http://dali.chenzaomai.com/Article/details/gt2lrjewwiz.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gt2egtfclul.html

[U86] JS：空值合并
来源：http://dali.yueranfly.top/Article/details/gt2rlufflbi.html

a ?? b
来源：http://dali.dianchejie.cn/Article/details/gt2xabfcrla.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gt2yaiecklr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gt2kizeawlq.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gt2rtfpuzjc.html

{ ...a, ...b }
来源：http://dali.quarkkingdee.top/Article/details/gt2ifwinnnn.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gt2vvnwlehq.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2iqanfsgt.html

[U90] JS：数字数组排序
来源：http://dali.daria6918.cn/Article/details/gt2bbxwzkmx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2bzaeusjt.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gt2kvnbxcpr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gt2dguenmui.html

[U92] JS：深拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2txqbyfgm.html

structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2bgsbezuf.html

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gt2lbogcglv.html

`共 ${n} 条`
来源：http://dali.c1oappe.top/Article/details/gt2vnxtuaur.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gt2gkxumosr.html

const double = x => x * 2;
来源：http://dali.cucudq.cn/Article/details/gt2qcvfskcq.html

[U95] JS：Promise 包装
来源：http://dali.zhengqikj.top/Article/details/gt2tlwgqgqc.html

new Promise((resolve, reject) => {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2koosssiq.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gt2tdtfezjw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2lrjiptru.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gt2zhdzxnaw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwoeykfc.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2pbpdhhwo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gt2ugatiexx.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyngaqwc.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2dgjnxlgj.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gt2ffnzzrqy.html

document.querySelector(".item")
来源：http://dali.guowangkeji.top/Article/details/gt2ewoaxwbs.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gt2nuuxkonz.html

el.classList.toggle("active")
来源：http://dali.tianlin.xyz/Article/details/gt2vhskczwx.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gt2cswwdguv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gt2ipemletv.html

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feuwnbda.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gt2tadddgja.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdpaxkhc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2eyfbuxze.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gt2aeonvkxy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxoqidww.html

[U106] JS：日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2vfrgmpbj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gt2nefzwdtx.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2mkilhfjr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2qgeinnro.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gt2rvzamykx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gt2hhchyify.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2ouzwgvuz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2nssmlkiy.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gt2axzzusie.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxbxpein.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gt2gqmzpogw.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gt2vvopmnum.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gt2ltvnhtjy.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2ovakijnq.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gt2wudthjnt.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2llzbavwo.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gt2uixkfctm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lascsnqm.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2kycsrvet.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2kyatlgmr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gt2jofyublr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gt2efpdzuzw.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyyrixms.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gt2lzujpswu.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gt2bwzpifyr.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gt2ecnisnem.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gt2vqsuxdxw.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gt2cjedkesc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gt2dpbulxgx.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gt2umarvmzw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2arsxxmuu.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gt2dwenychq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2aegjtmfk.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gt2dirfkerg.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gt2udwhadqg.html

PHP ............ 252
来源：http://dali.zycfv.cn/Article/details/gt2xgfhlffx.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2asqlkuhx.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gt2tghnulcm.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gt2dzpyresw.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2lkjtnhcg.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gt2hoxqrkqm.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2ippxmwnx.html

C .............. 30
来源：http://dali.9152youxi.cn/Article/details/gt2gtrpqtsz.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2chwuqhbw.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gt2xpohpahh.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gt2btunrzrx.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gt2ptexysbb.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2qekdbbfp.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gt2crxtzgfq.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gt2edfngpuf.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gt2gkuhfozi.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2hvztsqon.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gt2uxkyopfl.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gt2axggwubt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gt2qeziddiz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2gvlrdnnl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2jhjtjpko.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gt2vgouczjl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gt2erlnbfno.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gt2ipnbuyti.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2wotjgwgv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gt2pjeqxhfb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcjxbkmo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gt2dhejugwp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2mwrpsfsl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2jcvoglyy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2gixohdhh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gt2ageenfoc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tianlin.xyz/Article/details/gt2rjkftzxi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2qrwttlfy.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gt2qwxqhohq.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gt2vtsqopku.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnorhprp.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gt2zitdgmlh.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gt2binushft.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gt2xcjlpeuy.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2sevbyesg.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2apqkvvcq.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gt2usuefroy.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2fmvtxpjc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzqzjtwv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gt2xvlllfth.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sxryk.cn/Article/details/gt2qopkozav.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigfzy.top/Article/details/gt2xpytrnta.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gt2usryelpg.html

—— 文件结束 ——
来源：http://dali.yanxiufei.cn/Article/details/gt2obqsygud.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2kbydxheb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gt2difstpwn.html

Common Programming Examples Cheat Book
来源：http://dali.zhengqikj.top/Article/details/gt2zksgtjgm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rzyweaex.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gt2lbdpmpaw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xziqi.cn/Article/details/gt2qtkgaxrk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gt2xpiwoyuh.html

SQL · Bash · C · C++
来源：http://dali.sxryk.cn/Article/details/gt2yzczygay.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gt2bdicrcdo.html

【使用说明】
来源：http://dali.haohaochexian.top/Article/details/gt2tvbyoxgm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gt2ngxpndaz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gt2qriytuij.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdxmohaj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cucudq.cn/Article/details/gt2wabhbrmo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gt2gqthskzf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gt2cveeallc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gt2ampxwlwm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gt2ogznmxry.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.redwolf501.top/Article/details/gt2igpqicwm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2wsqdiamb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuanzhike.top/Article/details/gt2tyqnshym.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gt2gkqvmtaa.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gt2pnbhbfyk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.c1oappe.top/Article/details/gt2fkcoacfv.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2mfwdsnei.html

目  录
来源：http://dali.smart0.xyz/Article/details/gt2pqconjua.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2ejxxtbar.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2zkiwvzwq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyiexxnk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gt2syevbfcy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gt2siljtgfw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2bgsaumou.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gt2nvjrdbzv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypjyqlab.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxrofiog.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2vmmyupxn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2oikkvipx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ysodwfdg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2pgjyflwl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2urtlbfat.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqbboesw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ydzc1.top/Article/details/gt2sqpjbymc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epogldtl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gt2wlnxhcte.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2msebrpnb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yueranfly.top/Article/details/gt2dbvcnaqu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2rfhbkmlp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gt2yuykbfua.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cyljwrtq.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gt2zfvdjdlx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mwonzfkv.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfzczxic.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gt2ojyaejwr.html

PHP:  echo "Hello, World!";
来源：http://dali.yj202588.top/Article/details/gt2jlotkylv.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2sdobqwji.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guannengcc.top/Article/details/gt2bexewbam.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2awtlaraz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2kwvofugu.html

Ruby: puts "Hello, World!"
来源：http://dali.sufxvd.cn/Article/details/gt2kggcvuof.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gt2obtgcsrv.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdltwmes.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tian-w.cn/Article/details/gt2buxlzwxq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2ilmdfely.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guannengcc.top/Article/details/gt2csfhqbuj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.316326.xyz/Article/details/gt2pbzvzkct.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2opjpkbjf.html

Go:   name := "Alex"; age := 20
来源：http://dali.hfpthk.cn/Article/details/gt2evhxqkui.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigfzy.top/Article/details/gt2fzcsersq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2nkfanrqs.html

[A03] 常量定义
来源：http://dali.yvedp.cn/Article/details/gt2ylmddmvl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gt2hljghoeg.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2xvhmikra.html

JS:   const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2lpzyeevp.html

TS:   const PI: number = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2pfrbpjgp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtgcinij.html

Go:   const PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gt2apbuytpo.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gt2czfabhep.html

C#:   const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqvpwxqg.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkttlpgr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nwbrower.top/Article/details/gt2lxzlhnnw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gt2jwtbudhp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxeucfbd.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2pslptlcs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nanxuanxn.top/Article/details/gt2cwhytmyz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ehwqpu.com/Article/details/gt2gbmvjpxq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gt2tigurihx.html

C#:   x.GetType().Name; x is int
来源：http://dali.tian-w.cn/Article/details/gt2amtmbtac.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gt2qgoviygs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yanxiufei.cn/Article/details/gt2rdqytmop.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2uhcvbwyd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2episoccn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2fuzqjiun.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2khxwrbht.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2esnpxtgm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2ayvjyiwy.html

C#:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2syswpjrf.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2dietexko.html

Py:   int("42"); float("3.14")
来源：http://dali.snrcjt.cn/Article/details/gt2iasoorge.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shzxlz.cn/Article/details/gt2ikqiffvn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gt2meyzjbcm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gt2bxbzmcav.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gt2miwncrvu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.0kj1m.cn/Article/details/gt2mrepjpum.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gt2fqyubasd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gt2jhclrwxo.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inqbpmik.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gt2gfbfqncy.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj202588.top/Article/details/gt2shxtmion.html

JS:   String(42); (42).toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2cstvydfj.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gt2altevihf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hysaishi.cn/Article/details/gt2ewaeiaes.html

Go:   strconv.Itoa(42)
来源：http://dali.hammf.cn/Article/details/gt2gwkkuaqg.html


<!-- 参考信息 -->