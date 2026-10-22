代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gt2yhkuxgjl.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gt2jbbuxlhz.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gt2kjdcivwu.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gt2ipnnohox.html

[U55] PHP：match 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2hfkrzclu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2wmldxrzo.html

[U56] PHP：命名参数
来源：http://dali.sufxvd.cn/Article/details/gt2ueqqkltk.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2mznhqnqp.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2pvusjhtx.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gt2gwbjvhbf.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gt2zgxtodbv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2iyuphmvo.html

[U59] PHP：自定义排序
来源：http://dali.vqdsnc.cn/Article/details/gt2pzqbxmsf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gt2cimgaecj.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcmgaias.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.iojbl.cn/Article/details/gt2qrvjgolv.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gt2jrfcwxtz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2wkztpyxc.html

[U62] PHP：日期对象
来源：http://dali.haohaochexian.top/Article/details/gt2oaoqqmdy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangdashe.top/Article/details/gt2lrgecpkc.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gt2anadmcal.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gt2liihlzod.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2nbeuvyxk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gt2vhdokbeg.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gt2lmxbdsjn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2ocqpzivm.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gt2ealgiawz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gt2tmnvrrim.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gt2ehcrqlmn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gt2npchhkdr.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gt2lohypmip.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gt2khjemegz.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258888.top/Article/details/gt2kfnqnpsn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.haohaochexian.top/Article/details/gt2tdowayrh.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gt2ioytqbfz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pengpengdd.cyou/Article/details/gt2bczdgktz.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2tfhtshbe.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2ikcpxasa.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gt2jgoezwbs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gt2smqlgfxz.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gt2lveendht.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gt2odkyebzn.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2sefvhrnm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gt2xlzkdkpo.html

[U75] PHP：依赖注入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poktqalt.html

composer require psr/container
来源：http://dali.daria6918.cn/Article/details/gt2twxweojd.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gt2ohqurjar.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gt2wmwdneox.html

[U77] PHP：模板渲染
来源：http://dali.xuanzx.com/Article/details/gt2darhbbpb.html

composer require twig/twig
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsdiqzav.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gt2nputexnj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gt2kpnauzow.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gt2qaupbvep.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gt2udvuwlmj.html

[U80] PHP：代码规范修复
来源：http://dali.sysykeji.top/Article/details/gt2quiyewge.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gt2vdchqomm.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gt2nsiulmtt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzpputw.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gt2dmgrojyv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gt2jqriqxug.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gt2ebuqcyaq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2qgphktyq.html

[U84] JS：CommonJS 写法
来源：http://dali.tian-w.cn/Article/details/gt2trxobfbi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gt2fsjczmel.html

[U85] JS：可选链
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssmuzrym.html

a?.b?.c
来源：http://dali.hnxiangtu.top/Article/details/gt2akprrxtt.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gt2achgjabs.html

a ?? b
来源：http://dali.smart0.xyz/Article/details/gt2gqpvwjqt.html

[U87] JS：解构默认值
来源：http://dali.meibo888.top/Article/details/gt2bnewwoef.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yongpay.top/Article/details/gt2rhmbzcry.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gt2yfabzygd.html

{ ...a, ...b }
来源：http://dali.c1oappe.top/Article/details/gt2rkkeakhj.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gt2prvmrlfd.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2ykwbemcf.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gt2dfssbhcb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2vibwqmuu.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gt2jjqatdhw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangshuangyany.cn/Article/details/gt2snarptwa.html

[U92] JS：深拷贝
来源：http://dali.bjfxy.top/Article/details/gt2stwwpamm.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2ivwzcyxt.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gt2zxnofeyj.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gt2kdevvrlu.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gt2ayrekqgh.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gt2bhkauzmn.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzeelsgg.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gt2vlcnfcze.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gt2uddyminh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2pvkgowjr.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2besdyafl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoeocjts.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuanzx.com/Article/details/gt2maqomumw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shzxlz.cn/Article/details/gt2ujrvxstx.html

[U99] JS：事件监听
来源：http://dali.redwolf501.top/Article/details/gt2wgtpdugv.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gt2skfqkcmn.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gt2fmigsbif.html

document.querySelector(".item")
来源：http://dali.iojbl.cn/Article/details/gt2iyonzvgj.html

[U101] JS：classList 操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpkqryyd.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gt2dhgcapbl.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gt2vtcuifcu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gt2zfrulvjc.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gt2fdhegoxk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gt2nugdgyxn.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gt2tqqwnxss.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2nfvoxszp.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gt2bipoolrp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sweek.top/Article/details/gt2wsnybbsb.html

[U106] JS：日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2vrjbcvkk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xinyue.icu/Article/details/gt2jpmgtniq.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2rhpeftom.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2auytxhir.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gt2gpkhgzze.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gt2drbqzcdm.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsdbkpnv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyyymhf.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gt2iwndqyoi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gt2emwkqzku.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2nqippnyd.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2cszcahvi.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gt2ljaslura.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2jpxzvqwt.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gt2rzgfsvff.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2ozdtigid.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gt2mejouucg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2tlershtt.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2nrwfumvh.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2tspqfquz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gt2jaefdvok.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gt2gmkglgri.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gt2yqcpoold.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gt2irdjavkq.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gt2tffnuqmc.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmsluaxs.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gt2wctzvznq.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gt2tzxygiar.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gt2aekolkig.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2jimrvwwk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2pyuacfog.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gt2paldsopn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wtlrlqyt.html

按语言统计（条）：
来源：http://dali.birdmap.top/Article/details/gt2puzkvfdm.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gt2ytpbwkcj.html

PHP ............ 252
来源：http://dali.zhengqikj.top/Article/details/gt2fnvgpaid.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gt2fnualpuq.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsxwcnxu.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2zlzejgsw.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gt2nkxfaxyo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgdzkhr.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gt2kmjgkuvd.html

C .............. 30
来源：http://dali.xuanzx.com/Article/details/gt2zybmqazx.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gt2noxsxbbt.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gt2bjdaazvp.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gt2sjxhldhs.html

Kotlin ......... 15
来源：http://dali.gotoacloud.top/Article/details/gt2avtfzcpq.html

Swift .......... 15
来源：http://dali.316326.xyz/Article/details/gt2btbhmyhm.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gt2imedabvq.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gt2qbfgxbxf.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gt2avhjzovv.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2hvawwugr.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2yjnanjfb.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evguasnl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2rbrteaim.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2ialwhese.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kimpsclc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gt2panpxelf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqevseei.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2zxusyton.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2lndllvpn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msuftdwe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2rnevtgqq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2timsvmkn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2axiwtluk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2fctetibv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2ibigixnk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gt2mgiyfpcx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gt2kaiqgjdp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2uldmsnqq.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwjsyzlr.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gt2sgdfaffi.html

S C / C++ 专题                          60
来源：http://dali.jqgfzy.top/Article/details/gt2kexxfnji.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gt2yxapjylc.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gt2jmftwahc.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2oiarwdns.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gt2amaomhxf.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gt2oauyxfnx.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbyodswv.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2ghzwqjfh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gt2jgjuqyxc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gt2smanyqcc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pycfn.com/Article/details/gt2ljaevzhp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gt2mhwktldl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gt2lmlhbnib.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opxjlwto.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2noqzelfm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gt2qkpvnzws.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2waenfhcl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2uheewcub.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gt2nnwzihae.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fzhhl.top/Article/details/gt2bkdwhbld.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gt2zsoapnhw.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gt2vnhtbycx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gt2qffxpofl.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gt2diyyecbq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aibaodan.cn/Article/details/gt2zhtkjmal.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gt2xfxthses.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gaohongyu789.top/Article/details/gt2hnboggix.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gt2gybyrdge.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gt2eubetddc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.bjfxy.top/Article/details/gt2qoqvceiv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfpjjhqf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.birdmap.top/Article/details/gt2qcdwwhjf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gt2fmeafuzm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.mhx1999.top/Article/details/gt2kxrhyqxq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihqqijll.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gt2kclinxnx.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gt2fidqfkgs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gt2cjyxjhau.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2ntgwyodt.html

目  录
来源：http://dali.316326.xyz/Article/details/gt2vbndzdzc.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2axyfqlno.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gt2vupngrvm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2jvadsahg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gt2vaxjqznn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gt2qnfbmgiv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.meibo888.top/Article/details/gt2ooyzohna.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gt2vwjmishp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gt2zqpplkwb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2hkbyosxq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2lhingmkt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2twaavfrr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2ucifkhtv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwloabvx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2ojsjhipd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gt2fnaviiur.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gt2qkffdxpq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2uljyisvw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gt2eclrtdfx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2uwimkqyz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ivvv.top/Article/details/gt2ldsmnhfz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2yttshtki.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2oamegdbp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2piafxjwx.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gt2jngsgirh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2trlxuksi.html

[A01] Hello World
来源：http://dali.ybcxt.top/Article/details/gt2yigckgxp.html

Py:   print("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gt2nskiwzqn.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2kbeshdat.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2ixjlxbcf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sweek.top/Article/details/gt2ompaqvgb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbylnujt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gt2vlzxbsph.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zurdvjin.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgbjhysj.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnilmlgd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gt2pgiesbok.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2ovrkbneh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2pgmoighr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueuvtded.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2mlcvjqmg.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gt2utrlrxxi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.bjfxy.top/Article/details/gt2nteyqlvx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2eseupvtt.html

[A03] 常量定义
来源：http://dali.aizwys.cn/Article/details/gt2zzobqyic.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgeeadd.html

PHP:  const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2ohwbiivm.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2lzqkqtqj.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2fyfjfwlc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqyrqvs.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2geohlatm.html

Ruby: PI = 3.14159
来源：http://dali.xuanzx.com/Article/details/gt2lqcxsolf.html

C#:   const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2dshahsuw.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gt2hztofywp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krjmtwuq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gt2fotgsixg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gt2rgfjqcrq.html

TS:   typeof x; x instanceof Date
来源：http://dali.sweek.top/Article/details/gt2dfwncovn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gt2ghahowli.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mybxbugs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xziqi.cn/Article/details/gt2mgjgysyz.html

C#:   x.GetType().Name; x is int
来源：http://dali.tian-w.cn/Article/details/gt2kiqycjjf.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gt2uhtzhirq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gt2pmqoyqln.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdqfuyst.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2baajqrkg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2tfpqieeq.html

Java: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2lcrtwdqh.html

Go:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2dajieurh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2rniosylh.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2vzhegzgx.html

[A06] 字符串转数字
来源：http://dali.sysykeji.top/Article/details/gt2uosyxveu.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pynuryjq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daria6918.cn/Article/details/gt2sauecyye.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jztnpfei.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2ncilyfqo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2yhxmqtnh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gt2csmvvlrf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.birdmap.top/Article/details/gt2gvdhpiec.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gt2vpruxsan.html

[A07] 数字转字符串
来源：http://dali.pycfn.com/Article/details/gt2vpqopkrc.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gt2byrxyfrp.html

PHP:  (string) 42; strval(42)
来源：http://dali.yueranfly.top/Article/details/gt2bmltvowr.html


<!-- 参考信息 -->