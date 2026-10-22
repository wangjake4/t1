代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtraykmjqn.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtdqgocolq.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtlcffscrk.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtvlwuaiak.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtwgexpxqz.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtnxtkqskc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gthlhvogph.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtduglxvan.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrhvyjea.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtzoikizkc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtzsuzuosv.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtelfmfbkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtfbdhutgl.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtmiruysrr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtwwnpjqmo.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtfuqcazwd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gthoakfrlu.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtgtlmoslf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtdzopjows.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtegxlgdlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtfrenjvhx.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtollahpfm.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtlvksddnx.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtcsacipdw.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtxmtxxcme.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabireuxb.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtjarnofbt.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtokkmrjth.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtusynwtcn.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtibwgstoo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtvsfmrfko.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtadrmjxvm.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtphvltxqc.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtjsokabje.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtzyxqcaag.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtjpxcflst.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtlwsqltyp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtvwdhkuzk.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtkjvlkbqn.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtlmcqxctx.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtrozxsncx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtrsdyfqxa.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtnzxogbzf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtncnxvjgy.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtggynfefr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gttefeqsak.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtxfxklymx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtxfyywxyq.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtgdsmbknn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtotqvxsvk.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtidxjeyze.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gttjqvmrmw.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtdzxuvbfa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtrrgnnmkf.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtvorntzbk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtocxkospr.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtklnxpgcu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtsgvmzjds.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gthtddtpit.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtncbiyjep.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtdvcjbbpa.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtgefzfedu.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesmllrqt.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtivycqvjb.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtbxkccamy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gttringewj.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtnbvfnsbx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtddzhtbnk.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtexlxbivp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtzcuhamek.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtpofdcarv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtsdtbksew.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtmaksrxpf.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfavaemdn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtcdyndwwa.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtgsziawil.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtcklxqtue.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtfqorqutu.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtzmoolxpu.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtrsfqpfam.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtmmsdfkup.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtqdckojqf.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtdrpkdgka.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtiauncald.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtgpvrdgho.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtppwgcbps.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtaxssffuc.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtswbpwfhx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtqourmdxu.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gthvqiihit.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtfbumaikv.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtdpoarwvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkagqkspe.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtkjyujvge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtvfmmbznw.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtltphhtvg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtzjgoqnqp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvhgjasub.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtihgudcaz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtomtoluwn.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtltmqfnys.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtowsnjipu.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtpizhxiiw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtktzrviyc.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtyxqtkbnv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtszcoxqhq.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtlltrzexr.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtukfyxnrb.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtsdcwutlr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtlhyiefup.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gtdcddsnni.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtdkuwvffa.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtfjfozrpv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtieevfbyj.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtzmzhsymk.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtdkljdqef.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtdhgmlxea.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtwczsdkbb.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtzmaljmqg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtjuocdgnj.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtmqaxwdjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gtpbvxgqrk.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gtacxsypll.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtgtyxdpwg.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimdaktqv.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtnkixepht.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtshyhfhch.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoswadwgn.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtqrsgturc.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtjfqsiylu.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtmyqfepcl.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtcqlacyfp.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtirihungr.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtpntyyzzf.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtsrqeozym.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gtpsskiqxn.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtxeswtpqe.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtpethqmaf.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtwueftqay.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtfmpktoey.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtniggheiu.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtaoxxtmdl.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtnertbmbu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gthfwdokds.html

[T23] Swift：函数
来源：http://dali.gogol.net.cn/Article/details/gtxuprsvaw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtfzwuoehi.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtstdfcpey.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtyewuglsd.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtbzayyhyp.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtiiludcqa.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtmueehjlj.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gthprsibwr.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtsvibbzhi.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtpalxlpec.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gtaiwxrwzk.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtwkparaby.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtglecfyhu.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gttgrirwcw.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtqrrbxoou.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtbehhywdi.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpoyibnjw.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtvsegragr.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtzijsztgc.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuwrupty.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtfwibvkno.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gthniruvge.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkmuczpt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtzmijqgya.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtrrjmdzwp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gttxugyyvm.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtqhirsddr.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtofadenwa.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtktmcuvyv.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtfitokuzn.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtnmvdubnd.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtpvsvgxnr.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtjveebmcn.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtmftfiaxe.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gtjubfwrhy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtvowndaat.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gtoredeosf.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtsjvumdod.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtnlbgxkjx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gtbdwitglu.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtgtxhoond.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtqletbcbq.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gttrbkohco.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gtossnaqtc.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtcchuzcxv.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtrqjrkozc.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtlrcvtnlv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtkhepsufw.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgfktvvl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtkzgxtpts.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtolmnfphf.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgwhnilw.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtaykvazul.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtjyjncfcg.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtznswhzwj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtwwecpdrt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gttskiioqr.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtsdskknwc.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtemfgxryn.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtctfjxdlq.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtzprkjvqz.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtiqrohohx.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtppdlujgj.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gthznyndrl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtdmkobrib.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtleaxvfja.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gteeiwcwgz.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gthjuqxfay.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gthzrrmypf.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtbryqtijd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtubogjixi.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtqjbjwzhj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtnehsqyws.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtubvulxkn.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtsdivyaka.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gtlciwuvka.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pycfn.com/Article/details/gtgyoafsoa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkhqjpilw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtdqcwkfaf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgpggzvvi.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gtcblfnqtl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gtoxvgisdb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtgrkoixqs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gteuhgkpmq.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gtdwpomoci.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtatzhrnfa.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtiodtmsjs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtmptwxqrr.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtscmcwgfw.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtfmhbujnm.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtnjuzzkvm.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gtubvcqyau.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gttdlgjmlp.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtcdzynigz.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtlovpkngn.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtmizmzfkl.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gtbhcpkmmg.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeosuupv.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gtlivgkfnh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gtqnyjgcyl.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtewoshagt.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtkxtytxve.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtwxfvrfpr.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtddwhkqyr.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gtlwxveihk.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtyvtmzsbr.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gtmuubntxn.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtoyjpgxxn.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuebeavgz.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gtvqqgiayg.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gtmlchorwa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtporyoumr.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtmqskhlaq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gtlagewffy.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtuldxpped.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtjfdgbjlf.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gtesrpvmva.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmijzbtm.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gtkgyrbcmp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gtjhsuuwfd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gtotjwcrgo.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtoynyezyr.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gtjabcbnnu.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtgohtykcx.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtvqcguljk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gtlwfecyqz.html

[U24] Py：路径操作
来源：http://dali.jlsjyb.cn/Article/details/gtwhryqbmy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtzzteyxku.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtvgdycgeo.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtlrtiiovz.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gtlkqfcdxx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gtwlextjza.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gtnurvpiyr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gtypzdnigv.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtmajgsugx.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtoayqtzpa.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gtholmgjgu.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gtiuvvmzfp.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtgfgqtztt.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gtcumbznav.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gtyfsuhgzb.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gtyzgrcpzx.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gtktprarjq.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gtbgchgegz.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gtefzhekpx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gtkxcqotll.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtwegsccog.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gtpjpkdinu.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtrnkyglgr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtvmuevvus.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtjdzyhiqd.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtrsddiujk.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtcrnzuuxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gtmuyajhwt.html

[U38] Py：获取脚本所在目录
来源：http://dali.aibaodan.cn/Article/details/gthxghzkpc.html

Path(__file__).resolve().parent
来源：http://dali.vqdsnc.cn/Article/details/gtjdsjgoxm.html


<!-- 参考信息 -->