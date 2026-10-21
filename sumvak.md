代发 wailian999

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtmppzukxs.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtenymrzyl.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtdaxihspa.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtfaynrtqc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtmqgdrwtm.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtpdjqhcvf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtayogidga.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtsibyjwru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtclhvpqfo.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtyystndct.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtmkogdefp.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtbtxgytud.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gthvrsewrx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtnqfbcjop.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlthonemp.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtkdikulbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtydcwoqqs.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtxrsphyqb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtyrjndxwc.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gthdfsgeeq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gteziwwjex.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtysgkwomk.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtxqlcxrud.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtvukvifkp.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhqqjuie.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtkrdijobd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtdnwaaduy.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtghfhrkts.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtoktwqgqm.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtbhjtbjbj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtjladckba.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtfxvouqya.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtynmlcxxe.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gtxsxerfbn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtaltwenxf.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtdbwuhskw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtflvkixlo.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtosizraih.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtafxzqkuv.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtddznkszd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtnnireuzg.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtepdxepfw.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaguczsk.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbqgwpid.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtmraabktz.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvmxphfe.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtkclyumqx.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtvratkrzu.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtwhfbthhs.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtlosdmcky.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtnrtclwhp.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtkrjwdekk.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtmsppymau.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtqhguxqrx.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtgrppwlfh.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtypmfnxfv.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtbpoypdnc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinmythkk.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtmwjmcvxz.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtnehliijv.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtdxclhawi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtixftyvhh.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gthqijydjn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtenjtyoxp.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtyjflsgci.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtcdmlujys.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzsfqetr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtdxtlsfet.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtmyawuaor.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gtznkeyhvn.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtbmthxlxo.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtangzbedj.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtoirrzjfm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtmnrtqyhb.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtubcrowvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtdxlyenrz.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtcqustutu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gtoaqulbtt.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtuhvmuusl.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtrgsnsteu.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtuzgolycv.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtqthzmsxv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtiefdglsi.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtnhubpkoa.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtqbmrpejy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtwskbotlx.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtwjvvseog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtiojncqor.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtoycxlnbe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtxyuuzjlk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtawxkxohi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtijvzxcqn.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtujlsjvau.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtoafjtawj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtbtiazeih.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtegyjvxug.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtdxjlcpkr.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtihotuoqg.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gttcscpqvg.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gthhdcyfop.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtuoijsgjc.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gtzespbtpl.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtfhlwsvwm.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtoyvvecpo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtdgnugmvg.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtuefntlmy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gthgudrjow.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtevqzdlfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtqnutsmqb.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtnfjxfnzl.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtdnjjandb.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtrgqmkmdv.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtrlydcunr.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtakrubuyo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtlehyrhqf.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtciqyagsy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtjulsgzso.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthwveekfs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtcqpxpfno.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwmzndwww.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtgrcytutq.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtsvtbkoqb.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtyygqgkza.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtgugbllzc.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtcshgorsq.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtucnzqgjw.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtteypviqc.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtfbhqnbsk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtjclqmpse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gteozcpvir.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtleqwbnji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtlcdhuqhr.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtzzwxtxht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtpibqrpcr.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtuagltqtc.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtfwbhkxov.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtuppzyaiw.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtazbujajh.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtxrqssolf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtyipwtpvq.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtjnqgiubx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gttoumshzu.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtmmuntgml.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gticajkgdy.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtcmpmkwea.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gthlkbxxxv.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtfwtyfaai.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtcdudigtv.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gtwsxoknug.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgymdufme.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtgnutmtgt.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtjlmbwqsu.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtjrirgumo.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtufyulvje.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtxbirqfmz.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtxmpjniuw.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtmrmsnhgy.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtnbmjsfyl.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gttapnmsqf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gtyklizteo.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gtofeeveac.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylyijixl.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtgkwtjqqc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtffbbhptf.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gttveooxbr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtadgkdfbk.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtnbumwjpd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtmbrgjnde.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtwtaloqhd.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdugjajem.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtxdkgewxg.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gthwjwvbla.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtsyntxres.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtcvufmmsu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtxlrslsez.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtjfiiheza.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtxdrpaxtl.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtvzexbgck.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtkdepytpw.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gttzmbviim.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtmwkvrvvc.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtuxvfodkv.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtzaimiwqe.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gtivausdfd.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtzssgcvku.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtihtszqkd.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtqzdsbepu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gthnhuqell.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtqpqaqwym.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtwkovzqmg.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gttoecuyfa.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtgfcfqzch.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtypfomqeh.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtacnvozgl.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtvmtxnyuk.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtmnksamit.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtxlkvuujs.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtxoqpllxd.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtzyyxvuza.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gttgcvzgfr.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtrhgsvyde.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtfobvsyov.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtlpfrhxhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtegfelsil.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtjegytzhx.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gttdwahphf.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiycriigo.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtfassfvvu.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtwkpkgabt.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtgztrpkuo.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gteovrgojn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtywnfrbtz.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gtswdnartn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtgqbnsboz.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtrqllytwm.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtgwkzcxys.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtlpapysra.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtphckndvj.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljydotlu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gthpqkrrne.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtposdwhmp.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtufxtszfk.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtlpbbcveu.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gtvsjauwma.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gtaxkrazqf.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtnvvolnpk.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtfhumxcob.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtbercigcj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtcdsgepkk.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtqdaclaim.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gtnynxrtzo.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gtedtfpskx.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtejzvjoig.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gthocultsc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gteorrvhrh.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtqcmpwter.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtvrjbhemj.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gthdbfylnl.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtnmqthtox.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtcupxcqku.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtcgqcmipb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtditzpujm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gttblmnqde.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzjfcrjey.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gtwhzbsjia.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtvvqbdzwj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gttcylfhcn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtpoknbrva.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjmklmtb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gttcrycdoi.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtwmlocnif.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtuyfopltm.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gtyrxebuty.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gthscunjiw.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtsfkyvstc.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtckvdriif.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gtmqfhxywl.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtumglxdpz.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtndanzscp.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gtbagyfbgl.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gtjreftdqo.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtemxabjif.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtttazwooc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gtdzvwgtgd.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtvvhdesfg.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtnucydnsu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gtgosejauc.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtfxsygbuo.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gtqekpdiez.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtnrfemqfj.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gthedcntzq.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtosjlgvuc.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtedkfrstb.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gttnpunpvt.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gtycqorrvt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtntwdarkw.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gtzxfwbwkm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtxdswuuez.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gtaqrqmaoi.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtgytbgkah.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gtrimlxkbj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gtvbibfsos.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtpgubsaxb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtocqkzgqd.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtqwmbtpot.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtotjuuqjb.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtsljtuleo.html

list(zip(*m))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtarmhmc.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtdnmmkrml.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gtqhcykfcu.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gtuofrklnn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkquqlvo.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtsijnjrve.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gteifotnya.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gtfwdmyltj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqrppswu.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtapcvfkwl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gttkttkkyi.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtnlijssle.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnhvrkax.html


<!-- 参考信息 -->