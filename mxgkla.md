代发 wailian999

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtrdrsfaou.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfuicofrl.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtbgskduth.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtgdiywemz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtzufdnjpc.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gtnhafwwte.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gtpsohzerx.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtpodfmydg.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtkpnytgzl.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtducxyvbd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtghzrkbjn.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturalgblz.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtcfdfinnk.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtwynauten.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtihzpmupc.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtvlbhthez.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtpjeibkvj.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtnvzpwwzt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtqnzilpbn.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gthxzrggnm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtlcejpkyr.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtzyvpcddo.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtjegitpwy.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtjlmjshso.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtafrhjpki.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtlumzdobw.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtlxoequcg.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtjlxrkgmf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtsfhocvaf.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gtfmxqotud.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtksedwukf.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtbgtehcop.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtoxnfsxtg.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtrjzkfkxm.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtaoznncwi.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtgzedwfxt.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtffpgpzpy.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtnenbbalg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gttvtvifzf.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtzcoqnqyr.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtoymeiups.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtlvobskep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtubxvsmgz.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdvyeybp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtofvzqozh.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtdqbvxivh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gthwmpyudb.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtsbmmstbu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtphmmummd.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtyjlgrkmb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtdnvfbrkz.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtsptbspez.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtqiimojyo.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtrtyyflry.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtsqophlft.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gthwbcpyhw.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtxuwkbrqj.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtqgkekhcz.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtrfzojjhu.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gthajnqsid.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtrhztkoff.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtuuutapwz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtrxnmkquy.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtzadxjpdu.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtvdjkptdf.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gttotubshb.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtlwxpbyol.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtpobyadfl.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtgjooodni.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtngltxncm.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtprxfdjet.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gthqiieduk.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtlzpzrshy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtiwhdavbn.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtjtcdsnbi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqmvapuhm.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuponiwgi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtwjkehuym.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtbvvnxuzq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtndkpgqmc.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtxmxwhxyg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtipuqpqoe.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtuvxljspe.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtpeyrfsdk.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtbykasuuh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcqqfcky.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtzdolqtoq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtrtxggrcl.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtpiqwtkei.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtepeqgnrc.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtcbzharmn.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtcvpjhnka.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezofptwm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtittpmzlg.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtmtvwlrsu.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtiuztatca.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtcbgbviyo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtnvkvglgf.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtlpdvcsyu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtduyvwjvp.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtbtgyxljw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtadddljiw.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtkabtxgtr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtmgmhetbq.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtsrhnvfvb.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtkhdgasgc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtsvxqfxbj.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtxyxictkn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gttlasydue.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtifqmcgit.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtqczkyqfb.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtqlbvveuc.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtafrdunci.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtvtwwtyrv.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtshnmdtas.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gtefqwjkcf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtzjtmpxjg.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtzssbrbmg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gthazczzzx.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtzupxzixj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtueyvdkwo.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gtafhtkdmc.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyivcriz.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtboarrurh.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtwzkqskgx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtklhrxncd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtsgpbpuzf.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtmcoykyzv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtaescdjbt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzezfsfof.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtpaudslva.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxloditwz.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtbkdgdzfq.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtwmxqcamf.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtgdttjxba.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtgwdvqlns.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtppullylf.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtuzxrixat.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtgdxnryux.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gtchvrwcbi.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gtztbbnlkn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtrjklgkth.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtgxiaukwv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtracvuyti.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtihgiqfhc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtnoyswvyd.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtgktvkgcj.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtqmyvcnnq.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtiuybhsem.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtrtyjlxve.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtaoqprgsx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gtsiofoxou.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gtfuwpbkhz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtsfoyircr.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtdcusovrz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtzfirdwos.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtrcyuccwp.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtqdqmtrrz.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtpitgcbwf.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gteoyyhhez.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtorakhmut.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gthtoavnjb.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gtjwiiykrl.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtemuuiygd.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtvpneyfsz.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtakgknjyh.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtpecnrjoq.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtilhnlymn.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gttyvjawhv.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gtaxzzkifb.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtrvvfdpik.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gttvoypcff.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtvfilqgaz.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtioxpyngz.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtzdcnrrat.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtvxkyjuwc.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gteduhodqq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yonumen.top/Article/details/gtfmwiawzv.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtmkelwchk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtfltjqznm.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtfwafdyou.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtpkehjpzu.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtqpzdhtey.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtyzpretfg.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gttllqkydb.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtsajtnisy.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtlqiukftd.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtuqkbrrdd.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtihmqajlu.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtpwzjnudx.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtsalnalvz.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtzicwingr.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtcujoqfzk.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtspfcwodn.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gtpgsxquvm.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtoynnvdfy.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtyitvwelz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtucevskxg.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtxybewymk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtndrweayf.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtrylezphv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtcwudtyag.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtvkmilytw.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtctzqnwxr.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtxulzcqsn.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtfrpuiban.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtgwhuyedo.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtetpxlbdg.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtttqxfmqy.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gttmcfdmxa.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtefkkbiss.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrgzeqdm.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtjpeocmtn.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gtejppgdhr.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gtschqznto.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtihigarde.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtwppdtrbw.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gttcybwgbt.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gttsepidvc.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrbqzjsjq.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtkuleddqy.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtvuzxrzcn.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtqpdshxab.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtpkeuplpw.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtpokzlepu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtjvybltam.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmbozcbd.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtsnuytrfk.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtkuuzvnih.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtnxqphnvi.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexoqsqip.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtwizhwsuv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtpapagqgz.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtxbkgvodl.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtkklyizjk.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gtddclwajh.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtitgoxglp.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtomuqnxtt.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtifudgaxa.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gttewjypex.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gtzzicefta.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtxjjjsjfj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gtkeosyskf.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtashisdqm.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gtvvipbfij.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtovobzuda.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjyjzouw.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtvqrffsis.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtqtrdkpbl.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtzdxmkkun.html

for (i <- 1 to 10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtlhmzgoka.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtjngcwfox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gtilkkklmv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtduejigri.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtegpwejss.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkewrmbua.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gtzkawznyb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtmjkxbeyn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtimbstuwc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtsktrernp.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtdlzsuyya.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtnzjpgqqz.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtpkmfvrxy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtrplsaoxo.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gteohtegdj.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtfjfvlqby.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtlznvjvli.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gtemtzblkq.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtyubuqhpk.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gtszdwodte.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtelwwptnb.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gttnnwbgup.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtaodtqgeo.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtubjjtkys.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtcqlqezhg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtbiadzpli.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtkkqyldjg.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gtkzzlrond.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenlongwang.top/Article/details/gtpxoztztz.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtzahehbar.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gtbjjvnddi.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtsogtexjx.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtblkjalav.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gtaaqqxpdt.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtwhfumrbd.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gtuhapgnfm.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuikjjwik.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gtgobthhfl.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtaazezpde.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gtpjfmxznc.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtdmtdtdai.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtomwucvdo.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtaxotjyca.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtlkuqnemw.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtxvzavihs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtzhdjsbrs.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtvcymucal.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gtxzlqgjjw.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtzrobifbd.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gtodlfncqt.html


<!-- 参考信息 -->