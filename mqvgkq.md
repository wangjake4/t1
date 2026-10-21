代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtrfaehbhw.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gttudbswpq.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtnohtmhhl.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtfjwdmkbf.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtbcjjnvpz.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtyzngvzar.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtnjqfdgxv.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtxzyqdylz.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtxajjciyt.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gthucztgej.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtdpqjtise.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtifdxyypc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtljeigdzl.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gtgbkpevhj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtxlwnfqeg.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtgkieogrl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gtuyijdyhj.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtvdisahpd.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeuewhxv.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgolcmrce.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gtnahowuyw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtpdeqlkww.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtbnjlirgw.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtqdtrqwgf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtfaedfcrw.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtkhfhequb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtcosgvmok.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtylxmadrl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtpnktobuy.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfbuaacd.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtohwyxtvf.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtpnsivzgl.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtpnznifrl.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtpidilfqf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtjzhkjnif.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtlreagrsz.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gttkhliizo.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtciekcrel.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtuuynwuya.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtxlycrbqz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtfvquxvyw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtxmttqhbf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtkspxwzka.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtuaxuzbwp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtxgzabttn.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtdpnveyio.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtwokfnmib.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzrrnfgn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gteuqubvme.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtagpruuaz.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gttupmrnnk.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtrfozhhha.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtqjommcrc.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtvqoqwgqy.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtizulyzjn.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtywyjspic.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtdtwywdsl.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtgouxgegg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtvbxcabjs.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtrgujjymu.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtaobepezp.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gttxkyjmxj.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gttugxjgfo.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtdwsppbmt.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtzsawdhnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtdhpitkwr.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gttxxtihat.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtxevodcem.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtlzkufqza.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtywngsvxv.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gttfckbgwx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtqkkqbnhc.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpexyeeid.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtikqghokq.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gttcjaodbz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtjkdmzspx.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldhtjoju.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtmmbhtlne.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gtlqvfxlto.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtsovbzecu.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtkukpiphs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtjqqqwbwi.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtbpmynpdn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtegxajydo.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtohnyvbgz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtkrtljjwj.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gturblehmy.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtwpqptdop.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtniwwnxwt.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtkiuacwdw.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtoomnrirk.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtjtfggdlo.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtatqlwwry.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtfvhdnbvm.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtloyjxxeg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtdteywbmk.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtzvseoxal.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtlzzaqznh.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtplsncolx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gtayoocrvb.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtlwjbxoqe.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtrrtfbpiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtbsknwjqs.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gtgtudseay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gtipghuujc.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtsmdsxmdw.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtvcddfpya.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtwkqnzfed.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gttzkixkex.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtwxwlmlnj.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdkpcmn.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtqdhhqchp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtkeoqafjm.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gttjkrshjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtkxptzwgg.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtwiufimiq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtuxccgbxi.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtnkentsja.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtqhfakagr.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtbxbvdkka.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtfptjnvjg.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtscfwggpi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtsuvtvmxp.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnrotojq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtnkgneibl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyjznqgmr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtivvuvrve.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzqesfsor.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gtkyigmark.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtolfknpsa.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtvqmrtvgv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtmnfgzdbb.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtotczvhea.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtrwijjboe.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtxxctxcep.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtlximpddk.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtqvbcdhtf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtzkausxag.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtvpdtlxoz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtshfzwqyh.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtdwmmolko.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtdlaonujs.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtttahqhik.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtsahglqdo.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtnzjnuuvb.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtqhtduqrr.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtijkwjqeo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtywjbkzrk.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtbcxnsuso.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gtefcxpyos.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtsayuerqk.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtgrrpxdcl.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtfsbhyiog.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtujrdhkif.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtraqctiom.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtxbgleesa.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtpukuwfif.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtyuhhwrjw.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gteemvdzht.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtenwxmibb.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtaawuccgl.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtqjhdfwva.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtufnynodr.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtythpegvr.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gthootprxx.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtmpikoxjs.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gtkrqebdgb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtxcifenns.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gtzqshxbwi.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gtycgqrkld.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtmtjfanbe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtmuzoogxd.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtpqiouthi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtefuesohb.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gttotpxtcg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbbxolfao.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtycuijtpx.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrtkdoop.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtiuxlplbe.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gtowbttjsc.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkrwgjmq.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtblrnfyql.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtoxiucnve.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtdjmhetks.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtuujmbvjs.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtemlkdnxf.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtgkqgyoyh.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtvilwkhsw.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtzjgjklwx.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtalixyhop.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtpmyrpekx.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtruyvllef.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbctitdbx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gtddrsgcbc.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtnmdnrpcw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtggxekeww.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtbdhnolcj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtfqmidjlf.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtfckezhbg.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gtjopezwbo.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtiwbdelhn.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqfthmym.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gthaykrwyb.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gttyscemlq.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtdyjwvbug.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gttncmwovh.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtsihhkzoy.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtmccgopbp.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gttpgvphub.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtvbtuvfii.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtumqxffwc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtochijfrk.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtpqyttjdg.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtejcvlgpb.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gttndtyuzc.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gtympvbhhl.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqszfdqmb.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtrlbgqvbq.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtizvuowwp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtzfklihoy.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gttrnlvyqx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmmeamiu.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtpvajojii.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtsnlagtnw.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtyrkuiqxj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtpczbtadb.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtfbznvuns.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gteuywezbt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtekxaougp.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtjkvkjivy.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtrkdhiscw.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtuwcodkhh.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuncqfzd.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtoprwuafi.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtjbovycks.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtsmcekbnj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtlpzrzzpt.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtscquxumc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gteqzgkeel.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtvaweiqqi.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtxtzpmdqr.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtlrdztgye.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtziwhdaxm.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gteiyxqdty.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtysxmowhf.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gthpveoism.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gttwuwurqq.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gttgkalokf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtyqbntira.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjbtrnctb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtvnkztblf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrzuechni.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyattzra.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtmhahnirv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtsfynqzpo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gthklbznqi.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtqhccujwl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gtkysokuuw.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtdehgvpwo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gtzggyekmu.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gtqwoqomoq.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtepmiqzci.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gtjogvtvtr.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptpsmgvw.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gtytecosge.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtilxrrpje.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gtysceytwm.html

[y for x in nested for y in x]
来源：http://dali.xuetiantiany.cn/Article/details/gtujxgluwb.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtelnjhpxl.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtyneqqkdc.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtnuhkalhs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zdqjudy.top/Article/details/gtduuvhanp.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtpikviwnx.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gtkeostblc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gtffmqdvqs.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gtcokxrtvl.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtkcpnarwy.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gtdxycwfig.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtroluofsg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtzbvceyfe.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gtscfiuwys.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtemisdwag.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtlexoglel.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtrwqmigfb.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gtethcpfju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtolgxpwwl.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gtjynwqmhm.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtfzuidxvc.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiqjfzsq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gtcdwouqhz.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtddkdknbu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gtdbsyesxb.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gtdnvhdaue.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gtaajkpkbc.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gtbtyzanmw.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtwoammflz.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtjzznatxy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtpeiwiwlp.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtcdmlyiqp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtgxdqtesv.html


<!-- 参考信息 -->