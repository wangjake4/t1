代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidfbuky.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2prrrrlvz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpsbptk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjozxhsx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pagreppg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jszgmyig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcfaoqx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgcmykx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qabvszpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbfzxcg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoarmma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2askdvxbg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yemoxxaz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpifupv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nskxqeue.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aocsafeu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2carjzzqp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2alclgmyo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxxjufu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnjaghz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmcvdnq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mprbdazw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2etikzjaw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlwphzm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjnnwht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqswlkku.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gwndmtgf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2betnseia.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcktefv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2stqfknji.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdhtzdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xywfjhki.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jilnceas.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoyvhfq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhoasjz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grbhrjpt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mltvrlyz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mteipvzz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zncctasn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncayzfw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsakuom.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaeleje.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsjidbq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwbiopg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlzrbpl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nckvdwww.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoowbou.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbpqujy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zappwwrt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zexymllz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2keagdnre.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtpekzx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjxtuqb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2szdfhwbi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaqhwnd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwjfsjq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjsaviy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtdpcpe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2scrcbohl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pngmwayt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gixxaazf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2faawlajl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cahbyklx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztylacqd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2labrkdqg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbetphf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2biuxmcwp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyejaxe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsmsyyu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2izyboqyo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzxvxrf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwyvkqa.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wewdemtp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nklpxque.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtooauzr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ikslnwnj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkokthn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wpblqftl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pufflxoe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hiloxcbx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2whecajia.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kavlfjno.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hurfazwe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2flgwlrcp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2efhtsrui.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2snampxnk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swjsgfbw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qykztidn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbssufe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaglupnd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlufdmun.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qigbmwsf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhpwulh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkxroxk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jduraouy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rijutkyt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxshkdp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfadghnp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rujdzjvh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onzmjkga.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzboxlh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrdrdaj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xemqsbeo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxlvbxj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtekjyo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiiuhqn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnndjc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2caynmtec.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awyapwtv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czmppqpt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcsbcxv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2eotfhlvr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opvumvfd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtewnrhb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2byooghsz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmluirj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyiwvbg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlcyxhv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebslfnzx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2symqcevn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwqxvop.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xfascbws.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fweupynn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gvslzphj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhcbfjz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxgjkda.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkxdoyr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2egdabrid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiuhdrp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhaakap.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrhhwpr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhxqemy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqdnnto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geiourur.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqciriq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bevjdfki.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrukjsz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vngegiyp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqtiuff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvigxysa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iydfgetu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpwauql.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gexrfuka.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvmkypp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzquqdrv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vktfsarn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vexvaylj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2usruujry.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxqjoae.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yugstcuv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yubekzfj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnhbpcd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxdkres.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyetirxp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2betbgikh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cggwqkls.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2duvmrsgg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqzidwu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htjvzqsn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwftibgw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxjicpl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfzrphn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtryceeh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfohjrrm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2juuwusay.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnbqvvb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eftsrtsk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtyzguh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfefsto.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbeimhk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nkovlkjp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjpvmnd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bdolxjxl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblcpnzr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bwncnorv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkqyefs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbrxavm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyesvdz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbuirek.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uesalfxd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opdyuhdg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2giczldaf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2amahsoxe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhjyqrd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkvmyue.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyoxbqd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sddyeiqf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvjyjcs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpkzeha.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2puheawpk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzmjicw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tunrvwop.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkyyezm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lxetbaqc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kofpncxa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkzrrxs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qtybcpeo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2osfqtomm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvkcodi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fejhtuce.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfyvggt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwashdk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xskrotzx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbjhnuh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wadvsghe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pefsokny.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rolonhwj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaitqbf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuzdzju.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wozfirqb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2foksbxwp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nssnclgg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2upxskcik.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpspbogr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2liorlbmf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwloqgzn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxpskkj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrywgpg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vneipfdt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqwslxt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xftquoro.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzfvozb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uunepiun.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xllnopja.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtjlhrq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osrupkmy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wljtnasa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfmrovc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oliavsmp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2npsmsmtm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2imwwbvti.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdswkzlz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2olimucvm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dibbezjf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nskexurw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoqeoza.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdluzqs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcaqqzy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuadibz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2irekybvg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2elcxunkn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gczbsvnc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkssrmry.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnydgfz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wddkebcc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwtcclt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcqecog.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vygsuijw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlsaigk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrbioji.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmidugf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2palafepy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gksrortw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzogrbx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tciwxpkd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwrysc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzefxlw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwtimsr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2upqdxwam.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rutnbztg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzswnjsp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqojdqqq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2miwmbajo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jykzifxg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2azruskcc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyujivaf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2motdqgzx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oitfscmq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kecbodcd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jomvqwem.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmgitlw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuzcujr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjyndgc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tguzpgac.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgloqvs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yalnovmh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2teatgghw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jluudemw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnltlfw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2etaogapm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2urstexhb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksjhplw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxyeud.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjhexao.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqsgnmo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2omwnlzup.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uormtyql.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxkelnw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ilndaybq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2twalsdzu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gootlvaf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvlgtin.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuircvm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwgvwbj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ncreaams.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2twvycdaq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhktkpq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2igwqdpyz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2idfvmpvt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbntpegz.html


<!-- 参考信息 -->