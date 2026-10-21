代发 wailian999

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtllkibcig.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtenaompyv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtfdsawcyh.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhigeren.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtfqvgbyar.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtylnehofh.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzqnljjq.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gthedewswz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtibxuppdp.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtccxawopm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtxsjjhvsu.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtgktdgbps.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtsbupziln.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtxrkabtfy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtrahyhsyk.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtuddsxkkm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdruoyxe.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gteanzsmbu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtfosardfa.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtdxyginwp.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtvmyurksp.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtntcahppb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtqzreopdm.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtitoamluq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtznbjgtxo.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtmxgdqikb.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtupjqkdax.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnjrncpjf.html

S. C / C++ 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtybszqfxf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbflpahjk.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtwhbhysmw.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtrrjpudue.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtbibyzcoy.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtuqiuvzcn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gthbuvpmnl.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtzfxswilu.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtventsvpa.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtpbudliga.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtpfcejynt.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gthicapyju.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtllfynuya.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfyuhspp.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtffjnqigd.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtbnxboxov.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtsvmguvfq.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtvtgccaxz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtkvoxlzqp.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtcdhzclbs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtrfjhwges.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtixqpdwvi.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtyekrczgy.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtideuwkpf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtpjyurpwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtfxanlzpe.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtqyqkssmu.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtytddhdjq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gteyqmiylm.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gtiikwhfkl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtnihuoxjc.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtkrjmcgwh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtefntjuij.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtgmqvpgjt.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gthcuqwdcy.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtkcejvogb.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtmojioygr.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtwgwrfsjy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtpsmxvkun.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtnfosycqv.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtnanwmwwb.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtowjrodfn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gthnibxixf.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gtxqoukmde.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtiiepwxnh.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtftlkmhsf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtzsyhmvoc.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtyzqwtabt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gttslphybj.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtqeqecxhz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtbbqmskrr.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwotuauw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtlqwsuqtj.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtsdduwbdu.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjhbarsd.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtghesiobw.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhvlibcx.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtitrrqrpx.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtsbelfzhl.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtixnizdhc.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtwljcvtkq.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtcaucukji.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtyapiszqo.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtyfpcpcxm.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtgncsrcxs.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gthluglxxs.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtnmnwcrws.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtcsfomdfq.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gttwlpzcbu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gthqrdmgeg.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtexxkqkbk.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtpvhpgjsw.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtpemfrnml.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtegplcmep.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtlsszxvvi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtelhwavnl.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfibsntsx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gthsyzzgfh.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtuonivble.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtconwqoui.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtrqdkjuoi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtqplgzeoq.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtdfyhwnii.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtehthjwmh.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmjsefkw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gtuzbkwvzl.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtpzvddxdr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtvhuyuqif.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtlxaceuxy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtlbycpsqx.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtlhfxqusq.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gttarfpmlx.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtkokuxnej.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtryreeeeh.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtfypogpzm.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtrdcftkpw.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtxuvilfoc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtzhswkzpk.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtzqpghiiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtlfveohzm.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtfchqvqxw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtakcllnuv.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtvbtgyusg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtiibzrzqp.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtgdhbnnbt.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtwofuuzmo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtfpuhpkhx.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtylklpqcp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtcgfhnbac.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtiunepzqc.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtdrtamuiz.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtkpyimjjl.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtftyoiyiv.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtlsyztglw.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtjuonrewk.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtynxsdcgz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtmokvsmga.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtwhascrmw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtzdmtlukk.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtlaxmvnam.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmibbwhfb.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtnlzwevks.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtuqpxolrk.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtyfrvgdkq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtvhhlkbqk.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtzpjcgvsa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtsrnsaigp.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gthrwckeev.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtztuvvsqp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqulvhijk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtcdozeloy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtajwkqdrb.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtvsvfkjib.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtpsjidvbp.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxcubuvci.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtzpnizdem.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtbphjpaaq.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtxjsgoqvu.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gtqvmexkca.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtzjgtljuq.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtgdeeykql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtaijyszbi.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gthbzmeorz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvvmmhav.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtmycbuznj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtkzjyuxbz.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtmjkuayni.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtlgcimsef.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnehqnsej.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtohxywzsp.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtmyawdedo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtdvgbwpof.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtwxjscbmy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gttjjelwhv.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtxchxuqnf.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtxobxcqvn.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtdckdemfb.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtdezmdoyb.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gtkshjrvag.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtdswdtnyi.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtkagahoou.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtjkefztuz.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtyzzqljiq.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtdjmfyohg.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtnbxlxtwv.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtdjvudhem.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtgrxxqsjx.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtaiibmxah.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtvypzvdtv.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gtcwtwysow.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtzcfvazpa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtdokyocyd.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtxlqgbdfr.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtulhtcsca.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtjroufpaj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtmitiazdi.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gthzusotfe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtoulgfnqu.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtltodfcgp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtscvxasjq.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtzhijekcu.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtzlhurrtp.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtcnzgdpvd.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtjyjtaphx.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gtlkmogaxu.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtxkraqldr.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtmgcjbyor.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtdtzwkzkb.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtewjadgsj.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtrbdpeauz.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gttzppyrsi.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtfqsdyprj.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuvyaysl.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtsgmshobo.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtyiubbkdx.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtqhtoghln.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtzozwykal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtgmgwklur.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtapvyeygt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtnsghunhi.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtwcpacexq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtqljgwmsd.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtotlmkcmw.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtwtgxoetf.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gtadcjqtni.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtstkjwynm.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtvhirufsg.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtrrftxicv.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtiemmlcti.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gttxlgjtzb.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtpbldzfxt.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtvnzojlzx.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtiteybnvl.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtljztttyg.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfpnvbex.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gtprzsgmlf.html

[T43] Perl：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtfsnxhcrx.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtpqmrqjwy.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtuagilgig.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtehluoebr.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtjetonrde.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtxrmiidcr.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtcrofgjhs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gtcvaccias.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtbzhtqbfd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtsdyyiznd.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtryjyiicz.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtckbwfkoy.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtijahymgq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsickgjxa.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtudcvlffj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtftgdbfjd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtckfwbmio.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtwsaxfamy.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtdcffxzoy.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gthoyoatcq.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtrefufnki.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtagjjfdfu.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtiitzoxcp.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtdjyuwzey.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtrstftftn.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsyrugfq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtgeyyeubz.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gthmutivxn.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtwxnsdzyk.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtublncskj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gtxgwumfqe.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtuvaxstei.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtrmukzpjh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtqifhcmvo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtfujgftyd.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtutqmunro.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtrnhasppp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkizuayka.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtlkxprdaw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcoqlfhme.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtpeofsjml.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtjefhosxf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtiwvggdwx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtzjtrotmt.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtnqurnqix.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtxpwmspgt.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzyxtzge.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gtflboucau.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtfggsytag.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtmzuxdotc.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtondziqcy.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gtgdhgzzsw.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gtfwmnujrx.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gtzoutfnxc.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtspzugpyl.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gtjuhyogbm.html


<!-- 参考信息 -->