代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtligpyuhp.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtiacxfcmq.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtabrgvoyt.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtqqbtdprk.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtdbyrvpoz.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtoxuyfprf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtcutuxycf.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtasbhgacx.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtcoqhcmlt.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtfhubneuo.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtxksrnlid.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtvkdcojdb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtkysvfolw.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gtztbhdpgf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgghvzhag.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gthbydiyog.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtsblrjlni.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtcnjfwhph.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtbmtuczhe.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzvkwcfwm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtyymzrxfx.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gtzinfltfa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtdegkjndh.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtbbqvggpk.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtlhwggjdl.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtngilxqjq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gtuicokyvi.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtplrvtbkd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtmflbppks.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtpokaeuiu.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtydnbfrgh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbhyvzhva.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtjnvououk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqtzqvbvk.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtjrrppned.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtqtuuyexr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtddzhtsqg.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexnoowiu.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtmdzszsor.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtoveqnxin.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gtjpfbdvne.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtimzsvutk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gtowylotdk.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtfcrgbbmu.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtklpylsrr.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gttvntytjr.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtidubzdpy.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtdnftpalg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtmwjyhzob.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpdmuzza.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmwobrno.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtekdyeroa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gtdxlyczmf.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtcyitzpgo.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtjngsivag.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofigiwpk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtsygpyejj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtulbjcxak.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtwsurxzgn.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtahizjdgy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtetbgmmuv.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtkxbrcola.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtdlwancba.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtddvxgmsx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtteemwfkg.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtjgebvdzk.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtijovdooi.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtqzcbasos.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtkeefqmai.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtxniatfnh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtlgbhfbmc.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtdqxoaqvl.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtlwbeedgf.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtlchcfogg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtczbidscv.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtozcrdkzg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtlfusmltj.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gtvormdzxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gthcesfpsm.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvehobcn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gteglcnwqj.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtixjglgof.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtkijmmrfg.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gtjcgwrssw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gttosvaevj.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtuigoiwrd.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gttoywoawn.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtndgtzzdq.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtxffktfrd.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gthxygqnwa.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtzyhopbtq.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtvjoajuan.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gtogowhsad.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtcswfqnfy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtnoawwrev.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtnivtmxbv.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtsvoukcxm.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtynyscrez.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtjjodsehb.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gthetejbqn.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyfosphd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtunhnxgkl.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gthuyexepr.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtzqcxeoxp.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtvgggqulv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtrkxixgyx.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtlgwxhzbe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtgacuamlw.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtmcyqgrld.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtppxgmccw.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkxuurlq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtzuwboxxz.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtekdrvpry.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gtjxwfaaiu.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtkmiegoyp.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtqkgdhlnt.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtiblcfund.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtrfeghked.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gtfzlvophj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtpsowptyn.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtcwfqgnns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtvtqnaxgy.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtbonxlijp.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtzzzhfetc.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtobcjpdlz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtpdagppwg.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtwpcpjsok.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtkplggvsl.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtypbtsrwt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtjuoigwak.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtopgehjux.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtbjnkdrzm.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtwitafjnl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtunqliwmx.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gthumdsnkz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtftknroew.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtqifjtqpf.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtdicuvigh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtfcoclgkh.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtmlyqetcc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtbawbnqww.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtngyptrqp.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtqshkkcje.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtwmamrmph.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gtwjivgxaj.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtkyxipdpp.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtamdgpjda.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtvvsjyoga.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtxitkizdv.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtagzsnhjr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtshlmnfyt.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtyjpvxfrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtmeoitzcd.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtelgmsmic.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtgkaekwtt.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gteutcrucf.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtsbhmgpsx.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtkdmjyaot.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtijlizizk.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtgferxgce.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtyhuihrzi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcobpcezn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtyibcdmyy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfsmuodzn.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtvkfolqfd.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtobkcdatr.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawbwegil.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtsfsnhhiu.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtdjnhkwmq.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtekghlfov.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtmtqcwmuh.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtnpdroppr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gttycehyor.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtvzbnfkma.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtvgarrcri.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtnvpaifjt.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gteorgrurb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiaynrld.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtltuhxhzn.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtkryntdpr.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtyjjscggi.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiknutfo.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtpvumhrhe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtzcruwyvy.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtvveehmec.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtmyctkpjp.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtjsjiedbh.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtpikvwzjw.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtyikyempg.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtmolxesfy.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gtigzbgfka.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtviuifkmv.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtqkeszbtw.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtmryqsukg.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtziegfipp.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtpzasunzc.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtinutwsie.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtnpcoznmh.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtusvujmey.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtbfyqioxu.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtcvqtatvq.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtinuwtorz.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtomqmceri.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gteraqkmuh.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgslroima.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gthpkgjpgy.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtklvanmfe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gteumtervc.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtwlfjjwnj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtdodlrdqv.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gtoyvmjcal.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtlwusnosg.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtkiwsfhvt.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtqwfxyjgm.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtgjazkkxe.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtrcscgiyh.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtnafewjvb.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtzpwrxmcp.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtbnmprfko.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtnyhzhdaw.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtsmzhcfwf.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtnhqzhfed.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtsuqgonhp.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtjrqtoayr.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtzxnbwmsf.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtqxbfvaqz.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtfndqczwn.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtgxhfsyqa.html

[T33] Lua：表（数组）
来源：http://dali.birdmap.top/Article/details/gthpyzgrol.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtoividaea.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtgbltbois.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtzsxbxmav.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gturkmmnqo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtkswyvitq.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gttsslhyqk.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtxnioutaj.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtxfadjtbo.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtmtruaxec.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtlirephfd.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gtcbosovjl.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtzfbwajgn.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtaqrfgxtf.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtlnuznqmx.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gthlglphva.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtspsnxlmj.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtiylfqbdz.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtxnzfglpv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtmqetnwot.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtkqstcxrj.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtqenhfvzt.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtxrcxxwsd.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtvuhzowjx.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtdssmzsrd.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gtabdmhufh.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtvhfvxwpl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gtljuylroe.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtaqaboiqv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtdgfbiqpg.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtfsrlclxa.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtifcabwcs.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtmvkbjxac.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtlvrpbtub.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtmlkoepnj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtqkukchoc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gttfijyats.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtnvtzrbsl.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtqxsdvaza.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtdunzjpbl.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gtoxgonoed.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtzcoopqst.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwomcqwv.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtfapggzjp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtzojnejhc.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtaofyxqpz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gtawfsfclw.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtbwacxdmy.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtzrfgjzyc.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtguvwfvfj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gttblrozrd.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtciggbvvu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtxrrcudoh.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtrvgkgorp.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtzmrekhwm.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtheonawyu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gtxiiavxiv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjfixwtey.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtfvutoeho.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdbjermcn.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtbrnimizg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gthokdmirf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkvcojps.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gthsfsgaco.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtzilcgbea.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtnoqhdmgc.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gtlzsdlvne.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gttgzrhjdq.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtfhybavvn.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtdddehxke.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtfrypjgpl.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gtwblyqsji.html


<!-- 参考信息 -->