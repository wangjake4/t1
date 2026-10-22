代发 wailian999

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gt2zsraqgmy.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gt2ndtaqywo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gt2zhjxkycy.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2ienjhhnr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqoetdnb.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2ajlrunhl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2dpiipgbg.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2solfblab.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2bxgszrpe.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gt2ssfmkuia.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdmairdn.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvassblt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gt2kjaheddj.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gt2onrelesd.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gt2nznvqefc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyplxrvg.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2mepaobkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2sqojgpyb.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2huontonk.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gt2tvighsgq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gt2xrcezrjz.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyiigtfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gt2yujkfkin.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsrjreon.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gt2mlfimwvi.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gt2otzczskq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gt2elxbtlwe.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2ujpvfzvl.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tamodsrr.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2cydeflur.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2esdwfbmo.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gt2cdpxjejj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gt2oojxwcny.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gt2wwiwveij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2ybhaoimb.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2gxmurpzh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gt2vjihkxdx.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gt2oqxxsxar.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2hdpiouza.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2jlmcgbod.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnolyhta.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2rvxrzlrd.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2nqldparu.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrotekiy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2rhjrkfik.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2iovtzone.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2obbhqttl.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gt2nayorjsw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gt2kpxbzugt.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2zrulmbjs.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2byoeujlv.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gt2emweycsk.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gt2boedrfmx.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2eykucbog.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2xrxocuik.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2ujchlokn.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gt2vcoplcqn.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2kmofnvtx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2izkubhpu.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gt2dibcvdqa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2giaaulho.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmaiwsir.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2tmttytkk.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulwmmswe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2bwtnllhk.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzlgvnrt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2bdssgrpn.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2egkpcsra.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2zciaslue.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2xktywptn.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gt2ntpiqfan.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gt2unetrlxo.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gt2vpqbvvus.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2wmasapmv.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2lcnrwhzl.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gt2hbdecgzh.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2qildwovm.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2iuvlbpzu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gt2uqubpyhl.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gt2ooaonxmr.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2lbdjscpk.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2ejovcqig.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2rbkzzpck.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2fouhdxsj.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gt2hqwqiere.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tqhzbpcm.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2hfojilqk.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2vahagtkh.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2mhivoodx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gt2mfzzeqih.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gt2lvqbqxwz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gt2zdzwxxiq.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2hmvxkyzp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2iexmtyhq.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hldbjkvj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2geekklpg.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gt2vtoqxzpz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2faygvmus.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2ndjofymr.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2vaksejgi.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gt2bkwhsexz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gt2tbjzabqd.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2wrtlqirx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ddpbfarh.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2eiaujqyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gt2vddiotfb.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2lnowmlta.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udehiuci.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gt2nhxquhix.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gt2clpwxsyn.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gt2tlfrwbqh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvnswxl.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gt2iwqiuyfl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gt2izcahblq.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gt2xqrdvvei.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gt2bfowbouo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2rzwiober.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2yyzpkorp.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ifslxipa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gt2zbyprkht.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2syuorovt.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gt2zdhvuexe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gt2fgnudbbb.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gt2njqntfra.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2ulsvzpia.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2htybsren.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbladkjx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gt2ohxwherc.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gt2rovhedac.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gt2ucpcawvj.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2zapkykyk.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2kmultybn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gt2sofpmynm.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2midvfaxu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkmajzio.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gt2sxrkuzoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2moucvrge.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gt2zhwvhebq.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2dhblxuch.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2azkwthhn.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2puubgbbr.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2zoilckog.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gt2cjtverkv.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gt2yjozounw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gt2bazngojx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ealhbvrk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gt2fsfelsle.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sizaydbk.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2qtlqfvnc.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2vtedgesl.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2ygwomddj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gt2enllyehf.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2johxaxgz.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2ycerqlqv.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gt2gqfhghxy.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjuztxdc.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gt2ctbzrshy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gt2qxcmxlot.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2hzwgvcku.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2zhnsjeco.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2ubywuejn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2pryyjzwt.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2jumnsmit.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2gdyhepqt.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gt2nddgpwnt.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2zhxqchzg.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpkrxanf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zddmmfim.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gt2mehytfrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2tmntbmbn.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gt2dfzmjecx.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2ylvadwvv.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gt2tygorcem.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2bosptraw.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2xuqwqgui.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2ofuugguw.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gt2queeqmsb.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytwztvbz.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2njgobpgr.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2nsklviiy.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gt2edaunwxh.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gt2nyrwfpdp.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2tdbzgvwm.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gt2tqtevnox.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2gpkwnrlu.html

if let n = opt { print(n) }
来源：http://dali.chenlongwang.top/Article/details/gt2rzbczbow.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2mmkjvoxi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2wosoepzu.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2rhcylefp.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gt2khrywuvh.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gt2svfbanue.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2bumdjxsr.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gt2othphmya.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2pefbngmw.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gt2cbqdxska.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2rpsofhdc.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2gqwzyflp.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gt2kiopaflf.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2etcveler.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2sugratyh.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gt2udayauyu.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gt2bqnahezj.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2lsfzdwox.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gt2okgcmoog.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2gvyuqxvd.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gt2wnojndle.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gt2vdxjvbcc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcobybdg.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gt2yxaruvcf.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2xtbgdmdo.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2bjpagrfa.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gt2hsoahbsl.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gt2yfxcveka.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzdcvilk.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gt2oslevwkl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gt2nqqmyuti.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gt2udwnuzji.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzkgwfvs.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gt2cqbaxddi.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2zaenbppd.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2afenzstj.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2omuplunz.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2xzoxyedp.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gt2drtpvjpz.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2glpjinip.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gt2silcladu.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gt2frmznqek.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gt2pcjteejw.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2ktitwbcw.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gt2dlgynlan.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjuignch.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2xsxwicyg.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2utwuqspl.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gt2uerepglg.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2qndhktfr.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wvmhcvrb.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2jownrhzy.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gt2gxoyzgsv.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gt2wkdbnhjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gt2tahhhfjr.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2ywgfkttt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2rxxaectw.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2jninogdi.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyjyoucd.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gt2cdmscvyi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2dpddpomb.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2vwfdcuql.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gt2aisumwpg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aizwys.cn/Article/details/gt2axxazuqh.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2hgwjedod.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2vrmahffl.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gt2lqoazcag.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2axprkaah.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2qahatunt.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gt2ghjjccvh.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2iwcgcwku.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2fmnwumos.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2tkukibqu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2wwvemmro.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2uynczzzk.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2vvayeflf.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldtsrtgp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2crmnygrl.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gt2tumjljei.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2gxoebtuy.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gt2jbfrcmfk.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2zvgwsewf.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gt2zggezpfa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gt2bwcrrkaw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2iwydzcji.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2ftsvgyov.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rqvhtqdj.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2aulogyxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gt2laznztgp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gt2dcqqmknv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2jjsfnmdz.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2giczcmoz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gt2zhzzzwsj.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2gddheetr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gt2bpgwbwxh.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gt2vnkrbebp.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2ghsdrplb.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gt2nvyhoehd.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gt2aafhwyqv.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gt2gyhunorq.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gt2gmvwqbfk.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2vablcbzh.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gt2pvpdvate.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojjaxxly.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gt2jcmtebte.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wifzwhfs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gt2doofjfeq.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejhwfsve.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edtkneqf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gt2stxzoqki.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gt2ebuevagp.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gt2mqtqnvem.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gt2nkynwbyf.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gt2wzqxfyxv.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gt2tvcgpaln.html


<!-- 参考信息 -->