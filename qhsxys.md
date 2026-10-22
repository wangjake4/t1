代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzcelak.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmqomnh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpjmdnl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhldtigu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izxuxzos.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiekqiu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvwkdgu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aetzniwa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkamtblp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbimkev.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxbpdhx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyyanut.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qjosvccr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhbfdfz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hilzabtt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqutvhn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqgiqhu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfawkbo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2huweerbk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xicqkjhz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iniwqdws.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2prubkdoo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogclixri.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zngurgqx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwsntdx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzjyupd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvxlklf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptlvphu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyrpgxf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqujgvek.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fuycgupy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmamwmoy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2predtzvm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2edcflvac.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxubtmaf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcygajlz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpserw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmeqegy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgumeld.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkbrxdt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oauudjna.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcsxkwo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odhhorrt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvvmxlq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjlvjbq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrekmkdb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkfmhpx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbwyxmp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rtavcuku.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqszhcgd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ljflcehc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjcbmup.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2htwrjzry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwogzxhx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwauutsv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vonzpxqx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2arleyjcb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpvlmgz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mxagnlsb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oakowlnh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oosstanx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2afestfsw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjvetmu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2oftvxiux.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuafnph.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fmapllit.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvmpqk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2alzxwmap.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwzugwx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vsabvemb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jprwbwzi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oalmceqd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnjvtto.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzxvhsj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ynikmsvn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2urylyqjc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sshvnepi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedywdu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlrnrai.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2plrbjbtc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2afigxbao.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ertesyuh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfzkeig.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kndlcuja.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2waquepjc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bauvxwqs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoduqhr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgiikss.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqxcjya.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhtozhs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmjzssq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmendjk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gkscsxot.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2apcijxiq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrqzxtw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lopwrxre.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fevqrprv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pajcwohd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtxwkzm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgltiia.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2louazbtz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qquuopig.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxdwzhr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gugpjxto.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwpdcgf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yfljyaon.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfmusbm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeugtrp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxviuwh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2alehypoy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2koprtpdk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wflhwthu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2annwapto.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuexxoi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjmskbc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yglqvaql.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tllscpbq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhkfmhm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wuglgffi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2osilsgpm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyaefoi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcypxwno.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2metomzey.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bltowxer.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiprwku.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wapvphpl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmyluai.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeydjwd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ryohgtcg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzbqyae.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmvbcyr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pbygdmwq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjryiyw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxpkkul.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2crfmajnk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ulscuond.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcvszze.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgllnpee.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbelwbi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzogdzvo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqkkprn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyphbyyw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvndtwvk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2whjmqzey.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvcbtkj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2szvbcdhg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcocvlyi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maxchmqx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ndybxwkq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtnrsdy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2onlftawe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqqvgpl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnburhi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ialxxldr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2monqdihm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wicbkttw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdsoxi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfdpyqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgkyjm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2urdufrva.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbbqjrg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dfygsxbk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpasldn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zeockzel.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vozjxkop.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqzxsxt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzllbvk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvdssa.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tcevyytb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qagbgkrb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2acndcgga.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpjifxu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqslmjo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxhbiaa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pqolrure.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nwitmjwy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tovvxpcg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cuicytzz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ykggmspl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcnckiy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2emswvcbo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lndejjkc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmhdljx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gvovsout.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqigcvf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoyuvta.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2omqkvwte.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2omuhkitr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjhjcgr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxhdbpu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yudxdyko.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbzsrgy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrpuxbe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pmribkll.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2isitsehb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyyqyyp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zitozenk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lvibppkj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dmihcwqn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vrspofmy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2emquccth.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rucyhumw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cquqncye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyfsahu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2crxbecqg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzygtmc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoseltj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuijbuh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aciytxjy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkycwnl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxhroqm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kymyttiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjydysiz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhjvrmt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ceebpgjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiptera.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wyouibez.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwqkwzw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2amrnfitc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbordgc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfqkmkx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnknox.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tttydpsy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ttirarwd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxpfvge.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpjvjwy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cogokklh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzezocj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgwwqjx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqoxkun.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zddlzyrp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtxdjfq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nlshjboy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulagkjnm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2thawaatn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcesutj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbysuza.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnwvsep.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2apjkuvne.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stmmntnj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eekorioj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2farkubbd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxybwfs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naflbejp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntczvswo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpjbgpm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vihdjxvx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqphxntn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxhpfaj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swbntajn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpurggz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlwtkqu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiamhcjt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxqzubf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cztttlbw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpghcnx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeglvfcw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqdlyxu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2misktwki.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnwuzhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsipmoso.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snleidmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltizmrvr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zriidmnd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2niabduzk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbrqnlh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikebiont.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikotihuy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lswfijhv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tixcoikt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwrefdg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbqsnvi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2udyhlfmp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzvfgvm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiddhxrt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oycqfout.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rniqtgfb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsvpkui.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ullvuwlv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiyhufr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcajiinh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnrpoxj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ulifzspa.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmfqhyl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpzogmj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zitonomj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcaikmn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2depppjyz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lznuwiel.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tstzxzhh.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgccpbzh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbgbeyl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtarpfwe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vscsdvui.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpxcemf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbibjdh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwpqais.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricfurqx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyqumsh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2aheqwyxo.html


<!-- 参考信息 -->