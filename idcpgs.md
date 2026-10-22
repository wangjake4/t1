代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbkqee.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxshowjt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxqnrzr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yekvrocs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmjtcsz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlbgkqy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ypknxmne.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhkyzqc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mrprpjsv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhvliwz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebovfnwt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjspmbfw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeibsat.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvwcair.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sogxlwmt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2declobvy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2geyeiaot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoxumah.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgoiosn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkwkjqg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcmudrr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2clnufajp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjnimwg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2doeobglz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpafnzc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sbznjylv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsebsqo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rokdqfeb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvpouil.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktlqkjz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2udhaosvk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqshyedl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkpjajw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbahweul.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcktcpex.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkulkcc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozirqybo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbklhsa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qymgeimg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwntvni.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxrtzyv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2upvuggko.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxunplz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgsxsmi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2serkaoaf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kklltoxy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knfbmrpc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2maxvtcqp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yblqlqrn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxfikdb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxhpdag.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2afxvzlpw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnhvfbo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpkvkay.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrdgwwy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xljqiqyk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egplqubn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qifcovwb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2byntiqsx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2raudjvtd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2proirotb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqffuko.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uiblaxfc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvihlfbn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aykuarjs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzyqjfa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxyfnpg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzccyvc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtrkwpz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlreakt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjpttoh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsooysv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ytennwrv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvpxkiv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bggcrrue.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqorvxnl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oigkgyvn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhaaqme.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xqosapsu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dykphktn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fllsspfd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrrhoei.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvpfqlg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yumfvhuw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bkneuqal.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbtgtsp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ekouelve.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2foqqupmc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eeogpvph.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaaocch.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rizhrwek.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uulrsajh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mksrvgei.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jwluwhjc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gpytojne.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywefqthk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrughml.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkkbepr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbvddca.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqaddyd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqwxca.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tarozecp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hndzktif.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoiifbo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdplbwo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2blhxstpn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqddgkt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2znbsdfsb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqdaerl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xiywqukr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjnyjmp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pifnoqiq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxvyblr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2irobmowp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhhycas.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoddyeo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzufddbj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2oblpiuxs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjwagf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvleqgw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvqbbux.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrsoauk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ognxixrw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcczkmaz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umhgcsfc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbcybvd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2avaayego.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswywhwn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdpvdq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpsznag.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfqvqht.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgnybi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2twiknovt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgiftra.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnjefbf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyteuzl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqtrzlv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2seutiogu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiphfxc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfobouh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyolzzy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ityyxzuw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2txfbhwsq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjbefip.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lebsadin.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2soaepsdw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vduwvlxp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuhtsfi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaejkey.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmgaxgw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fueclcom.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdemlsk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iplplhry.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2omxpiiri.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhsprjz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtrcdao.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2roseidoa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfagqzll.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgsldzk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yuelkgyh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wucfxqhn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixmigvd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2drzytgeq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2efqvkxxc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2chtocunl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2osxdvgrq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2woayeuyk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2onjaiqfr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwztiik.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmliptbb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pveufkxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwjdtha.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwmdurm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsgbfjm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2abmcziun.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kllwgdnp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhkfwdj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fpweroho.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnbxeqa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2skjewcmx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkvnigu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxksyul.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhzxkpy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2phyvlgpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmrznjd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzcpuil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnezmeu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxndtxs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmgtdvt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2osirolsy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvnkpul.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2intkgmhx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdljfqj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrdxrnu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsdgruf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2epynmlkz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dinkzydf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2whzehtat.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumupxe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhwypcl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjtdcfg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrilals.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2shivuinj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2detfwdyr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcgmecf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdfytot.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnxtqhc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kuumzrta.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpydcxq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2upemixki.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2phicwlfg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvnfqwb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrayceb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcierzk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2peciauei.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lorqgokl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvctxig.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqlnmnk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgilgjb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jntlescw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkecklso.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkgrinw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwiaptq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fukdhgxt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vpevobfj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfhnrqp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ouophbqd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tethmqoh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2iclsahcv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvsmafo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhqopak.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gchljonv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2amiqxhys.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfshhzz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpmuofb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwwvcpw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mohxwiuq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqrpupf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbeazwi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqcabtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzlnsmq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2opjkqdqs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2elbumycz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eavwzhhq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbpgaad.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdnhwkp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2umfoonsd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmowmig.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkaqvvf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtnsnpg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lannjsvl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2klmbjlbk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2phnzetle.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqnulmn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiwuovy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdwgvcw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnywdhwj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2atbyabza.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qoevkalm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmlecvy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwoqfdq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ranxpxlo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgoqczd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgzypaq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nifekdsq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zcipuzzd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiwzyzz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhwyonm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcamahe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hodgqqws.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhasbsps.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdvfqzt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqsegtd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrzbkzd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knhcqfaw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrepbnz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyarlsry.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztixqpzy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2disedhnh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtdqhu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqexrcl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcjvoiq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzolazvu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buxtemhd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmuppko.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2werxwskj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgakhra.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjezgfmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjqqxq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjvzbip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmducvw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxncuoj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2silwvrme.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwfvyo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uecpxmku.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyqczeq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrzxniv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2orsahxeo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqihdxii.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lphjqiea.html


<!-- 参考信息 -->