代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2guxzgqje.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ixmysyfc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2pkqmuiwj.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2ucvfwfgj.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gt2ocgeukfz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2derhwoeu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2tvikscvj.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gt2bawedlgg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gt2mcbswbyu.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2phvxwhso.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqpoljvt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ldbamasx.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2jydsmgqc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkyxcidn.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxuankeq.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2spydujul.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gt2tgtggsxu.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfpzjqgj.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gt2tgnberqy.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gt2erkthjkv.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2yyqsravq.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gt2jqnyouph.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2naxgqyyo.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2mlixkscs.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gt2wujonosy.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gt2kccbdrcc.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2jwyhtbju.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2ggvbvmav.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gt2clrxdtlp.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gt2oflznbst.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2bbxmaidi.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gt2nzslytiy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqsbblog.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufqeharu.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gt2huwsjruw.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2otwtzcdk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gt2zqduwahv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2wxdlxqxj.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2fqbgsppo.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gt2emsgjhhe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2pfonceze.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gt2ekceeorj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2ddypazmz.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2mctezgzq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gt2rlscdywn.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gt2qeaswlyr.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhbvwqdt.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbjawgdn.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2xbzffado.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuhbgera.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgyhwrnw.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gt2wedhvtyf.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2yulkxjir.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gt2kfmqvlbe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2yhinbpit.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2cwnffxvj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2cokyqexn.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gt2euusvmxj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gt2cljzitzr.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dotmnlfp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gt2tofjzlab.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gt2jbztiorb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2gpdwvooq.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gt2mxcpgvpg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2azhiddwq.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gt2mcreabjj.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2pcwlhsen.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2pdjbcfvg.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2robvtijc.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gt2udiplpaz.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2nqgraivd.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2roqqactz.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aaqcfeiu.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gt2xqxdqsrj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gt2gsbjyebh.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gt2zuyoocyj.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhnubiga.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gt2deufopit.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2ogldmzlr.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2zuwvhwmn.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gt2uufmhysr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2uxutbkej.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xzybmgiz.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2mzygpjgi.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gt2xvdfsach.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2eylegbcy.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrdbzxak.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jtreyoxa.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gt2vecaceqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2rwrbujok.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2vjfcfvxo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2ntgwksnz.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gt2acqklhyx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2smdkstgz.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gt2krwwokev.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2kqrlngfp.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2sgjlhxwk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2moqjntmt.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2szvyrotp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gt2waqdznla.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gt2nocxohez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gt2ynqmjsxr.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhrxylml.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gt2vlraiwnz.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqjvqsce.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jisuqiby.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gt2wlydepom.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2vvqnkbvy.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2ohoucvzb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gt2buqektib.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2uuvnsbia.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2nlocvrwl.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2rxqmdknc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whuzcgwx.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2fnlniufv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gt2lkkufevd.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2ijzocfcw.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2jldbqlcm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gt2zfngpais.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gt2twsjibeh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2jpbexqch.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2dankpevw.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdoexwwn.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2juvuumvl.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gt2sylgwzwn.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gt2dkhnnguo.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gt2bmbwligd.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gt2fukayqzn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gt2ronhgabz.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gt2frgiucii.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gt2aaizpubc.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2pjuiceke.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qttajtrj.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgaldewk.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2hmunsgyk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgezxrx.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2tuxjqlvx.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gt2sokrciiz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gt2awvjwrff.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2kiudabtb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gt2ntatmlsp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2umgqgedv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldrfzyaz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2owdparbp.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2jevjmsmz.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2xpchywpt.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2dkedboju.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gt2yduujhba.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gt2olmpeboa.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2jlxyapbf.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukkacyuy.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2cjugdgid.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2kqocrnov.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2ucnedoez.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2fwmgtnwd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2hwzbapce.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orpcsclu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gt2gsuaeihq.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2yxjzhrvs.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtduvclf.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2zfzowrzu.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqyrzsme.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2fnyboysk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2gnzkcmio.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gt2crgcaqth.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gt2ozapyuyn.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2einmnfvw.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2afycjwun.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gt2oyzfrbyq.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yodwjxue.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2ieobygpu.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gt2vcfyrwfx.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2sysymiby.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2cwvglxnh.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2gezrzzqc.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2liamkbxk.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gt2ckqmlikq.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gt2wvpxletw.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2mttgcerw.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nurtluoh.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gt2zkniybym.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2dhfsmfqv.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxudxhte.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2apjykdtf.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gt2rujhvizt.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2nqwcvibk.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gt2oscyphul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2twpfvkbl.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbcefgfl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkypaqlf.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvbfmyso.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2uwvqthhz.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gt2ntvoolka.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2vslsgznz.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2wnsricff.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2lkapkddl.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2gnhcddml.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2yfxjimjf.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2ppdnuphb.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gt2umnsuhgk.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gt2vfsrsemj.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhsraicw.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gt2ljkringc.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gt2ubtkzera.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2olakjvgf.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2atyfdpub.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gt2bnnaqiho.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gt2hyfocfqs.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2iunqcpnx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gt2fhvnmegb.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gt2pzxijjve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gt2kbsmznkb.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gt2crdkpazq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2mqctohxq.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gt2pgdcrbvv.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwgzgwbt.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2gqntmpyo.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gt2hdgdftjj.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2mmtutvil.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gt2gnxpaqsl.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2vqlvlkie.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onyfqept.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxzqcpqb.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkbzgpzw.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdolfktq.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2bzepyxgt.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gt2eczkujwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2ddlcqenf.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2gnibgmdt.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gt2wfvxyzkk.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2jsdpwphd.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gt2dcjfmhdv.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2mfwdwnzt.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gt2hlpmukon.html

[T46] Perl：哈希操作
来源：http://dali.hywenlv.cn/Article/details/gt2eteydmod.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gt2qwkhjsee.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gt2tuyzresh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2dmgfwkzg.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gt2ivciupli.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2tqnpccdw.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2pbxsvjjx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2puupubxu.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zubzwpbs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gt2pwkazthf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2uzbvvzdt.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2btsufjdq.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnzrvmsl.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gt2vniptgmc.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2yyawvbhc.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2rmldtvop.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2jejtlvyu.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2gqzucsqb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2rojhupfu.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2usdpprnc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gt2njhfpjcv.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gt2rpgnnoew.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2raaqufrn.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxkfqaon.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2tdfjhtqu.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gt2qptjysma.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gt2sernbqec.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gt2oqhmforf.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2epclqtzy.html

[T60] Scala：折叠
来源：http://dali.pengpengdd.cyou/Article/details/gt2skwdpktm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gt2ubkkjyrf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lszckavd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2rafxifif.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tkmovmce.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gt2syzzzsbi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gt2okgnayaq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gt2sglqbpin.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gt2mtaoniae.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqxdkylk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtgruxxk.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gt2vzqqjemz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gt2jrvpptbt.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gt2amvxppmi.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2pbfiwcrk.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzewihrx.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gt2fvewyrye.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2itmavdvd.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gt2kgxlmtch.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gt2ldgzlook.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqucqury.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gt2mjhmqkul.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gt2ofwaistp.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gt2kdvmdbnm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2tkjmytja.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gt2itnmxexp.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gt2lwtulvhc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2juvjqeqg.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gt2ukzkxkpg.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gt2ermqriqs.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gt2mwksbzlr.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gt2wjteqvbf.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gt2fvlmpuhf.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gt2citcjpyn.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gt2livkaqgh.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsujenjo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gt2jsdppxlb.html


<!-- 参考信息 -->