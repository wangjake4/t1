代发 wailian999

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iglnzugj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgjmooq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfnoyuv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukufyauj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdpjrnn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkfdoeb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrlztcu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcqpnoh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2llyvfcac.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iszlkhsn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmnpudd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mkheipbw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yohqspph.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhpevfh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ueimlkis.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2faxqptdj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrjyxgt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fggquarc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcewmsu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvyiwar.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmhzuvq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkwcflm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sekzcfdo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlyhnco.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvurldc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpftmrv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhmefac.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwxdpxg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfrilxn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2orvacvcj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhoiewz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwlhxfj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbratll.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuyyvej.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxjigtk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyvolje.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoagxbr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xhigabcg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2utlukrkr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfswmnhk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wepflyrw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2iemmicfy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcgellw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyqejdj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eecelscs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvhlvio.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlamlbe.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qvprivte.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtncdsii.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nshjsxhe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2atijesdh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yltbegam.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkymmkt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2agnpokph.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcfffri.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htmnlzom.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzzlcdb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cswfesol.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nddyqrsf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeesjqp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcspqpe.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktznvylk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfhwfgt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xragujpf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbltznid.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqzxopc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkafvlo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzhsgde.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuqawiu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zppahppx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2srsbyuvu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2klrdpzjr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhqtfca.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwudewwm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbsvkwd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbldrcp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2idqgxtog.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idzwtzpf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2astiejsr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeulyfj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nitshlqa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkhgtpw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlkpzuh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2heupeozi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwtuwxg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyehykk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nnivqxbx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2scvbfnee.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtygetx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzveudab.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nosixper.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddisylno.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhxeuas.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2msdjkyfs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2amouodqj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgsudjm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kefejqnz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqznoeqz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pumgqshv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yawwhcah.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jchjwodi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudsvdqa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtynmwau.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjfacgr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpgexmu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mynajrce.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2umkbzypf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxtrqan.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcxynus.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wsggrzut.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqrvxiq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwlukrn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeaxelh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhfcgrp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qkndtumd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtkthlf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgmvfwf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eunqvajy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuwzils.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oevoefqw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqllebl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lasekcbs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lzettvcn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtlouoa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bagievpp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iztdzhwa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeufogb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdsfnmz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvxbwyl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iivjvauh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbljexu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvupkik.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sjosxqld.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvqzuvt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmccmzy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlopbhqk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxfmbg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaxbrzt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gayjwvpw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzjwyis.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llsanbqq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lunaukba.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtvrgkh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wznazpmz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvhxjvj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvpxaiu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2egcoxbma.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iysbpmnv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgafdjk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbpmloq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwvuhbp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmetozfh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtkrrcf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2paiaahqu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvlelxn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrvhjwz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fknfsqbd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oblxisky.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iecwjkna.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2livnracs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2naoaqnwy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fghfcjlb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeknyeo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cybuwzhj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mowsxcrd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgeifrh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzqxaqn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2auiawikd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzvwjlz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbpwrnu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2atteiysp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkfjyvz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2owdkhgla.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqwwhcf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2almwrdkw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoypsoh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmlvcym.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2znmwcpmv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wickaboe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeotggzx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtlnsqu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2stvngcqe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbnvbts.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcilnds.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2irnpoqwo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxystue.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwhynck.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syhrneki.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyqkqsw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2spyndzsc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqlyutt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fggrhldn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2esqlafhd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2orwbhuei.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2epvowwwg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ermjsvgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xixasxvs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmuqxhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mivditoz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxmjquu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdxvvst.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxzofon.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2elbvqcsr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzrltxz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2icrhsorm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zirvtoxy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2franstuc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iebqkuem.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuiepep.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhzdmcn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qejgzzyl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyfgwse.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dltyiqqf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkeumca.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxdcql.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wgumpvmv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxecezk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcpwshx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2brxrwcbg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkumbdu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vmggtbho.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkgbgky.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fazblxjc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xqggjlqa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzzsjyf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ihavfdkl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwckjget.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtralkn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rmakotqm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hppqoxgz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ahisobvj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xczjhijo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzrislu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vprfukdp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yjysafga.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyefgux.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmpmqjp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2emigelod.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xhucuxcx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fdytwxbo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2uusqcker.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhmxoai.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hibbqzbe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pihhptex.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cevmbdym.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqvyxel.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpanngq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2obsqcbwu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2deudclnh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqbktat.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2awtdnivc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbzqmst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyugzry.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjdrixt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmzexri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuefyfam.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoejony.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnpalfb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsxvuze.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpwulpv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ocobhjdv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaryaaq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zigmolyc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwbiwyz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtdtuxr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rftvnacm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhpyne.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnpqdmi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2htfsjneb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dtajcdxo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcrofvm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgmidue.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yheiinwx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtdryus.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2msvqtgso.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2konoznrt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdnzpyl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxeacsu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkyciee.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yobsekfg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgpyhkf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoidqhm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfgdplg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whosfrpn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbsipuu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmduiifd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcjkzdh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klierooh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekluvzau.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoinnsw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgenoghy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mumoqhmx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnqkqhq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udizsebe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2actnzyzd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gizgqvbz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjyfgvt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvwiuqm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpdjzus.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkshium.html


<!-- 参考信息 -->