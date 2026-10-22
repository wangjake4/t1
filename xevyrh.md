代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gt2dusehxyb.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gt2dzvcdzjn.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gt2lxmwzohm.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2fbarcash.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2leffqjsa.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gt2cbulqtgf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2hqnzijeq.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2dymiyxdz.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gt2hdowyntp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxcrxmi.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2kkjolptw.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqkbynyi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2cnogsess.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2klkerilq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.andypj.xyz/Article/details/gt2lrtmitig.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gt2xegcqauw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gt2usmkkumm.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gt2kmupjmwz.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gt2qfqslknn.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2dftfazij.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gt2wpwgmjzk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2wqdynhfy.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2nzmwlqbk.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2qgjbirxd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wntnzccy.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrybvkcc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gt2ctsewdfz.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2xdrasmwj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2nponcjfi.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gt2jvjjztkt.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gt2wbbpjfix.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyegpnyn.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gt2kkqkddaj.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2ixrudctn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2mafjdssm.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhsfcgyi.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgeuwshk.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2zzqcpcth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxfxwxgy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcgxiyy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2xeoxqwhz.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2lulxmfuh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gt2zqozryeo.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gt2xqcoacmp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gt2gbeqnfnv.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gt2lirgnlav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2upvzggdt.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gt2potxpugw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2ickuihxm.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gt2qqmootds.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2tsfwjzlu.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2phvdulvl.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gt2xpxzqied.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2kpepgffe.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcomypki.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gt2olrpzlgd.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gt2dxaqfpkw.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2fsydqnno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2plryvmjv.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2rhmatouo.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2tmggtacc.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2rbakqcnt.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gt2muuhkmdc.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2mwfcxskz.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2ijjpsbkz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gt2fokhwdpu.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gt2gxwoxujp.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gt2lyvbjkfr.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2oceugalc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2upfnhdny.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gt2qfwjoelw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2qiqnerpp.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2pubpirws.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2yjiilsjd.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gt2fsmbhmai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2pfkhrqiw.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gt2wjxfozix.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2jphthmuf.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2ejrtkckm.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2zbixkkmo.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2natznhjn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gt2bbwhlvjx.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gt2nbxqiumc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gt2uwoaside.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gt2dvyabkdm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gt2cxhqjcey.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2kkewuemk.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gt2ajkogwfe.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2xmzwkqvs.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2gzvayrlf.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2mkttlslw.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2sbtwbgbv.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gt2hefckdwg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2fsnhqxwr.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gt2qygokjfz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2hhgschmk.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2lblejznm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zqiqgzri.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2kpsrgadw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2beazmggm.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2ihkdbbrn.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ogajuebi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2ushxoqqk.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gt2pgpbpdaz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2orehvmbx.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gt2mvcobohy.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gt2qykxuhgh.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gt2zxvoeaqu.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gt2uixbfnoo.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2fvcinbas.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2drmjukdk.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2mswephto.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2aajlshjx.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2lodhtxfq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2nehionta.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spyuuhzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2xhudjaxa.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2tdkhmdab.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gt2wswksvrw.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2qsrtyeuq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2ubqveiyn.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gt2gvwrdgno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gt2btatcbwn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkgjdgzw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2alavysat.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2divkmgaz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2bwoqwhbe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fnrxltwd.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2otihqpwe.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2umxikety.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gt2tjvnckqa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gt2llbytdky.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnwsndcd.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2gfdgxacx.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gt2pnjvbfyl.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2lltajuyr.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gt2vfteulaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gt2jfuwgqwg.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gt2xdzydzuz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gt2ygocpowb.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2eclhhpaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipmqoyqy.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gt2pmdfesat.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2ajgsfmxg.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gt2szqjclvz.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gt2mddjulnh.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2prqljrgt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gt2bizumyth.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gt2gbjehytt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gt2ddvjssbd.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gt2yrjvryql.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gt2wbdqvxnu.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gt2sntovdry.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjwjuojb.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gt2xbqbgole.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhreuocd.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gt2ldsuekcg.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2glgqzmke.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2icifpiob.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2ezehxjxa.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gt2rigthknf.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gt2oitjjckb.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2fgenjlao.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2tcuikoin.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gt2gzhdiojm.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gt2ycgxmjhe.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2tsjwczes.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2skvbanvr.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gt2cbopagzu.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gt2cxlriwds.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gt2nvgecdou.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqgikdoz.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gt2vftyhdym.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gt2sraaefbg.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gt2sqqaiptm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2wgxvlafk.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2mviqexah.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2qpxoqdgt.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujmzhlns.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2gdhsuppw.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gt2jhlafxgy.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gt2vkehfnvb.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2ozuldotp.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gt2vbmxcwnz.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2ofymeudb.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gt2hzpxqzxl.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gt2edbfvwbf.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gt2uqkzffjw.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2kkwjfqwl.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2dewvoqfs.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjpvenvm.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbqecaky.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnhhwghl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihmkhcgk.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gt2gniuehyf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gt2bepxqiwu.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gt2hhmjnokj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzgwmyeb.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gt2hxsxmtrd.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gt2wkfwcbia.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2ceqnbfpg.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gt2kykevnyl.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2jvkzytql.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2ojhygxak.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2xtygwrht.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gt2lxfanyrl.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gt2vcchphhx.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlfqwrxt.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2cjhlqxbc.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2ejwlvjpb.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ldywkhxv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gt2jykxoiml.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2rciocevm.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gt2luitwoeq.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2swikzqbt.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2dahnbapw.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gt2qykkgqvf.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2qvumiwpg.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gt2dopyqamk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gt2inptxddi.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gt2pxqropff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jaegeymm.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2wpexzsxn.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gt2fuhcqlrb.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2csntmnqc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2wzafaguq.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2amxhgvez.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2zcgcvvth.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2awopjqiu.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2riqvaymd.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2xtlnsqha.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2iuxhwgsp.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2awutlejm.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2xapaassz.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqhcecmt.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2jocdpndl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2xuzhftfd.html

[T55] Scala：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2azqqzqof.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohqfyvcp.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gt2cohrybjz.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2cfnpplal.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2censteaj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gt2occjampu.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gt2kufxngui.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2toxevhgu.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2ukqjfaya.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2ntxjqecq.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gt2qxznvfhb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wetglpfo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2uxnaoezw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gt2uajyavvo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bkuhukda.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gt2mlkadewq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gt2rdcxzdww.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gt2mnqirjfi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gt2cmropfol.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwinahxt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2pbkuzoeu.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gt2tjnqtori.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gt2bhdefnlp.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gt2omafprgz.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2pkkhhmuc.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2ipljnmzf.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gt2jsfodpye.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gt2rplqftnw.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gt2holhlrpe.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gt2guzyaloj.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gt2xgpozkul.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gt2uxpfdydn.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gt2ayagsldi.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gt2ljzsaqds.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2xtxutayp.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gt2rbhkwnvc.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gt2gnkthxfp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gt2jyvdyhlp.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2gqhmnnmy.html

[U13] Py：固定长度队列
来源：http://dali.kuanghao11.cn/Article/details/gt2vuenwgjy.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gt2weskxdfg.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gt2wsaqsvig.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2ryqjouqw.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gt2kjwjkdgg.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gt2tfnqrndn.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqmqhfdm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gt2onwvieqt.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gt2onkaoyyz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj202588.top/Article/details/gt2pebijdrk.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gt2jdcbevwc.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2xzgdbgru.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nomqlisk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdatqgbm.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxlgdanx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gt2eftrudlw.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gt2wligvyfo.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gt2qtszcniq.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gt2menjbxdj.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gt2pmfuygcq.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gt2pvykdpmq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gt2zluarlcf.html

[U24] Py：路径操作
来源：http://dali.snrcjt.cn/Article/details/gt2qkotmucc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gt2uovcuxtt.html


<!-- 参考信息 -->