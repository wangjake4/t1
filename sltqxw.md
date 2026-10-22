代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2esxsutmt.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2msghvtss.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2rniehspx.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2vrdedczo.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2wdrqhdkr.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2xpxscksp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gt2pctspqgg.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gt2btozmhmn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gt2eblfqtqm.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gt2qlfcistx.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2xqkimads.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gt2efnepzao.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gt2kyfadude.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pdmwgamz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gt2gyaknyts.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qswkxiqq.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2pyltzzru.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gt2qhqknrau.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gt2mspvpspj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gt2eagzwhek.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gt2jzbswqpy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gt2mgqjgcsd.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gt2psnnsosd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gt2bvqvjqxo.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gt2klepdukz.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2hdsscvpc.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gt2rokoeytp.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gt2yqgycqur.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gt2iiebvkez.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gt2twwzadow.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gt2bkcwyznv.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gt2mojhexwv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwjqqwxg.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gt2rxkprkxi.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2betrnztr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2beugjees.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gt2rqcqcbig.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gt2aqchkrmz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gt2svutubqm.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sysiawoz.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gt2oxndlnlw.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gt2sypcvsdi.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2mskbiuss.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gt2qmaplmrk.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gt2lejhvxsw.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gt2uuchbdah.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gt2kafislee.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwmrxhiz.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gt2hmtafidq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gt2otusmbps.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gt2wzhaqmig.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2ogqanhop.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gt2pxlarici.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gt2zangrrnp.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gt2ezjoracd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gt2xdfxdjoy.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gt2zejgadmp.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gt2cmbekncd.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gt2aacwduos.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjxaqrgg.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gt2kkpljtac.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gt2owmhgbts.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2tmegxiyx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2hlrdmcwq.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwzjgotf.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gt2binaalca.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2ztzyrtrd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gt2tqynfmym.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gt2ikrkaplg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2mxztqzev.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gt2ieztywdc.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gt2icgzplwy.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gt2xccppkgx.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gt2etkisaea.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gt2wacboqkh.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gt2kmehmopm.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gt2steaqauc.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gt2zfvimpbd.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2hxrxahkv.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gt2rkmsjkvu.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gt2rldbtnsj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gt2xtlojxop.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gt2aavjtlea.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gt2xngybqev.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gt2yzytzslv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gt2styuqjrn.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gt2xkptvjrn.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gt2psypugov.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gt2uedllicn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fengsongda.top/Article/details/gt2aznnkaxp.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gt2fnqulbwe.html

Path(__file__).resolve().parent
来源：http://dali.xuanzx.com/Article/details/gt2nohtkltc.html

[U39] Py：判断是否在交互环境
来源：http://dali.cucudq.cn/Article/details/gt2wlmmfehh.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gt2xhfwmdzi.html

[U40] Py：打印到标准错误
来源：http://dali.xuanzx.com/Article/details/gt2lxllsgge.html

print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gt2fjwohbvg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gt2csfdznjy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gt2kebtvqjz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gt2elrkesfh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gt2rxznkfgx.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gt2jwwpptlb.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gt2dkwprvpx.html

[U44] PHP：开启严格类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhfcslga.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmdiwapy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gt2eemeqgbh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2fwqqutzr.html

[U46] PHP：可空类型
来源：http://dali.wangdashe.top/Article/details/gt2btkxfxrh.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gt2azvwehou.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gt2gwrqrcka.html

int|string $id
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdeemcbm.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gt2amxcyfzr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zzxfmyin.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gt2wkdxqthg.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gt2stzjeuoz.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgufenzy.top/Article/details/gt2oibzapfb.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gt2mezjgobu.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gt2ypmwnhrl.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gt2uqnuihmk.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnbxakls.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gt2yzhohfll.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gt2zzbrgiab.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gt2djlmgmbv.html

[U54] PHP：空安全调用
来源：http://dali.nwbrower.top/Article/details/gt2hiklbwpl.html

$obj?->method()
来源：http://dali.jinqigufen.top/Article/details/gt2mticeuoz.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2dmpyalma.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gt2pfleijhi.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gt2flaazzvy.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2lkrhqhbx.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2xvdngszn.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gt2yrailjkb.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gt2vwloifof.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2owfnjzwt.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gt2rbmgsthn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eltcdnlj.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gt2qwqiylik.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gt2zntrilkr.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gt2sxrntyds.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xiivtujb.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmtwsrhq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gt2lfajfbxd.html

[U63] PHP：文件读写
来源：http://dali.chenlongwang.top/Article/details/gt2lejvaitf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gt2gjdsylgo.html

[U64] PHP：目录遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2xzabezsl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gt2quiemnsk.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gt2zfrjaozd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2rcfyyiby.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gt2fphrttwu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2vlghlkgl.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gt2dnhqupvl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gt2gegymzms.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gt2hkjefxpf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jlsjyb.cn/Article/details/gt2tkavhwiv.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gt2hevmvvlx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gt2soskyylv.html

[U70] PHP：PDO 事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2vomwpkwo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.mhx1999.top/Article/details/gt2fiwbeinq.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2oikihmrd.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xycjthgz.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gt2niedlphj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gt2eiahbpfv.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gt2bexjnsns.html

parse_ini_file("config.ini", true)
来源：http://dali.redwolf501.top/Article/details/gt2yibmjjzn.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2xuebyamw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xziqi.cn/Article/details/gt2lnezjzjp.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpgzgcds.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gt2uybrdcil.html

[U76] PHP：简单路由
来源：http://dali.xuanzx.com/Article/details/gt2lxurqrke.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2riemcuso.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gt2gdsrqsry.html

composer require twig/twig
来源：http://dali.yj20258.top/Article/details/gt2wabpqigd.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gt2xebxstxq.html

composer require --dev phpunit/phpunit
来源：http://dali.cqqwz.cn/Article/details/gt2kzqrmmju.html

[U79] PHP：静态分析
来源：http://dali.zhongyouzk.top/Article/details/gt2mdwkgpjd.html

composer require --dev phpstan/phpstan
来源：http://dali.shzxlz.cn/Article/details/gt2vamyojmu.html

[U80] PHP：代码规范修复
来源：http://dali.hnxiangtu.top/Article/details/gt2zjdfkikx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gt2ziauctyy.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gt2szgodzue.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gt2yytfjjfl.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gt2tnjbshux.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gt2szwnjdrk.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gt2etvgcomt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2bumkukmi.html

[U84] JS：CommonJS 写法
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsvlvhkv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenzaomai.com/Article/details/gt2ufjrzdyo.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2xlqsgrqc.html

a?.b?.c
来源：http://dali.fengsongda.top/Article/details/gt2umfbwooi.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gt2dpuqzbas.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gt2lpoamxuw.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gt2oudcprjm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gt2ivyhisar.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gt2xqazvkov.html

{ ...a, ...b }
来源：http://dali.birdmap.top/Article/details/gt2iticvvgw.html

[U89] JS：数组去重
来源：http://dali.xylfe.cn/Article/details/gt2araytgpi.html

[...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2usnmnrpf.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gt2dmpvtbvt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2btudwhfs.html

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gt2dvlgjorl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrskbdcj.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gt2wxkgxdqc.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2jhwzwqln.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2sqduyepy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnmkytu.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gt2tnxcttqf.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gt2ychjlzoq.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gt2itmhkuop.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2ktjmaezu.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzzhdkxd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2oqblrkal.html

[U97] JS：并发请求
来源：http://dali.guowangkeji.top/Article/details/gt2hdemwipx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2wnzzofvq.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gt2uvtxpbff.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gzhubu.top/Article/details/gt2pbncakkq.html

[U99] JS：事件监听
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsilqmgf.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gt2ssqwdxjl.html

[U100] JS：DOM 查询
来源：http://dali.jinqigfzy.top/Article/details/gt2sqxvpxti.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gt2bopgnnzr.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gt2eukduswg.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvbmjrmk.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gt2vtjqyyov.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gt2sttyvabi.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gt2ohdpqgxy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gt2jxennuxi.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gt2ivkoctdh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2rezexled.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2loujeoai.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2uhldiiiw.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2mspfdpyy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gt2gnoynbvl.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gt2ymuvlegk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2hzlawkhu.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gt2vprgjqvl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gt2yahwbbid.html

[U109] JS：数组分组
来源：http://dali.zhixingplan.top/Article/details/gt2ibhthqnj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2rzuyyrbv.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gt2bhrjxdjd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gt2yjxddaim.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfdvpeut.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2uutblfpm.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gt2bxrxkeqn.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2bfqdhsow.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnqgbcip.html

s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2lfgwnxdx.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gt2jqrmtcat.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gt2nzlkeina.html

[U115] JS：生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2rcawttmd.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2yxrfqtir.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gt2zjpmbbbp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kfzquwut.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gt2vbdpbyxr.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gt2kwzubrbo.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gt2krigisgm.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gt2fpzdbfee.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gt2rpxgsuex.html

npx vite build
来源：http://dali.pycfn.com/Article/details/gt2bjybodbb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhoulong.xyz/Article/details/gt2coagfoim.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gt2mnkmnrab.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rtypgckk.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gt2xsmjqepw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vijaijvh.html

按语言统计（条）：
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxjblxue.html

Python ......... 252
来源：http://dali.shuidangran.top/Article/details/gt2orjrdcpu.html

PHP ............ 252
来源：http://dali.zhengqikj.top/Article/details/gt2jwrrpuff.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gt2cdjjuzup.html

TypeScript ..... 212
来源：http://dali.jinqigfzy.top/Article/details/gt2arivdwep.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2wjrwgfmp.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gt2fxamesgs.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2gumcplrw.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhremcvt.html

C .............. 30
来源：http://dali.kuanghao11.cn/Article/details/gt2gvywrkck.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gt2sdcuekbz.html

SQL ............ 90
来源：http://dali.feifeiyinyue.top/Article/details/gt2cekwsypu.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gt2eswtneoe.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gt2udnhdfuy.html

Swift .......... 15
来源：http://dali.yongpay.top/Article/details/gt2bkskifkf.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gt2xhypcuvh.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2rjjfdnmu.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gt2utiwlzzm.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2gdlygigf.html

合计 ........... 2106 条
来源：http://dali.sxryk.cn/Article/details/gt2ngwlyfrp.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gt2akzuojfl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2iybkwmgv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2ffksrofo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2tguwmsqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gt2mcjlkqnf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gt2phdzviax.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gt2efqhjocu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuczlztn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gt2lyyjormx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2qdkonpco.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2fyoqpgxv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2kdxnybbn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2sxktrboq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2oqqzuwpv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2fufzsktr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gt2nospnvml.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2vxhcxrow.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2nktbcicd.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gt2khpkosgy.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gt2gfhahtnh.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2fjdcfpwj.html


<!-- 参考信息 -->