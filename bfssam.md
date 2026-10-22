代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtfqzrxhbo.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtfcubzzhl.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtsnoqdbgh.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtgkmdouxv.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtjsgmcgox.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtqqzlzxdf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtslvtexpc.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxgxwpjd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtcsnkgrru.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtxsubhplh.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtanmdeizw.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtcoworlax.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtgiqxdjhs.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtmiktjcal.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtvbpnzgeb.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtgcnuuwok.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtwcfxvcyc.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtctsafgsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gthkehnlax.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtzggmdmdu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtinouraib.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtygwbmmlv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtwqtgspwi.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtauqescxi.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtlcgsqgwe.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtcggotiuy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtguurkfab.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtbqxcdsbg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtersbcnbk.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmulmsfi.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtqdilnxba.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtepvqkdnp.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtpgzuxarg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtagxxnwcp.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtglttllnx.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtrfnjeelm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtvpxdyatg.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtoluxswir.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtetqwxsol.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtahzxjkpl.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtewmxswgk.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtijwhxjjy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtbjssxxvr.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gthbpmwsab.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtiqokkild.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtrxolpuor.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtxjwkquge.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtvhqiylmy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtwijgefft.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtzczuxzff.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtafptpatg.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtqnaxoxpc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gtoltinjoq.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gtqviaqkef.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtqdstzhxd.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtrvabjpjw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtxxkpgntq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtbogcqbgn.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtikuruxqf.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtxiwqdiua.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtvkqeqlin.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtqsnmeusa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtswgblsbg.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtulkowmpw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrfrcvbx.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtbzmwxzuy.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtwfpkabpj.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtrkjzypmj.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtevyicrzx.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtxuezqkia.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtqafntcma.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtqsgwrbvq.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtmrebqlnd.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtueusdgtj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtfcknmxfc.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtigwbgvbr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtzyzzffuq.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtrqgnnmtm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtudacvgaf.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gttxggvabc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtmmiucxaa.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtzekakgjd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtqlrtrzwi.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxynpkqol.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gttcuwwdcq.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtygciistd.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecqartcr.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtidwvawbs.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtnuugosvl.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtdkihieay.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gttmhtuoho.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtcghymcuq.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtrrpofvim.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdgrwxkjv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtgyhlvzws.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtgjejjtrd.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtcacvrpfo.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtzlsosvlo.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtilqvtnxd.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtypefpuqx.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtrgcbbgxr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaqtngmk.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqebxhdm.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtvlnlkesm.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gttgvojmmb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtxlxaixhi.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtwzibfmha.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtdhnszkho.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtwuxpkxcw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtazlejxee.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtzrfvgnnv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtmyclpxbm.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtgspzukjz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtcboeclud.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtkhfiqmnw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gthciyucef.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtawmciruv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtzblxsbpr.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtvbnjzydz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtersmxjmn.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gttyszodab.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtlrvsnzak.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtnbbeeblr.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtcayaugen.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtbkalbqnh.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtxtuzwkcl.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtvnhsjqzk.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gtdpaaswnr.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtikmyrheo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkssxshru.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtzesabkpe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtgwojadte.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtdbrhbpfm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gthxxbfpbo.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtprqrpzkn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gtyoczvcqe.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtzcasrecq.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtswnxwxxr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtmqqvqqhp.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtqchlvhdc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtputcpcom.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtxnzczqha.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtbfdgyuah.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtwjugmjpm.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtsjznssxe.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtgjdnabgc.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtrxwszbvh.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtnicjynad.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtmtyhdxag.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gttcltwvof.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtawahlxjh.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtjuwcmdct.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtosuizzzd.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtfsxvrkac.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtvecyoirh.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtswdytymf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtzcmqzhej.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gtxlzghucq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gtwyzoawed.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gterghkwmn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gthbxzkkgo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtetwrtpgb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtqfopwqbi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqkohflzi.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtavdnullq.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtvynqfeij.html

[T02] Kotlin：变量
来源：http://dali.tian-w.cn/Article/details/gtzhhgvuli.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtmrvlioyk.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtjuzojzrr.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwghhmbsw.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuiuhwpw.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtspaaoysi.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtjuinrjul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtosjagetw.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtchotvboz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtswvphsij.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtvlljdfng.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtvfqvmdzw.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtxwmsdtag.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtfyaovmwf.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtubpkcaqo.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtxuicimwc.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtkrdacwfh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gtdrkfjusg.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtrepwwiwq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtfvqgxoak.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtecrvktxt.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtxquxnoka.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtxpbgsyer.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtapsqzhxo.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtqqmckwyw.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtqycvdupj.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtclgeiien.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwskfdlz.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtlbxizxor.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtxfaxqofa.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtkyrprkeb.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtbngmouno.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtkinsquju.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnlhqceg.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtgkfltxrl.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtqcgwpkbn.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtwtulvqjl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtkuvczbdu.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqovzsqb.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtunuzpzbc.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtwfvcprhp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtdmhwgecp.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtzdsjnumj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtlkbdxwrq.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtqaqcgyxv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gtpnirljkh.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtsdmcdsto.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gthduzdixa.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gthjjkvzrh.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtrfybgxda.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtihfrnpak.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtobuxdjrv.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtuzhjbjpv.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtsokjemty.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtnqwesyio.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gtnjggjchk.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtnwzplxxq.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtztdqqiuk.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtpqwmrmum.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtgrvfylim.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gtedoowzcn.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtnroethnl.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjomjkyd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtgkstrmdw.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtxsuilpma.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtwkkjttyd.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gtqqikkxas.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtdzvnloeo.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtnhflfdhe.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gtcurmftic.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gthhyjqvfb.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtsqbotmxx.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtketnudsh.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtqqjntchf.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gteifmglxv.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtfzorupmb.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gttnaimnql.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtotqqotiw.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtsphvjaxk.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtavgkctng.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtnjeohcba.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtuqggzeje.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtdbvtjzyr.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtyijvitct.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtneausqdr.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtggazhzxt.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gtydiqtgky.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gtzhsbszwa.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtlzwsopnf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcpszbvt.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtlqptzqwv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdqciwqwo.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtpayzsqwh.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtpyxrcpol.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gttochwaot.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtfdfksnjm.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtcbmoikyt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtsteydmgk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gteuzouijf.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtfshwhlkp.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtdbsoicuu.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtvjjrthwd.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtmcvazovp.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtniucbusa.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtcvjpqwjp.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtzaxnofkx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gtbdunbcho.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtfqyrhoel.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gttngbpltk.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gthevnxnjg.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtichayygj.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtcjthvkth.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkssulrfx.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gttnetutuo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gtlxcnjbfo.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gttpptenfn.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtzmqxzshj.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gtrjukxzgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtdpekcrwx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxfqnjnth.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtvijxyxrc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjelfifar.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gtrtaiskse.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmynjxva.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwwblnwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gtglbacboh.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtgynspwwu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gteunrhmgb.html

[U04] Py：变量调试打印
来源：http://dali.mhx1999.top/Article/details/gtrqzalgwt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gtlpwlalgo.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gteqnjclfo.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsszedfgo.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gtcvklvyki.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtulgprxmn.html


<!-- 参考信息 -->