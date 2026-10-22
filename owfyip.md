代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnqellto.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2wovspfeq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2mthsfnza.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gt2elccamkf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjmomsjx.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2gdyahegp.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2tyvsnedg.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gt2oozrmelp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypmhkilp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pbotbzrg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2mavzcqfo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hmpwffoy.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gt2fxnsvyfu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzgblecp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gt2fqtopbgx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gt2prmkfzdx.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwbuwcph.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhixingplan.top/Article/details/gt2vdejgjmb.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkmqcqsp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gt2hposdgpl.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gt2wjiwnrva.html

list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ufrkownl.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbdtyxix.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gt2llyxzmve.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qusftble.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gt2efwhdcnb.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gt2qtjggkrh.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gt2ewmtnswk.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gt2lcyrsnxo.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlnawfou.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2topfivfe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gt2ckxvjxxv.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gt2stzsbcpj.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdkaudbo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gt2qxohrhhx.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2senbtooe.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gt2gvnimbeb.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gt2vbijcwwz.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gt2dhvianar.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvgfvkgs.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gt2dpuvnqie.html

t = time.perf_counter()
来源：http://dali.meibo888.top/Article/details/gt2glipcwph.html

[U16] Py：命令行参数解析
来源：http://dali.0kj1m.cn/Article/details/gt2wmwrqqpa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gt2ridtopah.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gt2vfhnlxiz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hywenlv.cn/Article/details/gt2rzesvlsc.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gt2qapgksbt.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2ndpyfmhm.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gt2caesayje.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gt2ugprkhcp.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2ephpomnt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gt2uyyntszc.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gt2hrouvakq.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gt2royjvqlh.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygeolzti.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gt2nectfwie.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2gvflgaqb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gt2ddmdbddy.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gt2aykdlraa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2iimjbnzj.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gt2jzuoqtuz.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gt2tnqyidwe.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gt2didobace.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gt2ntniuwth.html

[U27] Py：异步 HTTP
来源：http://dali.0kj1m.cn/Article/details/gt2jqronxtz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gt2ffvcghxt.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gt2acpwwwsr.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gt2phsoteiw.html

[U29] Py：属性校验
来源：http://dali.xziqi.cn/Article/details/gt2ottsffwl.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gt2myscvppr.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2wzawikwh.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gt2vxqmsbng.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gt2keqqbcsa.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gt2aufxpbho.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdzfpfpk.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gt2xfyywdad.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gt2ydfjejxc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuxming.cn/Article/details/gt2ztgaohpb.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gt2uevbsmvf.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gt2bitbvwyc.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gt2uuuzinpx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gt2ezkkbftj.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2xedijimt.html

schedule.every(10).minutes.do(job)
来源：http://dali.guowangkeji.top/Article/details/gt2woeatftb.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcpvfive.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gt2hffmwxbr.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gt2wooraddv.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gt2omuxbioh.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gt2qwyzbbqn.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gt2lwvddfdb.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gt2qbmakkfg.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2uvyjwpza.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gt2porijqvr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gogol.net.cn/Article/details/gt2ldtsmuvz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gt2ljqddzki.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gt2uncnxqho.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2ouqghrzv.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gt2bfewjtwl.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gt2dmxopjod.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gt2ioocjfum.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqvufnjp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2yvkajjxf.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gt2uyddxetd.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gt2ayqjxjoa.html

[U47] PHP：联合类型
来源：http://dali.snrcjt.cn/Article/details/gt2xfpfpsqu.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gt2wfatilrq.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gt2mcyrwuqz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnmqeaad.html

[U49] PHP：只读属性
来源：http://dali.yanxiufei.cn/Article/details/gt2lwtxrmrj.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gt2hnqcixip.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqbtmkhl.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdrdmdya.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gt2wpadagvz.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gt2jdrepiwc.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gt2gcnvllte.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2gamsfmvx.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gt2gqzhasmv.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elfwuonx.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gt2hgcxijnp.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gt2jpqwimvx.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuaiqqcw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gt2ssewjtfq.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqhmbjha.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2jddoymje.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gt2xkowbbdy.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxpzdrzx.html

[U58] PHP：数组三件套
来源：http://dali.dianchejie.cn/Article/details/gt2mggzzscz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2alakhlsc.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gt2dipidmoa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gt2jnmlhvwy.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gt2muclvksj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gt2phvjtohc.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gt2vzsbrzvs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycszuvwx.html

[U62] PHP：日期对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2cumkiuoe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gt2qqvwgxno.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gt2iftucmfg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gt2olzzwutw.html

[U64] PHP：目录遍历
来源：http://dali.iojbl.cn/Article/details/gt2kakazmup.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmpajyqo.html

[U65] PHP：会话
来源：http://dali.yangfankeji.com/Article/details/gt2gqrlajjx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2jlghxolg.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gt2oshrubfd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gt2kzfxompt.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gt2jnundwcv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gt2qguntfqo.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gt2dgfcbzlr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gt2yahwebqv.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gt2uxbatawe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cdnleiting.top/Article/details/gt2rjkxqhbj.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gt2mleeobtb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gt2pttdojbi.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2mthvucqv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zdqjudy.top/Article/details/gt2pupsgplp.html

[U72] PHP：写错误日志
来源：http://dali.316326.xyz/Article/details/gt2urapegmy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gt2huiguorl.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gt2evzrxnyx.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gt2nkqdynxx.html

[U74] PHP：读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2gtehnqxa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usdqarnt.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gt2cpuincjq.html

composer require psr/container
来源：http://dali.316326.xyz/Article/details/gt2gcyolgzf.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gt2ofgxvgiy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrfrwazd.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gt2irrtrskh.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gt2xomhsmir.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2lqvchewe.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gt2xzggyilh.html

[U79] PHP：静态分析
来源：http://dali.hnxiangtu.top/Article/details/gt2zpqtoyyd.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsnbslsc.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxicbmlo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ppjwa.cn/Article/details/gt2lehfbwre.html

[U81] JS：初始化项目
来源：http://dali.xylfe.cn/Article/details/gt2nvjvxyld.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gt2cbbhzghb.html

[U82] JS：package.json 脚本
来源：http://dali.nanxinkj.top/Article/details/gt2bncepnte.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gt2lurgnfvn.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmzwvcwr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gt2aayybsrv.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gt2kxeeymwo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gt2khhgrznm.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gt2tcnbxglu.html

a?.b?.c
来源：http://dali.fengsongda.top/Article/details/gt2utnrijly.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gt2qqqobfat.html

a ?? b
来源：http://dali.redwolf501.top/Article/details/gt2riyjexvi.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gt2drphpvvu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jianghu66.top/Article/details/gt2rohvhduh.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gt2qumqutvd.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gt2opgjraul.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gt2pyggwzin.html

[...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2bqjpmrvg.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gt2obxlduhd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2cxnnnsca.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gt2aqewrlto.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gt2xjtgbzpn.html

[U92] JS：深拷贝
来源：http://dali.yonumen.top/Article/details/gt2sthfqdfy.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2dtzlkmxq.html

[U93] JS：模板字符串
来源：http://dali.c1oappe.top/Article/details/gt2gogavapm.html

`共 ${n} 条`
来源：http://dali.yongpay.top/Article/details/gt2ezswgtij.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gt2hqpjlmzo.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2tmrbedau.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gt2lygrlnav.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gt2tsvdypry.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gt2wzdekcef.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2vknzxvar.html

[U97] JS：并发请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvuinhzt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2zxhuldma.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2vetutvwg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gt2zykuxesw.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gt2xidcapfv.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gt2yapjaxec.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gt2rtvngjzo.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gt2oihdfpef.html

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gt2ekilzpam.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gt2ubnmrudq.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkpctnqe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gt2lhmqwxyi.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gt2saxwyuwm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gt2pruisjjc.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gt2iwterelx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2zdgefyni.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gt2axxqcbtu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyvqdnpe.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gt2hilhalyl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gt2bgnmkbgb.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2baiinxco.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2atugbuqk.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gt2lqyitdsw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.andypj.xyz/Article/details/gt2dfrxosjw.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gt2nctgimar.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdfeoyhx.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gt2zjgftqsh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.smart0.xyz/Article/details/gt2wupaqupu.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gt2nvlbqycy.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gt2thwjyapr.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gt2eazjryll.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2rwrkkxei.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gt2hyfrvhea.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2elccwhyn.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gt2ooosisjh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2qcvgbjyl.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2gnzzhxfm.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2mfqhvapi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gt2tmeuqsdn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2molykrdu.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gt2tttarjuo.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gt2ojqhwulk.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gt2oblixzhv.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gt2swvriawt.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gt2qqignzqs.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gt2qxqropyv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gt2xxxxkmdi.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gt2jcongtyx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2sdxyrjwz.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuujhlnp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmbpxerq.html

按语言统计（条）：
来源：http://dali.mhx1999.top/Article/details/gt2rvzrucwc.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gt2bnzpwbgn.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gt2uuumwkan.html

JavaScript ..... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiiiqunr.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gt2infqjwjw.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2ryqesnsw.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2ycpmfcxt.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2yymcdsjt.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gt2cpnhvefu.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gt2yoylpleg.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gt2gqffowuj.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gt2evtqmypi.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gt2bzipcoed.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gt2ntaemxsb.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gt2eqyvanjy.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gt2rtopvcil.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gt2kbqzlxzg.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gt2urolpdoy.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2qbcfnneb.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gt2aleypdsi.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gt2ofzenbat.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eamifump.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2fvgcpzpy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2ntylghbg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhaereax.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gt2kfmovtrm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gt2ksaomiwo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2bxbcpsra.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gt2lzujnpuu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2jhdoywuv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gt2lmmrrpnj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2tuaeofnj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2vpozyede.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2xdkkrqwy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2vezslxxc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gt2shhgkbtw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2qylahukr.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gt2wmitikqm.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gt2vzeuvajr.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnlbhjnm.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gt2funyvlii.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gt2temsaeqm.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2cescmgub.html

合计                                  2106 条
来源：http://dali.zhongyouzk.top/Article/details/gt2cccdiclb.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2zrfgopsg.html


<!-- 参考信息 -->