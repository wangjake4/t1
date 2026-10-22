代发 wailian999

[U51] PHP：数组解构
来源：http://dali.jlsjyb.cn/Article/details/gt2epanirqz.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gt2smjwirge.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flqczsov.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gt2mejngagc.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gt2givpojnl.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gt2vgpmtyqe.html

[U54] PHP：空安全调用
来源：http://dali.cucudq.cn/Article/details/gt2nyriavup.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gt2zcdzljth.html

[U55] PHP：match 表达式
来源：http://dali.fengsongda.top/Article/details/gt2slkroria.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gt2iwmdebjg.html

[U56] PHP：命名参数
来源：http://dali.dashuyun.cn/Article/details/gt2jdlcifch.html

f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2opfgfiey.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2bpjiiqbb.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gt2qvnhfzkf.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gt2wujgxwax.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gt2ppgeowug.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gt2bfbgwllu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2muhwyubd.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gt2zdfictfx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cucudq.cn/Article/details/gt2lxmxjcgh.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gt2crviufpb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2bqfsmkrk.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gt2gbegfayw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxuanxn.top/Article/details/gt2dbzauxub.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxmwfyio.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgufenzy.top/Article/details/gt2vryaljko.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gt2hxtxjvtt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjqcgzvi.html

[U65] PHP：会话
来源：http://dali.haohaochexian.top/Article/details/gt2tvxfduva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2fmwtylbu.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gt2bmnumsoi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gt2fgupbksj.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gt2qoqqprzc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dggguwzo.html

[U68] PHP：PDO 连接
来源：http://dali.jqgfzy.top/Article/details/gt2bdmpvred.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xinyue.icu/Article/details/gt2ufhfxvvv.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gt2ppbpzcbq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zycfv.cn/Article/details/gt2eojwmlid.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gt2naemspks.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gt2laotybhu.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2xasblypi.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2dqtbxngd.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gt2lkilcnrz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhongyouzk.top/Article/details/gt2euwzghwy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfjssanp.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gt2llbfpfle.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2gzznegjw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gt2simiekfi.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gt2mjevgbbf.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gt2jtsgefmx.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gt2ylcpcefq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gt2vpltqkzk.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gt2zvfmunnw.html

composer require twig/twig
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbhwcwvr.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gt2slkoqatr.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gt2voqnsvym.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gt2vrcqfdfk.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfmoamkn.html

[U80] PHP：代码规范修复
来源：http://dali.gogol.net.cn/Article/details/gt2zygwszyq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gt2ooopeesu.html

[U81] JS：初始化项目
来源：http://dali.bjfxy.top/Article/details/gt2qrkgsobx.html

npm init -y;  npm i express
来源：http://dali.cheryme.top/Article/details/gt2aqwxhxqk.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsrfukhn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihdlkrp.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gt2kluftcac.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2vsyjrlwu.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gt2bzreltow.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gt2qpacteto.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gt2yaovhfrm.html

a?.b?.c
来源：http://dali.jinqigfzy.top/Article/details/gt2mkaphknu.html

[U86] JS：空值合并
来源：http://dali.cucudq.cn/Article/details/gt2ondsxogc.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gt2tprkwkmd.html

[U87] JS：解构默认值
来源：http://dali.yangfankeji.com/Article/details/gt2rgzovyxy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yvedp.cn/Article/details/gt2qwaxvuur.html

[U88] JS：对象展开合并
来源：http://dali.guannengcc.top/Article/details/gt2uxmzbrmg.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gt2tpuzpysg.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gt2hbcwiufr.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2bdgqpulr.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gt2zqgzvzth.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2txqbzwkq.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxjitrmv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhoulong.xyz/Article/details/gt2rpobmcun.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gt2cbitmegw.html

structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bffizowt.html

[U93] JS：模板字符串
来源：http://dali.c1oappe.top/Article/details/gt2flaagfqx.html

`共 ${n} 条`
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmpkgync.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsoviuxt.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gt2frvvaecg.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gt2mosekkvj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2nqgsplql.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gt2lipttrfg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2huhcgkry.html

[U97] JS：并发请求
来源：http://dali.pycfn.com/Article/details/gt2ixwzorqh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2ryipnvnt.html

[U98] JS：fetch 带 JSON
来源：http://dali.sysykeji.top/Article/details/gt2topizdzx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gt2uyjbpagc.html

[U99] JS：事件监听
来源：http://dali.jiagoushi.top/Article/details/gt2nyedrnbj.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gt2xuvhgfuf.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gt2mnvagasb.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gt2rdmnkccr.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gt2muvdtklt.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gt2ffqpnfrf.html

[U102] JS：本地存储
来源：http://dali.yuxming.cn/Article/details/gt2hmwpmbkn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gt2jpwqzpdu.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gt2cqfyxcto.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gt2shjqtspp.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gt2qwosdffd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghrohamp.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gt2tpuauyas.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gt2ndfwkwof.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2ndzzovnj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gt2ochfxeeu.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2rflwpcdx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxvefkyw.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2etujccpy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gt2hllrqfqr.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gt2npxgxfng.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gt2vprvwara.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gt2cjgijiqr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gt2gqygwduq.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gt2cgrpnhxj.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzumkbwa.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gt2rtvyytyx.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2zuxqydoh.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gt2gxqptfgk.html

s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2tjhrfwpf.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2gqcwkbsd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2ehikfcpa.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2kbiaflak.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2mlbkhkqv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxuanxn.top/Article/details/gt2smyqcuhq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qemcdutt.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gt2nokebery.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgufenzy.top/Article/details/gt2ouenfzyo.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xszxutny.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gt2zulsnezy.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gt2aypkfzaq.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gt2iarrwwpb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gt2njzpebmh.html

import.meta.env.VITE_API_URL
来源：http://dali.c1oappe.top/Article/details/gt2pbmgqsew.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2itsbmrlo.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gt2ghcovonm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2iludrczl.html

按语言统计（条）：
来源：http://dali.yongpay.top/Article/details/gt2xqhgprxq.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gt2nzqaexud.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gt2pqqpalvw.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gt2hlusqrqr.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2djazdqco.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2xtdyoqdc.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujvbisda.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2quqczyxj.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gt2dkzwxyhp.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gt2vboqcona.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gt2wmtynkbu.html

SQL ............ 90
来源：http://dali.xziqi.cn/Article/details/gt2cdfbdljt.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whjvxzti.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gt2sdxqlfoi.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gt2cibyxaxf.html

Lua ............ 10
来源：http://dali.cucudq.cn/Article/details/gt2iegzmffz.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gt2asqmzpfv.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gt2mqmrfalj.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2wbfkqoef.html

合计 ........... 2106 条
来源：http://dali.nwbrower.top/Article/details/gt2iqgpnbps.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gt2binkwtpt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gt2unntmoga.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2qaijlsqp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2pkpflnim.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2oeshxekx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gt2clftaxqo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkudveyr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpulxuwn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2gqegwjrx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2xwesvkjn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2xvwmmedj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2ikpneftp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2okivaquc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2euwndybq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdnushwu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gt2tnjmqlkj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2imfvvrwl.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gt2laqgscym.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuysxfna.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gt2csfutzrs.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gt2qbbormdq.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gt2aqhnwcjx.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2wqtecsod.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzzmwuav.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2lgasinpo.html

使用提醒
来源：http://dali.xylfe.cn/Article/details/gt2ngomtawa.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2hpspvvmj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gotoacloud.top/Article/details/gt2rtxprfeg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangdashe.top/Article/details/gt2fadaiqrs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gt2evkrtlhe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gt2bjtvaxux.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gt2ddrvbdlq.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gt2rixmkgqs.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2spxdpdlp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gt2wtaekums.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gt2nfowovkb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mqisvbpb.html

【收录内容】
来源：http://dali.zycfv.cn/Article/details/gt2htsyxnkb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhoulong.xyz/Article/details/gt2ytxdbbnl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrogdigd.html

SQL · Bash · C · C++
来源：http://dali.sxryk.cn/Article/details/gt2rjnxtnpn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gt2lmkbgjlv.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gt2utkstzsa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.andypj.xyz/Article/details/gt2moslvtvj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tanke756.top/Article/details/gt2heidcddw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gotoacloud.top/Article/details/gt2oiflzaxx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gt2hdhqjpri.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gt2qsiyltml.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pycfn.com/Article/details/gt2xyqjyato.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkelyire.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jyoumei.cn/Article/details/gt2dqmnoqii.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gt2xmqhlpfp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gotoacloud.top/Article/details/gt2xazctctf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigufen.top/Article/details/gt2yesuweec.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gt2uqgegpus.html

【文件统计】
来源：http://dali.316326.xyz/Article/details/gt2onhssief.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gt2zsyzjqbt.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2mespzjcs.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gt2dtbyaddg.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2bumyqegd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2rcbipszy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2utjmjljf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gt2pwodibio.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gt2ifbzrfax.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gt2hqakszek.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxlgsopn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvnvpijf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ehqsofms.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdefkkcq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gt2fopmskxd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uydbagfi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2eiaekbdy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tudqsxdj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gt2kvlkvffu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gt2xelysgwk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2mgzhptus.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmqslmgu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gt2gubympay.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgnpovvo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvmsrvqm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gt2jdorafhd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ehysgwkz.html

A. 基础语法与类型
来源：http://dali.wangdashe.top/Article/details/gt2bhsoanyu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xlydgsna.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2zvtrisen.html

Py:   print("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gt2bjymiuty.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gt2bfphqgoi.html

JS:   console.log("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gt2bbkpcvxy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2fgubhrrk.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvnqlrga.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gt2txtgxzbq.html

Ruby: puts "Hello, World!"
来源：http://dali.jyoumei.cn/Article/details/gt2iqtwrfno.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gt2luxbcbpd.html

[A02] 变量声明与赋值
来源：http://dali.xziqi.cn/Article/details/gt2yzyhnvua.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhoulong.xyz/Article/details/gt2hramliyn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2jbrpqptt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfggcasq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2yziiymfr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2mqqqmxfs.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gt2uljxcvva.html

Ruby: name = "Alex"; age = 20
来源：http://dali.birdmap.top/Article/details/gt2bahzvqmb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2nzrsyzhg.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2xswtllll.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gt2wnpvzmgu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgurrmwk.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2wdqdqyyt.html

TS:   const PI: number = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2ekiknsjv.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2lpeloymy.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2rttbbvhz.html

Ruby: PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gt2srrnwvee.html

C#:   const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2vcmqxgao.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2umjljsfu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gt2lqkupdzl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sweek.top/Article/details/gt2ydqxzeak.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2zygnzqxx.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gt2pxbuwqmq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yueranfly.top/Article/details/gt2siwduztk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gt2uxirwsnm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ituwspzq.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gt2yywcjore.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulwonami.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sysykeji.top/Article/details/gt2ctgkbhqy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2pzdrszce.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmhopgil.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2tceozwmc.html

Java: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2ollhlnnn.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2gllbapzj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2hnzifllm.html

C#:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2nyditlbt.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eykvizvx.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gt2dbbenokz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gt2uwdeubjz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tanke756.top/Article/details/gt2tlrsktav.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gt2jgsfqwnj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gt2hbpbeprd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigfzy.top/Article/details/gt2zvfoqnjv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gt2jhrpqire.html


<!-- 参考信息 -->