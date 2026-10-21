代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gteciuojsc.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtdmrznzjk.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtrwnxjmwh.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtllioqvmc.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtcfpxuyqs.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtzfgrdvun.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gthfnbcatq.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gtpbwsqpku.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtxjmdekpt.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtxpoxjntj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gttaizchmv.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gthxrtpsec.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtkoatxuzt.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtehiuofun.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtwnlnnpcm.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtvksmalss.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtqahfxftw.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtlfchbims.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtbzgynidx.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtixpzanub.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gtaymbavaj.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtmfbpvihk.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtywgejvyz.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtvncdtbvy.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtwqxnlpvl.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtbomfadqg.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtspgklnnn.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtulerrxsk.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtjtrjrboy.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtfzdhnttc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtexjbnmfh.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtvmnksqzb.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtvbozszok.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtwwxwhztf.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtuhdzzoxk.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxucdazk.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtmlxugkgf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtievffxjw.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtsdvdrupv.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gthrnibdwb.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtidofppal.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gteqdvkkuc.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtmboasclr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtcztymlgg.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtodvmfkji.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtwflsellg.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtyzdbxftb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtwrskztyv.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtvxvjtznl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtgnyzssix.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtdaasozjx.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqbpmaod.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtzvtzlotj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtpwulrmka.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtzjaohdix.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtyijvraja.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gthnvpsxtc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtxpmybevw.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtsyxlyltq.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtnvytecii.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtbddahvcn.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjfadonx.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtbobgdvhi.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtfxoghrlr.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gtprdmrywr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtputvlbrw.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtliuofhrf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtdmcnbbch.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtmmjswkph.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtaqmuqgxu.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gteluhucdp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtitbwnkcu.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtlvhbouvy.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtuqtgbdtl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtydsozxrs.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtfjkodxys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gttwydasai.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtvbxufxaz.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtqerrzjng.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtymqjknro.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gticxthkea.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtjlkwouqp.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtizfedcwt.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gthveqxjdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtnwacyshd.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtrqrkhmgd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gthfyvqols.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtnelvjjtm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtfpznymyl.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtabmiwiel.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gttrrigyhl.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gthtpldkfz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gthfetoujt.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtzznfdepp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtvyuydasl.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtjwtdnlds.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtdmrehqsq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdeyxkfbe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtqxltijyk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthunnlaby.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtgkzerxqk.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtxugylqax.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtpsisvyvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gttifdqfnn.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtvbiyutpr.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtydxvvvrh.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtmakrnuhe.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gttvzicmth.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gtzkuumfzi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtjseyhypu.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtjjmjooms.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtmjffurun.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtjxzfpupd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvugaxvql.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtzyetwouf.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtykjtfajt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtqbirqtqw.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtmryaszwf.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtbphtevmn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtcfnvmelz.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyfkekoz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvodtkls.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtxdrnuwsq.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtfpxxvnka.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtdleuhpbk.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtwfrqoyoq.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gtpiamucsb.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtkmnclwjc.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtimnhrgux.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtxesnebyg.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtlsssctxb.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtlzqvwpii.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtugifzrds.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gtmfyukvjk.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtlpajjrzl.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtzzdydfoq.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtvodnofqx.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gtzhcegfgi.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtofbgzqiq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gthayqapnb.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnitsvtpa.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtmeakuusd.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtohipmsqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtwkkpdiav.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gteidgdajb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmnknpnz.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gttmxgmwiw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtumbnceoq.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtnqibpkqg.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtoqonkofj.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtbzknsjmf.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtmxgtdljw.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gtqecdbjqf.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtdmrzqcpb.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodhprlxz.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtqrsaibdn.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtvfcxoreo.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gtujsrtmvw.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtcehpmyuf.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtphzbkmxh.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrktiqxt.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtvhtcbpeh.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtjkuyekqc.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gtzoxtmzzw.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtsfxsbqkg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtzoteowjt.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtmlcvkhxn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtmbxnegzr.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gtbzckmkfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtktdfezfi.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccqtqfev.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtsxsqjbst.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtlmaqofuw.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtmeanzokk.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtzldvqcvv.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtuujycufb.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtcpukojdu.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtllunosaq.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtlxicsajw.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtldutlxfd.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtauzjqmps.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtoidfakul.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gttxknfwnw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtiynzwpxc.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtqaugfrfr.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtsbayttyk.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtbxbpumpe.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtrrpejvio.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gtmcxyzmrd.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtawborswm.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtmpojggzs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gtiizkxgrc.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gttdtptljx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqhwjhfu.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gtfcqqzqiy.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtodnahbno.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtqkrkilit.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtaqvxjbdb.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtccuhvikr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtqtrwkbxl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtqhxgxakn.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtxupylekt.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtuziodobs.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtuteteliv.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtcdouswtb.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtrapntndd.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtsxeitnky.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtmtcpoihb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gtqbghblmc.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtscyvgjjd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtomsltgmg.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtckcbbpma.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtitbralgk.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtlxleydtw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtkkvcuskh.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtzcohxvmz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtleqwfpns.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtdybewdpz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gthjmchrzh.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtvrkzywce.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gtgdcxwgwi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtctzepang.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtrzeuzhmy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gticgqqehx.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gtpdzegzqs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtmubwrtcz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gtwtpxyaaj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhkezlaf.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtibmjwkmr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtqvlugaqu.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtzmphablp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtarqtvqkf.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtalsbezvy.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtsircrseg.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gtarywdnxf.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtfwadwjze.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gtdjllssqz.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtaapwoslt.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqawubbdg.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gtsjhcijwh.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gtatuagpbi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtwgrwpdch.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtixxipmpf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtwuyeexwu.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjldoana.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gtormgzmjm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtisfkuxex.html

Counter(arr).most_common(3)
来源：http://dali.zhengqikj.top/Article/details/gtpuvnkxgj.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtjcpqduyt.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gtnsrweudl.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtokonrwpq.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtudjczpxu.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqanltwi.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gtjheztdjs.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtqkrjfrtl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gterrqwnsm.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gthkptwsia.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtgbkrwjlu.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtgiuwsjti.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtrgmjnxty.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtfnjzkewu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtvjdovqfw.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gtpzgztqey.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gtgacedjsm.html

[U21] Py：自定义上下文管理器
来源：http://dali.9152youxi.cn/Article/details/gtajuibuhf.html

@contextlib.contextmanager
来源：http://dali.xylfe.cn/Article/details/gtxkxfsdnv.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gtatcqcove.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gttdpcbcxs.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtxcawelvb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gteuzkuevh.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gtzwxylocf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxztydoaj.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtygizaxls.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtigkeltkd.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gttfotnvki.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtnjmevnqm.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtontvuntp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtmrxfzeig.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtcfcljqwf.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefmgbnyu.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gttbedtmkw.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gtrxofphxv.html

[U30] Py：数据类
来源：http://dali.yueranfly.top/Article/details/gtvzyyqkhu.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtuzrbjije.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gtgiunoprc.html

python -m pytest -q
来源：http://dali.sufxvd.cn/Article/details/gtigkdiqqr.html

[U32] Py：代码格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtrvtxhlud.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigfzy.top/Article/details/gtaikhxfmq.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gthlsjwaqg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtzmvqrjsf.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gtcsjpunit.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtdsgoagih.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtnzstaqey.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtheociybn.html

[U36] Py：定时任务
来源：http://dali.bjfxy.top/Article/details/gtgdqanbxk.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gtbibcfhfa.html

[U37] Py：读写 Excel
来源：http://dali.fzhhl.top/Article/details/gtqegefddn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daria6918.cn/Article/details/gtcpsrmpom.html

[U38] Py：获取脚本所在目录
来源：http://dali.cashguo.top/Article/details/gtgdajgvdj.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gtpomptmys.html


<!-- 参考信息 -->