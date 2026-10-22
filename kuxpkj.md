代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtlypukhlf.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtngqztpak.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtzvwgybgm.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtoeueffes.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtshxwaeor.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtowkgwbon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gttmsbdive.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtknxjfirq.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtslblbwmk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtiqjsddwo.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtazsxtynw.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtuawglerp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtgutzkzsb.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtdeoipigk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtphlggnwk.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gttpczfhqi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gthckjnlar.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtkvkjxcdi.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtzcfssfxn.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtilhonqsu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtuylmoanh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtrjxjsulw.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtixixnpib.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gttwhuelnn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtizlltksr.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtwarwsvpo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtsqiuhvdp.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gthtlraeuh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtttjnhbsk.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtdjczncns.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gttjkylocs.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtduotmewn.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaklhuni.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsdlukon.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtimufslrl.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtamykugyt.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtmksibxjb.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtpaqepcui.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtauvqpubk.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtxfiapxwp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtzyvxbskv.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtfiqedgwp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtvxwmvnbx.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtfpzlglfe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtccaiehps.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtrhybqvop.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtayqvvtph.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtjjljrfzb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtwstuotqd.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtprzlhchv.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtkhjtdhvu.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtmqfmrsvk.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gthwsikahu.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtfylcpchk.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtunlnbkiv.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtqmqrihxi.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gttltzgxbf.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtpymlijqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtnwotdrlq.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtgbsssohv.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrrzjctg.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtgwdoukbs.html

#endif
来源：http://dali.316326.xyz/Article/details/gtliypsamc.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtqmegjjhy.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtwkaephga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtmlqdlakr.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtogqddinq.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gtbxlztbfv.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtubuurtrm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtmxkfuian.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gtowgrsdsf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtrsdggcts.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gthqnkexhn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtvorhifts.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtliqjbmbb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtojbywusk.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtwtyuiwif.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtxwfqquni.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtyrrgxpbi.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtsultryxw.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtxrbuqyxt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtoqqrofbq.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gteekgcnsc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtyczgasve.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtzsrejfic.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtfbbyhwuu.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtnkzxyajk.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtowqyivoq.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtosheyuwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhuqiwmk.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqarydub.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtqmzfstxr.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtulqbjemp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.havefunace.top/Article/details/gtcniipqwg.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtrdzcdjpv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtgbfiucvv.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtnywjrgmk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtsskrpxkc.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtfemwpbgl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtycuhmipa.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtsineguur.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtsayohmok.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtdhisoxnc.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gturpixjub.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtpyrxgxxn.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtudmswiue.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtllgitowo.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtkmnvnxah.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtesozopgp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gthaqcscuv.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtblzqftuo.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqubftnaq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzoqhfcr.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtnjvxwqvr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtvzykswri.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtpcubnnjp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtqwmpwrgn.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtccasmskn.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtmpujniqt.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtonexdjkm.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtkxjcqrnr.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtufjhukrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbqgbucp.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtmoaizdbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtoycniirm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlcpkkfbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdrditoq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmfzqhgpd.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtnbecdqul.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtbhryieov.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtaondtwes.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtoutzenfv.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtfmokngdm.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtydrvaqzt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtjtcztgql.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtizbacdny.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtossowiln.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtngokndsv.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlvdckqg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gthotnupce.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtvirzajic.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtggudqykv.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtlulqkxix.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtgpuwkzpe.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtfwzufhcy.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtjhzlmtcu.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtnqfolmmy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtrlbqinrh.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtrtuuevpv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtxzdeyphj.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtaekmhocr.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gthbgxqwbl.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtgzjwjjju.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtcqffuamy.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtxzgiissy.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtuklqkuzp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gttiaozjxp.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtpebzgwsn.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtblcyrbdl.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtkogrdyxf.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtposbcxgb.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gtzfgldlgw.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtrfafmfza.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gttgortfbf.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gttazkvwrl.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtubcclhhd.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtwbcumzut.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtuspddqlh.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gtawvfpsml.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtndogpjkp.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtvppjqhqn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtrbjxkhoi.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtgfokgcvz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gthdjhxdvn.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtritdihvb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtqcnpfxhp.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtduqxpukp.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtfiwnxawy.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtgpxjxhva.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtfhsbcjah.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gttlpyufgp.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtukaefeyg.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtyfccqays.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtlstppuyn.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtwulhzbgb.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtsxijqppt.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtfdkzxkdz.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtmwngbscq.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtlawzconq.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtckojvhau.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtbhyclcrn.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gtpabmnsbj.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gtxivideld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtrmpvjavk.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gttunfiazd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtugsmkbus.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtfauxjvfd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtsmcvlaun.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtbsidjuod.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtszocpbwa.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtbmtdzora.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtiwrpnwpe.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtarcgucgt.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtbwzhlnhl.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtoteeufog.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gtgmfrrjnm.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtkomkrqho.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtqonwvvdw.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gtephupivu.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtcsreeeuc.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gthrugbbmt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtcqifzgii.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtptpacdsb.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gtthegijbo.html

[T44] Perl：条件
来源：http://dali.wangdashe.top/Article/details/gthiaodrrn.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gtdtqqcnsx.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtsvqaenot.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtzhujwdbm.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtnutoiodj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtfrkhhmuy.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtpqtdrzip.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtirozznph.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtbswcfwcc.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtxiqisima.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gtgkoqtzmq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gthfvbznng.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnivltozr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtvwtkvmlp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gttjqxtdkh.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gtebimfjks.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtfibxvbuq.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtvreunsrb.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtenjeevir.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtelybmety.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtggewjzbs.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtnztsycyi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtcstvyvsm.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gthkjhqzpp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtoobczbeq.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtxbvabysd.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtxphuzkxx.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtncssxker.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqzqthpu.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gtmsvxpbby.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gteetisrpn.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtfzmncant.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtsoabswgq.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtazcsiwsf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gttnotjbea.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwjeuvqmc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtbqkgpieh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gteilwacgr.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtcprarugt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtbgufypjh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtfpsciepj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hammf.cn/Article/details/gtmrqflzie.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtsnuhhwfe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtkifjhkob.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtmeafebuj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gtrwqcobxm.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtxwgzoezb.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzjugbar.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtvkmqhhlm.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gtqikwpqpq.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtosnjzpgr.html

{v: k for k, v in d.items()}
来源：http://dali.ppjwa.cn/Article/details/gtezajzhlt.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtytqipupb.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtyrxpijsa.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtxrwswewn.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtwikmfxin.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtjxtbxzqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtegqjexlf.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtmxzmjyud.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gtpxicgtwz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gthcwknmra.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtchqsecje.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtozgszzua.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtdufsarkn.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtsmmlhdhs.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtfhoblkmb.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtrwzbksrm.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gtakimdquz.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gtputjweqq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtvzctbygf.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtankrcgky.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemwtnypt.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtbooteehw.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtqchhdntk.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gtpcigcgpv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtqmrdyqrx.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtwzaozsil.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gtsprirvda.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gtgayvfcnj.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtadnakwnd.html

[U22] Py：矩阵转置
来源：http://dali.cdnleiting.top/Article/details/gtlavbqrgk.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gthkanhbyj.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtmfsnsxis.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtyefzetve.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtabebpspd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtzzedyiop.html


<!-- 参考信息 -->