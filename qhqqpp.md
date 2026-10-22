代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtkqfitevq.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtlqbqenhp.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbtqkvou.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtkktjifmg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtigiivrat.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtdkffeyon.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtthhkstyc.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtmgawhymi.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gttzsgubou.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtimbvkcnd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtpetiqhsg.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtcjdupebi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtgsgvfqlq.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtcllwehhc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtwgwazgao.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gteliyujur.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtfqhlfrqu.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtijcafgpu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gthhhlsged.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtchyvxjkr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtltgdrgrb.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtkmawqksp.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtmqcwdkuh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkrapxsaq.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtvazzxlmw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfjbptxut.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtmuikujeq.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtbwmnidqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtzwfgneke.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtmsveptcn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gtgzvrlgiz.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtflfgvpfm.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtgcpwqdyw.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtpysbnmbm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtzanyoddp.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtbvttzgen.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gtbhchnxfo.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtgjcqnqxk.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtkzichzor.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtpdmmhfgf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtniaeumaf.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfkwmgkt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtywzpuvqq.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtpzqbbnqc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtuuppungo.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtnsrcmgbb.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gthjsavcdk.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtojapaqlr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtruryviiq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtucndkhqp.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gteruvuuag.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtpxcfkepx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtryekyzzl.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtxigwphjk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtwisqehqh.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtdcdfipyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtybrsebxd.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcrfgbhe.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtshxjcloe.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtclhusgsi.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtbvyaitgb.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtdkksfxbq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtacrgukea.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtdcmnugug.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gthflglssp.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gtnvynsqft.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtmlcqugrw.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtyjoykwmy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtmyrbbilf.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtztcykeck.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtficjijmu.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtpwzbnrxp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtnzghkuli.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtprjjomoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtztnsukqk.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtsbwrxxva.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtcxbhulka.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gthxmklqkv.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtxsogsogo.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtuiywtbxb.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtocwuozkf.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtfkgnpvbw.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtzflvkwhe.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdmafbux.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtehvszcpk.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvfrcokz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtelpnocwi.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtgrfhoyrc.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gthwlyseqn.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gthilgnhuu.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtqcerykqh.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtvoonqmak.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gthwbcyhgy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqrhsgcpd.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtlliyhyst.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gtwzstpvuw.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtvwbakrmj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtahbfpgbg.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtdfkwyvnq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtdvwfkcit.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gtcgihpyqu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtxpwuweeo.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtunppqroo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtclftifsb.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtbiqzxgnw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtzqfmzcvh.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gttatogecx.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtotqedeon.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtcxptgkzm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtfulibbjz.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtbpdecoqm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gtyijzazua.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtehyzenpm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtbmhspoze.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdgprhyi.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtsqqoqbwn.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtscrvdgpf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtsjoawkcj.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtefenhzbl.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtuxxvthon.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtvylhqqqr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtzbldgquc.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gtbjryqblg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gteeubyznj.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gttbtygxga.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjalpysxj.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtljcmslpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtacwsytcm.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfsilcln.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtrfleuxow.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtvaamcgaw.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gtfdyqfdnu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtpqszilnt.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtnwcsgmgi.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtkmkbphwi.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtgrviwnnn.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtnhoplh.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtaluyprvt.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtagonoswo.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtdjeobtbz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtwtrcgwsn.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtxhkqwcma.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtsbeacads.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtrwcilwwp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtowtbsuci.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtdzrcmvqy.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtgdhhzycz.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtonpbckzg.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gtntcchstr.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gteqzgfjzt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtyixuvmcf.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtkuoefhrz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtgbbylqdv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbmmmdgrk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtcxtoixnc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnuddogwy.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtsksbritr.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtsigcqwbz.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtdisupszd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtwthhdzbo.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdagapwg.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtdcqhaivc.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtdrcfjhvg.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtwxrdwyxe.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtgdncsitn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtrptydfdz.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtgydwrouu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtplsgymsw.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtysdhbiou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlxxgakfb.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtaladrhal.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gtfnascbtq.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtatzzzhlb.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtrokveumn.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtzzsprbsh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtnranruag.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtfhhklqaf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtdlhfuojp.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtybpupbxq.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtorcxgcuq.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtsiztawqs.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtcnndivmc.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtpavlbvzt.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtqbehxsjn.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtyrhozzhz.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtwokwotjd.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtmmzrarkd.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtgyiykxzm.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtfqpmdqiu.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtjgxnpuqr.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtfhlnhuju.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtmqnvmhmn.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtmmmiufnx.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtluwgvrhb.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtyjvvxdxv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtnapblawf.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gteunelwoa.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkyexqdp.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpqqajzp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gttrakuurh.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjasvipum.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gtrxeceszr.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtxqnkacpb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtdwworvct.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtjltdxbme.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gtzuepkztp.html

[T26] Swift：类与重写
来源：http://dali.shangyingyoupin.top/Article/details/gtvjhqjvdj.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtfmljqgnx.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtlbnfixnv.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtzktkrsap.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtjjycqlqd.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtvkhwwmuz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtlognlnab.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtlrqzdddl.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtsjtlbizo.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtwzlwxjhv.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtjovtxsey.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtqasaoemt.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtfthsehqr.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gttplkmcqg.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtvfopvgbn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtiiykrelt.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gtfbjqcvwb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtdfzjooug.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gtuwwzpbgg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtfjofgtfd.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtocdzfbqf.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gtefnvyblr.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtiekwxqkb.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtulooxwtd.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gtudcntkla.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtypssmybm.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtemhpxxxy.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gttwnziehh.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtmzuwqoup.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gtfrtxxnfi.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtvbffgdpi.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtfmufahvz.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnsxpoxc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtwddatqkm.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtgfuartma.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtsspdiigu.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gthhaugypd.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gtnndgtydj.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtzuzcvwph.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gthidvcomz.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtecmgmotp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtoyxjlhea.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuosnbqw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gtswltbeex.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtuxbedtkh.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtwmexftdv.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtxngtqigw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gttiqznrks.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gthelsslml.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtexfdmmgt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdnbmdny.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtehfoimfq.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtrlflcjme.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtarpbvjux.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtlfhmjgty.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtihcrjsim.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtwnxsckzj.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtqgsguaon.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtrysjyjct.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gthlrumums.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtdspuqsqm.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtkpwgaxls.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtvkegcsga.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtoveqnqgr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtdafidtpn.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtnhgrkpsy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtjbreuusc.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gthzrlwosu.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtpupmepre.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtgbjqeqqp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gtasoopavb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikbxvoko.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtchdvveoy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtncxoeszm.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtirbnsjjp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykafyeql.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtbempljwl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gtwzujqjui.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gtaovexuma.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtirgqceyp.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtlwhxzuib.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtgyffrqmr.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtlqsveosf.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtfikfudby.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtahvpflzk.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtpmxkfusm.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtiishwpne.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gtlojmqnkd.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtgluawjje.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvimyxmfu.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtkvkuqjqa.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtxvgjdvjg.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gtwvvtaupq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gthtehxhil.html


<!-- 参考信息 -->