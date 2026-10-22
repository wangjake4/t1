代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pinreiqy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlqxlmt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwjvjqr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjinsqq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2awdvfdef.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsduszx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuqdizc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nbojfqal.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkqglyp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwcoyoz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqzniig.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnuvxxd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2awwdruuz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzswowfy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkixhmb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2misobzms.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qaflklyp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqorued.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2idxaxbnt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcqfucz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnldefu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rktropdy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwaxjko.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecloeskj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xktrakrn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jguilwvw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kihekvqf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnvhqth.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrruypu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kztiqjbi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nydqdrci.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwrkynj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsajvad.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgfleng.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjzitnq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tehymtnz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhqlekx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2eozgiewr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qjogrdff.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrquzymz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqbsjzf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmgktfc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyurumf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbloxwfu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvcrztd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2haecrilf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pygucdkw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2spkfvjib.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgvqlgg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeeswrt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcefntsw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgqybnf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbjnfdu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2serykgmd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrqperj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocobsxkn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvucfumg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zecornxu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjfllhn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggthdvqj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgokdkv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqytuqia.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2imewhqah.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhvpius.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtimoap.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhilxwoo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cevvwqso.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxzgzoe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrpyxvb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2llhcsuqz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btqljtyv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpujbqkx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ickdxnfj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqglthdo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wkycuwna.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hybzewhb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxocqpn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwlzipc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qetnzojk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsmrucw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tozbzceu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcxvrae.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhtkyn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtzwbsu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgddfcn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xargkyxt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmqppyo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sojbprgf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2omapncxs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfvqsck.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfszqay.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcublwru.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iczeaiyc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mucmvomb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzudrce.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbmckiv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vidkqtqy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpspomu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhhtbgw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgahqrh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rynacwkh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ssudwhak.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqktlu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpgnrbo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wguwgxcu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvujxxu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bexampii.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2irqoanxm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjdlryj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqrgyel.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdhfoxd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhdnbdm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pmazuyuq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwqvorq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cghrgfgo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbpqybi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahufavhy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxydpfzb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rimpbhun.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiznqxol.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfesiov.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2arecbesa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcsslza.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tepvlcia.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecihdeyh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2altckyis.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wswrlqvd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgaslyc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeuaubr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cicuwrzb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuiglxl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvzarvj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyfjddv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fytowvtm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdxxqkb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uopfgftc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyxraby.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2miezfrbc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hpylqwwg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uskihnvv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2alcpthfz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rbucxiyl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrmcaoa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvioajpn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kciffqnn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrjwltz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rpteofwv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqappqkj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2czooagad.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxvjyxw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvheldz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwxitqn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqswfpg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mteqyube.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oohpjnro.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nemdctvw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqbffzc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhuqdmc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qciqgrso.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vokqscpj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ormrbjaa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sldhtkpe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gvptgfgm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnjwpcl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lshbdekt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkezxnnk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2znxtebkd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ighgnmlo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzyjvpt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ximjilco.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uycbidyv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyidwzta.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyhfjsc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uckkmcgy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlivsot.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwuzheu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2famqpdjw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgzgggj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmxizjd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2eesvgmkr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2atgmdnll.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bqefvmik.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxxuupg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dbanculb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eajskdvp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2afeeqcri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grrlnbqo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsmwrlb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hulopcrt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsmydth.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmkedfn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuryqtu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uagandcp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcehpmk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yksgwkww.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bibvefok.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuoezgk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkpznfl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cenjvscd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gaujoxwe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqgxaoi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2chpekevl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vftdyjsx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eytyojyk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrgvopc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzufsui.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjvmqpn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2thetibxp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqckqpa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpnzoja.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2etkcclgc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dcitmmzc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhhiten.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdlwcwi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmephhm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vqemlpuc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnvgrsl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uhentfks.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzofnuad.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2btahnsid.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjpyigb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgbacsl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmhwtou.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhrjicd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoptnmk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gexjtupv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2acosgclk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rprlmshz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfqhbrb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obdrceno.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpoeloa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvfaqkn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2teorrvih.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dtczuhcg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjzbjyt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkffodp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ushqrfne.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sbetjmgb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvamjkbc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rszqieeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwnquaf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2obvjigve.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmxijzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaorgvs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxzuax.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2orkrpdrl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2afnuqwkb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eybspotm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvdqizz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqafsbi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iaejuxbj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfrrveg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmamxvr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjlzemz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2keufagbz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnetwkdm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2syhfqeep.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzzaszr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2evrloynz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuvmidf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2otabtkwv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zftfdoxk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rownlyei.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2egzktzih.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjmclxc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2sbklylnt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zusonyru.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huippgwr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2laznembl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msmwmame.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhhslti.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byxqthau.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yclhubqc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoulcux.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srmbojpu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swcfmkjw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zamofmcp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxcsfna.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgdwfyi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxivtxx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcvarqg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnfofxm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkozgbu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxkixqv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnoxwbu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bygrxfek.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtrblus.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzriwla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2furlhnza.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzrigtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmezbad.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxffapay.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwqaqhw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2seydirpu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbhrzax.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrfivtk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xodqlshj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmvnckb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hngmgjnx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsxrwgy.html


<!-- 参考信息 -->