代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2fxudoqcf.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2sgynjzzb.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2mahvfqax.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2gqakuoyc.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2sbsoasiv.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uovziilq.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2ahofvszq.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqtcjfga.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gt2dlsthvea.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2bhpfqvpa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gt2ytpshlui.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2jzjcmwtr.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gt2qvnngiia.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wuwbppek.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxinkj.top/Article/details/gt2ntkmvben.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2iaxidpmx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gt2yfkfzpwq.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gt2zutokufk.html

for (i <- 1 to 10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2zanwijtg.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gt2zwbsfxsn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2feadbyjo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2zxwxmbiw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugnxvreo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mrzdixqp.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gt2shwoubvu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gt2xhnurtyy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gt2aeuhmche.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2vtrypnvr.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gt2qknjymvv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uafzxexr.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gt2lobqgmzc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gt2ynltsfxp.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gt2gebejbip.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2knqjvzqr.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gatgqgdb.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gt2cvhvbxkt.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gt2tsonstom.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gt2yikqtvcs.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gt2npitbout.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2rzmjvnsg.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gt2xkvdthhh.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gt2rreeliei.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gt2qcfgkyaw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gt2knypjfbs.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gt2lyjuozpg.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gt2xxmpxorr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2ldemrtlo.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gt2raxmlvkw.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gt2lqfxrlvt.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gt2bpxavads.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gt2anjayndl.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gt2konibthx.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbeacacg.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gt2yuyzskxz.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqzrqusn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gt2trskawnh.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhwkkjvp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gt2yimryieh.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gt2ucswewbk.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2qaasljtz.html

[U19] Py：正则替换带回调
来源：http://dali.fengsongda.top/Article/details/gt2cuffuubg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gt2tqzmuskc.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gt2fqwjjqef.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2evaszrqi.html

[U21] Py：自定义上下文管理器
来源：http://dali.c1oappe.top/Article/details/gt2oglosdwz.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gt2autoyptz.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gt2wxywermi.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gt2mictiieu.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gt2xzeooydg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynryfpzn.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gt2ozhsvbum.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2riexnrgf.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gt2siafgadh.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gt2iksfvmtb.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2xbwtcexk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gt2vktnxrqx.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gt2mvvbibhj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gt2sjrochsa.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gt2tbbemdds.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gt2dkrodhzj.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gt2bheualvs.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gt2iryvzqqa.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2bbjynlgk.html

@dataclass(slots=True)
来源：http://dali.meibo888.top/Article/details/gt2wuazaqjm.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggopiodo.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gt2epuqnocd.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpbrzwnl.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2wdmfqruf.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gt2nhwhlaqt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2ibffnyyu.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gt2koqmbzsz.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gt2ogfxdbxo.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gt2ibumrbcq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gt2daageanf.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gt2eizcplkm.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gt2qyubmeha.html

[U37] Py：读写 Excel
来源：http://dali.yj20258888.top/Article/details/gt2tqeardzr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2khiuhqsu.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gt2kmhdbzba.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gt2ddasxqgu.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2bixbzsdl.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gt2zeisupau.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2srxgmmaz.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2tfwhrfwf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gt2kbdafogc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsemuwvw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gt2lxggsjei.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gt2zaanzguj.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2inbfuwva.html

namespace App\Http;
来源：http://dali.meibo888.top/Article/details/gt2twrehhkh.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2tepikmdl.html

declare(strict_types=1);
来源：http://dali.quarkkingdee.top/Article/details/gt2kswetwgw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgufenzy.top/Article/details/gt2slioccbo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2okqncggo.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gt2lhzlzutq.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gt2wvcmlolp.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gt2pqoszjeg.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gt2tehchjjs.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gt2oaudgdxs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2amtijjsn.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gt2lmeamhgq.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gt2rnhapmvq.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gt2rqpvtdww.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vzmppann.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekhncyue.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwfxnxkk.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gt2lpjnfxrt.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gt2gjhkpwfd.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gt2pfawexck.html

$v = $a ?? $b ?? "default";
来源：http://dali.haohaochexian.top/Article/details/gt2ryxgqtol.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gt2lruvtugy.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gt2blliufpr.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2aicxxmbq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.redwolf501.top/Article/details/gt2czxvvrky.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gt2ukdraqct.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2qpfhymbc.html

[U57] PHP：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2xcckycvd.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gt2cposipnc.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gt2ygdmvysf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gt2yrqlvdsu.html

[U59] PHP：自定义排序
来源：http://dali.ehwqpu.com/Article/details/gt2vnsvpvbo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2rgdgtziq.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gt2xavqaddn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.316326.xyz/Article/details/gt2bzvcatje.html

[U61] PHP：正则
来源：http://dali.cucudq.cn/Article/details/gt2epnoxhuo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2zucvwsjn.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gt2hbrbvgev.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gt2ydurdros.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2zwczlvsg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gt2tttelxbz.html

[U64] PHP：目录遍历
来源：http://dali.iojbl.cn/Article/details/gt2avoivigt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gt2gvlojyiy.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gt2widwtzvi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2ogrjzzue.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gt2xvlxnvwe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gt2kbidzeun.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gt2qjgleyey.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yongpay.top/Article/details/gt2odpkrine.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gt2sfkvjlbk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gt2fykfyrpz.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gt2inzfcdmf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hfpthk.cn/Article/details/gt2dtioiqve.html

[U70] PHP：PDO 事务
来源：http://dali.smart0.xyz/Article/details/gt2zqbvpaym.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.0kj1m.cn/Article/details/gt2juudwmuu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyivuft.html

throw new RuntimeException("失败", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2kvqnxlkz.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gt2krxfqoys.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangshuangyany.cn/Article/details/gt2hefeahbg.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gt2tgnrvjeg.html

parse_ini_file("config.ini", true)
来源：http://dali.gotoacloud.top/Article/details/gt2jvipiyao.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2kiwwxkqe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gt2bijansfm.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gt2tbilfzdn.html

composer require psr/container
来源：http://dali.sysykeji.top/Article/details/gt2ezjvwsjt.html

[U76] PHP：简单路由
来源：http://dali.jinqigufen.top/Article/details/gt2xiclninn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gt2pfpbzgmh.html

[U77] PHP：模板渲染
来源：http://dali.yangfankeji.com/Article/details/gt2arafsfbu.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfdsecje.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gt2yvtrrayq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2xnhdnhym.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gt2ppzlklbj.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gt2wbywaqmj.html

[U80] PHP：代码规范修复
来源：http://dali.chenlongwang.top/Article/details/gt2kjxoduag.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvkwzmot.html

[U81] JS：初始化项目
来源：http://dali.ppjwa.cn/Article/details/gt2qxfojkvu.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gt2syvxvgiq.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gt2paliuykl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjxjracz.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gt2gbenddhm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gt2gdzzmluf.html

[U84] JS：CommonJS 写法
来源：http://dali.nwbrower.top/Article/details/gt2wbpdnvxr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gogol.net.cn/Article/details/gt2qpnjyvat.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gt2sexebjsl.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gt2mirjizpe.html

[U86] JS：空值合并
来源：http://dali.xylfe.cn/Article/details/gt2wgxdzque.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gt2rhuiemvi.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gt2dszfwmlc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gt2djiheuzm.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gt2hebapknr.html

{ ...a, ...b }
来源：http://dali.tanke756.top/Article/details/gt2oedpmgme.html

[U89] JS：数组去重
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugtubczd.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2nagevnae.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gt2updnlmti.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2rsfzvoxb.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gt2tewnbkip.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pycfn.com/Article/details/gt2bofvmtgc.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gt2akhqcemf.html

structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2tbairyoh.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gt2xrqxdgjy.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozuampyq.html

[U94] JS：箭头函数
来源：http://dali.sysykeji.top/Article/details/gt2gvvjuryk.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocpwewli.html

[U95] JS：Promise 包装
来源：http://dali.sweek.top/Article/details/gt2qbdzcusr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gt2qorvarkl.html

[U96] JS：async/await 与异常
来源：http://dali.pycfn.com/Article/details/gt2lezinuxg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2lxewlmww.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gt2asguarvj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2qcvnnvqn.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gt2wfwxxnmd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gt2yrluogaa.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gt2eaaosjxg.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gt2qgjbrkva.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2ejrnfhud.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzqxhjfg.html

[U101] JS：classList 操作
来源：http://dali.haohaochexian.top/Article/details/gt2uzllvjdm.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gt2uzwgsind.html

[U102] JS：本地存储
来源：http://dali.tianlin.xyz/Article/details/gt2vstrnhud.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivobhciy.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpurmddy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gt2hqnpljym.html

[U104] JS：防抖
来源：http://dali.zhoulong.xyz/Article/details/gt2rjqavouz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2wuoqxind.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2paybuddm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruvxhxuw.html

[U106] JS：日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2lualjwfc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drbwuigs.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2bctawovq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2uaumdhsk.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gt2oulruvfy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luxwaazs.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gt2stimyopq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2eoqewsqm.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gt2qsntniou.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gt2wkmmkncl.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxueyfdh.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2jefnoyiv.html

[U112] JS：字符串补位
来源：http://dali.cheryme.top/Article/details/gt2htwlluew.html

"7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2biygmqmw.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gt2pknvneel.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2goceivru.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gt2igqzaviu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gt2aewdjujc.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2fgrjyyva.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2vhcwepfe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xylfe.cn/Article/details/gt2vcewzphc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqrfqftd.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gt2lbluohhs.html

npm i -D vitest;  npx vitest
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuolbgqz.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gt2snanniid.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gt2vgcegfll.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gt2draunevz.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gt2cwhzeyyt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sysykeji.top/Article/details/gt2kbpgynvo.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gt2fjojczft.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ghgrvvvt.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gt2uqbxyzxg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gigovmsp.html

按语言统计（条）：
来源：http://dali.nwbrower.top/Article/details/gt2vfqxqsiy.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gt2vgdirbby.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gt2hauyadgk.html

JavaScript ..... 252
来源：http://dali.zhongyouzk.top/Article/details/gt2ubcmuicj.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gt2apnxvpvl.html

Java ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2fhfmbazh.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2seavngvw.html

Ruby ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuignjea.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gt2kkboxdth.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gt2igwewxum.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gt2twcfmjyc.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gt2hzwgqrbv.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gt2cyrlttzv.html

Kotlin ......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2oujctkzu.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gt2vnkpzaye.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gt2omdxpaqb.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gt2iombkrcs.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gt2jsphfatv.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2iozfklcl.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2vlrxrfbt.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gt2koifgexl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gt2sncapgmn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qohjijoy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gt2bavcehat.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gt2cxfybwla.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gt2pwitodfd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gt2doseusea.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2ovyyvbat.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2nmwarghc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2ujmrcmko.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gt2resmaurb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2uqosamhn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2aciabidz.html


<!-- 参考信息 -->