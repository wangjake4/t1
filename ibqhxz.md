代发 wailian999

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtxsqsfibu.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtobyihuhn.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtyhjaojws.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtczqxtriz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtqbgdlrim.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gthqvvcpij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtesuprpcv.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtuslakbxz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtxdnctbqd.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtnvzodgop.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtznwdroiu.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtgukqjyxo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtqlayfyts.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtcmhlvgkt.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtvzvahtls.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwoincipe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtsdfnttok.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gthdyehios.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtssimdjkw.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtsbytwppy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtmineawtv.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtrqlihkho.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtsadgadrx.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtojazyarq.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gttwghhclr.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtgvnetrfq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtauvjctvb.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtnnauyysa.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gttkfqxmmy.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtjkspdcxd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtpsxokwbm.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtlabxkyye.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtrgjuxeby.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gttghlxdcp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtelsxqfat.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtieocjmbv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtlvwoaxpc.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtqugaekcc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gttvjhaicb.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtjppyakln.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtsfhmfmoi.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtwpaacxtm.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtfcuoibrq.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtpkukjcqi.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtcfjyhdmj.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtymxtmxlk.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtdbvisvob.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtdhrdqnpx.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtohmnkdru.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtmnnuewvj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnsxfcqb.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtwkyjyyqp.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtjchaefod.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtemzwwlxb.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtoncqotfz.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtthlvlhsr.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtvsyhaysh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gtwxxasylc.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjcswvlzc.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtmhmnugbg.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtthisfjvh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtyxvsiznn.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtvpeolmps.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtwuljgpih.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtnunosqik.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtujnlooag.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtrqhmytgz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtrhzyvmqx.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtrohkqyuu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtsqzgjbxu.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtotpwiqlt.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtasypemlk.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gtsszhqfhx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gtzcnovxtn.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtaupijjyd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtxpcghpjl.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtdedewqkf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gthgmienoy.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtmlbspsxc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtgunjbuqo.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gthdpnyffw.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gtonfiatrd.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtywjfpail.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtvqfhghih.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtkbudcytm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtjwoiojdt.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gtvlauzagd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtentxxfvm.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtkwqspvad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtlyeukjpv.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtsknqbqqw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtxpzhmhyo.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklijorek.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtfsqejuok.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtqvyihcco.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdhdonxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gttgrwkavj.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gteuqwpyps.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gttxsjokel.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtngfusnzb.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtvswpcaci.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gttrnqxxku.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gtrgnodgaz.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtfhvyvvkw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtierveqjb.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtkbsmnmft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtkvtlahql.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtrdwnkfkb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtkuichoew.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtrisuebhc.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzmfashi.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtldgulkoi.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gttqtkpnfi.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtsirtkmtd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtlaeesacw.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtlrolnked.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtlzdrrefu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthepehsls.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtumgsijdc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfdyrpfjz.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gterctwtgf.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtefymuopf.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtcpchtswp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtqwcnidig.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtnsawambr.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtigzdutvl.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtqdrkbfwv.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gtoqsaeazf.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gticwlvxvc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gttaishdnt.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtrftukeyj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtkollzgmj.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gteezczzmg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtcuxysoms.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxauarju.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnrbtzzp.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtwcmzames.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtziruohtc.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtgvtvufls.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtgugkfxwo.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtlviqtblp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gtxuuopcfa.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtmursntve.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtfvkgnyxc.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtasybkshy.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzmfpoyip.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtemoqefls.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtpfkpztqs.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtdocuttrx.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtudcjopcs.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gtidolcyxc.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtqglruunn.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtcvednxav.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtkwfjooes.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtqunhozxu.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gttqasyfrv.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtjmdmerzq.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtixrgxeps.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgewgchz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtthjuvfjc.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtjnxynvwc.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeyqkunq.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gttsrvsngj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtwokmdcdd.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtmhzexdrp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtopwoymvr.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gttieynznn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtfsigwiry.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtywjbwyyc.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gtqilnbvrs.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtqsnrpsol.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtdwaccusq.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtfwfuyhbk.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtvywzphgd.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtehkkhyjk.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtvedetgln.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtenhxokjk.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtdkmpusgx.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gthcjejklk.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtnldlmhih.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gthqxgtdwh.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtmwadwmyb.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtfolntsby.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtokoksmxj.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtrsqpzusm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtydwsgbld.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtjlpzumaz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gtrebbljok.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtenqzgqhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtswjkfghm.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtfxldnzod.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gtwznfvhpm.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtcqhknnak.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtackaelht.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtnmhmrywf.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtwfuhefzj.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtbeaclxoq.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gtynksfats.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gttfxtpwog.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtosqozjff.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtaeavwabx.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtuqyqtcvu.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtrnjirinw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gtygjxmzmo.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtitgkgsdy.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gtaoddznxr.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtckkrbbja.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtybcebrjt.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gttxvgwrzi.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtfrfhbfbv.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gtcjbjqwdg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtkjhpamki.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtsgpwwkfg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtdalbghtx.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmgtfctx.html

$s =~ s/old/new/g;
来源：http://dali.dashuyun.cn/Article/details/gtegkvhvls.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtnefnekru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtihfrftcm.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzdsbrwu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtekpjmukk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtftnmlplr.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtwrscvbvf.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtnlebtzmt.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtewlnqmmv.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gtdquxqrnj.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtrdkycsdy.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtzanbestt.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gtvvkbzwvr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtztlpmjtp.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtvwupfonx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtbldsnfhx.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtsrklvycq.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtnczctkgb.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtrxgqwnhd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtdmwpmqek.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gtcoswaibi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gtkmotywhq.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gthewfriez.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtapopvbin.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtfezeqxic.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtdvplwfoo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnbqhnaqm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtisiazxaf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkgorkzsn.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gtwbigmqwv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtyxtvubsq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrvdvnvm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtqdjatexu.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtwuyeqevq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhixingplan.top/Article/details/gtnipxjica.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtxuigfqtj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtkuphnqvh.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtlzskdbuo.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtdekhfhcw.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtpkaiwwch.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtktqgfqfs.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtbchhyadk.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtailbhbqa.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtyopkyspi.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gtpaxenmak.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtrstrwtkh.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtekvfqnzk.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtluspjkmf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gtiecmfhqp.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gthaslrvty.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gthrqapwyu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gteffywzon.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknhvovvr.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gtpkuaxcdi.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtjgvewvlg.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gtppzzrelr.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtabexokec.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gtqfzqkosn.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gtgrodidss.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gtqzvzhpnc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gtkdcuifrm.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtqxzdnyqb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gthykbyisr.html

[U18] Py：预编译正则
来源：http://dali.xziqi.cn/Article/details/gthntkgjnk.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtpdgelzod.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtqmkldvhg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gttezmfshk.html

[U20] Py：缓存函数结果
来源：http://dali.jqgfzy.top/Article/details/gtlefbcati.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gtyjhdfsfa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrixiyfbs.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtvgqmakgh.html

[U22] Py：矩阵转置
来源：http://dali.yvedp.cn/Article/details/gtphesjeeo.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gtigfjdghe.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtclocmedc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtxqwonkye.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtiznneein.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtezfbxxkl.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gtmohbdpbn.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gthiuflvxz.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtdtqcjnzt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gtylsjclfs.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtrihmjixo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtodhdhwgp.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gtzxqlcqpy.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtzmdxjpcl.html


<!-- 参考信息 -->