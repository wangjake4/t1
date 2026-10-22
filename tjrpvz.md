代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtcwruyhgx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtelhnjuva.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gtoasgxbwz.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtrxwsnicj.html

[U57] PHP：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtmxwcwjla.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gtqbwtgqws.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtqoxisvbf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzhmlmde.html

[U59] PHP：自定义排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnuewxiu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtneophvdb.html

[U60] PHP：JSON 编解码
来源：http://dali.hfpthk.cn/Article/details/gtuczkscss.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gtdwspzmym.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtkdswiyku.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtlqsglpip.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gtovojgyfw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhiwuduotai.top/Article/details/gtcwlkjodm.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gtvnodjdzp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtzpgadifm.html

[U64] PHP：目录遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulzacxwd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dianchejie.cn/Article/details/gtytuskzuy.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtsosmujda.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtjvecmmun.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gtvfgprvfg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gtgjbxnopa.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gtsxcdayip.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hongshengwenyu.top/Article/details/gttielddtd.html

[U68] PHP：PDO 连接
来源：http://dali.yj202588.top/Article/details/gtloiubebo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yongpay.top/Article/details/gtizaghuus.html

[U69] PHP：PDO 预处理
来源：http://dali.yuxming.cn/Article/details/gtzwpyughd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guannengcc.top/Article/details/gttaldewsq.html

[U70] PHP：PDO 事务
来源：http://dali.jqgfzy.top/Article/details/gtvnmivvfq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtzkwrtbxu.html

[U71] PHP：抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gthikgtchl.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtfdbnunfl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gtmlzvowng.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gthbjcvetq.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtcouqzrir.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtuyfageir.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gtnyxunaax.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtxozptyuk.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxhhnvch.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gtwvvtmxsf.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtlfkzkrwd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gtinghlkeu.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gtrwqfkwud.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gthrrwcmxx.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gtthgqwzal.html

composer require --dev phpunit/phpunit
来源：http://dali.xuanzx.com/Article/details/gtbkdoffqv.html

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gtbkeohfaq.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtgsrhbwgw.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtysdlfiqa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gtxlyshpnb.html

[U81] JS：初始化项目
来源：http://dali.vqdsnc.cn/Article/details/gtzzsylrno.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gtutjwxamq.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gtydakbook.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gttpqocaki.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnxiangtu.top/Article/details/gtbulrywns.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtnwyqrzam.html

[U84] JS：CommonJS 写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznydomma.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gthjcgnmlv.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gtqjhuqfpg.html

a?.b?.c
来源：http://dali.cashguo.top/Article/details/gtdbvtosms.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtpiwxhylw.html

a ?? b
来源：http://dali.ppjwa.cn/Article/details/gtrgnutunm.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gtmgxqmhki.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzdytunh.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gtzbfwhopl.html

{ ...a, ...b }
来源：http://dali.dashuyun.cn/Article/details/gtpfurllso.html

[U89] JS：数组去重
来源：http://dali.shzxlz.cn/Article/details/gtivmoyxys.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gttmxbxbth.html

[U90] JS：数字数组排序
来源：http://dali.9152youxi.cn/Article/details/gttywldqlh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtmowzlwhn.html

[U91] JS：对象键值遍历
来源：http://dali.nanxinkj.top/Article/details/gttvvejhaj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gtetuufzoi.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gtxvgfczfz.html

structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfmrgvif.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gtxgylgdej.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gttacojzel.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtjoxsnjom.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gtqkffbpnt.html

[U95] JS：Promise 包装
来源：http://dali.fengsongda.top/Article/details/gtgseqprbh.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gtrizqtjyn.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtsgehwyum.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtlzmcagnk.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gtdvcveecy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtadmjlxbz.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysykpljg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtvoegbdmm.html

[U99] JS：事件监听
来源：http://dali.xuanzx.com/Article/details/gtfkosrjzt.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtzrjcalnm.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gtfzydggkx.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrnahgjl.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gtcdgyymbx.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gttqwhplpy.html

[U102] JS：本地存储
来源：http://dali.snrcjt.cn/Article/details/gtoaxdwznd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtzclurbqv.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gtwjmghpfo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yvedp.cn/Article/details/gtlyuomvle.html

[U104] JS：防抖
来源：http://dali.cheryme.top/Article/details/gtpzcioxzi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtvvbwuvqh.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gtvysnuktq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtqzyfvllb.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepwaoptw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtifpzyrrk.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtnjosdkrx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtcqgsboqt.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtpvefufdt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtyfqfxujf.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtcvxakola.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtstiomxkv.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzpuicne.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gtqjhgqufm.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdkscsln.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gtdwiqyagk.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvhaykdi.html

"7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtvccfkqui.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtfiywyjnm.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtizdnzbzz.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gtphkabzre.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtdefbycxo.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtnsrhwccq.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtussuowaq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gtbmtbbths.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtbrxmamul.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtxovhbqls.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gtvzpadcsv.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gtwksrihnn.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtipfdjxgx.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gtkqxqcuug.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gthvskasqu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtsfflzuho.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gtykfkdgpx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtapncepho.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gtagdpnseh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzqnryili.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtdlwezecv.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcavdxly.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtahtkrpdt.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gtlumkdqfa.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gttvvepogp.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gtcyisufgm.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtyvutccpt.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtvxuvwosj.html

C# ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdxvtxbm.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpyhfist.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtlacbtnsw.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtpawcffqk.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gtoplugivv.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtnylgjnkp.html

Swift .......... 15
来源：http://dali.snrcjt.cn/Article/details/gtpbqmpjej.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfxnryiz.html

Perl ........... 10
来源：http://dali.hnqzz.top/Article/details/gtxdepazva.html

Scala .......... 10
来源：http://dali.shzxlz.cn/Article/details/gteipydske.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gtwuzerite.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtetekzqvh.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gtltlozoff.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtibtwlzzn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtcngkldvm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtpxtqomwt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtjbtrsarh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gtzmguicdq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtetscrqfe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtuuprxsyr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gtjcljtaxo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtulyyqtnn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtnozpyjrq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtbhocyqqf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtetdeqzhn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gthrgrohmp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtasrqslmn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gtibcqnsdk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtvclqweqp.html

Q SQL 专题                              90
来源：http://dali.dianchejie.cn/Article/details/gtwgnhozmi.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gtnfyvixpi.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtlvievrrk.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gtglbyzbvu.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gtscnvwomy.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtskujspuo.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gtjsqllwbd.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtktldbpxx.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gttwwsqhrv.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtqokzfqyq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtjldlrdsh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gtesrivhvr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gtzcsamihd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gtfvoxefra.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.redwolf501.top/Article/details/gtqlymuksp.html

—— 文件结束 ——
来源：http://dali.feifeiyinyue.top/Article/details/gttgksamlo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgboheofq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gtqsrtosoi.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtgxefbtwj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoneztxgn.html

【收录内容】
来源：http://dali.hnxiangtu.top/Article/details/gtcyijttlj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gtmpbabmha.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtwxvzudwo.html

SQL · Bash · C · C++
来源：http://dali.cdnleiting.top/Article/details/gtdggavkji.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtzbifnvln.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtovzrtkxh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yongpay.top/Article/details/gtwqmccoyk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuanzhike.top/Article/details/gtznormhtf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.havefunace.top/Article/details/gtxpvxtmhp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuxming.cn/Article/details/gtvrkrgxwk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gtdjvvqujs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhoulong.xyz/Article/details/gtyajfgdft.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gtdtgkfgsr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gtfztlqfco.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.9152youxi.cn/Article/details/gtvscfrzls.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dashuyun.cn/Article/details/gttobogxza.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtbqenpqrt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gotoacloud.top/Article/details/gtiuwpdddf.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gthpbcygwv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtqspzabbz.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtjbvxxjje.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtdtimzuqu.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtqmdiclow.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtshbmsgip.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtrjjrnarq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtejnbkmbq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtomngwbsq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigufen.top/Article/details/gtktuqazxr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gthzzdwiuz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtefhadnob.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtlzwmqbcx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtqlplpumm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtqntwrroh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtlbuiltol.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gthdiabijd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtrrlvfvzw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtpwlootjr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnqzz.top/Article/details/gtozayeelb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gttdflcftd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.vqdsnc.cn/Article/details/gtraydqamq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xziqi.cn/Article/details/gtjxyjvwiw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ehwqpu.com/Article/details/gtubpmbigk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtfzxczpmc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtuydjfikf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttpfztmnj.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gtnjirvxwv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjbzeeyss.html

[A01] Hello World
来源：http://dali.havefunace.top/Article/details/gtxsmjhfxn.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtcqfmgraw.html

PHP:  echo "Hello, World!";
来源：http://dali.chenzaomai.com/Article/details/gtlikuejlv.html

JS:   console.log("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtitdgotph.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gteuabzjsz.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtsysvpqqy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtniqeoctw.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gtdlkznkir.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtrvnnuhkl.html

[A02] 变量声明与赋值
来源：http://dali.aizwys.cn/Article/details/gtxszsebre.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gteflynvne.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cucudq.cn/Article/details/gtydkxaxpy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtcvhfhues.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhengqikj.top/Article/details/gtdtwqvtjh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gthmdwuosk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gtfgstfjbd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtagfngzwn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtzmevaexe.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gtacmcjqhw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtqhelildm.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtberzamnb.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gttthczkma.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtgrrfjngf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffufqukh.html

Go:   const PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gthykxcnsv.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtxgrtfcmr.html

C#:   const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtgyidkzqu.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gtbwvgufyr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gtryyrocua.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ehwqpu.com/Article/details/gtlmwcpyzc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtnmndeipo.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gthbdgcfye.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtiikfboik.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykgxakfm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hysaishi.cn/Article/details/gtflfnfkhj.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gtsvktrhdo.html

[A05] 整数除法与取模
来源：http://dali.birdmap.top/Article/details/gtvhwkyfeg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtmrjwjgvm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gttivgcqtj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtkodczypo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtpyuzbrua.html

Java: 7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtfpyzwczi.html

Go:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtnjteycto.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtsyrjihtu.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcttgafo.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtqmxgdlut.html

Py:   int("42"); float("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtzskvrlkp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hammf.cn/Article/details/gtiwsgwerm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtecoaacie.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtefgoaqgx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtvopxzysd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfeoumvm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yangfankeji.com/Article/details/gthyjeyuln.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtbuoktvun.html

[A07] 数字转字符串
来源：http://dali.andypj.xyz/Article/details/gtrgyjgkyl.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gtcwwwgxwd.html

PHP:  (string) 42; strval(42)
来源：http://dali.9152youxi.cn/Article/details/gthykyluba.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gthmmjaihc.html

TS:   String(42)
来源：http://dali.tanke756.top/Article/details/gtqlpsorxr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtspfkinzy.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxinkj.top/Article/details/gtjaeehclp.html


<!-- 参考信息 -->