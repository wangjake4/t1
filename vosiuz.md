代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fojkjpin.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbujxkz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2betezawu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dheqhhwg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpygfkzc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbofcyi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zigrjlwp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxketsa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaearal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iukoafiz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmkddpd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnfdkmi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgqnsld.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlpraou.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otesulky.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cieqmswa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lqorafrp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgcbauc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgqkdbv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqbxhbv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhvldpv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyoqplg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgbaljq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lwutruty.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frauubrc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvjxvxq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2giqpvswg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aljlztag.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpconywt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2earvxwgf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgftaom.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeftinue.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uikolzzc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejynzpre.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uohtcgnt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmexpfa.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxzvryt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feuvpkfd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqekvlze.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uadlrpvp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnsvqhf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dexnjpco.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxsgvch.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnpsevm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkljxusi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnhfygo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uofbrzaz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfryfprc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lanngkpo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2obufecrd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvnqhca.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nehfirys.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsydsstw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnjgrei.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhmqxma.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaikfai.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sglcfpkq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fetdvade.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2smhxhxgb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ujenpava.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzgouof.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkfdavt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2afbzorwz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wndspfra.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2imbzpccv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whpzmaos.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxcpbrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuibjes.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbpvlvh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzmoebk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2esjdtojt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krhsdtsh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cyytdjfx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2auefalpu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gegqmkrv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yucypulf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsvmric.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2edoxkrzh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eokntbgb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoofwpwg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2htlliocf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjskngk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcqggtw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxbwyto.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlgxbtn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpurray.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtbsjps.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkxmdvu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2muoogqse.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwfmxit.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cehrlrwr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaarnve.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyqctdf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsonfoow.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2flymdwho.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqvwqwi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jjckjnph.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoljshwq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cshdprri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnjwjjc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qswvndou.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmdznzw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vuokkybr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oybffobf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrlixne.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrytxnn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqtkjla.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbpddak.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vfznlsay.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wmufxtlv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zycothuh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mahvblot.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giljrhsm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2quhtudty.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2orguihwo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2geoledkz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lezdfbss.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmpazoq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sbplotep.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bneyraqz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmkeupx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbmoywn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gylnzinn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjukkjh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hxainjuu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gwodwtky.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgspgdb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvltxys.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcrxrpp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fttnvpyq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeughsd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjwyrzw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2joegucyf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnwmmkw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwltyyni.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwcywfh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqclbfl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkihzcql.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbswbbn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ournvsmg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2keyiimvb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgykqyn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzbsglx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vcslfmyk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwgagmo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxkbixe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvspkqr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jidjiorf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtgintc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2omyqufpb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrdmaxo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrdcaes.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwkdipc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eglcbfsz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chrtzbhy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdhclwe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2helhwjqw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktztivy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyagxraj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeyknil.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmsqbhs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwhsbd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sagmnlhy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjkknqm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xtprlgxf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gitjncar.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgquegw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzfjann.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fibbtohk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yodwrsda.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2febgbgzl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrzrluy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwpheoy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2brtorxlp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ponszzvc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsvpzsf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpxkzyo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qijdanwk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeleaxn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwauooer.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgyoutu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2biiquxuv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2resojvfd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlueivty.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrrrhhv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yswunxtx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fctpvpoy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zugufswf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2atdkxorw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqamfai.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfwqjck.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoqfkmi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wrltgrne.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vghytttz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pohvpxsk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdchjkf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqrnifc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ighnonvx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bocxdrnc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2emxytymh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfhbqpa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbdjzgo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwlnyxc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tctgmeeq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzakfwx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wepnprna.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzihczel.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbbdpww.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ysycyccn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjcvfch.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2harioibu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmeqirb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhnqdqj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgthfwn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stlpgjsu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwvhmog.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghyftn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hogahiad.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dhikrban.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjjoutz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lccokgsm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2becebozp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zelhjofx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2avwvbcbt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsnyeve.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lxclxbmo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2etqaqdaz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxlpzxe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeezqpf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2irpxpqch.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tzomhdrk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2isgtggpk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvcgrby.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyyizhu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpnwcip.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2plekjlhr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ezijmscq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2owlckqaj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hahcfyzr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2umteahyd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjffpeda.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcmndiv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrxjehs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2voshcdnu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtlqljv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iquroydg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uumflwkt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlmgyfe.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwahxvg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2iuidnrhq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bltjukzi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2taalyeqw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkznnma.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lsltqwxn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2neebpwap.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqiqbrf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpjgbsh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yartwxak.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gkatcpaa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oecpbcmk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2svvoqjiw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpzeakb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vawylevj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jjihsujs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2seiknefe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxfsjyh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxjwffd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgosuzsw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjogakz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2npwblrap.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2akcitlfp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqopbenk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ueugwizp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2llonbafo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgwllti.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnjogtl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjhmtbn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qigpgseu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xobekoji.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kucxeogw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmozyaj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aizijpmd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbzbtgj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvksjpj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaeeokc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpksnbz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhqzcss.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjjgbqi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnisoos.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dugkhcpm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2odwdiazv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2letnfdlw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvbhoql.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwprllt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orqhcxnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcovxdwg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzhuzna.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzptvca.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vopcdxmg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvurxweh.html


<!-- 参考信息 -->