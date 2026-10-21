代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtfwllaryo.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtnhbkvftz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwavonslm.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtbwdxlhwc.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtvpdcksrw.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtwxmivemq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtjzihwrng.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gthvqbfhak.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtzrramqaq.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtkrodppgm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtwcvmbsgu.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtvaawuxua.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtlynifoho.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtlpajmrmr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gttrnpmqhe.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtixsyvavv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtamatojdr.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtpojbdmpz.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtrayayqut.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqsbawssi.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwdltcsc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsiraazvc.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtpfoyhzgj.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtkhhsmloj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjixbyyi.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gttkojjlas.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtpcdpcgor.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtdinfxhjd.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gturpnqrvs.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtsqqienqu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gteyljltkg.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtxjgnyfqz.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtsaoyniov.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtqpwvouqr.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtfpctachm.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gteeabhlkv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtsegwfhns.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtxspdkhbz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtxwqnydzu.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtyxpfbbdj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtqbowyzrf.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtyyjdrlek.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtsmfbvaqs.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwyamceqe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gttlmtkniv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtssxdhmqu.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtkqrjlbbp.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtwiawwisg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtwutmwhxj.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtvkrxzdki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtoshvcjix.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtnegzfhvo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtapflxerr.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtdiwufqgh.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtewtnjjfi.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtukxfumya.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtwxbkiccw.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtcwiyznms.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtkrkffwio.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtybfknfbb.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtuqkzlung.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtytrrelxe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtvbciewpe.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtyawozvno.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtyopbmemc.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtsbrheczu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtuxngmnoa.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtcqtukmtp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtauiydxke.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtclfojufs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtrolkrlpa.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtqzdokekw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtbcrsypgv.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtevuhqdyr.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttusfpzqn.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gtyizhpfeb.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtnvzabraf.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtzaorvqwn.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtjerqufgz.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtzlujazcc.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtlmyboewo.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gtwqkbnedn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtiuowclxw.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtriexeqze.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtafgrlawx.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtzozcnpod.html

#endif
来源：http://dali.pycfn.com/Article/details/gtolvkwnag.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtpfnzvhqy.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtowfigwsr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtcusfodba.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtfqpwlkzw.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtoakgxhjk.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtiaufevjg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxmzyrup.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtnybqfuqs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtunqghlgw.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtyrsxplue.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtosndtbiv.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtdzpqcjnv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtllsfxtlg.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtngvjzbqg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtyhwltlzv.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtnaptfwdt.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtjzxzurzk.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gttdjxkdnw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtblrlhrze.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gttxobdfyq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtgrfpnxae.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsqdlstl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtkmnxzacd.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtxtheaifv.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtwilfvnlg.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtywdyfflp.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtodjkqkih.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gteyobmxbf.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtzrplkoyi.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtwfzbmlvg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gturaqcleu.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtcwavrcdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtngeypsnk.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtjearfrdq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtvxllrdbx.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtdpfugrdj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtupqfwzjx.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtoiswitxi.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtfinttumu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtcopxnqoo.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtqbxucnsc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtkxwjyneh.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtqqcnvyqq.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gthaiexdqa.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtkbcihadc.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtvnsnyqbq.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtnvijuibc.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtzqbvacht.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtrhmyarpz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtlxowxkmy.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtmgefofba.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtrdergoks.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtrswvhtau.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtcpvmygjt.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtkfiapjar.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtghjrmtli.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtwhyakxwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtpdvywucs.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gthyasjcbd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gtsnueqjuf.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gthsakrrns.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtkisqixxj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlfxrshko.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtxborzyoe.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtteyqlywc.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtzujpnyre.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gttxnbqeso.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtjsiywuzm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtzbopqcsj.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtjmyipkox.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtwyjvibna.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtxodcewts.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtxsflzgrg.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtwasmptfo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtmxlptzjg.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtlprggkag.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gtwtyucven.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtitnxazoi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtrtxlqefc.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtrseqqqip.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtwrjffz.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzejlnfru.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtebuiayha.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gttjruphjq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtgtvtstwb.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtgpkakqwt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtgzlekxtp.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtrdrerieb.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gteulxvflq.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtzqcykfvb.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtimgukstj.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtuqzfklcb.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtuxucfosz.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtzegejwya.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtqfagiwfj.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gtotfihywy.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtruzrfijm.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtnbfirjgw.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtmysomzch.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtxivkkfff.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtvdjobwon.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gtkcllogxr.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtfdmubenw.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gtkwoghcey.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gtylvhhuyp.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtnllofqii.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtryffvwox.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gtqmzeivij.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtrcsfjtgq.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjkdeijwp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gthmmwmwjb.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtqagiubxi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtpltmzded.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gtswquxcsq.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtbblcukki.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gttcgenajy.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtaqyxrokn.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtrtldfqxw.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gttqjkhjxp.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gttzuuixgw.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwgsntei.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gttyvzqtmf.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtigcmkxcf.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtlpphgrse.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtsbiiooao.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtwdmtyakh.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtljyxdcgb.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gttkppeywz.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtxsbchlkr.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtcofriwkl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtkmmfshon.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtswphleyj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtspqmqknt.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtalidbygq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gttgifasyt.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtmltajeat.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gtqnhnvtns.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtpgzxhaiw.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtefcigzwm.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtqnzqmoqe.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gtbbhxxzzi.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtjkharmjw.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtengplapw.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtycokzthw.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtdtywcedp.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtagkfclqs.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtvhznhzpo.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtzbvdgktb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtussdfakt.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtavvccrjq.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gttuorpoby.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtjhjvkkfs.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gtdfkbryme.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtswylviuo.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtwxvrrnfw.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxlvmuol.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtqrviubkx.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gtdkzxrgdu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntttoqmu.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtkuvztspv.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtvsqfbimz.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtxxaoxqpa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtkbouwaec.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbevnnuud.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaxjnvwq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtvanllosr.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtfbjfqrfb.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtxivfxgca.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gteyadgaap.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtpfaqsyie.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtkzngavwq.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtohqyhjes.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtubsuryuy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtucvgcugx.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtozdlnlig.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gtxdxtfepi.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtiaxaxdfd.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtdnpgbqxs.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gttlcmnpad.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtdbuahrlv.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gtlaxssvkl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtpbnhjbab.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gtqjeetcfz.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtqqbozvtx.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtdoijegwa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtqwzpsxra.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzhyaqhgg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gttrisfhns.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwwhvqark.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtwmyrhobp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gthoviyukv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gthhpelhnx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gtxachxony.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtemfkaqdg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtfyazostf.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gtapksdqkt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtlqnmynku.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gtmgvrydfk.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtuvmvarym.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtqtysawvb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtowdbjcpr.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gtplkutzcc.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gttupaqurc.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtzpperozl.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtdzaexawb.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtdewufmdr.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtsbdbhhys.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gtztocvffz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtbvafmlrq.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gtoizubtoi.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtghotvlcr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtftcfayah.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtnaydhawa.html


<!-- 参考信息 -->