代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hogaljck.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2apbvpuzd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbzhtnw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2izaxjmyo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfezeaj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zespcoya.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wwopipfo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfikiqr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwgadxb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2osuutzrr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhshvgt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwvbjmr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwiyzu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbcmupg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdmqhjp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeexuyrq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyahpog.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2siriwnpo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2houfpksy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbllxwh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ldshqpvh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjrmrgv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpjylyz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wylizwmn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnrltev.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lieiusfz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gykxafan.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2getlxejf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxueomn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhwugzs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuyuqon.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pekvoxuk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlfmwfq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfeveqw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqewvqkk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxtymci.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2okprkcwv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuccyyit.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdswrskb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqgoxzs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibapffwc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2idiszdyu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxucbdzn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafcqnkb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeopihl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zazebple.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrrfaiq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqvgdas.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2caxzxity.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwezxds.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vaddhxoj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmnxhsk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kadrkgbu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwadbypl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjivrb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eknnnkyp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2krfcbjwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvobacp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2adfmqqhx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmgdptn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwswbzs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzydajuh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqaxxao.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkdmzcq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bynaxwkn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsjnqwn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hochlomw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2amzeorzw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2snlrgduh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klqvokto.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmegkqdt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yeusljtv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfhvtbi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyvnibr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mncqkiom.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfemxty.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlbdfwl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2chokibig.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkhoixm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjuyeth.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2huhsrfgw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmcicv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2heyfvtbr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jittopyq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2embbwtmk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeztxei.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fftqeffd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyfczby.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sednizhb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfxnhjp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ltveewuy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ognmvuvw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2etekmwxs.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rymdijbz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpyurag.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2msfintbu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jduvmzqw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2krngamxo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oitcpryz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqpawvq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ncicemnu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsneopj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hozfsqdy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gncrbmez.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsqpxai.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2haycmbai.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2myiibjpx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otaqotve.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdyhqwd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvsczgx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2siajnpyq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeogkig.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhcuedr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzcrxje.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkxrbfz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjtzfuh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiqdyxv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuhuoqn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrsyqzr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrcorac.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ielljumy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nhztveoz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpilfzl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnbfazh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsxxiza.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhhqkcp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2efbtnfmf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wxciznbr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rtekddtq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwzehnt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvczlt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2phvzeovl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2piddnxvn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqczftte.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkilcex.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkwsblr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2glasjsbq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzotduiv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmmmewg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhspba.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjxfjrh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhetserw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aluqsncr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aczwlwev.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoerhjf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjghpjqk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoswspb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtydaop.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvwypgq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaffgtjn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2skhgtjno.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uidtqich.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwtjvrm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxsygia.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2suzrlphv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyyouil.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rnofguag.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgalznnz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsytdnm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axnuzoah.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gkohxtjl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwekfbms.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2quonpgee.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrmfklj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rgknzlin.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtdbkfx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcnmzzl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kijnbpyi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nblckzvw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkuquiw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjtaaht.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pyreggqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2objxnbtd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxgwqnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oocpbujc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2akuysgcq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2apokipqm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vktvnmbc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hswwtduu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qurfzfah.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmmakgn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wafhntpl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hvryutha.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyhcclq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2twxzbipy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvftaus.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzbbdft.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tblgyqmc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxvftn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oljoavoh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oayirouf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumxbyx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjjvxlr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrrypjr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vunnqvcx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yubplorx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bhojxoee.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mvainyaj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfvlnwy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cjctzqij.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjovbdb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuwwhen.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmcgalb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyqvffl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjzfzta.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrhwapp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhxzczb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdnrbwb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ygydvywl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqagxio.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2syjiclbf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwojmucj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2accwrori.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmqpmlk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hvifhzxc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wapxydbf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2udcefsca.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpwohox.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbekxqd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2herqyvtk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoyyyfh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2csdwsnri.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvsvtai.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2urbxjdwz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpzvfxz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdvmfhn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzcsqix.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdveejb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2booiyoki.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2slcjtqjl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2stvbblvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjzdzac.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwggwcr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2snpsstii.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2izbrhurh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oibkurfs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fubfpqrv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcohqyt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfpfbqp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lymyjekg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jadtqmqx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmbvjvp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2trpnxhyb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbgqelx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2llizklpv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpknvjr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mpweochl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqefqlk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftgbhi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeonzda.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpufuwh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2limelrkp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2otzoqiss.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgggufu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuoszvh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtntsuo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foseumia.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwusazpr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaktikck.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkgulqg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mylibxlb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwoytzz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjngqspc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmouldx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwlpnoj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuocesr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2asxlpmdo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajarcmrn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kovmwmws.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaaswer.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgabmxzo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2upobityp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfypfpem.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luvgnykp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzegjlgv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwpgdvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dndznamf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wphbdgyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cogqjmld.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqceiehx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fowrduom.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaeudgs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbfewns.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcooepgv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlzzvol.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jluavijs.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkrufmz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpmljjs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdbskr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhiizyx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2amnfffxm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjigulr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sziazylz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxzbdvr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqixrwe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdcbrja.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsxwjtc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lektaehf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mbizabwg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcyohxw.html


<!-- 参考信息 -->