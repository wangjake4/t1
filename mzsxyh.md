代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtvsvqpawx.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllrdifdy.html

[U54] PHP：空安全调用
来源：http://dali.yanxiufei.cn/Article/details/gtkpapikeo.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gtuxkcoikt.html

[U55] PHP：match 表达式
来源：http://dali.tianlin.xyz/Article/details/gtmukuvfpl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtaiviyimb.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gtwbvvlzmq.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtiyuubsuy.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gtzmxchsco.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gtxrvuggoq.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gtjouvxais.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gtigjmenpl.html

[U59] PHP：自定义排序
来源：http://dali.yj20258888.top/Article/details/gtrabjlqaq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gteltiivke.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gtvhdpoypz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gtgxuoyjev.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gtpyniinis.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtgomwwgmm.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcznguaz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gtmuwnalxo.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtzywqbiji.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnklyvez.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtpslzfuxb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtwhkqlqtg.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gtgpxhnsuh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtsxrmybuu.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gthrizsspj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ybcxt.top/Article/details/gtligzxbae.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gtrranoinc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.mhx1999.top/Article/details/gtlsqamtdb.html

[U68] PHP：PDO 连接
来源：http://dali.cheryme.top/Article/details/gttjnhubsc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtjbsusjln.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxnupnfo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gthgsnvxry.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gtjskidegk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gtaypchxee.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gthfaehpkl.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtymacgjzn.html

[U72] PHP：写错误日志
来源：http://dali.yangfankeji.com/Article/details/gtkcnntyuz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gtyiodnuod.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gtnqkmnudc.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgufenzy.top/Article/details/gtpjiuzawg.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtrwvprimx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtcbgqdgkq.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gtxfntzkwe.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtbrkdxgob.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsfuzraq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtseslaneo.html

[U77] PHP：模板渲染
来源：http://dali.gzhubu.top/Article/details/gtngznjhlm.html

composer require twig/twig
来源：http://dali.yangfankeji.com/Article/details/gttrkfqfxo.html

[U78] PHP：单元测试
来源：http://dali.chenzaomai.com/Article/details/gtehbhwjju.html

composer require --dev phpunit/phpunit
来源：http://dali.jinqigfzy.top/Article/details/gtoyzqiywx.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtmhmnpokv.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gtcjynumsv.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gtfawyqupx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.quarkkingdee.top/Article/details/gtugtvcqzv.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gtbzrzbyym.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gtanknkglw.html

[U82] JS：package.json 脚本
来源：http://dali.sweek.top/Article/details/gtiirmddcb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gttvasbxjn.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gtzdcklyhd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtpqjupeto.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gtcytvcuja.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtubevlnpn.html

[U85] JS：可选链
来源：http://dali.shanyushiyangtech.top/Article/details/gtlatqzkth.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gtonjtyomq.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtywvkfchn.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtwplzvjtt.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtliljnvrx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtpqhuaxqw.html

[U88] JS：对象展开合并
来源：http://dali.ehwqpu.com/Article/details/gtaimipuzc.html

{ ...a, ...b }
来源：http://dali.nanxuanxn.top/Article/details/gtipnrnewo.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gtqetzeutj.html

[...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtixlyrnre.html

[U90] JS：数字数组排序
来源：http://dali.chenjidiqi.icu/Article/details/gtdpxnxgwo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtwnunvpwl.html

[U91] JS：对象键值遍历
来源：http://dali.mhx1999.top/Article/details/gtgvnzwsdx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gtgpjybeay.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gtfqckzwtm.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfbdmxbcs.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtwksjzxft.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gtftkvdfbu.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gthyebdxso.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gtanwauzat.html

[U95] JS：Promise 包装
来源：http://dali.daxiang520.top/Article/details/gtnwgpzvbb.html

new Promise((resolve, reject) => {})
来源：http://dali.aibaodan.cn/Article/details/gtqysjclkq.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtctntvhji.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtntpwolds.html

[U97] JS：并发请求
来源：http://dali.zycfv.cn/Article/details/gtxjhodeog.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtayzklsok.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gtcwalajby.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gthdhcrgvj.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtwcswyvap.html

el.addEventListener("click", e => {})
来源：http://dali.hfpthk.cn/Article/details/gtapfnrfdc.html

[U100] JS：DOM 查询
来源：http://dali.jqgfzy.top/Article/details/gtwvvmjmto.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtfmncejrm.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gtooshuvqx.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtljuqflnb.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gtqbynywhk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfvduwdn.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gtggewxzgn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtnskfklfj.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtlcdjfuij.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtjhnzmval.html

[U105] JS：节流
来源：http://dali.vqdsnc.cn/Article/details/gtbwbksecx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gtjxfvplyu.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gtcmukgxhd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gtpqensekx.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gthkabcemj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtgzamccgu.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gtkcqgdisr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gtytcxnrqv.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gtxegubmrf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtboyglgzp.html

[U110] JS：数组分块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixoiamti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtrhmxsilz.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtaitgaton.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtfgtdhdng.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gtdvugvsxo.html

"7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtsmfncolx.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gtfhozrraw.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtfkgaoqsa.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gtcdeogqfy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtwnplkdze.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtzjdawlvf.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gteygrbbhi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtekfwzuis.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtfhddzbxo.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtelruvibz.html

npm i -D vitest;  npx vitest
来源：http://dali.zdqjudy.top/Article/details/gtuyvhnyhw.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtcyacsybz.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtoddcsvxh.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtocjcvluj.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtouospaxp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gtunwztiaq.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gthcysgtfj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmmdejkfh.html

统计汇总
来源：http://dali.cqqwz.cn/Article/details/gttpxnrayc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxxbhrghx.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gtjskzekvm.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtgctpwepp.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gtuptnpaov.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gtqsdyucib.html

TypeScript ..... 212
来源：http://dali.jlsjyb.cn/Article/details/gtwflltgho.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtzbghmovn.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtzvgsglbq.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtimhawvqe.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gttztakgct.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtinqhvgsj.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtbqjbkxnn.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmjqlwel.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtepasbdjk.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtfampapej.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gtrakzkdkp.html

Lua ............ 10
来源：http://dali.bjfxy.top/Article/details/gtltnqupma.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtfqzhrdbj.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gtcexhmvvv.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtcfpemajl.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gtympjwwsz.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gthcxddhio.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmovqzjv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtqshagktb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtiowlhyba.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtiwthsfok.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtqacwezeh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtirgpbofy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtgcfgsntl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtvebxxyzi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtycktopdk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtnijuimai.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqysszpov.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtwyztlbqb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtgwjajukn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtxmavjrem.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258888.top/Article/details/gtvricwaxt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gthmxxrxiz.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtrtjkpyfm.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gthdognnxe.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtjkufaljy.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gtoawpfali.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gtiticqsns.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtfnfdzekp.html

合计                                  2106 条
来源：http://dali.shzxlz.cn/Article/details/gthfdcnibb.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtzfyhykji.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gtqfqhifei.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtzcvososc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gtbfuwwooc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gtpxaekhua.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gtiwrtyhus.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gtautpdolz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gtmbtiyyrt.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtgblsyhdv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtykugryiz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yvedp.cn/Article/details/gtjqosquof.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtekkyskms.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtckukvwll.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gtdopfbwjt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangkeji.top/Article/details/gticjdyzaq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gtcdxzlwnf.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gtucviafhc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.havefunace.top/Article/details/gtdqmeskrb.html

【使用说明】
来源：http://dali.hnxiangtu.top/Article/details/gtauctdhuo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphjvpenw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gtxfcchrxd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtluditdrh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gtsbhzvwtr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sysykeji.top/Article/details/gtqqjxnpkv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gtkxezihqh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtozndjfht.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtyhzfnwtp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hywenlv.cn/Article/details/gtixvixvvx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtpobenyij.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hammf.cn/Article/details/gtfmbgelut.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ivvv.top/Article/details/gtleamzjor.html

【文件统计】
来源：http://dali.cdnleiting.top/Article/details/gtuqhovxgq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxuanxn.top/Article/details/gtltbptovl.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtgyrorujr.html

目  录
来源：http://dali.yuxming.cn/Article/details/gtfsdtdrmb.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtfcxzvcvb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtifrmurub.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtsmtpuwhs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcremxplj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtfvaofyfi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cheryme.top/Article/details/gtixlncpzr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gtlqzclwhz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtkcitquva.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gtabnerayb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtdrablasf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthefcxhcd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtgopdwznc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtodohckpg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtlyvlfdmz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gteyuiloap.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gtgjjhjeoc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtffhinrhs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gtgevncfnu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtomdbjves.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.meibo888.top/Article/details/gthowlcywp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtykmbhbzj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtfejovzok.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtamufusjy.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gtefxjntnz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvoceguxu.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtjhcnvjrj.html

Py:   print("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtzqhwjnmq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gtppkkvzdz.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtsenrtdco.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtpxoptd.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtkevtmfvf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtzttwgeqa.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigufen.top/Article/details/gtqapqfznw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtznptcimd.html

[A02] 变量声明与赋值
来源：http://dali.hysaishi.cn/Article/details/gtspooviaj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guowangkeji.top/Article/details/gtvjbpnxfm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtmllwneaz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatuqgvem.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gtvpmdindy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtbbkjifrr.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuxming.cn/Article/details/gthmjprpjo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gtnkpgtqmx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gttdfjtius.html

[A03] 常量定义
来源：http://dali.zhiwuduotai.top/Article/details/gtimuhjwca.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gtakpxfewc.html

PHP:  const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtesrhvtbt.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqqqihabw.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gttancqiit.html

Java: static final double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtlrmgboer.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtwkffetzd.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtosdknmom.html

C#:   const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnerczrin.html

[A04] 判断变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtyxpnynbq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.vqdsnc.cn/Article/details/gtybknfrrc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xziqi.cn/Article/details/gtwycoikhr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypipllhb.html

TS:   typeof x; x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtmwtlmlme.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jiagoushi.top/Article/details/gtibgqczsp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.iojbl.cn/Article/details/gtncrsygep.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sufxvd.cn/Article/details/gtdnwnzddl.html

C#:   x.GetType().Name; x is int
来源：http://dali.gzhubu.top/Article/details/gtlpnfaitl.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gtmfyevicf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj202588.top/Article/details/gtklkqnipo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtrkftmdzx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtnqyhgwwe.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtpqfuzslh.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtagggdaxu.html

Go:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtmjekmmlu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtqxgusbrg.html

C#:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtcwsfgbdt.html

[A06] 字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtxxzlptvu.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtvofveqlt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.andypj.xyz/Article/details/gtifahtjbl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtkaktirfz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtbguawraq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gtyphnykfl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtddtgaswb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yvedp.cn/Article/details/gtvztzaxha.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gtjgcwgydj.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtfddnqdkj.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtakkqrlpt.html

PHP:  (string) 42; strval(42)
来源：http://dali.yangfankeji.com/Article/details/gtbpvwepgi.html


<!-- 参考信息 -->