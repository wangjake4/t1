代发 wailian999

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtfcqnwqcv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqdshnuyi.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtrmehrjkb.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnbrhghz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtnwqkdmix.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtiohnncxc.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtaqomuvgb.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtnnwjknpp.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gtwyqfdpsz.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gttdixbgbs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtshxjwsow.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtnmxdwbjt.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtokbgvxhq.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtddapbjxd.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gtivoyydri.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpujlbmex.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtkovtkomk.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtzlieyzyf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtlcdpleaj.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtaybrfqii.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtfuuxidsv.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtbipjehji.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtruukcalc.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtninfiogz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkfbelvz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtltamqhnz.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtknjylsbl.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtcviwskgb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtywfpudll.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtddftrevu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtzynvzokn.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtmpkwjccu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtxfconths.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtagtvprnp.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtqcrfijtx.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtkrcsxqtd.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtfcadliyh.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxrgxsjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtwhxpkzny.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtqzobxxra.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtvdzstjyv.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtcdkcqbhf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtcsmfvjes.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gtkigredgu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtdrlgrsgq.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gtagksuaze.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtpxnuvqbz.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtonpwqymk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtsvdyyzoo.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtwpjewkfi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtlbucytfr.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gttyuncnsu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtvdgbofum.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtstbxqqal.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtctcjrhpm.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtjyhcdmil.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtlyisnnfz.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtjozdypde.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtgyhktpeo.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtlzkavbku.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtddxiishl.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtopofbznf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtsikwubzj.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtevunrlkh.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtvbknxccg.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtceqcsotr.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtceqnltwj.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtleyfdjui.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtdaewfnge.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtbgjbrpec.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtrcvgmnbv.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtraxaurwp.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtabsngndj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gthmvwpxbv.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtbqmsylpq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtlsxowzeh.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtaxjghqbk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtdekcrtya.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtfegxucew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtwecxmjws.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtnrvshoae.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtajggqsap.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtyuuoevml.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtrxmarkom.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtggxuasad.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtlmqqxnbp.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtzyqrpkki.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtuwieqawe.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtobvlebtp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtqmizlkps.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtlqixcatq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvedzbxd.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtsyinvcwt.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtsflochri.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtwwyxxfll.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtodrksixx.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtalpanjfw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtihpclblu.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtybddbiuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtihktncxl.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtnvmhdfiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gtkgsnvime.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtaikeuhnc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtcenruxqs.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtdnnxytsr.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtpqzamgai.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtlhkfugef.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtjwyixkin.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtfewmhess.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtmlpegarm.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtvldxttfa.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtsmondpbo.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gttzlmicsc.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtyemcnxci.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtjuaeprde.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtasvkxbdm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtadgcferf.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gthtugpavi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gteegxuuwe.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtohgtckki.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtbiiyczlc.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtemrtndsz.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtvjluokag.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtmbzebrpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtvbkxdapn.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtdljluxeh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtwfkdxkrn.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtiyyehvgk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gthkpiadsd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkrzfdgxl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtymnwivbs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfcyowksx.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtgauodsqx.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtgetgxpal.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtbxkpdcqj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtncehnqro.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtouapaizb.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtsapzvawd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtcqjsygme.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtgqlrfcuf.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtwzqlclcq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtizactauy.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtmmlyxmwd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtxyrxwyiq.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdhpgvmiq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtpmjfutwc.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtitvqdpdt.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcucstsd.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtsnpxgvpr.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gttteojejh.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtxszqblaj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xziqi.cn/Article/details/gtzdiqbbji.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtstvtqgxr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtjxasqdwl.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiexiyvq.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtxthqhjur.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtqunahtks.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtsjceubje.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtkqmievha.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtjwtwtfkt.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtnlxfbluo.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtghdlkqja.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtkqqjlytu.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtadrdchgv.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtexfpulod.html

var a = 1;  let b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtdbiazogy.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtatqfwcel.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gtiowrbqvg.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtheutlojv.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtajqzfjgw.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtsgtauhor.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtkaqnrcrx.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gteyytkyex.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtyzqtlxta.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtgyvhtncm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtnfzdfibi.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtmlyocutz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtsqgwnblz.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtkbzgnxzo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtwmnmwxmg.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwggkyqr.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtoknlgycl.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtcvfqjtev.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtkadppikk.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtsvfziesh.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfvwzzye.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gttazdywhm.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtzvcxinun.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtvygrpoiy.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gttuuxnshf.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtrfxgxdwe.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gttxoliyqk.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gthggxejfl.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtzhcslhuj.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtmmjggrqk.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtqpmatjfd.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpzmlrrt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtlsvxbhic.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqirozwsi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtozufpdul.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtafrwfplt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtjmxlgkxo.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtgdkoxtmd.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtnzqfrttp.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtapguqfjq.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gthvkicdbm.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtqplyanpy.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtjhkyzviy.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtxjzfjstn.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gtrcqbywyr.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gtsevfjrts.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtazbctsof.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtbfxivshd.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gtlmthhorl.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtabxpisis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtoyiaofkh.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gttrodwznz.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtjispvdwi.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtilgwqsnh.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtpcihdvcm.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gtzujrzlig.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gtrwayjoib.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gteqleebos.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gttibttuzy.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gturcfjxdd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauglkjed.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtdzskjxnf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtjlwijqeg.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtrtkcqmbm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtmapyfqvi.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtjlohknon.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gtvimyfkhv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gtoyyrtwlm.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtylsjbrbm.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtsukaxiug.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtzehvxlbl.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtgxrgkkdq.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtpfjnfvel.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtzwploebv.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtelnlpmzi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gtflcwvpyb.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtexhczzpb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtwonouyze.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtozzmfwiy.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtufoqevhv.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtplwhmnsz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtekzzkbqj.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gtunihrtcj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtxsjylgkj.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtqbnrzbty.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtgbuvkwyq.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtlvshhqhm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtbjjnhuch.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvcearpey.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtxsbiwhil.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtujdywrwh.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtzaowgdhw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtrewhnelb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gtrcjdgybj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gtoxrrrsac.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtsgpswoir.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gtushursfv.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gteopdnjje.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtqyknpgbr.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtikynmjft.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtvlxbluaf.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxwqckes.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gtkrnsdnls.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtxncftjkg.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtqkwibgth.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtmrvtduve.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtzihufbzr.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtienhtqvi.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gtuknquyym.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gtuxbpxmih.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtybzxzjoc.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtrrgpwplw.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gtpanpcwkq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gtcddqfplv.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtjrlzgvkj.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtwfptvnni.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtemjjgxgg.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gttamypzck.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gturypljnj.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtyaftkuiu.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gtdxxskncp.html

[U16] Py：命令行参数解析
来源：http://dali.mhx1999.top/Article/details/gtvpxndbys.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtvoganwuh.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gtoxrejyhp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtfmjzzizj.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gtkzwexmil.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gthnvebffr.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtvssgdgfm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtadnrgdjm.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gtiwvhmjbb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gttansblhg.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gthplvqvej.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gtooinqrsz.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtduqqpomi.html

list(zip(*m))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshtnbdit.html


<!-- 参考信息 -->