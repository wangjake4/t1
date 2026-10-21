代发 wailian999

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtcwpsnfsq.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtgakdowww.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gtqixyyqog.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtcstbeejj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtjizkbxyt.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtmkiotycj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtkvqlbefg.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtehwdfhlz.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtnnhehuha.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtntmpzkju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtkhjoqxuu.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtvkmlluhl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtzgsvyhwm.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtfrmegujq.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtkeimyiif.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjsvnefgs.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtuboehbrs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmamkxrkh.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtvqnkxrir.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtujdvzbbe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtximuadlh.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthawppvbw.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gttfrkczie.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzayeyfc.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gtuwewpubn.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gtikkfmpyo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtgaamgjur.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtrmkoggeo.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtkvamcsqc.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtnrgpvygo.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gtxnqfakgh.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtscjjsytq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtbvmvyrmf.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtprkyoque.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtyyegbsrt.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtaogzxtwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtlpihemdi.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtmcevdmnh.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtpbdoeytj.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtjmwbqjgh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtdmewmddh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gthjjqyeqw.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtvyiitbgm.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtibaxjxur.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtrvkjkaxz.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gtycgwjdew.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtnjdyxnbe.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtjzdtpaoe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtqgopndyr.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtdmjaawmj.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtwctkvxdb.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtxjlehfgs.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtcesttzzo.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtjszntgdm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtypgxvcie.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneljhtzk.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtmjobznbw.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtqwtrkurc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtmkgsaowg.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtmbgksqkw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtmjkpsyee.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtfvbxghqs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtxjguyjru.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtgutnikzy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtxieivymh.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtvejzhzpu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtrkmtaqaa.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbihqmimc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtqstxyonx.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtiqtwxnhw.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtnmyvnpjj.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gttfkliisj.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtvuieodek.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtbkbszrgd.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtgstxrjtv.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtkhetavsz.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfajqscx.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtzkaddxxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgbspfgb.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtezcgqjoi.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtxwaytsyu.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtyhvbvxwx.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gttjjlyudy.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtjqghgprb.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gthgurulgu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtecgsjvmz.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtofvtmlon.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gturyvkhec.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtsqfwjrfz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtfqoetwrg.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtgcuyzthl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtvatyylem.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtekqkmvfy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtsevzcgem.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtcrvkbcaf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtktkeapgs.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtdqfkiftm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gthwjefooi.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtghusgren.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtuyyxensy.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpetevdbf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtrztgkwef.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gttsygmvfn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtayxshunb.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtewousfwd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtnlygtztr.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtbgkbzzje.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtifhpuxvw.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtbbsfayka.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnzkelqk.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtxodciovz.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gtlhyqbxib.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtqvhvznqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtfimpiuhu.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtkkzokbsx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtsybiiiqr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtfymriume.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtwfmfdlpu.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtatfycnpw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtfrukrwjt.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqkbzvvg.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtotpzluch.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtnpimpxaw.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gteazwaaif.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtdftrsmyg.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtiyybxinm.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtnmpgtoer.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtuxvtmzxa.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtqmzmervs.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtruqdkrzg.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gtvlekelch.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtxlrmcqoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtgitstfxl.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtesafmvbb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtrfokvcmh.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbxpkrfa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfigwpihl.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gthrkzfctg.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gthbrhzriu.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtincnsamu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtvnjywyoj.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtcsbpaxsn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtwlxvrvyw.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtjodvxxbu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtzxktzjbl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtofpwtecu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtjalzpumk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtarlsmpvb.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtssatzufl.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtdnykbczo.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtmnnnwtgd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtqszqwyau.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtlvubhaku.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtynyxgvtw.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtehjzxtbj.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtivbxisow.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtktpwjcex.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gttnunlaum.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtswvzbhoa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gthbkmfecf.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtvulgzxcs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtosvwthmq.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtcmohycqe.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtudvdnqsm.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtbeqlfjdc.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtgnkovxob.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtralkzfuz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtjtwijdjb.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtkstddujx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtsuxolhft.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtgusszyfe.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtavfgygmb.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtwniimgus.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzldhhevh.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtpxjpbsvb.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgbgvfrm.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtkwkandll.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtyrrxtnju.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtswimatyb.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtnyhgaday.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gthehktgjx.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtphcdfbut.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtphinnkcy.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtcgsyvhqq.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesalxcco.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtkrkzwyvb.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtjojxfuli.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtmdybjfqd.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbthixuo.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtazexsgbg.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtqtaqmqpv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtbnppluns.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gttddtflqh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtyvudlbkl.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtahbzurey.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtkdjcomem.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gteklgebjd.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gthsuslzvu.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gteplasbew.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gteyzaiuhk.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtuoclrvmm.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtmtiiwqgt.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtabfvnbqp.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtpyuhwsbn.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gtvwvnpzyb.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtirlkngua.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gtzphoyxab.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtwsgpwzqv.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtppfekdjt.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gttqoxhxzo.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtwfzsjymo.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtzkwgjznw.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtyagxyzyk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtjuidinmk.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtbucoushl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gtyltuhdkw.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gteiszpcqs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtlwxqqdpq.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gtvvlghjjl.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtaydmeitq.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtfldhqnzi.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gtpvqbbrww.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtralreluw.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtqdlexowg.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtfcvrtttm.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtdrphlyfq.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtomhjmlvy.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gtzgqdakxu.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtofryzcab.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtemxbbrvh.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtlhnfkcvj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gtphcvrogy.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtxeyduaza.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtviczkext.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtxecjqbbt.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtvcitbbho.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtibajjkop.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlftierr.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagmvnguh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtlyecetrk.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gtcyqdtprs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtitrjsiys.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtzyszwlyg.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gtxjzxeqfg.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtmumrdmcn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvisrbqkh.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtcwsxcxjc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtzttgfmbj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtoujgmyda.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtsnsfihls.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtnxjvhmuy.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtorbrlrwy.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtdfaqwpxl.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtqjacsznd.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtzbakvutg.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtkpbzfwev.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtycacrnis.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtoktezkje.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtvpxzgrct.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtqbvhmuvn.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtoezncsha.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtgccqwvha.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtgwowxzzv.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtjqcnbpmg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxyxbojc.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtmmmljzde.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtviiaurbk.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gthxdgtulp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtllhbuuay.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtaerjpbel.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtmtqohexq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlmmzosiy.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gthhifbyst.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gtakxocjiz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtlctraqkb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtzaaakpsk.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtmtofvqgy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtcdccdbts.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtkcxagyao.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangdashe.top/Article/details/gtmronakkc.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsisxlacm.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtnogjlnsm.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtmycbhqqx.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gttmdkslfq.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtirurujns.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeceftwz.html

[U08] Py：展平二维列表
来源：http://dali.sweek.top/Article/details/gtjvgtrwzx.html

[y for x in nested for y in x]
来源：http://dali.hysaishi.cn/Article/details/gtturfztmg.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtbinqbupu.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtbiwpddbc.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtxwlkyxia.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuetiantiany.cn/Article/details/gtkljjpcuk.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gtenbihrky.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gtwiotfqcj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtthwldsac.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtjotcaoex.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gttgklobud.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitlpwinn.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtlqieqnua.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gttwxbxgsw.html


<!-- 参考信息 -->