代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtbgxgqegk.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtusluotjj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtusevtxnd.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtdlvgghcp.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtnftsdxwd.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtfjnzyyfu.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtowjujbtc.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtgripfhfg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtibgjcmvb.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtywcupflv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gtagchpidz.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtgdzeamqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtawjpxbmf.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtezqsjzdk.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtrokstikz.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtrfcevlvs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gtfliidyri.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtnilkxyxv.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtgylrqesa.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtczkruero.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtrntiajxb.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtgjlscvdv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gthhulamlw.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtdahxruao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtravaimag.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtvzfaemoi.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpfjmdbe.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtftzbnmqc.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtdmhkxbjp.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtezirawfj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtdwykovyt.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtcayknipv.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtuwrjoeyo.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gtdwqvhgzh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivacqpgm.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtjbgnizja.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtckkyurpp.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtuzgkrmya.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtozqgkdvk.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtmnlyrefx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtblvitvkg.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtfzdzjqve.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gttgqytwzd.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtbdphvsvx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtdwxmxqgk.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtoiljmfuy.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtcquxpjly.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtsnnefvbz.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtjemycqnc.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtfrfwvblh.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtmahdqllf.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtmqzdmmvv.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtrawsavuz.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtpxrbpdwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtbxyfsfmw.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gthqabvzxp.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtjdvkheqs.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtyznpfmhi.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtgoibgxcc.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtfafijrxn.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtoxusjcwa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtqbjvklqk.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtesxyqfng.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtdoantnlg.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtsnswikae.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gttvfcznlv.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtgdetdqev.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtzmlwzwox.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gttbheylxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtypkymuxj.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtlxvrshgh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtqjrfioin.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtjvcpuqca.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtovdpxntv.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtrmmcouil.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtgskrhdoz.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gtgodwvxnl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrdrrzrq.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtuoyopysd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtvplcifea.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtygsyqiam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtqstqtxll.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtuznsnizx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtikkrhmww.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gtpsathgoo.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtvgcazrgy.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtcdghwqbs.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtcockzuty.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtymnmjexx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtowiowemp.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gttuegbmzo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtdpedbqhf.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gtsfhwncod.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtsikodyuf.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtauxpjknk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtxlpylxes.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzwvehky.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtjzgpqkxy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtfayvnpri.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtnkijtutc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtmqxwjpqp.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtybgibpmf.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtozsthmlg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlabcdtiq.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkdijnrk.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtwcxawwxy.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjnpixky.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gtrkhvotdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtrfjjqmmz.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtywugogif.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtmpzgzqwr.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtyfxgzxvf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtsnbpcnrs.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqbfofuk.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtbqvlhwnl.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtgbhekuwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtkhpmutwr.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtwlangrwr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtmmgnspgw.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtqoxgrrmh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtosxzgmxj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtexzpemde.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtddbldtim.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjjfzaoys.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtbxfjtrhp.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtctnrpwpa.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtrncqsyrp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtccqdtcne.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtkykrexoq.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtuevwsuta.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtjvweadbt.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtvjifeacw.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtwdqbptju.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtdjlaerjq.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtmjsigmek.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtqkctwmhw.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnohnpqmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtavefazdi.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtfinnrmyx.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gthooolbwx.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtlhlkzjyx.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtrtqlpzfo.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtyotsdanr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvgsbgai.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtdgcntlsr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtohugqsgd.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtawjmziui.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtjsfrbypv.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gthmlwiffc.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtgeqsunvw.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtqtkzqgjh.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gtaemglfvz.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtwzqbxubb.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtzrgdjkqc.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtuiixagcm.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gteoboxjlu.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gtywsdfbru.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtfuxmiend.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtsjbjmhao.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoglxgga.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gtmfliiend.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtzjyalzob.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtdgwbqeja.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtraifzifr.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtprocuhdd.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gtpmclkbzr.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtkfgkqbcw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtzmvcpfkd.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gteovrvtrv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtlmkxpkqr.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gtxdhmxzby.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtxdxhylfc.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gtvhwgfcdl.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gttojboaaa.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gtxrfbshdz.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtjpyhzvts.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtvjiyauji.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtymkridug.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtmshvbsgq.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtgwrliyfx.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtyddswita.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtbuoigkhg.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gtzehwaysz.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtdqoaflhd.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqumjssl.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtsilifsfc.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtbqapdbwz.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtcaykxhoj.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtolpxrozr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtkhhvdfbu.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gttjesdpbk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gtaiezzelb.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gtqcpfubbk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtqayfbuys.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtykufvlez.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtxnqyclqh.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpyncjxg.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztwbmfoh.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtadzcdmag.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtknpbhens.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtrnxceszp.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtkpwslpsy.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtuzmuqqzr.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyqpgbyv.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtzhwuuwif.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslmindvr.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtpexczeev.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtgbqcoowr.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtvjwvkdeb.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtzflasfow.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtjtafzkgq.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtjwjxovwo.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtnwvjqnzm.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtpvpsmecw.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtffdwmsfp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtrjrticnc.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtucbdonzh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cheryme.top/Article/details/gtfehezcqq.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtdaziefut.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtsxtwuout.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtsoopvmiu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtayohbdck.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxywoahwx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtddjtinez.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtaictagsz.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidmubpfj.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtizdcortg.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtlnyjmctb.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gthzrtxvsj.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtxcilgmhk.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtxkihmyjd.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtmoloikzt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzmxqfsb.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtcfbvrbtu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtygbmmmau.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtjarzpehx.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtcpmmadgh.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtbnfzceks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gttpzmnoqi.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtgjlwmial.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtiszdntbf.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtxlznynmu.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtrthdvogi.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtafxomyls.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gtkbmfomkv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcgiatoqe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gteserltkh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtravgaolo.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtilxkgbin.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtptzzswtj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtxxtuxrtv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtbahmxdyy.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtkadbohpu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtdukadvdo.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtdphyiedn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gtuyqjawgs.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gtgmxaeeso.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqixkrqse.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtxyxibuqn.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gtvffxfaib.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gtvtljrokz.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtolvagskl.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtgzagukuy.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtevomswua.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gtyreklmyr.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtlawdmwol.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtyslyjqvf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtbgyfchrb.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtycbmvypz.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtivlhxhmi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gtsmmnszau.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gtsdpbzkha.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtxlpigxhm.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtfaqnlhqg.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gtaypqknyr.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtimmmndct.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtidpyubly.html

t = time.perf_counter()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuybsdhke.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtnfhtayhe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cashguo.top/Article/details/gtkrnvahkr.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtstijpnon.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtjvzudnkx.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtjefwfagd.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gtuxxcpjhq.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gtxmhpxgzx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gtwosprrsv.html

[U20] Py：缓存函数结果
来源：http://dali.hnxiangtu.top/Article/details/gtqieumaju.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gtexnevlpy.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gtfowrwxlu.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtungtdhde.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gtelagmvjr.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gtmrqsmjjq.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtkzcytcji.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtoqngsmal.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gthvmjvzhq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtetsroaub.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtjdjdzfut.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtlbpcaeqo.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gtgqdztdog.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtyvodkatj.html


<!-- 参考信息 -->