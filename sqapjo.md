代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujwykbch.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtslhewwlw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtkrnuiyti.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtoigmfirx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtyqiwpgbr.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtgkzxzlyp.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtumfyacyp.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtsqgsvlkg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtyezhmdzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtojabiigu.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtybalwvhp.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtgtftwcaj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtedttqine.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtgwrgqgvp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtmtilhxcw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtowuaniem.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtdrvwmiok.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtbjigcpsq.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtsynnwxst.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtyxnvknss.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtiipithab.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtnltlyowm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtettigcga.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtmjjxvwyc.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtibpguycl.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gtsflbhfae.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtyasllpwl.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gthfmhrlds.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtexvkzdwp.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtbmbcxpbu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gtwrnofhmh.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtbulxobjz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtmgwjqxll.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtauomtsfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtyhvgksfk.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtcnhjljeg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gteekylehz.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gtnmirphdw.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gthrddqwen.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtxfvtdehz.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtcvhjisfe.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtclfafkni.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtocqcqloi.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtbxoccyas.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtykgdojud.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gttwasfaow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gticdkpnid.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtfbfxigne.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtcpyvwkup.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtjnrtzegy.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtfutqpboq.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gttblfsoni.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtqbwmavnz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoklcoskd.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxchjptn.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtthvekrqa.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtzmleqwnz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtsmnfrmin.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtzhhdlmzu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtmvxpuudp.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtguixgflw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtczvnvtci.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtdsshdemc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtftawiqky.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtuxuqelrw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gttxypatdv.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtergbhcjm.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtafdtclbz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtyvxrauzp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykzlnibe.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtrckhqgvh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtnrdyrfhi.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtlgmkuksb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtlcgnsxcm.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtzowperex.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtllzzuwon.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtrrygoqef.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtptoisizl.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtumicntpf.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnijzmsl.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtrvbzpobd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtgpdcxrah.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtnqmttogs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtpdamwhno.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtsrevzbci.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtsuxlhmrs.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtyfczkkbs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtxcrujzig.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtimpjekpo.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtbmacpwsx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtyzjowdru.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtbfdesyda.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzmxtgsn.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtdwpmriyc.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtzggllhoi.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtqqvrzyzq.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzreywcsl.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtasizadfv.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gttcwnwowx.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtcubjliqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtojdywbnl.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtguskcatc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtmihcbiqp.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtwokesiqm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtelnbbtjc.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtxtnbacwa.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtwfpmgtmd.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtffcfpiuq.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtxvybvaeb.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtsxjdaijn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtsffbcttg.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtlznaplrm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtnaocbrzs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqmdhmymc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtnzttmfcf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfbnnkcqm.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbewcdufa.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtxgoykhbi.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtguuooupi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtlmtuykwl.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtitwhnwdn.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtkcwwhjab.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtxblnadlz.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtuhgmbepi.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtgdiggmiy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtphevugct.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtjmjqoizr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtoivujouf.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtkakxrgqf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtktcbbrct.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtpjhcdvvm.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtzqpkvtjd.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtcqehandi.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtniespfni.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtlluyprqz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtpcwruocp.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtiyxnknry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gttqdbpxxs.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheermqmb.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtodotjskx.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtaotdynwz.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkrdfdrss.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gttvjsbjjm.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gtxnktmfyo.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtlrnilhnf.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtxcqfwcnu.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtswhjacxj.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtnswzkeie.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtghaamtvg.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtirmwiofl.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtfqyhbrzy.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtteyycwsw.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gtdoebsnal.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtrilyakjp.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtpfazwncv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gtqlnbezsk.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtghoxijep.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtdxgsjkbx.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtuvdtjywo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtqajlgrkm.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gtgykdccel.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gttgugeuaa.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtagpafetn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gturrkizlu.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtgucjakdy.html

struct P { var x: Int }
来源：http://dali.yueranfly.top/Article/details/gtexhzjgzn.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gtjaqzpwxr.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtgmfcgdsu.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtvktwqrku.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtvgxmqehr.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtoitgpiot.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtcmdullav.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtygobugoe.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtebdbmwui.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtvedficcy.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtcbhpsnoe.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryjobqhh.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtnmdclwco.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtraxswldk.html

local a = 1
来源：http://dali.aibaodan.cn/Article/details/gtamegcdjm.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtemzxcvsi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtjuyknhzn.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtyxxabfog.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtklkoqpyz.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtnogjipny.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtglpdlwov.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtsxerpjau.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtjhrmrsex.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtoipaxtne.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gthtnaflqy.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtdthogucp.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusemcqcc.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtqgrwejbp.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtmossnuxh.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtxmuekfvp.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gttwfmrrtu.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtkxblxsgl.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gtadamwcmf.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtzfqmztiq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtphseipal.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gturclryiw.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtpgpywsma.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtpttzeadb.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtpkkqnahp.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtrhxkocog.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gtudlxbime.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtvxagtsfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gthvaarfxr.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gttlyjeeyg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtlmxlalcx.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gteyrxvrja.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtvnibxlcm.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtfpvuywbv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gthlgkhhhb.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtiptprvti.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gtyuuwhsvt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtfeobvgbm.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtuynuxjry.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtbwgzhzrj.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtncgharwe.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtlefxzwjz.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvebawfxy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtlejiyeah.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gtjhrlcplj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gtlztkanuq.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtgahzbtnd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtvznqiazs.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtdmwtlskd.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtxongiscj.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtggiiheft.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtgysebaac.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtuxlsfsyt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtfbotxzkx.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitxuihao.html

for (i <- 1 to 10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtdgobnzdm.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtwwsnhjvx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtlrjbikai.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsmqbpxkw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gttzsiovlp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnmagndub.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gtqezrtvpn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gtmhlytttn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtadccwppp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gttyvbmmwx.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtpyktgjkb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gtlnxmqaxa.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpsrcevn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gttgnlsofc.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtqomezjvi.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtvcxvmnde.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gtdizuiuvo.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtsnbedwrr.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gtyipumvyf.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtgttqztfa.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gtuiogiomz.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtnollifyy.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtyszkgomr.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtxlggjclb.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gtuvwuvpsg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtcnvtupjo.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtuhaksiah.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtuyfbvqho.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gtycwaxskh.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtzkghmvgr.html

[U13] Py：固定长度队列
来源：http://dali.gaohongyu789.top/Article/details/gtleqbwadf.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtgqyxrxqi.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gticzhvbza.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gtkryrjrsn.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtgqhgqune.html

t = time.perf_counter()
来源：http://dali.gotoacloud.top/Article/details/gtdhwqlvmp.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtwjwmcgpa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gtfjevuvny.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gtgpkjqsqx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtzkltncgb.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gtogdszytu.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtoebqnfoa.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gtpyboepqg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gtqimtythc.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gtxtvgomyg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtpeiycduu.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtpcrohxiv.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtiyxbutot.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gthqbmphsp.html

list(zip(*m))
来源：http://dali.dianchejie.cn/Article/details/gtxccszejn.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtsqkijaqs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gtgcqzrvmn.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtgfuuagof.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtxwmkvwnq.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gtdtydsesp.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gtusyknnkq.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtqsepctuh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gtoaffjpkv.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlmdwxml.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gtoqvctjvz.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtsuburftw.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gttauqjjiv.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gtxjavixat.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzchcaiv.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtfiahavja.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzeehsck.html


<!-- 参考信息 -->