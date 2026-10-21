代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtcvauxcdy.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtqejbwvxe.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gtyfnqlkfj.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtynmoszup.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtisqqmfvi.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtaelkjsrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtohaopkll.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtoziqwhxk.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtwhgkieki.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtojimsfgm.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtmlruiftw.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtpibevhsr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtxocnarjs.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtlvvfzqwc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtpqfjhogj.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtnbmhvqnt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtnetbwbtj.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gteekhdodg.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtmzedgiph.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtdlepwisa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtkovgvsrd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtsbmmnaot.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtrzlbzgjs.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtzqukvpei.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtbfeawiiw.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gttzbzzjzo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtybinjorm.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtyxyurmiw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtcaaonfaa.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gttslpjppr.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gthijkeypt.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtysiewajc.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvogulsis.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtoyllzljd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtivicyyrd.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtltzfookg.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtditmddfj.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gturqmkvda.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtcmzbfyrg.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtxhbnvzdc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gthiiqmptx.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtlrdoioyd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtxeaifeff.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjyabqvs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtupcmhgnh.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtdcjjlsun.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtnndbuihl.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabgdyqri.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppuwvpuk.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtidllvhcg.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtwjejkaeh.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtplrwevnn.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmzhkgfj.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtrbbximqf.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtjgflzipe.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtbigefiug.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtdntgkdoy.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtlqpyhxlc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtdnascgln.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtdipcscxn.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gthjbiimgw.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtkxzvovze.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtjxnbglwe.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtefkpndcb.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtlufrxkns.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtagrylbus.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtezkfdlts.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gttpfsladx.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtoucktdlo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gteoirsbiy.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtqhkxazbh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtatfdanpo.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtszhfaddk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gteqbjbmyp.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtzlogozss.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtpyqqmmwr.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtyqxgrpvl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtrijslccz.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtuoksazws.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtyenmragj.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtvsxgwaaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtwejjqvph.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtdyeoqsln.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtfkixmmjv.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtetfmiqin.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gttonhbsyh.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtehgxqyat.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtdlrmwcty.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtedaprzus.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetigbzzh.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblostrzj.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtfgwpzdvq.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtsbkmbrjv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gthhoqstkj.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtesavlyme.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtvxyqyffz.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtoswggvok.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtpeanfjrb.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtpqfhyvvt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtjkrddrgc.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtrrgxsmxg.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtbgknnhiz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtmzdvuvsi.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtjcagyojx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtnlsgqpda.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtlctvcndw.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtrsuhkkdq.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtwkdznyvr.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtjjufirav.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtdzorrcqb.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtrtspbywn.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtvdijuitr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gtbufxtmba.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gthvfzknbf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gtsvvtbsui.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtufcmbkmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtbwuzznne.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gttfjsyjqj.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtxvwpbpav.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtfnexvtxi.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzybmvbcp.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtaublqzqf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtedudafme.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtzvdwqfbu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtigiodkxn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnvnrfkkx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtcqmgyyhv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwcslolub.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtrodpxjid.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtzztihvsn.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtjkwvdpwx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtarpioran.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtjikhhjwk.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtqtqpscyz.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtocbzazov.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtppmcembe.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gtoclpssea.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gtyfafwgfo.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtffzwggfu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gticoodnxo.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtzvjpciqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtnydgiriz.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtziozcgbz.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtrqdosgwc.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gtvnoxyhxv.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtbkmniapx.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtzmqputhw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtrbdkguju.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtbfgrlyjb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtfvnmynmw.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtcshkiaqg.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtjjjnnxsm.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtxnsyjuto.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtiaruponn.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtychfhfif.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtsowjyzvb.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtpwetqzvx.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtjjvlpocy.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gteuexprde.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtrzsstvcw.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtouvxyumt.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtrtusxiea.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtopaoqcrm.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtynyuodao.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtachmvpwa.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtwrylejqn.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtcjleucda.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gthdznmqan.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtaxnumbfd.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtfclnzwcr.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gtequymagc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtofauowsu.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtzszkjjbu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtdkruxrvz.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtogtxfstb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtmqfjdycf.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtcgwxjier.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtofsanhze.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtsapljdwu.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiilalwmp.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtjlbjjvxx.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtanwfmyiv.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtqyufemuw.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtotqdpoua.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gttabtproa.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtepvzrwsm.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtpsgafblj.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtwvjrjxxn.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtqxkcxasl.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtreqwmlbg.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtpaejaddb.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtsfpcixml.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtoaqfftla.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gtpbjmpzbi.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gtlzkvrios.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtjyoywtxj.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtnevlsopl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gtpppbeeaw.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gtrilmyetq.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtzepreqqq.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtasfrhkhp.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gtffsciwun.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gtlfafsmfd.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtqmcnteon.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gthbzftgow.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtmhxzedgc.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtmyvmugju.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gttlokfujs.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtenjfgwkr.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtnzrbpjhe.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtnwovsnkp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtgvvwyffq.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtcnulmohb.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtjhydtvyv.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtqgqavrgu.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbnrdjcbm.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtyyjxqnwp.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtojfxekjr.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqmpqfxc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtsjetyrdw.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gthizpdbmd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoshwnbcp.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtqwjlugjw.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtxkbpmvav.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtgzkwmqmw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtundziykw.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtqyhnfmzw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtfpuzdwik.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtkuokpelm.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtswlaumta.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtrhdxlqhx.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtjgbgttkb.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtvkqxhsyb.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtbamxqlxg.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtczpktfdp.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtiujzwdla.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqbnoqfv.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtfqutwdue.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtgniicsuf.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gtdgxjooag.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtvirjhfko.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtgyebwxgi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqhhoerx.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gtxorkkstz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtpgthdvva.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtxlrajyft.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtlrogbjyl.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtntrzztec.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gthtcagqop.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznhnlmzn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtqyvprsly.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtigbvkydd.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtggzhulza.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtigyukipc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gtjxmuqyoz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gtjrincnok.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gttlqebshe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gtiggezpir.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtbwpmrfwb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtykorhpoi.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtlpepwobm.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtrdgkdbqt.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtdgsvbjwu.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtkdafajfy.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtywymmbws.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtrprclxui.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtltegiwmu.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtrvrwcfhz.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gtajisbsat.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gteyildpxr.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtlvchkquj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gthqynweln.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtuteyjycu.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkfumwbx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtzsaahdve.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtllxwmzrf.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtigbcbfsr.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gtsyxpexoi.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gtwhmqlqod.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtmpbdzzjz.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtjwdxqxfa.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtaktmwwex.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtpwdnqvcv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthystpkbv.html

[U17] Py：初始化日志
来源：http://dali.yj20258888.top/Article/details/gtlnnsvcjt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtcptczsej.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtgycqchkl.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtklyoxajz.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtzyxoabna.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtzdrngnuq.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gtxlhdsbii.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtzcbxwjyw.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtpxgeusca.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gttctjszaj.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtymwpmbvz.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtzrwzjkoq.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtnqejmabp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gtlvuptwrw.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gtizqxvnjo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtbcggyhvf.html


<!-- 参考信息 -->