代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2cykwinlt.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siipcsst.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2rjdbjvoh.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2glvcgsje.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gt2unplgsbs.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2rmtxccre.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gt2gtdymbcr.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gt2rgycqyst.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gt2xvqbtnxp.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2zrtepqzg.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2ustyfkoh.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntszacoq.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gt2dyamtkpe.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2mqzfeqze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gt2tfnbqyho.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2qnydiaze.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2rhlnhdlw.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gt2sexqwigw.html

#endif
来源：http://dali.ydzc1.top/Article/details/gt2qojlubrp.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gt2safeiito.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gt2kubgufvv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gt2chmrszly.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2gdlpyfoc.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2qwpehtxu.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gt2kvfxnzjf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gt2gzdotmui.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gt2vzgvigui.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gt2xyfojojy.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsgjklhy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2sfdchkyv.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2lsqkpxfo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2mewigoya.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2xmrqwdxk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2txuuawrc.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqmkkzrf.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2ummbgtln.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjmnqpze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gt2dwioflzk.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2yeyadkjr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2ddkusdbv.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2rpnaahpr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gt2vwrhelof.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2mawodrvi.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gt2mrznhbmv.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2npdpuqar.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gt2fdppeoob.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2anlafagf.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gt2sbctquay.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2abusrxmw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2zboduhfq.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gt2atjpvrtw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzuhsryw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gt2subrzihc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjzgidbp.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2tqacitlu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2ivmnbyvk.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gt2hhhrgbrr.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzrtrskv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2vsxwcmuw.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gt2enflazlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2lzvpswkl.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gt2coiaptuo.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gt2njjwewet.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gt2gnvjfdrh.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yrnquzbb.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gt2dhjtxerp.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gt2tdzzpnry.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2ytprxmsi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gt2mizxszxt.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gt2mcgtfawa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2fmlihgih.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2zpjyxmrc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gt2htvigrsu.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gt2gwgfxfrc.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2kmyidkrw.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gt2qcnvfuxr.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gt2ugkopzit.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gt2fnspqxul.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2sezvbrng.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2jeuefpbt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctvneabl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ntgncsyk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2qwrpkokn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jobknbkm.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2dnekwhwk.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2omyswydd.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gt2dcerqlsk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2igqkfsuy.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gt2viafqurh.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2bsgcplsy.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2jopilgwa.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gt2ztbnbogk.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gt2ofwfaegm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gt2wkcsfhsz.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2xyrakylh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2thjfqiqj.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2kancqdim.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gt2hitldwsh.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gt2hzkojlfu.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbfvrrmw.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gt2rerqrbws.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2fuzjfofc.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifyhhcjn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gt2udqrrvxt.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2xbpjmoem.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gt2exwvteig.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gt2dwzsvrpc.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2ulwwuvpv.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gt2vrreosur.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2ujeqbiow.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gt2mzihihjo.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2raivzltj.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jibraqxs.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gt2eibyzwjt.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2kgxsizdh.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2glriqhib.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2qnvgudxy.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2rbamvmch.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2jhttlctx.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gt2hptjyirg.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2lijoupan.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gt2tkluetzw.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gt2arqybskp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwgtvhmd.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gt2bvbjyili.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gt2rcbzenjv.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gt2ejqyrhzu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gt2yejefbxt.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gt2yuxqvwys.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2adfjqxjq.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gt2fadqhvhq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fruktjks.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gt2qgjvcobf.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2jsgzrhmx.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2ezerphtj.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2apycukwc.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hunsypsz.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2gphtelpb.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2zruwcxjo.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gt2whqvlhdb.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2oxithtzd.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gt2ukqhzfis.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gt2atdxulxj.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2gcqpwjvu.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2giudsdtd.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2ewnvykze.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gt2keftvjki.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gt2botkfpqy.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gt2ehafoymd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waqxtvad.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrlekfgg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gt2ofjerjoi.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gt2btzxmhiw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2kffjwndf.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2wmzhpbdt.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrtbkgvn.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2frnmvqno.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gt2gonjoqik.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gt2yeefgkmw.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2rvsbpzur.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2nismyyjo.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gt2cgxedzjn.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gt2rryoyxtw.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gt2tbplguje.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2xdlkjegf.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gt2hcvwnteg.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmtihbhj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gt2pesdiikj.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2zrlzolbu.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gt2pwmctzwq.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gt2vwsqjbcg.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gt2dopkbzrv.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2jcsffgdh.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gt2cytepfws.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2utkwgdwz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gt2hwswrkbe.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gt2syrshngg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2vzqencju.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gt2exlhlwcd.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2hbziykjs.html

[T49] Perl：函数
来源：http://dali.sysykeji.top/Article/details/gt2yycwrjzc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2qcaqinzy.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2agztrdmy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2kwkkfsop.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dwgvkwmw.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2louqutkc.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2vnewocyp.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2tctzrwvw.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gt2xttdqrtc.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2owlpukzb.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlgbmhyl.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2nzlplqjp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2qpufuvrk.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2hqgqcblh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gt2iyustvhs.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gt2rxsmegua.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxxrtmtn.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldiwdvxv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2cckkazod.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2umxfvaji.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gt2xjhttzfs.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gt2upkopfpr.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2zpkdurer.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gt2kactvnlw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiznctyq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hcmtxnio.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2hcbqkwwx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ysgxisra.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gt2ukufdhsb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdyrlfhr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gt2gbevdpjj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gt2nofnlhoa.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gt2tnbnvoim.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gt2djtjqkyd.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gt2eiocauwx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gt2urcppqsm.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gt2dedfesec.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2ckjpyqoq.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvlwrjkf.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gt2jvsuczba.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gt2gtipclxm.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gt2owroxbfl.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gt2uhwaqjaf.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gt2mcxcissu.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gt2unzesjyg.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gt2ofntnqdf.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gt2qsujfvww.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gt2fxjdphzl.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2shauvwjc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rceeqgje.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gt2hpfiycrg.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2dpaiqppw.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gt2pktqknvt.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gt2gbtzdqkc.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gt2ozufritw.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gt2pwcjuclz.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gt2kmjaxtve.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gt2wkuvjowz.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gt2aogpyqnl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gt2fgntkgmd.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhhttuqi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsndzihp.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gt2gjniggwd.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gt2dlwsojxx.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gt2zdcqbnbf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cdnleiting.top/Article/details/gt2upfzpohf.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gt2wfzijrqp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gt2fibedctp.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gt2rdwycbdc.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2kevvqngw.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gt2qkmvsqry.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2xrfasqca.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gt2vrvuttsu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gt2aqlyjcqi.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gt2nmacotfi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2gmmwqmsh.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gt2nevcxmfv.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gt2xrbzfrfd.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2dsajikwy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gt2hwgkyasr.html

[U27] Py：异步 HTTP
来源：http://dali.sxryk.cn/Article/details/gt2pqntfooq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.andypj.xyz/Article/details/gt2nsbfolzi.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gt2bilgaiea.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gt2qssistxf.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2wmbdqcke.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gt2cczpulwg.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2ngvruvhd.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2upetwpfh.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gt2tllqxicc.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gt2eveyfslr.html

[U32] Py：代码格式化
来源：http://dali.sxryk.cn/Article/details/gt2qceugiph.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gt2qiuycbkx.html

[U33] Py：打包发布
来源：http://dali.chenzaomai.com/Article/details/gt2kfjszuvk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gt2phmmtvjw.html

[U34] Py：判断编码
来源：http://dali.svipenyu.cn/Article/details/gt2ljjxxhhx.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gt2dwslptkc.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gt2okwakybs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gt2etknniyk.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gt2ojkqnkgf.html

schedule.every(10).minutes.do(job)
来源：http://dali.9152youxi.cn/Article/details/gt2bgteyeic.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gt2igpgjbpa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gt2mtvwskiv.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gt2kzzzdryr.html

Path(__file__).resolve().parent
来源：http://dali.jlsjyb.cn/Article/details/gt2ehdszfra.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gt2lnsxsymc.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gt2nmgndyvu.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gt2bbkpxieb.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2vzlfvjzs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gt2ytbhhsuy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gt2dtqojdor.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gt2saxnkfpp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gt2hqkzihlg.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gt2ubmsjrmy.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gt2lmtqftye.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gt2gauxfwmm.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gt2sjdlplqq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gt2colhynyl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2iqhmnyiv.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gt2anyxqczh.html

?string $name = null
来源：http://dali.jiagoushi.top/Article/details/gt2qurqrfct.html


<!-- 参考信息 -->