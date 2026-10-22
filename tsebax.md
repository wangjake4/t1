代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2pvsqlvoc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gt2endixtdg.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfuatdln.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gt2dcztelil.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gt2qaadcyzl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gt2kdpwodmo.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2zhnsstws.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gt2epxbpdwp.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzjtlixj.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gt2hvqkkcxy.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2mwegqvvu.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmgvibyq.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2iedhpcbq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gt2owwoyapy.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2hilxvmsi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gt2balpfrtd.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2cgfrimxo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2hjdqzrxg.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2xydqfayt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhmzmjxc.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gt2hvfwhjua.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2ezblmiqf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2ghiwntii.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmqexqev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2abbwxaby.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2bjgddxtw.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2geronket.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gt2uyevmxqd.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2awdjxlmt.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2mpqjuaxd.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gt2gdcmrnif.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gt2bcwettfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykjjsuit.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gt2ptrfgrtf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gt2eousupdk.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gt2zqfkvinw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2fkxzmrlg.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gt2uixaqozw.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2ybueyqzg.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gt2pswvxump.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gt2xxxriidd.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2kzwxllzn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vanvditq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gt2stnhmxyg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2kgrhgrld.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wrsbatme.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtxqbqz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wybghdtk.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2mrzipghz.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2ptnutuhn.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2egujvmnr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gt2kxhtxdbu.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2dolzibdy.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2fehdgiju.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2dpitcdjd.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gt2mhmbtlvx.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2gmxjgyoj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gt2lkgheitf.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2hbxwrpjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2fzyxdwbo.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gt2mxuqlngr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2vcyzdfwj.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gt2ugcqrmjr.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2ydpnbxgb.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gt2rkzwvuqn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gt2keymmtee.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbdpsxdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2jhjucgxm.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2adqxkexr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2hruxnhsc.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gt2pafwmnqh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2mlzpayax.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2najasgzi.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gt2vjdorllz.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2qqkmgxqx.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2oajhoska.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2jlwxherx.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqoiqrql.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2rwxteozy.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2bxofrsnj.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2jnexhizc.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gt2jkbhlnzv.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2rkgvpwmr.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2mlpsdjdk.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2ztoyfadx.html

if let n = opt { print(n) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daszkpgo.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gt2gwxjzhdi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gt2hynqhuxb.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gt2usqpsloz.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2gfckjfkq.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2dnjtlmzp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gt2gwfnusjf.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gt2ryxdyisq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gt2gtlqvayk.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gt2urrjmrui.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2jobfykct.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gt2egnikcpm.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2yyujwqhm.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gt2qneyixas.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gt2uhldomsc.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2cndvlsst.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2ktxfkruk.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2bgojiqqn.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2xvdwglpf.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2qvpfeeyj.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gt2rywebkah.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gt2mglnpllm.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyiahpmg.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2dkdwlqch.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2okatubpf.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gt2orfndvlw.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gt2tojjnahm.html

[T33] Lua：表（数组）
来源：http://dali.cdnleiting.top/Article/details/gt2xqwrstvx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gt2ticjcqze.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gt2ottpqzjw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inxxvibc.html

[T35] Lua：字典表
来源：http://dali.jyoumei.cn/Article/details/gt2qjhvqsvj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2vayajtef.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gt2ylrsengw.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gt2rrqevxno.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2kbahwxvv.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gt2rytlgmhl.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2rndswbbv.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gt2ildzuoau.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrqumlpe.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gt2aiwvgbge.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2mmtfabvj.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofoppvcs.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2gslijwsq.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2ohdwfcnm.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gt2sumilbwq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gt2cjxzujsk.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2ubuoafdu.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gt2sxkiyyyl.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gt2mlisywkd.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2fghuovxc.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gt2ielmswxi.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gt2jcnoscvi.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2grgbizqu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gt2trcbkeor.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gt2cekkrvri.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gt2vawexbaa.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gt2jvkxvuiy.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gt2lrxszfda.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gt2rzdnayaz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2doaldyzf.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2zyiyzmpq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gt2aislafdm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2unthfvsa.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqpjomyq.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2viohzuqk.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2xhehimib.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2awbvkryu.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2uoenlpye.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2vuhzeant.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2npecvtib.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwfoizic.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2polqcqla.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gt2aqfobeqd.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gt2uqjxcwsu.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shtbbnoa.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2yqsdcqpz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2rukaiicv.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gt2wnhlawfl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gt2lgehgtco.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gt2cqywqzhr.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2lnbfhoet.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gt2xrpvogha.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gt2fwtqtarw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2citizcvz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gt2sqvonkzc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nudnujmg.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdylqrml.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenlongwang.top/Article/details/gt2xkniltvu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gt2uhdyuwzr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szdmeqpy.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gt2qydkpifu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdrgfzqp.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gt2stuqxgor.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2kfskocuk.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shvuhsvo.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2hdvvhmvj.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gt2kncgmmce.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gt2rdutryvt.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gt2uiwwfcuc.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gt2zxrcykfm.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gt2ehrwjzwk.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhknawmx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amdjcjqz.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gt2cnqusjim.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gt2etdmjbun.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gt2vpevzzlg.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gt2gquphofu.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gt2qtubxega.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gt2wzbuplxx.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gt2ybiajixn.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gt2zhbreomt.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gt2thspkkuh.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2cejbszil.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gt2xcqtxygd.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gt2uanhxjrf.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gt2bynivbcu.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gt2yuokkjed.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbpfjten.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyktbvtf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gt2yqqjzzil.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gt2vbdtnwoe.html

pat = re.compile(r"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2aorxmujw.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwkpcjrz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.svipenyu.cn/Article/details/gt2dtsiseql.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2lxxazhlm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gt2pftrtksj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gt2vcicisap.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gt2rnnvikcr.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gt2eysugaby.html

list(zip(*m))
来源：http://dali.cheryme.top/Article/details/gt2qtmpzugi.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2qajkhudq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gt2bsirhfhr.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gt2fmxvqdnr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2pmgqmggv.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gt2goaiszrb.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnayxyaj.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjdpuelb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gt2whuufkad.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivncrjpz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gt2iflupvgu.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gt2dtxhatci.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gt2dkwfzown.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gt2ykbkpbvq.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gt2vviqffpy.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gt2owlafwwa.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gt2adiimirl.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gt2bokseqaw.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjbjkoyk.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gt2qypjasbd.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2hyeqfhvw.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gt2fxjelqtr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gt2ukxxwexu.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gt2fatobhzm.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gt2rindjehs.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gt2ctdffoiq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gt2igosltrd.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gt2oufnviel.html

schedule.every(10).minutes.do(job)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2henbdigl.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gt2maudrzyw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hammf.cn/Article/details/gt2civkdooa.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gt2rkhgswul.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gt2xnffkdvj.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gt2fugpkuum.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gt2bkwgignt.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gt2oaxflazp.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2jskzcqds.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gt2buahcipm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2ldwxhtcg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuanzhike.top/Article/details/gt2bxzmwfhp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fampvolp.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gt2cvhlbdmj.html

namespace App\Http;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnycbegi.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gt2uflhultg.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gt2ktmpbaec.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gt2pfnaeauo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2uapxgdkj.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zeolclhr.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gt2vwrytqiy.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gt2ruuquhpk.html

int|string $id
来源：http://dali.ppjwa.cn/Article/details/gt2lxpsrfbs.html

[U48] PHP：纯枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkdfmvht.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gt2qzyydmue.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gt2byspanii.html

public readonly string $name
来源：http://dali.sufxvd.cn/Article/details/gt2dkfeuahp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecklcgyj.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gt2dertwgsq.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gt2bedxofsz.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gt2gijwldnz.html

[U52] PHP：箭头函数
来源：http://dali.c1oappe.top/Article/details/gt2zwsjmdew.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gt2vlkripfe.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gt2turjuxsd.html

$v = $a ?? $b ?? "default";
来源：http://dali.nwbrower.top/Article/details/gt2phxlrzsr.html

[U54] PHP：空安全调用
来源：http://dali.guowangkeji.top/Article/details/gt2uvihcssx.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gt2djagvchd.html

[U55] PHP：match 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2bhrderif.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2xqwygvat.html

[U56] PHP：命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdjxdlzn.html

f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2lkqrgaph.html

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2fisfrbdm.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gt2bpcmpnpq.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gt2wywgqynr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gt2rzsrqhcx.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gt2hccrzpwe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2uuzkwuij.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gt2dowqhlss.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gt2soypemsv.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gt2kqbesgjj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2opiytlxx.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gt2txylphel.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gt2eialwwoo.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gt2dmlrvaqe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ybcxt.top/Article/details/gt2qnejaany.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gt2zkduripx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gt2nqidzbaw.html


<!-- 参考信息 -->