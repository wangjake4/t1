代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ovspkqrk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xycmvhqd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyqzgzo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbykdqh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdtjmao.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnmbhj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2upjvmred.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfllohg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wntodkob.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpnjxbh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnjauqe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqegaxab.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gllbvomk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2umcxactv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oeodebbv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zdovxquo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iatjzbju.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjjeypl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwtqlsv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwajfqku.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyqggeh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcutvvnq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxzwsdw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdwyhpw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2skqfwmpu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiokrqc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vihmpnxo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2udlgigwm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jusgyete.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2csaouupc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzuhpfl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfmespb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkkyvio.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaxvlbw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2slxnehqf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2azxoibfr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjdxqeg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lovnjuix.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcyolen.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xomvhfwz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beoukbdu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbvrriy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oybbhfdp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wowbzgmy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gfamkfbs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ubktukwq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibolacyx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiviiahx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrwjcib.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jchillpq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2twlsgyyr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smfgbodn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yigrucsi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2onwzbfqk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvqrbvz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaocphbi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hjljchno.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoavngq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtkttum.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfxmqoc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2btbanbjn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuosxzo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gftcxevo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhsabmq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yadnmgoh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bepjaknl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfubmff.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2unbgqgfs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdamnak.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvafopuk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwmslgc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiadwdi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqmnxch.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcyfnfr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwqsdhw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrhvtzq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiruyuw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2btwraqiu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcsesva.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rowllafv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiqccua.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwynbbyg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkzxevg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsvkrao.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nswjpvyz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxyfej.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbmjhzh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pasotpnr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdbqoqy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfbzrew.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwhytqb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ednkoyuj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gubjttnh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjvbqor.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zeppmagv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxqdmet.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rphxtltx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtnmtqz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qilabsdj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwqmvbi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtldglr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqaaofg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2irohohwk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fthhviqo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvjqmwg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdsasvq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2byjphjrg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rktzbwtb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwekobq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsbgeer.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2crdduxot.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmwtxvq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjpqyyu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkdjgcf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdduida.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhodqkt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaepmcs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkxdwph.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bquwoacp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvniwshm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwrbdjk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwmnknv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtyaezd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvgwolw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrxaupl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfkpeqg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mycpsxbk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpwzgrr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tvviurtn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbkkhft.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2spakstus.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsnlugy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiemvrx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpfpufd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sldesjse.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjhvipm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krfltbzd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmvella.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unpruebn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hughevek.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vgumtvub.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xefzbgmc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwymjfa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzqcjnn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjornur.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfbaniy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2umlaqgbi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sylqushj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxqpkwz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jeegppwo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zoembdog.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftndkpon.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2szzdkxbc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2scppgeyt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxjmlzk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnowryiw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpzfnpj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hstxgeju.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qoirdybp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lksmxgwu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tsebbemd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2houbqkpp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqsxwwr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jitqqfir.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnhtlil.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhurpsu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2scgybuud.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqdybwo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kziguliv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkeydra.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhxskvn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuyhfma.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdyldoz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfbmmrf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2isgnpars.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoejxxw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuhbmqr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2papzcvql.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdlcqlg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvbcqwh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrfqrsp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxnixff.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeesvkjc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnjkbmu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gztzkxjo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2azwnskhs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgeqmvz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lettvxzy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pftyymie.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zomzfchl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2swcqgzxz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrkohnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuszhaz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wusjqwra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvidfj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bajljqci.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyljlmx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrbnaqq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2monhalud.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rluukrho.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2brzncudp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ivayfjtr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyvtvog.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xexanqie.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qosqzlke.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kgczrwzs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwrzpti.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdlmrjw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kyugjjyx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkvhcif.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mswvwjqk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxqjdua.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2epeiakqp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjiantr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqfmgqu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkdivul.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ailrnwue.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2maapuntm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bhczvzxb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bryvtife.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiigerw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjfrdcn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrhbaif.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2itndfzyf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqcpglj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfcnlza.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dazcljgx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cneuoasp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdpyoqc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tkphyejq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2munietwf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zyopqwbx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrqdbqi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ytarmlbh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oehkbgan.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jykgothq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwqbesx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utxcmlvd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jweoboxb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjytpiyg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwoiwwb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oigrzjsk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfxyfri.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2swqerxln.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlmbaoe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuuqqgu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjvbwku.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2exkaqpth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2comczhhn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwchjzhn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgyojur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cadepqvu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfzmbct.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwtffkt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2sqibrozz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpjsofw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yojrtmmp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlezzom.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbtcskm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2amukiipl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2srgzpvxz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2idghvmia.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhfhybo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2axnuejcm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lclrvmwd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgdrmbq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxznmeqo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtaqekk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mweeiscj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2disyuein.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ezohdlub.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzqgnwq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kutrqgtd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwcftec.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlgusue.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkowvms.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjujqxrd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jphuemxs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnacbhwl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mghfabta.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stlixbcq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkfupho.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhecjuho.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcutnvhd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyyxmzw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbppwbta.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfhlwjq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuzzkgk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzngjyde.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcirjhu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foaudegr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emujbpqn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnltguzm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clhsfrin.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kplsrnvu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzztaonn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyzkskw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtmtejo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oawfwrrv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoxcmcc.html


<!-- 参考信息 -->