代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtduoxoqzz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtggkudjgj.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtrrahysmq.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gtlsgwoulq.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtioicgqnu.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtehowcgsn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtmdtxxdkq.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxthggln.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gttchzfirn.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtbovpybib.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gtagxtftbj.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtexvdhipj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtjxgriyct.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtlkpoufmj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtuvunoxjg.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtxhoyhown.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtbkpiukme.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtcmyowptp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtjuarvnwx.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtdrcqcjnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtzjtncgbn.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtfdkwfxfm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtoqbkafxl.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtnvuqsvxc.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtpjwtomjl.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtnbyoxujr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvwzzwlv.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtrjxypref.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtkrqpjqne.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmguoqcw.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtpwytljlv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkvjvkbiv.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gthuowtgsr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtoizzhzvp.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtdranubzh.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtxmutaqkz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtfdrstxiw.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtnphnlelj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtxrunvjlf.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtpdcsrdmy.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnrjwhuw.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoeylgma.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtrybwwoxv.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtfpjvvpxv.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjyynynnl.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtqutvqqsk.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtscvbefno.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtycnaokyl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtxarxrwxz.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtgggeurwo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtuhqfikuu.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gthewwrlby.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtaodmkcue.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtlpylggzn.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtbfevmsgy.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtpygddlen.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtxtdipfbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtqlihtpvc.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtfxozjwdv.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtunqhtfvw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtzbvukkfc.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtpecgyxys.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtitpetwjm.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtsyorpdtw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtaxtnijqx.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtzwxjrprr.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtujoflgrk.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtobxxxohk.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtfqwits.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtbybkxpto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtaanvaafw.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtkuujsyfd.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtdwrtabvc.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gttclwqlwe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtgzftozpq.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtmlxqiwsv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtvjjxasav.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpowhymo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtavqlmdcx.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtlcbbafwn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtwqgiixtc.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtjbrdsiet.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gttfwazbwf.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtwxtpfjhd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtxrxwpmkb.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtcaragaxu.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gthugeklhu.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtkzuxgqej.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtsjmbrdsl.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtdnptvzjz.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtakoourmq.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtoivgevzg.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gthnxabxhn.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmvjeezoc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtophyqhlr.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtxspwhqmy.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtnfiswago.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtkjtaghli.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtcweoeswn.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtpfqkvlgs.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gteiikslur.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtlrygkpkq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gthfmpmuni.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gthppyouin.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtrcmxnkfg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtnqamroks.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtnckklivb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gtfssgbhxj.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtnmhrzhfo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtglylilre.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtduprtkjj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtlrmnfwzu.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtpdiiioru.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtopvstkkf.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtxlyosiir.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtxljothjl.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtjrykzngt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtvstgalbm.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuorcnyk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gthrtgxatd.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtdrqlhtmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtnsjnwmfm.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtbdpnoona.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gttxipkuzk.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtqvxvrgkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtcitwkrec.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gttciktwol.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpnzjmiv.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtpesnxcnl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtndavukbb.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gtuijkefcd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyczynoy.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gttoeoezse.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtfytfqmhh.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtkucgfjds.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtkflwvogr.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcxcjggw.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmhrktxqc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtwtaynzdl.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtveraaxoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtesdxybig.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gthsaaxkby.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtwuhksceu.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtevzddntv.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtyxzeljgh.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtzxmbdaxs.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtnyvjedjm.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtljxxvosb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtfojdftvi.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuvgwgob.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthllqpiqs.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtywdlnnjy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gttxkrybwp.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtvsgiscsr.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtyehimuit.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtydackorh.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtwhdcczfd.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtywjvkraj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtuoeuotrq.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtdklhinpz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtcvtbemso.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcumnswnn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtbhauofqm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtehrcpelz.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtmfanskyn.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtgvajnvet.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gttwewmhiz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtmpebtndn.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtarwgyrwe.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtkhjokiux.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtvptbyzbr.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtleqexpwd.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gtvcdshetd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gteebgbnyy.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtxdiwawsa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtgvgojxev.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtjjmugssw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gtuvnqqolb.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtwbxvxcbf.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtzgxgrccz.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtsvvjjxym.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeaxeieg.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtnckqybjj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtxajkyikd.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtmqlrnehd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gtbpdigkpj.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtewdxftmm.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gtmgfttcyx.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtkrjvitpk.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtodeptbml.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtjgsnvugf.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtbofvjsny.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtjqwaidai.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtbivmhdbq.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghfjkyki.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtthvmpoet.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtcxxdiwdx.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtczwigbtu.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtucvaekdk.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtrbcjzitw.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtwcsglalo.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtypyrnpbz.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtuphlmjki.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gtbdixgpxf.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtbddydyqq.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtnyysxbrd.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtmvhejenw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtagcbfsrl.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gtpaqhfwsr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtwbzphsld.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtdnlmjeku.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtsapnybqv.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtzdioihvm.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtzwggfrbb.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gtzzxaltdy.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtgibiarme.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtgiuxsuap.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtwuljfeds.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrussxtgg.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gtslfrmyty.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gtonychidw.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtrowzqnjc.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtdylhxigf.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtykfyrcox.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gthdcganmu.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtiukzngec.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlimpmimi.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtycidnofd.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gtcyklqsmg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmbszmdo.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtrxlwtoyk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbnxczfs.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhemawnz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtdymufhwc.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtgeewcguj.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtbuvkibtm.html

[T37] Lua：字符串拼接
来源：http://dali.sweek.top/Article/details/gtvankpsnw.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gtunrpioay.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtqqrhcjch.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gtirpkvyfa.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtzzjpgxvm.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtsabxejqm.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gtfjlfaylg.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidsclrcz.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gtdjunjaix.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtdhckqdyb.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gtinqpsseo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fzhhl.top/Article/details/gtuseychty.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gteaipohfr.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gtheescyhy.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtweicinst.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcdhklsms.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtjgzzgkjf.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtrcpttjgu.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtycnorpoa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gtncphhexb.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtkhoqgkzq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxttlubvq.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtffwxqjji.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtbdziuefg.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtlcuvcodj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtteetbrro.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gthdwlggtt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtinhjcgwx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gtlmdbznao.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtbisskovo.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtcgbjdeit.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtqkmocuiq.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtfsxybzji.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtddjdxnra.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtdelltwiy.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtqxbmhwfv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtepprmjxr.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gttovhwpun.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtbpgmhufb.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gttyngjhzm.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gtpdgxpnok.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtcrgleuke.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtcqfhigxk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtldufkorf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gtyqpjlpin.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtnumgpzdl.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtqvdyefik.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtocbjvxrw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtempjgsip.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzueslqrk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtxowdvslo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkygimyyd.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtafjxazky.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gtiraawngr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtwttgrvgy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtbyscqlfi.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtmjmfwyrn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gttqatuodu.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejwqmnjv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtvfcljsgz.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtycbuxwib.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtwpgidkbh.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gthabdzjkc.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gtihpqbjnl.html


<!-- 参考信息 -->