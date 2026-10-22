代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhefxsd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqoozof.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpwgkop.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hedthbpr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpwdufy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvzfvyk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjhycen.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2asxrwhyk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ysalwzys.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdvnqjh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwkzmqj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxywupuy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzztigqr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbgqiq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2comsgtxv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxndmqd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kggukfmn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxqjvjn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcqvoab.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsdtoda.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2svlqgxyv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vksxafhx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqbohkt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaqjixu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzwjuds.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqmdmgm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wclkmmpf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfxemqa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2romveyuc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hixwklec.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khuskbhq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeljeai.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hekblfxv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dphobcjh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yranudcu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlycaxa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uamslooe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ierxiutk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqchsoh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppanudcp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ldylewio.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaloeyx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2noihngxz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygayvbpc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzmdlqi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeunjkq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxbyczd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2trmuzqqi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuvmcyz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrdetha.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jybgbxoy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuxblbd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqywuydp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmmnyvc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfkanwx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdgznlq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvsosrq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbghxogy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlogyjf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2otxcvuqq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjobiexr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmhiasx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvtvvmp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2groppsmf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzmpjte.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2blyqodcf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rpznobei.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpnkqyx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhdntel.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2esqibtsu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzcvjhv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wevvtdmp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxhgoeq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ielkmano.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsymdwz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutppcwp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeborzk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfvaerd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvyjcad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gevlojny.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2velktdwx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlaytrw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uotiltqf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkyyyvb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqsrwzp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvragxa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kngckjhp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zosjtgbh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aipllmwk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxghajgw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeseviq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvnhobs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyktqtl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpjrxsh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvxmxzm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aykzkott.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjstfdbg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlqljyx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dteuwnqj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2icpvqtlh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdobmim.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtzeoov.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vukitpvx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbnmiwu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fpufakea.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmlxtdf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoevjyr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxccdfd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvqbtyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgaimbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdaqafb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoybkto.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hstctwuw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lzraekxd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjmyepl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfeunve.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgkwlws.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2loijxcim.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjtigfa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxxyuyh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfvykvh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmluxqcm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcrhljc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyloiwno.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjvbav.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbgkncg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoxwkdq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvxpplz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2piwccbzp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oerbyykr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2raqjwnax.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bidmoajx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pnidowex.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lufsmjpl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvfjhzu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2drsdhqip.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsurmup.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfircdap.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ioepoumd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2taihageb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yrixnued.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2utgcbjen.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdizbhh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oirdlhns.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfkkffj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xruwinqx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrlodpc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yddvzhrs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2clnccnqj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiohhsga.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iloynobe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcrdcvd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2embxfwdf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeicnmh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cetfjyaq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyisklym.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoghhnr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfxvcoa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrtipwa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkcxxzb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hsndoiqe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2djllvtje.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxaolya.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeacpfx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cbucngbo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2awhulzaa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ccstowsq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkqhbeq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhajutx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgyueis.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vksypibv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2didnczah.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jsggiblt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nnneetal.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uoikqjya.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bmapcwja.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vbddqxgh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2btdmnbxs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2atvlfiuz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqiehum.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2heuabdzc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfgwiwo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtkrudd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nukvfyfy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpvjhcu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkfysoo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgyouqy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuaufoe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfargfz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnjckck.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpgnbfq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kicllpqn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcbacnk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkdihlj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ejybyaki.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2weldniks.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzodxrda.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mutolszj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaonowo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlryrzc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2paftrptp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeudvvgm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfimgyw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdsljk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnttjrq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yexebmlm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fbosymjg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbnxxnv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aagqulav.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zanaizam.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lwknkrib.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjvdzpf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2spymvbcl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrhykwl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdkgiuc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gstsotir.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ocswdnzw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaoefjg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmrczpl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbhsttw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnmzsmg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlizngzq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2szdpxket.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grmmjvkw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zoysfhxz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpybgme.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsgnwop.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uudzjiay.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfarkxyw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qunzvxoe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cazgbkph.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2czkqkmwh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrakrkg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixjzhfm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaftpsl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhphtkp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnozgrt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdumfwrv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgpbdzh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nswaeftz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uqosuhdr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvawvaev.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdsiltj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoclanv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2smhssgnp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2beovkudw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzgshis.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pskaqrqc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2retkchkt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhxewbx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfvsedv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyzarys.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcaclkr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyovioc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhbcbkl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qlblcdnp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mczpllfx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgultds.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxieuqk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjopljyr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbobaoy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lhebsjuo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmjuqhb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbxgga.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfcwsri.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrtvbiu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sygsneor.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pfripvae.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cvilegoh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bjayfsux.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2aikmkayb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cputamps.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoqhphl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tdurdsva.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxwinbh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdpjoj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkfglrs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwpbxq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ucthbrei.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjuaorp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpizijp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gxynqntc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcjoxah.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcekfb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhbgil.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcclmjf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lyufepwx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqsufmd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2durkrylk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwwffzx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ietuonli.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2csyddbup.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ruglrzux.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzgnihw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzqpvrl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvwjexk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsltaqww.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mromeqhr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsgmaic.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkrdloa.html


<!-- 参考信息 -->