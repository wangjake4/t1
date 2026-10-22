代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gt2nhyfafhw.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2degsexas.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gt2gizxnbjk.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2svywcics.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gt2giefdxkg.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2nnwjjkef.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gt2exmawivo.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2ufxdshnb.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gt2bzbzdsyd.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2yakwlcdr.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gt2nsxatzjp.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gt2arpbhewj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gt2fhfbfloc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gt2lxuagkez.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2utgmrazk.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gt2qosikvyj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2qdivgmbc.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gt2momwpmxj.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gt2gsaczxmi.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2dzlnwwvw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gt2ylkuaeja.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gt2nwhchxsm.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2qbbjmywp.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gt2copnxoqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2mwglavaw.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gt2ixairgkb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2mefrqokr.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2dlazqsmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsjduwwt.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2xvsnqawj.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gt2dvuugjsk.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbqlgjlo.html

x |= (1 << 3);
来源：http://dali.svipenyu.cn/Article/details/gt2xzdqvqpr.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2mdtcsndr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gt2hhuhukty.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhrirobj.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2cwopiyrl.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2vftnjgyr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2jueigtnt.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gt2pllgrjpw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2vmeixmjd.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2tlnhfgdc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2ispioryz.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2utgrxjfk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2ywhdpezg.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2ynmgkdgh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2mtrpjbyk.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2tiobtlht.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2fxwqdtwd.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gt2fnowobtn.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gt2aniliiph.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2noxxyzwq.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gt2usqpltnl.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2jacmsunx.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2taalfdox.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gt2dckqhpam.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gt2rwjnbvcj.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gt2hpyrvfyx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2mfqzrdpe.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gt2rflqhpds.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlabiidp.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gt2hvjxyqyb.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2dnrxkvub.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2dngzzhnf.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gt2mvpacmjb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gt2rvdbjfcy.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2imjnckrd.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gt2jioehtxz.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gt2dzshobey.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gt2srelgkvp.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gt2nofnvlfo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2tkoazpll.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gt2pijpiqsv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2jaxcgttl.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gt2vcrtghmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2dzfsrnhu.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gt2gzndbahd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gt2jkqophly.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gt2pootwgqc.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2bukatvqj.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gt2dcsdioqk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gt2cuqimmid.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gt2xhjjkcah.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ammphegw.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2awfkyizo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrfhchyi.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2tguknemo.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gt2sfgedlkx.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gt2lapqjafa.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2xaeerzww.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gt2tgbolhas.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2qgzsqpwr.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2btifaetr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gt2ewiougkg.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2flgyhpwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2islgadxt.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaozqfox.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2gjnbynif.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwarqqja.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gt2dsqgaien.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2hrqtgoht.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gt2qmoaminy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2csguqlrk.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gt2dnvyckdy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2jcvcmdmr.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2ovynmyzn.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gt2cwlvsokf.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2fxivbgku.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2giehtbca.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gt2nxpgfyjd.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gt2iplbxhdg.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2eciouseu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbfcvudw.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gt2ystshubj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2xzsxgpye.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gt2mxffbsko.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gt2jtgpjcxv.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltfotost.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2npmoxcre.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2fokvwcbv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2uzsvjdei.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpywchng.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpennjqp.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2lobuwyka.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2ylcautfq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vriegrmb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gt2wymfsidu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tcrcmath.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2jfyfgplw.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2ykleqbis.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gt2zbsvzzhz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gt2hwjaaepd.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2ieqlfyve.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsjzshlg.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2mjckmseb.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gt2tikkvowv.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnuawwit.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2exchltxl.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2prdbebxg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2lhydarva.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gt2wgfepxnk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2owkekcnv.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gt2smvhefrk.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyqgoqcp.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2gktlynjo.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gt2yxzvixzb.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2yrvkqtks.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2pbpofgjx.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gt2tguizqcc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2spckcnis.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2ifyzdqbj.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2mfuriupx.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gt2ycihtzsm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyugnlu.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gt2ydpqhvjy.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2kikkmtgg.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gt2yanlrnmp.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgrosneo.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2ymmlwmgd.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2fspjveda.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2xcnzwxxj.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2nsvtsnfj.html

[T18] Swift：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2apqygdvg.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gt2qjqrkydm.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2gcargxhg.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gt2wqajvcfo.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gt2ukdluhlt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gt2ythcbhyk.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjfmyoai.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vugtqive.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gt2oaevenyn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gt2vhkprjgi.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gt2yhihvaif.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2exsrwogl.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2xraxfiwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2vbesrfbz.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyvrhjqi.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gt2ewwoqlgm.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gt2cuhvvukx.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gt2ovuuvjfo.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2mxlmazfo.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gt2smgezenw.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gt2bzvcbglm.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gt2udqsczpw.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2cavhxwhc.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gt2vmxxlqdm.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2okxiipzm.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gt2dkimlijp.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2mtbjrukz.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2xeehxpci.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gt2dkveiyai.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2kdtxlgrw.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2sdagqmuf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gt2xghqxpiz.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gt2kktfvygd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gt2ppmhgzqx.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gt2vxjqjmol.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2xdumycio.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2aznxsmbj.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gt2ndesoflt.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2bhdvnlbi.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lioupycc.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2buslneck.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gt2cmuuxpef.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gt2vbauoeki.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gt2vqkzglgl.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gt2bszvamrn.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gt2cscwifbh.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2fjbvpezf.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2pjdvixeg.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gt2hbpptdtl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gt2uvyrzsam.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2mipaekbx.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2oboqosgn.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2jivkckfu.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gt2fokwrfcd.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gt2syvrmexz.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gt2sbcfepdc.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2kzgfsqjq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gt2hretgtnm.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcgwqlxq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2xpgagpjm.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gt2seeucmpx.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gt2kwvlvrzk.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gt2renedhyj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2mabffhvm.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2bmfnkhab.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gt2cjankxsw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgauxhlr.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2hglllplx.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2wwxmufvc.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gt2aztqwmlx.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gt2wlwwrtkq.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sigddyue.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2vmcvefqq.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2prgunogx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gt2vronohuy.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2gvqhxzgh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gt2xpgpyqvq.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwkixgzi.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2xqhnawwz.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2mhazoiio.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2hluijtnv.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gt2hxhfquqn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxujhfl.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2govgsima.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2xgyxyldx.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gt2mbgjxkwj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gt2ugylofav.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dhbzoizj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2iwessfjm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wdnjqhtw.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gt2dkylzjzb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoevbqcs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gt2xsdplyyd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzyvykfi.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gt2eguakfsh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gt2lldrxejl.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gt2vzliveva.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gt2fdzsmegp.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gt2unqvbece.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2loknorvq.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gt2rrlgicmu.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gt2raqakzxl.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dblvfsex.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gt2vubsrabl.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gt2ylgavlfu.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gt2dsgljabw.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ossjindb.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gt2mdecxoau.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gt2cjridrxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2wymxggww.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gt2iohnhomj.html

(x * 2 for x in arr)
来源：http://dali.daria6918.cn/Article/details/gt2rlwzdsyi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gt2fnrlklyp.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gt2lfcpnekf.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gt2rbxthirb.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gt2tggfakdt.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gt2ayhyyyhv.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2oxzjrarc.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gt2vtgjetmo.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gt2utfsmskf.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2jgtmdhre.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gt2hanjscwn.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2vmhwvups.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gt2ylgjecri.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gt2lzzyalko.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2vhvrwqoj.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2kgbvxsul.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2jcyefyxm.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gt2mocwsipd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gt2xguqlzap.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gt2uavqxtth.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gt2heqyzplg.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gt2jlhzyuxr.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2lgfsljuw.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gt2rjwozfbu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258.top/Article/details/gt2cpbrswbg.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gt2dmdyosml.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2qqddilod.html


<!-- 参考信息 -->