代发 wailian999

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtxiaefrhs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gttzrlsvkh.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtafvrohfe.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtyfwepxri.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtgozhtfme.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtzfsvjywk.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gtiddsowmt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtmylajbvh.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gthzmtaftm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtpptxoxlz.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtgqtxkzrf.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtkrpirfnf.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtzxurdaxv.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtaxckawrx.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtlnpzbzim.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfbxygpai.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuspqcfl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtiumxysuf.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtaibhtwiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gtveyvsdzb.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtefyxakgz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtxscljvjw.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsedeprn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtnsvnahum.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtohkxalsg.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtfftjopcg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtfsnymvqv.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtznwxkrxf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdnkileu.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtsuwixhkp.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtjsevmzqm.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtsvoqrjuh.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtctpylwhi.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtfffplfwj.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyysjgbuq.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtusaaougi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtzxraejjv.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtrfmfjwqt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtknkbmxlu.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gtpphsqnof.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gthmdpdrmm.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtkpgqefly.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtfzqpcamg.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gthxstforj.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtarltwmgg.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtcrtnzotx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtjqarxydm.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtzyecyzzp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtcclykpoe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtiwxzklwb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtpwsenqaw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgzffqqzj.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtzwgxpwtj.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gthscdvplx.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtjsailrqk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtmnbubtgz.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtqgkgfpnx.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtmwckoudb.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtmgicphrx.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtckryphed.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtaopvbjgy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gtqcfnuumi.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtxsuvvthd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtddymwjlt.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtfzpixwlh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtxbsjurrp.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtrjzzskjx.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtmlfmzrtf.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtleaadmax.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtlzpvobla.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtdxqwuwrv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtucmvitqp.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtdqlkebis.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtdfkuhvdb.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtlvgxttvm.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtsiovlwet.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gttkuogctq.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtrxpesyik.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtipvfqufy.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtcwjfnwpy.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtxqmeglgu.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtyqixvams.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gthhubxbit.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtixytstme.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtufvlismp.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtwiqypesi.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtazobcumf.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtetpteukh.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtjixlonhs.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtfjtlorjp.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtmmaqegkh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gtywxmnaqf.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtihvpzwoe.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gtmxjzdmxu.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gtufnzlplp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gthtttzgdj.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtutgtrxpi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtxjyelefv.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtfbswimud.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtairxtexh.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtfuiyptuy.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtvcgeymth.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtkrluyd.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtnxetqtjt.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtqjwnorwm.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtinmyriqj.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikybtvev.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gtbxfxkhyt.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtfhhniexu.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gttgousezd.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtldegfzcs.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtbegkgjey.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtzrlilksu.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gthzfjqrnl.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gtqypfrsso.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtdsegfrpq.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtkfktvzbh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gthstueluw.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtpejzfwex.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtkuhcpiay.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtdnrvanku.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtjvhtowdk.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtenzzfamm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtfutlosgl.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtpyhoqjnt.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtiznmmkju.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtufntartl.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gtoiaotatr.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtwiumpnjc.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtgbpiektd.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtxlrxbsee.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtxgbtqfmb.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtfazzvmgv.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtktzzpnxo.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtedgxuerr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtsrccdrro.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtpvzqscpx.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtxzczgxmm.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtblzpxpmd.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gtbbdgziwd.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtucepticu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gtfroqpbzd.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtsduhhfyx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtexamhqyo.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmrrpmvf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gtxvjuceqd.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtnvbbyjup.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtgyzunuui.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtftnucpwz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtnjadmkzn.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtcfrhtqpl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtgvujxwwj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtfnftacwz.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gttlwtltzt.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtrfilpucj.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtttvcpakr.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtmmjrecoe.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtgxwyaxvn.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcpkhuhq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtnrzdbkom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtjmqdpjxo.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtpfxabuwg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gtdrgsffrm.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtdqgslkgo.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtyetgytsh.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtwboqqifi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtrdhykqlc.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gtcljjddyb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtiycegosg.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtvrvgdbpd.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtvpjwixvk.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gthcnqztxz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gthdxbnpxg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaravskeu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtwguvjuxd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtimhkvbik.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtkabmnajy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtubfvvwel.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfginmblx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbuwpqce.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtrlqwykwn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtkziaqihm.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtegpexttt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtjxuhheuw.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtisaalmaq.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtrrbhoskq.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtwrohvrfn.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gthbbtgvxd.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtabtrifhg.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtrwnrfiif.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gtlttzgazj.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gthdouttck.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gttzktqxvm.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gtpmttbqnz.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtmbceuswx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gthhksvwgn.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtsmeyfyjv.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gtzcnvggun.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gtcdllgstr.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtxuxvwjzc.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjwzhqxj.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtpmhnsjlt.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtwqcghkhx.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gtskujleza.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtmcvoxnlu.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gtonwwnkgb.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gtygvyxyls.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoslsrqe.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtxfdxqbgg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtrpdmlapq.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gthezpdvkj.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtxoqeyevm.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtzgreyofd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtiiqgpyzm.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtsdoevnlp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gtyxirjlyi.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gtleifnbii.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqpzqdtj.html

[U22] Py：矩阵转置
来源：http://dali.haohaochexian.top/Article/details/gtdncpsgyj.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtuazmfpdu.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gtuztyycod.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtqksdktiy.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtzorotill.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtenvqcvzf.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gtqwkczfbe.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gttiyplzra.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gtxyrymles.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gtevxlgaqt.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtkakqrmfv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gteaqgqulb.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gtlcdjtdma.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gtuqcidjdz.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gtryffjknd.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gtdwgkmwjj.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gteagxgxpp.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gtfuvafnki.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gtgbsemxwz.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gtjmswtbrg.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gtbdbxjefq.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtzpsobttf.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtkehkjahr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sweek.top/Article/details/gtohbrgtyb.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtfjfqacrb.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gtsojkhsny.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtzucacbbf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtaswxjtkt.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gtxywxhftn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gtwbmozxme.html

[U37] Py：读写 Excel
来源：http://dali.jqgfzy.top/Article/details/gthmnbygiw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gtglbiprja.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gtwlcarvjk.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtehzdkkrj.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gtzsieczne.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtsbvfxiax.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gtxnrxcprz.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtgbobibak.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gtbxzngawo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtdkgxhhfk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cashguo.top/Article/details/gtzuunqsug.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gtkgjzjljy.html

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gtutkkpnjs.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtlraafyka.html

[U44] PHP：开启严格类型
来源：http://dali.xylfe.cn/Article/details/gthntjxfya.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gtjnxstbtr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtwmjsfllf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtrwrpwunt.html

[U46] PHP：可空类型
来源：http://dali.316326.xyz/Article/details/gtgyqcmeag.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gtwmiliawm.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gtzvhjimfq.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gtuczokcsn.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtwtmvoghb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aibaodan.cn/Article/details/gtcdrdgqld.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtlwcmdbkj.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtayvcdcop.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gtbauumlem.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttnfykpkv.html

[U51] PHP：数组解构
来源：http://dali.jiagoushi.top/Article/details/gtecfsrqmr.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gtrwxsdern.html

[U52] PHP：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gtaflofhiv.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gtpkavpbgj.html

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gtjjzccvbj.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gthebozmvv.html

[U54] PHP：空安全调用
来源：http://dali.hfpthk.cn/Article/details/gtoddpwqmq.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gtwgjrqhks.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtfybwdomq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xziqi.cn/Article/details/gtxmssmkif.html

[U56] PHP：命名参数
来源：http://dali.snrcjt.cn/Article/details/gtixfyjlyp.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtcjocusue.html

[U57] PHP：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtjmhivlfo.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtbdntczcn.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtycpbmrfo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtdjyhvqrp.html

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gtectplubm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtwrdwwwwk.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gteqsfygnn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtjwjhszzg.html

[U61] PHP：正则
来源：http://dali.feifeiyinyue.top/Article/details/gtqgyezonr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtrdaysyzr.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gttrjlgvxq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cheryme.top/Article/details/gtplojydar.html


<!-- 参考信息 -->