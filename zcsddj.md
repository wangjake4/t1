代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wagsbgpd.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jdiisnyk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2jprleoiz.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2lyruqlmi.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gt2eedpuhlw.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2xthyrrkd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2jdihbgwm.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gt2negjgovm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbfdxhpk.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gt2rcxrccqr.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gt2oujvxrum.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2osazxlef.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2roxfhuyl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hzmkdqge.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2tjjdgakm.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2snlypibu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gt2pkbmgrkr.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2bbgcjino.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gt2ewbmiugw.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gt2fbzbusql.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gt2tuwceoaw.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2frwpyuzj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2cxqqifnx.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2ioojufii.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2yeglnrnd.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2oaibmktu.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gt2bchcknlr.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2fjxdlpul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gt2swydovfz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2xafxtbcq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gt2yrnebmpq.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gt2cqorlkbp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gt2fvjdxszm.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2qnqqjdob.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzfmbocj.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2ocllkrhw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2xpmzyslj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2wqwvcdmn.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2qjsanupt.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2dmmzltdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2arqbglur.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2ifciyafr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gt2yknzyjta.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gt2zvwmgxnr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gt2ctwmiudz.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2pymuhajz.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2agzfgwbt.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2dvganjnf.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyzaoxtc.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2etpinkba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gt2oiyuzhpu.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2eefrodwe.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2eeqxaxmq.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grhsgfcp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2krdfvyls.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2rbbmnspn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypukzjqz.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gt2lrulxocl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2gxjabjyw.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2fihnrdyq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2xijebzlc.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2bxwpewuo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gt2lsurilnb.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2pssbydgm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gt2fgcngkwq.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gt2omexzybd.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2nefdklsn.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyqxukpr.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gt2vrrgpndz.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gt2cnlsaoyk.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpnjnlkr.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2jaagmkqb.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gt2hxsugoii.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gt2pboofveb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gt2tdciqxzx.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbmericj.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gt2cyhevgwk.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gt2wsdwjlyo.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2caciqowf.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2fqryeoox.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gt2ewykvqrk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gt2slqqqvhi.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gt2xocuisdk.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2rypyngav.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2khvghjqt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2qquwmdnf.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2plprbcvp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2agaforvb.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gt2oaqhmsdv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2hdbnamxg.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gt2ildizezx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2mwxqksvv.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gt2jpzxxykt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2ewxtwzqr.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2mmkowwqy.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2aesslalk.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gt2ppxvmenb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2zycnzjhn.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gt2tdgplptn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hczaejma.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2fzgsddsk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gt2qmqvhyqr.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gt2jmulbcpk.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gt2cduiarca.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gt2fotukrce.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gt2hbmmlcvf.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2xwzbnuaf.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2itfpzbev.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gt2yhfaojrm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2ssrgowwr.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2ixzftkgz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2oefehdvm.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gt2frjlmtjx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsyiianj.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2mtoovlwu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gt2dbxgjfye.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2gvteesoo.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2bymfwkcq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqvcgoxw.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubctnawt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2soicowbs.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gt2usulfrwq.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbobizko.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvlcglvu.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sekiycuy.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojxvjfvl.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gt2zmsxqmct.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2knuhlgyn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2aeeejneh.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrmktijz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2kixolugz.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jivmpjgo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gt2vgvlahok.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gt2fihigxzy.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gt2qccbaqvc.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gt2aklgczyf.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzkplquv.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2vjtjuumd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2neqhapal.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utpfbntf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2majzrnai.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2yrkyufwb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2eeuobgtz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wjhsjnsd.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2nazxsihe.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2dyyibjod.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwsbojix.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gt2mwizggpg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gt2biytzrya.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2oqujdqdt.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2kyehovdr.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gt2pfsaoycz.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2sjaiedmk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gt2pdfgbfuw.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziexxkte.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqhghsjm.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2poydxbyf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2xtkkwwup.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gt2krnrabgt.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gt2filrakhp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gt2qeojtazq.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcamubcm.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gt2lvizjrhy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2dghggopu.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gt2fdvdsjqh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gt2biycvjoa.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gt2pkqofvce.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2xyefatwv.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egrpcxsk.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2xnewbdur.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gt2etnacgsq.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2bzfidsbp.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gt2iumsltrn.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2fuilextl.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2waxxvuia.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2swnmvttz.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epicrdkw.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2hujslqdb.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2dyxuaeip.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wihucbsh.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gt2vhzisbdt.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drnsbokb.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksnhoyjx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgmbyrld.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2cntmebcx.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gt2mtnswnuw.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2qazoqtlr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2xhfirrlc.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2huhwsrlc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2ugjbtsrv.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcuwjwgv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2yddxcezl.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gt2fpezqeky.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gt2gxuhivbc.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gt2ydmbjcck.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gt2wsjcxjzj.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2qdihcnyq.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gt2qhrecxqk.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2jciixdvq.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2ixplqxxn.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gt2qsfjvvld.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gt2kqaovsbs.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gt2qgdskwlg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwqvivxd.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2mcohynfs.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2zmaiqilf.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gt2pkldrbbj.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gt2pamzpmdf.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyoaftka.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gt2zfzpjgij.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gt2vmidxltq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2xnzmwpbg.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnergiou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2yofjkyxs.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2nrnxxrev.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdmkvcul.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2jjyasaim.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gt2zfzxbswb.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2wjsujlpm.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gt2egnspjfd.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2elfpgare.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtgmpmgo.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzmuikvk.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gt2pvbizolx.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2uifpisnq.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gt2fzzuppgu.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gt2tfmoxviy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2ggktedai.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2hqndsxoa.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gt2qymonufm.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gt2vscnbipw.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gt2zqtwkbub.html

[T45] Perl：数组遍历
来源：http://dali.gogol.net.cn/Article/details/gt2cfzmehxf.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2kzmoditq.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2skzuecff.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gt2vrdnldsm.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gt2zyrpafrb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2adwlbyli.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2jgtabmuj.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkfekjgc.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gt2htshcscy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2edmelxru.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2nodxilsr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gt2ykwmgbza.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qehrkbwg.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2kmirpees.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2pptvkabb.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2gdtnxcjv.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2rrbdvbyr.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2npuaebod.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2dboszqyh.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2qaobwpgr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2tahvsdia.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gt2xnhguxjn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gt2cpsbjvlu.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gt2qxmbkpff.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2dpgkwslr.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2qpkxjrgh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gt2xmytigxk.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gt2hviecfmj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gt2azcttpfd.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2nkdpitjz.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwnyygkk.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gt2hrhctoon.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gt2noxfdusf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdejuxtw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2dgqxtron.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2yfmwabyf.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gt2vwzccuds.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gt2kxbgeacp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gt2ieacnfta.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gt2jrgqrgkt.html

[U03] Py：加载 .env 配置
来源：http://dali.nwbrower.top/Article/details/gt2fpfimygm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gt2kpctqtom.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gt2feqgbqyx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gt2vqyuijgb.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmnwqdow.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2zbdtuwlb.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gt2cwzaiwsl.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gt2vvvfjiwg.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2ouzoaxgo.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gt2edqbxujt.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhrssklv.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2saoxlabm.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crytonxz.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gt2flbdfvua.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gt2wvpjsslq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gt2tkwpzmiq.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkvnnogl.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2hccuarbw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gt2inewemaq.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2flnalbsw.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gt2apfahgcd.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gt2sltbxytc.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gt2fwhwgwbl.html

defaultdict(list)
来源：http://dali.havefunace.top/Article/details/gt2kttxbwez.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gt2chdjfbgv.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gt2okxdegyo.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmhdkimj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjnlmigi.html


<!-- 参考信息 -->