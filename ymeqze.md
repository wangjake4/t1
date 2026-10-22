代发 wailian999

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gt2jzomqywq.html

int|string $id
来源：http://dali.chenzaomai.com/Article/details/gt2xrpvtkkj.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2qlnedmjz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jknqnoxh.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gt2tgseugbp.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnlqyaun.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qxigqabx.html

public function __construct(private int $id) {}
来源：http://dali.yj20258888.top/Article/details/gt2mgqpixxw.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gt2bwftwurn.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gt2melpzdhb.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gt2bdvpfvwm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gt2utxzmruz.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gt2fyqpxshy.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gt2cmpnuhha.html

[U54] PHP：空安全调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvqrvrgj.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyngayju.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gt2pmvzusmv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.bjfxy.top/Article/details/gt2ramdsaoo.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gt2qdhlxbrc.html

f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkaylynw.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2nlvxrmth.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2uvtwanbh.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gt2smazhfxt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2zmfdgjcj.html

[U59] PHP：自定义排序
来源：http://dali.xinyue.icu/Article/details/gt2ibcvuvru.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2lsxqclqc.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2expkhcff.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2fmazuisz.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gt2kvnyzpmu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2nkoqpaeh.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gt2ndpiqlyg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dianchejie.cn/Article/details/gt2gsaxfato.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gt2eqsxnfkj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hammf.cn/Article/details/gt2rtjmehbp.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynezrtsq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenlongwang.top/Article/details/gt2xxtwvczt.html

[U65] PHP：会话
来源：http://dali.zhongyouzk.top/Article/details/gt2xuhrqsry.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2vtpralup.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yawmimly.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aibaodan.cn/Article/details/gt2gpdapdxs.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gt2kubeglum.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gt2bmnarahz.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gt2dvxrfmja.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gt2dltcnirq.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gt2dlkayjqn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gt2rzudfuyo.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gt2kkbnaito.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gt2fqgywcqj.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxphtihi.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gt2imrnrivo.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gt2ioadhjoa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shangyingyoupin.top/Article/details/gt2pazgifsv.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2njiykdxq.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gt2nfdiauix.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2duhviraf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.birdmap.top/Article/details/gt2ibnoemvu.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gt2qykztzdi.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgmhrhjq.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gt2ytcrvasb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gt2hsglokdf.html

[U77] PHP：模板渲染
来源：http://dali.shzxlz.cn/Article/details/gt2hasdngfz.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gt2ahjrsprc.html

[U78] PHP：单元测试
来源：http://dali.0kj1m.cn/Article/details/gt2xilrttbn.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gt2jiaicrbi.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gt2wrbdddxi.html

composer require --dev phpstan/phpstan
来源：http://dali.jlsjyb.cn/Article/details/gt2angzgfdl.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gt2wupwpmgr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gt2tjbxpovk.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipixtshy.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gt2natiropg.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gt2utqsfaqr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgufenzy.top/Article/details/gt2eurgltaq.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gt2exdyalqr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2nxbifzov.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gt2lcwbiroz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.andypj.xyz/Article/details/gt2cpnyqciw.html

[U85] JS：可选链
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnfrxdfs.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gt2ekfvmygn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyhyelr.html

a ?? b
来源：http://dali.yuanzhike.top/Article/details/gt2btgypvog.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gt2ofxfllqf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pengpengdd.cyou/Article/details/gt2riszajcy.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gt2phtrsman.html

{ ...a, ...b }
来源：http://dali.svipenyu.cn/Article/details/gt2fethjbbh.html

[U89] JS：数组去重
来源：http://dali.sweek.top/Article/details/gt2njpvsxob.html

[...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2msfojeqf.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gt2qlrvrmzd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2ksizcxpw.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gt2avgcpnnw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gt2aklnprhp.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2soawalig.html

structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ijufzmnr.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vropjfja.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gt2idcznvnh.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gt2llwyukgh.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2lkwlnevw.html

[U95] JS：Promise 包装
来源：http://dali.zhixingplan.top/Article/details/gt2osjdmmxd.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gt2odlvbdle.html

[U96] JS：async/await 与异常
来源：http://dali.zhoulong.xyz/Article/details/gt2jnpodxzm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bpkwatfe.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2sfochixp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drphqkcq.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gt2nqggonlv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gt2xkrqoueb.html

[U99] JS：事件监听
来源：http://dali.aibaodan.cn/Article/details/gt2nmqaazah.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gt2vlodfmmq.html

[U100] JS：DOM 查询
来源：http://dali.tanke756.top/Article/details/gt2bdbctibs.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gt2fydvwdfy.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luclmuya.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gt2toibxihe.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gt2ismineqe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gt2mvgddgqr.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gt2qsbczgry.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gt2ahnihirf.html

[U104] JS：防抖
来源：http://dali.jianghu66.top/Article/details/gt2yyrhoawd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2bhwyzbvj.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gt2prbjgnrr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hufsfyav.html

[U106] JS：日期格式化
来源：http://dali.havefunace.top/Article/details/gt2qikjebqj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gt2ikxtviyg.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2bkdllbyk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2tenbjqec.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwaftvsg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gt2vwjymcug.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gt2vigtqxuk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylmyzghf.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2ratsdxou.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gt2xmphpaag.html

[U111] JS：对象转 Map
来源：http://dali.birdmap.top/Article/details/gt2sofapwro.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gt2telkwqnl.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gt2zuqpdqap.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2uqvibaeb.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gt2jpjtcoyy.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvblkmch.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gt2izjzmrun.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2pwxkshzu.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2ijlxuxcr.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2lixmvjee.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jlsjyb.cn/Article/details/gt2pcqyxxko.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmrtcfje.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gt2kitsubop.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gt2cqgnnddj.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2isulukow.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gt2dretzoua.html

[U119] JS：生产构建
来源：http://dali.fengsongda.top/Article/details/gt2jfmetypx.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aneoqebt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gt2glodethu.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gt2jfteltqu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xwdhqahu.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gt2tamvraoy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2knsqhidu.html

按语言统计（条）：
来源：http://dali.chenlongwang.top/Article/details/gt2sdovpuyb.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gt2rapicmyl.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gt2twkriufw.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2rjexsuii.html

TypeScript ..... 212
来源：http://dali.xinyue.icu/Article/details/gt2agrtbotm.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gt2pgfzvpog.html

Go ............. 212
来源：http://dali.zhixingplan.top/Article/details/gt2axorvkmg.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2tzfbgtdf.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gt2lcnpgans.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gt2zrumxtcx.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gt2shzrfcwl.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgaczgjm.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlovmqbf.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gt2msnnrqbe.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gt2dzzkmxdm.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gt2ihwtwefy.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gt2nqazyklg.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gt2azchkggt.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2blytrdao.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gt2jltvxqla.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gt2ubkdnqhn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2fuoigtxt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2qyxsuvyv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2xylvqdkn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gt2qudakwhd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gt2haxkuwmh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gt2gitiqwhs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gt2upveqnli.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gt2avmimawr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2pbmvrdtx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2qnfyfqvs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2inautyhn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2zejnfgmn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2syvfxxyp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gt2vddsmnof.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgufenzy.top/Article/details/gt2uioammfe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2kasvpuys.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gt2ewumamox.html

R Bash 专题                             80
来源：http://dali.xylfe.cn/Article/details/gt2hwgnnpnb.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gt2fbhztmcu.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gt2zvknsqcm.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knoorizt.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2amlhlwom.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hykunvwv.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2ylorzrrs.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gt2uljpvwdm.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2xmcalfib.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gt2fgqsehyb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gt2thiiznte.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnqzz.top/Article/details/gt2omtexcek.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gt2wcywtyha.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gt2hwdcrybx.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gt2kndxguty.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mbxwaxps.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gt2glkhkcpm.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gt2zvzgelwz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qiwcykov.html

【收录内容】
来源：http://dali.cqqwz.cn/Article/details/gt2txqgjwcv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2aujgvljc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gt2hesoxnsa.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gt2mheaoeoa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gt2kmzsphtk.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjvsjjjw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gt2vcvtmktj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hysaishi.cn/Article/details/gt2creicqsb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gt2usxwbhlw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hppwzfny.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gt2xjbgzbob.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gt2ajsisosu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cashguo.top/Article/details/gt2jqdckqtv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhongyouzk.top/Article/details/gt2enhknnbl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gt2jsbtafee.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2suqmojkj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gt2hkwimwpb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gt2lzzfloox.html

【文件统计】
来源：http://dali.xinyue.icu/Article/details/gt2immwkrdj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.9152youxi.cn/Article/details/gt2pgbzkseg.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2gwnmrsix.html

目  录
来源：http://dali.0kj1m.cn/Article/details/gt2winpujmi.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmjcudza.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gt2akcqzdmy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gt2timqofyw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gt2hkozbehj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gt2rvbtlhge.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gt2hrlnksuc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2jdzhgvlu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywhmsdmo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gt2nkwgbbyv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2xuatesso.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gt2qkfiohmm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqspclpq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2irisiuis.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2qmquwsjy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlgtgnsg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gotoacloud.top/Article/details/gt2puuthicb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2flnoqsve.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nleqojaz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2ezgiaygp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gt2cbqkgufk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flezmvjf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2xkkwhkyl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wrclqtax.html

A. 基础语法与类型
来源：http://dali.dianchejie.cn/Article/details/gt2razlrtfg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xdysbovr.html

[A01] Hello World
来源：http://dali.yj202588.top/Article/details/gt2tprsnwht.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unphaeys.html

PHP:  echo "Hello, World!";
来源：http://dali.shzxlz.cn/Article/details/gt2zfpzlxys.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gt2retkofle.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gt2koszpwbf.html

Java: System.out.println("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2eyyknagy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gt2skcmefmk.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gt2syxxvzdt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gt2erwmigcm.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gt2amdpmmoi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gt2iwelpybq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2iwgcsplk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2nzxwdetg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgasbjbg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2gronjkgc.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gt2kkkwzggc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gt2arpruxkh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fneflnvn.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aooqfxtc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gt2osvfbevd.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2nmycmynb.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2jadmwybe.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2kdtcbymo.html

Java: static final double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2aquapqqc.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjjqnqlj.html

Ruby: PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gt2nfjobwty.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2poikxygz.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2mkuiirwf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbbmjezk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gt2slvdtvge.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvdvsulq.html

TS:   typeof x; x instanceof Date
来源：http://dali.ivvv.top/Article/details/gt2fjhrvrad.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gt2qnfvqjyw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gt2ttelnrvo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aizwys.cn/Article/details/gt2mrwgttuc.html

C#:   x.GetType().Name; x is int
来源：http://dali.bjfxy.top/Article/details/gt2hjgeluop.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkfftji.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.vqdsnc.cn/Article/details/gt2oyftdepr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gt2ycuwzmio.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2didqlpsw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2lqtalerz.html

Java: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2yufgugnu.html

Go:   7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2utivgpca.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amiuuyoq.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2mqffgnog.html


<!-- 参考信息 -->