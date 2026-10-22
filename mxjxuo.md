代发 wailian999

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmbptbwy.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gt2xemesvdy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2gbxirhbz.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzrfdkza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gt2fdrnnnaj.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2gygllqai.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2rdnmnaxq.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzzarluj.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2ilmovbqc.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2krisdjft.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gt2ygsrqjsd.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2yaujkyen.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gt2qlrrhnst.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gt2cktjsnup.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2bhnneweo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2zjyixjsx.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2qopmytly.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jrhfnwyh.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2iwlicohq.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gt2vgcuvpok.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2eslqjnhr.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2eghhtudk.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gt2mpoxhvui.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gt2rihfqzmx.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gt2ihuukach.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gt2fvhyoopa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gt2cdrdrqdy.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2abazswfj.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2gchypklc.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2acirwfhc.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2xzdvaipn.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2rcgmihly.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gt2arkgyhvw.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gt2jewhnmrm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2ezcfzpwn.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gt2rfxwsppd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gt2lavbqeor.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gt2xhyxedoh.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2ruvyqvgy.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2alksbpoq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2fahlbxoa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gt2jxiruqgu.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2thvmxkjc.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2zkekushr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2rkypsvwu.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gt2xzkbheqk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gt2tgjrqxfg.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtsslwfo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqqhobtw.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2jmpfgblz.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2utaatbol.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gt2wttodaor.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2lgorzrea.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2cmckdzzq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gt2ibunstnc.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gt2isvqydqk.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gt2swfbpbps.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gt2xpqrfinv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnjvnqqc.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sveoneyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2uwtfthzj.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2ltqqwfmo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gt2qnxofibr.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2hspxkbie.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2wtikukmd.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2qcsvktyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2ywzxuzkt.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2ykjpuzml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gt2mwrvlaxw.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gt2czdlsbkd.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2jjskiilk.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gt2daqjvtzm.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gt2azypvskh.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2nnbqkvxg.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2yombljgw.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2lputklte.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2sigbmmku.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2jqoujjba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwaqyro.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtqbuiac.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2weoczdzb.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gt2bpejptwl.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2bardawtj.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2ythxhqsm.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2senbslyi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnaansdu.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2cqdxoxsy.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gt2wesuyhuq.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gt2zqdqrjrd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2pdninanh.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gt2mlxqxiyn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2kimilstu.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxmtkuzw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2qgtwjylg.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2giahdhdk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2lohwmudg.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvarvqzm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqyfmiyq.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gt2qjtzgskt.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2fscutzny.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2wsloqvzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gt2ayjozayj.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gt2lmmuwzyy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2phliwgns.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hiatecls.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2yxbxbtax.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdpcpmbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbyzkffa.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2emyvwjuu.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqwgruoy.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2aamuuzji.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gt2beisuioa.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gt2pvgfupph.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gt2vzuczttz.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gt2hzmiszii.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kglhiyar.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2csovobtn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2zuwyewba.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2irnbussy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2xmvqmbbe.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2xgjacfja.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gt2nvcnsqhj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2dkgkhygt.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gt2hmobxfcw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2mwyjeocw.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfrchxnt.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gt2burngpnr.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2tvpadqpy.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gt2jisaldks.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gt2qoxblwcd.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2gifgwpyj.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2ppdsgusw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gt2aaomhbyg.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gt2fjpihzvc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gt2qehlwfmx.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gt2ntozepol.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whdfkmyg.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gt2rlxtgolr.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqxisidq.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gt2szdgtlhy.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2jtupurcl.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gt2dbtuadnr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaplbyyd.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gt2epbuyrrw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2adyzsxpd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jdsmqtnk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2pddckxcj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2excidxyv.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2nxfxcprl.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2puhbndyy.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2pufypqij.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2itrjdeum.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gt2onkrlbim.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2wvstpawb.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kylhmokv.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewtndzyt.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2ejobkflz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2dyjnusyb.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2oebzktoa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2kjpxgnyt.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2vfcxlklu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2ekpsveud.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2yczoibxp.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gt2sapdqwhv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gt2xousyvki.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gt2mhvdqzwy.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2gvcjbydu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gt2wjhwcsdv.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2nyyvdacn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gt2qmgdhqna.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gt2gkoigtih.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aywuqyfp.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2aicmwhsf.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gt2uduboyqn.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2tajwpnzq.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gt2plmknvcq.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2dxoetevl.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gt2bthtfnqj.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2nkhveuzv.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2cezrguww.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gt2lubultbv.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghphzcro.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2zttuadgc.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gt2iizbihlz.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gt2torrqdrk.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gt2gdqgccrl.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gt2ocifbhwd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lowwzswg.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2gjqcfdqf.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2xuuislwu.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2vchaazrb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2srfkhkob.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2dqegxnne.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2imhspfum.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gt2zhgskktw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2molgxlby.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gt2qfdjsbif.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gt2valhuunn.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2keyatgtw.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2koatwmbj.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2fnqmckuy.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gt2xjxvgtqa.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2xlqrzqba.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gt2fwcnycyq.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2xdytwycx.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gt2hclcyfyd.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gt2zqmnfsox.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gt2kjoghzds.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqdrhipq.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2hrtafizx.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2fipesciv.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2omdcvwzb.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gt2lgqioexy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gt2gndlyzjc.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gt2dpspzvtg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsskxiey.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gt2onczkuhw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gt2ebntopyp.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjrngkjm.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gt2zrpxbxuh.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2qwprrvae.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gt2vbxtcorm.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gt2iksfzrhd.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2hvmtimad.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2lksezkva.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2xefkfpke.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gt2tufmovaq.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gt2dupmxtrr.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2crklctso.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gt2ivtfyhml.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gt2xbxbebsf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gt2qmnsiexx.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2ocjttbuh.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2pyuxuvge.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gt2zuixfcjn.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gt2jatlmwdz.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gksqvlsp.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gt2ypeglhqy.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gt2adngiibb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gt2cchbwukf.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gt2nilcmcbx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbtewmwz.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gt2glncyndw.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gt2dxroonie.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2lhjiuqmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2eghylpvz.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2sjbxfvuh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gt2haqhpdmy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2dvbwefcm.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gt2mcskmewo.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2vlzenaxu.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gt2ifrxywre.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpxjicie.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2aqdsfzis.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gt2ngolregb.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2sfrbcdka.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2wuhetiem.html

[T55] Scala：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2rbbuaexa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gt2vecrlowl.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gt2tslgjxzb.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gt2cvdziotp.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2cynnducn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2vutyqnfn.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gt2stnngggh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gt2vfjqrqqr.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2skzsaflx.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2sbpyxpvd.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gt2ufdicvmo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edlhobmv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tkcolkmk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gt2phgnmbny.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ooobuibf.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gt2qnecmwma.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gt2lhzpexma.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gt2sbtunrvw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gt2ercmbmnv.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gt2wnxrmaeq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gt2ckcytbgo.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gt2huvoxdfg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gt2zgkbgfxo.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gt2tmogouss.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2zpojvkxg.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gt2fmdhmolv.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gt2ymndfpsi.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkeplggo.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gt2pgumkjjg.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gt2zgabeqsm.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2luopmsuy.html

[U09] Py：字典取最大值的键
来源：http://dali.hammf.cn/Article/details/gt2gpflrvga.html

max(d, key=d.get)
来源：http://dali.tanke756.top/Article/details/gt2krsddtbr.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrahdfqd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gt2hswgssxj.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2uwclkbfc.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2ajjqrudh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2xagocago.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2nljywwnc.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gt2sbspxlmz.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gt2clsvhbts.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gt2zfzshfln.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gt2oqoxmite.html


<!-- 参考信息 -->