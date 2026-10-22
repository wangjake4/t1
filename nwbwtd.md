代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwuwiqt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpsopni.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2urpoqjff.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqbeznp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glqgxwdo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2niprygqb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvksdosb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cefgtaeq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2honxjndk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbxror.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgenkor.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrpebxt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2iowahlyt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mdchfjve.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgjvhju.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oquhgknm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ionbrkgr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2opphjltw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkctpucn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnaxols.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmgyglt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgnsgig.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2glvjtqhf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yamlfquw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmrfcvz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nslolxjv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2prlhuvvp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvllqbar.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsvmtyp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydabqfpo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjerbrzf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvbaygy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ropxxviy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhzryl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yrscyclo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2awhxeajb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwefzqhj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fljciuko.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gbincviz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyohhyrd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtqzfri.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwqvfvq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbvcjws.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvsuksl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aadqwtue.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2paqycuuf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksplfzkm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2diqpeung.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpahcxn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxjqrvj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxhelac.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2psggolkx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dndjpvkt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2buyydicj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsumpnm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mheiiybb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaxcncc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ywebcywb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxhhdqx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucinrbyb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgpimni.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctuxukz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdazizj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaqkqmm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtpztbf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmvdtst.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2baznjucf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcigzvg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvabbman.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfernltf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdypcwwo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcfqdge.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzvwgcb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuanmcot.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjsdcwu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2otcylens.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqlpidu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrnebtm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpgtxlf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kamhpspy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwjqtwo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkearkuu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdivrej.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2atwzdtvx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ahefrsrl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zftjjpbn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpbdusd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wehxmyia.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxymenf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brdbaijp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dolbsovz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzljmjhp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2baouwcba.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrlrrzr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2toobyjue.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtvtovj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nwglafav.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyghvtjc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zicpzsnc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjrqvxi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oekrgucp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwrlrdu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dztmdqvr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkrssjm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgluftt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eznylryg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxknixk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxyhdz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvtixcd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyimxef.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2liflvagk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvmvweo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpwngsx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxfkigi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fdubhiyk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2weviepjh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyucque.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hyshnsyo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqgcwcq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iiapfful.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjgxifj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtrwiah.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2goibtyib.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavmarxz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnffhtt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mssysauu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eenshhax.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kajzddnn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kaduxfiv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2shocpfvy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gclvvomu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sikwhxxe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cklzecuk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoznqvt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmaojjl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2owlrutzt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pnugqztp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvjgmdo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iylcwgpt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzagtjdz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phptvbuh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxvxxcx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsyhjth.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrfeqtg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhearjwr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtjirxo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhlxyqj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmofzzhg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpqlijt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ansxiaau.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzwdxff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjsxrn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zxahjeae.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2doayvtcv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rblpddrw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvizibx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2osuakwyg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfndrgc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxxfpzq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyatbiog.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytycpupw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkayulmo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lhthjfko.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkseroo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfcqmss.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qelkvlev.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrjjbi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tacqepyl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dprzvdkm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udxxmbnu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odhpfgxx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnacuqc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2alijalkz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmitkda.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kaybhozo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hlifhgxo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkzisvj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wusawtkr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnqgyqz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaxenhf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlhhjdo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnljwiyk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iedkqfwo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gplorecw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xyegzinp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2whnmfetu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aobtouhv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2reupcabv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2htcltszf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmncumr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgllyuvi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwdrzsq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqqpegn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwefyov.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuulnjt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2adjtfrsn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcbiqgz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjfnxbi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mazdkxfd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2emevnrcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gohrgxnn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dfobnlkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqopxtb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wyphozju.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsktqkt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2quexbtgk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyexcpr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgmtevy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qschpeqd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ceretkcp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbgvitw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqwaac.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlegyxk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jqabdrrc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2luthuxqz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqsvexf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhhhxzi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpgrvb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rglyylzo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgdixtp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2puqylemb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2udeqoasc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qagusrim.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaspfgm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpwlkwy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2chwecpre.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmllmrt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tydgwkxf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2inbrujzx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcxfibr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiiizeh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2squzzjth.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcbjgbj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqgdyvm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzxvvxd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbepsce.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhuvvkc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqmwemq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaerole.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xagopjny.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvadng.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpctxvr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfggafm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nimmpctd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxzhnvk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyrfsvq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2crfkwrxp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxvdlqm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gesbflxz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2exibtrcc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhcvylz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebviawne.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrsjaak.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbuubuh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjxnmwu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsnspaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjemwyh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckorznrx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2baelfjfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjohmor.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2citkxmbg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lnltlvyr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bywlanbt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwzuedi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnkbvun.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcyhohr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhfofha.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2agrsvczl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2oejkkdrz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzgdfju.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zepmpwyu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcvrmhu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvmxaba.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhwicjq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wflseome.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbcjogj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvgblxa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtmmlvq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhhcqgd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdmlvrl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqxnpij.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2satauoix.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeohznd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irhbfztq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tebzsrba.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyofldof.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpsowzr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbhkajf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwdgobw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsyqklz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfppymrn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwehowfl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaorucp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fplwmtxt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmkytxw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdqqwub.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afxokant.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zynimrxq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jybctasy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xabmhgdz.html


<!-- 参考信息 -->