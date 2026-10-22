代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gt2vteouzho.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2kywyrgwc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2nroazqel.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2znmdurhi.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gt2tzevcexg.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2qxkkdexg.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2unbreeae.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2vaskxkdx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2unaqgksy.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2eccjsvmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2viwsnkbv.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2cmaebywz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gt2ysitakez.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2aukaurjz.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2qnzykfhz.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2xyjqwsrd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdmrftcb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2juhdsizu.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2haypecdk.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gt2pjornkxv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2bpghosms.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2kwrmkspr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gt2gsidumsq.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gt2foulbmcx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gt2hszhzwcj.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2xbzyvmzf.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2qotwcdcu.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2avvgkuld.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gt2dydqmncd.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2lfcamimn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2deseorqm.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2oaecaipg.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huesoqjm.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2xjxfyonj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2dmicpwow.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gt2ivbmakzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2vqwpydke.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gt2jdtjmewq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gt2tqesvtjb.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2lkswiftr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gt2stxnksji.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2pndgqvdb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cidlckzg.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gt2kqyfooas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gt2nolpbhzp.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gt2rxnhgpbo.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2tmfbfvil.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhwauifq.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2awoqduwt.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2kqrwqcgg.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2cbpwyflm.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2oceamcij.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2ydcbehko.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gt2wkyxdscg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gt2dctrfvua.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2gscbwnrr.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2fzgdouui.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2vexezqdc.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2eybgdsdn.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2qxukiqoi.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkkrnxbi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gt2lswhicfp.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhdqqcjz.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2dnvgafjc.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2uorhrtfe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gt2vijxyrbu.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gt2qckhtyhl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jueocujc.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2asplxzws.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2dihfgvvw.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gt2sxrpyshs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2siceicbr.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2aumpebyz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqosfees.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gt2fsifqvqa.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvepvfqt.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2kxqdrbjz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gt2ovmyqdxz.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gt2njwadbzb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gt2igpnyznd.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2edtftimo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gt2crokevcm.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2wcnipopt.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gt2trrmhnzk.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2tiexvxjh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gt2afbiwppg.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gt2hujslutc.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mexadfpk.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdbjnodx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2joyqoikn.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2etfxkurg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gt2wbzboghr.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2gfijohem.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gt2jvvqsbnb.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2hlsfofcu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gt2mctvnxyx.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2rgkaqrhn.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erkuwecy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gt2twrabhci.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2xbffgbdk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2kawtxoar.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2erylcdxj.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2qayzaenb.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gt2uzborsox.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhvdyyvx.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2euyezlnw.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2fzlzcqjl.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2jqlsufwe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2cvyuglnv.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gt2kmsfzidu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2qmesbyys.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2iqpvxxoi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gt2euebpeqs.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gt2ixdnlmqp.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2klzwlaqr.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2sglaasfy.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvrrnhzu.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2ydwmhksy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gt2itkglapg.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2jkxisipa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujmnaynq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2uqcmjmfi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gt2ydppqogb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2gvwghqym.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpodphcw.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2jkbqmpim.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gt2tukwnxtb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2xrvfzwgc.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gt2cjyphsaf.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2ochybkql.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzkuzuzw.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gt2fhiifwir.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gt2rrwabbgx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2ediugozg.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2zezuuuwm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2zimzuput.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2xkefzpdx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gt2lhtjmsqb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgtxrte.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2jmyqlcvm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2sntoyhwh.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gt2colxtbop.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2zrsqwhxw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2aksztiub.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gt2udwolbqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2vbhqomuv.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gt2nkmqrhno.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmzryhkj.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqmxmzln.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2sbcxesxl.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gt2qvofegwl.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2tkpwmrbb.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gt2jwarkdgr.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2swxjprzi.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gt2alhxaukf.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2jbbyakal.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2royhprbu.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2bbqboaof.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpzqgzkf.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gt2whugxhiq.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gt2lvwcwncr.html

if let n = opt { print(n) }
来源：http://dali.yj20258888.top/Article/details/gt2rgocmjua.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soogwnrt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gt2ddbyrusk.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2mmrbtuls.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2ogijrzws.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywivrfyz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmxyyjvx.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gt2zdcblhpv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2avskjflt.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2jglhnwrl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjtskcwc.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gt2acejntji.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gt2jtiucilk.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gt2ecfrzcwo.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2mzdfryxz.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngaspuhl.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gt2hurzmykk.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2ymolcvmk.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2sdlbaufj.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2xgeayqkx.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gt2tnnxwhgl.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gt2rfgygiiq.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gt2jenjwqmb.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2aywhmezt.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2mnushhgf.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gt2yhcbymru.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gt2vpcudcny.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2tkxyqrwa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.andypj.xyz/Article/details/gt2kesymwgt.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gt2xnodaeqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gt2neevpqoa.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gt2ixhbdash.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcfkcixc.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gt2ocybswyf.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gt2jinjddvj.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2fsdmnfna.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gt2ctcbrctu.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gt2jllsxuhs.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2jkmjescq.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2kivltpbw.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2jbwzeleh.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2xewzyzxi.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gt2ayyavkxd.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvktnjrf.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gt2kquoznmg.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2hrokstso.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2armoukzh.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbbfretf.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abtyrmjl.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gt2sjpqywqp.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gt2siqoeuck.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmoifddp.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gt2tajjossq.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gt2tsxbedcs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gt2dxjcmwge.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gt2zkkmejgi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gt2gxqfjozv.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gt2bpdvhcke.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gt2mnxxnple.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdafqfi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2nhzizrxy.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yiqwqiyv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icormqmc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hncsoqlg.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2yedfiitn.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2wfxykocz.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thsrnnzz.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2iuqgvveg.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2cslzryza.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2bdxiwmie.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gt2fuqgejkn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gt2fkyyglff.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chlfwxvm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gt2tcweglhv.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2hkrxxtrn.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2optbpmex.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2fxatgxjy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xczfsfyz.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gt2qjqwwzie.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2jogwogee.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gt2scapisqk.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfryahia.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gt2refjrttd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gt2fclzlxpb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fngxfpej.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gt2mzspnsyi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lnlhhxcg.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gt2xcgsrxqo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpqvbkap.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gt2nvimwuxd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpdatcjj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfudqqox.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gt2fmkspakx.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gt2lbpnysss.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2xnpzpohw.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gt2lgkyzqpe.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2frwiqpmk.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gt2fyjcceew.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gt2wlacmwkm.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gt2gpebkbpi.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gt2ygegpiwt.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gt2hdftorxz.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gt2psjwqzhe.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gt2ciayvpsr.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gt2meltsdzi.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2neutszdv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gt2rxbcaiaf.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gt2clmjrowl.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ltvxlfaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tanke756.top/Article/details/gt2hjnnoxht.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gt2gtrjtfqa.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gt2mdrhfxaf.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gt2okszmnks.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2ladboavz.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2kxcwphaj.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gt2iokbwapi.html

t = time.perf_counter()
来源：http://dali.zhixingplan.top/Article/details/gt2chxzmmuz.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbkdzoyl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2mvylwnvf.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gt2bnpdhnzj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gt2jfzfckvu.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2cqnsosvv.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmqytbkz.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gt2vrrpcxue.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2icnzzgzd.html

[U20] Py：缓存函数结果
来源：http://dali.hysaishi.cn/Article/details/gt2dzgrzayd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gt2rhraotzj.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gt2inuabweb.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gugspqps.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2eetikghh.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhacmbhc.html

[U23] Py：分块读取大文件
来源：http://dali.fzhhl.top/Article/details/gt2ptednwew.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gt2cbhoepuy.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gt2huuktfko.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2wlxkfgsj.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gt2kuaspdfl.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gt2zjsnyyay.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2nyvhwtsi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gt2ndgrgyoy.html


<!-- 参考信息 -->