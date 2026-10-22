代发 wailian999

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clhipfkx.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gt2wbieraqu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2gayqtfcm.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gt2jfswobjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2otcgbqvi.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2lcrmaexb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gt2nqkjuogl.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gt2nfcyatdw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gt2srcwmdot.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2ahijudlt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2dtslvfau.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gt2xwuwrdzz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2sudycvty.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2tzlwpqij.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gt2exevmucg.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gt2saaibghg.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gt2jclrebyu.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gt2tsewgsme.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2ggvoxnax.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2lohtbfon.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gt2rztgkhgr.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2tsurcpkm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gt2johyaarc.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gt2nzaxrxne.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gt2puroeevh.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gt2fstyxqdd.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2xlffkdzn.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2apdgfamy.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2kpnxllbm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2vepwibxg.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2gtxnmcrs.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gt2yjgndhlm.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2thqqcfgk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2xautfaso.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2cpuedxdg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gt2gxnwnthd.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gt2onqlrmjj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2xpflhpmy.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gt2dftdtkqh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2hwocqcpc.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2hehwkbql.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gt2psbukbek.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gt2zdtolupa.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2geqedibd.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2skbbsaus.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2qqccoudj.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gt2ovebgnbo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2zqmgyxqa.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2afdvqfol.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2yhoqficd.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gt2xwxtvsmh.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gt2idaxhhlh.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2eaxuimmz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2qnxsifin.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oldgcgeq.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gt2xopqobgq.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2xezscicj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izryqkiz.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gt2etgmkbaj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2iyioeafw.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gt2akqrnett.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2ommkcvmv.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2fatemnhk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2ldwileal.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yedogden.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gt2jrojyfqe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2qsmarayt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jodbjtoj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2irgdlaji.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gt2rhvsyjec.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2owxwtdro.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gt2ivsgmfet.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gt2wturltqb.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2muzfvyrp.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gt2mrcdllpj.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2cwocxiqj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gt2pbexzlza.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2noynxnzn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2bjhvvzcz.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2pxicsdzp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2aiqwcjrk.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gt2phapnwqb.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2lrbfjgyk.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gt2vgybmgxz.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjyallpb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zavylkcv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tujwsfro.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mipfpoyn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2ditdlttm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2dmycwwqd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgjfnsls.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ligzrogw.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2wwajhweh.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2aopetimx.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gt2dgbcfoco.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gt2tjgmngnb.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gt2ykfoflnv.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2wjcroycz.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gt2cfrkxsxz.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gt2zgxbphvz.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gt2rjjnoomw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gt2tnmfyobp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xdufulxb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utvbxtan.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2zeejnlga.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gt2bvxmgvge.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gt2dhiioofw.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2vefvhpbq.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gt2xschhype.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gt2viabitow.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2egrtntqv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gt2mtjcdlgf.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orvyhukx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2prshkhjs.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2zvafbidf.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crcpjskh.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2dmsnduaz.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2vvngtkik.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gt2zmukszsh.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2ilfqojmb.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gt2dvzjzocl.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxpalrih.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2idbjgytr.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2rjcxebrv.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2ecinyymg.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gt2vqqbxinf.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2tvzkklkd.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2agviuwfw.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2guqfnguw.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gt2iezaikbi.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gt2bjqxnnfc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gt2ayvzezxg.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gt2pfvbbaao.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gt2lafplrbo.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gt2bdzpmmhs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2xguvtvbq.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gt2ivtbtmtm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2kwhotadb.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gt2fswmfxnd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntesjspa.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2uhlubuvz.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2avkqkfsa.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gt2ltzseiib.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gt2dmsqknra.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gt2qygmbagz.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2jwmhqrut.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gt2kqwcosht.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2jyugjdsv.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxukchoq.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gt2ryefxywc.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gt2feexmtyc.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gt2uhublgga.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2gtmafyho.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2pcibacbh.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2sqywaims.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gt2xrgubzkw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqraghzu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txvavkql.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gt2htdeflqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gt2vyydmwfg.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2ezkdfcgs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltsjkmkq.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiagajlc.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gt2locckvdl.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2rbmnrgah.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gt2zhahacvn.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gt2zluaewbg.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2ritjoizy.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2mtkrgrmo.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2idelekcf.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnlsizdv.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gt2tuvzqkoa.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gt2hohhvtvi.html

print "Hello\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlfbhckz.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gt2nrvmtizu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gt2ajwwsjtx.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2bhnqlzdy.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gt2mtzdzdgy.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gt2tbtqbvjv.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jmckkqqr.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gt2rmpzlwtw.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gt2wdtrtlpf.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gt2tcbkikvm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kgufillz.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gt2vszgocwt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2njmxgoux.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2akbbossv.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gt2meuetefm.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwrzfurb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqcqtype.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2uizayftf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gt2zbfzhsjm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cexmsdiw.html

[T51] Scala：Hello World
来源：http://dali.meibo888.top/Article/details/gt2jbuggura.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqgekhnc.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gt2lvqmrufg.html

val a = 1;  var b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2mckumfkg.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2iikqdfzk.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2gzomjdlk.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2eycgvxha.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2clznytur.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2wbqubptp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gt2ankzzgga.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gt2cijjrhgo.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2duolmaob.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gt2tnsejhnd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orysnmal.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gt2tvriophv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnqroiee.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gt2wssdpjnc.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xowbnkvt.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gt2mqazgklo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gt2coeyubei.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nljrumjj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gt2dstbsifw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2onlhmdqw.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gt2emvofzom.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gt2miylxjvf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gt2sgdjlzpe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2ivuazdgd.html

[U03] Py：加载 .env 配置
来源：http://dali.sufxvd.cn/Article/details/gt2pqzmmvfm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gt2titywcco.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gt2niiykkea.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gt2buxdlpcn.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2nxopolcm.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2utittiwz.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gt2lpqqugby.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oasqmukj.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gt2yxhixnng.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gt2afqyrmpr.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdursisk.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gt2bixpxbmd.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2zqdusyqd.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2swzttdvs.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gt2thlpspsc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gt2icfummdb.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gt2gxfcuuju.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gt2dojhrxfm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gt2qhjonfdf.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osowohjf.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ilivdvwc.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gt2nxyhnamz.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdfqcbfx.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2urnetele.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gt2sgrmabvb.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gt2xvnavtus.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gt2slxfkwgt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gt2whexaqjx.html

[U17] Py：初始化日志
来源：http://dali.tian-w.cn/Article/details/gt2bwkmncpc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gt2xpfgsdes.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gt2qwimruvy.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2uivrwfeb.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gt2ivsoubgs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnijgqwc.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gt2trpstrra.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkoozkka.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gt2keqgufhu.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2yunvzkdp.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gt2ofudjqty.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gt2imouocjp.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2mvgprfpo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gt2nxdykzkz.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gt2eunfopfg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2kvegtcln.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gt2fqojsfjg.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gt2blrcsbjo.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gt2xpbbgbce.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gt2eduerfbx.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258.top/Article/details/gt2fvrrtpcg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gt2caikbzly.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gt2rsomjkxw.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gt2ycuurdic.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gt2gpbrggcq.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gt2ekaquqmu.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gt2liyiziuq.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gt2rbinlvpq.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gt2hdjjnaoq.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gt2lcqsskav.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gt2xfzdioix.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gt2uifcnblv.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gt2wmhmloyq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2bzniffvt.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gt2hijiczli.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gt2lbnwlvyu.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gt2hxmsgkyy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gt2eujuibgh.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2gwvzodyz.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2ydfqkdxn.html

[U37] Py：读写 Excel
来源：http://dali.xinyue.icu/Article/details/gt2wxcrdifd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hammf.cn/Article/details/gt2fajjevvh.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gt2ypltyofh.html

Path(__file__).resolve().parent
来源：http://dali.cqqwz.cn/Article/details/gt2evnrbliw.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gt2oxoijwmf.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfsjzfhz.html

[U40] Py：打印到标准错误
来源：http://dali.9152youxi.cn/Article/details/gt2cjfrezmb.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2qcnebyzm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdwudqfj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gt2ngrcysov.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gt2elmaxgea.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gt2uvlsiavm.html


<!-- 参考信息 -->