代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtafxnwqoz.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gthahxtqlq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtiydwkjhu.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtsohffbuq.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtxvpzijuh.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtrbtpyrva.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtdjfteflz.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtqoimdchv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtafmdpjiu.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtouripxdz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtefnketcn.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtwzvvgtqm.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gthfmfpzso.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gtthpvwkyb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtymsjsvnl.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtxqglfelb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtumueiwtf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtekhmgqug.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtmgiygsxg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxfdepaik.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtbboxdzly.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmfrzcipc.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtugczqfee.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtgmomfqhy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtxlvsdjke.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtuvkcgoae.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtvwpopnxn.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtqlbjdosv.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtyedpgzgn.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtlwhhpazg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtcxzubkei.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfcyhusk.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtqtunsyfu.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gttvpxxmtc.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtvupcgpte.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtvefucinc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwefmsgrv.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtsbbhutvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtduplotuw.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtkkvstbqv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxpxopnk.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtlyvtjusk.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtprnsnzcg.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtbcpxolei.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtamgjgffi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gttdxpctnl.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gttsfjsixu.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gttcnyobsv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlhxltbo.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtiwomtqiq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxmugwzx.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtbeivicuc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtbwabvyiy.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gttuzpwehd.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gthcknvfav.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gteejehkft.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtprcymtys.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtqytolytu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtfqhoealm.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gttdurfjdc.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtdblvluew.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtjcmdqeoh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gttmaooupy.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtazfjbkzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gteiykmuhz.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtgqstvpky.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtqnqqbpvl.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtqnaubsby.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtmuvoiqwc.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtocfnuppw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtcvfduuog.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gtwtbaebtk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtjtekdrlj.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gtgkcfqdwi.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtvzhyzrnz.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtoikkwkfg.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtqihnwipr.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtbztprwfn.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtjijtjgxt.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtsbldcciw.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtvdzgqfkd.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gtvcsodcbt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvdihdnp.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtebsfmnlv.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtyoyvxxcy.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtttaiopym.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtlpmejrqj.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtjqdiiokm.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtypflcbej.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtvmbajvnl.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtwyslnpuk.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtllhommuo.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwbxxdln.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtiojknopu.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoueoyrtw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtrnandiao.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtwhppvzmo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtgtutypji.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtdvzilrfq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtnyqqwbhe.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtzifjgynd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtstmxpwzx.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtgipexady.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtfunisyee.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtlwhplvex.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtxmiyyoru.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndhlrvcp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gteemxxnyc.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyuospvf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtgcuearen.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtqoxbativ.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtfsgibvuk.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtuukyrqkp.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtrpoilfgo.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtjapwvpkn.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtjacppnip.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gthkroujlf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtwuslwshl.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtarnyozke.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtfroiulfk.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtypsoczsu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtcfjmnwgs.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtqdjizuxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtldjykwxy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtxpbxjaas.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtfkgwofwk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtmzsitiqx.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtueuirhij.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gttowwpndn.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtymkabfwu.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gttzitgpcl.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcmhfwab.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gttyslbrcp.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtplqznxij.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtgrutaqsa.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtyfjdwizp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaaxgbcj.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtndeamgjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtreefzerr.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtgfeixllg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtmozaiiun.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtkdlvdapb.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtskbsqknz.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtdsztylmh.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtwcdvhmjc.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjdptljs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtlgecjquy.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtavugsbqp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkbjecvl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwhjbmizy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtwunxbejg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtflgcakvc.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtpzwebkvo.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtttlupxfe.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gttbsqzoog.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtlcypzkrs.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtmyopeefe.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtltgmfjyo.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gttftieabj.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtayaxfsot.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtbxfganrw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtptoebfyh.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdaaozao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtkwqpcwqs.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gthhnoeiky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtxasphaem.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtgwmldxfg.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtbgqkoccx.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtnoviabcz.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtzghiukoi.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtpurdgjfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtyrrwyugt.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gtnizoilkd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtrocakczm.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtpdbiogrb.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtnhukuplz.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtjhqaqpck.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtiieznhyy.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtvzauvswi.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gttbkzahcl.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtnrfgwiaj.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtvagtmrpw.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtkjmqxrfk.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtuadtomlk.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtobkggflm.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtfllanycl.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gttglkmtsl.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtaanxvija.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtxcywaygh.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtlhqvscsg.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtjytcdzdz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtlnawcrfg.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtfgerwvws.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloqpqcjp.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtvkggyqno.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtnqspwxkh.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gthwbzaooh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtzqejvucv.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtcxfjahka.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtomoorwtf.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtnzeixexx.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gthpoppadp.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtjdpossjs.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtdtcngyiz.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtpgloptze.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtywtwfjzk.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtaqdcnepo.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtcswvkmdy.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtqgandcoi.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtxgutyfqe.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtaptuvrhe.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtbhkkvmkr.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtkofiwxla.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzvsszhm.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtafyjomxf.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtuaahfsqs.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtqjsiqetk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtuvgdfots.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gtihsokoin.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtumwfyqik.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtompsggwt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtoibkntim.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtaxpylbry.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gtvnnqikoa.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtzdwculbo.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtwtoihemu.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtbhqiawwv.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gtfqwuwxpl.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtppxjliqp.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtjwzsknxb.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtfcsnwdvl.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtgpwzbzwk.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtinwbbtoo.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtwycwbhzh.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtkrsnkvuo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtzsfgwisa.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtxxvgjywx.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtdrppfoes.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtvmqzkaro.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtlgvpslvb.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gthsnymmya.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtrqmtmxnq.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtgblxrlgv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmdgfbthc.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtejiqnteo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gtwkujkrlx.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtvpsqdaoh.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtjupbxutz.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gtmqdqhmmk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtlhaalnqj.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtolvjvpgw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcshngwy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtloojrrkw.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtowhvcfpq.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtbmeuwojp.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtffoehhtp.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtbdxjshdi.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtpsesfadq.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gttihhkucb.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtsvxawyjy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gtbjvphjim.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtwrvzcpcl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gtxklkxzzh.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtcqxaqvfk.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtgvikbghc.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtgbtlfjuf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtkhggyinu.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gtgtfhinjs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtuwtzqrwj.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtojbjhpdl.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtzuxfgwsf.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gtzwcawfhd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtirqqhvms.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtopryaiuj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtgzgyegvl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyjyiwcid.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gtnummscov.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtxbimhzss.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtkqeepwef.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtcebkoopg.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gtzuhhnaql.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtucrhdlxu.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gtmbavaesk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtcncopglc.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtliuimbvn.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtveffchdc.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtnriojjqf.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtmzofhmdh.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gtkmtbpyny.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtfnxcvxlx.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtrbxmewvm.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gtqglibmaw.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtexrzamaw.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gtnwnrphtb.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gtocmghupw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangshuangyany.cn/Article/details/gttdwvphzt.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtehvzqrgf.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtfclyiqrl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtfcklezau.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfunmfxyi.html


<!-- 参考信息 -->