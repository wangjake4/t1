代发 wailian999

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gt2pirghkln.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gt2taxpjavf.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gt2arpyzahu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nyzgcsrb.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gt2gqospmtt.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gt2nkgvttxo.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gt2fqgeqgrk.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2pnqldqke.html

[U51] PHP：数组解构
来源：http://dali.haohaochexian.top/Article/details/gt2mmdzjlqw.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gt2yptreycx.html

[U52] PHP：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gt2bizipmkr.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gt2nvrootqv.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oavwewiw.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuanzx.com/Article/details/gt2oiuwketv.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gt2jbcbenon.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gt2dvlxwwdq.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqxdapnm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yueranfly.top/Article/details/gt2bmswglzc.html

[U56] PHP：命名参数
来源：http://dali.yonumen.top/Article/details/gt2jcxgwrwo.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2tkbmdvkv.html

[U57] PHP：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2rmfeuihv.html

"值: {$a}"
来源：http://dali.guowangkeji.top/Article/details/gt2rcyuqlhe.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gt2fziysmrx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2dfuumhvq.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gt2ihwzinkk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2xwpdijcu.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gt2jurykcng.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gt2rezhzlom.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmgucrnl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gt2cluuyamz.html

[U62] PHP：日期对象
来源：http://dali.hammf.cn/Article/details/gt2hmwtphkz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gt2zqijtxvv.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gt2nmehxdrn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gt2vbtykpsa.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2gjqldcvj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gt2ucpxscyd.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gt2ekzgrhpb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2cxasudkw.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrodcxzg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iybpctmy.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gt2zrfmbrby.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xziqi.cn/Article/details/gt2bqhsasfa.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gt2ihzvgvkg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gt2irtnhorx.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gt2qbogssbk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gt2hlvapjat.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gt2lzfneulv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gt2nhllkubl.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2ivywqcum.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2houuqdia.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2inwaqxoz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gt2hvzhehgx.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hijhbpaa.html

parse_ini_file("config.ini", true)
来源：http://dali.chenzaomai.com/Article/details/gt2xfwxnswv.html

[U74] PHP：读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2qkwfwwdl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tanke756.top/Article/details/gt2swsluqjy.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gt2ywvfrocx.html

composer require psr/container
来源：http://dali.jqgufenzy.top/Article/details/gt2furcemxs.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gt2vwidhnog.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oreangbo.html

[U77] PHP：模板渲染
来源：http://dali.shangyingyoupin.top/Article/details/gt2xouebsyt.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gt2llsleiyi.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gt2ltcjkxav.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2lhqnthip.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gt2lmfqzsdf.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gt2yegzgjrx.html

[U80] PHP：代码规范修复
来源：http://dali.redwolf501.top/Article/details/gt2zwadxjej.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueismcvd.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gt2pxctipcr.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gt2rfwtxmtf.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gt2taowpbuq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jlsjyb.cn/Article/details/gt2fbqudnsn.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gt2esgqczyw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2oafoercn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gt2bzuaique.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gt2kosebrtw.html

[U85] JS：可选链
来源：http://dali.birdmap.top/Article/details/gt2ggeojlfo.html

a?.b?.c
来源：http://dali.cucudq.cn/Article/details/gt2axnvjxux.html

[U86] JS：空值合并
来源：http://dali.chenlongwang.top/Article/details/gt2qjgbdxce.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdqjfatq.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gt2tryleogz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gt2deqiyigs.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gt2ynrakyfj.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gt2rvmlknad.html

[U89] JS：数组去重
来源：http://dali.redwolf501.top/Article/details/gt2bdjyjhmg.html

[...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2ppioewtk.html

[U90] JS：数字数组排序
来源：http://dali.redwolf501.top/Article/details/gt2rqnvtoyf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2vzmcpyal.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gt2mrbvsdjb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gt2blzacunb.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gt2hftqxcdy.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2wcrniksr.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gt2pushabwk.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gt2mvsjnfyl.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gt2jknsnzhb.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gt2cvobrfoc.html

[U95] JS：Promise 包装
来源：http://dali.zhengqikj.top/Article/details/gt2nizrtcih.html

new Promise((resolve, reject) => {})
来源：http://dali.c1oappe.top/Article/details/gt2mslnesfy.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egbsrnqb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2arqkgoel.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gt2nlgxpeqs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2rqhbkuwz.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gt2gzxtrqtf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gt2tjoarmpn.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gt2hkqivekh.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gt2nsrupuqe.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gt2ezlgvzcg.html

document.querySelector(".item")
来源：http://dali.aibaodan.cn/Article/details/gt2hkhqiykp.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gt2ztdhdgzq.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gt2tmxwurca.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gt2tzgqgbgr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gt2acubmsgw.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2obitxpcc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbavfrdk.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gt2hfatxaqu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2dnvupouk.html

[U105] JS：节流
来源：http://dali.aizwys.cn/Article/details/gt2rsctihln.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gt2bmsgutzd.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gt2pucwvhwb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gt2dlpngjqs.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gt2ccfxfsyh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2sdvwmkrx.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gt2vtfdeyrh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gt2kvampilc.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gt2ivibxfny.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2apkimsmy.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gt2nvdssltn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.havefunace.top/Article/details/gt2lppshdum.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gt2agbrjkxf.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gt2dwvvinrp.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gt2xkjxcpgk.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2gkqlqtih.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gt2xhwzexhu.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2pwzetgov.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxmoutci.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gt2avtmexgt.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2nmwlmvmm.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2jtvhotqd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gt2bfphgobt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ydzc1.top/Article/details/gt2mehrgiys.html

[U117] JS：单元测试
来源：http://dali.yonumen.top/Article/details/gt2dmydtwyo.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2dpjqfupj.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gt2jwteylsf.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gt2owdkamqc.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gt2ndxcncuw.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfbcqyck.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2qzifecyd.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gt2cwrvximr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2rqxrgbir.html

统计汇总
来源：http://dali.cucudq.cn/Article/details/gt2rskssxji.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2vniqaler.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gt2oohdxbyf.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gt2msyvqlqk.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gt2mauzhrpz.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbxwvnvq.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gt2hvueittc.html

Java ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2ipuyzvig.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyjxawyh.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gt2kqvplcei.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gt2qxkdjxqj.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gt2tpwhddcw.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gt2zgtirgro.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gt2tdcufwcg.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gt2vwdrvyat.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gt2ezoqbgxy.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2falfpnos.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gt2ntxriqjk.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmxechku.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gt2atiszvct.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2njucgwtu.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gt2ejeyyiqa.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gt2thcwujqy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2ubbfyqnb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gt2cpuuspgm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltbcoeqe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gifhdqcb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gt2nkpepqrw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gt2dipfedkd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2miifdwpw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gt2egolpbae.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2wiupxgkt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gt2llsvmbnf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2zsmarmrt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2pakzidrp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2fgjkmjvn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyhmnaif.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jyoumei.cn/Article/details/gt2kpduhahh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2oqsysdec.html

Q SQL 专题                              90
来源：http://dali.zycfv.cn/Article/details/gt2pgypdbga.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2zixsocoh.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gt2tnbrruez.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gt2feqtwqso.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gt2sxuslgwb.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2laivrcuk.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gt2molreqmx.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvhaqjwm.html

使用提醒
来源：http://dali.hammf.cn/Article/details/gt2vepbpkix.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2egfzazby.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gt2bvkfpufr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuxming.cn/Article/details/gt2rvvbwyyo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gt2hvxpdayx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gt2rklurdex.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgenlqgu.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivordjbc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2cnrpbgjd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ybcxt.top/Article/details/gt2nyfawdmw.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gt2dworbhwu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vbrmpokb.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gt2mwtvtciv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.andypj.xyz/Article/details/gt2icojwmln.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gt2tfwwnaqn.html

SQL · Bash · C · C++
来源：http://dali.9152youxi.cn/Article/details/gt2cgrtyndi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gt2agjscdpj.html

【使用说明】
来源：http://dali.hnxiangtu.top/Article/details/gt2cqnfxybu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gt2buchlymb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gt2ppxeyqkr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gt2qktjwovf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigfzy.top/Article/details/gt2hriyjkdx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gt2dewckpxt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gt2gojtgcaw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gt2gsxwuhld.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2mqvbioeo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gt2iqcrxqox.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gt2fizbkoix.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cucudq.cn/Article/details/gt2whqftosr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gt2qiwsmimr.html

【文件统计】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snitdvmo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xinyue.icu/Article/details/gt2ahbajglz.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2ighrtncl.html

目  录
来源：http://dali.jiagoushi.top/Article/details/gt2jxvsntpf.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2timutjjj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gt2dvebceok.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2klntehgk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2xaruynra.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2bmdrfwnm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzgvwoix.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gt2knncrhji.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gt2sikewser.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2deyogbgs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2juvcwkmv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gt2avdfypkt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2dpkmlbvm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2zmfymbkb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2ihvibkxs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2btmajqms.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuanzhike.top/Article/details/gt2amybxhvk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2fgkfcgvf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gt2lkaotnpe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzpqbiwd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2ymljhuqy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2wsjqqhej.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gt2evzlzsxj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2nvggpils.html

A. 基础语法与类型
来源：http://dali.yuxming.cn/Article/details/gt2abaqfeak.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2kekeggfa.html

[A01] Hello World
来源：http://dali.pycfn.com/Article/details/gt2rtsidsgp.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gt2bpzurmbg.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gt2dvhebrez.html

JS:   console.log("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2iodqqiir.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gt2mrkjynit.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2optwsqsg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2kuynrzaf.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jycrsamp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gt2qtiubllm.html

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gt2jmjlqmtx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aibaodan.cn/Article/details/gt2wjrauprs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2niivfwbi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2iktfjfwl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gt2mnnnrxev.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2kvrakyiw.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gt2uaqejskx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fzhhl.top/Article/details/gt2cmkxozga.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2migaohdp.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2begbvsgr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgufenzy.top/Article/details/gt2rroswjdx.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2mvfzlhfg.html

JS:   const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2koesajnp.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2ufmxcfse.html

Java: static final double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2ufwugjsa.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2afemnpaa.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gt2wkpwjdvu.html

C#:   const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2qbxdmmkx.html

[A04] 判断变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2lgaqxniz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gt2yozgcerq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqwajgji.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gt2jwonhubu.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gt2krwqabxx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gt2evggtjdl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gt2gyeslofy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goyonbme.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gt2oipeurpj.html

[A05] 整数除法与取模
来源：http://dali.jqgufenzy.top/Article/details/gt2rfanytld.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.0kj1m.cn/Article/details/gt2utkbwuyh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2vvkiynhg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2zyxvesbz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2gsuresyp.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2cgonwrxv.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2lhealtxx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2lzerqveu.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjminfie.html


<!-- 参考信息 -->