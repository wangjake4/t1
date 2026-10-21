代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gtesaqkvbe.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gtgtjmncbh.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gtybpfwywx.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gtkvrvdlmc.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gtvatkknuj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hysaishi.cn/Article/details/gtlzamorva.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gtpeheiifp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzfopgzg.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gtxqccbhwo.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtpombygdo.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gtzhzjsyik.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtiglkjbgl.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtynmbfahi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxinkj.top/Article/details/gtesoslncl.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gtsseimazl.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtmxccblyo.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweqxekki.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtxhcsgybr.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gthcydcxaf.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gtvsyhrtoo.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gtgkfsiuna.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtxcepmudz.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gtmqdoppic.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtmqcbtizr.html

[U33] Py：打包发布
来源：http://dali.haohaochexian.top/Article/details/gtoyjuyhte.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.feifeiyinyue.top/Article/details/gtzzlrxiec.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtccekcoil.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtizzshkxq.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtbtdzrohf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.havefunace.top/Article/details/gtzholkppq.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtvvtlxjnc.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gtvnguphac.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtygwdvpql.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtxhmpeppz.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gtpsgvfpfz.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtqhancpkb.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gteagksrkt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtsvyfsfro.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gtzggsktii.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtwucmdthc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtesumabqo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258888.top/Article/details/gtiehhyddy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gthuoxwavc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtmaicaejl.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gtofiafczn.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gtkmdtucdb.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtnyrzjerq.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gtvgonhlte.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gtbmihpypz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gttivnotbk.html

[U46] PHP：可空类型
来源：http://dali.xinyue.icu/Article/details/gtdzhgafta.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gtwsntzbkh.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gttomsgowg.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtwrcibxly.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gtxuqzajpv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gtrnmpbeje.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtjghkdyzx.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gthmkafifq.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasvfszqd.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gtnxsteraf.html

[U51] PHP：数组解构
来源：http://dali.jianghu66.top/Article/details/gtvcnlcush.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gtypnvgrjl.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtetvwhluw.html

$double = fn($x) => $x * 2;
来源：http://dali.316326.xyz/Article/details/gtpuwsfwdr.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gtrexfmbrp.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gtabsecozy.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gtuvfcctfd.html

$obj?->method()
来源：http://dali.shzxlz.cn/Article/details/gtmziquduw.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gtuxzwaysj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtzeexczwg.html

[U56] PHP：命名参数
来源：http://dali.svipenyu.cn/Article/details/gtfftnlmvz.html

f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtfrvopsic.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtpfrjzsfq.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gtrsftfkyn.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gtamliirkm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzrxifcc.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtninwlrtu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtkwhqcghs.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gtlygchell.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gtjoxvpolq.html

[U61] PHP：正则
来源：http://dali.gaohongyu789.top/Article/details/gtkyuvpqee.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtzrbtxiun.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gtducatihq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.c1oappe.top/Article/details/gtzmrlexrx.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfwurkwb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gttrebzdvy.html

[U64] PHP：目录遍历
来源：http://dali.zdqjudy.top/Article/details/gtflnmdhlg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shzxlz.cn/Article/details/gtbxipcfnv.html

[U65] PHP：会话
来源：http://dali.guannengcc.top/Article/details/gtolmwnbaz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtdzyzxvyl.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gtldzvpkrw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.meibo888.top/Article/details/gtbkhjchpc.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gtsgnefwsq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sxryk.cn/Article/details/gtpcdggjmr.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtlxmyroga.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gtrdrfnfvc.html

[U69] PHP：PDO 预处理
来源：http://dali.bjfxy.top/Article/details/gtezryiktq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtrmaymvxc.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gtbnivzmiu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yueranfly.top/Article/details/gtrxsunngy.html

[U71] PHP：抛出异常
来源：http://dali.havefunace.top/Article/details/gttwbqbbhn.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtadpybyge.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gtkaepjzid.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnqzz.top/Article/details/gthxcxdtqa.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuzycnyc.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gtnmloyucu.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtnieyfqox.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gtfajtaazw.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gtfrmjhsyt.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gtqtwbfhhs.html

[U76] PHP：简单路由
来源：http://dali.ybcxt.top/Article/details/gtaryieujo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gtizgyktqd.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gtcgfzdzdo.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtsoqwskvz.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtgqlepphh.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gtziqhsjta.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gtuhalxruv.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gtbcpnldcy.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtixrsrifx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aibaodan.cn/Article/details/gtndykvlzr.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gtweviqvtw.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gtqawiafll.html

[U82] JS：package.json 脚本
来源：http://dali.yanxiufei.cn/Article/details/gtqzecrfcy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangdashe.top/Article/details/gtzrjjfauu.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gtwuvpcxaq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gteekfxemr.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gtehpopibv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtfqsouufp.html

[U85] JS：可选链
来源：http://dali.yuxming.cn/Article/details/gteixkkdol.html

a?.b?.c
来源：http://dali.zdqjudy.top/Article/details/gtjrwccuic.html

[U86] JS：空值合并
来源：http://dali.xziqi.cn/Article/details/gtkxfsschm.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gtobbrwgvk.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gtxzthvwxr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gttperyepr.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gtfzoklaya.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gtmgqlyaid.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gtyhdrnfgc.html

[...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtxmdstcvt.html

[U90] JS：数字数组排序
来源：http://dali.gogol.net.cn/Article/details/gtkufcudlv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtnrqcefin.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gtxzcjbhsq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gtfxfucljl.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gtmwjcvoso.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtznyzjwqb.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gtqhczdqye.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gtgumfujtx.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gtecmqxmzd.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtgopbgebt.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gtsaqbasrs.html

new Promise((resolve, reject) => {})
来源：http://dali.andypj.xyz/Article/details/gtycizviwy.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtyburpguy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaamdmox.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtoxvaylqg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtvakdurpp.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gtkwbhoyhs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gtaszbimhm.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtbwtlprhk.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gtmctsdjcd.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gtqsbywavs.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gtvvqlgszt.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gthinbvcmp.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtpdcjvjle.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtgrjgdpjm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtvqkydkqs.html

[U103] JS：定时器
来源：http://dali.jqgfzy.top/Article/details/gtarhszpwp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gtudhbabxl.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtqqnqugpl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtrtetuiea.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtbkcluhtm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtxhacesiz.html

[U106] JS：日期格式化
来源：http://dali.yongpay.top/Article/details/gthpyvtwsa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cucudq.cn/Article/details/gtqllxyiwo.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gttsebqdkv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtigijnlfh.html

[U108] JS：随机整数
来源：http://dali.wangdashe.top/Article/details/gttkzpfzkh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gthhjxvbqp.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gtzhacungo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtjyguprgq.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtqesagchg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gttcmuamni.html

[U111] JS：对象转 Map
来源：http://dali.zycfv.cn/Article/details/gtoirzbfci.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtirjleqow.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gtonedfzuw.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtjoqljcmk.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gttgswboeo.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gttzqwmaoq.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gtfwspxtoi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtfochvgic.html

[U115] JS：生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtrrxdwrfd.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwchwujg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gtswsxjzyu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gtnzrrseei.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtmfjqxvks.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gtpbkqdejq.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gtxyzrdsyh.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gteqjccnpk.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gthjmiihgz.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtydupoium.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gtkhlhsxpy.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtpkigqfux.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmmvsjnst.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtlchjeaao.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdasonqdd.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtfdvogpan.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gtivvwozwd.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtvvsrushu.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtbimbdsik.html

TypeScript ..... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtgfhoelzb.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtagzfmerb.html

Go ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtunsgffbc.html

Ruby ........... 212
来源：http://dali.gzhubu.top/Article/details/gtijjbryrp.html

C# ............. 212
来源：http://dali.yj202588.top/Article/details/gtdfjeuhvb.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gteizcsuhx.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gtxkhejtcx.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtczczpgar.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gttppjqhdr.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtvaebhqji.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtdxhxvufx.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gtyeydetqc.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gtyybrroda.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gtkmsjmasp.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtxfocbana.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtmiuanrwh.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gtybvttlxx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtlpcqyilm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtylprslcy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtductebsv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtazkcqcds.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtsvjntima.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtlhcshrkq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtbunubijh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtrcklbqtg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtuooqywni.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtrhzeduot.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtrbugzzqw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtlrwcstjn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtbqthfbiw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtajfhfqdk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gtdqreezyc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtybkrvpgx.html

Q SQL 专题                              90
来源：http://dali.yj202588.top/Article/details/gtfxrldhsq.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gtxuqcwwot.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gtzceixdwh.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtuybdnata.html

U 高频实用片段                         120
来源：http://dali.vqdsnc.cn/Article/details/gtxhmaczuv.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtlfwsytul.html

合计                                  2106 条
来源：http://dali.mhx1999.top/Article/details/gtserxhpsq.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtkshrfeyv.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gtnofjjick.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtxerzaguz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hywenlv.cn/Article/details/gtmdhgjbge.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yanxiufei.cn/Article/details/gtxpzzakkv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hongshengwenyu.top/Article/details/gtpjbtbqzs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gaohongyu789.top/Article/details/gtquhwwtrr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetblrebx.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gtmnacsdhl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdgwetur.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtnmrdjjut.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gtjyjylarb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcibjzrsl.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gtvkjhjmxq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gtxjhyfrun.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.smart0.xyz/Article/details/gteafyjdjn.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtzdzfgdfp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cashguo.top/Article/details/gtdkkbliwl.html

【使用说明】
来源：http://dali.shanyushiyangkeji.top/Article/details/gturvumhki.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shuidangran.top/Article/details/gtthxmrsml.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gturrxsmdf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtukprrilo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gtadbaduqc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiwztvsp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gtyxncypjj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daria6918.cn/Article/details/gtzeearrns.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yueranfly.top/Article/details/gtpdmqtltd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtkxmcqgxu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yueranfly.top/Article/details/gttbjmzpjl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtxodpyznm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gtvjougbrt.html

【文件统计】
来源：http://dali.andypj.xyz/Article/details/gtjucuumfh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cheryme.top/Article/details/gtkytnokrd.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtixghfzrl.html

目  录
来源：http://dali.cashguo.top/Article/details/gtmgfbadus.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtlehyxoru.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtwemlfydt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtalfkvwgb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehlgggqf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtiissxfit.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gtmzlksnrf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqyldmcdt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtpvbsadjp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtjxlqeboy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtswiagttt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtenpkumqv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gternckslj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtdodzgvca.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtzrdqbohm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtwrbkdfew.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gotoacloud.top/Article/details/gtwlfxxmvu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtwnvelddq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hfpthk.cn/Article/details/gtconfasra.html


<!-- 参考信息 -->