代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtngycdwxm.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtdhshjfnb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtehzbabhf.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtgzvurzla.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtxdnqxrct.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtfddqcqqz.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtciwyluvs.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtabbmwbss.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtobdslajs.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtaljwbizv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtvzckuoio.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtxqdllxtx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtwcpizkkg.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gthsokejxr.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtzkcqryel.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtrgjsauxx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtpgoodnrh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtjjwugycm.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtdhebbhfn.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtncqqysyk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtbmctxfep.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtrcpwmhnt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtgqgsqtlk.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gthlutzixp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtechprvls.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtyizrmbtx.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtypdwnqlr.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtzuedldmd.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtrneoewwk.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtatqjywwo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmvxonky.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtwgqsavmz.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtrnckyntu.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtzedwczqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtrhkrttrs.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtibbmkyhy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtabswtz.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtsjgdkdlh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtqqxwnxof.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtjdmscrfa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtdemejmng.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtwoqhibpc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtkhdxslse.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtqyjxjnol.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtxbxeyhoj.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtdcufboxk.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtfljcexgy.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtotopmwkm.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtkfexdchv.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtamxxepnq.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtrliczooy.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtslzmopxn.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqyqrdbo.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtzxnuehzp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtsmndysvv.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtfelpmdjo.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtsgebpzow.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtekuqapdf.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtuafojndr.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gttoqroiir.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gttsouleln.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtlapowlgx.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtxwycjolc.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gttwkvuofi.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtoywjkgqf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gttjukooxp.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtslsyjupo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtqszjaado.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtpflxvnfz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtwjxuhabg.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtannsdfxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtutclukjx.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtmivfnclc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gttxkkgokj.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtylibstfl.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtjkslzexs.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtdwpawuxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtugqaijkm.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtyolnaqgf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtmbplaqfk.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtchwsgzba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtavdenbqo.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gthprvabky.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtbnjvzqdf.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gtsfjcpwnt.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtiwtgcddr.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtrkslrxke.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtsnvnhexr.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtgfrwbmbm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtqmydesve.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gttnwaivej.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtiwknykgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtucprplle.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtjnfckvoh.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtdrijekfs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtvloyezmn.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtxspzqnso.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtwrbitxgl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtrnlnmaas.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gttanfdljb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtrtkhcayv.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsykgexd.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gthcxglchc.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtoaiinfdj.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmblbzhra.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtngphrzmg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtlnmnrtdr.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtclleirwt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtxcgatwah.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtfciujwow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtsyrdaetj.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gtvrrfckbx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtgqbbsnel.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtabxzhzmf.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtwmimqvfm.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtohutkfey.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtfqrhyotx.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtgtsebiar.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtzodmvsox.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczjjwsnk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtigtrewvc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmzkbrvse.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtvkghcgij.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdlpgiuma.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtjbngyxtq.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtxkaprskw.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtmzowdwge.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gthyciygjg.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtalbloxbt.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtqmhquyjg.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gttdreqlid.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtbrwucgyh.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtqtbcgbvd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtgznlppgj.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtlvmcmqvg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtfamxuzgm.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtvhzaxfhm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtwuanytsl.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtecxcbxnz.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtpvyyztag.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtcfdggryf.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtqkaqkydn.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtlxfkngpp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtstobxqmx.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtzyhdggmw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtnbhhjgbb.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtsiwvjnqn.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtdlwwaryg.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtgrkencsi.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtktbtyzzt.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtardazhrt.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtxeunokfa.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpenrfzk.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gthcimxkjy.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtigdxseiy.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtdqfqbeno.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtizpdvpkl.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtwhzbntdr.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gticubomqj.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gtqenbxbex.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtqsxxjdyr.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtlmuonari.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gtrvimissz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtscdhfibf.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtdywetyvb.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtunryzbzh.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtrkaakmhr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlqcqrqj.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gttuscdxie.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtylfzvdhv.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtkrceqktm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gttncjpwcu.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtbdwdktsq.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtlqctoacv.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gtphdjtlzq.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtxqfwfzqf.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtndwwvsxn.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtsfdfliir.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gtolwaycoz.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtqwstekio.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gttxymoyrn.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtkrwzzajd.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtilfjwdiy.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtitwnhldr.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtgorsdadl.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtqlzjlzfm.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gttkuxyvhu.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtuiuixnod.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtuifadxdx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gtxlrkmrbm.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtoywctatm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtzdxicinq.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gtjkshgmqu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtimxlhtug.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gteijzxivx.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gthdaajtqn.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtsoqackdr.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtdplavjlf.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtmiygnltp.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtrrmntlsa.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtnpqonmyo.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtzkccxtgw.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtrxmqvjgt.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtjqjxgvqz.html

[T41] Perl：Hello World
来源：http://dali.yuanzhike.top/Article/details/gthuanszvi.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtxdicnxkc.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtfnfvwvem.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gtqsewrwzj.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtazitenwr.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtwdlortjs.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gttsykqrze.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtenbnekqa.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtclhudhxc.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gtfxdvihru.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gtlmajwexs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtgsnrsorg.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtykvcnwsz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtihflkwqr.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gtbokxjrnv.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtowpytadb.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtdsgvmolj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtkyuvabur.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtzvkhvqae.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtfyrsxcsz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gttulucdzr.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtqanwukgg.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtewqjrtso.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtcqewnkxy.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gttlelkbka.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gtjptypond.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfspdegia.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gtohyvvwgf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtkpydgaqs.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtyietazcd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtscmzvdyz.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtxzdgexdv.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtjqafdwgc.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtcrxjbvkp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtlblekcbb.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gtvmfirdpy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtgdwqmglp.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtgdwpgnmf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gterjmcgll.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtydckidvt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtpzynjpxn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gteqmmpoax.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gthuwstxke.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtftmurotp.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gtfrgzpnfj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtxvbrtbsa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtlzkwnjgi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtdiqahadz.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtdpjtnrlj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gtcfyyyboj.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gtnnsehxbj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gthlmvtduo.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtyhcqbyjt.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtfsqstnre.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtqyyolzzq.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtenughkdg.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtsucwidsr.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gteachflkt.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtxqxfzqmj.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gthbfafhtt.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtxjwdluda.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gtqwtykhzd.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtirnxxfas.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtvmtvmqop.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gtxytjycpw.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcyogmcaa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gtdrsrcmhf.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gttmzhgaga.html

[U13] Py：固定长度队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhniwwjn.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtdfavlgcl.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gtwdbyrxde.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqhrefdy.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtszoltdmx.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gthwpfldhi.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtbuevmpeu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gtyefcjzeb.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtgyrbzuuy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gthhyjyuwh.html

[U18] Py：预编译正则
来源：http://dali.yuanzhike.top/Article/details/gtgpqxxvnl.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtzeoozknu.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gtogmtiavf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shuidangran.top/Article/details/gttuubbvxp.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtbazgcyft.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gtjovmbwrz.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gtnxeshpkg.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyufjqar.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtrvvhucyu.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gtkosdtrlj.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtsylfrkpq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gtpwqgxaro.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtapuqydyi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtomaniubh.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gtlhfjzgwc.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtpkgdorrv.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gtynehpppp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykiteucd.html


<!-- 参考信息 -->