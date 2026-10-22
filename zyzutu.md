代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2bdnupcnq.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gt2iukcggtx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2xpaqmcpe.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2bkudoidm.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gt2fcmaqccp.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atheqoil.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2tgofuhkc.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gt2xzpgdiex.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gt2wzcwvnhz.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmwvqdlp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2ahlpmprb.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gt2hekgoqyf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gt2nyjrowqu.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gt2lbrwumze.html

int *p = &a;  *p = 5;
来源：http://dali.yonumen.top/Article/details/gt2hqsmjnzp.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2nigavxvq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2oqbfywdo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2lkchqzbt.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2babnehma.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gt2oxlhuqfp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2qzafbmuu.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gt2zcxhjfxa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfpxiflg.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2hjhiivmr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwszfhmh.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2lyvsqdvh.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gt2yujocvhr.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gt2dddybnsa.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2ooscospy.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2dzhbhvsj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gt2gotqyikr.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2mlgxbjkn.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2lpyfalnr.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gt2jarpjcpo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2xqomqjne.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2bbvvljvs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ecakvaps.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2daqrrrhe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2dhgyopvd.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2mqlvuals.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gt2mzrdopag.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2qtqxzbit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2nchhfpbt.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2pnuvnoap.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2sfhxmqik.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gt2czddwbmi.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gt2kstnyrxw.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2qwibhpqu.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gt2tyuadksc.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2ilouhwcz.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziozcntq.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gt2khpojpuj.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpfpazlf.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2knkdegqh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdpewbbr.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gt2fnuxwuth.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2dxhryjli.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2kvloxugi.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gt2ssfwoqor.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2siqqpusm.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfgfzzns.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gt2xbfqlcyx.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2vlwhwqln.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2qmkreemh.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gt2oolbxces.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2ecwuhnsq.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2ejsbdkos.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggbpecoi.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gt2ikggsgfn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrcxifsx.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gt2snackjwp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2zeqzefwq.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2uukidift.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2nlidtvzf.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2xujtdprx.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2gsuaxhlr.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gt2hlubianc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gt2qnxrmlzy.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2napmantk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2jbhhgdit.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2djioyudk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gt2izxadrbn.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2alliuvyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gt2nanbpled.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2ojitzgsu.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gt2cdebhrmh.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2lbmjtpew.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2kczzmvhe.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2szynsdsu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gt2qeufedis.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gt2gglwdwvy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gt2afnhlxym.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcumoezf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gt2ccdlynew.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2wnzpsuwj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2dqxkxkjt.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2jtoalmwl.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2efakzgbi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zilsthcq.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gt2lhrcmecc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2mdhzlzom.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2qebbcnyk.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2usrzftge.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2rtzugtud.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2snekalbb.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2fiyavlwm.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2vnlfiupq.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gt2kazxjyas.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gt2ftydkyvl.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxmjagxw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gt2yugihacp.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwfydalq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vnssfbox.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gt2ntaclgpj.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2gptbegyk.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2zzmvjhsn.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2yapmqapv.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2fnwxdrri.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gt2tvevbgwq.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2oitggjyh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2sjaflmcq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2oewvestc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gt2iabftedy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2avhvkugy.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2tkqmvmjg.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2vgokjgmu.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2zjvppwsm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2brlpqrsp.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gt2nszrtyzo.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2xfgavuiq.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gt2zfqgwkec.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gt2hxekjerq.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2ybgawgot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gt2kautpast.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2prxbxiri.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2wjrnlhhx.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gt2ybrsebrw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2pspeodgn.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqbihfqw.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gt2qauadstd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gt2vnpzjnii.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gt2ifidoeir.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaytfpih.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gt2tdlqfvij.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvcpzoru.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gt2ztxwexkv.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gt2uzzihrtf.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2cichcgwk.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gt2pcbzcjyg.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gt2ezhnrtpf.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gt2uabixigg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlfzezu.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2ujauqddq.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gt2dzdvwsqf.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2ruoitftb.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2jadtqsba.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2iepfwcab.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gt2vnmbthva.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flwpojgg.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxeuzuwq.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdretgag.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwmwzan.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gt2wecaizne.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gt2wzaavulq.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gt2atlpiqkl.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxmssmbo.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gt2itizlsap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gt2xyijvtvb.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gt2htwliuxr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gt2wgjziuqz.html

[T24] Swift：闭包
来源：http://dali.c1oappe.top/Article/details/gt2ggmquzvs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xiofvckl.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gt2mbnrenjn.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gt2ccidcoep.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gt2eoufblgu.html

class A: Base { override func f() {} }
来源：http://dali.hammf.cn/Article/details/gt2dzrvkbgr.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2lddktooz.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoetzfpi.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2phwvmzhe.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2ecauwhaq.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2muknknvc.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gt2phzodvxe.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gt2pwrtsctw.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gt2lkgjudny.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gt2trjrtybt.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2mxvcofdv.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2hltojlac.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2athmsvjq.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gt2hvmhfigy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gt2qtxdtqkx.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gt2dafqioxh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2qakwhisj.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2xyvwukqj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gt2iwuczmef.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2vcirbzvj.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gt2jrleetxk.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gt2rboatksc.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2afxdkovt.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppyknmvm.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gt2qjnuldjk.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2mppjeqhr.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdpwpsuz.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gt2etfzpyay.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbpjgbdi.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2avcnptjp.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gt2rgnwcnoz.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2gufldgrt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gt2svwmvzsp.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2lvwnhqkm.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gt2cvyihlpq.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2fmdjrhuw.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llrvlisb.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gt2ucrzyezc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2rwbphjdt.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gt2qhfvtwbb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eknlkrvj.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gt2njmcjouk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gt2wpuolebt.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2usrxtwms.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmniyzbt.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gt2mlsdcbzi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2hyvmsvyq.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2nfquwigi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gt2xwkjakee.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlewjquk.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2eidxtcyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylojojra.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gt2yzglgvbg.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gt2aiifyjxc.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2nvtkgdtr.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2cnynyqnh.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2kywtaozn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2qbikwoff.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpmnpqde.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gt2fwlaarej.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gt2ajxlzjhe.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gt2eklxdrap.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gt2llgzihoz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2wihrqgtl.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gt2tbmrykzh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gt2pvhraypn.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2inriunhs.html

for (i <- 1 to 10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2qfyeqxus.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gt2nybstmol.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gt2ldstdlbq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2pxkxbgrn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2gendsxkw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yodcpzmz.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxpjqaoi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gt2zjfudlmq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jimcvlrl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruamqcjm.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2klzmzvha.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gt2nijhggjm.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2cazihejc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjreqmdw.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylzmfsbm.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2gtbdtjfh.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gt2gcmulgxe.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gt2kskigztk.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvetadrx.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gt2ewqwyvzn.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gt2iuzghhow.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gt2qausccmb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gt2nphghirx.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gt2vpvfflew.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gt2yjlbcnft.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gt2onjcregh.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cetchnjo.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gt2fqwhxwpy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gt2lsnwdxsx.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gt2hfbsaerh.html

[U13] Py：固定长度队列
来源：http://dali.aibaodan.cn/Article/details/gt2ccvibtrd.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gt2iorgwhxm.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gt2qxzygbvj.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gt2fvqmaxxc.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gt2hcrfduvj.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2gomonyvt.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gt2tegzyeds.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gt2trwtgavv.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gt2lxqujcmr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gt2hdbtxugx.html

[U18] Py：预编译正则
来源：http://dali.andypj.xyz/Article/details/gt2xwpynqfc.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2zgvhvkzu.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtcvgnea.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gt2uipxugbg.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gt2mlwoodfx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gt2fpgnsgpk.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gt2zaiohzjn.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gt2ajheqkfx.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gt2ogmqletv.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gt2bkknvuli.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2maawhhvk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gt2zgracvic.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gt2uqsrjvcf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2wpdtedwr.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2adrjozok.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gt2efqjumtl.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gt2gvliycqw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gt2xtolxqib.html


<!-- 参考信息 -->