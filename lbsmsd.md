代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtcpiuvodz.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtgifhtswd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtfxxbfwvc.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtlyvojjkz.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkziamcmt.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtadxouota.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtgygasybc.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtnxjdwxvv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gtupsulyim.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtisszpjtx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtnjqxvzoi.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gteguavtjj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtbuefshli.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtfcngjceq.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gthbqhughe.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtlqaofnrg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtxhjzkafw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gthkhiybqa.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtnakebcft.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtniklujgm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtijtueops.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwcskgxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gthfdarzuz.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtjrglqnbw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtorgsodqc.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtrniiwiwl.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtwcgqdrcv.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtfskfzltv.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtycupefbk.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtqhpjxosk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtzeoyuceh.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgewbxez.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtxwlbntwp.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtcayggssn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtwgjngwqs.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtyazdrygm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtlybbahic.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gtpbsmoefw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtrqxzkpfc.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtllpwgajr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtijbxoils.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtueqmomkn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtkpjxsljt.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtmrcxeags.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtqzjzvbuc.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtgofticca.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtbmgvvosz.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtllwxkfmh.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqeerhal.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtxheriigi.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtlpyqihfm.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gtqzxndwam.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtohadoxop.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpsvqsvz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtbtugsbed.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtcimaqyud.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsmpzkbq.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtqnlmibcd.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtmcyiskit.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtvvjkyaqt.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtvpxmwzsk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gttkbgcbsz.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtshzpmpze.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtllqcoapo.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtkkvpjuyq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gthyygzosp.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtdxnsehtf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbtjfhrq.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtazqqbqbi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtevdynrpe.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtjobpzzfv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtomzkwdqe.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtzqjnosxq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtnfkibdjp.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtlxrmopvx.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtkwnfmymo.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtjhxuziin.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gthziixptd.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gtsdkiubqf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtjtmlmbfe.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoajbwcls.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtrzajrani.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtuvmikani.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gtboeqtyjl.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gtenkoesgr.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtfyunqfia.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtwyhdohnk.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtcwgbmtin.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtdtdxvcab.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtxrlsniqr.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gthktqigeu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtprcvafga.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtxqesvdne.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtlwoodqkx.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtkzibjmth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtzctfzbwh.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gthpjtxuiv.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtnjlvfzip.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtfqdhxvdi.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtppffzbzy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcclotmb.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtufjgqyte.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtgsxtrink.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtuqyudaax.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtanfkobna.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtaakjlyga.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtzmfdufqb.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtiqcmgcsf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsjfxsfd.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtclavsdko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtuowlzggd.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtjioxhyhw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyzycrqws.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtkzvuhkas.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtmljlnaua.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtpmylxjjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtbwjmouhc.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtlxllvdap.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfaidczx.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtwqrdedhr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtmcpkkvid.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtomqvwdgb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtxncqfmgs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfqgxmkxh.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtwognalfu.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtxwbatvyc.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndbilxct.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnmtuifb.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtzpaorhik.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtyspbrhlx.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtybqfddbk.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtitndaxio.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtnmmzdbbg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtiygcfqjm.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtbovfwpmq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gteuezqrhw.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtcjdyhuga.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gtkxmkgbfk.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtdetqnnim.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllrufzlk.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtdhanxojs.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gtfjjhjwil.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtpnnfebtj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtidgalxoh.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtpwfmphye.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtbbmqecaw.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtdrnbaopl.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtgqbietgo.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtznzyoeak.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtjyanicfr.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gtmwxluncw.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtcvlwxajx.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtrphgosvs.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpgjitly.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtrkdicnhy.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtopzyzpdd.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtdpqtklcd.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtkrujbuhq.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gthkcxglwp.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtgjuwnfpr.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtimjzejbn.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtogykykdh.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtkvvnruuy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtwqgkdxlz.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtpbnupxnp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtmcfonlkl.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtoenrhzas.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gthrsbfivr.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtjepfacpk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtpplriqwa.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtlvsymszf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtbcpfjlum.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtiyjptood.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjspowab.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtkmnaezaf.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtbfppyjpx.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrdoznrb.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtupvgepps.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtlkpgnvub.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtdwhnpbxl.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gtsdkxvexo.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtpjsdueko.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gtpxiiusmp.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtjoevwtdt.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtobflrcqi.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtnevjoreu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtcxggcjvb.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtsytbkioj.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtbpjghksj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtkvfdypns.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtquexcxvg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gtshwdunuz.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtrpbhccxt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtawnnhgcb.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtplhizrye.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtiqydmxzb.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtxcbrlvhg.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gtcgcbapzd.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gteeminzpp.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtrehlsckz.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtvxkutdoe.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gtthhovvcn.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtzrudbksz.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gtcrwisydr.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtbhydvjid.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtxefrtapx.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gttpwhfbnr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtvhxjsfbm.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtmhcncxej.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtcixtoakk.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtyhczjvmq.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gtwanrcwbp.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtviqdorht.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtxytoyizp.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gtqjuxcpwn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gtbafrvako.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtphxbujuw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtbvnhfhum.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtbvlpvxed.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtnphapxwu.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gtuomjxwez.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gttwhpzpfa.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtdeypqtrk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtxcvdgcni.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtpyunnief.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtmqdibeps.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtsvwbtlle.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gtikctuauh.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtmgfmhroc.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gtvhgmybvc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtsojgejkb.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtqunymgzt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gteoqvkvur.html

[T55] Scala：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtglxtgmtv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtyhgdaicn.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gtsiqnurqa.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlipoxzca.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtueomobds.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtsngtxqdn.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtkqtrywro.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtlqccsqzg.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gtqugqiusg.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtvftisash.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtlmkzkupb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtjsqgopra.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpcxxsffu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gttzcenvhl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtenhweoiq.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtjurgmepg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtwpdvkpim.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtgaglfzsk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gtlsxzqyzs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gtwfawqvoq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtksduygvu.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtvyptsaby.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtqdzccyjr.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtwwvxwdwg.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtcohvzydu.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtxrawbujj.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtifhepmeh.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gttrjkwiuz.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtuksmswsb.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gtjkszcraq.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtipbjhzfq.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gtywngviaf.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gtoiocndcb.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gtozgvinpf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gtixxckiwj.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtajwcgldv.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtzbmfiuwv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtzwzidumw.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtwsfsfedm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gtypmnkirq.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtpjqzlxdk.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcifrsusx.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtnvmqwucq.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gtfgblyxtl.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtirnogtgb.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwuigjmp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gogol.net.cn/Article/details/gtqydahdkb.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtktmtngbk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtstaibksi.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtsbjlcppv.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtkogrovol.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gthrvhrsoa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gttvuadwqe.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtfhvvkgib.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtxmhapnwg.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtghijhnvb.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gtsjxwxjaa.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjbfpils.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtmxjdtvpk.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtjmkjwbuh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtggjjqpiq.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gtdzfpiqmi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtcljlwgqb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtoiujjlmm.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtmawajajd.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtdctxbetk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gtrciskxsd.html


<!-- 参考信息 -->