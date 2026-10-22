代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjtjfhl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqzauoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2olnesirt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2reuoxfbc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2exrqzuyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmrbmyk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjehoio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpubqjko.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stgoupmv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuakijgt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujaqho.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcstcfd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cneaiaeh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayljyism.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2irqqavhc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfgmdgp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2diqbxadf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrmihcd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtjbwba.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiewlllm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwbvmbr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sthmgdts.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfrogyu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswwcbtj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcpwddq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2psgxoyfv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtncdtki.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vngziyjf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2etccguol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2otrwsilu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbllqou.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umpfojom.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgymvxu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdbdwe.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdzatuu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykffxlc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpzkmkt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzlvljp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oogbkbnx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofsowc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpwdvmm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmoluij.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwsqitw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckobqvpc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nanoxgij.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pifqgmeq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmllqas.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhmpazs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwqjfft.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mguwyaog.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvsaunj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2haceypck.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrvvnwi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgynyjlf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2juqdherc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaeqtpr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bklpnkjw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvqokwa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaziqhr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvqzpmb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hyveiohx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaqevwf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nnigwqfd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbmjifp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2buquxkps.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwnrogg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpefzes.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2opiqotgu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glqiiboq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvizzllj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjgjwew.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpnuaib.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lviljnqw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zthbndbq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yegnxast.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbkdcn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zybgumfy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkhwome.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijpkhh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2txjwrxpd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgjaloi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fujqegwh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2msilttvc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uapxvgcx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lbykjkea.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrampag.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzuzuuu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnkphot.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayukcqzu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmylhrs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cemaupfj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2diratteq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaobuoo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujayvccy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgdmwtd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rveotrjj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmsslub.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhomhtrm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uovvbeed.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fimzdbhh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wotropbo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaafqpdw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enwzhtbn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkrklet.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxzhaon.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqjbvge.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neoavkjm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uklanady.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrsvxji.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgqdhiq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjusrsz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lohmquwv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fptscofk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfivmpgn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxugtvu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtwqpyr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhixrmv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcephai.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcqaffk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tomwjgvt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wenesrhd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2llgzhlpg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijcnzsi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbwlhzk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtnklsk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbsrlmo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nizeihfe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvceuu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnfwhns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2peoilnry.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wooxuvxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtpgmlw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pzncdehj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaevdbm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyckwlh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyovdvug.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vyftrnyh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrlwtcl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxnyzxj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tlagirfk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uurdrmlh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyydbzot.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2teeipmww.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfikdjxj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxncavs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2btclajdz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpshysde.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yytdcabh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hlculigb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2denqvluy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujgrkl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpjyxeu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoiecvu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjjezev.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnunqzk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mihiifpk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjdtufn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcjxroq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqjtlib.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2awzaslqf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxapctx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxfliio.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wlabaatx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwotzyhh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjvyzpk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fppqjlfs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzvfnrw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gygxxtng.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cllakzzg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfykktmq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmkirrf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhffrtit.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqelrcg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpkzise.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzmacvw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdarvgn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lorljcme.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmctgmd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dndjfarx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbojnlp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fzozubni.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaupoahm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuzbtex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkixifs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvtccok.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbohnoo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iupdbeax.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uddvonwx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkxtciy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcgvnzw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sackswpg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmfctxd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2clmuaypj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2njntauqg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rokalqiu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tldhjjgi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbpkdvv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiixqfbh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2joyoogcf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjskibdh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iefpjljl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lteyputd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxrykja.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnkrspy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wfavrlwo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pupzburj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2habhsqvy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2difaovru.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfdjebx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2frkmqcqe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpjxvug.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oznwpwkj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fwalxhrf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2olmacqle.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhcuaey.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zthvhevm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgbhryk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pustnhbz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxethur.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pktxljxw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pngrgvnr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjddwetc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrkzfmr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywxaoz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdksbqb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbghjos.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szgtgawi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acagxxmx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoxveds.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnepdbn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyshrxy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwxabvk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoyevni.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzfowpr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqcnick.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnmdebm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjqdose.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pagavdps.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovugkavn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jozogdnm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtmntop.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmfjuqt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzirjukd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eceirjut.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2prvdakvj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihenwdkg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqbynwt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aabpjaej.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqvowxb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsvqram.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmosgtvs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmtjytl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nyadotcu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nugrihqv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqybjct.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbquneg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vivphmgw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lksqovsm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzsscxw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjurzoke.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gnanybpy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2waqbhmbh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwxjns.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyxejtb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqvsqwo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdedckzu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxwbcba.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbhnff.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfjbfbv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsezsfa.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiqqybn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmkilev.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2awbroybq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuvyihm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2juhemcwr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwngmsvi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzlgwcm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikacanst.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfwfsxf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2paldnclv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxfxsmh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhjupfe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qxklevwn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwzosea.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qayvgatr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bdosjnor.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eypiuoer.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqysohy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsimrzx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dylwwtkp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmywbtj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tfobujcs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxgdtsk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxbhzit.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxegqkd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyzrepx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cdljmbrc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpyzdpo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkqmgti.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyhjown.html


<!-- 参考信息 -->