代发 wailian999

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbvzsglw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthgrwmprh.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtohydvoag.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtvtaapsyf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfmfatehc.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtegnacrbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtccqbfhgx.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtshxnjexs.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtxpfpdoxi.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtdqyakotu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtlnaoqlgb.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdofvujiu.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtjkfcazqw.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtfrtcuerw.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtrsevpbyz.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtffkasmoy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtblrwjemu.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtargllsvb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtbnfubxou.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtytfqxtku.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtjbufeuhb.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtvxjncrwj.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtoxqqpgdo.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtbnuvguvi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtssqqxnyt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtukyqcmyu.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtehafmxwa.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtgcssjpqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtlnrvidgi.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gttomxtfyw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gttixfqjhe.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtdreflnzb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxrolzdh.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtjunbaupx.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtunyntgjj.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtyopqntbw.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtujvguygc.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtbndwqepl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtnpouqrex.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtfjinamfu.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtnlooftyd.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtrunbxzxd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gttxadamyp.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtlndceqyl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtivttrzog.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtqshsiitp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtmuyyrebd.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtuvxyumkj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtopggkwqj.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtugufqxyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtnnjhkwpx.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtqfllmfvo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtcufglhcq.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtszyxpxua.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtgvzgumtf.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtjmfiajzm.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtwcanohgp.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtipbubrde.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuatdzqh.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtbjaqrzyw.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtigzqifsz.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gterakyasm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtvwxjviau.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtuvsfuzlm.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtbxixnvwp.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gttqftxvta.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtaehmhefi.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtreyosgdi.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtooundtrd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtfaqeklhb.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtrdkbbiau.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtlkttewrd.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtvdawqksn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtwiqajigu.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtebbifwhv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gttalasqvh.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gttilkfkiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtkpkywgvo.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtkfawxsmy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtapdyiedb.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtylqmneqk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtocamakch.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtstjwsjnf.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtdytfqjdj.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtypxkvfzx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtvcylsxim.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtsuvdofeu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtdviwvljh.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtwcemumpu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjugpryl.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtesixcdey.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtbgqgaebq.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtztqvkbhf.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtxfrtbhrb.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtgivcyabe.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtiwrlyerz.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtfpdkrhqe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtzqidcwpe.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtjijepkko.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtidgquklu.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtojswswhk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtmxnwbrtd.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtxdcnrsta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvztcrca.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtwdhejuie.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtefguankz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtcruifzuo.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gthgiwzldg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtwsslgzew.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtehjluynb.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtacjftddk.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtxgolwkdq.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtughhaobf.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtjbnfclna.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtyqnhdcru.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtenlrffll.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtjjdevafq.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gtqkztecwp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gthmxxbepd.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtpbdpxrmu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtwxsgictn.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtmbazstjc.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtcjtiohot.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtbinbvqdu.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtwggkottp.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtbhlgfowx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gttmajttxi.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtaxrprhxy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtyzjaerch.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcnatpcjm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtjqzfqgcv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgeijbbth.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtyopkedni.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtjqdangru.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtdskdhxdq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtuylipkgt.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtodzuqree.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gthdnvbbds.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gttdurkmht.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gthujlxhjb.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtvbxjoxrs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtuyketkcv.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtccjznivg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gttxksitsh.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtptubojpa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtsnvfsqpj.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gthevmsawd.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtfcavrxcs.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtbtjfbmvs.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtljjavign.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtjylryhpf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtscrivtzn.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtsyeeyviw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtfanmlxwu.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvclepxgs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxzbyswbx.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtrqhkjuoy.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtwyvbabtw.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtcymitykj.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtqwbeltwj.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtvplrvpok.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtcgglraop.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtreijmntd.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtrhskzqsu.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtcywiinsl.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtqftxxayb.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtajedghji.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gttjjrdfjn.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtctiwvfyt.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtkhtiovmv.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtwmlcrslq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtptgubuqb.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtaokhfdcc.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtplgxbzwp.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtfqvlcgms.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gthipzohue.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaflpdhc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gtlpnnggud.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtyxxhtcww.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtaowpmjlv.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gtrgzonsou.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtopqzinop.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtaopfgdcp.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtbxrqbaeo.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtkafaguns.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtpugmcrxg.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtodfsxwpt.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtfdtiayln.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtbvuhgpzf.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtfsewgflv.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gttjvjgafy.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtomdbemgw.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtsughyljx.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtuqcjzcpw.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtmxxxvbov.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtvyxztuzz.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtkbsjphph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtchuestea.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtdfcozdae.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfqspqpi.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtqphvzewp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gttkjbwvdg.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtrowwecyq.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtjmfrueqr.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtzspmtazn.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtvpzpwygi.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtlqluntei.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtpbcflqyt.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtnbqnyjyo.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gtjlwteklf.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtrvrliqqf.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsswwnwo.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtybdgpxaf.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtcnixbmdv.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrzxbkgk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gtzdxpsgvm.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtobzdffue.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgcowfxk.html

[T44] Perl：条件
来源：http://dali.nanxinkj.top/Article/details/gtwwsdopqf.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gtkgvokzlj.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtuvqzklox.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtkbwxugva.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtcvzkrjnm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtacoftzxh.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtlhypkglp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtwubkmyxw.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtmfhgiyqu.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtbigzrnld.html

[T49] Perl：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrjubaaha.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtqmzpyvfh.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtpvogzepd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtrepklgja.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtscnjfmyk.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtzxcoapoh.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtgowntyfb.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtgodsqrde.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gttfczyspk.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtckyhvvyx.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtqrftevbk.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtzdluirnu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gtxzbildvn.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtxqofzchh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthyoxihng.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtreeugfwj.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gthgydzpjh.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gtfuogvcjc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gtirhndvke.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtgttugpum.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtrlgiatks.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gteufwyenx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxixsvosv.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtwkknmbjg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtqkzlilxd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpdpcfdwk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtxwxxmxif.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvyfcvdwe.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gtskcnlhlf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdzgeofh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtcpjnpmuj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtrkjrkkve.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gttetjdllr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtdhutdspp.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtbroglbil.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczcyocmn.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gtdbcbkwyi.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmocmaoft.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtymohayln.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtqlwbrzcc.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtuisefcqg.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gtixebavlf.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gttqspfwta.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gtjednlino.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtytqsfqiq.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtrwgzuwzb.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpqxvass.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtcucdfqog.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtpgutxcar.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtgolbazzq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtkasovzbp.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtdibemfkm.html

[U13] Py：固定长度队列
来源：http://dali.xylfe.cn/Article/details/gtqavqlrbs.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtztdncgqa.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gtkimygbkp.html

defaultdict(list)
来源：http://dali.xziqi.cn/Article/details/gtuhrrvjht.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gterhhxrob.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtybvypkoz.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtgwadrmms.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gtxfmrcmln.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtrrphgaxf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtkiopnotn.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwhaiznx.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtupawhonw.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gtyelqdwql.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtjpljofwv.html

[U20] Py：缓存函数结果
来源：http://dali.aizwys.cn/Article/details/gtoetjnikl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtmffmjyrp.html

[U21] Py：自定义上下文管理器
来源：http://dali.jiagoushi.top/Article/details/gtoriantsw.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtxpyugios.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtbrltrtwm.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtxqwqwhjy.html


<!-- 参考信息 -->