代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gt2xvuuqqmf.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gt2emosqbco.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2vxrgcfoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ipnwrlyx.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2rktwrqei.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2dnaucbsr.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2maldjmcr.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gt2nywkyhtt.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gt2lkjkuvqx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2rhgnzwqm.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2edwjaiam.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gt2yuhxuvea.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gt2gzfstslb.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2bcjdzwbv.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgoxwmfw.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2yiirnknn.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gt2otpbyybc.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2fopcovww.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gt2yrregqkc.html

[T54] Scala：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2yfoqofto.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gt2sswfqurj.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2rlbhiwqt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rppidanb.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gt2rfktliqu.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vneqboee.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2gdcwcwit.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2vigbqyll.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2rppjyths.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2nloiocda.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gt2htkdxmin.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2bwevjbzc.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gt2cuhbriwc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gt2hczzzzhz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cllngifp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gt2cmrwghpo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2cgicutta.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2nlryziym.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gt2moquyivy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gt2kcwuajqc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2glowrftc.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2boifxmbr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sxryk.cn/Article/details/gt2scpyagfj.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gt2xestzdkl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gt2qifcyakx.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gt2kebskjst.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2uydbvyio.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gt2zfoxcegj.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gt2fvvvvruu.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gt2wflgyjpf.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gt2ofbczkef.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2civiaipq.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gt2sodyzode.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gt2fiqkjtin.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gt2gbifevbc.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gt2cjfehmjn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gt2peocrkya.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gt2keabmkzj.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gt2yyaveqxh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2dsrmseqw.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijidhzxn.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2umwxmldr.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gt2seiokpvx.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gt2bdvcwmrp.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2glsrhkgg.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gt2iwiyqmek.html

t = time.perf_counter()
来源：http://dali.gaohongyu789.top/Article/details/gt2qkjxloqq.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gt2oogouecs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gt2wwouwxjh.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gt2cknvlvtk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gt2tlmsdevk.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gt2sekskzds.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2wzfrnvmz.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gt2uffiqrma.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gt2mmscoadn.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2oypkhtnv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gt2yyebjfst.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrhintgg.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gt2gvvhzrlv.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gt2tgxpdmqg.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gt2aijmuktb.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gt2reekpqga.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxfajoyc.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gt2mgjxpace.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2qoftzwkj.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gt2riflxazh.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gt2exmobblf.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpghrpqo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gt2ymaipbnc.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gt2tyuycvjb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gt2psqnimwg.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtoawcar.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gt2cmweefuz.html

[U29] Py：属性校验
来源：http://dali.sufxvd.cn/Article/details/gt2pmygsnoq.html

@property 与 @x.setter 配合
来源：http://dali.nanxinkj.top/Article/details/gt2kmqidwej.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2imbabctk.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gt2fvxeqcul.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gt2auvatgih.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gt2cdlbknpe.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gt2jlpnhvrc.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gt2yxdpuash.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gt2hamerrid.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2yceoblna.html

[U34] Py：判断编码
来源：http://dali.cdnleiting.top/Article/details/gt2hddyoytz.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bugrbtzv.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2lutpioxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtvcdvwm.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gt2asowhudl.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gt2tmppcdxm.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gt2jafillko.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gt2inhhlxem.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2jhvziuoj.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gt2qslgknwq.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gt2geatfune.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gt2rcwtfhsz.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gt2dnmpnyrg.html

print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2fwkxuryi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufeouauu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2ywlydbmv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gt2vworybcn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymflfkss.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvyhhiit.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gt2zddzekeo.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gt2rlpixicx.html

declare(strict_types=1);
来源：http://dali.mhx1999.top/Article/details/gt2eljuiqcz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gt2khsmqngs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2ghicavbs.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gt2avhiydqd.html

?string $name = null
来源：http://dali.cqqwz.cn/Article/details/gt2lglwsout.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2vobrzvsa.html

int|string $id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abpwxmpu.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2aelivfpy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xinddrrn.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpczfnvv.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gt2mggpdjpa.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gt2onaqfbiq.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gt2edyokpbf.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gt2yynnqdvr.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2haqpjmtt.html

[U52] PHP：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gt2cbbmdsbe.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gt2mrypfeeg.html

[U53] PHP：空合并运算符
来源：http://dali.zdqjudy.top/Article/details/gt2nheeizje.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gt2kttharel.html

[U54] PHP：空安全调用
来源：http://dali.zhongyouzk.top/Article/details/gt2txdfqwga.html

$obj?->method()
来源：http://dali.jlsjyb.cn/Article/details/gt2xtkynzvt.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gt2tyxmjymy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrwdvgiw.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gt2wmgmrlro.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2ksfuvlxv.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2awmjnwzn.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gt2iemmwwau.html

[U58] PHP：数组三件套
来源：http://dali.zhiwuduotai.top/Article/details/gt2srftzstb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ianzryhf.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gt2ynldswxh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2cqmxjzhg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gt2oozjyyyp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gt2soyishlj.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gt2metllfkd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2xivopyin.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltatycie.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gt2cmlufxiy.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gt2nzrpwnnc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cddvxvmk.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gt2clvcsmrf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffclaxah.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gt2bumcmtjz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2hkgfwieb.html

[U66] PHP：设置 Cookie
来源：http://dali.shzxlz.cn/Article/details/gt2xvcgozox.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2hfyelnnm.html

[U67] PHP：处理文件上传
来源：http://dali.dianchejie.cn/Article/details/gt2ukcottka.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gt2pdnnzsuq.html

[U68] PHP：PDO 连接
来源：http://dali.aizwys.cn/Article/details/gt2rcjwxwxh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gt2nhtldgpg.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2hxjtndkx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guannengcc.top/Article/details/gt2cwuqqhxn.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gt2usehenct.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meopjmsr.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewhevvli.html

throw new RuntimeException("失败", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2gesdelar.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gt2olqqjqxz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gt2iqgkjasz.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gt2ejemqggw.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gt2bhygixkb.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2ngejdvho.html

getenv("APP_ENV") ?: "production"
来源：http://dali.bjfxy.top/Article/details/gt2hmvxhkdh.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gt2iarrqfhh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lriosuxi.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gt2anqksfoy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gt2ehxqtsga.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gt2hmgzagkp.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edydevhy.html

[U78] PHP：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2awketikg.html

composer require --dev phpunit/phpunit
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quzihezx.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gt2yjaoxzvo.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gt2qnopvxfz.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gt2uvpfrklj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gt2wxukwjsz.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gt2qzxfjmaa.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gt2utprmvsc.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gt2cigskesh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gt2ntnbuvtw.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gt2ayjpwrkn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2ooqlvrun.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gt2boehiwqo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj202588.top/Article/details/gt2bbwpjegz.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gt2myzcamwg.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gt2izijkzaw.html

[U86] JS：空值合并
来源：http://dali.9152youxi.cn/Article/details/gt2jrnbbdvu.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gt2teaxvzcs.html

[U87] JS：解构默认值
来源：http://dali.yangfankeji.com/Article/details/gt2qgwecxpu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.redwolf501.top/Article/details/gt2bwqmbfyw.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gt2sviqmslv.html

{ ...a, ...b }
来源：http://dali.quarkkingdee.top/Article/details/gt2gujlowqd.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghgjoxiy.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2xfoblrjw.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gt2pmhzefqq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2slekqnjz.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gt2jjnxdzav.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gt2qkfzjmbo.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klocfcxw.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2lhkqsdcm.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gt2nlixlhcw.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2eafopohx.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gt2kcxutvpm.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gt2strusyxr.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muomhjnx.html

new Promise((resolve, reject) => {})
来源：http://dali.hammf.cn/Article/details/gt2vcwenggh.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gt2pmdattyw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2ntdikzgi.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gt2lubrvpfx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2kgwlilmt.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gt2rjbggozf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2bncphszs.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gt2ssrlzebp.html

el.addEventListener("click", e => {})
来源：http://dali.zhixingplan.top/Article/details/gt2ztsddeeh.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kalwhaqv.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqdgjeev.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gt2rmzukwhn.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gt2mamydvso.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gt2oxdybakx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cdnleiting.top/Article/details/gt2zgrheakj.html

[U103] JS：定时器
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbjawflu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gt2mrqklukb.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdrxlxil.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2qhddbjaa.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfuzpiie.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuanzhike.top/Article/details/gt2kmvdnwuy.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2ktcoxskd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gt2lqficnkb.html

[U107] JS：数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2pgbdanmu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2bonhvrdi.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gt2iwpzhhfd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hysaishi.cn/Article/details/gt2ajmsxosa.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gt2pbaygeue.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mquqogxt.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gt2blnkbumx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fzhhl.top/Article/details/gt2zuodcmjk.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gt2vhvznieq.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2hbvhvbbu.html

[U112] JS：字符串补位
来源：http://dali.yj202588.top/Article/details/gt2ajqfqlkh.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2ysiblkyf.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gt2oxbptips.html

s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2gssatcnt.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gt2zfyocwhr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2pcgclptv.html

[U115] JS：生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2fosqlbre.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2pwikjehb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfuawpks.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikdukxxs.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gt2bkzjlnht.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gt2kqawgwnk.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2xekjiwci.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2ssfomqww.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gt2vagyzdso.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gt2ihbxbcdj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gt2tjmkfxic.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gt2eyqbxrxm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjyiotig.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gt2xzybozri.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2dlmcxfda.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gt2oybcfjog.html

Python ......... 252
来源：http://dali.cdnleiting.top/Article/details/gt2nckpmuni.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gt2wfmiitlr.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2uynirwcq.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2poiryabu.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gt2jnsejkte.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2wfzjilrg.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqdjtcsy.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2jnkzzgrw.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gt2uamgoxte.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gt2qmpqsitg.html

SQL ............ 90
来源：http://dali.daxiang520.top/Article/details/gt2oucyjzsk.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gt2aplzccru.html

Kotlin ......... 15
来源：http://dali.cucudq.cn/Article/details/gt2wkuhzpwo.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gt2oebmqtso.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gt2jdkhkagz.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfvegwtl.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gt2iriillls.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2sblqtuqv.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqichyyz.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgoctdpl.html


<!-- 参考信息 -->