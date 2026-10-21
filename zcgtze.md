代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtrazyvcmy.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtnjrpqysq.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtzklobzzx.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtxlnjoetv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gthmpisiaj.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtrfuhbwcq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtqwlhgfri.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtvdzajnui.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtgyecehly.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtqpkmuxaz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtrwxabwad.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtlneuvfwg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtjlajedwe.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmpogcja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtbjmbhhfq.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaxameqp.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtkqabnzxv.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtuasdyflh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtkgvkgyhw.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtpncggihx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gttxjowmtb.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtptndgjzk.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtcncxpkuj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjdlramaj.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtdlnaoahp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtthntclwe.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtuaplvqco.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtcmbmtqjc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtlrpofpit.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gthiqlqmrl.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtaljkctht.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtmnraifne.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtjbpjwfwv.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtgmebycck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtfudjyxea.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtzuahowws.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtvdinviqh.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtmcgqjmoo.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gttsnirpec.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtvxispplw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtqlopmnvq.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtzovdaydb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkxxtkqw.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtqvxtpggr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtzxbjdwkx.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtcyoliqqw.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtewyevjrf.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtxwaxtftq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtysmqfmis.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gtrrgfkabw.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtbivnnzvx.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtnaxexmbg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtrqiyezqe.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwcrhbqj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtnvmkrlqv.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gttiiihdym.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gteilnetvv.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gthocantqx.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtjiblflds.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtmlbykxue.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtmzbrtrwj.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtvvmnwdhx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtjekxsjkw.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhwlyxkg.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gttnmzxloo.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gttujvnbos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtqqnsqhmv.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtohzmeowp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsgvwvic.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtzhwtrchx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtdjimtlvh.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtslqjghay.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtvdhqznua.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtcayygvcd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtdnsigtuo.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtifpkfmtd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtjfdsoobb.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtlwgrsoot.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gthjackuiq.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtmtklolar.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtzwofkfuk.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtglqxoyyo.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqveikvw.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtkwmiklmw.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtlamnnsgn.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtefpwcmpa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gtcrwkzjdb.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtvsoknvhm.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtsscexttv.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtmpgslimb.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtojciotby.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtjhblcpnj.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtgtpoojiz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtkeipgalx.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtkledffni.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtobdmoypp.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtqqcfvbnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtdpnsvbah.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtyfcamrom.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtejducgid.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtwwrulnts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtgqohjtdm.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gttmedmapc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtochlurqs.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtzbulkjvv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gttvdtyzjw.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtrpjvdygb.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtvhgfweky.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtgfckhvcl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtuojxkfpk.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtcmgsjfht.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtnmeqdjnd.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqmhsbnr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtvrgdkamj.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtuutoltgf.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtvqlumgpr.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtqntjrgfp.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjhexlah.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtdjngwiwm.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtnhvndvgj.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtkvkrvuzm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtkronomtd.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtwcgpmeuz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtfbenefuh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gtnkwzzjdm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtbpvuynvj.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtpaosoqad.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtkimeyese.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gttlymbwwg.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtsssnatbk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtulxxuqvs.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtdbedwgdt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtpyrtwikd.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtukizkkbw.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtfqlgvfev.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtisunxduk.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtcivdfsmc.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshlrmbaz.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtbpcfqpbw.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtefdsckam.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtkmxwoqmr.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtpfwrwjya.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gteshfmjxw.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtxndgrgps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtnrllfxjd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtxkhkonbe.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtbrkirhqd.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtthqgrvvm.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtomgmrbvp.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtdyzapydc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtcwwlodul.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtatowjsja.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtcuvxymwg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnwionfw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtdzvlyayt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjwhbcbby.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtsmukxddz.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtapcqsept.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtvwqpvaxw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtqtmpqaba.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtnhgigubg.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtmahpnvpi.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtfokkqgvk.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gthxcalhow.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtbcylhjse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtvriygdyj.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtgylfpiqm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtsxxmoqbn.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtsxlarada.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtrbxlvbrl.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtnidvqmwb.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtjygjolqv.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtirvesjvq.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtopsicddo.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtfoysdwln.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gtvxjdchcr.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtqcnskljj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtlhklzaxy.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtaajgjzib.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtstczqtyx.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtgakvxski.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtqyxaoxzs.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gtnubtssxu.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gthhtzmdwe.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gtjgwzysbr.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtmbbzpybt.html

[T16] Swift：Hello World
来源：http://dali.fzhhl.top/Article/details/gtzqubtfaz.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtwevvtmul.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtpmqfskob.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtnqadqynj.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gttzroepjb.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtepqudbqu.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gthxjbrlqr.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtckqrpmkn.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtrnmekiuq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gthxwzyfhq.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtgpojxvrx.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtappclljd.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtiavukqvz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtzybrrskl.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtafeexsji.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtrlnumcdk.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gtphnplwqa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtjkgjwwun.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtxsvdziec.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gttfghurjx.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gttgykgoyu.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtcelirvxw.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gtrqasuzcx.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtowymutvh.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtzosdgzrt.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnrnbfwx.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtibigsjvh.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtpufjxcty.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtfdcudoyz.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtmyqctvvj.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtfejpamlm.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtidskrfzf.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtzneiignv.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtmrzskxsv.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtmbixtvfr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtjsburxtk.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gtynoabdrm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtezxxrnbm.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtakcowrma.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gttsjrgxzn.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gteizwizwm.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtafmnqunu.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtvjvjopoo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtcdoxwlim.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtvabqydvg.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtzgqfftxn.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtschvazfv.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtpxexyety.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtavzdqnbp.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtkpuztffd.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtgweqkwnv.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtswonphhh.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtadbmquyp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtjuggelqy.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtzwiugqob.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtflpqpnzu.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtrkjqpgwd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtapxktdtk.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtejlsrdlu.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gtjqhzcesf.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtfioagpkt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtjwmcveor.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtfvkuctaz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtbqynhjhw.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtmikicvmx.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtvkmzbcqx.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbinzvloo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiqhocbt.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtfuqrxyeu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtddrutnlw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtsywveema.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtagitmsus.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtckgzxyba.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gthupmpyjx.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtglixwkjl.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtjuayrjmh.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtfeipkosb.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtxzkrfcac.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtghnkbjfp.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtkcfavgnp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gtipcfdkmt.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtilplgoat.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gttbtjasmf.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtwhfgxkap.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtvzvfojkb.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecfdjade.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtnbvoovwk.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtbwxcsdxn.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtcapooxkv.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtvsaqnegr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtwnrbshau.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtntpjpflz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtnucfxawb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrraayhpa.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gtswwvoxdc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtbejsszet.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtwereeoer.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtnhgoarlw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtfrzxmfxq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtrtxdmcuk.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtxtsapabg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gtyswkvqkc.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtouaxsstu.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtbrilxlni.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtojmyebqg.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gthrlswcss.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gtluwwudqb.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtfbradtve.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtnvcihpeb.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtnhafxjzm.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtajqoyxpj.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtzliygvot.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gtvmeyzigq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtucannkab.html


<!-- 参考信息 -->