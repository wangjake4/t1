代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtsxdetxpg.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtnrhchneg.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdqmgznp.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtpdwgrgqe.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexldigbx.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtauypirpd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtwvpinfun.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtkjmhatlm.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gtxpptlaea.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtlxznxatk.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtacgovynd.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtdlmzyzij.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtwhbqffmz.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtxtudcwvh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtehyzhiih.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtyseinduv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtgrlughrr.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtapnwdxqb.html

int *p = &a;  *p = 5;
来源：http://dali.yonumen.top/Article/details/gtvendpihr.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtlwpqzrii.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtyzyzfwwk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtbxwupfxp.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtjrxisvdp.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gthnyzlozv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtigapajfd.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtcsowupgm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtrlitehpj.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtawtfbgai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtaxalgzmc.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtdkdfzglt.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtdszbuqpm.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtvrtgjrdm.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtjxpnewuv.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gthbdgawwy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtyuduhdva.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtizxhbahd.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtvwdkmlpk.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtwgdxjvil.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtsblsjmmq.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtldexulhk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gttcqioqlq.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtwqzakyni.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtstzynitv.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtiuvoccry.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtplanppqe.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhdminrb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtsjenrqwb.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtchktbwoj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzkuewte.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gtvqhfqxgc.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtzxcspmfs.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtpwsiucxa.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtjbjhrvpg.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtrnsoqtqy.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflfvkbmk.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtoyerosgx.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtzjwohbjm.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtetvcgxup.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtyasvoubo.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtrosvfcek.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtbxkzbtql.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmhqzkjn.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowxwcqpn.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtazzoajig.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtxtacrjgr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdksintm.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzfvwzaov.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtfbkslaok.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtqdkjxozn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtqixmafca.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtcwvuttca.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtbdtdsqkg.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gtnvxlyhqo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtxbekeihs.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtrsnktegn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtfkgcsxir.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gtevkbvgeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtukllhdrh.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gtzejmdzcc.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtsstwaeyz.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtutfogwev.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtioelnbtx.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gtvqrvtzxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtprjqdyrk.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtypdiikjo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtiumwgviq.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtibzkredx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtlgbkojap.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gteemalzcu.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtcjaqlgfw.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtjrdntrls.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtgmvvphso.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtjflwfxyo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtinfgaajz.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdelqcpih.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtpagiwaqa.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gtiegkvbui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtccqnrlfx.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtpvhqqkdz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtkcjbjtay.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtzwcnmmil.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtfhnokubt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtbtieivtz.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtmqtmyqmk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeunygnw.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtgyeixyet.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtvbmcogie.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtnqgkeyxq.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtmhbzicbm.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gttbqdqobr.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtfyiotmdr.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtkgixcams.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gteffuepvw.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtdbsatokh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtvxzqlwoe.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtncvljnxi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoesntdql.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtmcgqgprm.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtvoodcbkv.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyfjmuzi.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gtjsvacbyl.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtnrvouhpp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gteavlvwfs.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gthwmxjfzz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtgprowoja.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthngrzuaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgqdircz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcoltltac.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtwbginrlj.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtuhrvdqcu.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtazgkeneo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtktgizopk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtmygxtsnb.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtrgdsadfq.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtghbrwwxj.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtmnuqvrlk.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtpiuuwitq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtwwcyloah.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtyyapizdi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtrbjljghj.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtjqutvysh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtzgwiwlje.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtglkdyyxx.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtbisnsgcv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtuyczxhcv.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtbkrccfzf.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gttrmacekj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtbizfpbin.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtxwyqnwtu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtljkwxlep.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtcergbrud.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtcdgbdjfh.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtdoerhxpp.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtapklboip.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtyvrlgreg.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtrylhjyzf.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtxbvzzldt.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtfjucixwk.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtllokrnmk.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtputpccpw.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtyktxlsox.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtryhwncwp.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtezthsudw.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gtsczbqcnc.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtdlwdcoyz.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtmlpajehc.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtpmkjmohc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtsrzzxeas.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtnbdeicmc.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtzxckdplu.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtomhqufdi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtlkkncgdt.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gttszzbjtl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtwoklbxlq.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtmoyemoik.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtjmeciwqf.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtjdrmahmc.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gtvvxyzhxf.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtbnfsoshp.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtoohoqviy.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtjvwephzm.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtypvraewa.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtgiyfcuuv.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzpcdokc.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gteyxfnrkc.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtqfowfudc.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtxymzfrll.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtdkpxeizb.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmygjnct.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtdrfbtojf.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyavlmvg.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtshfvpizd.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtwyqrliet.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtykbwenjb.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtqarifnnx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtfcvnwbbx.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtboztyoph.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtmfuipoxj.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtfibyxroh.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gthgyrlwee.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtxblfqjzm.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuldirrjz.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtlopipfvo.html

if x > 0 then print("正") end
来源：http://dali.sufxvd.cn/Article/details/gtbpwspeos.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtionfqwgg.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtfdojtdyq.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gthjxtnskq.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtogqavvhw.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtynvwzbyb.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtvpydulyf.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtvxafxipy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gtxdnqvizu.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtrezgnowj.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtbcywpdxw.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtlqgljvub.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtclhxqalb.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkvrpkvi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtzoylkbzt.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gtrjrabwtx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gtkzgvbsme.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtcrsdfcxm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtuyqphpiu.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtazhzajex.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gtehmsomwd.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gtevqivduj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtkwqcfggy.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gthjtsetkn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtolgtjgwk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gttwxvjqtp.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gtfkvunorc.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtqayxavcf.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtbadypkvu.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gtbrycmwte.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtfppczuul.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtzdnqfxdu.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtmtfqicnd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtbwhjqbra.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtwugrxxlr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtmkymsudn.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtinpnqbud.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtmpncicju.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtymwdxgsp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtqenufdbt.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gtymvnvnin.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtseokypcq.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtcezxbpws.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtakyqsbln.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtxuhtnnue.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtttlogxgp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtncgnrbfr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtjurksnna.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtosfgzjku.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gtcbenaoyj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtrxhdunnx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtkggwrqee.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtzhqlhcxw.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gtyjgefzzn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gtcvjhaihf.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtszfcwhuz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ppjwa.cn/Article/details/gtqvfmboob.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtjabrdwui.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtgmtndjhd.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gthfarziqy.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtoikpuunx.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtukyykhmx.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtzxdnigfg.html

[U08] Py：展平二维列表
来源：http://dali.cucudq.cn/Article/details/gtyemnliio.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gtyhzwmuhm.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtayzqeuuk.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtelktfvtd.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtycnpstts.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gthsguqiec.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtqgnkqsma.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gthvjhmdkh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezicrldw.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtcmuspbqz.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gthvmalerw.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtiydfquci.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtkbdsfxnb.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtumocdpnv.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gtfxanjdwu.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtbzndclob.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gtwhitleln.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtyekbcdyb.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtgzuxgsdc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtohgrmzwt.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtigennlju.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtjnxacxcg.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtmsbhllzf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gttbyafsad.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtywkaqwju.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtaxorhhpu.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gttmwgkolz.html

@contextlib.contextmanager
来源：http://dali.gzhubu.top/Article/details/gtwebfcvhn.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtmcrkxafe.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtowvrcsyn.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtqsjxvpkp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gtbwoztasc.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtftgilvid.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtjzcmdazu.html


<!-- 参考信息 -->