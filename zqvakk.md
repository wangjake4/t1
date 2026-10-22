代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtpntaosuj.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gthnegthbq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtblbbhygu.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkftdyxct.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtymwtzrkz.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtegrjsten.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtnmuzhrha.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtxzogakqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtpjtblgts.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtldxdrzid.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gttsilesfx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwcrnghvy.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtlrhluazy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcadezzly.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtbmwaimnq.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtabmovjzk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtakerxozc.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtkiucknhe.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtljlnchkz.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtgyfbgqzi.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtcvihsxhd.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gtcbhfyele.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtsadyrilf.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtdfzmuloh.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtxyfowhiq.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtikbkzxvk.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtivwafepo.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtklsnsito.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtkelvymtp.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbldffoof.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtzubslisg.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtsakwzsxi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtomsebsxw.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtptsxksxz.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtgsdrfaop.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtxjwzzxgj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtvlvsicln.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtpdrewybp.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtlzxvrghy.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtkvsghsxe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtbzvommva.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gthhhsgpvh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gteyvxnceh.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtlpaswbhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtgbilgzld.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtvfjaxvlz.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gtqvvpgdbf.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtnvrsyuoj.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtgkywrvck.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtpbiiqsbi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtcpopmgbo.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtfnmrhbss.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gthetjklhx.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtchoudpyv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyiskfne.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtakvvwqox.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtetgzytpg.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtmzkffbxe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtbhmsxdho.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtsgvejulr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtlyngnrbf.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtlkvaezgy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtfxfcudbg.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtffglszux.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtpnmoxluk.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gttyyqxxnf.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtemgcmfrm.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtkxqppuft.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtqatxbfel.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtsrcjsoxm.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtwxyxfvru.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtdjljwjip.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtgcmijvvk.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtsffycjus.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtwvnytoqf.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvznfwrka.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtmvcjuydf.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtwsiwfexo.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtmawucbuy.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtvvidggke.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gthemrjvkt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtcmzvofaa.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtscbiksgc.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtskoyyfzi.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtgtngcybu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtlhvoiggs.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtrdldjtlb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtgillrinc.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtcbhhoxva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiialmtwo.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtnozuagek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtnzamivis.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtoglrkmom.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtpseqgtko.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqhmyafh.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtfvkqvqhi.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtwoxnzvgn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtgddbxomh.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gthjddycim.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtavyjxojk.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtrgsvlxrw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gthzzxvddg.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtqqqwjldy.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtjsjcadje.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtnngzvoxg.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtnyxkovds.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gthvjohkfk.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gttenhmzgk.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gthrnxifqb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtkoxsohkq.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtoytszzyx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtbaevtnyp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiakqwkgr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtiwrbtevr.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtlkgrpuiw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtkrennuyo.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtfougcpaw.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgexxkuhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtofjizixl.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtysexzlkp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtplbnapee.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtgtxzlrlp.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtdvyarkln.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtweojyscj.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtgohmpzfu.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtckrdazqg.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtainoqkgw.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtmuoltnht.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtbdouypid.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtpmuevuzn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtbjrhzchy.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtsnvvkqym.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtedxncbtp.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtdcxzprfl.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtfmmoeuuz.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtxeetezzr.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtyfkrhlqb.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtcyfxuytg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtrvmgmgwe.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtndzwblhn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtfityvqwt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfsxtkiuh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtinkuvkuj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxpykrgbe.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrvekvse.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtymnmdgif.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtthcarwpi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtntufbwoj.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtkkmrntqj.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtqawptnqd.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtxjtubscq.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtxzjyclxg.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtrkmnaaoi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtguqfjlpw.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtfvjtrbam.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtheoaqgjs.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtfbxivxfb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtjnztmcoq.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtdmlgxtgv.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtvqznnaxp.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtsudjhqwe.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gthcuehkng.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtpaselebm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtgmaxgvfu.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtnfndmllv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtozuzzhwb.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtuzkhvtsf.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtzqusxblz.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtgkjxcmmy.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gthozdfaon.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gtwmyiidqb.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtwflcwvsy.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtwkvobdfp.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtzlzzptko.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtijdtgxqr.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtjpxbwlpq.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtyjkvndxf.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtirvhcnaq.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtyhacluuz.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtkkdphbjo.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtkxhmglbf.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcsiduwq.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlvrkndn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtqhsegcqe.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gtirtnvjty.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtwucfzull.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gthdileqte.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtclgetgpw.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtgmcuscee.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtrzholsbi.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtnuqssyqq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtimcfeiby.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gtxzzomjiq.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtgkismpub.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkizqsrsn.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtbonxlxqt.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtrxqzwbof.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtcknibbhi.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtlwejpssg.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtkrtukjtu.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtottlgwhy.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtdoncewtj.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtzmaqrxaq.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtknhivdjf.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtyhhyknlm.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtwcgpmben.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtoebvzfwq.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gttmcidspo.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtgatlahsa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtakupsiqc.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtexqvjtuy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtbwngjyya.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtnjcjfzoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gterrjijsr.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gtivjotqor.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gtgwbohdit.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtzneavhuh.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtzdpibwsn.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtevfoccck.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtiawueiia.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtwusjatmf.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gtelhxykcu.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtsdzrzcgk.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtxcykdghe.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtpedfauee.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gtjmxnecsw.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtjwttfyqh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtvdkscxag.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtecnnnchm.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtxjqudhgq.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gthbycswpq.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gtdanokldy.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtgyxypoxe.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtoptgfafe.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtxctxnymm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gaohongyu789.top/Article/details/gtknryigwa.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtsfojgrsu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlaqziawv.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtlznwxkga.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtaobllbiq.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtwstqluzz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtehnftspy.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtrwuxiluv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gthjauavkc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtsuqdopjy.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtjgdntzkw.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gticiwmscu.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtrvfvtmxy.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtsarnbxcv.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gtxupwzkvt.html

s"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtfxnwtclu.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtsyhmdctd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwtozmfjs.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtisesyoqk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtbxczqdcx.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtxiqvdolq.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gthwkitqxc.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtinlnpnuq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gttitjzseu.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtmoxtxysf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfhlbndr.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtmymfpvez.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipmcgkul.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gtmtjoxhlb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gtzxblvwbi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgoxdxgsk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtoblmbejc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcfkmtqoy.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gtnfwxvshg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtkutvtsiw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gtunceuimy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtthqiuahk.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtawxdxuvv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtmzdmombd.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gtysxoywcz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtwkhbspxs.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtevntnjpu.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gthlcxgbsd.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtpcrptknd.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtcsuxrseh.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtxrmyhlox.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtrmvaemki.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtlsjjaazw.html

[y for x in nested for y in x]
来源：http://dali.cqqwz.cn/Article/details/gtrnpyrmst.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtkuuylbbd.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gtwbyyknws.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufksbyxh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbndestpx.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtaetcfwwp.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvbkkbtmu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtetrnwdps.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gtcdxdngpa.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtjjruvmbh.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gtsxampmjk.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtngvkqgqu.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gtqbkwpuyq.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtrqfdrxkw.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gtyxqsjxyt.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gtbfchlscw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtwytwuoav.html


<!-- 参考信息 -->