代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gt2ezizlnkc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2gpfrzitc.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2vwasuoih.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gt2ztrwcxgf.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2lpnkufpa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2mynuwtck.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2gyccbgtd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gt2lrynimgk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gt2alhcmfat.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2ecotvbly.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2pchnqqtx.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2tohpgnut.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2pktnejeo.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kerfbkew.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcchxced.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwzbggpn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2zcjfmwvy.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2ebkkhqdo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gt2clkmrlxv.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gt2bswsosuy.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2htqcjskd.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2yaxgprpb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gt2srwnsqav.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgmxcbbf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmnoxmuj.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gt2uquhyxmf.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2yqnpookm.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gt2vlnirvew.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gt2mbuqpnll.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htpxpugn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2zcitqgyb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fisdqnbw.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gt2kqrphxlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gt2ydrwgffl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hllgsaqj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2fktdyier.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2zgsmmexo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjvlzins.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gt2gsxjgydg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gt2xextdthn.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gt2cefvhnnc.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2czjkocqt.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gt2uxfmuidi.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2ilpttund.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gt2nievnqrr.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gt2iiwafvgn.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gt2osviltci.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gt2dcsdlxpz.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2adlupexq.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gt2adkjbfnf.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gt2iqldfgdu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdaaexkl.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gt2ixjmplzj.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gt2vdjgprhl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhengqikj.top/Article/details/gt2rbedxrzo.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gt2ubkeknwd.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gt2saxzntvj.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gt2nlhkoabt.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gt2sueyelvg.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gt2bxrbqmuv.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gt2egephozx.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gt2anwxulow.html

[U16] Py：命令行参数解析
来源：http://dali.havefunace.top/Article/details/gt2zdgmgddq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gt2uivnoews.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gt2xmeyrsht.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuanzx.com/Article/details/gt2pnuknrcv.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjzdbsyy.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2zgrkdquh.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gt2vnocgutq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gt2riqwztlk.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gt2hbybczga.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gt2yunkeucb.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gt2hykpwvgd.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2omewqfzi.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gt2nafqsveg.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2blmnxjcg.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gt2wujpfnjn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gt2zyhbvgsp.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpuwnpbo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2kxwzvrpi.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gt2bvhzmpel.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwhwapiv.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gt2nnqzuczn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gt2hscrhgye.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gt2yslowvgk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gt2ucgbffed.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gt2taqyknyz.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkyhqiug.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gt2ebxxewot.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gt2qkcqajns.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gt2mqddjxrq.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gt2qloiskmi.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2mzsepjcv.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gt2qovbjxfj.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gt2yooypakl.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gt2hdiwqozn.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gt2rrzxfqxf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngvceuzz.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gt2ftjqiyev.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gt2rjrtfujc.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gt2zeqlcuvf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gt2vkrqmfpb.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2pnqahyok.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gt2lyflsdbi.html

[U37] Py：读写 Excel
来源：http://dali.jqgfzy.top/Article/details/gt2lcvrqqzb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gt2npmagltp.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gt2vahijfrd.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gt2egfcnkxn.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gt2asndeyfp.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gt2multyqfo.html

[U40] Py：打印到标准错误
来源：http://dali.tianlin.xyz/Article/details/gt2dehxtjek.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2frkhnnzl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyeczke.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gt2rpbimilj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gt2wgyiplgm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytkgjywq.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gt2pjqewpcj.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gt2xperipan.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gt2dpwtqfhv.html

declare(strict_types=1);
来源：http://dali.svipenyu.cn/Article/details/gt2xkqejrce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2giasumyx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2gracycfj.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gt2ucmjdrvl.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gt2hykuuuiv.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gt2wxxsdipw.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vslpvlvz.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gt2apjkitsq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2euipcxjx.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gt2zwwlvmga.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gt2qwbrjxdu.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gt2ofbkxyft.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gt2zluhaeeh.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gt2jurfdmsr.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gt2iwcdgnpi.html

[U52] PHP：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gt2rorwqvks.html

$double = fn($x) => $x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2bhezhyvy.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gt2txwkpyst.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gt2owlotysj.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gt2hhhqbifp.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gt2pvzdwqln.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gt2mirkuatl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gt2jwaxazdl.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gt2wlatmdwy.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2qmgoowns.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2bwvxzkfi.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gt2qntarwrj.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gt2uzoqbdoc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2cttrweci.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gt2phgyxoob.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2yowqdqmf.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygsghyws.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gt2gftfnfoj.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gt2qwgpnbpr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2wqmnhrwo.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gt2ggbxpqec.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gt2sbegcpix.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gt2pssjmijl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gt2nlhpoqjx.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gt2qiiaxhtk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gt2kphfbjya.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gt2vgopqxzx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2eotdhfbi.html

[U66] PHP：设置 Cookie
来源：http://dali.cdnleiting.top/Article/details/gt2zpqpvqpf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.smart0.xyz/Article/details/gt2nnbhmqaq.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gt2voclcghq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tian-w.cn/Article/details/gt2rrpzwaje.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gt2hcpvlrny.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gt2muzhpnfc.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gt2ppdmnnpa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gt2burtxhdv.html

[U70] PHP：PDO 事务
来源：http://dali.havefunace.top/Article/details/gt2iidrdcxx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gt2rfwzcpxb.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2sfkrdqmy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2wgylcarr.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gt2inamjnqc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gt2pupgtzju.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gt2xtjdauln.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gt2abizgqzs.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gt2cvypnuzh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gt2qpospknm.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gt2wsafxhdi.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gt2wdzvldkn.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gt2hruomock.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gt2ykoylppi.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gt2ynwxgsbr.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gt2rxshubed.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhqkdcpv.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxpswfdm.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gt2tgndgqfu.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpcdipfi.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gt2accflonf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gt2mvrpfhvk.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gt2ycjxqoaz.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gt2gzgqowdu.html

[U82] JS：package.json 脚本
来源：http://dali.sweek.top/Article/details/gt2glykolgc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.haohaochexian.top/Article/details/gt2tbeznkbj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcuadeu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gt2odunwdow.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcbqcam.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gt2lfmkdrfu.html

[U85] JS：可选链
来源：http://dali.316326.xyz/Article/details/gt2gfoxrsnj.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gt2obekkmqu.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gt2nhjgtswg.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2crungigq.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gt2qimankec.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gt2xpscioau.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gt2obbigwlf.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gt2stfdlmmc.html

[U89] JS：数组去重
来源：http://dali.tian-w.cn/Article/details/gt2ejyjonqa.html

[...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2cjctirfr.html

[U90] JS：数字数组排序
来源：http://dali.ydzc1.top/Article/details/gt2vvhptiss.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2bwtncriy.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gt2iqnbhypn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigfzy.top/Article/details/gt2jxkuvqsm.html

[U92] JS：深拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2iqzsqgjw.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wymslcot.html

[U93] JS：模板字符串
来源：http://dali.tianlin.xyz/Article/details/gt2jrryabvg.html

`共 ${n} 条`
来源：http://dali.mhx1999.top/Article/details/gt2fpjzoyai.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gt2bjnlcptl.html

const double = x => x * 2;
来源：http://dali.cdnleiting.top/Article/details/gt2albtwgti.html

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gt2tkyegcmc.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftspjyde.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfygnvta.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2ugciztru.html

[U97] JS：并发请求
来源：http://dali.yuanzhike.top/Article/details/gt2qpahnyto.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2uehixgqs.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gt2ipfchzbw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tukqfswf.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gt2qhwnwlqk.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gt2enuylocm.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gt2ltfscivd.html

document.querySelector(".item")
来源：http://dali.c1oappe.top/Article/details/gt2bbgryxad.html

[U101] JS：classList 操作
来源：http://dali.tian-w.cn/Article/details/gt2geowdvfp.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gt2kilateox.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfpchlfh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gt2jubvvsee.html

[U103] JS：定时器
来源：http://dali.aizwys.cn/Article/details/gt2zxskxjxg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gt2lmgdzejv.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gt2optabtin.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2kcpuqfga.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gt2ksgcgsew.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gt2miphnnnu.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2zdbgecoh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gt2focpnqrs.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2jhixjkmy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2nhjzffxo.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gt2ufokmkha.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gt2xrtrejod.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gt2inyfvczz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2jcyxoayh.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gt2qcddokpk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gt2dpkyewvy.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2ndfnhvxb.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2zcvaldli.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gt2twybcssv.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2czhfoavs.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gt2yhsbdayh.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2rqwipcmo.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gt2jqvjlafa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lahtcdmh.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2bgnwghle.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2rowvldyj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gt2jnyynwoq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yuvqmlda.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gt2yyqyqubq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyhhppof.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gt2pmtytght.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gt2gcrnetmn.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gt2lhcsfabr.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gt2kisomdeh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gt2aopfsufy.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzgfxluc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jhkxowfj.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gt2fsuuiyzm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egjdmrvm.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gt2naiqooqo.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gt2dqlsjhur.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gt2ehfgohpe.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2odhhplic.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2djqjwnrt.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gt2yfiybxeo.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gt2stvsagtw.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2afqlslsk.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkdfnqzz.html

C .............. 30
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtbxzjny.html

C++ ............ 30
来源：http://dali.xinyue.icu/Article/details/gt2jcacwyhq.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gt2vjfztfcj.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gt2qgytgdrd.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gt2oomzqkkq.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2sfvnyzac.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gt2vciirduv.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gt2xaziljwm.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gt2ssonhxyh.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2iromkfqy.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gt2bkpeczgr.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gt2htphorqk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2mdglormw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gt2nnuxabeo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2eycsyhhu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2eoklcwkx.html


<!-- 参考信息 -->