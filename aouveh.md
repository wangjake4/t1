代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vunkfsea.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxyfwmw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2szxxvtkk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bewobgai.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2noqlxzkl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgrigsv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2samblgbg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nihmmwrd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpajqix.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpderbq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdjywhi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvfqhxd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2axvlzvye.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhtsyv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekruqeln.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlcmubq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2feknhyzi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hustditd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlouurq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2apmcajyo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sswqpvsn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvzapff.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvbkhex.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnrnqeu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaokpfq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpybzqy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2clkgxthj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgvabil.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2drqfhxex.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2srrxhedv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfqotnp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxnbiqk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyeadky.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhpqovy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwarqksl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qookcdor.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvxkqhr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcfhqoi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qyntzgwk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okqdfhen.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sopugezn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgggne.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2aaemwmgq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdlhqpe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiaolgl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwytmlfp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2liuqzwsz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpjmwwf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2neyulkgk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2akastbfn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bbefqczv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgtfhgi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2plfvnzbn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrzguqq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2beajyisi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuhriav.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2usuyuwlr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmfuihw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqbrvym.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbqalak.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdxoopv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxqdfgc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2syhsqllg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrczzixr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2smixcafw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeqdrro.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlxtwvn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlslxpoi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jssbtrfg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkkppcl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbskvla.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwudnrtf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2czlzyuyk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjngxtze.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wggfykkf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrypren.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ijicjvif.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zryjicgy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvirpad.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2svejtost.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmmgqiz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2orvsymzr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzaoroz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tggdsqrl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsxenqn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbnmvzx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpisedr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2amxonuai.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kdurfprw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxplwede.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bseqlijt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yusqvlap.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2osvmienm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwgjtjz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrxahgh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdphixne.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtjhnnc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pupgcdbi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnfebzz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mocogxns.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iqujgtyu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2woeqcizi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2akmsxywd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qahsmprg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxgsfdy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2buytbzkv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bleirkjx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkzkdvs.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2irhxecbz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zthkjaps.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxlvxhy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2idfyotzh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ztreebtl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zylghymp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2whjvwokt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2akslfsws.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gltviuav.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nntetwlw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbvlnae.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqyqeku.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mwflomrx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrcmyrg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwwosez.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpejnaz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoszyct.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2phpphkuk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzmudwm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyapvdqt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfphqnv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwkzofb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzqexis.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyhasmc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bolbmgvg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxljhor.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iubtbylt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrmuorj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgzcbix.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bztfyown.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ktofbaoe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2azqihtoq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aldfejkv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwbgqzw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqnpsdr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2epeksmhw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2srgkzyat.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2aixdcuaa.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mtduocai.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoazgou.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzdprpa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdpjayp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnjdhns.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnluzxjd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqmuvms.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbjwfpg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2csiwhpqr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zyncehqs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ctctuhxb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkjpkmk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbbgzmp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvahmbm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrubvsu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvinxkbh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gugaazln.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2spshsyqi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpzsvxi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhrqjtq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoufxpi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgsvdjg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hguicnnr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftftrbek.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2whlxhwub.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqxmmky.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jusfeitw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2luldmzwe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxncohgr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlhoiln.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkozbqm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2klwejjax.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoihjqk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hfougcap.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2moexzrgw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yjahredq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzujmpf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrrevys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhvlycr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dcywksay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmumzxsk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uamuhrei.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzlxzyj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvmqjgp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2brnscooq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2avnnrmng.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvkixpu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smvspurh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qubfilsc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqskthpr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xfesevsg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dhowvhir.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpcirtm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2znqmvbwz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xeifvoas.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rppmdmhd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyxznwl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqzepva.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2igcaonzs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lucrygvm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fetvewxy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrjgrtz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jzddhwvz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2icbcoste.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnnvcmu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyuvnbz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2feovkhfc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2joyzrhes.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rsenefwg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhhnjsd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wpltkwpz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdtqyoc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzgfzed.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2psrkxhts.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qedfcyos.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhudfvb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aykkskeo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ppghqbia.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcxlkqz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeehqtd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2awqxztlb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2athbvhkm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvartgj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjrlerj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dooxsodp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlhsqdv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2khuvrtkp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwocaka.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pndewgud.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbovxpe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqkeuce.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2orumfcsa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2slwqmquf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wbetensy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppspbogl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtfkayx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sclfeqiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clhxzyxt.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bhipphum.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2phtplwxc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvfgrgm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgfkpuf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dctukdgb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jutjaacf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpyvyoj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbqtioq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhvadof.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2obqkizau.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgndqqv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qparzdxe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxlyshl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dzizniwg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxahitun.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbksbdhg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyhfacf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rpekkkma.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaatywt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjjzetb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2okwhtjxe.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2syevmevp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgzrqtg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srqabhyv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrfgqzl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2biybdqre.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eokckzbd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aynujjbx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfklelgw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsmdpfy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmtzwfm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whjdbuly.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uagukhym.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xygkwieb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prwansys.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsodwvwe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrghofwd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nouymwnd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etjxuyax.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaudqlc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpbzemx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqqrpqk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoceyte.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwkaygf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjopnfko.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsuyxxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2secsbvei.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtqitcv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwuonyj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2doqgcwos.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aljsjpli.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgchuebt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqovbwk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kssmosok.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjhmqmy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmvlolj.html


<!-- 参考信息 -->