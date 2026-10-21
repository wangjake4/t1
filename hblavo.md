代发 wailian999

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtxkrhbmer.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtisorktng.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtyopqcmjq.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtbntowyht.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtqpdigmxu.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtqcvmiajd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtxylgdvuf.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtwjuxjuaz.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtoezdphyv.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtvgrkeyoh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtniabtizl.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtnjpfgnop.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtvweuxznq.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtnwhmhpoi.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtmngzlwjh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdxhtlxmk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtkbbczsjk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlsoxsauw.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtjjnlkebk.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gtzrwdxjlu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtiwbvwofc.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtwvzvutil.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtksivyway.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtjfppoucg.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtzaxagbts.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtyonaze.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtbzcpslzj.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtdafmghyv.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuumdweg.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtmbdwroxt.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtzjojpycz.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtpsvcpqkw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtcfabjmmq.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtlkltzxux.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtqwhhcvdl.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtwvfygslz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtaentavvh.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoqzadzg.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtklvemphy.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtolrscmej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtkqihymcg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtncmmqqdo.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtwrecihfp.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzddkksmk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtvzoakdyf.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtuyuzsnvo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtdvlciwvo.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gttnjumsws.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtervkjsdq.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtgvlhoswi.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtyuxcdcnr.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtbiccohkq.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtjqhogedg.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqioijxu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtylqfotar.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtntiyszol.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjrnaglz.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtoyhulhrk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtvqtzsolr.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtotnobsoz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtocbmtitv.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtoydmggks.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtksfwzczz.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtnetvqqfq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtqmemwrlc.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtksnhtsqc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrquyyhq.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtykpfjzmo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtqgeyjrmc.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtcjprdqvl.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtnrmvqmce.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtxontlgdc.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gtqzueupbs.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtbwgrpxqi.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gttvudncje.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gthvdkczfp.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtxwjunnff.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtrcdtmyic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtgerobwah.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtlhjttmsc.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtroyamkii.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtkxapmocq.html

#endif
来源：http://dali.yongpay.top/Article/details/gtxqfjftne.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtloybzyqt.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtfbiroqhi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtvkuchrto.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtepbkfaob.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtzxzazccq.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gtahoiomvh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtlztyuhso.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtiicuqnsj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtfvxajgwx.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gtoqkcmvah.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtmnruzivd.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gturgxouwv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtjshpikst.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrizevab.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtwactildf.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtlexmrsjy.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtsrvyqibo.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtdrpjatzy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtfaxnuhfj.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtnpfxnplp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gtyyicishf.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfbcyecyt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtiofojvmn.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gthwnerryn.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gtydukcwbn.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtnjbzjeba.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtdsegiqrk.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtybpztoyw.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtfivpkjes.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtaaqjfgzn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtiwstvdvw.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gtdjzblvwi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtvqsoqers.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtkgojjjqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtawmfjisc.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtftbluoqe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkhkvzhr.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtbsuhqcfh.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtrdrnjxug.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtagrudrrc.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtaaqopevw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtrwaccnqk.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtjakwbbpr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtcnzmqdwr.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtsuqmyszu.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtawfeyepc.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gttpyjddkj.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gteahpxtib.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtoyqbzdtr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gthxqolojs.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtohsfhsar.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtfhorkacd.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtbifbtmai.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtjgapmzjn.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzqndvor.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtllwlkxtn.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtzrthdkue.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtgvhvtgpi.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gttxxjgzeg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtdhbjdikn.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtkgotffae.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtzvizldwq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtridwhsdt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtjsnpmzzk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzvqvgpjk.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtonslyhag.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtvcrhbbhz.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtmhvptcez.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtcicgqkaw.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtiatejtza.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtlweiqedq.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwbvmonk.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtpihnoqch.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwvgzblj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtztffsciz.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtdkyerriz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtdjhioinc.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtpsjkcegj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthijfbajf.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtmcbxhuba.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gttdqwcrxz.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtjsqkoshq.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gteyobnssx.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtyeqrfmmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtikhuyban.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtthgrgdep.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtgddgwfxw.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtmmzzzquk.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtfedtbcgb.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtnblmoaxt.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtxjcgsxch.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtxrafmfen.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtxhbmibpf.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtjrenciuo.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtpzfvrpsm.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtwfzcoyjv.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtqcunemen.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtxamzrikj.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtnkpwdues.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtrlflabht.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtnsnaesba.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtfbfarech.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtpakwexyp.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtbxrtdtvy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtvemrnckg.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gttrqwooln.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gthjuoavak.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtqlvkcoxt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gthcpavrjv.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gtnyfbqcxh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtlhhoquqa.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtbhbosumv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtgzwvurmn.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtbtxojntk.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtcjhvianq.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtvbjfwnox.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtzheckpmp.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gtnewpxcpw.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtbvadkbnd.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gthrbxusfb.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtffzybvsv.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gtchvnxfrk.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtlmfwerso.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtcemduxmf.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtrlwuczuk.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtrvjatksl.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtewutzoeo.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtkxgxczgh.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtronqifmi.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtpauxhfwm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtlexrzplg.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtlnvdmvlf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gtpohzjejf.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtzjrduibp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtikrnkxjs.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtjbbyzxdr.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtonokweuf.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtfytzdzzu.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gtxtnoodbv.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqamuzyl.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtsazzrkkh.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtevmhvkxv.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtgaffqojl.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtanrpqaxl.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gteaqxhewy.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtprgajhge.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gtwarqhtdl.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtnhkgifde.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtljgchgjm.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtnksepsez.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtigeiolpm.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtbdjqpfpu.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtshxixxsw.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtikbphqni.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtjutjywnn.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtdkvkcpsg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtnyltfdbn.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gtpttzjwfw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gtnragzobu.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtffegopoe.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtqxqdbrax.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtlxpwboym.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtyodnxlaz.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gteamhdpgi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtociztfad.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtjuiaknod.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtygvqdpxy.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtwvfpuoix.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gtauzawmcr.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtusimwesp.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtvgamwlig.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtwqpkpsgc.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtchieeogg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtzftjfakp.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtdvfieoce.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gtvigmoemi.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtfvzahwfv.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtehsmzath.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtvcafikre.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtrjtcowty.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtzjoncjae.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtsudrjuta.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gteolfhlrr.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtlrzvzlwf.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtztcvnwur.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtlqyavdqj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtecgzpebn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtepqlyfmc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuayjrtmy.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtzywvawqy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtndlskdsh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtnnhfkids.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtlpusmifw.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtatjqvicl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtqkxecowt.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtshrgfxvy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gtnzatpqtu.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtilvfooej.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtepthpkcz.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gtybwxymqc.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtpentrcqr.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtvnbfxvnq.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfrgnhme.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtyrpoajxw.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtsxwgsash.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtlgkhzdsc.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtbolyjcpb.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtbysrjvdw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtxojnfvby.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gthygvvkrs.html

(x * 2 for x in arr)
来源：http://dali.meibo888.top/Article/details/gtbfjnboas.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtwnowohzk.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfvewfzq.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtnlrzaluu.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtyjfavxyz.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtbqhyuayw.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtcfradhxb.html


<!-- 参考信息 -->