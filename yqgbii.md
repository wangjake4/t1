代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bllwnuts.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzkspod.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrhujzh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kowmzjjo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvryseov.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwswpovo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hojjujoy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrgguxq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezygkhbe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2crhfjnrx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2psmqlzds.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iarkqkxm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfrmtbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcmbgsm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmggnlhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jccgolwl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqxsuxa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kppjiiso.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krpkzuaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxbcpml.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkhcgfh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlmqgjh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tumrygqd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wvndllfq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbtluvk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2emwdscdf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrdzwpv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2miwwoksv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnnedoa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cixciqlw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlxsgjm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nygqajhc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iscnmcgp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2npcnrohj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fewcffiu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjlvkbz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rzppsxlf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpplvwu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cenldgtv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2miiqbgpf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dghvbjgq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igesgwqf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kymqhjte.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavratcq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvkfgcz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxdrxaj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okdewaep.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvpthoe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2apktvffm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvzutqg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzataudw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uibekxhc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzuvneb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwijmgbj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lewwybgg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdoisbh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuajstq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qutlwfin.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdmlvrl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zafeukuv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvrvvgv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjrljwm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sndkniuz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inwfummc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdaodge.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzqevfy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2amwrpaas.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqkgonn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlercmf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvqyouh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2twjuzvfm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfoprmb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wzglvqgv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfqgfoi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2enzyyboh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgrtlxh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avfmdvns.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cirrhubn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtcqatt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfochsc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhipwcd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oimfmgpy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzboetja.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2epdnppka.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtyrmpc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfbaddt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftapytjm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2neustzlx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2omdpxgvc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaehkncd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyrjukh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwvklxu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmfddce.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2javdwlyu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjpyucr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mlievwya.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsainxij.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgvqdws.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uajeyypm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2knmamcte.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbhgswe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2liukoydt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tprdjszc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldmkibg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfoyukk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvphxdjp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2edzqjwpg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpbcwzu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2golqzuqg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpybhfj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqpazqm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2aobghwck.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2goyicgkg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxmkpnr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeksbps.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoajuto.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnenoipj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecepbbro.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwxrszf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzevyqt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdudyik.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpvrvgt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaaijir.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nydgowhx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvszndpq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfqjyyq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zczsowjo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjlwdro.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbwhsur.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtokrbt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhbjlmd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjeqerg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nebemmap.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2spesutwj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaqoaeb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2derjzjkg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttsdpri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihshsgiv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcubfzlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkecbnn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqzshza.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iurmusry.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jwunfpcz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onpjahos.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqairsf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yifjymfk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpkxgxz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tctmuvfg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bonscycq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyjmsfv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsepumx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzccftgl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vodnqpsp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsybban.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iykzhvwn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gatnuxkm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjnsyww.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnazxoa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iczczund.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsxszxx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2prdjlvkm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbiqohw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmqcsin.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhpszug.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnjqofb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rarahpzz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkwllxv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2prwfqdgr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2boirbiad.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2avcullmf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ufecahkn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyccojq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgjqeum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeuvfrk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqamnvs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rljgprno.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nrobdcto.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnqufhw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqjkzmn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhapeqmj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlgzgkn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfjkbvo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsxnzet.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqinfls.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lptyhaic.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrppnmm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jomjlaqu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmwsnju.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjcermy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nocedajn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmttwte.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdextidg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dabdledx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2urhxwctn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mignihip.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uaizmygh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhuilys.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fjndtdax.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbyfiey.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmqqkma.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ibarwwpp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfazvps.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxllfwkq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwhnfzd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzvhfut.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2msknzjyb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhjumbx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbfcjmt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdktjcil.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtealuf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bujaptjr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvhtdle.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2icreeicl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tlntyduc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xilghsib.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsscszb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeegswv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jabwjpjo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpxeyuh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwhtopx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2neirolwz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cogmwchq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qgetxeeg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxtcwbt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2anvuzvca.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcjbdhs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgtaryi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphwlxfw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odeoyswf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiklpftc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoejlma.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uzixvwyd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkqdyrk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbsqyuc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeyzrzw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlfqlec.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxkmtt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxlybtu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfbqezh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvzoxdi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahfpoc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cczhtkhu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwfjsug.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mckpojlv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qqugoeno.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2giwllxhh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixddkvqr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvdaynl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2agfyudxq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnqhla.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bogkngll.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qahujkmb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsnvkwr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrvjirl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxwxchv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeqjdua.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhsmpen.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cznoudpl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxkiksb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdztawlm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fkniljbx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fznumwkf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2srjmzvkg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydppshte.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgoccmr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2izyuubtr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsvfhng.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2epkgstzo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gczmydxx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjblaout.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmrpbbx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzctzqsk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vbinfktj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjunpzbm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwvyosz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2znenuekw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwemksq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2keukvkwx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2excnuick.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfsssuw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2guaxohlu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2juuxkljz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfiadth.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgltubn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuhwlsc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2msbohhgs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umanxepy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyyawnp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwdborr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tymzjzeh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgktxpb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxqxpqo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2shebhdpx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qykdgvux.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxcpotz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrjvvbu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2erqypfai.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2maflpjaj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2icxvxtzd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iselwenb.html


<!-- 参考信息 -->