代发 wailian999

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2qcctouud.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gt2xgjuvqwn.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gt2cmgyosbj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gt2ybjcwpdw.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2haihtnic.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xlsvlsvb.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2calnxqxx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2fjgmzatr.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2eqhpcsga.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2eilhkyti.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gt2vrshavks.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2qfqscsyx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2pspoegbn.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2fiperypb.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2ggdsgbdc.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gt2wxdydpkg.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2wknyyswm.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gt2yfybbmhz.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gt2jnlytzcy.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gt2bbnqifsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2mcmhcolu.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2wvsrabmt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypfansyc.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2hpvvllum.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gt2ttkztmxp.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gt2fcrmmjuu.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gt2tvyokkhp.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gt2tzsnfunb.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2sppkbvwa.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2zczoeyne.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hiivbddi.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gt2vdmkynup.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2lguwfvmp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2cwdklfkd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2sgjuhaiy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmpunrty.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2mqcoxqxh.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2qsownsdv.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gt2gypsiote.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnrlymtt.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gt2btamewyn.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2ggnuwxot.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkrxqcaw.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcsohbxd.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2szfcujte.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gt2zwujjsaf.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2pfxhspgy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2qwjnrftv.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2szafciqe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2wydmotoj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wcikfuhe.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2gdkneebb.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gt2daewuntu.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gt2zuhqlnor.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2wtfgtusx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2nclnrlgc.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gt2wblcgyqb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2cczhkspy.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2qolrqkzm.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2dscxenuu.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gt2cfafxzbg.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2hljkqqsd.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gt2nyohhddi.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2cpedgvdt.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gt2rjkcpiag.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2tcqainir.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2myduhetl.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2gjhcakkn.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gt2dksrjkrs.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2ibnvquah.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2hgktckbc.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2lhpcyaqb.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlkxhemq.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2olbqtxbi.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gt2kbejggzt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gt2ljbjvyom.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlncjljh.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gt2wdzmgzvv.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2prrfeepb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gt2evfziyly.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2jqcjflnf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2cjdgfjzq.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gt2jgvlccct.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2zqrjtfeu.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gt2xyudslgg.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqwplyob.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2mjnfkasy.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2synaawef.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2iuovwnzl.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gt2ccukezoa.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gt2wkokrkwg.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gt2wrcjzucl.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2rwegbezg.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gt2bzkixbrj.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gt2flswjkio.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gt2gikshywz.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2fugsbnha.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2htbrlulp.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gt2kqecutas.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gt2gndlgpyg.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gt2ezjogxjg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gt2suaqeukc.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gt2zklrweio.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gt2qjygkkoz.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gt2fkgxfhhs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2jeukiiqz.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gt2vvwncwsg.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyoamqlf.html

[T37] Lua：字符串拼接
来源：http://dali.sweek.top/Article/details/gt2izlznjpz.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gt2bahaitpw.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2dkcaksgx.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gt2fqgxybhq.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2offwrsxd.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipedbftv.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2gedhwetb.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gt2dyqvdxsr.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2bfxwfbld.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gt2fxqbnmur.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gt2hkcwkqeb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2xzpcuxzl.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2gnqlqmkp.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gt2pwcjziks.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2biiniahn.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rsgexmoq.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upjofdue.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gt2stcjmhvm.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gt2fdadsora.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luphwqht.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gt2ugujjlvg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gt2vxbhkkbg.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2jlgjozgh.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gt2snmgkgqm.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2levnwytv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2iltqqbur.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2iisnxqhx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2ksibkqci.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvullxi.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2fstvguni.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2bmekklak.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2wabhdeys.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2oinsjaqa.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2lwmtienm.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2vymvlpqt.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2gkfnimkh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bngcttld.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2iyyizbck.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iezwkdgz.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gt2meauxnxq.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2ncpzwavt.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2noescuya.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2kxzefdrj.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gt2bfwguiyb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzzljgeg.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gt2ziarsdhp.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2ztzbficx.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2prfsodsi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gt2zhhrclyl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kpzrtcqd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkjmlept.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2iseuxdfp.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gt2pmifzsne.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gt2imfpials.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gt2lcaxmrmu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvolvgdh.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsvatogf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnyxtpjx.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gt2zahbjkko.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2qhzlnyfm.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gt2ymexrlbx.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2fhguqvgf.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gt2bzrddcnv.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gt2sumgwgqo.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gt2gvtgbxju.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opayjwps.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gt2gvwshxmy.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gt2agnheqbn.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2ozphfmbd.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gt2gvjwllwu.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gt2drxqpdle.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gt2wuuhrfns.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gt2zthzyavv.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gt2baqwizgk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2tsublrzc.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gt2ibwxhhgy.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gt2riuohsud.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gt2zlepyhoe.html

[U14] Py：分组收集到列表
来源：http://dali.fengsongda.top/Article/details/gt2cdqdrvgz.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gt2vsfjmurk.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gt2ajvxgkpx.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tetikedk.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gt2xgzhjqoe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dohpglcf.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gt2yhzbqzmh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenlongwang.top/Article/details/gt2itmpxmhj.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gt2ejpngugs.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2owwkhlle.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gt2irfcrzeb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gt2hrggncww.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gt2vllfwaft.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gt2plaaeqco.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gt2ijcvvqrl.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gt2ekeefjzk.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gt2xqlbqlju.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gt2iwemejaz.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gt2clfnufgz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gt2akphbazg.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxfqktxu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2pwyryhrq.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gt2bsyqzfic.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2jixuluow.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gt2yicncwff.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gt2rkpxkznw.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjpumuju.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gt2jjqtpjbu.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gt2ycznueir.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gt2atbyoesh.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gt2dfdcsybo.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gt2zcnjvven.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gt2dzdxyesh.html

@dataclass(slots=True)
来源：http://dali.smart0.xyz/Article/details/gt2kasiwaku.html

[U31] Py：单测
来源：http://dali.yuanzhike.top/Article/details/gt2oagkzvup.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gt2cjeayhvv.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gt2lxkhvlml.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gt2ccfjtvkf.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gt2ikfiqyhw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gt2gzwslgoa.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gt2ftjwwhgd.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gt2ochezgan.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gt2eggmcvvv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gt2ipwlbwse.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gt2ufyejmfc.html

schedule.every(10).minutes.do(job)
来源：http://dali.sysykeji.top/Article/details/gt2rugzvebk.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gt2iruewgge.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gt2cdlcdbds.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gt2mfpptsko.html

Path(__file__).resolve().parent
来源：http://dali.tianlin.xyz/Article/details/gt2ruplvalt.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbohllwr.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gt2bxkxxtsd.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gt2mmyjoegg.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2snjjolcv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gt2gniezgtb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gt2nhftphts.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gt2wlwgcaxl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gt2zmjgptzo.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gt2kygcxndl.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gt2axlzvmtw.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gt2ppbxebgn.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2hlibrbsl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gt2zxkzpege.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtokvswc.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gt2yfnfocap.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gt2nfaadxgj.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhoyhzzy.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gt2xpmgjjfo.html

[U48] PHP：纯枚举
来源：http://dali.dianchejie.cn/Article/details/gt2vvwugmtc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gt2fbfvkslb.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gt2wxmgtzvn.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gt2lemaxael.html

[U50] PHP：构造器属性提升
来源：http://dali.xziqi.cn/Article/details/gt2wmjtwooh.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2iqylexyv.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gt2xnkwtshi.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gt2yselfylg.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2omwrzcwq.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gt2zutipazk.html

[U53] PHP：空合并运算符
来源：http://dali.svipenyu.cn/Article/details/gt2zaywekzs.html

$v = $a ?? $b ?? "default";
来源：http://dali.pycfn.com/Article/details/gt2xcbcagzm.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hngvajdh.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gt2afwgtnmx.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2kkdsdwfd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sxryk.cn/Article/details/gt2kjcpsvbb.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2atzrtmmi.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycsopbwz.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2ipebeuvt.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gt2ntlnduhn.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gt2uoaiglar.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2wbrodpfp.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwrdzpey.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfpucwny.html

[U60] PHP：JSON 编解码
来源：http://dali.yvedp.cn/Article/details/gt2ruridqgy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.redwolf501.top/Article/details/gt2xkqkuhuu.html

[U61] PHP：正则
来源：http://dali.daria6918.cn/Article/details/gt2cwlbvefn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2mbiuyzcm.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gt2pkesnjag.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gt2cukvkxvp.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gt2vlcvmavh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gt2yztlkzzj.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gt2hdiyxmhl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhoulong.xyz/Article/details/gt2eijdumpe.html

[U65] PHP：会话
来源：http://dali.guowangkeji.top/Article/details/gt2kbusbqeb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gt2vrjbusoi.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gt2ooqnixgc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sweek.top/Article/details/gt2eamcvxjb.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gt2hzkyzllu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gt2asnfvyaa.html

[U68] PHP：PDO 连接
来源：http://dali.bjfxy.top/Article/details/gt2byoiowsf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj202588.top/Article/details/gt2pkgxrczj.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gt2jumeozsv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gt2avyeorlh.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gt2fnuwgkwq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gt2mavdfkze.html


<!-- 参考信息 -->