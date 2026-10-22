代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gteipotevd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtpytiarzv.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtubmdkzjl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gtdwftugwq.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtcjjkbtei.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gteelmyghl.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtevuciulm.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtcipscltq.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtcwpltgky.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtqnaiqdpi.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gthxoofsml.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuufmzav.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtkpizmdsg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtlhtvqcut.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtfksfduyp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgdyrzjq.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtuhzpddoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtnqxezhmb.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtttszxhfm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtapnvyqdy.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtllpxujgp.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gthslpveuc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gteouokwzd.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtlayhtjya.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtfvorcwjh.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtwfdglhun.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtdyatjdjf.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtcmbbxpgs.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtynpfhtif.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtrdwpkewh.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtlpctowrb.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfglylyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtchkweyww.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtdczvxulu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumbfmpzv.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtdscsckvy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaqitaemp.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtwrkdauzi.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtbsxcbgtn.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gtgmnvbcqz.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtewmgualf.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtwexxdcyp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtxfnxkrfc.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtigkgwlxj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtugcglzhd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gteyoyuwcn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtsaysxolp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsqwajyog.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtfugtsdju.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtlulxlkco.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirglzhim.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtijrjcnxu.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gtfweqykaw.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtsbetcreo.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtepplevhu.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtvkqvztug.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtebnpvrsv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtoonoheky.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtjuckjdks.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtybrtmuqf.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtftlhzofg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtvhnyxfku.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtikodmrgt.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gttvgrccmc.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtdkqipsfi.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtppyyviyr.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gttlbtbngd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtoncusyyq.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgluokdhi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gthucwyjod.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtdaigazof.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtabcoahss.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtpragrftl.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtiqrexqey.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gttslghuez.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdqwijee.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtuvhxujwj.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gtcqmmdxer.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtqaaoghpn.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtjopqqcgb.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtcoguuzdd.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gtzsmtcbiz.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtcnxwbizs.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gttjhnjfnf.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtzkmcfmvp.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtkghluthb.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtuozraztm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtoeadudgu.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gtlbplhycj.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtfqlgmypn.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtvhcxzotz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gtdvqepqcc.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtkfblkfvv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtohxbvgos.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtumfdwvjd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtalzlmeex.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtrnqynczj.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtgfemaftm.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtofkegbhm.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtqzekutws.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtzcunmzzw.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtaplgjnod.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtwpcplmwm.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtgpwzvukf.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtqqusqmyi.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gtwprtnduq.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gtonztxune.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtgvoibtvv.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtorwacjir.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtnejtdxiu.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtktdxorvu.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtlxemseqs.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gtwxlifrrg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtibyschei.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtpwouxqhy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtjlobknex.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtqlkdgnuq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtmoetbrxw.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtwbsqonvg.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtjmpczcrr.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gtdxyojkyv.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gtpfpzouqf.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtgekqvziv.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtccbciqfg.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtuznazgnl.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtoziiyqzs.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gtelirxure.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtiwfrbyer.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtxizjynec.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyufkjiek.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtyquwoazd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtztdrlwdt.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtqagwafxq.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtnqlpdeal.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtspbslumv.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtqbvriqbo.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtyzzlifyk.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gtztqxguxt.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtonexpmdc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtweijbxwr.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtccutcrow.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtobyahxre.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtbtabweyz.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtvwvuxecz.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gtuuypipcs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtgmavgqpq.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtwhqjerty.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtvoqmeily.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkoeznbqv.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdgxhjxq.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtatfbrqeu.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtxfriundb.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtghkixsbo.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysqlmglw.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtxpsljrmh.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtnjoexvsy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtxtkfzdky.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtkduhedzb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtxuscyrpb.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtvhozhtrp.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gthldtmsif.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtqjuahzqw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtvgrinrfw.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtzfwjzqxw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtqmbjhcrj.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gtaefacntl.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtifiqrain.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtsypjzpms.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtgzjdklso.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvcvcqogk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtgjdmbwwc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkzcuxfcs.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtycrhednf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtqiikouvw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuylfdmal.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtlvobpxmq.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtxggzwdeg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gtlxeqansh.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtidpajelb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtncjgysto.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gtyldorykc.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtqmxebggg.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtdulnkfmk.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtiyxxeuhe.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gtvsxlkcuw.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtcnmavnga.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtqdofwgax.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtispqhyax.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtdikthgzm.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gtixvlindu.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gtqyuitrhx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtxvxpcozz.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtjcvlzwvc.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuodmjyl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtqklnpzqm.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaguwayi.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtaaebsqnl.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtlvnhcyqh.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtgpougedw.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtnyvczjlu.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtssbbkydw.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtynyrcnxb.html

[U16] Py：命令行参数解析
来源：http://dali.havefunace.top/Article/details/gtbnkfqjrf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gtihbfmsln.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtcpjnwpie.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gttdikszbr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtynyjvyjj.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtawabimmq.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtagmfitit.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtdpmpbmes.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gtyqikqzny.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtkbjcfpaz.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtxmdscwdy.html

@contextlib.contextmanager
来源：http://dali.svipenyu.cn/Article/details/gtiykhdcan.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gtbbnyfggt.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtzieszgqu.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtxugtmdbk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtrqqftgmt.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gtsvuefxze.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtzbdvenvj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtuhbbsnqz.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtabrqhzpa.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtuhnnlniv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwruvdtrk.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gtiiutelae.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtseneyocr.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtniubnxpx.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtyuiqknbr.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gtxtnzarwc.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gtcorkklky.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gtizcsugse.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtqlyqxkfx.html

[U31] Py：单测
来源：http://dali.hammf.cn/Article/details/gtntakvekc.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gtswwljiuc.html

[U32] Py：代码格式化
来源：http://dali.mhx1999.top/Article/details/gttiuhyfwb.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gtsnkjujrs.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gtncdayefh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gtwtsunmkz.html

[U34] Py：判断编码
来源：http://dali.feifeiyinyue.top/Article/details/gtiiwywgpo.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtdmeijvrk.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtjehdjfsp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtxyvvcako.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtnhxiacae.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gthloticnx.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtthigcmep.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigufen.top/Article/details/gtmzvptgnm.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtfpriyvzx.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqngjuapb.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gtasdewros.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcneekqdo.html

[U40] Py：打印到标准错误
来源：http://dali.hysaishi.cn/Article/details/gtvzmvqblm.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtytxnuron.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtsthymftx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gtfzmjnblq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gtpjsgvwdw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gthnviomiy.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtrpeityps.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gtwijrtfyv.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gtqepdkfln.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gtfwhiqduw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gtkhzoslhp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtwrxsrwqs.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gtkjqomwqv.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gtxrfvoujd.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gtjefeoovo.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gtuoyiidpl.html

[U48] PHP：纯枚举
来源：http://dali.c1oappe.top/Article/details/gtcjrhnojz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtmewoibqi.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gtoblbykkf.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtlwzgjoax.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtcypttqfn.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gtvimroown.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtpydjloip.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gtfyrrhmgy.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtgjrthejb.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtznrapedd.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtclfuwalm.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gtboggyhsy.html

[U54] PHP：空安全调用
来源：http://dali.guowangkeji.top/Article/details/gtzukscnmf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtxqxibhvh.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtdzvazogk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gtrnbhuxzj.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtnnqytgng.html

f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtiapoiphr.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoypjyli.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtcnhpopqe.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtgfjusddw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gtcpbevvav.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gtktalaogr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtdnzdodwd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gtxrbqkdbi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258888.top/Article/details/gtzafuyybw.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgoubarg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gteggqxwuo.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gtdqhcgcvd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gtnqsmythe.html

[U63] PHP：文件读写
来源：http://dali.316326.xyz/Article/details/gtbqrqwclm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gtmnqkwpim.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gtnskroebr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtqvbwdhna.html


<!-- 参考信息 -->