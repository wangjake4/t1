代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtoawjubue.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gtdufdrsxa.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtkrxnavrw.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtuvcyfckz.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtgfpwggai.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gtqjqaxvph.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtjcvdevpx.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtoxxhiysz.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtddxiwmmp.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtlauszktj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtyoljdgxc.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtwozrhjuy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuvbxlvy.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gtembbyskl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtffykhzum.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtbsxukwiv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtmutexmco.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtqmyyrnwj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtsalotojn.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtlncwvhak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtmrzjspnn.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtqiteycts.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtktkavryj.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtwfjkxuts.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtmckkauqc.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtfeneihbt.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtvbkvvkam.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtzpzodcph.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtmsgasgis.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtxrijltgn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtatixflyh.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwcobrnb.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtcaxrodpn.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkjsgjvr.html

#endif
来源：http://dali.hammf.cn/Article/details/gttdboxxof.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtclxfjujc.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtxgdxomcr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtiildjvmo.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavqykmls.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtqtxinknb.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtslfihawo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtpapikjxb.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabinxron.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtudzewvpe.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtryisqfhq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gttjqkwjai.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtvzcdvymf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgpoemwn.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gthvzyqxqk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtphkolfqq.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtcykluovz.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gthmjvxqdx.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtdgcewkjh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtspxgkzfk.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtgmsofcgr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtaewbdcrs.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtyacsigtz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtrbqeclzy.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtvlthnjel.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtzsjpxpbt.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtbvhibikq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtqhzsxosc.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtnkmyvyfr.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtzmebkong.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtaneaybid.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtksvscwzj.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtlzorldbw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gthcrqwacb.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtbwqofoso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtxmlebypk.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtogdgxrpv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtvfuzwlts.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtlprhnfot.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtcbpdqevo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gthroldfcb.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtzhniaqcw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtpicwvthg.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtpuhtsfpb.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtxgfthapx.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtlhizqmwz.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtnjavzjhs.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtsyykeweu.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtkpdhzjxb.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gthgmesivt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gthnfoqtnv.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtjykydtpy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtqcpxepzh.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtvremgcoe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtcmvfytmv.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhutzbtz.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtzlzllpta.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypqizpsd.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtijqflsve.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtdcmrhvtt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtkkeijhvl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgknbtaov.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gthouezcni.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnlfzquhw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjatsdulp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwavveqfn.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtcfltrnsr.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gttnodxqrd.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtchcxalto.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtxuitjdmx.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gteqfvyyou.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtqgplisai.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtreytycip.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtyujxnylg.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gttqethbky.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtkrswdtfl.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtoqdojypt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtpjyseose.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtxfhfsqio.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gttzgelpyy.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtjeoaqzjt.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtfeqxpmle.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtfdakatok.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gttcjrhohw.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gthvihtlby.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gteuqlqwau.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtmtuywwyg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtmratvhgx.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtjkuknqfh.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtekgycvvl.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtmupqxegl.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gthmigmlke.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtpzvkvclu.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtmflvogsc.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtbmedmjvu.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtxanoewbe.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtycucefge.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtxulutmrh.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gtjxqbimwm.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtcnskeklj.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtfxizalko.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtqlbkltkc.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gtzgrilzxj.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gtnagfckzb.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtupcwuxnm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtsrlcfkkx.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtkrenqbpn.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtygjcfncl.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtsuqvxvtp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtyhxrdxuq.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtszvlfong.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gttlvemeih.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gttgbddnvm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtezztdalw.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtmemggnud.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtyysykywr.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gtxsjdubgd.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtcznipdhm.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtahfjunoe.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gteqeszjbi.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtmdgmyznh.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtlnwzryme.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtdsloptcd.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtywxgbavs.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtfptznual.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtftlrdgvi.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtnqzxkwpt.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtererwrta.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrfkowot.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtnhrvzelj.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gtlcvdwhwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtjhulshiq.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtnehqgqex.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtmewzolse.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtxozgvebd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtrsahntph.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtdufzmvba.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtpgruluzh.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtbsythjpz.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gtaqqapmyq.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtlamgjtfd.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gtdnzofkfh.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtklpfsedo.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtvtomuxuh.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gthpgojswu.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gtddkhvpnw.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtshwbnsgh.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gttbngzbvg.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gttzwzajdk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxydgprlt.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gttcxlhqyn.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gthzodiogk.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtlsfegltg.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtsaoxpanm.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtxotaghtk.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtmhkzsnyy.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtyicoorrp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuiswvzd.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gtkzgadayu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtcpkvynjs.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtfbmkutqz.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtkgckmqlc.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtxsvnngnf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtnpfjdtqx.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtvdkorxue.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtknjwslgr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gtqbqsxyvk.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gtpqslkpxx.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtpghszkgn.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtmbhetqrv.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtkiggcnth.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gthacxhfpq.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gthimcklnx.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtiwfwwrig.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtwrvvnzzr.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gttrrycuir.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gtmhspbscb.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gtssprzbjd.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtxurhcemn.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gttqqokxuc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtbigyefix.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtceoeitum.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtzjfihfoj.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlntejivi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtaqnczzyz.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtpdmzhznn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gtarpxyzhn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrkvkwzmf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtgbxjrmvm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrhxcouzg.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtxlyqkysi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtzmwdejvf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtpxnjcncj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gteqwzeoat.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gtxkbzpnuy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtuietltyr.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtbckckdjq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gtabepbyiq.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gtqauadsjn.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtvqzipasl.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtljygrkou.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gthfexvcpg.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gteishzjtw.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtavmrksxc.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtwduvbhks.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtkvjabbsd.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gtlteygznb.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtclflpbra.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxfcvnos.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtutmpcaps.html

[U11] Py：生成器表达式
来源：http://dali.yuxming.cn/Article/details/gtqbidkrdq.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gtinwwyrnh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gtnupshoqb.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjypuflua.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbdsnnec.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtkawymopw.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gtefkwuyhe.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gtssqowfjo.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gtrrvlfxtr.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gtxpswptzr.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtowfkhcyu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tanke756.top/Article/details/gtfbhmhhyu.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtyutqsbfc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtddrztlaq.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtrzsxbqyj.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtkspvjkxo.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtuajlxqsj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpamgbso.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtlqybjylc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtjarorhvb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtfklnjfel.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gtpspyekha.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gtjdujutev.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gtycfueiwo.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gthditfgbb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtsxxjsezw.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gtcddqxiqc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtbpajkrqu.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gthkpnyqns.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gtxeftzqdj.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gttxosqvni.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtipjadgpe.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtyycrexdb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtxacnreoc.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gtclrslhkg.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtqrsbhead.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gtbnzrpzty.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gtaaoygqgc.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtliqfmjkk.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gthixngixz.html

[U31] Py：单测
来源：http://dali.yj202588.top/Article/details/gtwxmzvqtn.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtoyvsrels.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gtuzvaynik.html

ruff format . && ruff check --fix .
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsjfyddu.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtqoymwtap.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gtqirivxup.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gtybraiyok.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtsctgzidw.html

[U35] Py：发送邮件
来源：http://dali.cheryme.top/Article/details/gtsyjjybds.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtrcjyircw.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gtnuhsqvnt.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtpnlrchmx.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gtfszlqjej.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtylfcemac.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gtxewbtvpp.html

Path(__file__).resolve().parent
来源：http://dali.chenjidiqi.icu/Article/details/gtjgjfpoxs.html


<!-- 参考信息 -->