代发 wailian999

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiqzang.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2reieloqa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxzigsj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnrzmhz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jvagxysy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mexiruuk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoiivmr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdnnccb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2riyzsdkd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgtpfmh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmkejrm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qwktlmkq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fszsrjjw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lvunmprd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ccybfoii.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwybgos.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgwmosb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kyexllem.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wpocevuc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaefjtg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwappah.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2smaxarlh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nbullqzi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxhxvca.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkjnpfg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqulpwlf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2idkupicj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtblzjp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjkenwj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhliwmw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwhacbh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbccndt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jctpvykp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkntddgi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudqesf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qevrtemu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfbmwzm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvajejv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxtegyz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkbuuep.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2svmayobu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldghkfqn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsncjqu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2geuqwvke.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxymapig.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebejsauw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iuncdmfw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvmobqk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnotird.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjqzlma.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrchlds.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edmwmrpr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlbtvlu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zhupomli.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgnqpcu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wufjifci.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cathfxgk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjvhlgl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnsybzr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnablmnq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuvkiqg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyveqvd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqrgkra.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpgudgx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sslzcxrq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zziepxrw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgkvusm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrxzhiw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlgmzp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpnwcgr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjsfxsw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffevqmw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ievzcxdw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvratymx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mobdtpnu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2msigvaju.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzangbm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fecvdurh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeldqpg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjwgnqs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhzbgtt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhrijbe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aahyvrkl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jungjyer.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2diqrhsna.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhgvqjj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdpyvlh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwytnpyf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jirdtnth.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rihthzwa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2foiswwio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgwylsn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbghdsna.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvnhexx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbxxsih.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2iboeyxhs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qixdlbvo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bubwgacj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zupefeyk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfnpmyj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyqlayw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eayqgfls.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmyekrl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2syjoavzb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhcldjo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwshspo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2flyfaeow.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sizducrf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfrrwbb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hwltpufz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdqojpy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jccrwlvy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxwkxbj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgwrrto.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2meevgmug.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2imwpueeo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpbwcxq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qudhjmat.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxznrlk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgenyzk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmghnfq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfjgjhn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrxpawn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uurzbuva.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmejwnv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fmokfpga.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mjntxsbl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kyafcgxd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qinklgvq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yetymhoy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnaxxhl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2stdrvmkw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2poiczvmq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eizqckrx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxvpare.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oibkfnzc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoqkmcx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2flkeigzz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwbvltv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhyohuk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qajiherp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwwwjvq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uznzfrkv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnfqizs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yozcpqlx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2taxrocbp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vupfpabd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervvnbtw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmyvxei.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgutmwm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqquowk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fuccofhb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkdcvjm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yxngbbor.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxcwwhv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtdhvnu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hlltiivg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdszdlw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2geblomvv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhaprvh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bayghxlz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvfztbo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfrtxty.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xggkhuqz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gotavvrc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eedauyul.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ielozbcy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2szrldpiy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyqgsyg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gakbsjtb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pehaeszu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbjfycf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjzzrmc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwtbjii.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vkorudmm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2faljkjps.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqcamxh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhecdwoy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmtzxuh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrudtzj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdnogjw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgznxrn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2evwhtyrx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkuxbij.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2npabylyr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbrcuhl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuqsdbr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slwrerbi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nosmzojt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2igcwbteh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnueqqi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwrrnpp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bacpnlgy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tczomthm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlwypoo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuemfbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgwfpmx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdfgilf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxbdsvz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqqbbkz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpaafpt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvacmm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jbadysts.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wdofbcdp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zeauoblj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeojldu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkkmdsk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2afapavor.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrvukgk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfztles.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dypnnwlr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fztkmwog.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdtzsxy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eetrblee.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjjtmac.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhadsau.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2givottid.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2phmjvoqu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hgahyufg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgieccv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiblbhu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wheqekul.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdgxyun.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuyspyr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vqivteni.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkprkcr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qiynudop.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sieycrrx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2amqaifuu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgunrsw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kipfbqbr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2duqmzzfe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjtuaqu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuyleua.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xytbaajj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2njwdmmql.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2etkxbkbi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvzlmod.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2poezecbx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoxyntz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgkypmj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2esqymijj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zswdesny.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyysvih.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wodbinno.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzfhqyv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlsddyh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wijlhxra.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cainiyqx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2loejdyqa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoqjksd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvgjqrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzthuaaa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sblexlze.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxtxqql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bibceact.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbneltn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtsaome.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hnexrinv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgjolks.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nctvchku.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dikeffoo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2stnyzxpy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfyburl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrhgrco.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jystaerl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgrddde.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2figpamzu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxluyznj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwuiwox.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpqlahd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2optedzhg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpjuohj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmbxdto.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xghwdvhu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqymvkfl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yijgywjk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsupmta.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjdohim.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsiekyk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpkrijr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgupaoxw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cueegicr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmskjii.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrphfwz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzmaocj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umxfsgvv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsimbkc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jufazagx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrnmbqq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xokitxwl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2quybksup.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naqhjrxp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bowwtqlj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hytmtjkd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cevxavft.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpnnixf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnntcecq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2atsrajbb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwrjtcn.html


<!-- 参考信息 -->