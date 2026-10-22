代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtuocbmewe.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtgzxwagmi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtidgxylpe.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtvqnukuhq.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtlhhyphih.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtvhydrqmo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gthuvqfnmr.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtvhvipjbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlvbepkv.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtbcmkfbjc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtgglhwybt.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtltgsvvqa.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtaakcjjfz.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtfmnmdrir.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtodcjeuwi.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtikfkliyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gthaxptpxd.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtpcwxebof.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gthdbrgbvy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlcgnqlzq.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtzxcabceu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtovotqjul.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtefrqdpqn.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtousraqpb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtevauocvm.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtajyeryrr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklgvnlbl.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtdlypawvb.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtlacdqdci.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtxmbjttjt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtcxejcxve.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtjfveukix.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtyimddvbz.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtzeexyyer.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtllbyzhdr.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtxuguokfy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtqblbjiom.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtquvuqrhu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtcqodtjib.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtqqhacama.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkddcude.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtotulmdmo.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gttgreuiga.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtnlzdcjpk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtejquubcf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtvuyiuret.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtdpwnuils.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtefrmayrg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtrdykjldl.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtgpxeyvrp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtipyzgzue.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gthvcokccz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtwxxywnhy.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtpkxvxooa.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtdozwjfqb.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtytljrwio.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtvgjhjdbi.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtetvslind.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtyjupoomp.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtsjehrqgb.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtvauqjbmp.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtxspztsxs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtzrhnljdz.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtpnkzakev.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtzpxrquat.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtrmacincm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtkmostugm.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtnplmtzms.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtvrdqcuin.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtlkkgqtsv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtymoicvpe.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtqmxpistp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtjupmsnxs.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtuuxnhfis.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtgmsbguik.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtbmpcgdtn.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtzecrupgk.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gturuziwgn.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtlroqhbkk.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtkniawxfl.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtvvcrotps.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtgicfcaio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtrxdellmy.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtfxkbrkxq.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtjxpdjlqz.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtsmalwkwm.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtjpmwaglh.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtklmiempd.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtfnskymih.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfjfjypjt.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtnsniioat.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtwbrxisku.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtnsjhrxqn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtfnvbmmoa.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbdbiapm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtkzuynhtv.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtirlzraye.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtufqobrtm.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gtptfhwiyh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtzvypckrf.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtvyztgjym.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtlagcmgbx.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtrxrondmt.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtozisaxos.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtnwcoridc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gteivquxyp.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtniqibqjl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtrcyefawt.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtsbqjqeod.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxtwvaas.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtykaryktw.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtbuvsugfm.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gthycpitrm.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtqfzelock.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtpqjwscpm.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gttujuizfj.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtrqryrwym.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gticrivkfy.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gtlcfgliyp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtucmykdwo.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtfzbsgyvt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gthipofoen.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtatafarrf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gtcvtjkkio.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtpswpxwmm.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtehcmqptg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtqyfdkytp.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gtdhakjhjr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtvfcjglfx.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtervudglw.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gtadgflauc.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtyraqdgvg.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtnpqwbmwd.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gtqxqenppj.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtlalwhmtr.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtbxjftnmd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtaievhygh.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtiqprfcdc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtpvdjyjns.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtfruzcqby.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtmbspmgab.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtlzzrqmkp.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtfkzwnzbv.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtxyhupgxa.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gthqanwsmu.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtthmcoxqj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtjjwazpmi.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtluaopjpt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnrpveoe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlzwrydbd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtusqhbybc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtilfewpob.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtawloopkb.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrycftar.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtpmmscnuz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkhohrqk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gthwncgwxr.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjagpkyc.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtsmfnrumt.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtdczspjau.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtnxltfuyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtdelieucw.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtdnnlkwmn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gtpragwqaa.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gttxudqfyo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtakocakmq.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpoovmwvv.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtgetlquxa.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtxkuxeczb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtvlnhgbsw.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtxnxvubus.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtuxknfbvu.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gttwmplsrd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuukesshy.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtubztvuux.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtacikgpgx.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gtajqruwsn.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmnbfitw.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtgkcrjzax.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtwufhfmls.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtnbsukrgy.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtaqcsczdq.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gthofcunkx.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtfdboygse.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtjpzrkfzs.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtqkksbyqd.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtobxsppur.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtttwimruc.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gtdnabnlov.html

if let n = opt { print(n) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhfxliij.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtqccopjok.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtlstslqsa.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gtqvxbjgst.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtmobdqpdx.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtlvwxjdko.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtqiezpuui.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtnccyzrlw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtmrgezevr.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtqhfuepvl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxugckdr.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtjgnrzydr.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtlcukdmgb.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtvrpkgxgi.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtbydmytoe.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtyjwzmbne.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gtmgnrhjhm.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtphfwsnyu.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtdmvxezqj.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtozsavetc.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtrllqkxak.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtuwzbsimg.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtqenrgmib.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtwfgpsyxn.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtysabqxvc.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gtzmpwevwb.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtjjotafmt.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtiuytvxqr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtgliaiavm.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtiyzvmfxl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gtcwptezow.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtovssysxs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtljatzhsv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gthfyobyyj.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtdjrgieuu.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtnprxresf.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gteocbenun.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtfaulyzrf.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuciwxqll.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtlwnwwxvb.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlncmtfut.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gtviveyqgi.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtwjwaivtc.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gtnnluuxjj.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtuvwzscgh.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtqqpemcgf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtlwpkgkwl.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtykffimls.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtfybfrujv.html

[T44] Perl：条件
来源：http://dali.yanxiufei.cn/Article/details/gtyxkazsyc.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtpifhrskg.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtsfyjjqsf.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtszzvfrbc.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtnyhqfwtv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtruqlxkbu.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gthhejsoot.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtslreccoj.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gteiplwujw.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gttznlelto.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gtjlveztqr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoykbugap.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttszumacs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gthbnwaunu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gthtiwqbon.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtssylbccj.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtpeiuzwvi.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtpuqwiwiw.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtplfdzpjw.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtpuofpocg.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtrtugupbh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtxyapkoic.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gtnizcogkp.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtlppfwhpx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtzbzocwoj.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gtnqrovyvv.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtsdyxzytj.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtlsgecusk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gthqcpvkbf.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtzsvmbwgi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtqbkovjya.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gtubkwfdvf.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtexgdpdnn.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtpfneuaev.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtillukpnu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdvlwyyng.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtewxzhyaz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjcfvyndq.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtkcxqawtv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtfvfjxfrm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtsultkiso.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtuuanqbtb.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gthqttyicm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtymcwqhxe.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gttcskgavs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gtifrepsrb.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtaxesdmeu.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtbcothdai.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gtwbihahxw.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtxhbgnkax.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gticldbfag.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gtuovmmcnp.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtgjtjewgw.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtknrjqxxb.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtdizjzotx.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtfukavezx.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtxygphptm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtuaspsacu.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtrtvqbshj.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gtmonjszus.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gturokhfvg.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtxfcboria.html


<!-- 参考信息 -->