代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kouftxsh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hktanlzd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbkpceq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophjwxza.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2edcmpcnc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhohkcc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfxmzhb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fadkmsck.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nygrwgyp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhuzbrt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vaujexcx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2proamyqo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrcestl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeojule.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnnvfip.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgpzayi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wztvfafo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpsjtmy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfgtkpq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoxqquy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2szevfaps.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2auypdnrk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaxwset.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2biruksoe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaueaua.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2valomfuf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjhtlaa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfecvhm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hngjjswq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmavxmj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyujcevu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkutyns.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqfepmd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kikbvufd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzpvmjw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvjyepk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odfghgia.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkbglvz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqkhlzv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ethmtebw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gonwtnxl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yocfvwnv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjwodse.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izhvygeq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfqbefv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybgamtt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrywmhad.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuftgjau.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ythrnajj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kksuwlbq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcyducn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2emzvispr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhojity.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2albtlibu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aswbhtip.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbsxrxs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdaduce.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2acdekgyk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwtlbqs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqucspok.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovesamgt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2efgonjsp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lzauxjxe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2natjgaes.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tptwmucn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxndztx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2upqhqgvr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjzdtoy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wuefaekc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmizxhtf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pidtxcny.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsnhyww.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgrsvkg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyzgyqe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2driaayrk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjxcfpl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpzroka.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpifitx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cotdsxeq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxahife.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fgipodsp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2orqsjgha.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbebsyna.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgglfuhh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwetofkf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyoript.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krpugcao.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzocvku.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcncxhn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgospkfg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hafuogdd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbabinqu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkuingz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuyijae.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzvaqiv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmkfcve.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbufego.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zujxszko.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkrbdoc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xviegswb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yzixyfgk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2oibahjbc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2slntbhdp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gudjkkgb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2axrrsbat.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmaduvz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2auexsxno.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2abbtzzai.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwjlhfn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvguelg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjbnbqv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfgkpkm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uevcyriw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhnrlvh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nvovsazy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzqjhwb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tudkpfnd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jywvahgd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzftlgy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2snowqbed.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mczxnmdv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gttjpsas.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2obhibiiy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2atijxojj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xewbnbrf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiehrdb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrtrllg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nftijnon.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apamwrrv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2crikkxzh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qopslfxu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnslcwmq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bybqlvpc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmawbba.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkgvsfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuxvwok.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhljwfm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nswcmxxl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsvqasj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiqmxmz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ealphnqq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgysywiw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2smdkayve.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gemnfrqd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wruuztvr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2etlxfvtd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtflnfd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvdzqwy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qagviypv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2duabqfqr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cirtattx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizmemd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2twtdteng.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gimpxusd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dthglogg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2szddbewg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkjmnym.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpdtkio.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtieplpj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkxswlt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaiuava.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssjeqht.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeadpof.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gydchedo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jqblxeoh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcmlhcs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fopicnod.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tubakdvo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2leutrrbr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjykhqsc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcezlyp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdgdukz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsespwq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfwozgd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrfgudr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwxhdkr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egwnangk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuhqvtc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgrtijr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qnswalbg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxmnijk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxtqjve.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkstzup.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gpicktjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlxmnwe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hltpaljy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzefigri.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pqljzkwu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuzddok.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kosdnwhe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2znphdpay.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxqncpf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2adnwvmrw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hopotwjn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhleanw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsxvhxr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcghjee.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkuosqh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbuiyfd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vtolvqfe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2klgnvgor.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2llwmnkis.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhcdzki.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hkordist.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cljchnfr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pinxivcx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2unavzlde.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gptvdadl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfwlbmx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2macjkfhp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuhkkgc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2paismeqd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qldkkysc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiffvxn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtktroz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlyulhc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzdkqbq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqgtxtw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tvomwbqt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kojjpahq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsobieu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfpxuoy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrlsozu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aaevvzec.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zywnmpwd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwywyon.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcyqtbf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxmmvcg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2thjxqefe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdsjtbx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaoxmyu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2otatfxxa.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2nombezjj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2brvumqbb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2saquwgpn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqimvog.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrthrm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdojghy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmghiygj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuwiwmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2woxvaikv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnkdmnn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2plvslhkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpcrczz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2inqohcqp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wajureqk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwbqcwm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrlwbfm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dixglxdc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiqpuna.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vakpjclv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtpkviw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxdjvvy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2djdazudr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdslpcw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bobjjrtu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjvybpp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cftpuisz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yagqglqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmbmsxa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qicqptyi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgenzssg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfrprku.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2niwwhvzr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbmejaj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcfyqcu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2guxpzrty.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbydzlar.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsggisr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hodaqgel.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qptmglav.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxjjibe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbnjnhf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeyxsis.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxybxmxg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qccwvbwg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtkvsis.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqryhao.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yupgaxzx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoogrjs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwkkgtm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkxgbqx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdedzqlf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtotdagt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aorqebxx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgvmwcx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oigumbmi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oggttrbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hapigntp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smkgvzvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hawsgmxg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgjrrtn.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiilmie.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnfsbnj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvfgbsp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nurdblel.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnkcpvj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvakwslu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqoxzgs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvufgwi.html


<!-- 参考信息 -->