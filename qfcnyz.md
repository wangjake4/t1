代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gtjmrfzoax.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtodblaxyj.html

[U46] PHP：可空类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzzrhsroq.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtoxhdidhr.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtnltyadae.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gtzknhsukp.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gtfnxxoije.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlzfjzuke.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gtngaqlipq.html

public readonly string $name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvucvxqy.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtjtatavuy.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gtmxaburcz.html

[U51] PHP：数组解构
来源：http://dali.hnxiangtu.top/Article/details/gtcfkgetao.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gtuguqsdfc.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtftyrlnka.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeensdjn.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtjwelknfj.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gtfqoevngv.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtizbiywgq.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gtnxqhhsig.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gteqzutmbw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtylezkxea.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gtbhpjtxqw.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtaexuivik.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgfqphrc.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtwfdmzbgh.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gtiqtuzzfo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gthjywvfga.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gtemtlpcum.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtheacnjcv.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtpglqgqol.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gtovcysopn.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gtrjmfnmpj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtiotswqeu.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtryjrpybe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtljdqumns.html

[U63] PHP：文件读写
来源：http://dali.hnqzz.top/Article/details/gtwyjlyiad.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhoulong.xyz/Article/details/gtdlamamrd.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gtblyygmrh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gtxprsrnsg.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtelgxzekm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.birdmap.top/Article/details/gtrwezkynu.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gttdcvvpap.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gtuxqnzwou.html

[U67] PHP：处理文件上传
来源：http://dali.zhongyouzk.top/Article/details/gtolglforp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gtbhwhbqjh.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtnsdlclto.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gtzlmgaoje.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtuomodjmx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gtnfyshksb.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtakbvyptd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtfjlfrcqg.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtnbglxzob.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gttwtxqwki.html

[U72] PHP：写错误日志
来源：http://dali.redwolf501.top/Article/details/gtgkoomsuv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gtyrymvwor.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gtlcqrppqb.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gtifjxgmcs.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtgcenufyf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtqczqmckp.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gtxrvurrzb.html

composer require psr/container
来源：http://dali.0kj1m.cn/Article/details/gtmzlxevpu.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gtpnrweygi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtsvofflma.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gtlosclnlq.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gtliughixv.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtukclczsl.html

composer require --dev phpunit/phpunit
来源：http://dali.nwbrower.top/Article/details/gtgfhoqfkg.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtnhohdfsm.html

composer require --dev phpstan/phpstan
来源：http://dali.chenzaomai.com/Article/details/gtrtnahxpn.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtrqwxdhod.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gtrtswhjiu.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtqbzludbd.html

npm init -y;  npm i express
来源：http://dali.9152youxi.cn/Article/details/gtecxxeits.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gtaaccoqjd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtzmcgapmw.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtrsytpokm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtyjbkxdsb.html

[U84] JS：CommonJS 写法
来源：http://dali.kuanghao11.cn/Article/details/gtbadfjfks.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtubjdbnyk.html

[U85] JS：可选链
来源：http://dali.yvedp.cn/Article/details/gtwbuqdker.html

a?.b?.c
来源：http://dali.hongshengwenyu.top/Article/details/gtyqvavjqk.html

[U86] JS：空值合并
来源：http://dali.redwolf501.top/Article/details/gtsgwddzqi.html

a ?? b
来源：http://dali.gogol.net.cn/Article/details/gtosdrjhyl.html

[U87] JS：解构默认值
来源：http://dali.xziqi.cn/Article/details/gtcnzsufkn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gtlrcucqyi.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gtgsciannq.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gtyttxdovm.html

[U89] JS：数组去重
来源：http://dali.yuanzhike.top/Article/details/gtxrvojewu.html

[...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gttivlwxhl.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtsarpfbug.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtrbiruyai.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gtmwpwcvmm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ehwqpu.com/Article/details/gtrcuspdvn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtawzuzyod.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmmzweyfm.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gtprzkechp.html

`共 ${n} 条`
来源：http://dali.quarkkingdee.top/Article/details/gtnznmyroc.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtwzjcnstn.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtrstmlsnu.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gtxxmxfjzx.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtzgitaztl.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtpyrxiycc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtgudpnaop.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtqrcgpvux.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtbaxvnphx.html

[U98] JS：fetch 带 JSON
来源：http://dali.sysykeji.top/Article/details/gthoacasal.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtlmxhphxi.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gtomlmpjwg.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojncxfst.html

[U100] JS：DOM 查询
来源：http://dali.tianlin.xyz/Article/details/gtpghxetck.html

document.querySelector(".item")
来源：http://dali.snrcjt.cn/Article/details/gtnkigdbpi.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gtivuyhnim.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtpdxxvjty.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtpbpqrssp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shzxlz.cn/Article/details/gtggmoyexr.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gttzdllaml.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daria6918.cn/Article/details/gtqwzqlncm.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtffivbeyq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtrygifbjt.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gtzrhvrbzy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtruqrnbni.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gtsdowbihs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtycyqxrmu.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gtbpxihydm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnltfawhk.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gtthkqvqyo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gtoohgqumq.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtbsqupzxq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtmhjwlhxr.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtxqhhvriu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtunmhihoj.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gtexhktfjl.html

new Map(Object.entries(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtkfzomzkg.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtgswflqwt.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtsocjczqa.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtnpycphvr.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpybrtgmk.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gtvnyvduxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gthbkzihit.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtqaapadvi.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtgcppmzmv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yanxiufei.cn/Article/details/gtqjrgjmbs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gtnhwwvcst.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gttnvykzoj.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpfvioan.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gtnusxjhwt.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gtxzwlnker.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gtsfdcztxn.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtzqhiyqic.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtkmwnhfwg.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gthfpcarls.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyccaiwsy.html

统计汇总
来源：http://dali.yuxming.cn/Article/details/gteertgyxu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgfowvdd.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gtucfhbalh.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gtrxuebrmm.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtvjwtjuyw.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gtrkuqtnml.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtwmzttsof.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtibqjmele.html

Go ............. 212
来源：http://dali.gzhubu.top/Article/details/gtusbhmqqr.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtjtkiyuit.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtocnafpxv.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtkvhdcsxb.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtwjhkfihz.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gthkzzrcla.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gtthjpyqwp.html

Kotlin ......... 15
来源：http://dali.gotoacloud.top/Article/details/gtpzbdzapu.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtwecothny.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtzhodnaig.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtuyjlkcxs.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtbyntgqut.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtvrsihfaa.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtrhgqpbxk.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtofoxvfvl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtvewtdwjk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtmqstqeel.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtjrwzaqez.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gtrgnlmely.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gthevnqpbb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtthbpfpyz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gtqetfqchw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtumpggnuh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtdxqscexb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtuaggxboc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtjxcftlmg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtzmgawqrs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtxekcnmug.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtfemwdmca.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gtetfrkziy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtpzfdnryj.html

Q SQL 专题                              90
来源：http://dali.hnqzz.top/Article/details/gtlldtfull.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gtviwykckq.html

S C / C++ 专题                          60
来源：http://dali.feifeiyinyue.top/Article/details/gtprfhvadi.html

T 其他语言补充                          60
来源：http://dali.wangdashe.top/Article/details/gtqrwjelhr.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gtsirvcacp.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtgnkphnuw.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gtqskyvzlo.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtfnvfhcog.html

使用提醒
来源：http://dali.xylfe.cn/Article/details/gtntrqhqqv.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtnmusmkul.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guowangkeji.top/Article/details/gtygckdkmm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aizwys.cn/Article/details/gtverropbu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuanzhike.top/Article/details/gtankratdy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfcszcpv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtlihfvzsi.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gtvefsmmob.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjqmddivq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtzrbjgj.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gtgazfnzgj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgdcintlg.html

【收录内容】
来源：http://dali.yongpay.top/Article/details/gtwpofmsol.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ybcxt.top/Article/details/gtxyenpzca.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zdqjudy.top/Article/details/gttcotghta.html

SQL · Bash · C · C++
来源：http://dali.ydzc1.top/Article/details/gtxujyakuv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gtohbjouml.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtepaatwab.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gtslyjuflh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gtekmyjbci.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gtomphneol.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.0kj1m.cn/Article/details/gtddmgpccj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gtzvnjxibt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gtcsfqoqwr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gtcdnjcpha.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hywenlv.cn/Article/details/gtpriflmcw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuanzx.com/Article/details/gtmghacxeo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.smart0.xyz/Article/details/gttipbmosa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nwbrower.top/Article/details/gttnrwhvil.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gtniysfhms.html

【文件统计】
来源：http://dali.quarkkingdee.top/Article/details/gtxsffagvr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gtbeolfrzc.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtfzuhykek.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gtvpeqaoar.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtbksbycxb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtgdzmsehp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtptakznwd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtwhbsfwrb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrkvqesq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuanzhike.top/Article/details/gthozaaadm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtjrmngnya.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtqlvstttz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtmteknxrk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtrkvzitvs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahuffzqa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuziqqktb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtfdlgtiro.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtbwhqhmpp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtktesamfi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gtwpxchwxh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtlngiikfv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gteivdylii.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtlsxtpspp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtbvjckzqq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtscgwfvfu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtpiifrpaq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbjgfqimc.html

A. 基础语法与类型
来源：http://dali.daxiang520.top/Article/details/gtzksoqhnr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtylqiucrr.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gtcutyhbsy.html

Py:   print("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtdaozkfpz.html

PHP:  echo "Hello, World!";
来源：http://dali.dianchejie.cn/Article/details/gtfvlsifrb.html

JS:   console.log("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtnfrtzpmc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gtoecdyqby.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtegggpwko.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gtewhgsjks.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gtmrqsxehu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gthtiaprjw.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gttcbtoeyv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sweek.top/Article/details/gtthvivvta.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtsbrgnpvq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtrtsipedt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxuanxn.top/Article/details/gttkcmrgur.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtqpibvoqi.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gtigacuslt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258888.top/Article/details/gtmrebmsxj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtlwpztoik.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtkgsqargs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigfzy.top/Article/details/gtrcuecgic.html

PHP:  const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwngyuebh.html

JS:   const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtumtmyzdr.html

TS:   const PI: number = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtidvkguhx.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtgmhvwhjb.html

Go:   const PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gtyymlsdzz.html

Ruby: PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtutlmqvhr.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtvxdqxxkz.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gthxiadnap.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangdashe.top/Article/details/gtvtxchwvt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tanke756.top/Article/details/gtnsjcfskw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtuhcosmim.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtrfsqnaio.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hywenlv.cn/Article/details/gtstklausj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gtmemjuelz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.haohaochexian.top/Article/details/gtpchppjil.html

C#:   x.GetType().Name; x is int
来源：http://dali.hongshengwenyu.top/Article/details/gtctznwnib.html

[A05] 整数除法与取模
来源：http://dali.zhengqikj.top/Article/details/gtaxinyglb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yanxiufei.cn/Article/details/gtnisuxdbh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtdqfgelbm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gttetwkaea.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtwmxyqzqr.html


<!-- 参考信息 -->