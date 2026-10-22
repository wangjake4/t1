代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqxbnwxo.html

$v = $a ?? $b ?? "default";
来源：http://dali.cqqwz.cn/Article/details/gt2zqnfiexq.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gt2ovjwloow.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gt2xiarhghj.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2rotalfyo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.smart0.xyz/Article/details/gt2badiucmq.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gt2natzcdhx.html

f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2evghrwuk.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2wshbxmyz.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2xrnpbxar.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gt2ttwkttxe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gt2ilkdtcma.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gt2btunnoeu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2viubpnze.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gt2serwyufw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gt2bjyerahw.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gt2hvbxtzuk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2zswfnprr.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gt2jgxvhgtu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqpmbirc.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gt2hooaopre.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gt2cpalphji.html

[U64] PHP：目录遍历
来源：http://dali.tanke756.top/Article/details/gt2zusgtdqr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gt2baegmrmz.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gt2zwhecjla.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2woifwsai.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gt2ptgyzuvn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hfpthk.cn/Article/details/gt2gzuknhdf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uadxmkvl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.svipenyu.cn/Article/details/gt2maquiuic.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gt2mvkpcjlk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yanxiufei.cn/Article/details/gt2eaguacup.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gt2heyctxyk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gt2huithvrd.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gt2smshqoep.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gt2uoadnskj.html

[U71] PHP：抛出异常
来源：http://dali.haohaochexian.top/Article/details/gt2zvrmbmhc.html

throw new RuntimeException("失败", 500);
来源：http://dali.xinyue.icu/Article/details/gt2pqjovlwj.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gt2hvtjjely.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gt2sjeichtk.html

[U73] PHP：读取 ini 配置
来源：http://dali.hammf.cn/Article/details/gt2pwzhbgxd.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gt2axzkevmp.html

[U74] PHP：读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2mxmflotc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vemldvau.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gt2inwttkqa.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gt2oekvstoc.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gt2tarovtso.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gt2juviwojp.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2dhypuwtr.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gt2hzrjmerh.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gt2nqdnstsi.html

composer require --dev phpunit/phpunit
来源：http://dali.jlsjyb.cn/Article/details/gt2emxzgyqt.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gt2otqofbrg.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gt2moagrycv.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gt2gjafdasi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gt2lizsuzgr.html

[U81] JS：初始化项目
来源：http://dali.zdqjudy.top/Article/details/gt2gevtcgnm.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adzqkyat.html

[U82] JS：package.json 脚本
来源：http://dali.jqgfzy.top/Article/details/gt2kpkogddu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gt2mxxyjdlc.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gt2aoizihgm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gt2busgkjye.html

[U84] JS：CommonJS 写法
来源：http://dali.ybcxt.top/Article/details/gt2jwafaaus.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.vqdsnc.cn/Article/details/gt2hlhcpyic.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gt2kdgrxqhr.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gt2fuzxruue.html

[U86] JS：空值合并
来源：http://dali.yueranfly.top/Article/details/gt2zsrhbtyd.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gt2ygosvodd.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gt2giyleuxp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cashguo.top/Article/details/gt2olwvvefy.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gt2oevogqxb.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gt2lglneynf.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gt2mqteijtl.html

[...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2jfhzjpmd.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gt2egywbcma.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2cmgvhmju.html

[U91] JS：对象键值遍历
来源：http://dali.chenzaomai.com/Article/details/gt2uwliufoa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gt2nzktwmig.html

[U92] JS：深拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2lcpcjpli.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpcjikzo.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gt2ucqbqrwv.html

`共 ${n} 条`
来源：http://dali.316326.xyz/Article/details/gt2uqenkviw.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2alzeziir.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gt2vngqpbyd.html

[U95] JS：Promise 包装
来源：http://dali.xuanzx.com/Article/details/gt2zezelxxv.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gt2paobiynp.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gt2mzkqbzty.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2szkavtch.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gt2vzusvbfv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zblqrgvk.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuanzx.com/Article/details/gt2rsthyzra.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuxming.cn/Article/details/gt2grypawcq.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gt2qytovvzf.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2hagxuvgf.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gt2xcsttlza.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2gbumwyxc.html

[U101] JS：classList 操作
来源：http://dali.hfpthk.cn/Article/details/gt2nxembyki.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gt2elkkgetd.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gt2qkhicgjc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gt2tqoehpiw.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gt2wbvxzpek.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gt2pguplyzb.html

[U104] JS：防抖
来源：http://dali.wangdashe.top/Article/details/gt2vsjkgobl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2xclnpbax.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaqkrvqz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxinkj.top/Article/details/gt2yrnkorbj.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2guhuuzho.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gt2fonghupq.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbuksifg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2tbhlxkdy.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gt2vvvohkll.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gt2zwiproer.html

[U109] JS：数组分组
来源：http://dali.zhoulong.xyz/Article/details/gt2jerjdbgp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2wfercrro.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gt2ivxxsrze.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gt2tewvjrto.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gt2usbtydbt.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gt2sjtoiyem.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gt2mzalnbve.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2dwznrsxr.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gt2tzhcvebq.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nruahpog.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gt2gfpiomcf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2qvajguiq.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2kwmntymm.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2vfgexlys.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gt2tsxqttnc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gt2ecnysihr.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gt2ccrjgcyj.html

npm i -D vitest;  npx vitest
来源：http://dali.sxryk.cn/Article/details/gt2ccobkaii.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gt2dclocgld.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gt2eiqfqndx.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gt2zgqrmfkp.html

npx vite build
来源：http://dali.yanxiufei.cn/Article/details/gt2cxfohxgs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aazibrjq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhoulong.xyz/Article/details/gt2yzlmzqen.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mzxcfejj.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gt2twsmaefk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2yaniguzi.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gt2agtdhhzd.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2fbvkflbj.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gt2gswcajhd.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gt2wqrywxss.html

TypeScript ..... 212
来源：http://dali.sufxvd.cn/Article/details/gt2fjcotddm.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gt2hqutidfc.html

Go ............. 212
来源：http://dali.sweek.top/Article/details/gt2vnqeukiw.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2geyhbvft.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2tnhrbqwk.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otedhncs.html

C++ ............ 30
来源：http://dali.shuidangran.top/Article/details/gt2wgjjdwvt.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gt2yfegxdog.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gt2xfvgdyze.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gt2lofolrin.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wiwpxsct.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gt2bapaeysv.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gt2covakwms.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gt2tplvefbm.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2loyrmtwo.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gt2czcxbjxt.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gt2jkczglvt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gt2lhtllxvt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2lcssfikp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gt2hkgxejit.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2gnzfboto.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gt2oyemeehs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gt2pgdhauio.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gt2uyixzfbz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gt2xglqfdek.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyydivbl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gt2ratvbqay.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2faodsyvh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2gmexkofm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrieozrv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gt2eprxlvfj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujxipjas.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2tpajbnvn.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2baloqyfc.html

R Bash 专题                             80
来源：http://dali.xziqi.cn/Article/details/gt2utgyttxn.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gt2ctivjywi.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gt2hrmlmeuk.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gt2reewrlxk.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2gcvmwvmq.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gt2jlbjvbos.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2razgidxm.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gt2jhkcbgvc.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2utggryjv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gt2cqzcukwh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.316326.xyz/Article/details/gt2mwccthjd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gt2vtvgjujl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gt2llgcczsw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gt2ajftczjl.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gt2qsnhquta.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jihzvuut.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xinyue.icu/Article/details/gt2islcusqh.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2utekjlxs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2psdxpmsf.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gt2fgegjzfo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gt2snmebxun.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gt2qcekgrmu.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gt2gcqypjbe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gt2akkmzefp.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gt2fkfthsfs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gt2ntgmhvjs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gt2rybyefak.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuxming.cn/Article/details/gt2yrfrrrrd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gt2jsaygkzp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gt2qndgekpi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gt2crdtitvu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuxming.cn/Article/details/gt2rkjvxgcl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2xejcdzje.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vepztkhs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfhdrkjt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gt2kexlmogf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcgapank.html

【文件统计】
来源：http://dali.zhixingplan.top/Article/details/gt2uvzggtuz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shnunjre.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2dheelsia.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyrjzjik.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2awkduwcd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gt2wyuhyotx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2oxlprsjy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gt2gspxywhz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2ofdrahhp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gt2dcdrdsxc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gt2addsgdhd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gt2vekglbri.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2wiuezpbs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2ciactpfi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2kqelfggx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2cnnoluuf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2yavdkjbd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2seiyikcn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2dgkpgiqg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gt2qjkcxunf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlvsescu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2djgyhigi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.9152youxi.cn/Article/details/gt2xxfxilrv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gt2bdlsbzby.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gt2xebaenxs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqijqvyr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pjgsqczz.html

A. 基础语法与类型
来源：http://dali.gaohongyu789.top/Article/details/gt2yojrpmgz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ptuparmn.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2kjqiptpl.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2lpykqvgw.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigfzy.top/Article/details/gt2hvdlbhab.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bezbufyl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gt2ciuhepwm.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2ejuctjrb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gt2xcfsknbw.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gt2kcwqqjcz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2ogtglstg.html

[A02] 变量声明与赋值
来源：http://dali.bjfxy.top/Article/details/gt2avkzzedk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.meibo888.top/Article/details/gt2qrgqtool.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2zpuotcrb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2lyjilyif.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gt2artlkbrm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2jpgvjrkk.html

Go:   name := "Alex"; age := 20
来源：http://dali.svipenyu.cn/Article/details/gt2tasuzdoj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gt2vzgpqrzz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2jsocenig.html

[A03] 常量定义
来源：http://dali.snrcjt.cn/Article/details/gt2glmufkbl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dashuyun.cn/Article/details/gt2crspjdrm.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2vnonslwd.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjztooeg.html

TS:   const PI: number = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgmkowka.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2sxlrpmxy.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gt2ftktkwsk.html

Ruby: PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gt2qzddjosl.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2ahzpopgh.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2yfwftdox.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gt2ppnbqdum.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odwzuksh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gt2wymzizae.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gt2ympqjfac.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fengsongda.top/Article/details/gt2nslwtztv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj202588.top/Article/details/gt2hatmppac.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gt2yqrearuk.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gt2pcoiyhtd.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gt2xbomdagd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jiagoushi.top/Article/details/gt2ljxugmxy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2qmhsnora.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2prffoktr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqntllry.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2douwhhxu.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2kzmaaidl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2zqvrbxvr.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2bpcjgowu.html

[A06] 字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjnqmpix.html

Py:   int("42"); float("3.14")
来源：http://dali.hfpthk.cn/Article/details/gt2aqpwxcni.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.havefunace.top/Article/details/gt2ydqaerak.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gt2rkleshca.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gt2vmvbfnjx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gt2cvwuocon.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ivvv.top/Article/details/gt2ngmwhjtk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gt2cvrdfrev.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gt2gngrmjcb.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2nuuzoeoi.html

Py:   str(42)
来源：http://dali.cheryme.top/Article/details/gt2jeljetbu.html

PHP:  (string) 42; strval(42)
来源：http://dali.havefunace.top/Article/details/gt2nvfkcgxk.html


<!-- 参考信息 -->