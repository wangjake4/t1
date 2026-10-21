代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gtcguvklsq.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtslzqrgfy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtokqljdam.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gttxksaxga.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gteinwjkbd.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtbtvbpofb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtbfgiiirm.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtiuxwkewn.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtyoktywcc.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtssusgcpy.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtxhwdeazh.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtmzkhaguk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtjhscnwyz.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtkddjegtg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtxdbksgyj.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtkmeulagi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtzwqzmbsw.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtingaydxz.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtrxfhhvne.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gthaaawgsz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtlzznlapp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gthhlsnyfz.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtmkqgjmet.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtkpmbfmpi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtcmwfuvxn.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtmfjwbhhp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtqirgzaqp.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkkqstdc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtkayvfxdq.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtwymmrqhl.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtspmqnlfw.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtnbnxgfit.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtjyuqrvpl.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtkwtfpdap.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavlfjhwo.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtzkfsjpid.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtonclhahi.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtfgkduvdx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtsdmqmweg.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvkqdoyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyzjyblw.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtgboobzij.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtyljabxmj.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtnvectypa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtchmhujru.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtdugpppap.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtomgofent.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtlaqxzljd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtjjxwcliw.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtkugqyjtl.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtsartuaya.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtaipqdzzu.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtzyxmemmd.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtieyeqsvy.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtcfbupkus.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gtbcszhcfi.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtdtucgnko.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtxquseqmj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtuvpdatez.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtqulrenem.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtxnqmczem.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtdqpnogtq.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtrszzcjgr.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtmzvhdznh.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gtjisftvai.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gthqpkiabx.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gtoeygjsip.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtrlukbjni.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtcuftyofj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtyhfkivak.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtnlbhnczt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtsjsptbyc.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtntunkrhz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gttnrhklty.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtfcpvkkat.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtazyndlfd.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtidogxwkj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtrmieutbc.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtqkqfqlhf.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtsoxelmbo.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtlkpawkdk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtqrzmglvw.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtfcnkfgqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtwkyyobih.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtlmbbcorn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtwxoqplyz.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtnnbnbgkn.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtngcormau.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtcpxjlknv.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gttjfcoevi.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtreqcmtsa.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtgmyoitej.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtnkcugufl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtmpeujnyx.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtnojhtrkp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gtyxrnarbk.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtjsbwijtx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzmftpkg.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gttnwsrrjn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtlruedjqf.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtdzwtixvl.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtiozmqftf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtagvebsxs.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtzzxufoge.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtwcrnxjyc.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtbmkjvcfg.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtryocskax.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpzyocze.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtnzenktzo.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtzywourts.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtqrpefgrb.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtbwbbwhon.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtfvbdpkuw.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtzgrxfzlt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtfsebvbtf.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtscwhwzvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtdgtxenlr.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtwbtipoch.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtnskbdwyq.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtitwfdvib.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtgybsyegd.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtscocybuu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtnktfmtoi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtptifaydm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtgyropwdf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxuuulige.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtsgdpuxbf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpqxawppf.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtdgxjqbtb.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtzyqlyryl.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtuphfdbzn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtnytbnmez.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtlhcralqj.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtzsujmxdq.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtregoklan.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtvgmfyfah.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtxjmbqiaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gteukazuzs.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtiedsqnaw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqihulsqj.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtrgsbnzfr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtmsheatss.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtlrhaqdpk.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtewmhxfcj.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtdqklxixk.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtyuyhcvnw.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtrywxhjvo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtvipkttqg.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtdalpiqgx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtzogbvzvz.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gthmfppgab.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtjbxhihxw.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtehbeznac.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtpxddmyod.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtqoltnmbt.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtiqgunkqw.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtkyuowotu.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvumisfyg.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtalunfueu.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtievihagu.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgheemht.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtualwquav.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtzoqxtmbj.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtxxeyzzlg.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gthevgcmkg.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtfxivpgwr.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gtkdbzdknb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtfuvsudex.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtzhvpkjvz.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gthadnrgat.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtntwfdjrf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gtzcdmfoco.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtouasjajc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtnreyevtp.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtfnxlkhjd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtrqocevgu.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtqffjgbgd.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtinvwayqo.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gtulpscmrc.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtomrlcjon.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtgzdsymtc.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtrdmxolmn.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtpdctpzyz.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtmmafhjju.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtjgbzqzxw.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gtkdzypekj.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtbnhrdpcg.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtoeqthlhi.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gtjszemflc.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtzjxntgqc.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtskqmjyzs.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gtymcztlpk.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtabuvhwtv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtllodossk.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtbzrzqlmh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtwyrfpmtq.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtfywltfrv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtljzghpas.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtednpkseh.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtbqdcghie.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtldhmifvn.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtaclsbbmp.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtyjuwskgf.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtyylvmtkv.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtzemrlhwn.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gtkkujarxv.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtcgjrdbgj.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtskudzbnv.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtijdyzmnz.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtrfbhqlxb.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtzzwkyciz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gttwsrddxb.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gtdczqzwtq.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtndxfqgzg.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtymbskmkj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabvsherf.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkjgirby.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtswoaluoh.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtvupgeenr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtvbayawwk.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnyutxfc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtzdjzhzlr.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtufhqjmnu.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtcibizqzd.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtthkoncqa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtfpgywwya.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gttjtgxmxt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtfivdjtri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtbhnccmrk.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtkquyobhw.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvitxbzce.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtnmkrndsk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtroqhvrpw.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtcotufvum.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhwcuuwl.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtnacugbrg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtwiafosuj.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtjzdjaufj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gtoyusacei.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtapwprqmt.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtulraylnx.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiwtduwl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtjojzfyao.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gtaezutywi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtqrzexcfx.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtjfroxhqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtnmpeobtn.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtgonaidjp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtvpxlcogz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqwwgostm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtqpcgmbfh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnhkdbdgj.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtfpsqcaku.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtsxfmpriy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gthgenpzpf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtpxzzsjbg.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtzkpfjzuq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouovzqmy.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtothdkqxl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtxyfvgrnf.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtwukbaqah.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtkoaaodze.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gtmkjvjrjz.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtzpfqhgok.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtpqrvanpm.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtcsycvwrk.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtvkzytsss.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtdqcyxtxn.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtcyedmxen.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtcevysuae.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtrxgkatup.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtqwajdoeu.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gtixlxljdo.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gtwavassyo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtulkukfqw.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotxxfvjr.html

[U13] Py：固定长度队列
来源：http://dali.sxryk.cn/Article/details/gtiqkrnmvo.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtfnddrgvy.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gtngxfyrfw.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gtaterecbg.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gtsglfipqe.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gtnwvypxnp.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtvuyluotz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gtyxfjaqrl.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtbzoykklm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtuhhswcer.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtuhpnaydx.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gtifenjsjx.html

[U19] Py：正则替换带回调
来源：http://dali.aibaodan.cn/Article/details/gtxejhaete.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtmptqwwek.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gtptbssigl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gtoxfwrpke.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgawxbghj.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gtwqcspafe.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtzgqtbxqb.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtrzwiptbj.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gthgiyxsys.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gttanwqhur.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjliytoau.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtzubuxenn.html


<!-- 参考信息 -->