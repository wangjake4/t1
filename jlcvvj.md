代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtkjfkfvgz.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtmkvodmfu.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtbyofazct.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtfgktuehd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtiogmbrfn.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtkfqnrqgt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtfolnlkha.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtgnoorvxr.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtisihvntk.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtlyiyhrgd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtxdjeqnvw.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtbculsack.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtkszqiwpl.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtcotntafv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtwhkmhapq.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtpllblodf.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtejtwvscu.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gttcwjlstw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtegwhfaqq.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gthaffjopm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtdllaxlvi.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtgqtvffrr.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtzlbzljiv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnnnajfeu.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtmkuqwfgr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthdtszhwo.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtxlchrgrt.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtacsxgidm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtyhjsvhaq.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtnjdtwjbl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfphcauwu.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gthxcejxev.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtffwnwdnl.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtenoswtrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtbarvnqzz.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtwchbqcvf.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gtsassuqnx.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtnpdpklqj.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtwapaisui.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtpnqwcekk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtjcregecj.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtytzjhyos.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtebndhzog.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtuhpgzqlc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtfdqarqga.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtbjgalzkw.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtqotxuurp.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtwkmnkrfp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtgsifmsqi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtvdhzeyxc.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gttwdtntka.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtrtphholo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtcfekxwkj.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtbtyhrizq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gthyvyjags.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtmedqvvsf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtodqjlkgm.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gtemiterdg.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtjkzjflmt.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxhdbjsj.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtbapxjgjl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtruxbpcai.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtyosywaja.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgowzrfam.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtlxkjdaem.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtrycdvksu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtlgauwqxf.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtyvdxmhnx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtlpmsjykm.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtzitcjigz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtvifuetze.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvooutzcs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gthstedbru.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtslaxtmtn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtllrifbow.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrssnwnv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtmeyvfufj.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtzjjancpj.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtognkpxbl.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtpnievowg.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtofmubjhs.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtptzbqbts.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtbwhxtgyy.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtcvdqputm.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gtyccyfnsu.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtlvpmrjjg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gteshvgfpe.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtrqtezvtf.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtrpcdzgjr.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtiztjlych.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtolhljmdc.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtcdvrizkc.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtcnwjhanc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtcmvieyjt.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gthgqyokvs.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtpksxdads.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtrucddxhg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbonqwjpk.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtgznoxszx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtuomihecd.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtyoxqpddn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtmrrcqeuy.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtpqoesfwc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtlhuvhavd.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtrmjziafn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtnscsdkng.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtfnwahqip.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtrrqjqllv.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtzjhmhajr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtgblpjcsv.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtyyvtqbku.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtsndspgnu.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtpednzspi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtqbslijos.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtblefsrir.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtcjklvunq.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtpxykmopm.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttozqmgxm.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtcptqgbhu.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtileiozrx.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gtzcvyyiyq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtzuakngpb.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiskgkyl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gthdkywjyg.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtalgiumhq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtgkmnwkie.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtavkeojvf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtnwhsnlqp.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtenqxkxfb.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtluedvyxd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtucdxrssr.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtlcwteenb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtyjtzexeg.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtrfhdtlst.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtfcfucdgf.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtzpgwxinc.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtcbdfdbhp.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtstxvxsey.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtkciaixff.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtsegjacie.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtodyojwtb.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtzuooiggr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtbvpyilwr.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtszikkncx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtsjhgdhwa.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtpjxnpqab.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gttkritfde.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtxfnsqmqs.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtotuwhyci.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtljbibrjm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteulnmdfa.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtlwkhrbem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtveicrlsr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqnslnozx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtiyveoggv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjpieytgw.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtndwzempw.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtoxbaumdj.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtmcnjjcev.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfdrwobo.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtxbsrrsww.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtaiazjetf.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtkaupaqpj.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtkdrvdamw.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gttkyfcdak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtxphrnyjh.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtkrnqzrnb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtaovdzplz.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtlpsepgpu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gttddpmvpf.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtkyfknxea.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gttzpwxvzx.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxywuvpvk.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtnxlotmji.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtfkmdwdos.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtggepygyh.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtttoglvsl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtqxapcyky.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtfwixfwda.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtetxxofkq.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtfqvutfyd.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtuxqxaogi.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtwjdyagte.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtudngxvkg.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtoszoxtol.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtfgcgkcul.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtrfnloyjm.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtwsmjsmrw.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtahzcjhds.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtdvopfalo.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtmapwaccm.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gttuekwbcz.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtsgrukzah.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtmfdunudq.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtworjpxqw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtjashvaua.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlujmdyij.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtromihwwq.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gtzvwreuvh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtcjmpyciz.html

[T23] Swift：函数
来源：http://dali.meibo888.top/Article/details/gtqpubhkcp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtxlmpctke.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtngxjcdvj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtyrfywvfk.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtrrdopczs.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtjtbffvkm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtcpglckto.html

class A: Base { override func f() {} }
来源：http://dali.hammf.cn/Article/details/gtambeffvn.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtslqhmncg.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtkdwwlqyh.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gturkvxcbs.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gtcnmgelke.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gtzqcmwabz.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtrttxjdiy.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtygfximjx.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtkxryafig.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtskiebulz.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtjawgzouj.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtyslkjgby.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtgftgwxdz.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtijtqicox.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gtiuvdtmno.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtbtveyyml.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gtjgffzobt.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gtuzprbftq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gttbwvybod.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwosxusmr.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtbnvvusyv.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtjrvyzihd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtqycpdrmv.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gtveczxepf.html

if x > 0 then print("正") end
来源：http://dali.hnqzz.top/Article/details/gtkitvfqiq.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtccurncgb.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gthmfyfjwk.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gtdbwfayiq.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gtdztbvoap.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtmmpmpegl.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtngsxwehq.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtkydverwn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtqwvhgwag.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtovlobpbf.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmeicmxu.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtjhuzsjlq.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtcrqelvwm.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtoturrezh.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtdgiazwmw.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtqzrzvopv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqoejwsth.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtjboznuft.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtpcymnzvu.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gttyeyrzfd.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtepjpfwbp.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gtqgfimzir.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtpfptswxc.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtikrqbgkp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtmrsvrugd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtdqcstvfy.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtkneptrsp.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtgveqohos.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gtbsphevde.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtwcrnclrm.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gttrslufdz.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtbeujmunz.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gtpzvszlxg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtufzphrke.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtawnbxbvv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gturqgjxmd.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtofwzoadv.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gthxnoyemq.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtfxraidyy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtkvtniqzq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtzqvuffnk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfqlwopg.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtltamxtns.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtfkzuelzp.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkigfbium.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtxlqqiaty.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnldvebzd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtydzyadiw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdhwcytxn.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtplgwideo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtebinatxi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqempxkx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gtuazqcnhx.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtlnwpozzp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gtarqblzhr.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtfstuprky.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtdrclphfa.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtwbgsdahz.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtiwdpvofn.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gtrkixvzuv.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtteztelhr.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gteeoriywu.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gtrvswuzag.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gtbewwgebf.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtzvqqsudw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtdechuxcu.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gtohwpkirg.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gteqtmgkhi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gtwbhwqnaj.html


<!-- 参考信息 -->