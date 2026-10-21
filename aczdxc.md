代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtqtwhuaqj.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtdbrdiffx.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtqjkvuflv.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtoemtkwyy.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtaybjvrfu.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtiqzturxj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtxpleyzto.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtuzvintck.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtsgvmubpc.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtwyeliujw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtyojxpryy.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gthiklyaeq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtvtrppecl.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtopttsolt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtoxitkewp.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gthpezcixo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gttjegjeti.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gthcyrwmrs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtqzdvqbki.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtxjxucxdo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gtjnbmmbgv.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtpavgqplw.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gteuicomua.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gteayqeiih.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtnzencofy.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtcykrhtqt.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtyzvsztfx.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrepzmji.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtpdssbrzx.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gtpzkvbjgl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtvkhxflbz.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrghoqzkr.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gttcqracyb.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtwibmnwje.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtkftzzdlb.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtjxcopnqz.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtegnelkqf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gttasklkyz.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtfgorpffq.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtapchtsde.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtummpplix.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtnzokutrv.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtjvddcbjo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gttmrckdtq.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gttqizibym.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtvgbkfggh.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtpqpgbnvf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtbembqwhu.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtgjxtlysv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gtakfzvicz.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtzqdzinry.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtmalajoog.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttynqttdo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtxmawpxna.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtkgfqbtdf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtuzgymykj.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtlumhlsat.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtzmwpdccz.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtvcmroqft.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gthgsmjssh.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtkrelmduq.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtcbhhvicu.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtvohoimsq.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtkzbawlam.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtxnobbpgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtbmfhbpvf.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtzevyvnky.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtvuyiokbb.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtowhfvoax.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtecujrlcq.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtrlpletxe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtesqbongz.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gthmqnfasr.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtbkykkcmo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtwuqqghlj.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gteusdkmzk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtnzoxeq.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtflrkgess.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtjqggvict.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtowtkopmm.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gtrhcoupab.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtwxdrlbcn.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtycvpxoam.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtsbwoojgz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtuxposwlf.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtybxfassq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gteoouizci.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gttelwzwpi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtmhzewegp.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtjivuducm.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtpqoqbjni.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtdciqzgeh.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gthbmrazjo.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtzrsmthcw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gtsnjjgyoj.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gtmvozjoox.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtjkjsgxal.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsxvqzrfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtwokowrgp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtoattnpas.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtatwsvqus.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtbavrloxk.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gttxcgqqka.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtapwurcgw.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdjemhvp.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtwpfgpxwx.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtqwtzlvwo.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtmqdcklwr.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtfhkowmfb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtffypklxa.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtrahmqcrs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtlfueewei.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtwwbbtqed.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtckkhwggb.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtiovswwxt.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtdtwfsdzt.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtgejlfxyk.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtduhunkau.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtdjzyafva.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtyyhgkqok.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gtbzwapkry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtokgtcadc.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtcbpumhoh.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtdgifrzus.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtgvxnqzbb.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjegbwrke.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtkyecaiqy.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtdyrpfkrb.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtegthgjip.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gthziffavv.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtmbkjladv.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtgdrpglgs.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtuirqemjz.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtbtjvgoje.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtpcwbyblr.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gtqsgxdlea.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gteozhstsy.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmcbroxr.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gtzzzajyld.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtxbfxdkkt.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtnlgpjfqf.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gteaffhqxm.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtcepllyzs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtneihnchj.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtzpqqgmtp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtpzybvuux.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtnzlhiblk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtdmobthkh.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gtqrnfevuz.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpioqfhs.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtmursexnu.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtraxzknvr.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtxawzhqlx.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxpykizb.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtjzlchdsg.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfzyoewj.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gthgbtcrgc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtgmxegutu.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtqzhumfte.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtyaiqcfpa.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gttwlvnvlc.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtivypioyy.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtgphpxuto.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtxypnpqbl.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gtnoeipkqm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvwlfvxy.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtxkvizton.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gttroprqok.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtuueirzjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmecawnf.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtkriznjcw.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtfszbgxoz.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gteympclht.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtuexwdybc.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gtfarcyehv.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtdbvrooym.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtlqcuzeaz.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtnvegmwaq.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtmtegfwib.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtzyzqypib.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtahsyhtoa.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gtsenzxyhs.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtawfqknnw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtlfztwtak.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtfrjbbova.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtjbzqcimn.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gtcmtbwmzh.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gtdmrbgara.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gteyfyazri.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gthjvdvslq.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfukjbbdw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtcfrddtbu.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxndvfctm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gtloribgzb.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gtrmsygbmo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtaaqamnyw.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gtifbklbhj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gttfkitont.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtypznhyaz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtchlmrsxe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtlavjsaom.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihbpnsdp.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtgybplewo.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gticmpezwk.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gtsvjjqmhd.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgwucfgq.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtsuawtoch.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtnkncdwqa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gtysfzqnru.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtkszrjerh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtfllcsjsx.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtjdjrddfy.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtatlgeyqt.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtrwihzhvy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtwafsuxtr.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gttxwbwcje.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtddorvtlf.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gtmieuhmhg.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtbymrtixw.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtgoiuhfdy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtnjcmsxqr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtntmmwvid.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwsklkcb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqqoejpjx.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtcflhjxyb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtndskihqx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtgwonyjcp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtqchveqli.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtsmgtvegi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtpsxxejtz.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtubujuylg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gtudzaicap.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtydxfiolr.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtfxbudycw.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtdtlmkpuw.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtuqyuztjw.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtclggzpmd.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtbpojjcjj.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtbluakapw.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtycvzwifg.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtvrfzyihc.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtzvyalbbo.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtdbeiikrt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gtqarsbizp.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gtxgkkimsu.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gtemztdekl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gthvdfyfhh.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtfzgfynow.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gttcfsdqvl.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtxksrxszh.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gticwpjzsk.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtiojipdga.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gtcbpuhkwt.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtslxxzojn.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtqaderyen.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gttxuvnkzp.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtaytwatob.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtlenxqtiq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtrupluwac.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gthuciynio.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gtnzllksca.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtqndflarx.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtofcdlmls.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gtxfvngkqz.html

[U21] Py：自定义上下文管理器
来源：http://dali.xylfe.cn/Article/details/gtjrtekrxr.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gtzdnxbzyi.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtfpnjnjrh.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gtpwqgsxeq.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtmosozqvm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtsjhcfzwh.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtucibiqqh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtdyvogzzq.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gtgafqegmy.html

csv.DictReader(f)
来源：http://dali.tanke756.top/Article/details/gtytmwazdp.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtisatzyoo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gtrgeaoxdq.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtzcuvtffm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258.top/Article/details/gtlosinshg.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gtraieiqpb.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogwcrjgp.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtmhqlzarw.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gtfprywosp.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gtpuqquwql.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gtojvannyg.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtdgzvqmfw.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtzneyarmn.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gtdsedornp.html

ruff format . && ruff check --fix .
来源：http://dali.yuanzhike.top/Article/details/gtwqnagqah.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjrwclle.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtxzfrgtlw.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtbggiiimt.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtcihqbsrh.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtzrwusdyy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xylfe.cn/Article/details/gtinguxrdj.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gttxpwfdvi.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtkhznwyin.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gthfxxjiup.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtbpdsofoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtpvavwnog.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gttxpolhga.html


<!-- 参考信息 -->