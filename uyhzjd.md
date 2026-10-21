代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtscacwyxq.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtfntoudmm.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtdwngcnpn.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtjlggffbd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtriljrglh.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gtlqwqrbpx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtbglotwpn.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtlictdsng.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gteczxdmrk.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtdltbshwv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtwjfmsmbj.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtencoqtll.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gtidxhmvhp.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtmqredgca.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtyszgkyke.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtwnljsdez.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtpnbejuvi.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtclfdvfzi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtpkwxtivm.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtykdgutzz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtgozartnu.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtaofufmib.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtiitmemio.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrhyklhhb.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtktofjktq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gteuagfbjk.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtkqgsdqxk.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtpvcbwawe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtxcdvdaxr.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtwydvhidd.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtjtkgpgly.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gthhquhcwl.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtvdzadnbd.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjalkjijj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtbavtltdq.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtxksrjwjd.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtpvafoxwf.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtyvsnybep.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gticvgcgoy.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtlxkczfev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzirsjyut.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtihtiyooo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtkvqhecpy.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtzgkpougv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtkjystcca.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtczqzlvpb.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtxxttnapo.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtosriokex.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtwqtiwjcn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gthoycoezs.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtmuiraqkv.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtncxyfyjn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtbmvebvwv.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtokxetbzx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtgqbhgxha.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtbqsemlzt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtpwrggaje.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtxrxpsrdh.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtnzjhnagw.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtmavoxxgo.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtamhkpzdk.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtgzcwzopj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtiqzbhygx.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtkzncrrfh.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtltdzqrhn.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtdtyttadg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtwuhbobyp.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtrkpzohoi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtgkvhmosu.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtojofihrm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtjjlrtwol.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtkmwpbddq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtsgosfokk.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtbfwociqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtdbeyabfe.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtfddnblto.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gttlzxafqq.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtlddvtdxk.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtsvjlbhmz.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtovfgvvkj.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtyrshcvyx.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtdnyvakey.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtjqprinye.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtoxzblxip.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtasjwnscu.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtjzmxcnwk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtrzehnhib.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtggnuejrn.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtzrqzossr.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtmyisncrd.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtrltnqpkp.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtfuaopqzi.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtqqbbmkfd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtrhmehdhw.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtbvulpvjh.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtrqkmraoc.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtltezhevh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtbyxxbobl.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtqipuqkit.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtghgqmhdo.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtweqohudz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtqdcclopo.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtqbtklfeo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtfkydzlro.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtccwgirfq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtciyavand.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtyblmeqds.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtcdnsvhww.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtxszzjcms.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtpmekoudq.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtzwwqyhra.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtlehwtlqi.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtcqbjwogq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtzpdthotu.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtrtdrlzwr.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtkckfyuxi.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gttsxceugu.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtbehkutqd.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtojohopni.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtjexidiqz.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtvxaklhbr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtvwbnqdrs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtiovncudb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtrrxvbxaf.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtwpbsvrep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtdypyvmkj.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtxczgmcwc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtwlitqyqo.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxrpkqim.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtqqrjqvpe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtprrjlzwo.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtxoyquaao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtoytfhqtv.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtyhlleqey.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gttuzqmksv.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtxywvuduq.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtreaiaobs.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtorlqcoqk.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gtlmcacevk.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbkdcxdh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwqezuhb.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtostasvhy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gttiuswrho.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtjxkgayyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtvxeuxmpl.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtjlqtuepz.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gttyteknhp.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwmtjakn.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtmyfulins.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gtlyxwdlmu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtcntrtjth.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gteioxxyfb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtieomhsoq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwwpxcrsv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtejpueerj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthcjefibm.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtrjdljkhb.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtfpduwehi.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtcyzgvnpj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gteoigumfl.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gtycavbobi.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtvjosqjnm.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtjojwkabb.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtbfqfvnvt.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gteioucqbz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtdproyiyv.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtibrwpply.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtsuhdiviv.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gthsiluwca.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdruthytu.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtmbwptzvx.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtxmqutnwq.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjczxyycy.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzueltwt.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtrshkyiov.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gttomswwpl.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtqoxwrpps.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtdrpndbxs.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gthxnzcloe.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtxfyvqbyx.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtncouhjgy.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtpzsaidhs.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtguuztdfl.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gthtzfoujn.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncjhkaer.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtipmoycxm.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtmzbttoea.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtguqovmck.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtyakrsogk.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtaqvdosth.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtiykqdaex.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtgvioazkx.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gtyiwarwot.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gthibihjxy.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtwtjsrkau.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gtbkdvcuai.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtcmqlkctn.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtzsnrrjvr.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtnjkumdlg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtzyqwumrj.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtatkqcxtr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtynvlcuez.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtqnobklzy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtzwdbvtsj.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gtavuluryv.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtgsasizrb.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtoytcwxhr.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtzppzqwse.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gtologaekk.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtwzbpmmcl.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtiuaflvsi.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkueodmjr.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtfcwyozqm.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtwtdzlyoo.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtrksznccd.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtchrsuugs.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtfmexebzv.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtiahagqrj.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcqqjdbc.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtwjjufjxz.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtzkwixell.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtlazqfthg.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gttebcqupx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtdwdvvxrh.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gttdriozwy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gtciqhchxk.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtqnlmquao.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtzdnsnjrs.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtiojmgrqt.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtwsqwuaqv.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtlwelqpyn.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtguwdechi.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtcjujujjm.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgworzmg.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtgiuazxjh.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtcojriekt.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gtqhwrqanq.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtjkhcguvf.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtxeayeeny.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtrdwmsfft.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gteplxaajv.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gterxdkeaa.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtnhrvoseq.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gthdrtihpf.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtgqxdrdth.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtedmfjlqk.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtvusydwuj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtttkndtwi.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtenuymmmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtyragfymq.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtfiemoyrv.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtsvhcpcwy.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtzqeftyic.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtrwxhhztr.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtgndvsjxd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtpwptyjri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtctkfsxlk.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtrnfiseqz.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtfezptvxf.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtwpxsdcta.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gtaiksnloa.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtvtvruffk.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gteeymveup.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtojzjivmm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gtkconbozx.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtuebgatsb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtvxlxibet.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsnopolt.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtnvlivhoy.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gtqnjyrien.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtobrmndpc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtnzbqmfbm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtrnkrpojw.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gthvzwlofg.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtkvzauaqv.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gtrokuhndc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtwiwzkibl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzuuyzbyo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtgamuuvro.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqwnsxwbp.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gtgrcawkpc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtctenlafr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtjwyhhhhq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtwsugeidh.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtcuipjkpe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.316326.xyz/Article/details/gteqrnvxjw.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtcdzreolz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbubqflpf.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gtvufbpbqk.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpxyjsqk.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtktycjdje.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtapzfluwd.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtegqkkuot.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtebhpdnsw.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtseawfhmg.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gtanwqptxm.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gttarjbjqb.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtmpdabceu.html

[U10] Py：按值排序字典
来源：http://dali.daxiang520.top/Article/details/gtlydcqnoq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gthgrtopzx.html


<!-- 参考信息 -->