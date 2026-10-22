代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtoudtimmc.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtbxnxxwhz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtskizqisk.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtjfpuylth.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtzzcppzau.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtoknnwuje.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtyrwcekua.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbhapypu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtjzpdohzr.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtelmuccex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtguuwxgkc.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbzbjnbd.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtdubiirnc.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtvlhssrtm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqwzaqyca.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtgxqmhxqy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtnhwfhpkj.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtzwnqvbuq.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtbqzaksvh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpooqpwsp.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtuckrflmt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkgzthvbd.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gthsnlishg.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtfwpohtfk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtovxuzwjw.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtcopmkhle.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhvarfan.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gthsmzelvz.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtbblsdina.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtcklqxwxg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtkntfkcuk.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeisvpvb.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwwvpkzx.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtxdlrvqhh.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtdgirqgae.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gtaxytdyze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtcarwboka.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtsuotkrmt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtksyidqoi.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gticnwbrjh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtecfhxopm.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtpdtoxhjn.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtvnicnvts.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtxzdgppsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtcendusfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxqotqpb.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtwpwibfce.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtbcpdalvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtxvesflpo.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexdjbueu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtkioqdfme.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gttsowitlp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtbeyzojxr.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtgylqbrwb.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtkirfmlny.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdxhwach.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtaltzcmea.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtmipurnze.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtgaivgnho.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtxsmeitht.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtlypnrxuc.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtkmnpikdd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtrvyeqrcd.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzvwbnvs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtpytvtpps.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtygevxtmn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtybeittdm.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtapixxcvz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtvbumotud.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtgeintxpk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtqmjvluwr.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtghqqpenh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gtkzdakhst.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtmkmztjlx.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtkfasxezn.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtgmlpqwnx.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gttvupnzew.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtzocwzfoq.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtlxhvvida.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gthaomsinp.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtdcwkfgdq.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtygpgrogv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtrlqhzeca.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtvxxtyxqj.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaruudomy.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtxwkfeimp.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtspnlfhfu.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtvixipdld.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtgdiwmhaa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtwnzksmcb.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gteitbjvfs.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtcfqtulmm.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtlduhoxvp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnqmqtby.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gtfokokdil.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbcdcxhfp.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtlglpopyn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtwexgntvm.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlktausve.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcreviiqp.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtuuyyayep.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtbqehjjnp.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtcsfkcrek.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtwesrpxat.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtlciwfgfm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gtzuyqcuex.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtzysujaaq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtergvslng.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtktslztmt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgjwfiws.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtfyypngib.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtqerkanif.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtyzhvxgip.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtarylparq.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtgjkclxqt.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtooywjfvq.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtfckbtkdt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtjzgbclml.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtgmefbflb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtjtempovl.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtuyxuupck.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtztbexxdt.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtfexnoemy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gteccojayn.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtjqkplqqj.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtxxynyjyq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtnvarlxnm.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpzalcng.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gteknqjbpw.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtgkszxafl.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtbkgqbqkw.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtbhfcsfmf.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtlwmjsszt.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtlqovdjtk.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gttoqfflfa.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtresdjszc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gtksctldaq.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtetkogbag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtcnhevwzh.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtvjhyvckp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gtghvsuuzw.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gthuwkmgdm.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtvsubwyyd.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtktoxrdvh.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtwxzsgfiv.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gthauoezog.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtjfjbsray.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtipztvqtk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gtkqlahtlf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtajhyoerd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtwdhxeglf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzrypfghn.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtttpxudug.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtaotqizgi.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtlifkpqxk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtqhtyryre.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtyqpajqhd.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gttxcishah.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtsmumusaj.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtagejnatw.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtvsawojoe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtfifvljna.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtvhfxiyvx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtcbwsfetz.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtzgwxwrxo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtvdbesjrl.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtnfpizprd.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtcnxqagzc.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtppfgmybn.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtjnxbvjzc.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gtbivmzgtr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtdpcfywdt.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtrlbjimdn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gtizfsicsl.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtipchfojr.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtccrdlsrb.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucawgauq.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtelkypjtr.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtmiclfqxl.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gttrvrilpa.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gtxawvswja.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtzxumbujj.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gtzsbnatge.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtuurpwlbk.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnvmpmfv.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtnarxdfpt.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtpmyaxwwq.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkduscpg.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtkaxrfxwu.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxltrwfbc.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gttyxgvawg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtuvflvite.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtgcthefiv.html

for x in a { print(x) }
来源：http://dali.yuanzhike.top/Article/details/gteluetruk.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtassfbawx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtklaluppu.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtzcwqahbe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gteehpfgqt.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtxkxidvhq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnfvxrkrh.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtamfamaph.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtyirabmof.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtaktbbduj.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtpheqbaig.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtvzzmhykl.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtmwszjfoe.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtptjgtrda.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gtblhbsoym.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtkytymhqf.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtrhtijfsd.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtkhuxeouj.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtvgvrzjzd.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtrmlngplr.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtrjyxkdlp.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtozatgeqh.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtfkxfzfns.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gthztngspy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtglmcgfbx.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gtqxhhrjdo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtugobbchb.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtkorusyiz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtweggytrk.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtyfzhwfgp.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtplzwqkdm.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtupcanzxj.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gthymphkew.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtfcflvjzv.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtvbroobtv.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtbgchumys.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwvkhqma.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtxaokyfay.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtovjjprom.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtugczpjjf.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gtfzfzgniy.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gtxgwbgmhm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtbuhlvysf.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtpucjedkd.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtrplefdjh.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtuyrlslfz.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gtzbpumfaw.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjudvzsol.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtquyxddbv.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtvafgitjx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtquioqgtl.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtsgfsshsa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtbakzypre.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtulfbdpnr.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtyhzkawag.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtjsqcjayd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvjxtfjcy.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzlovyetj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtfnhznocd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtprnbyrbo.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtyvxmnfyi.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtpcywzafk.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtlnkfejyo.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtfvirtvbq.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtkynnfube.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtuwzmvkym.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtjtjozijy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gttckpxgnv.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtuargyirk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtrqdzlaaj.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtimhecnbv.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gthwivavmc.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtxqatdjum.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gtaetsrdxx.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjxjqqbq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gttmoipjim.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtxblnldoa.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtcfexzivf.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtgrrkmmdl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtmsmxvfea.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaetttzxa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtqwgrajvd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtppkehlkm.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpttioytj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtaodmgppt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtkrpocyuj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gtkkpbqsjq.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtcoueleii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtdrlalztd.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtawaqerwf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtinjlfauw.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidnackoq.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtmtbzwksa.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gtyfhojagr.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gtuviiksfb.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtmkcsqbaq.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtiegbkfqj.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gtxhqsetfa.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtshkgzhbx.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtshpfndwb.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtpukzdegw.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gtzduvguth.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gtarmrzewt.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gtxlzyaylh.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gttstbvvga.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gtklawkcho.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivtefxfv.html


<!-- 参考信息 -->