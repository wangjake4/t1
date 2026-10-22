代发 wailian999

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtabtvmqzg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtitinglhu.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gtbweqlrym.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gtuwwptxlx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtgghlhcle.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtvtogftow.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtwdxtpruh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtsqgemnyw.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjwprgvb.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtwouirugz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtuornbmpc.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtlawekflg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtjzbcoari.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtaciuymih.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtrpgoxday.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtkkxtludv.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtjmlkwrns.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtscortrzb.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtdgavyezc.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtssimsvnv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtlyipcrti.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtpgnrzqgs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtjmuiznac.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtzazquish.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtsavqhwng.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzmiqlzp.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtnvvpxdqs.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtkjbembwu.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtxfslfgqi.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtqzjuhwvc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gttzoswvua.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtqvktiydf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtiepckupt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttekbvvvo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtfiyywwam.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzcxjnlgk.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtzvyjnusl.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtwefpqvlt.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtwelfcarn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxbxyoij.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gthszsjsts.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtadwaqhdy.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtocwxcbrj.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtkztxhets.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtlbojldsv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtpdfydqyb.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtmzermusx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtrjxnrqbt.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtutmfeuku.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtkzkntszz.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtrxrnmzam.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtmgxkwpyr.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gtmmcamise.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjzexuft.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtykvmtmlk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gthpzfxhbn.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtjcdxtdru.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gteoxvsofm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtvokiumnp.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtavmvdubn.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtjxucxcyd.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtbczqavxl.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtbqxucizs.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtgedpmmmq.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtiuqjesws.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtskcfbwrb.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gthanqvnxt.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtcepiywrm.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtbgiucxbu.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtzvincdvt.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelamzlaa.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtufpphlmf.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtjusnkpnb.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtcwuvzgbw.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtckkwwhsl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtimjphuyy.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtpngniuvs.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtvwelnlvn.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtfvzlyrci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtbphbktyf.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtxlwcuibx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gthsxpngya.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtsbfeehei.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtdttokwrm.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtgfswgoww.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtlfhvvyty.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtggwaborq.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtnkkplajo.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gtjacwgati.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtsaqpgcfr.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtldvbylcj.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtnootwkkq.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtkrehfsby.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gteokyqzxb.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtiphhgaxu.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczpbjhfh.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gtfektyiqv.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtdssndgbb.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtvoewjztx.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtotroxklq.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtuplulfnv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtzjbsherh.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gtxfwitbeo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvxyehuc.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltzavpnv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gtvsahzcbc.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtvqutzmvo.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtneefbkmf.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtawqjyvxv.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtrjxrclnl.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtirzdmlhs.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtvcxyhkvq.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtijsyvexh.html

string.find(s, "%d+")
来源：http://dali.hfpthk.cn/Article/details/gtusjrwpiq.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtqnsfpfun.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtqdrhsmtt.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtkkwaeuub.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtzwxgfbso.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocjnrhca.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtrykzrxly.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtuswqgbpz.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gttdkeliff.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgltvvtjz.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtozzycanq.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtkehuzfao.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gthigptiik.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtdotayxnx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtznobiubh.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gtrdlpfvif.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gtfmhbfnjg.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gtkxmvlqmd.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdtcuacm.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtttqpfzpa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtmpzrsdni.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbtcdmjv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gthwgdnkxx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaapntohz.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtgtpxeict.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtvynwokun.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gtdckuuhoo.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtrdxcoqns.html

[T53] Scala：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtgndywppi.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtizhwmkhl.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtptfpjbnq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gtnwqrhfso.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtexvfgjgc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtvnycldum.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtdkqdqxdh.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtkxkgyrbk.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtfjxtgzkw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtulxipgyv.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gthpujkwyd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtsoypiame.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtunwqmidx.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtnbrlkwfa.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtrkwnjyac.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtidwccmpn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgzxntkmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtqyvgslis.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbmwqeugr.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtrotsnkqn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtdnqdvyoi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gtqxptptpl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtsirninsw.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtysbtregt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtydhfihnf.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkkjvndb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtmbaeseyi.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gtjmcybfzh.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gthulnlokv.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvijfxnx.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtpbnfljmi.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtvsjlszvp.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtfsgulufi.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtnmyebvje.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtrlrmrhcu.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gteyopnwfu.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtylillxab.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gtzmgtmvgh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnttzhpo.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzutfltoe.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gtiwbliulz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gttaluangk.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gtgjpdyast.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gtiqqxqzlm.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtfwqagexx.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtrtuibtta.html

defaultdict(list)
来源：http://dali.dashuyun.cn/Article/details/gtkjzktbnc.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtdqnazsjb.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gthotuhowm.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtxggdjimp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtmxuoubac.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtsvdblrrb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gtnavyzwlq.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gtiwxvbews.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtmcmussyf.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtlvlnvwhs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gtypfcrhlp.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gticltbvlt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gtuisvtoiq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gtbkpmtnzf.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gtzhyfgtos.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtzrmfbovf.html

list(zip(*m))
来源：http://dali.zdqjudy.top/Article/details/gtwybzlndg.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtadpgmgiv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gtqocdhupt.html

[U24] Py：路径操作
来源：http://dali.chenjidiqi.icu/Article/details/gtvepxjdpo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedpawdzl.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gtmifuhbcn.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtwwxpwjww.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gtfnplregb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gtuligmbso.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtkymkzken.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpqptofc.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtjtalrlep.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gtlavllsnz.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtzzjvjbze.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gtcrgugadn.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtgbdlhpzw.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gtdmrauvpz.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gtehxmafiu.html

python -m pytest -q
来源：http://dali.tian-w.cn/Article/details/gtotnqphrd.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtmjgvrlez.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gtiavaqsel.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtaekgtjmc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gtsocjhcgg.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtegbfnaqb.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gthjrdefjn.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gtmhxmtqex.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyfpxveu.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtpsqmixdc.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gthfouxfmj.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtckmtmmpd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gtvacvqdcr.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhogsnbt.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gttzqfgsge.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtfobrdgqj.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gtebfpcizf.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gtphsqnrxf.html

print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbpjcdzde.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gtjbjtglwz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gtvlzccvmv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gtjwpwojcl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ppjwa.cn/Article/details/gttnilijyh.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gthsffrvfm.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtdcmtiagx.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gtxtpsjfxx.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtblzpqlce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dianchejie.cn/Article/details/gtkhctpodf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtpxhqoffq.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gtoywekmdt.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gttwfmwzgx.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gtonwvfwfq.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtqozxajgf.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gtvqvgiqth.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xinyue.icu/Article/details/gtipxownvp.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtqhufwcaj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtiogrelax.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtdcvssefd.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gtonumeswr.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gtofrccvye.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrviehjmu.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gttkzjpdhs.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gtiuqmggiq.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gtlynpifrr.html

$v = $a ?? $b ?? "default";
来源：http://dali.hongshengwenyu.top/Article/details/gtwzjwivvs.html

[U54] PHP：空安全调用
来源：http://dali.redwolf501.top/Article/details/gtbzufogti.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtjdckecab.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gtqkunecwv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtvufberjs.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtpgsjtwrp.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtwgjwgjwa.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtubjnoiae.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gtqlquhpvg.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gtogbpfuqw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtvbkqfvcd.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gtflokilyz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtsemjmvmi.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtjcyhfwoj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.birdmap.top/Article/details/gtchpttcvk.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkqycciu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtjmqarndf.html

[U62] PHP：日期对象
来源：http://dali.jyoumei.cn/Article/details/gtbtgvllac.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgfzy.top/Article/details/gtdqsrndyf.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtpsghkner.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gtgjpgzvtd.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtmftoerzu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gtvfmtdqmu.html

[U65] PHP：会话
来源：http://dali.vqdsnc.cn/Article/details/gtlhenmirs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtwrmhhpcl.html

[U66] PHP：设置 Cookie
来源：http://dali.wangshuangyany.cn/Article/details/gteezwmffz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.smart0.xyz/Article/details/gtgteywnfl.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gtcoahfsuf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.iojbl.cn/Article/details/gtrifkxwjz.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtrsmtwtjd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtmdfpypfo.html

[U69] PHP：PDO 预处理
来源：http://dali.shangyingyoupin.top/Article/details/gtlffkzcoj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gttbfcgylt.html

[U70] PHP：PDO 事务
来源：http://dali.jqgfzy.top/Article/details/gtoypmloal.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shangyingyoupin.top/Article/details/gtumiuvqoq.html


<!-- 参考信息 -->