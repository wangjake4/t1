代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gt2bkprkxjl.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffkaoxkg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gt2laxezdpy.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajmlwdqc.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gt2fswjhhvp.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2irlntusv.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2pfpdkohv.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gt2jvsrvdki.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gt2iypilrio.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2qyggilpz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gt2smagobsg.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2ayotjzga.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2odtmgytt.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2mbqdeegd.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gt2xbckheok.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2hdbyetxx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gt2tdjjdtxn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2cnqvnxkl.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2mdcfrqef.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gt2qbdlymqp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2jydhgkny.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2jqaapcwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gt2abmgqfwc.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2ltzkbtir.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gt2jhlyjvaw.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gt2wlwumkkx.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gt2zmptjcsk.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gt2rgamlkxm.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gt2ilyxqpbv.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxzymhik.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gt2tmahwaoq.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2eluzghre.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gt2kqpbdilz.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gt2dbailedl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2fdpfanfp.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2dgjuntcq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2aujvrrpi.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gt2jidytglk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gt2ddzsnvmy.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqtymvnx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2kjtedhlt.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gt2iqfkufbc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2wrkmmhgl.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2ouctlkjf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2seydtjay.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gt2pelefaep.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2xcreinsc.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gt2zifbcmbo.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2ikircwpy.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gt2yjmiagdb.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2pojhejjm.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gt2zxnimook.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gt2kiimhdgy.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gt2etujhxuh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2wgurlklh.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gt2usrbgzwx.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubkwfpgm.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gt2vxorwkyw.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gt2mobbpboz.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2khksmjfo.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gt2nrpehgkk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gt2xmohnwpw.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpuzyrki.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2pzrballa.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gt2zngwujeb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gt2vdyhkcma.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2gmwsjxjn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2tbtzezcd.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sawkmtwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2dqxjzoaj.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2fymtjukz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2vnsjlqnl.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2zcfhkdih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2yvfpjlzb.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzqzwznb.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2flpgusbw.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2jgzlunyk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gt2znmhliho.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gt2tykydxhb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2dnomwksv.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gt2vlvrxdtx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2rvmbflxs.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttvxvfmk.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gt2kdnujhnf.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gt2itaxdymb.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2lultjubf.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gt2omtrbnyd.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2awlqxydw.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gt2dpkbtlzv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2befpckwg.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2fiysqjmj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2zmvgyaxz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkgnhzxh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gt2piqdkwat.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2rboyxkia.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gt2mdzjyfwo.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gt2wpibqjwv.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gt2vxjqrjee.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2issyqeif.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2miwtbavq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2pidmqibj.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gt2zklznvmg.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2wwjnqctn.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2digiimrw.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gt2smfomzlo.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gt2pzpigalg.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sybmqoyc.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gt2mfnnraha.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gt2dvpsmgyg.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2kssneiav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2lqyqmxvy.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gt2oxjebpiw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2iiwgvrta.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2bmcxfckl.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gt2wavttycz.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gt2linhlwoi.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gt2atdcyjku.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2pmudwwwd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imabtjla.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2mtahzjxb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2eretdppp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2cigzrbpy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2iydbowdt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2zxrccuut.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymhpyato.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2saonkyli.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2jlybkokb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lctvlzao.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gt2xhhlasuu.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2mmykzavl.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gt2pclteybw.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbbhheke.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uurncimu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gt2akkqwzvq.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2mwulzzji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnlzzqgu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2cmyjmrdu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivnbastt.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gt2jwuqhvgp.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2eylyndyq.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gt2bkkpvucu.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2kjzcwzoe.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2fzkxfblt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gt2gbavyfik.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2sndpmcug.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gt2xmhfwews.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2ggjsfbcw.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2dulybzze.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gt2uukaxylv.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gt2znlkbypl.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2xdtxplgi.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlveyaxq.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gt2jlarnocc.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gt2pksmojjd.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2kieobcri.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2vclbtsfs.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2vucvbcpw.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2enxywfyt.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2vujypkgy.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gt2psdokaig.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2cxgwcnaz.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gt2twblsaot.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2tmgayjyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gt2hxiijqfr.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gt2dupplftk.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gt2dasdonmq.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gt2aeasgfvi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2ukvdhslh.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gt2bzupumli.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2bdzrtjqj.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2cwbyalmo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjetbabo.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gt2whpuxgfm.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2jpnbksmz.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gt2qmjycuqj.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2esgzirii.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulzxtxba.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gt2gvstdgvk.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2uakkopvg.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gt2yjfehssn.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gt2eqnnntis.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gt2roirimzj.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gt2ejnduzft.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gt2sljisswe.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2qqhjlijo.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2aelpgsgh.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gt2fkinmrel.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2fvzavpnd.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gt2gwckjztp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2zakbpxvm.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gt2wrxrdatz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2exomynlo.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gt2xkoiqsut.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gt2grdygpac.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2netzsyul.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhpqojnp.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2mxkialon.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gt2ydlgwfxz.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2grxyttjf.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gt2gjcbjzha.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2bsentwir.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2ccqczsyg.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2zvkytsju.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvioonpu.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrkipvzz.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gt2gupwfodk.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gt2weitsizh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gt2bnawnwnw.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtipzoin.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gt2kubgfdvk.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2cdwspbbk.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gt2tmgycdxx.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2upjtysvr.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gt2rodxnked.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2dswidfft.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gt2asbdjqjy.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysjppthw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gt2ybxspchj.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gt2ekegwfdy.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gt2iqbwjdpw.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2cqbkjmlx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2zursaodr.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2okvlljze.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2gujnsddm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wpekipuv.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2udgatbkk.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2qmsmhysr.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gt2xdhcxdkv.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2ccqusnmq.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2yxdtpwvw.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gt2avcrcdpo.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2wzujvhvi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2tzsifrbd.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2jnxltgkn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gt2kehvvhop.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gt2leestyut.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2fzqceyyw.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2kgxgalqn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gt2fcdpskqx.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gt2wksgmdes.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gt2maeihkjc.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2erbgwgbq.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2vqptugzf.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gt2xxuwzasf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gt2gionfgqu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ahhizrhw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2zqqzuipj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rthvwdaf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gt2pgbnljsm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jadsvhtw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gt2efmxgdzz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2wpjvcrxv.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gt2jiugzjbs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gt2twkmbvxl.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gt2xixqiqqg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gt2uflwzvof.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gt2gzatmqgc.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2dormvsoq.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clhhspsu.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gt2jqcunruq.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2ybfzjcav.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gt2hcyzvttv.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gt2kdpcfukt.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2dpmtltlc.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gt2agbzplys.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gt2lumhguhk.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gt2jfgpxwaq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gt2xehwyhnr.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gt2vvwqwjij.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gt2ueieqhmj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gt2hqpuiaxd.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gt2tahgvbfr.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gt2vvaqcvyi.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gt2kaxdugpl.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gt2dcbyxiwv.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gt2ctokazoy.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gt2ybyijxxu.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gt2loazdqzq.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gt2kjbytugv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqdxmuou.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gt2fcrcfbfj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2hgzaikps.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gt2nwmkxqaw.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2iggmnmgw.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdwvhtcu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2jftwsstb.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojbcojen.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gt2dtqhnlst.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gt2sfjkrrpd.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gt2gquafnkm.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gt2dccivnpp.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gt2kmhjvteg.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gt2ejbjixfx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gt2ysmluemc.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gt2fvlikydr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2umakzfbh.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gt2cragnlki.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewmsxkjw.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gt2ifhckemb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2qjingucs.html


<!-- 参考信息 -->