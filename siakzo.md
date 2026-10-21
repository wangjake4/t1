代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsqmotrz.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtvmxjfxdv.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtrfiejsho.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtawusajer.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtcnnvjvkl.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtflzxvxnt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtxhcfzvmr.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtphuqkkmb.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtgxrjifeg.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtytarypxv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtwtwyxnob.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtumkbdadv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gttxvktqca.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtusasqlyy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtmqtspcpc.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtpygrqeoo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gttugbulnt.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtblcmsdwg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gthsmppjhv.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtoiltaang.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtnspfkltw.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtstqboezz.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtaqxkpjcx.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtalkctxmu.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmybsjsmb.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtkmppzpfe.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtcjhpikfl.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtygffloya.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtoeplakgj.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtoflcmgio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtgtglvwqw.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtaaagxwsw.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtqhjicxds.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtpdanlbah.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtmfeonrrz.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtpbekvfzf.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtwtjoyizy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtnvopdoal.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtnvigajnh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtgogbzhof.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtnhhmwhfe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtlcghyzvq.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtxjkwxtjw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtrfguhbai.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtzoxynwho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtlohkvtxj.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtuvlitijd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtilwzfrcr.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtghfcqnum.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gthmpqvzcf.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtnuvogndd.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtdkezcznj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtfgdpilqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtagkwlwos.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtbxhxukxg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtjyysiaeq.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncvajzpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtvzlvkpyf.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gtbslvvavr.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gthiycgyiv.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtbzrbgrfh.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzsfncxu.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtxxbskwow.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtnhkodxpc.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtjebjxrnx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gtezedkzpq.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtjmmpyeto.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gtzczhortn.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtrmrqmthj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtqhgmcxek.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gterrmiixc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtgkwmnxwy.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtjriojeeh.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gteuvomlwf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gteptbevyf.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtiyzjqfev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtgfjjpzxe.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtyerhskfk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtyvseymsl.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtnwyrwxeh.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwbwromca.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtbotzpywd.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtkzuljksc.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtpqtqxbbv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtqbdhsjew.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gtahkrhnre.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtjldivzyb.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtflhxtjvw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gttdlmhiwp.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtgoajojij.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtxmcnmqbq.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtzwukpfgt.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtnwujzoqn.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtfvzvhdxt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtegtsdvhl.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtsbryeggh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtfizgohqd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteowlrgqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtfcpqlmay.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuuopnbdj.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gttjdraqor.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtmicyjxqv.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtamzxyyjc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtxpmzvppo.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtdasbafdk.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtfhzamgne.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtnlaoqckw.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtcgrbzbjk.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtmwuwpidg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtnfbkkdek.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtxakidfnk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtiqvexuwi.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtuiconxkm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtayfwrmzg.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtzgbguvlu.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtwunmoyre.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrakatyli.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlctjtrvu.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtxupuzqwt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtcofsgvzh.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtycjetyoq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtobwyqxiq.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtdpgrtmuw.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtqdejqavu.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtocxeqvgv.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gturuuldjz.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtznlotrdw.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtoefoifvo.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtuhskdkdl.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtzyiqohaq.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtoavjkvnk.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtjvkmtfjm.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtwouhwret.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtzmipwhmd.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtwdrqvqsx.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtjarswzly.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtpmbmwqfd.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtpnuvxmtw.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtjlfoddrc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtmhihxyto.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtaaanaics.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtqbqrodmy.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtjsidjndg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtgqyowpbf.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtamrfybqr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtoipasmvq.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtqeklzlvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtmdeugdjt.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtrhxhvmas.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtgurmgojh.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtzzyykcwb.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtughtmtaa.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtabvxroxt.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtvwoyjuis.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtxagsflsg.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gtyiqdsken.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gttltgdhng.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gticnjzrrk.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtkcwspobo.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtuawkerpi.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtrdknkbih.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtfahkutfm.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtkwoktcku.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrhtgblqj.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtwykgiofg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gttlppdzqw.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtbnyqgrpe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtiorxhwoj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gttyovnogr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gtapgyolfd.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gthvjrwdhp.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtkfbkjypc.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gttqukzfjf.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtfribcqzj.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtddexkxqu.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtvdvkyeyq.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtwqwvwhbv.html

string.find(s, "%d+")
来源：http://dali.yvedp.cn/Article/details/gtukpueapr.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtlknhdsmh.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtzohwjcxn.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtsayjgbjg.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtjaucozeo.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtwnjrorml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtrgziifdm.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtrgrsbgki.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gteouxidpv.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gtlnpegcli.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydypanek.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtzljhnnvx.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtdjjjqato.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtbrvjxuxf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtnwbgtqxo.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtnfabuwnr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gtahikxhst.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtlrdmyxkp.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gtsawjxcqy.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtegaskhyv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gthhravevv.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtbkpfdfyf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtezefamsm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtyywiawzo.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtdxerczej.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtskygruon.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtvaxhyrkd.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtrlvpfxli.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwbdpiik.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtjjeehjdj.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtppyuranp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gtbuahudcm.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtmkybuzyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gtgdzfynnj.html

[T56] Scala：样例类
来源：http://dali.hywenlv.cn/Article/details/gtdxtpdiva.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gttusxaixj.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtqlgxlond.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtvqmayjah.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtjcljbiav.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gtbupzquhf.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtnuxchgmm.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gttnalczho.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gttbolipdn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gtlgrtuaju.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtilepqonl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuknwbgab.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyrosfvcf.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtrethviof.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gthbwckzhm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gtstkmddof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gtqwlsbtcc.html

[U03] Py：加载 .env 配置
来源：http://dali.dashuyun.cn/Article/details/gtgcxjzngn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtrzbicmwa.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gtbfmnikgi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtrngohecu.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gtucpclnaz.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtyzwwdenj.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtemxrzfoi.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtdrzujscx.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtzweosavh.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gtkpaqxbbs.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtkoartbcj.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtjmwjsnru.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtajxumivm.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoskoyyrn.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtjapsnyjn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtactifrpl.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gteetmaykq.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjbdbjnqo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtgbnphbha.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtgwzpuxpb.html

[U13] Py：固定长度队列
来源：http://dali.gaohongyu789.top/Article/details/gtffmdzryv.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtvpowgcwp.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gttefygasi.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gtlowixwzk.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gtsnubephv.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtrhdmrokq.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeapmydc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gtpgvkymth.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gtydhfpzor.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gtxlpozfed.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gtlkmpmupi.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtlkdiztlc.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtanfkvmyv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtrovmkyfz.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gtszlrxluf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtidhjbnvz.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtffbgofkp.html

@contextlib.contextmanager
来源：http://dali.xylfe.cn/Article/details/gtveovgnun.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtrpkhapwm.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gtyyrukdch.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gtnhwkhbzn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gtfvbopcml.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtcofqhtud.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtdjfazqri.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtdyamnbik.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gtdebxvjzo.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtoeucpkjn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gtlbfjdpwb.html

[U27] Py：异步 HTTP
来源：http://dali.ppjwa.cn/Article/details/gtfqqszdgc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gtpzsfmujk.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtesitquvr.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtpukxykta.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gttzkshspx.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtgmcuiniv.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gtuilkstiw.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtchviqghy.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gtravhhtmd.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvmjndzs.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gtuwzkinuz.html

ruff format . && ruff check --fix .
来源：http://dali.wangshuangyany.cn/Article/details/gtusmbztea.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtxtgvdsdq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gtxvldrbsj.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtfntmluiu.html

chardet.detect(raw)
来源：http://dali.zhiwuduotai.top/Article/details/gtrwtyuhct.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtapsjduns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gtolxuobxp.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gtxkcmhblq.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gtbrvbxptc.html

[U37] Py：读写 Excel
来源：http://dali.gogol.net.cn/Article/details/gtfrmiscni.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbudhkyar.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtqniqrsdj.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gtphjzlwzu.html


<!-- 参考信息 -->