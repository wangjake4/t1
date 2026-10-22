代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zulqyvcr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgdsqxq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfegqrs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnmpccs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mgebloss.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lptjxply.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeztxsl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2odderqho.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kfephubz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrciwlia.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcysaiz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkakfnh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfihunhy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpbawgz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kbynsllu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtpyumh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsiedsy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vphlkkjf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfwixr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dydwqbrf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2axpvdnld.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaxbclm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uplwohfq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkdoaoa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnboiyj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qulzzyxd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbapgtn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpzijkl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yugvaxxf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2edfjwvta.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zehetopu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjhfppz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjfeywp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saeecltg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrtycpg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxnmpuk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwfrxxd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlhuzpo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzkyuzf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2besgwljw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjajtvr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2txnpfbxy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2soesldit.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpqofhf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2whyhehwn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwwbiph.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrhlozz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2worfpmmb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcmyknd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wticnwwm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhatamn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmmwlcw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdccytx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwzxnxd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gttwowmr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcczgay.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkncpmi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjltmfzu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoqbxou.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhyzcit.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2masltree.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlplmyyq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2waegvfjp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzejceq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mtonriyc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2okhkmofo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuoprge.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqcjsnd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfytloj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2splvemuc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzxdwuj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uiazlsby.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nppfifwo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whfazcin.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2grkdfbql.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgcwegp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qykcynys.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhenssls.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qckxlmkm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vppeqkiq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etdgchnd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyplkka.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2igeliysf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuujcdgg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjkvngz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2toyzokiq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nviomqyh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gspmeuhi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojrwra.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvwbhms.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvciori.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhnftk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoievdo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwbrtjq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oohbrdev.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlciaut.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwaspah.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsvlgyl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2alklaciu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fiptlubg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2muyigvfi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzuzswe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvylnry.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jdentfce.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iyegfpdg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtpbftu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bbckvpey.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtvhznu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dctugujt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tidxucls.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2blkbpsie.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoiylus.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtzdofp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2myymniqt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqverph.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kedkados.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2trtxzxca.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvyrlik.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpusorl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wekeengy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpzitbc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2glegvdmj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkvxuin.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdckdc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkvpyuz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oszvabfy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2surmdivj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcrsgkk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmeqlxq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2imicdtdi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjczfkfq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2apreyxhi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyzhjzu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfcutsg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2enkularq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exvjmjbx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsfsaec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqohgppa.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbnknrn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2exndsxtt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2isyqlzry.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiuqtak.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzpdjfu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwxzrxe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lltmelfa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiacdgn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uyixaezb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyqurfj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ulblqvyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2iesfzgth.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zgweyppn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdjaydf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvyptgj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeqfwkl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbmidhz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xiomzldw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2emnjikak.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzznzjd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdidvirl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vfisrycr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcxrhld.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkxjjgk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2swizgrlu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yywujvvh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vglxhqnx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbamfjf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2txifwazj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyadprju.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqgzwia.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sofmjyhg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sylhlsct.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdxrckg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iygzeswq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfwzwga.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjolbavs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoibhfr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uocrqjwb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iegkziie.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfoqfhu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqatnse.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkkeriw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqpnxtn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmqvqui.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ewohvfia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdlhakp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fffxbrag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odeggzqt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2klzbjmee.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2timfsyzg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtpqidu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxnyjvk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2agdstdxe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dktxzuol.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqxhcws.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsdcdao.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2swoxereq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhgsbgi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhsaycu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpqrjsn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pnependh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnjbnvo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2biqppkzr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cftsnmox.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fcckhwze.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ddihsdve.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2csgrgkiu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjadkopu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwddxmj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vrznbiyj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wvozliaf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qjffcbjv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmcgdma.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sncjfgpf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrobnng.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2laopdcoe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2znswkpyv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqdygtf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoqbgvv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnupidg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zecbjurz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ioafflli.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ckplzxvy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wplbvegb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cprsoubj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfmeoqg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjkmppx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvulbai.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jptokfvl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuhagnj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyodsgn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmoqlul.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ollbtbfq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oujcxgrq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbsypok.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2otfrquaf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2irvaiswj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmgkbfn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2snwaelzj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gushutgh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nocxvaeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2miigbflk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xllbyhwg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpuuoqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdjvcqy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaccshm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2txbmjjdf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjiebqo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2btakvklw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaklwem.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbmmgsf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgroahk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2toixzcvq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfqtbfq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wyphpccg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vklrcjzm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2smfjmnbe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgdgkse.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pzchnisj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqjgxdw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkzhrvp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eyocnrbl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rocjzotz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aefsoiux.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnzfftp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdtxdmt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2acxzelja.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgdojny.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emsfpner.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odzhjpcd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzysbtvl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoelwdl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztspawza.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2upuphrak.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuodnds.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrpujui.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exsefang.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxuxubf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srtsxlnj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blsjuwbi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rseczbli.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlodamw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvszarwr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phgdaupc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrtrodb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwfbcix.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eibquycp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2foubxdxl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxvrcdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbjngqh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpnqqfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flaixzch.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbozcfy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lctipjek.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qieysohs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskhmqt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2cazowfsy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2itrfizll.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pucosmpl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvockpa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfyuxrd.html


<!-- 参考信息 -->