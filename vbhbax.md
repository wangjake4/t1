代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2hasixxap.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gt2ooptqtjl.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gt2vawdekms.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2ijflxngo.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2oslvmhil.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2ndczqwez.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2uokfyesr.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2surbchbm.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gt2qmzymbjk.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2luvijuag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gt2vperqgwo.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gt2tkodgqdb.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2cwjdetze.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2zantqmzr.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gt2tncnlyes.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2epqshosl.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2jfkizqza.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gt2srsltkrq.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gt2auxiemux.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gt2ooxtyajz.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gt2jhxoahqp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gt2xfuilhng.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gt2dolacmpk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2xqnjjhxv.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2xzopalgf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjrlyaam.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2omvthwnt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2xzpejtal.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gt2lchuubxp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gt2ubpvrbyv.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gt2snslmukc.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2ayndlbhp.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2udnorznp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gt2lnrwesjg.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2gwsroaqg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwegsyms.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gt2vwkghmjm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gt2mflmclyf.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gt2tqijqavh.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gt2wktemgmf.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gt2jubndhvf.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nydbvngb.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gt2jztehhur.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2bthlxpbk.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gt2rugiwyoq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2wuddgkbh.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2vdmypqcl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gt2bbsgdtnt.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2bnpgtkqn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2ctsiarjq.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2wwmirjaz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gt2ngpqegpb.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2gclvrooc.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gt2bwgxkrdv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2pzlkmcmh.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gt2ooquesqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxbdpdug.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2ovxevkpv.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gt2bzjffssf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhdmrndd.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2godgdfqp.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lalsahrc.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2nexlfkcm.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2wqubgigt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2hxpkmkhn.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gt2zmzyeqfl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gt2cxjfvcwr.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2wbdjbnye.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gt2yjzvxcvq.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2oispplft.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2isqgkutp.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gt2lzlvdiua.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2hujjajki.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2odhlnepw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2sbgpqhpy.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2hrnkrqid.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gt2epgvzkea.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ejsmbqev.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2imbwrdxc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2amutijzh.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2lfpxmnjj.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2pkkvogxj.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2xzzfusku.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2rrhxaelz.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2vewocbhb.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2kfcsornn.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnhgkhgp.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gt2fhrtuwsv.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2cqifxenb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2ufnwiqpb.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gt2awaqmqki.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gt2onbozzzq.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2nwzmmhqh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gt2kdffpdrj.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2uicnjhzf.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2wiocdcni.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnzoitvn.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gt2xpvozsmi.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gt2sktaioei.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gt2rppzisfx.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2nqhxmrma.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdarpgmo.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gt2fheoxeyu.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2betacyid.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gt2bpoyrqpc.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2xmhvodoc.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2raxzxclq.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2vaxetlqq.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2nnblcust.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2wmisicbj.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwhcpqkn.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2mqdcwtov.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gt2gcypibxd.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2sipvplvj.html

[T18] Swift：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2jfshubqw.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gt2pluwuofo.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkhbaiuu.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gt2jmfdzlpq.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2atolxsdp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gt2wpvxetdl.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsuacgto.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2wgwrznya.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gt2fjquelcy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2nyrwqmpx.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gt2fhxriiqs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoesjxnw.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2akbvfdri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2febgpzcl.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gt2bickjugx.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2sprxzdlw.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gt2hmbqsfhn.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2dxmnhnrx.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2rsedvtqt.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gt2snfpgymk.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2mzpatipq.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gt2jqydxbvy.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luawspei.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gt2uafzrhbl.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gt2sfddrmqg.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gt2blkfukmw.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptrmzprk.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2qatwtezp.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umjswlmt.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2qvzyiqyg.html

[T33] Lua：表（数组）
来源：http://dali.dianchejie.cn/Article/details/gt2zwlgaiah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2ywpwdbos.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gt2baxjvkpj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gt2nzukijam.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gt2vqanjpza.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gt2aqyczgby.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gt2phfihmby.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gt2fxaluola.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2nmovvjyn.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2nibcvdzx.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gt2kadvloiw.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdmyfyuz.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvzrnvvz.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gt2dveaehwu.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqjcyqac.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gt2sohbgzol.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2mjnqbcna.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2danwswwz.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gt2ykedmhxl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2emapbmop.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2kekoyjhj.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gt2uroukmxg.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntqdybbu.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gt2zhugscco.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2tjgmxwnc.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gt2hdnjcnbg.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gt2wgqnqguz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2uunmdxhb.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2ybqtyply.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkvxqct.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2rtrziupp.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gt2isfiplpz.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gt2kauyizcu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2hsctpwra.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2lzezmujh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgyqhozp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gt2qtbcxotm.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2cqfjmgyt.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asetfxrh.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gt2roluvaqz.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gt2huizjord.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2ahviksif.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2kcdltfpf.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2vdocoqsi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2sysrnzdu.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2emzcfuaa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2firxnztl.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gt2fokyiaoc.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2bfdmpqta.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2butkmkay.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2kcnzsnol.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcncpqwg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gt2yrwzpcoc.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gt2dptifwev.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeyfnnvb.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gt2cgvgivno.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gt2tgpvxsef.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2amyhawyf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gt2fbcvhewu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipzfqwzh.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gt2mjoxqifi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gt2yhgergvk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gt2qpxjhqet.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gt2yavctcbo.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gt2ortgrskk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2dthxibib.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gt2wsuksrzk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2mxkdknql.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxscxwpb.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2tvbsixjg.html

[U06] Py：合并两个字典
来源：http://dali.yueranfly.top/Article/details/gt2fdlioxdm.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gt2kjgghgki.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gt2dikrbioo.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gt2jjhuwtyk.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gt2sqgchzrr.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gt2suafzarg.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gt2zvlfijmw.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gt2ejgyjhwc.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gt2fadwpyqp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gt2samvkxzn.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2temhwkxa.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gt2ocjpjvor.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gt2zbkbbbrp.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gt2magnyxjs.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gt2brgcgjfy.html

deque(maxlen=10)
来源：http://dali.sweek.top/Article/details/gt2sejdcqux.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2vxbiozpz.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gt2urgmgket.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gt2thhprqvi.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gt2vwwkbgqk.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzuxpjjg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gt2wclhpgsr.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gt2eiledard.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gt2uqfzubnc.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gt2jvhevbak.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2mmbpekqx.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gt2khlypgmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xajbajix.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2mkuriutr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gt2dbfvyuvq.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gt2ymbbkeja.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2vonbgtte.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2jweaorku.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2cnlzkfns.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdvdysba.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2xslrpqyd.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gt2yggmqyix.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2lwudenry.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gt2zhbuouup.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gt2hquooewm.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gt2bywaobcz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gt2kwwlwsif.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gt2yehygscg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnxiangtu.top/Article/details/gt2kpytmqvs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyicpsk.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gt2azelwndj.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gt2inbxgmal.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhsgjlas.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gt2olfoukgi.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gt2tpzelehw.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gt2wshuzhgf.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gt2rkeyijyc.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2dvmmwvkf.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gt2eyjimlzn.html

[U33] Py：打包发布
来源：http://dali.haohaochexian.top/Article/details/gt2chxurrve.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gt2otkrmnrw.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gt2petwjdag.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gt2afnoevtq.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gt2ljcmgufi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tanke756.top/Article/details/gt2uspuemds.html

[U36] Py：定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2rsbyzqzf.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gt2jwjxdxzy.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2kauuynqv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gt2rvxpdnqy.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxnntgip.html

Path(__file__).resolve().parent
来源：http://dali.cqqwz.cn/Article/details/gt2hazdjtjf.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gt2bfvkkiar.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gt2pcottvie.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gt2rfbpbgaf.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2wtiwsfqi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gt2agxsyrje.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gt2autyyije.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gt2ncniuenm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gt2oznyvwig.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gt2snzuclci.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gt2jqxmtvuo.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gt2vjvlfdxy.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gt2abxsvznx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tanke756.top/Article/details/gt2ehcyaeke.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2mjesolwy.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gt2cgnhqahd.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gt2iupditpj.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ricoyopl.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gt2gnbqbwnj.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gt2rwjfptzo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gt2jeriaxhq.html


<!-- 参考信息 -->