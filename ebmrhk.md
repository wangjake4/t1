代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gtfjszqasd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtlwemvwyd.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gteekiuevr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtqroohbfp.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gtfkcixquk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtjmszxxsu.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtpjzvwgzd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hfpthk.cn/Article/details/gtejqgdoyr.html

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gtnibafmty.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gtfhnithas.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtiduzarvf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtjekwwcuk.html

[U65] PHP：会话
来源：http://dali.cashguo.top/Article/details/gtdnpedxsk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtpzejancl.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtdfsnnxny.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gtoxyzyzhx.html

[U67] PHP：处理文件上传
来源：http://dali.cheryme.top/Article/details/gtkwbdomxz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.316326.xyz/Article/details/gtoeichtzg.html

[U68] PHP：PDO 连接
来源：http://dali.daxiang520.top/Article/details/gtxfaqcnrt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtnlfvsdzj.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtihyywaws.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gtgfzgyvge.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gtmzdmfous.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gtudwccffl.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztwgmdeh.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gtdwyuzqrw.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtroryywqq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xziqi.cn/Article/details/gtysbnglqq.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtwtxidzqc.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtxjslgiaq.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtimgtiqzu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.bjfxy.top/Article/details/gtitpjqxpa.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gtprbkowtu.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtowujjwqc.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtoylrvsva.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gtinyeaaii.html

[U77] PHP：模板渲染
来源：http://dali.zhixingplan.top/Article/details/gtmwfwnwyb.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtvfdxhsrg.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtudnrbtwn.html

composer require --dev phpunit/phpunit
来源：http://dali.sufxvd.cn/Article/details/gtujhkevzc.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gttptmlslh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhixingplan.top/Article/details/gtlvpodfju.html

[U80] PHP：代码规范修复
来源：http://dali.smart0.xyz/Article/details/gtllvwtvit.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gtkooxgshb.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gteroxgpmx.html

npm init -y;  npm i express
来源：http://dali.nanxinkj.top/Article/details/gtijymbajg.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gtlzhkeahy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtcbwogvtj.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gtkqqolrsx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtfmvrvozd.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gtellsdvsl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gtnpnqsfdh.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gtgrxerzfg.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gthszrmuvy.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gtnekniore.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtaszbhaxi.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gtwgzmidmz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhengqikj.top/Article/details/gtyikkxmce.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtdnrmeceq.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtqmlkfspk.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gthzmedcol.html

[...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gtjpftfrrt.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtwvpzypqx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtxiakfqka.html

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gtxftnlcrj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenjidiqi.icu/Article/details/gtsrkmmaln.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtijmxhzmd.html

structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwdvftler.html

[U93] JS：模板字符串
来源：http://dali.ivvv.top/Article/details/gtkwzxxnbg.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gtslufazjo.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtgfitczrp.html

const double = x => x * 2;
来源：http://dali.smart0.xyz/Article/details/gtxqbcchcs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gthlxhkogm.html

new Promise((resolve, reject) => {})
来源：http://dali.yanxiufei.cn/Article/details/gthwktfgdy.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvnuwjzw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtslzbhdux.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfizperjo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtsgenpdel.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtjrtkewro.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gtsdgztihj.html

[U99] JS：事件监听
来源：http://dali.chenlongwang.top/Article/details/gtricqhvak.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gteaxekuvq.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtrpwbbwbv.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gttbssjzlv.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtnvouhtch.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gtiecjdgff.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gthmmvxyeg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtvwtkfqvl.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtckhddsvo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gtmuohfcne.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gttruorcgu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gttolbxzmi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtjnravarx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gtztmycbuk.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gtjvdrcvvy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gtbworbzjs.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gtynyhnqnv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtdjwposjw.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtpkhczwce.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gtanbslqxj.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtducssbjj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtrepfnywp.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gtiihaydmj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daxiang520.top/Article/details/gtpbgxegco.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtffyxyduj.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtuljljvco.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtptmtrvtk.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtnwmdkvfy.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtcnfzlsag.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtxlzaoqbw.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gthzpfzwsv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtqisewtbj.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldaagkxw.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtvoahdknf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gtvzaayste.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtpqcqqqre.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtnptzrlwe.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gtwnpcrvgj.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gtfkclvczi.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtqeuusbgf.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gthrcjzyyt.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtptlgfdda.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gtrygqdmwx.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gtlzsrqtja.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoidsuxxg.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gtngfplrqu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtixndkrqn.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gtxufdbpjy.html

Python ......... 252
来源：http://dali.nanxinkj.top/Article/details/gtojhdrwgo.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gtrmsmaqsq.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtondvqcaf.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gttxgygzls.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gtucxxnmov.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gthkwitpgj.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gtbgbgouck.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gtzgvlxuim.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtagnfxkbp.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gtwlsqeksv.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtrxqnfuch.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gtjrfzemjg.html

Kotlin ......... 15
来源：http://dali.xuanzx.com/Article/details/gtbwbjkshl.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtgtibwyor.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtzcftpwvc.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtchbyucea.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtwgvntvfd.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtnuaxbjfv.html

合计 ........... 2106 条
来源：http://dali.cqqwz.cn/Article/details/gtcjkjntzt.html

按章节统计：
来源：http://dali.yj20258.top/Article/details/gtfbetwxvg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtixktrxll.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtuhemrdrv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcikvsnii.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtponlbtgq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gtmixxoyln.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gtknjqwhuf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtqdjvzwal.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtktjcamsx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gthkuavnor.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtluksezde.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtgpotaqpj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtfgyiivbc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtedtpppql.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gttgbzwgxx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhiwuduotai.top/Article/details/gtqvwznrhp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtsdenovit.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtbaxbbwer.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gtdzzllypp.html

S C / C++ 专题                          60
来源：http://dali.xuanzx.com/Article/details/gtwotdlnwi.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmhvdyqg.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gtmfswrbst.html

------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gteyqoemsn.html

合计                                  2106 条
来源：http://dali.birdmap.top/Article/details/gtammjzokv.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtkjrepmjw.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gtbkbudusa.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtjmemmvgy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.havefunace.top/Article/details/gtrldopsqi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guowangkeji.top/Article/details/gtyrhngpsy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gtshvforec.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gturiosgrh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fzhhl.top/Article/details/gtucidprnh.html

—— 文件结束 ——
来源：http://dali.gzhubu.top/Article/details/gtzmpdxwlu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxcxvifjm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrqxslek.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gtxbjqbmus.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqkylmrqi.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gtmondiexf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.dianchejie.cn/Article/details/gtlklidudg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.quarkkingdee.top/Article/details/gtedhbppyk.html

SQL · Bash · C · C++
来源：http://dali.cheryme.top/Article/details/gtxxlqpqut.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrsitdkh.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gtxwzxhfdl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.0kj1m.cn/Article/details/gtqdxsmwij.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtnvrvozaj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gtujlcpfhc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hongshengwenyu.top/Article/details/gtlqyywzga.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangshuangyany.cn/Article/details/gtlwalaxev.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dianchejie.cn/Article/details/gtyrkbkbnm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gtmsjptaqs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzzovxcj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuanzx.com/Article/details/gtjplmkupf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuanzhike.top/Article/details/gtmbamyntr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsgexgwf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gtsjyenkgi.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gtxbrruiyi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gtgkqoxodx.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtlmfevayj.html

目  录
来源：http://dali.jlsjyb.cn/Article/details/gtjeutdgwd.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtsvvakden.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtveswsdho.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtztwikbbv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtixithdco.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gtgczomela.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtixdtngjd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsnsbdtz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtdcgobtat.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtjlqpbxxq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtiosvtnkb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gtvydknucl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtdwxyaphf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtpyvwadma.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtybaeaiux.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtiiqwwrfz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtzhzgkvcv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtopsyraru.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gtykurujoj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtycgfatuw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gtwdkfjyuy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtzqkijsoq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtkhovckgy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrzfeiyph.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gttqbdyjln.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbgehphio.html

[A01] Hello World
来源：http://dali.aizwys.cn/Article/details/gtbnhcnjdl.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhvzzber.html

PHP:  echo "Hello, World!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsacwhbs.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkebxqcxu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guannengcc.top/Article/details/gtianmjxhk.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtuyuqjwzy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtxyhjekry.html

Ruby: puts "Hello, World!"
来源：http://dali.smart0.xyz/Article/details/gtriylldan.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gthzpuruhm.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gtigeldiqa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtsubiyliz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gtdppiuvca.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gthqdwwzhq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gtjgfrshnz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtnbcfkura.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtnucuhlrn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.mhx1999.top/Article/details/gthvzentou.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhnngsaz.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gtxgegsdlw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258.top/Article/details/gttcypnqha.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtrliuvpcj.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtjafewont.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gthxnrljwx.html

Java: static final double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtqoleemsa.html

Go:   const PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtfxdntdtl.html

Ruby: PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtrlbvkyic.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtoqszlmgs.html

[A04] 判断变量类型
来源：http://dali.xziqi.cn/Article/details/gtxgzzofll.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.meibo888.top/Article/details/gtgzzzirjc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gtzmjffrcu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtuwrsfiiz.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtenltvpob.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gtjvtrgrnv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.c1oappe.top/Article/details/gteqehojxx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gtchoovdle.html

C#:   x.GetType().Name; x is int
来源：http://dali.ppjwa.cn/Article/details/gtlywsuyhk.html

[A05] 整数除法与取模
来源：http://dali.birdmap.top/Article/details/gtayzogskp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gtesewoxiy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtglkjbsku.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtyoeiaktn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtjloglgur.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtfqbawgdf.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtoacziqdw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gteuzfetwc.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtitfgqlca.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtiqazeunc.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtbpilsyvx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.iojbl.cn/Article/details/gtvrcljkgv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtffpasnyb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gthbepczre.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtgtavxmyv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxuanxn.top/Article/details/gtqrtwewut.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsztxsrwx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtnrttkjkj.html

[A07] 数字转字符串
来源：http://dali.smart0.xyz/Article/details/gtrtdripif.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gtzdfwtpgr.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhhzrjpp.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gttwhpmizs.html

TS:   String(42)
来源：http://dali.316326.xyz/Article/details/gtufzwhwdy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhoulong.xyz/Article/details/gthtjtjmhp.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gtdpvzqypq.html

Ruby: 42.to_s
来源：http://dali.gzhubu.top/Article/details/gtfaqelofc.html

C#:   42.ToString()
来源：http://dali.0kj1m.cn/Article/details/gtaiybxmra.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gtousibpby.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtfwogyfbv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aibaodan.cn/Article/details/gtammqpwgz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtvojqckrf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fzhhl.top/Article/details/gtwuazfvsu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtwdilfifl.html


<!-- 参考信息 -->