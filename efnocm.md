代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gt2yndrrxjj.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2unldmefp.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2gbqbadlv.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2gemahrxq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2iodhwxxn.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2zfgaihmq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2fenctpxd.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gt2rxfaqifn.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gt2iaeauqib.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hakqupms.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2mbnofwem.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2oukhfsky.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2ionqagtd.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gt2ekpcdpqi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqiukksk.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gt2urujblgk.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2bwfnwfdq.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kovkbqzn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gt2jfhxigtb.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gt2rdtjckwm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gt2hjivhgnd.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2xogpbacz.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2uwpejawa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kiukvesx.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtprlppo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2nxdxemen.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2bdkgflic.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gt2qxquewhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gt2hprjorqa.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2ahjslaqj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgbydpyl.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gt2ihzmbcrj.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gt2tcryflsg.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gt2qfwdpyfk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibolhyvh.html

[S05] C：字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2xmrnektz.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2qaoijmwn.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2ophmjuge.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gt2kbcsddpg.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrixdqbx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2mtbvmekw.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gt2xogwmsdl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqbdwkrq.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2fkfwpbvn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2intoijqp.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gt2sxdmoiyc.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zobipdrc.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czsmgwij.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2fzdtkbtd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmewxdoj.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2dnucjout.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2lcndqfdy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2yazdmqxd.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gt2uppwkdeh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gt2suxqviaj.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2lgwpgbow.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2lfsmfnwf.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2terlzaud.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gt2wzbcazsd.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gt2yjhremvx.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gt2izmlzosv.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2nisgpmuk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2satzpvmo.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gt2wxnvoejg.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gt2nemxkwwm.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gt2dbozufes.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2qwvzudiw.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gt2aqzajatv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsguhrdi.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2cucwuuzt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2iqixykeo.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2voqscfut.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gt2qldtpdnv.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gt2pjmupfjc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gt2wrphpmjr.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gt2luiigwac.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gt2xkpjavns.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gt2pqcbetwm.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2yeurosea.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gt2oadbnswt.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2fdnioirx.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2pigiuerb.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2ludmarbp.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gt2uwjiihpu.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fshyfnfh.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2uppcvhfj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gt2brpijxsm.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gt2vupzufrt.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gt2vasyrsnl.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2lmalnfww.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2qoowkyxz.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2ecebslfm.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gt2apsrqnde.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2mhsxkjgf.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xpmputil.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2szecvitl.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2hdglylin.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gt2dkwfjxsk.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gt2eplaqzml.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gxuvwiku.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gt2gxsvmykd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2ibbitghk.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2zavyjcch.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2ieuisgqf.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2ybvpvkif.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2pwvepcge.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2wmrvfgww.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2zhegujof.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gt2mucwfzae.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2svrmapci.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2ijnomnab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2ugsbaeya.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2ykxezdsl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gt2eyziomoc.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gt2qqmwihfe.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gt2cqkjiqvm.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2zkhrfbwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2czvrsoye.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gt2llqwsqpj.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2twtoubae.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2xsagcfrn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gt2yaxuxyss.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gt2fyldpcqs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2rddnwbwi.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2rmlmstec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2hlgckdlr.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2cqzdcksz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gt2eowaaeii.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2grjwphvi.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gt2xvofiawi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2sbxwxqry.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gt2uokcnlmq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2neihtkoa.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2ftotlbyw.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gt2heomkbwp.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2jkgletjz.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2oegygdht.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2egjqakea.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gt2uodoktlz.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gt2qknwfpdi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adtmaeul.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gt2jvgtadhm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gt2ssycuakb.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2ovsavson.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnlrzlux.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gt2btpywgpr.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2xlatekqg.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2haxsoktt.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gt2lmwmkhqm.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gt2rhuaistx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gt2pysodret.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gt2yqmgghbe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gt2nkcwhymb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2damgcscc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2nhuxpwar.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2baknfhlx.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2ctrogwbi.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2skgdbxar.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2tahcvpqu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytcgtpzd.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyhhzlbh.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2ynjkfmkn.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gt2hsfypnoo.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikisrhvn.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gt2vjnxqydm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2eclkhbln.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gt2yczjrsrm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2rrvhzxon.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2jgcvryel.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2xxoashbq.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2qetjlygx.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2xktenrpj.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gt2mkrxstvb.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gt2oskfwydr.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gt2moijhsjx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2ndmfewdz.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2oljwnnol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gt2lhboehqa.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gt2reidudyj.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2tkwktmaq.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2egtspgff.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gt2idoxosor.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2vobzcbts.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gt2lubwrfro.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gt2zpadlbcj.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gt2xelhyqwq.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2dkkpgtjp.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2mwefnhvu.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2sgggnjvn.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2rqcrvrdt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grqhmonu.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2lgyxxwuj.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2yadenyaa.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gt2jfodiwxw.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gt2ardakpxh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gt2isckbwoj.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gt2wmotnjtl.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gt2twoovgtb.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2fmvocijk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gt2hcvaxyvq.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gt2kzjfluto.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2gwxjnggj.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2jakizldp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gt2rdjbskqh.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gt2syzmuxfo.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gt2fsfvfbts.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gt2qcsvtgew.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gt2slznnhcs.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gt2ekxdzmtr.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2wuymbsfn.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2hxeltpjo.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gt2vlaoeors.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gt2vnbumrik.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gt2jboswcvu.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gt2nzwfqekm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2ewppftfg.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2lcrkwxby.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2xopvcivm.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gt2gmkenyqg.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2vqcvzrqn.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gt2yndizhvk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gt2zsipessb.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gt2ftuxqnno.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gt2xxdnhfre.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gt2ommvkazw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gt2tzddbdib.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2yxjvxmeg.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gt2dkhsxdve.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2rpqmljlw.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gt2achrzqka.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gt2zyjewynr.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gt2fxcynydm.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2uvywarut.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gt2jphdcnry.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gt2cupxsnms.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gt2uneqbvjh.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gt2mdmuamew.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gt2wjrxbrgs.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gt2jvzgnalg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2gdotfffh.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2mclecnlz.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gt2zfumvizj.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2yvkbteji.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gt2aubfwzba.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gt2hochpfzt.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gt2jozktdss.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gt2jgimxqne.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ysluamdb.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gt2gzvniymz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gt2niztxspt.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2jimakslc.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gt2hhlfxmbk.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtmpzjeg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2aomssruq.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2pzdxufkz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gt2vvipsvuu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gt2nkemhofc.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2keittfvp.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2vgiaykwk.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gt2zxptkvzw.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2bnmfppaq.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2inbetfsg.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2vmbqpcns.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gt2hhtxewhv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zihfwknn.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2vbpejyww.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gt2giwcyajj.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urqnthxn.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2pazocpzr.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2hkocagrh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2barkazvf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2erzkgjxi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2zymesfhi.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcgasmdr.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2kblbpckb.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gt2fzygauvd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2jqybidie.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rphtvevc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxhoojxs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2sdzeboof.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gt2prvktijm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gt2niblkwxc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkjntlej.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyzlegfk.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gt2oncxbjfc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gt2lcbtkljx.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcmbvhqw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gt2ymgslica.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gt2ejbxdmyv.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2ojehkjhs.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izelmqwj.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gt2vncnfrun.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gt2udvqhsaz.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyhmnfyc.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gt2qcjfuoyq.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gt2fgjiuncz.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gt2mabnbocs.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gt2htkxvuiy.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gt2yzuiqpsn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gt2bhstqklv.html


<!-- 参考信息 -->