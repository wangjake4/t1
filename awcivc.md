代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2covevjjh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcsmwqb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiookzc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvyyqvf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvlhscp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2npsecpig.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfawvew.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nccqneaw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ceikvhbc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxltfgch.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwpgaua.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpuhopr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxspguq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eakmhsxf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmduqnda.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2iogrhuxu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwondf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2thgtqdhm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pabsqelf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2inijkwep.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmctmqtp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2stfpnpdq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxgxepp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrrzabb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yrchherr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfaipna.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiahngu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ushqiryq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkjlrma.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyboaaju.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atuxmlhq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oluwsvkm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nshnqfss.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cguzhkup.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzyhexp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ofndvdjj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbsebcx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgedjgt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yeakkogk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwltwuh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpkpgia.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhovmxb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2efbcwiel.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwymduh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtsqqmt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjxkcpx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bczpmpee.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwxxmzq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhwjfgm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxajawtt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fwztzuie.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ensplhjr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lwstxlqp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hljabdzt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdumezne.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vutafztp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sebfykaa.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcmbjra.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kcadwafl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rszlyebr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrksrfgh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uthhsqiz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sbarxqoo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcabgtnv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iczpwvzf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qajdkbcy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbcmzfz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjazpbt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvjtfma.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2srinbkzl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2beqgxhfk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2aessnccp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2csxekgze.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hocgegho.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqcknhf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjytkqa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2spinbrxf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvraiejn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdqnytj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fajsoiov.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfotwoa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaftqsx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyzgcyb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2itszfuho.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoszzjw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mowhzhxz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsnahsj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqwqftl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2spvnbadj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitwguzs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szjlzxab.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gstjjebg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnrssoj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uitvewzp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aiytbpxl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tevjhogo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoyrcmg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxjyddq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ymewgirt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bopqltgf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbolnog.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pxchycri.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrnzpsv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cumaomub.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjfugdb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hssixggm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2veasvnry.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrhwaum.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxztbjbi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzccmsvh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqmsedd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtchffj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmhyxnd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zafuztcn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmlzyko.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xivfsfkv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojblgedm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyyxkhx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2chrzzbzt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pepsylpy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2awvhcjhy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2usbltpkf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2biqavbjq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fitcyffw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nskrabks.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2eyopptsc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gybjovqa.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjngvwg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crdaezri.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wriesqsc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkhsfbp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoqcnxb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2brkaqykt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2epivsfnd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqrpbao.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxwfewf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2skfftuif.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xckevqdw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2okdjnjsw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2migomjco.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoljbgx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmheewi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtbtqoa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpibbem.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpojquoj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hipsqahp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iimwrpqe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdbxvpv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aqylocqj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhayjco.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iftwaxnz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgluqxq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuahnza.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twxbzrqv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpmhdej.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mryoomld.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yewgizvb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfxqhzf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2prqbyzbe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tabyygog.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcnhlzk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhhjqeo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqzuxks.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbevlfh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oysdasdr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2woppoxhb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pllxazvt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrkkpwp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyikxak.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkkypwb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtawblk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjflady.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2swvytimk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyshoyl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dteyyenp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikovvubu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhpdskg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hepgglbm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaqhckn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wwafmvol.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uchyrpdm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mckufldf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtvzyly.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2faqrduhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbbalzg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyzzmjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzsifdk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmksnivh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfcghso.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vhecxmol.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nwayndaa.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuxoxod.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvqmxd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zctorsty.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaaogxx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcxzywe.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2akqmvscv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnlirxv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wctohevz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqmhkvn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2coayskow.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbukjlx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxoopvr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2thcwwrxv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzvpdfa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbnwjup.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2azkmivyl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoftgzs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2blsvdryt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjkffus.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ocirnysy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2curbcqly.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzpwbrt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gumezpij.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2twppphmf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzozqnh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgflohb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbpsfvw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2krxftmhb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvvdfky.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cglpvtlc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvseabu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2thvfacrv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkfgtu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxumyim.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ngydlqjx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kywfcefj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2blplhcmf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlinyok.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pvykuapg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tedznhri.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lthnjkeg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2abegizid.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2busixpcs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2suiqvpof.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oceqobaw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdhityx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2idwocala.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgdsqjw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jnponcqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoegrln.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxmdkis.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ephibvmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtyrphx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dunlpmii.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oekmbxnt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnegmkj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpgakwr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2htnamwnr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2skmzimra.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnvqmjs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlgjnwr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wsldtlwb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaktves.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvbkbus.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiukjhd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxnysql.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qqplawiv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcnbghn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjtaskg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2picjwknd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoservy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zzstrfpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kubteavm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2voxomvlb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bbutwhdo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsqlbhn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erkqbolc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzntbtw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmgxomn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2niegaxit.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpcpwiw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amrnmiec.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjsniue.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmjijsb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckedmtig.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2riuejoxl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cazwgdqs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twmbdbii.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2meocyeaz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdshdzaj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2taaxqdte.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmhkvel.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcoodvi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrqkaow.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyzhopa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hakaadyg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqkzcrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaarmus.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opboyxyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxcmhwh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttakkpvs.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2prkriafq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kueftzca.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcozzzuv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbyfhug.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsuaojh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxjomlg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqzypij.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfpqpnh.html


<!-- 参考信息 -->