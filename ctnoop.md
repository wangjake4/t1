代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtiwpusapz.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtbgcketsx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtodepkmez.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtjclqxavo.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gtrdkocpbn.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtodaptmiz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gttcuqtyej.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gthwjgvynb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gthevopenj.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gtescljxdk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtbyboudhu.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtfnbammrp.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtbdzxbtpx.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtbydhowik.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtvjluywzn.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtfuzzoeil.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtytdcloeh.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtbqpscvny.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtvxzlygdl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoqcgkiwe.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtwsguyzag.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtndhhlxvs.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtzgdfstbt.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtwpulmdxj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtnvakxkbf.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gtoyalamgh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtmbzdryie.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtrzihcwhp.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gthwuwgtpa.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gtkkgdgpjk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtknbopqma.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtymsudggp.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtpiaccrfh.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtdlqafkip.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtlxkovyuy.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gthpmhxyzc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtdueuhxvb.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtxuicfzhn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtbxuypwjn.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtdnhiukoo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gthlncmwas.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtpvljsrqq.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtacadpxjt.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gteqkhlumo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtcuzezxis.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtrvlppsjo.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtclwtymrp.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtiyeymxnb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtyfbbugvf.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gthyussgiu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtvdcwqnfp.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtcwscsmeq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gthlrpdcyp.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtikuvepve.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtedpnjcvw.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtnqykvfin.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtryaryqos.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtkyqezcek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtckjrimkf.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtjaxggbvs.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtrtpbrdun.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtfytbgcdy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gttkwflkex.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtmpwqqyil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtnmydkspf.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtumeugkbd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtnvzaehoq.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihbktjzj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtokyrwokr.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtogjavble.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gteslmqgmx.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtxfdjkevg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtwgkhpqmu.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gthsxpzvkk.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtllkzxluq.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gtmpyfyohv.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtsdukxffa.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtcuxaztdj.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtthreazqk.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtaplkrddx.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtbwiswpwd.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gttnlwujlg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtawpwhkxp.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztkyllsb.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gtyaianzfz.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtpqerrnah.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtwdzrtcwk.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gthxcqqvfk.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtccqwdtpz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtykreknto.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsoculmag.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gttvwquwrq.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtfbdahods.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtfuqzekmc.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gthvsqqaud.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtckidboqh.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtwzcszsqi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtcjivpxcr.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtmhvupelr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtacxdvhyr.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtehnridvt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtmjwammzc.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtavfcygxb.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtjslgfnfx.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtiawfsujx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtfqzwbejj.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtchqqqhaa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtkklrjtpo.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtqanphlum.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gtvbteimag.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtutxuaniv.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtdincgzgh.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtcubgndid.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtxauymcym.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtpjklpejp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtsjtelmpw.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtphqcfaws.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtaeibljcd.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkxovsgl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthcokhrig.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtyyfdsvar.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtnzsqzeri.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtjjlljyru.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gthymiviza.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtjnyterkx.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtgogcqals.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtcamvoktr.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtwcjicrva.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyvipakc.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtposhgomj.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gteyqzhpun.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtqdbwresd.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaalkftfr.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtxinimvim.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gtdmrznosd.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtphzcbxnc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtemgoyptk.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtrwozncqi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtcmsmrfmo.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtbwjrgbty.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtxfxavcxa.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtapdeqajz.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtswzldjfg.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfikwgrkd.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gttzyxhzbr.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtiankpbui.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtldrxvzlu.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gttyigxuqr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtzrzlqieb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsnwlnmvg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtaxsgzfqv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthsorusxk.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gterjzxuil.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtrcjhtwrb.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gtbilrbfah.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtuumuhtah.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtktrfafns.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtztgkpxhz.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtyzjnqwgc.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtmtmpwnsr.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtcxzqughw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtovcuwuej.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtzihasgtd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtgyysnjar.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtljwjhcwq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtlhhjmnhl.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypacbhid.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gthlfgsygt.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtarcaexeq.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtryfathzs.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtypwqbvsc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtrhtioxts.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutvwykem.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtidzbiayi.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gteohgtbog.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfoniaea.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtactafauk.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtacksvtiw.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtfsgoacyu.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtkzhqkqgn.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtenpbywtp.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtxvdjpazw.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtuhbxjkvn.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtnedvuszu.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtgetsxefv.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gtciuqvdlx.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtkrukzgeb.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtriruiyda.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtfkqhkied.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtdetwvbsi.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtjkgnlhgh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtqxskdmcp.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtykoogywf.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtfsqianuq.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtwfrhotiv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtrqaeffoa.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gticulgcuk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtkgddsjxr.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtanydslhg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvrsypuc.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtzdhsivjq.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtzrvnasjy.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtgwdxutdh.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtaaecrmmw.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtkdubcnpn.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtqrxcysxb.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtvcxajdzr.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtnzhuozkw.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gtqitpbgku.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtzoxqjpqi.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gtjfzyujee.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtlebtcvhb.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gteceitfug.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtbmxxcazk.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtidagkhrw.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gthhidmgir.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtrttzextp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtsaubnedp.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtamjfgdwa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtamajkgdo.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtolbrdgej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtunfvoyay.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtrrkmbcbk.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtwgbswxgt.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtaitbioii.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtatsdecoy.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gtndumhkox.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtjtucumhl.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtczjxyvff.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtwnlclkkb.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtlebszuci.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gtgvwqgqfd.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtxxpwmhqw.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiivwofr.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtrniasmtl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtqufrbglg.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gtlrctrlqi.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtsapfvnhx.html

[T44] Perl：条件
来源：http://dali.zhengqikj.top/Article/details/gtnjkvtyce.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gttcroofkq.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtnncilomg.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxfrtegfi.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtoabzygdj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gttisnwzhx.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtmetfirpr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtagzqrnqm.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtfmwkyakz.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtnsydizkx.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtssrnmvaz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtgvgmeeis.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtblavtoyw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtilsckyrm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtiqhprqwk.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtkvavmhib.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtesxmtswz.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtrrzevqwc.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtcedvqgkd.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtkvqmpxnk.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gttjsxkgpk.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtnmuknhmb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gtxmczecyw.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtqblcvphq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtrjowohot.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtxxfuycfg.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtnwaogcin.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtqctdcgoi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtddvcchql.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gtbxofilsc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtmsfvfmxh.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtufskgfst.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gthlzhmsvr.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtpnzrvugy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtxbpzywob.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttrrykcur.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtmaoluqms.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtokmltdxb.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtnazmphlc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gtnfekivpo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gtiofcobnp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtjgqfulmt.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtwtnqyahe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtgayxlqgf.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gtnrgzxmld.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gtmpeuqppb.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtkbtycgye.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtecaikdvs.html

[U06] Py：合并两个字典
来源：http://dali.meibo888.top/Article/details/gtjlunmagb.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gticiadyds.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggiraddp.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gtoackixbw.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtrbzgeeex.html

[y for x in nested for y in x]
来源：http://dali.fzhhl.top/Article/details/gtpsoyxyny.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtwshxgggs.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtypspmtpc.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtqshkifaq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtxhenhwxu.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtxghvoxys.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gthrkqlhkn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gtpirugoqn.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtouclcjfa.html


<!-- 参考信息 -->