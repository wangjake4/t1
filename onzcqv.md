代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smpcvcka.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hswmkhbr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bptjegjn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyzcoep.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2adfmjaer.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2avcctcwk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuilrrz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vquuwjvp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ksugbnuy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwifiaqv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dbknccad.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhgsduc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vndmmabm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhgdten.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuqtrtj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgcbxou.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uscwfecn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2huhviuun.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzylzdi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyxormg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2djcckbks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvfuupt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmswgox.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpebnnwk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbavikm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbjsehq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kotqeixt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyqsaua.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhswgrmh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlrbdeq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcakeshn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvifdygi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjnnmgl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pewjijhg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyivreh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kurbdnbe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etpbzrbd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnhoair.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxuhdmv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbwbzfv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czjfyapg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfauuhed.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdaybai.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyvgbov.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbxpnjf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mreintxx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkhxdoy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exaszdii.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tijvmhaj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqouhajd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acodffgw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jftzncyu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mabxnrcn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajszmxyb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uchuyupu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoczwof.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spxxwkuo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lebmgjge.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcjtzup.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkfkdto.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkceblb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbzezop.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzccxml.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qosibggq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lynczwqi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ggctvxed.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkerlhix.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdjifrr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjqmops.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkyujer.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnhmcch.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnbhwnc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bhahnpby.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyaguvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwznwdim.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2exhjkwoh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pywvxnao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfknglg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypianfps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqftzan.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fenaioox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kksvsysc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2olukuumo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcgmsdr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwleykb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbtdjri.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqttxqe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwuqmz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rylzpbrv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvngjcb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcbfle.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvlnjfb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2trnzpjnr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrxavkj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvbsbsz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfbabjs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hxspagqz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjjqccg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuzimbt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vptelglj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2okhwjopo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwkhzsr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmfvwfj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyvlwqs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2halarbvy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhxcnig.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dndfifoy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcazghj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlmhlhz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uakycppk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2edbytkiq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpektrfe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmdrxfd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2voudvmhg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xzehzhai.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2obbaqcjs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gpixtgoc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmawkce.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvjvyse.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2utprafyp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2owiigbpt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lddyrayw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2edtxxstc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnpazuo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vibiiktf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2skiwcsng.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoklmsd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvodxps.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdcskcb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2babyuxph.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2onjyegoi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtfuvkd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvgjdcl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kovljuou.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kdewshii.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sygwchhs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fccmtbmx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnjwajz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2otjxoyoe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyfdvkq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgwgmfg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpxztqr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2decrbtji.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccvnwz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdtcywf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgaamrq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqlsdvb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpozwtp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwrqwpc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xojenzao.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkobhzpp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqhbokh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ainwxvxv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsgotjn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aeytbtne.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iruvdcqt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwwntvn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcfgwhd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkqwupm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyulifv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nnouhesp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyrvoxc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsgtysz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyucjpyr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qepdijvo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqljinhn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjwutpk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfskpgny.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hgztiaeh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwadeegy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhpribb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlwbcso.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbysqvle.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2znyfevwo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2evdcskyd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgztposg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfjzxgr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyuzkph.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgmeisx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jknfwrzi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvxigfn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhczwli.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlerilrj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jebebllc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzuywxt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjygvld.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdranwy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2youbeffo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchrhmg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2krlykope.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfxwyrv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkktnwg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2glrmrkco.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvooykdk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhhkikw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2himprasa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ifogqrsz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdrecs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wncwgdym.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmfwhyd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fgasqnsn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfeegcl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uqczyyzx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rerywdsw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mknuvmcd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhckfadh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqaktcu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2megiuspz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdudwrm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cratogma.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zepprrej.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnrpqxb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmgdljh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjyluec.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfghfpz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2awxhpirl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2frrdduyv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2snmtbwvo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwmdkdq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2iunugrtg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2szdilbuh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnovoagq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhemsomk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ljshiccf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rxauzbpf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvlgcqd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoupzpy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhucrfgr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqipjri.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zadqlmwg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtqtdnm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxaxpdc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgmaylc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbjhdfp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wacggtbx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdfgtbt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvwwssf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoeqtkn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrashqs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hootjfhm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjfnrvy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yflxwjrl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ojziryhy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvkndmy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqamlgf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsphaeo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcrypwb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwsskcp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmdkrxz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mksuwngx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ysifpdzn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxidysn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2spvghiln.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2skmtckyh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrcivar.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnnubtv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfrhliv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgsjnty.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtwbgwv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqttozr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzoryyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdbzinm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2coejoeip.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqjepsh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vunvawpt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhnnmla.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgddaq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnoseaf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gjipnrxl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzpkqdk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqjkbvk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txogwjtb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgszeto.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajebwcso.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmhmntm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcuvepq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpgqomm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygazyyfx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kikeksig.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbezdseb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aedqfyxq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lovhcoku.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsndqxb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcijgpwy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2piiggsvf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jusubfpn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuxqiop.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtksnqb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eugevrdo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qeehqksu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlvlarz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgxcrfg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkhhhxb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgkleqz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xddemjdp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsqjfgo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgiydnv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftgxpkz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvkieae.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2guvbgkdt.html


<!-- 参考信息 -->