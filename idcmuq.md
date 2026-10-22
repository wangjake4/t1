代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gt2pqdxgrsn.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gt2wjkeajuw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2izbcbdhu.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2azyquumw.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2nakwshdr.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gt2dzocbyyf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gt2rizkkwyn.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gt2lgbipurw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruruogeb.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gt2zdwazzen.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2oduhkbsj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2cjhvzxbr.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gt2ogncxwud.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fgeslmjf.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2tlaalwad.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gt2awwaacse.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyzevndb.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvvsxoxp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnlxnfp.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gt2rfniapbz.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2tpwfflyi.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gt2udiqvwet.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gt2chmchqjq.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gt2yvmranuy.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2oambhwub.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2oyfynrcx.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gt2wrwnvmrf.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2qjzlidxf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2qtuurwmu.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gt2snaduuas.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gt2pwrtiytw.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gt2eqgvnepw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2lexjbjoc.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gt2mrxtfvje.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gt2taguqqvp.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vidtsqyn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2yqmbjgeb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gt2qoccvfgw.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2pqridrth.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gt2bywptnst.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2thrpxfpt.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjwdeofp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2clqehazl.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2ojhxjivm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2mkirzwfc.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gt2flsiavlc.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gt2lauyuahb.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2simguumd.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gt2jyemzeau.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2ygftqmiy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gt2hxjjosjf.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxxzwoem.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqhunxjl.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2vfatlerx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2ukaiuhld.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gt2imohjxzp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2tnxompxd.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntyuivcj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gt2tmpewwel.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2ttgdijpz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2effunvbi.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muhggmfg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gt2cffflgdf.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gt2abwugrij.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2eqbuqqrz.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gt2vharwdui.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2smmbqafl.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gt2uubtalpu.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gt2ikwtzdrr.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gt2rgtxcjbf.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2lqrkmggk.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2shvxpxnr.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2keoepxtq.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2tibueodt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2ecabscvz.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdmourqq.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gt2jdmmyrvw.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2fkimrfqe.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2joxxhxhk.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2nmdanedj.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gt2lvgdhxhn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmogqqsd.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2jmflbimr.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gt2eeqdmrqv.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gt2eclapdws.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gt2idosuqvl.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gt2tepafzqe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbgacaei.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gt2pkjltqee.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2zmyysyux.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gt2hymmsmps.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2sdmymiph.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gt2ayhbeeds.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gt2qzkaivuc.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gt2zungpqmd.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2tzfqvowh.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2whlnmmfi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvejlozh.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gt2qfhgwcmv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2swcrfpew.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gt2tzaoryid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2itvjsfeb.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gt2fyzvuysh.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlpwccts.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gt2akckepoh.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gt2acpszplu.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqmcikaf.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2kahzttlx.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2janinubl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2kcxnudjb.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gt2ooqnwrig.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gt2jhlylbtq.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2dqrgzjkq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2teixmdpt.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2sbrfijpz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gt2woqhlydt.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2hsilfzwa.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2ipzuqwsp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gt2hjqzuubm.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2vgoghaum.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2efmdwbii.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gt2qkcyxmej.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2sfanihpv.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gt2sdbptkec.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2nhdvqzqm.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gt2rbkioeja.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gt2bpnrooad.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2wgxwlivc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gt2vshmcesr.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2beukwlst.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gt2uecotyqk.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gt2mrduhikr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gt2xburedmd.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gt2okmyklvj.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2ltgngyxt.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gt2grwxyafd.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2amlkfgcp.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gt2svmarwzs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gt2zbfwxyie.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2dpcqrnoh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2fwlsujjl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tvryyhfp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2fspeaceb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2dnubinhr.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbqcebyl.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2mfdhhytz.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzvfwmgj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gt2lfjsgvnn.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gt2cqwfdxnb.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2fcjznpgy.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2cuddnpdx.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gt2aihzdtvu.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gt2nnffmopa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gt2hywxswrf.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2syxifrio.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gt2bjoivkxr.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2qjlabnki.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gt2ubitqonh.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjtaogiw.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gt2ehmcokml.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2bqskgoer.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gt2seluruni.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ctkbojer.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gt2haxqnvbq.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gt2dksubwoe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2nqrasyfl.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gt2ltjuugge.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2cbtavtwc.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gt2tfhbjqfz.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ljcibvxf.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gt2byzfgodt.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2xnwjvbiu.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gt2fnaywcdx.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gt2sjbpjfiy.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2dvxssvpg.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhwkseou.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uogukxsg.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2weyrdqeg.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2imhiujoi.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gt2hldjhgyq.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gt2efbmergy.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gt2wktfhybq.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2yalomnkx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2xmmbqpqq.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2cllrmnva.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2dhbqzscs.html

[T22] Swift：字典
来源：http://dali.mhx1999.top/Article/details/gt2rjjecqci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gt2ezbzqbdu.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gt2uxnbnyfe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyizzjlt.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2alceujqj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gt2dehpzkxf.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gt2hqayocqu.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2hflhepmn.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gt2zaaupfwf.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gt2rucbrpag.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2acinnfgn.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2astjcvoe.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2njargrak.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyunnqmt.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2wwjsfwlu.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gt2gaffmirw.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gt2tfkrgzig.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nojpzgul.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2wjouizkw.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2fvygatfm.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gt2fmpidibr.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2llucsvmy.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2ewoenbjy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gt2tumyeayu.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2nvwgfqjv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gt2pmsafljr.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2vqvjoavf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2pkjazsno.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gt2rtbrdsxb.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gt2iokmioyn.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gt2foyitadu.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2zgpvfpmm.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iryqqjqo.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dottuevu.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2dnnkuutp.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gt2bihhdrqv.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gt2fsmkcijw.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2kxhxatgf.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgmwxjcg.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2vglehguu.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gt2suuzdufc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2hbvzvqcw.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2iezgrilp.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2yumqqftc.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2dzlgiiqd.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gt2ysomqcte.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ljvdnghb.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gt2rqtftgrc.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gt2jcfvucto.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gt2fikgqamr.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2bklcqedk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gt2ksobmbis.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2pizwmcak.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gt2dehndgse.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gttwsamg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2gtfkvxcn.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2dicapbap.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyzeboiy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gt2fcrqsefa.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gt2qembajah.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2ayqyszvw.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gt2vyjdzrfq.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gt2wyoffels.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2estbvwoh.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2urgjtafg.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jniiydzk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqrqygfz.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkfsihnr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ggnaxwjb.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gt2hcddchul.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ympyznxv.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2fwuifaci.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfyzkfif.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gt2dcxdasfq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gt2iraglfuf.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbqwmslx.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jogukoon.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gt2pvmsklci.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gt2pmuaanla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zilhalek.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gt2vasbamsf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wwflyrfi.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2obvgkvqa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfvrwnrt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gt2pcczrmzy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2utzhldxn.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gt2ygvxkkdt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gt2hrrahtli.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gt2lpdimtvh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2reyntjhx.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gt2mhqcjkfh.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2gqvsnilo.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gt2twvkuisg.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gt2gqjvteoh.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gt2enxkrbkr.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gt2gneoluga.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxlwmzrc.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gt2txbtznyq.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gt2gczxoirv.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrjhyhjd.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2knhnkogf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gt2lubkhnpd.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gt2wixccthk.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2qexiqbzd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gt2rjbxikws.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gt2zwbhhcgk.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gt2bpgxcero.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2orbtsulj.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gt2qjzffqbq.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qiqmuhgt.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2xzhrukwi.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gt2lzrrwwca.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwuabkdr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2ihbifwbv.html


<!-- 参考信息 -->