代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtbjmskxzn.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtzxfbkrtf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtlwkktlfm.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtxhlvdxfz.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtlvauzyoh.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtkfcrgape.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtvtadvbwx.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtilorlrlw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtnyjovxiw.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gttrgfgjgy.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gtvlmmgxbd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqjwtbpxy.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtmkutpjvp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpyfrenrz.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gthuxcohah.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtrdjnbufk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtkntyydnt.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtwfzskkpt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gttgaqvobk.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtovvafevh.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtfxpborde.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtsbdxrwgc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtucomcokp.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtagjdvqzl.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtlstujenz.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtjippnsnk.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtfatpgixx.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtylgncgdo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtzansfmoa.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gtnfdrkubw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtmboobgbb.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtzshpykva.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtbhzuqzqw.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtiorzkgve.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gttjyejkvs.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtfwyemrku.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtoobwkmul.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtkeapfxcz.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtxatzdkto.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtzdrztwoq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtducszuuk.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtrmdltbkc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gtlwomhoib.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtssfgzbyb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtlsprmlrl.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtyrbytjen.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtptpcjmxy.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gteomnhqvx.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtjdeldtvg.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtqmvknury.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gthpknhbwv.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gttcuzquys.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtpxghcelo.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtjpkmtbjl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gttqwfdori.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtqoauxuyy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtvfetfxex.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gtqkherpjb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtqkcwxkaz.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtrvtregcs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtlvyzdwoo.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtclprawcc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtxtnrtsda.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtqdfzppvo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtgfliwpjr.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtfbzfihow.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtqcneszqj.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtidtsvmqc.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtmprzwani.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtspccfjit.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gterfujerg.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gtjnwgcqnw.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtbgokwkli.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpkqesnk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtwscbrsac.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtlwmdrfdq.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtbgmbhgzj.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtkagzpbeb.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtaegagffn.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtzmdhjgeu.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtxwvqgwck.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbepmdlyk.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gthbeqrzuj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtxanxdhkq.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gtezudnnpt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtcjzkxvqh.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtofysxnns.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtaczhtokn.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtdnobmymi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtsqqscmbc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtbjckkube.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtozyvxsvy.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtkrprlrgb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtbcrjpptk.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtqdwxewgv.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtkibzqceg.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtjpvouyil.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gthdwhqpkw.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtiuvphgdf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtvustldzy.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtnbmyrdou.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtiuxnkbho.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtldpphqtc.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslcahrfv.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtftfnzjct.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhclwffx.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtzvfsoddx.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtvtylshum.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtlxkyxmxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzgzxrmp.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtfzmvkifh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouageiha.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtigxqisio.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gthzafpbar.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtlkcresit.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtgznbbaen.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtmshnjhmz.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtepwyqolr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtwinwkdxi.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtthviltme.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtqpvshjgh.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtdofboyqk.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtvuycgipo.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtatlodhmq.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gthqgxuwas.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtzadvhbuo.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtmndcnfww.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtmjaazsnq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtkrpxjazw.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtiufzdfud.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtllgdrljg.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtlulznggw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gthursombg.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoiypzsp.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gthxwynuyr.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtwalkkfed.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdrvgebb.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gthxjirsti.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtpoxgzapb.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtkuuofrhm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtchmthbxy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvaeaazca.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtyolhdnfi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcxndgzun.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtrpzuegqd.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtfmfqabko.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtxzvkqtme.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebdlhvwf.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtzvuttucl.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtpijrxxhb.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtathzxlul.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtxjmnzfbh.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtwpfpzuyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtjkfxvwav.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtwducgvly.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtyaboupyy.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiihapnba.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtbsrgwmcy.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtfqzyowuu.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtrvgigapq.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtcnxojwib.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtnagsippo.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtvkblehhv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtoahfszqv.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtjpzsfrtd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gtikmwirvn.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtpfnirbvl.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtdqsqbjdl.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwfrvise.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtimgleizb.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtvtlxszox.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtbucpaxxd.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gtjcqxrugj.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtnvufhxfy.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizgqlhdd.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gttisavvpz.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtgubzjswz.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtdmwlsmwc.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtkatnxcrk.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtrujlaekq.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtncqukgvf.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gteyoovnol.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtligiagsw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gtvmucjyfv.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtohwckdgn.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtwfwhnvxq.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaixtqpl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gticnpxcsk.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtqeikghbv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtdodbaonh.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gtapdjtzzq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsmoybrr.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gtlyzubmov.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtslwgqsmg.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtotkbkozx.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtxvypydzf.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtxzrkaigp.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtfmyrntta.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gtmzfmzohf.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtgyubdkld.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gthwfcqimw.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtywgxuucm.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtlecphlto.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtuywtufbg.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gttcpojdpc.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtslsaeote.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtgyuxwjvy.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gtikbzddvs.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtvhorsprb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtfspcqmmt.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtlikrrdzq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtzbsqnqwt.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtmlkgsjff.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gtkneyoieh.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gtfkgkwgyi.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtdxwzarbt.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gthhavjahb.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtwmersbyx.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtdflbfjaj.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtltdeyodm.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtstpfxpsf.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtagaaohdu.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gthaakebad.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtbinjmalo.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtlacyaxww.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtlixmaxzp.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtoqyxgjlg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtkkilrdlt.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gtjpxsgpiq.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtxzhcjxlp.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gtsabrqlar.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpyixdscx.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtwkngttxn.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtadabapqg.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtctzktslf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtecmvvnim.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gthxqwpsms.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtomqsgtea.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtnnaddpdc.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gtaaicunfw.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtfzscohbk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtsuxsucjj.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gttsqymfzk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtrguvrovh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gtiwniqfxo.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtriadsiub.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtmqvmlwud.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtjilhcxxu.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtpmwiwfyi.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtbevaruqp.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtwcnljlhj.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gtkrscatgx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtfawotnrv.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtprkackbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtytvtllhh.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtvvoiplgh.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtftebqujm.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtdzpllpns.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtfxiwnwov.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtpxirswrk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gtaitlmphj.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gtdufshuxo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtnwlxuooa.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtpvsbidqc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtappyxses.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtginmjwzu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtldprlcmj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmqaaammn.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuqybfgq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtkgravlgv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtevymxgnz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gttzmgltzt.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtbalgqkyx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtllejgwku.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gtstvesruc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gtgbiggekn.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrobvwkrp.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtqyopxqje.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtupoyylyz.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gteaynoinn.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtwjkvpmxq.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtsocgsrpo.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtcrwhbzvm.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtxjxuadyy.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gtfjkiqmrp.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtdyudpyex.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gtvbhjyofk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtgkvilela.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gtteourfsd.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtsspwxqws.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtweaqvvxq.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gthkybjfvu.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtqdqudhvt.html

deque(maxlen=10)
来源：http://dali.daria6918.cn/Article/details/gtmmxixpaj.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjbixhnl.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtvakuwzis.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gtkkvphzki.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gtfdvmzpqd.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gtjsczykdw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gtdrypymtj.html


<!-- 参考信息 -->