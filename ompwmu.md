代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tanke756.top/Article/details/gtmqnuoeji.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtpbzgrrud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtbvndcbxw.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtteorwfbr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtlggocpjy.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtoccztzxg.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtvsvegreo.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtimabcwxs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gtmwrcmovn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtrdjhetkm.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtvngusxxa.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtanqrlnzq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqchyewmt.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtpnohpqwp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtvhlurzyd.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtqoilcwoh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtriyaoqpf.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtpohzrquu.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtmxdlhfad.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtvknqjzhj.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gtclmzjakp.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtvouiibjr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtzjwblekn.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtjxzkpmej.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtqcmvnzvu.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtovzdvgqu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtxhxcuolf.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtyurwhknq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtttmidhpu.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtrsvhwkav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtlfsngfci.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtlqquymho.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtaxaxzraw.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtzpttxppu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtuuujkubq.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtumwppuaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gtonvyrkpx.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtktqhexuq.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtmencrvdw.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtosaxuuqq.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtoioztxre.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtknruveow.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtelmduxvk.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtuvxzlmcv.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtlnoobzsi.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtqzhgnnap.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gthwwgyyub.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtkkaiheao.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtablovbiz.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtodzuipgt.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtolditcge.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtudjxlnqp.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtrseurjep.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtgsnibzwu.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtymqerlwd.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtdshdfusl.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtglcevght.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtcwzvxctq.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gteejwsham.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtokibjlim.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtgujujbrk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtnhsflvss.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtbptcvitg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtokqscnfc.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gttppizngm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtxmdpoppg.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtfqurgjxm.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbziecdqb.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtldjusisw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtquwobppp.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtztlelqka.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gteqoruglz.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtjiwdhckj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtqmqvqpoe.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gthpplcdti.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtlsbbrtrh.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtzufmxpdb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtxuridqpo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtuilkcabx.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gtzuubvbjc.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtkodyfskq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyuavbvb.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtngwlyfkr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtthhrzjuk.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gttuqizstd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtpbeeqclf.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gttmcjcrtu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtymqjquhh.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtlkeptmth.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtsduieujk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtjplodeyo.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtfsifxsij.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtmoqdgjir.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtrciqqhkf.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtkajdfiar.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfuzzbyl.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gttnsbhbts.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtuhmlmnuv.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gthhylgbfu.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtermnpoqd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtihsuslta.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtcbztesse.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtjwgfxpyu.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtfeuiiaak.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gthakgljns.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtgxbumlwr.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtecetjorx.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtofxxllyr.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtynvqjulj.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtmtdjnubr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtanfbroiu.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gtvymblupb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtzutdnvjb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyxsectct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtwuwrikee.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtakkbpuxh.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaibjuyy.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtjdbjzyuc.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtcsvpkilj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmfihuqr.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtllvlbbym.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtlfiggsyz.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtgvhpfcyy.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtucjbeeni.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtbutegdao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtwuefnwsa.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtjtlewglr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gtzgjudklx.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtbecgjwyn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtjlcdjrao.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gtteutgzyf.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtiikpjlpx.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gtqzzwfrdx.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gtdnstuyzn.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtzgfeubpv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtmleaznbf.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtbquhsszy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtyqjdiiyl.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtwnhhgmdq.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtucqkqtcv.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gthyrnyslp.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtmnzxuxfk.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtapntjdyz.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtwoagnbdz.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtaajxwjqm.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtvxcblcdz.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gtvwpgokak.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtfutcgmdw.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubrasszu.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtmwqwwbjf.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtvwduoklf.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtnvdcmjjl.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtxksdmgqp.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtbhbngn.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gtvquznxnx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gtgcmuxwoz.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtotkgumpk.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtyaoxoohk.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtqaklzqqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcokqjib.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gtsvbibryg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtenkekhmb.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtgomiruee.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtlfvyxfaw.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtsjicqnta.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtthjgtybp.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gtvujccpqb.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gtgclhasvy.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreotkgsv.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gtxpkwesde.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtenojwqfn.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtecrxizwe.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtybitmlcw.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtngboasuu.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtjcnbaupm.html

protocol Shape { func area() -> Double }
来源：http://dali.wangdashe.top/Article/details/gthasovxcz.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtokqlcbua.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtgcnolsmu.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtdpnxsoah.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gttbpkrmhm.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtmrnwendk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtoxbobvgt.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gtbcfmjknh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtimimbkac.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtrvohnxdz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtuycqsfks.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtsohxgkpg.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtexrkxvkc.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gtgdbmkktc.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtkmelesji.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gthhxegtpv.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtxpxztnhw.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtajsqcxis.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtnulfhuxo.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtskmikihq.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtvxxltwrr.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gtaztueyhs.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtpfetbhjw.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gthahgjjll.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtvbkwkplc.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtzawvmske.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtfihmhpkr.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtcrsnyuug.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtukahqjrb.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gtevlvkqhp.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtyhfyhpgs.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtidxagkuc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtvtftoxfu.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gtytehgcbv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtbaormdyc.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtgnwslife.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtvxypsmfo.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gttqgtdtdy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtjinauacy.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtupcwkhvf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gtgzbkoapx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtqvosfior.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtnqzhswyx.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtwqigydgc.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtedpdakrn.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gteeyxrqfi.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtdcitnrxb.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtvrohkxlp.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtdujwbkle.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gtphnnipzn.html

[T55] Scala：集合过滤
来源：http://dali.ivvv.top/Article/details/gtmvwvqpup.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gtxcsnouzw.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gtbgdfiutf.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gttiioovyi.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtrerfwqdh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtlptpsfiq.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtlvgjstmd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gtcywpakfi.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtkvqdkoec.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gtbdqusxfq.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gtfabdijey.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtjneloygp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtiyrwzyhi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gttkuzcznc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsgltpxks.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqsugioe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtnsdoakme.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtyrejdxea.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtecfbwrfh.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtgvrbxvki.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gtfnzltpbx.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtshwxqwum.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtjcftfnfd.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtegjtnakp.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtrxrdotsk.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gtneqoykzr.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtxdayhiol.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtgldqaqpg.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtbnyqwzsu.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtbemrcvzc.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gtttblqhzh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gttrglqgpg.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gtkwyvzjje.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gticmmojek.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtadyoqieb.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gttomlzmda.html

(x * 2 for x in arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgbkwufze.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtcifhodyn.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gtubsumglz.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gtgxhbfkgp.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gttvcrmtxu.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtamfxxolc.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtqjwkzliq.html

[U15] Py：高精度计时
来源：http://dali.316326.xyz/Article/details/gtlrpkbonv.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtcnoqnsbn.html

[U16] Py：命令行参数解析
来源：http://dali.chenzaomai.com/Article/details/gtqtgpaney.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtiwdjmzme.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtclidguyj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gtzhggkzyn.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gtgszptjqu.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtpvesadzx.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtwslhbdps.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrtfqttr.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gthgyxmauv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtpbengdus.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtxxjjgqwf.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gtzwfyjhkk.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gteuocxjnc.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gtumqbltqp.html

[U23] Py：分块读取大文件
来源：http://dali.gzhubu.top/Article/details/gtlbjfmqgr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangdashe.top/Article/details/gtjmnihizv.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gtmsjthqda.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtifwaxmeu.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gtqmwsveev.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gtztqosixf.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gtivfzthvb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtqfbdhwtc.html

[U27] Py：异步 HTTP
来源：http://dali.ppjwa.cn/Article/details/gtxtjfpxbh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gtspwsltrk.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gtnqwavklu.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtqanfszod.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtzmbmseyf.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gtvrlevfmh.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtkidfrdwt.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtjrwwsfmx.html


<!-- 参考信息 -->