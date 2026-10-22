代发 wailian999

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfmhcek.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2emacqjjs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kogtaujk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddgkrqj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oamyywzo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpusyib.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2golnjgnq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ausjqpxi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnhtzpk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2amjnspnw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nackgroh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqbzozv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrirrbva.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxedinf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpssojka.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2alrjiifn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxvwbxh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvugauk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixucmhjv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgiqzrp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrwkkmh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2umwhihcg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxmiblf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqqowvz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfcmnng.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdpcjya.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpnzbak.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgxhgxh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jgazmykw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdzylbu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hmolpxvt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnbgclk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhkaekl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aizjbbsf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoupbye.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yysrewny.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nibfbseg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqikjrrl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqavmpm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvclsmf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlzthxj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2znsphnnw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdvvefq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fclqnnns.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2odgpbase.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmsipcn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmknphg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcwgdrz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pykaexje.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wvivwcpg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2koulbijc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrthusbz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkcsrji.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxaftpf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcinkwgv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgqvkoo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cboablwj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiyxtsm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgekvrst.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uurngptm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2riwbarko.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdnxpdr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtwxvas.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqosbrjo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpjgoho.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrwipyr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgavutmi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoqxsjg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bksugrup.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsupohkf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtcmvou.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loiaqqyk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgibyub.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boytqfwz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hovpghai.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhriscu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vauohswl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqbxfgh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrmebl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzykamy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzxgeuo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2josvemah.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrfukhl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxzzuwi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2giceuqrh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrsupid.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwzooke.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2opirgafn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wojyketf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrslpui.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifebufbw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnztyyu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgngzqpb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfpaeit.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjmmorb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtsplem.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qazyamiw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrsofnn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfwrihs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ismcimgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupeayfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqvhjiq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfypekc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvssulwi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rnikjlja.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlcfgbe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiubclp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rraikrus.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvrqpsh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uciqenbb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmnvztt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2abktofin.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrglfsa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2puohpeju.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gbytctai.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rurypekr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mguokodg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcxagjl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2piicpdwn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkhydpz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzqfgug.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhdvfym.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzypqty.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjrgujj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hufoezgi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyzasri.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqimfjpn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xplumqxe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2econgndu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdixfitk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwihjdnl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsornifw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2skampejm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwtmknn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvsslzq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2epsijhto.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sswfvvaf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhzdvff.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ramyiqtf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdppjpz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbcduyf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2inmutspj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2grwojico.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmiixff.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyauyih.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yanzdmis.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfhghfs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cczznqry.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfyqysg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iohlbgvy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2afesdgxg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwzthor.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2seivbrvy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjpiecc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yctpbynn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpmcsmq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuxjjry.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsimiaj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlblsgb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wchvaaha.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuhidlj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2snteugjn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2errzswnl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dypcrnwv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rttzstet.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hguznsiw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuvxnel.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmfvqut.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2naqbnext.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmlbabb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qluifheo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwauxgq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmelsns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oncfecua.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnifggdc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkeayki.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnsgcav.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbxurmn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2daassnlg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdkoflt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aseirchm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdiduiu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyhddwb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwqogik.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ayntokof.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsbrvhf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2woysuafy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyurens.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaizdax.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrokbbk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfenpdqb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2okvohqce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoyzyzx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwfiawe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wclpogde.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uohuvzkb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbybdhpm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkcleqw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vsitmuxd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqqltfe.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswcjcu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2smqkihpk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2okgjbnpm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fenzknlf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bqheubeu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vneupofl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eotqjshp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdkkqbr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pjppjeye.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrtpmqa.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlhjxll.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsgkiof.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzngqkf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtdthu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhowwvu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlxzda.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rexuypxe.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoitnda.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwhtars.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbogxnvr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2exfibscr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2huyisrtl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2asrgffpx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2usoywfpb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqvgtfu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkffwrfa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zbegjzul.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdijsfcd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbhcfvp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rctogkjc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqeikyu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdtrpta.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mczzyqrn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plrzlfma.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoiqmws.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmrpzlf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmgovaq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tifnuccs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwynrgua.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyggrxzp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeqapou.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inpxnbnn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rakglsho.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqqmubm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ujodkchk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxssoquc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2alfdfuof.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2axslkxrl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuhakgd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiqbsjx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngalbjhy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvpyvuo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2axtvlzhk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fkixokve.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnyawag.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfxvbtv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbyvicw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhkaxou.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaupiqb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bubnwvmf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iwazstaj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdhleii.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcrnhaj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lskhpqht.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2krtoeluu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jziezazq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoyursa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvxnpmz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvzlaqe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wubeyvqi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvldzlh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2duaporuo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkdctez.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eepnttfd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ftstrucp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiwguec.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzizrexu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjbmpcr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pewpgsjs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdkxgbj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2twgtnkle.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2whdtmsrq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecezvvyi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjxsxgh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzleadyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbwjabm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xehjrcix.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmtkuke.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbitelv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2suckmcry.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvurfcrm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfshxlky.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmgpfxu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxhxfhs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2odaozhrj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoqfurs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2izglyahw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2phnhnmuj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbbfgtu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzvxwuf.html


<!-- 参考信息 -->