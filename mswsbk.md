代发 wailian999

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtjfwshinh.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtvfrnuofl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtispxnpsy.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtdaqgeylo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtijuaxvpd.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtvkywpyqv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtlvdkeofj.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtwjwgqszp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gteadgryvn.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtrlzdjnpw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtktmakdhw.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtirxvlpnu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtlkwtiwhl.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtbwgveuqa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtwyatvrnh.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtrlwacrlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gtxhtakzfn.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtuudhhzzd.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtidkaxoky.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtvhdhcrey.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtybedgxey.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gthnpuxsql.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkmgjfcc.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtfzzihzew.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtjipbtvab.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtzwscdzkh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtoomiyhwh.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohfrvdup.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtrolmdcex.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtfpmkiafk.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gtbmkhrqcg.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtcjnqgwia.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtybkpzfdb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtwxfsgkla.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsnajcrue.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gttjhjjgse.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtwswrfjqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtjejkpcro.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtywbvbocy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtenuuqrem.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gthatiupxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtvyrdeldq.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gteswffmdb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtisaqoysb.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtkdmtrtbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtqhrpkoqa.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtbcdwtwxy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtwenhdqad.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtuaroqtao.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtxyntftbh.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtzycxpqsf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtuhhmsbex.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtwkcqvsjm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtwzhawqvw.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gttvfkahry.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gturnyrqbq.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtmpiyfgim.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtvzjsltkh.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gttyonngbz.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtydujereb.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfqkjubx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtagrpozca.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtexyuudqv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gthtnfzgtc.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtmsuunzfj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtafrnnrsy.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtnkykhlav.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtpkyuuebu.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtmsflvvtv.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtzriztalg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtwbkrwnhs.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtijzmvueu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtzervllbv.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtzlqeurer.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtaqnwbhwd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtieedzati.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtpxyieflo.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gthncgfjlz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmdoooaq.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtnvflrzea.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gtvmedmxjj.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtxknvvrax.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjutkhwsd.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtetqqumty.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtpsqrjafj.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtpjqhuqmu.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtgbofqgis.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxiipluf.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gtqrhrzdel.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gttegafowk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtxsztpjns.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtxtxfvakr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtnmzsuyed.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwykmljrc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtnmyfxeop.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttcordfym.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtdnedpbgz.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtydiqhtuj.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtbnpqgauk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtfyycnsgx.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gttazjcxjq.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtthinixwq.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtvborxjai.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtfczognry.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxokxntl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtnadwohab.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtaegfpjww.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtzjpglezu.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtujnxpafl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gtbnfekpie.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtfbpdimds.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcsgrtvc.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtoevjgemb.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtvbsftyiy.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtajihwzgu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtszxtmipb.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtgdnhpuos.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtyljnxtuw.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtiqqiueus.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwjskadla.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtlxcydfok.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtojnvavme.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtlnoiqsil.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtxmjauivv.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtehwnziow.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtlpuzddkx.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gttbcqahtw.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtsxnodwii.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gticllbced.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtzvckcdjm.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxwvmlfr.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtohxlboxo.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltffisgs.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtvvibecwr.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gtphxydjci.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gthundgjla.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gttjcccejh.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gthpsbekzm.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gthqyyoebs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gthpfwlapl.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtkkejvkjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtaxkzddkg.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtoudxobsr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtdyghvero.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtizylopof.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtfqwevxfw.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcvjusgj.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtxyxoqgxj.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtwpvdktuj.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtidatnguo.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtbvchkmaq.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gtzcfamwae.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtessigxls.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtcsojsxkk.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtfmylrzzb.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtdyiwxkzn.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtvzdwlxbq.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtklawrkfq.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtmgpcdlji.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtfnwrqcnx.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gtxxqfzbal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtegyusexg.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtlzdzhnib.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtlqzjiffx.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtajqicdsg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtxpefppov.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gtpsxrkvbe.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtokrayhtr.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwlolwjq.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gttlgsvgra.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtgpdhzxwd.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtbesrohkk.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gtcrpwuozd.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtphvtwiyy.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtaagmzezq.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtoynftpma.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtrvbguumy.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtsynuzbgh.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gttelsgoob.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gtqphatyet.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqlibset.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtjqhkfile.html

[T44] Perl：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtljhnrmgh.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtetnxhvio.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtohozehjx.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhmspfqi.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gttskbnrfz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gtryrvkorh.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gtsyeocoju.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtbbebgpef.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtlqgyribt.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtvjqipfgo.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtzwjthxti.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtlsmtnhjz.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkcbqdfsp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtbiflemjh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtieajldmy.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gtxrwnjcio.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtmrkoyfvv.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gtvwkimgtb.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtgmtjqflh.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtdwycjsuu.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtghbftbbz.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtpvuoodir.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gtakpphvnk.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtomkeorwp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtweqgtcgz.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtdiepefhq.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtafmsukkg.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtnphsalbr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtkcxoonhr.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtmxjajech.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtfconwova.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtqhyrujpg.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtmixwcuug.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtdiyvytex.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gtdainjwig.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgpamtslq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtbnwndxzm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtycedujdt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeoirrbg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtveijpooc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtyswkuoqf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtawbezpec.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtyljchisy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gthfbodxih.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gttslsvgpk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gtlwickqcq.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gthzbpttie.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtkedslbab.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gteweevirj.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtmptxpvpi.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gtrxehgpza.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtpagatonu.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtsayhkyex.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtevgzkppk.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtgalprdcf.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnsbgena.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtrejfqejd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gtwtkarqjj.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaieaodoy.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gttyinglby.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtjvktfabs.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtinznplai.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtlbmbtskc.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gtuvnsoshg.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtmzabibil.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtrpxqabbj.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtysrdiufq.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtnklxnrgw.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtgotoksfe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gtixqattyc.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrybulcy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtdfyfyvai.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtqjbphltr.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gtnxjmbofx.html

[U19] Py：正则替换带回调
来源：http://dali.aibaodan.cn/Article/details/gtpdqkiiip.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gtnfcefczu.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogdwaxjw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtgxfvykfq.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gtnatztxiq.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gtxxwktqjf.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtdwmeiyuv.html

list(zip(*m))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokpuddyb.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gtrxxxggci.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gtcnoeuwhw.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gtmkzrpmhj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtokwzujgh.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtoawdumzi.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtuknpmslh.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtxskhjcnp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtbjnzdjrp.html

[U27] Py：异步 HTTP
来源：http://dali.svipenyu.cn/Article/details/gtyuvnhomf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtvotqdxxe.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gteodtftik.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gttddspubw.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtlfdudmbl.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtulzvxpjd.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gtwbvnqvvp.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gtsvxttyoa.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtwvfclpbd.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gtzdkxrtqv.html

[U32] Py：代码格式化
来源：http://dali.bjfxy.top/Article/details/gtbkgijxkv.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtrhulrcuc.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtvymfouju.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gtziiqbbva.html

[U34] Py：判断编码
来源：http://dali.chenzaomai.com/Article/details/gtlxfkxsza.html

chardet.detect(raw)
来源：http://dali.zhiwuduotai.top/Article/details/gtnsppprkj.html

[U35] Py：发送邮件
来源：http://dali.cashguo.top/Article/details/gtbxyybvog.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gtavfhgubm.html

[U36] Py：定时任务
来源：http://dali.hnqzz.top/Article/details/gtfegtwbfp.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtkznonrbl.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gtbygxzpya.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gtgfttfdus.html

[U38] Py：获取脚本所在目录
来源：http://dali.jianghu66.top/Article/details/gtsmuwtuay.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gtnoxzqtae.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtrohhfdgh.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gtbfemupep.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gtdwmvxsfs.html

print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtithcqnfo.html


<!-- 参考信息 -->