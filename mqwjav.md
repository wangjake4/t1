代发 wailian999

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gt2uowzfzol.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqomsdko.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gt2vfgqutms.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2rkeshzhc.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gt2uiznxddd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2rlhepwan.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gt2nyqwtrow.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gt2iylioukq.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gt2tgnmoyao.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2xtuiuimp.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhuwuxkm.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2btwwhglb.html

[U57] PHP：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2kurklslv.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gt2dlobicnb.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bttuqpjd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gt2fgbcsuob.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gt2skjmtdtu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2iobuoypq.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gt2ukvpnffc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gt2qafyoyta.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gt2pwsqfjcj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2fflxgdfo.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2iilxfpaa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gt2xhlayegz.html

[U63] PHP：文件读写
来源：http://dali.fengsongda.top/Article/details/gt2ejkifoii.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gt2zirhefpi.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgoksnzw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gt2hcrrlfou.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rawqisxm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2xkfxsamm.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gt2neolbxkc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gt2nlebrpip.html

[U67] PHP：处理文件上传
来源：http://dali.aizwys.cn/Article/details/gt2yvgvynzn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gt2zyyhrfkw.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigufen.top/Article/details/gt2xhwfogwa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guannengcc.top/Article/details/gt2exxvqdsg.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2rowikoyp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gt2hcjczski.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gt2fkmiznts.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oylmeijo.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2zoenebpe.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzqmxbfk.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gt2hgfieewx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgyjxwyi.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnqzz.top/Article/details/gt2drarmpnj.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gt2stuitzdn.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2nrrchppl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jiagoushi.top/Article/details/gt2ypjpywnt.html

[U75] PHP：依赖注入
来源：http://dali.birdmap.top/Article/details/gt2rxginprx.html

composer require psr/container
来源：http://dali.yanxiufei.cn/Article/details/gt2inzphvlf.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gt2nbiqduyu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nwbrower.top/Article/details/gt2jmbaxzjk.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gt2iqzionsv.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gt2mzeypuuh.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gt2eduuddie.html

composer require --dev phpunit/phpunit
来源：http://dali.yanxiufei.cn/Article/details/gt2mfgnkrpb.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gt2gtzvkuqu.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gt2xuzstgzr.html

[U80] PHP：代码规范修复
来源：http://dali.haohaochexian.top/Article/details/gt2jmgcvcpk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gt2qojuiyej.html

[U81] JS：初始化项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zeuhlpql.html

npm init -y;  npm i express
来源：http://dali.jyoumei.cn/Article/details/gt2cwnileai.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gt2tyuzunld.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhoulong.xyz/Article/details/gt2jmupzkfx.html

[U83] JS：ES Module 导入导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yspzmlqz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2bqwkrfoq.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gt2soljuqaz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenzaomai.com/Article/details/gt2jltmbzbk.html

[U85] JS：可选链
来源：http://dali.316326.xyz/Article/details/gt2wcsjfmnb.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gt2eokfgcpk.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gt2xnhtplum.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gt2rwqeuehq.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsfetjdr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gt2wneajvgu.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itqhwlfe.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gt2jujkynkb.html

[U89] JS：数组去重
来源：http://dali.zhixingplan.top/Article/details/gt2lyvfwlol.html

[...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2nfovdrba.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gt2meljmqai.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2wbiohdtz.html

[U91] JS：对象键值遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ctkdpbhb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgsaqqos.html

[U92] JS：深拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2yhzabnka.html

structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvvxenmz.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gt2ncgawghh.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gt2cckwqsbm.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gt2nnizvmjs.html

const double = x => x * 2;
来源：http://dali.ppjwa.cn/Article/details/gt2pgdilzos.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gt2jvbxekxc.html

new Promise((resolve, reject) => {})
来源：http://dali.cqqwz.cn/Article/details/gt2bkppnqdj.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gt2tjcsaqjq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2trpxqmlr.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gt2drkpjjqk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2uwccecgc.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gt2ztfpborh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gt2vvyoxkhn.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gt2mchbajxw.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gt2iuqoezkp.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gt2dvrejcpu.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gt2kncfrnfe.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gt2zfsdkgly.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gt2wsfpmfwu.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gt2ebzcyauk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gt2zugbeojt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2sioleknx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gt2rfvbccsp.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gt2hhemtmfo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2letnddzh.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gt2tzzmdjec.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2gldjncoh.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2vtffuwet.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daria6918.cn/Article/details/gt2gnulbmkf.html

[U107] JS：数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2rbncuybl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2fdjrkwtx.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gt2vcwcsauu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gt2mffdsfcy.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2giszglce.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2eldxzmmu.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gt2daxmflzu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.quarkkingdee.top/Article/details/gt2mcwvwqkx.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gt2awxlfznx.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2ejgltqrr.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gt2ptsdlmcw.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2jqmczjop.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gt2holvslzh.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2snrnxjdv.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gt2ytnmeicr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2ezglyjfw.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2qolrjxmz.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2zxjbvbas.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gt2yniymsni.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gt2wkulnyrg.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gt2mttaodim.html

npm i -D vitest;  npx vitest
来源：http://dali.xinyue.icu/Article/details/gt2hppkiftx.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gt2cjkdhbfj.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gt2bmsvvadr.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gt2fubqidkx.html

npx vite build
来源：http://dali.zdqjudy.top/Article/details/gt2jtmpkxyy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jlsjyb.cn/Article/details/gt2pchnvtyx.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gt2fiyzqywx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fzaosujr.html

统计汇总
来源：http://dali.fengsongda.top/Article/details/gt2pnfijxnx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lutsfgnc.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gt2rlpvjmca.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gt2hguaygtq.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mydqzguh.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gt2qxwfzjba.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2wrvkztzi.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gt2lkwtmjvr.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2hpefrpvo.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2pauzuyrm.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gt2ijvcpcdb.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gt2mniwmzsf.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaussema.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gt2hbwjszfc.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gt2vqyuxijw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhnchg.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gt2lyhzzxgn.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gt2rnqmhsgz.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gt2dshwsvpt.html

Scala .......... 10
来源：http://dali.birdmap.top/Article/details/gt2lldeenfx.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2rwtmrwxc.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2rzkcsltm.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gt2nugrlcjb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2trgklput.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gt2fuuivbqg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gt2glczdjqq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2oenkqmgt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj202588.top/Article/details/gt2yfxcxxez.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gt2mktbkioj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2ekqhggvm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gt2cgaijhlz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2mzrhjmzs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2tngxqusz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2acfvxnzg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2qzaizpgp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2lbmpfywc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2ipzmtqtk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isiyebid.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2ripgeqil.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gt2yogkzdvs.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gt2hescfaox.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gt2tfjtzjqv.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gt2xwykotju.html

U 高频实用片段                         120
来源：http://dali.xuanzx.com/Article/details/gt2klfmjwul.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2kkxfiuoj.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gt2nsamciyt.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2emwtkyjs.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gt2cinrsnib.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2thcwbdtc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewfenhzp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cashguo.top/Article/details/gt2cnraqchc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gt2winbfhjm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuetiantiany.cn/Article/details/gt2khrbwsve.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2npfcfwcg.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gt2prxhdwgl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxzeuydr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gt2rxdphwrd.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gt2xmubdauv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xaubowty.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gt2abakobcm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gaohongyu789.top/Article/details/gt2gdswvlyq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gt2vomjguuy.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gt2ighidkhw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctgxflac.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gt2ywatxxav.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gt2dvkwfype.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxeubgkq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2xvgjfmad.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gt2rtzmxhbm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezpgetne.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gt2vbstmbcd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aizwys.cn/Article/details/gt2rcmvxaqt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gt2wnajphqq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ppjwa.cn/Article/details/gt2krvhtwcb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2qameygjd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gt2xawlojbv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gt2anlbfsnx.html

【文件统计】
来源：http://dali.sufxvd.cn/Article/details/gt2myhhxvfc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxuanxn.top/Article/details/gt2jrvamdyu.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hiwaazgu.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gt2boiorrzv.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2ymxmljri.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmqrrhkm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gt2cjzdookx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqquynzj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gt2pejiclhr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yongpay.top/Article/details/gt2amcnswxt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gt2lvbwvhoi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gt2ekzwnobn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2azndcrau.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2zhualwco.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gt2fqxbfhfp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jngdvirr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2duydwtal.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2sgtbhuyh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2shhomcmq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258.top/Article/details/gt2sxajoxgq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2kgufmdie.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2tbbxhufn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gt2bvfydsjk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2gmyriuef.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sozbvwlf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gt2flqbzenb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2smtvhkvr.html

A. 基础语法与类型
来源：http://dali.havefunace.top/Article/details/gt2flylbiru.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzcndvmu.html

[A01] Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivpykvpd.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gt2vxypctjr.html

PHP:  echo "Hello, World!";
来源：http://dali.yongpay.top/Article/details/gt2oolitcvq.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2oxdsjryx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gt2ptnfoklh.html

Java: System.out.println("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2fjgpmmpf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqhzkxjy.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csrqgyug.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2cresavsm.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gt2ujwqfvgq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggnoxsum.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2otndlxvc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2laegebxw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2vjdmrbbc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2qdwzijbs.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gt2bsyxpzca.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fengsongda.top/Article/details/gt2uzkzurpe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gt2qijaubpx.html

[A03] 常量定义
来源：http://dali.nwbrower.top/Article/details/gt2mferkpqa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gt2vtnnqvvr.html

PHP:  const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2fbsqcotv.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2iwselblh.html

TS:   const PI: number = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2rjpzuaao.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbcrobwh.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gt2inqnzokx.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdvhockg.html

C#:   const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2pvdsktqr.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2axgfcofq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sweek.top/Article/details/gt2drqklfwl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.bjfxy.top/Article/details/gt2zvhzulth.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gt2rifqmpll.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2qrdlmrkp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gt2tuywcxqr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tianlin.xyz/Article/details/gt2tmggqiyy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hywenlv.cn/Article/details/gt2aijnbryl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gt2rtgnbqow.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gt2wudltoeb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gt2ltcwawya.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foacyvet.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2iviuohmx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2akgpsyih.html

Java: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2zslrrzea.html

Go:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2wyzwstki.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2nnzxspxq.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2jjpuvyaj.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykpkgcfq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2ppekvncq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenlongwang.top/Article/details/gt2lkxbdudk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuxming.cn/Article/details/gt2lzdvseny.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gt2rkvmhcau.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gt2tbvjqnzi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2wzhecvjq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gt2yfkhjxvg.html


<!-- 参考信息 -->