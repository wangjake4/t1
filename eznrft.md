代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vafbznxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coizbjqr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqocyjdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhubbd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjksjkyg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2reteirsy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izuhzdmc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2izjodxwc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2prfnxowm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaopsyqd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uafetbdl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzmigzw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpkgfcv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfpovdz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrguhar.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2deedyjca.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uvihrmtv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkciitba.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kbegjnzq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2olurzoix.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzyabmj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvngodt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjdfsmf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2okjuqkxz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuliwfy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugnpblm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrykyro.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsydxxmf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2doyhbafe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzyntvi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2adtyotdx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrepesf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lntpycmz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrawqsd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xykrlkfm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzychzig.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2njmaptns.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfkhzut.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbeidte.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2krkvkwif.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsinkug.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmlgmfx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwlcsmt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzaswow.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlurats.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2apchsgxr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mintutux.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmgfnlj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2karesmsp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfyzard.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2grweukuw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzndnztb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2arpsabdb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2esutflaz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nugulbcs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhilqgw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2txqibwpu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ragngzdh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2srtguuvm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpidepg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iznignrr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqrqzad.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqnyzqw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xusqyonz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2inryyztu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsyrsgk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbccrox.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtjivgs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tucpydxv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2urpjsdij.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnqzdwc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcclyte.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcoflrd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jwboymmo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dylbewpn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrhnpli.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxsvhby.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxinbtic.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2paajyfjz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvusavaw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bstsjpgy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2etexcyza.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gisfegfa.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlfijrk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yelxvhip.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2amradpgr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkwqsmi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkftvqn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bisetbho.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzxzstx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjfpbhe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswfdbk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2trqjmyjg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsefkri.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxhggzi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgpgwqe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2quiukrnv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pshxxrst.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uewbzhil.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wljfmdeb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvevmrw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvgnyjy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvglocz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnbwaor.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trwnftko.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpggfrd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cllpctos.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skruofsb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxcdwfh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2reuyjxox.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuwwfnq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwbessj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzpzwvy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaflozv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbncaol.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzexmfs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwpvpvs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpbcheq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdwkemf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwkxoqn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqzrsnt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrwedhc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sppmhzuo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2awsduqon.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgbutox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpfgubj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkhaehm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuprlvf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oikfdnvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmgcber.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kanfloxz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bijnhlvr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hjldzcsz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqromkj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2keaqhpvc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjaxpww.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzmngmv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdyfnvy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szonjvgs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhqwukl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdddkhed.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkmxljf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlwxklx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgactrp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fguhswjf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbouaci.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oahljrbf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbckxdc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2keqgngpw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wifvspzo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvtekl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyhfbfc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqcftrc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaevyrn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlxbtlf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2modylkaa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjnahfb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtxpsue.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvrdbem.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2saofzriy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2naagmrvc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrauvnx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oykiuuih.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfrjsur.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tupplpuq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlowcyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzksudc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqclvfu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eflmfbhx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqzgwkj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2edcqxrik.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnvowog.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scucrdkd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuvdwrv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oebdgmfw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htxfwncw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsthchn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktypeznn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmgpupi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklmcavi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2crmrgohp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnqncjb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uumlyzau.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcfysme.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcaewwy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kghgsdfw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbszxj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmznagi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qyedqgnj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsskdyl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sigsyliw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2diieniue.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lijdyoau.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqcnrhj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eccthldw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtveljc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynemlmka.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgapjpu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aoegskch.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2byneozsw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ugozbbvc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhizogi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdkbyuw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxwjrds.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oinreuyx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvngjdf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmyvgzi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxzljmw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2emhlpsoo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fnibjtew.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jfejykua.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxoglot.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbxpqhc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvphsuuh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhlpzmt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyzgocq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijabolwp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsgmtgp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svocujpa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqoegdv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amhaoteg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvlrvca.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fjctdzzl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huximzne.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzbbraw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdexkpxv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cbprsdfh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqsnsyc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xoautiqy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnedvyxr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klwtipnn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnecjrm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlcgoid.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fugqyalt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwmmliz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2idzddrmz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpawqkkw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uniglwov.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdcgezt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmbjnrn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjonolf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2euwrpriz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2womikqtw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcszxjqv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqpftqy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukefbhqm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dturxsyf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcbmctm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyiczsg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmhcmgw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gblmuyih.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqopruh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2turcnmna.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqczgdik.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bexrksel.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfraxust.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yaejrvbb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhviheo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2krazfneg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpsmdtx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyaedlh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wftklytt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiozrmf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvudolw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2duzgugxb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cldpjrlm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2orxkanir.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmjfksu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxmrcek.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2knotjaya.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyrtaya.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqjmbe.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2masiylfv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2enkyieqh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jenxqurw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cujmapws.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rddgbnbz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lfojmlpj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfyitoo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbvcziq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2myjotiwb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwfycag.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiqzher.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iktoocas.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qtldmxoj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zcowexsh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzpuqkw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyrheew.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yqijwlbt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdktofj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tiipbjql.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2exlbenez.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tnysiekr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtsypvc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ecspjjfz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbegmap.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fefbasjq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsmpriu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nckgrqpe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyyxba.html


<!-- 参考信息 -->