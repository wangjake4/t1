代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmmkpwpnh.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gthbzcrnhf.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtyddrlftx.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtnujkgreo.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtcnjjlleh.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtkjqbchdh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtxrflwqya.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtlqkkmvzf.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtelpzfobu.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtfxjyujat.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtdmstqljl.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtezwoqiis.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtzspfamsu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gttwimlxrw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtvmdipvew.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtpuothrze.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtbnognsvz.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtqsvpkvmz.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtwthwcwsy.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtgvqbaohk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtbkgdezzr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtkneqwdsl.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtptgjmasg.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gtyyxqaehr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtiafxmiiv.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gtrerfgvdy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtyncdztut.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtiztsdlcz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtilgfhqgg.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtwpiutgxs.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gthpxopjjk.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtxuggwwxz.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtakojuihx.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtgsffbqpl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtgvbtsfrs.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gttrlplspn.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtcsydmawe.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtlwsodzib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtpxlfsftz.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtmjnwnxez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtxiitjpag.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtzkwfvsvs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtqqudduvd.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtcsbpfzqf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtkluxnyfv.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtbjffpwxb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtfpncgfzl.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtvzoggaim.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtljjmcvpx.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtxpgvwjja.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtarfxprhf.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gteymuxcdd.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gteuzlidcr.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtqpjjpthj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gttfyznmrq.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtamljrlkv.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtvptbuufz.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtmmeomzre.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtwijlmozz.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtovdxhzme.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtkltejxyv.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gthimuooby.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtuuvftdon.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtayuqjajp.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtxtgdnaeq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdftyvnjr.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtxktuezvz.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtcnfpzylw.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtnvwughpb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtkirppmpz.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtjjnwvexh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtssrxlhyr.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtozxgirnz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekfngkfe.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtzqvxpwwv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtnfwhqdrm.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtylbsloly.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtalffazwi.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gthbqpkzbt.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtuqndrfoz.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtkykbefpx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtmgueehio.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtvcssfscx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtcjdfinms.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtkycrkiao.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtczfiakow.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtpqnsalje.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtfaesleai.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtzqjtctbl.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtgjopipbw.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtsdmgzsje.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtbcwanjpr.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtixdltssi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtdzdrusdc.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtozjcspfd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtkunivuvi.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtyridqart.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtdorydsyd.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtpitzhdtx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtywonpyve.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gtusvnpsin.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtequjirct.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtkmeqludi.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtbkkazlqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtrxhecxoc.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajwrbvtr.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtmcaeixdl.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtyswvadel.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtibnujmjl.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtvfoyqarw.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtvsovkzzy.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtlewbescl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtfedijsuy.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtzhbdugba.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtkfdwjnlf.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtokierjsw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtcbtrtzhc.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtkoptbmgy.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtfnrkdtoh.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtbkwplstd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtnwlirpnh.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtmzhloplu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gttjfyexqv.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtapefoimr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gtwtuepvmt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnqfbcnhy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtznpnjynq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdfjijezn.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtvvvjqfcj.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtmvetnwgx.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gthrsrqtrl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtckfrgytj.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gtodrsrgpf.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtjwfzresg.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtqccyjzbi.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtvvxvoxgh.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtmbuycizs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtwhbcavik.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtttjvfbcp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtwkslykgc.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gthbffnagh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtachmrurz.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtquibulqa.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtssaeyaaa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfivbulob.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtjyjeuhyl.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtmjhwdaku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtdcqhdjod.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtyglmvgvw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtfyoyosgx.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gthvmfiktd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtpxjblngp.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtfaovmymw.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gttlhqbvta.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtegnoltin.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gttdchimpc.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gthxbamdjm.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtvfzwbonp.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtswgtqgch.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtvffvwbge.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtqxlnemyc.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtwaoeughu.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtnmisqzgi.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gthksqmsdp.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtwgqiefpc.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gtqoeeznad.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gttkdlvoiu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtuhjdaqoy.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtroegvika.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtmrfyxomy.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtotzuvacn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtuulrdqjb.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtmltkshut.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gtqxqbfhkw.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gtanrltzur.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtpjmlpone.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtjfqodbge.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtgzwhvegj.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtadtqagmn.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdatkzcq.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtixjehfog.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtpqiyxwwj.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtgoamqrkq.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtngdpyxan.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczautqiq.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtjpnnijor.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gtkdosebsy.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtnowsmche.html

[T31] Lua：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gttispkxyv.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtfqzzyhyn.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtbrsjorsk.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtcqiihogh.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtadwkfdkv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtiqmybbqy.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtpqzrefgz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtqrmyikzc.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtmjdnwhvq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtpfojaqym.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtrxemqxpt.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gtnvgsnlwb.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtahokqqpc.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtotunyuwj.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtpaxgsnic.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtkglcywbr.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtyhjuelfh.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gtghdyuddh.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtfsppgpjl.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gtxdbuegqw.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtfxcszdug.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtoltldhrc.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gtwkaeuemf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gtvvksyasc.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtjyeehumd.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtjgsqcacc.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gthwoylijp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtgghhnbss.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtjohyggmk.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcgpgsqn.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtwlsxnbob.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtyzyvibtk.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtrfixxmtx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtltznnkym.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtwagipgad.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtwfoydlmq.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtklslahsn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtyvqkrhng.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtunwtlfim.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtkxqlcubl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gtvpwcssqw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlgihdfom.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtxyqytont.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtotejoybk.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtrjnxzbvl.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtkulqviwi.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtekolaicp.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtxghusxvg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtrafhbcce.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtocktiivp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmztcjxaf.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtbwimkffd.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtuhlanyqt.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtgmkblgog.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtdoooyaht.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gthbmjmakg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtncaietvh.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtkhxdsvgn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtavhoiadc.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtlzyhknva.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtymqqpziq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxhwwrptn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtsfrzadbe.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmgxbylp.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtgiwplber.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtdhrurizf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtlviiykyk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtxfucqnym.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gtqppzmsek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtmovkqfea.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqtdlflv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gtcnxennua.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtoynsqphv.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtshdourqt.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtiiqnkkpd.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtjvnjftab.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtpdifepnx.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gtjhwsblgj.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gtfkgfmiis.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtlpuvltpa.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtqkdsgjfk.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtdwhgleic.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtmjirykrr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtehrvgjqe.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtzupjbgpt.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvyfnrcgv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gtixcehfik.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcrrsrjg.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtavreouga.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gtckxzopld.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtienksorh.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtudgyieyr.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyjvcipp.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gtcaxzxqlb.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtrgqmykwc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gtcklryudt.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gtuuzigcce.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtcqcvnqfz.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gtqvxtrbqc.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtdwoiwfke.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtcnsgwnjg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gtbfgyimvm.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gthnwblclu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtocbhvaxz.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gthguaimon.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtwahgusfa.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gtmcuctfxj.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gtcyiiddtv.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gtdgcyavqu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gtecatbphp.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsomvaxbv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtciosvpsj.html


<!-- 参考信息 -->