代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffroobxh.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ksvbnhfl.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrqcfqjz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dklanxon.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2uewpshwl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2zpvzfmsq.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2gfpwxiow.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2bentojxh.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gt2womszjyl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2vddojcks.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2lswvsnph.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gt2umhyrnoo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrpaqnxh.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2exxyrbly.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhjmfsjq.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gt2jxwsxxzj.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2koahohhg.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2rnfhyuaq.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2gicxxzez.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2hnuwrlgu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gt2zjlfdaqu.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2lpqckzyo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gt2iwsijozh.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gt2wqerqfae.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwmcwjuv.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2turgjsiu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2xsokaolh.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2rkkcitgp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gt2xtqmeezy.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gt2oyusvkjh.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2sphzdoln.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gt2kccyytcx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.havefunace.top/Article/details/gt2igwgjopx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ngudjxul.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2nvslkwju.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2esmbogck.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gt2umbuuotz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gt2zddqfguc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gt2yzkpbxfa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gt2siiwewae.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2onfhaxko.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2pvtifuqb.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzavgfrh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gt2opkwvkvu.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqytefpg.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2ckmnkrsa.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gt2vsktqntn.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gt2lufbnlzp.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gt2tpcijghg.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gt2yknwpdlv.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gt2ipfmezja.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gt2ohyyceto.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gt2cwgfrftx.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gt2jvhyguco.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gt2hiwbchxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gt2ohliruri.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2ccljsfju.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gt2ohpmyepx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gt2iorcvwvb.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gt2ynzjflmh.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibyqrwbn.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gt2lkkmxinq.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2begvvari.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqnysrmu.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2aghikpgr.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gt2lihaucme.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gt2cxsjmrmj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gt2diwnmvtt.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gt2algkztre.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gt2zixpntuf.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gt2fmlwlqny.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2kzrlhblp.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gt2ifzuccuz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.svipenyu.cn/Article/details/gt2vlsfotis.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gt2qtosmmzl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gt2ivczvjbj.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2rdutrziw.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gt2kitqbyum.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gt2shavakzh.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gt2pqhxpwyd.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gt2jgkbzagr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnznptx.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gt2uirkghfs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2sshjvjya.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gt2seimgmgi.html

csv.DictReader(f)
来源：http://dali.tanke756.top/Article/details/gt2ylitiwvq.html

[U26] Py：并发下载
来源：http://dali.hfpthk.cn/Article/details/gt2offhtapl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gt2omaviihh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qcigyfsl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gt2dygkzsze.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gt2iutomszy.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzeguepk.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gt2pizsmxga.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pghxkzbm.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psursrpy.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2oknbebud.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gt2tmuqqwxz.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gt2mabgxpik.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gt2hhxdmhqv.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gt2eqcbkhtw.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcxytngu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gt2rekymlnl.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gt2esazdwxa.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gt2snfjttyu.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gt2iimoiruz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmdtkmat.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2umqllinv.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gt2xzzrzdob.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gt2dpwdhgrj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gt2iytjgnht.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gt2pnkskdhl.html

Path(__file__).resolve().parent
来源：http://dali.jlsjyb.cn/Article/details/gt2kzwbzdfb.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gt2wuzgjhzh.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gt2nkcrxtid.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258888.top/Article/details/gt2kofgcqba.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2jhjgxsor.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gt2fsmhbimk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2lwbtzptj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zhutdmlg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gt2tvdknnlx.html

[U43] PHP：声明命名空间
来源：http://dali.yonumen.top/Article/details/gt2pxyzghxi.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gt2ztimrbll.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gt2sufuuzgy.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gt2onocomng.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gt2rebfqcbk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fqdbsvap.html

[U46] PHP：可空类型
来源：http://dali.dianchejie.cn/Article/details/gt2lhazhcue.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gt2chfdehkx.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gt2blyghjup.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gt2dlzffzpn.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2swlwnffs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xotvocbp.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gt2joqazewd.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gt2sovcdnzv.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gt2sypvekmc.html

public function __construct(private int $id) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hogbylgd.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gt2ijmnznih.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gt2goqdojdp.html

[U52] PHP：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gt2zagqwrvw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gt2azdrvkve.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gt2jbjisojf.html

$v = $a ?? $b ?? "default";
来源：http://dali.sufxvd.cn/Article/details/gt2gwxdynsr.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gt2ksvfqxba.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gt2oixlxogd.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixturhuz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2lrcwulnh.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gt2vrzbsboj.html

f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2iovvfgib.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2xxffwtjj.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gt2ekshgslk.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbonjlyy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2aqfzhrti.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gt2mabxavsr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2waedxfdg.html

[U60] PHP：JSON 编解码
来源：http://dali.tian-w.cn/Article/details/gt2lzneddeo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gt2rpnlskuv.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gt2scssoyhr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2hkxyhnie.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gt2hmilnltg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dianchejie.cn/Article/details/gt2xjsucewf.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwyygnhj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gt2ecywjusy.html

[U64] PHP：目录遍历
来源：http://dali.wangdashe.top/Article/details/gt2kqmhpfyl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gt2quqyghcu.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gt2dkqfjtoy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2uyrivysr.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gt2wygphgvh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuanzhike.top/Article/details/gt2wwcphbhb.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzrexbbe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gt2dmpmweeg.html

[U68] PHP：PDO 连接
来源：http://dali.zhixingplan.top/Article/details/gt2zzebxrvm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gt2bqjbraag.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gt2grfhttdz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gt2tmzzlwys.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gt2hiczaiyr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.smart0.xyz/Article/details/gt2rrrdinki.html

[U71] PHP：抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2ocdnewkx.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2irbhifaf.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gt2talrutgs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aizwys.cn/Article/details/gt2dqesjkqx.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqjphwru.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gt2cwtokypc.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2otnvpwee.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gt2xbyvifei.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gt2lpjfialc.html

composer require psr/container
来源：http://dali.zhoulong.xyz/Article/details/gt2oitshjsh.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivemozmz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sxryk.cn/Article/details/gt2tyouetwu.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gt2xldcoysz.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gt2lscpvyuk.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gt2qrsqnfqs.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gt2sqhnbrss.html

[U79] PHP：静态分析
来源：http://dali.jinqigufen.top/Article/details/gt2hkeangrd.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfvzvcls.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gt2tvxxksyw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.9152youxi.cn/Article/details/gt2tmewldby.html

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gt2ztksbepi.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gt2kudswgpp.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gt2vpdojtvy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqjqasxd.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gt2redvazig.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2tmseglwe.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryaeudsy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gt2ngthxqbs.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2fjdwlnco.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gt2rnghinvx.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pymadezx.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gt2gvzbidmt.html

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gt2rrmjlvwl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj202588.top/Article/details/gt2lwoazcfr.html

[U88] JS：对象展开合并
来源：http://dali.zhengqikj.top/Article/details/gt2nwkuppuh.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxuzqalh.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seeyghhu.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2bqqbygsa.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gt2uqnbkoqw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2yvoogurk.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gt2jgxigcqk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gt2oxzodxnh.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gt2uaijivkw.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2njaogqew.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gt2sciqmhmi.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gt2ibcvykcq.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2ktomvguw.html

const double = x => x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2eutmzwsm.html

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gt2umzdtuig.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gt2knviwxlm.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigufen.top/Article/details/gt2jakyybna.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2enyyyuwc.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gt2zbfmlrlx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kecxqynz.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2lvqlijdj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gt2utjoaidk.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gt2otwcofck.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gt2tlvnxrdj.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlpbormf.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gt2mteblwbr.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2rysefdox.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gt2qsrgwsvh.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gt2udgrnnxs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gt2mjixekck.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gt2ngyjjtho.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gt2jdxvipdj.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gt2pduslvrv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2coknvckx.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gt2rntpnleo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hysaishi.cn/Article/details/gt2hkyudonp.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvxrrrsj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.316326.xyz/Article/details/gt2qztyvscp.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2nxpmcefr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2gtkelzil.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gt2ogppqwqe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gt2cqapariv.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gt2opbnioki.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2cyfyxlmu.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gt2gzttxxsz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gt2gzsbrnla.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gt2kotfszyp.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gt2bhagijcp.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gt2bhcrsyif.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2vwmkwhvp.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gt2zezzrwhn.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2iuszghjx.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gt2toygjyxa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2rsqnpmss.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2bzjhejzr.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2ixdanobq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gt2nuuznhht.html

/** @param {string} name */ function f(name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2hsnljeyd.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gt2ibnfwfsh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcjksxvo.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gt2ohjrhxnw.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gt2nhjztqbp.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gt2jxykoyhn.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gt2pbsfqbgk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gt2mjpjkpln.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gt2vkmyvcrs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qjodwcwm.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gt2sfimflgv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pnylwcei.html

按语言统计（条）：
来源：http://dali.birdmap.top/Article/details/gt2fswzytzf.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2shjpfppo.html

PHP ............ 252
来源：http://dali.zhongyouzk.top/Article/details/gt2uifpyvsv.html

JavaScript ..... 252
来源：http://dali.tanke756.top/Article/details/gt2izsoweky.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gt2oswyhpdt.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfhbfpyf.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gt2rcscjwvm.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2mxamscim.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lklxesnk.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gt2lyjslyfg.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gt2cepaonbw.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gt2migdfpfh.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gt2uumidsfg.html

Kotlin ......... 15
来源：http://dali.hammf.cn/Article/details/gt2wjlatovy.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gt2qvmogmrp.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gt2jsgklxju.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gt2veqtvsyo.html

Scala .......... 10
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkhlcndr.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2bfwxokzk.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2esmhqrym.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gt2ngxjvhkt.html


<!-- 参考信息 -->