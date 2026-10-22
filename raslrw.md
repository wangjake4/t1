代发 wailian999

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqgejqwu.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gt2oqppeibw.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gt2lieaxmpw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gt2gupsrdre.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gt2isaekqfd.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gt2srocjxym.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gt2vomuiznc.html

public function __construct(private int $id) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qcwmiisp.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gt2snprehhs.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gt2fksgrbvl.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gt2onrrieqh.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2ahxjvdcb.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gt2oymkqeea.html

$v = $a ?? $b ?? "default";
来源：http://dali.c1oappe.top/Article/details/gt2vugdtqjm.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nymbfgxb.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gt2ufinncxi.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2igkllltl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajdozmtb.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2muahjyvy.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2ugopszme.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2dbvjvwbo.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gt2iazwvogo.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gt2wxpdogtd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guannengcc.top/Article/details/gt2wreyylae.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gt2fgijgkhh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2gokqjmzr.html

[U60] PHP：JSON 编解码
来源：http://dali.shuidangran.top/Article/details/gt2gxpyavna.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gt2ftidirav.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gt2myoqfpur.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2czwaehha.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gt2npayyvbd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gt2rmjvuasc.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gt2fvqhgzti.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gt2kvggixmt.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gt2pdibrmqw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhiwuduotai.top/Article/details/gt2fewqjsvq.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gt2rhgymgrq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2zbnjmzeo.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gt2blxgvxqu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yueranfly.top/Article/details/gt2bpbaeupd.html

[U67] PHP：处理文件上传
来源：http://dali.aizwys.cn/Article/details/gt2tflabrqw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gt2xohcljrd.html

[U68] PHP：PDO 连接
来源：http://dali.fzhhl.top/Article/details/gt2snpbgamv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gt2vyxseptv.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gt2mmavhcin.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gt2oekygtmx.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gt2crpqjdkp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gt2ciijgbsk.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gt2ximnujoq.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gt2cdzvszpj.html

[U72] PHP：写错误日志
来源：http://dali.daria6918.cn/Article/details/gt2hlstrgve.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jyoumei.cn/Article/details/gt2sqrvnbah.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gt2eyzeevyk.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wigerbcv.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfzweilu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gt2qparhzyc.html

[U75] PHP：依赖注入
来源：http://dali.cqqwz.cn/Article/details/gt2ezroaqfm.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gt2ljewvulp.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gt2ipfwdkxv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gt2gfignnan.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gt2ytmjqzxl.html

composer require twig/twig
来源：http://dali.c1oappe.top/Article/details/gt2zosztrte.html

[U78] PHP：单元测试
来源：http://dali.cdnleiting.top/Article/details/gt2fyrtunvk.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gt2qgyhhmky.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gt2hcswexqo.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gt2thkxrmjr.html

[U80] PHP：代码规范修复
来源：http://dali.smart0.xyz/Article/details/gt2rnnbkqdx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gt2iwemfyvn.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gt2radqmirm.html

npm init -y;  npm i express
来源：http://dali.nwbrower.top/Article/details/gt2ggblvzbq.html

[U82] JS：package.json 脚本
来源：http://dali.jqgfzy.top/Article/details/gt2nycdofar.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gt2orsogkjs.html

[U83] JS：ES Module 导入导出
来源：http://dali.bjfxy.top/Article/details/gt2rtahhozj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gt2hbxepvle.html

[U84] JS：CommonJS 写法
来源：http://dali.andypj.xyz/Article/details/gt2wsgeswbd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gt2jydioksl.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gt2icaltgih.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gt2crlxghxx.html

[U86] JS：空值合并
来源：http://dali.mhx1999.top/Article/details/gt2wgccicyz.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gt2xvewftsq.html

[U87] JS：解构默认值
来源：http://dali.cqqwz.cn/Article/details/gt2dpptmnql.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gt2uerljojw.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gt2xqeabuyw.html

{ ...a, ...b }
来源：http://dali.jianghu66.top/Article/details/gt2jbxvlwux.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gt2txgdlhco.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2aensjuii.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gt2fclcxutw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2mvkcipxz.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gt2rhezswcn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gt2deubeurl.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gt2sccnkdjb.html

structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ebinmczd.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gt2mefvdgle.html

`共 ${n} 条`
来源：http://dali.pycfn.com/Article/details/gt2dujhqwby.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2thyvfqko.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2cfkhgufz.html

[U95] JS：Promise 包装
来源：http://dali.jianghu66.top/Article/details/gt2nfukubdd.html

new Promise((resolve, reject) => {})
来源：http://dali.wangdashe.top/Article/details/gt2brgrppye.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gt2xzpgbxju.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxrslhyg.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2hfektefi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2emxdhkww.html

[U98] JS：fetch 带 JSON
来源：http://dali.c1oappe.top/Article/details/gt2dhyfidwv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gt2pmofisiv.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gt2duuxpidd.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gt2terjlulo.html

[U100] JS：DOM 查询
来源：http://dali.zhixingplan.top/Article/details/gt2xoedqeem.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gt2ceikklck.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhlgwtes.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2rpvbxcli.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2khwadoro.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gt2nenluuyj.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gt2imaeumni.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gt2acrwbzbk.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gt2dldghzvn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2qcciuuyi.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gt2ompptpvx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2ytzfyjzn.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2sxnylzpb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gt2mejpbazt.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gt2pnlefsvp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2cqftlrzg.html

[U108] JS：随机整数
来源：http://dali.zhixingplan.top/Article/details/gt2hxnvjchh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gt2dpjeakcq.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gt2wmqqmuzb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gt2ztfasvcx.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gt2fhyjvcot.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gt2fnocwmtj.html

[U111] JS：对象转 Map
来源：http://dali.wangdashe.top/Article/details/gt2ukkntfcm.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2cihfltce.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gt2bgeebado.html

"7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aoetkxyj.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gt2lybvvdwn.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2veiawufk.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gt2wrqegjar.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2cahlszgs.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2kbyrywet.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2jvmfhkmf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gt2tvnjyuyz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gt2qjifbnbp.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gt2xuupdycd.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gt2xfddaevy.html

[U118] JS：开发服务器
来源：http://dali.gaohongyu789.top/Article/details/gt2tlkytzah.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdaigumv.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gt2idhxizsq.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gt2tmawzahm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gt2ejcphwsb.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gt2ktprccno.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2jgrdmcvv.html

统计汇总
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byohocxe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2quydgckb.html

按语言统计（条）：
来源：http://dali.kuanghao11.cn/Article/details/gt2emmmogyy.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gt2xjrqqiyn.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gt2djrqfuya.html

JavaScript ..... 252
来源：http://dali.shuidangran.top/Article/details/gt2vwpofqcp.html

TypeScript ..... 212
来源：http://dali.xinyue.icu/Article/details/gt2mvcppwoq.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gt2znbfqmsa.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2abwoebdc.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2ouheqibl.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gt2uifaathb.html

C .............. 30
来源：http://dali.haohaochexian.top/Article/details/gt2azxxvkgj.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2uglcvkez.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gt2wltxxnzl.html

Bash ........... 80
来源：http://dali.cqqwz.cn/Article/details/gt2yjxnwqte.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gt2lgwhcgcc.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gt2ndxyzlsb.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gt2nufiimsh.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2hxkguojc.html

Scala .......... 10
来源：http://dali.zhoulong.xyz/Article/details/gt2mdxlihvr.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2ciudzrnv.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gt2cmamhyjf.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebrpgvxi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gt2rmkyxstg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2fmevuxtz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfjcsjis.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gt2pcwvznpm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yvedp.cn/Article/details/gt2mdbksmuv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gt2zlfrgcvz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gt2kjnoehvm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gt2czmqoarx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2rrwiwqtp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gt2capnimcs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxjzywiz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2tgzfpzmu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2jqwfdozt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gt2nelmhxeb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbawdtug.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2lgnaseuo.html

Q SQL 专题                              90
来源：http://dali.jlsjyb.cn/Article/details/gt2qaydoipj.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gt2qawphafv.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gt2wqkwioma.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2whmeqfgd.html

U 高频实用片段                         120
来源：http://dali.guowangkeji.top/Article/details/gt2bqxdecfm.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gt2gwaijihn.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2unjfguvf.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2kxvinsiy.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdpdaiha.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2etwbfzot.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gt2fhtvwukw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258888.top/Article/details/gt2uvdtnuqr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.snrcjt.cn/Article/details/gt2ehvnyfoi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gt2vwjofbgm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jianghu66.top/Article/details/gt2nqzrxdkn.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gt2ewatcdps.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cmtaolmt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gt2netesceb.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gt2sjboypak.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2iaubigjf.html

【收录内容】
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjsxpylu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gt2rejqigkr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gt2kgdkyjve.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gt2kjlqrnao.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daxiang520.top/Article/details/gt2tcatwwmq.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gt2zggtoqyu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhoulong.xyz/Article/details/gt2icluwgck.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aibaodan.cn/Article/details/gt2ptqjlpfc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cqqwz.cn/Article/details/gt2oqejhzhj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytmniwmm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gt2hzrvveso.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gt2ofjbcgox.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gt2kxhukilq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gt2plfotmie.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gt2kentbxex.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gt2rlcuqnnb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlnmzwmm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gt2ksedrhlw.html

【文件统计】
来源：http://dali.ehwqpu.com/Article/details/gt2uptybxnn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gt2etggbcqw.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2kpkzjqhx.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gt2hjlpgkaw.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2wujaxazd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gt2bygvnvex.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2kfpwapaj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gt2jnaejnkd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2zwxghetm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gt2jumoqudf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2cvjmpqey.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2fkwzybil.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2hhlaipyn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2iizfgtsd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gt2pquadhwy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2thxwsyim.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2yinvmoyl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2eujvkdqv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gt2tjrlqjir.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tianlin.xyz/Article/details/gt2xvsgiarv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gt2jxxknvhp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwzmkokb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2idotqfqr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gt2qghnulpw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gt2mocitfrx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2ehrwqdbe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wgzcryaf.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gt2bnevfizq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2joyiosqe.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syxqsdkb.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gt2czdqkzwa.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gt2jlqsprqy.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gt2llvvchvs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gt2lttqjois.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbegvicx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2ffcepvsk.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gt2yclevlpn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2nhslzffz.html

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gt2xdeocedg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gt2efjvpcjn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gt2fqsvxqmn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2rrdkyang.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqosjdwj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2uttrdcyq.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gt2bokvynlc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj202588.top/Article/details/gt2fucaqeyz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gt2nudtnwqu.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpxlkwfa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gt2rcikieye.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2ytdpnzhs.html

JS:   const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmaecjcw.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2efhajcic.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxgwzjqf.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gt2metafzzk.html

Ruby: PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gt2zuahosaj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvkjhnab.html

[A04] 判断变量类型
来源：http://dali.yj20258.top/Article/details/gt2qskdrtrs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gt2lafjogal.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aibaodan.cn/Article/details/gt2fczlqbok.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yongpay.top/Article/details/gt2jxaazmpn.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gt2adfuthls.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gt2kbswjqlx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gt2epfwziqy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangdashe.top/Article/details/gt2wkdughiv.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuanzx.com/Article/details/gt2erapjwpf.html

[A05] 整数除法与取模
来源：http://dali.yueranfly.top/Article/details/gt2bknzvctf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fengsongda.top/Article/details/gt2nxhvzono.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2amhmgjtc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2dvcnxdra.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtmizhac.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2zvmygdbm.html

Go:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2oquizvug.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2jyfdnget.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2leqvbjhh.html


<!-- 参考信息 -->