代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oosnhznm.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gt2lcqcovrv.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gt2kdkvmeam.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2erfunlwy.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gt2quxrovky.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gt2nhpnwuay.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxinkj.top/Article/details/gt2oobhfwqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqpzvmsu.html

[U61] PHP：正则
来源：http://dali.kuanghao11.cn/Article/details/gt2nvinefzt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2opdppsev.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfjtxxlr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guowangkeji.top/Article/details/gt2rqycvjiu.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gt2lwjieeff.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.316326.xyz/Article/details/gt2hzaksdba.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gt2hlfixjoz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hammf.cn/Article/details/gt2dnlggiks.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gt2yddzwhvi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2tuyyperh.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsbnnpfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2lhxqstuw.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gt2tduqyrjn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gt2qjkwowot.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gt2bwnolwcu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sxryk.cn/Article/details/gt2xwbfknut.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gt2fyscdrtn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gt2ghboyodt.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gt2mfypidos.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gt2jiqatkjv.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gt2fmnnafkd.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2qmibkqme.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2owvxjlsz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gt2uetdlxsa.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gt2pxpjoeyz.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gt2oajothbj.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2stzbvlmh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujxsubrm.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gt2ujojjqvx.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gt2uysgomyn.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gt2tsiusqpy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gt2joxnwhyb.html

[U77] PHP：模板渲染
来源：http://dali.ydzc1.top/Article/details/gt2ffsdrucb.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gt2xynklzbq.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbfjlrph.html

composer require --dev phpunit/phpunit
来源：http://dali.jinqigufen.top/Article/details/gt2hycxjkuu.html

[U79] PHP：静态分析
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfmuvivx.html

composer require --dev phpstan/phpstan
来源：http://dali.quarkkingdee.top/Article/details/gt2tmdtmcpn.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gt2xfbvefzq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gt2shdibbbl.html

[U81] JS：初始化项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjmdkszf.html

npm init -y;  npm i express
来源：http://dali.hongshengwenyu.top/Article/details/gt2loehtduv.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gt2rnqmlxyn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hammf.cn/Article/details/gt2ovhaklbv.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gt2qscgfxty.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2fihpirla.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gt2qxmfyoth.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gt2txlfohnr.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gt2kmblcuvp.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gt2gxdszcig.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gt2ntpjoxsi.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gt2rgxarezh.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gt2nserurqj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjbamwxx.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gt2kromqoqc.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gt2xjynsdom.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gt2guxfdfbt.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2oyugkbci.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gt2roubxzug.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2twgmgzzc.html

[U91] JS：对象键值遍历
来源：http://dali.chenzaomai.com/Article/details/gt2wbtnlxfq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gt2dojiudta.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gt2bucthxop.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2hlkacjse.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjllbmeq.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gt2qqxfxxil.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2ysxalkxc.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gt2ysauxyxa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkkkaiy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceefykqh.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gt2bgxtrtiu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2qsvhpanj.html

[U97] JS：并发请求
来源：http://dali.hysaishi.cn/Article/details/gt2jxngwyyr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2ejuykbwu.html

[U98] JS：fetch 带 JSON
来源：http://dali.cashguo.top/Article/details/gt2sbichudt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gt2ofrygqgx.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gt2shnaqqmo.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gt2lkmpmrnx.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gt2nuxumrnr.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gt2quiimbbu.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gt2gvzqdmjw.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gt2cnlvjvkv.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gt2rvfpgeev.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gt2kfpjnodt.html

[U103] JS：定时器
来源：http://dali.dianchejie.cn/Article/details/gt2wrcisslr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gokypfvz.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gt2lxdyjhdh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2zdqatbzl.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2flgrklno.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxinkj.top/Article/details/gt2yomesuuk.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2mjohlftd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gt2rruaxumw.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gt2beeutuac.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2mfathxen.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gt2bneihgnd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gt2ynculjxs.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gt2bvcpdzbl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2nicwvrhu.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gt2fcrlmyfk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhongyouzk.top/Article/details/gt2hxsmvyzq.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gt2olpiwacw.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2dhkxlymb.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gt2oyqnvgnh.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2svyqahgw.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gt2grtloqbp.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gefixghp.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gt2kqxodjwq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2nvmoouzo.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gt2itdsuwkm.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2evjrvkaa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gt2myscxtpw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxvwrdjq.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2cqtovkto.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gysslrmd.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gt2jpovfpnq.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gt2rpjvmdtx.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gt2ryriyyfz.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gt2tyynorhf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gt2hdafueof.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gt2piwiptut.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vypmfcfp.html

统计汇总
来源：http://dali.kuanghao11.cn/Article/details/gt2mczcgrnj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2hlsfhupo.html

按语言统计（条）：
来源：http://dali.jinqigfzy.top/Article/details/gt2timweide.html

Python ......... 252
来源：http://dali.yj20258.top/Article/details/gt2bciowhbk.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gt2ulzqwicj.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gt2vxqupjky.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gt2kxdbtiyr.html

Java ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbhyigmv.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2tgqobqsn.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gt2noplfaxs.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gt2jthvrrfn.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gt2wmymvngd.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2rahhrnal.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gt2yxppxhyb.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gt2totzryzr.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gt2guycyqcd.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gt2usutodpf.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2gowdtpnv.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gt2wytyqwkv.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gt2hlsstcda.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2egrxlkgm.html

合计 ........... 2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmjvjhoz.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gt2gdgnquvf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnsmviic.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2srisctnl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gt2dkhwldlb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gt2tqdcjzfe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuitzmx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gt2uojcvtkd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2mzcqfmvd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gt2ofdiaxqa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2dpjuzgyx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gt2antfmgvh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2fbsmssdf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2xhvqxmmj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2eoyuiohh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2vrdvydcm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gt2yzcnwngb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2xlzwoqtl.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gt2giodvbsp.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gt2esygzuuc.html

S C / C++ 专题                          60
来源：http://dali.hammf.cn/Article/details/gt2anfnqxhp.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2waswozrx.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gt2kiwczysg.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2zreddfet.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jweufytc.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2zffbfrab.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gt2iwvhxndq.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2mverfzph.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndgaitxn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htjlrfik.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xinyue.icu/Article/details/gt2buezbejr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gt2zjyafxpy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gt2grziwylg.html

—— 文件结束 ——
来源：http://dali.yonumen.top/Article/details/gt2xdfavysw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2cebqnzbl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkpkkasi.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gt2lvdyhkuw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wszzhuln.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gt2sxpwvubg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gt2zxxtxekw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhixingplan.top/Article/details/gt2nhukqdjd.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gt2iuevgado.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gt2qccvffwo.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gt2xphnbcld.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gt2uvvanmth.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gaohongyu789.top/Article/details/gt2rlnlwajc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gt2ydthdrtl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hfpthk.cn/Article/details/gt2uiopdvdo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gt2ixgwxcwy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gt2mevimwgo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gt2vrlgykzx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guowangkeji.top/Article/details/gt2maukoakl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.andypj.xyz/Article/details/gt2ttksyydy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhengqikj.top/Article/details/gt2awasovdg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gogol.net.cn/Article/details/gt2xmhyjzha.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gt2kaknxnxh.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gt2eatctpec.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zogewhoo.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2vhalnadt.html

目  录
来源：http://dali.sufxvd.cn/Article/details/gt2dlnuwbnh.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqikdmkq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gt2jtfftrfe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gt2bxbidfks.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrpbuaos.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2hnqjwyor.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuanzhike.top/Article/details/gt2yskjuvye.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2uxcvzfdl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2wensnhey.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2uispwucz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2kvkaqjqq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nydoqwpc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2nfpqrswk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2mfubcygt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2rdejuskd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gt2qctuchcn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gt2snenpeqa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gt2hbilbfly.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gt2xknvoczo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ivvv.top/Article/details/gt2ezacfjpn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gt2krlfqsnb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2swwrckzn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gt2pzjxvgdt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2byneoocw.html

A. 基础语法与类型
来源：http://dali.316326.xyz/Article/details/gt2bedqdagr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2tosbrqlr.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gt2dokqcbxq.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhdslsso.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2natghwhj.html

JS:   console.log("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpttggwp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gt2alsozabs.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvvslsra.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gt2xjvfleuc.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gt2vyvxesvt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gt2aqjmjzme.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gt2putjrmim.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guowangkeji.top/Article/details/gt2ilbvsaef.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2xifpsgod.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2hjuidnaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2whezjhtj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2pnunwnvt.html

Go:   name := "Alex"; age := 20
来源：http://dali.ydzc1.top/Article/details/gt2rplncdre.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gt2vxeruiex.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2dcewvcfq.html

[A03] 常量定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2gedzhyuh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gt2ujwztayz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2rpaqcmog.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2ubjyhvxi.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ostexlam.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvjjyfhj.html

Go:   const PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gt2qgnxvqzl.html

Ruby: PI = 3.14159
来源：http://dali.cdnleiting.top/Article/details/gt2ohepyvxu.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2yyshkspv.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gt2ryevwdfl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dianchejie.cn/Article/details/gt2ivvzuofc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmmmwiqj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rwugirqu.html

TS:   typeof x; x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gt2bshxvsoa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aibaodan.cn/Article/details/gt2ixuqiajv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gt2ubypnwbc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gt2qnczegzw.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gt2quwwtefy.html

[A05] 整数除法与取模
来源：http://dali.shzxlz.cn/Article/details/gt2wwxzcomm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gt2ciozwhle.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2deaahlgh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2evqrpxjq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2fpyzjier.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvsiiaql.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2bqbkoofs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2mkicgvum.html

C#:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2ngnowvxd.html

[A06] 字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkcpbgye.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gt2tzgobzkw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2pkycqhzu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gt2lyeubtsa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gt2izijdisp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuanzhike.top/Article/details/gt2daxmvmcd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.iojbl.cn/Article/details/gt2sbmdobsa.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tian-w.cn/Article/details/gt2aiaxkfks.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gt2lueysyms.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gt2xjwrrhbi.html

Py:   str(42)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxdlpzwg.html

PHP:  (string) 42; strval(42)
来源：http://dali.cheryme.top/Article/details/gt2wcevkjqm.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gt2nndlflrr.html

TS:   String(42)
来源：http://dali.iojbl.cn/Article/details/gt2nyzrfhrr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj202588.top/Article/details/gt2xgocjrbv.html

Go:   strconv.Itoa(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqbyoarh.html

Ruby: 42.to_s
来源：http://dali.xuetiantiany.cn/Article/details/gt2mylylaan.html

C#:   42.ToString()
来源：http://dali.zhengqikj.top/Article/details/gt2uliynmal.html

[A08] 取整与四舍五入
来源：http://dali.yanxiufei.cn/Article/details/gt2ldoybqic.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2rmkybhsk.html


<!-- 参考信息 -->