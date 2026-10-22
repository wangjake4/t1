代发 wailian999

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtdtyatofp.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtvgxbceqj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtibhhnobk.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtophvkkbw.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtileexosz.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtpzdrqecx.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gtvkefzpjj.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtqnvjummf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtajuzqmas.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtpzkndmru.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gthawhywjk.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtomxytnoo.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjyzgjfu.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtolvehrjn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtgsdnngjp.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtzmngxqmb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtzsfwicqr.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gtenlgwgvc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtfvuxjlmy.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtxgzdpqzq.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtznopuksz.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtddhsfvur.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtskhhlicb.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtwivliccl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtnncpiqpq.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gthyjijwao.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtqvwpvjpj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpuayszpa.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtogyqundv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthltnxhxa.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtsacibgzd.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtxanyigwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtsykqcejl.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtonnbioca.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtonteimgp.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtpdqmsoeh.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtfedqcnfp.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtiwgfixgd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtvnmgmyba.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtqswmghcy.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtbhsxnqia.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtsfivikbw.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtnucqgaer.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtnzywdumz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtwrxxqfgb.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtgnwirxsg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtcydrinko.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gtbaggybqu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtlylvkeoe.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtxqnzjocm.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtbpabirzi.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtztdtdaqm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtngzykthp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtlgqrwzcj.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtzravvxsj.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtvxtatdzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtvddfmjqw.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtorcfimpo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtlpedfmsu.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtsrdkhyzs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtchubcuul.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtgujirkxj.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtomfbmxms.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtignbecao.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtcteegvgr.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtenmikndc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtowdaukor.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtezgxnavj.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtznycvpbx.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gtmlpnnpgz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtlgkturjk.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtcngfgerw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtcmwkwomw.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtstnlluhu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjypgyimj.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtrelptlji.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtaomvyykf.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtnnfdabkn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtuowvfpqz.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtrhmhglim.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtzumabxlg.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtnvkasxmh.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtlyjnfroz.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtoyixxsya.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtnqlcjzee.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtwivgkajp.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtuioteagj.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtaqrchqcc.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtmojecimf.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtrvidmgxc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtiducbxro.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gthbhjauud.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtvzulzkrs.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtiozgoqwu.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtzbgxrlbb.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtmcrfjshz.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtmddbfcxh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtxmrgdexm.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtctszpcvl.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtjdffkfpg.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtztysavks.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtvcmxuele.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtjjyjjsga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtqjkdfbyg.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtomarbxjs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtgnhzfbbk.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtpcwodnpb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtwtxcavyf.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtvtpkmsoz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtpmedbifg.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtwtvvfcim.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gttdfytega.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtcwzwxzry.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtnqmzursq.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtnlejqlni.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtgxzehkbf.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtsizpxbfc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gteaprmnuj.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxguxtbbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtxyyvqqzc.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtalknpbdm.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtmlkiwlej.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtqnqitgpn.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtufsthono.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtraxfgtjy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtwivteuye.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtngxhurvw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gttuvbhkvi.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtuayuazos.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gtegzolcfs.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtauyuwnxr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtyooujstc.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtphcjozre.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtasxmqjiq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtghaqpzbd.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtjslahiny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtdbkrxdgo.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtlmmrdydq.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtwkseefkl.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtwsotffpx.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtzelnosnq.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gthqimnkde.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtvkigyhjk.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtotblnbmd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gttopqgbwj.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtdnhijynl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtfshjtmwi.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtxhjdnlry.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtbmwiaetj.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtkfxkntnc.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtogiziwrq.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtfdokfdlc.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtkmnghvjb.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtnsubszxq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtlngkfqek.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtqcahsdfx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtcemhxzmr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxtvsmkv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtyuddsjhi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxdizwlou.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtuukoryta.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtmrwhqcsm.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtcjijdxmo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gthfdxxrbk.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtjxoinrjl.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtzzlkhryt.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtvywfibvp.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtjnhxlopp.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gthapibrzq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtlxnzastr.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtkkkmdqru.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtbufsyttv.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtszrjjutj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtdtfshiiv.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtdhsfhhjp.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtetsbyvsq.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtibxzkbpf.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtfcoenwxb.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrrmezvq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtnbgskirj.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtfbvgxuvw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtgpujfjof.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtvsavwtxz.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtrdurtgrl.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtcgfuoorb.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtblycvjlk.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtzsdjgdfc.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtjdbadiiv.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtvipmybng.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtmcnnjrlx.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtcugttojl.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtienmbkdr.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpdkurlc.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gteziwokjr.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtpdeojgnz.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtlsyvqgsl.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtrlnhdcqe.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtidahytfh.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gtrvrhsmap.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gtrjcuxxzz.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtwtjecpri.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtakzqybus.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhhepdgc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gtitdjabnp.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtchpmjqiu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gtutsilate.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtklysmeuj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtuafefczc.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtavetyrpz.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtbmucvxmz.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtujyrdpmw.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtbebqvrrb.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtneedthvi.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtqptwtgwl.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtsxxtdggv.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtpbnwvnwo.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtnydfgbcb.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtxjezepuf.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbqecegn.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtxfmvxlrq.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gtqvqggixt.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfmacelt.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtypfzxfzt.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtoivyxmne.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtgkmwqtyw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtvialfjkq.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtqrfqifyi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gtndryhlly.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtcxwfinvo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtkjhwygzm.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gtprbxkvjo.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtqzwnouyu.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtjrrocxgi.html

"a" .. "b"
来源：http://dali.ydzc1.top/Article/details/gtfupadamb.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtempugsrt.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtxwzjnmap.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gthqrbyifi.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gttliyyivg.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtrcqgxzsc.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtzhpxfgtg.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gttgikkkfy.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gtayyvepqr.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gtxwnsoskg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtjcldknhl.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtsoxjqypd.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtcbfouhja.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtnxkfdaac.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtjlnnqcfp.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtidqavcyu.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtskzjalyc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtfsjkhewc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtvsjrxzqg.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtcdpgjkmn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtimaoctxv.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtgzaiieai.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtiezopyeg.html

[T49] Perl：函数
来源：http://dali.zhoulong.xyz/Article/details/gtixkuwqqe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpjlsjujk.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtqvgvigih.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtepfaggfr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtztwbvbzm.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtipxptjee.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtbswxiyjv.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtocpdgfav.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtotunsgzg.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gteuatcbmq.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtncumneoq.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtiuvekbuj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtbdcmhnhz.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtyzsitznr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtxupqerxf.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gtkiiftwsq.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtbrkmjlgp.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtwsczvzkq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtwvniogzg.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gthbupdzxq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gtwwkufxle.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtamkcwaeg.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtpvqrsnkk.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtjrjyirtb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtwnptnusf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkidbldkt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtxfqbicyq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtyewdmrth.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtrcgvawcy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gtffotmlpp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtwuaaxatl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtnjtsxkln.html

[U03] Py：加载 .env 配置
来源：http://dali.nwbrower.top/Article/details/gtnzozcyth.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gtuiefdcgx.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtuuaddykn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gtqeuabemm.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtqknhuvdw.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtmpsegthr.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtnitttvww.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gtoqyaqyth.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtfibskqpt.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtmkdcqacq.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtpdzjqnwv.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gtbbvrillv.html


<!-- 参考信息 -->