代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gthisvudkt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtajuxbcus.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gthprwddnf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gtqiuufeaj.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtlfywgatl.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gtvvwctyfj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriacssns.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtadujhyqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtcjddunyb.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgcjqfia.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtdcqzzihn.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtiohdiurd.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtvablhncx.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtgtdjohec.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtntwsihrh.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtzyhirezj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtepkibrnx.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gticxsdvuw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtgcrvqcdr.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtkmzuiifw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtyylfirbu.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtcbfksdrj.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtvafrdpff.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjmyjupu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtcnpjqxmu.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtnqoooplu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtkpffzndx.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtbalfwdrw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtcwdkzmcr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthjsqgqri.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtufqozkck.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvmshbbhu.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtjtzzrrgt.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtyrmmkzxh.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtlzijxndf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtoorcndcu.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gteepcxzkb.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtwczntueb.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtadbuqnpo.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gtnrogizee.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtnqoecfje.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtmpqkgozg.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtdufykdps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtqsjilcbu.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtdgpmujsu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtmbjnzfgl.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtwbqomloo.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtdjypbobo.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtyncmvdlh.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtzkasjhaz.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtdpugckqw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtdkflejso.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtafepystz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtqlzghowq.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtietjlyst.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtrkwqkblr.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtvlncxgrj.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtchwmnvwc.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtxbahszvh.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtiykvhvaj.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtovhestvw.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtsnpjqemv.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtcbgcwakh.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtjcltxzya.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gthliauolj.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gththtcslt.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtawqhaccu.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gttkhkjiad.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtmvypjywc.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtcjpkmjwg.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtflyynuru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtinhleomg.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gtgdpstbra.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtmrqzuifb.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtwprfiqdc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtardxhdbt.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtyymbbfkw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtjtsufsif.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtjafbxpjn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtgzwzfoqo.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrjxufot.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gtocvtluhh.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtwffknfps.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtbdrziccn.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtmnnselyn.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtlmtcdtve.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtjwgidkbn.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtqiaxzjuw.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtdtjarxvu.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtcsenziin.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtrzrvbemi.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtjkcuebea.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtjoqimliz.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gteytezbyf.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtrdfbspcu.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtjusegrwd.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gttfgtgzrf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtascklxjh.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtfrgwrpxp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtitswvoml.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtwumtefnf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtibthwhmz.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtfshfwria.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtnfjsqxff.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchmdslru.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtehbkeoaj.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtbbymplom.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtapjkbjqu.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtreicociz.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gtgcelmnve.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gtuaxtoaaf.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtarujbfxm.html

[T41] Perl：Hello World
来源：http://dali.havefunace.top/Article/details/gtvnkxhkoe.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtxoygzvvq.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtqxwuxlcg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthiehgxw.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtsfyjhphz.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtwasrubyc.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttohatkjr.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeldfzhj.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtopcearte.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtspydxsyr.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtsxcdggvs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtnlyymzcm.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtpbdkozmg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gthwmrjhnk.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtondxdcqj.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtguccefdi.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtnrqneqpt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtffdczuqp.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnvbmpzrc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtvgzmbqqq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtvdlhckdk.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtcmrimvwk.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtahodwkfv.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gtdozbgevz.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtawfdpcki.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtmmstqkmy.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtlzoahszf.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtmvyfspek.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gtreslxzsm.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtpgflzjnk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gtdsuarlnq.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtufmfhzeg.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gthoycqfpj.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtmivyuaah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtnaaqjwyp.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtmwteiima.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtisgufyfy.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtmxlinwur.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtxrwxathz.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtsxdttybi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gtrmipgxvi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfezxcsbh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtdxfhtgfo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtaokflpct.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gtwglsyetj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtroaojcpg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtyzoytlnj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtrungmpgg.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gtbqbhxokd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gtiurgcsyw.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gtolztsale.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gtpqtwxqep.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtkyyeixky.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtqfkjphoo.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtpvrptwii.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtrcshnapu.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtxjlxnixw.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtdxiyomli.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtiqtlasea.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gtyzakovzx.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtpkwrfuka.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtdeszxaxb.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gtvjufursf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtlfhnmyzx.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtoearxnew.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtadirhlks.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtpqcrztwm.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gtsiidkoxk.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gtgfdddfhw.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtalfdclvr.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gttbuhojsb.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gturnbpndr.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gtpqlewffe.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gtkgansczt.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtvquwqnrc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtzkyluork.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtpptqeyxz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gtylkdooet.html

[U18] Py：预编译正则
来源：http://dali.xziqi.cn/Article/details/gtfgapnivz.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gtzvtpejav.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gtxiokilmb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgiptohtb.html

[U20] Py：缓存函数结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfzzpsij.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtmhroalky.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtvjlztpbr.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtmcbwsslh.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gthjjcpgin.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtaqkwkygw.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkibimmrh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yongpay.top/Article/details/gtokiuelrh.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtmsyazuyh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtzzyzdppm.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gtvgqwuzcz.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoftjlik.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtdlatputm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sufxvd.cn/Article/details/gtofsfxyci.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtqtyjosfl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtkeplfwhy.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gthljttmom.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gtiscceddo.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gtasustinz.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gteunvctqx.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gtrvfnwtoj.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtjlmlrpbb.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtopbueddc.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gtfdriqdag.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gtxuqnsnjv.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtgooqslsx.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtkanwglih.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gtasgyhzrg.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gtgtvqvnvb.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gtgmdmpkft.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtqknxzcny.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtlasdtxqi.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gtepjhuquq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zycfv.cn/Article/details/gthewmvngc.html

[U37] Py：读写 Excel
来源：http://dali.zhiwuduotai.top/Article/details/gtoauwkuyo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gtahomutes.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gtegpkmwvw.html

Path(__file__).resolve().parent
来源：http://dali.xuanzx.com/Article/details/gtyywtumbh.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gthvqimwki.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gtcfgyeaao.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gttwsregip.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtazsnzazq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gtvdkrqlqy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoucrokzs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gterjaxnga.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtwgasdirx.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtczaflgua.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gtbnqohqew.html

[U44] PHP：开启严格类型
来源：http://dali.shangyingyoupin.top/Article/details/gtgastebqv.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gtuhkazddx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shuidangran.top/Article/details/gtgfqxrgut.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtxvbaykgl.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gtcelppuqh.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gtbjupqvkq.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtvigkiqbf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtovjjifpa.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gtpzdafwjn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xziqi.cn/Article/details/gtygwkasbz.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gttuqylafr.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gtpuonynxt.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gthmrfthuk.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gtytawybzn.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gtmefjbovm.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gtfvcvyinh.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtdnnszvqc.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtbbembtli.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtukxkfabi.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtyaihvwoq.html

[U54] PHP：空安全调用
来源：http://dali.jqgfzy.top/Article/details/gthhmnifff.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtbgmcuhqw.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtwobgelrx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtfpcswplr.html

[U56] PHP：命名参数
来源：http://dali.fengsongda.top/Article/details/gtdkadfums.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtvoobnqyh.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gthlsdgfse.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gtmamjudgm.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvwormjr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtuklrnrkj.html

[U59] PHP：自定义排序
来源：http://dali.aizwys.cn/Article/details/gtrgnymojv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdouepppm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtfodjpefu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtdtqzvevs.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gtsmfokuyp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtfdevzyss.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtcrhekien.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gtwieftrzm.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gtvckkvgrg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gtxrdvuxhv.html

[U64] PHP：目录遍历
来源：http://dali.redwolf501.top/Article/details/gtyqqoluvg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gtrfwaujuh.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtxlvhikpn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtqlyugxdp.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gtjgpiqktg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guannengcc.top/Article/details/gtsutmvewl.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gtnrjnidne.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sxryk.cn/Article/details/gteargyida.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gtilvtiwsx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gtzoqinfei.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gtxopcctzh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tian-w.cn/Article/details/gtvzbljewv.html

[U70] PHP：PDO 事务
来源：http://dali.xylfe.cn/Article/details/gtnrqxnuai.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtvptdjvvz.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gtorrierwd.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gtrntmacht.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtsrvcrssn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gtzpfnywxs.html


<!-- 参考信息 -->