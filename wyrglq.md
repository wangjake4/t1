代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gt2ditfunio.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2uxabdqwp.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2esfmacoz.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2rmpkjofh.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gt2padlezar.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gt2avgceoxr.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2btazdlxc.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gt2ksnfbngq.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2keqmowrl.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmoyjhjt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2bitocbye.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2qrlptrwd.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2bnptarzg.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gt2evmupykx.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2xehoiksp.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2heowzimu.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gt2jxjvgqdb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gt2lwwmbrnd.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oludpydn.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2picztunl.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lttfzsym.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gt2kuiqomil.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gt2oezrxgns.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fvogmquq.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2czlcxaxb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2wguidjnf.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2znfrzjgj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2mlawvluh.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2yctnuioj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gt2leeovakw.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2yiavboqb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2iuuwlqzf.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gt2zhlxlmiv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gt2zwexlzon.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gt2wbgbepnj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gt2fkfksdpo.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2jevnpeyx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gt2xnsxentj.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gt2rcblttbi.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2pdbspfvv.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdjhdgfp.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2cbvxarga.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2tsiecnne.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryszgrev.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gt2heynrldr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2phwrlnoj.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gt2rfsfsacj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezcdvkdz.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gt2snpedkie.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2rndzvqfe.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2vfzcnooc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gt2ixqbhtje.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2qlscyyfk.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gt2dcgjvvhb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2mdbsjjzs.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gt2gcuzxuhm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufchjcot.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2brogyecg.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gt2otnqrfle.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2uxmstqzq.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2arduzfgm.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2birmuqqw.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2bhthzejl.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gt2qdlvbzql.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2tarxrhgl.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gt2ajbwgzqo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gt2wvpbqgeb.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2ajzhimgw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxkbiybe.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gt2rtbnlxeq.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2xatnodqd.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2hrwrisyv.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dizsasde.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gt2vlrnimgg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gt2wxclbuww.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gt2aemelmjq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2jdipmczj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wimncocn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2xiflpill.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2eylmkhdv.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzurtmuh.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2oimqfchj.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2ovqfeilp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2xrzyxaxi.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gt2ufzsbpog.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epparwpr.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekmkegcz.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2oluudcql.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgwmjmmh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gt2nqyhfgsw.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufeavdbu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2loshaigj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gt2ywjiwvkc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2bprtmirs.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gt2podhjcil.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gt2eftrvvhi.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gt2joedvvpf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2cpckwdjk.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2pflneyev.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqmmgve.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gt2lesxkuze.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2nrckwiys.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gt2gbqriiuo.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2iirezbcv.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2tsxugent.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2fmijyijv.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gt2jjfywyga.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwzgswsn.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gt2fqndobwj.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gt2qrcclkxo.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2flyndhpl.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2gaudbtgy.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2rseolnsv.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2smiadlex.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2qutpbvqn.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gt2lheajylz.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2dvotwzud.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gibjeldj.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gt2wvahqzev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2aqtxfjuu.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2bsezvdvg.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gt2kpobfsue.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gt2mwooafux.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gt2aavvlnai.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gt2kpefrjbb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgbrkeez.html

[T24] Swift：闭包
来源：http://dali.c1oappe.top/Article/details/gt2psrjgwdu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fptleqmh.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2jnwbcmnb.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2xgesfmlp.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gt2grsfiiaf.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gt2xpqygvhh.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gt2lqnfcivf.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gt2mncjyfeh.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2hmsreafv.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hisghamf.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nchkxljp.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2zddvhmcb.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewpcbotp.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrybbmwp.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2trrlczhv.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2cvdeyvwj.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2pdmyhbka.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gt2rjmgpcex.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gt2ajkbjpjd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gt2iehntvwm.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2bxnuayba.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2gwaofsfw.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2ywzafdnq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gt2hispjhuj.html

[T36] Lua：函数
来源：http://dali.fzhhl.top/Article/details/gt2zsjnmbji.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqlpgexx.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2egggqdkj.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gt2rladmrmt.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2xdtdompf.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtrwfkxy.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2yzulcnsk.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndixyxzm.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gt2eawnkhya.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gt2rubrhfpz.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2lholiuzi.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2gtmbbyog.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2nxlvezkt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2bcqosehw.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2bpiehztz.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gt2tiodnjcd.html

[T44] Perl：条件
来源：http://dali.zhengqikj.top/Article/details/gt2umaevqxb.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gt2uzsjdcuu.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gt2sciaalzp.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gt2ncedniih.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utigaypc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gt2sxayiawl.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gt2gmwylydy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2upbqtuqj.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gt2jdavbock.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gt2ossvahiw.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gt2ofprfhyz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2ijkhmdbi.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2wyxygjii.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gt2jrcfwzmk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gt2xcjmepgl.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2ivnduejv.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2vtipmcra.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2qqvyzsdw.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gt2ydjrvyca.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2uobcakeo.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2hipofvjo.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2hpuveqzm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2iksfklwq.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2znipurno.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gt2mljibtfq.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gt2hbjtlynz.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2teawyjew.html

[T57] Scala：模式匹配
来源：http://dali.tanke756.top/Article/details/gt2tizpfvdo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gt2pdsojzyl.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gt2qwlruhue.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtufcfiw.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2opiianjw.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2xjlyxmaz.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmiexkqz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yosozomt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xisadzhk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2czkakyws.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tzlexmql.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2nfelnpzq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gt2rqwdiiuf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2lihdkybh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gt2dtiibqfr.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzlvgjvy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxzixvxi.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gt2qllxwkpr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmgxtfc.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvoqhmsh.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2oruhncxd.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gt2lrjygnfu.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gt2okvonatb.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gt2rwpcuwwb.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttakjzls.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gt2smukgqbk.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gt2inoiiyuo.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gt2gjbgpcpk.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gt2omgcsenj.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gt2okbxgpxg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gt2amawfzvr.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2cgzlvgle.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gt2alhpasds.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gt2isqdcupo.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2alfhkkql.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gt2pxbjpbpe.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gt2jzceqour.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gt2oivaofid.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gt2gfrnzixh.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gt2haexsfho.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gt2hlarszrj.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gt2fzobvgvs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crjpgvus.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeqpumys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksniirox.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gt2kaohipfr.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhfhkfaq.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gt2fqzxgnhg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gt2ldvzraan.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gt2mnhahdod.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gt2moqmevwc.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klwpztff.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gt2cjicnfpk.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gt2gzyclksy.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gt2vgbmwwgn.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gt2dcdhtmbp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gt2sgadxtwv.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gt2wbexmxdh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2osdogjaj.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gt2xtxogqyb.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xriiprlm.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gt2noxsiypu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gt2tfhjdqhv.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gt2raecvbsr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgufenzy.top/Article/details/gt2aukejpyv.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gt2kevjrgud.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gt2qkpflrci.html

[U29] Py：属性校验
来源：http://dali.zycfv.cn/Article/details/gt2pczliyjh.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gt2yvizykva.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2avcprfxv.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gt2rltporot.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gt2tngqbrvz.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqlrllmw.html

[U32] Py：代码格式化
来源：http://dali.tian-w.cn/Article/details/gt2wrzsujqq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvhcjng.html

[U33] Py：打包发布
来源：http://dali.gogol.net.cn/Article/details/gt2elcigvas.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2dckfycte.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gt2leeualdu.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2wpdqszec.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gt2sfdeuctd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asdeirkx.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2tvqgczkj.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fijanbva.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gt2khlnjhtl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gt2upsjfvec.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbdkelil.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gt2xyktasng.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2porbpnpe.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gt2dkbrulul.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gt2knilvret.html

print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2bihkklqe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovskxbds.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gt2erprloew.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gt2xajhjfrl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxinkj.top/Article/details/gt2igyongln.html

[U43] PHP：声明命名空间
来源：http://dali.sweek.top/Article/details/gt2fbrxnkfr.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2qeejwjxy.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gt2kljcvktp.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gt2pzhlmaoc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gt2mjcutfnj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2tiigjtqz.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2bhbmfbxy.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gt2lfoivgcx.html

[U47] PHP：联合类型
来源：http://dali.xuanzx.com/Article/details/gt2toavakds.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gt2uhzalyki.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gt2aolkzbzg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nrdqemns.html


<!-- 参考信息 -->