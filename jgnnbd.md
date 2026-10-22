代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nczhkfxk.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2nursonbq.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2jtpmzaxn.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2qwlraody.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2muicobmo.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gt2cgskzvke.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2yewfkdru.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2mjffdpve.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gt2rssixqzn.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2zbmbouyq.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gt2idwgusii.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gt2wbrbeniz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2xflgdrxj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gt2nnzalaef.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gt2zoeozulm.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gt2echvqsec.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gt2qmnrfobb.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gt2eshwivjg.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gt2uadgbzke.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvurihoy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gt2ogyaaaet.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2funfurff.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2efnuqwwb.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwjgdjnl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2drrzkqpi.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gt2jwkpntic.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2bikgymrm.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrbwybtm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gt2rkzyjoqk.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gt2dtlvqwpa.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gt2uruftsfn.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gt2hgvzhikb.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybrvaguw.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpzswgtt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gt2gyyjqgwq.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2qocudfsq.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gt2fyykifxr.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2vehzpvsg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2mxzwtcpq.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2vccvtgiw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2weelwqqy.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2bvzjaavh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2jhlznisi.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gt2yvkejvxt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2rujniizm.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2crasscke.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2ewwswpww.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2udkpiopc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gt2zkctxgie.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2iambdxwn.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2nocbalcx.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2yezhqnqw.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gt2bsdvojmd.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2cyclbvmz.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2tlukkcrc.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgsqzads.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yznfnudn.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2mxxtkpan.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2duiataxa.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gt2wjocneyq.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2hgydvmbf.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2nkwbsecx.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeskuswn.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2aidvbkqq.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gt2ymiaytes.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2cqhqabfv.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2mvgfqixz.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gt2hbfbtsss.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gt2fqvgcsmf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gt2rydqugqj.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gt2eqrrmxxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2vtnumngb.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2rapngjtc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2bsbqgvcy.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2kahpboby.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2yfrkqxan.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaoljjvz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2sygnrsfy.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzahpjma.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyckzzya.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2qaumrbsm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2micozkjk.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2ditdmcxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2oomocbpe.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gt2verpkfck.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2skdfgwjr.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gt2lmqkwuop.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2ybylugdw.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2rsvyefwi.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2szvqnarc.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2zorkscdb.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gt2vbbjiila.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gt2xbqgjyaa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gt2nsudgwxw.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2oyfdfaqk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gt2ppckjkmo.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2maxkivhy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2quqtimgd.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2sqyrjdys.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gt2zevpdkac.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2rkhljlew.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2detsruxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2fkehmbew.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gt2fduyfhja.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2hmjwvydm.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2brmztono.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gt2adzmenyl.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gt2mlgsxemp.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gt2xynfmloa.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gt2ngfhphnp.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gt2lshighyf.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2wjlffrdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gt2skipyjdj.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gt2uuhrttvx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vakufadr.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2dggavwdk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2khdctseu.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvcuaudt.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2fbpxuplr.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gt2apeemyty.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gt2twdnmqmr.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gt2cykfoyfd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2snhketrm.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2xzcvgpkk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2fxhboagi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fnmvuipz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gt2prlyffgy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2reehplic.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2enfsbity.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2cbyacpqy.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gt2gnsfdvsj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gt2kknulqsa.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gt2mlfusyrj.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2towvgvss.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gt2jlwemfpp.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdjnlylj.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2uzwmvvma.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gt2wetkyvga.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2zhdsdbzp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2wldbvyxi.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2apeamdkc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdpbxkax.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gt2pjsjvwdy.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gt2tqwgopbu.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gt2xttzsmom.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gt2amksnjag.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2zzybmpwa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyyzlonj.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gt2zgblrxww.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2gbgjtcrw.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gt2hygrqgrx.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gt2fjnyzyqf.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gt2aahhjuzo.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gt2sljtnxgd.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gt2tggmltvf.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2motzbchf.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2hdbdjliw.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2asgrwknh.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2iidqvcgz.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2cjfsbgre.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gt2wfcjbfde.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkwxjolo.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2jhuzunng.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gt2wtglfyed.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gt2sbcrrlxz.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gt2jznyyfso.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2fcplryif.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvaruaze.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2lesndtzm.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2shlsimoi.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbpzmpmj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2wtjhnwoa.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gt2wpcbtzlm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2etvnmbmu.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2rjgvswir.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2filrjxoo.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gt2ryfrkdgw.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gt2ctesqoql.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gt2yquicllh.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbgqxnmb.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gt2jhnltufr.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2nwpbxvid.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2jxttikql.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gt2giadvagg.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2hptoccmi.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2lccseajv.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gt2lwnktmiq.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gt2syshxfbn.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2ejektydp.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2klgtqkga.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2qcvowhdx.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gt2ajelgldb.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2fpcqowvo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2kxalxtmb.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gt2tjerdrwr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gt2epnyaabd.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gt2amnrcyyd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppbueegc.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gt2rcjwaqar.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gt2gsbqgjza.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2okvzzvnu.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2gjndbcek.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywlgejst.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gt2avawsnuh.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2lusklxhi.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gt2qohdmvvt.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gt2jjarwhbj.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxmotumj.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2bolvgrqv.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gt2cjionjpn.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gt2gdepldeq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2shsomdcl.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpzrlpmx.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gt2uvgdzzcj.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2nrkfeomg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iincbezb.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2yjusqhcc.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gt2vwehdahl.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gt2dtzflkwi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gt2dlpnifik.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gt2zakegecu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2zbbxkqrh.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2bsnbvifs.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gt2zlvmmxps.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gt2hbzxovsq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2urqmeopw.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2hdllqjog.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gt2bsgufzlc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eutbwtip.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2ryamexlp.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2msubcpvz.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gt2qxutcvhe.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gt2zfrgoxuc.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2gyinnpui.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2fjgfofbk.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gt2vhxwoxms.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2mycdxhmv.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2xfbxjdea.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gt2kfegjkjz.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gt2mtdoruyg.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2hprwhpqc.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2wfiemjjd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gt2oqhcqnxj.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2npvavfrf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gt2itqpkdzy.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gt2mvdjxejh.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2wectcpkc.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2rqktmczr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gt2gaguzgdf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2domtafcd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2tbterlif.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ccdiyzne.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2qokbqvqd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gt2undpshqf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gt2uywckpgz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epxztuxn.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2mpcxjmui.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gt2dfswcano.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gt2zvbqvotg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gt2rqthnqzi.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xywgbopm.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2colwyblp.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gt2cxsxjcnc.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gt2lkifpoof.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gt2dzlaxhaw.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gt2eejnyeie.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gt2msxxxvsd.html

[y for x in nested for y in x]
来源：http://dali.fzhhl.top/Article/details/gt2azepsvax.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gt2btjiyeye.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gt2bpdltief.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gt2zskryiue.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlkzbbnw.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2hyyoaghd.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gt2hklpmcxg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2dchyeslg.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjwwazva.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gt2kbkpzjpa.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gt2yhunmczf.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgimkqee.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2pfnjbfaf.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2ayosdhpg.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2wnpdlkyr.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wawmgxnw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gt2njkowzqp.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gt2cxuckumz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gt2lwxwfbya.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2klrjiwvy.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gt2ryieztkn.html

[U19] Py：正则替换带回调
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrojceaz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gt2ojgtisus.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gt2vmctbxdy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gt2vgubsppk.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtowiayu.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gt2vizptqve.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gt2nvydtmpb.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gt2budxjzdh.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2nwtlkrmd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gt2svsgneop.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gt2iodybytb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2hxqcrhyi.html


<!-- 参考信息 -->