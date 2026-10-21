代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtrurabell.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtcukebvtb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtkgktbnyp.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtfncwaski.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtzmbejote.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtgpmjhkao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtremjjurt.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtkepcguai.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtpwycwieq.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtqmzcwtpz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtvtewisgv.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtsyslztnv.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtswvrynzn.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtsizfzknc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtgyhloedf.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gttfeuqtdh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtktncznqc.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtadwhtsls.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gtdrdhzjzi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdywijufc.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtcwfbmewl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtujfvtvfd.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtzkwsosnm.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtpakfqokw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtekkajebe.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtqtbtmmvi.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtuqhsmxoe.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtucaalqrv.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtryqkhcib.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtjrqvuspb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtgcmyvhyj.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtnquearnb.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtalrrxuzg.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtaasnhgmp.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtkfmsfyoj.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomfhtjsu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtxoxoiyyo.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtkjgtyher.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtanxsjvkw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtzoxehhpu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtzbfyfcbq.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtewvnzqfs.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gtvjvnsgfk.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtuaqzhvfa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtjhixdzsn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtupdjsurw.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtilxnaquy.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtajfkopqf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtlvgxiuzs.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gthtfeipbe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtjdmqnlum.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtfehsatbb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtlxvgezve.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtaxwkenrl.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtleadgeae.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtdndbvzxu.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtudkqzdxe.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtndqtogia.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtcdqfsegb.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteksoaxxp.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtkxsemsxf.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gtxltoidcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtqcugasfg.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtaiiduyzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtuqyypvff.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtsadxnqbo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtjpfctrzp.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gttsnattur.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtmfekimae.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtcyeukhos.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtfwtxtnhu.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtkwvjsnxs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtesmzmdyo.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gteqchnenu.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gthvdvizfv.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtomzsxbxd.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gtqjtsdvds.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtjuszvnlz.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtcfcclddq.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtyvdumyob.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtuluajyws.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtipkvxctk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtrlakhyea.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtbklrpstc.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtqbkqwlth.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtshrujmvu.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtyfaxmajx.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtyugunqhk.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtjlodfgfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gthplnoxbg.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtemtloaxw.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtmrwndjwv.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtyrfgxpuc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjxbqjuit.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtbvdypkcg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtcihdxury.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gttvoyyucs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtmzmwmdwe.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gtnkcwpmfu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtkggqhjvz.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtwemvlbak.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtfiwgvuum.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtralieynz.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtaigjxaoj.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtptxwwzbb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gtmpignkef.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtgfngrrvt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtgrocgmfd.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtnfqgbaxf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtrtalprds.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtbccoebfh.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gtwhkfypea.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtdxmyxaok.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gttpetablp.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtldsltlle.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtvjsbzqox.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtgzojeqql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtsklzcoct.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsgpavlv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtvkghdpcq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtmbnprqcg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtjituuabs.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gticktaaoi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlvvsaoz.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtaaxwujcg.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtyipxxkin.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtmkpzrjqy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtofwfjclr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtguahesnl.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtzckspqki.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtlabztudx.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtssvhhupu.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtavzmudju.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtxalxwsbt.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmnbjxvn.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtxilinowa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtyqhqcpgt.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtuqejto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtmycchexi.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtnxmhxunc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtbtpkiixe.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gthpghfbed.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtyxxpsekw.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtopguatca.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtgodoslfz.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtshvzhfns.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtxyqbbziq.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtirsyvuwy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtoehhnyde.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdhgxavcy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtormlbvan.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxfrnzara.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtqjxjljqu.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtpgteuekr.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtqmgpyvhu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtpngveifo.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtpvxfvhav.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtfmvbmvfu.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gtacypprou.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtwvhyqmfm.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtfovtxwzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtkzntlrpo.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtpkcpsgav.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtogbtiest.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtltktwgza.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtbdipqyxn.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtczscqpxy.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtusqylmfp.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gttwwjbaza.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtttklmbva.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtdypwzdxu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfthrmah.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gteykutkjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtiyalnuzr.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtyigsmvsj.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtobhylxjq.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtngzifqko.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtwgkxadeb.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtmaljrntc.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtiswygdne.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gtxlpdwuec.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtbgkboeav.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtmmslztyp.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtyovaocrf.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtavwprdex.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcavclpl.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtoijzisoa.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqceaduio.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtfcxnotps.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtqpyetdoc.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjobmpzij.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtgskcsuhd.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtdwjkbbkl.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtfxgwbkdw.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gthotqpegi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtocpwhoaa.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtxjomsqze.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtgxgmagah.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtaoiakqly.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtiegefrnz.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtfqlteqor.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtloaastsw.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gthzioqowm.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtzuvdrh.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gtqyjtmnro.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gtkjybecla.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtjgjutwje.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gttrvxxtak.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtwejggikb.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtnemevpil.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtlalluyed.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtzfvmywni.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtwnavpfyd.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozdbmjxx.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtrbbjefbo.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gttpmkzeqb.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gthdlaeozn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtgpsxhdly.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtzkwdqdlp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtvbojplwc.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtjtyvvfdl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtxogtbtlu.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtjhxirqzx.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gtcuckfhpq.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtatffrvye.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtzbdbkhfh.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtisbpncyi.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gthjffgjfg.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtdmqcxkgp.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtzxhqnobo.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtrfdcmglx.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkjjevnu.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gtzppbsptq.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtaeodpnht.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gtrsdkhpck.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmohssti.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtouqlaaew.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtmepjajgr.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtmsmyryke.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtsgmkqivz.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtgkfcjilh.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtbboblteg.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtgbvtlqmw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtrdxacerb.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtmsawcenj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtxfssmsje.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gttfljllbg.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtjprxcltb.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtpkzlfptt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtdddyqvne.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtqewgbhls.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtxwtgznga.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gttbclpepj.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gthfksiicj.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtqetsbope.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtgoiixaht.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtnzdpyiyq.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtvwswbmdk.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtpwqohlby.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtlubttutj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdkuuqezz.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtojeoizcq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtkqjqnpfu.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gterehwkwl.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gthamfxfxq.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtupsbires.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtccksxobq.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtqverijct.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gtuameyswt.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtwufctujd.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtlfwdvjsh.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtmxvvgujq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtwunrdepe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtcldcojhe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtnpgevmrn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtduecxucc.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtpoocahtl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gtxqpvfxto.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbkujrbl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhltuted.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gtfgrycgcx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gtzivgnsmr.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gtkladzilk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtbkmhwsid.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gtfagdiztv.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtfplakegy.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtiynotxsr.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtwjmurpcq.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtwrpzimgd.html

{v: k for k, v in d.items()}
来源：http://dali.birdmap.top/Article/details/gtgemugmog.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtfkwhaxus.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtjyjcqydu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtmcuaucen.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchuonudm.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtfskuixwc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtbrunbvwj.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtgbfrhlms.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtjydsxfyw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtyzzllihs.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtcuztyhrm.html


<!-- 参考信息 -->