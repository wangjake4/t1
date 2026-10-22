代发 wailian999

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gt2bgfrueup.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2waqcylep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2imyvzdhu.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gt2bokjfrxi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2lllcmrqo.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gt2buxifnqc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gt2eqwsfgvh.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gt2rudihrmc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2nmsbrnos.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gt2hlfnricg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gt2ljwgelkc.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2gixflclh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gt2hrbhbfab.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gt2zanbzxdy.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gt2ovrbtugs.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2kgigskkh.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gt2kjtwworg.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqqrtsrm.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2olcocanl.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gt2kiordboz.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2bqntgkgv.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gt2puqcymuq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2bhwfjwlc.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gt2jqlehhop.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2ioomkqtv.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gt2izdhozjk.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2siewkzfe.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gt2ptbvnirq.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2lzyxpkzx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gt2ortmvkca.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyqvmhxl.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gt2dmavsnly.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gt2vgllsfih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpnusyau.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubrmcaqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gt2ysudexro.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gt2xcrmxiqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2zfufjalg.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2qjthielk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2lwvnnouf.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2xjswmmkj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2gwxxksui.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2wvrjdbel.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2brippndl.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gt2qthjhdnw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gt2fntprhqx.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2ubjrsbwd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2adxecaaq.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2nvbmmvyc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2hwnwgvgl.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2pldoekaa.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gt2ctauuuok.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2jheupsic.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2aoeshlaa.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2hcyxbcma.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2finbzsvf.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2kmonhcms.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2sqbpwhnu.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gt2utwrdqoe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2mbyjqtkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gt2rrtpsuvy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gt2oavgfvzm.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2bcvkfziz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjxluprf.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2hmunkqzi.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2dgtncctv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2jrdordgb.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyjmfpuv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2twgvdwgy.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2twtgogni.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkbdpovb.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohhjcdbw.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gt2wtipvmns.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gt2gvmnzwqh.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2bdgwwdji.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gt2rqvyoxpi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2vkhlrcgr.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2mvkfqfgf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdldyznh.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2ugrrudbt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gt2ttoroffe.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gt2axytdckm.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2iaigwkni.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gt2pxefitkr.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dexxnkrr.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gt2pnccafvy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2tmwjbxtn.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2tmndmeuz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2utgyclmu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2oqfglpxx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2uqanqkbz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2nmvjjiyd.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2vuwncmct.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2prvnruws.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gt2cjhjokgx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gt2junpvcrz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2njdkrpgz.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2gzeibhdk.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gt2muxbijnn.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gt2qinfceen.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2daxkujqo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2esoesvkn.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2oigadmtz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2cjcvilej.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2zdaueilf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2scfzwotk.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2sxzlkdph.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gt2kdntotrt.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnlkapri.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gt2biojvqcu.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2xtwllsvr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2blznhiaq.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2wsmyumxn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gt2pswjgoig.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2faqqxdqw.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2vssrjdun.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gt2rwqomjgj.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gt2kvupnaro.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eztlvhrf.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2olqefwwq.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2oxfmdtnj.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2lbsagwhk.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gt2ajccdtwb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wempqxiz.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gt2lepxjfvq.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gt2klekvkul.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgrapsjl.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gt2dqnvnlfi.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2dltlhrnw.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2sicsxjwd.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gt2xysstyyn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gt2xmkwvpyf.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gt2ztzbauyf.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gt2kxgptrnr.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gt2zherrayg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2aqumvlpl.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ntomgrxm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gt2hqbivdyy.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unpfvqdd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2ogcezttg.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gt2fcwawxil.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gt2xqdxmsdb.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gt2pyvieuba.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gt2zuclxkfm.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gt2ywplbjvz.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gt2zotzsyzf.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gt2uyggrcde.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gt2bzggnens.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2pbtolbhb.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2hjzeadfb.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gt2apbsfxpg.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2tjqdqwwi.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gt2dhcjoyni.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2btldrtmj.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2jnyshmew.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gt2vgeonnfy.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2njkjxrfb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gt2mdrnxxtc.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gt2pfwxnfaj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gt2fuwocsnc.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gt2iqecjhyv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reyoppoo.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sappxvfn.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2gsxzjiwe.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2xtlrdkvi.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gt2inedxbml.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2hpcdpujj.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2jlfwjyir.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2kodyrcdc.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyycsjwl.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2xgmabfff.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzgrmdbl.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2icdzaidl.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gt2rraahtks.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gt2jeybxgzh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gt2rzauedgq.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2mgubuybt.html

"值: $a"
来源：http://dali.0kj1m.cn/Article/details/gt2xyiqxyzb.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxtwmjuq.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2sbpinvim.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2vwenjjhb.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gt2bstffkzd.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gt2shafpuog.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jykmjbbe.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gt2oyiergvq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbaspopc.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2dbdynfwk.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gt2zqtrjozz.html

[T49] Perl：函数
来源：http://dali.316326.xyz/Article/details/gt2gnsyjril.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sivbenkj.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2rklixafa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2rggqqroo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gt2innqoixa.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2qmcgqtwp.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2kyzumkgw.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gt2normgxbr.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gt2gayetnri.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2amzaesnf.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2uitofcid.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2mtcmzxxt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2duzmjiwb.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2ajiqtbxk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gt2aryrhkdl.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iayvxlrq.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2jxuwrcex.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2ifamjsad.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gt2njwlafte.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgozndoj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gt2spiukddn.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2hkimrzov.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2gxoxzntl.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gt2kkeprknh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gt2kpxnrlbu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2twaxzvuz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gt2aakfxvmm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsrrcdzg.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2beaqhyst.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzaatlzg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gt2ttijhljn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gt2wvvgphyy.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gt2weaxfler.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gt2ncnybioo.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gt2fcgtcwpu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gt2fbvfojon.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gt2qxvriitm.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxxgrblb.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gt2cagbwxqm.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gt2gwogdsfk.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gt2wrhhjoye.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipwdqqwh.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gt2lufzoxxo.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gt2atjnaxux.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gt2hwadijks.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gt2wzvskhtm.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gt2ozdykvgc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gt2dynqnijt.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2bklefrxn.html

(x * 2 for x in arr)
来源：http://dali.sweek.top/Article/details/gt2ysufzbag.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yongpay.top/Article/details/gt2chbbjjzb.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gt2stnvycrk.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gt2uienwwqc.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gt2usovxgns.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gt2ybmqblmv.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uazkeqdn.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gt2xvrhomqx.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gt2kohgtizg.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gt2stsgjcla.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gt2eftuglon.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gt2htgkrwap.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqnmlcbc.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gt2zalhdzkx.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gt2xdmljdev.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gt2osqnmiwx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gt2gnurzguy.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gt2shsabume.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gt2yjcbjlmk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gt2nvruwkkr.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2frzbasib.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2molwxdtq.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gt2gtpciqyr.html

[U23] Py：分块读取大文件
来源：http://dali.jqgfzy.top/Article/details/gt2wakdomfn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gt2uupdeqmt.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gt2nxonnker.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2jfzuwclh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqgfkoyr.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gt2urlosojd.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2jeojxuuh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gt2bkoepwot.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gt2qlvlmhym.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gt2cuelbseh.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gt2jxzokmlf.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gt2udwfdzzs.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gt2tkawwspt.html

@property 与 @x.setter 配合
来源：http://dali.ehwqpu.com/Article/details/gt2vmsreqds.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfjskass.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gt2mxmlhsxh.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gt2vymjtlfd.html

python -m pytest -q
来源：http://dali.xziqi.cn/Article/details/gt2vksushgc.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gt2jbvdlqae.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gt2fjtkiskb.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gt2hakrikep.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigfzy.top/Article/details/gt2lklvvnnf.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gt2wymecpuq.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwwhbeie.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gt2bnxnybzd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.316326.xyz/Article/details/gt2wygawdux.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2iulwvddu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmhhmuth.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gt2oiuzwoml.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gt2kkdrgeky.html

[U38] Py：获取脚本所在目录
来源：http://dali.jianghu66.top/Article/details/gt2uaghkgcy.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gt2jkkackhp.html

[U39] Py：判断是否在交互环境
来源：http://dali.c1oappe.top/Article/details/gt2dlpavnvk.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gt2hmwyhlnd.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gt2yoljdeho.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2dzoakshq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gt2cdeudkwx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gt2bmcaipdy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gt2otfzmrol.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gt2airgwnef.html


<!-- 参考信息 -->