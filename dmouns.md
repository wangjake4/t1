代发 wailian999

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtpijajfdq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtqssovhlw.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gthouhusbs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtlunsvrsh.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtfnxazggx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtczfqveso.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtkyzoyzxl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtruhtazti.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtmhzjthkq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtndtciydt.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtyrlawdhb.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtlmomcpiz.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gtryvrekkf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtfhrhibjx.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtzdkaruiw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtrdodjzky.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtnyskxbfk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtftdlsgwy.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtsqubmjgs.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtkvwkzxxe.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtyhylrico.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gthtedqnko.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtwjbksizm.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtxkuiotwz.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtkcusdhmj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtefaenech.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtxrgpacpx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtvfvnwwwv.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtlgwmdqix.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtucyftvwl.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtamtlibjs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtoidltcno.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtecavcgub.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtaylfvoun.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtozlkclmy.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gthbteorol.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtzspzfdzg.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtkzdrnjwq.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtosixexcj.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtseuoxidv.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gttcrlnfhv.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtbsnhpeyx.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtdpyiiped.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtyyvcjrzh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtexydihcj.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqkexdxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtbcvefakj.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gturoxzibw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtemeczgdo.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtkiwwvvmf.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtodgtezci.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtzobnaklp.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtcbxozndq.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtkypwaqve.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtdxcinkgo.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtgktxpvee.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtydlbufze.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtoyfqnfqk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtqdsabmym.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtobqrmujs.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtkiafqwwi.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtpnocakck.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtkxkvxqbr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcotsvfl.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gtehfjkjpb.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtbhzhjnif.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtoxczlpyh.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtxibynsjg.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtetqtojqe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtipmpzakw.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtejmvgkka.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gttrdqvzgi.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtgmpqjlhm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtmovysykv.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtcrmfprkf.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtemamqxbj.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtmmvlptqq.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gthkvdvelu.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtvwzjhbpg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gtoeecxpzm.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtabwhhysc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtjpjvcpxj.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtbczmddve.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtlbujrdom.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtgjzlvlkw.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtuwkyybgv.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtgdeuipbw.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gtokhlsuee.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtnwjokqyk.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtikbrhnfc.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtzxjtrujo.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtdlnaefdc.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtvworniov.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtontybdga.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtohkdyqty.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtlzaunmrd.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtyhibujky.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtwedmyint.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtsacqitsz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtzywvbitn.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtjdabkfws.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtnsxblnos.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtlqxbmrmz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gtfkdpljxd.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtspxbpsho.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtvrylbqsf.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtjwpoiaue.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtloropykg.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtkqhwukdl.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtetzeqtgj.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtzmbfzksh.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixnlhcix.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtkdpertll.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gttvdrvdcm.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtpaejprqk.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtqojysgfm.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtejqjskpf.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gtthptwxhv.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtocgceciz.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfjdgwxr.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtkoerkjoc.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtwzppbqpa.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtdjkoxndi.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtqsxuvoyg.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtxekjlifq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gttxdggclz.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gtbuqmnjfb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtfuckmupy.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtjpjxhzwh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtairznolk.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gttnladqfs.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtnmidkhjn.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtmvyxmosl.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtdpixwlta.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtcnzgpfrv.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtcadssljh.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gteszhfnfx.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtdayfkdek.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gtztialthh.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtjxeensgl.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtoztjagsj.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gtqtduqsrx.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtfkzofmsv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtsxpuehmh.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvwcscmv.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtengvxlis.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtkllvdlim.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtrqmqvcqp.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtleiuevmt.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtvwnsbmof.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gtmwanwbjr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtyvisdxah.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtibyxvekj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkukghkqp.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtuzijnpbg.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtakaufxwd.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtaefjepaw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtwkixnvhj.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtmotayrgh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gtroxtprmb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtgnrgpxxs.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtfgjfujhg.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhqavojf.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtgobxlgex.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtrlhwajni.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtzlxvgjci.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtfwryaxjs.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gthpiojqxn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gtahtrhmce.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtfdaciiuz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtkmikebpv.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gtijxioppp.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gttbzxibln.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtumezakob.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtazaekkfa.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtbivgsrhp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtjgfrmgbx.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapgzluhq.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtprjhemrg.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gttdvrsmpb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtvnzlpxbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtczllkpfe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtufsaokfg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgpermvow.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtdnbughpc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtosxdxolk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtvnpnvjnc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtwnlqzzdh.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtnlyfouwm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtipkductd.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gtmhtxuqon.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtdmtkpnvr.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkutwhyzs.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtxaudmsbx.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtysxmhqsk.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtwhyqsnls.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gtkrhjcadb.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkzuzjlp.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtalhvqrsd.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtiupyqlii.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtpnimrtsx.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gthctmgqcy.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtpilrbnjh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gtippkiwze.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtqapiiyea.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwadmlqxy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gtxmhptjmj.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gthjjbtkwa.html

[U13] Py：固定长度队列
来源：http://dali.aibaodan.cn/Article/details/gtjeppienw.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gtptibvmib.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gtaidxsbrx.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtsdfcfwsh.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtljduhbtz.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gtwevlolaq.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtopfrtiqx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gtxtyljwrb.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gtprgslelr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtrsweplox.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtnvxduxyk.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gtahkgtpht.html

[U19] Py：正则替换带回调
来源：http://dali.fengsongda.top/Article/details/gtzmmmqeaz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjjqgpqv.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtnkaicnes.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtuaantzra.html

[U21] Py：自定义上下文管理器
来源：http://dali.xylfe.cn/Article/details/gtypjnrguq.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtaqkojibk.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gtdwzefiwg.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtldvfxwkr.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtxqoxxbja.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gtfyfglpin.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gtpzctayvb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtqodotjiv.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gtezxbkzpk.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gthzngiujk.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtbxcphhig.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gtqkpjvasy.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gtstbcjpuz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdflqlqb.html

[U28] Py：类型别名
来源：http://dali.hammf.cn/Article/details/gtrdqxpgsb.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtdugqmjme.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gthqmrxnsd.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtxlzxorev.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gtwsetyouz.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gttmnjsqya.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gtlnistrnb.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gtmmuuphwb.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gtqfdsopva.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gtxjttsokp.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gttwxzkbxq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gtuqwzgyur.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtudcsvhdy.html

chardet.detect(raw)
来源：http://dali.yj20258888.top/Article/details/gttjiskvdx.html

[U35] Py：发送邮件
来源：http://dali.ivvv.top/Article/details/gtjmyrjdbu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gtbygmgdtr.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtiawtcpjb.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthusczpew.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtwafyenfq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtpyfphxkn.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gtzdizdpsk.html

Path(__file__).resolve().parent
来源：http://dali.cashguo.top/Article/details/gtsystmyby.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gtzatjbwor.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucdwdlow.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gtcodbkrzo.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtnwvhtgpg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gtxcvdgivh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtoozdhhkh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gtwpbxldul.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.0kj1m.cn/Article/details/gtzupotfrx.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gtxtqrekff.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gthcclktui.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gtsxqceryy.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtlaiwzmec.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtyxqesemh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymqbauta.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gtexrifjsq.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gttvpppbhx.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gtiyboxqbb.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gtpwgqldqj.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gtakmtwctj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkqhqedvw.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gtunbyemav.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtmfyszvio.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gtjfmjmufc.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtntdjfdjz.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtueeboiyr.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gtqfnyppoa.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvduaromv.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gthoekectw.html

[U53] PHP：空合并运算符
来源：http://dali.zhengqikj.top/Article/details/gtwgvvdnfx.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gtovcstwre.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtkupxkywm.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtnoaoxhib.html

[U55] PHP：match 表达式
来源：http://dali.hysaishi.cn/Article/details/gtwfltfnbk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtxffmxyvo.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtrkehwycz.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtwfzxrcta.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtgayuqbux.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gtitqnneig.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gtdosuzomc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtoyrvjioj.html


<!-- 参考信息 -->