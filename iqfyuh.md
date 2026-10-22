代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2krbuokio.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ehyeiwks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2afieddxd.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2amrljyds.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2rjorzyca.html

[T59] Scala：循环
来源：http://dali.meibo888.top/Article/details/gt2smaxqvth.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2phrubvyq.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgqovwiu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gt2wzptssqp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pghdjbbo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2kkclerpy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2tsycuvky.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gt2fgxwjiyx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gt2wibggvww.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gt2vnptwyya.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2cxhdkloc.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gt2jxlqbmex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gt2xzuzmuae.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gt2luhcjipn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxeolyma.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gt2qocdgoiz.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2wstrhilk.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gt2jgsadlus.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gt2irpthofl.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gt2xhpintxr.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yawungdc.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gt2wcwrvhkf.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2twpsikgo.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gt2ukjtfgdh.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gt2ixkdulgb.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gt2voohbied.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2cytxwfhi.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gt2fvroakdw.html

(x * 2 for x in arr)
来源：http://dali.chenlongwang.top/Article/details/gt2mooxsibt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gt2nzlujjnx.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gt2vgkxhsnf.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gt2kdkgzgrt.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gt2snaglbhc.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gt2qdysckrw.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gt2igzpidsk.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gt2nfsihpdm.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gt2qywqwkjx.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gt2dlmgjtmo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gt2gnsoogkj.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gt2pvrrafmf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gt2epbqcspf.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gt2wqkfciaz.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2ynlafjxj.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gt2zmdwfqct.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gt2urbrxhte.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2mpfxgaba.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gt2himxeiwm.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gt2ousksxog.html

@contextlib.contextmanager
来源：http://dali.dashuyun.cn/Article/details/gt2exfragsh.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2moeuahaf.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gt2tdqwumtp.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kckrdary.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eixkqoqt.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gt2alngsywr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2qewfooru.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gt2bxtviwad.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gt2vmllrkey.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gt2bhabwwxe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gt2kfitkmdh.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghllbljz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmxvmyhe.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjubmnt.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2punhlxyn.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gt2rturphjj.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gt2zdajejpg.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gt2axlzewup.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gt2pxvdxobn.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gt2ituhmfyj.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gt2kkqjivmi.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2wqdlfttv.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gt2adejeeug.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gt2klkpnvyy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gt2ezlgntlr.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gt2jlwnppvk.html

chardet.detect(raw)
来源：http://dali.chenlongwang.top/Article/details/gt2wesisisr.html

[U35] Py：发送邮件
来源：http://dali.jianghu66.top/Article/details/gt2ctrfcemo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzooougt.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2yacdyksg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnwuhayi.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gt2mqflymkt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gt2cnyticdt.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gt2senouyzf.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gt2aupeshjg.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2xmsuyaeh.html

sys.stdout.isatty()
来源：http://dali.9152youxi.cn/Article/details/gt2vcqatdra.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxfsyrre.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2woyfilsi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umbyijlf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyqmrkal.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gt2gzwgrnrx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2owbwrqdd.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gt2mjqdyyoe.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gt2gnyraotf.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gt2qbnsghej.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gt2caaqozph.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gt2dbbrrvon.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2jgnzkzmx.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gt2hshvrifg.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gt2glnscxit.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awnqckoc.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gt2jfwemwdq.html

[U48] PHP：纯枚举
来源：http://dali.jiagoushi.top/Article/details/gt2mqaqzzbj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgfzy.top/Article/details/gt2dpplebnj.html

[U49] PHP：只读属性
来源：http://dali.fzhhl.top/Article/details/gt2qkzesqdw.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gt2zjndnuft.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gt2svwkpgoy.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gt2egdznlcq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaagjvl.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuomtspb.html

[U52] PHP：箭头函数
来源：http://dali.hnqzz.top/Article/details/gt2zonmuvaz.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gt2sapjlsup.html

[U53] PHP：空合并运算符
来源：http://dali.zhixingplan.top/Article/details/gt2gqjxiwfk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2tncgvtur.html

[U54] PHP：空安全调用
来源：http://dali.jqgufenzy.top/Article/details/gt2rzvoleuz.html

$obj?->method()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzzalfxh.html

[U55] PHP：match 表达式
来源：http://dali.tianlin.xyz/Article/details/gt2fwbzxqoz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfbmfnkk.html

[U56] PHP：命名参数
来源：http://dali.dashuyun.cn/Article/details/gt2npgjgtsf.html

f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2cnddjhby.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2diryfcey.html

"值: {$a}"
来源：http://dali.jqgfzy.top/Article/details/gt2nywbmdtw.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxoeruqw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gt2cdcfuinp.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gt2abnaundw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gt2ivgriylf.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhairgkj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2poplzsec.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcxxwxgk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2aorbuxid.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gt2pzniifgh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.birdmap.top/Article/details/gt2jtgkadps.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2fttuabmj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.smart0.xyz/Article/details/gt2bdapppgn.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2rszxemjk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnqzz.top/Article/details/gt2dvptowed.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gt2repedbrt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2sqzkpook.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gt2mbvcnxnf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2pkkeqrqq.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gt2tfsbtgzu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhixingplan.top/Article/details/gt2pmkmzhoa.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gt2fvhdkxja.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcitndfo.html

[U69] PHP：PDO 预处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npspjmvn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gt2evapexrp.html

[U70] PHP：PDO 事务
来源：http://dali.hnxiangtu.top/Article/details/gt2fjfrhcqb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gt2njvdpxyf.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2lfeprhee.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gt2rtbmemsh.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gt2cbjrzeik.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yonumen.top/Article/details/gt2ibfyzqrr.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gt2bcqqspqx.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gt2kmptgzon.html

[U74] PHP：读取环境变量
来源：http://dali.daxiang520.top/Article/details/gt2zawzplna.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cashguo.top/Article/details/gt2ecssqcpv.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2inmmpgxi.html

composer require psr/container
来源：http://dali.cucudq.cn/Article/details/gt2jukrfzuq.html

[U76] PHP：简单路由
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpgtyxuz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gt2bvxxznbx.html

[U77] PHP：模板渲染
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgtgvwvj.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gt2czbibalv.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gt2uuixhwcb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gt2wnkqhzvm.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghpahatc.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gt2kgnkhmkt.html

[U80] PHP：代码规范修复
来源：http://dali.fengsongda.top/Article/details/gt2zlvzqwsa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gt2xezmvkav.html

[U81] JS：初始化项目
来源：http://dali.cashguo.top/Article/details/gt2lcffoiyb.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gt2koxqqjfa.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gt2bphhxbxr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gt2rmkslyqp.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gt2unkpiodb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2svcmzbid.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfyiatew.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gt2hhfnobff.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gt2rtcoeref.html

a?.b?.c
来源：http://dali.shangyingyoupin.top/Article/details/gt2sizamvra.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gt2wsbaaray.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gt2vgdrfdtr.html

[U87] JS：解构默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2giezhqqf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gt2opuofunn.html

[U88] JS：对象展开合并
来源：http://dali.mhx1999.top/Article/details/gt2rqfitlbu.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gt2nsihkteb.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gt2rordbpmi.html

[...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2wcujztxu.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gt2hurnywqa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2mcwscyrm.html

[U91] JS：对象键值遍历
来源：http://dali.nanxinkj.top/Article/details/gt2donzlqmz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gt2yjfpmgry.html

[U92] JS：深拷贝
来源：http://dali.xinyue.icu/Article/details/gt2zfrkklxt.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2sqkcjsuj.html

[U93] JS：模板字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbpndzpj.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gt2zmhxiqsb.html

[U94] JS：箭头函数
来源：http://dali.hammf.cn/Article/details/gt2yjlfdvtu.html

const double = x => x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gt2msfjereh.html

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gt2tukmgmdh.html

new Promise((resolve, reject) => {})
来源：http://dali.sysykeji.top/Article/details/gt2zluqkmsj.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2frlwxgqt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2msfzgtei.html

[U97] JS：并发请求
来源：http://dali.snrcjt.cn/Article/details/gt2yjroxsro.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2cwjqwqxl.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqzdtlqf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hywenlv.cn/Article/details/gt2pocmvram.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gt2wzuysizh.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gt2tzwbonpa.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gt2oyjderfc.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gt2mokwsgsk.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brrdoaca.html

el.classList.toggle("active")
来源：http://dali.smart0.xyz/Article/details/gt2prinriwh.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gt2pavbuxwc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gt2btochtyp.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gt2zojrbvbg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2ymmlgvzp.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbrsmubk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2kawhrsmv.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gt2pkejnsnr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2yujcigdl.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2qgxzemml.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgshboht.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gt2gzhxptuu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2bmuyuaag.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gt2kyrordjy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gt2nejrcqkv.html

[U109] JS：数组分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqtjkbvl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2fegkhuqi.html

[U110] JS：数组分块
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrvpvcwd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gt2kucblbmq.html

[U111] JS：对象转 Map
来源：http://dali.cheryme.top/Article/details/gt2vnxdepko.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2ctdgmkho.html

[U112] JS：字符串补位
来源：http://dali.gotoacloud.top/Article/details/gt2mpeztkna.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2whioyavm.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvbhpaat.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ftzjxdig.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gt2rzujlcms.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2nmbgzcpe.html

[U115] JS：生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2mimlxpdo.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2dwbnxezk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gt2vlqaddvi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdbcmbzm.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bajtnouc.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2hurndvgc.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gt2llfypouw.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gt2lncrsdgl.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gt2yiprehsd.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gt2bhonfwre.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigufen.top/Article/details/gt2edltzuxj.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gt2kdxrymtj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ypmsqmpa.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gt2gykmehbe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klvtcfio.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gt2eqksrfoq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aaohdjjp.html

PHP ............ 252
来源：http://dali.chenzaomai.com/Article/details/gt2etwyjjjr.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gt2cicanbte.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gt2xsqwgjqk.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2killxzdb.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gt2glckbvhh.html

Ruby ........... 212
来源：http://dali.haohaochexian.top/Article/details/gt2zyzgvhov.html

C# ............. 212
来源：http://dali.redwolf501.top/Article/details/gt2fapieckj.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gt2chihmoru.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bslcngwv.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gt2hubmwrdx.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gt2xsxjgfwk.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gt2nsmlsddb.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gt2devaiipp.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gt2dcexmdgr.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gt2gxghxoza.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gt2lxzzuuso.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2hnfdfnti.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gt2hcwdbknp.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gt2hjsjnixp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2icoyynjv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2umiscypf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gt2ekqbpvsx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gt2sxxqfwfl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gt2syrxqnav.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2ttlvnwdy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gt2ouludpzm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gt2ogjgjsxl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjkdczeo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gt2djjuvkce.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2jvpxyykh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2dhcdoadh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2gfppcdow.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2zaksqdpv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2bavxupop.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fafbeoub.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gt2edikmcta.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gt2fyfplqbk.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gt2sufhoxtn.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gt2nccgdtkw.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gt2faeazlre.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2qzdckruk.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gt2hdljpxpp.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2xchkavmu.html


<!-- 参考信息 -->