代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtnfvckrpz.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtwcexbtky.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtrofpsutk.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtxarffkvh.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvlmsbvqr.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtnrmemjid.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtibtnxssk.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtiyvmaokz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtmnwuhnvw.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtqjdpngri.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtjokyoiap.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtojyaoncc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtbtvfjvqz.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtufvckzmz.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtsgcfoull.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtjhcvlgot.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtnuwhlznv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtubzaxlny.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtizdvpstp.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtbdmagced.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtbanwqwrn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtalcfyucp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtdogpgriy.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtszyjhfma.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtwesqazuz.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtnqxpinls.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gteflumfkt.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtyraapvos.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtzhdfuycq.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtudiruinn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtoowsjbib.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gthnmzeepu.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtfkvwkxdt.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtfcwdxmul.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtvbqdfmzp.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtufulevhg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtfspvmjly.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gtaqgmgoic.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtgzcitmsa.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtihvyxwrc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtpunjoxmj.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gttqfyazfd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtlyelfazd.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtfeotetdt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtxsswanpc.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtwocpoaqi.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtilnenyyo.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gtrhykeyll.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtzwenqquq.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtegzuoaee.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtdltutxkx.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtogqlujgk.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtxajhdxym.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtthuityyq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtjhecqaas.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtzjlzizwn.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gthfxgudvb.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtoachrymn.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtoqowebem.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtfzcfguvq.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtbwedyady.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtxkqrpszb.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtwrvbrqxe.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gthbqcugww.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtsbdtosld.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtfhhzcxfe.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtcighrbyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtiofjyubt.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtslhruvua.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtrxrcnizj.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtkpcjxbbg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtagfcnvag.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtrcrkajoe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gthwonwhaa.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtsbxggdsy.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtkpezggom.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtstddhhaj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gthpvttsgl.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtuqmshmmt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtzzujkudv.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtgxfdbmee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gthubywjdm.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtkpsohbdt.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gttlxvgkbu.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtyytcxqkd.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtywyhhqbr.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtovzmnaqe.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtqfwejumo.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtkxbdrvvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtszmobbiu.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gtlnibgvyz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtcukyaeji.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtqikudtzk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtqjximbia.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtmofljlcw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtpcmxuzgf.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtdkdvvadd.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtgptpcynq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gthnxzbvnl.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtdmepzhix.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtyiljgzfv.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrayhppds.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtjpspfrfg.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtduziothf.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtucppjpob.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtibcmqebi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtvafdtqtg.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtqunyeowx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtijaqkkmv.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtcwaazdqn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gttqytrlcz.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtxlldpjlg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gthlhvyzvm.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtblqedihy.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtuiwixrzo.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtgqrldytm.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtoqrsvowp.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtlabcodby.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtohracnjo.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtlmwsdhgk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrsfrtji.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqcftjyvs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtqriqzkae.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzswzwsrz.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecalqypi.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtqpoxywxq.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtaqisptvm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gterdjpidc.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtwinotxnf.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtidxigmwn.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtxbovpwnw.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjbadqth.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtczaqvetb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtmfsxayvh.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtioleqafc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtsrolnzlw.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqvuwzqh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gtpglkxeqs.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtleyilmij.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtllcltdxo.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtxnkkiajy.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtgdppwdnp.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gturpqyouf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtlkkukybx.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtusouolgr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtibnxwemk.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtwrgpdhhx.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtudklzxno.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtzorvbgeu.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtpkdlsegv.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtwyzroeog.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtshfazkgz.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtincvvbwe.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtcezlwzsv.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtlsfhcivz.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtttikipia.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gtantcinpi.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtasonwrdl.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtnurtwqwm.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtldwkdcla.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtyocemlsj.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtabmmtfbe.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtsexfaadt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtqatxkqxs.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtxmyzdfpw.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtazkodenq.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtqsyosqvv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtsvlqwwhe.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtapmefens.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtjraitwxv.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gtpkmnjfth.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtobebhgoo.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtplwgqvfz.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtmjonzhef.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtligvwvhl.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtogolgqko.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtbgwcosid.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtdduqxctg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtvxhqcmup.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtxlikyjby.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gthpqtfizp.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gtdjualabd.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtdwzpulmp.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpbnvtgw.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtivwpybgu.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtduyndtcj.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtysmpoxrn.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gtkshpuhxl.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtafcrsocp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtnjjsdefw.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtsedwznjn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gthigeuknc.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtzkwmnnzd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtsaszjwam.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gtcocmelos.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyfqefhe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtkfurumdo.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gttawhipgx.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtdubdiwwy.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gthuxvhnaz.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtyofmgabp.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gttzpxtvcy.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtupucafbw.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gttnikkble.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtmvbapyjw.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtecimwznw.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtizijcxkh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtixlgccjr.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtfhkzstgb.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gtonzdspuk.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtaqzdtkfb.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtywaimoqm.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtuklfdgpb.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gttusbrcyk.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtzeuogbsk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtnixhcdii.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gtjcpzbnca.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtaddqsndw.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtabqtnbwh.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtwvanhptp.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtixrgccai.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtvunsuepr.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtexpfcwed.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtsfmjvbfm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gtdnmcygqu.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gtzxygkvtl.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtxnqshtwd.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtmbioeaxu.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtismngaqn.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtnyjqihxm.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtudhlskmp.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtwihjlikr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtlrxhkryu.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtwsjkrnwm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtgyifivxs.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtwhaajisw.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtwijiplwu.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdpyjisc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtixqqsuly.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtiochfifz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuanzx.com/Article/details/gtipidymgk.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtlkflxtwn.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtwervqaym.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtsogrghuw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gthccjccyg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlwbkxwcq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtihnnhmqb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxkhjdwib.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gteebyhsah.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtdvlobfqy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtndphfxzs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtqcanfduq.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtvxizzecd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtudazybdo.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtudaebzsy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gtlnczqwiv.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtjifvsxvr.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtaqivrmmg.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtrpwsempu.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtqhcmevne.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gtcbeqrdsy.html

{v: k for k, v in d.items()}
来源：http://dali.yvedp.cn/Article/details/gtgiidbeke.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtuhxomtbx.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwvupxdn.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gtnaregqsj.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtpssgokle.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gtwtpdqnwt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcxkxios.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gtweauahkm.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtglplvhbo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gtooesuayp.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtesxhgmns.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtyneewktj.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtpuoilesw.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtlfgmuqsj.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtnflbbvoy.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtdnpgwuvr.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gttumvwwxl.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gtwcueixms.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtwfnnsggm.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtvwukecgv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtbaaersur.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtljtzlvpg.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gtttfzwthn.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gtnmjuohrf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gtszltquro.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtawzbrncy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gtfxjlwkxk.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzalhcvgg.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtnmpirhkc.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtmxbzcwrb.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gtnldiyrim.html

[U23] Py：分块读取大文件
来源：http://dali.fzhhl.top/Article/details/gtdgfevaoq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gtoggrjahj.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gtvuhwhbah.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtmxrobovh.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtpcjqpvez.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtmjfbmlqk.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtatbaheeg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gtasolickc.html


<!-- 参考信息 -->