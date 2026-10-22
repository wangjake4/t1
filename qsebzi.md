代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zyntjfqo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgsybtc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vihxttiu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pghlgwqq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2twqrxvxk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehothlxx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vhekcxxd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxshepp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ngexzmvv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvljzety.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhycazs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagfzawx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfyjadv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoboxfc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvpjrfd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kctxxsch.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfaivwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrumyajl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2emebvshn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsalvus.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ijozjqfw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jexquzzb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iaobmkcd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aldpiryi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcesekn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvwngul.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiovypx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyvnggt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2twsaoofh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcyiwei.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzxvybb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2orhsfmfh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqpsbcy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkuibfb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vccthcdz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdkxsft.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flyfcbym.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvluejuo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdzyqra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbznygec.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdyjxzf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdoqifk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdoxvtl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zktospsv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bglrjnvo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rilijrhe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqfyby.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcpqjii.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vfusstil.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggipbfr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhdfiwp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwjufhp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rqawzcye.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjzgbkq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsewxip.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxhloim.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gnawmiyj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkouhhv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpkxtqs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ecztesby.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfialjj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvftlen.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtnjpsm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjweowf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cojxlcqy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2figedkfc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnzmlni.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cppiteoc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxzszxn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbthqvzd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txwlrxnw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyqlpcw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2atovslai.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2isiwhkpx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfcuarb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2leqrtdfi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urezbcnc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhwyewd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtogtey.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uebhtopi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdrjfcl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zstxwyyp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuaiopz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqacpgym.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yeueywny.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbiqdjx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogvdrj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxycnki.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cudhedbj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlrsrxn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqzwqaj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnpryuu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snfpizyk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csukvwgq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trxbsraj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcdkbwl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eharftuq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2akbzkhdt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcuwbzp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvopxqq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbskkdn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hejftgai.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jecsfblo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmpdsga.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfpqazi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuucnkj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzbauqe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fujmrtne.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2irmfuagj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxavllf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrribvvc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtwgnpk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpzbnye.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxvoxiq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbcsnbt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfomkbf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rimvzlss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtucxjyt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdsyhfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dritfoiw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2utmvcmyr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkuekub.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkilxea.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuhcbpo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpoqakv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xddtencd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nozavscs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2whpbkynv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfsytpt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2otefmukk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpwxuaw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yufwrjpf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqpdvgg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpaamcp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yliojxcm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2amnqtcer.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhprwsl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ablnzvpt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lotmtbqm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbappwb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ophhures.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxexvjz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nivtjvld.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uboyxprp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfadooz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgxjeht.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2heetkjyq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvbolic.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfsxtnz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwfdqsa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2shcqgcvi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuxqvga.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmzeeja.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwuuqn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2evmjeynp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2faqqfyqo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzcnwsl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkichsmq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2crbignhw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvctjhc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpezlax.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nvusfabx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fucaghkd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvdbwva.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oufwxdvf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mgufrrnc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeipcnm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpkvwcw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmwjmub.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadyedij.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpzbmgk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnxpsfv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dskydojr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgttpqd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sonljkad.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxxizgl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pcebfcft.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uorrqyoa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2frdmsaqi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahjnzi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlpwsfw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrnhwrr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uarrdfes.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zrakskoa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2oeifrsnx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcyuulp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2koijhdkz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaxlyhr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2isxxmisc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvppddzs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkooamvi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2axfdlwgr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnnjeef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2itfeeqxv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bywxieyk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pspyyjoy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugymqz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvqfyia.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqdvnd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfsdfdn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2axanwxfc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvvcpqz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2asbbrivl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chdyydep.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2etvkmiir.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvsjhht.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcmragz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkcnjig.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srtkdbpn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbypvqr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svsstmvq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vydukmfz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2msebnfou.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xueaaxzr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vprahnml.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfntmpiv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tocmunde.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2acegcmdy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhgtvhh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuomshk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oododgoo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tydppopl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2laefrppi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhcfgqa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuoirzr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjquxtex.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xaujssac.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaensix.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrodrycz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2brdaqpxf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkiajoa.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfmnsld.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gclwiytr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkivbbyu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdxjzvt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrasldjr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sowkmuob.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmvllnb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jamhcfqb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvabkfpa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnhiofs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgalkcd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgeyxdn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqdrcxx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtclorrl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cksdeops.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvxvuuy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2odslrrhj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqdzdyi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxngbxl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqhofgd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2saalmkhj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazjyfg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2utvpyfka.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kybzhlbh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsdhboo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzfqwal.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2abozmysu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqivqxvl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuavtfry.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2izqctkrd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgdkewh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbqydju.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ilynuwzw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rihmtdat.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaortuq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoecflgc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtzazvb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bomzgbeh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjukggp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ikejmemw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2igpjyenr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxfyasi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2luwzhltx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2imopktpg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2npyrxckl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2elewzntb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbwswfq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xettxmyr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyzepsk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ewawzgym.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hjekwnlm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjkgfwy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyfybbs.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqchyrm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlhrykk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ozayeqjx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2muvkcbhm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmgnzaf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tixneayu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqibthi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctakhxwm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2soycbyor.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkhklrh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cofkkbrt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoxlrbz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkiwpvt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aehlgfmz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpuoudx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxiyjds.html


<!-- 参考信息 -->