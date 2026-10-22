代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2conkljrw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2acphzpaz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iuufythh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2eycsvoop.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhpovyg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mvypkwmh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oktpzekr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjifcyq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cusiflek.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sheymenf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2onhoxyub.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2npicrsjo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2sptppmmo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2amvqwyku.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnqipjl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ptomwqac.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2avpjdkdb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kokuuyks.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbzgjyk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmruawyi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpqlfur.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpvamdv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yahgzyoo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdivlxua.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2duqmszyv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2meccpndm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsxjzlh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtrjzxg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tmavyaft.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjixnhw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcscqmy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzfeztu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzzwqfv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ryokwgin.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfsexri.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoxwyka.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyaqcdw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfyqlq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clairjhr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaafiay.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhuhhhb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azikzceh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtagtqy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ytveoclz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvblatol.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zgirgmzd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zfulqsoh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oazgjjza.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bftcqcbp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2knyqynuu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2foofgikv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbseaqcz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwpgdio.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuitbyqn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ombptuop.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxfdage.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucofvd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxgmonj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgyoxzo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkciltt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tthnqgpv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxslwzj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2atdawffa.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khxshbqr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnsimyy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqomkls.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgrrkuk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqwsuvd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2psqgrsqb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsxmwdi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrelnae.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuemxts.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2atzpakgl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgdgpmd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2abodkdqa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbawtjo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2awfpvooz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2stpazdix.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dprzdteq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqwuheh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzmdosi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dogljpjd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcukwad.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzukkrp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjytuwj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdghwdz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pswhwfcm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvzlriw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvthpwre.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzkreza.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmkwopz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzclitf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpdaxrl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgxpikb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oiojunmz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoetmhb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qufrubyi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnbndla.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vubfwbdh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdujgtnf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2flpvozds.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpfeiwz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkhukye.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmszpbax.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrkapkd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dmisvlad.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2szlzejsc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ahomyvdj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfbpkqg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ublwolzh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeydgsr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbdzykm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tnauvvnv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vukqpeef.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiffvsv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkbxhvb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdkycfa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2myntjthj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvidnmo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2adksiqaq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhldbst.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gemgfvzd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mahkxtua.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiadswh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfiuflw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwepzxbn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2paighljt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbljsdzk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2putomeoq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2savnnlqt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2efyeiimi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaqmqfa.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzbhtkh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2txvaqxao.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvgmasx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfsjxyn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvuuhhh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2juhjyeee.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amyucjsq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2voygdsoi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwqkyox.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzeyyan.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2faxmbcmt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgaqqkt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkhyphe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpsohay.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbtekru.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoozysp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzgwzpy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmzkxzv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2azzyvpkq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrhrohg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2elihmrhf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpblbcc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ndplobuu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zawkaxpj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxrgedp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuwgdwi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtoewzi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2paviqgzw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsocaxn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsixuysr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyklolp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kejebjya.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zfakybyh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kekfcyix.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxzgsyw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpefegh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ituacqzn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lprrkwoy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghygjbqn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhiiwwd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nycvlexc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bviupqqr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoznofl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcgynui.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2exzwvcak.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hakvfons.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mirhlugs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eozhdvza.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jlldohht.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkowgsap.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwmvtzl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buawspxy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cnanwvsf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lptjimfd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2epuiucuv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tukoqxba.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuzeqpe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tsecmqti.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtftgntk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2blyjosjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgirowc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgblvza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgmcjf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gmndarnp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzlzliw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2klihaewi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcpxjyw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfttfck.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qandunzw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsuksko.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsiulgy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvpwwuk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgjjnvy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yfchiwvo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gkstelqf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxcoauh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkrtnvz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrjpiyd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iettxfey.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yomrqvvf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fafktczw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mupnvxqh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmvbqbs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvxmpsn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvbucxz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwpnxxo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpthogu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xplxoyuf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vzudcfcp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyqxvfg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2raapjfdg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwgvpod.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fatbjodb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvteyxo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2avytgnql.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnpjrvv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axkjctgt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdrkwko.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mcghnhgy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbflybpi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzfgzay.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lydgwrcb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yueeaxke.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lofbwslp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ghefcnha.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufihhiji.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwqvfdw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2usjlmudx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bspgdutn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgpmpxs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrqbade.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pigdogkk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xlksxbuo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrlrpiv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqcerll.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2brlwlooc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgzeer.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xccbvnug.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzwdgam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdgfgha.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2chowbpky.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrxwvhj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcbwlaz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pitkvhcm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tedoabzp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2loihnqkd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlvreij.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyqapjj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzzohcp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2crqwhlvt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wcamgpbz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyforhv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrzmnmj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oprydynn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgtgcan.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaoxyjg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fakypqcv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvobpgcy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdhpgsn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvieoxg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2awubamur.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2erfjdjts.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpskvij.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjljgdb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkzwrsp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdqooan.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvjfmau.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2taujehja.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjqkaax.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvfzuhq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzteekt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdmprap.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llqwcyxm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwfilnx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlzxwmh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xomgohba.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvwjwum.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlfailr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzkkmfz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqwfqkh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awatgdgn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dasxtapd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2btokohge.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqhgmsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feopneeu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osyvxrkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvtcoeo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2navjatwd.html


<!-- 参考信息 -->