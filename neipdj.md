代发 wailian999

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gttwtbcent.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gtwxisxttm.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gtrngbcyog.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtnzuribzx.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gttcsvavqt.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gtlgqdljet.html

[U54] PHP：空安全调用
来源：http://dali.hfpthk.cn/Article/details/gtznefvrht.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gthdzrnqko.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzbrhpaq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gthbsaieeg.html

[U56] PHP：命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtpymwcrel.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtuwecozof.html

[U57] PHP：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtottslqel.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gtchhxbwbr.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gtsbmtvyvz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtabkyuzyd.html

[U59] PHP：自定义排序
来源：http://dali.gotoacloud.top/Article/details/gtbjntqztm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtmbhhszlt.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gtzybdfnjn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gtfgzkxcqp.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gtokcxmbuh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtahhfcgdx.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gtcruvfndk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtrdghlqok.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gthwezrrsz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigufen.top/Article/details/gtfzvfeszo.html

[U64] PHP：目录遍历
来源：http://dali.birdmap.top/Article/details/gtyqhgdkky.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shzxlz.cn/Article/details/gtnuauraeb.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtsmskpgut.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtricwhthv.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gtmzpkhkac.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtravnbwfp.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtkklkxlrt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtsynyitxs.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gtuxsfnabt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gtkrhkignt.html

[U69] PHP：PDO 预处理
来源：http://dali.chenlongwang.top/Article/details/gtljthfnze.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gthzmqsdzk.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gteeucvkls.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gtrbbkllod.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtnmlxipdj.html

throw new RuntimeException("失败", 500);
来源：http://dali.tianlin.xyz/Article/details/gtmigrhydj.html

[U72] PHP：写错误日志
来源：http://dali.316326.xyz/Article/details/gtwivyjrhq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gtseahypdk.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtumoeyhir.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgfzy.top/Article/details/gtkblrpccx.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtqebjtwub.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtbztgktpt.html

[U75] PHP：依赖注入
来源：http://dali.sufxvd.cn/Article/details/gtgggvacbz.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gtotmpyedq.html

[U76] PHP：简单路由
来源：http://dali.zycfv.cn/Article/details/gtjupxknkg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvppmrymw.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtwxqkhnux.html

composer require twig/twig
来源：http://dali.hnxiangtu.top/Article/details/gtieaaqtrv.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtfilaabrq.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gtuovvgqpd.html

[U79] PHP：静态分析
来源：http://dali.hywenlv.cn/Article/details/gttlungrzd.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gtvebbavjw.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gtzicgdpqt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtnpzdcgkk.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtzyvgrdeh.html

npm init -y;  npm i express
来源：http://dali.tanke756.top/Article/details/gtrlcpuyum.html

[U82] JS：package.json 脚本
来源：http://dali.kuanghao11.cn/Article/details/gtbkkwgqsq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbpftdnr.html

[U83] JS：ES Module 导入导出
来源：http://dali.cucudq.cn/Article/details/gtxpxmescq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtiyuvcuni.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gttdhoikpq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jiagoushi.top/Article/details/gtnkylzcdx.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtcdopvnke.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gtcjhvhfzx.html

[U86] JS：空值合并
来源：http://dali.ydzc1.top/Article/details/gtgghueebz.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpwjngnj.html

[U87] JS：解构默认值
来源：http://dali.zycfv.cn/Article/details/gtzcfqarwi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gttxfjckgc.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gtfdnsmtyl.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphlcgjhv.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtffzjmirg.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtctdznczc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtevoutrom.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbcjamiz.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gtuxnhogml.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gtirgcqzpm.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gtvynmvdgn.html

structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtxyqmzkhk.html

[U93] JS：模板字符串
来源：http://dali.cqqwz.cn/Article/details/gtsigxxoqw.html

`共 ${n} 条`
来源：http://dali.xinyue.icu/Article/details/gttpyslkkv.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtoiwkvzqa.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtbueixyrq.html

[U95] JS：Promise 包装
来源：http://dali.redwolf501.top/Article/details/gtnswzslvc.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gtwwkhftle.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gtevjkcawx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtezacmkll.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtizqkngkv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtwsglsqkf.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gttkdcbdws.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gtmdtqgskn.html

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gtumbofeqo.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gtxsrdwtwi.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gtyttdeohr.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gtdwmqytfl.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gtiuygkppa.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtltoizsvq.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gthilfiljc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gtugmrijnc.html

[U103] JS：定时器
来源：http://dali.mhx1999.top/Article/details/gtybatmcfc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gtqrfcaubq.html

[U104] JS：防抖
来源：http://dali.snrcjt.cn/Article/details/gtwdxqbbkn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtplkgxssu.html

[U105] JS：节流
来源：http://dali.birdmap.top/Article/details/gtgdoftzuy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gteknxjlux.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gtlaivxubg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpgntwlt.html

[U107] JS：数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtghvryjks.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtlfidnfph.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gtutlsabbs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtjeqrrodf.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtvbigcwav.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gttyokuffg.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddaisuge.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gtuybqdhqb.html

[U111] JS：对象转 Map
来源：http://dali.hywenlv.cn/Article/details/gtpxntvpnd.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gtuwvifubv.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtlvvhhuhj.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gteapviglp.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtyxigkyeq.html

s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtqldcjsdh.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gthxnpbwom.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtlxhyjckw.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtxdlgnpji.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtdygovctr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gtpczzjslp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtidgzttwr.html

[U117] JS：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtssdtsvon.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gtaqclhmvs.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gtbkwxfmsw.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtvbqkjyib.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtfzjzfalj.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gtafbqjnsv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtcgbldfdl.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gthfapjxpc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfgvoykvx.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtgnqcpxnn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlcktpjck.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gtgrltwpyh.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtuxmedzwz.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gtlbdzufwy.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gtzpbzanvy.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gtobcjcmaw.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtgirhjljw.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtzqkzpcvn.html

Ruby ........... 212
来源：http://dali.iojbl.cn/Article/details/gtilnbnpwd.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtncaqyidu.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtyhjgfjzf.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtvmoggaut.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtqcriedho.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtckcsriap.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gtxldzvykz.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gtahipwdqq.html

Lua ............ 10
来源：http://dali.ehwqpu.com/Article/details/gtwmzczofy.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtcybsidjf.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gthlqomros.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtpxkfmnsf.html

合计 ........... 2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtkaidunyi.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gthnkthshi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtpnswtbtl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtxtusfuob.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtlnhogzyc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtlvmajgso.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gtzdxvfuzw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtcpuuinlk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtmxpeolsh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtrlxyqowm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtqgdekupe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusussufj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtudasoutb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtxxwayytg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtggidbmen.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtsiyurdvd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gttunvrleu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtemkpfamq.html

Q SQL 专题                              90
来源：http://dali.aizwys.cn/Article/details/gtoprdtydh.html

R Bash 专题                             80
来源：http://dali.xylfe.cn/Article/details/gtqbcpfehx.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gtwlsorcpr.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gtzqjdjopq.html

U 高频实用片段                         120
来源：http://dali.zhixingplan.top/Article/details/gtemhmhtai.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtvrypclyi.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrdlgwsj.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtdefguuzp.html

使用提醒
来源：http://dali.svipenyu.cn/Article/details/gtlnsvlxfp.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gttsumjtpz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gtsisdrssz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gtjyeopwut.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtojfyxhzl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gtyqixutwp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gtiadregmn.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gtkvrilzws.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtuppwyvcg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gthvpggige.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtqorelgfg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtymbgysid.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gtawnjilcy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gtlrccqgws.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gtodpplpxy.html

SQL · Bash · C · C++
来源：http://dali.jinghuilouyu.cn/Article/details/gtixdqghkd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.redwolf501.top/Article/details/gtpaebardj.html

【使用说明】
来源：http://dali.jianghu66.top/Article/details/gtgmhgfxkj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gtljrnslhl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgufenzy.top/Article/details/gtdzoudrmj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gaohongyu789.top/Article/details/gtiuezylwr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvouciyzv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gtfckjvwxi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtvxeyyvob.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtvqiyhepc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gtxiogudvi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daxiang520.top/Article/details/gtbarlmnex.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gtuaezxlkq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sysykeji.top/Article/details/gtmjdqfysd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hysaishi.cn/Article/details/gtfgexnmlo.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gtwvegmywt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gtttzdkzmn.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtfsezkqlh.html

目  录
来源：http://dali.yj20258.top/Article/details/gtzjpwwlmo.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtunlpllst.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrxmgsem.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtlhyvppks.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtgyripvcp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtctdfxexi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gtuihdeqjm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtnppnyvpu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtduhldakz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtiackywob.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtybfexrff.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtkucjkfqz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtaibsmseg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtawpsygea.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtvmemwcej.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtwnwyfdcj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhixingplan.top/Article/details/gtfcliefhc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqmpiacb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtoigeifss.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtbihqydhk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkjyyvif.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gthtlubwoy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gthmgjcmiw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmzyuhevj.html

A. 基础语法与类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvjdinww.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpdvyefqo.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gtarisvxhd.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtazxvfdsw.html

PHP:  echo "Hello, World!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetcwzbsw.html

JS:   console.log("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtybqhlozc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tanke756.top/Article/details/gtpvahalei.html

Java: System.out.println("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtcuyutxzg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gteaelbixz.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsdgxtjy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtbwxcrodc.html

[A02] 变量声明与赋值
来源：http://dali.yangfankeji.com/Article/details/gtzpfumqyw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ehwqpu.com/Article/details/gtrvbixagf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtojjxjpft.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtlielswyy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daria6918.cn/Article/details/gtboxyxods.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gtwnmywhkl.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gtbdznimqv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gtwzhmrawc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtyocslnnl.html

[A03] 常量定义
来源：http://dali.zhiwuduotai.top/Article/details/gtvxtexfer.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hfpthk.cn/Article/details/gtkqsneqzl.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtniltkyhp.html

JS:   const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtdilvjzdy.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtfzwynedd.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtlpykylfx.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtuciwcccj.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gtnohfskoz.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtfnjlzvay.html

[A04] 判断变量类型
来源：http://dali.hammf.cn/Article/details/gtnamxeqkt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gotoacloud.top/Article/details/gtfnzhyhfg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtyzczfdpu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtfkowzcnw.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtidfdhnob.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gthavaulhw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zycfv.cn/Article/details/gtjeixsqhg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.smart0.xyz/Article/details/gtykhmnwkk.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangtech.top/Article/details/gtamepiwck.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gtsmluejsf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gtscvzyqzn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtramlnvwm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewgmgpxi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtfneuspaq.html

Java: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtlqrihyts.html

Go:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtdkuqgjva.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtaxuxyjcj.html

C#:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtpnrjrerr.html

[A06] 字符串转数字
来源：http://dali.daxiang520.top/Article/details/gteftygtsi.html

Py:   int("42"); float("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfpacrcg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtkmavbnak.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtlvdbdtnz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfdkwbhu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtshsewadh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gtkvmjinov.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgufenzy.top/Article/details/gtxivmxrto.html


<!-- 参考信息 -->