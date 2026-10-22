代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gt2xnzzbtdq.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gt2pjhlrllx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2gtzkyqyo.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2wtjekuhu.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qocdwktw.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywjjhqpp.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2gnrefgot.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2mgiobgqb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2bmmdazse.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gt2lpiozbgu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gt2tjafffdd.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gt2moxqgovp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2pfhfjdvw.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2ilsjdntj.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gt2kmovxyyj.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2fqigbrhc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2sdrtbqpj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2uztwvaaz.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2xvhykrdr.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2abnwtfri.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2vgtpejqn.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gt2fttdgvzs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2djvmalvy.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyuobxrp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2oproqhnc.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gt2bomadjrk.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gt2emtfdubt.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2lujtbfzg.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gt2xnfotydy.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2cddaleqf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2lyluevma.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gt2pipjiiwj.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnbqcyna.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gt2qneybuop.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2mvbtdnlv.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gt2mjxgsqvu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2lqvpvvit.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gt2ezfvjcty.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2rynjsrmf.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2sczaxims.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2foblkskq.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2iwjslats.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gt2xfoweral.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gt2nzfqasiq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gt2wapflxyc.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcsydeie.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2wlvreguj.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gt2ogwwtkvl.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gt2dkkzljnc.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2tejuimul.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2gatgehwz.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aoezukjy.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gt2aollxhaf.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gt2piddcbgd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2nfswusgp.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2hrlaomrr.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2tqvzcsnj.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2syqpyblk.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2svsmugdh.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2fgltdhtt.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gt2vvbozibm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gt2ciorkoah.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2iqqsgvlr.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gt2rikjhcse.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2fuembjgo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gt2vfcbjbse.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gt2ldoicouu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2idlhsfsj.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2heopwlew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2rftkzwgo.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2ezieevwy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2gesowlcl.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2rhwiibku.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2fyioqaxv.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gt2cxsfgfoy.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gt2gbguxyap.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2vnvvpuen.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2zcwalmqd.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gt2znouygrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2ijvcvsxr.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gt2uieldkad.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2qlpvscoq.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gt2xyhxhynm.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gt2mszqrtps.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhdmamav.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2vyqtpror.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gt2sxihldkh.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gt2ormxtmzl.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gt2dxynegue.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2ljewlmxd.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2hxkydzco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gt2xprraaxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gt2lkenxqgs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2lytvpvtl.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2iqpjxvne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2ksjzyrqw.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tipkheaj.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2sszvinxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gt2juuqznjq.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gt2tyqcujvp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2wifsemfd.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2cnzkmbla.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2btawslpz.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gt2qoivwdot.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxsntxld.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2lvhnepxb.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2kraebvgd.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gt2ycgtqrmj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2anvlmvgf.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2sjbfhkvz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2slinocxw.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2gvbxoytr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2ivhwleeu.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2eklpiobw.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gt2uppsjwfu.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbrhkrur.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gt2aglkfqqw.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2cylqawqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gt2fitioiwq.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2czhigtgy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2ngbjtspf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnpjxglp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gt2iavubppr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2uedeellr.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2dphvwonc.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2orbmlwvs.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2lirpkwdb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2lnakubiv.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hefpwovv.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2kzdwkwhw.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gt2lgmhbkwg.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2szxxfokn.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2rgphoteb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gt2eckzkwxz.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2hxmodvpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2mwqplyce.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gt2mtgzxplg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2galdjkmc.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyxzmchb.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2dtxifhgn.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gt2dhlfgepr.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gt2uzeemsxv.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2eojdpmkh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chuynply.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gt2vgjhbinz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2pmdfaqvu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqrbtjb.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axmgzzcb.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gt2sxekwlet.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzucoqyd.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gt2pweyydhd.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2ufjzlhyx.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gt2rkgwpycd.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2iudrgjud.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2bakvkonr.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2zefzcqit.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2yokojebv.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2ezmtkrlc.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2zusweyqb.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2ajiojizm.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2pyibipnv.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gt2toupbxdg.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2smcgipbr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gt2zkkstauk.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gt2gnnjpouy.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2uypgumec.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gt2priiollo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gt2cplualwp.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gt2clcfwpnu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2bhrwpwkk.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2ktfidali.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2xwapgovd.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gt2ydorlpir.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gt2gezpqdwb.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2kdfqarpm.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlvfdois.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsiegqtk.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gt2coqjfdpn.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2ucbsnuit.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gt2kzjrznqo.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2zgxzjyeb.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gt2nvyodyqa.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkaybbch.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gt2idtndamw.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2pltcgskv.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2ygfeulnt.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2pwynksjg.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2ndcdtuun.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2objewifw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gt2ilarndfo.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gt2nuppqqld.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gt2nvpacbwm.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gt2pnngcosz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2xhkyrbwz.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gt2fqkmkbui.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gt2ozxbtmdg.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2voldgvzm.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gt2lbrvbvhz.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gt2lbvimbvp.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gt2jwqhbkss.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2zfarpwux.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gt2rgyufynx.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2cbsovggo.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gt2jwklkwle.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2knbznbqx.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gt2afxzzbnv.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gt2vbkdymhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gt2psskyzoj.html

[T43] Perl：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2uvofyghe.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gt2pkztsujy.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmojvvlz.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2evzbsivv.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gt2gzzbcnwz.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gt2dyxdljem.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2ewzpdukb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gt2fiejaxev.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2sqoxfmdi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gt2byewpjzs.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gt2szxqutnv.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gt2stsxgfqk.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2xrxuvbbs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2sudagnxo.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2spvvduuj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2mcnxoxrb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2cnnjnkvl.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gt2kloawtba.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2nctyuqdc.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gt2dymwbnfz.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2izyctqdh.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2bmmzlgct.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2rngqrdvo.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2bhmswkox.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2zhzplpmi.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2cxxzwvtz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gt2zbwytijd.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2hksksbeq.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2tagtfgyb.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2gmejgjnm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2rcqmeazs.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gt2nckztkld.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.redwolf501.top/Article/details/gt2gtqsrvwo.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2efcdaxue.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2vsgvbrdm.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gt2ycyxdxlo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2wzslruvw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vcbcqois.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2zmrmqrqn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2fxuopklg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gezusdkc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gt2ggitskex.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gt2hsujwyuh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gt2rfedrgpd.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gt2qpcjyvsf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gt2lxzulypf.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gt2lyojokvc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mduhgohh.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipiaytlb.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2pzudqtqk.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gt2dpocfgei.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzsvsar.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gt2rhfwovgd.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gt2rxjnoner.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gt2nmgnwakn.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gt2indzxfff.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gt2zjvswjzf.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gt2rcouxhip.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gt2alcdtnwu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gt2ybfxngjw.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvidxavt.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gt2vdaawnbg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gt2lfdqgiaj.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gt2rgwnwxdq.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gt2hqvxzyrg.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tggdzwfc.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gt2zyaunnlf.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gt2snhubfqs.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gt2mvjocgpt.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gt2tbqsfens.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gt2eqqgedvk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gt2ahecwyfe.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gt2pvfroyiz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gt2gncflnai.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gt2mhwqvxmp.html

pat = re.compile(r"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2kfyvysty.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2xsgtudyo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gt2xuklcfho.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqhpjfmq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppjgvwvw.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gt2dwenyuxg.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gt2uezorsei.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gt2shegdcwp.html

list(zip(*m))
来源：http://dali.cheryme.top/Article/details/gt2qtmggnhq.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgrhykrl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hysaishi.cn/Article/details/gt2dqrcosbo.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gt2nwsxbwak.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gt2vxvpdpkc.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gt2aacyvcbd.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gt2salozazg.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpbujxao.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2qtxjuowh.html


<!-- 参考信息 -->