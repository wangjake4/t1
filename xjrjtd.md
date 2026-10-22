代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2epsrlbgl.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gt2aberhfbk.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gt2vzrbonkt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258888.top/Article/details/gt2qouchscb.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gt2bjvbcbth.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2zvphaaxq.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gt2gavxyxxb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gt2twysslvo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvnlofe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2wviimkmr.html

[U62] PHP：日期对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ourhrqjc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gt2etkdbxwg.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gt2vhaucjri.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gt2oziylesn.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gt2bqkhpnvw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ehwqpu.com/Article/details/gt2kfukvami.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gt2tbyhbikb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2borgzhzc.html

[U66] PHP：设置 Cookie
来源：http://dali.aizwys.cn/Article/details/gt2vgyntjre.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gt2fqvgswli.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gt2vcgovyar.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shuidangran.top/Article/details/gt2xkbpizre.html

[U68] PHP：PDO 连接
来源：http://dali.cqqwz.cn/Article/details/gt2ofebyooc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rggcbtmk.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gt2zxjuurlr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gt2wkjptlgo.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gt2qbzzibxm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.c1oappe.top/Article/details/gt2abimgwqq.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gt2mcuiskos.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqflrbp.html

[U72] PHP：写错误日志
来源：http://dali.fengsongda.top/Article/details/gt2witoxual.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpyevuku.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gt2usegykjs.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gt2oojkqaku.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2tdonpmjj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlweyfoc.html

[U75] PHP：依赖注入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlxlkqqm.html

composer require psr/container
来源：http://dali.vqdsnc.cn/Article/details/gt2drvikngv.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gt2sblpxazb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvvtabeg.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gt2mpkwtwqm.html

composer require twig/twig
来源：http://dali.hysaishi.cn/Article/details/gt2nxfiross.html

[U78] PHP：单元测试
来源：http://dali.jiagoushi.top/Article/details/gt2biunkyqz.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gt2tvzjshdd.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gt2qyphotks.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gt2tuhrkyyp.html

[U80] PHP：代码规范修复
来源：http://dali.kuanghao11.cn/Article/details/gt2wimfoicu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yongpay.top/Article/details/gt2slwrsgfv.html

[U81] JS：初始化项目
来源：http://dali.iojbl.cn/Article/details/gt2xsnxkjwj.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gt2ctukggwj.html

[U82] JS：package.json 脚本
来源：http://dali.zhengqikj.top/Article/details/gt2bclxxisb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gt2tkhpjppd.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbdfxjih.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gt2ljskaxov.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gt2xjuvnkvh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gt2taamcvmz.html

[U85] JS：可选链
来源：http://dali.havefunace.top/Article/details/gt2fbehnqzi.html

a?.b?.c
来源：http://dali.nanxuanxn.top/Article/details/gt2xadrgplu.html

[U86] JS：空值合并
来源：http://dali.mhx1999.top/Article/details/gt2tgcaujme.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2orgzvhvj.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gt2xomllwbk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gt2ollwiqfr.html

[U88] JS：对象展开合并
来源：http://dali.9152youxi.cn/Article/details/gt2uqrisdzy.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gt2witgsjgk.html

[U89] JS：数组去重
来源：http://dali.nanxinkj.top/Article/details/gt2ytfnsvsf.html

[...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2nfjcrxdw.html

[U90] JS：数字数组排序
来源：http://dali.yonumen.top/Article/details/gt2umqeiyon.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2thyjgivu.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gt2yqqgitxb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gt2kvjgesrm.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iazdnchk.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2klohwxnb.html

[U93] JS：模板字符串
来源：http://dali.gzhubu.top/Article/details/gt2wovuqhnx.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gt2nsxlgqzl.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2gdcjdrez.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2stphzomi.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gt2wzbnmpja.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gt2pixeunhg.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gt2otllmqup.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpbltvlh.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gt2csvwjvwb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2ujpjvfzn.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gt2mijzjdhy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjoddkow.html

[U99] JS：事件监听
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atgzxqke.html

el.addEventListener("click", e => {})
来源：http://dali.kuanghao11.cn/Article/details/gt2podulhcn.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gt2owbidgta.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2twimkvsy.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2mnbcdhil.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gt2oyncxvum.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gt2wpirytfz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gt2mvijediy.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gt2kiroooeb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdurhbkb.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gt2ozsoghmn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2ficpbyjm.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gt2bmmeebzj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnqzz.top/Article/details/gt2iqshrcrz.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2sjnoquuc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgufenzy.top/Article/details/gt2ejnoyfaz.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gt2xtjgqjtz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2vyxeixhe.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gt2xzpyvdxi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gt2ltatogvk.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gt2szjxeixs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2gbfxicrc.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2hsjjepbr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gt2bkrdpttt.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2didnjspu.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fratqnqu.html

[U112] JS：字符串补位
来源：http://dali.daxiang520.top/Article/details/gt2hxrafoui.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2ydwlogle.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gt2zcjmxhas.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2ehtqaxnh.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gt2yydtuxdr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gt2igntzvsf.html

[U115] JS：生成 UUID
来源：http://dali.shuidangran.top/Article/details/gt2arwtlbrf.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2manxnsjf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gt2uyzhbesv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.smart0.xyz/Article/details/gt2quynbchd.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gt2upizaoqf.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gt2ingwpqav.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2mmrwrbzp.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gt2fukxchrz.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gt2wmiolrmm.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gt2mgfskvrp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gt2fimyhvwy.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gt2puqmjtid.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2aksauebt.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzjwifdd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2bzzmmuan.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gt2sgwurfrh.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gt2geiquvzd.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gt2opcqyfvv.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gt2sxgvtrgx.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gt2yaliovvj.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2iculqayl.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2mfmbonhu.html

Ruby ........... 212
来源：http://dali.ydzc1.top/Article/details/gt2wqbehfaw.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gt2sycsqbly.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gt2btezesjc.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gt2zckqclkc.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gt2cqpbitzt.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gt2witlqafn.html

Kotlin ......... 15
来源：http://dali.guannengcc.top/Article/details/gt2drgcseib.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2bmfrfccy.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gt2hoccedcn.html

Perl ........... 10
来源：http://dali.cdnleiting.top/Article/details/gt2dfvpcsee.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2grwwcqls.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2xluaxcpn.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gt2sjamarng.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gt2bmrgeizb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gt2prtzixew.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rngojoiw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2sawntfgf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gt2xypuwxeu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gt2ntomfnnk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2dwifmaua.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gt2fwxctnem.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gt2wjcbcrtr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwzghbgs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwyuonld.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2uvecoajg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2zsmyreoy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2jfgmbcpd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gt2oivmmnyu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tian-w.cn/Article/details/gt2ivpvbhen.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2gaisoiwz.html

Q SQL 专题                              90
来源：http://dali.nanxuanxn.top/Article/details/gt2wfnyijaw.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gt2jhdaaksp.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gt2vsyjnids.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gt2zkbhhssw.html

U 高频实用片段                         120
来源：http://dali.jyoumei.cn/Article/details/gt2riprjbvp.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2cysaqzdr.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znazfzwy.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2eztemuaa.html

使用提醒
来源：http://dali.zhengqikj.top/Article/details/gt2oikcqfmn.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2eiqtkzbh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gt2vdifluzp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gt2licpexre.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjmulguu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hywenlv.cn/Article/details/gt2nsziljgp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gt2qipcgcce.html

—— 文件结束 ——
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aekcblds.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mpfawhsz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gt2inmccgee.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqjpeixk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2pfxjdwtv.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gt2xgoqjwhn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gt2ezfsaymz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.bjfxy.top/Article/details/gt2srqjgtag.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gt2puhwmdiw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gt2xjhjcywb.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gt2yraavovj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gt2slisvpjp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbbqchqo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gt2snogkuxq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeozccxc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gt2asrzqkho.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gt2ahmnugxi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gt2lygutlgs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.snrcjt.cn/Article/details/gt2pbkgrmoi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnbsiwlc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gt2efqhdcoi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gt2yphsbyhn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nwbrower.top/Article/details/gt2nituvzhj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xecxhdcm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gzhubu.top/Article/details/gt2ksgebdyh.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugwqqpip.html

目  录
来源：http://dali.gaohongyu789.top/Article/details/gt2tvaqtjke.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2umtwktam.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gt2vjfaqopy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2nwzrmheu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsmkiaqq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csrscjxs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenzaomai.com/Article/details/gt2jzstuwms.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gt2eslngafv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gt2vqcfiyxt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2kkjsfjcw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2itlpooos.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2yaepdwoy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2qvqzwhtw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2vtjzphbg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2ezkjsjsu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2cjrkwakr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdefqjgd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2pbaeyhml.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gt2vhkjdppv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenlongwang.top/Article/details/gt2dnmnalcu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gt2hpjutnps.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2ykbbairy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2fakrawtv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2hlovdqab.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gt2trymjqju.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wrulgiol.html

[A01] Hello World
来源：http://dali.sysykeji.top/Article/details/gt2htvzzjlz.html

Py:   print("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kusrdudi.html

PHP:  echo "Hello, World!";
来源：http://dali.zycfv.cn/Article/details/gt2zyfptjfv.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2yoazqbdy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gt2sipdkvcg.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwvdinrg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gt2zqrcvjgz.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gt2drpkmvoz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gt2nynwfqph.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gt2fkztabov.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrjbsonf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2yasswkpy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlfpkxpv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2mibnrdvh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2awxvyeea.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gt2ijmejnbu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmazztdm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2llanofcc.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gt2wnvhpjuc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gt2abasvzbx.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2ohdymwor.html

JS:   const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2ayaswbps.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykdcryik.html

Java: static final double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2kiaooxpy.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gt2tacgukcx.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gt2drfattxl.html

C#:   const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2trtssgae.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2qoxvoldb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2qstkenaf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hammf.cn/Article/details/gt2ewgfimnl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2ajjwxxxh.html

TS:   typeof x; x instanceof Date
来源：http://dali.dashuyun.cn/Article/details/gt2kihobffb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gt2kidxyyfb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gt2csxoacca.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ppjwa.cn/Article/details/gt2ronmmzqc.html

C#:   x.GetType().Name; x is int
来源：http://dali.snrcjt.cn/Article/details/gt2lccmlmjq.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gt2yukyvnwh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gt2tflqragl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2oanyniyi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2ominherq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyjplxbv.html

Java: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2qhlfdsov.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpkvvrdw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2ymthuuvw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxllfhb.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2eflwedpo.html

Py:   int("42"); float("3.14")
来源：http://dali.tanke756.top/Article/details/gt2isgepajd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqhwevmo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.smart0.xyz/Article/details/gt2roawzesj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gt2llwqgunk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2zlealfdx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxyxrwig.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfvlcexf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tianlin.xyz/Article/details/gt2ykmaihyo.html

[A07] 数字转字符串
来源：http://dali.havefunace.top/Article/details/gt2vfeyqvdb.html

Py:   str(42)
来源：http://dali.ydzc1.top/Article/details/gt2qudcoeza.html

PHP:  (string) 42; strval(42)
来源：http://dali.cdnleiting.top/Article/details/gt2gbgzynsx.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gt2mcstzlon.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gt2makloyxr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gt2ksvbuyuh.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsjzscll.html

Ruby: 42.to_s
来源：http://dali.jianghu66.top/Article/details/gt2ltdymmrp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2afhcnjrj.html

[A08] 取整与四舍五入
来源：http://dali.yuanzhike.top/Article/details/gt2jyfltsbo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjhhsxe.html


<!-- 参考信息 -->