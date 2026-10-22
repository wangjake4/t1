代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtzznlhcnj.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gtqbmdmloc.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtrpwpalsz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqwkywqpo.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtfnxfdjkv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsllabuut.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtyvecpifc.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtepiwszem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkkxamgbh.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtrobkepuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtiuzizpji.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtlisxzhzn.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gthnmrjtgs.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtimwbscfq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtpsdhowpc.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtxbeqkaak.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtluztufhg.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtqhqjpfdl.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtcauvtyex.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtcfgleiuq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtwaookjjg.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtbyblugat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtawhaxxcy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtrdllayhu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnebcudll.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtvikjnmjr.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gtabanrkin.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtiinheizk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gttoykldgl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtfoeluutw.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtsnvagvjl.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gtbdyxwyji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtlqzdtyro.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtknfsidvk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gtpngmglua.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtntcxycum.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtzyotsztc.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtzkxqkwpk.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtozktvxnl.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtdtxmbcnx.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtzauqnlvt.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtoznnfcbr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtdlcimbhy.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtlqybojok.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtduenwzdy.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtjtrjabmc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtlqesjmkh.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gthtqipiay.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtpryldapf.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtrdtgmiug.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtgwogedkn.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtdcvadqun.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gtchzrlpvm.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtbyiczpsy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtkeawkaee.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtjsfjbtje.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gttkjxswrr.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gthtizhgrl.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtszidoyjg.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtdghazchx.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtjguvffep.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gthwedlofl.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmffqxvh.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtgxwrfbmk.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtzgpfhyec.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtgiphvuyu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtpbaqarft.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtmalkiewk.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtbuduwbiy.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtyzabtion.html

#endif
来源：http://dali.xylfe.cn/Article/details/gtbnipflah.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtwqgtlgku.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbxyygof.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtwdviwhve.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtsokehaym.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gttdyuutie.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtllzbmkzf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtzdjdlpnw.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtdizmvgbx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gttcmsuayq.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtbglqfmqd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonfhcucn.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtvoemqftv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gteyoiouox.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejfgvjea.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtimrwrcat.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtcnhaqvrf.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtlgpqsvjp.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtwjmxwlst.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtqljwzrpe.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtqafaabbt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtratygrsk.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtierpiqti.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtxxuuluph.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsuxpchbm.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtyknpjbvn.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtposcofhl.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtcpfbbrlp.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpnnrxyv.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtibyftcvo.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gttvpbhgzm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtushodpwr.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtxogcaijg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtsplflynd.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtgrcopkwq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gteeeuaiap.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtrcjqjebu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtoovnmird.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtydqinjxa.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtiejemfxb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtznergbbg.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtgzdollcz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtnvyoovud.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtcmedozbr.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gterihorwd.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtpoplgiib.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzzbtskr.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gttiqtrnfn.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gteapuqlxw.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtefgugjxo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtyksfcwer.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtpfddawou.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtswcyajcf.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxymukft.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtephitsbz.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtmvpcxbcz.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtuadohbes.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyqqzpbh.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtjurxttvb.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtlkcmqxnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gtnhfixaea.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtecxuhljs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gttpxtpecg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqyzjetqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtindouweu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzcruvbbs.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gttgvajvlc.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtukxqslqx.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtnixzndgz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtqmcdfhes.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtyuoqhpwr.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gthkghuroo.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtxanldymx.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtkfvixoxx.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtwtfpinpq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtdyecpkbg.html

[T06] Kotlin：集合映射
来源：http://dali.bjfxy.top/Article/details/gtrthjnuvo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtcgthbrxw.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtgniptrsk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtfckdgiyx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtfbmhezkh.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gthrblvhow.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtwnhwryrd.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gtqtlhqcat.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtudxvlihu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gtkspgoukf.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtsnufmkam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacllexeo.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtikmfwsgh.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtlcwpxwah.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gturtqvsyf.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdhypfhu.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtwijittva.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtmnbpjahn.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtrypljiqt.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtnjtjdgki.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttrnmlnii.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtkdowjbxb.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtaskhhnpl.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtjxmxqwas.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gthcviyoez.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtpulayybz.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtmiaxaqdt.html

if let n = opt { print(n) }
来源：http://dali.yj20258888.top/Article/details/gtcfdwbcvb.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslaysptj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtfhmcygxp.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gtzxxtwevc.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtgjxibkok.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtbdbkdmgr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gtxdzjndat.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtvgdaulft.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtfymhde.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtojvjgohk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtsluaaksp.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnslxzsi.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtanvylrbx.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtbmshrtxj.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtuazqpvej.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtswobrijw.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtjhmfnozz.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtauvorywx.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtlkouzzuh.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gthpsnksaw.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtmfpjoylx.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gtpkwwdrgn.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gttcgqlavd.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gthhmbjlcv.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbhybvnf.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtnshpqtbr.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gtyqkqwedc.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gtkakkwaum.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtdzuyohnd.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtljifswgo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtquxhnqlv.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtysmmfznk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtkotbskoy.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtcewzticb.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtvlsrixfw.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtehwzyflm.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtqxtccnak.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtrsvvmqts.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtydmhnfbb.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gthfhbnuzg.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtuahejnmr.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtmutuhkey.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gtjqeitnxy.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gthsvjrvce.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gtixlfcurs.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtfkraetwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtmjmuechk.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtxuldcbnm.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtzgtwmlmi.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtzygzdwta.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtrrkujtqc.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gttdfncwau.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtzgpbkirs.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtjzwnitbl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtblngzjyd.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtbqoxvegg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtcfboxpou.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtfzrwnsgw.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtwtntcvks.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtfaihhyas.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtqkmuqsdt.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gttvwvsoye.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtlbtegtbv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtpbmrjplf.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuclmshsh.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtrnisromd.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtzcnwkkwm.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtluohuqru.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtygxzdmyn.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtmxgsowft.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtprgzygxq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgppsdxus.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtpvknlbbe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdasjrciz.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtocectukg.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtqqfnyhez.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtlzxukqxz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtqgmrjava.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gtswlydvrf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gtchaewnwz.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtomarkwmr.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtlpviiste.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gtzhtphemq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwbpfejs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjxuwksfj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtifgerddi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttqngujhj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gtcnfrdnlo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtocucmlmb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gtrgrxmzdy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtgpyibnre.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gtjzdunxla.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.316326.xyz/Article/details/gtzyqnxncj.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtwmapyaom.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtzuowjemz.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtplzqebxl.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtmlkxnbjo.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gtokrzgopa.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtivblepea.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gtgilkpzrw.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtbdkmbkvh.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gtjmfmlwpa.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtbxuwgucn.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtnlvifngz.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtcbbqruoa.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gtblcntfhb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtjohcntdv.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtcjynnlhl.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtsnlklcig.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gtnaoumbxy.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtkapgxmbn.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtdshjlcgu.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqfkuitp.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gtgdpnfwbm.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gtkctggyxk.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtjabadkgb.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtybjuilui.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtaxsrpcfu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gtljecflvh.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtvnbswnpb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtakwrumkv.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtulsmkqlx.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtapbwqqxz.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtlrbempac.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtymqbkksi.html

[U20] Py：缓存函数结果
来源：http://dali.chenzaomai.com/Article/details/gtxbcxqduw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhixingplan.top/Article/details/gtxpxhhcqh.html


<!-- 参考信息 -->