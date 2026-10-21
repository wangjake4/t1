代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtcqsibayw.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtkeszqzmu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtpdjfcykm.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gtjglwwupo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtinucxbgc.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtrspknxqt.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gthxiyrzyu.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gttoomkwsi.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtcohbyuvs.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtwhhahtbr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtdjjwpdwf.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtynverluu.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gtlrzslngj.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtamqdozjc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtjpjarczn.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gthhgkfghw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtesnpgrtv.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtlpztrdud.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtzqoxpjjw.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtgcgxglgp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtgspwhyxl.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtewiteckp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtpnmlnplb.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtkutfswuz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtswuazeke.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtpglznxtx.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtjlnrzicy.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtxkkldemc.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjmzokxo.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtesdqyoyw.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtehacqsuf.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtqcrmxwzo.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtlhdjiubx.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtaaxllzjp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtvglbgqvc.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtvvrhlnxh.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtuqxlaxgs.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtlrgmqshy.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtjhgpwukf.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtkkvkgdxr.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtplgoweym.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtuijcepls.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtowutwbby.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtorjzzffv.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtgeqijzsa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxusukdff.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtklmxuvjr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbytzxrdi.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtjhgpgicv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtitqgxjwl.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtchgcttvn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtpskfrqpn.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtafzvczpf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gthxufpirh.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtzdlmlyju.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtbjjefmce.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtpioybwuq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtirmyivem.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtxbghgbfl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtyrkcejol.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtrobzvixg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gthlgvgvif.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtehlkzgci.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtgrxqkzqv.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtujeffhlj.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtrtpozstr.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtrdkmkhtl.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtrfqurjma.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtihhncygx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtnzdxcvsq.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtzdrvdtfk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtxsdvjoqi.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtkfhqqjjy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtqzxtlpcp.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtnasyrtvh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gtjhmxwjzp.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtznzpsegk.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdznpbcvy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtsirlhena.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtohzsvdao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtqtytyaif.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtpthrcrnw.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtccbxabtp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtffpvksdw.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gthhxjawfl.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtomwaxjus.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtzmdbxbxd.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtvlsdhmhs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtwchvslvf.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gthjcrhrdp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtjyfelcns.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtpvlefnhy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtavvaturb.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtyhnhsnpg.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtmdourana.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnnzgfpf.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtzdzguucd.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtnhmyefnv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gthhmtrfwp.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtdisxkhra.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtfhxfryyd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrojyahis.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtmevnvjuu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqrimedva.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtumxiayfj.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtniesgbpu.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtlehtrfia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtdldezjun.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhfaktuw.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtkexedesa.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtudyxzofv.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtlcjdkyyz.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gtupjgaylb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtnrfnbjoz.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtfxuqeydu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtyzmdvocy.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtvnwkvuha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtjrjdmxko.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtbehpzvjp.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gthqyeoaln.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtsxmqtjtf.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtchdrfhxo.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtbvbeqqgf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtjqkyylcm.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtmdkpihhi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtxkvfnxix.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtpmhohmhu.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtgshrdxbo.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtrpoqjbyh.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtfoooatuv.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtodjugrdh.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtckuqnvbr.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gtvvlbytnx.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniiujjem.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtowssrirk.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtrlrvurbp.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtsnpqjjmq.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzghurkwk.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtednqmkfc.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtyexscflf.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtlhzxbafy.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtonnscokh.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtawintpyz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtlxydrvvt.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtbenbfahy.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gtamtmzcfe.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtyxubidyp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtspczcbaq.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtachfeyye.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtpeoqzcuy.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gtxfwqgzey.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtgtpbsuzi.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtjwbdfvgy.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtumwokndn.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtgnvwhyfh.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtrbinrbvp.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtmbeviiqn.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gtrfgrefba.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtzymdjhzr.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtkxnbtzaq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtycmuzofu.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtjycexkxf.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtrhdamxys.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gthqxnhkso.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gtyatccrvm.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtsckswxzv.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtuhjwwiuc.html

local a = 1
来源：http://dali.aibaodan.cn/Article/details/gtjnfyzzok.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtpfhssjry.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gtqevkdwxk.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gthnovrfok.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtzybedtgo.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtyilghepc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtxbceldil.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gttgtsyhob.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtcgtvxsnz.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnyyzvue.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gtlfahhyns.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtzezkbnlh.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtritflqdj.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtqdbeutpm.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtyqzhfsgv.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gtgbkcukbi.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtreqxlych.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtczwyflbz.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtbtjzvzxk.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gtnoaoixsn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtdtxzqvrh.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gteqmhpoff.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gtdjsbxkxs.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtesltsazm.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeswvpfr.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gthequqozd.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gtujjtnmfw.html

[T46] Perl：哈希操作
来源：http://dali.gzhubu.top/Article/details/gtqqtxhxup.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtmmlrqdde.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gtmscolifq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtirtbpifa.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtgrzzavok.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtqoomzriz.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgbjvzjol.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtldkaxbiv.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtutrvfnum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtqamyzvgf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtorefkodr.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtuhfezaxi.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjvtdeku.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gtdpkarnhg.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtnntlzmso.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gttohbkffc.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtrnqdqocp.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtktigktsq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gtlcbwyrpu.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmsxbhew.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtavkrqxop.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtwqunmmfh.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtfhgtlotj.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtrmluwvxi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtowwtvaso.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gttwgysvxi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlienvcwv.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtttsjqxbi.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtuhgfcapu.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gtngmyreyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtstvebjdq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnzmttxxq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gthsoshacf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtejnwvqhk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtxgxnltis.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtnuhzndju.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtkjcrogri.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyfyxdhr.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtziurqjxs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxfbuhfe.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtbupoqjog.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtgcejjnhj.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtsykkeuoo.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtcciqemho.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gtpdwpquuz.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtliixpvzy.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtsyuoslxb.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtodrjfxpu.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gttirltqkt.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtxvwkuqyt.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gtpzjwzizs.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gtpekuoytj.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtdssbuipj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtactjzvpt.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtatnrnlbt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtvcfrutvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtabcftqmm.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtbqiutqoi.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gtcstdsiur.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gtixmlqoam.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gttsrbjvia.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtyejqtwjx.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gtramltwgk.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtjbbowimz.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtbqvzzqon.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gtpidsggdn.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtyloxkcua.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtdoxezxko.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtfinfgvgv.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtbwxqupqk.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtaefxrgzf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gtxmbnlrew.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gtxgqqgaae.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gttvmwfhiy.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gtvjeabdod.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtdluahsjo.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gtbhrsvoys.html

list(zip(*m))
来源：http://dali.fzhhl.top/Article/details/gtnvvitequ.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtpgswsnhx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gtwxoyvqkz.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtusxdqqte.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gttzuqbyrh.html

[U25] Py：CSV 按字典读
来源：http://dali.ehwqpu.com/Article/details/gtsjublrcb.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtnxdstmfu.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gtdunupuez.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccvjxwap.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gtuwtdwmdp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gtkwthdnwj.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gtoczkhdgx.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtsliowfjl.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtnnzxdgov.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykwjzffy.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjkstcqz.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpzaxxvj.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtzavsczyo.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gtbpxcjwld.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gthotoywgl.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtnaxgklkb.html

[U33] Py：打包发布
来源：http://dali.aibaodan.cn/Article/details/gtzgjrweaa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gtglhfqpir.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gttreekkji.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtkjtjbrrl.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtzwgqjdzb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gtumlobihu.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtronhiifk.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gtxjvjjkwf.html


<!-- 参考信息 -->