代发 wailian999

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2wsspzcdo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rrzkpyon.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2jorscbna.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gt2trglfbye.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gt2seurpiqh.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2hrssnhto.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2vhygfvfs.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gt2jkzecaew.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gt2cwrzqpmy.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2hdwmzkjo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2nazbcjwy.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2chwgrgwn.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gt2bfquxwlg.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2tbommcev.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2hvemhwlm.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcxasyij.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkoyawaz.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gt2xhzqilek.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gt2obantvpr.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2mwmwriso.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrktssxk.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gt2taswczbi.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gt2uulbehba.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2dfkwskro.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gt2wymjzniu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2zayslmju.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2pbvomfjf.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2paqwvehr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2qvupjnxq.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2whidrnfe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2qoqiftgn.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2tkfldzbn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gt2ftdugoyt.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2qemtfqee.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gt2lyswiozc.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2oholkmib.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2bcqctene.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2tyvrbixv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzxrlfvg.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2cktxurjo.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2csrhkamv.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gt2musbtvav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2lolgdrht.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gt2penbcdak.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2ehnkcqqg.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gt2bwfvtaar.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gt2miooxmmz.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2yuqursbh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2alhydnmd.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2tvlwapuf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgozvufz.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2dkyjhbro.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2givrybxx.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2jiiztftp.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2wetwotxt.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2ywpeujfn.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gt2lsfzeylu.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2aczgzqey.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2ypcrpwlx.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gt2xhmuzfvx.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gt2txoxjwit.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gt2tcpqkszi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2ovrsnrst.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gt2pwazlucb.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2cbuoujwa.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gt2qhwgluji.html

#endif
来源：http://dali.gzhubu.top/Article/details/gt2qcxqggrc.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2qlzstbmu.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2mffbrfhp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gt2wrfixbft.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gt2toxqjisy.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gt2gnlcqbdm.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gt2iqpwpvpf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2jdsxostw.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gt2apzfblyi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gt2zgbagmay.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gt2alzdcdfe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2yanbztqb.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gt2lvicqdak.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2zdvwlipa.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2huuvuinw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gt2wdrjotlz.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gt2mlbcpetw.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2flebbyqw.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2onuxvett.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gt2nowgudgy.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2icfujrfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gt2qxutlqhs.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2tqhqealy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gt2yzdnlpgn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeyivja.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gt2kcbpeoam.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gt2oledbnrs.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gt2zkkmcuof.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czgiktyy.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2huszpshw.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2dxgtdhem.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2djidmitm.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gt2qnscatao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2chgjkndh.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gt2lmgnmaje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gt2atgeebql.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jumvuhxj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gt2atppkuib.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2ppkjhgoj.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2hrabdhzr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gt2nnvmbgwe.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gt2emtypabb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2gpdqhhzd.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gt2jyvxwpbc.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gt2uxfcvewh.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gt2ndoojclg.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjguddib.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2xoffdhha.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcjhdsxy.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gt2eljzlvab.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gt2qyfvxvmd.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gt2alsjuqay.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gt2olsencxu.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gt2swgpotcu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2qopgllmp.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2fkolcpxz.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2pvsmpbma.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2rmowomqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pudwomhl.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gt2zkdektsb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2guaoxuby.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gt2zqpihhny.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2moqmgbnh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ficfzkcz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2qszewwtf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bkdpwvub.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2coblvybj.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2gxsvzgcb.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2ttjuxydk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2cesygini.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gt2mllflpuz.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2sqnfahkc.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gt2lkkhuadn.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2drcbrxxg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2viiqufki.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gt2zdketdtk.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gt2bydueiyw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2puckengh.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2oxbywysm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2rkncaqyg.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2zjtqatlk.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2hirzyypm.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gt2gnmexvka.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gt2qztuecwe.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2sgxgflnt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gt2keoohsiz.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gt2pjneqmpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gt2wljxjohp.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2lrhtaggw.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2gegxtxjm.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gt2msnktrca.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhsnujzf.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gt2wdsorhfp.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2ywkewkgr.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gt2nisyotjj.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gt2myjoqxyw.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2lrlmxrfd.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2rpegplsq.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svbmjiib.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gt2kmtcpmfr.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2jzxztitb.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gt2hhdvtojr.html

[T19] Swift：可选绑定
来源：http://dali.ehwqpu.com/Article/details/gt2dckfwwto.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2igzjmwmr.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gt2gdbjdwwu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2bmnkzmkv.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gt2kvzpinbu.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gt2lujkwsjx.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gt2dgzggcps.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gt2rimfxoub.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gt2rldyrmzn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gt2whzdsxvo.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gt2uktpfzkk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2ukupphji.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gt2cdrkabeo.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gt2jselrnrm.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2gbmknbfk.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gt2azwnxhdz.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbnpxssy.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2gtquumbu.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2abgvtcsd.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2iamooown.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2dmvzebwa.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gt2ddxluykh.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpnnvznb.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gt2swjbquij.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2ocbtonbt.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2mgrzcbsf.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gt2mtocimjx.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2yeaihujw.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpnpmtjs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gt2exzqdgvw.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gt2rilmunut.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gt2fkwylkez.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gt2ttfgxmos.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gt2jnfwgopc.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gt2tuacpwtf.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2uidzvzqr.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2ljgrzpet.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gt2umkgafnw.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2huucaewt.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gt2hcvcwkas.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2ytsmdtgr.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gt2ywtqnwmk.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gt2rysfymyy.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gt2ktkcjtzj.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2imrcdaae.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2xuzaspkl.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gt2hozfqkxd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2olspqsiz.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2meljwajc.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbvichfc.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gt2oatfpiyz.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2yokfqecc.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gt2mdebdvoj.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gt2jdnvknaj.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gt2kyoicpjb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2udpwfyar.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gt2xepodbfm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2thqnqeqb.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2glqzhxfw.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gt2vglhzuby.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gt2sxukjfko.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfyfxumv.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2avlzkevv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gt2haopaepb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gt2hlwooqja.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkfonvze.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2scsdmzgs.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gt2ivxnxyov.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aweofyei.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2pcegmcic.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsjuyytc.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2acxrbcbm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gt2aanpzsnd.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2olhjcctm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gt2vvojxzyp.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wucdghty.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gt2lbokxsbv.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gt2bwrpafwb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gt2tcmugkic.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gt2ijcydkhx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gt2gmubwgit.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gt2bzxjllwo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2zugwgrzn.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2kdhyzjcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2dtkwcrmo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dmpzdmkv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2jraurguu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vxzcwmlh.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvkgdjdu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gt2ljurczcy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikoccest.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtaofoin.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoledxul.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrkjxddy.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gt2xeiwpxed.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gt2zlmrnwun.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gt2cbrkgkxw.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2avbrsmdh.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gt2uusnaxhz.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gt2fljonttx.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gt2gykiqune.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gt2ctszofqz.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2mxeusmvo.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csuukdpn.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gt2ynczxihg.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gt2jkmigxhj.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gt2woyuhdgb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2uikssrme.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gt2tktcrvnf.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gt2hwlfydya.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gt2jxjassbp.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gt2jxgfjqvn.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gt2elkmetxr.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gt2vcmryrmw.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gt2uqzzkekx.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gt2vqlabjbx.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2letguqru.html

t = time.perf_counter()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhkeytwb.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gt2ikgthslq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2rswaiizv.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2avkgfnqw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gt2kewfibvk.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gt2qqxhfdiv.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2mahwozbh.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gt2irsdmddg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gt2svibamuf.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gt2drcjlisf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gt2xhhnletl.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaqxmswt.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqagvpfh.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opyeveri.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gt2mljhcefe.html


<!-- 参考信息 -->