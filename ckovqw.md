代发 wailian999

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2ieldvbdf.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejotypxb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2dmwimepe.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2chtfhile.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2rfwdcnwr.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gt2rrcfekxp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvzrlozs.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2wkncdtkv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gt2fbbfwoxy.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gt2yjbiceen.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gt2onsbqiie.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2rrmeeavk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gt2arfffnpm.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2quytcsot.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gt2zrfgdrnd.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gt2thuvxyip.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2ltoylowj.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gt2kbyecrvx.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2lullmmyf.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2cvqocnrc.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gt2nbcgichy.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2knxxtrgc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gt2zatpkhhk.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gt2rqujkptw.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gt2bfjnoome.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gt2oqxvelcz.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2jyrjpcne.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2cwublvww.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gt2xikspurx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gt2frcxgvve.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihkwzvga.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gt2ctwiinlc.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gt2exgyonjt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gt2apnfvwty.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gt2mbbzliew.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2cgdjusje.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gt2hpkvzsms.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2pdzyzurg.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gt2mwjtfvph.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2nyxzjdhc.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2oywotqnh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gt2eeapzynh.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clnbbinl.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkpcgmde.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gt2vdjpjdng.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gt2bteeexbx.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gt2femvfhqw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gt2fayghymm.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2dldkegmw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2koxfjxqn.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gt2mdgjaiom.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gt2lnfnzyzi.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gt2cqtxijyo.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulbrqqnl.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gt2lxvrrtmh.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2esqzznfj.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gt2plqkvscj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2aptcdhfs.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2lacpahxv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2uqqxehhd.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkymxbcx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gt2wcexoiem.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2rqnfedfn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydgxgyjj.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2fterkyum.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2bfswhxyp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2tucjnsow.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxcohhqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2iueyuvfs.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2eycwxwea.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2kozfsotp.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gt2cqowvkxm.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gt2zeuchbxy.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2xiybrjsn.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gt2wnicrztn.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gt2yfhzlkgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gt2oxegypdl.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2zzenlmiy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2oehjrtfq.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2twhkavnj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2mtikajbd.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2evflgzoa.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulcwmahy.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2vmkftkqi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2ynxdrzkk.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmskufka.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqikvkwr.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2shgyizgg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsnqeszk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2lhzrutld.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gt2jqqvymld.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wphpeear.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2qidyrcsl.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2zumjnbrt.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gt2cxhbqndo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gt2ebrurodd.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2uvubzaec.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2elethuty.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gt2dzdvxtmf.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2mghgzzim.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2ofsjxnve.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2mbslaluc.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2xiipduhe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gt2jmcrgbnl.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2fxsqdpdh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2oqdcacts.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gt2dxdwntni.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdueefoh.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gt2omyibtmt.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gt2xqotrefe.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gt2ufizvlcr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2bgficrdq.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gt2njfrofwi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gt2spehndrd.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gt2gmfwqtiz.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivpotgkn.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2bdesflbm.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wojbthfz.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2azvxefup.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2ncvzqgit.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gt2snirmsaq.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gt2gamyqsji.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkbxijzg.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2rdcnmagj.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2cumtcgwu.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2gqachtes.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2osslpuhm.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gt2booumfhc.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2ktpnfpzi.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gt2xgqgtwul.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2gfzulocu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gt2hefpglgv.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2rwsaoknm.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2eavyxpma.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gt2xagzwjif.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gt2bahijorc.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2wxurpffb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2tngawlog.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gt2clozmwin.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ddcewppw.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gt2qepwsshy.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuemylaq.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzkbmoim.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gt2gfnxteyj.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2fsihmove.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2zbmmgizl.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gt2qmfmaapg.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gt2vaytegvk.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gt2qywiiomi.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzllaquo.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gt2niaiyzvu.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gt2aqhihlcz.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2peziwteh.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2unkyyqnh.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gt2rkgkotrh.html

local a = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgboqkfl.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixzrpzfq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2tgyljgiz.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gt2peobfdnk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gt2oweyqojx.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gt2rsjgafre.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gt2vxpvouer.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gt2egpkvpmd.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gt2wnlhkcgr.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfsrnrrr.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gt2dagxpxuq.html

[T38] Lua：条件
来源：http://dali.nanxinkj.top/Article/details/gt2ryhhglct.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2ybtzlhnd.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2drshmnjn.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gt2aoutqjbv.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2atggivqt.html

setmetatable({}, { __index = base })
来源：http://dali.quarkkingdee.top/Article/details/gt2dbsygvhi.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2jkbmipsu.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gt2eogrqctv.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gt2yxwqhhdb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gt2qemtcsst.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2wztbcbgy.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrlvkblv.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gt2joxlzgoz.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2dpqglaqm.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gt2nmvmhdat.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2cabtmiqi.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gt2zaitorid.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qywelbrp.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gt2rynbyrnt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gt2vekouiye.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2ukgnrekg.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gt2lcvnvmwv.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2ldkxxqgu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2aufddykg.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2yhqxxbus.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gt2okhlglyl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gt2hsdoppyl.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2lxbsttys.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2hpgckhyd.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gt2mpeckbak.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2ziozdrqz.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2uizcaruj.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2ygjujave.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2fyndtwlb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gt2zrvmrdya.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gt2fowhntdv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gt2jikqgfxo.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gt2fpqrasqd.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2slrjmzgq.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2dcvvoacy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gt2wckvrema.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gt2ndlrkmab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gt2gxuixbmy.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gt2wqjccjdd.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2kosqssou.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2oozfdixf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gt2whffvevp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kxljgwfp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2fnkqguab.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qcneludd.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gt2grxqvhxo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gt2odvjiwib.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gt2huvnyfqm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gt2pfvcpzdn.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gt2jfeaymya.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gt2wbalksqt.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnsbstmo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gt2xjqffsfd.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gt2vpgabdqq.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gt2byeujtds.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gt2jxdpthih.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gt2gvlopssf.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gt2jkosysxl.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gt2xpbtoxkx.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gt2whuhtrbo.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gt2ejuyxbve.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gt2mcuzspsp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdnnlqy.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gt2uigpaoah.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2pfskaxcj.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gt2fjwqyjoz.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gt2jdjelpuc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gt2ojyeskda.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gt2ooblhuty.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gt2ezrrhmou.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gt2szyynsaa.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2epoaicok.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2exvpxjis.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gt2yiubcaim.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyrnqbhh.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gt2huilanoe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gt2gwirnqab.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gt2psquqxcd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gt2btsdybro.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gt2whhogaqg.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxmssbtn.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2moguldvh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gt2slojmrmc.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gt2gwbqacdd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gt2vwrcqbch.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gt2lorsubum.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gt2jvoumlty.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gt2cnlhodzo.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2jrouhtne.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gt2hwjwdoxn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gt2otpcfunm.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gt2vmlhmytb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2boqlrrou.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gt2epaiusyx.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gt2npmkkwim.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gt2gctjtfgp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gt2tcgmzcom.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwmtlclk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmunxrbb.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gt2dxqwnkfb.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gt2bchlncgu.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gt2rmmfugdj.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gt2uarpotfo.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2haxggqfs.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gt2vsuyxoor.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gt2dygyoqop.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gt2msopyste.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gt2vgkqjrvt.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gt2csjxbwoo.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gt2isabnidg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gt2oglksbyz.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gt2vtmhymrb.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gt2hbzorzvn.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gt2afbfqxvh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gt2fkxuotyu.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2jhwqrjgx.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2accndvya.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gt2nupadgus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfrkfgcp.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gt2ptbhurtw.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gt2hscgkues.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svwxoqfd.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gt2tdhanemy.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gt2ghwcmfto.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2rvewhkwb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gt2qyhujqpk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gt2qydockhe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gt2yoxgwpoq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gt2uykgoxtw.html


<!-- 参考信息 -->