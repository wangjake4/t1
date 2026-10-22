代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtnfknuine.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtwxytogdc.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtudqdoswr.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtytyzuero.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gttjgugonh.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtfipdlyqe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtrpcioznh.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtzzopxbdw.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtetgxfkyd.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtwegcupqz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtnasxhrxq.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtgkeqfvsn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtmcuomitq.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gtikabekmm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtqzzoltys.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtpzzluazl.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtjuigpjdj.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gtnqfbwfoa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtkispkpih.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtizwazsgt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtyefrlgzi.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtmhpwjaim.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gttidkffes.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttawmzzca.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtvbvdnrfa.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgjghksml.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtqrrerflp.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtkpaandgd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtobvjksoh.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtraioexqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtcierigjs.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtkgefesls.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueuthmqv.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtrnwrxbzz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtuwlkrqlw.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtitpgkkdd.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvhgwhxdt.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghfkqukx.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtyyqzakcd.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxbkydty.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtiojhksfq.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gttangzjlb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtfpofcxrw.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtwylxtscd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtjykxptmg.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtlxugexfc.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtzbdlhqfz.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtdrbhekfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtdaazroxd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gteknlptke.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtdbjscrwe.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gtzwzektgj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtajnjlbyn.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtcfajwxft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtwurahzym.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtlebeyajn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtlvyxvzft.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtaqbvgvbr.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtclziagpt.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtonmealkx.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtmshkayqu.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtxwtihgqg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gtxfjcaaml.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtgirunrnb.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtnvjbmtle.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtiqyzcnwz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtbdwuysxq.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtufvdgelr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtoqkmphza.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtojuwqgui.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtmayxhywh.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtvzbddtwv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtzktxafpg.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtwusulkcr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpeehqlr.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtfxqgsyed.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gthowmbhov.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtequytuax.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtncxmqppu.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtdmvgefol.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtahtrxzgt.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmqooiqs.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtmtyknnuk.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtthgajmzp.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtjhjtthds.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtficjytik.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtbiqivaow.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtvxhorawg.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtcnmkdrhz.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gttjexifiy.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtxxuvttvp.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtohsrwhfo.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtbvbhahxq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthiypyrax.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtabksfskx.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtvbfkkeni.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtxwnskvop.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtqkulvkyl.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtzgkchhdc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtvokibfly.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtyavrxjxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtqhxpoxyg.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtvczhlnxg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtxqdwjuqk.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtahjrxhyo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtmwblxmer.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtirmxnprm.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtlvovtdlz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gttnnnvopr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtcfjqgohr.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtoqpjpsfd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtgoamovpw.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtcghsyzye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtjjzmafxt.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtjgnaevwi.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtjkbejulg.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtydjtsrzy.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gthyyzvvdh.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtqbthvtdo.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtofhdxiqr.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtxqrxjdbq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtxbslmgrr.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtnuikiaee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtzigdampy.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtjniwwoou.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtucuilrqm.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtktjujfhs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gtibzuovep.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtcanfadkr.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtjkikmulh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gteupswrjw.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtnplmjpmx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gttzncfric.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtrjjbgsno.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gthpbabtot.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtmvjjlkzk.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtbllcjwag.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtantxdnod.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtzhjghrnr.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtokiwwbqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtibvbnquq.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gttmwpseoo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtoxwuumzt.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gtrsbjdxkm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlbnillc.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtkahmukbm.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtjikzerrc.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtjjfrejtu.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtxipksjjo.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdnweurd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtvmjqzesz.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtlrwqjwgq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtvijytcln.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnhmvaysf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtdrsemfdd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlllulphq.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtrwnbfifa.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtlexxvehu.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtmuzaxckc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtgoagyhda.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtvgoazawt.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbspszibu.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtiptszhmq.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtkglppzyo.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtejltxgpe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gtcuyzdodn.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtopenpncs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gthxacctpi.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gthargfnvf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtzwxilvvw.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtevwebfkj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtvtjngtcy.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtmqqqxlkk.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtwqfxhcng.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gttmmmgzkx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtkivxlwcs.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtnpdbatce.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gttiktvjbk.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtzlunpigc.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtuceovoma.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyjalyum.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtegcwncen.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gttyhuwbqx.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtqctoyfkd.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtvjrooogr.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtmvllosho.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtzxzgbceo.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtcjlytibm.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtuoadrtoh.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gthhvhlpjn.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtdxrqfwrr.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtwtzniesv.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtirhzvjwu.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtrsnbgfmv.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtswilcprb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtfnuiqeuz.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gtmzeywsiq.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gthiopmxcg.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtkmoxtkqf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gtehqwcuaa.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gtjrtgiivn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtmodbzwil.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtrtoeszms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtlizmbjhs.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gtpvsvsxte.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtdssxyana.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtbhndvjwm.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtoxklmrgb.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtuhnazabm.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzfyabqf.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtnixniniy.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtcjjlwclf.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtcfotwsbr.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtswbuaysa.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gtpydvbgbg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtqwfcnicl.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtmahxzdku.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gttmzqcswt.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtsjgjkieh.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtsqgsylei.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtnilbuesr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtepnphdsf.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gtgygfhpxo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gtuijaaowe.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtrjcpsoqx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtvmdvfgkz.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gtlolcztnh.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtppxnmmvo.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtvfbffseu.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtitkpfzys.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtfudlwwyk.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtjscglpck.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtkupbqxmg.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gthafeaeqv.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklfgbtuv.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gtsxolmljc.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtdrjkzhxd.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtvynylbuq.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gtwvypabsj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtcmpddhry.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gtdungqbuz.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gtzyirwlvf.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtujdbqxpq.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gtmctigxgp.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtgzbkdizn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtommrlsjr.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtszmlfbcn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gthxmgdmhx.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtomdsglsg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtchyapxai.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtjqtwzgyr.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gttuphdhgb.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtwzkmkegf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtlidvwzxf.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtuqwzvskd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtpzwhcqhx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuuhgzjrl.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtwwvuvaqg.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtqxefzpmu.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtfgokxcld.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtfwhwlknt.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtfswugvcr.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtecfmthgk.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtcnzcmswy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gtnfxkrgft.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtisgiokyu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtnkkxtdpl.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtkurnwfxz.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtonbqrmoi.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtajonigcc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtsxuaskqu.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtfttselno.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtjsgqksvo.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gtmghpnnqm.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtjfbqacch.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtfwvcosnd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtqrrgggix.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbefnagjn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtftzpysoy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwjvhcvep.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gtyvswwpcd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gteubazekg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gttxhjjkui.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtmwxtfoec.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gtyrropxkw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gtnjdixckz.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtfshsxnln.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gtzklviyiz.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gteoxwgebz.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtfowpjekv.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gtdcbkprca.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gtbcdcldng.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtpyjmakmj.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlbxnitq.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gttiwxcyoz.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtsajpayis.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtaoziinad.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gtifppzgcr.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtnqzzcyje.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gttkseimfn.html


<!-- 参考信息 -->