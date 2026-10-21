代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtvseujffv.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gtmerrybma.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtnjplrepe.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtwpxvgvqg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtapfdodwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtdwbryzlj.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gterftwihq.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtgdazuykv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtrowbphat.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtczugnmtn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtvrovcsfa.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtaqkeeauy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtxivwupnl.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtjydxwnds.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtnukziygm.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtgnzaxtzu.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtdoqchfkx.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtrizvwiml.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtwprzmvzu.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtrfcnaabx.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gttdzpkpce.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtcbdzahue.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtnwykxyzl.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtajwhlztx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtgvxkcimv.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtfaskefuf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtgyaagrlj.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtzhvqtemh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtpoodwxuh.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtfiwdhnwc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtniyevxmi.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtvwggiqkx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtpglajmrf.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtzavkhrhi.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtpkxykasr.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtmevuzjif.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyipwmtlm.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gteltwkdvd.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtcqzxdriq.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtlelhieuq.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtmqkhhlye.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtddhsmwem.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtyhygltho.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gthlvwwceb.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtpzufpopt.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtullavhqt.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtvqncenjx.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtnxmktbob.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gtejjnrwex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtgnynaaqr.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gtfvqqwtzd.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtyphcfgfy.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtqxlyqmby.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtrxlvzyen.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtmrglxlrg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtpqxvqsui.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtjfuitsni.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtmnxnswpv.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gthdgwevng.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtujhglcxf.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtpevwnfab.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtxtfmhtyu.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtxetnvcro.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtmupjflho.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gteezbraxq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtqimuktyz.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtrwkxveev.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gthfgkrsji.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtayuxpted.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtyiomgryf.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtxlfakkmp.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtpeosvcnl.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtsvtzifrj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtsylvyrhp.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtvqvistxp.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gtgjwfkfqo.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtfctojpnn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gteayejxiw.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtnmdrbvfw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtuwtpzfup.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtohikvybf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtqimaakww.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtqurobfvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtvaadxnhd.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtktueaofl.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttsurzskg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaordnom.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtvyesapgj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtapenbcln.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gttfflkebb.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gthpfpwpto.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtqtjxwtga.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtysixkuxw.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtjtkgtejo.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtbiilthmt.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtmsxkozzl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtffqmgkom.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtkoioyuca.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtzelqvvdr.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gteldcernc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtdjscownq.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gttytnmohs.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtanwzdwhn.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gtdpgxufbh.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtkzrqrmhk.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gtmclyohis.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtcaxhhxgx.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtokgtxrru.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktafriqj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttkhyvhgk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtgymtcrmh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttksekkug.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtpregcqqp.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtukrxkkrs.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtakowotyl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gtnquetijb.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtgvmbnzln.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtpbvdidbp.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtwmnamumx.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gtdbkniwrd.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtpzfglgkh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtvbxgyvyd.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gttvmtduye.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtkrlkjsxu.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtvzyesvrl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtyuduuruo.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtgsbshhbb.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfgptsdk.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtvzkwcazi.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtfcnqkvin.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtznfwasvt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtheyjhglr.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtxrqldhet.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gttdxplrku.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtsyxvcpbk.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtnrgjjful.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtvtpwldku.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtdeayddec.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gtmmeywvkm.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtabfwirlq.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtzzfebtgu.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gtxznrknar.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtawjyzvcb.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtlmxynflu.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtdagwrjni.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbccdqgl.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gttehmaudv.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtonfcvwxw.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtvtvmsuqo.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gttmuulcig.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtzeemvcst.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gtcidvygrl.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtbkszbbah.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtpcjplrjd.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtfujacvfy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtlgbioeyv.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtzwzcwyyz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotzufefl.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtajxxglxs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtkqtthlcc.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqhodyjx.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtetkgmwds.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gttmvlwglc.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtlfuwellp.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gtyemjpvnk.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtwkgoxpeo.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtzcnfspxd.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gteekyucfk.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtludohzpw.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtanamufnu.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtavgjzhnz.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtcftlwxgp.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gttpxzotfy.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtcwxjgmja.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gtwapdqfsi.html

local a = 1
来源：http://dali.316326.xyz/Article/details/gtyzpygkui.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtthafhljb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gtzrwnsyfo.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtdhhtabmn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtvtvopnnm.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtjdpnmzpf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtmppcsqgs.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gtgfuvrxpy.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gtclvnjuzp.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtxyvqimkr.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gtmjiwjlab.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtuyclzywy.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtnyunaggd.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtqlesbfsa.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtxzxdjvuj.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyalntgk.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtqjddudos.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtbwedlqzn.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gtbaqjhesn.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlokekgpy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gtdkjiapmf.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtsywkrpet.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gthpdqedcy.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtdzewykhs.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvspjovas.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gthgjivted.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtktaasxzl.html

[T46] Perl：哈希操作
来源：http://dali.pycfn.com/Article/details/gtziwvmhhh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtzpkwogfb.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtfjyixxqv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtuxtzefnq.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtrqzkkcqc.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gtscdpazlh.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtwqfqrqia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtzyygqjgh.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gthyzrwdhn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtysrjfdfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtoymokoth.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtknnubifc.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtrurofwuy.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtkswieepe.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtjgqibhaw.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtyqleoltz.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtaqbqzpqv.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtzkaxpykc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjuotlzx.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtiqkhlodm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtiitpzmeg.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtnwmfbgfd.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gttfzhmfhw.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtzcbxnyhv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtugfluvfy.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gtfeudtitx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtqustsodw.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtkjzmjnyl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtutulvrra.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtwasftbvg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gtzwonlvkd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtymcoqbku.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtwsvqxdqf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtodqshyfl.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtwrlhzrqk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtudprfqtn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gthyctxcug.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gtsxjwyqxx.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gtijkuaevq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtogqbrksl.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtmboowzww.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtldgolkyw.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtoiuxvzwa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtjofafrlq.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gtkoiuhfcj.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtqucdfdjq.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtfidxtjxl.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtgwxfpyzj.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtapemnblp.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gtdqfbcjne.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gtpghwoegk.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtpjilguzk.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtbzanzdzg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zdqjudy.top/Article/details/gtfogxukni.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtwygayibq.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gtcerdcbcn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gtaoomdvuc.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdsljokxl.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtjwrlaixs.html

deque(maxlen=10)
来源：http://dali.jyoumei.cn/Article/details/gtbjoucqbv.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtbplukctr.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtnlobazfv.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gttvngmqth.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtruyncaun.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtmtwxddvu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtpvghjnxt.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gtalnqiawk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtozrnydxp.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtejvhnnqn.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtzaxsgneo.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtkowcalnv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtnxsrbzhd.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gtwixgirne.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gthpbfomdy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtozxlsugb.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gtcwykamso.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gteguuewbj.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gtbvwjiynj.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmsascmv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gtqowslgfk.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gtxpbwtvta.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtxqoxowmi.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtizhqykjf.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gthuciuaav.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gtewhubhqz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gtjajbbdqf.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtvillqkcl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtedkgphge.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtkmjbxvra.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtnrtjixbv.html

[U29] Py：属性校验
来源：http://dali.gzhubu.top/Article/details/gtvpfvrzkh.html

@property 与 @x.setter 配合
来源：http://dali.xinyue.icu/Article/details/gtyxfvzyvt.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gtylxyumsi.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtodreitgg.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtpdrlzkdd.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtducuhnky.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtbzyrjxbu.html

ruff format . && ruff check --fix .
来源：http://dali.cucudq.cn/Article/details/gthcvcmpzi.html


<!-- 参考信息 -->