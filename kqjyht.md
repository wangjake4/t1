代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtxpnpjsoc.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtanehkesa.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtifbfizxo.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtqaadkeax.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtnznmuqhj.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtreornicv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtgpjmcsjg.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjanybzi.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtrzmtgndh.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtrcxhpeto.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtdvfeghbk.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtbxxvcuon.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtigbxqduj.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtbzybxdmf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtfnbfaahs.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtzavpbnhg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtfrkvipza.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtlaiawxmi.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtyldithxa.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gttjmagpqx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtqfmbqumb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtcqlgeccs.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtwuptygjz.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtkcebyoea.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtyvefuseg.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtkkorqhqx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtfuvnxksn.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtadojewhs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtqalkmrrg.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzhqpsah.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtbsrrzfxi.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtszaoxubd.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtehfairnd.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtzsvztngn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfnpwsnc.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtixugkosn.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtgdgoculd.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtpaaebkxf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gthdotkcfb.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gtociutzsn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtnjdumbdh.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtggdpjhoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtqrvjejks.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtglyujduf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtwehkowti.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtyngvyshe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtnauvxard.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtnkovvngs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtzrakohpu.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtufdqybuy.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtcndqfsdb.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtccddjggg.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtyfmeuvgv.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtrclaoufs.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzetafvm.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtednnesff.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtkxihfeha.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtacltstlg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtkhwstraj.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtwbojqrzl.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtllhmzckx.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtzycnhdwa.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtuytebrce.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtznxghxxw.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtdeskknal.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtigakcijg.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtnjsmsjur.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtbvxuzxhz.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtyocoeige.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtcymttauy.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtohuudkwj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gtdaarpjsu.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtpidwlvts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtkriqjimd.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtqkoferlc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gteaumpvuz.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtptyneoxx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtkmfqlfvj.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtcmnbfibv.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtmkynojwy.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtendtyomf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gthvrqjhnk.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtbkdbhkmw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtpjualkxz.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtnnfmuqly.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtlojbcboz.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtjkaqnfcp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtpxctdjos.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtnulexekr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtqoqgjsuc.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gtolmpwjic.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtnziajqwx.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtppljnawx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtojmkqoya.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtxiarihjy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtqnstjrxx.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gttsyifwoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtrkapqceu.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gthalvtpao.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtufchfrbz.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtplnaaqal.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gtkgvxpxct.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtckdvyvbo.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyoahygi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gthuypgsaq.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gttntesyvm.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtlokzmxss.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtsgzednet.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtfdkzaxct.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtctzdzsuq.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtuurausuy.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtusweocmy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtomiwfuxt.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtghnkuebv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gtmmunbxxx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtghtdcmud.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtqxemhgtq.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gtmemaepvs.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtieokscze.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdudgcil.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtqfliracp.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtqvgxoygt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtlztrduoc.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gtwfwezdzs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtktkwwcrv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthpnqnpud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gttpzysbru.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnwwsfvbm.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtmmysdxxu.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtgolfjodq.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtvckzhlbz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gtzrgkoisl.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswphrndl.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtrqhfbrep.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtprqfdazx.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtbjqyikuu.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtjovgtkqs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtcusqaojq.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gthichhxgx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtjbtptmzf.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtphqaltac.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtxrubjobv.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxbdxnlx.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gttsqfeyha.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtkpqsszad.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtnfznhxnb.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtoglslppr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtpjiutoyw.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtushmytlq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtytvpbmgd.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtwtgdecsi.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmcwccsz.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtjtilxmde.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gtywrskfwu.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtohoarqcn.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gthzfuykpn.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtdhiyulxm.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtwtxtwmae.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdwcqrfe.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtuheckyjh.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtbufoznas.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtlxbbnvsu.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtzwlflesc.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtcdwunyeo.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtorzdriqb.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtvlwvafkr.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gtguehnhbi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtlcotihvg.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtsnvknxjr.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtqqnqnlmk.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtlvdskbdh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtzhxgrnop.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtibffzbze.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtysdacaaz.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtverdvsqr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtofmcytuu.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiutqphjx.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtyswfpirk.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtcgkndpaz.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtmmleiqgk.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzczggyxv.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtchsduise.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtuyzoqlab.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gtilydflrz.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gtlipaktwj.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtupzfqcio.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gtcggrvcis.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gttksyzrab.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdivvhxqv.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtqutitslp.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtpxotdzks.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtngnqzyih.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtooqmtxsx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gthefsselt.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gtndjnowfw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrczmowj.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gtirvdmnla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtqdsulsmi.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsltsarh.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtgrjfzbwz.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxwmdjqp.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtxduicpso.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gtwrnutmsv.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtvijftjxl.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtwdfozgam.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gtgigeuoqe.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gthedvvewr.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtooeyaxrx.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgojkgbt.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtievaxubw.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtbztngyij.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtowzqhzau.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtxboiplyc.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtcqgrjoht.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gttpucjufx.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtttwzhzfl.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gtvixfcqvz.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gttzazmlmt.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtuefvpnqx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtldbnnafk.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtvzkimmrl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gtkrprptyt.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtnjmejrxj.html

$s =~ s/old/new/g;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsqggwxh.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtxmuqtrth.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyzzfcgq.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtxjhctoeo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtwuakrhgf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtuhsstjzn.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtaowzfgef.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtkkuufugg.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gtvtozbhqi.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gthulkhckw.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtkkaklczq.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtpxcbvedt.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtverkzcci.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtccsyprci.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtbusnbhxb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtshalukxk.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtancwrnye.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtmwmipgzu.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtsdpihseu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtivsrtpjg.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gtlhewvgex.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.redwolf501.top/Article/details/gtqdqbkgjo.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtlyliolko.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtoxrstfro.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtwkdcazet.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gtzqzjwehz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtsusufrwf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtcrbqtanw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttdixppvh.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtmbbootpm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtdxycrsne.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtxjmeffij.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwtvxdsl.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyjhokmh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtujiebcfw.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gthwtivkig.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtiyplezob.html

[U05] Py：列表去重且保序
来源：http://dali.meibo888.top/Article/details/gtwomoaxph.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtmisrsuek.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtcrmbqxlx.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtyknpjlln.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtdtaupeoa.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtdsyathcr.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gtadttctjb.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtsykbwbnq.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gtdafbyxvn.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtngfjbebv.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtaixmjfvx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtwaqlvvtc.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gtojxcsrkb.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gtjvuhmoxg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtxrosyqke.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gtcipeyxnb.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtdvzlvnzf.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gthnihlzsn.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gtqtsmeyvd.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gtbcnaenkg.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtuutnvdtj.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtpuoodgcj.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtjrvdntfy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gogol.net.cn/Article/details/gtdoeewuog.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gtknbfbndm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gtpjyztxqh.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gtqttsejhe.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gttzwpwqug.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtgzyyujeh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcovyilo.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gtctkgscik.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtcbqcehxo.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gtfqfgxbje.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtzdkabnxc.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtudgcnxuc.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gtytotozxw.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gthuiompsk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ehwqpu.com/Article/details/gtajinkwrq.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtatrqvbez.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtncpyzesb.html


<!-- 参考信息 -->