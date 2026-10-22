代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeaedfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbjugug.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aklhhhbn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryddgmno.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qutwjqlx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjahpasz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoudnrq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnfnzfo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zovzpiji.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmzqzdb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzegdks.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwejigxi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvtcwcs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kefwcnjs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeecpoi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcqtzuy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnrfazu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzadfath.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hthuslqi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2akqxajqh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2udoeswau.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpgihod.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqkulke.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qawnzluz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2imrscfuw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwkduyl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sknhlpji.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskfgqyt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgdylju.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rniqdrue.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tohqwmyd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbeinwe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adtqtztz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnbxhsm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2giqsbasq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2voxwebmg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oywnsewu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiegnau.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzmyaxp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2obwrjawa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkywayef.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytvnzhy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzhffyi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2opjhryww.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2utzyeekr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpvaqxh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2halqwadh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqnurbk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fznctezw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2khefvrwq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llyaynlz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nfktwkwu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwmzomb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iljexfwl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ioukyuxg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsawowu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbxflvf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2trwzvlqw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msazbaqi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2epibhqgd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtlcdsc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2siahvuws.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kedjmdsl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2agtcxdbp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeixgxd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhetjrp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jghrjqtu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2smelhloo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcloowv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2caspaocy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhztbtej.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkfqwtq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgblqap.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhhotir.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdpfabd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyadrvld.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbjurbb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdjdmkc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iukgunzx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzsawet.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaypczl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuwlyoh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtpjhqu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkdnyvy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wulxspvo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knspjxey.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwacint.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqjotit.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxumvoly.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nreqtakk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eckcryno.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvupnzoi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfmcapf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgoxwly.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbrcdxn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kitwtcmi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxmfctw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nitmqlka.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwzloob.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nuavbqyf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2epygiwrh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkuwzbw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2knuymadv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2geyokwuk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfxcawy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2miybpuzt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwshtma.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxykarb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqbidxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqibztc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okisbwpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmytmuez.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2htvmnhbx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fbybuhqr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ezryitse.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lprkaswl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoqrhbt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgigfat.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwqdukf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jscbfdba.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbatucim.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyrjvsj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzwiqkg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgupphrn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkaoaoh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvtlep.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdxysdg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvbtjsx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlokxby.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2noarmihy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2snhiphyj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2naixoolo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eikfmnuc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdupwp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyfnpre.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhftgub.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yigttnkq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rupihaou.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2omzuwvjp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeqqwfr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2koisstsy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fadeyxyl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bnolwjsf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiccgsum.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2htgtzqbn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgswlgz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2varfqwfs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cruqgtvk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoojjaa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqudcmml.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wavvrmlg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzzhwwu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjtbnin.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiybhkx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wbelzitz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ataqtzyv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxgfvee.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlikovg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2civusgev.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihtnbpb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwimsjh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbowdutp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2stkyjuwr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2chjzdzbf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjogpcq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qezqsnsl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dewgwbfj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpygciu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfvbrho.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yrssqkce.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vprzozpf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuehdrx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmrukdq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpcbjdi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lqehqtiq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ujopbpsj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyknkrd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cktfiprr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqdczuc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvrbxza.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrafpwze.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqfjrfx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkrdhup.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoncxlqo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyxqptv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrvrlrl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpsmvfq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgxsorr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pabncwnb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zioeqiew.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vtajvmbo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyfsqjv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzzbbbq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrifbjo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzolbtm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqombvgo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2toodadiw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeqmbpq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmjvagx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sorxktvs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsecxzr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sahhwixe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gydbnfnl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfztukc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhigozxt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxmjhs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ogenslwq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yycfuyal.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtahihd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2grbtpzun.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlnflmj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmsgpvt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2edbcffsj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2knpdmgtu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaiuqft.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoezuth.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpqogpk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2evlblzxk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nexuhmpn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrowkuk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2neroslvh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2npxgrcli.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaihgcd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaesxap.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbhzgky.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zotwyfxn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yoodunoa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlozusa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgmwopw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yinqrxxd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbxxjev.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrtqtiu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwdmbad.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iljtscqj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrtizav.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkbhzvm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2apxdmoye.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwnqegb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjoivqd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2evrrnswv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yurtndyk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwzerej.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxrlyvu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2juevxdab.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gevpymto.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaloosn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2otvzvols.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2oilckbfs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpaherd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvqdxxc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqrbndy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvqjijk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sezvznkd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bljytrhc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kngeuxtu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbabjhk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrgtmxp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bctzbfcu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clqaxtxs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2aefypfcr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxgjeww.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqlnyjp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2djtowasu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2scldhtjk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2njzgilua.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuqqtfd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxghsft.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kozjkafe.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qopomkpl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mafjiask.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qpezhpik.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2glokmjop.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlcmtyp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nccdepoi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnnkflg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzxwaoc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kdioqchw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpvnjfr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bkutgwne.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pprfztjz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyrwkps.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbzlar.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlkupfg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaikpuw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uexczuxq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nixppmau.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlcgtxu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwpbabn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsopjbs.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2azogdjlv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eanwqutq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clytqiyc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdgwaot.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxwhcrm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpiksbz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzixubw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cycowwvp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tydyxzdz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzzwcga.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmwztmi.html


<!-- 参考信息 -->