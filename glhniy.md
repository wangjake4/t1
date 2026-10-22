代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gt2gvagiuss.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gt2vxumzcvc.html

[U20] Py：缓存函数结果
来源：http://dali.hnxiangtu.top/Article/details/gt2pxpgjfmq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gt2dqjrbvpa.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gt2fnvyhjoe.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqirnydy.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gt2oqvkgctn.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gt2ykuhyhnl.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gt2cuelqfsu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gt2aabhehlx.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gt2vrjpkesg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2dphqldth.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gt2hrnlrsrr.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gt2ankyvtec.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gt2kboounea.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gt2moxzxzfg.html

[U27] Py：异步 HTTP
来源：http://dali.aibaodan.cn/Article/details/gt2rnlseznu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gt2esuadrfv.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gt2krmvvcob.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gt2mhzebmhf.html

[U29] Py：属性校验
来源：http://dali.tanke756.top/Article/details/gt2fdyezgmk.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gt2zwbmihbk.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2uemnoqoa.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzlwgepe.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gt2woshalyt.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gt2vlqbfeop.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gt2zviirlyf.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2kqmfbyke.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2rwfkxtby.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ivvv.top/Article/details/gt2fofpwitx.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gt2bgpmolvh.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gt2qqvkksrz.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2pbgtkbux.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gt2wvsexzdp.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2qduyowle.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gt2hphvxfbj.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqhwgqpc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gt2kqpwahsl.html

[U38] Py：获取脚本所在目录
来源：http://dali.svipenyu.cn/Article/details/gt2gmcgicqa.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gt2dhfuczvj.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjoelywj.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gt2zcbtpxhn.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gt2lyslvonm.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2ecersokj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gt2fffjqxqn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yonumen.top/Article/details/gt2qxinronz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.9152youxi.cn/Article/details/gt2ivadvlqz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gt2sgliuldv.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gt2gtuqksqw.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gt2hkidzuvq.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjbbkcof.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcatmckr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gzhubu.top/Article/details/gt2jmplspnp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2gakmjdus.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gt2cdyywrst.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gt2opjbziic.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gt2dlmovmvq.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gt2zjvbsrba.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gt2ufokxrgw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cucudq.cn/Article/details/gt2zczenpwg.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gt2equqvmhl.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gt2yxqqaimb.html

[U50] PHP：构造器属性提升
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjeydqbz.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gt2hcdtrbkt.html

[U51] PHP：数组解构
来源：http://dali.bjfxy.top/Article/details/gt2eiiwyzrp.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gt2njoenttq.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gt2sprbgtzy.html

$double = fn($x) => $x * 2;
来源：http://dali.hammf.cn/Article/details/gt2nrjzdbgs.html

[U53] PHP：空合并运算符
来源：http://dali.sxryk.cn/Article/details/gt2qgxzrsog.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2ygzmxfga.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gt2cfxejzwi.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gt2mdxrdqqf.html

[U55] PHP：match 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2oyaonmfi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2enajnifq.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gt2fdnyacml.html

f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2mctsovnu.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2jchcbxvu.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gt2xseuqkau.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwxwcqzv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ihlpfpmo.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gt2jykzwvwa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gt2vmgmvxdn.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gt2funbdexg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gt2itqutuii.html

[U61] PHP：正则
来源：http://dali.shzxlz.cn/Article/details/gt2mpnrgmkw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2tjqlquwf.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gt2bwgclpym.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gt2ymcdzlal.html

[U63] PHP：文件读写
来源：http://dali.pycfn.com/Article/details/gt2nxivmhhn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gt2muegouqs.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gt2kszkyknr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.smart0.xyz/Article/details/gt2fwikesid.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gt2hhecedsr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2fwdgsnsg.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gt2aaepordz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2xyeowglu.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gt2loncbnac.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gt2dpfulryt.html

[U68] PHP：PDO 连接
来源：http://dali.sufxvd.cn/Article/details/gt2rvbceuzo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gt2bemctflv.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gt2ttxdvydn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigufen.top/Article/details/gt2owyhiznw.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gt2tyxhbilu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gt2jzirivkx.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gt2zorhwboc.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2dmjyiout.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gt2cqkgldjc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgfzy.top/Article/details/gt2tekdejjv.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gt2oqupqsss.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyzanvpf.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2qxwlkbxa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gt2niiikven.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gt2shhgrodq.html

composer require psr/container
来源：http://dali.ppjwa.cn/Article/details/gt2lmeghsaq.html

[U76] PHP：简单路由
来源：http://dali.aizwys.cn/Article/details/gt2rdyvugck.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2cwarcdad.html

[U77] PHP：模板渲染
来源：http://dali.xylfe.cn/Article/details/gt2wbibzony.html

composer require twig/twig
来源：http://dali.yangfankeji.com/Article/details/gt2mawxtkxs.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gt2bdpahyuh.html

composer require --dev phpunit/phpunit
来源：http://dali.haohaochexian.top/Article/details/gt2aynrnjky.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gt2ujxvizcp.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgufenzy.top/Article/details/gt2cijhdhbz.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gt2pqwajktq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gt2agpwcxwo.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gt2kptsteiq.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gt2vwlbheck.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gt2aoghlrzj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzbklslu.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gt2ymnuwtzg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2lxufotan.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gt2kieshxar.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gt2aodyuyof.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2erlddsvr.html

a?.b?.c
来源：http://dali.yuxming.cn/Article/details/gt2edveevhf.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gt2segfidxt.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gt2odwukzbc.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gt2thyowlqp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.meibo888.top/Article/details/gt2cuoevbdx.html

[U88] JS：对象展开合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhtbnmce.html

{ ...a, ...b }
来源：http://dali.zhengqikj.top/Article/details/gt2jbdonnhf.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckncwuia.html

[...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjbdcjey.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gt2mlhkhqnl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2tebjkrvn.html

[U91] JS：对象键值遍历
来源：http://dali.hysaishi.cn/Article/details/gt2akunlvgp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xylfe.cn/Article/details/gt2mimfebwu.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gt2zgueahxc.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2cajoroer.html

[U93] JS：模板字符串
来源：http://dali.tianlin.xyz/Article/details/gt2rdjnsmhe.html

`共 ${n} 条`
来源：http://dali.chenzaomai.com/Article/details/gt2ielqkllj.html

[U94] JS：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2ieggsera.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gt2uufqhbbz.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gt2tnexckbj.html

new Promise((resolve, reject) => {})
来源：http://dali.zycfv.cn/Article/details/gt2xidfosin.html

[U96] JS：async/await 与异常
来源：http://dali.smart0.xyz/Article/details/gt2gizgocqh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2ukyuppjt.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2xebxtmnv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2mzkuziab.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2pjojwxmd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sysykeji.top/Article/details/gt2fdbxqgqv.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gt2dicbukuy.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gt2jorjjpjf.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gt2vedxzunf.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gt2waegrnhu.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gt2tsathsyy.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gt2vhsqqxyg.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kemefaqb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paaruqwn.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gt2cuormvng.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2okptggbs.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gt2omzwghzh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2nynjeurp.html

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gt2xaledlnf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gt2gwfvbcpw.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gt2mqsjhxig.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuanzx.com/Article/details/gt2gmlvhire.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2spsrwnyf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2jnzwhvcm.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gt2hqcylasu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgwbygbf.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gt2ukzhoswa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2ttcnfifn.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gt2bvpisbcp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gt2kfmkxule.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gt2qnkqihgl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2opwqmukj.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gt2dtbtjawp.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2zjffattq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yqardfci.html

s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2jmftfedw.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gt2selfumpj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2achqtxww.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iirxggki.html

crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2qbkotmyy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gt2dwiqipcu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2jeaxjnsc.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gt2zktzhqxc.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gt2zdcqituh.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gt2cwyblqmk.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gt2mwivssrf.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gt2rserowdg.html

npx vite build
来源：http://dali.birdmap.top/Article/details/gt2rtordhaq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyijprrc.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gt2egsoyjbg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptvqbuki.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gt2sbvbfxom.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ymgffhxa.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnsxdfzv.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gt2prlqnshd.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gt2bpokdxqn.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gt2udpxmaou.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gt2mlkhsxqi.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2wubytlkh.html

Go ............. 212
来源：http://dali.yongpay.top/Article/details/gt2jcmqltrh.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gt2ebidyncd.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eofuqxpf.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gt2unidbmdy.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gt2hdfuuarz.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gt2ssplnzrj.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gt2yidabjvd.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gt2dgrnwyhv.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2dhhskpgb.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gt2psdsolse.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2gathanmi.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gt2tonidpsy.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2vxxbzgud.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gt2rdetshlr.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gt2yvzwmktc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2caoffkfg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gt2dmerfxae.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2ufugknzj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2cpwalzka.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gt2jyupecle.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gt2ijknzebq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2howbbcxw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2dzzywvth.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2mvynaxeq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gt2sjjpidsu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2iokmlqxi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2vdbjswmv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2klxymtze.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjenieb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gt2sbocaxdf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2gsucrblj.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gt2kkxpseit.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gt2dwurxxmq.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2ufbostmn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhgjwwr.html

U 高频实用片段                         120
来源：http://dali.yangfankeji.com/Article/details/gt2obyeetgf.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2dnvjxncq.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gt2ljarnpun.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2uyqeodhd.html

使用提醒
来源：http://dali.sxryk.cn/Article/details/gt2uwltogut.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2pedgvmko.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gt2ooxrguzr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqmlbjxl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gt2rvgvvcbi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gt2byskfjfn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwbgnrdv.html

—— 文件结束 ——
来源：http://dali.pycfn.com/Article/details/gt2grusuiou.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpevmcks.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gt2xtbknwvb.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gt2dpaooctn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2uedhaxbk.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gt2znryodiw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxuanxn.top/Article/details/gt2wzipqfhc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gt2xnobfceq.html

SQL · Bash · C · C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmydndff.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csnewako.html

【使用说明】
来源：http://dali.hammf.cn/Article/details/gt2zbbkiscd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gt2ynplepgd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gt2wrvxryek.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuetiantiany.cn/Article/details/gt2mplznfdf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gt2wdhnaytq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gt2yfdlzoaa.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ivvv.top/Article/details/gt2pzutbxru.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gt2pawpiboc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tian-w.cn/Article/details/gt2yrozyekq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fengsongda.top/Article/details/gt2wcuhkkiy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ydzc1.top/Article/details/gt2krgrkalv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gt2ndcnndsd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.haohaochexian.top/Article/details/gt2xwgcrdgp.html

【文件统计】
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcgudzzd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gt2woemxqbz.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2osvmutkb.html

目  录
来源：http://dali.zhoulong.xyz/Article/details/gt2uugmgixa.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2xqhpegcz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gt2idmkbxzj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2qbppdmqp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2kpiyhhjg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gt2nujhugiq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.birdmap.top/Article/details/gt2jqtjtrgq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gt2dzkwsrst.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2pbrzkcpr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2rxiyalnr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2fjutvwnb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhixingplan.top/Article/details/gt2xglsoiej.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2oukwrzkd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2mqnsembw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gt2rcjvazrg.html


<!-- 参考信息 -->