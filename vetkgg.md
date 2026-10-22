代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtkigcggaw.html

"值: {$a}"
来源：http://dali.haohaochexian.top/Article/details/gtvgbergsw.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gtkzcrztrv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtaatlahrs.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gthymizuxm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtxgedxepx.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gtoiwchirf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmpuisid.html

[U61] PHP：正则
来源：http://dali.chenlongwang.top/Article/details/gtkykxpkkn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtvgdqmxig.html

[U62] PHP：日期对象
来源：http://dali.jyoumei.cn/Article/details/gtxqvqecec.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gtrqyppanb.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtjsqrymfz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrnzpqdv.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gttmfalemo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gtqnslajfr.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygvypjbj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtfriyxzda.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gtutaxgzqi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgbbbann.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gtfgujvajg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jyoumei.cn/Article/details/gtnloeyqbt.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtxrijmjkn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtndyerlng.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gthmdcprnc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gtavplcaeq.html

[U70] PHP：PDO 事务
来源：http://dali.hnxiangtu.top/Article/details/gthmtfrhlh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtmsqhyoxz.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gtmldildyi.html

throw new RuntimeException("失败", 500);
来源：http://dali.yueranfly.top/Article/details/gtksopoash.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtfioxlkof.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnqzz.top/Article/details/gtqwrftnfo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gtkptapytt.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gtjcsgqlgn.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjebfnsbw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gtmdduyhab.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gtlesvyfss.html

composer require psr/container
来源：http://dali.guowangkeji.top/Article/details/gtubaoudqx.html

[U76] PHP：简单路由
来源：http://dali.hysaishi.cn/Article/details/gtcbgofjtw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gtaekamzsl.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtsccyqsbf.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gtfmuizenp.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtzxlixmot.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrofbqsjf.html

[U79] PHP：静态分析
来源：http://dali.hnxiangtu.top/Article/details/gtwmxwlsww.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gtqbsfpofl.html

[U80] PHP：代码规范修复
来源：http://dali.yvedp.cn/Article/details/gtloczzjlu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.andypj.xyz/Article/details/gtfluzilbq.html

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtfmhzpfnf.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gthatmuibp.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtxpykrzrg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangdashe.top/Article/details/gtapsqedsc.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenlongwang.top/Article/details/gtzpzjjday.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtylkrhpsy.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gtcldhmumz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gtflsgwace.html

[U85] JS：可选链
来源：http://dali.fengsongda.top/Article/details/gtzfolyvrn.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gtaqrsqboi.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gttpavczrw.html

a ?? b
来源：http://dali.cqqwz.cn/Article/details/gtsqnesjew.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gtkmzenoss.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gtdleisiwa.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gtfqvqjsno.html

{ ...a, ...b }
来源：http://dali.gaohongyu789.top/Article/details/gtxcifizai.html

[U89] JS：数组去重
来源：http://dali.aizwys.cn/Article/details/gttonipayf.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtsnnevawj.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gtztxzcdsw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtvypglyfa.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gtcsgkspsu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gtdymdaprf.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtszaleyud.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtcfbsoyna.html

[U93] JS：模板字符串
来源：http://dali.xinyue.icu/Article/details/gtfzicqwpv.html

`共 ${n} 条`
来源：http://dali.sysykeji.top/Article/details/gtbjambdzv.html

[U94] JS：箭头函数
来源：http://dali.havefunace.top/Article/details/gtvcqiyuqk.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gtkurmenii.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gtdsesmqem.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtumokuxsd.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtsfrzkuun.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gttljhyzis.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtrgibfbrm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gttenoyooq.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtjdakbyrv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtqdpottew.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtvumervwv.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtarihtfqq.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtnfvwovvq.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gtovmvupxx.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gtyyaykxuz.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gteandgshb.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtzdtxkwpw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gteegmkmrj.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gtmhzerrik.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.andypj.xyz/Article/details/gtgbnkbwbp.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gtrnqrmszn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtjwcgeyjz.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gteelurkow.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtyafowsts.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtatzmkttc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtworpqknw.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gtayhwmkmz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofkcxzhg.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtdcvbwghh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gtqmrxlbbb.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gtsbwwpbic.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtoevyifpy.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gtztowftii.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtogejeute.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtjshjkonp.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gtgjxwrzni.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtxrgcmlsr.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtrolyvpno.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtdnhedafl.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtiebgsfwo.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtgemnglqb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypzxrxij.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtcumsqbdu.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gttrwmcreh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gtuykzpvds.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtdyxtxkjg.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtbhmcmebn.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gtsmphtdhu.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gthyjllqjh.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtcguojqsa.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtfhfvwttk.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtgfhpsmas.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yueranfly.top/Article/details/gtzxmoqyqg.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gtoxyhgzxb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyywwievv.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gtmfblcqqc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbjjlfslu.html

按语言统计（条）：
来源：http://dali.jinqigfzy.top/Article/details/gtzmekwebe.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtnsyfjbil.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtpwjjtbxh.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gtgcsjyzzl.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtokcscejj.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtopobmcss.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gthxvqhusv.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gtmjbrytyg.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtmzunryid.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gtjywtninr.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtvtfnxgab.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gtlqpgukmc.html

Bash ........... 80
来源：http://dali.hysaishi.cn/Article/details/gtbhexfboi.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgebmqqg.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtpslfqocu.html

Lua ............ 10
来源：http://dali.ybcxt.top/Article/details/gtrildcqxl.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtvpscucmm.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gtujixpzox.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtdseddhpi.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtdwislkrz.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gttojqnduh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gtuzxyytql.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtwolvjcvd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtpfqhszab.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gtuboeoivn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gtwqcccayl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtlrtzutmr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtrqgrbqvt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtjooeorxy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtpxnzptwe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gtwvsastmh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gttqnijfki.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtayrrfzbo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtmhexvkcx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtwsqkvovi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.havefunace.top/Article/details/gtfectclar.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtabtstyrx.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gtycyclels.html

R Bash 专题                             80
来源：http://dali.shuidangran.top/Article/details/gttlarsijo.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtyqdqmomj.html

T 其他语言补充                          60
来源：http://dali.zhixingplan.top/Article/details/gtiwlnkcbh.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gtblwichny.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtdjfvsxov.html

合计                                  2106 条
来源：http://dali.jianghu66.top/Article/details/gtrtatyurw.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtdiwruvdi.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gtahfyhbwl.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtkoooekmp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtfjptonln.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangdashe.top/Article/details/gtctjgtdzc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtedducshu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gtfrpmbyqb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.0kj1m.cn/Article/details/gtuccpwpxq.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtaqkoiobj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsijvuulk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigfzy.top/Article/details/gtznpymulx.html

Common Programming Examples Cheat Book
来源：http://dali.fengsongda.top/Article/details/gttrpmprwg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtywdakidv.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gtqlyfvabn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.feifeiyinyue.top/Article/details/gtfbimcnqz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gticmtycoz.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gtspbowsel.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gzhubu.top/Article/details/gtnwufudef.html

【使用说明】
来源：http://dali.daria6918.cn/Article/details/gtelviaetn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxenybqt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jianghu66.top/Article/details/gtvoksddlf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gtkxbcjukc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gtkpffqtcn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtwpmqgqrk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.snrcjt.cn/Article/details/gtissazeyt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gtvkbcffmp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guowangkeji.top/Article/details/gtyqqxlhtz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gtlernudun.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqoqtxkj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcchzxhjz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gtxxavbfoy.html

【文件统计】
来源：http://dali.fzhhl.top/Article/details/gtrsbdraxz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhiwuduotai.top/Article/details/gtnvcvvrjz.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtixqareki.html

目  录
来源：http://dali.xinyue.icu/Article/details/gtfynkpxdp.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtggeuhomm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtdazxsuvb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtjxxjwdib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtgaoyroem.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gtngmavzqr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gtyqgblqmh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gtlmhsntvw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtnzqwdjke.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtehgbguds.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtfpjroqyy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtaipgwmao.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtatipryyu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtmoehqros.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtabhitmvo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtkkskhawe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gtlyhreeun.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtlnrmvowi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtachrmqlc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtddhhknfm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtukhicfbh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtugcffomk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtatanglra.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjuqtuakb.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gtprobpbxm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtaacvvqqs.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gtygfvsgyq.html

Py:   print("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtqglpfcoo.html

PHP:  echo "Hello, World!";
来源：http://dali.yueranfly.top/Article/details/gtrkywctjz.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtyxcomgwy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgfzy.top/Article/details/gtmsqmxknh.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtphhwqwog.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtvhbldnxh.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfsnnmpd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtyccrpych.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtlrpaqati.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhongyouzk.top/Article/details/gtanmwsmyj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtnklcjdcy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtwmmavutc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtfkumoxuj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gtzvsahnyr.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdskbdrs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gtscultzfe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtdozhdjwk.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtavleiryk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuanzx.com/Article/details/gtbdfaoxeq.html

PHP:  const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtdepctthj.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtiminucbu.html

TS:   const PI: number = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtyuptzgag.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtscwvdkqq.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtcvffmleh.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtehtuvzic.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtnvvspmrp.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtslyovmba.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxuanxn.top/Article/details/gtdjrfrsbc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cdnleiting.top/Article/details/gtkydskejv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gtwovdjodn.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtecbwetcm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtamewqgbf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sxryk.cn/Article/details/gtjznccmzh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnxiangtu.top/Article/details/gtuxdybigw.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gtjhkltzam.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gtrfkflrih.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sxryk.cn/Article/details/gtffmpugky.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtbuzsdmah.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtzgbjwmrl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtwqxiaqjl.html

Java: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtqfgthyeq.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtntbtevqt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtlwijvaer.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtdczjwzga.html

[A06] 字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtdoaypmfn.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gthjholfxp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gtqtpstmlr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtnbbwomql.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtmthfhusm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtdmiyzlfx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ivvv.top/Article/details/gtbmmdhdpp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aibaodan.cn/Article/details/gtxkmkiyop.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtsvmfigwv.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gtugdgzlhm.html

Py:   str(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtasaslirz.html

PHP:  (string) 42; strval(42)
来源：http://dali.c1oappe.top/Article/details/gtpbhnnpac.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gtrbsqkyqw.html

TS:   String(42)
来源：http://dali.hnxiangtu.top/Article/details/gtpfihythf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shuidangran.top/Article/details/gthnontvjt.html

Go:   strconv.Itoa(42)
来源：http://dali.ppjwa.cn/Article/details/gtdtmeitoh.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gtkdaqddcz.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gtxeoszazf.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gtfuzmroat.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gttwsqhuyi.html


<!-- 参考信息 -->