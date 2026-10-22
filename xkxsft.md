代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gthtyurmis.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtuixudolk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gteqiclfrs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gtfsijnnvv.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtohhrtmad.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtovyshthh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtmwqgqlgo.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtsoxhzfvd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtqkxutyfw.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtnnrcdutk.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtsjuygcua.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfdewudex.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtkrippklp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyracobys.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtpucgysyb.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtjumjhjtb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtobwghvwb.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtvimymqmi.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtcxetfqks.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtplxwpzmv.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gttkjzqlko.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gtqhoqcfrl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gttmuqyumn.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtslllcbje.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtfrhbsbyh.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtioxoajyt.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtrxtvcveg.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gthkmukqmp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtibjhcdcp.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtqvuikvjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtfzoiclwq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtdguqozzm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gttitosexa.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtvcgbuodz.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtxlvzrhyw.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtjhpexlnr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtloixrvwo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtbwavubkd.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtizmdqbaj.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtmmtudmdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtmrgnxgzs.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtnwzzswdw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtvaynybzc.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gttzesfgfd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyibbfld.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtyjiafxqe.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtpgirioue.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtqtjxbcmd.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykscwimv.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtxpycdlrh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtlcfdwtxb.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtrdbqffmp.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtwjuwrzzr.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gttepnstwp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gttrohibhy.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtjgbiwwoz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtqdcuoxtc.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtblhquoyg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtkyuxhjyp.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtsvhpbvnw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtijipsbiu.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtpqiqjudn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtocloxtmr.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gthxznntyh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtcvtizwjl.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtvqpulmgb.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtzrgwfgoj.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtwnjbrwxa.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtpnbtzfnx.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtwmdssdkt.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtfqvkvrjg.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtazzelulp.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtxndhhpba.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtqoaqnquc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtyxcofzts.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtthdkycmx.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtdhszahwc.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtemhlfbyk.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtsalnqjeh.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtxgfkttns.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtvbomcuae.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtonvoxpei.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtmbugguzt.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtswhrghhk.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtzkawkwwo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtdbwqypuz.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtpffoeloj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtgvogoubm.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtwmactbnq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtwkhdpeup.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlwuogge.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtqxmuyias.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtpnwqixdj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtowgcolgk.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtetcgbawu.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtiaqqwkbd.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtdpasznlg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtpxajgetz.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtbcnhxgvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnxijany.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gtrqtkmlwe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtewnilkwk.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtalwxbekj.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtzapihbgq.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtyyiwzrnr.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtucpvqvbl.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkablmoep.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtbpvffkrb.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtmqpncrjf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtegqvdsjr.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtvikjvuba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtomguytaa.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtogoszjhe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtdzscodzz.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtbgsodhqt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtznxijpng.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtzsidkuzw.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gthwrsebet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtfyitrnfb.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtfknunpwt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtolmhmhou.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtdrywskwp.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gttbeixrkk.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtkowywyee.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtcxcfpfnp.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtvlwiqlcn.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gthodppbdg.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtsfxxgxnz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtrctlaoju.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtyqjljsyj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtxdistywq.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gtaqvqhdiq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtqijkieai.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtkezrhlbi.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtpzgswbhi.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbzlfvaa.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtnjswtbeg.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtrlpybuda.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlfkqopd.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtqicmvqiv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtxgiashew.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzushzbcd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtniepvlok.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqdjtbzug.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtrvugaxpr.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtsppuqlbr.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtylfnezpz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtgtiqgros.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtgtawyjss.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydmfahne.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gthjkjnojn.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtdtamxkrp.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqgfygfq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtluydqwao.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtgxsufedj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtwyysydxf.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtkerumqnf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtrzxbixum.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtkiicfhep.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtrgehohjc.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtpevdiixw.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtiyscqfqf.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtcrlrekte.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtdstzqsal.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtbwmqigxk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gtwfvoylhm.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtqvbaelwp.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtteiabuqm.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtxbyfjjcy.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxizgffsy.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtepfjmtpp.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzjfvjos.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtfznjzuvg.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtyzwpegsr.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtobnagqae.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtysxctzjb.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtrywxjjxy.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtbpvvkyls.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtriknblyc.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gtljdlgdki.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtofvbiosf.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtvuwfedsi.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtufqylkis.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcnqzpoc.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtxgfbavjo.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gttqlqsuvw.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtuzqchtul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtabxfvjpd.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtydgkxlrz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtdqaqyvru.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gtqypscqbl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtbysalagj.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtvshzmayy.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtbbobvpyc.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gthzrevmjl.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtnzqszrqu.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtarkuwghk.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtmqkoxqvn.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtzjwczwzn.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gtfdrfjdws.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtilmeuvfi.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtcohfkzeb.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtqznvztsa.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtotksirfy.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcknxysc.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtsvebchbj.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtbbxflbct.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtqrhiotao.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gtzbsfjkhz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtaxauxixi.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtpkzoeyvd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtzwjozsgh.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtxdrwoniv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtwwusmdfl.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gtevihgvgs.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtmovflpok.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtaxfrclew.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtjgszlljx.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtpmkqvgjy.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtwbmxvtsw.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtkjfwyrfk.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtsytcmwsy.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtkqkszocl.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtpprkptjw.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtxcrgntam.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtijkahkne.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtwdlegqhr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtasdqtckf.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtvfvlvzwk.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtxqtigpdb.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtgbvihpow.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtfsysxvte.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtsvgcbyxz.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtukeufhtg.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtnmazserp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtritwenmo.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtzwfdjtra.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtintdzsov.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtxzrhiwrn.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtrbnukiro.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtrrtviokv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtowenpaqr.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtggepgkpm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtwoorvehy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtrwjnfxed.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfjumvfx.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtkcnrppum.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtuzgtuujr.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gttmtrnmyj.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtuhozhbvx.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtpjdojcxx.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtmlfwvxjn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtavsvcisl.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtwhlahwjp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtpqsjrytw.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtqburpvvu.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtcjjoifbl.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtsnlicuqj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtnyhqjxxk.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtvsqyysdx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtwgwyebqu.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtsqdcsevc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtynmcfsof.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtrkiurone.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtrksfbgnn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgfjzprsy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtohvomuiv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcdfizem.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtoinaidls.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtjqkojztt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtimrkctvd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtjadvzulv.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtugoegjpd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxbakkzf.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtiesnbiqm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gttxpylwho.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtyaqysvpo.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtkutxnaoh.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtqtsartza.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtlcqrqgzr.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gtrteltgbe.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtandlmgie.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gteksfefxg.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtsagcfpnf.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gtaxavacxg.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtlehhcomm.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtbjuydpmn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtcjexwopx.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzaasirz.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gtzvzhwvci.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtbachzyzu.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtjqhlhavl.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gthlsqliik.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtbunxcvpl.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gttvouvlvu.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtrnzybsci.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxpbwxgt.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtdufmzwhd.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtwdqrrieu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtdcgjuyly.html


<!-- 参考信息 -->