代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gt2tpsgixrk.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2iwvnkzvv.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gt2mohrftst.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2nifpdtyy.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2xyfnjlei.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gt2imjzzrnm.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gt2jkvojjkh.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gt2fwabckbb.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gt2xjgmejfs.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gt2takdlvdk.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvhqykha.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2tiisgmpe.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gt2windmwzm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glagiiwa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gt2pfkzhppx.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gt2rvkbwwrz.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gt2rxvocwmd.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gt2tbdjopqe.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gt2dhzswqnt.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gt2sguiaxmf.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gt2fveaqjqx.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gt2uwoysbql.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gt2jijeyvrp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gt2qcdoaguw.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gt2lmromxps.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gt2eyigewba.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gt2abnvxiva.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2balqjexq.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gt2huqvrmcn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gt2grmxpmfg.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gt2dofrqjbu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gt2onosonco.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gt2ssfmpzbk.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtiqlwos.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gt2waizlrgj.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqtigkef.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gt2dekydzvh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnnuehea.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gt2nbjytipl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2iinijciu.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gt2mknltmxd.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gt2tfbgewgz.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxzvezvs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gt2dnoqjxwh.html

[U27] Py：异步 HTTP
来源：http://dali.yuanzhike.top/Article/details/gt2auasuylj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdvunyxl.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ornywugf.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gt2qctksvny.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhltptdv.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gt2nnjmpazl.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gt2nrrxybsa.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gt2cvtemomy.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gt2unhmyqzh.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gt2ndsrycfx.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gt2oxynlgqa.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwjnluyg.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydvckpra.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gt2jiirmwjk.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gt2ijgookps.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gt2mzeeofdy.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmmigzgg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lktaoeox.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2tfplluow.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpdxijct.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sovvumsh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gt2eolmytzg.html

[U38] Py：获取脚本所在目录
来源：http://dali.jianghu66.top/Article/details/gt2knslyqpg.html

Path(__file__).resolve().parent
来源：http://dali.smart0.xyz/Article/details/gt2nqrafflb.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gt2rxijbfwk.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gt2bapmzqqq.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gt2uhxvicyu.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2ewjtkngg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gt2aqdalcik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gt2zkhynbht.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gt2kfrjodbs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqerrulz.html

[U43] PHP：声明命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwidrfdi.html

namespace App\Http;
来源：http://dali.ybcxt.top/Article/details/gt2bttqvvbo.html

[U44] PHP：开启严格类型
来源：http://dali.chenlongwang.top/Article/details/gt2uykmmdpp.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2yqzygvpq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2kwnllcrn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2ovmehiuh.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gt2puxyewhc.html

?string $name = null
来源：http://dali.redwolf501.top/Article/details/gt2nvjquovr.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gt2eowzjote.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gt2jqqfdlkj.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gt2czungdrv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ojgzefrs.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gt2snaitfmr.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddsnisah.html

[U50] PHP：构造器属性提升
来源：http://dali.vqdsnc.cn/Article/details/gt2udipxaba.html

public function __construct(private int $id) {}
来源：http://dali.cqqwz.cn/Article/details/gt2rbrklijl.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gt2yqizfuyy.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gt2umvlfmcq.html

[U52] PHP：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gt2ekdexfbb.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gt2ovjbnpwy.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gt2wscedqww.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gt2gatrpdmx.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gt2elkgalsg.html

$obj?->method()
来源：http://dali.svipenyu.cn/Article/details/gt2wmfithia.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2eavuwyqj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gt2lfyddugb.html

[U56] PHP：命名参数
来源：http://dali.dashuyun.cn/Article/details/gt2uhohtzwj.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2ffzsfjse.html

[U57] PHP：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbpdxqxz.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxufpade.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gt2tzbyxwoq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2sprcplpy.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gt2mttkynmi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aayhbjrl.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gt2ygzrelfi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gt2fskcjmru.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gt2fvmqgubo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2frqjtvoe.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gt2atbzjdan.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gt2kwpfpazv.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gt2viypxqqg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gt2shilskab.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gt2ecbbyors.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gt2ufoabqbo.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gt2avgdmllk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2rklwsfxg.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gt2xtylftgd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gt2eujlemsp.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gt2dwgfvsoj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tian-w.cn/Article/details/gt2rskopran.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsdtskln.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gt2gaohulab.html

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gt2nqhzfobf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gt2ooroosyz.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gt2llmlrbvo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gt2pdioyvva.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2ceqwggug.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2anhzvhxa.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gt2ehturekn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gt2sobrrfjr.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2jpucfwyx.html

parse_ini_file("config.ini", true)
来源：http://dali.0kj1m.cn/Article/details/gt2vbcdfvnv.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2fcinorww.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gt2ypyktgsf.html

[U75] PHP：依赖注入
来源：http://dali.redwolf501.top/Article/details/gt2ymnaxxfu.html

composer require psr/container
来源：http://dali.ppjwa.cn/Article/details/gt2nmygtxzq.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gt2ijykuiip.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uecexkbq.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gt2lcexmczb.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gt2mhvwliln.html

[U78] PHP：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2hyyocreo.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gt2urhwhhlx.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gt2jenpneyk.html

composer require --dev phpstan/phpstan
来源：http://dali.havefunace.top/Article/details/gt2ctrhwwiv.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gt2zmlvrzlh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhixingplan.top/Article/details/gt2llifbtjo.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gt2hjzqxvpn.html

npm init -y;  npm i express
来源：http://dali.andypj.xyz/Article/details/gt2eejfryyb.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gt2icejmqqb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gt2swlwlzjp.html

[U83] JS：ES Module 导入导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvcpztos.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2eoqdomaa.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gt2hhottqeg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fzhhl.top/Article/details/gt2wkpzypiu.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gt2swtmesnu.html

a?.b?.c
来源：http://dali.9152youxi.cn/Article/details/gt2zsbznovq.html

[U86] JS：空值合并
来源：http://dali.sxryk.cn/Article/details/gt2khgavxvl.html

a ?? b
来源：http://dali.shuidangran.top/Article/details/gt2jnqojpjn.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gt2vcwpilou.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhongyouzk.top/Article/details/gt2ddzkshmx.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gt2qqkiazbm.html

{ ...a, ...b }
来源：http://dali.gzhubu.top/Article/details/gt2mfmzplno.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gt2xpvxzdde.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2yaignarm.html

[U90] JS：数字数组排序
来源：http://dali.gotoacloud.top/Article/details/gt2qfszhutz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2rjzbyzqw.html

[U91] JS：对象键值遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2pbnoojof.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gt2jdbmujma.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gt2sbdpwxev.html

structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kexwzltz.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2glofeakx.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gt2lklhkgbg.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gt2gppfygza.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2ryowdznq.html

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gt2znqapdvg.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gt2nlndemlw.html

[U96] JS：async/await 与异常
来源：http://dali.smart0.xyz/Article/details/gt2xbsjfngq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2baamkczw.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gt2mcnhuxmd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2aihjkzvw.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2uvjpcywq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gt2lninmifr.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gt2jkyuptjw.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gt2cjelgtcc.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gt2uzsafcwb.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxkknxzr.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gt2mbvfqpqh.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gt2lseqmrwl.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2zbbvavdo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gt2cuynqttc.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gt2kurmbflv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gt2atqtlhgm.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gt2dlukzogu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2auhsjxej.html

[U105] JS：节流
来源：http://dali.hammf.cn/Article/details/gt2junitlqq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sweek.top/Article/details/gt2wqxwwoef.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbmkuqxs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gt2iqebqmca.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2dyahadbd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2dvnfkmtb.html

[U108] JS：随机整数
来源：http://dali.yuanzhike.top/Article/details/gt2cgnwcqlw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gt2cygfszjy.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgwwksog.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gt2gvdffqkr.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gt2bavgjyhu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gt2wqcgzldb.html

[U111] JS：对象转 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2maehqscr.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2zvtwhwgf.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gt2dzuyaekg.html

"7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2jwxgilqh.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gt2fbmbekox.html

s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2tpexgkan.html

[U114] JS：JSON 深比较
来源：http://dali.hnqzz.top/Article/details/gt2klvxukxf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2wnbgjojm.html

[U115] JS：生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2tsggcfgw.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2vlahlygm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigufen.top/Article/details/gt2rcyhnocr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gt2ncpvcisp.html

[U117] JS：单元测试
来源：http://dali.ybcxt.top/Article/details/gt2mdencibp.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gt2qynfitbg.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gt2twxfmmte.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gt2jmpzvhdi.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gt2aroytmxq.html

npx vite build
来源：http://dali.daria6918.cn/Article/details/gt2omojlphw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.andypj.xyz/Article/details/gt2ftwrjwnn.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gt2wrbvbatf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2tssnvzof.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euwfdlrl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ymczggoy.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gt2eqrqegxc.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gt2mddxqayg.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gt2ddkcqxet.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gt2qbbznhdl.html

TypeScript ..... 212
来源：http://dali.sweek.top/Article/details/gt2glpufxhd.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbuqijhw.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gt2snvlnsyx.html

Ruby ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prioidxg.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2onqiuggv.html

C .............. 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxfrooyy.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gt2kzgigufp.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gt2lsxbmrnu.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gt2swepxsmj.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gt2hgwrtynw.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhvuerby.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gt2dqngctko.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gt2mrlionfq.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gt2ytsoefuc.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2izrtghcf.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gt2vjiocnsz.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gt2ckfkcpig.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2srstbbkv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfebgeox.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2jxuatanw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gt2pcgfdayi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gt2bfwikein.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2mlvkisvs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsjqhxfi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2equtccog.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2dqfzzxob.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gt2vocjsofn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2iydjpmon.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2gjvvokyf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2gkqxkooy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2glorlfrb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqlqnvev.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqbswaes.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gt2uujcvgxr.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gt2hwpaoyvc.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkhihhre.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gt2grboehcr.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gt2acatcpln.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2xhhejsme.html

合计                                  2106 条
来源：http://dali.yuxming.cn/Article/details/gt2hzdzbimr.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2emnidxgh.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gt2bczykiif.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2wgqzvgij.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gt2nudgndio.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gt2ydefgjzq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jianghu66.top/Article/details/gt2ocumxtni.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jiagoushi.top/Article/details/gt2bjvbnytw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxuanxn.top/Article/details/gt2zvwvbkgr.html

—— 文件结束 ——
来源：http://dali.meibo888.top/Article/details/gt2kanqixjk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wquruuzl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gt2iixfaksj.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gt2gnnhyubj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2mttmplsd.html

【收录内容】
来源：http://dali.jinqigfzy.top/Article/details/gt2hhwonshr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenlongwang.top/Article/details/gt2flthfhmv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vitrynov.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gt2lutomsvd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gt2otfasnkj.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gt2byxlxlyr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jianghu66.top/Article/details/gt2wbkcfixe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcnxninj.html


<!-- 参考信息 -->